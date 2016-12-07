#### Test 95321062fff4ed0_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/BFA27EDA-DD78-4F7E-92E7-EF2019B82EAD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BFA27EDA-DD78-4F7E-92E7-EF2019B82EAD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D657D0B3-AFD7-434D-B0AC-C358BAE5F390/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57313"
,(lldb)     command script import "/tmp/BFA27EDA-DD78-4F7E-92E7-EF2019B82EAD/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 18:32:07.929 ThaliTest[442:294016] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/09FD3F20-52F4-4E3C-88F9-F94FA7194F91/Library/Cookies/Cookies.binarycookies
,2016-12-07 18:32:08.259 ThaliTest[442:294016] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 18:32:08.261 ThaliTest[442:294016] Multi-tasking -> Device: YES, App: YES
,2016-12-07 18:32:08.277 ThaliTest[442:294016] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 18:32:10.394 ThaliTest[442:294016] Using UIWebView
,2016-12-07 18:32:10.401 ThaliTest[442:294016] [CDVTimer][handleopenurl] 0.369012ms
,2016-12-07 18:32:10.408 ThaliTest[442:294016] [CDVTimer][intentandnavigationfilter] 6.303966ms
,2016-12-07 18:32:10.409 ThaliTest[442:294016] [CDVTimer][gesturehandler] 0.272989ms
2016-12-07 18:32:10.409 ThaliTest[442:294016] [CDVTimer][TotalPluginStartup] 8.532047ms
,2016-12-07 18:32:17.730 ThaliTest[442:294016] Resetting plugins due to page load.
,2016-12-07 18:32:21.227 ThaliTest[442:294016] Finished load of: file:///var/mobile/Containers/Bundle/Application/D657D0B3-AFD7-434D-B0AC-C358BAE5F390/ThaliTest.app/www/index.html
,2016-12-07 18:32:21.495 ThaliTest[442:294016] JXcore Cordova plugin initializing
,2016-12-07 18:32:21.496 ThaliTest[442:294262] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 17:32:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 17:32:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 17:32:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-07 17:32:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 17:32:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 17:32:57 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.48837095499039
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
