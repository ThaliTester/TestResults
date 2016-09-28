#### Test 87126746a66927d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E4E1F512-AFD7-4E8D-BDCF-2DBD902B10EE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E4E1F512-AFD7-4E8D-BDCF-2DBD902B10EE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7170EB93-F4F3-4F89-8289-F7D5821D82B5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54537"
,(lldb)     command script import "/tmp/E4E1F512-AFD7-4E8D-BDCF-2DBD902B10EE/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 16:30:25.089 ThaliTest[1621:2529592] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/29144FED-3B60-4A76-B666-5C42A0F5FC30/Library/Cookies/Cookies.binarycookies
,2016-09-28 16:30:25.164 ThaliTest[1621:2529592] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 16:30:25.165 ThaliTest[1621:2529592] Multi-tasking -> Device: YES, App: YES
,2016-09-28 16:30:25.181 ThaliTest[1621:2529592] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 16:30:25.612 ThaliTest[1621:2529592] Using UIWebView
,2016-09-28 16:30:25.619 ThaliTest[1621:2529592] [CDVTimer][handleopenurl] 0.585973ms
,2016-09-28 16:30:25.626 ThaliTest[1621:2529592] [CDVTimer][intentandnavigationfilter] 6.875038ms
2016-09-28 16:30:25.627 ThaliTest[1621:2529592] [CDVTimer][gesturehandler] 0.263989ms
2016-09-28 16:30:25.627 ThaliTest[1621:2529592] [CDVTimer][TotalPluginS,tartup] 9.265006ms
,2016-09-28 16:30:31.093 ThaliTest[1621:2529592] Resetting plugins due to page load.
,2016-09-28 16:30:31.467 ThaliTest[1621:2529592] Finished load of: file:///var/containers/Bundle/Application/7170EB93-F4F3-4F89-8289-F7D5821D82B5/ThaliTest.app/www/index.html
,2016-09-28 16:30:31.803 ThaliTest[1621:2529592] JXcore Cordova plugin initializing
,2016-09-28 16:30:31.804 ThaliTest[1621:2529766] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x138cded60>
,Optional("97A81095-6C19-4546-8487-9DD0B63A4E6B")
nil
,nil
,Optional("339E1DE1-C296-485D-A1E8-2B2D4E99E473")
,Optional("30B0042F-C2C5-4A97-BB0A-8DE3FC469DEB")
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.35743099451065
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
