#### Test 871169237a0ab14_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/871169237a0ab14/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2031E8F8-149C-42E6-81AA-E9E5E1163238/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/2031E8F8-149C-42E6-81AA-E9E5E1163238/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/871169237a0ab14/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/871169237a0ab14/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/CAEB0724-523A-4837-93B8-DD56F8FF0643/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62466"
,(lldb)     command script import "/tmp/2031E8F8-149C-42E6-81AA-E9E5E1163238/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 04:42:08.257 ThaliTest[1880:2456348] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF6ADE4C-211A-443B-99DA-7024DE88672F/Library/Cookies/Cookies.binarycookies
,2016-09-29 04:42:08.351 ThaliTest[1880:2456348] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 04:42:08.354 ThaliTest[1880:2456348] Multi-tasking -> Device: YES, App: YES
,2016-09-29 04:42:08.377 ThaliTest[1880:2456348] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 04:42:08.872 ThaliTest[1880:2456348] Using UIWebView
,2016-09-29 04:42:08.882 ThaliTest[1880:2456348] [CDVTimer][handleopenurl] 0.472009ms
,2016-09-29 04:42:08.890 ThaliTest[1880:2456348] [CDVTimer][intentandnavigationfilter] 7.282972ms
2016-09-29 04:42:08.891 ThaliTest[1880:2456348] [CDVTimer][gesturehandler] 0.315011ms
2016-09-29 04:42:08.892 ThaliTest[1880:2456348] [CDVTimer][TotalPluginStartup] 9.794950ms
,2016-09-29 04:42:14.759 ThaliTest[1880:2456348] Resetting plugins due to page load.
,2016-09-29 04:42:15.234 ThaliTest[1880:2456348] Finished load of: file:///var/containers/Bundle/Application/CAEB0724-523A-4837-93B8-DD56F8FF0643/ThaliTest.app/www/index.html
,2016-09-29 04:42:15.610 ThaliTest[1880:2456348] JXcore Cordova plugin initializing
,2016-09-29 04:42:15.611 ThaliTest[1880:2456525] JXcore instance initializing
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
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  54
Number of passed tests:  54
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  17.2352129817009
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
