#### Test 8621445004dab41_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8621445004dab41/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AEC2DE4E-3588-4CB6-8D1B-57B08F4D47B1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AEC2DE4E-3588-4CB6-8D1B-57B08F4D47B1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8621445004dab41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8621445004dab41/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DF29C5D8-C389-44F8-A44C-3F7C459F717F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49741"
,(lldb)     command script import "/tmp/AEC2DE4E-3588-4CB6-8D1B-57B08F4D47B1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 01:03:41.961 ThaliTest[2836:5887815] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/50613841-53D2-470C-8540-DD88B2865DF2/Library/Cookies/Cookies.binarycookies
,2016-09-22 01:03:42.075 ThaliTest[2836:5887815] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 01:03:42.076 ThaliTest[2836:5887815] Multi-tasking -> Device: YES, App: YES
,2016-09-22 01:03:42.100 ThaliTest[2836:5887815] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 01:03:43.651 ThaliTest[2836:5887815] Using UIWebView
,2016-09-22 01:03:43.660 ThaliTest[2836:5887815] [CDVTimer][handleopenurl] 0.489056ms
,2016-09-22 01:03:43.669 ThaliTest[2836:5887815] [CDVTimer][intentandnavigationfilter] 8.293033ms
2016-09-22 01:03:43.669 ThaliTest[2836:5887815] [CDVTimer][gesturehandler] 0.402987ms
2016-09-22 01:03:43.670 ThaliTest[2836:5887815] [CDVTimer][TotalPluginS,tartup] 11.057019ms
,2016-09-22 01:03:50.281 ThaliTest[2836:5887815] Resetting plugins due to page load.
,2016-09-22 01:03:53.899 ThaliTest[2836:5887815] Finished load of: file:///var/mobile/Containers/Bundle/Application/DF29C5D8-C389-44F8-A44C-3F7C459F717F/ThaliTest.app/www/index.html
,2016-09-22 01:03:54.216 ThaliTest[2836:5887815] JXcore Cordova plugin initializing
,2016-09-22 01:03:54.218 ThaliTest[2836:5888041] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x139a30660>
,Optional("6D6C3A2A-7674-42C5-BC8A-E6BC4E62A5D2")
,nil
,nil
,Optional("A0C25646-804C-4B59-8AA9-8669A6CDB4D7")
,Optional("8C635995-5907-41CA-96ED-8EAC8ADCE464")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 01:04:18.312 ThaliTest[2836:5887815] BTM: attaching to BTServer
,2016-09-22 01:04:19.032 ThaliTest[2836:5887815] BTM: local device power state changed
2016-09-22 01:04:19.032 ThaliTest[2836:5887815] BTM: power is now on
,2016-09-22 01:04:23.718 ThaliTest[2836:5887815] BTM: local device power state changed
2016-09-22 01:04:23.719 ThaliTest[2836:5887815] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.65709900856018
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
