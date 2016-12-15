#### Test 981169263321dad_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/981169263321dad/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F25CF581-1E47-4290-8651-66F3780A1201/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F25CF581-1E47-4290-8651-66F3780A1201/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/981169263321dad/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/981169263321dad/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B226C42E-48A7-491F-A942-F6853AB21DE5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61979"
,(lldb)     command script import "/tmp/F25CF581-1E47-4290-8651-66F3780A1201/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-15 11:14:10.271 ThaliTest[836:1386622] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B17C1B3B-0EEE-44A9-80B6-90038DDB6842/Library/Cookies/Cookies.binarycookies
,2016-12-15 11:14:10.388 ThaliTest[836:1386622] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-15 11:14:10.389 ThaliTest[836:1386622] Multi-tasking -> Device: YES, App: YES
,2016-12-15 11:14:10.413 ThaliTest[836:1386622] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-15 11:14:11.984 ThaliTest[836:1386622] Using UIWebView
,2016-12-15 11:14:11.992 ThaliTest[836:1386622] [CDVTimer][handleopenurl] 0.424981ms
,2016-12-15 11:14:12.003 ThaliTest[836:1386622] [CDVTimer][intentandnavigationfilter] 9.662032ms
2016-12-15 11:14:12.004 ThaliTest[836:1386622] [CDVTimer][gesturehandler] 0.458002ms
2016-12-15 11:14:12.004 ThaliTest[836:1386622] [CDVTimer][TotalPluginStar,tup] 12.553990ms
,2016-12-15 11:14:17.851 ThaliTest[836:1386622] Resetting plugins due to page load.
,2016-12-15 11:14:21.299 ThaliTest[836:1386622] Finished load of: file:///var/mobile/Containers/Bundle/Application/B226C42E-48A7-491F-A942-F6853AB21DE5/ThaliTest.app/www/index.html
,2016-12-15 11:14:21.606 ThaliTest[836:1386622] JXcore Cordova plugin initializing
,2016-12-15 11:14:21.607 ThaliTest[836:1386848] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-15 10:14:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-15 10:14:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-15 10:14:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-15 10:14:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-15 10:14:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-15 10:14:59 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.77030497789383
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
