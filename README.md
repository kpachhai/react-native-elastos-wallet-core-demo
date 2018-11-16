# react-native-elastos-mainchain-demo

This is a demo app using the react-native-elastos-wallet-core npm package.

## How to use for ios

```
$ git clone https://github.com/cyber-republic/react-native-elastos-wallet-core-demo
$ cd react-native-elastos-wallet-core-demo
$ npm i
$ cd node_modules/react-native-elastos-wallet-core/Elastos.ORG.Wallet.Lib.C/build/ios/src
$ install_name_tool -id  "$(pwd)/libElastos.Wallet.Utility.dylib" libElastos.Wallet.Utility.dylib
$ react-native start
$ react-native run-ios
```

## How to use for android

```
$ git clone https://github.com/cyber-republic/react-native-elastos-wallet-core-demo
$ cd react-native-elastos-wallet-core-demo
$ npm i
```

Open android folder using Android Studio and add `node_modules/react-native-elastos-wallet-core/android/libs/lib.aar` to the project using following link
http://docs.onemobilesdk.aol.com/android-ad-sdk/adding-aar-files.html

To run the app
```
$ react-native run-android
```

<img src="https://ademcan.net/images/ElaWalletGenerateMnemonic.png" width="400">
