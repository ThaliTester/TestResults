#### Test 852639026a23328_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/39BE19DC-F192-4F90-B9DD-B8868EBB23F1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/39BE19DC-F192-4F90-B9DD-B8868EBB23F1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/852639026a23328/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/87076F1F-8975-4BDC-BE58-2BDBC825C1E6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61064"
,(lldb)     command script import "/tmp/39BE19DC-F192-4F90-B9DD-B8868EBB23F1/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 05:46:00.931 ThaliTest[1130:1432298] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7A26E669-12D7-4D36-AAEE-2CC1EDDCBC28/Library/Cookies/Cookies.binarycookies
,2016-09-20 05:46:01.012 ThaliTest[1130:1432298] Apache Cordova native platform version 4.2.1 is starting.
2016-09-20 05:46:01.014 ThaliTest[1130:1432298] Multi-tasking -> Device: YES, App: YES
,2016-09-20 05:46:01.033 ThaliTest[1130:1432298] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 05:46:01.451 ThaliTest[1130:1432298] Using UIWebView
,2016-09-20 05:46:01.461 ThaliTest[1130:1432298] [CDVTimer][handleopenurl] 0.369012ms
,2016-09-20 05:46:01.469 ThaliTest[1130:1432298] [CDVTimer][intentandnavigationfilter] 7.063031ms
2016-09-20 05:46:01.470 ThaliTest[1130:1432298] [CDVTimer][gesturehandler] 0.270009ms
2016-09-20 05:46:01.470 ThaliTest[1130:1432298] [CDVTimer][TotalPluginS,tartup] 9.289980ms
,2016-09-20 05:46:07.209 ThaliTest[1130:1432298] Resetting plugins due to page load.
,2016-09-20 05:46:07.716 ThaliTest[1130:1432298] Finished load of: file:///var/containers/Bundle/Application/87076F1F-8975-4BDC-BE58-2BDBC825C1E6/ThaliTest.app/www/index.html
,2016-09-20 05:46:08.118 ThaliTest[1130:1432298] JXcore Cordova plugin initializing
,2016-09-20 05:46:08.119 ThaliTest[1130:1432465] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x156b538b0>
,Optional("C6634C34-BBC3-4FD6-9DC8-A525B606902F")
nil
nil
Optional("5D9CD15A-A23A-4685-AF33-F543ADB86844")
,Optional("570CCC65-88C6-4611-B49A-9FBB6F2FC098")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-20 05:46:30.145 ThaliTest[1130:1432298] BTM: attaching to BTServer
,2016-09-20 05:46:31.298 ThaliTest[1130:1432298] BTM: local device power state changed
2016-09-20 05:46:31.300 ThaliTest[1130:1432298] BTM: power is now off
,2016-09-20 05:46:32.067 ThaliTest[1130:1432298] BTM: local device power state changed
2016-09-20 05:46:32.068 ThaliTest[1130:1432298] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  16.48616999387741
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
