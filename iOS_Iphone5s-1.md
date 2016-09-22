#### Test 8504691186bae88_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CE3B5CF8-A676-4726-95E4-02A18565DFC4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CE3B5CF8-A676-4726-95E4-02A18565DFC4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E1B0DCEB-D4ED-414A-99ED-DE6E0B14AC95/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54941"
,(lldb)     command script import "/tmp/CE3B5CF8-A676-4726-95E4-02A18565DFC4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 09:59:25.050 ThaliTest[2878:5947829] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F4577F49-75D3-42DC-85EF-124D63D681A9/Library/Cookies/Cookies.binarycookies
,2016-09-22 09:59:25.174 ThaliTest[2878:5947829] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 09:59:25.175 ThaliTest[2878:5947829] Multi-tasking -> Device: YES, App: YES
,2016-09-22 09:59:25.196 ThaliTest[2878:5947829] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 09:59:26.531 ThaliTest[2878:5947829] Using UIWebView
,2016-09-22 09:59:26.540 ThaliTest[2878:5947829] [CDVTimer][handleopenurl] 0.661016ms
,2016-09-22 09:59:26.548 ThaliTest[2878:5947829] [CDVTimer][intentandnavigationfilter] 8.287966ms
2016-09-22 09:59:26.549 ThaliTest[2878:5947829] [CDVTimer][gesturehandler] 0.351965ms
2016-09-22 09:59:26.550 ThaliTest[2878:5947829] [CDVTimer][TotalPluginStartup] 11.159003ms
,2016-09-22 09:59:32.320 ThaliTest[2878:5947829] Resetting plugins due to page load.
,2016-09-22 09:59:35.795 ThaliTest[2878:5947829] Finished load of: file:///var/mobile/Containers/Bundle/Application/E1B0DCEB-D4ED-414A-99ED-DE6E0B14AC95/ThaliTest.app/www/index.html
,2016-09-22 09:59:36.098 ThaliTest[2878:5947829] JXcore Cordova plugin initializing
,2016-09-22 09:59:36.099 ThaliTest[2878:5948057] JXcore instance initializing
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
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 09:59:45.099 ThaliTest[2878:5947829] BTM: attaching to BTServer
,2016-09-22 09:59:45.769 ThaliTest[2878:5947829] BTM: local device power state changed
2016-09-22 09:59:45.770 ThaliTest[2878:5947829] BTM: power is now on
,2016-09-22 09:59:50.499 ThaliTest[2878:5947829] BTM: local device power state changed
2016-09-22 09:59:50.500 ThaliTest[2878:5947829] BTM: power is now off
,received session: <ThaliCore.Session: 0x12ff358d0>
,Optional("28A32E14-ADD7-4ABA-B6C3-6F7B558E940C")
,nil
,nil
,Optional("5D890A5D-83EF-46C0-BE0A-3023AE98F769")
,Optional("CE01EF2E-B972-48CE-B26B-543E74EC64CA")
,*Native tests were executed*
,Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  20.06070899963379
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
