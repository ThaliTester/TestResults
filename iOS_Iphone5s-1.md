#### Test 830701775d60530_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B1BB1D57-92E6-43FC-B288-F03AEE3BBC08/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B1BB1D57-92E6-43FC-B288-F03AEE3BBC08/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3955B2DA-F175-4C02-9954-AEF2804A24F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58221"
,(lldb)     command script import "/tmp/B1BB1D57-92E6-43FC-B288-F03AEE3BBC08/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 14:40:13.823 ThaliTest[2045:4430391] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CFFAD506-45DC-4F16-BD11-531B67E39273/Library/Cookies/Cookies.binarycookies
,2016-09-12 14:40:14.076 ThaliTest[2045:4430391] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 14:40:14.077 ThaliTest[2045:4430391] Multi-tasking -> Device: YES, App: YES
,2016-09-12 14:40:14.094 ThaliTest[2045:4430391] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 14:40:14.877 ThaliTest[2045:4430391] Using UIWebView
,2016-09-12 14:40:14.880 ThaliTest[2045:4430391] [CDVTimer][handleopenurl] 0.169992ms
,2016-09-12 14:40:14.883 ThaliTest[2045:4430391] [CDVTimer][intentandnavigationfilter] 3.057003ms
2016-09-12 14:40:14.883 ThaliTest[2045:4430391] [CDVTimer][gesturehandler] 0.150979ms
2016-09-12 14:40:14.884 ThaliTest[2045:4430391] [CDVTimer][TotalPluginStartup] 4.056036ms
,2016-09-12 14:40:17.816 ThaliTest[2045:4430391] Resetting plugins due to page load.
,2016-09-12 14:40:19.247 ThaliTest[2045:4430391] Finished load of: file:///var/mobile/Containers/Bundle/Application/3955B2DA-F175-4C02-9954-AEF2804A24F4/ThaliTest.app/www/index.html
,2016-09-12 14:40:19.432 ThaliTest[2045:4430391] JXcore Cordova plugin initializing
2016-09-12 14:40:19.433 ThaliTest[2045:4430567] JXcore instance initializing
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
Total number of executed tests:  16
Number of passed tests:  16
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  38.69304400682449
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
