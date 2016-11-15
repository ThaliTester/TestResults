#### Test 9376531715755df_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9376531715755df/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/703CD725-62E8-478A-9D4B-0AB88E173925/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/703CD725-62E8-478A-9D4B-0AB88E173925/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9376531715755df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9376531715755df/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E9F4471B-50DA-4AFB-AE23-A196240A94AD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63767"
,(lldb)     command script import "/tmp/703CD725-62E8-478A-9D4B-0AB88E173925/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-15 18:29:02.659 ThaliTest[5734:14586930] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C2E09D71-542E-4C67-AAC2-112073A3D075/Library/Cookies/Cookies.binarycookies
,2016-11-15 18:29:03.149 ThaliTest[5734:14586930] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-15 18:29:03.150 ThaliTest[5734:14586930] Multi-tasking -> Device: YES, App: YES
,2016-11-15 18:29:03.169 ThaliTest[5734:14586930] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-15 18:29:03.947 ThaliTest[5734:14586930] Using UIWebView
,2016-11-15 18:29:03.950 ThaliTest[5734:14586930] [CDVTimer][handleopenurl] 0.169992ms
2016-11-15 18:29:03.953 ThaliTest[5734:14586930] [CDVTimer][intentandnavigationfilter] 2.834976ms
2016-11-15 18:29:03.954 ThaliTest[5734:14586930] [CDVTimer][gesturehandler] 0.124991ms
2016-11-15 18:29:03.954 ThaliTest[5734:14586930] [CDVTimer][TotalPluginStartup] 4.540980ms
,2016-11-15 18:29:06.956 ThaliTest[5734:14586930] Resetting plugins due to page load.
,2016-11-15 18:29:08.407 ThaliTest[5734:14586930] Finished load of: file:///var/mobile/Containers/Bundle/Application/E9F4471B-50DA-4AFB-AE23-A196240A94AD/ThaliTest.app/www/index.html
,2016-11-15 18:29:08.598 ThaliTest[5734:14586930] JXcore Cordova plugin initializing
,2016-11-15 18:29:08.599 ThaliTest[5734:14587094] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-15 17:29:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-15 17:29:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-15 17:29:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-15 17:29:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-15 17:29:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-15 17:29:45 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.74538898468018
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
