#### Test 8291407367fbc55_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8291407367fbc55/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FE60EA9A-46A5-45A9-80F8-D7F5BED2C237/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/FE60EA9A-46A5-45A9-80F8-D7F5BED2C237/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8291407367fbc55/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8291407367fbc55/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/382C0749-2186-451B-9A96-A106F8739AD4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61436"
,(lldb)     command script import "/tmp/FE60EA9A-46A5-45A9-80F8-D7F5BED2C237/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 09:40:58.426 ThaliTest[2176:4252487] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1743A24F-CFC0-4B6B-84FF-FC7265625EF4/Library/Cookies/Cookies.binarycookies
,2016-09-13 09:40:58.963 ThaliTest[2176:4252487] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 09:40:58.965 ThaliTest[2176:4252487] Multi-tasking -> Device: YES, App: YES
,2016-09-13 09:40:58.983 ThaliTest[2176:4252487] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 09:41:01.096 ThaliTest[2176:4252487] Using UIWebView
,2016-09-13 09:41:01.103 ThaliTest[2176:4252487] [CDVTimer][handleopenurl] 0.397980ms
,2016-09-13 09:41:01.111 ThaliTest[2176:4252487] [CDVTimer][intentandnavigationfilter] 6.755948ms
,2016-09-13 09:41:01.112 ThaliTest[2176:4252487] [CDVTimer][gesturehandler] 0.311017ms
,2016-09-13 09:41:01.112 ThaliTest[2176:4252487] [CDVTimer][TotalPluginStartup] 9.262979ms
,2016-09-13 09:41:08.184 ThaliTest[2176:4252487] Resetting plugins due to page load.
,2016-09-13 09:41:12.008 ThaliTest[2176:4252487] Finished load of: file:///var/mobile/Containers/Bundle/Application/382C0749-2186-451B-9A96-A106F8739AD4/ThaliTest.app/www/index.html
,2016-09-13 09:41:12.212 ThaliTest[2176:4252487] JXcore Cordova plugin initializing
,2016-09-13 09:41:12.212 ThaliTest[2176:4252758] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x184c5e40>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  48
,Number of passed tests:  48
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  12.94204097986221
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
