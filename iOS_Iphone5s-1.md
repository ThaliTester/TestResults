#### Test 79896569fbe8035_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79896569fbe8035/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B24EF8CA-FD8E-4DB9-B359-4E7D723AB2EF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B24EF8CA-FD8E-4DB9-B359-4E7D723AB2EF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79896569fbe8035/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79896569fbe8035/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C7249376-779B-4FBF-8062-0CA75D8F918C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59871"
,(lldb)     command script import "/tmp/B24EF8CA-FD8E-4DB9-B359-4E7D723AB2EF/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-26 21:51:55.344 ThaliTest[1016:2011108] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/73682A89-0611-4E84-87B8-495C1A2983F0/Library/Cookies/Cookies.binarycookies
,2016-08-26 21:51:55.800 ThaliTest[1016:2011108] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 21:51:55.802 ThaliTest[1016:2011108] Multi-tasking -> Device: YES, App: YES
,2016-08-26 21:51:55.828 ThaliTest[1016:2011108] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 21:51:57.885 ThaliTest[1016:2011108] Using UIWebView
,2016-08-26 21:51:57.893 ThaliTest[1016:2011108] [CDVTimer][handleopenurl] 0.924051ms
,2016-08-26 21:51:57.902 ThaliTest[1016:2011108] [CDVTimer][intentandnavigationfilter] 8.129001ms
2016-08-26 21:51:57.903 ThaliTest[1016:2011108] [CDVTimer][gesturehandler] 0.461996ms
2016-08-26 21:51:57.904 ThaliTest[1016:2011108] [CDVTimer][TotalPluginStartup] 11.435032ms
,2016-08-26 21:52:04.219 ThaliTest[1016:2011108] Resetting plugins due to page load.
,2016-08-26 21:52:07.946 ThaliTest[1016:2011108] Finished load of: file:///var/mobile/Containers/Bundle/Application/C7249376-779B-4FBF-8062-0CA75D8F918C/ThaliTest.app/www/index.html
,2016-08-26 21:52:08.206 ThaliTest[1016:2011108] JXcore Cordova plugin initializing
,2016-08-26 21:52:08.207 ThaliTest[1016:2011327] JXcore instance initializing
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
Total number of executed tests:  5
Number of passed tests:  5
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.008095026016235352
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
