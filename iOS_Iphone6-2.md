#### Test 85960304fe37dec_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304fe37dec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AC5E73CF-1307-419D-9902-70BDD3AEDFE6/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/AC5E73CF-1307-419D-9902-70BDD3AEDFE6/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304fe37dec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304fe37dec/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/22D64D10-A88D-447D-93C8-641BFEB7F0BA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57883"
,(lldb)     command script import "/tmp/AC5E73CF-1307-419D-9902-70BDD3AEDFE6/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 05:58:01.678 ThaliTest[1206:1546526] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/208D0047-46FC-4E18-9B12-697833FC6F72/Library/Cookies/Cookies.binarycookies
,2016-09-21 05:58:01.996 ThaliTest[1206:1546526] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 05:58:01.998 ThaliTest[1206:1546526] Multi-tasking -> Device: YES, App: YES
,2016-09-21 05:58:02.023 ThaliTest[1206:1546526] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 05:58:02.559 ThaliTest[1206:1546526] Using UIWebView
,2016-09-21 05:58:02.569 ThaliTest[1206:1546526] [CDVTimer][handleopenurl] 0.433981ms
,2016-09-21 05:58:02.577 ThaliTest[1206:1546526] [CDVTimer][intentandnavigationfilter] 7.179022ms
2016-09-21 05:58:02.578 ThaliTest[1206:1546526] [CDVTimer][gesturehandler] 0.319004ms
2016-09-21 05:58:02.578 ThaliTest[1206:1546526] [CDVTimer][TotalPluginS,tartup] 9.670973ms
,2016-09-21 05:58:08.622 ThaliTest[1206:1546526] Resetting plugins due to page load.
,2016-09-21 05:58:09.124 ThaliTest[1206:1546526] Finished load of: file:///var/containers/Bundle/Application/22D64D10-A88D-447D-93C8-641BFEB7F0BA/ThaliTest.app/www/index.html
,2016-09-21 05:58:09.528 ThaliTest[1206:1546526] JXcore Cordova plugin initializing
,2016-09-21 05:58:09.529 ThaliTest[1206:1546722] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 05:58:16.078 ThaliTest[1206:1546722] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 05:58:16.078 ThaliTest[1206:1546722] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 05:58:16.079 ThaliTest[1206:1546722] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 05:58:16.080 ThaliTest[1206:1546722] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 05:58:16.457 ThaliTest[1206:1546722] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.00282597541809082
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
