#### Test 103941844b3b02b3_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/103941844b3b02b3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C4B94F02-9A73-4FBB-AEDA-D2C5A502EABD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C4B94F02-9A73-4FBB-AEDA-D2C5A502EABD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/103941844b3b02b3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/103941844b3b02b3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/30585CA6-3844-471F-A71D-856FD6F72E0E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57378"
,(lldb)     command script import "/tmp/C4B94F02-9A73-4FBB-AEDA-D2C5A502EABD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-31 15:39:07.860 ThaliTest[3106:8107798] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FF540849-DABC-4A90-9C05-DF7E8C76AE6B/Library/Cookies/Cookies.binarycookies
,2017-01-31 15:39:07.984 ThaliTest[3106:8107798] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-31 15:39:07.986 ThaliTest[3106:8107798] Multi-tasking -> Device: YES, App: YES
,2017-01-31 15:39:08.011 ThaliTest[3106:8107798] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-31 15:39:09.636 ThaliTest[3106:8107798] Using UIWebView
,2017-01-31 15:39:09.645 ThaliTest[3106:8107798] [CDVTimer][handleopenurl] 0.658989ms
,2017-01-31 15:39:09.654 ThaliTest[3106:8107798] [CDVTimer][intentandnavigationfilter] 9.127975ms
2017-01-31 15:39:09.655 ThaliTest[3106:8107798] [CDVTimer][gesturehandler] 0.382960ms
2017-01-31 15:39:09.656 ThaliTest[3106:8107798] [CDVTimer][TotalPluginS,tartup] 12.127995ms
,2017-01-31 15:39:16.186 ThaliTest[3106:8107798] Resetting plugins due to page load.
,2017-01-31 15:39:19.639 ThaliTest[3106:8107798] Finished load of: file:///var/mobile/Containers/Bundle/Application/30585CA6-3844-471F-A71D-856FD6F72E0E/ThaliTest.app/www/index.html
,2017-01-31 15:39:19.955 ThaliTest[3106:8107798] JXcore Cordova plugin initializing
,2017-01-31 15:39:19.956 ThaliTest[3106:8108014] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-31 14:39:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-31 14:39:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-31 14:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-31 14:39:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-31 14:39:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-31 14:39:58 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.93266201019287
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
