#### Test 85525887fe3c967_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85525887fe3c967/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A9622D75-5AFA-4C01-B6C6-D8CEF8A8EE38/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A9622D75-5AFA-4C01-B6C6-D8CEF8A8EE38/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85525887fe3c967/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85525887fe3c967/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FC17E167-63BB-4050-98F7-44153C8E0EAB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59053"
,(lldb)     command script import "/tmp/A9622D75-5AFA-4C01-B6C6-D8CEF8A8EE38/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-19 15:01:22.248 ThaliTest[2600:5509530] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/90150D6F-679F-48E2-83AE-5957F94CC029/Library/Cookies/Cookies.binarycookies
,2016-09-19 15:01:22.709 ThaliTest[2600:5509530] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-19 15:01:22.710 ThaliTest[2600:5509530] Multi-tasking -> Device: YES, App: YES
,2016-09-19 15:01:22.732 ThaliTest[2600:5509530] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-19 15:01:24.371 ThaliTest[2600:5509530] Using UIWebView
,2016-09-19 15:01:24.378 ThaliTest[2600:5509530] [CDVTimer][handleopenurl] 0.604033ms
,2016-09-19 15:01:24.387 ThaliTest[2600:5509530] [CDVTimer][intentandnavigationfilter] 7.853985ms
2016-09-19 15:01:24.388 ThaliTest[2600:5509530] [CDVTimer][gesturehandler] 0.369012ms
2016-09-19 15:01:24.388 ThaliTest[2600:5509530] [CDVTimer][TotalPluginS,tartup] 10.635972ms
,2016-09-19 15:01:30.807 ThaliTest[2600:5509530] Resetting plugins due to page load.
,2016-09-19 15:01:34.404 ThaliTest[2600:5509530] Finished load of: file:///var/mobile/Containers/Bundle/Application/FC17E167-63BB-4050-98F7-44153C8E0EAB/ThaliTest.app/www/index.html
,2016-09-19 15:01:34.735 ThaliTest[2600:5509530] JXcore Cordova plugin initializing
,2016-09-19 15:01:34.736 ThaliTest[2600:5509767] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-19 15:01:42.834 ThaliTest[2600:5509767] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-19 15:01:42.835 ThaliTest[2600:5509767] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-19 15:01:42.836 ThaliTest[2600:5509767] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-19 15:01:42.839 ThaliTest[2600:5509767] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-19 15:01:43.229 ThaliTest[2600:5509767] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.007042050361633301
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
