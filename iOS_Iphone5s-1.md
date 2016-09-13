#### Test 8291407367fbc55_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8291407367fbc55/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DD7D8D11-5EE0-4069-9D12-51B5D6A28337/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DD7D8D11-5EE0-4069-9D12-51B5D6A28337/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8291407367fbc55/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8291407367fbc55/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2AC47CD5-1A09-4DFE-9A72-2F9C5707DA53/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61438"
,(lldb)     command script import "/tmp/DD7D8D11-5EE0-4069-9D12-51B5D6A28337/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 09:40:57.922 ThaliTest[2105:4547331] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B87D5495-C271-4076-8939-09282A3F131B/Library/Cookies/Cookies.binarycookies
,2016-09-13 09:40:58.342 ThaliTest[2105:4547331] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 09:40:58.344 ThaliTest[2105:4547331] Multi-tasking -> Device: YES, App: YES
,2016-09-13 09:40:58.365 ThaliTest[2105:4547331] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 09:41:00.403 ThaliTest[2105:4547331] Using UIWebView
,2016-09-13 09:41:00.411 ThaliTest[2105:4547331] [CDVTimer][handleopenurl] 0.519037ms
,2016-09-13 09:41:00.420 ThaliTest[2105:4547331] [CDVTimer][intentandnavigationfilter] 7.974982ms
2016-09-13 09:41:00.421 ThaliTest[2105:4547331] [CDVTimer][gesturehandler] 0.400007ms
2016-09-13 09:41:00.421 ThaliTest[2105:4547331] [CDVTimer][TotalPluginStartup] 11.173010ms
,2016-09-13 09:41:07.317 ThaliTest[2105:4547331] Resetting plugins due to page load.
,2016-09-13 09:41:10.672 ThaliTest[2105:4547331] Finished load of: file:///var/mobile/Containers/Bundle/Application/2AC47CD5-1A09-4DFE-9A72-2F9C5707DA53/ThaliTest.app/www/index.html
,2016-09-13 09:41:10.918 ThaliTest[2105:4547331] JXcore Cordova plugin initializing
,2016-09-13 09:41:10.920 ThaliTest[2105:4547561] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x14ed5360>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  48
,Number of passed tests:  48
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  11.05298095941544
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
