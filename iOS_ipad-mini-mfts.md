#### Test 9957274948e8cbe_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9957274948e8cbe/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/75C69C24-92E3-42F5-BB3B-AF06DA1CD117/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/75C69C24-92E3-42F5-BB3B-AF06DA1CD117/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9957274948e8cbe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9957274948e8cbe/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2E7AC329-C2E6-427F-9367-D5694ABA7E67/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55499"
,(lldb)     command script import "/tmp/75C69C24-92E3-42F5-BB3B-AF06DA1CD117/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-09 13:24:17.438 ThaliTest[1427:4874141] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BCB5CB8F-BA78-4A09-9491-2B41D9859B89/Library/Cookies/Cookies.binarycookies
,2017-01-09 13:24:17.586 ThaliTest[1427:4874141] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-09 13:24:17.588 ThaliTest[1427:4874141] Multi-tasking -> Device: YES, App: YES
,2017-01-09 13:24:17.611 ThaliTest[1427:4874141] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-09 13:24:18.107 ThaliTest[1427:4874141] Using UIWebView
,2017-01-09 13:24:18.114 ThaliTest[1427:4874141] [CDVTimer][handleopenurl] 0.455976ms
2017-01-09 13:24:18.122 ThaliTest[1427:4874141] [CDVTimer][intentandnavigationfilter] 7.009983ms
2017-01-09 13:24:18.123 ThaliTest[1427:4874141] [CDVTimer][gesturehandle,r] 0.326991ms
2017-01-09 13:24:18.123 ThaliTest[1427:4874141] [CDVTimer][TotalPluginStartup] 9.110987ms
,2017-01-09 13:24:24.978 ThaliTest[1427:4874141] Resetting plugins due to page load.
,2017-01-09 13:24:25.543 ThaliTest[1427:4874141] Finished load of: file:///var/containers/Bundle/Application/2E7AC329-C2E6-427F-9367-D5694ABA7E67/ThaliTest.app/www/index.html
,2017-01-09 13:24:25.793 ThaliTest[1427:4874141] JXcore Cordova plugin initializing
,2017-01-09 13:24:25.795 ThaliTest[1427:4874288] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2017-01-09 12:25:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-09 12:25:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-09 12:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-09 12:25:04 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-09 12:25:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-09 12:25:44 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  39.48683398962021
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
