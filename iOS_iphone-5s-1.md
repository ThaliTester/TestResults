#### Test 99530606e7215e5_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A41E0ECD-68E6-4D47-A247-AA6A1FA2153A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A41E0ECD-68E6-4D47-A247-AA6A1FA2153A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4C9E02E4-1D14-44DA-9F4D-3936B4AC94F8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60308"
,(lldb)     command script import "/tmp/A41E0ECD-68E6-4D47-A247-AA6A1FA2153A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-03 14:55:07.338 ThaliTest[1905:4279199] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AB57C378-060C-426B-A182-183E34351AB5/Library/Cookies/Cookies.binarycookies
,2017-01-03 14:55:07.840 ThaliTest[1905:4279199] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-03 14:55:07.841 ThaliTest[1905:4279199] Multi-tasking -> Device: YES, App: YES
,2017-01-03 14:55:07.860 ThaliTest[1905:4279199] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-03 14:55:08.671 ThaliTest[1905:4279199] Using UIWebView
,2017-01-03 14:55:08.676 ThaliTest[1905:4279199] [CDVTimer][handleopenurl] 0.165999ms
,2017-01-03 14:55:08.681 ThaliTest[1905:4279199] [CDVTimer][intentandnavigationfilter] 4.528999ms
2017-01-03 14:55:08.681 ThaliTest[1905:4279199] [CDVTimer][gesturehandler] 0.155985ms
2017-01-03 14:55:08.681 ThaliTest[1905:4279199] [CDVTimer][TotalPluginS,tartup] 5.678952ms
,2017-01-03 14:55:11.825 ThaliTest[1905:4279199] Resetting plugins due to page load.
,2017-01-03 14:55:13.296 ThaliTest[1905:4279199] Finished load of: file:///var/mobile/Containers/Bundle/Application/4C9E02E4-1D14-44DA-9F4D-3936B4AC94F8/ThaliTest.app/www/index.html
,2017-01-03 14:55:13.551 ThaliTest[1905:4279199] JXcore Cordova plugin initializing
,2017-01-03 14:55:13.552 ThaliTest[1905:4279375] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-03 13:55:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-03 13:55:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-03 13:55:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-03 13:55:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-03 13:55:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-03 13:55:51 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.20794600248337
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
