# Repro for issue 7263

## Versions

firebase: v13.10.2<br>
node: v20.12.2<br>
platform: macOS Sonoma 14.5

## Steps to reproduce

1. Run `firebase apphosting:backends:create --project PROJECT_ID --location us-central1`
   - Follow the setup process, but set a value for teh app's root directory
   - ? Specify your app's root directory relative to your repository /my-app
   - ? Do you want to deploy now? (Yes)
2. Error occurs

```
Error: build build-2024-06-04-001 failed to build
```
