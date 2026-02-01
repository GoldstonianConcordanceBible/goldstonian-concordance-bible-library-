# Branch Protection (Required)

Apply these settings on GitHub to prevent manipulation of canonical content:

Protect branch: `main`
- Require pull request before merging
- Require at least 1 approval
- Require conversation resolution
- Require status checks (if enabled)
- Do NOT allow force pushes
- Do NOT allow deletions

Optional:
- Restrict who can push to matching branches (owners only)