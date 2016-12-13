#### Test 9772710378c4b3e_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/D5660116-B4EB-49E2-A0DE-C6B70866CC74/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D5660116-B4EB-49E2-A0DE-C6B70866CC74/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0CBC6737-119A-451C-882D-434E5FDAD495/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54414"
,(lldb)     command script import "/tmp/D5660116-B4EB-49E2-A0DE-C6B70866CC74/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 13:33:50.134 ThaliTest[711:1106682] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BBAEBBF6-E26B-4B0D-806D-343CE93318DA/Library/Cookies/Cookies.binarycookies
,2016-12-13 13:33:50.258 ThaliTest[711:1106682] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-13 13:33:50.260 ThaliTest[711:1106682] Multi-tasking -> Device: YES, App: YES
,2016-12-13 13:33:50.290 ThaliTest[711:1106682] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 13:33:51.869 ThaliTest[711:1106682] Using UIWebView
,2016-12-13 13:33:51.878 ThaliTest[711:1106682] [CDVTimer][handleopenurl] 0.423968ms
,2016-12-13 13:33:51.888 ThaliTest[711:1106682] [CDVTimer][intentandnavigationfilter] 10.343015ms
2016-12-13 13:33:51.889 ThaliTest[711:1106682] [CDVTimer][gesturehandler] 0.385046ms
2016-12-13 13:33:51.890 ThaliTest[711:1106682] [CDVTimer][TotalPluginSta,rtup] 13.090014ms
,2016-12-13 13:33:57.675 ThaliTest[711:1106682] Resetting plugins due to page load.
,2016-12-13 13:34:00.597 ThaliTest[711:1106682] Finished load of: file:///var/mobile/Containers/Bundle/Application/0CBC6737-119A-451C-882D-434E5FDAD495/ThaliTest.app/www/index.html
,2016-12-13 13:34:00.785 ThaliTest[711:1106682] JXcore Cordova plugin initializing
,2016-12-13 13:34:00.786 ThaliTest[711:1106907] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 12:34:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 12:34:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 12:34:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-13 12:34:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 12:34:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 12:34:38 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.92534500360489
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
