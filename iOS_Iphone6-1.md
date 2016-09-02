#### Test 83268893e6b65d6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893e6b65d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C7B88F9B-2BA9-4796-BD45-23735500C89B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C7B88F9B-2BA9-4796-BD45-23735500C89B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893e6b65d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893e6b65d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2161B0BA-E1CE-4F0A-A2F5-5771E94BB7A6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57972"
,(lldb)     command script import "/tmp/C7B88F9B-2BA9-4796-BD45-23735500C89B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 15:24:40.903 ThaliTest[1085:1584618] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0AD8263-BA3C-4033-B9E4-3EBFA6539238/Library/Cookies/Cookies.binarycookies
,2016-09-02 15:24:41.344 ThaliTest[1085:1584618] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 15:24:41.346 ThaliTest[1085:1584618] Multi-tasking -> Device: YES, App: YES
,2016-09-02 15:24:41.372 ThaliTest[1085:1584618] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 15:24:43.271 ThaliTest[1085:1584618] Using UIWebView
,2016-09-02 15:24:43.278 ThaliTest[1085:1584618] [CDVTimer][handleopenurl] 0.626028ms
,2016-09-02 15:24:43.286 ThaliTest[1085:1584618] [CDVTimer][intentandnavigationfilter] 8.199990ms
2016-09-02 15:24:43.287 ThaliTest[1085:1584618] [CDVTimer][gesturehandler] 0.329971ms
2016-09-02 15:24:43.287 ThaliTest[1085:1584618] [CDVTimer][TotalPluginStartup] 10.710001ms
,2016-09-02 15:24:49.832 ThaliTest[1085:1584618] Resetting plugins due to page load.
,2016-09-02 15:24:53.350 ThaliTest[1085:1584618] Finished load of: file:///var/mobile/Containers/Bundle/Application/2161B0BA-E1CE-4F0A-A2F5-5771E94BB7A6/ThaliTest.app/www/index.html
,2016-09-02 15:24:53.577 ThaliTest[1085:1584618] JXcore Cordova plugin initializing
,2016-09-02 15:24:53.578 ThaliTest[1085:1584876] JXcore instance initializing
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
Total number of executed tests:  28
Number of passed tests:  28
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  42.96306198835373
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
