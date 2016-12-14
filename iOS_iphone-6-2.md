#### Test 97920233248158d_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/97920233248158d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E6346937-5BF0-46C0-98BE-2B36F1B65E77/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/E6346937-5BF0-46C0-98BE-2B36F1B65E77/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/97920233248158d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/97920233248158d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5BA6410E-3DAE-476A-B03C-31EA09FB223C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56671"
,(lldb)     command script import "/tmp/E6346937-5BF0-46C0-98BE-2B36F1B65E77/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-14 15:09:52.255 ThaliTest[751:927222] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8D548A26-31A1-441C-9B28-CFD6314527DC/Library/Cookies/Cookies.binarycookies
,2016-12-14 15:09:52.337 ThaliTest[751:927222] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-14 15:09:52.340 ThaliTest[751:927222] Multi-tasking -> Device: YES, App: YES
,2016-12-14 15:09:52.366 ThaliTest[751:927222] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-14 15:09:52.798 ThaliTest[751:927222] Using UIWebView
,2016-12-14 15:09:52.806 ThaliTest[751:927222] [CDVTimer][handleopenurl] 0.320017ms
,2016-12-14 15:09:52.815 ThaliTest[751:927222] [CDVTimer][intentandnavigationfilter] 8.442998ms
2016-12-14 15:09:52.816 ThaliTest[751:927222] [CDVTimer][gesturehandler] 0.295043ms
2016-12-14 15:09:52.816 ThaliTest[751:927222] [CDVTimer][TotalPluginStartup] 11.017978ms
,2016-12-14 15:09:58.755 ThaliTest[751:927222] Resetting plugins due to page load.
,2016-12-14 15:09:59.072 ThaliTest[751:927222] Finished load of: file:///var/containers/Bundle/Application/5BA6410E-3DAE-476A-B03C-31EA09FB223C/ThaliTest.app/www/index.html
,2016-12-14 15:09:59.408 ThaliTest[751:927222] JXcore Cordova plugin initializing
,2016-12-14 15:09:59.409 ThaliTest[751:927431] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-14 14:10:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-14 14:10:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-14 14:10:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-14 14:10:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-14 14:10:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-14 14:10:35 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.62405997514725
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
