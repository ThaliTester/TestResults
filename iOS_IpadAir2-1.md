#### Test 8291407379492e1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8291407379492e1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D781B724-EF2C-48F1-97D2-8254B3E45199/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D781B724-EF2C-48F1-97D2-8254B3E45199/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8291407379492e1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8291407379492e1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C0E696E0-E44E-4BC4-8792-D34DA07FD1F9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52875"
,(lldb)     command script import "/tmp/D781B724-EF2C-48F1-97D2-8254B3E45199/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-29 10:22:27.309 ThaliTest[1221:2344598] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BE87110F-C2C1-4E29-9680-83B456DEA871/Library/Cookies/Cookies.binarycookies
,2016-08-29 10:22:27.746 ThaliTest[1221:2344598] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 10:22:27.747 ThaliTest[1221:2344598] Multi-tasking -> Device: YES, App: YES
,2016-08-29 10:22:27.765 ThaliTest[1221:2344598] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 10:22:29.827 ThaliTest[1221:2344598] Using UIWebView
,2016-08-29 10:22:29.837 ThaliTest[1221:2344598] [CDVTimer][handleopenurl] 0.400007ms
,2016-08-29 10:22:29.844 ThaliTest[1221:2344598] [CDVTimer][intentandnavigationfilter] 6.614983ms
,2016-08-29 10:22:29.845 ThaliTest[1221:2344598] [CDVTimer][gesturehandler] 0.304997ms
,2016-08-29 10:22:29.845 ThaliTest[1221:2344598] [CDVTimer][TotalPluginStartup] 8.931994ms
,2016-08-29 10:22:37.071 ThaliTest[1221:2344598] Resetting plugins due to page load.
,2016-08-29 10:22:40.817 ThaliTest[1221:2344598] Finished load of: file:///var/mobile/Containers/Bundle/Application/C0E696E0-E44E-4BC4-8792-D34DA07FD1F9/ThaliTest.app/www/index.html
,2016-08-29 10:22:41.030 ThaliTest[1221:2344598] JXcore Cordova plugin initializing
,2016-08-29 10:22:41.032 ThaliTest[1221:2344883] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  20
Number of passed tests:  20
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  43.82903897762299
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
