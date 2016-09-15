#### Test 836273372ac050d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273372ac050d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/82A6FA24-EA61-4955-9990-DF94C98BA086/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/82A6FA24-EA61-4955-9990-DF94C98BA086/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273372ac050d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273372ac050d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/71EF3844-A0C7-4FD1-894D-1F807F7545D3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51904"
,(lldb)     command script import "/tmp/82A6FA24-EA61-4955-9990-DF94C98BA086/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 08:47:36.895 ThaliTest[2316:4855338] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F3783364-FE63-4587-9338-ED25B2475FD6/Library/Cookies/Cookies.binarycookies
,2016-09-15 08:47:37.160 ThaliTest[2316:4855338] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 08:47:37.162 ThaliTest[2316:4855338] Multi-tasking -> Device: YES, App: YES
,2016-09-15 08:47:37.179 ThaliTest[2316:4855338] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 08:47:37.977 ThaliTest[2316:4855338] Using UIWebView
,2016-09-15 08:47:37.982 ThaliTest[2316:4855338] [CDVTimer][handleopenurl] 0.155985ms
,2016-09-15 08:47:37.985 ThaliTest[2316:4855338] [CDVTimer][intentandnavigationfilter] 2.855003ms
2016-09-15 08:47:37.986 ThaliTest[2316:4855338] [CDVTimer][gesturehandler] 0.144005ms
2016-09-15 08:47:37.986 ThaliTest[2316:4855338] [CDVTimer][TotalPluginStartup] 3.822982ms
,2016-09-15 08:47:40.980 ThaliTest[2316:4855338] Resetting plugins due to page load.
,2016-09-15 08:47:42.417 ThaliTest[2316:4855338] Finished load of: file:///var/mobile/Containers/Bundle/Application/71EF3844-A0C7-4FD1-894D-1F807F7545D3/ThaliTest.app/www/index.html
,2016-09-15 08:47:42.602 ThaliTest[2316:4855338] JXcore Cordova plugin initializing
,2016-09-15 08:47:42.605 ThaliTest[2316:4855515] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 08:47:50.440 ThaliTest[2316:4855515] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-15 08:47:50.442 ThaliTest[2316:4855515] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 08:47:50.442 ThaliTest[2316:4855515] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {,"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-15 08:47:50.444 ThaliTest[2316:4855515] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-09-15 08:47:50.834 ThaliTest[2316:4855515] jxcore: executeNativeTests: success
,Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.003737032413482666
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
