#### Test 86482582895a768_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86482582895a768/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A35CF99D-DE4D-48BE-983C-B428A06E7246/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A35CF99D-DE4D-48BE-983C-B428A06E7246/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86482582895a768/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86482582895a768/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4F8A00A9-5C86-42DB-8CE5-7519D2744684/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62785"
,(lldb)     command script import "/tmp/A35CF99D-DE4D-48BE-983C-B428A06E7246/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 16:58:16.304 ThaliTest[3224:5605145] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2CE8A783-C4E0-4DAE-89CA-40EF1C138E3B/Library/Cookies/Cookies.binarycookies
,2016-09-23 16:58:16.668 ThaliTest[3224:5605145] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 16:58:16.670 ThaliTest[3224:5605145] Multi-tasking -> Device: YES, App: YES
,2016-09-23 16:58:16.689 ThaliTest[3224:5605145] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 16:58:18.655 ThaliTest[3224:5605145] Using UIWebView
,2016-09-23 16:58:18.662 ThaliTest[3224:5605145] [CDVTimer][handleopenurl] 0.526011ms
,2016-09-23 16:58:18.670 ThaliTest[3224:5605145] [CDVTimer][intentandnavigationfilter] 7.622004ms
,2016-09-23 16:58:18.671 ThaliTest[3224:5605145] [CDVTimer][gesturehandler] 0.423014ms
2016-09-23 16:58:18.671 ThaliTest[3224:5605145] [CDVTimer][TotalPluginStartup] 10.134041ms
,2016-09-23 16:58:25.221 ThaliTest[3224:5605145] Resetting plugins due to page load.
,2016-09-23 16:58:28.380 ThaliTest[3224:5605145] Finished load of: file:///var/mobile/Containers/Bundle/Application/4F8A00A9-5C86-42DB-8CE5-7519D2744684/ThaliTest.app/www/index.html
,2016-09-23 16:58:28.654 ThaliTest[3224:5605145] JXcore Cordova plugin initializing
,2016-09-23 16:58:28.654 ThaliTest[3224:5605392] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x147fb4070>
,Optional("8D47853B-58E4-48BF-AAAC-3108A541957A")
,nil
,nil
,Optional("5489D61C-E978-4180-B64A-B65F30345A88")
,Optional("EA8F11AA-12AB-41A0-BE69-CF0DC2A2F026")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-23 16:58:54.881 ThaliTest[3224:5605145] BTM: attaching to BTServer
,2016-09-23 16:58:55.693 ThaliTest[3224:5605145] BTM: local device power state changed
2016-09-23 16:58:55.697 ThaliTest[3224:5605145] BTM: power is now on
,2016-09-23 16:59:00.355 ThaliTest[3224:5605145] BTM: local device power state changed
2016-09-23 16:59:00.356 ThaliTest[3224:5605145] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.06786900758743
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
