#### Test 82914073a7b15c1_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073a7b15c1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3BB31EAD-FE32-4B32-BC16-10D1E32510D1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3BB31EAD-FE32-4B32-BC16-10D1E32510D1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073a7b15c1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073a7b15c1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/13C203F4-9A78-41A0-A207-4AE2AF847139/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57801"
,(lldb)     command script import "/tmp/3BB31EAD-FE32-4B32-BC16-10D1E32510D1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 18:38:33.922 ThaliTest[1185:2427600] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FCB9B0F4-0654-425E-AC96-D12EF569FB71/Library/Cookies/Cookies.binarycookies
,2016-08-29 18:38:34.329 ThaliTest[1185:2427600] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 18:38:34.331 ThaliTest[1185:2427600] Multi-tasking -> Device: YES, App: YES
,2016-08-29 18:38:34.357 ThaliTest[1185:2427600] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 18:38:36.353 ThaliTest[1185:2427600] Using UIWebView
,2016-08-29 18:38:36.361 ThaliTest[1185:2427600] [CDVTimer][handleopenurl] 0.469029ms
,2016-08-29 18:38:36.370 ThaliTest[1185:2427600] [CDVTimer][intentandnavigationfilter] 8.138001ms
2016-08-29 18:38:36.371 ThaliTest[1185:2427600] [CDVTimer][gesturehandler] 0.410020ms
2016-08-29 18:38:36.371 ThaliTest[1185:2427600] [CDVTimer][TotalPluginStartup] 11.307001ms
,2016-08-29 18:38:42.562 ThaliTest[1185:2427600] Resetting plugins due to page load.
,2016-08-29 18:38:45.700 ThaliTest[1185:2427600] Finished load of: file:///var/mobile/Containers/Bundle/Application/13C203F4-9A78-41A0-A207-4AE2AF847139/ThaliTest.app/www/index.html
,2016-08-29 18:38:45.716 ThaliTest[1185:2427600] JXcore Cordova plugin initializing
,2016-08-29 18:38:45.717 ThaliTest[1185:2427834] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  20
Number of passed tests:  20
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  44.05722099542618
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
