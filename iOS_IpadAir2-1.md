#### Test 83268893665f77c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893665f77c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C749D59C-6EF4-4817-A8B7-5CFBC3970F21/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C749D59C-6EF4-4817-A8B7-5CFBC3970F21/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893665f77c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893665f77c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/22B17343-CB37-4559-9C4E-BB88B79AD62C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50254"
,(lldb)     command script import "/tmp/C749D59C-6EF4-4817-A8B7-5CFBC3970F21/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-09-06 16:54:39.665 ThaliTest[1766:3382404] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/110FCCD0-04CA-46C2-BAEC-0DC9FB8FB645/Library/Cookies/Cookies.binarycookies
,2016-09-06 16:54:40.082 ThaliTest[1766:3382404] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 16:54:40.083 ThaliTest[1766:3382404] Multi-tasking -> Device: YES, App: YES
,2016-09-06 16:54:40.103 ThaliTest[1766:3382404] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 16:54:41.956 ThaliTest[1766:3382404] Using UIWebView
,2016-09-06 16:54:41.963 ThaliTest[1766:3382404] [CDVTimer][handleopenurl] 0.441968ms
,2016-09-06 16:54:41.970 ThaliTest[1766:3382404] [CDVTimer][intentandnavigationfilter] 6.877005ms
,2016-09-06 16:54:41.971 ThaliTest[1766:3382404] [CDVTimer][gesturehandler] 0.331998ms
,2016-09-06 16:54:41.972 ThaliTest[1766:3382404] [CDVTimer][TotalPluginStartup] 9.328008ms
,2016-09-06 16:54:48.243 ThaliTest[1766:3382404] Resetting plugins due to page load.
,2016-09-06 16:54:51.739 ThaliTest[1766:3382404] Finished load of: file:///var/mobile/Containers/Bundle/Application/22B17343-CB37-4559-9C4E-BB88B79AD62C/ThaliTest.app/www/index.html
,2016-09-06 16:54:51.961 ThaliTest[1766:3382404] JXcore Cordova plugin initializing
,2016-09-06 16:54:51.962 ThaliTest[1766:3382668] JXcore instance initializing
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
,*Native tests were executed*
,Total number of executed tests:  44
Number of passed tests:  44
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  12.67571204900742
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
