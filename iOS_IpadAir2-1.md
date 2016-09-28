#### Test 8504691135967af_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C913526B-8ECD-4F8F-97D2-444D82B136BF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C913526B-8ECD-4F8F-97D2-444D82B136BF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/668BAF54-FA6C-4172-946E-8D16E5DD3E0F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59796"
,(lldb)     command script import "/tmp/C913526B-8ECD-4F8F-97D2-444D82B136BF/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 09:41:41.101 ThaliTest[3503:6191158] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/48F057A5-AB83-4E27-9A2E-F74717533CAA/Library/Cookies/Cookies.binarycookies
,2016-09-28 09:41:41.459 ThaliTest[3503:6191158] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 09:41:41.460 ThaliTest[3503:6191158] Multi-tasking -> Device: YES, App: YES
,2016-09-28 09:41:41.479 ThaliTest[3503:6191158] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 09:41:43.474 ThaliTest[3503:6191158] Using UIWebView
,2016-09-28 09:41:43.484 ThaliTest[3503:6191158] [CDVTimer][handleopenurl] 0.351012ms
,2016-09-28 09:41:43.491 ThaliTest[3503:6191158] [CDVTimer][intentandnavigationfilter] 6.852984ms
,2016-09-28 09:41:43.492 ThaliTest[3503:6191158] [CDVTimer][gesturehandler] 0.361025ms
2016-09-28 09:41:43.493 ThaliTest[3503:6191158] [CDVTimer][TotalPluginStartup] 9.172976ms
,2016-09-28 09:41:49.864 ThaliTest[3503:6191158] Resetting plugins due to page load.
,2016-09-28 09:41:53.120 ThaliTest[3503:6191158] Finished load of: file:///var/mobile/Containers/Bundle/Application/668BAF54-FA6C-4172-946E-8D16E5DD3E0F/ThaliTest.app/www/index.html
,2016-09-28 09:41:53.402 ThaliTest[3503:6191158] JXcore Cordova plugin initializing
,2016-09-28 09:41:53.403 ThaliTest[3503:6191448] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x15f421080>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("E4952919-3F92-43EF-B503-98897609E2D0")
,nil
,nil
,Optional("337C9C0E-24F5-4EAC-B8A3-366E53F64C03")
,Optional("73855698-D25B-49C7-85C1-C512F34E334C")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  53
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  18.78719997406006
Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
