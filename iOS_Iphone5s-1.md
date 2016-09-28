#### Test 87126746a66927d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9BEC60B7-D1AD-4926-B868-DF85AA70C798/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9BEC60B7-D1AD-4926-B868-DF85AA70C798/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/285621F0-4037-4904-8109-5E0B7CB37B92/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54539"
,(lldb)     command script import "/tmp/9BEC60B7-D1AD-4926-B868-DF85AA70C798/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 16:30:31.005 ThaliTest[3450:6971398] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9DD8DFC7-244D-4D4A-9A5E-891D9B8B5C08/Library/Cookies/Cookies.binarycookies
,2016-09-28 16:30:31.122 ThaliTest[3450:6971398] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 16:30:31.123 ThaliTest[3450:6971398] Multi-tasking -> Device: YES, App: YES
,2016-09-28 16:30:31.149 ThaliTest[3450:6971398] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 16:30:32.709 ThaliTest[3450:6971398] Using UIWebView
,2016-09-28 16:30:32.717 ThaliTest[3450:6971398] [CDVTimer][handleopenurl] 0.751972ms
,2016-09-28 16:30:32.726 ThaliTest[3450:6971398] [CDVTimer][intentandnavigationfilter] 8.171022ms
2016-09-28 16:30:32.727 ThaliTest[3450:6971398] [CDVTimer][gesturehandler] 0.365973ms
2016-09-28 16:30:32.727 ThaliTest[3450:6971398] [CDVTimer][TotalPluginStartup] 11.180997ms
,2016-09-28 16:30:38.946 ThaliTest[3450:6971398] Resetting plugins due to page load.
,2016-09-28 16:30:42.283 ThaliTest[3450:6971398] Finished load of: file:///var/mobile/Containers/Bundle/Application/285621F0-4037-4904-8109-5E0B7CB37B92/ThaliTest.app/www/index.html
,2016-09-28 16:30:42.586 ThaliTest[3450:6971398] JXcore Cordova plugin initializing
,2016-09-28 16:30:42.587 ThaliTest[3450:6971634] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1509829f0>
,Optional("18AB40A9-EC6A-41D9-994B-DCE926136327")
,nil
,nil
,Optional("B35E4A87-57CE-4DB3-9C8A-765353FC1B16")
,Optional("9282B42E-9043-4EAA-8FBD-BFDCAD977BFB")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.26845300197601
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
