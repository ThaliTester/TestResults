#### Test 8712674671a25ec_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F3BE9B52-73DF-4755-949B-D254F9A952FE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F3BE9B52-73DF-4755-949B-D254F9A952FE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1237DFE7-803E-44A3-A855-888E47F029DC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64213"
,(lldb)     command script import "/tmp/F3BE9B52-73DF-4755-949B-D254F9A952FE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 09:40:49.076 ThaliTest[3588:6319838] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F8242974-E159-42A0-88A0-EECB37ECDF41/Library/Cookies/Cookies.binarycookies
,2016-09-29 09:40:49.399 ThaliTest[3588:6319838] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 09:40:49.400 ThaliTest[3588:6319838] Multi-tasking -> Device: YES, App: YES
,2016-09-29 09:40:49.416 ThaliTest[3588:6319838] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 09:40:51.384 ThaliTest[3588:6319838] Using UIWebView
,2016-09-29 09:40:51.390 ThaliTest[3588:6319838] [CDVTimer][handleopenurl] 0.337958ms
,2016-09-29 09:40:51.398 ThaliTest[3588:6319838] [CDVTimer][intentandnavigationfilter] 6.784022ms
,2016-09-29 09:40:51.399 ThaliTest[3588:6319838] [CDVTimer][gesturehandler] 0.306010ms
,2016-09-29 09:40:51.399 ThaliTest[3588:6319838] [CDVTimer][TotalPluginStartup] 9.104013ms
,2016-09-29 09:40:58.316 ThaliTest[3588:6319838] Resetting plugins due to page load.
,2016-09-29 09:41:01.936 ThaliTest[3588:6319838] Finished load of: file:///var/mobile/Containers/Bundle/Application/1237DFE7-803E-44A3-A855-888E47F029DC/ThaliTest.app/www/index.html
,2016-09-29 09:41:02.126 ThaliTest[3588:6319838] JXcore Cordova plugin initializing
,2016-09-29 09:41:02.127 ThaliTest[3588:6320118] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1290b8a00>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("7275A35F-98A1-4B5D-A6EE-FDA2EC2DA37B")
,nil
,nil
,Optional("79B27623-EA07-47D5-A0AC-543ACFF5FC3B")
,Optional("C3516830-5EB7-40A3-91F4-E7A4BC815043")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  56
Number of passed tests:  54
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  19.23718899488449
Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
