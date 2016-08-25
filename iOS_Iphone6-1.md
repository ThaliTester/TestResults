#### Test 82728424cc1b7f1_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82728424cc1b7f1/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6377EEF0-3F8F-4632-9E74-619E6273B0AE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6377EEF0-3F8F-4632-9E74-619E6273B0AE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/82728424cc1b7f1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82728424cc1b7f1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3B9DAC1E-7FBE-48A9-A599-08CBB1772108/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65449"
,(lldb)     command script import "/tmp/6377EEF0-3F8F-4632-9E74-619E6273B0AE/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 21:48:07.548 ThaliTest[462:479295] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FCEAB623-655C-41FB-9513-9D04B86BDB65/Library/Cookies/Cookies.binarycookies
,2016-08-25 21:48:08.092 ThaliTest[462:479295] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 21:48:08.093 ThaliTest[462:479295] Multi-tasking -> Device: YES, App: YES
,2016-08-25 21:48:08.112 ThaliTest[462:479295] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 21:48:10.019 ThaliTest[462:479295] Using UIWebView
,2016-08-25 21:48:10.026 ThaliTest[462:479295] [CDVTimer][handleopenurl] 0.390947ms
,2016-08-25 21:48:10.035 ThaliTest[462:479295] [CDVTimer][intentandnavigationfilter] 7.606030ms
2016-08-25 21:48:10.035 ThaliTest[462:479295] [CDVTimer][gesturehandler] 0.330031ms
2016-08-25 21:48:10.036 ThaliTest[462:479295] [CDVTimer][TotalPluginStartup] 9.927988ms
,2016-08-25 21:48:16.559 ThaliTest[462:479295] Resetting plugins due to page load.
,2016-08-25 21:48:19.832 ThaliTest[462:479295] Finished load of: file:///var/mobile/Containers/Bundle/Application/3B9DAC1E-7FBE-48A9-A599-08CBB1772108/ThaliTest.app/www/index.html
,2016-08-25 21:48:20.061 ThaliTest[462:479295] JXcore Cordova plugin initializing
,2016-08-25 21:48:20.062 ThaliTest[462:479554] JXcore instance initializing
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
,Total number of executed tests:  5
Number of passed tests:  5
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.006667017936706543
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
