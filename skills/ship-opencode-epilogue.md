
### Step 8 — Trigger opencode review

Post the review comment on the PR so the opencode GitHub Action picks it up:

```bash
gh pr comment <PR number> --body "/oc please review this PR and approve if you find it ready to merge"
```

Update the report to also tell the user that the opencode review has been triggered.
