#### Test 864825827cea8e2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864825827cea8e2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F319EBCB-4646-453B-92B0-98B5169B9E05/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F319EBCB-4646-453B-92B0-98B5169B9E05/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864825827cea8e2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864825827cea8e2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E061FCC4-18A9-4EB7-8C2C-C136BFA79AE6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61178"
,(lldb)     command script import "/tmp/F319EBCB-4646-453B-92B0-98B5169B9E05/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-09-23 13:11:25.426 ThaliTest[3070:6146063] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C313F375-BA9E-4220-8DBC-2DBCCFFC74ED/Library/Cookies/Cookies.binarycookies
,2016-09-23 13:11:25.543 ThaliTest[3070:6146063] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 13:11:25.544 ThaliTest[3070:6146063] Multi-tasking -> Device: YES, App: YES
,2016-09-23 13:11:25.567 ThaliTest[3070:6146063] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 13:11:26.885 ThaliTest[3070:6146063] Using UIWebView
,2016-09-23 13:11:26.894 ThaliTest[3070:6146063] [CDVTimer][handleopenurl] 0.719011ms
,2016-09-23 13:11:26.902 ThaliTest[3070:6146063] [CDVTimer][intentandnavigationfilter] 8.090019ms
2016-09-23 13:11:26.903 ThaliTest[3070:6146063] [CDVTimer][gesturehandler] 0.400007ms
2016-09-23 13:11:26.904 ThaliTest[3070:6146063] [CDVTimer][TotalPluginS,tartup] 11.072993ms
,2016-09-23 13:11:32.982 ThaliTest[3070:6146063] Resetting plugins due to page load.
,2016-09-23 13:11:36.562 ThaliTest[3070:6146063] Finished load of: file:///var/mobile/Containers/Bundle/Application/E061FCC4-18A9-4EB7-8C2C-C136BFA79AE6/ThaliTest.app/www/index.html
,2016-09-23 13:11:36.871 ThaliTest[3070:6146063] JXcore Cordova plugin initializing
,2016-09-23 13:11:36.872 ThaliTest[3070:6146306] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x13127d670>
,Optional("5DB2A138-74E7-40BA-A87F-915E95D8C734")
nil
,nil
,Optional("97F868F3-3C27-4637-B6A9-51613DA087B9")
,Optional("201F25C8-A913-47A8-99B9-99C5DDA6A332")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 13:12:00.551 ThaliTest[3070:6146063] BTM: attaching to BTServer
,2016-09-23 13:12:01.228 ThaliTest[3070:6146063] BTM: local device power state changed
2016-09-23 13:12:01.228 ThaliTest[3070:6146063] BTM: power is now on
,2016-09-23 13:12:05.949 ThaliTest[3070:6146063] BTM: local device power state changed
2016-09-23 13:12:05.954 ThaliTest[3070:6146063] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.10489696264267
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
