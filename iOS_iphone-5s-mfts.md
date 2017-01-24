#### Test 102271039a5a4541_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102271039a5a4541/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/FD9978F6-39F3-462E-93DA-9276A9074178/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/FD9978F6-39F3-462E-93DA-9276A9074178/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102271039a5a4541/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102271039a5a4541/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/169B0017-B103-4EF4-825E-7E0EBC7240CB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63963"
,(lldb)     command script import "/tmp/FD9978F6-39F3-462E-93DA-9276A9074178/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 18:13:58.211 ThaliTest[689:1538337] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7D047B3B-0257-47A6-8214-DFD1D9CCB5EE/Library/Cookies/Cookies.binarycookies
,2017-01-24 18:13:58.260 ThaliTest[689:1538337] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-24 18:13:58.262 ThaliTest[689:1538337] Multi-tasking -> Device: YES, App: YES
,2017-01-24 18:13:58.274 ThaliTest[689:1538337] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 18:13:58.592 ThaliTest[689:1538337] Using UIWebView
,2017-01-24 18:13:58.596 ThaliTest[689:1538337] [CDVTimer][handleopenurl] 0.208974ms
,2017-01-24 18:13:58.601 ThaliTest[689:1538337] [CDVTimer][intentandnavigationfilter] 5.492032ms
2017-01-24 18:13:58.602 ThaliTest[689:1538337] [CDVTimer][gesturehandler] 0.189960ms
2017-01-24 18:13:58.602 ThaliTest[689:1538337] [CDVTimer][TotalPluginStartup] 6.900012ms
,2017-01-24 18:14:05.540 ThaliTest[689:1538337] Resetting plugins due to page load.
,2017-01-24 18:14:06.256 ThaliTest[689:1538337] Finished load of: file:///var/containers/Bundle/Application/169B0017-B103-4EF4-825E-7E0EBC7240CB/ThaliTest.app/www/index.html
,2017-01-24 18:14:06.691 ThaliTest[689:1538337] JXcore Cordova plugin initializing
,2017-01-24 18:14:06.692 ThaliTest[689:1538520] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-24 17:14:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-24 17:14:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 17:14:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-24 17:14:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-24 17:14:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-24 17:14:45 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.22708702087402
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
