#### Test 86891305c474d20_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86891305c474d20/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/46C62F10-BCA6-4D82-AB2D-F888E2805225/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/46C62F10-BCA6-4D82-AB2D-F888E2805225/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86891305c474d20/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86891305c474d20/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BBBDDF10-756B-4EF2-A6D5-95EF6481E21F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56514"
,(lldb)     command script import "/tmp/46C62F10-BCA6-4D82-AB2D-F888E2805225/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:58:47.095 ThaliTest[3454:6085809] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4B9633DF-65D4-4883-83A8-DFE9CFBBE488/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:58:47.426 ThaliTest[3454:6085809] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:58:47.427 ThaliTest[3454:6085809] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:58:47.443 ThaliTest[3454:6085809] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:58:49.583 ThaliTest[3454:6085809] Using UIWebView
,2016-09-27 12:58:49.590 ThaliTest[3454:6085809] [CDVTimer][handleopenurl] 0.321984ms
,2016-09-27 12:58:49.597 ThaliTest[3454:6085809] [CDVTimer][intentandnavigationfilter] 6.494045ms
,2016-09-27 12:58:49.597 ThaliTest[3454:6085809] [CDVTimer][gesturehandler] 0.304997ms
,2016-09-27 12:58:49.598 ThaliTest[3454:6085809] [CDVTimer][TotalPluginStartup] 8.696973ms
,2016-09-27 12:58:56.796 ThaliTest[3454:6085809] Resetting plugins due to page load.
,2016-09-27 12:58:59.988 ThaliTest[3454:6085809] Finished load of: file:///var/mobile/Containers/Bundle/Application/BBBDDF10-756B-4EF2-A6D5-95EF6481E21F/ThaliTest.app/www/index.html
,2016-09-27 12:59:00.214 ThaliTest[3454:6085809] JXcore Cordova plugin initializing
,2016-09-27 12:59:00.214 ThaliTest[3454:6086037] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,received session: <ThaliCore.Session: 0x140da5330>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("21BDD5C8-D43F-49FC-9267-C0C0760791F3")
,nil
,nil
,Optional("63D38941-6361-4549-9C7A-451888A88D75")
,Optional("6EFDD70C-C2C0-4CF0-AF16-232333B13CFB")
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  54
Number of failed tests:  2
Number of ignored tests:  0
,Total duration:  19.34823703765869
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
