#### Test 102706742aeb8de5_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102706742aeb8de5/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/93486FA1-885C-4720-8B05-63863C687CDE/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/93486FA1-885C-4720-8B05-63863C687CDE/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102706742aeb8de5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102706742aeb8de5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3BE284E1-31FE-49C1-8E45-D1B5C3A98109/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52270"
,(lldb)     command script import "/tmp/93486FA1-885C-4720-8B05-63863C687CDE/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-30 08:45:27.492 ThaliTest[2058:7657235] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7C8F9BAC-4F19-4E6E-B992-DD543F3FCA19/Library/Cookies/Cookies.binarycookies
,2017-01-30 08:45:27.644 ThaliTest[2058:7657235] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-30 08:45:27.647 ThaliTest[2058:7657235] Multi-tasking -> Device: YES, App: YES
,2017-01-30 08:45:27.674 ThaliTest[2058:7657235] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-30 08:45:28.350 ThaliTest[2058:7657235] Using UIWebView
,2017-01-30 08:45:28.356 ThaliTest[2058:7657235] [CDVTimer][handleopenurl] 0.622988ms
,2017-01-30 08:45:28.364 ThaliTest[2058:7657235] [CDVTimer][intentandnavigationfilter] 7.514000ms
2017-01-30 08:45:28.365 ThaliTest[2058:7657235] [CDVTimer][gesturehandler] 0.328004ms
2017-01-30 08:45:28.365 ThaliTest[2058:7657235] [CDVTimer][TotalPluginStartup] 9.830952ms
,2017-01-30 08:45:37.920 ThaliTest[2058:7657235] Resetting plugins due to page load.
,2017-01-30 08:45:38.670 ThaliTest[2058:7657235] Finished load of: file:///var/containers/Bundle/Application/3BE284E1-31FE-49C1-8E45-D1B5C3A98109/ThaliTest.app/www/index.html
,2017-01-30 08:45:38.919 ThaliTest[2058:7657235] JXcore Cordova plugin initializing
,2017-01-30 08:45:38.921 ThaliTest[2058:7657403] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-30 07:46:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-30 07:46:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-30 07:46:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-01-30 07:46:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-30 07:46:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-30 07:46:54 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  33.42454701662064
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
