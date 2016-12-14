#### Test 97920233248158d_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/97920233248158d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/ED408805-AD2D-42A5-8D17-11484DFBC5E6/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/ED408805-AD2D-42A5-8D17-11484DFBC5E6/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/97920233248158d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/97920233248158d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7600569B-AB8A-48A1-AF5A-E86004E0B6F9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56663"
,(lldb)     command script import "/tmp/ED408805-AD2D-42A5-8D17-11484DFBC5E6/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-12-14 15:09:05.778 ThaliTest[549:1192410] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/04492EAD-71B8-4AD2-B3AF-239725D42478/Library/Cookies/Cookies.binarycookies
,2016-12-14 15:09:05.924 ThaliTest[549:1192410] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-14 15:09:05.928 ThaliTest[549:1192410] Multi-tasking -> Device: YES, App: YES
,2016-12-14 15:09:05.960 ThaliTest[549:1192410] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-14 15:09:06.763 ThaliTest[549:1192410] Using UIWebView
,2016-12-14 15:09:06.770 ThaliTest[549:1192410] [CDVTimer][handleopenurl] 0.393987ms
,2016-12-14 15:09:06.777 ThaliTest[549:1192410] [CDVTimer][intentandnavigationfilter] 7.244051ms
2016-12-14 15:09:06.778 ThaliTest[549:1192410] [CDVTimer][gesturehandler] 0.369012ms
2016-12-14 15:09:06.778 ThaliTest[549:1192410] [CDVTimer][TotalPluginStartup] 9.409010ms
,2016-12-14 15:09:17.423 ThaliTest[549:1192410] Resetting plugins due to page load.
,2016-12-14 15:09:18.217 ThaliTest[549:1192410] Finished load of: file:///var/containers/Bundle/Application/7600569B-AB8A-48A1-AF5A-E86004E0B6F9/ThaliTest.app/www/index.html
,2016-12-14 15:09:18.466 ThaliTest[549:1192410] JXcore Cordova plugin initializing
,2016-12-14 15:09:18.468 ThaliTest[549:1192600] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-14 14:09:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-14 14:09:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-14 14:09:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-14 14:09:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-14 14:09:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-14 14:10:25 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  30.31956899166107
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
