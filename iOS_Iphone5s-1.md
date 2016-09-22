#### Test 855258872e8b4bc_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E9894A3F-3761-407E-915E-0A5013B73BD5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E9894A3F-3761-407E-915E-0A5013B73BD5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/801648A5-995E-4CD8-B970-C9A72B30AEA1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49659"
,(lldb)     command script import "/tmp/E9894A3F-3761-407E-915E-0A5013B73BD5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 13:33:08.161 ThaliTest[2926:5976709] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/96BFD97D-CD98-4531-824A-BFEE9C80AA1A/Library/Cookies/Cookies.binarycookies
,2016-09-22 13:33:08.277 ThaliTest[2926:5976709] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 13:33:08.278 ThaliTest[2926:5976709] Multi-tasking -> Device: YES, App: YES
,2016-09-22 13:33:08.304 ThaliTest[2926:5976709] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 13:33:09.937 ThaliTest[2926:5976709] Using UIWebView
,2016-09-22 13:33:09.948 ThaliTest[2926:5976709] [CDVTimer][handleopenurl] 0.494957ms
,2016-09-22 13:33:09.957 ThaliTest[2926:5976709] [CDVTimer][intentandnavigationfilter] 9.175003ms
2016-09-22 13:33:09.958 ThaliTest[2926:5976709] [CDVTimer][gesturehandler] 0.382960ms
2016-09-22 13:33:09.959 ThaliTest[2926:5976709] [CDVTimer][TotalPluginS,tartup] 11.956990ms
,2016-09-22 13:33:16.109 ThaliTest[2926:5976709] Resetting plugins due to page load.
,2016-09-22 13:33:19.733 ThaliTest[2926:5976709] Finished load of: file:///var/mobile/Containers/Bundle/Application/801648A5-995E-4CD8-B970-C9A72B30AEA1/ThaliTest.app/www/index.html
,2016-09-22 13:33:20.033 ThaliTest[2926:5976709] JXcore Cordova plugin initializing
,2016-09-22 13:33:20.034 ThaliTest[2926:5976945] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x1297b7b10>
,Optional("C9FAE9FF-25AC-4C43-868C-636C9B44B729")
,nil
,nil
,Optional("81930AB5-531C-42BE-A60E-B947B8886624")
,Optional("4F2C0198-5032-4785-92A8-43CA7654EAD1")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-22 13:33:43.220 ThaliTest[2926:5976709] BTM: attaching to BTServer
,2016-09-22 13:33:43.918 ThaliTest[2926:5976709] BTM: local device power state changed
2016-09-22 13:33:43.926 ThaliTest[2926:5976709] BTM: power is now on
,2016-09-22 13:33:48.640 ThaliTest[2926:5976709] BTM: local device power state changed
2016-09-22 13:33:48.644 ThaliTest[2926:5976709] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  19.80383104085922
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
