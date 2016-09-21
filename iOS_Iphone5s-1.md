#### Test 862144504e2d579_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/862144504e2d579/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0F1A053A-FDF2-42A3-8241-1E9BE5358EC8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0F1A053A-FDF2-42A3-8241-1E9BE5358EC8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/862144504e2d579/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/862144504e2d579/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FF7D9D86-ECEA-4541-AC5E-E36BF09F3D73/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64524"
,(lldb)     command script import "/tmp/0F1A053A-FDF2-42A3-8241-1E9BE5358EC8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 00:43:34.189 ThaliTest[2829:5883804] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AB150EFC-2333-45EE-91D3-3E623725B4F3/Library/Cookies/Cookies.binarycookies
,2016-09-22 00:43:34.790 ThaliTest[2829:5883804] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 00:43:34.791 ThaliTest[2829:5883804] Multi-tasking -> Device: YES, App: YES
,2016-09-22 00:43:34.809 ThaliTest[2829:5883804] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 00:43:36.338 ThaliTest[2829:5883804] Using UIWebView
,2016-09-22 00:43:36.347 ThaliTest[2829:5883804] [CDVTimer][handleopenurl] 0.651002ms
,2016-09-22 00:43:36.356 ThaliTest[2829:5883804] [CDVTimer][intentandnavigationfilter] 8.322001ms
2016-09-22 00:43:36.357 ThaliTest[2829:5883804] [CDVTimer][gesturehandler] 0.416040ms
2016-09-22 00:43:36.357 ThaliTest[2829:5883804] [CDVTimer][TotalPluginS,tartup] 11.267960ms
,2016-09-22 00:43:42.998 ThaliTest[2829:5883804] Resetting plugins due to page load.
,2016-09-22 00:43:46.064 ThaliTest[2829:5883804] Finished load of: file:///var/mobile/Containers/Bundle/Application/FF7D9D86-ECEA-4541-AC5E-E36BF09F3D73/ThaliTest.app/www/index.html
,2016-09-22 00:43:46.310 ThaliTest[2829:5883804] JXcore Cordova plugin initializing
,2016-09-22 00:43:46.311 ThaliTest[2829:5884022] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1376fb340>
,Optional("9DB63BDD-33FE-4321-AEC7-A9004C5A4A79")
,nil
,nil
,Optional("94492C64-9D41-4A03-A0C6-C115C605F734")
,Optional("40FD42E4-B12F-496B-ADD8-5E7E26D7A278")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 00:44:10.515 ThaliTest[2829:5883804] BTM: attaching to BTServer
,2016-09-22 00:44:11.226 ThaliTest[2829:5883804] BTM: local device power state changed
,2016-09-22 00:44:11.245 ThaliTest[2829:5883804] BTM: power is now on
,2016-09-22 00:44:15.945 ThaliTest[2829:5883804] BTM: local device power state changed
2016-09-22 00:44:15.946 ThaliTest[2829:5883804] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.74819505214691
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
