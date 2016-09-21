#### Test 86174379abea55c_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3E9539DC-B15D-4E70-8C17-D6338FF48108/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/3E9539DC-B15D-4E70-8C17-D6338FF48108/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6B49D048-DFAF-4562-BFBB-0A010892ED57/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56117"
,(lldb)     command script import "/tmp/3E9539DC-B15D-4E70-8C17-D6338FF48108/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 09:28:51.371 ThaliTest[1244:1566683] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1BDD4D22-67FF-4319-95CD-FD7EB517A64E/Library/Cookies/Cookies.binarycookies
,2016-09-21 09:28:51.405 ThaliTest[1244:1566683] Apache Cordova native platform version 4.2.1 is starting.
2016-09-21 09:28:51.406 ThaliTest[1244:1566683] Multi-tasking -> Device: YES, App: YES
,2016-09-21 09:28:51.421 ThaliTest[1244:1566683] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 09:28:51.766 ThaliTest[1244:1566683] Using UIWebView
,2016-09-21 09:28:51.770 ThaliTest[1244:1566683] [CDVTimer][handleopenurl] 0.333011ms
,2016-09-21 09:28:51.775 ThaliTest[1244:1566683] [CDVTimer][intentandnavigationfilter] 4.600048ms
2016-09-21 09:28:51.776 ThaliTest[1244:1566683] [CDVTimer][gesturehandler] 0.208020ms
2016-09-21 09:28:51.776 ThaliTest[1244:1566683] [CDVTimer][TotalPluginStartup] 6.218016ms
,2016-09-21 09:28:57.168 ThaliTest[1244:1566683] Resetting plugins due to page load.
,2016-09-21 09:28:57.783 ThaliTest[1244:1566683] Finished load of: file:///var/containers/Bundle/Application/6B49D048-DFAF-4562-BFBB-0A010892ED57/ThaliTest.app/www/index.html
,2016-09-21 09:28:58.187 ThaliTest[1244:1566683] JXcore Cordova plugin initializing
,2016-09-21 09:28:58.188 ThaliTest[1244:1566853] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12e0c3bf0>
,Optional("773D1E6B-51F2-4EDF-98DC-F74842FB4E06")
,nil
,nil
,Optional("09ACCB30-6A24-4024-B86A-35F8EBA2CA68")
,Optional("4E6509A8-6FF8-440C-A5FF-3DB189CC1E3D")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-21 09:29:20.624 ThaliTest[1244:1566683] BTM: attaching to BTServer
,2016-09-21 09:29:21.424 ThaliTest[1244:1566683] BTM: local device power state changed
2016-09-21 09:29:21.425 ThaliTest[1244:1566683] BTM: power is now on
,2016-09-21 09:29:26.126 ThaliTest[1244:1566683] BTM: local device power state changed
2016-09-21 09:29:26.126 ThaliTest[1244:1566683] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  20.57568699121475
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
