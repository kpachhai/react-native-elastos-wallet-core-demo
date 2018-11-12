# react-native-elastos-mainchain-demo

This is a demo app using the react-native-elastos-wallet-core npm package.

## How to use

```
$ git clone https://github.com/cyber-republic/react-native-elastos-wallet-core-demo
$ cd react-native-elastos-wallet-core-demo
$ npm i
$ cd node_modules/react-native-elastos-wallet-core-demo/Elastos.ORG.Wallet.Lib.C/build/ios/src
$ install_name_tool -id  "$(pwd)/libElastos.Wallet.Utility.dylib" libElastos.Wallet.Utility.dylib
$ react-native start
$ react-native run-ios
```

<img src="https://ademcan.net/images/ElaWalletGenerateMnemonic.png" width="400">
