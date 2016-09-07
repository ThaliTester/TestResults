#### Test 83627337a1c904e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337a1c904e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0C330468-1538-4A77-AEAE-1BBAFC8A459C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0C330468-1538-4A77-AEAE-1BBAFC8A459C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337a1c904e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337a1c904e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ED5046CF-6076-4B7C-A40A-690D6FA409B1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61437"
,(lldb)     command script import "/tmp/0C330468-1538-4A77-AEAE-1BBAFC8A459C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 09:32:57.976 ThaliTest[1768:3707481] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7328A2C6-6259-47AF-80E9-194B46832B57/Library/Cookies/Cookies.binarycookies
,2016-09-07 09:32:58.226 ThaliTest[1768:3707481] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 09:32:58.227 ThaliTest[1768:3707481] Multi-tasking -> Device: YES, App: YES
,2016-09-07 09:32:58.247 ThaliTest[1768:3707481] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 09:32:59.014 ThaliTest[1768:3707481] Using UIWebView
,2016-09-07 09:32:59.017 ThaliTest[1768:3707481] [CDVTimer][handleopenurl] 0.156045ms
,2016-09-07 09:32:59.020 ThaliTest[1768:3707481] [CDVTimer][intentandnavigationfilter] 2.824962ms
2016-09-07 09:32:59.021 ThaliTest[1768:3707481] [CDVTimer][gesturehandler] 0.136018ms
2016-09-07 09:32:59.021 ThaliTest[1768:3707481] [CDVTimer][TotalPluginStartup] 3.805995ms
,2016-09-07 09:33:01.932 ThaliTest[1768:3707481] Resetting plugins due to page load.
,2016-09-07 09:33:03.369 ThaliTest[1768:3707481] Finished load of: file:///var/mobile/Containers/Bundle/Application/ED5046CF-6076-4B7C-A40A-690D6FA409B1/ThaliTest.app/www/index.html
,2016-09-07 09:33:03.560 ThaliTest[1768:3707481] JXcore Cordova plugin initializing
2016-09-07 09:33:03.561 ThaliTest[1768:3707668] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 09:33:11.446 ThaliTest[1768:3707668] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-07 09:33:11.447 ThaliTest[1768:3707668] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-07 09:33:11.448 ThaliTest[1768:3707668] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-07 09:33:11.451 ThaliTest[1768:3707668] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-09-07 09:33:11.844 ThaliTest[1768:3707668] jxcore: executeNativeTests: success
,Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.006796956062316895
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
