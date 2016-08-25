#### Test 827284243e10cd0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/827284243e10cd0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/73FEBE73-4147-442E-8C2B-D9FBA7C35C3C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/73FEBE73-4147-442E-8C2B-D9FBA7C35C3C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/827284243e10cd0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/827284243e10cd0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/565B3BD9-EB51-42BE-B1BB-F866777B14C3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60116"
,(lldb)     command script import "/tmp/73FEBE73-4147-442E-8C2B-D9FBA7C35C3C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-25 17:18:53.100 ThaliTest[962:1844261] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6651A55D-9F59-43A9-A916-DD49344725CE/Library/Cookies/Cookies.binarycookies
,2016-08-25 17:18:53.460 ThaliTest[962:1844261] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 17:18:53.461 ThaliTest[962:1844261] Multi-tasking -> Device: YES, App: YES
,2016-08-25 17:18:53.479 ThaliTest[962:1844261] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 17:18:55.328 ThaliTest[962:1844261] Using UIWebView
,2016-08-25 17:18:55.335 ThaliTest[962:1844261] [CDVTimer][handleopenurl] 0.389993ms
,2016-08-25 17:18:55.343 ThaliTest[962:1844261] [CDVTimer][intentandnavigationfilter] 6.810963ms
,2016-08-25 17:18:55.344 ThaliTest[962:1844261] [CDVTimer][gesturehandler] 0.397980ms
2016-08-25 17:18:55.344 ThaliTest[962:1844261] [CDVTimer][TotalPluginStartup] 9.604990ms
,2016-08-25 17:19:01.571 ThaliTest[962:1844261] Resetting plugins due to page load.
,2016-08-25 17:19:05.000 ThaliTest[962:1844261] Finished load of: file:///var/mobile/Containers/Bundle/Application/565B3BD9-EB51-42BE-B1BB-F866777B14C3/ThaliTest.app/www/index.html
,2016-08-25 17:19:05.220 ThaliTest[962:1844261] JXcore Cordova plugin initializing
,2016-08-25 17:19:05.220 ThaliTest[962:1844491] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
