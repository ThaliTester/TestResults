#### Test 864825820901bf9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864825820901bf9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6C1129EE-0C68-402A-B612-8E5992C228B4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6C1129EE-0C68-402A-B612-8E5992C228B4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864825820901bf9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864825820901bf9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2B1E4746-2DB1-4DE0-977D-A11944A99C78/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56081"
,(lldb)     command script import "/tmp/6C1129EE-0C68-402A-B612-8E5992C228B4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 12:01:46.509 ThaliTest[3047:6135324] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3C8808E4-B54D-4960-9216-3D4ED4A6B6AF/Library/Cookies/Cookies.binarycookies
,2016-09-23 12:01:46.638 ThaliTest[3047:6135324] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 12:01:46.639 ThaliTest[3047:6135324] Multi-tasking -> Device: YES, App: YES
,2016-09-23 12:01:46.659 ThaliTest[3047:6135324] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 12:01:48.223 ThaliTest[3047:6135324] Using UIWebView
,2016-09-23 12:01:48.234 ThaliTest[3047:6135324] [CDVTimer][handleopenurl] 0.494003ms
,2016-09-23 12:01:48.243 ThaliTest[3047:6135324] [CDVTimer][intentandnavigationfilter] 8.336961ms
2016-09-23 12:01:48.244 ThaliTest[3047:6135324] [CDVTimer][gesturehandler] 0.367999ms
2016-09-23 12:01:48.245 ThaliTest[3047:6135324] [CDVTimer][TotalPluginS,tartup] 11.058033ms
,2016-09-23 12:01:53.984 ThaliTest[3047:6135324] Resetting plugins due to page load.
,2016-09-23 12:01:57.291 ThaliTest[3047:6135324] Finished load of: file:///var/mobile/Containers/Bundle/Application/2B1E4746-2DB1-4DE0-977D-A11944A99C78/ThaliTest.app/www/index.html
,2016-09-23 12:01:57.588 ThaliTest[3047:6135324] JXcore Cordova plugin initializing
,2016-09-23 12:01:57.589 ThaliTest[3047:6135559] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x126bb83d0>
,Optional("28CA5451-ED58-441A-9A2E-4DCABF6286B9")
,nil
,nil
,Optional("A67B582B-935D-4D34-BE1F-4DC1F7B1CDF4")
,Optional("E852E0EE-257F-4805-8879-EC669752152D")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 12:02:21.649 ThaliTest[3047:6135324] BTM: attaching to BTServer
,2016-09-23 12:02:22.330 ThaliTest[3047:6135324] BTM: local device power state changed
2016-09-23 12:02:22.331 ThaliTest[3047:6135324] BTM: power is now on
,2016-09-23 12:02:27.020 ThaliTest[3047:6135324] BTM: local device power state changed
2016-09-23 12:02:27.021 ThaliTest[3047:6135324] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.5307719707489
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
