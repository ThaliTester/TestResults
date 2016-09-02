#### Test 83444050ceb1988_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83444050ceb1988/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/15BDA54D-428D-4117-8965-114DAA761F21/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/15BDA54D-428D-4117-8965-114DAA761F21/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83444050ceb1988/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83444050ceb1988/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/29BC785A-3D7D-47E8-88D4-40D6AF9FD183/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59520"
,(lldb)     command script import "/tmp/15BDA54D-428D-4117-8965-114DAA761F21/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 19:05:25.973 ThaliTest[1528:3033699] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E17CCE70-BA27-49DB-B73D-55ECD7FEBD9E/Library/Cookies/Cookies.binarycookies
,2016-09-02 19:05:26.419 ThaliTest[1528:3033699] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 19:05:26.420 ThaliTest[1528:3033699] Multi-tasking -> Device: YES, App: YES
,2016-09-02 19:05:26.444 ThaliTest[1528:3033699] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 19:05:28.197 ThaliTest[1528:3033699] Using UIWebView
,2016-09-02 19:05:28.205 ThaliTest[1528:3033699] [CDVTimer][handleopenurl] 0.486970ms
,2016-09-02 19:05:28.214 ThaliTest[1528:3033699] [CDVTimer][intentandnavigationfilter] 8.067966ms
2016-09-02 19:05:28.215 ThaliTest[1528:3033699] [CDVTimer][gesturehandler] 0.392973ms
2016-09-02 19:05:28.215 ThaliTest[1528:3033699] [CDVTimer][TotalPluginS,tartup] 10.898948ms
,2016-09-02 19:05:34.889 ThaliTest[1528:3033699] Resetting plugins due to page load.
,2016-09-02 19:05:37.966 ThaliTest[1528:3033699] Finished load of: file:///var/mobile/Containers/Bundle/Application/29BC785A-3D7D-47E8-88D4-40D6AF9FD183/ThaliTest.app/www/index.html
,2016-09-02 19:05:38.194 ThaliTest[1528:3033699] JXcore Cordova plugin initializing
,2016-09-02 19:05:38.195 ThaliTest[1528:3033930] JXcore instance initializing
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
Total number of executed tests:  15
Number of passed tests:  15
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  38.48628604412079
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackgroun
```
