#### Test 96524298edd5c74_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/6FC9B2D5-68B7-413B-B525-033F38435086/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6FC9B2D5-68B7-413B-B525-033F38435086/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2DFFB356-298F-4A92-82D3-C212B26FDD16/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60874"
,(lldb)     command script import "/tmp/6FC9B2D5-68B7-413B-B525-033F38435086/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 12:51:05.730 ThaliTest[375:266467] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AF2CF291-9125-4E07-8D56-5025AF0F0871/Library/Cookies/Cookies.binarycookies
,2016-12-07 12:51:06.394 ThaliTest[375:266467] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 12:51:06.396 ThaliTest[375:266467] Multi-tasking -> Device: YES, App: YES
,2016-12-07 12:51:06.419 ThaliTest[375:266467] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 12:51:08.057 ThaliTest[375:266467] Using UIWebView
,2016-12-07 12:51:08.065 ThaliTest[375:266467] [CDVTimer][handleopenurl] 0.427008ms
,2016-12-07 12:51:08.076 ThaliTest[375:266467] [CDVTimer][intentandnavigationfilter] 10.451972ms
2016-12-07 12:51:08.077 ThaliTest[375:266467] [CDVTimer][gesturehandler] 0.438035ms
2016-12-07 12:51:08.077 ThaliTest[375:266467] [CDVTimer][TotalPluginStartup] 13.431966ms
,2016-12-07 12:51:14.296 ThaliTest[375:266467] Resetting plugins due to page load.
,2016-12-07 12:51:17.184 ThaliTest[375:266467] Finished load of: file:///var/mobile/Containers/Bundle/Application/2DFFB356-298F-4A92-82D3-C212B26FDD16/ThaliTest.app/www/index.html
,2016-12-07 12:51:17.447 ThaliTest[375:266467] JXcore Cordova plugin initializing
2016-12-07 12:51:17.448 ThaliTest[375:266693] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 11:51:55 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.97323602437973
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
