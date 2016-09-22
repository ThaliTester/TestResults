#### Test 855258874296799_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/24838183-7460-46B9-B67A-AB79AC6A2032/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/24838183-7460-46B9-B67A-AB79AC6A2032/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/371E3654-A24F-402A-A534-00C57CF073FD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51626"
,(lldb)     command script import "/tmp/24838183-7460-46B9-B67A-AB79AC6A2032/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 14:06:28.094 ThaliTest[3035:5446031] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/30A3810A-8D5E-406E-B768-903CF42238E4/Library/Cookies/Cookies.binarycookies
,2016-09-22 14:06:28.417 ThaliTest[3035:5446031] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 14:06:28.419 ThaliTest[3035:5446031] Multi-tasking -> Device: YES, App: YES
,2016-09-22 14:06:28.433 ThaliTest[3035:5446031] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 14:06:30.133 ThaliTest[3035:5446031] Using UIWebView
,2016-09-22 14:06:30.140 ThaliTest[3035:5446031] [CDVTimer][handleopenurl] 0.352979ms
,2016-09-22 14:06:30.147 ThaliTest[3035:5446031] [CDVTimer][intentandnavigationfilter] 6.334007ms
,2016-09-22 14:06:30.148 ThaliTest[3035:5446031] [CDVTimer][gesturehandler] 0.288010ms
,2016-09-22 14:06:30.148 ThaliTest[3035:5446031] [CDVTimer][TotalPluginStartup] 8.522987ms
,2016-09-22 14:06:36.409 ThaliTest[3035:5446031] Resetting plugins due to page load.
,2016-09-22 14:06:39.264 ThaliTest[3035:5446031] Finished load of: file:///var/mobile/Containers/Bundle/Application/371E3654-A24F-402A-A534-00C57CF073FD/ThaliTest.app/www/index.html
,2016-09-22 14:06:39.475 ThaliTest[3035:5446031] JXcore Cordova plugin initializing
,2016-09-22 14:06:39.476 ThaliTest[3035:5446264] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x150e94e60>
,Optional("76458864-A38F-4FF3-A503-094B9C4E336A")
,nil
,nil
,Optional("328C48D5-0F51-44A9-9350-23ED196EA662")
,Optional("E9765E7C-FD05-4695-BA70-72096C7E9155")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 14:07:05.244 ThaliTest[3035:5446031] BTM: attaching to BTServer
,2016-09-22 14:07:06.040 ThaliTest[3035:5446031] BTM: local device power state changed
2016-09-22 14:07:06.041 ThaliTest[3035:5446031] BTM: power is now on
,2016-09-22 14:07:10.792 ThaliTest[3035:5446031] BTM: local device power state changed
2016-09-22 14:07:10.792 ThaliTest[3035:5446031] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.79726195335388
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
