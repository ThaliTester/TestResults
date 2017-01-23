#### Test 1027067426d01702_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1027067426d01702/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/3C437157-A724-44EA-9474-FA0FA5F86219/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3C437157-A724-44EA-9474-FA0FA5F86219/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1027067426d01702/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1027067426d01702/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8407C2DA-7F4B-4E49-8B9C-EDAE45A4F3FE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50197"
,(lldb)     command script import "/tmp/3C437157-A724-44EA-9474-FA0FA5F86219/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-23 13:39:46.899 ThaliTest[2724:6825544] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/733BAE9A-5DAC-4BB2-8622-1B60234164A6/Library/Cookies/Cookies.binarycookies
,2017-01-23 13:39:47.427 ThaliTest[2724:6825544] Apache Cordova native platform version 4.3.1 is starting.
2017-01-23 13:39:47.428 ThaliTest[2724:6825544] Multi-tasking -> Device: YES, App: YES
,2017-01-23 13:39:47.447 ThaliTest[2724:6825544] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-23 13:39:48.316 ThaliTest[2724:6825544] Using UIWebView
2017-01-23 13:39:48.319 ThaliTest[2724:6825544] [CDVTimer][handleopenurl] 0.184000ms
2017-01-23 13:39:48.324 ThaliTest[2724:6825544] [CDVTimer][intentandnavigationfilter] 4.319012ms
2017-01,-23 13:39:48.324 ThaliTest[2724:6825544] [CDVTimer][gesturehandler] 0.174999ms
2017-01-23 13:39:48.324 ThaliTest[2724:6825544] [CDVTimer][TotalPluginStartup] 5.373001ms
,2017-01-23 13:39:51.700 ThaliTest[2724:6825544] Resetting plugins due to page load.
,2017-01-23 13:39:53.304 ThaliTest[2724:6825544] Finished load of: file:///var/mobile/Containers/Bundle/Application/8407C2DA-7F4B-4E49-8B9C-EDAE45A4F3FE/ThaliTest.app/www/index.html
,2017-01-23 13:39:53.516 ThaliTest[2724:6825544] JXcore Cordova plugin initializing
,2017-01-23 13:39:53.517 ThaliTest[2724:6825723] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-23 12:40:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-23 12:40:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-23 12:40:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-23 12:40:09 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2017-01-23 12:40:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-23 12:40:33 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.85788202285767
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
