#### Test 85046911d6c2afe_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3F9A5799-CF8C-4056-AA16-88C381F08A58/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3F9A5799-CF8C-4056-AA16-88C381F08A58/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D0DE59F0-C6F8-443D-BA12-FBEEC48874DE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49269"
,(lldb)     command script import "/tmp/3F9A5799-CF8C-4056-AA16-88C381F08A58/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 11:01:48.815 ThaliTest[999:1588198] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6B2947C4-11DB-40BF-8B7D-869F4F9FAAE7/Library/Cookies/Cookies.binarycookies
,2016-09-21 11:01:49.043 ThaliTest[999:1588198] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 11:01:49.045 ThaliTest[999:1588198] Multi-tasking -> Device: YES, App: YES
,2016-09-21 11:01:49.065 ThaliTest[999:1588198] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 11:01:49.530 ThaliTest[999:1588198] Using UIWebView
,2016-09-21 11:01:49.540 ThaliTest[999:1588198] [CDVTimer][handleopenurl] 0.535965ms
,2016-09-21 11:01:49.548 ThaliTest[999:1588198] [CDVTimer][intentandnavigationfilter] 7.146001ms
2016-09-21 11:01:49.548 ThaliTest[999:1588198] [CDVTimer][gesturehandler] 0.306010ms
2016-09-21 11:01:49.549 ThaliTest[999:1588198] [CDVTimer][TotalPluginStar,tup] 9.570003ms
,2016-09-21 11:01:54.974 ThaliTest[999:1588198] Resetting plugins due to page load.
,2016-09-21 11:01:55.280 ThaliTest[999:1588198] Finished load of: file:///var/containers/Bundle/Application/D0DE59F0-C6F8-443D-BA12-FBEEC48874DE/ThaliTest.app/www/index.html
,2016-09-21 11:01:55.628 ThaliTest[999:1588198] JXcore Cordova plugin initializing
2016-09-21 11:01:55.629 ThaliTest[999:1588377] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-09-21 11:02:02.540 ThaliTest[999:1588377] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 11:02:02.540 ThaliTest[999:1588377] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 11:02:02.540 ThaliTest[999:1588,377] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 11:02:02.542 ThaliTest[999:1588377] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 11:02:02.948 ThaliTest[999:1588377] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003256022930145264
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
