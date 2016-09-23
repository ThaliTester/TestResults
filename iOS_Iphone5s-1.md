#### Test 85046911dcbf444_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A575853B-62F1-41DB-B935-966D1CFA45D9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A575853B-62F1-41DB-B935-966D1CFA45D9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/73397BF3-E4F6-4765-A32B-80D4D998757A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61772"
,(lldb)     command script import "/tmp/A575853B-62F1-41DB-B935-966D1CFA45D9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 08:39:30.843 ThaliTest[3013:6108601] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5D8A0D4F-A2AC-4D9C-B636-4D33DF312ACB/Library/Cookies/Cookies.binarycookies
,2016-09-23 08:39:30.962 ThaliTest[3013:6108601] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 08:39:30.963 ThaliTest[3013:6108601] Multi-tasking -> Device: YES, App: YES
,2016-09-23 08:39:30.984 ThaliTest[3013:6108601] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 08:39:32.473 ThaliTest[3013:6108601] Using UIWebView
,2016-09-23 08:39:32.481 ThaliTest[3013:6108601] [CDVTimer][handleopenurl] 0.494003ms
,2016-09-23 08:39:32.490 ThaliTest[3013:6108601] [CDVTimer][intentandnavigationfilter] 8.177042ms
2016-09-23 08:39:32.491 ThaliTest[3013:6108601] [CDVTimer][gesturehandler] 0.541031ms
2016-09-23 08:39:32.492 ThaliTest[3013:6108601] [CDVTimer][TotalPluginS,tartup] 11.412978ms
,2016-09-23 08:39:39.352 ThaliTest[3013:6108601] Resetting plugins due to page load.
,2016-09-23 08:39:43.067 ThaliTest[3013:6108601] Finished load of: file:///var/mobile/Containers/Bundle/Application/73397BF3-E4F6-4765-A32B-80D4D998757A/ThaliTest.app/www/index.html
,2016-09-23 08:39:43.387 ThaliTest[3013:6108601] JXcore Cordova plugin initializing
2016-09-23 08:39:43.388 ThaliTest[3013:6108828] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 08:39:52.392 ThaliTest[3013:6108601] BTM: attaching to BTServer
,2016-09-23 08:39:53.176 ThaliTest[3013:6108601] BTM: local device power state changed
2016-09-23 08:39:53.176 ThaliTest[3013:6108601] BTM: power is now on
,2016-09-23 08:39:57.910 ThaliTest[3013:6108601] BTM: local device power state changed
2016-09-23 08:39:57.910 ThaliTest[3013:6108601] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  7
Number of passed tests:  7
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  5.712478041648865
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
