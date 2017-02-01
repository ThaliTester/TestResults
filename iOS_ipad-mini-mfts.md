#### Test 104148237c83cb35_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/104148237c83cb35/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8223A6AF-26CD-48F6-A6EB-E04A02B72BB3/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/8223A6AF-26CD-48F6-A6EB-E04A02B72BB3/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/104148237c83cb35/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/104148237c83cb35/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0D2DD649-5B2D-4F46-8058-43317755306F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60263"
,(lldb)     command script import "/tmp/8223A6AF-26CD-48F6-A6EB-E04A02B72BB3/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-01 20:12:04.114 ThaliTest[2135:8042373] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/106A1025-2EAA-41E7-9ADF-69C0C29B83B2/Library/Cookies/Cookies.binarycookies
,2017-02-01 20:12:04.272 ThaliTest[2135:8042373] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-01 20:12:04.277 ThaliTest[2135:8042373] Multi-tasking -> Device: YES, App: YES
,2017-02-01 20:12:04.304 ThaliTest[2135:8042373] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-01 20:12:04.953 ThaliTest[2135:8042373] Using UIWebView
,2017-02-01 20:12:04.961 ThaliTest[2135:8042373] [CDVTimer][handleopenurl] 0.521004ms
,2017-02-01 20:12:04.969 ThaliTest[2135:8042373] [CDVTimer][intentandnavigationfilter] 7.502973ms
2017-02-01 20:12:04.970 ThaliTest[2135:8042373] [CDVTimer][gesturehandler] 0.333011ms
2017-02-01 20:12:04.970 ThaliTest[2135:8042373] [CDVTimer][TotalPluginS,tartup] 9.711981ms
,2017-02-01 20:12:13.753 ThaliTest[2135:8042373] Resetting plugins due to page load.
,2017-02-01 20:12:14.456 ThaliTest[2135:8042373] Finished load of: file:///var/containers/Bundle/Application/0D2DD649-5B2D-4F46-8058-43317755306F/ThaliTest.app/www/index.html
,2017-02-01 20:12:14.706 ThaliTest[2135:8042373] JXcore Cordova plugin initializing
,2017-02-01 20:12:14.707 ThaliTest[2135:8042532] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-01 19:12:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-01 19:12:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-01 19:12:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-02-01 19:12:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-01 19:12:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-02-01 19:13:33 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  35.64574497938156
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
