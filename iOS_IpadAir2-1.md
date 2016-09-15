#### Test 829140738877506_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/EAADDDAB-FD34-4C9C-BBBE-72AA543027A3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/EAADDDAB-FD34-4C9C-BBBE-72AA543027A3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5B126508-8CCA-4752-88D5-F301A31BDCF7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52902"
,(lldb)     command script import "/tmp/EAADDDAB-FD34-4C9C-BBBE-72AA543027A3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 14:02:46.133 ThaliTest[2453:4546177] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/489E9145-F77A-440B-8829-1AF125EBAD64/Library/Cookies/Cookies.binarycookies
,2016-09-15 14:02:46.446 ThaliTest[2453:4546177] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 14:02:46.447 ThaliTest[2453:4546177] Multi-tasking -> Device: YES, App: YES
,2016-09-15 14:02:46.462 ThaliTest[2453:4546177] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 14:02:48.150 ThaliTest[2453:4546177] Using UIWebView
,2016-09-15 14:02:48.157 ThaliTest[2453:4546177] [CDVTimer][handleopenurl] 0.342965ms
,2016-09-15 14:02:48.164 ThaliTest[2453:4546177] [CDVTimer][intentandnavigationfilter] 6.514966ms
,2016-09-15 14:02:48.165 ThaliTest[2453:4546177] [CDVTimer][gesturehandler] 0.311017ms
,2016-09-15 14:02:48.165 ThaliTest[2453:4546177] [CDVTimer][TotalPluginStartup] 8.677006ms
,2016-09-15 14:02:54.443 ThaliTest[2453:4546177] Resetting plugins due to page load.
,2016-09-15 14:02:57.359 ThaliTest[2453:4546177] Finished load of: file:///var/mobile/Containers/Bundle/Application/5B126508-8CCA-4752-88D5-F301A31BDCF7/ThaliTest.app/www/index.html
,2016-09-15 14:02:57.629 ThaliTest[2453:4546177] JXcore Cordova plugin initializing
,2016-09-15 14:02:57.630 ThaliTest[2453:4546417] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x10c70f210>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-15 14:03:17.537 ThaliTest[2453:4546177] BTM: attaching to BTServer
,2016-09-15 14:03:18.338 ThaliTest[2453:4546177] BTM: local device power state changed
2016-09-15 14:03:18.338 ThaliTest[2453:4546177] BTM: power is now on
,2016-09-15 14:03:22.998 ThaliTest[2453:4546177] BTM: local device power state changed
2016-09-15 14:03:22.998 ThaliTest[2453:4546177] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  48
,Number of passed tests:  48
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  18.68994498252869
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
