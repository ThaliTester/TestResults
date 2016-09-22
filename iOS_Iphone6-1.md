#### Test 85046911aebbc53_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911aebbc53/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/692EF4AE-BF3F-4FD5-9E92-8C4E6F9A5914/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/692EF4AE-BF3F-4FD5-9E92-8C4E6F9A5914/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911aebbc53/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911aebbc53/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/33F628C3-DAE1-49A8-B642-7F9BB554D48C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53431"
,(lldb)     command script import "/tmp/692EF4AE-BF3F-4FD5-9E92-8C4E6F9A5914/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 09:43:28.957 ThaliTest[1125:1714956] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E7790DA3-A4FA-49D9-BF92-4B426C5FF30B/Library/Cookies/Cookies.binarycookies
,2016-09-22 09:43:28.998 ThaliTest[1125:1714956] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 09:43:28.999 ThaliTest[1125:1714956] Multi-tasking -> Device: YES, App: YES
,2016-09-22 09:43:29.011 ThaliTest[1125:1714956] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 09:43:29.328 ThaliTest[1125:1714956] Using UIWebView
,2016-09-22 09:43:29.332 ThaliTest[1125:1714956] [CDVTimer][handleopenurl] 0.196993ms
,2016-09-22 09:43:29.336 ThaliTest[1125:1714956] [CDVTimer][intentandnavigationfilter] 3.582001ms
2016-09-22 09:43:29.336 ThaliTest[1125:1714956] [CDVTimer][gesturehandler] 0.160992ms
2016-09-22 09:43:29.336 ThaliTest[1125:1714956] [CDVTimer][TotalPluginS,tartup] 4.727006ms
,2016-09-22 09:43:34.432 ThaliTest[1125:1714956] Resetting plugins due to page load.
,2016-09-22 09:43:34.794 ThaliTest[1125:1714956] Finished load of: file:///var/containers/Bundle/Application/33F628C3-DAE1-49A8-B642-7F9BB554D48C/ThaliTest.app/www/index.html
,2016-09-22 09:43:35.125 ThaliTest[1125:1714956] JXcore Cordova plugin initializing
,2016-09-22 09:43:35.125 ThaliTest[1125:1715129] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x14f083690>
,Optional("62B84CF2-9540-4C03-BA85-CC01A6B6EE34")
,nil
,nil
,Optional("1D462552-963B-49FC-B9C8-8B96677FCEE5")
,Optional("D76467B1-13B4-4883-A189-8AA48581A37E")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 09:43:57.019 ThaliTest[1125:1714956] BTM: attaching to BTServer
,2016-09-22 09:43:57.769 ThaliTest[1125:1714956] BTM: local device power state changed
2016-09-22 09:43:57.770 ThaliTest[1125:1714956] BTM: power is now on
,2016-09-22 09:44:02.524 ThaliTest[1125:1714956] BTM: local device power state changed
2016-09-22 09:44:02.525 ThaliTest[1125:1714956] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  19.7798810005188
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
