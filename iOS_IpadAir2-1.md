#### Test 85046911e91e24b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C6258A2B-AA25-45AD-B709-3B5BAFE99F1C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C6258A2B-AA25-45AD-B709-3B5BAFE99F1C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B45343B3-2908-45C3-98CC-940DE48A21E0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51916"
,(lldb)     command script import "/tmp/C6258A2B-AA25-45AD-B709-3B5BAFE99F1C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 17:16:35.459 ThaliTest[2311:4423171] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1AE66B25-DB7B-4521-A6A3-0B3F32FDA7F7/Library/Cookies/Cookies.binarycookies
,2016-09-14 17:16:35.847 ThaliTest[2311:4423171] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 17:16:35.848 ThaliTest[2311:4423171] Multi-tasking -> Device: YES, App: YES
,2016-09-14 17:16:35.867 ThaliTest[2311:4423171] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 17:16:37.753 ThaliTest[2311:4423171] Using UIWebView
,2016-09-14 17:16:37.763 ThaliTest[2311:4423171] [CDVTimer][handleopenurl] 0.386000ms
,2016-09-14 17:16:37.770 ThaliTest[2311:4423171] [CDVTimer][intentandnavigationfilter] 7.261992ms
,2016-09-14 17:16:37.771 ThaliTest[2311:4423171] [CDVTimer][gesturehandler] 0.322998ms
,2016-09-14 17:16:37.771 ThaliTest[2311:4423171] [CDVTimer][TotalPluginStartup] 9.512961ms
,2016-09-14 17:16:44.072 ThaliTest[2311:4423171] Resetting plugins due to page load.
,2016-09-14 17:16:47.407 ThaliTest[2311:4423171] Finished load of: file:///var/mobile/Containers/Bundle/Application/B45343B3-2908-45C3-98CC-940DE48A21E0/ThaliTest.app/www/index.html
,2016-09-14 17:16:47.599 ThaliTest[2311:4423171] JXcore Cordova plugin initializing
,2016-09-14 17:16:47.600 ThaliTest[2311:4423404] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 17:16:53.728 ThaliTest[2311:4423404] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-14 17:16:53.728 ThaliTest[2311:4423404] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-14 17:16:53.729 ThaliTest[2311:4423404] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 17:16:53.730 ThaliTest[2311:4423404] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-14 17:16:54.017 ThaliTest[2311:4423404] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005267024040222168
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
