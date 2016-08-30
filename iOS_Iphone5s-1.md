#### Test 832611203a07957_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832611203a07957/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/15929C12-973F-473F-A9F9-C10E0A0CCB87/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/15929C12-973F-473F-A9F9-C10E0A0CCB87/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/832611203a07957/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832611203a07957/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ADFFE44D-F935-4F47-9F2F-BD420AE31425/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60541"
,(lldb)     command script import "/tmp/15929C12-973F-473F-A9F9-C10E0A0CCB87/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 17:39:04.183 ThaliTest[1290:2573934] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B9EFD440-4071-4A42-A91E-952640A332A9/Library/Cookies/Cookies.binarycookies
,2016-08-30 17:39:04.579 ThaliTest[1290:2573934] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 17:39:04.581 ThaliTest[1290:2573934] Multi-tasking -> Device: YES, App: YES
,2016-08-30 17:39:04.608 ThaliTest[1290:2573934] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 17:39:06.534 ThaliTest[1290:2573934] Using UIWebView
,2016-08-30 17:39:06.542 ThaliTest[1290:2573934] [CDVTimer][handleopenurl] 0.768006ms
,2016-08-30 17:39:06.551 ThaliTest[1290:2573934] [CDVTimer][intentandnavigationfilter] 8.906960ms
2016-08-30 17:39:06.552 ThaliTest[1290:2573934] [CDVTimer][gesturehandler] 0.413001ms
2016-08-30 17:39:06.553 ThaliTest[1290:2573934] [CDVTimer][TotalPluginStartup] 12.033999ms
,2016-08-30 17:39:13.097 ThaliTest[1290:2573934] Resetting plugins due to page load.
,2016-08-30 17:39:16.409 ThaliTest[1290:2573934] Finished load of: file:///var/mobile/Containers/Bundle/Application/ADFFE44D-F935-4F47-9F2F-BD420AE31425/ThaliTest.app/www/index.html
,2016-08-30 17:39:16.649 ThaliTest[1290:2573934] JXcore Cordova plugin initializing
,2016-08-30 17:39:16.651 ThaliTest[1290:2574168] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 17:39:24.731 ThaliTest[1290:2574168] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-30 17:39:24.732 ThaliTest[1290:2574168] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 17:39:24.732 ThaliTest[1290:2574168] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 17:39:24.735 ThaliTest[1290:2574168] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 17:39:25.132 ThaliTest[1290:2574168] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.00517803430557251
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
