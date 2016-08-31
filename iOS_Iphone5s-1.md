#### Test 82914073b1ed9e5_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073b1ed9e5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/90F17217-BDFF-4087-A521-3367B84C7DCE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/90F17217-BDFF-4087-A521-3367B84C7DCE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073b1ed9e5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073b1ed9e5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A273765F-380E-43F4-831D-7528E8A0002D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56203"
,(lldb)     command script import "/tmp/90F17217-BDFF-4087-A521-3367B84C7DCE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-31 18:46:31.306 ThaliTest[1383:2731666] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/10729FDE-3D12-4602-A12D-8450230378C2/Library/Cookies/Cookies.binarycookies
,2016-08-31 18:46:31.678 ThaliTest[1383:2731666] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 18:46:31.680 ThaliTest[1383:2731666] Multi-tasking -> Device: YES, App: YES
,2016-08-31 18:46:31.702 ThaliTest[1383:2731666] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 18:46:33.370 ThaliTest[1383:2731666] Using UIWebView
,2016-08-31 18:46:33.379 ThaliTest[1383:2731666] [CDVTimer][handleopenurl] 0.684023ms
,2016-08-31 18:46:33.387 ThaliTest[1383:2731666] [CDVTimer][intentandnavigationfilter] 8.208990ms
2016-08-31 18:46:33.388 ThaliTest[1383:2731666] [CDVTimer][gesturehandler] 0.413001ms
2016-08-31 18:46:33.389 ThaliTest[1383:2731666] [CDVTimer][TotalPluginStartup] 11.219025ms
,2016-08-31 18:46:39.569 ThaliTest[1383:2731666] Resetting plugins due to page load.
,2016-08-31 18:46:42.333 ThaliTest[1383:2731666] Finished load of: file:///var/mobile/Containers/Bundle/Application/A273765F-380E-43F4-831D-7528E8A0002D/ThaliTest.app/www/index.html
,2016-08-31 18:46:42.575 ThaliTest[1383:2731666] JXcore Cordova plugin initializing
2016-08-31 18:46:42.576 ThaliTest[1383:2731875] JXcore instance initializing
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
Total number of executed tests:  22
Number of passed tests:  22
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  44.21102404594421
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
