#### Test 994652477e4ad1f_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/994652477e4ad1f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/252F0279-A9E2-4609-8BF4-E2444D1A2DD0/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/252F0279-A9E2-4609-8BF4-E2444D1A2DD0/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/994652477e4ad1f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/994652477e4ad1f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7B3F8ECF-C11C-4F24-A1F3-727B05DD8D88/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63040"
,(lldb)     command script import "/tmp/252F0279-A9E2-4609-8BF4-E2444D1A2DD0/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 15:22:28.660 ThaliTest[1365:2602051] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ACB3A1CD-B337-40B9-85D7-227CCED03B88/Library/Cookies/Cookies.binarycookies
,2016-12-28 15:22:28.762 ThaliTest[1365:2602051] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 15:22:28.764 ThaliTest[1365:2602051] Multi-tasking -> Device: YES, App: YES
,2016-12-28 15:22:28.786 ThaliTest[1365:2602051] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 15:22:29.296 ThaliTest[1365:2602051] Using UIWebView
,2016-12-28 15:22:29.308 ThaliTest[1365:2602051] [CDVTimer][handleopenurl] 0.398993ms
,2016-12-28 15:22:29.319 ThaliTest[1365:2602051] [CDVTimer][intentandnavigationfilter] 10.125995ms
2016-12-28 15:22:29.320 ThaliTest[1365:2602051] [CDVTimer][gesturehandler] 0.908017ms
2016-12-28 15:22:29.321 ThaliTest[1365:2602051] [CDVTimer][TotalPlugin,Startup] 13.554990ms
,2016-12-28 15:22:35.111 ThaliTest[1365:2602051] Resetting plugins due to page load.
,2016-12-28 15:22:35.460 ThaliTest[1365:2602051] Finished load of: file:///var/containers/Bundle/Application/7B3F8ECF-C11C-4F24-A1F3-727B05DD8D88/ThaliTest.app/www/index.html
,2016-12-28 15:22:35.846 ThaliTest[1365:2602051] JXcore Cordova plugin initializing
,2016-12-28 15:22:35.847 ThaliTest[1365:2602225] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 14:22:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 14:22:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 14:22:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-28 14:22:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 14:22:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 14:23:13 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.22158402204514
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
