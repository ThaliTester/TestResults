#### Test 8552588750d17b9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588750d17b9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C2C6B0F4-833B-4FE6-8B1B-64B543F5253B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C2C6B0F4-833B-4FE6-8B1B-64B543F5253B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588750d17b9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588750d17b9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/85538FA7-F9AA-4119-8EEB-2CBB4F81EC22/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60203"
,(lldb)     command script import "/tmp/C2C6B0F4-833B-4FE6-8B1B-64B543F5253B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 10:59:21.319 ThaliTest[2453:5026023] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E2E3DD31-17F9-4261-8D2B-6DC43DE31A58/Library/Cookies/Cookies.binarycookies
,2016-09-16 10:59:21.783 ThaliTest[2453:5026023] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 10:59:21.784 ThaliTest[2453:5026023] Multi-tasking -> Device: YES, App: YES
,2016-09-16 10:59:21.811 ThaliTest[2453:5026023] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 10:59:23.479 ThaliTest[2453:5026023] Using UIWebView
,2016-09-16 10:59:23.487 ThaliTest[2453:5026023] [CDVTimer][handleopenurl] 0.487983ms
,2016-09-16 10:59:23.496 ThaliTest[2453:5026023] [CDVTimer][intentandnavigationfilter] 8.142054ms
2016-09-16 10:59:23.497 ThaliTest[2453:5026023] [CDVTimer][gesturehandler] 0.367999ms
2016-09-16 10:59:23.498 ThaliTest[2453:5026023] [CDVTimer][TotalPluginStartup] 10.980964ms
,2016-09-16 10:59:30.153 ThaliTest[2453:5026023] Resetting plugins due to page load.
,2016-09-16 10:59:33.869 ThaliTest[2453:5026023] Finished load of: file:///var/mobile/Containers/Bundle/Application/85538FA7-F9AA-4119-8EEB-2CBB4F81EC22/ThaliTest.app/www/index.html
,2016-09-16 10:59:34.104 ThaliTest[2453:5026023] JXcore Cordova plugin initializing
,2016-09-16 10:59:34.105 ThaliTest[2453:5026253] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 10:59:42.228 ThaliTest[2453:5026253] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 10:59:42.228 ThaliTest[2453:5026253] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 10:59:42.228 ThaliTest[2453:5026253] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 10:59:42.231 ThaliTest[2453:5026253] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 10:59:42.620 ThaliTest[2453:5026253] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005369007587432861
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
