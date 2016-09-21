#### Test 85960304fe37dec_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304fe37dec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/20AC1E17-97BC-41CA-904C-D8D93EF4E15A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/20AC1E17-97BC-41CA-904C-D8D93EF4E15A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304fe37dec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304fe37dec/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/00689C39-C73E-42AB-A12E-B2D32D44A9EE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57886"
,(lldb)     command script import "/tmp/20AC1E17-97BC-41CA-904C-D8D93EF4E15A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 14:58:08.486 ThaliTest[2862:5308064] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/45573F75-8B1B-409B-80AC-DDED9A99E266/Library/Cookies/Cookies.binarycookies
,2016-09-21 14:58:08.828 ThaliTest[2862:5308064] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 14:58:08.829 ThaliTest[2862:5308064] Multi-tasking -> Device: YES, App: YES
,2016-09-21 14:58:08.846 ThaliTest[2862:5308064] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 14:58:11.013 ThaliTest[2862:5308064] Using UIWebView
,2016-09-21 14:58:11.021 ThaliTest[2862:5308064] [CDVTimer][handleopenurl] 0.406027ms
,2016-09-21 14:58:11.029 ThaliTest[2862:5308064] [CDVTimer][intentandnavigationfilter] 7.734954ms
,2016-09-21 14:58:11.030 ThaliTest[2862:5308064] [CDVTimer][gesturehandler] 0.361979ms
,2016-09-21 14:58:11.030 ThaliTest[2862:5308064] [CDVTimer][TotalPluginStartup] 10.129988ms
,2016-09-21 14:58:18.579 ThaliTest[2862:5308064] Resetting plugins due to page load.
,2016-09-21 14:58:22.529 ThaliTest[2862:5308064] Finished load of: file:///var/mobile/Containers/Bundle/Application/00689C39-C73E-42AB-A12E-B2D32D44A9EE/ThaliTest.app/www/index.html
,2016-09-21 14:58:22.728 ThaliTest[2862:5308064] JXcore Cordova plugin initializing
,2016-09-21 14:58:22.729 ThaliTest[2862:5308333] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 14:58:28.886 ThaliTest[2862:5308333] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-21 14:58:28.886 ThaliTest[2862:5308333] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 14:58:28.886 ThaliTest[2862:5308333] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 14:58:28.888 ThaliTest[2862:5308333] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 14:58:29.161 ThaliTest[2862:5308333] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.005113005638122559
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
