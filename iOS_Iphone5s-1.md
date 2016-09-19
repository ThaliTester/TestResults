#### Test 85046911783e9ea_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0B292ABB-B74F-4369-A699-BE51D84E1B7C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0B292ABB-B74F-4369-A699-BE51D84E1B7C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/39DE5AC3-1F29-4B94-BE89-9ABE5CEB3F9B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64841"
,(lldb)     command script import "/tmp/0B292ABB-B74F-4369-A699-BE51D84E1B7C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-19 18:59:09.523 ThaliTest[2612:5534398] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/961DF0AB-91AC-43D5-A92B-7079B427F1C0/Library/Cookies/Cookies.binarycookies
,2016-09-19 18:59:09.981 ThaliTest[2612:5534398] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-19 18:59:09.983 ThaliTest[2612:5534398] Multi-tasking -> Device: YES, App: YES
,2016-09-19 18:59:10.010 ThaliTest[2612:5534398] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-19 18:59:11.912 ThaliTest[2612:5534398] Using UIWebView
,2016-09-19 18:59:11.920 ThaliTest[2612:5534398] [CDVTimer][handleopenurl] 0.863016ms
,2016-09-19 18:59:11.929 ThaliTest[2612:5534398] [CDVTimer][intentandnavigationfilter] 7.996023ms
2016-09-19 18:59:11.930 ThaliTest[2612:5534398] [CDVTimer][gesturehandler] 0.395000ms
2016-09-19 18:59:11.930 ThaliTest[2612:5534398] [CDVTimer][TotalPluginStartup] 11.162996ms
,2016-09-19 18:59:18.825 ThaliTest[2612:5534398] Resetting plugins due to page load.
,2016-09-19 18:59:22.584 ThaliTest[2612:5534398] Finished load of: file:///var/mobile/Containers/Bundle/Application/39DE5AC3-1F29-4B94-BE89-9ABE5CEB3F9B/ThaliTest.app/www/index.html
,2016-09-19 18:59:22.823 ThaliTest[2612:5534398] JXcore Cordova plugin initializing
,2016-09-19 18:59:22.824 ThaliTest[2612:5534630] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-19 18:59:30.980 ThaliTest[2612:5534630] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-19 18:59:30.980 ThaliTest[2612:5534630] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-19 18:59:30.982 ThaliTest[2612:5534630] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-19 18:59:30.984 ThaliTest[2612:5534630] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-19 18:59:31.380 ThaliTest[2612:5534630] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.005032956600189209
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
