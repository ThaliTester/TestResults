#### Test 79763830cfa9ed9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830cfa9ed9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/689CB248-7B23-4763-9F4D-98C4F533B7C5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/689CB248-7B23-4763-9F4D-98C4F533B7C5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830cfa9ed9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830cfa9ed9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/65B645FE-47EF-40D3-AA78-2387372DD244/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60383"
,(lldb)     command script import "/tmp/689CB248-7B23-4763-9F4D-98C4F533B7C5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-08-26 15:41:14.386 ThaliTest[958:1967186] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AF13951D-1678-4445-965D-12258C8B0CBB/Library/Cookies/Cookies.binarycookies
,2016-08-26 15:41:14.734 ThaliTest[958:1967186] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 15:41:14.736 ThaliTest[958:1967186] Multi-tasking -> Device: YES, App: YES
,2016-08-26 15:41:14.754 ThaliTest[958:1967186] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 15:41:16.422 ThaliTest[958:1967186] Using UIWebView
,2016-08-26 15:41:16.430 ThaliTest[958:1967186] [CDVTimer][handleopenurl] 0.419021ms
,2016-08-26 15:41:16.439 ThaliTest[958:1967186] [CDVTimer][intentandnavigationfilter] 7.997990ms
2016-08-26 15:41:16.440 ThaliTest[958:1967186] [CDVTimer][gesturehandler] 0.383019ms
2016-08-26 15:41:16.440 ThaliTest[958:1967186] [CDVTimer][TotalPluginStartup] 10.739982ms
,2016-08-26 15:41:22.550 ThaliTest[958:1967186] Resetting plugins due to page load.
,2016-08-26 15:41:25.627 ThaliTest[958:1967186] Finished load of: file:///var/mobile/Containers/Bundle/Application/65B645FE-47EF-40D3-AA78-2387372DD244/ThaliTest.app/www/index.html
,2016-08-26 15:41:25.880 ThaliTest[958:1967186] JXcore Cordova plugin initializing
,2016-08-26 15:41:25.881 ThaliTest[958:1967434] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 15:41:33.963 ThaliTest[958:1967434] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-26 15:41:33.963 ThaliTest[958:1967434] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 15:41:33.964 ThaliTest[958:1967434] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 15:41:33.966 ThaliTest[958:1967434] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 15:41:34.353 ThaliTest[958:1967434] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  3
,Number of passed tests:  2
Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01807200908660889
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
