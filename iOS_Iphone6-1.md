#### Test 864536137cfe9e7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9266544F-F600-4F87-A652-A0134AE3A500/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9266544F-F600-4F87-A652-A0134AE3A500/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4AE4AC5F-0AF4-4B23-9644-B1567470B0DA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57186"
,(lldb)     command script import "/tmp/9266544F-F600-4F87-A652-A0134AE3A500/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 07:38:33.132 ThaliTest[1234:1838849] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2717A7A8-C1F3-4083-963F-FE8FB550E342/Library/Cookies/Cookies.binarycookies
,2016-09-23 07:38:33.202 ThaliTest[1234:1838849] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 07:38:33.204 ThaliTest[1234:1838849] Multi-tasking -> Device: YES, App: YES
,2016-09-23 07:38:33.221 ThaliTest[1234:1838849] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 07:38:33.720 ThaliTest[1234:1838849] Using UIWebView
,2016-09-23 07:38:33.730 ThaliTest[1234:1838849] [CDVTimer][handleopenurl] 0.436008ms
,2016-09-23 07:38:33.738 ThaliTest[1234:1838849] [CDVTimer][intentandnavigationfilter] 7.048011ms
2016-09-23 07:38:33.738 ThaliTest[1234:1838849] [CDVTimer][gesturehandler] 0.271976ms
2016-09-23 07:38:33.739 ThaliTest[1234:1838849] [CDVTimer][TotalPluginS,tartup] 9.397984ms
,2016-09-23 07:38:38.838 ThaliTest[1234:1838849] Resetting plugins due to page load.
,2016-09-23 07:38:39.201 ThaliTest[1234:1838849] Finished load of: file:///var/containers/Bundle/Application/4AE4AC5F-0AF4-4B23-9644-B1567470B0DA/ThaliTest.app/www/index.html
,2016-09-23 07:38:39.531 ThaliTest[1234:1838849] JXcore Cordova plugin initializing
2016-09-23 07:38:39.532 ThaliTest[1234:1839035] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x13db89080>
,Optional("6DBC7BDC-657C-45B6-8701-79FCB136DE08")
nil
,nil
,Optional("83FE692D-047B-4BBA-88D4-C37CB9215141")
,Optional("F0DD955E-96F6-4753-B79E-A60D4A8AA963")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-23 07:39:01.259 ThaliTest[1234:1838849] BTM: attaching to BTServer
,2016-09-23 07:39:02.037 ThaliTest[1234:1838849] BTM: local device power state changed
2016-09-23 07:39:02.037 ThaliTest[1234:1838849] BTM: power is now on
,2016-09-23 07:39:06.753 ThaliTest[1234:1838849] BTM: local device power state changed
2016-09-23 07:39:06.753 ThaliTest[1234:1838849] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  19.74226701259613
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
