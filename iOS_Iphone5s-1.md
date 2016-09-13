#### Test 846487404bc066c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5C618AF9-A0AB-4AC1-A0DE-4EEB2F8AC6C8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5C618AF9-A0AB-4AC1-A0DE-4EEB2F8AC6C8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/85B48491-EDB0-4162-B97D-424B0FE7C6CC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49385"
,(lldb)     command script import "/tmp/5C618AF9-A0AB-4AC1-A0DE-4EEB2F8AC6C8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 11:55:18.517 ThaliTest[2120:4561354] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F3144E85-B8C7-465E-87D5-1CE78E4774D2/Library/Cookies/Cookies.binarycookies
,2016-09-13 11:55:18.774 ThaliTest[2120:4561354] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 11:55:18.776 ThaliTest[2120:4561354] Multi-tasking -> Device: YES, App: YES
,2016-09-13 11:55:18.794 ThaliTest[2120:4561354] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 11:55:19.586 ThaliTest[2120:4561354] Using UIWebView
,2016-09-13 11:55:19.590 ThaliTest[2120:4561354] [CDVTimer][handleopenurl] 0.160992ms
,2016-09-13 11:55:19.594 ThaliTest[2120:4561354] [CDVTimer][intentandnavigationfilter] 3.553987ms
2016-09-13 11:55:19.594 ThaliTest[2120:4561354] [CDVTimer][gesturehandler] 0.151992ms
2016-09-13 11:55:19.595 ThaliTest[2120:4561354] [CDVTimer][TotalPluginS,tartup] 4.514992ms
,2016-09-13 11:55:22.538 ThaliTest[2120:4561354] Resetting plugins due to page load.
,2016-09-13 11:55:23.979 ThaliTest[2120:4561354] Finished load of: file:///var/mobile/Containers/Bundle/Application/85B48491-EDB0-4162-B97D-424B0FE7C6CC/ThaliTest.app/www/index.html
,2016-09-13 11:55:24.184 ThaliTest[2120:4561354] JXcore Cordova plugin initializing
2016-09-13 11:55:24.185 ThaliTest[2120:4561527] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 11:55:31.991 ThaliTest[2120:4561527] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 11:55:31.991 ThaliTest[2120:4561527] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 11:55:31.992 ThaliTest[2120:4,561527] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-13 11:55:31.994 ThaliTest[2120:4561527] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,2016-09-13 11:55:32.366 ThaliTest[2120:4561527] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  0.004787981510162354
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
