#### Test 82914073713e010_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073713e010/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8244D70F-AF36-4F7D-8A18-DD4DE5AA0D8B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8244D70F-AF36-4F7D-8A18-DD4DE5AA0D8B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073713e010/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073713e010/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/83E4B53C-0F18-4074-8566-BE0AF7B12C08/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60864"
,(lldb)     command script import "/tmp/8244D70F-AF36-4F7D-8A18-DD4DE5AA0D8B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 18:56:42.518 ThaliTest[2483:4573588] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AF172A79-DDA2-420F-9F5A-9DF7E13E6529/Library/Cookies/Cookies.binarycookies
,2016-09-15 18:56:42.850 ThaliTest[2483:4573588] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 18:56:42.851 ThaliTest[2483:4573588] Multi-tasking -> Device: YES, App: YES
,2016-09-15 18:56:42.867 ThaliTest[2483:4573588] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 18:56:44.720 ThaliTest[2483:4573588] Using UIWebView
,2016-09-15 18:56:44.727 ThaliTest[2483:4573588] [CDVTimer][handleopenurl] 0.494957ms
,2016-09-15 18:56:44.734 ThaliTest[2483:4573588] [CDVTimer][intentandnavigationfilter] 6.358981ms
,2016-09-15 18:56:44.734 ThaliTest[2483:4573588] [CDVTimer][gesturehandler] 0.276983ms
,2016-09-15 18:56:44.735 ThaliTest[2483:4573588] [CDVTimer][TotalPluginStartup] 8.713961ms
,2016-09-15 18:56:51.318 ThaliTest[2483:4573588] Resetting plugins due to page load.
,2016-09-15 18:56:54.387 ThaliTest[2483:4573588] Finished load of: file:///var/mobile/Containers/Bundle/Application/83E4B53C-0F18-4074-8566-BE0AF7B12C08/ThaliTest.app/www/index.html
,2016-09-15 18:56:54.663 ThaliTest[2483:4573588] JXcore Cordova plugin initializing
,2016-09-15 18:56:54.664 ThaliTest[2483:4573830] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x15d6581a0>
,4A096C03-5FA9-4AD2-844F-DCDD501A5651
Optional("4A096C03-5FA9-4AD2-844F-DCDD501A5651")
,nil
,nil

,FE1AF87B-E1DE-45E9-A51D-60506F833B5D
Optional("FE1AF87B-E1DE-45E9-A51D-60506F833B5D")
,8977968D-E390-4E53-B550-8002CE47CF51
Optional("8977968D-E390-4E53-B550-8002CE47CF51")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-15 18:57:13.746 ThaliTest[2483:4573588] BTM: attaching to BTServer
,2016-09-15 18:57:14.638 ThaliTest[2483:4573588] BTM: local device power state changed
2016-09-15 18:57:14.639 ThaliTest[2483:4573588] BTM: power is now on
,2016-09-15 18:57:19.387 ThaliTest[2483:4573588] BTM: local device power state changed
2016-09-15 18:57:19.388 ThaliTest[2483:4573588] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  46
,Number of passed tests:  46
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  18.18568903207779
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
