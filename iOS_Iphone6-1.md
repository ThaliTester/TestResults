#### Test 8621445004dab41_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8621445004dab41/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4691C971-0038-4AE2-ABF9-186A74E6ACB1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4691C971-0038-4AE2-ABF9-186A74E6ACB1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8621445004dab41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8621445004dab41/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/ECB2EF09-1719-4F7B-976B-B4D38D2ADEB3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49735"
,(lldb)     command script import "/tmp/4691C971-0038-4AE2-ABF9-186A74E6ACB1/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 01:03:38.264 ThaliTest[1096:1670447] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/77FE53D2-2AB6-498F-8272-F5FECFFE5CAF/Library/Cookies/Cookies.binarycookies
,2016-09-22 01:03:38.306 ThaliTest[1096:1670447] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 01:03:38.307 ThaliTest[1096:1670447] Multi-tasking -> Device: YES, App: YES
,2016-09-22 01:03:38.319 ThaliTest[1096:1670447] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 01:03:38.621 ThaliTest[1096:1670447] Using UIWebView
,2016-09-22 01:03:38.624 ThaliTest[1096:1670447] [CDVTimer][handleopenurl] 0.188053ms
,2016-09-22 01:03:38.628 ThaliTest[1096:1670447] [CDVTimer][intentandnavigationfilter] 3.436029ms
2016-09-22 01:03:38.629 ThaliTest[1096:1670447] [CDVTimer][gesturehandler] 0.150025ms
2016-09-22 01:03:38.629 ThaliTest[1096:1670447] [CDVTimer][TotalPluginS,tartup] 4.601002ms
,2016-09-22 01:03:43.834 ThaliTest[1096:1670447] Resetting plugins due to page load.
,2016-09-22 01:03:44.227 ThaliTest[1096:1670447] Finished load of: file:///var/containers/Bundle/Application/ECB2EF09-1719-4F7B-976B-B4D38D2ADEB3/ThaliTest.app/www/index.html
,2016-09-22 01:03:44.557 ThaliTest[1096:1670447] JXcore Cordova plugin initializing
,2016-09-22 01:03:44.558 ThaliTest[1096:1670619] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x13f6a2660>
,Optional("A1C00754-A62A-4BCE-87D5-6501DA6BA4B3")
nil
,nil
,Optional("D00D10A5-4B9E-4D70-AFD3-541F30FAF006")
,Optional("92C3DD47-6D7E-4774-AA2E-6A85E810F1AC")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 01:04:06.588 ThaliTest[1096:1670447] BTM: attaching to BTServer
,2016-09-22 01:04:07.359 ThaliTest[1096:1670447] BTM: local device power state changed
2016-09-22 01:04:07.359 ThaliTest[1096:1670447] BTM: power is now on
,2016-09-22 01:04:12.062 ThaliTest[1096:1670447] BTM: local device power state changed
2016-09-22 01:04:12.063 ThaliTest[1096:1670447] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.09125804901123
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered

```
