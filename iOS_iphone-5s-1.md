#### Test 104148244b516848_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/104148244b516848/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B92F38C2-D3F9-4DE1-BDD4-56F3EDC492CA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B92F38C2-D3F9-4DE1-BDD4-56F3EDC492CA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/104148244b516848/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/104148244b516848/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6C3B0609-17A6-4BF9-A7E8-2BA38F366B9D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54444"
,(lldb)     command script import "/tmp/B92F38C2-D3F9-4DE1-BDD4-56F3EDC492CA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-02 17:15:09.657 ThaliTest[3213:8454476] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7CF01B9D-8720-4A93-9C00-05C44FCE84C3/Library/Cookies/Cookies.binarycookies
,2017-02-02 17:15:09.785 ThaliTest[3213:8454476] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-02 17:15:09.787 ThaliTest[3213:8454476] Multi-tasking -> Device: YES, App: YES
,2017-02-02 17:15:09.814 ThaliTest[3213:8454476] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-02 17:15:11.329 ThaliTest[3213:8454476] Using UIWebView
,2017-02-02 17:15:11.338 ThaliTest[3213:8454476] [CDVTimer][handleopenurl] 1.659989ms
,2017-02-02 17:15:11.350 ThaliTest[3213:8454476] [CDVTimer][intentandnavigationfilter] 10.580003ms
2017-02-02 17:15:11.351 ThaliTest[3213:8454476] [CDVTimer][gesturehandler] 0.386059ms
2017-02-02 17:15:11.351 ThaliTest[3213:8454476] [CDVTimer][TotalPluginStartup] 14.702022ms
,2017-02-02 17:15:17.146 ThaliTest[3213:8454476] Resetting plugins due to page load.
,2017-02-02 17:15:20.450 ThaliTest[3213:8454476] Finished load of: file:///var/mobile/Containers/Bundle/Application/6C3B0609-17A6-4BF9-A7E8-2BA38F366B9D/ThaliTest.app/www/index.html
,2017-02-02 17:15:20.762 ThaliTest[3213:8454476] JXcore Cordova plugin initializing
2017-02-02 17:15:20.763 ThaliTest[3213:8454660] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-02 16:15:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-02 16:15:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-02 16:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-02-02 16:15:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-02 16:15:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-02-02 16:16:15 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  39.04371798038483
,Failed to execute UT.
,2017-02-02 16:16:15 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
