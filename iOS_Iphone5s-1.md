#### Test 82914073713e010_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073713e010/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2F2722F3-C702-4A15-B822-BCB75049D216/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2F2722F3-C702-4A15-B822-BCB75049D216/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073713e010/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073713e010/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3BF3B719-01A5-44CA-9F4A-E5E0F3B16365/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60863"
,(lldb)     command script import "/tmp/2F2722F3-C702-4A15-B822-BCB75049D216/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 18:56:38.913 ThaliTest[2393:4925867] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F9C2B5AE-1C5F-42C5-9EF6-2775DA2EC56D/Library/Cookies/Cookies.binarycookies
,2016-09-15 18:56:39.039 ThaliTest[2393:4925867] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 18:56:39.041 ThaliTest[2393:4925867] Multi-tasking -> Device: YES, App: YES
,2016-09-15 18:56:39.065 ThaliTest[2393:4925867] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 18:56:40.722 ThaliTest[2393:4925867] Using UIWebView
,2016-09-15 18:56:40.730 ThaliTest[2393:4925867] [CDVTimer][handleopenurl] 0.484049ms
,2016-09-15 18:56:40.739 ThaliTest[2393:4925867] [CDVTimer][intentandnavigationfilter] 8.387029ms
2016-09-15 18:56:40.740 ThaliTest[2393:4925867] [CDVTimer][gesturehandler] 0.372052ms
2016-09-15 18:56:40.741 ThaliTest[2393:4925867] [CDVTimer][TotalPluginS,tartup] 11.477947ms
,2016-09-15 18:56:46.646 ThaliTest[2393:4925867] Resetting plugins due to page load.
,2016-09-15 18:56:50.073 ThaliTest[2393:4925867] Finished load of: file:///var/mobile/Containers/Bundle/Application/3BF3B719-01A5-44CA-9F4A-E5E0F3B16365/ThaliTest.app/www/index.html
,2016-09-15 18:56:50.378 ThaliTest[2393:4925867] JXcore Cordova plugin initializing
,2016-09-15 18:56:50.379 ThaliTest[2393:4926086] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-15 18:56:59.394 ThaliTest[2393:4925867] BTM: attaching to BTServer
,2016-09-15 18:57:03.984 ThaliTest[2393:4925867] BTM: local device power state changed
2016-09-15 18:57:03.987 ThaliTest[2393:4925867] BTM: power is now off
,2016-09-15 18:57:04.689 ThaliTest[2393:4925867] BTM: local device power state changed
2016-09-15 18:57:04.689 ThaliTest[2393:4925867] BTM: power is now on
,received session: <ThaliCore.Session: 0x14ec16680>
,38FCB926-ADCA-4FBB-9572-463407E0054F
,Optional("38FCB926-ADCA-4FBB-9572-463407E0054F")
,nil
,nil

,CCA9D997-D032-4EF9-A74B-CFB7DF783339
,Optional("CCA9D997-D032-4EF9-A74B-CFB7DF783339")
,12DC2870-AFE7-488A-8FF4-881C1CFB0D35
,Optional("12DC2870-AFE7-488A-8FF4-881C1CFB0D35")
,*Native tests were executed*
,Total number of executed tests:  46
,Number of passed tests:  46
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  16.01575201749802
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
