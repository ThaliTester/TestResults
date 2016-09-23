#### Test 86453613e903f38_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86453613e903f38/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/45B1B98E-D880-4444-AA74-840410A9E940/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/45B1B98E-D880-4444-AA74-840410A9E940/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86453613e903f38/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86453613e903f38/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D4B35F47-F7FA-4F87-9DE1-D8161B4EC339/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58961"
,(lldb)     command script import "/tmp/45B1B98E-D880-4444-AA74-840410A9E940/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 08:07:23.250 ThaliTest[3097:5543329] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F2C21697-D750-42EB-B852-B2DEB3B6969E/Library/Cookies/Cookies.binarycookies
,2016-09-23 08:07:23.604 ThaliTest[3097:5543329] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 08:07:23.606 ThaliTest[3097:5543329] Multi-tasking -> Device: YES, App: YES
,2016-09-23 08:07:23.625 ThaliTest[3097:5543329] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 08:07:25.495 ThaliTest[3097:5543329] Using UIWebView
,2016-09-23 08:07:25.501 ThaliTest[3097:5543329] [CDVTimer][handleopenurl] 0.445008ms
,2016-09-23 08:07:25.509 ThaliTest[3097:5543329] [CDVTimer][intentandnavigationfilter] 7.232010ms
,2016-09-23 08:07:25.510 ThaliTest[3097:5543329] [CDVTimer][gesturehandler] 0.310004ms
,2016-09-23 08:07:25.510 ThaliTest[3097:5543329] [CDVTimer][TotalPluginStartup] 9.666026ms
,2016-09-23 08:07:31.745 ThaliTest[3097:5543329] Resetting plugins due to page load.
,2016-09-23 08:07:34.664 ThaliTest[3097:5543329] Finished load of: file:///var/mobile/Containers/Bundle/Application/D4B35F47-F7FA-4F87-9DE1-D8161B4EC339/ThaliTest.app/www/index.html
,2016-09-23 08:07:34.865 ThaliTest[3097:5543329] JXcore Cordova plugin initializing
,2016-09-23 08:07:34.866 ThaliTest[3097:5543589] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12ed0df20>
,Optional("340D5031-BCBF-4BCF-A0FE-D76CE2734B65")
,nil
,nil
,Optional("071983C5-447A-435C-A013-D2C668972FFE")
,Optional("5085B7E1-E9E7-4AC4-B390-82D8A2A7B11A")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 08:08:01.222 ThaliTest[3097:5543329] BTM: attaching to BTServer
,2016-09-23 08:08:02.031 ThaliTest[3097:5543329] BTM: local device power state changed
2016-09-23 08:08:02.031 ThaliTest[3097:5543329] BTM: power is now on
,2016-09-23 08:08:06.726 ThaliTest[3097:5543329] BTM: local device power state changed
2016-09-23 08:08:06.727 ThaliTest[3097:5543329] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.32419401407242
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
