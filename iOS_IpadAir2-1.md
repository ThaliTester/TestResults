#### Test 82894682a24f9af_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682a24f9af/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A054051B-E7DB-4994-A97D-A5E921E4C2AB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A054051B-E7DB-4994-A97D-A5E921E4C2AB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682a24f9af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682a24f9af/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D575C8C9-EC4C-405E-A258-B66F553F2EB4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51615"
,(lldb)     command script import "/tmp/A054051B-E7DB-4994-A97D-A5E921E4C2AB/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 17:36:02.435 ThaliTest[1089:2001312] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F0C05620-20E4-4CDB-9F00-9D7644EBCADA/Library/Cookies/Cookies.binarycookies
,2016-08-26 17:36:02.869 ThaliTest[1089:2001312] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 17:36:02.870 ThaliTest[1089:2001312] Multi-tasking -> Device: YES, App: YES
,2016-08-26 17:36:02.890 ThaliTest[1089:2001312] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 17:36:04.851 ThaliTest[1089:2001312] Using UIWebView
,2016-08-26 17:36:04.858 ThaliTest[1089:2001312] [CDVTimer][handleopenurl] 0.400007ms
,2016-08-26 17:36:04.865 ThaliTest[1089:2001312] [CDVTimer][intentandnavigationfilter] 6.577969ms
,2016-08-26 17:36:04.866 ThaliTest[1089:2001312] [CDVTimer][gesturehandler] 0.301003ms
,2016-08-26 17:36:04.866 ThaliTest[1089:2001312] [CDVTimer][TotalPluginStartup] 8.970976ms
,2016-08-26 17:36:11.962 ThaliTest[1089:2001312] Resetting plugins due to page load.
,2016-08-26 17:36:16.007 ThaliTest[1089:2001312] Finished load of: file:///var/mobile/Containers/Bundle/Application/D575C8C9-EC4C-405E-A258-B66F553F2EB4/ThaliTest.app/www/index.html
,2016-08-26 17:36:16.235 ThaliTest[1089:2001312] JXcore Cordova plugin initializing
,2016-08-26 17:36:16.236 ThaliTest[1089:2001543] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"cellular":"doNotCare","wifi":"on","bluetoothLowEnergy":"off","bluetooth":"off"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
,Total number of executed tests:  5
,Number of passed tests:  5
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.006604015827178955
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
