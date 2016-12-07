#### Test 962930629a6bd77_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/962930629a6bd77/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/D0D302A8-8501-48E1-A85A-C86560E9B0F9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/D0D302A8-8501-48E1-A85A-C86560E9B0F9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/962930629a6bd77/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/962930629a6bd77/build_ios/ThaliTest.app' (arm64).
,(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/22E781A1-4CD5-45CA-A27E-0F494421C1ED/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52834"
,(lldb)     command script import "/tmp/D0D302A8-8501-48E1-A85A-C86560E9B0F9/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 16:22:05.122 ThaliTest[333:135681] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FBE9B47C-2745-40CB-9783-9A0AB738EA82/Library/Cookies/Cookies.binarycookies
,2016-12-07 16:22:05.217 ThaliTest[333:135681] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 16:22:05.219 ThaliTest[333:135681] Multi-tasking -> Device: YES, App: YES
,2016-12-07 16:22:05.244 ThaliTest[333:135681] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 16:22:05.735 ThaliTest[333:135681] Using UIWebView
,2016-12-07 16:22:05.742 ThaliTest[333:135681] [CDVTimer][handleopenurl] 0.497997ms
,2016-12-07 16:22:05.751 ThaliTest[333:135681] [CDVTimer][intentandnavigationfilter] 8.762002ms
2016-12-07 16:22:05.752 ThaliTest[333:135681] [CDVTimer][gesturehandler] 0.289977ms
2016-12-07 16:22:05.752 ThaliTest[333:135681] [CDVTimer][TotalPluginStartup] 11.178017ms
,2016-12-07 16:22:11.700 ThaliTest[333:135681] Resetting plugins due to page load.
,2016-12-07 16:22:12.170 ThaliTest[333:135681] Finished load of: file:///var/containers/Bundle/Application/22E781A1-4CD5-45CA-A27E-0F494421C1ED/ThaliTest.app/www/index.html
,2016-12-07 16:22:12.647 ThaliTest[333:135681] JXcore Cordova plugin initializing
,2016-12-07 16:22:12.649 ThaliTest[333:135859] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 15:22:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 15:22:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 15:22:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
2016-12-07 15:22:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 15:22:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 15:22:49 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.18909299373627
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
