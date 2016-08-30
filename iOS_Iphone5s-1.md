#### Test 7976383051d2164_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7976383051d2164/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/390E4921-42A6-413A-BD59-CFD55D0C28F4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/390E4921-42A6-413A-BD59-CFD55D0C28F4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7976383051d2164/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7976383051d2164/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/68E572DB-9A24-42BF-99EA-75C9D5FD6FE7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50555"
,(lldb)     command script import "/tmp/390E4921-42A6-413A-BD59-CFD55D0C28F4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 11:35:25.696 ThaliTest[1223:2529791] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EC00D662-DB21-4BEC-8C64-6AD12F2AE3CF/Library/Cookies/Cookies.binarycookies
,2016-08-30 11:35:26.185 ThaliTest[1223:2529791] Apache Cordova native platform version 4.1.1 is starting.
2016-08-30 11:35:26.187 ThaliTest[1223:2529791] Multi-tasking -> Device: YES, App: YES
,2016-08-30 11:35:26.216 ThaliTest[1223:2529791] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 11:35:27.965 ThaliTest[1223:2529791] Using UIWebView
,2016-08-30 11:35:27.973 ThaliTest[1223:2529791] [CDVTimer][handleopenurl] 0.456035ms
,2016-08-30 11:35:27.982 ThaliTest[1223:2529791] [CDVTimer][intentandnavigationfilter] 8.035958ms
2016-08-30 11:35:27.983 ThaliTest[1223:2529791] [CDVTimer][gesturehandler] 0.373006ms
2016-08-30 11:35:27.983 ThaliTest[1223:2529791] [CDVTimer][TotalPluginStartup] 10.838985ms
,2016-08-30 11:35:33.913 ThaliTest[1223:2529791] Resetting plugins due to page load.
,2016-08-30 11:35:36.755 ThaliTest[1223:2529791] Finished load of: file:///var/mobile/Containers/Bundle/Application/68E572DB-9A24-42BF-99EA-75C9D5FD6FE7/ThaliTest.app/www/index.html
,2016-08-30 11:35:37.012 ThaliTest[1223:2529791] JXcore Cordova plugin initializing
,2016-08-30 11:35:37.013 ThaliTest[1223:2530013] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 11:35:45.182 ThaliTest[1223:2530013] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-30 11:35:45.183 ThaliTest[1223:2530013] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 11:35:45.184 ThaliTest[1223:2530013] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 11:35:45.186 ThaliTest[1223:2530013] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 11:35:45.571 ThaliTest[1223:2530013] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005415022373199463
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
