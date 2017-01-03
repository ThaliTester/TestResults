#### Test 995727499fee306_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/254BE8CD-4814-41D7-8638-B9AEBB22B2D4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/254BE8CD-4814-41D7-8638-B9AEBB22B2D4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8ACA61A7-91A4-4F94-9BA3-5A2479F94528/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55715"
,(lldb)     command script import "/tmp/254BE8CD-4814-41D7-8638-B9AEBB22B2D4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2017-01-03 11:35:32.976 ThaliTest[1882:4257151] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CD26631A-D976-456E-9B5B-952C52488B60/Library/Cookies/Cookies.binarycookies
,2017-01-03 11:35:33.634 ThaliTest[1882:4257151] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-03 11:35:33.635 ThaliTest[1882:4257151] Multi-tasking -> Device: YES, App: YES
,2017-01-03 11:35:33.653 ThaliTest[1882:4257151] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-03 11:35:35.617 ThaliTest[1882:4257151] Using UIWebView
,2017-01-03 11:35:35.626 ThaliTest[1882:4257151] [CDVTimer][handleopenurl] 0.455976ms
,2017-01-03 11:35:35.636 ThaliTest[1882:4257151] [CDVTimer][intentandnavigationfilter] 10.065019ms
2017-01-03 11:35:35.637 ThaliTest[1882:4257151] [CDVTimer][gesturehandler] 0.420988ms
2017-01-03 11:35:35.638 ThaliTest[1882:4257151] [CDVTimer][TotalPlugin,Startup] 13.066053ms
,2017-01-03 11:35:43.093 ThaliTest[1882:4257151] Resetting plugins due to page load.
,2017-01-03 11:35:46.692 ThaliTest[1882:4257151] Finished load of: file:///var/mobile/Containers/Bundle/Application/8ACA61A7-91A4-4F94-9BA3-5A2479F94528/ThaliTest.app/www/index.html
,2017-01-03 11:35:46.936 ThaliTest[1882:4257151] JXcore Cordova plugin initializing
,2017-01-03 11:35:46.937 ThaliTest[1882:4257389] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-03 10:36:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-03 10:36:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-03 10:36:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-03 10:36:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-03 10:36:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-03 10:36:24 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.07695704698563
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
