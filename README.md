# Steps to reproduce the issue:
1. Run `nx serve:my-app:sandbox`.
2. Verify that `{ command: 'serve', mode: 'development' }` is console logged instead of `{ command: 'serve', mode: 'sandbox' }`.
