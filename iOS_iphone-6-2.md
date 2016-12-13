#### Test 977271034c6c8cc_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/E3916A96-7CB0-49D3-A7D3-3B0959184B00/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/E3916A96-7CB0-49D3-A7D3-3B0959184B00/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5684EEF2-0C69-4C5A-854B-B6CDFCCD89A5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52721"
,(lldb)     command script import "/tmp/E3916A96-7CB0-49D3-A7D3-3B0959184B00/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 12:18:47.498 ThaliTest[664:788322] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/90E74A7E-18D7-4DF0-A658-2E1000F0D044/Library/Cookies/Cookies.binarycookies
,2016-12-13 12:18:47.539 ThaliTest[664:788322] Apache Cordova native platform version 4.3.1 is starting.
2016-12-13 12:18:47.540 ThaliTest[664:788322] Multi-tasking -> Device: YES, App: YES
,2016-12-13 12:18:47.554 ThaliTest[664:788322] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 12:18:47.900 ThaliTest[664:788322] Using UIWebView
,2016-12-13 12:18:47.905 ThaliTest[664:788322] [CDVTimer][handleopenurl] 0.313997ms
,2016-12-13 12:18:47.911 ThaliTest[664:788322] [CDVTimer][intentandnavigationfilter] 5.757987ms
2016-12-13 12:18:47.912 ThaliTest[664:788322] [CDVTimer][gesturehandler] 0.272036ms
2016-12-13 12:18:47.912 ThaliTest[664:788322] [CDVTimer][TotalPluginStartup] 7.485986ms
,2016-12-13 12:18:53.990 ThaliTest[664:788322] Resetting plugins due to page load.
,2016-12-13 12:18:54.327 ThaliTest[664:788322] Finished load of: file:///var/containers/Bundle/Application/5684EEF2-0C69-4C5A-854B-B6CDFCCD89A5/ThaliTest.app/www/index.html
,2016-12-13 12:18:54.680 ThaliTest[664:788322] JXcore Cordova plugin initializing
,2016-12-13 12:18:54.681 ThaliTest[664:788771] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 11:19:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 11:19:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 11:19:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-13 11:19:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 11:19:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 11:19:31 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.60098600387573
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnter
```
