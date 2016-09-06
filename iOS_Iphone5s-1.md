#### Test 83444050adbb179_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83444050adbb179/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A7B3DD90-56EA-45B0-A055-7B0802CC9D6F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A7B3DD90-56EA-45B0-A055-7B0802CC9D6F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83444050adbb179/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83444050adbb179/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0BCD0DCB-0BF3-4FC2-AC77-D548F894F7C5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57522"
,(lldb)     command script import "/tmp/A7B3DD90-56EA-45B0-A055-7B0802CC9D6F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 19:20:52.042 ThaliTest[1726:3622914] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C9C78AB4-CF7E-492D-B22E-DD58A9CED5D1/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:20:52.296 ThaliTest[1726:3622914] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 19:20:52.297 ThaliTest[1726:3622914] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:20:52.318 ThaliTest[1726:3622914] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:20:53.093 ThaliTest[1726:3622914] Using UIWebView
,2016-09-06 19:20:53.096 ThaliTest[1726:3622914] [CDVTimer][handleopenurl] 0.162005ms
,2016-09-06 19:20:53.099 ThaliTest[1726:3622914] [CDVTimer][intentandnavigationfilter] 2.885044ms
2016-09-06 19:20:53.100 ThaliTest[1726:3622914] [CDVTimer][gesturehandler] 0.172019ms
2016-09-06 19:20:53.100 ThaliTest[1726:3622914] [CDVTimer][TotalPluginS,tartup] 3.960967ms
,2016-09-06 19:20:56.064 ThaliTest[1726:3622914] Resetting plugins due to page load.
,2016-09-06 19:20:57.367 ThaliTest[1726:3622914] Finished load of: file:///var/mobile/Containers/Bundle/Application/0BCD0DCB-0BF3-4FC2-AC77-D548F894F7C5/ThaliTest.app/www/index.html
,2016-09-06 19:20:57.559 ThaliTest[1726:3622914] JXcore Cordova plugin initializing
,2016-09-06 19:20:57.560 ThaliTest[1726:3623093] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  15
Number of passed tests:  15
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  38.83406901359558
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
