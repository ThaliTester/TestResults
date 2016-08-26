#### Test 79896569fbe8035_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79896569fbe8035/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7051F3E4-A8F6-41F5-A69A-674916402906/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7051F3E4-A8F6-41F5-A69A-674916402906/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79896569fbe8035/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79896569fbe8035/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/340A5001-E5DD-45E4-85A1-969B11904DF6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59869"
,(lldb)     command script import "/tmp/7051F3E4-A8F6-41F5-A69A-674916402906/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 21:51:53.249 ThaliTest[601:627393] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/64DAF837-74C9-4BAA-8479-4A112B873F52/Library/Cookies/Cookies.binarycookies
,2016-08-26 21:51:53.603 ThaliTest[601:627393] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 21:51:53.604 ThaliTest[601:627393] Multi-tasking -> Device: YES, App: YES
,2016-08-26 21:51:53.626 ThaliTest[601:627393] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 21:51:55.511 ThaliTest[601:627393] Using UIWebView
,2016-08-26 21:51:55.518 ThaliTest[601:627393] [CDVTimer][handleopenurl] 0.513971ms
,2016-08-26 21:51:55.525 ThaliTest[601:627393] [CDVTimer][intentandnavigationfilter] 7.266998ms
2016-08-26 21:51:55.526 ThaliTest[601:627393] [CDVTimer][gesturehandler] 0.378013ms
2016-08-26 21:51:55.527 ThaliTest[601:627393] [CDVTimer][TotalPluginStartup] 9.783983ms
,2016-08-26 21:52:01.781 ThaliTest[601:627393] Resetting plugins due to page load.
,2016-08-26 21:52:04.829 ThaliTest[601:627393] Finished load of: file:///var/mobile/Containers/Bundle/Application/340A5001-E5DD-45E4-85A1-969B11904DF6/ThaliTest.app/www/index.html
,2016-08-26 21:52:05.075 ThaliTest[601:627393] JXcore Cordova plugin initializing
,2016-08-26 21:52:05.076 ThaliTest[601:627622] JXcore instance initializing
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
Number of ignored tests:  0
,Total duration:  0.006062030792236328
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
