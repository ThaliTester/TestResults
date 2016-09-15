#### Test 829140738685e0d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140738685e0d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B958A4EA-1D2C-462B-9412-DB9B79654002/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B958A4EA-1D2C-462B-9412-DB9B79654002/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140738685e0d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140738685e0d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8048C99E-C56B-4BC2-8A40-9EB7E13BF386/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52337"
,(lldb)     command script import "/tmp/B958A4EA-1D2C-462B-9412-DB9B79654002/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 13:56:46.009 ThaliTest[2445:4544481] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C6FF1F00-8E5E-4A49-9C9C-15FE15551961/Library/Cookies/Cookies.binarycookies
,2016-09-15 13:56:46.317 ThaliTest[2445:4544481] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 13:56:46.318 ThaliTest[2445:4544481] Multi-tasking -> Device: YES, App: YES
,2016-09-15 13:56:46.332 ThaliTest[2445:4544481] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 13:56:48.072 ThaliTest[2445:4544481] Using UIWebView
,2016-09-15 13:56:48.079 ThaliTest[2445:4544481] [CDVTimer][handleopenurl] 0.330985ms
,2016-09-15 13:56:48.087 ThaliTest[2445:4544481] [CDVTimer][intentandnavigationfilter] 7.160008ms
,2016-09-15 13:56:48.087 ThaliTest[2445:4544481] [CDVTimer][gesturehandler] 0.320017ms
,2016-09-15 13:56:48.088 ThaliTest[2445:4544481] [CDVTimer][TotalPluginStartup] 9.364963ms
,2016-09-15 13:56:54.444 ThaliTest[2445:4544481] Resetting plugins due to page load.
,2016-09-15 13:56:57.475 ThaliTest[2445:4544481] Finished load of: file:///var/mobile/Containers/Bundle/Application/8048C99E-C56B-4BC2-8A40-9EB7E13BF386/ThaliTest.app/www/index.html
,2016-09-15 13:56:57.688 ThaliTest[2445:4544481] JXcore Cordova plugin initializing
,2016-09-15 13:56:57.688 ThaliTest[2445:4544722] JXcore instance initializing
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
,Optional(false)
Optional(true)
,2016-09-15 13:57:04.363 ThaliTest[2445:4544481] BTM: attaching to BTServer
,2016-09-15 13:57:15.253 ThaliTest[2445:4544481] BTM: local device power state changed
2016-09-15 13:57:15.254 ThaliTest[2445:4544481] BTM: power is now on
,2016-09-15 13:57:19.939 ThaliTest[2445:4544481] BTM: local device power state changed
2016-09-15 13:57:19.939 ThaliTest[2445:4544481] BTM: power is now off
,received session: <ThaliCore.Session: 0x129958ca0>
,*Native tests were executed*
Total number of executed tests:  48
,Number of passed tests:  46
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  27.7819100022316
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
