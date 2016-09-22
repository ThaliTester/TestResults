#### Test 85960304727dacc_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304727dacc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/BDB31F13-B6D3-4566-BD85-47D0CA230A7D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BDB31F13-B6D3-4566-BD85-47D0CA230A7D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304727dacc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304727dacc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/702515D2-6667-49B8-B916-268088F3B27E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53063"
,(lldb)     command script import "/tmp/BDB31F13-B6D3-4566-BD85-47D0CA230A7D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 15:00:03.811 ThaliTest[3045:5451775] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8108C1CA-3563-422E-B741-53C0DE9EAB3B/Library/Cookies/Cookies.binarycookies
,2016-09-22 15:00:04.132 ThaliTest[3045:5451775] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 15:00:04.133 ThaliTest[3045:5451775] Multi-tasking -> Device: YES, App: YES
,2016-09-22 15:00:04.147 ThaliTest[3045:5451775] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 15:00:05.909 ThaliTest[3045:5451775] Using UIWebView
,2016-09-22 15:00:05.920 ThaliTest[3045:5451775] [CDVTimer][handleopenurl] 0.383973ms
,2016-09-22 15:00:05.927 ThaliTest[3045:5451775] [CDVTimer][intentandnavigationfilter] 6.523013ms
,2016-09-22 15:00:05.928 ThaliTest[3045:5451775] [CDVTimer][gesturehandler] 0.286043ms
,2016-09-22 15:00:05.928 ThaliTest[3045:5451775] [CDVTimer][TotalPluginStartup] 8.906007ms
,2016-09-22 15:00:12.321 ThaliTest[3045:5451775] Resetting plugins due to page load.
,2016-09-22 15:00:15.355 ThaliTest[3045:5451775] Finished load of: file:///var/mobile/Containers/Bundle/Application/702515D2-6667-49B8-B916-268088F3B27E/ThaliTest.app/www/index.html
,2016-09-22 15:00:15.619 ThaliTest[3045:5451775] JXcore Cordova plugin initializing
,2016-09-22 15:00:15.619 ThaliTest[3045:5452033] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x12d7d0b90>
,Optional("A4686E13-46DB-4D75-9077-6757C13C058F")
,nil
,nil
,Optional("D81F8267-A6C2-4744-BEFA-D5396A3997B3")
,Optional("6F8C813C-00FB-4968-9137-F662806435E6")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 15:00:41.260 ThaliTest[3045:5451775] BTM: attaching to BTServer
,2016-09-22 15:00:42.071 ThaliTest[3045:5451775] BTM: local device power state changed
2016-09-22 15:00:42.071 ThaliTest[3045:5451775] BTM: power is now on
,2016-09-22 15:00:46.722 ThaliTest[3045:5451775] BTM: local device power state changed
2016-09-22 15:00:46.723 ThaliTest[3045:5451775] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.58448398113251
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
