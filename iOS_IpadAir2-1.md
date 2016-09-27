#### Test 85046911c0a96fd_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B44ECCD0-7EED-445A-9168-7691C260C7FE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B44ECCD0-7EED-445A-9168-7691C260C7FE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CF0033B3-3D43-42AC-A3A3-BC01A58AB142/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56551"
,(lldb)     command script import "/tmp/B44ECCD0-7EED-445A-9168-7691C260C7FE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 13:05:18.047 ThaliTest[3462:6087488] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EDCA7529-EF9E-4EE6-8486-95A53B0A6D4F/Library/Cookies/Cookies.binarycookies
,2016-09-27 13:05:18.372 ThaliTest[3462:6087488] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 13:05:18.373 ThaliTest[3462:6087488] Multi-tasking -> Device: YES, App: YES
,2016-09-27 13:05:18.389 ThaliTest[3462:6087488] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 13:05:20.192 ThaliTest[3462:6087488] Using UIWebView
,2016-09-27 13:05:20.199 ThaliTest[3462:6087488] [CDVTimer][handleopenurl] 0.357032ms
,2016-09-27 13:05:20.206 ThaliTest[3462:6087488] [CDVTimer][intentandnavigationfilter] 6.287038ms
,2016-09-27 13:05:20.206 ThaliTest[3462:6087488] [CDVTimer][gesturehandler] 0.286996ms
2016-09-27 13:05:20.207 ThaliTest[3462:6087488] [CDVTimer][TotalPluginStartup] 8.549988ms
,2016-09-27 13:05:26.813 ThaliTest[3462:6087488] Resetting plugins due to page load.
,2016-09-27 13:05:30.136 ThaliTest[3462:6087488] Finished load of: file:///var/mobile/Containers/Bundle/Application/CF0033B3-3D43-42AC-A3A3-BC01A58AB142/ThaliTest.app/www/index.html
,2016-09-27 13:05:30.337 ThaliTest[3462:6087488] JXcore Cordova plugin initializing
2016-09-27 13:05:30.338 ThaliTest[3462:6087735] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x15206ff60>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("F1578706-20A6-4D04-9B47-28D1030FEC12")
,nil
,nil
,Optional("1444C968-C87C-4CDB-9F83-036653A7BD61")
,Optional("364309B1-426F-4AF8-8219-F167468A982B")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  53
Number of failed tests:  2
,Number of ignored tests:  0
Total duration:  19.36886698007584
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
