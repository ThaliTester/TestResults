#### Test 832688932759c28_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832688932759c28/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/21809C34-2F96-434D-90E7-562B0D332A39/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/21809C34-2F96-434D-90E7-562B0D332A39/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/832688932759c28/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832688932759c28/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/81D07FC8-7168-4A9E-AD41-03F1F4ED96A5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56364"
,(lldb)     command script import "/tmp/21809C34-2F96-434D-90E7-562B0D332A39/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 16:51:47.447 ThaliTest[856:1155920] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AF3B3FF2-750B-43E8-91CC-FD5CF4ACA42D/Library/Cookies/Cookies.binarycookies
,2016-08-30 16:51:47.879 ThaliTest[856:1155920] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 16:51:47.881 ThaliTest[856:1155920] Multi-tasking -> Device: YES, App: YES
,2016-08-30 16:51:47.906 ThaliTest[856:1155920] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 16:51:49.701 ThaliTest[856:1155920] Using UIWebView
,2016-08-30 16:51:49.708 ThaliTest[856:1155920] [CDVTimer][handleopenurl] 0.629008ms
,2016-08-30 16:51:49.716 ThaliTest[856:1155920] [CDVTimer][intentandnavigationfilter] 7.462978ms
2016-08-30 16:51:49.717 ThaliTest[856:1155920] [CDVTimer][gesturehandler] 0.356019ms
2016-08-30 16:51:49.717 ThaliTest[856:1155920] [CDVTimer][TotalPluginStar,tup] 10.394037ms
,2016-08-30 16:51:56.029 ThaliTest[856:1155920] Resetting plugins due to page load.
,2016-08-30 16:51:59.068 ThaliTest[856:1155920] Finished load of: file:///var/mobile/Containers/Bundle/Application/81D07FC8-7168-4A9E-AD41-03F1F4ED96A5/ThaliTest.app/www/index.html
,2016-08-30 16:51:59.300 ThaliTest[856:1155920] JXcore Cordova plugin initializing
,2016-08-30 16:51:59.301 ThaliTest[856:1156157] JXcore instance initializing
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
Total duration:  43.4497150182724
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
