#### Test 87116923a0346c7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87116923a0346c7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/15D99373-30ED-47F7-888B-24C6A32B91C5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/15D99373-30ED-47F7-888B-24C6A32B91C5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87116923a0346c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87116923a0346c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2B500EEF-F307-41C2-AFA2-60AF1525709F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62756"
,(lldb)     command script import "/tmp/15D99373-30ED-47F7-888B-24C6A32B91C5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 09:26:23.658 ThaliTest[1648:2617843] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3EC4976B-E5B6-44F1-B79F-49B26439C7FA/Library/Cookies/Cookies.binarycookies
,2016-09-29 09:26:23.694 ThaliTest[1648:2617843] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 09:26:23.695 ThaliTest[1648:2617843] Multi-tasking -> Device: YES, App: YES
,2016-09-29 09:26:23.708 ThaliTest[1648:2617843] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 09:26:24.024 ThaliTest[1648:2617843] Using UIWebView
,2016-09-29 09:26:24.029 ThaliTest[1648:2617843] [CDVTimer][handleopenurl] 0.187993ms
,2016-09-29 09:26:24.033 ThaliTest[1648:2617843] [CDVTimer][intentandnavigationfilter] 3.436983ms
2016-09-29 09:26:24.033 ThaliTest[1648:2617843] [CDVTimer][gesturehandler] 0.139952ms
2016-09-29 09:26:24.033 ThaliTest[1648:2617843] [CDVTimer][TotalPluginS,tartup] 4.592001ms
,2016-09-29 09:26:29.361 ThaliTest[1648:2617843] Resetting plugins due to page load.
,2016-09-29 09:26:29.741 ThaliTest[1648:2617843] Finished load of: file:///var/containers/Bundle/Application/2B500EEF-F307-41C2-AFA2-60AF1525709F/ThaliTest.app/www/index.html
,2016-09-29 09:26:30.071 ThaliTest[1648:2617843] JXcore Cordova plugin initializing
,2016-09-29 09:26:30.072 ThaliTest[1648:2618029] JXcore instance initializing
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
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  17.4326080083847
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
