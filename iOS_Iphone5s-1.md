#### Test 8504691135967af_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/10573DCA-6B65-435D-BFB8-8DEC1B8B5B1B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/10573DCA-6B65-435D-BFB8-8DEC1B8B5B1B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3C599EF8-57C8-41B6-A3E5-E3BCD68D07E0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59800"
,(lldb)     command script import "/tmp/10573DCA-6B65-435D-BFB8-8DEC1B8B5B1B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 09:41:48.543 ThaliTest[3414:6922758] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/03A02DE3-4ED3-4691-929E-6593B56D2C77/Library/Cookies/Cookies.binarycookies
,2016-09-28 09:41:48.653 ThaliTest[3414:6922758] Apache Cordova native platform version 4.2.1 is starting.
2016-09-28 09:41:48.655 ThaliTest[3414:6922758] Multi-tasking -> Device: YES, App: YES
,2016-09-28 09:41:48.679 ThaliTest[3414:6922758] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 09:41:50.229 ThaliTest[3414:6922758] Using UIWebView
,2016-09-28 09:41:50.237 ThaliTest[3414:6922758] [CDVTimer][handleopenurl] 0.545979ms
,2016-09-28 09:41:50.246 ThaliTest[3414:6922758] [CDVTimer][intentandnavigationfilter] 8.314013ms
2016-09-28 09:41:50.247 ThaliTest[3414:6922758] [CDVTimer][gesturehandler] 0.357985ms
2016-09-28 09:41:50.248 ThaliTest[3414:6922758] [CDVTimer][TotalPluginStartup] 11.056960ms
,2016-09-28 09:41:56.917 ThaliTest[3414:6922758] Resetting plugins due to page load.
,2016-09-28 09:42:00.684 ThaliTest[3414:6922758] Finished load of: file:///var/mobile/Containers/Bundle/Application/3C599EF8-57C8-41B6-A3E5-E3BCD68D07E0/ThaliTest.app/www/index.html
,2016-09-28 09:42:00.875 ThaliTest[3414:6922758] JXcore Cordova plugin initializing
,2016-09-28 09:42:00.876 ThaliTest[3414:6922980] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x16181a520>
,Optional("495E83F3-A77D-4A21-A128-1ABF493E6DFA")
,nil
,nil
,Optional("8FD2DB5A-DBB2-49FF-A6B6-F195946B1DC1")
,Optional("A834E2BD-36E7-4551-B8D5-1A23141E7977")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  55
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.87260401248932
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
