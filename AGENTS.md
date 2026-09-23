# Repository workflow

- When the user asks to commit, merge, push, or ship changes, complete the workflow through `main`: commit the intended changes, integrate the latest `origin/main`, and merge and push the result to `origin/main`. Do not stop after pushing a feature branch.
- Follow an explicit request to keep work on a branch, open a draft, or stop before merging instead of this default.
- Use a pull request targeting `main` when practical, and respect required reviews and checks. Never force-push `main` or bypass branch protections.
- Run checks appropriate to the changes before merging. Preserve unrelated user changes and do not rename workspace branches.
- After pushing to `main`, verify the production deployment at `https://onlygrond.com/`. Check the changed pages or assets as well as the deployment status when available. Report any deployment failure or blocker; do not call the work deployed merely because GitHub accepted the push.
