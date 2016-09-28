#### Test 8504691135967af_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8EA2A030-7684-4FF4-BDCA-9C05E1D7C407/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/8EA2A030-7684-4FF4-BDCA-9C05E1D7C407/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B1CAC0D6-F5CE-470F-B6CE-5E31944892B3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59801"
,(lldb)     command script import "/tmp/8EA2A030-7684-4FF4-BDCA-9C05E1D7C407/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 00:41:53.590 ThaliTest[1769:2321515] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0C911691-55F5-41D2-B535-EF944EE9A5E8/Library/Cookies/Cookies.binarycookies
,2016-09-28 00:41:53.676 ThaliTest[1769:2321515] Apache Cordova native platform version 4.2.1 is starting.
2016-09-28 00:41:53.677 ThaliTest[1769:2321515] Multi-tasking -> Device: YES, App: YES
,2016-09-28 00:41:53.699 ThaliTest[1769:2321515] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 00:41:54.161 ThaliTest[1769:2321515] Using UIWebView
,2016-09-28 00:41:54.171 ThaliTest[1769:2321515] [CDVTimer][handleopenurl] 0.374973ms
,2016-09-28 00:41:54.179 ThaliTest[1769:2321515] [CDVTimer][intentandnavigationfilter] 6.929994ms
2016-09-28 00:41:54.179 ThaliTest[1769:2321515] [CDVTimer][gesturehandler] 0.288963ms
2016-09-28 00:41:54.180 ThaliTest[1769:2321515] [CDVTimer][TotalPluginStartup] 9.229004ms
,2016-09-28 00:42:00.190 ThaliTest[1769:2321515] Resetting plugins due to page load.
,2016-09-28 00:42:00.539 ThaliTest[1769:2321515] Finished load of: file:///var/containers/Bundle/Application/B1CAC0D6-F5CE-470F-B6CE-5E31944892B3/ThaliTest.app/www/index.html
,2016-09-28 00:42:00.866 ThaliTest[1769:2321515] JXcore Cordova plugin initializing
2016-09-28 00:42:00.867 ThaliTest[1769:2321705] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x137b95b50>
,Optional("CD7ABA59-2E7D-4C1A-A5DA-B3C6D2B962A6")
nil
,nil
,Optional("BC1E5025-2B77-4EB0-8F2C-1778D9C65953")
,Optional("3DF365FF-AFEF-43A5-A0F4-7B5A0E5B19F5")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.96490299701691
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
