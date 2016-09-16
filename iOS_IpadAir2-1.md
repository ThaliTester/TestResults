#### Test 8326889394d960a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/1A74BC42-9CB0-4B66-8776-6E7F869BC352/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1A74BC42-9CB0-4B66-8776-6E7F869BC352/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2AE76FB5-9951-4F59-8EC1-9A1A74D0D33D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53761"
,(lldb)     command script import "/tmp/1A74BC42-9CB0-4B66-8776-6E7F869BC352/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 15:06:38.453 ThaliTest[2567:4684476] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/02A94FBC-F7B9-45C6-B523-1FB30EFA6525/Library/Cookies/Cookies.binarycookies
,2016-09-16 15:06:38.781 ThaliTest[2567:4684476] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 15:06:38.782 ThaliTest[2567:4684476] Multi-tasking -> Device: YES, App: YES
,2016-09-16 15:06:38.798 ThaliTest[2567:4684476] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 15:06:40.767 ThaliTest[2567:4684476] Using UIWebView
,2016-09-16 15:06:40.773 ThaliTest[2567:4684476] [CDVTimer][handleopenurl] 0.347018ms
,2016-09-16 15:06:40.780 ThaliTest[2567:4684476] [CDVTimer][intentandnavigationfilter] 6.287992ms
,2016-09-16 15:06:40.781 ThaliTest[2567:4684476] [CDVTimer][gesturehandler] 0.286996ms
,2016-09-16 15:06:40.781 ThaliTest[2567:4684476] [CDVTimer][TotalPluginStartup] 8.475006ms
,2016-09-16 15:06:47.856 ThaliTest[2567:4684476] Resetting plugins due to page load.
,2016-09-16 15:06:51.245 ThaliTest[2567:4684476] Finished load of: file:///var/mobile/Containers/Bundle/Application/2AE76FB5-9951-4F59-8EC1-9A1A74D0D33D/ThaliTest.app/www/index.html
,2016-09-16 15:06:51.457 ThaliTest[2567:4684476] JXcore Cordova plugin initializing
,2016-09-16 15:06:51.458 ThaliTest[2567:4684689] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-16 15:06:58.164 ThaliTest[2567:4684476] BTM: attaching to BTServer
,2016-09-16 15:07:09.056 ThaliTest[2567:4684476] BTM: local device power state changed
2016-09-16 15:07:09.056 ThaliTest[2567:4684476] BTM: power is now on
,2016-09-16 15:07:13.721 ThaliTest[2567:4684476] BTM: local device power state changed
2016-09-16 15:07:13.722 ThaliTest[2567:4684476] BTM: power is now off
,received session: <ThaliCore.Session: 0x14cee2540>
,D49AD5DD-D701-4BFA-A865-44ED0E9DC5C5
Optional("D49AD5DD-D701-4BFA-A865-44ED0E9DC5C5")
,nil
,nil

,1F10443A-E153-408C-B0EE-D4B9D1EBED6B
Optional("1F10443A-E153-408C-B0EE-D4B9D1EBED6B")
,DDDCDB31-2031-448D-BD81-2B97E7944B98
Optional("DDDCDB31-2031-448D-BD81-2B97E7944B98")
,*Native tests were executed*
Total number of executed tests:  52
Number of passed tests:  50
Number of failed tests:  2
,Number of ignored tests:  0
Total duration:  27.78193700313568
Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
