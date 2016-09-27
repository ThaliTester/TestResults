#### Test 850469112dc361b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469112dc361b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2476EBB2-04CA-49BD-9A8D-4EF3612351CC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2476EBB2-04CA-49BD-9A8D-4EF3612351CC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469112dc361b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469112dc361b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/243A4D6F-F4D0-4A97-BB65-C644CAE6B8F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53155"
,(lldb)     command script import "/tmp/2476EBB2-04CA-49BD-9A8D-4EF3612351CC/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:27:00.657 ThaliTest[3334:6778481] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EE5D49F3-214F-4150-ABC8-8DC302222934/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:27:00.772 ThaliTest[3334:6778481] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:27:00.773 ThaliTest[3334:6778481] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:27:00.797 ThaliTest[3334:6778481] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:27:02.439 ThaliTest[3334:6778481] Using UIWebView
,2016-09-27 12:27:02.448 ThaliTest[3334:6778481] [CDVTimer][handleopenurl] 0.478029ms
,2016-09-27 12:27:02.457 ThaliTest[3334:6778481] [CDVTimer][intentandnavigationfilter] 8.262038ms
2016-09-27 12:27:02.458 ThaliTest[3334:6778481] [CDVTimer][gesturehandler] 0.367999ms
2016-09-27 12:27:02.458 ThaliTest[3334:6778481] [CDVTimer][TotalPluginStartup] 11.164963ms
,2016-09-27 12:27:08.370 ThaliTest[3334:6778481] Resetting plugins due to page load.
,2016-09-27 12:27:11.715 ThaliTest[3334:6778481] Finished load of: file:///var/mobile/Containers/Bundle/Application/243A4D6F-F4D0-4A97-BB65-C644CAE6B8F4/ThaliTest.app/www/index.html
,2016-09-27 12:27:12.006 ThaliTest[3334:6778481] JXcore Cordova plugin initializing
,2016-09-27 12:27:12.008 ThaliTest[3334:6778707] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x14457ada0>
,Optional("19AD3850-B78B-4C76-BBED-804B2A7A6B17")
,nil
,nil
,Optional("AB19A0B3-348B-4C84-9325-CFC5F535BDAA")
,Optional("1AA9FFD8-B268-4271-8F74-E3508B9FF861")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
,Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.33270198106766
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
