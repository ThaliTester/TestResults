#### Test 85046911c8db9f2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c8db9f2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/EA349562-96A7-4AE6-8714-A8D97C5C66C4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/EA349562-96A7-4AE6-8714-A8D97C5C66C4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c8db9f2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c8db9f2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D4B1C132-0936-445A-8E8D-E5296606FAC4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59811"
,(lldb)     command script import "/tmp/EA349562-96A7-4AE6-8714-A8D97C5C66C4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 16:00:04.835 ThaliTest[2872:5314444] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/68BCEA20-9BF8-4674-ACC3-BAAA6B09FCFE/Library/Cookies/Cookies.binarycookies
,2016-09-21 16:00:05.177 ThaliTest[2872:5314444] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 16:00:05.178 ThaliTest[2872:5314444] Multi-tasking -> Device: YES, App: YES
,2016-09-21 16:00:05.193 ThaliTest[2872:5314444] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 16:00:07.189 ThaliTest[2872:5314444] Using UIWebView
,2016-09-21 16:00:07.199 ThaliTest[2872:5314444] [CDVTimer][handleopenurl] 0.384986ms
,2016-09-21 16:00:07.206 ThaliTest[2872:5314444] [CDVTimer][intentandnavigationfilter] 6.887019ms
,2016-09-21 16:00:07.207 ThaliTest[2872:5314444] [CDVTimer][gesturehandler] 0.347972ms
,2016-09-21 16:00:07.208 ThaliTest[2872:5314444] [CDVTimer][TotalPluginStartup] 9.289980ms
,2016-09-21 16:00:13.672 ThaliTest[2872:5314444] Resetting plugins due to page load.
,2016-09-21 16:00:17.274 ThaliTest[2872:5314444] Finished load of: file:///var/mobile/Containers/Bundle/Application/D4B1C132-0936-445A-8E8D-E5296606FAC4/ThaliTest.app/www/index.html
,2016-09-21 16:00:17.480 ThaliTest[2872:5314444] JXcore Cordova plugin initializing
,2016-09-21 16:00:17.481 ThaliTest[2872:5314716] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 16:00:23.576 ThaliTest[2872:5314716] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 16:00:23.577 ThaliTest[2872:5314716] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-21 16:00:23.577 ThaliTest[2872:5314716] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 16:00:23.578 ThaliTest[2872:5314716] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 16:00:23.865 ThaliTest[2872:5314716] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005057036876678467
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
