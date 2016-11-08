#### Test 896247960fcbde9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/757DA9C4-877D-47D8-9EA1-1BC8D68E98E7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/757DA9C4-877D-47D8-9EA1-1BC8D68E98E7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/098D7041-E743-415A-B3F9-641184A3A99C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64599"
,(lldb)     command script import "/tmp/757DA9C4-877D-47D8-9EA1-1BC8D68E98E7/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-11-08 11:17:12.990 ThaliTest[3197:7884487] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3DDB1916-FBCA-43B8-89C9-D2870D2102D2/Library/Cookies/Cookies.binarycookies
,2016-11-08 11:17:13.065 ThaliTest[3197:7884487] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-08 11:17:13.068 ThaliTest[3197:7884487] Multi-tasking -> Device: YES, App: YES
,2016-11-08 11:17:13.089 ThaliTest[3197:7884487] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-08 11:17:13.529 ThaliTest[3197:7884487] Using UIWebView
,2016-11-08 11:17:13.536 ThaliTest[3197:7884487] [CDVTimer][handleopenurl] 0.506997ms
,2016-11-08 11:17:13.544 ThaliTest[3197:7884487] [CDVTimer][intentandnavigationfilter] 7.285953ms
2016-11-08 11:17:13.545 ThaliTest[3197:7884487] [CDVTimer][gesturehandler] 0.340044ms
2016-11-08 11:17:13.545 ThaliTest[3197:7884487] [CDVTimer][TotalPluginS,tartup] 9.745002ms
,2016-11-08 11:17:18.952 ThaliTest[3197:7884487] Resetting plugins due to page load.
,2016-11-08 11:17:19.350 ThaliTest[3197:7884487] Finished load of: file:///var/containers/Bundle/Application/098D7041-E743-415A-B3F9-641184A3A99C/ThaliTest.app/www/index.html
,2016-11-08 11:17:19.679 ThaliTest[3197:7884487] JXcore Cordova plugin initializing
,2016-11-08 11:17:19.680 ThaliTest[3197:7884664] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-08 10:17:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-08 10:17:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-08 10:17:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-08 10:17:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-08 10:17:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-08 10:18:00 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  30.21263200044632
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
