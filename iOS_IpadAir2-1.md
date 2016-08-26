#### Test 797638309aa2d44_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638309aa2d44/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/43FAE553-AF4C-470A-80DB-019C708E0222/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/43FAE553-AF4C-470A-80DB-019C708E0222/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638309aa2d44/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638309aa2d44/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B8776C29-367D-4816-AB5F-58EC7DFFF0D7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65275"
,(lldb)     command script import "/tmp/43FAE553-AF4C-470A-80DB-019C708E0222/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 16:53:23.619 ThaliTest[1080:1995788] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CBB34308-060E-4D60-B2D0-5C41A5CB03B2/Library/Cookies/Cookies.binarycookies
,2016-08-26 16:53:23.973 ThaliTest[1080:1995788] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 16:53:23.974 ThaliTest[1080:1995788] Multi-tasking -> Device: YES, App: YES
,2016-08-26 16:53:23.990 ThaliTest[1080:1995788] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 16:53:25.837 ThaliTest[1080:1995788] Using UIWebView
,2016-08-26 16:53:25.846 ThaliTest[1080:1995788] [CDVTimer][handleopenurl] 0.415981ms
,2016-08-26 16:53:25.854 ThaliTest[1080:1995788] [CDVTimer][intentandnavigationfilter] 6.776989ms
,2016-08-26 16:53:25.855 ThaliTest[1080:1995788] [CDVTimer][gesturehandler] 0.337005ms
,2016-08-26 16:53:25.855 ThaliTest[1080:1995788] [CDVTimer][TotalPluginStartup] 9.449005ms
,2016-08-26 16:53:32.177 ThaliTest[1080:1995788] Resetting plugins due to page load.
,2016-08-26 16:53:35.756 ThaliTest[1080:1995788] Finished load of: file:///var/mobile/Containers/Bundle/Application/B8776C29-367D-4816-AB5F-58EC7DFFF0D7/ThaliTest.app/www/index.html
,2016-08-26 16:53:35.982 ThaliTest[1080:1995788] JXcore Cordova plugin initializing
,2016-08-26 16:53:35.982 ThaliTest[1080:1996025] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 16:53:42.113 ThaliTest[1080:1996025] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-26 16:53:42.113 ThaliTest[1080:1996025] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-26 16:53:42.114 ThaliTest[1080:1996025] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 16:53:42.115 ThaliTest[1080:1996025] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 16:53:42.405 ThaliTest[1080:1996025] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01389199495315552
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
