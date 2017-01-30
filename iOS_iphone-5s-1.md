#### Test 102706742aeb8de5_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102706742aeb8de5/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/74A6592A-6BB4-4F28-90FB-E094F2A820A4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/74A6592A-6BB4-4F28-90FB-E094F2A820A4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102706742aeb8de5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102706742aeb8de5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ADDAEFCB-BB75-4F9B-AD3B-9A14EE81B2E3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52272"
,(lldb)     command script import "/tmp/74A6592A-6BB4-4F28-90FB-E094F2A820A4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-30 08:46:16.192 ThaliTest[3043:7901874] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EB314420-CC94-4755-97BA-30D10FADE4EA/Library/Cookies/Cookies.binarycookies
,2017-01-30 08:46:16.267 ThaliTest[3043:7901874] Apache Cordova native platform version 4.3.1 is starting.
2017-01-30 08:46:16.268 ThaliTest[3043:7901874] Multi-tasking -> Device: YES, App: YES
,2017-01-30 08:46:16.288 ThaliTest[3043:7901874] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-30 08:46:17.230 ThaliTest[3043:7901874] Using UIWebView
,2017-01-30 08:46:17.234 ThaliTest[3043:7901874] [CDVTimer][handleopenurl] 0.169992ms
,2017-01-30 08:46:17.238 ThaliTest[3043:7901874] [CDVTimer][intentandnavigationfilter] 3.546953ms
2017-01-30 08:46:17.238 ThaliTest[3043:7901874] [CDVTimer][gesturehandler] 0.153005ms
2017-01-30 08:46:17.238 ThaliTest[3043:7901874] [CDVTimer][TotalPluginStartup] 4.638970ms
,2017-01-30 08:46:20.699 ThaliTest[3043:7901874] Resetting plugins due to page load.
,2017-01-30 08:46:22.244 ThaliTest[3043:7901874] Finished load of: file:///var/mobile/Containers/Bundle/Application/ADDAEFCB-BB75-4F9B-AD3B-9A14EE81B2E3/ThaliTest.app/www/index.html
,2017-01-30 08:46:22.563 ThaliTest[3043:7901874] JXcore Cordova plugin initializing
,2017-01-30 08:46:22.564 ThaliTest[3043:7902037] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-30 07:46:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-30 07:46:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-30 07:46:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-30 07:46:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-30 07:46:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-30 07:47:02 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  23.95104098320007
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
