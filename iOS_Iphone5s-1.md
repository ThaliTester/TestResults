#### Test 82728424d2195a9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82728424d2195a9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C8C15EBD-9426-44C4-AAED-E707F383364C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C8C15EBD-9426-44C4-AAED-E707F383364C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82728424d2195a9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82728424d2195a9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A09BC219-448B-4A26-BAE0-EB16B959E2E5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63915"
,(lldb)     command script import "/tmp/C8C15EBD-9426-44C4-AAED-E707F383364C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 20:51:51.485 ThaliTest[871:1847551] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EE012A65-C666-45A8-8A49-5E9129AD765C/Library/Cookies/Cookies.binarycookies
,2016-08-25 20:51:51.919 ThaliTest[871:1847551] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 20:51:51.921 ThaliTest[871:1847551] Multi-tasking -> Device: YES, App: YES
,2016-08-25 20:51:51.947 ThaliTest[871:1847551] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 20:51:53.925 ThaliTest[871:1847551] Using UIWebView
,2016-08-25 20:51:53.933 ThaliTest[871:1847551] [CDVTimer][handleopenurl] 0.591993ms
,2016-08-25 20:51:53.942 ThaliTest[871:1847551] [CDVTimer][intentandnavigationfilter] 7.917047ms
2016-08-25 20:51:53.943 ThaliTest[871:1847551] [CDVTimer][gesturehandler] 0.391006ms
2016-08-25 20:51:53.943 ThaliTest[871:1847551] [CDVTimer][TotalPluginStartup] 10.801971ms
,2016-08-25 20:52:00.242 ThaliTest[871:1847551] Resetting plugins due to page load.
,2016-08-25 20:52:02.596 ThaliTest[871:1847551] Finished load of: file:///var/mobile/Containers/Bundle/Application/A09BC219-448B-4A26-BAE0-EB16B959E2E5/ThaliTest.app/www/index.html
,2016-08-25 20:52:02.852 ThaliTest[871:1847551] JXcore Cordova plugin initializing
,2016-08-25 20:52:02.853 ThaliTest[871:1847787] JXcore instance initializing
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
,*Native tests were not executed*
Total number of executed tests:  undefined
,Number of passed tests:  undefined
,Number of failed tests:  undefined
,Number of ignored tests:  undefined
,Total duration:  undefined
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
