#### Test 862144504e2d579_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/862144504e2d579/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E98825A3-05DD-48AF-838F-94B3C47637CD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E98825A3-05DD-48AF-838F-94B3C47637CD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/862144504e2d579/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/862144504e2d579/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/669149E5-BA48-45FB-B658-4B7E6273580F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64522"
,(lldb)     command script import "/tmp/E98825A3-05DD-48AF-838F-94B3C47637CD/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 00:43:34.487 ThaliTest[2920:5362449] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C3C96D3F-C419-4589-B8A4-61516836AD1A/Library/Cookies/Cookies.binarycookies
,2016-09-22 00:43:34.812 ThaliTest[2920:5362449] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 00:43:34.813 ThaliTest[2920:5362449] Multi-tasking -> Device: YES, App: YES
,2016-09-22 00:43:34.830 ThaliTest[2920:5362449] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 00:43:36.637 ThaliTest[2920:5362449] Using UIWebView
,2016-09-22 00:43:36.644 ThaliTest[2920:5362449] [CDVTimer][handleopenurl] 0.465989ms
,2016-09-22 00:43:36.651 ThaliTest[2920:5362449] [CDVTimer][intentandnavigationfilter] 6.919980ms
,2016-09-22 00:43:36.652 ThaliTest[2920:5362449] [CDVTimer][gesturehandler] 0.329018ms
,2016-09-22 00:43:36.653 ThaliTest[2920:5362449] [CDVTimer][TotalPluginStartup] 9.312034ms
,2016-09-22 00:43:43.366 ThaliTest[2920:5362449] Resetting plugins due to page load.
,2016-09-22 00:43:46.611 ThaliTest[2920:5362449] Finished load of: file:///var/mobile/Containers/Bundle/Application/669149E5-BA48-45FB-B658-4B7E6273580F/ThaliTest.app/www/index.html
,2016-09-22 00:43:46.830 ThaliTest[2920:5362449] JXcore Cordova plugin initializing
,2016-09-22 00:43:46.830 ThaliTest[2920:5362702] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x130617b40>
,Optional("29616707-C29E-4812-9149-2A2E73483789")
,nil
,nil
,Optional("D56E915C-BA6F-442B-A227-9B90F3F20871")
,Optional("1AD644B8-AD30-4669-A434-98B1D0107335")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 00:44:13.239 ThaliTest[2920:5362449] BTM: attaching to BTServer
,2016-09-22 00:44:14.050 ThaliTest[2920:5362449] BTM: local device power state changed
2016-09-22 00:44:14.051 ThaliTest[2920:5362449] BTM: power is now on
,2016-09-22 00:44:18.711 ThaliTest[2920:5362449] BTM: local device power state changed
2016-09-22 00:44:18.712 ThaliTest[2920:5362449] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  25.35114002227783
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
