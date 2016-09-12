#### Test 84265062d118465_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/84265062d118465/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4ED5EAFC-AFDE-45ED-8049-F3236FD0C0A0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4ED5EAFC-AFDE-45ED-8049-F3236FD0C0A0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/84265062d118465/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/84265062d118465/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/08708556-77DB-4079-9C5D-C3C92C3B9733/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50554"
,(lldb)     command script import "/tmp/4ED5EAFC-AFDE-45ED-8049-F3236FD0C0A0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 18:12:08.536 ThaliTest[2133:4169852] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3C160E3C-0D9F-46BB-8295-91A34360A3AB/Library/Cookies/Cookies.binarycookies
,2016-09-12 18:12:08.795 ThaliTest[2133:4169852] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 18:12:08.796 ThaliTest[2133:4169852] Multi-tasking -> Device: YES, App: YES
,2016-09-12 18:12:08.809 ThaliTest[2133:4169852] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 18:12:09.847 ThaliTest[2133:4169852] Using UIWebView
,2016-09-12 18:12:09.850 ThaliTest[2133:4169852] [CDVTimer][handleopenurl] 0.097036ms
,2016-09-12 18:12:09.852 ThaliTest[2133:4169852] [CDVTimer][intentandnavigationfilter] 1.807034ms
2016-09-12 18:12:09.852 ThaliTest[2133:4169852] [CDVTimer][gesturehandler] 0.136018ms
2016-09-12 18:12:09.852 ThaliTest[2133:4169852] [CDVTimer][TotalPluginStartup] 2.475023ms
,2016-09-12 18:12:13.529 ThaliTest[2133:4169852] Resetting plugins due to page load.
,2016-09-12 18:12:15.150 ThaliTest[2133:4169852] Finished load of: file:///var/mobile/Containers/Bundle/Application/08708556-77DB-4079-9C5D-C3C92C3B9733/ThaliTest.app/www/index.html
,2016-09-12 18:12:15.281 ThaliTest[2133:4169852] JXcore Cordova plugin initializing
2016-09-12 18:12:15.281 ThaliTest[2133:4170029] JXcore instance initializing
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
,2016-09-12 18:12:21.729 ThaliTest[2133:4169852] BTM: attaching to BTServer
,2016-09-12 18:12:31.802 ThaliTest[2133:4169852] BTM: local device power state changed
2016-09-12 18:12:31.803 ThaliTest[2133:4169852] BTM: power is now off
,2016-09-12 18:12:32.593 ThaliTest[2133:4169852] BTM: local device power state changed
2016-09-12 18:12:32.594 ThaliTest[2133:4169852] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  15
,Number of passed tests:  13
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  49.19510495662689
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
