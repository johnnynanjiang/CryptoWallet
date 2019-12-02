# Cordova TrustWalletCore Extension

This example project demonstrates how to use the TrustWalletCore cordova plugin
Test


## Install

1.

```
git clone https://github.com/johnnynanjiang/CryptoWallet.git
git clone https://github.com/johnnynanjiang/TrustWalletCoreCordovaPluginSwift.git
```

You should now have `./CryptoWallet`, `./TrustWalletCoreCordovaPluginSwift`.

Repos:
* https://github.com/johnnynanjiang/CryptoWallet.git
* https://github.com/johnnynanjiang/TrustWalletCoreCordovaPluginSwift.git

2.
```
cd ./CryptoWallet
cordova platform add ios
cordova plugin add /full/path/to/TrustWalletCoreCordovaPluginSwift
cordova build ios
```

## Running

Open `platforms/ios/CryptoWallet.xcworkspace` in xcode and run either on the device or emulator.

### Implemented functions

1. Create Wallet

     Enter wallet name and password to create a new wallet. The alert message will return the wallet id. The wallet id is also      printed in the Xcode console. Copy wallet id, you will need it for mnemonic export.

2. Export Mnemonic

     Enter wallet id and password. The alert message will return the mnemonic.



## Notes
* remember to run `cordova build ios` everytime you make a change to the javascript
* remove and add plugin if you make changes to OBJ-C code and remember to build cordova again (as per above)
* debug using xcode debugger to step through code OBJ-C code
* debug using safari remote debugger to step through Javascript code or see errors

## References

* https://cordova.apache.org/docs/en/latest/guide/hybrid/plugins/
* https://cordova.apache.org/docs/en/latest/guide/platforms/ios/plugin.html
* https://github.com/apache/cordova-plugin-camera
* https://github.com/akofman/cordova-plugin-add-swift-support
