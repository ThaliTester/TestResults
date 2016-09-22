#### Test 855258872e8b4bc_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5DB2E808-D5B0-49D6-994F-BB42D0EA5A0B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5DB2E808-D5B0-49D6-994F-BB42D0EA5A0B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/755FF444-DED8-41CE-B534-FF94CBA5F8F9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49653"
,(lldb)     command script import "/tmp/5DB2E808-D5B0-49D6-994F-BB42D0EA5A0B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 13:33:05.568 ThaliTest[1181:1741480] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/915B7494-E5A7-43CB-B054-823AF78DAFEE/Library/Cookies/Cookies.binarycookies
,2016-09-22 13:33:05.610 ThaliTest[1181:1741480] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 13:33:05.611 ThaliTest[1181:1741480] Multi-tasking -> Device: YES, App: YES
,2016-09-22 13:33:05.623 ThaliTest[1181:1741480] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 13:33:05.938 ThaliTest[1181:1741480] Using UIWebView
2016-09-22 13:33:05.941 ThaliTest[1181:1741480] [CDVTimer][handleopenurl] 0.173986ms
2016-09-22 13:33:05.944 ThaliTest[1181:1741480] [CDVTimer][intentandnavigationfilter] 3.396988ms
2016-09,-22 13:33:05.945 ThaliTest[1181:1741480] [CDVTimer][gesturehandler] 0.138998ms
2016-09-22 13:33:05.945 ThaliTest[1181:1741480] [CDVTimer][TotalPluginStartup] 4.410028ms
,2016-09-22 13:33:11.200 ThaliTest[1181:1741480] Resetting plugins due to page load.
,2016-09-22 13:33:11.519 ThaliTest[1181:1741480] Finished load of: file:///var/containers/Bundle/Application/755FF444-DED8-41CE-B534-FF94CBA5F8F9/ThaliTest.app/www/index.html
,2016-09-22 13:33:11.879 ThaliTest[1181:1741480] JXcore Cordova plugin initializing
2016-09-22 13:33:11.880 ThaliTest[1181:1741650] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x141cb8c70>
,Optional("5850E643-A879-4AA3-90B8-52BC25BD50F9")
nil
,nil
,Optional("E34815E2-7528-44F7-9686-6DAB34DE4AB3")
,Optional("2F6CC974-53C3-4A99-8CFB-03E4917E2E46")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 13:33:34.196 ThaliTest[1181:1741480] BTM: attaching to BTServer
,2016-09-22 13:33:34.950 ThaliTest[1181:1741480] BTM: local device power state changed
2016-09-22 13:33:34.965 ThaliTest[1181:1741480] BTM: power is now on
,2016-09-22 13:33:39.685 ThaliTest[1181:1741480] BTM: local device power state changed
2016-09-22 13:33:39.688 ThaliTest[1181:1741480] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.41510003805161
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
