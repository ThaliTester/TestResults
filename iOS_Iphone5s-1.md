#### Test 797638309aa2d44_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638309aa2d44/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0FC1EA81-7CE0-4D16-ACF3-0810E3B55D07/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0FC1EA81-7CE0-4D16-ACF3-0810E3B55D07/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638309aa2d44/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638309aa2d44/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B4927C2F-7229-4B27-A33C-1B095EB841B4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65279"
,(lldb)     command script import "/tmp/0FC1EA81-7CE0-4D16-ACF3-0810E3B55D07/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 16:53:20.142 ThaliTest[966:1975406] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A5CD9AA0-E812-4623-8B94-41953D2313B2/Library/Cookies/Cookies.binarycookies
,2016-08-26 16:53:20.595 ThaliTest[966:1975406] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 16:53:20.597 ThaliTest[966:1975406] Multi-tasking -> Device: YES, App: YES
,2016-08-26 16:53:20.620 ThaliTest[966:1975406] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 16:53:22.287 ThaliTest[966:1975406] Using UIWebView
,2016-08-26 16:53:22.299 ThaliTest[966:1975406] [CDVTimer][handleopenurl] 0.474989ms
,2016-08-26 16:53:22.308 ThaliTest[966:1975406] [CDVTimer][intentandnavigationfilter] 7.944047ms
2016-08-26 16:53:22.309 ThaliTest[966:1975406] [CDVTimer][gesturehandler] 0.404000ms
2016-08-26 16:53:22.309 ThaliTest[966:1975406] [CDVTimer][TotalPluginStar,tup] 10.769010ms
,2016-08-26 16:53:28.095 ThaliTest[966:1975406] Resetting plugins due to page load.
,2016-08-26 16:53:31.019 ThaliTest[966:1975406] Finished load of: file:///var/mobile/Containers/Bundle/Application/B4927C2F-7229-4B27-A33C-1B095EB841B4/ThaliTest.app/www/index.html
,2016-08-26 16:53:31.279 ThaliTest[966:1975406] JXcore Cordova plugin initializing
,2016-08-26 16:53:31.281 ThaliTest[966:1975630] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 16:53:39.313 ThaliTest[966:1975630] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-26 16:53:39.314 ThaliTest[966:1975630] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 16:53:39.315 ThaliTest[966:1975630] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 16:53:39.317 ThaliTest[966:1975630] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 16:53:39.704 ThaliTest[966:1975630] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01709997653961182
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
