#### Test 8552588757d25d6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588757d25d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E8A02B59-3403-426B-A8C7-215189D9A193/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E8A02B59-3403-426B-A8C7-215189D9A193/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588757d25d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588757d25d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0E442C37-60AE-4AC5-8728-CEC77FB82C9A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51957"
,(lldb)     command script import "/tmp/E8A02B59-3403-426B-A8C7-215189D9A193/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 09:06:48.878 ThaliTest[2429:5010799] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/13CBC863-E74F-49DB-A4E0-45C45508C124/Library/Cookies/Cookies.binarycookies
,2016-09-16 09:06:49.284 ThaliTest[2429:5010799] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 09:06:49.286 ThaliTest[2429:5010799] Multi-tasking -> Device: YES, App: YES
,2016-09-16 09:06:49.307 ThaliTest[2429:5010799] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 09:06:51.080 ThaliTest[2429:5010799] Using UIWebView
,2016-09-16 09:06:51.091 ThaliTest[2429:5010799] [CDVTimer][handleopenurl] 0.449002ms
,2016-09-16 09:06:51.099 ThaliTest[2429:5010799] [CDVTimer][intentandnavigationfilter] 8.062959ms
2016-09-16 09:06:51.100 ThaliTest[2429:5010799] [CDVTimer][gesturehandler] 0.377953ms
2016-09-16 09:06:51.101 ThaliTest[2429:5010799] [CDVTimer][TotalPluginStartup] 10.695994ms
,2016-09-16 09:06:57.014 ThaliTest[2429:5010799] Resetting plugins due to page load.
,2016-09-16 09:06:59.789 ThaliTest[2429:5010799] Finished load of: file:///var/mobile/Containers/Bundle/Application/0E442C37-60AE-4AC5-8728-CEC77FB82C9A/ThaliTest.app/www/index.html
,2016-09-16 09:07:00.035 ThaliTest[2429:5010799] JXcore Cordova plugin initializing
,2016-09-16 09:07:00.148 ThaliTest[2429:5011029] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 09:07:08.212 ThaliTest[2429:5011029] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-16 09:07:08.213 ThaliTest[2429:5011029] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 09:07:08.213 ThaliTest[2429:5011029] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 09:07:08.215 ThaliTest[2429:5011029] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 09:07:08.603 ThaliTest[2429:5011029] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003475010395050049
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
