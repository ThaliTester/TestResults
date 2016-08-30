#### Test 797638305c870dd_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638305c870dd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2C4A46C9-817F-44B5-861B-4CC2DD82A29E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2C4A46C9-817F-44B5-861B-4CC2DD82A29E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638305c870dd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638305c870dd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4626C8C4-8D95-467B-9212-1B8077B2ED40/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50964"
,(lldb)     command script import "/tmp/2C4A46C9-817F-44B5-861B-4CC2DD82A29E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 15:59:15.544 ThaliTest[1266:2560699] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/35F71F5E-DF91-41A8-9486-61611DD8729C/Library/Cookies/Cookies.binarycookies
,2016-08-30 15:59:16.010 ThaliTest[1266:2560699] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 15:59:16.012 ThaliTest[1266:2560699] Multi-tasking -> Device: YES, App: YES
,2016-08-30 15:59:16.033 ThaliTest[1266:2560699] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 15:59:17.663 ThaliTest[1266:2560699] Using UIWebView
,2016-08-30 15:59:17.670 ThaliTest[1266:2560699] [CDVTimer][handleopenurl] 0.818968ms
,2016-08-30 15:59:17.679 ThaliTest[1266:2560699] [CDVTimer][intentandnavigationfilter] 8.140981ms
2016-08-30 15:59:17.680 ThaliTest[1266:2560699] [CDVTimer][gesturehandler] 0.405967ms
2016-08-30 15:59:17.681 ThaliTest[1266:2560699] [CDVTimer][TotalPluginStartup] 11.254013ms
,2016-08-30 15:59:23.381 ThaliTest[1266:2560699] Resetting plugins due to page load.
,2016-08-30 15:59:25.818 ThaliTest[1266:2560699] Finished load of: file:///var/mobile/Containers/Bundle/Application/4626C8C4-8D95-467B-9212-1B8077B2ED40/ThaliTest.app/www/index.html
,2016-08-30 15:59:26.055 ThaliTest[1266:2560699] JXcore Cordova plugin initializing
,2016-08-30 15:59:26.057 ThaliTest[1266:2560935] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 15:59:34.179 ThaliTest[1266:2560935] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-30 15:59:34.179 ThaliTest[1266:2560935] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 15:59:34.180 ThaliTest[1266:2560935] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 15:59:34.183 ThaliTest[1266:2560935] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 15:59:34.573 ThaliTest[1266:2560935] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003354966640472412
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
