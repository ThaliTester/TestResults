#### Test 83261120b3e784a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83261120b3e784a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/84FBC36D-6EC9-4BF9-939C-8B4A9BADF3CB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/84FBC36D-6EC9-4BF9-939C-8B4A9BADF3CB/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83261120b3e784a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83261120b3e784a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0E9B1206-B0C9-4AE6-A72C-0FC7759C7593/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60263"
,(lldb)     command script import "/tmp/84FBC36D-6EC9-4BF9-939C-8B4A9BADF3CB/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 12:06:22.675 ThaliTest[1336:2686085] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6EF95591-BEE2-4294-95A0-9042602BBEFA/Library/Cookies/Cookies.binarycookies
,2016-08-31 12:06:23.166 ThaliTest[1336:2686085] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 12:06:23.168 ThaliTest[1336:2686085] Multi-tasking -> Device: YES, App: YES
,2016-08-31 12:06:23.195 ThaliTest[1336:2686085] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 12:06:25.240 ThaliTest[1336:2686085] Using UIWebView
,2016-08-31 12:06:25.249 ThaliTest[1336:2686085] [CDVTimer][handleopenurl] 0.442982ms
,2016-08-31 12:06:25.257 ThaliTest[1336:2686085] [CDVTimer][intentandnavigationfilter] 8.148015ms
2016-08-31 12:06:25.258 ThaliTest[1336:2686085] [CDVTimer][gesturehandler] 0.396013ms
2016-08-31 12:06:25.259 ThaliTest[1336:2686085] [CDVTimer][TotalPluginS,tartup] 11.983991ms
,2016-08-31 12:06:31.338 ThaliTest[1336:2686085] Resetting plugins due to page load.
,2016-08-31 12:06:34.604 ThaliTest[1336:2686085] Finished load of: file:///var/mobile/Containers/Bundle/Application/0E9B1206-B0C9-4AE6-A72C-0FC7759C7593/ThaliTest.app/www/index.html
,2016-08-31 12:06:34.849 ThaliTest[1336:2686085] JXcore Cordova plugin initializing
,2016-08-31 12:06:34.851 ThaliTest[1336:2686338] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-31 12:06:42.950 ThaliTest[1336:2686338] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-31 12:06:42.951 ThaliTest[1336:2686338] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-31 12:06:42.951 ThaliTest[1336:2686338] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-31 12:06:42.953 ThaliTest[1336:2686338] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-31 12:06:43.343 ThaliTest[1336:2686338] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003023028373718262
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
