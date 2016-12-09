#### Test 9728853323bc6d7_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9728853323bc6d7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/60F06F5E-4510-4DD0-B41A-1ABC639FC7A7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/60F06F5E-4510-4DD0-B41A-1ABC639FC7A7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9728853323bc6d7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9728853323bc6d7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9E568155-95C6-4FAE-990A-975305B9EDD1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59440"
,(lldb)     command script import "/tmp/60F06F5E-4510-4DD0-B41A-1ABC639FC7A7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-09 12:20:08.996 ThaliTest[509:522893] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AF39B934-E4C8-4F45-A329-FA245C7B7BDB/Library/Cookies/Cookies.binarycookies
,2016-12-09 12:20:09.348 ThaliTest[509:522893] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-09 12:20:09.350 ThaliTest[509:522893] Multi-tasking -> Device: YES, App: YES
,2016-12-09 12:20:09.369 ThaliTest[509:522893] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-09 12:20:11.279 ThaliTest[509:522893] Using UIWebView
,2016-12-09 12:20:11.289 ThaliTest[509:522893] [CDVTimer][handleopenurl] 0.347018ms
,2016-12-09 12:20:11.296 ThaliTest[509:522893] [CDVTimer][intentandnavigationfilter] 6.462991ms
,2016-12-09 12:20:11.296 ThaliTest[509:522893] [CDVTimer][gesturehandler] 0.297010ms
,2016-12-09 12:20:11.297 ThaliTest[509:522893] [CDVTimer][TotalPluginStartup] 8.756995ms
,2016-12-09 12:20:18.286 ThaliTest[509:522893] Resetting plugins due to page load.
,2016-12-09 12:20:21.615 ThaliTest[509:522893] Finished load of: file:///var/mobile/Containers/Bundle/Application/9E568155-95C6-4FAE-990A-975305B9EDD1/ThaliTest.app/www/index.html
,2016-12-09 12:20:21.886 ThaliTest[509:522893] JXcore Cordova plugin initializing
,2016-12-09 12:20:21.887 ThaliTest[509:523141] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-09 11:20:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-09 11:20:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-09 11:20:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-09 11:20:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-09 11:20:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-09 11:20:58 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  27.46860098838806
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
