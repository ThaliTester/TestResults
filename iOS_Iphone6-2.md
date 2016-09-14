#### Test 82914073cc2505e_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FD2C4FB3-5918-450B-B9B9-95DD2E0FDCF3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/FD2C4FB3-5918-450B-B9B9-95DD2E0FDCF3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6D8D0697-4AD1-45CB-9F58-66EB65DE8D9A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50221"
,(lldb)     command script import "/tmp/FD2C4FB3-5918-450B-B9B9-95DD2E0FDCF3/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 14:40:17.901 ThaliTest[752:804058] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D28CAE45-1859-43A5-9963-F0C3D0279347/Library/Cookies/Cookies.binarycookies
,2016-09-14 14:40:17.974 ThaliTest[752:804058] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 14:40:17.975 ThaliTest[752:804058] Multi-tasking -> Device: YES, App: YES
,2016-09-14 14:40:17.990 ThaliTest[752:804058] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 14:40:18.442 ThaliTest[752:804058] Using UIWebView
,2016-09-14 14:40:18.452 ThaliTest[752:804058] [CDVTimer][handleopenurl] 0.419974ms
,2016-09-14 14:40:18.460 ThaliTest[752:804058] [CDVTimer][intentandnavigationfilter] 6.826997ms
2016-09-14 14:40:18.460 ThaliTest[752:804058] [CDVTimer][gesturehandler] 0.284016ms
2016-09-14 14:40:18.461 ThaliTest[752:804058] [CDVTimer][TotalPluginStartup] 9.239018ms
,2016-09-14 14:40:24.164 ThaliTest[752:804058] Resetting plugins due to page load.
,2016-09-14 14:40:24.824 ThaliTest[752:804058] Finished load of: file:///var/containers/Bundle/Application/6D8D0697-4AD1-45CB-9F58-66EB65DE8D9A/ThaliTest.app/www/index.html
,2016-09-14 14:40:25.248 ThaliTest[752:804058] JXcore Cordova plugin initializing
,2016-09-14 14:40:25.248 ThaliTest[752:804220] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x126d576f0>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-14 14:40:44.000 ThaliTest[752:804058] BTM: attaching to BTServer
,2016-09-14 14:40:45.315 ThaliTest[752:804058] BTM: local device power state changed
2016-09-14 14:40:45.315 ThaliTest[752:804058] BTM: power is now off
,2016-09-14 14:40:46.097 ThaliTest[752:804058] BTM: local device power state changed
2016-09-14 14:40:46.097 ThaliTest[752:804058] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  13.56665903329849
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
