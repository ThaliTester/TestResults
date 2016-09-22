#### Test 83268893919c9ad_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/25AAE856-F87D-4B86-8ED4-879F80523E87/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/25AAE856-F87D-4B86-8ED4-879F80523E87/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/73C4C349-2EFA-4B3D-A062-25AD28D84C9D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57921"
,(lldb)     command script import "/tmp/25AAE856-F87D-4B86-8ED4-879F80523E87/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 10:31:54.606 ThaliTest[2986:5421785] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D5836BD8-2D90-4CE2-B537-531E107CDDBC/Library/Cookies/Cookies.binarycookies
,2016-09-22 10:31:54.955 ThaliTest[2986:5421785] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 10:31:54.956 ThaliTest[2986:5421785] Multi-tasking -> Device: YES, App: YES
,2016-09-22 10:31:54.974 ThaliTest[2986:5421785] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 10:31:56.951 ThaliTest[2986:5421785] Using UIWebView
,2016-09-22 10:31:56.958 ThaliTest[2986:5421785] [CDVTimer][handleopenurl] 0.365973ms
,2016-09-22 10:31:56.965 ThaliTest[2986:5421785] [CDVTimer][intentandnavigationfilter] 6.344020ms
,2016-09-22 10:31:56.966 ThaliTest[2986:5421785] [CDVTimer][gesturehandler] 0.299990ms
,2016-09-22 10:31:56.966 ThaliTest[2986:5421785] [CDVTimer][TotalPluginStartup] 8.601010ms
,2016-09-22 10:32:03.331 ThaliTest[2986:5421785] Resetting plugins due to page load.
,2016-09-22 10:32:06.231 ThaliTest[2986:5421785] Finished load of: file:///var/mobile/Containers/Bundle/Application/73C4C349-2EFA-4B3D-A062-25AD28D84C9D/ThaliTest.app/www/index.html
,2016-09-22 10:32:06.503 ThaliTest[2986:5421785] JXcore Cordova plugin initializing
,2016-09-22 10:32:06.505 ThaliTest[2986:5422007] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x14f2fa8a0>
,Optional("AEBD61DD-C32C-4836-B755-E5F513682F80")
,nil
,nil
,Optional("4A98D0DA-6056-4B45-9F65-A68D213C8765")
,Optional("8AAB3090-1E3F-4E95-B766-95C595FDC499")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 10:32:32.771 ThaliTest[2986:5421785] BTM: attaching to BTServer
,2016-09-22 10:32:33.577 ThaliTest[2986:5421785] BTM: local device power state changed
2016-09-22 10:32:33.577 ThaliTest[2986:5421785] BTM: power is now on
,2016-09-22 10:32:38.238 ThaliTest[2986:5421785] BTM: local device power state changed
2016-09-22 10:32:38.239 ThaliTest[2986:5421785] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.18652004003525
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
