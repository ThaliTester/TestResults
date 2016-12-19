#### Test 9856377440205b4_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9856377440205b4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A2F8CD82-C1AE-4C53-9EA1-03420365F638/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A2F8CD82-C1AE-4C53-9EA1-03420365F638/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9856377440205b4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9856377440205b4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CC1A732C-7F51-4FAB-AF18-15D7642235D1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59624"
,(lldb)     command script import "/tmp/A2F8CD82-C1AE-4C53-9EA1-03420365F638/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 14:45:28.798 ThaliTest[1071:1997431] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8D008665-FF9D-4389-AB18-173F7B59E366/Library/Cookies/Cookies.binarycookies
,2016-12-19 14:45:29.414 ThaliTest[1071:1997431] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 14:45:29.416 ThaliTest[1071:1997431] Multi-tasking -> Device: YES, App: YES
,2016-12-19 14:45:29.441 ThaliTest[1071:1997431] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 14:45:31.066 ThaliTest[1071:1997431] Using UIWebView
,2016-12-19 14:45:31.075 ThaliTest[1071:1997431] [CDVTimer][handleopenurl] 0.478029ms
,2016-12-19 14:45:31.086 ThaliTest[1071:1997431] [CDVTimer][intentandnavigationfilter] 10.931015ms
2016-12-19 14:45:31.087 ThaliTest[1071:1997431] [CDVTimer][gesturehandler] 0.415981ms
2016-12-19 14:45:31.088 ThaliTest[1071:1997431] [CDVTimer][TotalPlugin,Startup] 13.759017ms
,2016-12-19 14:45:37.050 ThaliTest[1071:1997431] Resetting plugins due to page load.
,2016-12-19 14:45:40.286 ThaliTest[1071:1997431] Finished load of: file:///var/mobile/Containers/Bundle/Application/CC1A732C-7F51-4FAB-AF18-15D7642235D1/ThaliTest.app/www/index.html
,2016-12-19 14:45:40.531 ThaliTest[1071:1997431] JXcore Cordova plugin initializing
,2016-12-19 14:45:40.532 ThaliTest[1071:1997658] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 13:45:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 13:45:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 13:45:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-19 13:45:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 13:45:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-19 13:46:18 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.15271598100662
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
