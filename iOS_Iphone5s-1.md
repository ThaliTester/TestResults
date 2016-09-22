#### Test 855258874296799_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A6FD9840-1543-47AE-94B7-CE9F6CE8C2B3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A6FD9840-1543-47AE-94B7-CE9F6CE8C2B3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D103CFD1-E456-428B-8DED-33ECEE29A148/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51628"
,(lldb)     command script import "/tmp/A6FD9840-1543-47AE-94B7-CE9F6CE8C2B3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 14:06:26.501 ThaliTest[2934:5981959] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6523F946-78ED-4F12-8FC3-252C8E973E3E/Library/Cookies/Cookies.binarycookies
,2016-09-22 14:06:26.629 ThaliTest[2934:5981959] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 14:06:26.632 ThaliTest[2934:5981959] Multi-tasking -> Device: YES, App: YES
,2016-09-22 14:06:26.658 ThaliTest[2934:5981959] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 14:06:28.226 ThaliTest[2934:5981959] Using UIWebView
,2016-09-22 14:06:28.237 ThaliTest[2934:5981959] [CDVTimer][handleopenurl] 0.562012ms
,2016-09-22 14:06:28.246 ThaliTest[2934:5981959] [CDVTimer][intentandnavigationfilter] 8.199990ms
2016-09-22 14:06:28.247 ThaliTest[2934:5981959] [CDVTimer][gesturehandler] 0.376999ms
2016-09-22 14:06:28.247 ThaliTest[2934:5981959] [CDVTimer][TotalPluginS,tartup] 11.020005ms
,2016-09-22 14:06:33.995 ThaliTest[2934:5981959] Resetting plugins due to page load.
,2016-09-22 14:06:37.343 ThaliTest[2934:5981959] Finished load of: file:///var/mobile/Containers/Bundle/Application/D103CFD1-E456-428B-8DED-33ECEE29A148/ThaliTest.app/www/index.html
,2016-09-22 14:06:37.639 ThaliTest[2934:5981959] JXcore Cordova plugin initializing
,2016-09-22 14:06:37.641 ThaliTest[2934:5982183] JXcore instance initializing
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
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 14:06:46.619 ThaliTest[2934:5981959] BTM: attaching to BTServer
,2016-09-22 14:06:47.420 ThaliTest[2934:5981959] BTM: local device power state changed
2016-09-22 14:06:47.421 ThaliTest[2934:5981959] BTM: power is now on
,2016-09-22 14:06:52.151 ThaliTest[2934:5981959] BTM: local device power state changed
2016-09-22 14:06:52.152 ThaliTest[2934:5981959] BTM: power is now off
,received session: <ThaliCore.Session: 0x126afc000>
,Optional("995A2D03-B50F-49F3-A99C-E19B3A87F3E2")
,nil
,nil
,Optional("AACE0478-53AA-43C5-B1C5-B455332BF743")
,Optional("29FB637D-2F88-4A1A-B8EC-C54BDCAB1D66")
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  19.63098394870758
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
