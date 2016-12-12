#### Test 912434547c1b96c_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/912434547c1b96c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/ADDE3258-31A3-454A-8ADF-2A133E3AE7B2/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/ADDE3258-31A3-454A-8ADF-2A133E3AE7B2/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/912434547c1b96c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/912434547c1b96c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/74BF7F31-B64A-489C-8C8D-B41CD25BCD42/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50579"
,(lldb)     command script import "/tmp/ADDE3258-31A3-454A-8ADF-2A133E3AE7B2/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-12 18:32:23.556 ThaliTest[627:697301] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/75B8B037-56BB-4086-9238-1FB16D2E7606/Library/Cookies/Cookies.binarycookies
,2016-12-12 18:32:23.638 ThaliTest[627:697301] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-12 18:32:23.640 ThaliTest[627:697301] Multi-tasking -> Device: YES, App: YES
,2016-12-12 18:32:23.659 ThaliTest[627:697301] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-12 18:32:24.184 ThaliTest[627:697301] Using UIWebView
2016-12-12 18:32:24.191 ThaliTest[627:697301] [CDVTimer][handleopenurl] 1.398981ms
,2016-12-12 18:32:24.200 ThaliTest[627:697301] [CDVTimer][intentandnavigationfilter] 8.408010ms
2016-12-12 18:32:24.201 ThaliTest[627:697301] [CDVTimer][gesturehandler] 0.320971ms
2016-12-12 18:32:24.202 ThaliTest[627:697301] [CDVTimer][TotalPluginStartup] 11.795998ms
,2016-12-12 18:32:31.758 ThaliTest[627:697301] Resetting plugins due to page load.
,2016-12-12 18:32:32.368 ThaliTest[627:697301] Finished load of: file:///var/containers/Bundle/Application/74BF7F31-B64A-489C-8C8D-B41CD25BCD42/ThaliTest.app/www/index.html
,2016-12-12 18:32:32.816 ThaliTest[627:697301] JXcore Cordova plugin initializing
2016-12-12 18:32:32.817 ThaliTest[627:697515] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-12 17:32:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-12 17:32:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-12 17:32:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":null,"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":null}'
2016-12-12 17:32:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-12 17:32:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-12 17:33:14 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  31.36050802469254
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
