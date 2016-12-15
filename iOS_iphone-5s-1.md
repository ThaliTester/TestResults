#### Test 98115565db523c3_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98115565db523c3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/EAC9CE62-229A-4B17-9848-F473742BF110/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EAC9CE62-229A-4B17-9848-F473742BF110/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98115565db523c3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98115565db523c3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/93EE1DA1-2A82-4391-B46D-5FDE5D9ABF65/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49568"
,(lldb)     command script import "/tmp/EAC9CE62-229A-4B17-9848-F473742BF110/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-15 12:12:26.896 ThaliTest[851:1395098] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF194FE3-2C9F-4C5C-9AFE-82029A5683A0/Library/Cookies/Cookies.binarycookies
,2016-12-15 12:12:27.015 ThaliTest[851:1395098] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-15 12:12:27.016 ThaliTest[851:1395098] Multi-tasking -> Device: YES, App: YES
,2016-12-15 12:12:27.039 ThaliTest[851:1395098] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-15 12:12:28.546 ThaliTest[851:1395098] Using UIWebView
,2016-12-15 12:12:28.558 ThaliTest[851:1395098] [CDVTimer][handleopenurl] 0.429034ms
,2016-12-15 12:12:28.569 ThaliTest[851:1395098] [CDVTimer][intentandnavigationfilter] 10.336995ms
2016-12-15 12:12:28.570 ThaliTest[851:1395098] [CDVTimer][gesturehandler] 0.389993ms
2016-12-15 12:12:28.571 ThaliTest[851:1395098] [CDVTimer][TotalPluginSta,rtup] 13.202965ms
,2016-12-15 12:12:35.056 ThaliTest[851:1395098] Resetting plugins due to page load.
,2016-12-15 12:12:38.895 ThaliTest[851:1395098] Finished load of: file:///var/mobile/Containers/Bundle/Application/93EE1DA1-2A82-4391-B46D-5FDE5D9ABF65/ThaliTest.app/www/index.html
,2016-12-15 12:12:39.218 ThaliTest[851:1395098] JXcore Cordova plugin initializing
,2016-12-15 12:12:39.219 ThaliTest[851:1395330] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-15 11:12:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-15 11:12:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-15 11:12:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-15 11:12:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-15 11:12:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-15 11:13:17 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.50733399391174
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
