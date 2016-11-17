#### Test 937653176a1f39f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/937653176a1f39f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8033DF5D-853B-40B7-B6D5-55E3B26E9BA5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8033DF5D-853B-40B7-B6D5-55E3B26E9BA5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/937653176a1f39f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/937653176a1f39f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F8E88513-5F9E-487C-AA7E-2F8D4E765C13/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49379"
,(lldb)     command script import "/tmp/8033DF5D-853B-40B7-B6D5-55E3B26E9BA5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 11:00:36.072 ThaliTest[5842:14848619] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6EA3D661-B949-4C0C-8E77-B042E4FB9036/Library/Cookies/Cookies.binarycookies
,2016-11-17 11:00:36.136 ThaliTest[5842:14848619] Apache Cordova native platform version 4.2.1 is starting.
2016-11-17 11:00:36.138 ThaliTest[5842:14848619] Multi-tasking -> Device: YES, App: YES
,2016-11-17 11:00:36.151 ThaliTest[5842:14848619] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 11:00:36.938 ThaliTest[5842:14848619] Using UIWebView
,2016-11-17 11:00:36.941 ThaliTest[5842:14848619] [CDVTimer][handleopenurl] 0.229001ms
2016-11-17 11:00:36.944 ThaliTest[5842:14848619] [CDVTimer][intentandnavigationfilter] 2.739012ms
2016-11-17 11:00:36.944 ThaliTest[5842:14848619] [CDVTimer][gesturehandler] 0.124991ms
2016-11-17 11:00:36.945 ThaliTest[5842:14848619] [CDVTimer][TotalPluginStartup] 3.787041ms
,2016-11-17 11:00:39.972 ThaliTest[5842:14848619] Resetting plugins due to page load.
,2016-11-17 11:00:41.459 ThaliTest[5842:14848619] Finished load of: file:///var/mobile/Containers/Bundle/Application/F8E88513-5F9E-487C-AA7E-2F8D4E765C13/ThaliTest.app/www/index.html
,2016-11-17 11:00:41.644 ThaliTest[5842:14848619] JXcore Cordova plugin initializing
,2016-11-17 11:00:41.645 ThaliTest[5842:14848770] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 10:00:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-17 10:00:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 10:00:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-17 10:00:54 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2016-11-17 10:00:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-17 10:01:19 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.57833302021027
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
