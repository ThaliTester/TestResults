#### Test 85046911c8db9f2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c8db9f2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8874C5C4-2883-45B2-9EF4-FE7F2FF559B0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8874C5C4-2883-45B2-9EF4-FE7F2FF559B0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c8db9f2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c8db9f2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/70EA2209-2F43-4F05-829E-5572F79B8B86/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59703"
,(lldb)     command script import "/tmp/8874C5C4-2883-45B2-9EF4-FE7F2FF559B0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 15:59:42.806 ThaliTest[2781:5823300] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6BFF3A18-7FAF-4CBF-859F-D73CC9F2C331/Library/Cookies/Cookies.binarycookies
,2016-09-21 15:59:43.081 ThaliTest[2781:5823300] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 15:59:43.082 ThaliTest[2781:5823300] Multi-tasking -> Device: YES, App: YES
,2016-09-21 15:59:43.102 ThaliTest[2781:5823300] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 15:59:43.944 ThaliTest[2781:5823300] Using UIWebView
,2016-09-21 15:59:43.949 ThaliTest[2781:5823300] [CDVTimer][handleopenurl] 0.153005ms
2016-09-21 15:59:43.952 ThaliTest[2781:5823300] [CDVTimer][intentandnavigationfilter] 2.748013ms
2016-09-21 15:59:43.952 ThaliTest[2781:5823300] [CDVTimer][gesturehandle,r] 0.124037ms
2016-09-21 15:59:43.952 ThaliTest[2781:5823300] [CDVTimer][TotalPluginStartup] 3.633022ms
,2016-09-21 15:59:47.108 ThaliTest[2781:5823300] Resetting plugins due to page load.
,2016-09-21 15:59:48.551 ThaliTest[2781:5823300] Finished load of: file:///var/mobile/Containers/Bundle/Application/70EA2209-2F43-4F05-829E-5572F79B8B86/ThaliTest.app/www/index.html
,2016-09-21 15:59:48.732 ThaliTest[2781:5823300] JXcore Cordova plugin initializing
,2016-09-21 15:59:48.733 ThaliTest[2781:5823469] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 15:59:56.479 ThaliTest[2781:5823469] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 15:59:56.479 ThaliTest[2781:5823469] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 15:59:56.479 ThaliTest[2781:5823469] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 15:59:56.481 ThaliTest[2781:5823469] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 15:59:56.853 ThaliTest[2781:5823469] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004938960075378418
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
