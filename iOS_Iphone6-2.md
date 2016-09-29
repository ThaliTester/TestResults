#### Test 87116923a0346c7_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87116923a0346c7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4B3C73A5-C125-440F-805B-881DD6941CB1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/4B3C73A5-C125-440F-805B-881DD6941CB1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87116923a0346c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87116923a0346c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4ED4982E-16AD-4A0A-A71A-91765747BEF9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62752"
,(lldb)     command script import "/tmp/4B3C73A5-C125-440F-805B-881DD6941CB1/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-29 00:26:16.529 ThaliTest[1839:2431977] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DBA554F9-64D0-40F5-8791-08F36BD5061E/Library/Cookies/Cookies.binarycookies
,2016-09-29 00:26:16.566 ThaliTest[1839:2431977] Apache Cordova native platform version 4.2.1 is starting.
2016-09-29 00:26:16.567 ThaliTest[1839:2431977] Multi-tasking -> Device: YES, App: YES
,2016-09-29 00:26:16.581 ThaliTest[1839:2431977] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 00:26:16.916 ThaliTest[1839:2431977] Using UIWebView
,2016-09-29 00:26:16.921 ThaliTest[1839:2431977] [CDVTimer][handleopenurl] 0.335991ms
,2016-09-29 00:26:16.926 ThaliTest[1839:2431977] [CDVTimer][intentandnavigationfilter] 4.668951ms
2016-09-29 00:26:16.926 ThaliTest[1839:2431977] [CDVTimer][gesturehandler] 0.181973ms
2016-09-29 00:26:16.927 ThaliTest[1839:2431977] [CDVTimer][TotalPluginStartup] 6.231010ms
,2016-09-29 00:26:22.503 ThaliTest[1839:2431977] Resetting plugins due to page load.
,2016-09-29 00:26:22.957 ThaliTest[1839:2431977] Finished load of: file:///var/containers/Bundle/Application/4ED4982E-16AD-4A0A-A71A-91765747BEF9/ThaliTest.app/www/index.html
,2016-09-29 00:26:23.291 ThaliTest[1839:2431977] JXcore Cordova plugin initializing
,2016-09-29 00:26:23.292 ThaliTest[1839:2432147] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  54
,Number of passed tests:  54
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  18.35519796609879
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
