#### Test 98312760b2c4df9_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98312760b2c4df9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/83A50831-4888-4AEC-8C6C-014E1E056415/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/83A50831-4888-4AEC-8C6C-014E1E056415/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98312760b2c4df9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98312760b2c4df9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/44998E0D-51D7-4996-9159-09FC7C34D6AD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61612"
,(lldb)     command script import "/tmp/83A50831-4888-4AEC-8C6C-014E1E056415/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 15:13:24.817 ThaliTest[1078:2001093] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F5CE940F-6732-4A83-B055-A07605C6790C/Library/Cookies/Cookies.binarycookies
,2016-12-19 15:13:24.931 ThaliTest[1078:2001093] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 15:13:24.932 ThaliTest[1078:2001093] Multi-tasking -> Device: YES, App: YES
,2016-12-19 15:13:24.951 ThaliTest[1078:2001093] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 15:13:26.569 ThaliTest[1078:2001093] Using UIWebView
,2016-12-19 15:13:26.580 ThaliTest[1078:2001093] [CDVTimer][handleopenurl] 0.477016ms
,2016-12-19 15:13:26.591 ThaliTest[1078:2001093] [CDVTimer][intentandnavigationfilter] 10.270000ms
2016-12-19 15:13:26.592 ThaliTest[1078:2001093] [CDVTimer][gesturehandler] 0.431001ms
2016-12-19 15:13:26.593 ThaliTest[1078:2001093] [CDVTimer][TotalPluginStartup] 13.153017ms
,2016-12-19 15:13:32.345 ThaliTest[1078:2001093] Resetting plugins due to page load.
,2016-12-19 15:13:35.833 ThaliTest[1078:2001093] Finished load of: file:///var/mobile/Containers/Bundle/Application/44998E0D-51D7-4996-9159-09FC7C34D6AD/ThaliTest.app/www/index.html
,2016-12-19 15:13:36.135 ThaliTest[1078:2001093] JXcore Cordova plugin initializing
,2016-12-19 15:13:36.136 ThaliTest[1078:2001308] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 14:13:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 14:13:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 14:13:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-19 14:13:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 14:13:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-19 14:14:15 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  26.16772699356079
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
