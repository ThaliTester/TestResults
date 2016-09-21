#### Test 850469111b8590e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469111b8590e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5E5FD74F-E20C-42C0-9224-F085EA4CB23E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5E5FD74F-E20C-42C0-9224-F085EA4CB23E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469111b8590e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469111b8590e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4902F3D4-2AC8-4FFF-AF4E-EE8115D530CE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51557"
,(lldb)     command script import "/tmp/5E5FD74F-E20C-42C0-9224-F085EA4CB23E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 11:56:03.736 ThaliTest[2740:5794666] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AE9E7D18-53FD-4D73-B8CF-CF0CC047776E/Library/Cookies/Cookies.binarycookies
,2016-09-21 11:56:04.010 ThaliTest[2740:5794666] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 11:56:04.011 ThaliTest[2740:5794666] Multi-tasking -> Device: YES, App: YES
,2016-09-21 11:56:04.031 ThaliTest[2740:5794666] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 11:56:04.836 ThaliTest[2740:5794666] Using UIWebView
,2016-09-21 11:56:04.839 ThaliTest[2740:5794666] [CDVTimer][handleopenurl] 0.293970ms
,2016-09-21 11:56:04.842 ThaliTest[2740:5794666] [CDVTimer][intentandnavigationfilter] 2.777040ms
2016-09-21 11:56:04.843 ThaliTest[2740:5794666] [CDVTimer][gesturehandler] 0.135005ms
2016-09-21 11:56:04.843 ThaliTest[2740:5794666] [CDVTimer][TotalPluginStartup] 3.880978ms
,2016-09-21 11:56:07.919 ThaliTest[2740:5794666] Resetting plugins due to page load.
,2016-09-21 11:56:09.375 ThaliTest[2740:5794666] Finished load of: file:///var/mobile/Containers/Bundle/Application/4902F3D4-2AC8-4FFF-AF4E-EE8115D530CE/ThaliTest.app/www/index.html
,2016-09-21 11:56:09.554 ThaliTest[2740:5794666] JXcore Cordova plugin initializing
,2016-09-21 11:56:09.556 ThaliTest[2740:5794846] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 11:56:17.359 ThaliTest[2740:5794846] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 11:56:17.359 ThaliTest[2740:5794846] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 11:56:17.360 ThaliTest[2740:5,794846] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-21 11:56:17.361 ThaliTest[2740:5794846] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,2016-09-21 11:56:17.733 ThaliTest[2740:5794846] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  0.0,02879977226257324
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
