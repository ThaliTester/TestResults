#### Test 79763830eafb657_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830eafb657/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/19CC5216-40CD-4EAD-91D4-478B346CDE03/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/19CC5216-40CD-4EAD-91D4-478B346CDE03/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830eafb657/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830eafb657/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/19DAB880-5968-4D8A-BFAA-E83EA1998938/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58858"
,(lldb)     command script import "/tmp/19CC5216-40CD-4EAD-91D4-478B346CDE03/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 12:01:19.210 ThaliTest[1034:1961524] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4346BC64-D411-40FA-BE98-AD551F1D3AB2/Library/Cookies/Cookies.binarycookies
,2016-08-26 12:01:19.584 ThaliTest[1034:1961524] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 12:01:19.585 ThaliTest[1034:1961524] Multi-tasking -> Device: YES, App: YES
,2016-08-26 12:01:19.604 ThaliTest[1034:1961524] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 12:01:21.493 ThaliTest[1034:1961524] Using UIWebView
,2016-08-26 12:01:21.500 ThaliTest[1034:1961524] [CDVTimer][handleopenurl] 0.597000ms
,2016-08-26 12:01:21.507 ThaliTest[1034:1961524] [CDVTimer][intentandnavigationfilter] 6.605983ms
,2016-08-26 12:01:21.508 ThaliTest[1034:1961524] [CDVTimer][gesturehandler] 0.302970ms
,2016-08-26 12:01:21.508 ThaliTest[1034:1961524] [CDVTimer][TotalPluginStartup] 9.173036ms
,2016-08-26 12:01:28.112 ThaliTest[1034:1961524] Resetting plugins due to page load.
,2016-08-26 12:01:30.900 ThaliTest[1034:1961524] Finished load of: file:///var/mobile/Containers/Bundle/Application/19DAB880-5968-4D8A-BFAA-E83EA1998938/ThaliTest.app/www/index.html
,2016-08-26 12:01:31.130 ThaliTest[1034:1961524] JXcore Cordova plugin initializing
,2016-08-26 12:01:31.131 ThaliTest[1034:1961759] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 12:01:37.273 ThaliTest[1034:1961759] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-26 12:01:37.273 ThaliTest[1034:1961759] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-26 12:01:37.273 ThaliTest[1034:1961759] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 12:01:37.275 ThaliTest[1034:1961759] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 12:01:37.567 ThaliTest[1034:1961759] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01364099979400635
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
