#### Test 8326889395f7d73_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889395f7d73/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AFE33A0B-258B-4036-BB43-E2E6316ACD48/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AFE33A0B-258B-4036-BB43-E2E6316ACD48/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889395f7d73/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889395f7d73/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D4F2702C-11D7-4BCF-BCAA-DF23F4B203E9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59715"
,(lldb)     command script import "/tmp/AFE33A0B-258B-4036-BB43-E2E6316ACD48/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 12:55:42.296 ThaliTest[3063:6142329] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7736BCD8-CE08-497E-B7F4-666CF3CED2A1/Library/Cookies/Cookies.binarycookies
,2016-09-23 12:55:42.410 ThaliTest[3063:6142329] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 12:55:42.411 ThaliTest[3063:6142329] Multi-tasking -> Device: YES, App: YES
,2016-09-23 12:55:42.435 ThaliTest[3063:6142329] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 12:55:43.915 ThaliTest[3063:6142329] Using UIWebView
,2016-09-23 12:55:43.923 ThaliTest[3063:6142329] [CDVTimer][handleopenurl] 0.639021ms
,2016-09-23 12:55:43.931 ThaliTest[3063:6142329] [CDVTimer][intentandnavigationfilter] 7.818043ms
2016-09-23 12:55:43.932 ThaliTest[3063:6142329] [CDVTimer][gesturehandler] 0.497997ms
2016-09-23 12:55:43.933 ThaliTest[3063:6142329] [CDVTimer][TotalPluginS,tartup] 10.827005ms
,2016-09-23 12:55:49.592 ThaliTest[3063:6142329] Resetting plugins due to page load.
,2016-09-23 12:55:52.949 ThaliTest[3063:6142329] Finished load of: file:///var/mobile/Containers/Bundle/Application/D4F2702C-11D7-4BCF-BCAA-DF23F4B203E9/ThaliTest.app/www/index.html
,2016-09-23 12:55:53.255 ThaliTest[3063:6142329] JXcore Cordova plugin initializing
,2016-09-23 12:55:53.257 ThaliTest[3063:6142582] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x129912070>
,Optional("D5734154-5CA1-4003-B338-E20A5733BE22")
,nil
,nil
,Optional("FD61BA4B-F0A1-4471-8FFA-3C1B536FFAD1")
,Optional("35938E21-FF4E-4EFF-8162-146B67C55E34")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 12:56:17.462 ThaliTest[3063:6142329] BTM: attaching to BTServer
,2016-09-23 12:56:18.165 ThaliTest[3063:6142329] BTM: local device power state changed
2016-09-23 12:56:18.173 ThaliTest[3063:6142329] BTM: power is now on
,2016-09-23 12:56:22.885 ThaliTest[3063:6142329] BTM: local device power state changed
2016-09-23 12:56:22.887 ThaliTest[3063:6142329] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.72511696815491
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
