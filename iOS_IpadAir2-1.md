#### Test 8359140042466a2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8359140042466a2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/EF2C8A7B-F805-44D1-ADFF-B6BF358DCD49/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/EF2C8A7B-F805-44D1-ADFF-B6BF358DCD49/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8359140042466a2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8359140042466a2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/90155EFD-9C8E-4CBA-BB6C-6F8713BCDC91/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59311"
,(lldb)     command script import "/tmp/EF2C8A7B-F805-44D1-ADFF-B6BF358DCD49/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-01 10:58:02.654 ThaliTest[1521:2736735] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/63F31524-A731-4A85-BC1E-40AE54D9E170/Library/Cookies/Cookies.binarycookies
,2016-09-01 10:58:03.066 ThaliTest[1521:2736735] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-01 10:58:03.067 ThaliTest[1521:2736735] Multi-tasking -> Device: YES, App: YES
,2016-09-01 10:58:03.086 ThaliTest[1521:2736735] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-01 10:58:04.986 ThaliTest[1521:2736735] Using UIWebView
,2016-09-01 10:58:04.995 ThaliTest[1521:2736735] [CDVTimer][handleopenurl] 0.409007ms
,2016-09-01 10:58:05.003 ThaliTest[1521:2736735] [CDVTimer][intentandnavigationfilter] 6.592035ms
,2016-09-01 10:58:05.003 ThaliTest[1521:2736735] [CDVTimer][gesturehandler] 0.297010ms
,2016-09-01 10:58:05.004 ThaliTest[1521:2736735] [CDVTimer][TotalPluginStartup] 9.213030ms
,2016-09-01 10:58:11.365 ThaliTest[1521:2736735] Resetting plugins due to page load.
,2016-09-01 10:58:14.860 ThaliTest[1521:2736735] Finished load of: file:///var/mobile/Containers/Bundle/Application/90155EFD-9C8E-4CBA-BB6C-6F8713BCDC91/ThaliTest.app/www/index.html
,2016-09-01 10:58:15.056 ThaliTest[1521:2736735] JXcore Cordova plugin initializing
,2016-09-01 10:58:15.056 ThaliTest[1521:2737001] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-01 10:58:21.241 ThaliTest[1521:2737001] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-01 10:58:21.242 ThaliTest[1521:2737001] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-01 10:58:21.242 ThaliTest[1521:2737001] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-01 10:58:21.244 ThaliTest[1521:2737001] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-01 10:58:21.539 ThaliTest[1521:2737001] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005264997482299805
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
