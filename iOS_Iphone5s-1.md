#### Test 944077483e9c5d2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8B8D9B21-8A4E-41B7-97B4-32A97FDCAE1C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8B8D9B21-8A4E-41B7-97B4-32A97FDCAE1C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/60DCEEDF-CBEE-445E-A391-8C1968807C96/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56399"
,(lldb)     command script import "/tmp/8B8D9B21-8A4E-41B7-97B4-32A97FDCAE1C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 19:19:40.958 ThaliTest[5965:15061826] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/58076798-C6C1-4D9E-9D2C-6120A7CF058E/Library/Cookies/Cookies.binarycookies
,2016-11-18 19:19:41.020 ThaliTest[5965:15061826] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 19:19:41.021 ThaliTest[5965:15061826] Multi-tasking -> Device: YES, App: YES
,2016-11-18 19:19:41.037 ThaliTest[5965:15061826] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 19:19:41.865 ThaliTest[5965:15061826] Using UIWebView
,2016-11-18 19:19:41.869 ThaliTest[5965:15061826] [CDVTimer][handleopenurl] 0.176013ms
,2016-11-18 19:19:41.872 ThaliTest[5965:15061826] [CDVTimer][intentandnavigationfilter] 2.925038ms
2016-11-18 19:19:41.873 ThaliTest[5965:15061826] [CDVTimer][gesturehandler] 0.145018ms
2016-11-18 19:19:41.873 ThaliTest[5965:15061826] [CDVTimer][TotalPluginStartup] 3.974974ms
,2016-11-18 19:19:45.041 ThaliTest[5965:15061826] Resetting plugins due to page load.
,2016-11-18 19:19:46.565 ThaliTest[5965:15061826] Finished load of: file:///var/mobile/Containers/Bundle/Application/60DCEEDF-CBEE-445E-A391-8C1968807C96/ThaliTest.app/www/index.html
,2016-11-18 19:19:46.752 ThaliTest[5965:15061826] JXcore Cordova plugin initializing
,2016-11-18 19:19:46.753 ThaliTest[5965:15061998] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 18:19:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 18:19:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 18:19:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 18:19:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-18 18:19:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-18 18:20:23 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.0217370390892
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
