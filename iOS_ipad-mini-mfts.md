#### Test 996748488b0f149_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/996748488b0f149/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/19637308-E71C-4D74-AF22-E81ED7E009E6/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/19637308-E71C-4D74-AF22-E81ED7E009E6/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/996748488b0f149/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/996748488b0f149/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E0209639-76B9-475C-AC59-FD864FB25219/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53784"
,(lldb)     command script import "/tmp/19637308-E71C-4D74-AF22-E81ED7E009E6/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-09 12:53:25.974 ThaliTest[1421:4869643] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D8A1F38A-9C5A-4983-ADFD-DB1CF6FE53CE/Library/Cookies/Cookies.binarycookies
,2017-01-09 12:53:26.131 ThaliTest[1421:4869643] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-09 12:53:26.134 ThaliTest[1421:4869643] Multi-tasking -> Device: YES, App: YES
,2017-01-09 12:53:26.158 ThaliTest[1421:4869643] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-09 12:53:26.589 ThaliTest[1421:4869643] Using UIWebView
,2017-01-09 12:53:26.597 ThaliTest[1421:4869643] [CDVTimer][handleopenurl] 0.447989ms
2017-01-09 12:53:26.605 ThaliTest[1421:4869643] [CDVTimer][intentandnavigationfilter] 6.981015ms
2017-01-09 12:53:26.605 ThaliTest[1421:4869643] [CDVTimer][gesturehandle,r] 0.324965ms
2017-01-09 12:53:26.606 ThaliTest[1421:4869643] [CDVTimer][TotalPluginStartup] 9.036005ms
,2017-01-09 12:53:32.392 ThaliTest[1421:4869643] Resetting plugins due to page load.
,2017-01-09 12:53:32.890 ThaliTest[1421:4869643] Finished load of: file:///var/containers/Bundle/Application/E0209639-76B9-475C-AC59-FD864FB25219/ThaliTest.app/www/index.html
,2017-01-09 12:53:33.141 ThaliTest[1421:4869643] JXcore Cordova plugin initializing
2017-01-09 12:53:33.143 ThaliTest[1421:4869773] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-09 11:54:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-09 11:54:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-09 11:54:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-09 11:54:07 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-09 11:54:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-09 11:54:46 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  38.08179098367691
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
