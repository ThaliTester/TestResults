#### Test 10258170873f290a_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5B67AB0E-5A40-488D-915C-19CC1EFF8495/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5B67AB0E-5A40-488D-915C-19CC1EFF8495/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6CE8762E-D082-4F99-B25A-DE96EAFF525D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59895"
,(lldb)     command script import "/tmp/5B67AB0E-5A40-488D-915C-19CC1EFF8495/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 12:35:35.072 ThaliTest[2786:6963168] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/73DD2036-A8FF-42D6-85DE-30C10B13995D/Library/Cookies/Cookies.binarycookies
,2017-01-24 12:35:35.140 ThaliTest[2786:6963168] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-24 12:35:35.141 ThaliTest[2786:6963168] Multi-tasking -> Device: YES, App: YES
,2017-01-24 12:35:35.158 ThaliTest[2786:6963168] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 12:35:35.996 ThaliTest[2786:6963168] Using UIWebView
,2017-01-24 12:35:36.001 ThaliTest[2786:6963168] [CDVTimer][handleopenurl] 0.176013ms
,2017-01-24 12:35:36.006 ThaliTest[2786:6963168] [CDVTimer][intentandnavigationfilter] 4.492998ms
2017-01-24 12:35:36.006 ThaliTest[2786:6963168] [CDVTimer][gesturehandler] 0.154972ms
2017-01-24 12:35:36.006 ThaliTest[2786:6963168] [CDVTimer][TotalPluginStartup] 5.634010ms
,2017-01-24 12:35:39.199 ThaliTest[2786:6963168] Resetting plugins due to page load.
,2017-01-24 12:35:40.779 ThaliTest[2786:6963168] Finished load of: file:///var/mobile/Containers/Bundle/Application/6CE8762E-D082-4F99-B25A-DE96EAFF525D/ThaliTest.app/www/index.html
,2017-01-24 12:35:40.993 ThaliTest[2786:6963168] JXcore Cordova plugin initializing
,2017-01-24 12:35:40.994 ThaliTest[2786:6963338] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-24 11:35:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-24 11:35:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 11:35:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-24 11:35:56 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2017-01-24 11:35:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-24 11:36:21 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.5145800113678
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
