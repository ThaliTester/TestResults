#### Test 834526170a57107_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/834526170a57107/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A809FCD2-BED0-4AA7-B409-157715E47398/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A809FCD2-BED0-4AA7-B409-157715E47398/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/834526170a57107/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/834526170a57107/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BDA0C77E-7FA0-4729-A164-864C82F2C72D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64853"
,(lldb)     command script import "/tmp/A809FCD2-BED0-4AA7-B409-157715E47398/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 15:53:17.279 ThaliTest[941:1296719] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/539A30B1-E1C5-4710-897B-5C42274E6DBC/Library/Cookies/Cookies.binarycookies
,2016-08-31 15:53:17.669 ThaliTest[941:1296719] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 15:53:17.670 ThaliTest[941:1296719] Multi-tasking -> Device: YES, App: YES
,2016-08-31 15:53:17.693 ThaliTest[941:1296719] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 15:53:19.500 ThaliTest[941:1296719] Using UIWebView
,2016-08-31 15:53:19.507 ThaliTest[941:1296719] [CDVTimer][handleopenurl] 0.413001ms
,2016-08-31 15:53:19.514 ThaliTest[941:1296719] [CDVTimer][intentandnavigationfilter] 7.193983ms
2016-08-31 15:53:19.515 ThaliTest[941:1296719] [CDVTimer][gesturehandler] 0.367999ms
2016-08-31 15:53:19.516 ThaliTest[941:1296719] [CDVTimer][TotalPluginStar,tup] 9.590030ms
,2016-08-31 15:53:25.585 ThaliTest[941:1296719] Resetting plugins due to page load.
,2016-08-31 15:53:28.812 ThaliTest[941:1296719] Finished load of: file:///var/mobile/Containers/Bundle/Application/BDA0C77E-7FA0-4729-A164-864C82F2C72D/ThaliTest.app/www/index.html
,2016-08-31 15:53:29.038 ThaliTest[941:1296719] JXcore Cordova plugin initializing
,2016-08-31 15:53:29.040 ThaliTest[941:1296936] JXcore instance initializing
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
,Number of passed tests:  5
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.006479024887084961
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
