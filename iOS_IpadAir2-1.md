#### Test 8504691186bae88_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/3338B86A-0A0B-4B75-A0E8-04B5EA1919B4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3338B86A-0A0B-4B75-A0E8-04B5EA1919B4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FD65DE19-330F-4904-B174-2B22A6F51D38/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54939"
,(lldb)     command script import "/tmp/3338B86A-0A0B-4B75-A0E8-04B5EA1919B4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 09:59:26.522 ThaliTest[2970:5416761] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/019C0E08-AF5A-47C4-A18D-6DC46D917A58/Library/Cookies/Cookies.binarycookies
,2016-09-22 09:59:26.843 ThaliTest[2970:5416761] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 09:59:26.844 ThaliTest[2970:5416761] Multi-tasking -> Device: YES, App: YES
,2016-09-22 09:59:26.861 ThaliTest[2970:5416761] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 09:59:28.625 ThaliTest[2970:5416761] Using UIWebView
,2016-09-22 09:59:28.632 ThaliTest[2970:5416761] [CDVTimer][handleopenurl] 0.342011ms
,2016-09-22 09:59:28.638 ThaliTest[2970:5416761] [CDVTimer][intentandnavigationfilter] 6.308019ms
,2016-09-22 09:59:28.639 ThaliTest[2970:5416761] [CDVTimer][gesturehandler] 0.317991ms
,2016-09-22 09:59:28.640 ThaliTest[2970:5416761] [CDVTimer][TotalPluginStartup] 8.853018ms
,2016-09-22 09:59:35.108 ThaliTest[2970:5416761] Resetting plugins due to page load.
,2016-09-22 09:59:38.125 ThaliTest[2970:5416761] Finished load of: file:///var/mobile/Containers/Bundle/Application/FD65DE19-330F-4904-B174-2B22A6F51D38/ThaliTest.app/www/index.html
,2016-09-22 09:59:38.405 ThaliTest[2970:5416761] JXcore Cordova plugin initializing
,2016-09-22 09:59:38.406 ThaliTest[2970:5416988] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x145e55be0>
,Optional("B6E22F73-7A7B-4A83-8B95-2E9FFF90F522")
,nil
,nil
,Optional("C8D3927B-5EB2-418F-B2DE-1187F433DD77")
,Optional("FE0B4965-FD81-4127-891F-E308C2AB3A78")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 10:00:04.217 ThaliTest[2970:5416761] BTM: attaching to BTServer
,2016-09-22 10:00:05.034 ThaliTest[2970:5416761] BTM: local device power state changed
2016-09-22 10:00:05.035 ThaliTest[2970:5416761] BTM: power is now on
,2016-09-22 10:00:09.717 ThaliTest[2970:5416761] BTM: local device power state changed
2016-09-22 10:00:09.718 ThaliTest[2970:5416761] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.83567303419113
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
