# Note-ReactNative
- Video tutorial : https://www.youtube.com/watch?v=kNHuLOXR5T0&list=PLWBrqglnjNl31S91FFE63DtuRc9v9LSGl
- React-native for beginner
  npm install --> init lib for project


              //====== create project ======//
1.(in project directory) mkdir android/app/src/main/assets

2.npm install

3.react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res

4.react-native run-android
