#### Test 79763830cfa9ed9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830cfa9ed9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/67EE1CF2-C4BE-4210-8075-DF5B5E420FDC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/67EE1CF2-C4BE-4210-8075-DF5B5E420FDC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830cfa9ed9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830cfa9ed9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/05B83B03-CD3D-4BEC-A9B7-E58C64E02947/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60379"
,(lldb)     command script import "/tmp/67EE1CF2-C4BE-4210-8075-DF5B5E420FDC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 15:41:18.156 ThaliTest[1071:1987643] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/00CAEAAC-2F88-4EAA-988A-2EDC01BBA026/Library/Cookies/Cookies.binarycookies
,2016-08-26 15:41:18.541 ThaliTest[1071:1987643] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 15:41:18.542 ThaliTest[1071:1987643] Multi-tasking -> Device: YES, App: YES
,2016-08-26 15:41:18.561 ThaliTest[1071:1987643] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 15:41:20.509 ThaliTest[1071:1987643] Using UIWebView
,2016-08-26 15:41:20.516 ThaliTest[1071:1987643] [CDVTimer][handleopenurl] 0.428021ms
,2016-08-26 15:41:20.523 ThaliTest[1071:1987643] [CDVTimer][intentandnavigationfilter] 6.633997ms
,2016-08-26 15:41:20.524 ThaliTest[1071:1987643] [CDVTimer][gesturehandler] 0.307024ms
,2016-08-26 15:41:20.524 ThaliTest[1071:1987643] [CDVTimer][TotalPluginStartup] 9.039998ms
,2016-08-26 15:41:27.010 ThaliTest[1071:1987643] Resetting plugins due to page load.
,2016-08-26 15:41:30.906 ThaliTest[1071:1987643] Finished load of: file:///var/mobile/Containers/Bundle/Application/05B83B03-CD3D-4BEC-A9B7-E58C64E02947/ThaliTest.app/www/index.html
,2016-08-26 15:41:31.131 ThaliTest[1071:1987643] JXcore Cordova plugin initializing
,2016-08-26 15:41:31.132 ThaliTest[1071:1987890] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 15:41:37.321 ThaliTest[1071:1987890] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-26 15:41:37.321 ThaliTest[1071:1987890] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-26 15:41:37.322 ThaliTest[1071:1987890] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 15:41:37.323 ThaliTest[1071:1987890] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 15:41:37.618 ThaliTest[1071:1987890] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  3
Number of passed tests:  2
,Number of failed tests:  1
Number of ignored tests:  0
,Total duration:  0.01416295766830444
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
