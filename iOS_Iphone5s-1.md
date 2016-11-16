#### Test 93986313a169e88_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93986313a169e88/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/C2D08120-8613-42C3-B73A-0E59864D8A7A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C2D08120-8613-42C3-B73A-0E59864D8A7A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93986313a169e88/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93986313a169e88/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DEA3ED73-1F2D-41AB-B0A7-9F589FDB8624/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59891"
,(lldb)     command script import "/tmp/C2D08120-8613-42C3-B73A-0E59864D8A7A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-11-16 17:09:08.909 ThaliTest[5786:14731620] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F7F6651-5B22-48EA-BC8C-ACD27FFFAB8B/Library/Cookies/Cookies.binarycookies
,2016-11-16 17:09:09.434 ThaliTest[5786:14731620] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-16 17:09:09.435 ThaliTest[5786:14731620] Multi-tasking -> Device: YES, App: YES
,2016-11-16 17:09:09.454 ThaliTest[5786:14731620] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-16 17:09:10.234 ThaliTest[5786:14731620] Using UIWebView
,2016-11-16 17:09:10.237 ThaliTest[5786:14731620] [CDVTimer][handleopenurl] 0.172019ms
2016-11-16 17:09:10.240 ThaliTest[5786:14731620] [CDVTimer][intentandnavigationfilter] 2.783000ms
2016-11-16 17:09:10.241 ThaliTest[5786:14731620] [CDVTimer][gesturehan,dler] 0.138998ms
2016-11-16 17:09:10.241 ThaliTest[5786:14731620] [CDVTimer][TotalPluginStartup] 4.568040ms
,2016-11-16 17:09:13.293 ThaliTest[5786:14731620] Resetting plugins due to page load.
,2016-11-16 17:09:14.668 ThaliTest[5786:14731620] Finished load of: file:///var/mobile/Containers/Bundle/Application/DEA3ED73-1F2D-41AB-B0A7-9F589FDB8624/ThaliTest.app/www/index.html
,2016-11-16 17:09:14.908 ThaliTest[5786:14731620] JXcore Cordova plugin initializing
2016-11-16 17:09:14.909 ThaliTest[5786:14731795] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-11-16 16:09:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-16 16:09:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-16 16:09:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-16 16:09:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-16 16:09:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-16 16:09:51 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.22359198331833
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
