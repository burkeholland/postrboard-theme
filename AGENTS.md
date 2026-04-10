When the user says "publish", you should trigger the publish workflow:

1. Increment the version number. For small changes, increment the patch version. For minor changes, increment the minor version. For major changes, increment the major version. Use your own discretion.
2. Update CHANGELOG.md with the new version entry.
3. Stage and commit the changes.
4. Push the commit to the remote repository.
5. Create a git tag matching the version number (e.g. `v0.1.6`) and push it: `git tag v{version} && git push origin v{version}`

The GitHub Action triggers on `v*` tags and handles the marketplace publish.