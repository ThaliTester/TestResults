#### Test 7976383051d2164_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7976383051d2164/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E8E2A1EF-AC0E-4903-AD40-03944F3305B0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E8E2A1EF-AC0E-4903-AD40-03944F3305B0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7976383051d2164/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7976383051d2164/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CE22A587-A152-4CF7-949D-79649B01AFCF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50523"
,(lldb)     command script import "/tmp/E8E2A1EF-AC0E-4903-AD40-03944F3305B0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-30 11:35:29.439 ThaliTest[1327:2481695] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3E3F17B4-F1E3-4FE7-9527-1D23AD9DA5FE/Library/Cookies/Cookies.binarycookies
,2016-08-30 11:35:29.869 ThaliTest[1327:2481695] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 11:35:29.871 ThaliTest[1327:2481695] Multi-tasking -> Device: YES, App: YES
,2016-08-30 11:35:29.890 ThaliTest[1327:2481695] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 11:35:31.748 ThaliTest[1327:2481695] Using UIWebView
,2016-08-30 11:35:31.756 ThaliTest[1327:2481695] [CDVTimer][handleopenurl] 1.811981ms
,2016-08-30 11:35:31.764 ThaliTest[1327:2481695] [CDVTimer][intentandnavigationfilter] 7.818997ms
,2016-08-30 11:35:31.765 ThaliTest[1327:2481695] [CDVTimer][gesturehandler] 0.351012ms
,2016-08-30 11:35:31.765 ThaliTest[1327:2481695] [CDVTimer][TotalPluginStartup] 11.823952ms
,2016-08-30 11:35:38.444 ThaliTest[1327:2481695] Resetting plugins due to page load.
,2016-08-30 11:35:42.022 ThaliTest[1327:2481695] Finished load of: file:///var/mobile/Containers/Bundle/Application/CE22A587-A152-4CF7-949D-79649B01AFCF/ThaliTest.app/www/index.html
,2016-08-30 11:35:42.236 ThaliTest[1327:2481695] JXcore Cordova plugin initializing
,2016-08-30 11:35:42.237 ThaliTest[1327:2481962] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 11:35:48.431 ThaliTest[1327:2481962] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-30 11:35:48.431 ThaliTest[1327:2481962] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-30 11:35:48.432 ThaliTest[1327:2481962] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 11:35:48.433 ThaliTest[1327:2481962] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 11:35:48.726 ThaliTest[1327:2481962] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.005250036716461182
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
