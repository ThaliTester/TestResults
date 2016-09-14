#### Test 8526390230c731c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/65538DB0-7740-4747-B22E-44750FC69912/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/65538DB0-7740-4747-B22E-44750FC69912/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FEAC0E8D-3C48-4896-8F29-255D22E922DC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50171"
,(lldb)     command script import "/tmp/65538DB0-7740-4747-B22E-44750FC69912/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 22:57:43.171 ThaliTest[2280:4794135] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6A9DD6E3-A268-4FE6-8768-D5F36FC0D064/Library/Cookies/Cookies.binarycookies
,2016-09-14 22:57:43.297 ThaliTest[2280:4794135] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 22:57:43.299 ThaliTest[2280:4794135] Multi-tasking -> Device: YES, App: YES
,2016-09-14 22:57:43.327 ThaliTest[2280:4794135] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 22:57:45.060 ThaliTest[2280:4794135] Using UIWebView
,2016-09-14 22:57:45.069 ThaliTest[2280:4794135] [CDVTimer][handleopenurl] 0.487983ms
,2016-09-14 22:57:45.078 ThaliTest[2280:4794135] [CDVTimer][intentandnavigationfilter] 8.085966ms
2016-09-14 22:57:45.079 ThaliTest[2280:4794135] [CDVTimer][gesturehandler] 0.420034ms
2016-09-14 22:57:45.079 ThaliTest[2280:4794135] [CDVTimer][TotalPluginS,tartup] 11.292994ms
,2016-09-14 22:57:52.065 ThaliTest[2280:4794135] Resetting plugins due to page load.
,2016-09-14 22:57:55.747 ThaliTest[2280:4794135] Finished load of: file:///var/mobile/Containers/Bundle/Application/FEAC0E8D-3C48-4896-8F29-255D22E922DC/ThaliTest.app/www/index.html
,2016-09-14 22:57:56.070 ThaliTest[2280:4794135] JXcore Cordova plugin initializing
,2016-09-14 22:57:56.072 ThaliTest[2280:4794384] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x13916fdb0>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 22:58:19.717 ThaliTest[2280:4794135] BTM: attaching to BTServer
,2016-09-14 22:58:20.808 ThaliTest[2280:4794135] BTM: local device power state changed
2016-09-14 22:58:20.808 ThaliTest[2280:4794135] BTM: power is now off
,2016-09-14 22:58:21.588 ThaliTest[2280:4794135] BTM: local device power state changed
2016-09-14 22:58:21.590 ThaliTest[2280:4794135] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  51
Number of passed tests:  51
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  16.75581896305084
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
