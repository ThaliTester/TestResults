#### Test 8962479676fe425_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8962479676fe425/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1FFF5B20-9F1D-4745-9D35-07E89671A420/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/1FFF5B20-9F1D-4745-9D35-07E89671A420/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8962479676fe425/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8962479676fe425/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/688ABC16-9DC3-4E90-8F8C-D2FD2A4FA989/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57528"
,(lldb)     command script import "/tmp/1FFF5B20-9F1D-4745-9D35-07E89671A420/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-09 01:33:10.993 ThaliTest[3189:7151991] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FF04FA79-E0DD-4260-A6C3-0A4A84E93C7C/Library/Cookies/Cookies.binarycookies
,2016-11-09 01:33:11.037 ThaliTest[3189:7151991] Apache Cordova native platform version 4.2.1 is starting.
2016-11-09 01:33:11.038 ThaliTest[3189:7151991] Multi-tasking -> Device: YES, App: YES
,2016-11-09 01:33:11.050 ThaliTest[3189:7151991] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 01:33:11.403 ThaliTest[3189:7151991] Using UIWebView
,2016-11-09 01:33:11.409 ThaliTest[3189:7151991] [CDVTimer][handleopenurl] 0.264943ms
,2016-11-09 01:33:11.414 ThaliTest[3189:7151991] [CDVTimer][intentandnavigationfilter] 4.621983ms
2016-11-09 01:33:11.415 ThaliTest[3189:7151991] [CDVTimer][gesturehandler] 0.267982ms
2016-11-09 01:33:11.415 ThaliTest[3189:7151991] [CDVTimer][TotalPluginS,tartup] 6.276011ms
,2016-11-09 01:33:17.455 ThaliTest[3189:7151991] Resetting plugins due to page load.
,2016-11-09 01:33:17.837 ThaliTest[3189:7151991] Finished load of: file:///var/containers/Bundle/Application/688ABC16-9DC3-4E90-8F8C-D2FD2A4FA989/ThaliTest.app/www/index.html
,2016-11-09 01:33:18.169 ThaliTest[3189:7151991] JXcore Cordova plugin initializing
,2016-11-09 01:33:18.170 ThaliTest[3189:7152174] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 09:33:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-09 09:33:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 09:33:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-09 09:33:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-09 09:33:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-09 09:33:54 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.11848801374435
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
