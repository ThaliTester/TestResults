#### Test 85046911e91e24b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/99265B51-8A11-47A0-A634-5F2AF9F8902F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/99265B51-8A11-47A0-A634-5F2AF9F8902F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6C2F9487-E4D5-4A62-8EFC-F2CDFDAAB373/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51917"
,(lldb)     command script import "/tmp/99265B51-8A11-47A0-A634-5F2AF9F8902F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 17:16:32.812 ThaliTest[2236:4753205] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/05A52518-6EBC-4C2B-82BA-2D0481CFB6AF/Library/Cookies/Cookies.binarycookies
,2016-09-14 17:16:33.304 ThaliTest[2236:4753205] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 17:16:33.306 ThaliTest[2236:4753205] Multi-tasking -> Device: YES, App: YES
,2016-09-14 17:16:33.332 ThaliTest[2236:4753205] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 17:16:34.949 ThaliTest[2236:4753205] Using UIWebView
,2016-09-14 17:16:34.957 ThaliTest[2236:4753205] [CDVTimer][handleopenurl] 0.470996ms
,2016-09-14 17:16:34.966 ThaliTest[2236:4753205] [CDVTimer][intentandnavigationfilter] 8.054972ms
2016-09-14 17:16:34.967 ThaliTest[2236:4753205] [CDVTimer][gesturehandler] 0.362039ms
2016-09-14 17:16:34.967 ThaliTest[2236:4753205] [CDVTimer][TotalPluginS,tartup] 10.712981ms
,2016-09-14 17:16:40.684 ThaliTest[2236:4753205] Resetting plugins due to page load.
,2016-09-14 17:16:43.110 ThaliTest[2236:4753205] Finished load of: file:///var/mobile/Containers/Bundle/Application/6C2F9487-E4D5-4A62-8EFC-F2CDFDAAB373/ThaliTest.app/www/index.html
,2016-09-14 17:16:43.429 ThaliTest[2236:4753205] JXcore Cordova plugin initializing
2016-09-14 17:16:43.430 ThaliTest[2236:4753442] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 17:16:51.642 ThaliTest[2236:4753442] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 17:16:51.642 ThaliTest[2236:4753442] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 17:16:51.642 ThaliTest[2236:4753442] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 17:16:51.645 ThaliTest[2236:4753442] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-14 17:16:52.028 ThaliTest[2236:4753442] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005405962467193604
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
