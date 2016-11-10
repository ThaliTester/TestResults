#### Test 910208789f3a884_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/910208789f3a884/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/13752108-206A-4E10-BB33-B96F4FBD1532/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/13752108-206A-4E10-BB33-B96F4FBD1532/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/910208789f3a884/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/910208789f3a884/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/19B4544D-7297-44D0-BDB2-7F6DA4D2CEA9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57845"
,(lldb)     command script import "/tmp/13752108-206A-4E10-BB33-B96F4FBD1532/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-10 05:45:29.747 ThaliTest[3277:7303994] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/92529602-E652-4908-80EA-D3E660C63C39/Library/Cookies/Cookies.binarycookies
,2016-11-10 05:45:29.784 ThaliTest[3277:7303994] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-10 05:45:29.785 ThaliTest[3277:7303994] Multi-tasking -> Device: YES, App: YES
,2016-11-10 05:45:29.796 ThaliTest[3277:7303994] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 05:45:30.163 ThaliTest[3277:7303994] Using UIWebView
2016-11-10 05:45:30.168 ThaliTest[3277:7303994] [CDVTimer][handleopenurl] 0.239968ms
,2016-11-10 05:45:30.173 ThaliTest[3277:7303994] [CDVTimer][intentandnavigationfilter] 4.616022ms
,2016-11-10 05:45:30.173 ThaliTest[3277:7303994] [CDVTimer][gesturehandler] 0.317037ms
,2016-11-10 05:45:30.174 ThaliTest[3277:7303994] [CDVTimer][TotalPluginStartup] 6.314039ms
,2016-11-10 05:45:37.187 ThaliTest[3277:7303994] Resetting plugins due to page load.
,2016-11-10 05:45:37.893 ThaliTest[3277:7303994] Finished load of: file:///var/containers/Bundle/Application/19B4544D-7297-44D0-BDB2-7F6DA4D2CEA9/ThaliTest.app/www/index.html
,2016-11-10 05:45:38.254 ThaliTest[3277:7303994] JXcore Cordova plugin initializing
,2016-11-10 05:45:38.255 ThaliTest[3277:7304161] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 13:45:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-10 13:45:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-10 13:45:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-10 13:45:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-10 13:45:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-10 13:46:13 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.3726019859314
**,**TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
