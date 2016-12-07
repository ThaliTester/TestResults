#### Test 96524298edd5c74_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/7F970102-09AC-47A5-9A60-368ACFB70A3A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7F970102-09AC-47A5-9A60-368ACFB70A3A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/24439768-BDE3-4BC7-86D9-32A2E10FD49D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60873"
,(lldb)     command script import "/tmp/7F970102-09AC-47A5-9A60-368ACFB70A3A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 12:51:08.282 ThaliTest[376:252359] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/84F1BB37-23BB-4D0E-93ED-CD109D90FB24/Library/Cookies/Cookies.binarycookies
,2016-12-07 12:51:08.619 ThaliTest[376:252359] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 12:51:08.620 ThaliTest[376:252359] Multi-tasking -> Device: YES, App: YES
,2016-12-07 12:51:08.640 ThaliTest[376:252359] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 12:51:10.604 ThaliTest[376:252359] Using UIWebView
,2016-12-07 12:51:10.611 ThaliTest[376:252359] [CDVTimer][handleopenurl] 0.383973ms
,2016-12-07 12:51:10.618 ThaliTest[376:252359] [CDVTimer][intentandnavigationfilter] 6.516993ms
,2016-12-07 12:51:10.619 ThaliTest[376:252359] [CDVTimer][gesturehandler] 0.280976ms
,2016-12-07 12:51:10.619 ThaliTest[376:252359] [CDVTimer][TotalPluginStartup] 9.064972ms
,2016-12-07 12:51:17.390 ThaliTest[376:252359] Resetting plugins due to page load.
,2016-12-07 12:51:20.973 ThaliTest[376:252359] Finished load of: file:///var/mobile/Containers/Bundle/Application/24439768-BDE3-4BC7-86D9-32A2E10FD49D/ThaliTest.app/www/index.html
,2016-12-07 12:51:21.203 ThaliTest[376:252359] JXcore Cordova plugin initializing
,2016-12-07 12:51:21.204 ThaliTest[376:252606] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
JXcore engine is started
,2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
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
,Total duration:  25.06567800045013
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
