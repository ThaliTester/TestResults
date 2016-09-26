#### Test 8670851855de81a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8670851855de81a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D71F9373-696A-40FE-9A3F-E6B1B3B2D3BF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D71F9373-696A-40FE-9A3F-E6B1B3B2D3BF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8670851855de81a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8670851855de81a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DEFF694E-D732-44F3-AD03-FE21ACD38598/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60399"
,(lldb)     command script import "/tmp/D71F9373-696A-40FE-9A3F-E6B1B3B2D3BF/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 11:45:56.614 ThaliTest[3330:5942744] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/149C0A95-CD83-4486-BB37-BE2DE1916FB7/Library/Cookies/Cookies.binarycookies
,2016-09-26 11:45:57.011 ThaliTest[3330:5942744] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 11:45:57.013 ThaliTest[3330:5942744] Multi-tasking -> Device: YES, App: YES
,2016-09-26 11:45:57.034 ThaliTest[3330:5942744] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 11:45:58.992 ThaliTest[3330:5942744] Using UIWebView
,2016-09-26 11:45:58.999 ThaliTest[3330:5942744] [CDVTimer][handleopenurl] 0.346005ms
,2016-09-26 11:45:59.007 ThaliTest[3330:5942744] [CDVTimer][intentandnavigationfilter] 6.793976ms
,2016-09-26 11:45:59.007 ThaliTest[3330:5942744] [CDVTimer][gesturehandler] 0.284016ms
,2016-09-26 11:45:59.008 ThaliTest[3330:5942744] [CDVTimer][TotalPluginStartup] 8.931994ms
,2016-09-26 11:46:05.428 ThaliTest[3330:5942744] Resetting plugins due to page load.
,2016-09-26 11:46:08.350 ThaliTest[3330:5942744] Finished load of: file:///var/mobile/Containers/Bundle/Application/DEFF694E-D732-44F3-AD03-FE21ACD38598/ThaliTest.app/www/index.html
,2016-09-26 11:46:08.634 ThaliTest[3330:5942744] JXcore Cordova plugin initializing
,2016-09-26 11:46:08.635 ThaliTest[3330:5942987] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x14f42a870>
,Optional("3A0C8335-22B3-45FD-9148-6F1C35E9C40E")
,nil
,nil
,Optional("CAEDDC27-729B-4367-BA4E-F36C43B7ABD7")
,Optional("5594CD67-FC49-4A89-B051-70083670D9F0")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-26 11:46:34.846 ThaliTest[3330:5942744] BTM: attaching to BTServer
,2016-09-26 11:46:35.669 ThaliTest[3330:5942744] BTM: local device power state changed
2016-09-26 11:46:35.670 ThaliTest[3330:5942744] BTM: power is now on
,2016-09-26 11:46:40.340 ThaliTest[3330:5942744] BTM: local device power state changed
2016-09-26 11:46:40.341 ThaliTest[3330:5942744] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  50
,Number of passed tests:  48
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  25.03624898195267
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
