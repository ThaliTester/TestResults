#### Test 99247393a8ecbf4_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99247393a8ecbf4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/516AE81F-DCB3-48E5-A4C6-26B94FC5D04D/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/516AE81F-DCB3-48E5-A4C6-26B94FC5D04D/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99247393a8ecbf4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99247393a8ecbf4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FCCAAD3B-60BC-4CF4-AA9C-C88E6798D815/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61212"
,(lldb)     command script import "/tmp/516AE81F-DCB3-48E5-A4C6-26B94FC5D04D/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 11:46:22.456 ThaliTest[939:2871496] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/28FC5888-1812-4836-894A-05D528655B3E/Library/Cookies/Cookies.binarycookies
,2016-12-26 11:46:22.603 ThaliTest[939:2871496] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 11:46:22.605 ThaliTest[939:2871496] Multi-tasking -> Device: YES, App: YES
,2016-12-26 11:46:22.633 ThaliTest[939:2871496] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 11:46:23.419 ThaliTest[939:2871496] Using UIWebView
,2016-12-26 11:46:23.425 ThaliTest[939:2871496] [CDVTimer][handleopenurl] 0.501990ms
,2016-12-26 11:46:23.433 ThaliTest[939:2871496] [CDVTimer][intentandnavigationfilter] 7.192016ms
2016-12-26 11:46:23.434 ThaliTest[939:2871496] [CDVTimer][gesturehandler] 0.329018ms
2016-12-26 11:46:23.434 ThaliTest[939:2871496] [CDVTimer][TotalPluginStartup] 9.380043ms
,2016-12-26 11:46:34.031 ThaliTest[939:2871496] Resetting plugins due to page load.
,2016-12-26 11:46:34.826 ThaliTest[939:2871496] Finished load of: file:///var/containers/Bundle/Application/FCCAAD3B-60BC-4CF4-AA9C-C88E6798D815/ThaliTest.app/www/index.html
,2016-12-26 11:46:35.067 ThaliTest[939:2871496] JXcore Cordova plugin initializing
,2016-12-26 11:46:35.069 ThaliTest[939:2871687] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 10:47:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 10:47:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 10:47:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-26 10:47:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 10:47:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-26 10:47:45 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.93543499708176
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
