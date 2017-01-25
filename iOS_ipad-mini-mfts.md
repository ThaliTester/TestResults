#### Test 10307209017d2aad_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10307209017d2aad/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/D41C2796-9ED5-4E70-9520-B7B70EC27536/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/D41C2796-9ED5-4E70-9520-B7B70EC27536/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10307209017d2aad/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10307209017d2aad/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/788CE29D-172E-4DF4-B120-02986CE05007/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50023"
,(lldb)     command script import "/tmp/D41C2796-9ED5-4E70-9520-B7B70EC27536/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 09:42:54.169 ThaliTest[1899:6905078] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/436B21CB-DEA4-4BE1-A440-BD5A9F4F4A5D/Library/Cookies/Cookies.binarycookies
,2017-01-25 09:42:54.333 ThaliTest[1899:6905078] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-25 09:42:54.336 ThaliTest[1899:6905078] Multi-tasking -> Device: YES, App: YES
,2017-01-25 09:42:54.366 ThaliTest[1899:6905078] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-25 09:42:54.851 ThaliTest[1899:6905078] Using UIWebView
,2017-01-25 09:42:54.858 ThaliTest[1899:6905078] [CDVTimer][handleopenurl] 0.880003ms
,2017-01-25 09:42:54.866 ThaliTest[1899:6905078] [CDVTimer][intentandnavigationfilter] 7.667959ms
2017-01-25 09:42:54.867 ThaliTest[1899:6905078] [CDVTimer][gesturehandler] 0.329971ms
2017-01-25 09:42:54.867 ThaliTest[1899:6905078] [CDVTimer][TotalPluginStartup] 10.268986ms
,2017-01-25 09:43:01.727 ThaliTest[1899:6905078] Resetting plugins due to page load.
,2017-01-25 09:43:02.182 ThaliTest[1899:6905078] Finished load of: file:///var/containers/Bundle/Application/788CE29D-172E-4DF4-B120-02986CE05007/ThaliTest.app/www/index.html
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 09:43:02.529 ThaliTest[1899:6905078] JXcore Cordova plugin initializing
2017-01-25 09:43:02.532 ThaliTest[1899:6905225] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 08:43:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-25 08:43:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-25 08:43:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-25 08:43:42 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-25 08:43:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-25 08:44:15 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  32.02676802873611
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
