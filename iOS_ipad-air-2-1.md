#### Test 965327534acc906_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/965327534acc906/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/F03C874E-F82E-40CA-98EF-CB3886B4DBB4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F03C874E-F82E-40CA-98EF-CB3886B4DBB4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/965327534acc906/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/965327534acc906/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D4FD1AF5-4B09-4D49-9D9E-DDF4F3A160D7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62990"
,(lldb)     command script import "/tmp/F03C874E-F82E-40CA-98EF-CB3886B4DBB4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-12-07 14:16:15.089 ThaliTest[386:262079] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2D867080-1848-4B7D-8B27-1FD9BAE090E1/Library/Cookies/Cookies.binarycookies
,2016-12-07 14:16:15.462 ThaliTest[386:262079] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 14:16:15.464 ThaliTest[386:262079] Multi-tasking -> Device: YES, App: YES
,2016-12-07 14:16:15.482 ThaliTest[386:262079] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 14:16:17.481 ThaliTest[386:262079] Using UIWebView
,2016-12-07 14:16:17.490 ThaliTest[386:262079] [CDVTimer][handleopenurl] 0.494003ms
,2016-12-07 14:16:17.499 ThaliTest[386:262079] [CDVTimer][intentandnavigationfilter] 7.822990ms
,2016-12-07 14:16:17.499 ThaliTest[386:262079] [CDVTimer][gesturehandler] 0.340998ms
,2016-12-07 14:16:17.500 ThaliTest[386:262079] [CDVTimer][TotalPluginStartup] 10.334015ms
,2016-12-07 14:16:24.109 ThaliTest[386:262079] Resetting plugins due to page load.
,2016-12-07 14:16:27.464 ThaliTest[386:262079] Finished load of: file:///var/mobile/Containers/Bundle/Application/D4FD1AF5-4B09-4D49-9D9E-DDF4F3A160D7/ThaliTest.app/www/index.html
,2016-12-07 14:16:27.669 ThaliTest[386:262079] JXcore Cordova plugin initializing
,2016-12-07 14:16:27.670 ThaliTest[386:262340] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 13:16:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 13:16:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 13:16:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-07 13:16:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 13:16:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 13:17:03 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.70462602376938
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
