#### Test 98710374837bb9b_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/73180689-00C6-44C1-918A-5D63B64E7159/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/73180689-00C6-44C1-918A-5D63B64E7159/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FBE7BA57-79D8-4119-B58B-F0DBB8E80CF6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50573"
,(lldb)     command script import "/tmp/73180689-00C6-44C1-918A-5D63B64E7159/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-22 18:59:40.825 ThaliTest[1231:2472669] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F1CB4268-69F8-4167-8A3B-46D1C2D979BA/Library/Cookies/Cookies.binarycookies
,2016-12-22 18:59:40.941 ThaliTest[1231:2472669] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-22 18:59:40.942 ThaliTest[1231:2472669] Multi-tasking -> Device: YES, App: YES
,2016-12-22 18:59:40.966 ThaliTest[1231:2472669] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-22 18:59:42.480 ThaliTest[1231:2472669] Using UIWebView
,2016-12-22 18:59:42.488 ThaliTest[1231:2472669] [CDVTimer][handleopenurl] 0.464976ms
,2016-12-22 18:59:42.499 ThaliTest[1231:2472669] [CDVTimer][intentandnavigationfilter] 10.182977ms
2016-12-22 18:59:42.500 ThaliTest[1231:2472669] [CDVTimer][gesturehandler] 0.414014ms
2016-12-22 18:59:42.501 ThaliTest[1231:2472669] [CDVTimer][TotalPlugin,Startup] 13.189018ms
,2016-12-22 18:59:48.666 ThaliTest[1231:2472669] Resetting plugins due to page load.
,2016-12-22 18:59:52.465 ThaliTest[1231:2472669] Finished load of: file:///var/mobile/Containers/Bundle/Application/FBE7BA57-79D8-4119-B58B-F0DBB8E80CF6/ThaliTest.app/www/index.html
,2016-12-22 18:59:52.781 ThaliTest[1231:2472669] JXcore Cordova plugin initializing
,2016-12-22 18:59:52.782 ThaliTest[1231:2472889] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-22 18:00:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-22 18:00:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-22 18:00:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-22 18:00:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-22 18:00:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-22 18:00:31 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  25.16754502058029
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
