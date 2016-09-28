#### Test 85046911920cb66_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C175FB83-8FA8-4F70-B3B3-A25BD57911A0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C175FB83-8FA8-4F70-B3B3-A25BD57911A0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/59B2BD10-11DC-40EC-A94B-02169BD0F056/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61278"
,(lldb)     command script import "/tmp/C175FB83-8FA8-4F70-B3B3-A25BD57911A0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-28 10:04:37.418 ThaliTest[1595:2493467] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2DD5098B-D709-4D9C-B76E-C1C6FED42B82/Library/Cookies/Cookies.binarycookies
,2016-09-28 10:04:37.487 ThaliTest[1595:2493467] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 10:04:37.489 ThaliTest[1595:2493467] Multi-tasking -> Device: YES, App: YES
,2016-09-28 10:04:37.508 ThaliTest[1595:2493467] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 10:04:37.949 ThaliTest[1595:2493467] Using UIWebView
,2016-09-28 10:04:37.959 ThaliTest[1595:2493467] [CDVTimer][handleopenurl] 0.382006ms
,2016-09-28 10:04:37.966 ThaliTest[1595:2493467] [CDVTimer][intentandnavigationfilter] 6.954968ms
2016-09-28 10:04:37.967 ThaliTest[1595:2493467] [CDVTimer][gesturehandler] 0.292003ms
2016-09-28 10:04:37.967 ThaliTest[1595:2493467] [CDVTimer][TotalPluginS,tartup] 9.281993ms
,2016-09-28 10:04:43.127 ThaliTest[1595:2493467] Resetting plugins due to page load.
,2016-09-28 10:04:43.483 ThaliTest[1595:2493467] Finished load of: file:///var/containers/Bundle/Application/59B2BD10-11DC-40EC-A94B-02169BD0F056/ThaliTest.app/www/index.html
,2016-09-28 10:04:43.813 ThaliTest[1595:2493467] JXcore Cordova plugin initializing
,2016-09-28 10:04:43.814 ThaliTest[1595:2493634] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x14668b1f0>
,Optional("5233E5F8-899B-477B-AB4B-5DE864F90E72")
,nil
,nil
,Optional("CDE8ACC8-B145-4602-8A42-F05642B5D05A")
,Optional("559365AC-C0CB-458F-8A31-FDD8AAE7901C")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.33661097288132
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
