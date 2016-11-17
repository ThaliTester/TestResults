#### Test 935721672ca5349_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/935721672ca5349/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/99023A0D-8D0C-415B-8B13-A8FC87F18B9C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/99023A0D-8D0C-415B-8B13-A8FC87F18B9C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/935721672ca5349/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/935721672ca5349/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DAB419DE-EEEA-43A9-B949-00AE393C6C52/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58655"
,(lldb)     command script import "/tmp/99023A0D-8D0C-415B-8B13-A8FC87F18B9C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 14:37:17.674 ThaliTest[5887:14876721] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A3ABCAFE-ECED-4E87-A4F7-B5E79783904E/Library/Cookies/Cookies.binarycookies
,2016-11-17 14:37:17.734 ThaliTest[5887:14876721] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-17 14:37:17.736 ThaliTest[5887:14876721] Multi-tasking -> Device: YES, App: YES
,2016-11-17 14:37:17.753 ThaliTest[5887:14876721] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 14:37:18.572 ThaliTest[5887:14876721] Using UIWebView
2016-11-17 14:37:18.575 ThaliTest[5887:14876721] [CDVTimer][handleopenurl] 0.155032ms
2016-11-17 14:37:18.578 ThaliTest[5887:14876721] [CDVTimer][intentandnavigationfilter] 2.752006ms
2016,-11-17 14:37:18.578 ThaliTest[5887:14876721] [CDVTimer][gesturehandler] 0.137031ms
2016-11-17 14:37:18.578 ThaliTest[5887:14876721] [CDVTimer][TotalPluginStartup] 3.681004ms
,2016-11-17 14:37:21.650 ThaliTest[5887:14876721] Resetting plugins due to page load.
,2016-11-17 14:37:23.302 ThaliTest[5887:14876721] Finished load of: file:///var/mobile/Containers/Bundle/Application/DAB419DE-EEEA-43A9-B949-00AE393C6C52/ThaliTest.app/www/index.html
,2016-11-17 14:37:23.497 ThaliTest[5887:14876721] JXcore Cordova plugin initializing
,2016-11-17 14:37:23.498 ThaliTest[5887:14876900] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 13:37:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 13:37:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 13:37:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 13:37:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 13:37:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-17 13:37:59 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.19364500045776
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
