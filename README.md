# 9013matrix.com

This repo holds the 9013matrix.com web site code.  You can find it under the `src` folder.

## Deployment

Changes pushed to the `main` brach will be deployed automatically and immediately.  You should probably test them locally first!

It does this using a hook to push those changes to the `build` branch, which is then pushed to our hosting provider.  It uses the intermediate `build` step in case we ever need more a more complicated build step that
generates other files.

You should avoid pushing to the `build` branch manually.

For details, see [the publish workflow](./.github/workflows/publish.yml).



