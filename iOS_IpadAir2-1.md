#### Test 80912877ffdb7be_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/80912877ffdb7be/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D362AE03-E274-4065-97A6-126D6E995C41/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D362AE03-E274-4065-97A6-126D6E995C41/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/80912877ffdb7be/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/80912877ffdb7be/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3C08DD0D-BBF9-4AD5-B105-FD899297FF13/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63635"
,(lldb)     command script import "/tmp/D362AE03-E274-4065-97A6-126D6E995C41/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-24 10:03:19.633 ThaliTest[866:1655628] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/02EE2DB5-6058-4A23-9DE9-3005142B707E/Library/Cookies/Cookies.binarycookies
,2016-08-24 10:03:20.094 ThaliTest[866:1655628] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-24 10:03:20.095 ThaliTest[866:1655628] Multi-tasking -> Device: YES, App: YES
,2016-08-24 10:03:20.114 ThaliTest[866:1655628] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-24 10:03:22.143 ThaliTest[866:1655628] Using UIWebView
,2016-08-24 10:03:22.154 ThaliTest[866:1655628] [CDVTimer][handleopenurl] 0.445008ms
,2016-08-24 10:03:22.162 ThaliTest[866:1655628] [CDVTimer][intentandnavigationfilter] 7.497013ms
,2016-08-24 10:03:22.163 ThaliTest[866:1655628] [CDVTimer][gesturehandler] 0.336945ms
2016-08-24 10:03:22.163 ThaliTest[866:1655628] [CDVTimer][TotalPluginStartup] 10.137975ms
,2016-08-24 10:03:29.306 ThaliTest[866:1655628] Resetting plugins due to page load.
,2016-08-24 10:03:33.219 ThaliTest[866:1655628] Finished load of: file:///var/mobile/Containers/Bundle/Application/3C08DD0D-BBF9-4AD5-B105-FD899297FF13/ThaliTest.app/www/index.html
,2016-08-24 10:03:33.446 ThaliTest[866:1655628] JXcore Cordova plugin initializing
,2016-08-24 10:03:33.447 ThaliTest[866:1655882] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-24 10:03:39.640 ThaliTest[866:1655882] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-24 10:03:39.641 ThaliTest[866:1655882] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-24 10:03:39.641 ThaliTest[866:1655882] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-24 10:03:39.643 ThaliTest[866:1655882] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-24 10:03:39.895 ThaliTest[866:1655882] Native method executeNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
