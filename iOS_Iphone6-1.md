#### Test 832688936f8f85f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832688936f8f85f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E608FBAF-9ADE-48BF-9CE0-C467ABF5648B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E608FBAF-9ADE-48BF-9CE0-C467ABF5648B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/832688936f8f85f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832688936f8f85f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/627841E3-286E-4445-8399-2FF70DBB2111/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53314"
,(lldb)     command script import "/tmp/E608FBAF-9ADE-48BF-9CE0-C467ABF5648B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 11:34:08.879 ThaliTest[1060:1558956] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/33DF8E5F-915F-492F-AE94-225F5D47FCA2/Library/Cookies/Cookies.binarycookies
,2016-09-02 11:34:09.350 ThaliTest[1060:1558956] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 11:34:09.351 ThaliTest[1060:1558956] Multi-tasking -> Device: YES, App: YES
,2016-09-02 11:34:09.374 ThaliTest[1060:1558956] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 11:34:11.263 ThaliTest[1060:1558956] Using UIWebView
,2016-09-02 11:34:11.270 ThaliTest[1060:1558956] [CDVTimer][handleopenurl] 0.687003ms
,2016-09-02 11:34:11.278 ThaliTest[1060:1558956] [CDVTimer][intentandnavigationfilter] 7.228017ms
2016-09-02 11:34:11.279 ThaliTest[1060:1558956] [CDVTimer][gesturehandler] 0.353992ms
2016-09-02 11:34:11.279 ThaliTest[1060:1558956] [CDVTimer][TotalPluginStartup] 9.959996ms
,2016-09-02 11:34:18.119 ThaliTest[1060:1558956] Resetting plugins due to page load.
,2016-09-02 11:34:21.248 ThaliTest[1060:1558956] Finished load of: file:///var/mobile/Containers/Bundle/Application/627841E3-286E-4445-8399-2FF70DBB2111/ThaliTest.app/www/index.html
,2016-09-02 11:34:21.485 ThaliTest[1060:1558956] JXcore Cordova plugin initializing
,2016-09-02 11:34:21.486 ThaliTest[1060:1559211] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  25
,Number of passed tests:  25
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  42.19716596603394
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
