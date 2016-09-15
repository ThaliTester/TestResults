#### Test 83627337176b608_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/07726EF6-4AA8-4579-ABF6-EA450863B105/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/07726EF6-4AA8-4579-ABF6-EA450863B105/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/65213572-D850-413B-B894-2A07C07CB6C9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59227"
,(lldb)     command script import "/tmp/07726EF6-4AA8-4579-ABF6-EA450863B105/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 16:28:38.376 ThaliTest[2471:4560610] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0D7A8A71-0F8B-4218-AADE-FF8E5E544E1E/Library/Cookies/Cookies.binarycookies
,2016-09-15 16:28:38.753 ThaliTest[2471:4560610] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 16:28:38.755 ThaliTest[2471:4560610] Multi-tasking -> Device: YES, App: YES
,2016-09-15 16:28:38.774 ThaliTest[2471:4560610] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 16:28:40.671 ThaliTest[2471:4560610] Using UIWebView
,2016-09-15 16:28:40.678 ThaliTest[2471:4560610] [CDVTimer][handleopenurl] 0.378013ms
,2016-09-15 16:28:40.686 ThaliTest[2471:4560610] [CDVTimer][intentandnavigationfilter] 7.353008ms
,2016-09-15 16:28:40.687 ThaliTest[2471:4560610] [CDVTimer][gesturehandler] 0.353038ms
,2016-09-15 16:28:40.687 ThaliTest[2471:4560610] [CDVTimer][TotalPluginStartup] 9.762049ms
,2016-09-15 16:28:47.858 ThaliTest[2471:4560610] Resetting plugins due to page load.
,2016-09-15 16:28:51.457 ThaliTest[2471:4560610] Finished load of: file:///var/mobile/Containers/Bundle/Application/65213572-D850-413B-B894-2A07C07CB6C9/ThaliTest.app/www/index.html
,2016-09-15 16:28:51.655 ThaliTest[2471:4560610] JXcore Cordova plugin initializing
,2016-09-15 16:28:51.656 ThaliTest[2471:4560873] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 16:28:57.885 ThaliTest[2471:4560873] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 16:28:57.886 ThaliTest[2471:4560873] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 16:28:57.886 ThaliTest[2471:4560873] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-15 16:28:57.888 ThaliTest[2471:4560873] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-15 16:28:58.178 ThaliTest[2471:4560873] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.005084991455078125
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
