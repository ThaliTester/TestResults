#### Test 83268893e6b65d6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893e6b65d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CE45481F-272A-4932-A82F-089F8C5B7951/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CE45481F-272A-4932-A82F-089F8C5B7951/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893e6b65d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893e6b65d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AD6484E6-7052-4D51-AD27-0CA5AFD4E2A9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57975"
,(lldb)     command script import "/tmp/CE45481F-272A-4932-A82F-089F8C5B7951/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 15:24:42.169 ThaliTest[1514:3011094] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DE2E25A1-2382-4825-AB5A-88277486585E/Library/Cookies/Cookies.binarycookies
,2016-09-02 15:24:42.575 ThaliTest[1514:3011094] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 15:24:42.577 ThaliTest[1514:3011094] Multi-tasking -> Device: YES, App: YES
,2016-09-02 15:24:42.603 ThaliTest[1514:3011094] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 15:24:44.601 ThaliTest[1514:3011094] Using UIWebView
,2016-09-02 15:24:44.613 ThaliTest[1514:3011094] [CDVTimer][handleopenurl] 0.567973ms
,2016-09-02 15:24:44.623 ThaliTest[1514:3011094] [CDVTimer][intentandnavigationfilter] 9.733021ms
2016-09-02 15:24:44.624 ThaliTest[1514:3011094] [CDVTimer][gesturehandler] 0.388980ms
2016-09-02 15:24:44.624 ThaliTest[1514:3011094] [CDVTimer][TotalPluginS,tartup] 12.750983ms
,2016-09-02 15:24:50.718 ThaliTest[1514:3011094] Resetting plugins due to page load.
,2016-09-02 15:24:54.146 ThaliTest[1514:3011094] Finished load of: file:///var/mobile/Containers/Bundle/Application/AD6484E6-7052-4D51-AD27-0CA5AFD4E2A9/ThaliTest.app/www/index.html
,2016-09-02 15:24:54.383 ThaliTest[1514:3011094] JXcore Cordova plugin initializing
,2016-09-02 15:24:54.384 ThaliTest[1514:3011332] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
Total duration:  43.33918398618698
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
