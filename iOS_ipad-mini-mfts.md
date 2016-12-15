#### Test 98149861816c514_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98149861816c514/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E8F7F680-0A24-458C-92EC-551AF0527BC9/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/E8F7F680-0A24-458C-92EC-551AF0527BC9/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98149861816c514/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98149861816c514/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FA16A9D3-4906-4EED-A622-26191D8156CA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51250"
,(lldb)     command script import "/tmp/E8F7F680-0A24-458C-92EC-551AF0527BC9/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-15 18:49:18.989 ThaliTest[602:1358482] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/52D9D6C6-721C-4BE3-9446-63541E3AD83F/Library/Cookies/Cookies.binarycookies
,2016-12-15 18:49:19.123 ThaliTest[602:1358482] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-15 18:49:19.126 ThaliTest[602:1358482] Multi-tasking -> Device: YES, App: YES
,2016-12-15 18:49:19.154 ThaliTest[602:1358482] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-15 18:49:19.932 ThaliTest[602:1358482] Using UIWebView
,2016-12-15 18:49:19.938 ThaliTest[602:1358482] [CDVTimer][handleopenurl] 0.461996ms
,2016-12-15 18:49:19.945 ThaliTest[602:1358482] [CDVTimer][intentandnavigationfilter] 7.180989ms
2016-12-15 18:49:19.946 ThaliTest[602:1358482] [CDVTimer][gesturehandler] 0.338972ms
2016-12-15 18:49:19.947 ThaliTest[602:1358482] [CDVTimer][TotalPluginStartup] 9.317040ms
,2016-12-15 18:49:30.521 ThaliTest[602:1358482] Resetting plugins due to page load.
,2016-12-15 18:49:31.308 ThaliTest[602:1358482] Finished load of: file:///var/containers/Bundle/Application/FA16A9D3-4906-4EED-A622-26191D8156CA/ThaliTest.app/www/index.html
,2016-12-15 18:49:31.547 ThaliTest[602:1358482] JXcore Cordova plugin initializing
,2016-12-15 18:49:31.549 ThaliTest[602:1358653] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-15 17:50:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-15 17:50:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-15 17:50:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-15 17:50:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-15 17:50:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-12-15 17:50:39 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  31.80239200592041
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
