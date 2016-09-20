#### Test 85046911bd0d025_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911bd0d025/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7A2C8DE2-1E0F-4911-AD55-15E371FF0927/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7A2C8DE2-1E0F-4911-AD55-15E371FF0927/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911bd0d025/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911bd0d025/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2FC18F67-DDF2-46F1-9936-9C266D1CE728/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54978"
,(lldb)     command script import "/tmp/7A2C8DE2-1E0F-4911-AD55-15E371FF0927/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 13:37:50.181 ThaliTest[2671:5658806] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C05E397E-35F7-4332-94EA-252ADEC45DB8/Library/Cookies/Cookies.binarycookies
,2016-09-20 13:37:50.620 ThaliTest[2671:5658806] Apache Cordova native platform version 4.2.1 is starting.
2016-09-20 13:37:50.622 ThaliTest[2671:5658806] Multi-tasking -> Device: YES, App: YES
,2016-09-20 13:37:50.643 ThaliTest[2671:5658806] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 13:37:52.318 ThaliTest[2671:5658806] Using UIWebView
,2016-09-20 13:37:52.326 ThaliTest[2671:5658806] [CDVTimer][handleopenurl] 0.599980ms
,2016-09-20 13:37:52.335 ThaliTest[2671:5658806] [CDVTimer][intentandnavigationfilter] 8.024037ms
2016-09-20 13:37:52.336 ThaliTest[2671:5658806] [CDVTimer][gesturehandler] 0.369012ms
2016-09-20 13:37:52.336 ThaliTest[2671:5658806] [CDVTimer][TotalPluginS,tartup] 10.818958ms
,2016-09-20 13:37:58.689 ThaliTest[2671:5658806] Resetting plugins due to page load.
,2016-09-20 13:38:01.637 ThaliTest[2671:5658806] Finished load of: file:///var/mobile/Containers/Bundle/Application/2FC18F67-DDF2-46F1-9936-9C266D1CE728/ThaliTest.app/www/index.html
,2016-09-20 13:38:01.825 ThaliTest[2671:5658806] JXcore Cordova plugin initializing
,2016-09-20 13:38:01.826 ThaliTest[2671:5659033] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 13:38:09.910 ThaliTest[2671:5659033] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 13:38:09.911 ThaliTest[2671:5659033] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-20 13:38:09.911 ThaliTest[2671:5659033] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-20 13:38:09.913 ThaliTest[2671:5659033] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 13:38:10.298 ThaliTest[2671:5659033] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005375027656555176
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
