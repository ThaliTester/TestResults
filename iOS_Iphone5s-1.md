#### Test 85046911d6c2afe_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FD4DADAA-906E-4CC1-96C9-C32FF83DD445/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FD4DADAA-906E-4CC1-96C9-C32FF83DD445/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/56E11F51-D683-4E4F-88B4-8ED38FD0A75C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49267"
,(lldb)     command script import "/tmp/FD4DADAA-906E-4CC1-96C9-C32FF83DD445/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 11:01:38.926 ThaliTest[2732:5789292] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B265244C-CAF6-4571-8BEA-E162481A82DB/Library/Cookies/Cookies.binarycookies
,2016-09-21 11:01:39.202 ThaliTest[2732:5789292] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 11:01:39.203 ThaliTest[2732:5789292] Multi-tasking -> Device: YES, App: YES
,2016-09-21 11:01:39.223 ThaliTest[2732:5789292] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 11:01:40.040 ThaliTest[2732:5789292] Using UIWebView
2016-09-21 11:01:40.043 ThaliTest[2732:5789292] [CDVTimer][handleopenurl] 0.153005ms
,2016-09-21 11:01:40.046 ThaliTest[2732:5789292] [CDVTimer][intentandnavigationfilter] 2.874017ms
2016-09-21 11:01:40.047 ThaliTest[2732:5789292] [CDVTimer][gesturehandler] 0.136971ms
2016-09-21 11:01:40.047 ThaliTest[2732:5789292] [CDVTimer][TotalPluginS,tartup] 3.784001ms
,2016-09-21 11:01:43.088 ThaliTest[2732:5789292] Resetting plugins due to page load.
,2016-09-21 11:01:44.509 ThaliTest[2732:5789292] Finished load of: file:///var/mobile/Containers/Bundle/Application/56E11F51-D683-4E4F-88B4-8ED38FD0A75C/ThaliTest.app/www/index.html
,2016-09-21 11:01:44.697 ThaliTest[2732:5789292] JXcore Cordova plugin initializing
,2016-09-21 11:01:44.698 ThaliTest[2732:5789477] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 11:01:52.518 ThaliTest[2732:5789477] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-21 11:01:52.519 ThaliTest[2732:5789477] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-21 11:01:52.520 ThaliTest[2732:5789477] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 11:01:52.523 ThaliTest[2732:5789477] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 11:01:52.897 ThaliTest[2732:5789477] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004770040512084961
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
