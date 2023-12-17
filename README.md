# The issue
@nx/vite serve target does not pull the mode option from the specified buildTarget after Nx v17.2.x.

# Expected behavior
@nx/vite serve target pulls the mode option from the specified buildTarget.

# Steps to reproduce the issue:
1. Run `nx serve:my-app:sandbox`.
2. Verify that `{ command: 'serve', mode: 'development' }` is console logged instead of `{ command: 'serve', mode: 'sandbox' }`.
