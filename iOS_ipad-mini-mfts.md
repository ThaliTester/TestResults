#### Test 9856377413b1ea0_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9856377413b1ea0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8D1AF7B7-5276-4CB5-BB87-E40E1ADE10DB/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/8D1AF7B7-5276-4CB5-BB87-E40E1ADE10DB/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9856377413b1ea0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9856377413b1ea0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DB14FD38-39E9-4696-AF80-DB0A7864E620/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56747"
,(lldb)     command script import "/tmp/8D1AF7B7-5276-4CB5-BB87-E40E1ADE10DB/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-21 15:41:19.436 ThaliTest[795:2180783] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1DF71081-E129-4A8A-9131-9B049C9FA376/Library/Cookies/Cookies.binarycookies
,2016-12-21 15:41:19.582 ThaliTest[795:2180783] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-21 15:41:19.586 ThaliTest[795:2180783] Multi-tasking -> Device: YES, App: YES
,2016-12-21 15:41:19.616 ThaliTest[795:2180783] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-21 15:41:20.426 ThaliTest[795:2180783] Using UIWebView
,2016-12-21 15:41:20.432 ThaliTest[795:2180783] [CDVTimer][handleopenurl] 0.593007ms
,2016-12-21 15:41:20.440 ThaliTest[795:2180783] [CDVTimer][intentandnavigationfilter] 7.144988ms
2016-12-21 15:41:20.440 ThaliTest[795:2180783] [CDVTimer][gesturehandler] 0.367999ms
2016-12-21 15:41:20.441 ThaliTest[795:2180783] [CDVTimer][TotalPluginStar,tup] 9.472013ms
,2016-12-21 15:41:31.111 ThaliTest[795:2180783] Resetting plugins due to page load.
,2016-12-21 15:41:31.911 ThaliTest[795:2180783] Finished load of: file:///var/containers/Bundle/Application/DB14FD38-39E9-4696-AF80-DB0A7864E620/ThaliTest.app/www/index.html
,2016-12-21 15:41:32.163 ThaliTest[795:2180783] JXcore Cordova plugin initializing
2016-12-21 15:41:32.165 ThaliTest[795:2180973] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-21 14:42:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-21 14:42:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-21 14:42:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-21 14:42:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-21 14:42:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-21 14:42:42 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.97478902339935
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
