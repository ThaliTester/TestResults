#### Test 82914073cc2505e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/AEC42409-1A0C-40BE-AFD4-74B89B58A00C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AEC42409-1A0C-40BE-AFD4-74B89B58A00C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073cc2505e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CB2817C4-5562-4409-8494-3926E8B7B843/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50217"
,(lldb)     command script import "/tmp/AEC42409-1A0C-40BE-AFD4-74B89B58A00C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 23:40:05.206 ThaliTest[2368:4462293] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B2CC0784-9D91-42C8-A6A5-448684B5722F/Library/Cookies/Cookies.binarycookies
,2016-09-14 23:40:05.424 ThaliTest[2368:4462293] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 23:40:05.425 ThaliTest[2368:4462293] Multi-tasking -> Device: YES, App: YES
,2016-09-14 23:40:05.438 ThaliTest[2368:4462293] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 23:40:06.256 ThaliTest[2368:4462293] Using UIWebView
,2016-09-14 23:40:06.258 ThaliTest[2368:4462293] [CDVTimer][handleopenurl] 0.093997ms
,2016-09-14 23:40:06.260 ThaliTest[2368:4462293] [CDVTimer][intentandnavigationfilter] 1.838982ms
2016-09-14 23:40:06.260 ThaliTest[2368:4462293] [CDVTimer][gesturehandler] 0.081003ms
2016-09-14 23:40:06.261 ThaliTest[2368:4462293] [CDVTimer][TotalPluginS,tartup] 2.443016ms
,2016-09-14 23:40:09.429 ThaliTest[2368:4462293] Resetting plugins due to page load.
,2016-09-14 23:40:10.851 ThaliTest[2368:4462293] Finished load of: file:///var/mobile/Containers/Bundle/Application/CB2817C4-5562-4409-8494-3926E8B7B843/ThaliTest.app/www/index.html
,2016-09-14 23:40:10.988 ThaliTest[2368:4462293] JXcore Cordova plugin initializing
2016-09-14 23:40:10.989 ThaliTest[2368:4462465] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 23:40:17.535 ThaliTest[2368:4462293] BTM: attaching to BTServer
,2016-09-14 23:40:22.046 ThaliTest[2368:4462293] BTM: local device power state changed
2016-09-14 23:40:22.046 ThaliTest[2368:4462293] BTM: power is now off
,2016-09-14 23:40:22.851 ThaliTest[2368:4462293] BTM: local device power state changed
2016-09-14 23:40:22.852 ThaliTest[2368:4462293] BTM: power is now on
,received session: <ThaliCore.Session: 0x158d491e0>
,*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  17.53760397434235
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
