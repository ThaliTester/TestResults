#### Test 93371269c81e6ec_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93371269c81e6ec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/5F2B7BB4-FF01-4776-BFFD-81F8B2DE5E7F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/5F2B7BB4-FF01-4776-BFFD-81F8B2DE5E7F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93371269c81e6ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93371269c81e6ec/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0126CD63-40A6-4DB3-B907-0CA9FDE81B67/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57412"
,(lldb)     command script import "/tmp/5F2B7BB4-FF01-4776-BFFD-81F8B2DE5E7F/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 10:44:49.414 ThaliTest[3713:8348636] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/61A5B750-F837-48A7-BE20-3FE32A52B98B/Library/Cookies/Cookies.binarycookies
,2016-11-18 10:44:49.451 ThaliTest[3713:8348636] Apache Cordova native platform version 4.2.1 is starting.
2016-11-18 10:44:49.452 ThaliTest[3713:8348636] Multi-tasking -> Device: YES, App: YES
,2016-11-18 10:44:49.467 ThaliTest[3713:8348636] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 10:44:49.846 ThaliTest[3713:8348636] Using UIWebView
,2016-11-18 10:44:49.852 ThaliTest[3713:8348636] [CDVTimer][handleopenurl] 0.276983ms
,2016-11-18 10:44:49.858 ThaliTest[3713:8348636] [CDVTimer][intentandnavigationfilter] 4.688025ms
2016-11-18 10:44:49.858 ThaliTest[3713:8348636] [CDVTimer][gesturehandler] 0.225008ms
2016-11-18 10:44:49.858 ThaliTest[3713:8348636] [CDVTimer][TotalPluginStartup] 6.312013ms
,2016-11-18 10:44:55.718 ThaliTest[3713:8348636] Resetting plugins due to page load.
,2016-11-18 10:44:56.344 ThaliTest[3713:8348636] Finished load of: file:///var/containers/Bundle/Application/0126CD63-40A6-4DB3-B907-0CA9FDE81B67/ThaliTest.app/www/index.html
,2016-11-18 10:44:56.756 ThaliTest[3713:8348636] JXcore Cordova plugin initializing
2016-11-18 10:44:56.757 ThaliTest[3713:8348803] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 18:45:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 18:45:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 18:45:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 18:45:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 18:45:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-18 18:45:32 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.27251499891281
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
