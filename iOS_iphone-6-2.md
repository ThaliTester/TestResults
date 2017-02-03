#### Test 104512680d43a431_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/104512680d43a431/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1EBFB955-5306-4B06-AD74-6E64A54874B9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/1EBFB955-5306-4B06-AD74-6E64A54874B9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/104512680d43a431/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/104512680d43a431/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/626BA372-149D-4E4C-9F7A-EBE789B6D255/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60378"
,(lldb)     command script import "/tmp/1EBFB955-5306-4B06-AD74-6E64A54874B9/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-03 13:48:41.204 ThaliTest[3927:1205139] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E8F012F7-F6AD-425A-8999-7E6303644C74/Library/Cookies/Cookies.binarycookies
,2017-02-03 13:48:41.243 ThaliTest[3927:1205139] Apache Cordova native platform version 4.3.1 is starting.
2017-02-03 13:48:41.244 ThaliTest[3927:1205139] Multi-tasking -> Device: YES, App: YES
,2017-02-03 13:48:41.257 ThaliTest[3927:1205139] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-03 13:48:41.577 ThaliTest[3927:1205139] Using UIWebView
2017-02-03 13:48:41.580 ThaliTest[3927:1205139] [CDVTimer][handleopenurl] 0.171006ms
,2017-02-03 13:48:41.584 ThaliTest[3927:1205139] [CDVTimer][intentandnavigationfilter] 4.076004ms
2017-02-03 13:48:41.585 ThaliTest[3927:1205139] [CDVTimer][gesturehandler] 0.142992ms
2017-02-03 13:48:41.585 ThaliTest[3927:1205139] [CDVTimer][TotalPluginStartup] 5.177021ms
,2017-02-03 13:48:47.505 ThaliTest[3927:1205139] Resetting plugins due to page load.
,2017-02-03 13:48:47.866 ThaliTest[3927:1205139] Finished load of: file:///var/containers/Bundle/Application/626BA372-149D-4E4C-9F7A-EBE789B6D255/ThaliTest.app/www/index.html
,2017-02-03 13:48:48.194 ThaliTest[3927:1205139] JXcore Cordova plugin initializing
,2017-02-03 13:48:48.195 ThaliTest[3927:1205327] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-03 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-03 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-03 12:48:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-02-03 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-03 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-02-03 12:49:24 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.64789301156998
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
