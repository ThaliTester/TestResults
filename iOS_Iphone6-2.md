#### Test 83627337b783869_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FC8FEC7D-98BB-47BD-A802-3BEEF288E9EC/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/FC8FEC7D-98BB-47BD-A802-3BEEF288E9EC/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/265EC24E-B026-4372-BE74-A823506857A1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60996"
,(lldb)     command script import "/tmp/FC8FEC7D-98BB-47BD-A802-3BEEF288E9EC/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 05:43:39.861 ThaliTest[693:757090] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F9ADF097-E201-4FA0-A027-8A6DD94B714C/Library/Cookies/Cookies.binarycookies
,2016-09-14 05:43:40.180 ThaliTest[693:757090] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 05:43:40.182 ThaliTest[693:757090] Multi-tasking -> Device: YES, App: YES
,2016-09-14 05:43:40.208 ThaliTest[693:757090] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 05:43:40.679 ThaliTest[693:757090] Using UIWebView
,2016-09-14 05:43:40.686 ThaliTest[693:757090] [CDVTimer][handleopenurl] 0.370979ms
,2016-09-14 05:43:40.694 ThaliTest[693:757090] [CDVTimer][intentandnavigationfilter] 7.234991ms
2016-09-14 05:43:40.695 ThaliTest[693:757090] [CDVTimer][gesturehandler] 0.312984ms
2016-09-14 05:43:40.695 ThaliTest[693:757090] [CDVTimer][TotalPluginStartup,] 9.469032ms
,2016-09-14 05:43:47.322 ThaliTest[693:757090] Resetting plugins due to page load.
,2016-09-14 05:43:47.731 ThaliTest[693:757090] Finished load of: file:///var/containers/Bundle/Application/265EC24E-B026-4372-BE74-A823506857A1/ThaliTest.app/www/index.html
,2016-09-14 05:43:48.112 ThaliTest[693:757090] JXcore Cordova plugin initializing
,2016-09-14 05:43:48.113 ThaliTest[693:757277] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 05:43:54.716 ThaliTest[693:757277] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 05:43:54.717 ThaliTest[693:757277] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 05:43:54.717 ThaliTest[693:757277] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 05:43:54.719 ThaliTest[693:757277] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
