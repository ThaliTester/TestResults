#### Test 79763830eafb657_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830eafb657/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6D027CDF-3E02-4A52-9912-3C196541D3F6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6D027CDF-3E02-4A52-9912-3C196541D3F6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830eafb657/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830eafb657/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3E66FC36-2A90-4397-9B95-458255368FEF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58862"
,(lldb)     command script import "/tmp/6D027CDF-3E02-4A52-9912-3C196541D3F6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 12:01:19.674 ThaliTest[923:1941019] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BE480B68-669C-4BAB-8781-F3A55F40D1CD/Library/Cookies/Cookies.binarycookies
,2016-08-26 12:01:20.101 ThaliTest[923:1941019] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 12:01:20.103 ThaliTest[923:1941019] Multi-tasking -> Device: YES, App: YES
,2016-08-26 12:01:20.125 ThaliTest[923:1941019] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 12:01:21.718 ThaliTest[923:1941019] Using UIWebView
,2016-08-26 12:01:21.730 ThaliTest[923:1941019] [CDVTimer][handleopenurl] 0.524998ms
,2016-08-26 12:01:21.738 ThaliTest[923:1941019] [CDVTimer][intentandnavigationfilter] 8.149028ms
2016-08-26 12:01:21.739 ThaliTest[923:1941019] [CDVTimer][gesturehandler] 0.376046ms
2016-08-26 12:01:21.740 ThaliTest[923:1941019] [CDVTimer][TotalPluginStar,tup] 11.210978ms
,2016-08-26 12:01:27.540 ThaliTest[923:1941019] Resetting plugins due to page load.
,2016-08-26 12:01:30.654 ThaliTest[923:1941019] Finished load of: file:///var/mobile/Containers/Bundle/Application/3E66FC36-2A90-4397-9B95-458255368FEF/ThaliTest.app/www/index.html
,2016-08-26 12:01:30.904 ThaliTest[923:1941019] JXcore Cordova plugin initializing
,2016-08-26 12:01:30.905 ThaliTest[923:1941236] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 12:01:39.001 ThaliTest[923:1941236] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-26 12:01:39.002 ThaliTest[923:1941236] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-26 12:01:39.002 ThaliTest[923:1941236] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 12:01:39.005 ThaliTest[923:1941236] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 12:01:39.395 ThaliTest[923:1941236] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.0143120288848877
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
