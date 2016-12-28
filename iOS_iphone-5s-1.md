#### Test 99530606d5b5815_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/BC3A42DE-6B69-4988-898A-D430258C9AEE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/BC3A42DE-6B69-4988-898A-D430258C9AEE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/37D17F99-8564-4977-8955-6900F4BDE3AE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49319"
,(lldb)     command script import "/tmp/BC3A42DE-6B69-4988-898A-D430258C9AEE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 16:33:13.560 ThaliTest[1608:3374400] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/85E225E6-E778-41EC-8EE7-CDFA47BD2E60/Library/Cookies/Cookies.binarycookies
,2016-12-28 16:33:13.681 ThaliTest[1608:3374400] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 16:33:13.683 ThaliTest[1608:3374400] Multi-tasking -> Device: YES, App: YES
,2016-12-28 16:33:13.709 ThaliTest[1608:3374400] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 16:33:15.130 ThaliTest[1608:3374400] Using UIWebView
,2016-12-28 16:33:15.139 ThaliTest[1608:3374400] [CDVTimer][handleopenurl] 0.586987ms
,2016-12-28 16:33:15.150 ThaliTest[1608:3374400] [CDVTimer][intentandnavigationfilter] 10.165036ms
2016-12-28 16:33:15.151 ThaliTest[1608:3374400] [CDVTimer][gesturehandler] 0.379980ms
2016-12-28 16:33:15.151 ThaliTest[1608:3374400] [CDVTimer][TotalPlugin,Startup] 13.301015ms
,2016-12-28 16:33:20.986 ThaliTest[1608:3374400] Resetting plugins due to page load.
,2016-12-28 16:33:24.020 ThaliTest[1608:3374400] Finished load of: file:///var/mobile/Containers/Bundle/Application/37D17F99-8564-4977-8955-6900F4BDE3AE/ThaliTest.app/www/index.html
,2016-12-28 16:33:24.331 ThaliTest[1608:3374400] JXcore Cordova plugin initializing
,2016-12-28 16:33:24.333 ThaliTest[1608:3374601] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 15:33:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 15:33:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 15:33:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-28 15:33:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 15:33:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-12-28 15:34:03 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  26.33349895477295
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
