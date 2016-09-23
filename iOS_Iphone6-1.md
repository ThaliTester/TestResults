#### Test 8326889395f7d73_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889395f7d73/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/88041ABD-1636-4095-BAFC-75B098CC8469/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/88041ABD-1636-4095-BAFC-75B098CC8469/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889395f7d73/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889395f7d73/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/EBE6F1E7-13B9-4473-9240-611BCE739451/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59695"
,(lldb)     command script import "/tmp/88041ABD-1636-4095-BAFC-75B098CC8469/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 12:55:37.910 ThaliTest[1307:1875333] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3F53BA7E-602E-43E7-A6F8-B2DE2B9DD2B9/Library/Cookies/Cookies.binarycookies
,2016-09-23 12:55:37.948 ThaliTest[1307:1875333] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 12:55:37.948 ThaliTest[1307:1875333] Multi-tasking -> Device: YES, App: YES
,2016-09-23 12:55:37.958 ThaliTest[1307:1875333] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 12:55:38.317 ThaliTest[1307:1875333] Using UIWebView
,2016-09-23 12:55:38.322 ThaliTest[1307:1875333] [CDVTimer][handleopenurl] 0.239015ms
,2016-09-23 12:55:38.327 ThaliTest[1307:1875333] [CDVTimer][intentandnavigationfilter] 4.844964ms
2016-09-23 12:55:38.327 ThaliTest[1307:1875333] [CDVTimer][gesturehandler] 0.202000ms
2016-09-23 12:55:38.328 ThaliTest[1307:1875333] [CDVTimer][TotalPluginS,tartup] 6.416976ms
,2016-09-23 12:55:43.665 ThaliTest[1307:1875333] Resetting plugins due to page load.
,2016-09-23 12:55:44.037 ThaliTest[1307:1875333] Finished load of: file:///var/containers/Bundle/Application/EBE6F1E7-13B9-4473-9240-611BCE739451/ThaliTest.app/www/index.html
,2016-09-23 12:55:44.367 ThaliTest[1307:1875333] JXcore Cordova plugin initializing
,2016-09-23 12:55:44.368 ThaliTest[1307:1875505] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x138e15410>
,Optional("C28E800A-8A61-4413-BC83-7B0366AAAEA1")
nil
,nil
,Optional("7989349B-DAE3-4A82-B777-87FF5E456668")
,Optional("DF8EB97B-CA12-4356-B97A-16115730D177")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-23 12:56:06.319 ThaliTest[1307:1875333] BTM: attaching to BTServer
,2016-09-23 12:56:07.061 ThaliTest[1307:1875333] BTM: local device power state changed
2016-09-23 12:56:07.063 ThaliTest[1307:1875333] BTM: power is now on
,2016-09-23 12:56:11.755 ThaliTest[1307:1875333] BTM: local device power state changed
2016-09-23 12:56:11.756 ThaliTest[1307:1875333] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  20.02153700590134
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
