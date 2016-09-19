#### Test 85046911783e9ea_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/83380C04-AA88-4FE7-B25A-99EB265D22B0/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/83380C04-AA88-4FE7-B25A-99EB265D22B0/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2E66183F-A22B-43D8-BEB3-786EA932FF3C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64836"
,(lldb)     command script import "/tmp/83380C04-AA88-4FE7-B25A-99EB265D22B0/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-19 09:59:03.937 ThaliTest[1058:1337516] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C164C7C7-5524-4920-8ACD-50FEEEBF6FD1/Library/Cookies/Cookies.binarycookies
,2016-09-19 09:59:04.240 ThaliTest[1058:1337516] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-19 09:59:04.242 ThaliTest[1058:1337516] Multi-tasking -> Device: YES, App: YES
,2016-09-19 09:59:04.267 ThaliTest[1058:1337516] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-19 09:59:04.820 ThaliTest[1058:1337516] Using UIWebView
,2016-09-19 09:59:04.827 ThaliTest[1058:1337516] [CDVTimer][handleopenurl] 0.387967ms
,2016-09-19 09:59:04.835 ThaliTest[1058:1337516] [CDVTimer][intentandnavigationfilter] 7.063031ms
2016-09-19 09:59:04.835 ThaliTest[1058:1337516] [CDVTimer][gesturehandler] 0.307024ms
2016-09-19 09:59:04.836 ThaliTest[1058:1337516] [CDVTimer][TotalPluginS,tartup] 9.311020ms
,2016-09-19 09:59:10.592 ThaliTest[1058:1337516] Resetting plugins due to page load.
,2016-09-19 09:59:11.077 ThaliTest[1058:1337516] Finished load of: file:///var/containers/Bundle/Application/2E66183F-A22B-43D8-BEB3-786EA932FF3C/ThaliTest.app/www/index.html
,2016-09-19 09:59:11.479 ThaliTest[1058:1337516] JXcore Cordova plugin initializing
,2016-09-19 09:59:11.480 ThaliTest[1058:1337701] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-19 09:59:18.085 ThaliTest[1058:1337701] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-19 09:59:18.085 ThaliTest[1058:1337701] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-19 09:59:18.086 ThaliTest[1058:1337701] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-19 09:59:18.088 ThaliTest[1058:1337701] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-19 09:59:18.495 ThaliTest[1058:1337701] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.002547979354858398
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
