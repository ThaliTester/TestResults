#### Test 8962479676fe425_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8962479676fe425/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D111437D-2677-49E2-BF9A-D0FB2C349447/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D111437D-2677-49E2-BF9A-D0FB2C349447/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8962479676fe425/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8962479676fe425/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/64107638-5836-4894-A62B-EB6DBD908738/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57530"
,(lldb)     command script import "/tmp/D111437D-2677-49E2-BF9A-D0FB2C349447/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-11-09 10:33:12.189 ThaliTest[5401:13634533] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BFD524E5-36BD-4501-BC1D-CF29CB0E4323/Library/Cookies/Cookies.binarycookies
,2016-11-09 10:33:12.308 ThaliTest[5401:13634533] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-09 10:33:12.309 ThaliTest[5401:13634533] Multi-tasking -> Device: YES, App: YES
,2016-11-09 10:33:12.338 ThaliTest[5401:13634533] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 10:33:13.778 ThaliTest[5401:13634533] Using UIWebView
,2016-11-09 10:33:13.789 ThaliTest[5401:13634533] [CDVTimer][handleopenurl] 1.242995ms
,2016-11-09 10:33:13.799 ThaliTest[5401:13634533] [CDVTimer][intentandnavigationfilter] 8.912981ms
2016-11-09 10:33:13.800 ThaliTest[5401:13634533] [CDVTimer][gesturehandler] 0.423014ms
2016-11-09 10:33:13.800 ThaliTest[5401:13634533] [CDVTimer][TotalPlug,inStartup] 12.480021ms
,2016-11-09 10:33:19.392 ThaliTest[5401:13634533] Resetting plugins due to page load.
,2016-11-09 10:33:23.128 ThaliTest[5401:13634533] Finished load of: file:///var/mobile/Containers/Bundle/Application/64107638-5836-4894-A62B-EB6DBD908738/ThaliTest.app/www/index.html
,2016-11-09 10:33:23.435 ThaliTest[5401:13634533] JXcore Cordova plugin initializing
,2016-11-09 10:33:23.436 ThaliTest[5401:13634755] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 09:33:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-09 09:33:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 09:33:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-09 09:33:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-09 09:33:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-09 09:34:00 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.55568599700928
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
