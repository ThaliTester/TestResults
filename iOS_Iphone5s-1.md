#### Test 86453613e903f38_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86453613e903f38/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AC5B2128-1347-4170-9B1E-F064B2F76397/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AC5B2128-1347-4170-9B1E-F064B2F76397/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86453613e903f38/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86453613e903f38/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0F1D7EA2-347A-4C32-B8D9-DBC89E38E74F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58964"
,(lldb)     command script import "/tmp/AC5B2128-1347-4170-9B1E-F064B2F76397/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 08:07:21.136 ThaliTest[2998:6103498] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7504EA4B-2C79-49A4-9E69-60F1CCE6AC1E/Library/Cookies/Cookies.binarycookies
,2016-09-23 08:07:21.259 ThaliTest[2998:6103498] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 08:07:21.261 ThaliTest[2998:6103498] Multi-tasking -> Device: YES, App: YES
,2016-09-23 08:07:21.289 ThaliTest[2998:6103498] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 08:07:22.781 ThaliTest[2998:6103498] Using UIWebView
,2016-09-23 08:07:22.789 ThaliTest[2998:6103498] [CDVTimer][handleopenurl] 0.488997ms
,2016-09-23 08:07:22.798 ThaliTest[2998:6103498] [CDVTimer][intentandnavigationfilter] 8.732021ms
2016-09-23 08:07:22.799 ThaliTest[2998:6103498] [CDVTimer][gesturehandler] 0.400007ms
2016-09-23 08:07:22.800 ThaliTest[2998:6103498] [CDVTimer][TotalPluginS,tartup] 11.641979ms
,2016-09-23 08:07:28.490 ThaliTest[2998:6103498] Resetting plugins due to page load.
,2016-09-23 08:07:31.939 ThaliTest[2998:6103498] Finished load of: file:///var/mobile/Containers/Bundle/Application/0F1D7EA2-347A-4C32-B8D9-DBC89E38E74F/ThaliTest.app/www/index.html
,2016-09-23 08:07:32.248 ThaliTest[2998:6103498] JXcore Cordova plugin initializing
,2016-09-23 08:07:32.249 ThaliTest[2998:6103716] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x1404ec170>
,Optional("054A5903-0918-478C-B246-2E59831C3ED7")
,nil
,nil
,Optional("F51CA27F-4956-4A3E-90C2-3B87E4D37433")
,Optional("4DD0D360-D659-4326-8B37-BAF07AEE8A11")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 08:07:56.745 ThaliTest[2998:6103498] BTM: attaching to BTServer
,2016-09-23 08:07:57.435 ThaliTest[2998:6103498] BTM: local device power state changed
2016-09-23 08:07:57.437 ThaliTest[2998:6103498] BTM: power is now on
,2016-09-23 08:08:02.166 ThaliTest[2998:6103498] BTM: local device power state changed
2016-09-23 08:08:02.170 ThaliTest[2998:6103498] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.97387301921844
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered

```
