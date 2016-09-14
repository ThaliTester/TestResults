#### Test 82914073cc2505e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1F28F426-B928-4FB8-98A0-99FC992104CD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1F28F426-B928-4FB8-98A0-99FC992104CD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9B3CD822-7EC6-4003-B345-A09AE9B4109B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50223"
,(lldb)     command script import "/tmp/1F28F426-B928-4FB8-98A0-99FC992104CD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 23:40:21.330 ThaliTest[2287:4798935] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/01AA035E-601A-41F5-BB20-4EAB55DCB029/Library/Cookies/Cookies.binarycookies
,2016-09-14 23:40:21.447 ThaliTest[2287:4798935] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 23:40:21.448 ThaliTest[2287:4798935] Multi-tasking -> Device: YES, App: YES
,2016-09-14 23:40:21.472 ThaliTest[2287:4798935] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 23:40:23.175 ThaliTest[2287:4798935] Using UIWebView
,2016-09-14 23:40:23.184 ThaliTest[2287:4798935] [CDVTimer][handleopenurl] 0.522017ms
,2016-09-14 23:40:23.193 ThaliTest[2287:4798935] [CDVTimer][intentandnavigationfilter] 8.144021ms
2016-09-14 23:40:23.194 ThaliTest[2287:4798935] [CDVTimer][gesturehandler] 0.360966ms
2016-09-14 23:40:23.194 ThaliTest[2287:4798935] [CDVTimer][TotalPluginS,tartup] 11.498988ms
,2016-09-14 23:40:30.579 ThaliTest[2287:4798935] Resetting plugins due to page load.
,2016-09-14 23:40:34.476 ThaliTest[2287:4798935] Finished load of: file:///var/mobile/Containers/Bundle/Application/9B3CD822-7EC6-4003-B345-A09AE9B4109B/ThaliTest.app/www/index.html
,2016-09-14 23:40:34.793 ThaliTest[2287:4798935] JXcore Cordova plugin initializing
,2016-09-14 23:40:34.794 ThaliTest[2287:4799166] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 23:40:43.858 ThaliTest[2287:4798935] BTM: attaching to BTServer
,2016-09-14 23:40:48.467 ThaliTest[2287:4798935] BTM: local device power state changed
2016-09-14 23:40:48.468 ThaliTest[2287:4798935] BTM: power is now off
,2016-09-14 23:40:49.160 ThaliTest[2287:4798935] BTM: local device power state changed
2016-09-14 23:40:49.161 ThaliTest[2287:4798935] BTM: power is now on
,received session: <ThaliCore.Session: 0x13019fd90>
,*Native tests were executed*
,Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  16.2722589969635
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
