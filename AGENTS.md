When the user says "publish", you should trigger the publish workflow:

1. Increment the version number. For small changes, increment the patch version. For minor changes, increment the minor version. For major changes, increment the major version. Use your own discretion.
2. Stage and commit the changes
3. Push the changes to the remote repository

A GitHub Action will handle the rest.