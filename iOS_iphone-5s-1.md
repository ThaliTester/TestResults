#### Test 98149861816c514_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98149861816c514/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/50290635-EEFB-4D97-9681-7C7ABE57842D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/50290635-EEFB-4D97-9681-7C7ABE57842D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98149861816c514/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98149861816c514/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EB1A1AF4-05E5-4FF2-A06F-64A3AB2E95C3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51252"
,(lldb)     command script import "/tmp/50290635-EEFB-4D97-9681-7C7ABE57842D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-15 18:50:00.611 ThaliTest[869:1436000] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4FA8C42F-7548-49B0-9AC2-0B8C5D1F00F2/Library/Cookies/Cookies.binarycookies
,2016-12-15 18:50:00.724 ThaliTest[869:1436000] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-15 18:50:00.726 ThaliTest[869:1436000] Multi-tasking -> Device: YES, App: YES
,2016-12-15 18:50:00.754 ThaliTest[869:1436000] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-15 18:50:02.278 ThaliTest[869:1436000] Using UIWebView
,2016-12-15 18:50:02.289 ThaliTest[869:1436000] [CDVTimer][handleopenurl] 0.429988ms
,2016-12-15 18:50:02.300 ThaliTest[869:1436000] [CDVTimer][intentandnavigationfilter] 10.169983ms
2016-12-15 18:50:02.301 ThaliTest[869:1436000] [CDVTimer][gesturehandler] 0.380993ms
2016-12-15 18:50:02.301 ThaliTest[869:1436000] [CDVTimer][TotalPluginSta,rtup] 12.977958ms
,2016-12-15 18:50:08.057 ThaliTest[869:1436000] Resetting plugins due to page load.
,2016-12-15 18:50:11.563 ThaliTest[869:1436000] Finished load of: file:///var/mobile/Containers/Bundle/Application/EB1A1AF4-05E5-4FF2-A06F-64A3AB2E95C3/ThaliTest.app/www/index.html
,2016-12-15 18:50:11.882 ThaliTest[869:1436000] JXcore Cordova plugin initializing
2016-12-15 18:50:11.883 ThaliTest[869:1436239] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-15 17:50:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-15 17:50:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-15 17:50:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-15 17:50:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-15 17:50:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-15 17:50:48 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.79410201311111
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
