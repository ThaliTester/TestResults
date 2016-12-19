#### Test 98312760e1b00a5_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98312760e1b00a5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A7E314BA-B9BC-4A0F-9A22-6E1834978A0E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A7E314BA-B9BC-4A0F-9A22-6E1834978A0E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98312760e1b00a5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98312760e1b00a5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DF10C116-9170-4243-BB80-D83320196339/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56324"
,(lldb)     command script import "/tmp/A7E314BA-B9BC-4A0F-9A22-6E1834978A0E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 13:17:54.682 ThaliTest[1052:1985222] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/49404F9F-94D8-407E-B419-4DC7B81DB599/Library/Cookies/Cookies.binarycookies
,2016-12-19 13:17:54.798 ThaliTest[1052:1985222] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 13:17:54.800 ThaliTest[1052:1985222] Multi-tasking -> Device: YES, App: YES
,2016-12-19 13:17:54.821 ThaliTest[1052:1985222] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 13:17:56.194 ThaliTest[1052:1985222] Using UIWebView
,2016-12-19 13:17:56.202 ThaliTest[1052:1985222] [CDVTimer][handleopenurl] 0.469029ms
,2016-12-19 13:17:56.213 ThaliTest[1052:1985222] [CDVTimer][intentandnavigationfilter] 10.338962ms
2016-12-19 13:17:56.214 ThaliTest[1052:1985222] [CDVTimer][gesturehandler] 0.382006ms
2016-12-19 13:17:56.215 ThaliTest[1052:1985222] [CDVTimer][TotalPlugin,Startup] 13.294995ms
,2016-12-19 13:18:02.027 ThaliTest[1052:1985222] Resetting plugins due to page load.
,2016-12-19 13:18:05.762 ThaliTest[1052:1985222] Finished load of: file:///var/mobile/Containers/Bundle/Application/DF10C116-9170-4243-BB80-D83320196339/ThaliTest.app/www/index.html
,2016-12-19 13:18:06.082 ThaliTest[1052:1985222] JXcore Cordova plugin initializing
,2016-12-19 13:18:06.083 ThaliTest[1052:1985441] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 12:18:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 12:18:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 12:18:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-19 12:18:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 12:18:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
Optional(false)
Optional(true)
,2016-12-19 12:18:44 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.85505503416061
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
