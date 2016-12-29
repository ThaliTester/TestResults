#### Test 9965213169fe96d_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A643A093-2F3E-44F5-9D08-344CA3379AC8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A643A093-2F3E-44F5-9D08-344CA3379AC8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FB6D7312-CA31-4509-9918-D82841437D55/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63260"
,(lldb)     command script import "/tmp/A643A093-2F3E-44F5-9D08-344CA3379AC8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 14:37:41.566 ThaliTest[1672:3515259] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F486698B-F262-40DC-B760-668276A575DB/Library/Cookies/Cookies.binarycookies
,2016-12-29 14:37:41.676 ThaliTest[1672:3515259] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 14:37:41.678 ThaliTest[1672:3515259] Multi-tasking -> Device: YES, App: YES
,2016-12-29 14:37:41.699 ThaliTest[1672:3515259] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 14:37:43.246 ThaliTest[1672:3515259] Using UIWebView
,2016-12-29 14:37:43.258 ThaliTest[1672:3515259] [CDVTimer][handleopenurl] 0.464976ms
,2016-12-29 14:37:43.269 ThaliTest[1672:3515259] [CDVTimer][intentandnavigationfilter] 10.582030ms
2016-12-29 14:37:43.270 ThaliTest[1672:3515259] [CDVTimer][gesturehandler] 0.424981ms
2016-12-29 14:37:43.271 ThaliTest[1672:3515259] [CDVTimer][TotalPlugin,Startup] 13.834000ms
,2016-12-29 14:37:48.931 ThaliTest[1672:3515259] Resetting plugins due to page load.
,2016-12-29 14:37:52.077 ThaliTest[1672:3515259] Finished load of: file:///var/mobile/Containers/Bundle/Application/FB6D7312-CA31-4509-9918-D82841437D55/ThaliTest.app/www/index.html
,2016-12-29 14:37:52.385 ThaliTest[1672:3515259] JXcore Cordova plugin initializing
,2016-12-29 14:37:52.387 ThaliTest[1672:3515452] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 13:38:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-29 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-29 13:38:30 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.05546003580093
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
