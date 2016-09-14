#### Test 8526390229a14d1_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1A4296D0-1C12-4A28-94E1-B6BFBCA0C954/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1A4296D0-1C12-4A28-94E1-B6BFBCA0C954/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/41B17C8D-B6B9-484A-9BF3-8E087E94D5CB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50115"
,(lldb)     command script import "/tmp/1A4296D0-1C12-4A28-94E1-B6BFBCA0C954/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 22:14:57.021 ThaliTest[621:774747] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A303BEAA-F4C9-4401-9F88-6C6DE45216B3/Library/Cookies/Cookies.binarycookies
,2016-09-14 22:14:57.089 ThaliTest[621:774747] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 22:14:57.091 ThaliTest[621:774747] Multi-tasking -> Device: YES, App: YES
,2016-09-14 22:14:57.106 ThaliTest[621:774747] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 22:14:57.514 ThaliTest[621:774747] Using UIWebView
,2016-09-14 22:14:57.522 ThaliTest[621:774747] [CDVTimer][handleopenurl] 0.452995ms
,2016-09-14 22:14:57.530 ThaliTest[621:774747] [CDVTimer][intentandnavigationfilter] 7.769048ms
2016-09-14 22:14:57.531 ThaliTest[621:774747] [CDVTimer][gesturehandler] 0.292957ms
2016-09-14 22:14:57.531 ThaliTest[621:774747] [CDVTimer][TotalPluginStartup,] 10.141015ms
,2016-09-14 22:15:02.530 ThaliTest[621:774747] Resetting plugins due to page load.
,2016-09-14 22:15:02.878 ThaliTest[621:774747] Finished load of: file:///var/containers/Bundle/Application/41B17C8D-B6B9-484A-9BF3-8E087E94D5CB/ThaliTest.app/www/index.html
,2016-09-14 22:15:03.303 ThaliTest[621:774747] JXcore Cordova plugin initializing
,2016-09-14 22:15:03.304 ThaliTest[621:774902] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x1468948f0>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-14 22:15:24.991 ThaliTest[621:774747] BTM: attaching to BTServer
,2016-09-14 22:15:27.602 ThaliTest[621:774747] BTM: local device power state changed
2016-09-14 22:15:27.603 ThaliTest[621:774747] BTM: power is now off
,2016-09-14 22:15:28.350 ThaliTest[621:774747] BTM: local device power state changed
2016-09-14 22:15:28.351 ThaliTest[621:774747] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  17.71932798624039
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
