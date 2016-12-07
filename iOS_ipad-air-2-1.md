#### Test 96524298ae159c7_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/5ED5CA77-C7DF-4C0C-BFA3-6F67D5DB3E17/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5ED5CA77-C7DF-4C0C-BFA3-6F67D5DB3E17/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96524298ae159c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/047B0CAD-E462-44AA-A64D-3DB16378BE01/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58231"
,(lldb)     command script import "/tmp/5ED5CA77-C7DF-4C0C-BFA3-6F67D5DB3E17/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-12-07 12:07:44.341 ThaliTest[367:247000] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/622B3E68-7F19-44E4-A169-5E8D07807FD8/Library/Cookies/Cookies.binarycookies
,2016-12-07 12:07:44.701 ThaliTest[367:247000] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 12:07:44.703 ThaliTest[367:247000] Multi-tasking -> Device: YES, App: YES
,2016-12-07 12:07:44.722 ThaliTest[367:247000] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 12:07:46.747 ThaliTest[367:247000] Using UIWebView
,2016-12-07 12:07:46.754 ThaliTest[367:247000] [CDVTimer][handleopenurl] 0.470996ms
,2016-12-07 12:07:46.761 ThaliTest[367:247000] [CDVTimer][intentandnavigationfilter] 6.718993ms
,2016-12-07 12:07:46.762 ThaliTest[367:247000] [CDVTimer][gesturehandler] 0.275016ms
,2016-12-07 12:07:46.762 ThaliTest[367:247000] [CDVTimer][TotalPluginStartup] 9.029031ms
,2016-12-07 12:07:53.284 ThaliTest[367:247000] Resetting plugins due to page load.
,2016-12-07 12:07:56.349 ThaliTest[367:247000] Finished load of: file:///var/mobile/Containers/Bundle/Application/047B0CAD-E462-44AA-A64D-3DB16378BE01/ThaliTest.app/www/index.html
,2016-12-07 12:07:56.590 ThaliTest[367:247000] JXcore Cordova plugin initializing
,2016-12-07 12:07:56.590 ThaliTest[367:247228] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 11:08:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 11:08:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 11:08:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-07 11:08:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 11:08:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 11:08:32 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.9342890381813
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
