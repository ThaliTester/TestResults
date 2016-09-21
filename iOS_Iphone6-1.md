#### Test 83268893ec4b63c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D18741EF-97E8-4241-A084-C0614856F229/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
Executing commands in '/tmp/D18741EF-97E8-4241-A084-C0614856F229/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E617F59A-07B2-48C8-98A4-EEEEE629F881/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63809"
,(lldb)     command script import "/tmp/D18741EF-97E8-4241-A084-C0614856F229/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 16:48:05.858 ThaliTest[1062:1625058] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8B580AA8-1E40-4E09-B773-35B795FD01A1/Library/Cookies/Cookies.binarycookies
,2016-09-21 16:48:05.896 ThaliTest[1062:1625058] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 16:48:05.897 ThaliTest[1062:1625058] Multi-tasking -> Device: YES, App: YES
,2016-09-21 16:48:05.908 ThaliTest[1062:1625058] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 16:48:06.212 ThaliTest[1062:1625058] Using UIWebView
,2016-09-21 16:48:06.216 ThaliTest[1062:1625058] [CDVTimer][handleopenurl] 0.169992ms
,2016-09-21 16:48:06.220 ThaliTest[1062:1625058] [CDVTimer][intentandnavigationfilter] 3.450990ms
,2016-09-21 16:48:06.220 ThaliTest[1062:1625058] [CDVTimer][gesturehandler] 0.308037ms
,2016-09-21 16:48:06.220 ThaliTest[1062:1625058] [CDVTimer][TotalPluginStartup] 4.858017ms
,2016-09-21 16:48:11.608 ThaliTest[1062:1625058] Resetting plugins due to page load.
,2016-09-21 16:48:11.989 ThaliTest[1062:1625058] Finished load of: file:///var/containers/Bundle/Application/E617F59A-07B2-48C8-98A4-EEEEE629F881/ThaliTest.app/www/index.html
,2016-09-21 16:48:12.320 ThaliTest[1062:1625058] JXcore Cordova plugin initializing
,2016-09-21 16:48:12.321 ThaliTest[1062:1625224] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1386407d0>
,Optional("9E6DFCC2-E412-467C-90E5-61EE6EFDEA46")
nil
,nil
,Optional("0DB8150F-4004-4584-9D87-A6E9FCFB255D")
,Optional("71F34488-7C9A-4456-B04E-2D7F03DE170E")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-21 16:48:33.319 ThaliTest[1062:1625058] BTM: attaching to BTServer
,2016-09-21 16:48:34.102 ThaliTest[1062:1625058] BTM: local device power state changed
2016-09-21 16:48:34.114 ThaliTest[1062:1625058] BTM: power is now on
,2016-09-21 16:48:38.833 ThaliTest[1062:1625058] BTM: local device power state changed
2016-09-21 16:48:38.833 ThaliTest[1062:1625058] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  19.09366601705551
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered

```
