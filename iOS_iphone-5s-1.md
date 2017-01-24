#### Test 102271039975da4b_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102271039975da4b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/52A5D031-183D-45E4-9F66-1202EED3F763/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/52A5D031-183D-45E4-9F66-1202EED3F763/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102271039975da4b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102271039975da4b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B01823F1-807C-45EB-B841-F0B2153C2A46/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61960"
,(lldb)     command script import "/tmp/52A5D031-183D-45E4-9F66-1202EED3F763/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 16:05:51.498 ThaliTest[2797:6984970] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C2333F0B-F07A-40E2-8818-7A0B872B70CE/Library/Cookies/Cookies.binarycookies
,2017-01-24 16:05:51.565 ThaliTest[2797:6984970] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-24 16:05:51.566 ThaliTest[2797:6984970] Multi-tasking -> Device: YES, App: YES
,2017-01-24 16:05:51.585 ThaliTest[2797:6984970] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 16:05:52.414 ThaliTest[2797:6984970] Using UIWebView
,2017-01-24 16:05:52.418 ThaliTest[2797:6984970] [CDVTimer][handleopenurl] 0.387967ms
,2017-01-24 16:05:52.423 ThaliTest[2797:6984970] [CDVTimer][intentandnavigationfilter] 4.518986ms
2017-01-24 16:05:52.423 ThaliTest[2797:6984970] [CDVTimer][gesturehandler] 0.214994ms
2017-01-24 16:05:52.423 ThaliTest[2797:6984970] [CDVTimer][TotalPluginS,tartup] 5.962014ms
,2017-01-24 16:05:55.624 ThaliTest[2797:6984970] Resetting plugins due to page load.
,2017-01-24 16:05:57.387 ThaliTest[2797:6984970] Finished load of: file:///var/mobile/Containers/Bundle/Application/B01823F1-807C-45EB-B841-F0B2153C2A46/ThaliTest.app/www/index.html
,2017-01-24 16:05:57.597 ThaliTest[2797:6984970] JXcore Cordova plugin initializing
,2017-01-24 16:05:57.598 ThaliTest[2797:6985156] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-24 15:06:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-24 15:06:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 15:06:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-24 15:06:13 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2017-01-24 15:06:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-24 15:06:38 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.47074300050735
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
