#### Test 836273379690449_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7685EC39-2D1B-4D5A-A516-4F0FBEAD815A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7685EC39-2D1B-4D5A-A516-4F0FBEAD815A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273379690449/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0961960B-E0E0-4CB8-B169-603AF41349A8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56623"
,(lldb)     command script import "/tmp/7685EC39-2D1B-4D5A-A516-4F0FBEAD815A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 14:16:34.011 ThaliTest[2137:4577320] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D433DDF6-40D4-41C1-BF02-291B28846D6B/Library/Cookies/Cookies.binarycookies
,2016-09-13 14:16:34.266 ThaliTest[2137:4577320] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 14:16:34.268 ThaliTest[2137:4577320] Multi-tasking -> Device: YES, App: YES
,2016-09-13 14:16:34.287 ThaliTest[2137:4577320] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 14:16:35.066 ThaliTest[2137:4577320] Using UIWebView
,2016-09-13 14:16:35.070 ThaliTest[2137:4577320] [CDVTimer][handleopenurl] 0.162005ms
2016-09-13 14:16:35.073 ThaliTest[2137:4577320] [CDVTimer][intentandnavigationfilter] 2.646983ms
2016-09-13 14:16:35.073 ThaliTest[2137:4577320] [CDVTimer][gesturehandle,r] 0.122964ms
2016-09-13 14:16:35.073 ThaliTest[2137:4577320] [CDVTimer][TotalPluginStartup] 3.549039ms
,2016-09-13 14:16:38.028 ThaliTest[2137:4577320] Resetting plugins due to page load.
,2016-09-13 14:16:39.459 ThaliTest[2137:4577320] Finished load of: file:///var/mobile/Containers/Bundle/Application/0961960B-E0E0-4CB8-B169-603AF41349A8/ThaliTest.app/www/index.html
,2016-09-13 14:16:39.655 ThaliTest[2137:4577320] JXcore Cordova plugin initializing
2016-09-13 14:16:39.656 ThaliTest[2137:4577509] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 14:16:47.446 ThaliTest[2137:4577509] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 14:16:47.447 ThaliTest[2137:4577509] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 14:16:47.447 ThaliTest[2137:4577509] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-13 14:16:47.449 ThaliTest[2137:4577509] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-09-13 14:16:47.845 ThaliTest[2137:4577509] jxcore: executeNativeTests: success
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  0.002905011177062988
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
