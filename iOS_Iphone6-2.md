#### Test 865221020889ce9_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8C740169-F273-4C03-8DCD-E7742B9E0C21/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/8C740169-F273-4C03-8DCD-E7742B9E0C21/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/14B96148-41D6-4DA8-8DB2-8DF10429A351/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59253"
,(lldb)     command script import "/tmp/8C740169-F273-4C03-8DCD-E7742B9E0C21/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 07:31:33.131 ThaliTest[1635:2131158] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4CC62AD6-9519-431C-A056-87745C7DBC30/Library/Cookies/Cookies.binarycookies
,2016-09-26 07:31:33.214 ThaliTest[1635:2131158] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 07:31:33.216 ThaliTest[1635:2131158] Multi-tasking -> Device: YES, App: YES
,2016-09-26 07:31:33.240 ThaliTest[1635:2131158] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 07:31:33.735 ThaliTest[1635:2131158] Using UIWebView
,2016-09-26 07:31:33.743 ThaliTest[1635:2131158] [CDVTimer][handleopenurl] 0.499010ms
,2016-09-26 07:31:33.750 ThaliTest[1635:2131158] [CDVTimer][intentandnavigationfilter] 7.034004ms
2016-09-26 07:31:33.751 ThaliTest[1635:2131158] [CDVTimer][gesturehandler] 0.289977ms
2016-09-26 07:31:33.751 ThaliTest[1635:2131158] [CDVTimer][TotalPluginS,tartup] 9.455025ms
,2016-09-26 07:31:39.031 ThaliTest[1635:2131158] Resetting plugins due to page load.
,2016-09-26 07:31:39.480 ThaliTest[1635:2131158] Finished load of: file:///var/containers/Bundle/Application/14B96148-41D6-4DA8-8DB2-8DF10429A351/ThaliTest.app/www/index.html
,2016-09-26 07:31:39.819 ThaliTest[1635:2131158] JXcore Cordova plugin initializing
,2016-09-26 07:31:39.820 ThaliTest[1635:2131327] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12f3b7fe0>
,Optional("9D6B03A2-6CB9-4F96-B971-B29635EC242F")
nil
,nil
,Optional("62205C03-876B-49AA-9770-8B8B8928D938")
,Optional("5945B973-EB87-4BA4-B5F6-699330EBF595")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  14.29663401842117
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
