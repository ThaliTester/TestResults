#### Test 81444731251ddd8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81444731251ddd8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CFF0FBD2-C6BB-40C7-B040-A7BFC77B1951/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CFF0FBD2-C6BB-40C7-B040-A7BFC77B1951/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81444731251ddd8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81444731251ddd8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CF03BF2C-10A9-4997-9487-6ABE6A0E2A23/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56009"
,(lldb)     command script import "/tmp/CFF0FBD2-C6BB-40C7-B040-A7BFC77B1951/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 19:01:24.148 ThaliTest[991:1991090] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DB8E108F-FE6B-43C5-BBEF-F7167D48EAF4/Library/Cookies/Cookies.binarycookies
,2016-08-26 19:01:24.598 ThaliTest[991:1991090] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 19:01:24.600 ThaliTest[991:1991090] Multi-tasking -> Device: YES, App: YES
,2016-08-26 19:01:24.626 ThaliTest[991:1991090] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 19:01:26.326 ThaliTest[991:1991090] Using UIWebView
,2016-08-26 19:01:26.337 ThaliTest[991:1991090] [CDVTimer][handleopenurl] 0.454962ms
,2016-08-26 19:01:26.346 ThaliTest[991:1991090] [CDVTimer][intentandnavigationfilter] 8.130014ms
2016-08-26 19:01:26.347 ThaliTest[991:1991090] [CDVTimer][gesturehandler] 0.376999ms
2016-08-26 19:01:26.348 ThaliTest[991:1991090] [CDVTimer][TotalPluginStar,tup] 10.878980ms
,2016-08-26 19:01:32.053 ThaliTest[991:1991090] Resetting plugins due to page load.
,2016-08-26 19:01:34.947 ThaliTest[991:1991090] Finished load of: file:///var/mobile/Containers/Bundle/Application/CF03BF2C-10A9-4997-9487-6ABE6A0E2A23/ThaliTest.app/www/index.html
,2016-08-26 19:01:35.193 ThaliTest[991:1991090] JXcore Cordova plugin initializing
,2016-08-26 19:01:35.194 ThaliTest[991:1991341] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,*Native tests were executed*
,Total number of executed tests:  15
,Number of passed tests:  15
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  38.16295999288559
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
