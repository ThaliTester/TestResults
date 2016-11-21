#### Test 94407748f58d03e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/94407748f58d03e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/F73826DF-0DD6-48A1-9644-14616213F3D4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F73826DF-0DD6-48A1-9644-14616213F3D4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/94407748f58d03e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/94407748f58d03e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/89A51A3F-54E9-442A-B664-295A22A296A4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52842"
,(lldb)     command script import "/tmp/F73826DF-0DD6-48A1-9644-14616213F3D4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 15:33:13.976 ThaliTest[3799:9736601] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/96225EA0-6C53-46AC-BB71-116119A9CF7E/Library/Cookies/Cookies.binarycookies
,2016-11-21 15:33:14.061 ThaliTest[3799:9736601] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 15:33:14.064 ThaliTest[3799:9736601] Multi-tasking -> Device: YES, App: YES
,2016-11-21 15:33:14.084 ThaliTest[3799:9736601] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 15:33:14.590 ThaliTest[3799:9736601] Using UIWebView
,2016-11-21 15:33:14.597 ThaliTest[3799:9736601] [CDVTimer][handleopenurl] 0.501990ms
,2016-11-21 15:33:14.605 ThaliTest[3799:9736601] [CDVTimer][intentandnavigationfilter] 6.826997ms
2016-11-21 15:33:14.605 ThaliTest[3799:9736601] [CDVTimer][gesturehandler] 0.263989ms
2016-11-21 15:33:14.606 ThaliTest[3799:9736601] [CDVTimer][TotalPluginStartup] 9.153008ms
,2016-11-21 15:33:20.076 ThaliTest[3799:9736601] Resetting plugins due to page load.
,2016-11-21 15:33:20.476 ThaliTest[3799:9736601] Finished load of: file:///var/containers/Bundle/Application/89A51A3F-54E9-442A-B664-295A22A296A4/ThaliTest.app/www/index.html
,2016-11-21 15:33:20.817 ThaliTest[3799:9736601] JXcore Cordova plugin initializing
,2016-11-21 15:33:20.818 ThaliTest[3799:9736778] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 14:33:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 14:33:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 14:33:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 14:33:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 14:33:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-21 14:33:56 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.50506401062012
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
