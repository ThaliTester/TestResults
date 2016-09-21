#### Test 85046911c074ee1_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/89A4955F-AB3E-44B4-9A16-A50FFF2810B3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/89A4955F-AB3E-44B4-9A16-A50FFF2810B3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D3A6E231-C0FC-4019-B097-73A444B5216B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56627"
,(lldb)     command script import "/tmp/89A4955F-AB3E-44B4-9A16-A50FFF2810B3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 13:39:31.237 ThaliTest[1033:1605841] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D4B65462-3A1B-42E4-AE1C-D723E5567281/Library/Cookies/Cookies.binarycookies
,2016-09-21 13:39:31.547 ThaliTest[1033:1605841] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 13:39:31.549 ThaliTest[1033:1605841] Multi-tasking -> Device: YES, App: YES
,2016-09-21 13:39:31.574 ThaliTest[1033:1605841] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 13:39:32.083 ThaliTest[1033:1605841] Using UIWebView
,2016-09-21 13:39:32.090 ThaliTest[1033:1605841] [CDVTimer][handleopenurl] 0.369966ms
,2016-09-21 13:39:32.098 ThaliTest[1033:1605841] [CDVTimer][intentandnavigationfilter] 7.214963ms
2016-09-21 13:39:32.098 ThaliTest[1033:1605841] [CDVTimer][gesturehandler] 0.342011ms
2016-09-21 13:39:32.099 ThaliTest[1033:1605841] [CDVTimer][TotalPluginS,tartup] 9.884000ms
,2016-09-21 13:39:37.689 ThaliTest[1033:1605841] Resetting plugins due to page load.
,2016-09-21 13:39:38.004 ThaliTest[1033:1605841] Finished load of: file:///var/containers/Bundle/Application/D3A6E231-C0FC-4019-B097-73A444B5216B/ThaliTest.app/www/index.html
,2016-09-21 13:39:38.332 ThaliTest[1033:1605841] JXcore Cordova plugin initializing
,2016-09-21 13:39:38.333 ThaliTest[1033:1606027] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 13:39:45.101 ThaliTest[1033:1606027] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 13:39:45.101 ThaliTest[1033:1606027] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 13:39:45.101 ThaliTest[1033:1606027] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 13:39:45.103 ThaliTest[1033:1606027] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 13:39:45.506 ThaliTest[1033:1606027] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.002170026302337646
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
