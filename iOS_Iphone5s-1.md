#### Test 861743790af7a74_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/61B9D59F-08F6-4AE9-ACB9-C6F30FC76086/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/61B9D59F-08F6-4AE9-ACB9-C6F30FC76086/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/663E72B0-D282-400B-94D8-E2A63F5A57D1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63470"
,(lldb)     command script import "/tmp/61B9D59F-08F6-4AE9-ACB9-C6F30FC76086/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 12:39:46.292 ThaliTest[2919:5970098] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5359C974-85C2-4C11-8E34-AAF60F038CF9/Library/Cookies/Cookies.binarycookies
,2016-09-22 12:39:46.407 ThaliTest[2919:5970098] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 12:39:46.409 ThaliTest[2919:5970098] Multi-tasking -> Device: YES, App: YES
,2016-09-22 12:39:46.432 ThaliTest[2919:5970098] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 12:39:48.009 ThaliTest[2919:5970098] Using UIWebView
,2016-09-22 12:39:48.017 ThaliTest[2919:5970098] [CDVTimer][handleopenurl] 0.465989ms
,2016-09-22 12:39:48.026 ThaliTest[2919:5970098] [CDVTimer][intentandnavigationfilter] 8.170009ms
2016-09-22 12:39:48.027 ThaliTest[2919:5970098] [CDVTimer][gesturehandler] 0.383973ms
2016-09-22 12:39:48.028 ThaliTest[2919:5970098] [CDVTimer][TotalPluginS,tartup] 11.143029ms
,2016-09-22 12:39:54.002 ThaliTest[2919:5970098] Resetting plugins due to page load.
,2016-09-22 12:39:57.552 ThaliTest[2919:5970098] Finished load of: file:///var/mobile/Containers/Bundle/Application/663E72B0-D282-400B-94D8-E2A63F5A57D1/ThaliTest.app/www/index.html
,2016-09-22 12:39:57.859 ThaliTest[2919:5970098] JXcore Cordova plugin initializing
,2016-09-22 12:39:57.861 ThaliTest[2919:5970296] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x1291b47e0>
,Optional("0A766327-7CBA-4491-8798-6B89DC9D95FE")
,nil
,nil
,Optional("BA59C657-5A79-4D30-BDE7-C8B74F1D9FA7")
,Optional("28EE3C3C-AAC4-4175-89FE-A46F3CB4810F")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 12:40:22.670 ThaliTest[2919:5970098] BTM: attaching to BTServer
,2016-09-22 12:40:23.476 ThaliTest[2919:5970098] BTM: local device power state changed
,2016-09-22 12:40:23.476 ThaliTest[2919:5970098] BTM: power is now on
,2016-09-22 12:40:28.177 ThaliTest[2919:5970098] BTM: local device power state changed
2016-09-22 12:40:28.178 ThaliTest[2919:5970098] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  21.42954301834106
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
