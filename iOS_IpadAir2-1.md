#### Test 832688934d87cf0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832688934d87cf0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D3D57513-D499-44BC-9EA4-E7843BF89437/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D3D57513-D499-44BC-9EA4-E7843BF89437/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/832688934d87cf0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832688934d87cf0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7BEBC332-BFBA-4354-8F2A-99AAD8C6FE4A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59623"
,(lldb)     command script import "/tmp/D3D57513-D499-44BC-9EA4-E7843BF89437/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 14:30:17.079 ThaliTest[2771:5177372] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C6C51202-97DF-46BF-8ADA-DC0C4D241C8C/Library/Cookies/Cookies.binarycookies
,2016-09-20 14:30:17.439 ThaliTest[2771:5177372] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 14:30:17.441 ThaliTest[2771:5177372] Multi-tasking -> Device: YES, App: YES
,2016-09-20 14:30:17.464 ThaliTest[2771:5177372] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 14:30:19.449 ThaliTest[2771:5177372] Using UIWebView
,2016-09-20 14:30:19.456 ThaliTest[2771:5177372] [CDVTimer][handleopenurl] 0.441968ms
,2016-09-20 14:30:19.463 ThaliTest[2771:5177372] [CDVTimer][intentandnavigationfilter] 6.418943ms
,2016-09-20 14:30:19.464 ThaliTest[2771:5177372] [CDVTimer][gesturehandler] 0.283957ms
,2016-09-20 14:30:19.464 ThaliTest[2771:5177372] [CDVTimer][TotalPluginStartup] 8.680999ms
,2016-09-20 14:30:25.819 ThaliTest[2771:5177372] Resetting plugins due to page load.
,2016-09-20 14:30:28.786 ThaliTest[2771:5177372] Finished load of: file:///var/mobile/Containers/Bundle/Application/7BEBC332-BFBA-4354-8F2A-99AAD8C6FE4A/ThaliTest.app/www/index.html
,2016-09-20 14:30:29.003 ThaliTest[2771:5177372] JXcore Cordova plugin initializing
,2016-09-20 14:30:29.004 ThaliTest[2771:5177603] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12ee8ff00>
,E0513E10-4A03-4A3F-8569-258A07297F80
Optional("E0513E10-4A03-4A3F-8569-258A07297F80")
,nil
,nil

,69289A17-2999-4DA6-A1ED-DBE1E40A9222
Optional("69289A17-2999-4DA6-A1ED-DBE1E40A9222")
,617C69AD-4C00-49F2-B5ED-2D0B3DCA3BEB
Optional("617C69AD-4C00-49F2-B5ED-2D0B3DCA3BEB")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-20 14:30:48.587 ThaliTest[2771:5177372] BTM: attaching to BTServer
,2016-09-20 14:30:49.402 ThaliTest[2771:5177372] BTM: local device power state changed
2016-09-20 14:30:49.403 ThaliTest[2771:5177372] BTM: power is now on
,2016-09-20 14:30:54.069 ThaliTest[2771:5177372] BTM: local device power state changed
2016-09-20 14:30:54.074 ThaliTest[2771:5177372] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  52
,Number of passed tests:  52
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  18.57131898403168
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
