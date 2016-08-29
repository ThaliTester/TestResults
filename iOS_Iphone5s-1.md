#### Test 829140738625595_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140738625595/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1C7D976A-355A-4DEF-95DB-20E77016BA54/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1C7D976A-355A-4DEF-95DB-20E77016BA54/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140738625595/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140738625595/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/25489939-00A3-45AD-83E0-9497BBC85DA3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55091"
,(lldb)     command script import "/tmp/1C7D976A-355A-4DEF-95DB-20E77016BA54/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 11:05:03.387 ThaliTest[1132:2375461] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DFFD58CB-489F-4440-8170-F04114E65551/Library/Cookies/Cookies.binarycookies
,2016-08-29 11:05:03.791 ThaliTest[1132:2375461] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 11:05:03.792 ThaliTest[1132:2375461] Multi-tasking -> Device: YES, App: YES
,2016-08-29 11:05:03.816 ThaliTest[1132:2375461] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 11:05:05.694 ThaliTest[1132:2375461] Using UIWebView
,2016-08-29 11:05:05.705 ThaliTest[1132:2375461] [CDVTimer][handleopenurl] 0.438035ms
,2016-08-29 11:05:05.713 ThaliTest[1132:2375461] [CDVTimer][intentandnavigationfilter] 8.073986ms
2016-08-29 11:05:05.714 ThaliTest[1132:2375461] [CDVTimer][gesturehandler] 0.389993ms
2016-08-29 11:05:05.715 ThaliTest[1132:2375461] [CDVTimer][TotalPluginS,tartup] 10.839045ms
,2016-08-29 11:05:12.250 ThaliTest[1132:2375461] Resetting plugins due to page load.
,2016-08-29 11:05:15.725 ThaliTest[1132:2375461] Finished load of: file:///var/mobile/Containers/Bundle/Application/25489939-00A3-45AD-83E0-9497BBC85DA3/ThaliTest.app/www/index.html
,2016-08-29 11:05:15.996 ThaliTest[1132:2375461] JXcore Cordova plugin initializing
,2016-08-29 11:05:15.997 ThaliTest[1132:2375724] JXcore instance initializing
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
,Total number of executed tests:  20
Number of passed tests:  20
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  44.19237196445465
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
