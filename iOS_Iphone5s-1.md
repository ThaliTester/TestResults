#### Test 836273372e7ca3d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4BE0D96A-F321-466A-8750-4ABA2C66BC73/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4BE0D96A-F321-466A-8750-4ABA2C66BC73/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273372e7ca3d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/83FE3120-EA6C-450E-9585-1E19ABAD575F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59924"
,(lldb)     command script import "/tmp/4BE0D96A-F321-466A-8750-4ABA2C66BC73/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 09:16:07.898 ThaliTest[2097:4544037] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/469445DC-9DC8-4742-B3E3-52D1C58E1877/Library/Cookies/Cookies.binarycookies
,2016-09-13 09:16:08.298 ThaliTest[2097:4544037] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 09:16:08.300 ThaliTest[2097:4544037] Multi-tasking -> Device: YES, App: YES
,2016-09-13 09:16:08.326 ThaliTest[2097:4544037] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 09:16:10.034 ThaliTest[2097:4544037] Using UIWebView
,2016-09-13 09:16:10.042 ThaliTest[2097:4544037] [CDVTimer][handleopenurl] 0.428021ms
,2016-09-13 09:16:10.051 ThaliTest[2097:4544037] [CDVTimer][intentandnavigationfilter] 8.008003ms
2016-09-13 09:16:10.052 ThaliTest[2097:4544037] [CDVTimer][gesturehandler] 0.393033ms
2016-09-13 09:16:10.052 ThaliTest[2097:4544037] [CDVTimer][TotalPluginStartup] 10.857046ms
,2016-09-13 09:16:16.858 ThaliTest[2097:4544037] Resetting plugins due to page load.
,2016-09-13 09:16:20.376 ThaliTest[2097:4544037] Finished load of: file:///var/mobile/Containers/Bundle/Application/83FE3120-EA6C-450E-9585-1E19ABAD575F/ThaliTest.app/www/index.html
,2016-09-13 09:16:20.599 ThaliTest[2097:4544037] JXcore Cordova plugin initializing
,2016-09-13 09:16:20.601 ThaliTest[2097:4544298] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 09:16:28.691 ThaliTest[2097:4544298] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-13 09:16:28.692 ThaliTest[2097:4544298] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 09:16:28.693 ThaliTest[2097:4544298] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 09:16:28.695 ThaliTest[2097:4544298] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
