Created using
`npx react-native@0.70.6 init ldtest --version 0.70.6`

Install dependencies using npm, than run
`npm run android`

Results in the error

```
* What went wrong:
Could not determine the dependencies of task ':app:processDebugResources'.
> Could not resolve all task dependencies for configuration ':app:debugRuntimeClasspath'.
   > Could not find any matches for com.facebook.react:react-android:+ as no versions of com.facebook.react:react-android are available.
     Searched in the following locations:
       - file:/Users/maartenvanbeek/Projects/ldtest/node_modules/react-native/android/com/facebook/react/react-android/maven-metadata.xml
       - file:/Users/maartenvanbeek/Projects/ldtest/node_modules/jsc-android/dist/com/facebook/react/react-android/maven-metadata.xml
       - https://dl.google.com/dl/android/maven2/com/facebook/react/react-android/maven-metadata.xml
       - https://www.jitpack.io/com/facebook/react/react-android/maven-metadata.xml
     Required by:
         project :app > project :launchdarkly-react-native-client-sdk
```
