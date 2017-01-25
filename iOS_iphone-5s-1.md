#### Test 102271039e649845_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102271039e649845/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/8444311C-9E71-4C95-8EF7-B570C2B4A14D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8444311C-9E71-4C95-8EF7-B570C2B4A14D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102271039e649845/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102271039e649845/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/363F467E-8FBD-4B43-AD5B-AFA58763F453/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51964"
,(lldb)     command script import "/tmp/8444311C-9E71-4C95-8EF7-B570C2B4A14D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 10:26:33.229 ThaliTest[2847:7097644] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ED26B181-710A-4FE5-9CF9-0FAEE72498C1/Library/Cookies/Cookies.binarycookies
,2017-01-25 10:26:33.301 ThaliTest[2847:7097644] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-25 10:26:33.302 ThaliTest[2847:7097644] Multi-tasking -> Device: YES, App: YES
,2017-01-25 10:26:33.322 ThaliTest[2847:7097644] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-25 10:26:34.199 ThaliTest[2847:7097644] Using UIWebView
,2017-01-25 10:26:34.203 ThaliTest[2847:7097644] [CDVTimer][handleopenurl] 0.172019ms
,2017-01-25 10:26:34.208 ThaliTest[2847:7097644] [CDVTimer][intentandnavigationfilter] 4.184008ms
2017-01-25 10:26:34.208 ThaliTest[2847:7097644] [CDVTimer][gesturehandler] 0.174046ms
2017-01-25 10:26:34.208 ThaliTest[2847:7097644] [CDVTimer][TotalPluginS,tartup] 5.342007ms
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 10:26:37.619 ThaliTest[2847:7097644] Resetting plugins due to page load.
,2017-01-25 10:26:39.265 ThaliTest[2847:7097644] Finished load of: file:///var/mobile/Containers/Bundle/Application/363F467E-8FBD-4B43-AD5B-AFA58763F453/ThaliTest.app/www/index.html
,2017-01-25 10:26:39.476 ThaliTest[2847:7097644] JXcore Cordova plugin initializing
,2017-01-25 10:26:39.477 ThaliTest[2847:7097830] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 09:26:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-25 09:26:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-25 09:26:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-25 09:26:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-25 09:26:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-25 09:27:19 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.04121398925781
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
