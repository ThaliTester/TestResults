#### Test 994652477e4ad1f_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/994652477e4ad1f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D0B9160B-1F3E-4C1E-95C3-EEBCE866F82A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D0B9160B-1F3E-4C1E-95C3-EEBCE866F82A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/994652477e4ad1f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/994652477e4ad1f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9EC41240-5B63-4167-9CB7-6459811A2BFA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63037"
,(lldb)     command script import "/tmp/D0B9160B-1F3E-4C1E-95C3-EEBCE866F82A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 15:22:18.145 ThaliTest[1598:3364848] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4BBE7798-9444-49A8-B3C4-90888B36E11B/Library/Cookies/Cookies.binarycookies
,2016-12-28 15:22:18.261 ThaliTest[1598:3364848] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 15:22:18.263 ThaliTest[1598:3364848] Multi-tasking -> Device: YES, App: YES
,2016-12-28 15:22:18.288 ThaliTest[1598:3364848] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 15:22:19.620 ThaliTest[1598:3364848] Using UIWebView
,2016-12-28 15:22:19.628 ThaliTest[1598:3364848] [CDVTimer][handleopenurl] 0.449002ms
,2016-12-28 15:22:19.639 ThaliTest[1598:3364848] [CDVTimer][intentandnavigationfilter] 10.085046ms
2016-12-28 15:22:19.640 ThaliTest[1598:3364848] [CDVTimer][gesturehandler] 0.427008ms
2016-12-28 15:22:19.640 ThaliTest[1598:3364848] [CDVTimer][TotalPluginStartup] 13.091981ms
,2016-12-28 15:22:25.477 ThaliTest[1598:3364848] Resetting plugins due to page load.
,2016-12-28 15:22:28.831 ThaliTest[1598:3364848] Finished load of: file:///var/mobile/Containers/Bundle/Application/9EC41240-5B63-4167-9CB7-6459811A2BFA/ThaliTest.app/www/index.html
,2016-12-28 15:22:29.155 ThaliTest[1598:3364848] JXcore Cordova plugin initializing
,2016-12-28 15:22:29.157 ThaliTest[1598:3365053] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 14:22:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 14:22:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 14:22:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-28 14:22:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 14:22:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 14:23:07 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.16069096326828
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
