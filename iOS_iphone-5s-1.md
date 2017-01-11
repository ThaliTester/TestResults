#### Test 995727498cdcb4a_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/995727498cdcb4a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/72A0DA19-7983-41D4-B388-B8ECF2E2D8E5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/72A0DA19-7983-41D4-B388-B8ECF2E2D8E5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/995727498cdcb4a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/995727498cdcb4a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CFE23288-AEFA-4486-A2A2-6A30167547B2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63748"
,(lldb)     command script import "/tmp/72A0DA19-7983-41D4-B388-B8ECF2E2D8E5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-11 12:59:37.240 ThaliTest[2244:5347994] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CCFDFCBE-E8F2-4BF1-94EF-A56B45D447C3/Library/Cookies/Cookies.binarycookies
,2017-01-11 12:59:37.314 ThaliTest[2244:5347994] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-11 12:59:37.315 ThaliTest[2244:5347994] Multi-tasking -> Device: YES, App: YES
,2017-01-11 12:59:37.331 ThaliTest[2244:5347994] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-11 12:59:38.170 ThaliTest[2244:5347994] Using UIWebView
2017-01-11 12:59:38.175 ThaliTest[2244:5347994] [CDVTimer][handleopenurl] 0.167012ms
,2017-01-11 12:59:38.180 ThaliTest[2244:5347994] [CDVTimer][intentandnavigationfilter] 4.539967ms
2017-01-11 12:59:38.180 ThaliTest[2244:5347994] [CDVTimer][gesturehandler] 0.152946ms
2017-01-11 12:59:38.180 ThaliTest[2244:5347994] [CDVTimer][TotalPluginStartup] 5.602956ms
,2017-01-11 12:59:41.335 ThaliTest[2244:5347994] Resetting plugins due to page load.
,2017-01-11 12:59:43.096 ThaliTest[2244:5347994] Finished load of: file:///var/mobile/Containers/Bundle/Application/CFE23288-AEFA-4486-A2A2-6A30167547B2/ThaliTest.app/www/index.html
,2017-01-11 12:59:43.314 ThaliTest[2244:5347994] JXcore Cordova plugin initializing
2017-01-11 12:59:43.315 ThaliTest[2244:5348163] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-11 11:59:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-11 11:59:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-11 11:59:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-11 11:59:58 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2017-01-11 11:59:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-11 12:00:23 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.72825002670288
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
