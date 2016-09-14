#### Test 82914073a6a0640_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073a6a0640/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8F22FD6A-803D-4E63-802E-97B8A7BB1BE4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8F22FD6A-803D-4E63-802E-97B8A7BB1BE4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073a6a0640/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073a6a0640/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5B0F4E90-F66B-46D7-99D2-6BB62D5B1D86/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64952"
,(lldb)     command script import "/tmp/8F22FD6A-803D-4E63-802E-97B8A7BB1BE4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 20:07:01.962 ThaliTest[2339:4440840] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/293FD111-A6E9-4EE5-9325-00AE0FAA1B33/Library/Cookies/Cookies.binarycookies
,2016-09-14 20:07:02.340 ThaliTest[2339:4440840] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 20:07:02.342 ThaliTest[2339:4440840] Multi-tasking -> Device: YES, App: YES
,2016-09-14 20:07:02.364 ThaliTest[2339:4440840] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 20:07:04.329 ThaliTest[2339:4440840] Using UIWebView
,2016-09-14 20:07:04.339 ThaliTest[2339:4440840] [CDVTimer][handleopenurl] 0.348985ms
,2016-09-14 20:07:04.346 ThaliTest[2339:4440840] [CDVTimer][intentandnavigationfilter] 6.991982ms
,2016-09-14 20:07:04.347 ThaliTest[2339:4440840] [CDVTimer][gesturehandler] 0.335991ms
,2016-09-14 20:07:04.348 ThaliTest[2339:4440840] [CDVTimer][TotalPluginStartup] 9.266973ms
,2016-09-14 20:07:10.872 ThaliTest[2339:4440840] Resetting plugins due to page load.
,2016-09-14 20:07:13.705 ThaliTest[2339:4440840] Finished load of: file:///var/mobile/Containers/Bundle/Application/5B0F4E90-F66B-46D7-99D2-6BB62D5B1D86/ThaliTest.app/www/index.html
,2016-09-14 20:07:13.916 ThaliTest[2339:4440840] JXcore Cordova plugin initializing
,2016-09-14 20:07:13.917 ThaliTest[2339:4441098] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x124e05410>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 20:07:32.777 ThaliTest[2339:4440840] BTM: attaching to BTServer
,2016-09-14 20:07:33.842 ThaliTest[2339:4440840] BTM: local device power state changed
2016-09-14 20:07:33.842 ThaliTest[2339:4440840] BTM: power is now off
,2016-09-14 20:07:34.634 ThaliTest[2339:4440840] BTM: local device power state changed
2016-09-14 20:07:34.634 ThaliTest[2339:4440840] BTM: power is now on
,*Native tests were executed*
,Total number of executed tests:  48
,Number of passed tests:  48
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.20415997505188
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
