#### Test 10258170873f290a_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/36EFC34C-1B53-4EE1-8820-40FCA7B445B0/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/36EFC34C-1B53-4EE1-8820-40FCA7B445B0/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/248D711E-A536-45C2-84C2-7D486760D321/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59891"
,(lldb)     command script import "/tmp/36EFC34C-1B53-4EE1-8820-40FCA7B445B0/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 12:34:57.507 ThaliTest[1861:6771410] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/65586375-069C-4125-A05F-BBEF315F6980/Library/Cookies/Cookies.binarycookies
,2017-01-24 12:34:57.669 ThaliTest[1861:6771410] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-24 12:34:57.672 ThaliTest[1861:6771410] Multi-tasking -> Device: YES, App: YES
,2017-01-24 12:34:57.706 ThaliTest[1861:6771410] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 12:34:58.184 ThaliTest[1861:6771410] Using UIWebView
,2017-01-24 12:34:58.191 ThaliTest[1861:6771410] [CDVTimer][handleopenurl] 1.549959ms
2017-01-24 12:34:58.198 ThaliTest[1861:6771410] [CDVTimer][intentandnavigationfilter] 6.933033ms
2017-01-24 12:34:58.199 ThaliTest[1861:6771410] [CDVTimer][gesturehandle,r] 0.328958ms
2017-01-24 12:34:58.199 ThaliTest[1861:6771410] [CDVTimer][TotalPluginStartup] 10.028005ms
,2017-01-24 12:35:05.069 ThaliTest[1861:6771410] Resetting plugins due to page load.
,2017-01-24 12:35:05.601 ThaliTest[1861:6771410] Finished load of: file:///var/containers/Bundle/Application/248D711E-A536-45C2-84C2-7D486760D321/ThaliTest.app/www/index.html
,2017-01-24 12:35:05.859 ThaliTest[1861:6771410] JXcore Cordova plugin initializing
2017-01-24 12:35:05.861 ThaliTest[1861:6771554] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2017-01-24 11:35:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-24 11:35:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 11:35:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-24 11:35:44 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-24 11:35:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-24 11:36:17 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.54112702608109
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
