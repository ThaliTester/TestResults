#### Test 832688934d87cf0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832688934d87cf0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C01DE496-67A2-41A4-98BF-1A6BB7D66DE0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C01DE496-67A2-41A4-98BF-1A6BB7D66DE0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/832688934d87cf0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832688934d87cf0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/90976D49-2428-48F6-9481-292FFB40457C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59619"
,(lldb)     command script import "/tmp/C01DE496-67A2-41A4-98BF-1A6BB7D66DE0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 14:30:09.892 ThaliTest[966:1483087] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/645318C3-DA55-470F-B150-A6BBE29976DE/Library/Cookies/Cookies.binarycookies
,2016-09-20 14:30:09.976 ThaliTest[966:1483087] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 14:30:09.980 ThaliTest[966:1483087] Multi-tasking -> Device: YES, App: YES
,2016-09-20 14:30:10.003 ThaliTest[966:1483087] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 14:30:10.491 ThaliTest[966:1483087] Using UIWebView
,2016-09-20 14:30:10.498 ThaliTest[966:1483087] [CDVTimer][handleopenurl] 0.328004ms
,2016-09-20 14:30:10.506 ThaliTest[966:1483087] [CDVTimer][intentandnavigationfilter] 7.268012ms
2016-09-20 14:30:10.507 ThaliTest[966:1483087] [CDVTimer][gesturehandler] 0.320017ms
2016-09-20 14:30:10.507 ThaliTest[966:1483087] [CDVTimer][TotalPluginStartup] 9.585977ms
,2016-09-20 14:30:15.727 ThaliTest[966:1483087] Resetting plugins due to page load.
,2016-09-20 14:30:16.121 ThaliTest[966:1483087] Finished load of: file:///var/containers/Bundle/Application/90976D49-2428-48F6-9481-292FFB40457C/ThaliTest.app/www/index.html
,2016-09-20 14:30:16.475 ThaliTest[966:1483087] JXcore Cordova plugin initializing
,2016-09-20 14:30:16.475 ThaliTest[966:1483247] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-20 14:30:24.030 ThaliTest[966:1483087] BTM: attaching to BTServer
,2016-09-20 14:30:35.267 ThaliTest[966:1483087] BTM: local device power state changed
2016-09-20 14:30:35.268 ThaliTest[966:1483087] BTM: power is now off
,received session: <ThaliCore.Session: 0x1572ccad0>
,7F9408D1-908A-4DDE-AECF-4E442537E187
,Optional("7F9408D1-908A-4DDE-AECF-4E442537E187")
nil
,nil

,D3EE8CD1-6E9E-4A67-BC51-4535677C0CA9
,Optional("D3EE8CD1-6E9E-4A67-BC51-4535677C0CA9")
,4578CB4D-CD03-4637-9635-F399C0564D9D
,Optional("4578CB4D-CD03-4637-9635-F399C0564D9D")
,*Native tests were executed*
,Total number of executed tests:  52
,Number of passed tests:  50
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  23.51256603002548
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
