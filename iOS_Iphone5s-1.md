#### Test 86185956533f65d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/174E35FF-D1D2-4615-A02B-ED4131A73EA5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/174E35FF-D1D2-4615-A02B-ED4131A73EA5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/12C2A1D2-483B-411A-B5C8-A52AA028B96F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53504"
,(lldb)     command script import "/tmp/174E35FF-D1D2-4615-A02B-ED4131A73EA5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 17:55:37.246 ThaliTest[2805:5838387] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/541AEBC9-483C-41CE-A2C1-336DA301B867/Library/Cookies/Cookies.binarycookies
,2016-09-21 17:55:37.362 ThaliTest[2805:5838387] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 17:55:37.364 ThaliTest[2805:5838387] Multi-tasking -> Device: YES, App: YES
,2016-09-21 17:55:37.389 ThaliTest[2805:5838387] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 17:55:39.013 ThaliTest[2805:5838387] Using UIWebView
,2016-09-21 17:55:39.021 ThaliTest[2805:5838387] [CDVTimer][handleopenurl] 0.474989ms
,2016-09-21 17:55:39.030 ThaliTest[2805:5838387] [CDVTimer][intentandnavigationfilter] 8.189023ms
2016-09-21 17:55:39.030 ThaliTest[2805:5838387] [CDVTimer][gesturehandler] 0.365973ms
2016-09-21 17:55:39.031 ThaliTest[2805:5838387] [CDVTimer][TotalPluginStartup] 10.966003ms
,2016-09-21 17:55:45.054 ThaliTest[2805:5838387] Resetting plugins due to page load.
,2016-09-21 17:55:48.373 ThaliTest[2805:5838387] Finished load of: file:///var/mobile/Containers/Bundle/Application/12C2A1D2-483B-411A-B5C8-A52AA028B96F/ThaliTest.app/www/index.html
,2016-09-21 17:55:48.688 ThaliTest[2805:5838387] JXcore Cordova plugin initializing
,2016-09-21 17:55:48.689 ThaliTest[2805:5838625] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x14670d960>
,Optional("EEE7187C-30C0-44A0-A771-D6FF827F57AC")
,nil
,nil
,Optional("BB578D36-E220-403C-AC27-A3014F6A3D2F")
,Optional("D7402059-E5F2-47C3-A5AE-579F14636223")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-21 17:56:12.170 ThaliTest[2805:5838387] BTM: attaching to BTServer
,2016-09-21 17:56:12.862 ThaliTest[2805:5838387] BTM: local device power state changed
2016-09-21 17:56:12.863 ThaliTest[2805:5838387] BTM: power is now on
,2016-09-21 17:56:17.593 ThaliTest[2805:5838387] BTM: local device power state changed
2016-09-21 17:56:17.593 ThaliTest[2805:5838387] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
,Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.14251101016998
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
