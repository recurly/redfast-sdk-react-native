# Recurly Engage React Native TV Example App

The `@recurly/engage-react-native` and `@recurly/engage-core` packages are published on the public npm registry, so no auth token or `.npmrc` registry override is required to install them. Update the `appId` / `userId` values in `App.tsx` with your own Pulse app credentials before starting the app below.

## Install Recurly Engage React Native SDK packages

```bash
npm install --legacy-peer-deps # OR yarn install
npm run prebuild # OR yarn prebuild
```

## Run the example app

```bash
nvm use 18.18 # minimum node version

# for Android or FireTV run
npm run android # or yarn android

# for AppleTV run
npm run ios # or yarn ios
```
