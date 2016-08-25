#### Test 79763830bc83054_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830bc83054/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/302A4C12-E20E-4BCC-BED6-A2A0B68FA986/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/302A4C12-E20E-4BCC-BED6-A2A0B68FA986/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830bc83054/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830bc83054/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4AAE5C06-A7A4-43F7-9211-B660BC8AED14/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52749"
,(lldb)     command script import "/tmp/302A4C12-E20E-4BCC-BED6-A2A0B68FA986/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-25 10:45:30.024 ThaliTest[930:1801967] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6E21BC3F-8D29-4130-8CE8-FA1E0A1C3BCB/Library/Cookies/Cookies.binarycookies
,2016-08-25 10:45:30.445 ThaliTest[930:1801967] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 10:45:30.447 ThaliTest[930:1801967] Multi-tasking -> Device: YES, App: YES
,2016-08-25 10:45:30.465 ThaliTest[930:1801967] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 10:45:32.530 ThaliTest[930:1801967] Using UIWebView
,2016-08-25 10:45:32.537 ThaliTest[930:1801967] [CDVTimer][handleopenurl] 0.431001ms
,2016-08-25 10:45:32.544 ThaliTest[930:1801967] [CDVTimer][intentandnavigationfilter] 6.944001ms
,2016-08-25 10:45:32.545 ThaliTest[930:1801967] [CDVTimer][gesturehandler] 0.326991ms
,2016-08-25 10:45:32.545 ThaliTest[930:1801967] [CDVTimer][TotalPluginStartup] 9.287000ms
,2016-08-25 10:45:39.811 ThaliTest[930:1801967] Resetting plugins due to page load.
,2016-08-25 10:45:43.585 ThaliTest[930:1801967] Finished load of: file:///var/mobile/Containers/Bundle/Application/4AAE5C06-A7A4-43F7-9211-B660BC8AED14/ThaliTest.app/www/index.html
,2016-08-25 10:45:43.805 ThaliTest[930:1801967] JXcore Cordova plugin initializing
,2016-08-25 10:45:43.805 ThaliTest[930:1802264] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-25 10:45:49.973 ThaliTest[930:1802264] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-25 10:45:49.973 ThaliTest[930:1802264] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-25 10:45:49.974 ThaliTest[930:1802264] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-25 10:45:49.975 ThaliTest[930:1802264] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-25 10:45:50.228 ThaliTest[930:1802264] Native method executeNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
