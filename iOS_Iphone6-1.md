#### Test 829140730a15ac0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140730a15ac0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F461E0BE-F52C-47F0-868E-70C002744909/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F461E0BE-F52C-47F0-868E-70C002744909/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140730a15ac0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140730a15ac0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A21034A0-1D12-45CD-8372-BAA9D293DEE7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52586"
,(lldb)     command script import "/tmp/F461E0BE-F52C-47F0-868E-70C002744909/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 13:14:51.819 ThaliTest[1385:2304045] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/125F5E8A-C1D7-41E1-90EC-D3CFB85C7253/Library/Cookies/Cookies.binarycookies
,2016-09-07 13:14:52.354 ThaliTest[1385:2304045] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 13:14:52.356 ThaliTest[1385:2304045] Multi-tasking -> Device: YES, App: YES
,2016-09-07 13:14:52.378 ThaliTest[1385:2304045] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 13:14:54.475 ThaliTest[1385:2304045] Using UIWebView
,2016-09-07 13:14:54.482 ThaliTest[1385:2304045] [CDVTimer][handleopenurl] 0.585973ms
,2016-09-07 13:14:54.490 ThaliTest[1385:2304045] [CDVTimer][intentandnavigationfilter] 7.166982ms
2016-09-07 13:14:54.491 ThaliTest[1385:2304045] [CDVTimer][gesturehandler] 0.331044ms
2016-09-07 13:14:54.491 ThaliTest[1385:2304045] [CDVTimer][TotalPluginS,tartup] 9.683967ms
,2016-09-07 13:15:02.279 ThaliTest[1385:2304045] Resetting plugins due to page load.
,2016-09-07 13:15:06.180 ThaliTest[1385:2304045] Finished load of: file:///var/mobile/Containers/Bundle/Application/A21034A0-1D12-45CD-8372-BAA9D293DEE7/ThaliTest.app/www/index.html
,2016-09-07 13:15:06.408 ThaliTest[1385:2304045] JXcore Cordova plugin initializing
,2016-09-07 13:15:06.409 ThaliTest[1385:2304301] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  38
,Number of passed tests:  38
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  12.05330097675323
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
