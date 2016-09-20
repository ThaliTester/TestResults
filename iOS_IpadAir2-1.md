#### Test 8552588743283b2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588743283b2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/9D509D0F-CD34-4C4E-ABD1-54A2439819CB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9D509D0F-CD34-4C4E-ABD1-54A2439819CB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588743283b2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588743283b2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8543B2B3-026D-4787-BAD0-23738378208B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51546"
,(lldb)     command script import "/tmp/9D509D0F-CD34-4C4E-ABD1-54A2439819CB/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 08:21:21.978 ThaliTest[2732:5141734] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/892B13E8-EE67-4BA2-A8E9-5BC3059971D2/Library/Cookies/Cookies.binarycookies
,2016-09-20 08:21:22.398 ThaliTest[2732:5141734] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-20 08:21:22.399 ThaliTest[2732:5141734] Multi-tasking -> Device: YES, App: YES
,2016-09-20 08:21:22.418 ThaliTest[2732:5141734] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 08:21:24.361 ThaliTest[2732:5141734] Using UIWebView
,2016-09-20 08:21:24.368 ThaliTest[2732:5141734] [CDVTimer][handleopenurl] 0.418007ms
,2016-09-20 08:21:24.375 ThaliTest[2732:5141734] [CDVTimer][intentandnavigationfilter] 6.700039ms
,2016-09-20 08:21:24.376 ThaliTest[2732:5141734] [CDVTimer][gesturehandler] 0.326037ms
,2016-09-20 08:21:24.376 ThaliTest[2732:5141734] [CDVTimer][TotalPluginStartup] 9.159982ms
,2016-09-20 08:21:31.490 ThaliTest[2732:5141734] Resetting plugins due to page load.
,2016-09-20 08:21:35.508 ThaliTest[2732:5141734] Finished load of: file:///var/mobile/Containers/Bundle/Application/8543B2B3-026D-4787-BAD0-23738378208B/ThaliTest.app/www/index.html
,2016-09-20 08:21:35.722 ThaliTest[2732:5141734] JXcore Cordova plugin initializing
,2016-09-20 08:21:35.723 ThaliTest[2732:5142010] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 08:21:41.944 ThaliTest[2732:5142010] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 08:21:41.945 ThaliTest[2732:5142010] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-20 08:21:41.945 ThaliTest[2732:5142010] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-20 08:21:41.947 ThaliTest[2732:5142010] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 08:21:42.239 ThaliTest[2732:5142010] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.0050240159034729
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
