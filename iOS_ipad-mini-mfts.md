#### Test 99373674dc17873_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99373674dc17873/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9DA25666-EAE3-45EE-B465-FB0F07626895/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/9DA25666-EAE3-45EE-B465-FB0F07626895/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99373674dc17873/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99373674dc17873/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9223E362-85B3-4156-87A0-3DDDC6246C2C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56597"
,(lldb)     command script import "/tmp/9DA25666-EAE3-45EE-B465-FB0F07626895/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 10:50:40.063 ThaliTest[994:3015837] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B3916717-DF3E-4393-B3B7-03D5415CFE60/Library/Cookies/Cookies.binarycookies
,2016-12-27 10:50:40.220 ThaliTest[994:3015837] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 10:50:40.223 ThaliTest[994:3015837] Multi-tasking -> Device: YES, App: YES
,2016-12-27 10:50:40.248 ThaliTest[994:3015837] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 10:50:41.044 ThaliTest[994:3015837] Using UIWebView
,2016-12-27 10:50:41.050 ThaliTest[994:3015837] [CDVTimer][handleopenurl] 0.478983ms
,2016-12-27 10:50:41.058 ThaliTest[994:3015837] [CDVTimer][intentandnavigationfilter] 7.582009ms
2016-12-27 10:50:41.059 ThaliTest[994:3015837] [CDVTimer][gesturehandler] 0.330985ms
2016-12-27 10:50:41.059 ThaliTest[994:3015837] [CDVTimer][TotalPluginStartup] 9.784997ms
,2016-12-27 10:50:51.644 ThaliTest[994:3015837] Resetting plugins due to page load.
,2016-12-27 10:50:52.418 ThaliTest[994:3015837] Finished load of: file:///var/containers/Bundle/Application/9223E362-85B3-4156-87A0-3DDDC6246C2C/ThaliTest.app/www/index.html
,2016-12-27 10:50:52.651 ThaliTest[994:3015837] JXcore Cordova plugin initializing
,2016-12-27 10:50:52.653 ThaliTest[994:3016033] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 09:51:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 09:51:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 09:51:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-27 09:51:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 09:51:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-27 09:52:02 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.94990402460098
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
