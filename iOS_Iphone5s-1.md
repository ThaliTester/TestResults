#### Test 87116923a0346c7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87116923a0346c7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0AEA5F7A-3C01-40D6-906F-EA263F540652/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0AEA5F7A-3C01-40D6-906F-EA263F540652/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87116923a0346c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87116923a0346c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6B9D4E8F-4096-4FFB-8C69-74ACD07E1A63/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62750"
,(lldb)     command script import "/tmp/0AEA5F7A-3C01-40D6-906F-EA263F540652/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 09:26:15.891 ThaliTest[3491:7084197] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8EDCCCEC-D093-420B-9603-A53658FCFA9E/Library/Cookies/Cookies.binarycookies
,2016-09-29 09:26:16.018 ThaliTest[3491:7084197] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 09:26:16.020 ThaliTest[3491:7084197] Multi-tasking -> Device: YES, App: YES
,2016-09-29 09:26:16.044 ThaliTest[3491:7084197] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 09:26:17.490 ThaliTest[3491:7084197] Using UIWebView
,2016-09-29 09:26:17.498 ThaliTest[3491:7084197] [CDVTimer][handleopenurl] 0.477016ms
,2016-09-29 09:26:17.507 ThaliTest[3491:7084197] [CDVTimer][intentandnavigationfilter] 8.226991ms
2016-09-29 09:26:17.508 ThaliTest[3491:7084197] [CDVTimer][gesturehandler] 0.407994ms
2016-09-29 09:26:17.509 ThaliTest[3491:7084197] [CDVTimer][TotalPluginS,tartup] 11.168957ms
,2016-09-29 09:26:22.889 ThaliTest[3491:7084197] Resetting plugins due to page load.
,2016-09-29 09:26:26.102 ThaliTest[3491:7084197] Finished load of: file:///var/mobile/Containers/Bundle/Application/6B9D4E8F-4096-4FFB-8C69-74ACD07E1A63/ThaliTest.app/www/index.html
,2016-09-29 09:26:26.401 ThaliTest[3491:7084197] JXcore Cordova plugin initializing
,2016-09-29 09:26:26.402 ThaliTest[3491:7084412] JXcore instance initializing
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
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  54
Number of passed tests:  54
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  17.38136702775955
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
