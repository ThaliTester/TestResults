#### Test 102585911d0c1950_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102585911d0c1950/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D2CAB418-EBE0-44A5-90E4-0E1A735030E1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D2CAB418-EBE0-44A5-90E4-0E1A735030E1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102585911d0c1950/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102585911d0c1950/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C340991D-A966-4419-A89D-842E044E2FEA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52107"
,(lldb)     command script import "/tmp/D2CAB418-EBE0-44A5-90E4-0E1A735030E1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-23 15:33:51.200 ThaliTest[2732:6837868] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D5477107-1CC8-4E4A-8F54-5D67ACE7DD60/Library/Cookies/Cookies.binarycookies
,2017-01-23 15:33:51.271 ThaliTest[2732:6837868] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-23 15:33:51.272 ThaliTest[2732:6837868] Multi-tasking -> Device: YES, App: YES
,2017-01-23 15:33:51.290 ThaliTest[2732:6837868] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-23 15:33:52.134 ThaliTest[2732:6837868] Using UIWebView
,2017-01-23 15:33:52.139 ThaliTest[2732:6837868] [CDVTimer][handleopenurl] 0.168979ms
,2017-01-23 15:33:52.144 ThaliTest[2732:6837868] [CDVTimer][intentandnavigationfilter] 4.506946ms
2017-01-23 15:33:52.144 ThaliTest[2732:6837868] [CDVTimer][gesturehandler] 0.170946ms
2017-01-23 15:33:52.145 ThaliTest[2732:6837868] [CDVTimer][TotalPluginStartup] 5.638957ms
,2017-01-23 15:33:55.373 ThaliTest[2732:6837868] Resetting plugins due to page load.
,2017-01-23 15:33:57.139 ThaliTest[2732:6837868] Finished load of: file:///var/mobile/Containers/Bundle/Application/C340991D-A966-4419-A89D-842E044E2FEA/ThaliTest.app/www/index.html
,2017-01-23 15:33:57.351 ThaliTest[2732:6837868] JXcore Cordova plugin initializing
,2017-01-23 15:33:57.352 ThaliTest[2732:6838037] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-23 14:34:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-23 14:34:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-23 14:34:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-23 14:34:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-23 14:34:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-23 14:34:36 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  22.93329501152039
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
