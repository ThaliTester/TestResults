#### Test 862144504e2d579_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/862144504e2d579/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B1F7F21B-3328-4034-B450-53B26289A15E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B1F7F21B-3328-4034-B450-53B26289A15E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/862144504e2d579/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/862144504e2d579/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0619AB76-162D-477C-87F2-2F68C8F35447/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64518"
,(lldb)     command script import "/tmp/B1F7F21B-3328-4034-B450-53B26289A15E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 00:43:30.209 ThaliTest[1089:1667248] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DBECC92E-36D1-4F3F-BB11-7D795A52A268/Library/Cookies/Cookies.binarycookies
,2016-09-22 00:43:30.282 ThaliTest[1089:1667248] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 00:43:30.285 ThaliTest[1089:1667248] Multi-tasking -> Device: YES, App: YES
,2016-09-22 00:43:30.300 ThaliTest[1089:1667248] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 00:43:30.815 ThaliTest[1089:1667248] Using UIWebView
,2016-09-22 00:43:30.822 ThaliTest[1089:1667248] [CDVTimer][handleopenurl] 0.477970ms
,2016-09-22 00:43:30.830 ThaliTest[1089:1667248] [CDVTimer][intentandnavigationfilter] 7.247984ms
2016-09-22 00:43:30.831 ThaliTest[1089:1667248] [CDVTimer][gesturehandler] 0.307977ms
2016-09-22 00:43:30.831 ThaliTest[1089:1667248] [CDVTimer][TotalPluginStartup] 9.661019ms
,2016-09-22 00:43:36.126 ThaliTest[1089:1667248] Resetting plugins due to page load.
,2016-09-22 00:43:36.514 ThaliTest[1089:1667248] Finished load of: file:///var/containers/Bundle/Application/0619AB76-162D-477C-87F2-2F68C8F35447/ThaliTest.app/www/index.html
,2016-09-22 00:43:36.844 ThaliTest[1089:1667248] JXcore Cordova plugin initializing
,2016-09-22 00:43:36.845 ThaliTest[1089:1667427] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x12789b710>
,Optional("D76EB99F-4FB6-4C94-BC9B-A32FA725BED7")
nil
,nil
,Optional("80BD54D4-4543-4ACF-812A-AB1A51AE7E04")
,Optional("0A6E869B-42B8-47E3-A6C4-28039A26BDE8")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 00:43:58.340 ThaliTest[1089:1667248] BTM: attaching to BTServer
,2016-09-22 00:43:59.099 ThaliTest[1089:1667248] BTM: local device power state changed
2016-09-22 00:43:59.100 ThaliTest[1089:1667248] BTM: power is now on
,2016-09-22 00:44:03.840 ThaliTest[1089:1667248] BTM: local device power state changed
2016-09-22 00:44:03.840 ThaliTest[1089:1667248] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  19.55923998355865
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
