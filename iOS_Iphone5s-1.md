#### Test 93572167fd0bc1d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93572167fd0bc1d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/7C99909E-C1B1-4012-BF92-C7A4CFAC8FAA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7C99909E-C1B1-4012-BF92-C7A4CFAC8FAA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93572167fd0bc1d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93572167fd0bc1d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7C4F8A90-8A50-4C46-AB7A-D94476BE20EE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62759"
,(lldb)     command script import "/tmp/7C99909E-C1B1-4012-BF92-C7A4CFAC8FAA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-16 18:34:38.731 ThaliTest[5803:14742869] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C14B10D8-09B6-43E9-9BD1-74535ADD563C/Library/Cookies/Cookies.binarycookies
,2016-11-16 18:34:38.790 ThaliTest[5803:14742869] Apache Cordova native platform version 4.2.1 is starting.
2016-11-16 18:34:38.791 ThaliTest[5803:14742869] Multi-tasking -> Device: YES, App: YES
,2016-11-16 18:34:38.807 ThaliTest[5803:14742869] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-16 18:34:39.578 ThaliTest[5803:14742869] Using UIWebView
2016-11-16 18:34:39.580 ThaliTest[5803:14742869] [CDVTimer][handleopenurl] 0.180006ms
,2016-11-16 18:34:39.584 ThaliTest[5803:14742869] [CDVTimer][intentandnavigationfilter] 3.339052ms
2016-11-16 18:34:39.584 ThaliTest[5803:14742869] [CDVTimer][gesturehandler] 0.146985ms
2016-11-16 18:34:39.584 ThaliTest[5803:14742869] [CDVTimer][TotalPlug,inStartup] 4.334033ms
,2016-11-16 18:34:42.595 ThaliTest[5803:14742869] Resetting plugins due to page load.
,2016-11-16 18:34:44.206 ThaliTest[5803:14742869] Finished load of: file:///var/mobile/Containers/Bundle/Application/7C4F8A90-8A50-4C46-AB7A-D94476BE20EE/ThaliTest.app/www/index.html
,2016-11-16 18:34:44.397 ThaliTest[5803:14742869] JXcore Cordova plugin initializing
,2016-11-16 18:34:44.398 ThaliTest[5803:14743017] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-16 17:34:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-16 17:34:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-16 17:34:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-16 17:34:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-16 17:34:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-16 17:35:23 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  26.1411190032959
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
