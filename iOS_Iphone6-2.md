#### Test 94407748f58d03e_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/94407748f58d03e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/6FFB8158-0A73-443C-907A-A825D6969CEB/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/6FFB8158-0A73-443C-907A-A825D6969CEB/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/94407748f58d03e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/94407748f58d03e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2604D360-5501-4C56-B40C-7E7850B12C18/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52941"
,(lldb)     command script import "/tmp/6FFB8158-0A73-443C-907A-A825D6969CEB/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 06:33:22.740 ThaliTest[3826:8701370] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AB02CE46-3C8E-4DD5-9784-16842D482F21/Library/Cookies/Cookies.binarycookies
,2016-11-21 06:33:22.777 ThaliTest[3826:8701370] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 06:33:22.778 ThaliTest[3826:8701370] Multi-tasking -> Device: YES, App: YES
,2016-11-21 06:33:22.791 ThaliTest[3826:8701370] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 06:33:23.144 ThaliTest[3826:8701370] Using UIWebView
,2016-11-21 06:33:23.151 ThaliTest[3826:8701370] [CDVTimer][handleopenurl] 0.290036ms
,2016-11-21 06:33:23.156 ThaliTest[3826:8701370] [CDVTimer][intentandnavigationfilter] 4.689991ms
2016-11-21 06:33:23.157 ThaliTest[3826:8701370] [CDVTimer][gesturehandler] 0.186980ms
2016-11-21 06:33:23.157 ThaliTest[3826:8701370] [CDVTimer][TotalPluginS,tartup] 6.362021ms
,2016-11-21 06:33:28.671 ThaliTest[3826:8701370] Resetting plugins due to page load.
,2016-11-21 06:33:29.101 ThaliTest[3826:8701370] Finished load of: file:///var/containers/Bundle/Application/2604D360-5501-4C56-B40C-7E7850B12C18/ThaliTest.app/www/index.html
,2016-11-21 06:33:29.437 ThaliTest[3826:8701370] JXcore Cordova plugin initializing
,2016-11-21 06:33:29.438 ThaliTest[3826:8701544] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 14:33:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 14:33:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 14:33:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 14:33:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 14:33:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-21 14:34:05 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.71147298812866
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
