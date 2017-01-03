#### Test 99530606e7215e5_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F53D00B1-FDE1-4296-998E-02050018DB81/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/F53D00B1-FDE1-4296-998E-02050018DB81/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1BB5E840-5BCC-4ACB-8F1A-8DC2D817ECF6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60310"
,(lldb)     command script import "/tmp/F53D00B1-FDE1-4296-998E-02050018DB81/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-03 14:55:07.315 ThaliTest[1755:3452849] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F6A39053-D5B2-44C0-A371-840BC5898A77/Library/Cookies/Cookies.binarycookies
,2017-01-03 14:55:07.361 ThaliTest[1755:3452849] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-03 14:55:07.362 ThaliTest[1755:3452849] Multi-tasking -> Device: YES, App: YES
,2017-01-03 14:55:07.374 ThaliTest[1755:3452849] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-03 14:55:07.612 ThaliTest[1755:3452849] Using UIWebView
,2017-01-03 14:55:07.615 ThaliTest[1755:3452849] [CDVTimer][handleopenurl] 0.111997ms
,2017-01-03 14:55:07.618 ThaliTest[1755:3452849] [CDVTimer][intentandnavigationfilter] 2.969027ms
2017-01-03 14:55:07.618 ThaliTest[1755:3452849] [CDVTimer][gesturehandler] 0.101984ms
2017-01-03 14:55:07.618 ThaliTest[1755:3452849] [CDVTimer][TotalPluginStartup] 3.732026ms
,2017-01-03 14:55:10.884 ThaliTest[1755:3452849] Resetting plugins due to page load.
,2017-01-03 14:55:11.143 ThaliTest[1755:3452849] Finished load of: file:///var/containers/Bundle/Application/1BB5E840-5BCC-4ACB-8F1A-8DC2D817ECF6/ThaliTest.app/www/index.html
,2017-01-03 14:55:11.473 ThaliTest[1755:3452849] JXcore Cordova plugin initializing
,2017-01-03 14:55:11.474 ThaliTest[1755:3453006] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-03 13:55:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-03 13:55:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-03 13:55:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
2017-01-03 13:55:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-03 13:55:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-03 13:55:46 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  23.96318399906158
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
