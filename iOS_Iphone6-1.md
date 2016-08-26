#### Test 797638309aa2d44_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638309aa2d44/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B56C6BB4-6883-4C93-B872-AFC9692BAF42/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B56C6BB4-6883-4C93-B872-AFC9692BAF42/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638309aa2d44/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638309aa2d44/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BE8634E6-F128-4D43-BB19-F332BECC4EA5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65276"
,(lldb)     command script import "/tmp/B56C6BB4-6883-4C93-B872-AFC9692BAF42/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 16:53:19.033 ThaliTest[552:593239] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4D4A1826-71D5-4DC9-9953-678536C18393/Library/Cookies/Cookies.binarycookies
,2016-08-26 16:53:19.454 ThaliTest[552:593239] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 16:53:19.456 ThaliTest[552:593239] Multi-tasking -> Device: YES, App: YES
,2016-08-26 16:53:19.481 ThaliTest[552:593239] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 16:53:21.209 ThaliTest[552:593239] Using UIWebView
,2016-08-26 16:53:21.216 ThaliTest[552:593239] [CDVTimer][handleopenurl] 0.382006ms
,2016-08-26 16:53:21.224 ThaliTest[552:593239] [CDVTimer][intentandnavigationfilter] 7.277966ms
2016-08-26 16:53:21.225 ThaliTest[552:593239] [CDVTimer][gesturehandler] 0.324965ms
2016-08-26 16:53:21.225 ThaliTest[552:593239] [CDVTimer][TotalPluginStartup,] 9.603024ms
,2016-08-26 16:53:27.201 ThaliTest[552:593239] Resetting plugins due to page load.
,2016-08-26 16:53:29.965 ThaliTest[552:593239] Finished load of: file:///var/mobile/Containers/Bundle/Application/BE8634E6-F128-4D43-BB19-F332BECC4EA5/ThaliTest.app/www/index.html
,2016-08-26 16:53:30.194 ThaliTest[552:593239] JXcore Cordova plugin initializing
,2016-08-26 16:53:30.195 ThaliTest[552:593490] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 16:53:37.092 ThaliTest[552:593490] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-26 16:53:37.092 ThaliTest[552:593490] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 16:53:37.092 ThaliTest[552:593490] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 16:53:37.094 ThaliTest[552:593490] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 16:53:37.420 ThaliTest[552:593490] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  3
,Number of passed tests:  2
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  0.01113897562026978
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
