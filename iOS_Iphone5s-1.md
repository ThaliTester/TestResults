#### Test 85046911b7c1908_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911b7c1908/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/415E9413-DFBC-47F1-BB88-A08FB765400E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/415E9413-DFBC-47F1-BB88-A08FB765400E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911b7c1908/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911b7c1908/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BD4390FA-3864-4E84-9CBA-7ED7CA63CF08/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65148"
,(lldb)     command script import "/tmp/415E9413-DFBC-47F1-BB88-A08FB765400E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 11:20:31.312 ThaliTest[3437:6937231] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3587440F-B39F-48C1-9FBD-DDF3C1CEC642/Library/Cookies/Cookies.binarycookies
,2016-09-28 11:20:31.432 ThaliTest[3437:6937231] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 11:20:31.434 ThaliTest[3437:6937231] Multi-tasking -> Device: YES, App: YES
,2016-09-28 11:20:31.456 ThaliTest[3437:6937231] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 11:20:33.108 ThaliTest[3437:6937231] Using UIWebView
,2016-09-28 11:20:33.116 ThaliTest[3437:6937231] [CDVTimer][handleopenurl] 0.617027ms
,2016-09-28 11:20:33.125 ThaliTest[3437:6937231] [CDVTimer][intentandnavigationfilter] 8.332014ms
2016-09-28 11:20:33.126 ThaliTest[3437:6937231] [CDVTimer][gesturehandler] 0.379980ms
2016-09-28 11:20:33.126 ThaliTest[3437:6937231] [CDVTimer][TotalPluginStartup] 11.173964ms
,2016-09-28 11:20:39.289 ThaliTest[3437:6937231] Resetting plugins due to page load.
,2016-09-28 11:20:42.984 ThaliTest[3437:6937231] Finished load of: file:///var/mobile/Containers/Bundle/Application/BD4390FA-3864-4E84-9CBA-7ED7CA63CF08/ThaliTest.app/www/index.html
,2016-09-28 11:20:43.293 ThaliTest[3437:6937231] JXcore Cordova plugin initializing
,2016-09-28 11:20:43.295 ThaliTest[3437:6937463] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,received session: <ThaliCore.Session: 0x1300c70c0>
,Optional("C77C6B9D-DBAF-4C81-86DD-622FB8ECF736")
,nil
,nil
,Optional("86C61CE5-486C-4A75-B5C0-057D391638EC")
,Optional("EE4626D3-C3FA-4EC2-AB83-F2F00DEA7E17")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  13.73571300506592
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
