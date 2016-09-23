#### Test 85046911b09b63d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911b09b63d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1EE8225A-9665-4879-BF4D-9E7537AB0010/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1EE8225A-9665-4879-BF4D-9E7537AB0010/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911b09b63d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911b09b63d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F7884B82-FA58-434B-937E-820888D78544/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64788"
,(lldb)     command script import "/tmp/1EE8225A-9665-4879-BF4D-9E7537AB0010/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 09:54:09.162 ThaliTest[1270:1854558] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/956701A2-F60A-4187-8D3F-A1B8F70DC60B/Library/Cookies/Cookies.binarycookies
,2016-09-23 09:54:09.202 ThaliTest[1270:1854558] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 09:54:09.203 ThaliTest[1270:1854558] Multi-tasking -> Device: YES, App: YES
,2016-09-23 09:54:09.216 ThaliTest[1270:1854558] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 09:54:09.551 ThaliTest[1270:1854558] Using UIWebView
,2016-09-23 09:54:09.556 ThaliTest[1270:1854558] [CDVTimer][handleopenurl] 0.329971ms
,2016-09-23 09:54:09.561 ThaliTest[1270:1854558] [CDVTimer][intentandnavigationfilter] 4.608989ms
2016-09-23 09:54:09.561 ThaliTest[1270:1854558] [CDVTimer][gesturehandler] 0.202000ms
2016-09-23 09:54:09.561 ThaliTest[1270:1854558] [CDVTimer][TotalPluginS,tartup] 6.247997ms
,2016-09-23 09:54:14.723 ThaliTest[1270:1854558] Resetting plugins due to page load.
,2016-09-23 09:54:15.114 ThaliTest[1270:1854558] Finished load of: file:///var/containers/Bundle/Application/F7884B82-FA58-434B-937E-820888D78544/ThaliTest.app/www/index.html
,2016-09-23 09:54:15.446 ThaliTest[1270:1854558] JXcore Cordova plugin initializing
,2016-09-23 09:54:15.447 ThaliTest[1270:1855358] JXcore instance initializing
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
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 09:54:22.974 ThaliTest[1270:1854558] BTM: attaching to BTServer
,2016-09-23 09:54:23.713 ThaliTest[1270:1854558] BTM: local device power state changed
2016-09-23 09:54:23.713 ThaliTest[1270:1854558] BTM: power is now on
,2016-09-23 09:54:28.478 ThaliTest[1270:1854558] BTM: local device power state changed
2016-09-23 09:54:28.479 ThaliTest[1270:1854558] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  7
Number of passed tests:  7
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  5.65330296754837
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
