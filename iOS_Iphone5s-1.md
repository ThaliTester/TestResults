#### Test 8326889394d960a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0348DEBD-5186-40FA-98A1-407663A19505/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0348DEBD-5186-40FA-98A1-407663A19505/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/90981590-782E-4A3D-892C-46E0116A8719/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53763"
,(lldb)     command script import "/tmp/0348DEBD-5186-40FA-98A1-407663A19505/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 15:06:35.756 ThaliTest[2472:5054007] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/28134274-0A6C-4940-A546-1AF4A26797EE/Library/Cookies/Cookies.binarycookies
,2016-09-16 15:06:35.872 ThaliTest[2472:5054007] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 15:06:35.874 ThaliTest[2472:5054007] Multi-tasking -> Device: YES, App: YES
,2016-09-16 15:06:35.897 ThaliTest[2472:5054007] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 15:06:37.386 ThaliTest[2472:5054007] Using UIWebView
,2016-09-16 15:06:37.394 ThaliTest[2472:5054007] [CDVTimer][handleopenurl] 0.573039ms
,2016-09-16 15:06:37.403 ThaliTest[2472:5054007] [CDVTimer][intentandnavigationfilter] 8.203983ms
2016-09-16 15:06:37.404 ThaliTest[2472:5054007] [CDVTimer][gesturehandler] 0.364006ms
2016-09-16 15:06:37.404 ThaliTest[2472:5054007] [CDVTimer][TotalPluginS,tartup] 11.336029ms
,2016-09-16 15:06:44.071 ThaliTest[2472:5054007] Resetting plugins due to page load.
,2016-09-16 15:06:47.823 ThaliTest[2472:5054007] Finished load of: file:///var/mobile/Containers/Bundle/Application/90981590-782E-4A3D-892C-46E0116A8719/ThaliTest.app/www/index.html
,2016-09-16 15:06:48.140 ThaliTest[2472:5054007] JXcore Cordova plugin initializing
,2016-09-16 15:06:48.141 ThaliTest[2472:5054221] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x136283490>
,A77E3A14-2C13-4075-9A8F-3354732A6461
,Optional("A77E3A14-2C13-4075-9A8F-3354732A6461")
,nil
,nil

,C28A40DE-FCDF-4B6B-B960-62FB4268F313
Optional("C28A40DE-FCDF-4B6B-B960-62FB4268F313")
,1BF1B14E-E321-4DF3-BAF4-029E9858C80A
Optional("1BF1B14E-E321-4DF3-BAF4-029E9858C80A")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-16 15:07:07.668 ThaliTest[2472:5054007] BTM: attaching to BTServer
,2016-09-16 15:07:08.767 ThaliTest[2472:5054007] BTM: local device power state changed
,2016-09-16 15:07:08.771 ThaliTest[2472:5054007] BTM: power is now off
,2016-09-16 15:07:09.455 ThaliTest[2472:5054007] BTM: local device power state changed
2016-09-16 15:07:09.456 ThaliTest[2472:5054007] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  52
Number of passed tests:  52
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  12.58032405376434
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
