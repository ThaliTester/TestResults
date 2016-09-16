#### Test 83627337176b608_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1AD8ECB8-0068-47EF-A108-CE0562257B1B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1AD8ECB8-0068-47EF-A108-CE0562257B1B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2218BCCB-1CF4-424D-8D1D-F78F1E91B374/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55860"
,(lldb)     command script import "/tmp/1AD8ECB8-0068-47EF-A108-CE0562257B1B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 10:01:06.068 ThaliTest[2438:5017547] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CB476701-3F95-406A-964F-5CC367D80A06/Library/Cookies/Cookies.binarycookies
,2016-09-16 10:01:06.511 ThaliTest[2438:5017547] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 10:01:06.513 ThaliTest[2438:5017547] Multi-tasking -> Device: YES, App: YES
,2016-09-16 10:01:06.537 ThaliTest[2438:5017547] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 10:01:08.239 ThaliTest[2438:5017547] Using UIWebView
,2016-09-16 10:01:08.250 ThaliTest[2438:5017547] [CDVTimer][handleopenurl] 0.474989ms
,2016-09-16 10:01:08.258 ThaliTest[2438:5017547] [CDVTimer][intentandnavigationfilter] 7.952034ms
2016-09-16 10:01:08.259 ThaliTest[2438:5017547] [CDVTimer][gesturehandler] 0.412047ms
2016-09-16 10:01:08.260 ThaliTest[2438:5017547] [CDVTimer][TotalPluginS,tartup] 10.811031ms
,2016-09-16 10:01:14.012 ThaliTest[2438:5017547] Resetting plugins due to page load.
,2016-09-16 10:01:16.745 ThaliTest[2438:5017547] Finished load of: file:///var/mobile/Containers/Bundle/Application/2218BCCB-1CF4-424D-8D1D-F78F1E91B374/ThaliTest.app/www/index.html
,2016-09-16 10:01:17.060 ThaliTest[2438:5017547] JXcore Cordova plugin initializing
,2016-09-16 10:01:17.061 ThaliTest[2438:5017790] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 10:01:25.117 ThaliTest[2438:5017790] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-16 10:01:25.118 ThaliTest[2438:5017790] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 10:01:25.118 ThaliTest[2438:5017790] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 10:01:25.120 ThaliTest[2438:5017790] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 10:01:25.512 ThaliTest[2438:5017790] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004086971282958984
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
