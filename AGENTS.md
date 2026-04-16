When the user says "publish", you should trigger the publish workflow:

1. Increment the version number using **CalVer** format: `YYYY.MMDD.ITERATION` (e.g. `2026.416.1`). The iteration starts at 1 for each new day and increments if multiple publishes happen on the same day.
2. Update CHANGELOG.md with the new version entry.
3. Stage and commit the changes.
4. Push the commit to the remote repository.
5. Create a git tag matching the version number (e.g. `v2026.416.1`) and push it: `git tag v{version} && git push origin v{version}`

The GitHub Action triggers on `v*` tags and handles the marketplace publish.