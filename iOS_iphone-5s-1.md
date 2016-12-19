#### Test 9856377493d976a_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9856377493d976a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/3ACBFF82-FB21-46F7-9FEC-F55A73E44E90/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3ACBFF82-FB21-46F7-9FEC-F55A73E44E90/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9856377493d976a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9856377493d976a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C781657A-47E0-4BE2-A0D3-1C4E13C9FAA1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62913"
,(lldb)     command script import "/tmp/3ACBFF82-FB21-46F7-9FEC-F55A73E44E90/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 15:38:12.767 ThaliTest[1085:2005232] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/090660D0-CB36-4220-AD9B-67A7E8BC2AAA/Library/Cookies/Cookies.binarycookies
,2016-12-19 15:38:12.899 ThaliTest[1085:2005232] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 15:38:12.901 ThaliTest[1085:2005232] Multi-tasking -> Device: YES, App: YES
,2016-12-19 15:38:12.924 ThaliTest[1085:2005232] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 15:38:14.353 ThaliTest[1085:2005232] Using UIWebView
,2016-12-19 15:38:14.359 ThaliTest[1085:2005232] [CDVTimer][handleopenurl] 0.314951ms
,2016-12-19 15:38:14.366 ThaliTest[1085:2005232] [CDVTimer][intentandnavigationfilter] 6.366968ms
2016-12-19 15:38:14.367 ThaliTest[1085:2005232] [CDVTimer][gesturehandler] 0.258029ms
2016-12-19 15:38:14.367 ThaliTest[1085:2005232] [CDVTimer][TotalPluginS,tartup] 8.289993ms
,2016-12-19 15:38:20.066 ThaliTest[1085:2005232] Resetting plugins due to page load.
,2016-12-19 15:38:23.374 ThaliTest[1085:2005232] Finished load of: file:///var/mobile/Containers/Bundle/Application/C781657A-47E0-4BE2-A0D3-1C4E13C9FAA1/ThaliTest.app/www/index.html
,2016-12-19 15:38:23.691 ThaliTest[1085:2005232] JXcore Cordova plugin initializing
,2016-12-19 15:38:23.692 ThaliTest[1085:2005466] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 14:38:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 14:38:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 14:38:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-19 14:38:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 14:38:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-19 14:39:04 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  27.57011795043945
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
