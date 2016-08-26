#### Test 79763830e2067e4_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830e2067e4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/CE5B0141-3C8F-4304-B2F2-EA15F9B8416B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CE5B0141-3C8F-4304-B2F2-EA15F9B8416B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830e2067e4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830e2067e4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3CB24099-87E4-4A00-ABBA-80B78B1A1EFC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53333"
,(lldb)     command script import "/tmp/CE5B0141-3C8F-4304-B2F2-EA15F9B8416B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 14:15:55.857 ThaliTest[1060:1977988] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/93346ACA-DB2E-4D1A-9813-AFE237A23568/Library/Cookies/Cookies.binarycookies
,2016-08-26 14:15:56.194 ThaliTest[1060:1977988] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 14:15:56.195 ThaliTest[1060:1977988] Multi-tasking -> Device: YES, App: YES
,2016-08-26 14:15:56.210 ThaliTest[1060:1977988] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 14:15:58.070 ThaliTest[1060:1977988] Using UIWebView
,2016-08-26 14:15:58.077 ThaliTest[1060:1977988] [CDVTimer][handleopenurl] 0.437975ms
,2016-08-26 14:15:58.084 ThaliTest[1060:1977988] [CDVTimer][intentandnavigationfilter] 6.852984ms
,2016-08-26 14:15:58.085 ThaliTest[1060:1977988] [CDVTimer][gesturehandler] 0.335038ms
,2016-08-26 14:15:58.086 ThaliTest[1060:1977988] [CDVTimer][TotalPluginStartup] 9.335995ms
,2016-08-26 14:16:04.556 ThaliTest[1060:1977988] Resetting plugins due to page load.
,2016-08-26 14:16:08.255 ThaliTest[1060:1977988] Finished load of: file:///var/mobile/Containers/Bundle/Application/3CB24099-87E4-4A00-ABBA-80B78B1A1EFC/ThaliTest.app/www/index.html
,2016-08-26 14:16:08.484 ThaliTest[1060:1977988] JXcore Cordova plugin initializing
,2016-08-26 14:16:08.485 ThaliTest[1060:1978225] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 14:16:14.713 ThaliTest[1060:1978225] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-26 14:16:14.714 ThaliTest[1060:1978225] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 14:16:14.714 ThaliTest[1060:1978225] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 14:16:14.716 ThaliTest[1060:1978225] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 14:16:15.014 ThaliTest[1060:1978225] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  3
Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01284098625183105
Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
