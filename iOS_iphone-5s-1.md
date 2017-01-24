#### Test 1027067423e9264e_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1027067423e9264e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/F1ABECC1-2227-4A46-B41F-635F9072B47F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F1ABECC1-2227-4A46-B41F-635F9072B47F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1027067423e9264e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1027067423e9264e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/905E39EE-CEF1-42DF-A105-026521F9B74F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54953"
,(lldb)     command script import "/tmp/F1ABECC1-2227-4A46-B41F-635F9072B47F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2017-01-24 08:02:04.168 ThaliTest[2767:6934804] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/52F4133C-FCF0-4839-9851-5A400AE8554C/Library/Cookies/Cookies.binarycookies
,2017-01-24 08:02:04.672 ThaliTest[2767:6934804] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-24 08:02:04.673 ThaliTest[2767:6934804] Multi-tasking -> Device: YES, App: YES
,2017-01-24 08:02:04.693 ThaliTest[2767:6934804] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 08:02:05.500 ThaliTest[2767:6934804] Using UIWebView
2017-01-24 08:02:05.503 ThaliTest[2767:6934804] [CDVTimer][handleopenurl] 0.171006ms
,2017-01-24 08:02:05.508 ThaliTest[2767:6934804] [CDVTimer][intentandnavigationfilter] 4.611015ms
2017-01-24 08:02:05.508 ThaliTest[2767:6934804] [CDVTimer][gesturehandler] 0.160992ms
2017-01-24 08:02:05.508 ThaliTest[2767:6934804] [CDVTimer][TotalPluginStartup] 5.659997ms
,2017-01-24 08:02:08.713 ThaliTest[2767:6934804] Resetting plugins due to page load.
,2017-01-24 08:02:10.300 ThaliTest[2767:6934804] Finished load of: file:///var/mobile/Containers/Bundle/Application/905E39EE-CEF1-42DF-A105-026521F9B74F/ThaliTest.app/www/index.html
,2017-01-24 08:02:10.505 ThaliTest[2767:6934804] JXcore Cordova plugin initializing
,2017-01-24 08:02:10.506 ThaliTest[2767:6934983] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-24 07:02:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-24 07:02:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 07:02:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-24 07:02:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-24 07:02:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-24 07:02:50 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.59836995601654
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
