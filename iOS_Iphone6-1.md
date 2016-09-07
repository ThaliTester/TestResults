#### Test 83627337a1c904e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337a1c904e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/34379A0A-840C-40D4-B37B-7FE433ECC8F2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/34379A0A-840C-40D4-B37B-7FE433ECC8F2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337a1c904e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337a1c904e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C1DD087F-DF68-418F-8AD8-805C33092C91/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61439"
,(lldb)     command script import "/tmp/34379A0A-840C-40D4-B37B-7FE433ECC8F2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 09:33:20.280 ThaliTest[1343:2275810] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/70CB04F0-1EEA-4430-B84F-D0E64054D62B/Library/Cookies/Cookies.binarycookies
,2016-09-07 09:33:20.813 ThaliTest[1343:2275810] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 09:33:20.815 ThaliTest[1343:2275810] Multi-tasking -> Device: YES, App: YES
,2016-09-07 09:33:20.837 ThaliTest[1343:2275810] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 09:33:23.148 ThaliTest[1343:2275810] Using UIWebView
,2016-09-07 09:33:23.155 ThaliTest[1343:2275810] [CDVTimer][handleopenurl] 0.613987ms
,2016-09-07 09:33:23.163 ThaliTest[1343:2275810] [CDVTimer][intentandnavigationfilter] 7.357001ms
2016-09-07 09:33:23.164 ThaliTest[1343:2275810] [CDVTimer][gesturehandler] 0.452995ms
2016-09-07 09:33:23.165 ThaliTest[1343:2275810] [CDVTimer][TotalPluginS,tartup] 10.205030ms
,2016-09-07 09:33:30.537 ThaliTest[1343:2275810] Resetting plugins due to page load.
,2016-09-07 09:33:34.539 ThaliTest[1343:2275810] Finished load of: file:///var/mobile/Containers/Bundle/Application/C1DD087F-DF68-418F-8AD8-805C33092C91/ThaliTest.app/www/index.html
,2016-09-07 09:33:34.756 ThaliTest[1343:2275810] JXcore Cordova plugin initializing
,2016-09-07 09:33:34.757 ThaliTest[1343:2276073] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 09:33:41.733 ThaliTest[1343:2276073] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-07 09:33:41.733 ThaliTest[1343:2276073] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-07 09:33:41.734 ThaliTest[1343:2,276073] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-07 09:33:41.736 ThaliTest[1343:2276073] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
