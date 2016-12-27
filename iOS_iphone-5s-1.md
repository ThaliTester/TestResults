#### Test 994652478fe1256_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/994652478fe1256/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/15E940AA-3D86-4413-89E6-C3FE1B89DB24/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/15E940AA-3D86-4413-89E6-C3FE1B89DB24/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/994652478fe1256/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/994652478fe1256/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/265DB5E1-174A-4EDE-868A-E8837A2168A3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55484"
,(lldb)     command script import "/tmp/15E940AA-3D86-4413-89E6-C3FE1B89DB24/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 18:41:17.806 ThaliTest[1544:3234110] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7958C123-43C5-4C06-AC1F-AC24494737D8/Library/Cookies/Cookies.binarycookies
,2016-12-27 18:41:17.924 ThaliTest[1544:3234110] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 18:41:17.926 ThaliTest[1544:3234110] Multi-tasking -> Device: YES, App: YES
,2016-12-27 18:41:17.951 ThaliTest[1544:3234110] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 18:41:19.587 ThaliTest[1544:3234110] Using UIWebView
,2016-12-27 18:41:19.595 ThaliTest[1544:3234110] [CDVTimer][handleopenurl] 0.455022ms
,2016-12-27 18:41:19.606 ThaliTest[1544:3234110] [CDVTimer][intentandnavigationfilter] 10.457993ms
2016-12-27 18:41:19.607 ThaliTest[1544:3234110] [CDVTimer][gesturehandler] 0.388026ms
2016-12-27 18:41:19.607 ThaliTest[1544:3234110] [CDVTimer][TotalPlugin,Startup] 13.357997ms
,2016-12-27 18:41:26.606 ThaliTest[1544:3234110] Resetting plugins due to page load.
,2016-12-27 18:41:31.015 ThaliTest[1544:3234110] Finished load of: file:///var/mobile/Containers/Bundle/Application/265DB5E1-174A-4EDE-868A-E8837A2168A3/ThaliTest.app/www/index.html
,2016-12-27 18:41:31.338 ThaliTest[1544:3234110] JXcore Cordova plugin initializing
,2016-12-27 18:41:31.339 ThaliTest[1544:3234310] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 17:41:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 17:41:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 17:41:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-27 17:41:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 17:41:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-27 17:42:09 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.04087501764297
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
