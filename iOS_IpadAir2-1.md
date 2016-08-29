#### Test 829140738625595_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140738625595/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/2701C9C6-2C90-439F-AB6A-FF7A15A17992/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2701C9C6-2C90-439F-AB6A-FF7A15A17992/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140738625595/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140738625595/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/59B93D9A-894C-422C-A3B5-40A1662E12F6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55087"
,(lldb)     command script import "/tmp/2701C9C6-2C90-439F-AB6A-FF7A15A17992/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 11:05:03.703 ThaliTest[1234:2349657] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/30B19781-1810-441B-87EF-D0EE8A64C060/Library/Cookies/Cookies.binarycookies
,2016-08-29 11:05:04.083 ThaliTest[1234:2349657] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 11:05:04.085 ThaliTest[1234:2349657] Multi-tasking -> Device: YES, App: YES
,2016-08-29 11:05:04.105 ThaliTest[1234:2349657] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 11:05:06.107 ThaliTest[1234:2349657] Using UIWebView
,2016-08-29 11:05:06.113 ThaliTest[1234:2349657] [CDVTimer][handleopenurl] 0.373006ms
,2016-08-29 11:05:06.121 ThaliTest[1234:2349657] [CDVTimer][intentandnavigationfilter] 7.152021ms
,2016-08-29 11:05:06.122 ThaliTest[1234:2349657] [CDVTimer][gesturehandler] 0.367999ms
2016-08-29 11:05:06.123 ThaliTest[1234:2349657] [CDVTimer][TotalPluginStartup] 9.926975ms
,2016-08-29 11:05:12.824 ThaliTest[1234:2349657] Resetting plugins due to page load.
,2016-08-29 11:05:16.676 ThaliTest[1234:2349657] Finished load of: file:///var/mobile/Containers/Bundle/Application/59B93D9A-894C-422C-A3B5-40A1662E12F6/ThaliTest.app/www/index.html
,2016-08-29 11:05:16.892 ThaliTest[1234:2349657] JXcore Cordova plugin initializing
,2016-08-29 11:05:16.893 ThaliTest[1234:2349918] JXcore instance initializing
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
Total number of executed tests:  20
,Number of passed tests:  20
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  43.26560395956039
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
