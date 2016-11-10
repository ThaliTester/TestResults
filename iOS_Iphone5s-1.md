#### Test 910208789f3a884_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/910208789f3a884/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7B1A63BC-0D01-4645-BDE5-47AB8E2358AB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7B1A63BC-0D01-4645-BDE5-47AB8E2358AB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/910208789f3a884/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/910208789f3a884/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/699221E5-0A00-436E-9383-D23F5B880DC0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57843"
,(lldb)     command script import "/tmp/7B1A63BC-0D01-4645-BDE5-47AB8E2358AB/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-10 14:45:22.369 ThaliTest[5496:13819130] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E51A0633-9076-4964-8EAD-3A1CB6AE1740/Library/Cookies/Cookies.binarycookies
,2016-11-10 14:45:22.431 ThaliTest[5496:13819130] Apache Cordova native platform version 4.2.1 is starting.
2016-11-10 14:45:22.432 ThaliTest[5496:13819130] Multi-tasking -> Device: YES, App: YES
,2016-11-10 14:45:22.450 ThaliTest[5496:13819130] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 14:45:23.227 ThaliTest[5496:13819130] Using UIWebView
,2016-11-10 14:45:23.231 ThaliTest[5496:13819130] [CDVTimer][handleopenurl] 0.177979ms
2016-11-10 14:45:23.234 ThaliTest[5496:13819130] [CDVTimer][intentandnavigationfilter] 2.723038ms
2016-11-10 14:45:23.234 ThaliTest[5496:13819130] [CDVTimer][gesturehan,dler] 0.128031ms
2016-11-10 14:45:23.235 ThaliTest[5496:13819130] [CDVTimer][TotalPluginStartup] 3.681004ms
,2016-11-10 14:45:26.210 ThaliTest[5496:13819130] Resetting plugins due to page load.
,2016-11-10 14:45:27.829 ThaliTest[5496:13819130] Finished load of: file:///var/mobile/Containers/Bundle/Application/699221E5-0A00-436E-9383-D23F5B880DC0/ThaliTest.app/www/index.html
,2016-11-10 14:45:28.023 ThaliTest[5496:13819130] JXcore Cordova plugin initializing
,2016-11-10 14:45:28.024 ThaliTest[5496:13819294] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 13:45:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-10 13:45:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-10 13:45:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-10 13:45:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-10 13:45:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-10 13:46:04 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.045166015625
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
