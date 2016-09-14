#### Test 82914073cc2505e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/32AC309B-885D-4702-896F-1DFAD4CD7163/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/32AC309B-885D-4702-896F-1DFAD4CD7163/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4C71F2E6-FBCF-41BD-9818-94B4054D47A1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50219"
,(lldb)     command script import "/tmp/32AC309B-885D-4702-896F-1DFAD4CD7163/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-14 23:40:15.079 ThaliTest[637:783537] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B6C01C44-3B45-427A-8584-A02041832568/Library/Cookies/Cookies.binarycookies
,2016-09-14 23:40:15.160 ThaliTest[637:783537] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 23:40:15.162 ThaliTest[637:783537] Multi-tasking -> Device: YES, App: YES
,2016-09-14 23:40:15.182 ThaliTest[637:783537] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 23:40:15.635 ThaliTest[637:783537] Using UIWebView
,2016-09-14 23:40:15.642 ThaliTest[637:783537] [CDVTimer][handleopenurl] 0.378013ms
,2016-09-14 23:40:15.650 ThaliTest[637:783537] [CDVTimer][intentandnavigationfilter] 6.992996ms
2016-09-14 23:40:15.650 ThaliTest[637:783537] [CDVTimer][gesturehandler] 0.289977ms
2016-09-14 23:40:15.651 ThaliTest[637:783537] [CDVTimer][TotalPluginStartup] 9.266019ms
,2016-09-14 23:40:20.601 ThaliTest[637:783537] Resetting plugins due to page load.
,2016-09-14 23:40:20.954 ThaliTest[637:783537] Finished load of: file:///var/containers/Bundle/Application/4C71F2E6-FBCF-41BD-9818-94B4054D47A1/ThaliTest.app/www/index.html
,2016-09-14 23:40:21.298 ThaliTest[637:783537] JXcore Cordova plugin initializing
,2016-09-14 23:40:21.299 ThaliTest[637:783695] JXcore instance initializing
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
,2016-09-14 23:40:28.815 ThaliTest[637:783537] BTM: attaching to BTServer
,2016-09-14 23:40:33.406 ThaliTest[637:783537] BTM: local device power state changed
2016-09-14 23:40:33.410 ThaliTest[637:783537] BTM: power is now off
,2016-09-14 23:40:34.161 ThaliTest[637:783537] BTM: local device power state changed
2016-09-14 23:40:34.162 ThaliTest[637:783537] BTM: power is now on
,received session: <ThaliCore.Session: 0x16170b6f0>
,*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  16.85773199796677
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
