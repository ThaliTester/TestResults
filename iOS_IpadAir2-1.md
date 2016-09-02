#### Test 8326889394b7a14_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889394b7a14/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/99E599D9-84DC-47E5-BC8F-423E6A9804BE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/99E599D9-84DC-47E5-BC8F-423E6A9804BE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889394b7a14/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889394b7a14/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A86B464D-9F52-4DBC-8F0D-E5B8BD092B65/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56383"
,(lldb)     command script import "/tmp/99E599D9-84DC-47E5-BC8F-423E6A9804BE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 12:22:47.809 ThaliTest[1599:2871431] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3AAD1647-9315-472F-8CB4-527E8B2EF9B8/Library/Cookies/Cookies.binarycookies
,2016-09-02 12:22:48.238 ThaliTest[1599:2871431] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 12:22:48.239 ThaliTest[1599:2871431] Multi-tasking -> Device: YES, App: YES
,2016-09-02 12:22:48.259 ThaliTest[1599:2871431] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 12:22:50.303 ThaliTest[1599:2871431] Using UIWebView
,2016-09-02 12:22:50.313 ThaliTest[1599:2871431] [CDVTimer][handleopenurl] 0.406981ms
,2016-09-02 12:22:50.320 ThaliTest[1599:2871431] [CDVTimer][intentandnavigationfilter] 7.052004ms
,2016-09-02 12:22:50.321 ThaliTest[1599:2871431] [CDVTimer][gesturehandler] 0.399053ms
2016-09-02 12:22:50.321 ThaliTest[1599:2871431] [CDVTimer][TotalPluginStartup] 9.576976ms
,2016-09-02 12:22:56.811 ThaliTest[1599:2871431] Resetting plugins due to page load.
,2016-09-02 12:23:00.645 ThaliTest[1599:2871431] Finished load of: file:///var/mobile/Containers/Bundle/Application/A86B464D-9F52-4DBC-8F0D-E5B8BD092B65/ThaliTest.app/www/index.html
,2016-09-02 12:23:00.790 ThaliTest[1599:2871431] JXcore Cordova plugin initializing
,2016-09-02 12:23:00.792 ThaliTest[1599:2871676] JXcore instance initializing
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
Total number of executed tests:  28
,Number of passed tests:  28
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  42.76785904169083
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
