#### Test 944077483e9c5d2_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/E5F9143F-F0DE-489E-A590-1856F9816997/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/E5F9143F-F0DE-489E-A590-1856F9816997/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/501B56B0-8B0F-4C33-97D4-693F0ABB03EC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56657"
,(lldb)     command script import "/tmp/E5F9143F-F0DE-489E-A590-1856F9816997/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 10:20:10.538 ThaliTest[3706:8345925] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E4CF98F0-F224-4314-804C-8ACB922AAADB/Library/Cookies/Cookies.binarycookies
,2016-11-18 10:20:10.576 ThaliTest[3706:8345925] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 10:20:10.577 ThaliTest[3706:8345925] Multi-tasking -> Device: YES, App: YES
,2016-11-18 10:20:10.592 ThaliTest[3706:8345925] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 10:20:10.891 ThaliTest[3706:8345925] Using UIWebView
2016-11-18 10:20:10.894 ThaliTest[3706:8345925] [CDVTimer][handleopenurl] 0.177979ms
,2016-11-18 10:20:10.899 ThaliTest[3706:8345925] [CDVTimer][intentandnavigationfilter] 4.469991ms
2016-11-18 10:20:10.900 ThaliTest[3706:8345925] [CDVTimer][gesturehandler] 0.180960ms
2016-11-18 10:20:10.900 ThaliTest[3706:8345925] [CDVTimer][TotalPluginStartup] 5.630016ms
,2016-11-18 10:20:16.198 ThaliTest[3706:8345925] Resetting plugins due to page load.
,2016-11-18 10:20:16.776 ThaliTest[3706:8345925] Finished load of: file:///var/containers/Bundle/Application/501B56B0-8B0F-4C33-97D4-693F0ABB03EC/ThaliTest.app/www/index.html
,2016-11-18 10:20:17.191 ThaliTest[3706:8345925] JXcore Cordova plugin initializing
,2016-11-18 10:20:17.191 ThaliTest[3706:8346097] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 18:20:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 18:20:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 18:20:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 18:20:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 18:20:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-18 18:20:52 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.71504300832748
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
