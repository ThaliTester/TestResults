#### Test 85046911c8db9f2_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c8db9f2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E7546B8F-FEBF-482C-B240-330FE5CF30C8/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/E7546B8F-FEBF-482C-B240-330FE5CF30C8/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c8db9f2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c8db9f2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/ED37EE85-2854-41DE-A10D-938445B01EE1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59784"
,(lldb)     command script import "/tmp/E7546B8F-FEBF-482C-B240-330FE5CF30C8/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 06:59:58.017 ThaliTest[1214:1552266] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8C72B6D7-A554-4378-855A-A40AD1A34BAA/Library/Cookies/Cookies.binarycookies
,2016-09-21 06:59:58.332 ThaliTest[1214:1552266] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 06:59:58.333 ThaliTest[1214:1552266] Multi-tasking -> Device: YES, App: YES
,2016-09-21 06:59:58.359 ThaliTest[1214:1552266] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 06:59:58.858 ThaliTest[1214:1552266] Using UIWebView
,2016-09-21 06:59:58.864 ThaliTest[1214:1552266] [CDVTimer][handleopenurl] 0.383973ms
,2016-09-21 06:59:58.872 ThaliTest[1214:1552266] [CDVTimer][intentandnavigationfilter] 7.182956ms
2016-09-21 06:59:58.873 ThaliTest[1214:1552266] [CDVTimer][gesturehandler] 0.337958ms
2016-09-21 06:59:58.873 ThaliTest[1214:1552266] [CDVTimer][TotalPluginS,tartup] 9.451985ms
,2016-09-21 07:00:04.682 ThaliTest[1214:1552266] Resetting plugins due to page load.
,2016-09-21 07:00:05.144 ThaliTest[1214:1552266] Finished load of: file:///var/containers/Bundle/Application/ED37EE85-2854-41DE-A10D-938445B01EE1/ThaliTest.app/www/index.html
,2016-09-21 07:00:05.547 ThaliTest[1214:1552266] JXcore Cordova plugin initializing
,2016-09-21 07:00:05.548 ThaliTest[1214:1552463] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 07:00:12.075 ThaliTest[1214:1552463] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 07:00:12.076 ThaliTest[1214:1552463] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 07:00:12.076 ThaliTest[1214:1552463] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 07:00:12.078 ThaliTest[1214:1552463] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 07:00:12.462 ThaliTest[1214:1552463] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.002740979194641113
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
