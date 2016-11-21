#### Test 94626375b5fe2b0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/FA0E42F8-0392-47C3-BAB3-9B61F126FA7F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/FA0E42F8-0392-47C3-BAB3-9B61F126FA7F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/26BEA2B7-C1C7-497F-A425-411119C9A3D8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61073"
,(lldb)     command script import "/tmp/FA0E42F8-0392-47C3-BAB3-9B61F126FA7F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 17:38:10.119 ThaliTest[349:358087] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5B9DC569-B1FD-4983-8A2B-A64810C393D7/Library/Cookies/Cookies.binarycookies
,2016-11-21 17:38:10.500 ThaliTest[349:358087] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 17:38:10.501 ThaliTest[349:358087] Multi-tasking -> Device: YES, App: YES
,2016-11-21 17:38:10.523 ThaliTest[349:358087] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 17:38:12.467 ThaliTest[349:358087] Using UIWebView
,2016-11-21 17:38:12.474 ThaliTest[349:358087] [CDVTimer][handleopenurl] 0.470996ms
,2016-11-21 17:38:12.482 ThaliTest[349:358087] [CDVTimer][intentandnavigationfilter] 6.635010ms
,2016-11-21 17:38:12.483 ThaliTest[349:358087] [CDVTimer][gesturehandler] 0.325978ms
,2016-11-21 17:38:12.483 ThaliTest[349:358087] [CDVTimer][TotalPluginStartup] 9.217978ms
,2016-11-21 17:38:19.165 ThaliTest[349:358087] Resetting plugins due to page load.
,2016-11-21 17:38:22.309 ThaliTest[349:358087] Finished load of: file:///var/mobile/Containers/Bundle/Application/26BEA2B7-C1C7-497F-A425-411119C9A3D8/ThaliTest.app/www/index.html
,2016-11-21 17:38:22.541 ThaliTest[349:358087] JXcore Cordova plugin initializing
,2016-11-21 17:38:22.542 ThaliTest[349:358314] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 16:38:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 16:38:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 16:38:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-21 16:38:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-21 16:38:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 16:38:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-11-21 16:38:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-21 16:38:58 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.25111699104309
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
