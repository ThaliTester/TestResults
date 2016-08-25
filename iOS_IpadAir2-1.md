#### Test 82728424ebd9a7c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82728424ebd9a7c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/06EE61F3-330E-42D7-A028-B24E88A333D3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/06EE61F3-330E-42D7-A028-B24E88A333D3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82728424ebd9a7c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82728424ebd9a7c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A4A93131-0B25-4662-BF50-7E684E1FCC9F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61352"
,(lldb)     command script import "/tmp/06EE61F3-330E-42D7-A028-B24E88A333D3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 17:37:57.769 ThaliTest[970:1846984] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BD5F1C6B-D49A-4570-89E5-8D363058761F/Library/Cookies/Cookies.binarycookies
,2016-08-25 17:37:58.164 ThaliTest[970:1846984] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 17:37:58.165 ThaliTest[970:1846984] Multi-tasking -> Device: YES, App: YES
,2016-08-25 17:37:58.185 ThaliTest[970:1846984] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 17:38:00.153 ThaliTest[970:1846984] Using UIWebView
,2016-08-25 17:38:00.158 ThaliTest[970:1846984] [CDVTimer][handleopenurl] 0.303984ms
,2016-08-25 17:38:00.163 ThaliTest[970:1846984] [CDVTimer][intentandnavigationfilter] 4.354000ms
,2016-08-25 17:38:00.164 ThaliTest[970:1846984] [CDVTimer][gesturehandler] 0.191033ms
,2016-08-25 17:38:00.164 ThaliTest[970:1846984] [CDVTimer][TotalPluginStartup] 5.814970ms
,2016-08-25 17:38:06.626 ThaliTest[970:1846984] Resetting plugins due to page load.
,2016-08-25 17:38:10.330 ThaliTest[970:1846984] Finished load of: file:///var/mobile/Containers/Bundle/Application/A4A93131-0B25-4662-BF50-7E684E1FCC9F/ThaliTest.app/www/index.html
,2016-08-25 17:38:10.547 ThaliTest[970:1846984] JXcore Cordova plugin initializing
2016-08-25 17:38:10.547 ThaliTest[970:1847270] JXcore instance initializing
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
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
