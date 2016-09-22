#### Test 8617437972ae596_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437972ae596/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5F79F7CD-E7ED-41A8-875C-4816511D11B9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/5F79F7CD-E7ED-41A8-875C-4816511D11B9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437972ae596/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437972ae596/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D5E45EED-E47E-4D65-81F2-957A37AEFCD0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56436"
,(lldb)     command script import "/tmp/5F79F7CD-E7ED-41A8-875C-4816511D11B9/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 01:15:56.886 ThaliTest[1301:1643760] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/81AEC908-EAB1-437B-8A95-90B218CA6858/Library/Cookies/Cookies.binarycookies
,2016-09-22 01:15:56.948 ThaliTest[1301:1643760] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 01:15:56.949 ThaliTest[1301:1643760] Multi-tasking -> Device: YES, App: YES
,2016-09-22 01:15:56.963 ThaliTest[1301:1643760] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 01:15:57.401 ThaliTest[1301:1643760] Using UIWebView
,2016-09-22 01:15:57.408 ThaliTest[1301:1643760] [CDVTimer][handleopenurl] 0.335991ms
,2016-09-22 01:15:57.415 ThaliTest[1301:1643760] [CDVTimer][intentandnavigationfilter] 6.865978ms
2016-09-22 01:15:57.416 ThaliTest[1301:1643760] [CDVTimer][gesturehandler] 0.299990ms
2016-09-22 01:15:57.416 ThaliTest[1301:1643760] [CDVTimer][TotalPluginS,tartup] 9.011030ms
,2016-09-22 01:16:02.976 ThaliTest[1301:1643760] Resetting plugins due to page load.
,2016-09-22 01:16:03.419 ThaliTest[1301:1643760] Finished load of: file:///var/containers/Bundle/Application/D5E45EED-E47E-4D65-81F2-957A37AEFCD0/ThaliTest.app/www/index.html
,2016-09-22 01:16:03.761 ThaliTest[1301:1643760] JXcore Cordova plugin initializing
,2016-09-22 01:16:03.762 ThaliTest[1301:1643920] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x15e3b0930>
,Optional("2B0B7F62-730E-4161-82CD-9ACCEEE7EBCB")
,nil
,nil
,Optional("AB0EA8F7-2FD8-41AC-AD52-468A964D0C07")
,Optional("6D86343C-A2A4-46E8-8D1A-61BF076D3CF2")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 01:16:26.077 ThaliTest[1301:1643760] BTM: attaching to BTServer
,2016-09-22 01:16:26.866 ThaliTest[1301:1643760] BTM: local device power state changed
2016-09-22 01:16:26.874 ThaliTest[1301:1643760] BTM: power is now on
,2016-09-22 01:16:31.569 ThaliTest[1301:1643760] BTM: local device power state changed
2016-09-22 01:16:31.570 ThaliTest[1301:1643760] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  20.44555604457855
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
