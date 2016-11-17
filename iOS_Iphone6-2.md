#### Test 935721672ca5349_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/935721672ca5349/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/B7DFA186-8867-4F30-B240-CD501FB6BBBB/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/B7DFA186-8867-4F30-B240-CD501FB6BBBB/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/935721672ca5349/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/935721672ca5349/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/58875A5A-A4CF-4033-AA5C-BD0914C68355/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58671"
,(lldb)     command script import "/tmp/B7DFA186-8867-4F30-B240-CD501FB6BBBB/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 05:37:31.534 ThaliTest[3632:8189437] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8A76C933-FF48-424D-BDE1-21D98303F6AD/Library/Cookies/Cookies.binarycookies
,2016-11-17 05:37:31.574 ThaliTest[3632:8189437] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-17 05:37:31.575 ThaliTest[3632:8189437] Multi-tasking -> Device: YES, App: YES
,2016-11-17 05:37:31.592 ThaliTest[3632:8189437] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 05:37:31.901 ThaliTest[3632:8189437] Using UIWebView
,2016-11-17 05:37:31.906 ThaliTest[3632:8189437] [CDVTimer][handleopenurl] 0.202000ms
,2016-11-17 05:37:31.910 ThaliTest[3632:8189437] [CDVTimer][intentandnavigationfilter] 3.584027ms
2016-11-17 05:37:31.910 ThaliTest[3632:8189437] [CDVTimer][gesturehandler] 0.137985ms
2016-11-17 05:37:31.910 ThaliTest[3632:8189437] [CDVTimer][TotalPluginStartup] 4.741967ms
,2016-11-17 05:37:37.451 ThaliTest[3632:8189437] Resetting plugins due to page load.
,2016-11-17 05:37:37.918 ThaliTest[3632:8189437] Finished load of: file:///var/containers/Bundle/Application/58875A5A-A4CF-4033-AA5C-BD0914C68355/ThaliTest.app/www/index.html
,2016-11-17 05:37:38.260 ThaliTest[3632:8189437] JXcore Cordova plugin initializing
,2016-11-17 05:37:38.261 ThaliTest[3632:8189639] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 13:37:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 13:37:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 13:37:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 13:37:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 13:37:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-17 13:38:12 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.8272260427475
**,**TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
