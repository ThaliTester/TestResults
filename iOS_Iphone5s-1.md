#### Test 827284243e10cd0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/827284243e10cd0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/652B1EF6-F119-40D0-8FA4-F65C72771EDC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/652B1EF6-F119-40D0-8FA4-F65C72771EDC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/827284243e10cd0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/827284243e10cd0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A0B7C405-940C-4F75-8DF1-18C0E618AC7C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60120"
,(lldb)     command script import "/tmp/652B1EF6-F119-40D0-8FA4-F65C72771EDC/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 17:18:50.864 ThaliTest[852:1823602] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B57CDCE9-D47F-42E5-8E04-CC09C9088C4C/Library/Cookies/Cookies.binarycookies
,2016-08-25 17:18:51.309 ThaliTest[852:1823602] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 17:18:51.311 ThaliTest[852:1823602] Multi-tasking -> Device: YES, App: YES
,2016-08-25 17:18:51.337 ThaliTest[852:1823602] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 17:18:53.027 ThaliTest[852:1823602] Using UIWebView
,2016-08-25 17:18:53.035 ThaliTest[852:1823602] [CDVTimer][handleopenurl] 0.510991ms
,2016-08-25 17:18:53.044 ThaliTest[852:1823602] [CDVTimer][intentandnavigationfilter] 8.230031ms
2016-08-25 17:18:53.045 ThaliTest[852:1823602] [CDVTimer][gesturehandler] 0.415981ms
2016-08-25 17:18:53.046 ThaliTest[852:1823602] [CDVTimer][TotalPluginStar,tup] 11.144996ms
,2016-08-25 17:18:58.777 ThaliTest[852:1823602] Resetting plugins due to page load.
,2016-08-25 17:19:01.423 ThaliTest[852:1823602] Finished load of: file:///var/mobile/Containers/Bundle/Application/A0B7C405-940C-4F75-8DF1-18C0E618AC7C/ThaliTest.app/www/index.html
,2016-08-25 17:19:01.621 ThaliTest[852:1823602] JXcore Cordova plugin initializing
,2016-08-25 17:19:01.622 ThaliTest[852:1823822] JXcore instance initializing
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
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
