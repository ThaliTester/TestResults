#### Test 864536137cfe9e7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/65F7856E-7DF3-47B2-930B-27484B2CD643/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/65F7856E-7DF3-47B2-930B-27484B2CD643/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9C49CF47-4200-4ED9-B11A-EC98CE652226/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57192"
,(lldb)     command script import "/tmp/65F7856E-7DF3-47B2-930B-27484B2CD643/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 07:38:37.098 ThaliTest[2990:6098499] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/340515B0-3917-4239-8F85-578C387C38E9/Library/Cookies/Cookies.binarycookies
,2016-09-23 07:38:37.208 ThaliTest[2990:6098499] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 07:38:37.209 ThaliTest[2990:6098499] Multi-tasking -> Device: YES, App: YES
,2016-09-23 07:38:37.233 ThaliTest[2990:6098499] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 07:38:38.793 ThaliTest[2990:6098499] Using UIWebView
,2016-09-23 07:38:38.801 ThaliTest[2990:6098499] [CDVTimer][handleopenurl] 0.500977ms
,2016-09-23 07:38:38.810 ThaliTest[2990:6098499] [CDVTimer][intentandnavigationfilter] 8.396029ms
2016-09-23 07:38:38.811 ThaliTest[2990:6098499] [CDVTimer][gesturehandler] 0.422001ms
2016-09-23 07:38:38.812 ThaliTest[2990:6098499] [CDVTimer][TotalPluginS,tartup] 11.224031ms
,2016-09-23 07:38:45.099 ThaliTest[2990:6098499] Resetting plugins due to page load.
,2016-09-23 07:38:49.049 ThaliTest[2990:6098499] Finished load of: file:///var/mobile/Containers/Bundle/Application/9C49CF47-4200-4ED9-B11A-EC98CE652226/ThaliTest.app/www/index.html
,2016-09-23 07:38:49.367 ThaliTest[2990:6098499] JXcore Cordova plugin initializing
,2016-09-23 07:38:49.369 ThaliTest[2990:6098722] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x136f7da00>
,Optional("973AF1F2-37B1-42BF-9FC8-AA8B471F1092")
,nil
,nil
,Optional("2DDEFF2A-54B2-4A07-B683-047299D403EE")
,Optional("CE51A19E-88DB-41F0-8856-9880D37F9CB3")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 07:39:13.011 ThaliTest[2990:6098499] BTM: attaching to BTServer
,2016-09-23 07:39:13.723 ThaliTest[2990:6098499] BTM: local device power state changed
,2016-09-23 07:39:13.742 ThaliTest[2990:6098499] BTM: power is now on
,2016-09-23 07:39:18.444 ThaliTest[2990:6098499] BTM: local device power state changed
2016-09-23 07:39:18.445 ThaliTest[2990:6098499] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
,Number of passed tests:  50
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  20.20876097679138
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
