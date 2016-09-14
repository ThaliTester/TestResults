#### Test 8526390229a14d1_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7D992D2F-7BB5-4344-A8D2-E3223B8F51E2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7D992D2F-7BB5-4344-A8D2-E3223B8F51E2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/815AE437-C4EF-4489-AE47-F5B91FA71429/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50113"
,(lldb)     command script import "/tmp/7D992D2F-7BB5-4344-A8D2-E3223B8F51E2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 22:14:47.529 ThaliTest[2272:4787932] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0BC7E29C-73C9-4690-A282-8A8C1F1975C8/Library/Cookies/Cookies.binarycookies
,2016-09-14 22:14:47.592 ThaliTest[2272:4787932] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 22:14:47.594 ThaliTest[2272:4787932] Multi-tasking -> Device: YES, App: YES
,2016-09-14 22:14:47.611 ThaliTest[2272:4787932] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 22:14:48.385 ThaliTest[2272:4787932] Using UIWebView
2016-09-14 22:14:48.388 ThaliTest[2272:4787932] [CDVTimer][handleopenurl] 0.163019ms
,2016-09-14 22:14:48.392 ThaliTest[2272:4787932] [CDVTimer][intentandnavigationfilter] 3.886998ms
2016-09-14 22:14:48.392 ThaliTest[2272:4787932] [CDVTimer][gesturehandler] 0.124991ms
2016-09-14 22:14:48.392 ThaliTest[2272:4787932] [CDVTimer][TotalPluginStartup] 4.842043ms
,2016-09-14 22:14:51.424 ThaliTest[2272:4787932] Resetting plugins due to page load.
,2016-09-14 22:14:53.064 ThaliTest[2272:4787932] Finished load of: file:///var/mobile/Containers/Bundle/Application/815AE437-C4EF-4489-AE47-F5B91FA71429/ThaliTest.app/www/index.html
,2016-09-14 22:14:53.257 ThaliTest[2272:4787932] JXcore Cordova plugin initializing
,2016-09-14 22:14:53.258 ThaliTest[2272:4788101] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x158743960>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 22:15:16.045 ThaliTest[2272:4787932] BTM: attaching to BTServer
,2016-09-14 22:15:17.453 ThaliTest[2272:4787932] BTM: local device power state changed
2016-09-14 22:15:17.453 ThaliTest[2272:4787932] BTM: power is now off
,2016-09-14 22:15:18.145 ThaliTest[2272:4787932] BTM: local device power state changed
2016-09-14 22:15:18.147 ThaliTest[2272:4787932] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  16.30881994962692
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
