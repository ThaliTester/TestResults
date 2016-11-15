#### Test 93371269d9d2d87_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93371269d9d2d87/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/0BA714C8-4A9C-4987-BF2B-6C85F0C77FDE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0BA714C8-4A9C-4987-BF2B-6C85F0C77FDE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93371269d9d2d87/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93371269d9d2d87/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B4C3C830-F649-4DD7-8A56-AD7EE6965166/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60522"
,(lldb)     command script import "/tmp/0BA714C8-4A9C-4987-BF2B-6C85F0C77FDE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-15 16:38:59.095 ThaliTest[5724:14574204] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9E5BDDD3-2460-47F1-9287-56A7A1AC2C7D/Library/Cookies/Cookies.binarycookies
,2016-11-15 16:38:59.156 ThaliTest[5724:14574204] Apache Cordova native platform version 4.2.1 is starting.
2016-11-15 16:38:59.157 ThaliTest[5724:14574204] Multi-tasking -> Device: YES, App: YES
,2016-11-15 16:38:59.176 ThaliTest[5724:14574204] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-15 16:38:59.992 ThaliTest[5724:14574204] Using UIWebView
,2016-11-15 16:38:59.997 ThaliTest[5724:14574204] [CDVTimer][handleopenurl] 0.170946ms
2016-11-15 16:39:00.000 ThaliTest[5724:14574204] [CDVTimer][intentandnavigationfilter] 2.772033ms
2016-11-15 16:39:00.000 ThaliTest[5724:14574204] [CDVTimer][gesturehandler] 0.127017ms
2016-11-15 16:39:00.000 ThaliTest[5724:14574204] [CDVTimer][TotalPluginStartup] 3.723025ms
,2016-11-15 16:39:03.062 ThaliTest[5724:14574204] Resetting plugins due to page load.
,2016-11-15 16:39:04.688 ThaliTest[5724:14574204] Finished load of: file:///var/mobile/Containers/Bundle/Application/B4C3C830-F649-4DD7-8A56-AD7EE6965166/ThaliTest.app/www/index.html
,2016-11-15 16:39:04.889 ThaliTest[5724:14574204] JXcore Cordova plugin initializing
2016-11-15 16:39:04.890 ThaliTest[5724:14574376] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-15 15:39:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-15 15:39:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-15 15:39:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-15 15:39:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-15 15:39:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-15 15:39:41 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.14536100625992
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
