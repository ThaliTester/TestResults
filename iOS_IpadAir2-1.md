#### Test 859603041ea1ffb_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/859603041ea1ffb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/29C393F2-F9E3-4F39-A77D-056F0C74EDF6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/29C393F2-F9E3-4F39-A77D-056F0C74EDF6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/859603041ea1ffb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/859603041ea1ffb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/78D66BAD-4D74-4B8C-B326-FD0BE2898EF9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51996"
,(lldb)     command script import "/tmp/29C393F2-F9E3-4F39-A77D-056F0C74EDF6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 12:11:36.400 ThaliTest[2835:5291366] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/68FBB766-0905-4413-A5A6-83306A02E5AC/Library/Cookies/Cookies.binarycookies
,2016-09-21 12:11:36.724 ThaliTest[2835:5291366] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 12:11:36.725 ThaliTest[2835:5291366] Multi-tasking -> Device: YES, App: YES
,2016-09-21 12:11:36.741 ThaliTest[2835:5291366] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 12:11:38.598 ThaliTest[2835:5291366] Using UIWebView
,2016-09-21 12:11:38.605 ThaliTest[2835:5291366] [CDVTimer][handleopenurl] 0.374019ms
,2016-09-21 12:11:38.612 ThaliTest[2835:5291366] [CDVTimer][intentandnavigationfilter] 6.766975ms
,2016-09-21 12:11:38.613 ThaliTest[2835:5291366] [CDVTimer][gesturehandler] 0.317037ms
,2016-09-21 12:11:38.614 ThaliTest[2835:5291366] [CDVTimer][TotalPluginStartup] 8.971989ms
,2016-09-21 12:11:46.126 ThaliTest[2835:5291366] Resetting plugins due to page load.
,2016-09-21 12:11:50.488 ThaliTest[2835:5291366] Finished load of: file:///var/mobile/Containers/Bundle/Application/78D66BAD-4D74-4B8C-B326-FD0BE2898EF9/ThaliTest.app/www/index.html
,2016-09-21 12:11:50.695 ThaliTest[2835:5291366] JXcore Cordova plugin initializing
,2016-09-21 12:11:50.696 ThaliTest[2835:5291660] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 12:11:56.834 ThaliTest[2835:5291660] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 12:11:56.835 ThaliTest[2835:5291660] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-21 12:11:56.835 ThaliTest[2835:5291660] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 12:11:56.837 ThaliTest[2835:5291660] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 12:11:57.114 ThaliTest[2835:5291660] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.005037963390350342
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
