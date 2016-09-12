#### Test 8362733705cfec3_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/84B7DF43-A462-41B8-A91B-65565679A70F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/84B7DF43-A462-41B8-A91B-65565679A70F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8362733705cfec3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0C962353-712B-4398-8E3A-F0F2F87D077A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56690"
,(lldb)     command script import "/tmp/84B7DF43-A462-41B8-A91B-65565679A70F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 13:55:23.016 ThaliTest[2037:4424964] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/46436394-BF33-4681-B68F-E43A993229A0/Library/Cookies/Cookies.binarycookies
,2016-09-12 13:55:23.274 ThaliTest[2037:4424964] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 13:55:23.275 ThaliTest[2037:4424964] Multi-tasking -> Device: YES, App: YES
,2016-09-12 13:55:23.295 ThaliTest[2037:4424964] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 13:55:24.080 ThaliTest[2037:4424964] Using UIWebView
2016-09-12 13:55:24.083 ThaliTest[2037:4424964] [CDVTimer][handleopenurl] 0.155985ms
,2016-09-12 13:55:24.086 ThaliTest[2037:4424964] [CDVTimer][intentandnavigationfilter] 2.835989ms
2016-09-12 13:55:24.086 ThaliTest[2037:4424964] [CDVTimer][gesturehandler] 0.144958ms
2016-09-12 13:55:24.087 ThaliTest[2037:4424964] [CDVTimer][TotalPluginS,tartup] 3.762007ms
,2016-09-12 13:55:27.047 ThaliTest[2037:4424964] Resetting plugins due to page load.
,2016-09-12 13:55:28.459 ThaliTest[2037:4424964] Finished load of: file:///var/mobile/Containers/Bundle/Application/0C962353-712B-4398-8E3A-F0F2F87D077A/ThaliTest.app/www/index.html
,2016-09-12 13:55:28.639 ThaliTest[2037:4424964] JXcore Cordova plugin initializing
,2016-09-12 13:55:28.640 ThaliTest[2037:4425138] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-12 13:55:36.447 ThaliTest[2037:4425138] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-12 13:55:36.449 ThaliTest[2037:4425138] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-12 13:55:36.450 ThaliTest[2037:4425138] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-12 13:55:36.453 ThaliTest[2037:4425138] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-09-12 13:55:36.848 ThaliTest[2037:4425138] jxcore: executeNativeTests: success
,Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.004718959331512451
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
