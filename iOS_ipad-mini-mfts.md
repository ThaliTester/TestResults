#### Test 978514903f1da2e_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/1EDD3E37-19D6-4DAD-A4FC-2553A3DF4F77/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/1EDD3E37-19D6-4DAD-A4FC-2553A3DF4F77/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FDA2A3A9-3E53-441F-9165-EA7B19C93881/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59841"
,(lldb)     command script import "/tmp/1EDD3E37-19D6-4DAD-A4FC-2553A3DF4F77/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-14 00:08:23.073 ThaliTest[523:1104983] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AD5E0A3E-C674-4C1E-9363-B3B26DC468F5/Library/Cookies/Cookies.binarycookies
,2016-12-14 00:08:23.219 ThaliTest[523:1104983] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-14 00:08:23.222 ThaliTest[523:1104983] Multi-tasking -> Device: YES, App: YES
,2016-12-14 00:08:23.245 ThaliTest[523:1104983] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-14 00:08:24.022 ThaliTest[523:1104983] Using UIWebView
,2016-12-14 00:08:24.034 ThaliTest[523:1104983] [CDVTimer][handleopenurl] 0.369012ms
,2016-12-14 00:08:24.041 ThaliTest[523:1104983] [CDVTimer][intentandnavigationfilter] 7.161975ms
2016-12-14 00:08:24.042 ThaliTest[523:1104983] [CDVTimer][gesturehandler] 0.331044ms
,2016-12-14 00:08:24.042 ThaliTest[523:1104983] [CDVTimer][TotalPluginStartup] 9.232998ms
,2016-12-14 00:08:34.472 ThaliTest[523:1104983] Resetting plugins due to page load.
,2016-12-14 00:08:35.256 ThaliTest[523:1104983] Finished load of: file:///var/containers/Bundle/Application/FDA2A3A9-3E53-441F-9165-EA7B19C93881/ThaliTest.app/www/index.html
,2016-12-14 00:08:35.497 ThaliTest[523:1104983] JXcore Cordova plugin initializing
,2016-12-14 00:08:35.498 ThaliTest[523:1105153] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 23:09:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 23:09:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 23:09:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-13 23:09:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 23:09:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 23:09:41 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  30.36695200204849
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
