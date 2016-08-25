#### Test 7989656923d4b17_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7989656923d4b17/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/707098F6-00A2-4304-9939-D06912B1BBA7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/707098F6-00A2-4304-9939-D06912B1BBA7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7989656923d4b17/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7989656923d4b17/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EDFD11CE-8CD4-4C77-8532-16E2B1089AEE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56753"
,(lldb)     command script import "/tmp/707098F6-00A2-4304-9939-D06912B1BBA7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 16:34:29.280 ThaliTest[844:1818653] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3186F1D9-1BAA-4C60-A0E0-C43160B370DE/Library/Cookies/Cookies.binarycookies
,2016-08-25 16:34:29.704 ThaliTest[844:1818653] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 16:34:29.706 ThaliTest[844:1818653] Multi-tasking -> Device: YES, App: YES
,2016-08-25 16:34:29.731 ThaliTest[844:1818653] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 16:34:31.440 ThaliTest[844:1818653] Using UIWebView
,2016-08-25 16:34:31.448 ThaliTest[844:1818653] [CDVTimer][handleopenurl] 0.433981ms
,2016-08-25 16:34:31.457 ThaliTest[844:1818653] [CDVTimer][intentandnavigationfilter] 8.202970ms
2016-08-25 16:34:31.458 ThaliTest[844:1818653] [CDVTimer][gesturehandler] 0.367999ms
2016-08-25 16:34:31.458 ThaliTest[844:1818653] [CDVTimer][TotalPluginStar,tup] 10.924041ms
,2016-08-25 16:34:37.273 ThaliTest[844:1818653] Resetting plugins due to page load.
,2016-08-25 16:34:40.091 ThaliTest[844:1818653] Finished load of: file:///var/mobile/Containers/Bundle/Application/EDFD11CE-8CD4-4C77-8532-16E2B1089AEE/ThaliTest.app/www/index.html
,2016-08-25 16:34:40.344 ThaliTest[844:1818653] JXcore Cordova plugin initializing
,2016-08-25 16:34:40.346 ThaliTest[844:1818865] JXcore instance initializing
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
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
