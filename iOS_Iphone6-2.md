#### Test 86185956533f65d_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FFE402A5-0780-4CC3-9042-A7BC6A93470B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/FFE402A5-0780-4CC3-9042-A7BC6A93470B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E4493AC4-FDFA-4D03-8DB3-A2676F29A63B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53476"
,(lldb)     command script import "/tmp/FFE402A5-0780-4CC3-9042-A7BC6A93470B/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 08:55:32.903 ThaliTest[1236:1563277] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/16D3C6EA-26D7-463C-8325-25D1A041EC64/Library/Cookies/Cookies.binarycookies
,2016-09-21 08:55:32.953 ThaliTest[1236:1563277] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 08:55:32.954 ThaliTest[1236:1563277] Multi-tasking -> Device: YES, App: YES
,2016-09-21 08:55:32.966 ThaliTest[1236:1563277] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 08:55:33.309 ThaliTest[1236:1563277] Using UIWebView
2016-09-21 08:55:33.313 ThaliTest[1236:1563277] [CDVTimer][handleopenurl] 0.173986ms
2016-09-21 08:55:33.317 ThaliTest[1236:1563277] [CDVTimer][intentandnavigationfilter] 3.358006ms
,2016-09-21 08:55:33.318 ThaliTest[1236:1563277] [CDVTimer][gesturehandler] 1.307011ms
2016-09-21 08:55:33.319 ThaliTest[1236:1563277] [CDVTimer][TotalPluginStartup] 5.699039ms
,2016-09-21 08:55:38.838 ThaliTest[1236:1563277] Resetting plugins due to page load.
,2016-09-21 08:55:39.404 ThaliTest[1236:1563277] Finished load of: file:///var/containers/Bundle/Application/E4493AC4-FDFA-4D03-8DB3-A2676F29A63B/ThaliTest.app/www/index.html
,2016-09-21 08:55:39.804 ThaliTest[1236:1563277] JXcore Cordova plugin initializing
2016-09-21 08:55:39.805 ThaliTest[1236:1563446] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x16073a7c0>
,Optional("90B4849B-A0A4-4263-B73A-D5556394A001")
,nil
,nil
,Optional("BD5FE9EC-1406-4DBA-A9CF-170B15479456")
,Optional("4D1DB1EB-E796-4BA9-9166-19B0EA4FD1D7")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-21 08:56:01.398 ThaliTest[1236:1563277] BTM: attaching to BTServer
,2016-09-21 08:56:02.169 ThaliTest[1236:1563277] BTM: local device power state changed
2016-09-21 08:56:02.182 ThaliTest[1236:1563277] BTM: power is now on
,2016-09-21 08:56:06.857 ThaliTest[1236:1563277] BTM: local device power state changed
2016-09-21 08:56:06.857 ThaliTest[1236:1563277] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  19.81147402524948
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
