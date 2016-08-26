#### Test 82914073856d1c8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073856d1c8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7C4A6D18-08BB-461B-85D9-04F8157C0AEC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7C4A6D18-08BB-461B-85D9-04F8157C0AEC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073856d1c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073856d1c8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6B057C1D-1E0E-4803-9540-C76A4E3761BF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59597"
,(lldb)     command script import "/tmp/7C4A6D18-08BB-461B-85D9-04F8157C0AEC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 19:44:05.495 ThaliTest[1115:2016938] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1593FC4F-49C1-44C0-A51D-C1926BDA2F0D/Library/Cookies/Cookies.binarycookies
,2016-08-26 19:44:05.931 ThaliTest[1115:2016938] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 19:44:05.933 ThaliTest[1115:2016938] Multi-tasking -> Device: YES, App: YES
,2016-08-26 19:44:05.951 ThaliTest[1115:2016938] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 19:44:07.988 ThaliTest[1115:2016938] Using UIWebView
,2016-08-26 19:44:07.995 ThaliTest[1115:2016938] [CDVTimer][handleopenurl] 0.427961ms
,2016-08-26 19:44:08.002 ThaliTest[1115:2016938] [CDVTimer][intentandnavigationfilter] 7.171988ms
,2016-08-26 19:44:08.003 ThaliTest[1115:2016938] [CDVTimer][gesturehandler] 0.312984ms
,2016-08-26 19:44:08.003 ThaliTest[1115:2016938] [CDVTimer][TotalPluginStartup] 9.687006ms
,2016-08-26 19:44:14.571 ThaliTest[1115:2016938] Resetting plugins due to page load.
,2016-08-26 19:44:18.493 ThaliTest[1115:2016938] Finished load of: file:///var/mobile/Containers/Bundle/Application/6B057C1D-1E0E-4803-9540-C76A4E3761BF/ThaliTest.app/www/index.html
,2016-08-26 19:44:18.707 ThaliTest[1115:2016938] JXcore Cordova plugin initializing
,2016-08-26 19:44:18.708 ThaliTest[1115:2017195] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  20
Number of passed tests:  20
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  42.59232598543167
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
