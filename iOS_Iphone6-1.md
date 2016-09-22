#### Test 85046911aad23fc_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911aad23fc/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9003A3ED-1B62-4FA7-82D5-D5E2D2B59C4D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9003A3ED-1B62-4FA7-82D5-D5E2D2B59C4D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911aad23fc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911aad23fc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/517DC152-0F3D-4E8D-BBE1-69777B45F8AF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59142"
,(lldb)     command script import "/tmp/9003A3ED-1B62-4FA7-82D5-D5E2D2B59C4D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 10:48:02.225 ThaliTest[1157:1724578] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/81801CDA-AEDA-4454-9707-E31B02E0099A/Library/Cookies/Cookies.binarycookies
,2016-09-22 10:48:02.313 ThaliTest[1157:1724578] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 10:48:02.316 ThaliTest[1157:1724578] Multi-tasking -> Device: YES, App: YES
,2016-09-22 10:48:02.333 ThaliTest[1157:1724578] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 10:48:02.783 ThaliTest[1157:1724578] Using UIWebView
,2016-09-22 10:48:02.790 ThaliTest[1157:1724578] [CDVTimer][handleopenurl] 0.388980ms
,2016-09-22 10:48:02.798 ThaliTest[1157:1724578] [CDVTimer][intentandnavigationfilter] 7.625997ms
2016-09-22 10:48:02.799 ThaliTest[1157:1724578] [CDVTimer][gesturehandler] 0.311017ms
2016-09-22 10:48:02.799 ThaliTest[1157:1724578] [CDVTimer][TotalPluginStartup] 9.947002ms
,2016-09-22 10:48:08.319 ThaliTest[1157:1724578] Resetting plugins due to page load.
,2016-09-22 10:48:08.675 ThaliTest[1157:1724578] Finished load of: file:///var/containers/Bundle/Application/517DC152-0F3D-4E8D-BBE1-69777B45F8AF/ThaliTest.app/www/index.html
,2016-09-22 10:48:09.003 ThaliTest[1157:1724578] JXcore Cordova plugin initializing
,2016-09-22 10:48:09.004 ThaliTest[1157:1724741] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 10:48:16.577 ThaliTest[1157:1724578] BTM: attaching to BTServer
,2016-09-22 10:48:17.320 ThaliTest[1157:1724578] BTM: local device power state changed
2016-09-22 10:48:17.345 ThaliTest[1157:1724578] BTM: power is now on
,2016-09-22 10:48:22.054 ThaliTest[1157:1724578] BTM: local device power state changed
2016-09-22 10:48:22.055 ThaliTest[1157:1724578] BTM: power is now off
,received session: <ThaliCore.Session: 0x14560ee40>
,Optional("997602E3-3FE3-4F1C-BE62-B854BBB7DFC2")
nil
,nil
,Optional("F2FCBB39-A948-456A-A36B-6C35BA3CB0CE")
,Optional("F56363FA-3D79-4810-9273-E26F0FC68A1A")
,*Native tests were executed*
,Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  21.46367698907852
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
