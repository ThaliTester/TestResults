#### Test 82914073b4ce5c2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073b4ce5c2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9E6A5B86-FD51-46C8-8EDB-D37A0980B147/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9E6A5B86-FD51-46C8-8EDB-D37A0980B147/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073b4ce5c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073b4ce5c2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FDC9AA73-895E-4D16-8C8D-C4920258C55A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58139"
,(lldb)     command script import "/tmp/9E6A5B86-FD51-46C8-8EDB-D37A0980B147/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 15:11:10.034 ThaliTest[2221:4284098] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/65683EDB-ABAC-4E91-9BED-0C6A530E80CF/Library/Cookies/Cookies.binarycookies
,2016-09-13 15:11:10.267 ThaliTest[2221:4284098] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 15:11:10.268 ThaliTest[2221:4284098] Multi-tasking -> Device: YES, App: YES
,2016-09-13 15:11:10.280 ThaliTest[2221:4284098] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 15:11:11.219 ThaliTest[2221:4284098] Using UIWebView
,2016-09-13 15:11:11.221 ThaliTest[2221:4284098] [CDVTimer][handleopenurl] 0.089049ms
,2016-09-13 15:11:11.223 ThaliTest[2221:4284098] [CDVTimer][intentandnavigationfilter] 1.816034ms
2016-09-13 15:11:11.223 ThaliTest[2221:4284098] [CDVTimer][gesturehandler] 0.081003ms
2016-09-13 15:11:11.223 ThaliTest[2221:4284098] [CDVTimer][TotalPluginStartup] 2.424955ms
,2016-09-13 15:11:14.561 ThaliTest[2221:4284098] Resetting plugins due to page load.
,2016-09-13 15:11:16.087 ThaliTest[2221:4284098] Finished load of: file:///var/mobile/Containers/Bundle/Application/FDC9AA73-895E-4D16-8C8D-C4920258C55A/ThaliTest.app/www/index.html
,2016-09-13 15:11:16.227 ThaliTest[2221:4284098] JXcore Cordova plugin initializing
,2016-09-13 15:11:16.228 ThaliTest[2221:4284265] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12737ab40>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-13 15:11:35.790 ThaliTest[2221:4284098] BTM: attaching to BTServer
,2016-09-13 15:11:36.562 ThaliTest[2221:4284098] BTM: local device power state changed
,2016-09-13 15:11:36.562 ThaliTest[2221:4284098] BTM: power is now off
,2016-09-13 15:11:37.360 ThaliTest[2221:4284098] BTM: local device power state changed
2016-09-13 15:11:37.360 ThaliTest[2221:4284098] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  14.88655799627304
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
