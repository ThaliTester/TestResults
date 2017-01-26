#### Test 103295431c2804f2_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/103295431c2804f2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/30D6F26D-C00C-4DD6-84D9-C32F67ACFF75/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/30D6F26D-C00C-4DD6-84D9-C32F67ACFF75/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/103295431c2804f2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/103295431c2804f2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5BBBCF86-4788-4B85-851A-A162B218E965/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57440"
,(lldb)     command script import "/tmp/30D6F26D-C00C-4DD6-84D9-C32F67ACFF75/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-26 13:41:16.011 ThaliTest[2902:7275945] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/84B7040C-A59B-4AC8-86DC-40D3815F240B/Library/Cookies/Cookies.binarycookies
,2017-01-26 13:41:16.137 ThaliTest[2902:7275945] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-26 13:41:16.138 ThaliTest[2902:7275945] Multi-tasking -> Device: YES, App: YES
,2017-01-26 13:41:16.165 ThaliTest[2902:7275945] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-26 13:41:17.705 ThaliTest[2902:7275945] Using UIWebView
,2017-01-26 13:41:17.716 ThaliTest[2902:7275945] [CDVTimer][handleopenurl] 0.433028ms
,2017-01-26 13:41:17.725 ThaliTest[2902:7275945] [CDVTimer][intentandnavigationfilter] 9.090006ms
2017-01-26 13:41:17.726 ThaliTest[2902:7275945] [CDVTimer][gesturehandler] 0.382006ms
2017-01-26 13:41:17.727 ThaliTest[2902:7275945] [CDVTimer][TotalPluginS,tartup] 11.880994ms
,2017-01-26 13:41:25.180 ThaliTest[2902:7275945] Resetting plugins due to page load.
,2017-01-26 13:41:29.512 ThaliTest[2902:7275945] Finished load of: file:///var/mobile/Containers/Bundle/Application/5BBBCF86-4788-4B85-851A-A162B218E965/ThaliTest.app/www/index.html
,2017-01-26 13:41:29.828 ThaliTest[2902:7275945] JXcore Cordova plugin initializing
,2017-01-26 13:41:29.829 ThaliTest[2902:7276170] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-26 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-26 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-26 12:41:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-26 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-26 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-26 12:42:08 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.11217600107193
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
