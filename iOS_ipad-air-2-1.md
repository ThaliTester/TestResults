#### Test 953210620aa0610_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/600B2813-D2D5-4B9D-A026-38B018670484/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/600B2813-D2D5-4B9D-A026-38B018670484/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C0135DF3-D9E1-4997-A5AB-3DA63635F459/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54845"
,(lldb)     command script import "/tmp/600B2813-D2D5-4B9D-A026-38B018670484/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 16:47:15.183 ThaliTest[425:281552] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BFA58B12-EAD1-4253-9B86-67D3AE56EA17/Library/Cookies/Cookies.binarycookies
,2016-12-07 16:47:15.584 ThaliTest[425:281552] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 16:47:15.586 ThaliTest[425:281552] Multi-tasking -> Device: YES, App: YES
,2016-12-07 16:47:15.605 ThaliTest[425:281552] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 16:47:17.620 ThaliTest[425:281552] Using UIWebView
,2016-12-07 16:47:17.630 ThaliTest[425:281552] [CDVTimer][handleopenurl] 0.343978ms
,2016-12-07 16:47:17.637 ThaliTest[425:281552] [CDVTimer][intentandnavigationfilter] 6.366968ms
,2016-12-07 16:47:17.637 ThaliTest[425:281552] [CDVTimer][gesturehandler] 0.272036ms
,2016-12-07 16:47:17.638 ThaliTest[425:281552] [CDVTimer][TotalPluginStartup] 8.561015ms
,2016-12-07 16:47:24.213 ThaliTest[425:281552] Resetting plugins due to page load.
,2016-12-07 16:47:28.040 ThaliTest[425:281552] Finished load of: file:///var/mobile/Containers/Bundle/Application/C0135DF3-D9E1-4997-A5AB-3DA63635F459/ThaliTest.app/www/index.html
,2016-12-07 16:47:28.245 ThaliTest[425:281552] JXcore Cordova plugin initializing
,2016-12-07 16:47:28.246 ThaliTest[425:281799] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 15:47:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 15:47:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 15:47:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-07 15:47:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 15:47:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 15:48:03 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.97832101583481
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
