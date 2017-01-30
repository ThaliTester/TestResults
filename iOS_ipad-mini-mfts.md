#### Test 103691986c90445e_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/103691986c90445e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/34F7A645-1D26-4508-8D2C-9FFFDB34B71E/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/34F7A645-1D26-4508-8D2C-9FFFDB34B71E/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/103691986c90445e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/103691986c90445e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7198C9A9-3B14-48D9-803C-E8BA1280E1A9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54171"
,(lldb)     command script import "/tmp/34F7A645-1D26-4508-8D2C-9FFFDB34B71E/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-30 09:35:00.303 ThaliTest[2065:7664149] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B6930CD8-FFA7-4273-9CBB-C6C821E180B1/Library/Cookies/Cookies.binarycookies
,2017-01-30 09:35:00.441 ThaliTest[2065:7664149] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-30 09:35:00.444 ThaliTest[2065:7664149] Multi-tasking -> Device: YES, App: YES
,2017-01-30 09:35:00.468 ThaliTest[2065:7664149] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-30 09:35:01.234 ThaliTest[2065:7664149] Using UIWebView
,2017-01-30 09:35:01.240 ThaliTest[2065:7664149] [CDVTimer][handleopenurl] 0.598967ms
,2017-01-30 09:35:01.248 ThaliTest[2065:7664149] [CDVTimer][intentandnavigationfilter] 7.256985ms
2017-01-30 09:35:01.248 ThaliTest[2065:7664149] [CDVTimer][gesturehandler] 0.325024ms
2017-01-30 09:35:01.249 ThaliTest[2065:7664149] [CDVTimer][TotalPluginS,tartup] 9.548008ms
,2017-01-30 09:35:11.669 ThaliTest[2065:7664149] Resetting plugins due to page load.
,2017-01-30 09:35:12.415 ThaliTest[2065:7664149] Finished load of: file:///var/containers/Bundle/Application/7198C9A9-3B14-48D9-803C-E8BA1280E1A9/ThaliTest.app/www/index.html
,2017-01-30 09:35:12.646 ThaliTest[2065:7664149] JXcore Cordova plugin initializing
,2017-01-30 09:35:12.648 ThaliTest[2065:7664332] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-30 08:35:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-30 08:35:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-30 08:35:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-01-30 08:35:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-30 08:35:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-30 08:36:27 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  33.36826801300049
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
