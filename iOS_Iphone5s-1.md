#### Test 85960304727dacc_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304727dacc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9E8D4119-87DD-477F-A0C0-52DCFFFCE8D9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9E8D4119-87DD-477F-A0C0-52DCFFFCE8D9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304727dacc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304727dacc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B97D667E-6F6F-47E3-9879-121AE476AAFA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53079"
,(lldb)     command script import "/tmp/9E8D4119-87DD-477F-A0C0-52DCFFFCE8D9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 15:00:02.475 ThaliTest[2942:5987734] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FF9FBC40-45BC-4AF7-81B5-48A4C3CD9631/Library/Cookies/Cookies.binarycookies
,2016-09-22 15:00:02.584 ThaliTest[2942:5987734] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 15:00:02.586 ThaliTest[2942:5987734] Multi-tasking -> Device: YES, App: YES
,2016-09-22 15:00:02.607 ThaliTest[2942:5987734] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 15:00:04.056 ThaliTest[2942:5987734] Using UIWebView
,2016-09-22 15:00:04.065 ThaliTest[2942:5987734] [CDVTimer][handleopenurl] 0.486016ms
,2016-09-22 15:00:04.073 ThaliTest[2942:5987734] [CDVTimer][intentandnavigationfilter] 8.098006ms
2016-09-22 15:00:04.074 ThaliTest[2942:5987734] [CDVTimer][gesturehandler] 0.382006ms
2016-09-22 15:00:04.075 ThaliTest[2942:5987734] [CDVTimer][TotalPluginS,tartup] 10.962009ms
,2016-09-22 15:00:10.056 ThaliTest[2942:5987734] Resetting plugins due to page load.
,2016-09-22 15:00:13.378 ThaliTest[2942:5987734] Finished load of: file:///var/mobile/Containers/Bundle/Application/B97D667E-6F6F-47E3-9879-121AE476AAFA/ThaliTest.app/www/index.html
,2016-09-22 15:00:13.689 ThaliTest[2942:5987734] JXcore Cordova plugin initializing
,2016-09-22 15:00:13.690 ThaliTest[2942:5987973] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x1284ab330>
,Optional("10A74B40-B4F4-43CC-926A-DBCA25A80203")
,nil
,nil
,Optional("A8A1CC00-8095-4359-9C64-4490FD6A38C1")
,Optional("9BD0A9DE-49C1-4C42-B2AA-B3DFE390722D")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 15:00:37.353 ThaliTest[2942:5987734] BTM: attaching to BTServer
,2016-09-22 15:00:38.059 ThaliTest[2942:5987734] BTM: local device power state changed
2016-09-22 15:00:38.060 ThaliTest[2942:5987734] BTM: power is now on
,2016-09-22 15:00:42.800 ThaliTest[2942:5987734] BTM: local device power state changed
2016-09-22 15:00:42.800 ThaliTest[2942:5987734] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  20.40449297428131
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
