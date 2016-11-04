#### Test 8962479671c5ab8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DA911052-CEB5-4D42-9109-0DFEF492D430/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DA911052-CEB5-4D42-9109-0DFEF492D430/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/398AEC8C-8CD2-418B-BCA4-9A563A7F756D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49250"
,(lldb)     command script import "/tmp/DA911052-CEB5-4D42-9109-0DFEF492D430/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-04 14:14:49.018 ThaliTest[3032:7352873] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/53ABFDB9-7AEE-4C9F-B387-3BBCE06297DF/Library/Cookies/Cookies.binarycookies
,2016-11-04 14:14:49.113 ThaliTest[3032:7352873] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-04 14:14:49.115 ThaliTest[3032:7352873] Multi-tasking -> Device: YES, App: YES
,2016-11-04 14:14:49.139 ThaliTest[3032:7352873] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-04 14:14:49.634 ThaliTest[3032:7352873] Using UIWebView
,2016-11-04 14:14:49.642 ThaliTest[3032:7352873] [CDVTimer][handleopenurl] 0.560999ms
,2016-11-04 14:14:49.649 ThaliTest[3032:7352873] [CDVTimer][intentandnavigationfilter] 7.403970ms
2016-11-04 14:14:49.650 ThaliTest[3032:7352873] [CDVTimer][gesturehandler] 0.287950ms
2016-11-04 14:14:49.651 ThaliTest[3032:7352873] [CDVTimer][TotalPluginStartup] 9.930968ms
,2016-11-04 14:14:55.133 ThaliTest[3032:7352873] Resetting plugins due to page load.
,2016-11-04 14:14:55.490 ThaliTest[3032:7352873] Finished load of: file:///var/containers/Bundle/Application/398AEC8C-8CD2-418B-BCA4-9A563A7F756D/ThaliTest.app/www/index.html
,2016-11-04 14:14:55.821 ThaliTest[3032:7352873] JXcore Cordova plugin initializing
,2016-11-04 14:14:55.822 ThaliTest[3032:7353054] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-04 13:15:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-04 13:15:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-04 13:15:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-04 13:15:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-04 13:15:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-04 13:15:33 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  26.94888401031494
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
