#### Test 80912877691b6a3_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/80912877691b6a3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4F1D6935-AFA8-48AA-B763-0E398873EB37/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4F1D6935-AFA8-48AA-B763-0E398873EB37/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/80912877691b6a3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/80912877691b6a3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1C73AD63-F0D8-43CC-BD84-80391087D2A1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65151"
,(lldb)     command script import "/tmp/4F1D6935-AFA8-48AA-B763-0E398873EB37/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-24 12:44:09.978 ThaliTest[877:1672976] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B656ADC0-3EBF-465E-AC17-8A4EB5A050EB/Library/Cookies/Cookies.binarycookies
,2016-08-24 12:44:10.421 ThaliTest[877:1672976] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-24 12:44:10.422 ThaliTest[877:1672976] Multi-tasking -> Device: YES, App: YES
,2016-08-24 12:44:10.441 ThaliTest[877:1672976] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-24 12:44:12.367 ThaliTest[877:1672976] Using UIWebView
,2016-08-24 12:44:12.374 ThaliTest[877:1672976] [CDVTimer][handleopenurl] 0.613987ms
,2016-08-24 12:44:12.381 ThaliTest[877:1672976] [CDVTimer][intentandnavigationfilter] 6.473005ms
,2016-08-24 12:44:12.382 ThaliTest[877:1672976] [CDVTimer][gesturehandler] 0.329018ms
2016-08-24 12:44:12.382 ThaliTest[877:1672976] [CDVTimer][TotalPluginStartup] 9.114981ms
,2016-08-24 12:44:18.759 ThaliTest[877:1672976] Resetting plugins due to page load.
,2016-08-24 12:44:21.975 ThaliTest[877:1672976] Finished load of: file:///var/mobile/Containers/Bundle/Application/1C73AD63-F0D8-43CC-BD84-80391087D2A1/ThaliTest.app/www/index.html
,2016-08-24 12:44:22.189 ThaliTest[877:1672976] JXcore Cordova plugin initializing
,2016-08-24 12:44:22.190 ThaliTest[877:1673236] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-24 12:44:28.353 ThaliTest[877:1673236] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-24 12:44:28.353 ThaliTest[877:1673236] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-24 12:44:28.353 ThaliTest[877:1673236] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-24 12:44:28.355 ThaliTest[877:1673236] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-24 12:44:28.606 ThaliTest[877:1673236] Native method executeNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
