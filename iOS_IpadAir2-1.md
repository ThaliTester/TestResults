#### Test 83268893e6b65d6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893e6b65d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/AD40F33E-C391-449B-8172-316283BB9489/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AD40F33E-C391-449B-8172-316283BB9489/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893e6b65d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893e6b65d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/25392BCC-1074-4AC4-A09D-B5D0FE9D25AD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57971"
,(lldb)     command script import "/tmp/AD40F33E-C391-449B-8172-316283BB9489/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 15:24:44.784 ThaliTest[1613:2888771] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3F93A5AB-94B4-4F03-8271-698D8923720C/Library/Cookies/Cookies.binarycookies
,2016-09-02 15:24:45.229 ThaliTest[1613:2888771] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 15:24:45.230 ThaliTest[1613:2888771] Multi-tasking -> Device: YES, App: YES
,2016-09-02 15:24:45.259 ThaliTest[1613:2888771] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 15:24:47.286 ThaliTest[1613:2888771] Using UIWebView
,2016-09-02 15:24:47.292 ThaliTest[1613:2888771] [CDVTimer][handleopenurl] 0.402033ms
,2016-09-02 15:24:47.300 ThaliTest[1613:2888771] [CDVTimer][intentandnavigationfilter] 6.672978ms
,2016-09-02 15:24:47.301 ThaliTest[1613:2888771] [CDVTimer][gesturehandler] 0.315011ms
,2016-09-02 15:24:47.301 ThaliTest[1613:2888771] [CDVTimer][TotalPluginStartup] 9.208977ms
,2016-09-02 15:24:53.868 ThaliTest[1613:2888771] Resetting plugins due to page load.
,2016-09-02 15:24:57.244 ThaliTest[1613:2888771] Finished load of: file:///var/mobile/Containers/Bundle/Application/25392BCC-1074-4AC4-A09D-B5D0FE9D25AD/ThaliTest.app/www/index.html
,2016-09-02 15:24:57.457 ThaliTest[1613:2888771] JXcore Cordova plugin initializing
,2016-09-02 15:24:57.458 ThaliTest[1613:2889058] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
,Total number of executed tests:  28
,Number of passed tests:  28
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  43.97066402435303
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
