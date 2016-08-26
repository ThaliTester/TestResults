#### Test 797638308bd3e25_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638308bd3e25/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B25386EA-DDC8-402F-8FAB-A111C4BD77A4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B25386EA-DDC8-402F-8FAB-A111C4BD77A4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638308bd3e25/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638308bd3e25/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/80C71B94-7031-4D26-A208-ABA17B8F2ED3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63159"
,(lldb)     command script import "/tmp/B25386EA-DDC8-402F-8FAB-A111C4BD77A4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 12:43:51.214 ThaliTest[1044:1966886] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/642601BE-C058-429D-8966-F32DB71CB2F3/Library/Cookies/Cookies.binarycookies
,2016-08-26 12:43:51.643 ThaliTest[1044:1966886] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 12:43:51.644 ThaliTest[1044:1966886] Multi-tasking -> Device: YES, App: YES
,2016-08-26 12:43:51.663 ThaliTest[1044:1966886] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 12:43:53.630 ThaliTest[1044:1966886] Using UIWebView
,2016-08-26 12:43:53.638 ThaliTest[1044:1966886] [CDVTimer][handleopenurl] 0.449955ms
,2016-08-26 12:43:53.645 ThaliTest[1044:1966886] [CDVTimer][intentandnavigationfilter] 6.784022ms
,2016-08-26 12:43:53.646 ThaliTest[1044:1966886] [CDVTimer][gesturehandler] 0.312984ms
,2016-08-26 12:43:53.646 ThaliTest[1044:1966886] [CDVTimer][TotalPluginStartup] 9.201050ms
,2016-08-26 12:44:00.167 ThaliTest[1044:1966886] Resetting plugins due to page load.
,2016-08-26 12:44:03.928 ThaliTest[1044:1966886] Finished load of: file:///var/mobile/Containers/Bundle/Application/80C71B94-7031-4D26-A208-ABA17B8F2ED3/ThaliTest.app/www/index.html
,2016-08-26 12:44:04.149 ThaliTest[1044:1966886] JXcore Cordova plugin initializing
,2016-08-26 12:44:04.150 ThaliTest[1044:1967126] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 12:44:10.284 ThaliTest[1044:1967126] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-26 12:44:10.284 ThaliTest[1044:1967126] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 12:44:10.285 ThaliTest[1044:1967126] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 12:44:10.286 ThaliTest[1044:1967126] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 12:44:10.577 ThaliTest[1044:1967126] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01391804218292236
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
