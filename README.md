# expo-google-sign-in

> Source code for the deprecated `expo-google-sign-in` package.

`expo-google-sign-in` was a classic "Bare Workflow" module that couldn't be used in the Expo Go app due to native build-time requirements. The package also didn't support the web platform and often wasn't on the latest version of the upstream `GoogleSignIn` native package.

We recommend migrating to the community package [`@react-native-google-signin/google-signin`](https://github.com/react-native-google-signin/google-signin) which supports [EAS Build](https://docs.expo.dev/build/introduction/) and Expo Development Clients!

Alternatively, you can use the Expo package [`expo-auth-session/providers/google`](https://docs.expo.dev/guides/authentication/#google) which works on iOS, Android, and web. This package does not support the native sign-in modal on Android, instead using a secure web modal (recommended approach for most authentication providers).

- Documentation: [SDK 45 Google Sign-In](https://github.com/expo/expo/blob/sdk-45/docs/pages/versions/v45.0.0/sdk/google-sign-in.md).
