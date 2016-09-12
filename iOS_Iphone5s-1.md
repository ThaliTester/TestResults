#### Test 846487400fb5c63_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/846487400fb5c63/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2D3358B6-7C3D-41C3-A31B-6B275BC6614E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2D3358B6-7C3D-41C3-A31B-6B275BC6614E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/846487400fb5c63/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/846487400fb5c63/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2AEA79C2-990B-415F-A54F-C46EEF4A3F25/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54632"
,(lldb)     command script import "/tmp/2D3358B6-7C3D-41C3-A31B-6B275BC6614E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 13:09:36.865 ThaliTest[2023:4419248] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0B845A7F-074C-443A-809E-3911757C2CDE/Library/Cookies/Cookies.binarycookies
,2016-09-12 13:09:37.136 ThaliTest[2023:4419248] Apache Cordova native platform version 4.1.1 is starting.
2016-09-12 13:09:37.137 ThaliTest[2023:4419248] Multi-tasking -> Device: YES, App: YES
,2016-09-12 13:09:37.156 ThaliTest[2023:4419248] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 13:09:37.923 ThaliTest[2023:4419248] Using UIWebView
2016-09-12 13:09:37.926 ThaliTest[2023:4419248] [CDVTimer][handleopenurl] 0.169992ms
,2016-09-12 13:09:37.929 ThaliTest[2023:4419248] [CDVTimer][intentandnavigationfilter] 2.868056ms
2016-09-12 13:09:37.929 ThaliTest[2023:4419248] [CDVTimer][gesturehandler] 0.145972ms
2016-09-12 13:09:37.929 ThaliTest[2023:4419248] [CDVTimer][TotalPluginStartup] 3.818989ms
,2016-09-12 13:09:40.799 ThaliTest[2023:4419248] Resetting plugins due to page load.
,2016-09-12 13:09:42.175 ThaliTest[2023:4419248] Finished load of: file:///var/mobile/Containers/Bundle/Application/2AEA79C2-990B-415F-A54F-C46EEF4A3F25/ThaliTest.app/www/index.html
,2016-09-12 13:09:42.184 ThaliTest[2023:4419248] JXcore Cordova plugin initializing
,2016-09-12 13:09:42.185 ThaliTest[2023:4419418] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-12 13:09:50.273 ThaliTest[2023:4419418] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-12 13:09:50.273 ThaliTest[2023:4419418] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-12 13:09:50.273 ThaliTest[2023:4419418] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-12 13:09:50.277 ThaliTest[2023:4419418] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-12 13:09:50.669 ThaliTest[2023:4419418] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.003500998020172119
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
