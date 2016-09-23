#### Test 86482582895a768_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86482582895a768/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DF13F20F-92E3-465D-9DBC-F1E3BAC67CEB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DF13F20F-92E3-465D-9DBC-F1E3BAC67CEB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86482582895a768/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86482582895a768/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D07529F3-4379-4548-8439-2ED50205DDE5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62782"
,(lldb)     command script import "/tmp/DF13F20F-92E3-465D-9DBC-F1E3BAC67CEB/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 16:58:12.704 ThaliTest[1351:1901172] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9B6A0FCB-FB73-4913-A6FE-A5436C62B7A9/Library/Cookies/Cookies.binarycookies
,2016-09-23 16:58:12.768 ThaliTest[1351:1901172] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 16:58:12.769 ThaliTest[1351:1901172] Multi-tasking -> Device: YES, App: YES
,2016-09-23 16:58:12.785 ThaliTest[1351:1901172] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 16:58:13.202 ThaliTest[1351:1901172] Using UIWebView
,2016-09-23 16:58:13.209 ThaliTest[1351:1901172] [CDVTimer][handleopenurl] 0.536978ms
,2016-09-23 16:58:13.216 ThaliTest[1351:1901172] [CDVTimer][intentandnavigationfilter] 6.889999ms
2016-09-23 16:58:13.217 ThaliTest[1351:1901172] [CDVTimer][gesturehandler] 0.333011ms
2016-09-23 16:58:13.217 ThaliTest[1351:1901172] [CDVTimer][TotalPluginS,tartup] 9.433031ms
,2016-09-23 16:58:18.574 ThaliTest[1351:1901172] Resetting plugins due to page load.
,2016-09-23 16:58:18.937 ThaliTest[1351:1901172] Finished load of: file:///var/containers/Bundle/Application/D07529F3-4379-4548-8439-2ED50205DDE5/ThaliTest.app/www/index.html
,2016-09-23 16:58:19.266 ThaliTest[1351:1901172] JXcore Cordova plugin initializing
2016-09-23 16:58:19.267 ThaliTest[1351:1901334] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 16:58:26.844 ThaliTest[1351:1901172] BTM: attaching to BTServer
,2016-09-23 16:58:27.570 ThaliTest[1351:1901172] BTM: local device power state changed
2016-09-23 16:58:27.571 ThaliTest[1351:1901172] BTM: power is now on
,2016-09-23 16:58:32.302 ThaliTest[1351:1901172] BTM: local device power state changed
2016-09-23 16:58:32.307 ThaliTest[1351:1901172] BTM: power is now off
,received session: <ThaliCore.Session: 0x159c796e0>
,Optional("E2CB958A-9C24-46C2-9D3A-11064E1C710A")
nil
,nil
,Optional("12A47C29-56E9-493E-8A4B-B0C3FB59DDA1")
,Optional("6418C1B8-2364-45CE-95BD-133F333CA63D")
,*Native tests were executed*
,Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  20.08376199007034
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
