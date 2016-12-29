#### Test 992473934db55e8_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/992473934db55e8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3903CDB4-EBF7-4F97-8BE7-CC47EEDD4731/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/3903CDB4-EBF7-4F97-8BE7-CC47EEDD4731/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/992473934db55e8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/992473934db55e8/build_ios/ThaliTest.app' (arm64).
,(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9BB0BF2A-5B7A-4989-91D3-9B7EB6B38DE5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61117"
,(lldb)     command script import "/tmp/3903CDB4-EBF7-4F97-8BE7-CC47EEDD4731/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 14:05:58.896 ThaliTest[1122:3342922] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E48C9E08-9E82-4FD9-A2EB-4BF623085F77/Library/Cookies/Cookies.binarycookies
,2016-12-29 14:05:59.036 ThaliTest[1122:3342922] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 14:05:59.038 ThaliTest[1122:3342922] Multi-tasking -> Device: YES, App: YES
,2016-12-29 14:05:59.067 ThaliTest[1122:3342922] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 14:05:59.699 ThaliTest[1122:3342922] Using UIWebView
,2016-12-29 14:05:59.705 ThaliTest[1122:3342922] [CDVTimer][handleopenurl] 0.440001ms
,2016-12-29 14:05:59.713 ThaliTest[1122:3342922] [CDVTimer][intentandnavigationfilter] 7.283986ms
2016-12-29 14:05:59.714 ThaliTest[1122:3342922] [CDVTimer][gesturehandler] 0.333011ms
2016-12-29 14:05:59.714 ThaliTest[1122:3342922] [CDVTimer][TotalPluginS,tartup] 9.436011ms
,2016-12-29 14:06:08.501 ThaliTest[1122:3342922] Resetting plugins due to page load.
,2016-12-29 14:06:09.188 ThaliTest[1122:3342922] Finished load of: file:///var/containers/Bundle/Application/9BB0BF2A-5B7A-4989-91D3-9B7EB6B38DE5/ThaliTest.app/www/index.html
,2016-12-29 14:06:09.421 ThaliTest[1122:3342922] JXcore Cordova plugin initializing
,2016-12-29 14:06:09.423 ThaliTest[1122:3343087] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 13:06:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 13:06:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 13:06:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-29 13:06:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 13:06:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-29 13:07:19 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  32.93687295913696
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
