#### Test 85046911c074ee1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/69AFADBD-20EA-4780-926A-6A03F52466ED/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/69AFADBD-20EA-4780-926A-6A03F52466ED/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c074ee1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9F50010B-171D-433F-9654-F621FAC7250E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56630"
,(lldb)     command script import "/tmp/69AFADBD-20EA-4780-926A-6A03F52466ED/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 13:39:37.315 ThaliTest[2852:5300678] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/950563B0-D22D-4D31-A130-34F8A94A2C73/Library/Cookies/Cookies.binarycookies
,2016-09-21 13:39:37.643 ThaliTest[2852:5300678] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 13:39:37.644 ThaliTest[2852:5300678] Multi-tasking -> Device: YES, App: YES
,2016-09-21 13:39:37.659 ThaliTest[2852:5300678] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 13:39:39.446 ThaliTest[2852:5300678] Using UIWebView
,2016-09-21 13:39:39.453 ThaliTest[2852:5300678] [CDVTimer][handleopenurl] 0.398993ms
,2016-09-21 13:39:39.460 ThaliTest[2852:5300678] [CDVTimer][intentandnavigationfilter] 6.716013ms
,2016-09-21 13:39:39.461 ThaliTest[2852:5300678] [CDVTimer][gesturehandler] 0.419021ms
2016-09-21 13:39:39.461 ThaliTest[2852:5300678] [CDVTimer][TotalPluginStartup] 9.200990ms
,2016-09-21 13:39:47.005 ThaliTest[2852:5300678] Resetting plugins due to page load.
,2016-09-21 13:39:51.149 ThaliTest[2852:5300678] Finished load of: file:///var/mobile/Containers/Bundle/Application/9F50010B-171D-433F-9654-F621FAC7250E/ThaliTest.app/www/index.html
,2016-09-21 13:39:51.359 ThaliTest[2852:5300678] JXcore Cordova plugin initializing
,2016-09-21 13:39:51.359 ThaliTest[2852:5300962] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 13:39:57.496 ThaliTest[2852:5300962] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 13:39:57.496 ThaliTest[2852:5300962] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-21 13:39:57.496 ThaliTest[2852:5300962] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 13:39:57.498 ThaliTest[2852:5300962] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 13:39:57.785 ThaliTest[2852:5300962] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.005043983459472656
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
