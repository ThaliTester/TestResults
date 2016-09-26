#### Test 86482582e70b00a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86482582e70b00a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D27724A0-5283-4FC3-A999-09B26F46BAFA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D27724A0-5283-4FC3-A999-09B26F46BAFA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86482582e70b00a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86482582e70b00a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/251353C1-7A54-4ED6-9013-B8FDEB92FCE6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64596"
,(lldb)     command script import "/tmp/D27724A0-5283-4FC3-A999-09B26F46BAFA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 12:32:22.599 ThaliTest[1440:2244647] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BA884007-2381-47CB-830A-DFE024385DBD/Library/Cookies/Cookies.binarycookies
,2016-09-26 12:32:22.639 ThaliTest[1440:2244647] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 12:32:22.640 ThaliTest[1440:2244647] Multi-tasking -> Device: YES, App: YES
,2016-09-26 12:32:22.651 ThaliTest[1440:2244647] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 12:32:22.976 ThaliTest[1440:2244647] Using UIWebView
,2016-09-26 12:32:22.981 ThaliTest[1440:2244647] [CDVTimer][handleopenurl] 0.191987ms
,2016-09-26 12:32:22.985 ThaliTest[1440:2244647] [CDVTimer][intentandnavigationfilter] 3.648996ms
2016-09-26 12:32:22.985 ThaliTest[1440:2244647] [CDVTimer][gesturehandler] 0.149965ms
2016-09-26 12:32:22.985 ThaliTest[1440:2244647] [CDVTimer][TotalPluginS,tartup] 4.837990ms
,2016-09-26 12:32:28.257 ThaliTest[1440:2244647] Resetting plugins due to page load.
,2016-09-26 12:32:28.614 ThaliTest[1440:2244647] Finished load of: file:///var/containers/Bundle/Application/251353C1-7A54-4ED6-9013-B8FDEB92FCE6/ThaliTest.app/www/index.html
,2016-09-26 12:32:28.984 ThaliTest[1440:2244647] JXcore Cordova plugin initializing
,2016-09-26 12:32:28.985 ThaliTest[1440:2244830] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1469ae2c0>
,Optional("461441BC-0950-498A-BEE0-2E4575CD62D0")
,nil
,nil
,Optional("6EA477D9-BCB3-4B1F-9722-BF82F1D0F17E")
,Optional("C10F4D85-485A-4FDF-9BCD-43562D1BC05F")
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.58450400829315
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
