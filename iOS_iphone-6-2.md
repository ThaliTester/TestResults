#### Test 100892963a470a85_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/100892963a470a85/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9C730C87-D692-4367-8E94-0A3AD4301F4C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/9C730C87-D692-4367-8E94-0A3AD4301F4C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/100892963a470a85/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/100892963a470a85/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C969545D-F882-4D6B-B2C9-0AF16F2D6B7F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59212"
,(lldb)     command script import "/tmp/9C730C87-D692-4367-8E94-0A3AD4301F4C/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-10 16:53:28.009 ThaliTest[219:51710] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/35901545-EB81-4A92-8E4F-028DA5A40D67/Library/Cookies/Cookies.binarycookies
,2017-01-10 16:53:28.102 ThaliTest[219:51710] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-10 16:53:28.104 ThaliTest[219:51710] Multi-tasking -> Device: YES, App: YES
,2017-01-10 16:53:28.121 ThaliTest[219:51710] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-10 16:53:28.913 ThaliTest[219:51710] Using UIWebView
2017-01-10 16:53:28.920 ThaliTest[219:51710] [CDVTimer][handleopenurl] 0.340998ms
,2017-01-10 16:53:28.930 ThaliTest[219:51710] [CDVTimer][intentandnavigationfilter] 9.166956ms
2017-01-10 16:53:28.931 ThaliTest[219:51710] [CDVTimer][gesturehandler] 0.313997ms
2017-01-10 16:53:28.931 ThaliTest[219:51710] [CDVTimer][TotalPluginStartup] 11.378050ms
,2017-01-10 16:53:35.762 ThaliTest[219:51710] Resetting plugins due to page load.
,2017-01-10 16:53:36.241 ThaliTest[219:51710] Finished load of: file:///var/containers/Bundle/Application/C969545D-F882-4D6B-B2C9-0AF16F2D6B7F/ThaliTest.app/www/index.html
,2017-01-10 16:53:36.570 ThaliTest[219:51710] JXcore Cordova plugin initializing
,2017-01-10 16:53:36.571 ThaliTest[219:51938] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-10 15:53:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-10 15:53:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-10 15:53:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
2017-01-10 15:53:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-10 15:53:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-10 15:54:11 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.42780101299286
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
