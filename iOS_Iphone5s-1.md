#### Test 83276082be030e3_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83276082be030e3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E7814D91-730E-49D3-8D4B-97A1F2749CF3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E7814D91-730E-49D3-8D4B-97A1F2749CF3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83276082be030e3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83276082be030e3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A5F77C8F-06D9-40E3-A1B1-E8F79AD8B51F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55372"
,(lldb)     command script import "/tmp/E7814D91-730E-49D3-8D4B-97A1F2749CF3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 10:02:17.547 ThaliTest[2325:4864357] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/83591FA3-7552-4A2F-B127-3BE94DDE6122/Library/Cookies/Cookies.binarycookies
,2016-09-15 10:02:17.813 ThaliTest[2325:4864357] Apache Cordova native platform version 4.1.1 is starting.
2016-09-15 10:02:17.814 ThaliTest[2325:4864357] Multi-tasking -> Device: YES, App: YES
,2016-09-15 10:02:17.834 ThaliTest[2325:4864357] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 10:02:18.646 ThaliTest[2325:4864357] Using UIWebView
2016-09-15 10:02:18.649 ThaliTest[2325:4864357] [CDVTimer][handleopenurl] 0.146985ms
,2016-09-15 10:02:18.653 ThaliTest[2325:4864357] [CDVTimer][intentandnavigationfilter] 3.862023ms
2016-09-15 10:02:18.653 ThaliTest[2325:4864357] [CDVTimer][gesturehandler] 0.153005ms
2016-09-15 10:02:18.653 ThaliTest[2325:4864357] [CDVTimer][TotalPluginS,tartup] 4.779994ms
,2016-09-15 10:02:21.748 ThaliTest[2325:4864357] Resetting plugins due to page load.
,2016-09-15 10:02:23.206 ThaliTest[2325:4864357] Finished load of: file:///var/mobile/Containers/Bundle/Application/A5F77C8F-06D9-40E3-A1B1-E8F79AD8B51F/ThaliTest.app/www/index.html
,2016-09-15 10:02:23.215 ThaliTest[2325:4864357] JXcore Cordova plugin initializing
,2016-09-15 10:02:23.216 ThaliTest[2325:4864525] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 10:02:31.176 ThaliTest[2325:4864525] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-15 10:02:31.177 ThaliTest[2325:4864525] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-15 10:02:31.178 ThaliTest[2325:4864525] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 10:02:31.181 ThaliTest[2325:4864525] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-09-15 10:02:31.575 ThaliTest[2325:4864525] jxcore: executeNativeTests: success
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.00656503438949585
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
