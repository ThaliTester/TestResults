#### Test 99448283f49b3a7_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/81A13743-8135-4E4E-93B1-9E640B0B3D56/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/81A13743-8135-4E4E-93B1-9E640B0B3D56/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2BE0216D-AE56-4A17-AC1F-245FE1D46B16/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51145"
,(lldb)     command script import "/tmp/81A13743-8135-4E4E-93B1-9E640B0B3D56/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-12-28 16:58:25.949 ThaliTest[1616:3377834] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/93CAFF62-7C1A-417C-A930-A6DF70916A5E/Library/Cookies/Cookies.binarycookies
,2016-12-28 16:58:26.044 ThaliTest[1616:3377834] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 16:58:26.046 ThaliTest[1616:3377834] Multi-tasking -> Device: YES, App: YES
,2016-12-28 16:58:26.066 ThaliTest[1616:3377834] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 16:58:27.419 ThaliTest[1616:3377834] Using UIWebView
,2016-12-28 16:58:27.431 ThaliTest[1616:3377834] [CDVTimer][handleopenurl] 0.422001ms
,2016-12-28 16:58:27.441 ThaliTest[1616:3377834] [CDVTimer][intentandnavigationfilter] 10.140002ms
2016-12-28 16:58:27.442 ThaliTest[1616:3377834] [CDVTimer][gesturehandler] 0.451982ms
2016-12-28 16:58:27.443 ThaliTest[1616:3377834] [CDVTimer][TotalPlugin,Startup] 13.015032ms
,2016-12-28 16:58:33.287 ThaliTest[1616:3377834] Resetting plugins due to page load.
,2016-12-28 16:58:36.581 ThaliTest[1616:3377834] Finished load of: file:///var/mobile/Containers/Bundle/Application/2BE0216D-AE56-4A17-AC1F-245FE1D46B16/ThaliTest.app/www/index.html
,2016-12-28 16:58:36.879 ThaliTest[1616:3377834] JXcore Cordova plugin initializing
,2016-12-28 16:58:36.880 ThaliTest[1616:3378035] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 15:58:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 15:58:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 15:58:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-28 15:58:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 15:58:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 15:59:14 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.61272096633911
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
