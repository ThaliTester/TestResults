#### Test 85046911906f2db_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911906f2db/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/62C14F24-FC72-4267-97A4-B15E55090DE1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/62C14F24-FC72-4267-97A4-B15E55090DE1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911906f2db/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911906f2db/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/11F15083-8997-4F15-8C35-C76D3B81EDDA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51261"
,(lldb)     command script import "/tmp/62C14F24-FC72-4267-97A4-B15E55090DE1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 08:58:46.863 ThaliTest[2948:5408797] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/250DFE35-F6E3-42E8-B198-F314B49AEC37/Library/Cookies/Cookies.binarycookies
,2016-09-22 08:58:47.284 ThaliTest[2948:5408797] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 08:58:47.285 ThaliTest[2948:5408797] Multi-tasking -> Device: YES, App: YES
,2016-09-22 08:58:47.302 ThaliTest[2948:5408797] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 08:58:49.159 ThaliTest[2948:5408797] Using UIWebView
,2016-09-22 08:58:49.166 ThaliTest[2948:5408797] [CDVTimer][handleopenurl] 0.423014ms
,2016-09-22 08:58:49.173 ThaliTest[2948:5408797] [CDVTimer][intentandnavigationfilter] 6.573021ms
,2016-09-22 08:58:49.174 ThaliTest[2948:5408797] [CDVTimer][gesturehandler] 0.324965ms
,2016-09-22 08:58:49.174 ThaliTest[2948:5408797] [CDVTimer][TotalPluginStartup] 8.960962ms
,2016-09-22 08:58:56.318 ThaliTest[2948:5408797] Resetting plugins due to page load.
,2016-09-22 08:59:00.195 ThaliTest[2948:5408797] Finished load of: file:///var/mobile/Containers/Bundle/Application/11F15083-8997-4F15-8C35-C76D3B81EDDA/ThaliTest.app/www/index.html
,2016-09-22 08:59:00.336 ThaliTest[2948:5408797] JXcore Cordova plugin initializing
2016-09-22 08:59:00.337 ThaliTest[2948:5409088] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-22 08:59:06.473 ThaliTest[2948:5409088] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-22 08:59:06.474 ThaliTest[2948:5409088] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-22 08:59:06.474 ThaliTest[2948:5409088] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-22 08:59:06.476 ThaliTest[2948:5409088] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-22 08:59:06.766 ThaliTest[2948:5409088] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.005041956901550293
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
