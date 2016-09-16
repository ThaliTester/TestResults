#### Test 85519194329c724_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85519194329c724/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/0BD23C96-E4F1-43D6-B25D-A1DCF0EC6573/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0BD23C96-E4F1-43D6-B25D-A1DCF0EC6573/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85519194329c724/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85519194329c724/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CF9B75B7-8467-4A76-AABD-6F088775FA7E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50223"
,(lldb)     command script import "/tmp/0BD23C96-E4F1-43D6-B25D-A1DCF0EC6573/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 07:22:09.405 ThaliTest[2506:4638305] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2AF1BBFE-4AC7-4832-82DF-E87A8CBE0CE9/Library/Cookies/Cookies.binarycookies
,2016-09-16 07:22:09.788 ThaliTest[2506:4638305] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 07:22:09.790 ThaliTest[2506:4638305] Multi-tasking -> Device: YES, App: YES
,2016-09-16 07:22:09.810 ThaliTest[2506:4638305] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 07:22:11.876 ThaliTest[2506:4638305] Using UIWebView
,2016-09-16 07:22:11.882 ThaliTest[2506:4638305] [CDVTimer][handleopenurl] 0.335991ms
,2016-09-16 07:22:11.890 ThaliTest[2506:4638305] [CDVTimer][intentandnavigationfilter] 6.855011ms
,2016-09-16 07:22:11.891 ThaliTest[2506:4638305] [CDVTimer][gesturehandler] 0.487030ms
,2016-09-16 07:22:11.891 ThaliTest[2506:4638305] [CDVTimer][TotalPluginStartup] 9.375989ms
,2016-09-16 07:22:19.885 ThaliTest[2506:4638305] Resetting plugins due to page load.
,2016-09-16 07:22:23.680 ThaliTest[2506:4638305] Finished load of: file:///var/mobile/Containers/Bundle/Application/CF9B75B7-8467-4A76-AABD-6F088775FA7E/ThaliTest.app/www/index.html
,2016-09-16 07:22:23.898 ThaliTest[2506:4638305] JXcore Cordova plugin initializing
,2016-09-16 07:22:23.899 ThaliTest[2506:4638562] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Unit Test app is loaded

```
