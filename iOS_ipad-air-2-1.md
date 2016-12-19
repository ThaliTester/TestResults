#### Test 9856377440205b4_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9856377440205b4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A6141075-059B-4FE2-875E-6D5F7F0798F4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A6141075-059B-4FE2-875E-6D5F7F0798F4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9856377440205b4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9856377440205b4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D0B5A8AA-4986-4ECC-91A5-19A164FD4351/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59628"
,(lldb)     command script import "/tmp/A6141075-059B-4FE2-875E-6D5F7F0798F4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 14:45:32.708 ThaliTest[1031:1945677] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A744F51A-152D-4DBF-B771-2741CBADC503/Library/Cookies/Cookies.binarycookies
,2016-12-19 14:45:33.072 ThaliTest[1031:1945677] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 14:45:33.074 ThaliTest[1031:1945677] Multi-tasking -> Device: YES, App: YES
,2016-12-19 14:45:33.093 ThaliTest[1031:1945677] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 14:45:35.149 ThaliTest[1031:1945677] Using UIWebView
,2016-12-19 14:45:35.159 ThaliTest[1031:1945677] [CDVTimer][handleopenurl] 0.356972ms
,2016-12-19 14:45:35.166 ThaliTest[1031:1945677] [CDVTimer][intentandnavigationfilter] 6.955028ms
,2016-12-19 14:45:35.167 ThaliTest[1031:1945677] [CDVTimer][gesturehandler] 0.336051ms
2016-12-19 14:45:35.168 ThaliTest[1031:1945677] [CDVTimer][TotalPluginStartup] 9.254038ms
,2016-12-19 14:45:41.830 ThaliTest[1031:1945677] Resetting plugins due to page load.
,2016-12-19 14:45:45.641 ThaliTest[1031:1945677] Finished load of: file:///var/mobile/Containers/Bundle/Application/D0B5A8AA-4986-4ECC-91A5-19A164FD4351/ThaliTest.app/www/index.html
,2016-12-19 14:45:45.912 ThaliTest[1031:1945677] JXcore Cordova plugin initializing
,2016-12-19 14:45:45.913 ThaliTest[1031:1945907] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 13:45:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 13:45:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 13:45:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-19 13:45:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 13:45:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 5 seconds, with unfulfilled expectations: "Browser's mock node client received a message". in file: Optional("<unknown>"), line: 0
,2016-12-19 13:46:27 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  31.8239940404892
,Failed to execute UT.
,2016-12-19 13:46:27 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
