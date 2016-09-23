#### Test 864536137cfe9e7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/86800AC6-371A-4958-B89B-0BD5F04AEC11/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/86800AC6-371A-4958-B89B-0BD5F04AEC11/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864536137cfe9e7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BC634F97-AE6C-4CD8-AC30-CFF5C5B4DBA7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57190"
,(lldb)     command script import "/tmp/86800AC6-371A-4958-B89B-0BD5F04AEC11/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 07:38:39.422 ThaliTest[3089:5539757] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ABD93C96-E0AE-4D10-AA1D-8796D24017B6/Library/Cookies/Cookies.binarycookies
,2016-09-23 07:38:39.780 ThaliTest[3089:5539757] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 07:38:39.782 ThaliTest[3089:5539757] Multi-tasking -> Device: YES, App: YES
,2016-09-23 07:38:39.803 ThaliTest[3089:5539757] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 07:38:41.748 ThaliTest[3089:5539757] Using UIWebView
,2016-09-23 07:38:41.755 ThaliTest[3089:5539757] [CDVTimer][handleopenurl] 0.504971ms
,2016-09-23 07:38:41.762 ThaliTest[3089:5539757] [CDVTimer][intentandnavigationfilter] 6.484032ms
,2016-09-23 07:38:41.763 ThaliTest[3089:5539757] [CDVTimer][gesturehandler] 0.330985ms
,2016-09-23 07:38:41.763 ThaliTest[3089:5539757] [CDVTimer][TotalPluginStartup] 9.167016ms
,2016-09-23 07:38:48.433 ThaliTest[3089:5539757] Resetting plugins due to page load.
,2016-09-23 07:38:51.948 ThaliTest[3089:5539757] Finished load of: file:///var/mobile/Containers/Bundle/Application/BC634F97-AE6C-4CD8-AC30-CFF5C5B4DBA7/ThaliTest.app/www/index.html
,2016-09-23 07:38:52.169 ThaliTest[3089:5539757] JXcore Cordova plugin initializing
,2016-09-23 07:38:52.170 ThaliTest[3089:5540007] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x137893d60>
,Optional("15859375-0417-4F2A-847E-A1CD3D6B1CD1")
,nil
,nil
,Optional("9273ED05-02E9-4743-B63E-79718E8FBD58")
,Optional("A73B9238-E844-4105-A770-E80D0A81887B")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 07:39:18.373 ThaliTest[3089:5539757] BTM: attaching to BTServer
,2016-09-23 07:39:19.174 ThaliTest[3089:5539757] BTM: local device power state changed
2016-09-23 07:39:19.174 ThaliTest[3089:5539757] BTM: power is now on
,2016-09-23 07:39:23.825 ThaliTest[3089:5539757] BTM: local device power state changed
2016-09-23 07:39:23.826 ThaliTest[3089:5539757] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.15840095281601
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
