#### Test 8552588757d25d6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588757d25d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/ED047DB6-9558-4431-8E17-F690FBBAA236/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/ED047DB6-9558-4431-8E17-F690FBBAA236/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588757d25d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588757d25d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/BC2F027F-8CA2-4667-A7C6-E2F358EC28F0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51907"
,(lldb)     command script import "/tmp/ED047DB6-9558-4431-8E17-F690FBBAA236/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 09:06:46.234 ThaliTest[767:964056] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A13DF887-9AC5-484F-B449-CFCECFC0967F/Library/Cookies/Cookies.binarycookies
,2016-09-16 09:06:46.559 ThaliTest[767:964056] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 09:06:46.561 ThaliTest[767:964056] Multi-tasking -> Device: YES, App: YES
,2016-09-16 09:06:46.583 ThaliTest[767:964056] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 09:06:47.013 ThaliTest[767:964056] Using UIWebView
,2016-09-16 09:06:47.020 ThaliTest[767:964056] [CDVTimer][handleopenurl] 0.393033ms
,2016-09-16 09:06:47.030 ThaliTest[767:964056] [CDVTimer][intentandnavigationfilter] 9.504020ms
2016-09-16 09:06:47.031 ThaliTest[767:964056] [CDVTimer][gesturehandler] 0.383019ms
2016-09-16 09:06:47.032 ThaliTest[767:964056] [CDVTimer][TotalPluginStartup,] 11.977971ms
,2016-09-16 09:06:52.741 ThaliTest[767:964056] Resetting plugins due to page load.
,2016-09-16 09:06:53.030 ThaliTest[767:964056] Finished load of: file:///var/containers/Bundle/Application/BC2F027F-8CA2-4667-A7C6-E2F358EC28F0/ThaliTest.app/www/index.html
,2016-09-16 09:06:53.374 ThaliTest[767:964056] JXcore Cordova plugin initializing
,2016-09-16 09:06:53.374 ThaliTest[767:964269] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 09:07:00.129 ThaliTest[767:964269] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 09:07:00.129 ThaliTest[767:964269] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 09:07:00.130 ThaliTest[767:964269] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 09:07:00.132 ThaliTest[767:964269] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 09:07:00.524 ThaliTest[767:964269] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003629982471466064
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
