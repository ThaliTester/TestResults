#### Test 82894682da71698_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/78080153-CB6F-4B72-BD3F-D640CD421A31/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/78080153-CB6F-4B72-BD3F-D640CD421A31/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/355B891A-6113-4FE6-9761-C2AA90D051FB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53412"
,(lldb)     command script import "/tmp/78080153-CB6F-4B72-BD3F-D640CD421A31/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 00:04:10.517 ThaliTest[434:530439] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/410D4F3B-B6C7-4032-A00D-BC0808E7BF1C/Library/Cookies/Cookies.binarycookies
,2016-09-13 00:04:10.558 ThaliTest[434:530439] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 00:04:10.560 ThaliTest[434:530439] Multi-tasking -> Device: YES, App: YES
,2016-09-13 00:04:10.572 ThaliTest[434:530439] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 00:04:10.858 ThaliTest[434:530439] Using UIWebView
,2016-09-13 00:04:10.862 ThaliTest[434:530439] [CDVTimer][handleopenurl] 0.132024ms
,2016-09-13 00:04:10.864 ThaliTest[434:530439] [CDVTimer][intentandnavigationfilter] 2.634048ms
2016-09-13 00:04:10.865 ThaliTest[434:530439] [CDVTimer][gesturehandler] 0.120044ms
2016-09-13 00:04:10.865 ThaliTest[434:530439] [CDVTimer][TotalPluginStartup,] 3.546000ms
,2016-09-13 00:04:16.427 ThaliTest[434:530439] Resetting plugins due to page load.
,2016-09-13 00:04:16.802 ThaliTest[434:530439] Finished load of: file:///var/containers/Bundle/Application/355B891A-6113-4FE6-9761-C2AA90D051FB/ThaliTest.app/www/index.html
,2016-09-13 00:04:17.181 ThaliTest[434:530439] JXcore Cordova plugin initializing
,2016-09-13 00:04:17.182 ThaliTest[434:530612] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,2016-09-13 00:05:03.353 ThaliTest[434:530439] BTM: attaching to BTServer
,2016-09-13 00:05:04.536 ThaliTest[434:530439] BTM: local device power state changed
2016-09-13 00:05:04.537 ThaliTest[434:530439] BTM: power is now off
,2016-09-13 00:05:05.297 ThaliTest[434:530439] BTM: local device power state changed
2016-09-13 00:05:05.297 ThaliTest[434:530439] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  16
Number of passed tests:  16
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  40.71161198616028
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
