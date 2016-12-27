#### Test 99448283c38bc5f_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99448283c38bc5f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/57F1CA28-87E5-4A20-8CEB-3E9A8416B9B4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/57F1CA28-87E5-4A20-8CEB-3E9A8416B9B4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/99448283c38bc5f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99448283c38bc5f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B2C16119-F1A9-429F-8CE2-7676A8B07AEB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52265"
,(lldb)     command script import "/tmp/57F1CA28-87E5-4A20-8CEB-3E9A8416B9B4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 15:51:35.450 ThaliTest[1525:3213604] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4C6651D1-66D4-4141-A08F-F07E863FD21D/Library/Cookies/Cookies.binarycookies
,2016-12-27 15:51:35.580 ThaliTest[1525:3213604] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 15:51:35.581 ThaliTest[1525:3213604] Multi-tasking -> Device: YES, App: YES
,2016-12-27 15:51:35.602 ThaliTest[1525:3213604] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 15:51:37.079 ThaliTest[1525:3213604] Using UIWebView
,2016-12-27 15:51:37.087 ThaliTest[1525:3213604] [CDVTimer][handleopenurl] 0.420988ms
,2016-12-27 15:51:37.098 ThaliTest[1525:3213604] [CDVTimer][intentandnavigationfilter] 10.203958ms
2016-12-27 15:51:37.099 ThaliTest[1525:3213604] [CDVTimer][gesturehandler] 0.382006ms
2016-12-27 15:51:37.100 ThaliTest[1525:3213604] [CDVTimer][TotalPlugin,Startup] 12.969971ms
,2016-12-27 15:51:42.724 ThaliTest[1525:3213604] Resetting plugins due to page load.
,2016-12-27 15:51:46.010 ThaliTest[1525:3213604] Finished load of: file:///var/mobile/Containers/Bundle/Application/B2C16119-F1A9-429F-8CE2-7676A8B07AEB/ThaliTest.app/www/index.html
,2016-12-27 15:51:46.313 ThaliTest[1525:3213604] JXcore Cordova plugin initializing
,2016-12-27 15:51:46.314 ThaliTest[1525:3213805] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 14:51:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 14:51:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 14:51:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-27 14:51:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 14:51:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-27 14:52:25 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.5995579957962
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
