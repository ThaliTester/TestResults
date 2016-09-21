#### Test 859603041ea1ffb_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/859603041ea1ffb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7AFCB405-1FCE-4835-88CC-538313C641AB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7AFCB405-1FCE-4835-88CC-538313C641AB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/859603041ea1ffb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/859603041ea1ffb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B722901E-F6B0-4BD1-9777-AD2B7190942F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51994"
,(lldb)     command script import "/tmp/7AFCB405-1FCE-4835-88CC-538313C641AB/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 12:11:16.135 ThaliTest[2747:5797975] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/02A84DA8-C339-40C2-A572-2DB1C1379979/Library/Cookies/Cookies.binarycookies
,2016-09-21 12:11:16.414 ThaliTest[2747:5797975] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 12:11:16.415 ThaliTest[2747:5797975] Multi-tasking -> Device: YES, App: YES
,2016-09-21 12:11:16.435 ThaliTest[2747:5797975] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 12:11:17.245 ThaliTest[2747:5797975] Using UIWebView
,2016-09-21 12:11:17.250 ThaliTest[2747:5797975] [CDVTimer][handleopenurl] 0.169992ms
2016-09-21 12:11:17.253 ThaliTest[2747:5797975] [CDVTimer][intentandnavigationfilter] 2.698004ms
2016-09-21 12:11:17.253 ThaliTest[2747:5797975] [CDVTimer][gesturehandler] 0.122964ms
2016-09-21 12:11:17.253 ThaliTest[2747:5797975] [CDVTimer][TotalPluginStartup] 3.607035ms
,2016-09-21 12:11:20.284 ThaliTest[2747:5797975] Resetting plugins due to page load.
,2016-09-21 12:11:21.561 ThaliTest[2747:5797975] Finished load of: file:///var/mobile/Containers/Bundle/Application/B722901E-F6B0-4BD1-9777-AD2B7190942F/ThaliTest.app/www/index.html
,2016-09-21 12:11:21.744 ThaliTest[2747:5797975] JXcore Cordova plugin initializing
2016-09-21 12:11:21.745 ThaliTest[2747:5798156] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 12:11:29.588 ThaliTest[2747:5798156] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 12:11:29.588 ThaliTest[2747:5798156] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 12:11:29.588 ThaliTest[2747:5,798156] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-21 12:11:29.592 ThaliTest[2747:5798156] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 12:11:29.959 ThaliTest[2747:5798156] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.00291597843170166
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
