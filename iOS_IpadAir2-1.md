#### Test 8552588750d17b9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588750d17b9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8C87E2B2-7B9C-42E1-8645-574625792EDA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8C87E2B2-7B9C-42E1-8645-574625792EDA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588750d17b9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588750d17b9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5B148ED9-5E04-41F0-8F65-EC36F1F4D686/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60201"
,(lldb)     command script import "/tmp/8C87E2B2-7B9C-42E1-8645-574625792EDA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 10:59:25.071 ThaliTest[2545:4661332] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2B709FD8-5C01-480D-85CC-C46AE720E9B5/Library/Cookies/Cookies.binarycookies
,2016-09-16 10:59:25.492 ThaliTest[2545:4661332] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 10:59:25.493 ThaliTest[2545:4661332] Multi-tasking -> Device: YES, App: YES
,2016-09-16 10:59:25.512 ThaliTest[2545:4661332] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 10:59:27.550 ThaliTest[2545:4661332] Using UIWebView
,2016-09-16 10:59:27.560 ThaliTest[2545:4661332] [CDVTimer][handleopenurl] 0.373006ms
,2016-09-16 10:59:27.567 ThaliTest[2545:4661332] [CDVTimer][intentandnavigationfilter] 6.576002ms
,2016-09-16 10:59:27.567 ThaliTest[2545:4661332] [CDVTimer][gesturehandler] 0.301003ms
,2016-09-16 10:59:27.568 ThaliTest[2545:4661332] [CDVTimer][TotalPluginStartup] 8.750975ms
,2016-09-16 10:59:34.589 ThaliTest[2545:4661332] Resetting plugins due to page load.
,2016-09-16 10:59:38.726 ThaliTest[2545:4661332] Finished load of: file:///var/mobile/Containers/Bundle/Application/5B148ED9-5E04-41F0-8F65-EC36F1F4D686/ThaliTest.app/www/index.html
,2016-09-16 10:59:38.934 ThaliTest[2545:4661332] JXcore Cordova plugin initializing
2016-09-16 10:59:38.934 ThaliTest[2545:4661585] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 10:59:45.133 ThaliTest[2545:4661585] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-16 10:59:45.133 ThaliTest[2545:4661585] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 10:59:45.134 ThaliTest[2545:4661585] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-16 10:59:45.135 ThaliTest[2545:4661585] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 10:59:45.431 ThaliTest[2545:4661585] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.005005002021789551
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
