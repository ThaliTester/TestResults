#### Test 8504691174f7534_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C61C964C-ADC4-4E8A-B87B-314A09F1D582/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C61C964C-ADC4-4E8A-B87B-314A09F1D582/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F0DB46AE-0740-4484-98F6-E5846EDDD3AB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58567"
,(lldb)     command script import "/tmp/C61C964C-ADC4-4E8A-B87B-314A09F1D582/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success,
,(lldb)     autoexit
,2016-09-15 12:00:22.173 ThaliTest[2341:4877842] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A4340A29-57C0-447B-91D1-482266EE6BCA/Library/Cookies/Cookies.binarycookies
,2016-09-15 12:00:22.443 ThaliTest[2341:4877842] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 12:00:22.444 ThaliTest[2341:4877842] Multi-tasking -> Device: YES, App: YES
,2016-09-15 12:00:22.463 ThaliTest[2341:4877842] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 12:00:23.298 ThaliTest[2341:4877842] Using UIWebView
,2016-09-15 12:00:23.302 ThaliTest[2341:4877842] [CDVTimer][handleopenurl] 0.156999ms
,2016-09-15 12:00:23.305 ThaliTest[2341:4877842] [CDVTimer][intentandnavigationfilter] 2.838016ms
2016-09-15 12:00:23.306 ThaliTest[2341:4877842] [CDVTimer][gesturehandler] 0.160992ms
2016-09-15 12:00:23.306 ThaliTest[2341:4877842] [CDVTimer][TotalPluginStartup] 3.829002ms
,2016-09-15 12:00:26.627 ThaliTest[2341:4877842] Resetting plugins due to page load.
,2016-09-15 12:00:27.974 ThaliTest[2341:4877842] Finished load of: file:///var/mobile/Containers/Bundle/Application/F0DB46AE-0740-4484-98F6-E5846EDDD3AB/ThaliTest.app/www/index.html
,2016-09-15 12:00:28.160 ThaliTest[2341:4877842] JXcore Cordova plugin initializing
2016-09-15 12:00:28.161 ThaliTest[2341:4878030] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 12:00:36.034 ThaliTest[2341:4878030] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-15 12:00:36.036 ThaliTest[2341:4878030] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-15 12:00:36.036 ThaliTest[2341:4878030] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 12:00:36.039 ThaliTest[2341:4878030] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-15 12:00:36.422 ThaliTest[2341:4878030] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.00491100549697876
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
