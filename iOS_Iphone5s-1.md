#### Test 86174379abea55c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5F362792-DDA4-485A-94CC-B91B3EC5B495/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5F362792-DDA4-485A-94CC-B91B3EC5B495/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/01411D7C-F09F-4E1D-B8F7-133E0AAABC9C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56122"
,(lldb)     command script import "/tmp/5F362792-DDA4-485A-94CC-B91B3EC5B495/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 18:28:54.540 ThaliTest[2812:5843412] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9B82C65E-97A6-4753-8AAA-6A1E281F0C0F/Library/Cookies/Cookies.binarycookies
,2016-09-21 18:28:54.663 ThaliTest[2812:5843412] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 18:28:54.664 ThaliTest[2812:5843412] Multi-tasking -> Device: YES, App: YES
,2016-09-21 18:28:54.686 ThaliTest[2812:5843412] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 18:28:56.291 ThaliTest[2812:5843412] Using UIWebView
,2016-09-21 18:28:56.303 ThaliTest[2812:5843412] [CDVTimer][handleopenurl] 0.445008ms
,2016-09-21 18:28:56.311 ThaliTest[2812:5843412] [CDVTimer][intentandnavigationfilter] 8.230984ms
2016-09-21 18:28:56.312 ThaliTest[2812:5843412] [CDVTimer][gesturehandler] 0.360012ms
2016-09-21 18:28:56.313 ThaliTest[2812:5843412] [CDVTimer][TotalPluginS,tartup] 10.933995ms
,2016-09-21 18:29:02.606 ThaliTest[2812:5843412] Resetting plugins due to page load.
,2016-09-21 18:29:06.415 ThaliTest[2812:5843412] Finished load of: file:///var/mobile/Containers/Bundle/Application/01411D7C-F09F-4E1D-B8F7-133E0AAABC9C/ThaliTest.app/www/index.html
,2016-09-21 18:29:06.736 ThaliTest[2812:5843412] JXcore Cordova plugin initializing
,2016-09-21 18:29:06.737 ThaliTest[2812:5843640] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x127712d40>
,Optional("6F1AF189-232B-4064-85E6-9D9F8821E38E")
,nil
,nil
,Optional("893ACC97-2538-4788-BFD2-35C647EE1524")
,Optional("C085669E-F156-40C9-86B1-05C69A721584")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-21 18:29:30.536 ThaliTest[2812:5843412] BTM: attaching to BTServer
,2016-09-21 18:29:31.242 ThaliTest[2812:5843412] BTM: local device power state changed
2016-09-21 18:29:31.243 ThaliTest[2812:5843412] BTM: power is now on
,2016-09-21 18:29:35.940 ThaliTest[2812:5843412] BTM: local device power state changed
2016-09-21 18:29:35.941 ThaliTest[2812:5843412] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.30412799119949
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
