#### Test 82914073f44248e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073f44248e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/169C3DE7-7312-49B1-927B-894FD5374AF5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/169C3DE7-7312-49B1-927B-894FD5374AF5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073f44248e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073f44248e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C6FD8B7D-A0EB-4281-AC20-DC752BA3D172/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57250"
,(lldb)     command script import "/tmp/169C3DE7-7312-49B1-927B-894FD5374AF5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 18:55:17.169 ThaliTest[1696:3615653] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D37C2B2A-1E3D-4A53-829A-C9A6AE11A7DF/Library/Cookies/Cookies.binarycookies
,2016-09-06 18:55:17.421 ThaliTest[1696:3615653] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 18:55:17.422 ThaliTest[1696:3615653] Multi-tasking -> Device: YES, App: YES
,2016-09-06 18:55:17.442 ThaliTest[1696:3615653] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 18:55:18.216 ThaliTest[1696:3615653] Using UIWebView
2016-09-06 18:55:18.219 ThaliTest[1696:3615653] [CDVTimer][handleopenurl] 0.149965ms
,2016-09-06 18:55:18.223 ThaliTest[1696:3615653] [CDVTimer][intentandnavigationfilter] 3.805995ms
2016-09-06 18:55:18.223 ThaliTest[1696:3615653] [CDVTimer][gesturehandler] 0.145018ms
2016-09-06 18:55:18.223 ThaliTest[1696:3615653] [CDVTimer][TotalPluginStartup] 4.747987ms
,2016-09-06 18:55:21.142 ThaliTest[1696:3615653] Resetting plugins due to page load.
,2016-09-06 18:55:22.424 ThaliTest[1696:3615653] Finished load of: file:///var/mobile/Containers/Bundle/Application/C6FD8B7D-A0EB-4281-AC20-DC752BA3D172/ThaliTest.app/www/index.html
,2016-09-06 18:55:22.608 ThaliTest[1696:3615653] JXcore Cordova plugin initializing
2016-09-06 18:55:22.609 ThaliTest[1696:3615828] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
,Total number of executed tests:  38
Number of passed tests:  38
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  12.16819697618484
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
