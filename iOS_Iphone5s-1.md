#### Test 79896569ef47422_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79896569ef47422/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/458EE030-1EBE-4056-B8AF-E46310D25B25/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/458EE030-1EBE-4056-B8AF-E46310D25B25/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79896569ef47422/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79896569ef47422/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1C0511FA-AC96-4E92-A03E-DD1E2F079C62/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52405"
,(lldb)     command script import "/tmp/458EE030-1EBE-4056-B8AF-E46310D25B25/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 18:18:35.103 ThaliTest[980:1985435] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C9F06526-1228-4D16-AFA2-726BE33BBB61/Library/Cookies/Cookies.binarycookies
,2016-08-26 18:18:35.523 ThaliTest[980:1985435] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 18:18:35.525 ThaliTest[980:1985435] Multi-tasking -> Device: YES, App: YES
,2016-08-26 18:18:35.545 ThaliTest[980:1985435] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 18:18:37.094 ThaliTest[980:1985435] Using UIWebView
,2016-08-26 18:18:37.103 ThaliTest[980:1985435] [CDVTimer][handleopenurl] 0.492036ms
,2016-08-26 18:18:37.111 ThaliTest[980:1985435] [CDVTimer][intentandnavigationfilter] 8.036017ms
2016-08-26 18:18:37.112 ThaliTest[980:1985435] [CDVTimer][gesturehandler] 0.378966ms
2016-08-26 18:18:37.113 ThaliTest[980:1985435] [CDVTimer][TotalPluginStartup] 10.803044ms
,2016-08-26 18:18:42.835 ThaliTest[980:1985435] Resetting plugins due to page load.
,2016-08-26 18:18:45.584 ThaliTest[980:1985435] Finished load of: file:///var/mobile/Containers/Bundle/Application/1C0511FA-AC96-4E92-A03E-DD1E2F079C62/ThaliTest.app/www/index.html
,2016-08-26 18:18:45.835 ThaliTest[980:1985435] JXcore Cordova plugin initializing
,2016-08-26 18:18:45.836 ThaliTest[980:1985658] JXcore instance initializing
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
,*Native tests were executed*
,Total number of executed tests:  5
Number of passed tests:  5
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.008288025856018066
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
