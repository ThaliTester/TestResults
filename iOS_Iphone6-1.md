#### Test 861743790af7a74_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2F7452AB-6B4C-4AB7-8B7F-2F60DCD8297D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2F7452AB-6B4C-4AB7-8B7F-2F60DCD8297D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/165E5716-FFFB-4469-8BBF-85B6A1C946CC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63442"
,(lldb)     command script import "/tmp/2F7452AB-6B4C-4AB7-8B7F-2F60DCD8297D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 12:39:41.925 ThaliTest[1173:1735911] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4CB99DE7-C312-48D5-BA65-912910AA65BA/Library/Cookies/Cookies.binarycookies
,2016-09-22 12:39:42.001 ThaliTest[1173:1735911] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 12:39:42.003 ThaliTest[1173:1735911] Multi-tasking -> Device: YES, App: YES
,2016-09-22 12:39:42.024 ThaliTest[1173:1735911] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 12:39:42.502 ThaliTest[1173:1735911] Using UIWebView
,2016-09-22 12:39:42.509 ThaliTest[1173:1735911] [CDVTimer][handleopenurl] 0.441968ms
,2016-09-22 12:39:42.517 ThaliTest[1173:1735911] [CDVTimer][intentandnavigationfilter] 6.807029ms
2016-09-22 12:39:42.517 ThaliTest[1173:1735911] [CDVTimer][gesturehandler] 0.269949ms
2016-09-22 12:39:42.518 ThaliTest[1173:1735911] [CDVTimer][TotalPluginStartup] 9.108961ms
,2016-09-22 12:39:47.728 ThaliTest[1173:1735911] Resetting plugins due to page load.
,2016-09-22 12:39:48.124 ThaliTest[1173:1735911] Finished load of: file:///var/containers/Bundle/Application/165E5716-FFFB-4469-8BBF-85B6A1C946CC/ThaliTest.app/www/index.html
,2016-09-22 12:39:48.455 ThaliTest[1173:1735911] JXcore Cordova plugin initializing
,2016-09-22 12:39:48.456 ThaliTest[1173:1736078] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 12:39:55.997 ThaliTest[1173:1735911] BTM: attaching to BTServer
,2016-09-22 12:39:56.739 ThaliTest[1173:1735911] BTM: local device power state changed
2016-09-22 12:39:56.739 ThaliTest[1173:1735911] BTM: power is now on
,2016-09-22 12:40:01.473 ThaliTest[1173:1735911] BTM: local device power state changed
2016-09-22 12:40:01.473 ThaliTest[1173:1735911] BTM: power is now off
,received session: <ThaliCore.Session: 0x1361f9330>
,Optional("E5E9226F-3473-489E-B065-EBBB8C60B2EE")
,nil
,nil
,Optional("A9C82F70-04EE-476E-A312-325DD9B91282")
,Optional("11E85456-4078-4F5B-BF03-AA884234A645")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  21.05367398262024
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
