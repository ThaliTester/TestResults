#### Test 937653172c2e8c7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/3AFC4DFA-6D3E-481A-8AB1-9820294293FF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3AFC4DFA-6D3E-481A-8AB1-9820294293FF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EFD31A12-DD0E-498D-B139-90EA44DA171A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51158"
,(lldb)     command script import "/tmp/3AFC4DFA-6D3E-481A-8AB1-9820294293FF/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 11:51:37.080 ThaliTest[5708:12389772] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EE062BCD-6874-4C0D-BBF8-037435BD5D4D/Library/Cookies/Cookies.binarycookies
,2016-11-17 11:51:37.317 ThaliTest[5708:12389772] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-17 11:51:37.318 ThaliTest[5708:12389772] Multi-tasking -> Device: YES, App: YES
,2016-11-17 11:51:37.330 ThaliTest[5708:12389772] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 11:51:38.145 ThaliTest[5708:12389772] Using UIWebView
,2016-11-17 11:51:38.148 ThaliTest[5708:12389772] [CDVTimer][handleopenurl] 0.101984ms
,2016-11-17 11:51:38.150 ThaliTest[5708:12389772] [CDVTimer][intentandnavigationfilter] 1.834989ms
2016-11-17 11:51:38.150 ThaliTest[5708:12389772] [CDVTimer][gesturehandler] 0.082970ms
2016-11-17 11:51:38.150 ThaliTest[5708:12389772] [CDVTimer][TotalPluginStartup] 2.455950ms
,2016-11-17 11:51:41.274 ThaliTest[5708:12389772] Resetting plugins due to page load.
,2016-11-17 11:51:42.697 ThaliTest[5708:12389772] Finished load of: file:///var/mobile/Containers/Bundle/Application/EFD31A12-DD0E-498D-B139-90EA44DA171A/ThaliTest.app/www/index.html
,2016-11-17 11:51:42.835 ThaliTest[5708:12389772] JXcore Cordova plugin initializing
,2016-11-17 11:51:42.836 ThaliTest[5708:12389943] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 10:51:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 10:51:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 10:51:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 10:51:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 10:51:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-17 10:52:27 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  34.85615605115891
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
