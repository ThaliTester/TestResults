#### Test 83268893feeea5a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893feeea5a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/320C07E4-0F94-4CA7-B010-0FA0246EF4B7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/320C07E4-0F94-4CA7-B010-0FA0246EF4B7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893feeea5a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893feeea5a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3C429EB3-4299-4851-B0B6-CB61ECE42337/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61663"
,(lldb)     command script import "/tmp/320C07E4-0F94-4CA7-B010-0FA0246EF4B7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 16:18:31.134 ThaliTest[2880:5317033] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/30B4149C-E379-4A0E-BA14-B903CCD10D9D/Library/Cookies/Cookies.binarycookies
,2016-09-21 16:18:31.442 ThaliTest[2880:5317033] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 16:18:31.443 ThaliTest[2880:5317033] Multi-tasking -> Device: YES, App: YES
,2016-09-21 16:18:31.457 ThaliTest[2880:5317033] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 16:18:33.200 ThaliTest[2880:5317033] Using UIWebView
,2016-09-21 16:18:33.207 ThaliTest[2880:5317033] [CDVTimer][handleopenurl] 0.338972ms
,2016-09-21 16:18:33.214 ThaliTest[2880:5317033] [CDVTimer][intentandnavigationfilter] 6.356001ms
,2016-09-21 16:18:33.214 ThaliTest[2880:5317033] [CDVTimer][gesturehandler] 0.276983ms
,2016-09-21 16:18:33.215 ThaliTest[2880:5317033] [CDVTimer][TotalPluginStartup] 8.433998ms
,2016-09-21 16:18:40.317 ThaliTest[2880:5317033] Resetting plugins due to page load.
,2016-09-21 16:18:43.601 ThaliTest[2880:5317033] Finished load of: file:///var/mobile/Containers/Bundle/Application/3C429EB3-4299-4851-B0B6-CB61ECE42337/ThaliTest.app/www/index.html
,2016-09-21 16:18:43.817 ThaliTest[2880:5317033] JXcore Cordova plugin initializing
,2016-09-21 16:18:43.817 ThaliTest[2880:5317266] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x13cf3ab20>
,Optional("CE736C2F-3503-467A-8B94-FA13B2125DE7")
,nil
,nil
,Optional("C34A9402-3E02-4044-8C31-3B1646AC0A81")
,Optional("AC2530F0-1C70-4AB8-9056-0E15BE79BC35")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-21 16:19:09.613 ThaliTest[2880:5317033] BTM: attaching to BTServer
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  50
,Number of failed tests:  6
,Number of ignored tests:  0
,Total duration:  39.40601402521133
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
