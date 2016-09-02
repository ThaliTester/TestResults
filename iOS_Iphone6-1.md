#### Test 8326889394b7a14_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889394b7a14/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D2D89E62-CE93-4D63-9F4F-5F8801A22517/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D2D89E62-CE93-4D63-9F4F-5F8801A22517/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889394b7a14/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889394b7a14/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2EA24116-CA71-4E5C-9223-084820880A58/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56384"
,(lldb)     command script import "/tmp/D2D89E62-CE93-4D63-9F4F-5F8801A22517/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-02 12:22:43.487 ThaliTest[1074:1565347] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/79F33C1D-2DDA-4FF3-AC12-392815E1A005/Library/Cookies/Cookies.binarycookies
,2016-09-02 12:22:43.887 ThaliTest[1074:1565347] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 12:22:43.888 ThaliTest[1074:1565347] Multi-tasking -> Device: YES, App: YES
,2016-09-02 12:22:43.911 ThaliTest[1074:1565347] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 12:22:45.823 ThaliTest[1074:1565347] Using UIWebView
,2016-09-02 12:22:45.832 ThaliTest[1074:1565347] [CDVTimer][handleopenurl] 0.633001ms
,2016-09-02 12:22:45.841 ThaliTest[1074:1565347] [CDVTimer][intentandnavigationfilter] 8.224010ms
2016-09-02 12:22:45.842 ThaliTest[1074:1565347] [CDVTimer][gesturehandler] 0.324011ms
2016-09-02 12:22:45.842 ThaliTest[1074:1565347] [CDVTimer][TotalPluginS,tartup] 10.846019ms
,2016-09-02 12:22:52.383 ThaliTest[1074:1565347] Resetting plugins due to page load.
,2016-09-02 12:22:55.510 ThaliTest[1074:1565347] Finished load of: file:///var/mobile/Containers/Bundle/Application/2EA24116-CA71-4E5C-9223-084820880A58/ThaliTest.app/www/index.html
,2016-09-02 12:22:55.745 ThaliTest[1074:1565347] JXcore Cordova plugin initializing
,2016-09-02 12:22:55.746 ThaliTest[1074:1565599] JXcore instance initializing
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
,Total number of executed tests:  28
Number of passed tests:  28
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  43.0407800078392
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
