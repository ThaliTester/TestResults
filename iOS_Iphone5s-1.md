#### Test 829140730a15ac0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140730a15ac0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/BBE674A1-43F8-49B9-A399-C556653A97C4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/BBE674A1-43F8-49B9-A399-C556653A97C4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140730a15ac0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140730a15ac0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4C669D5D-F70E-424D-86C0-0715F050E3B7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52584"
,(lldb)     command script import "/tmp/BBE674A1-43F8-49B9-A399-C556653A97C4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 13:14:28.367 ThaliTest[1808:3733424] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1D1C14C1-670A-4916-95A9-D38C17D83963/Library/Cookies/Cookies.binarycookies
,2016-09-07 13:14:28.625 ThaliTest[1808:3733424] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 13:14:28.627 ThaliTest[1808:3733424] Multi-tasking -> Device: YES, App: YES
,2016-09-07 13:14:28.647 ThaliTest[1808:3733424] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 13:14:29.432 ThaliTest[1808:3733424] Using UIWebView
2016-09-07 13:14:29.434 ThaliTest[1808:3733424] [CDVTimer][handleopenurl] 0.150979ms
,2016-09-07 13:14:29.438 ThaliTest[1808:3733424] [CDVTimer][intentandnavigationfilter] 3.767014ms
2016-09-07 13:14:29.439 ThaliTest[1808:3733424] [CDVTimer][gesturehandler] 0.151992ms
2016-09-07 13:14:29.439 ThaliTest[1808:3733424] [CDVTimer][TotalPluginS,tartup] 4.666984ms
,2016-09-07 13:14:32.378 ThaliTest[1808:3733424] Resetting plugins due to page load.
,2016-09-07 13:14:33.639 ThaliTest[1808:3733424] Finished load of: file:///var/mobile/Containers/Bundle/Application/4C669D5D-F70E-424D-86C0-0715F050E3B7/ThaliTest.app/www/index.html
,2016-09-07 13:14:33.828 ThaliTest[1808:3733424] JXcore Cordova plugin initializing
2016-09-07 13:14:33.829 ThaliTest[1808:3733616] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  38
,Number of passed tests:  38
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  12.10878902673721
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
