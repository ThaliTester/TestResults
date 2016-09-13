#### Test 836273370459b7a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273370459b7a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/212F8686-A0DF-47AD-B5FA-343EFAE6A699/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/212F8686-A0DF-47AD-B5FA-343EFAE6A699/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273370459b7a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273370459b7a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6164D5B2-39E4-4825-BE80-82BF17306864/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49735"
,(lldb)     command script import "/tmp/212F8686-A0DF-47AD-B5FA-343EFAE6A699/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 16:32:45.394 ThaliTest[2238:4293194] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FB68A2C4-B52E-4EF6-A785-8FA59EB652A2/Library/Cookies/Cookies.binarycookies
,2016-09-13 16:32:45.787 ThaliTest[2238:4293194] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 16:32:45.789 ThaliTest[2238:4293194] Multi-tasking -> Device: YES, App: YES
,2016-09-13 16:32:45.808 ThaliTest[2238:4293194] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 16:32:47.788 ThaliTest[2238:4293194] Using UIWebView
,2016-09-13 16:32:47.799 ThaliTest[2238:4293194] [CDVTimer][handleopenurl] 0.437975ms
,2016-09-13 16:32:47.807 ThaliTest[2238:4293194] [CDVTimer][intentandnavigationfilter] 6.784022ms
,2016-09-13 16:32:47.807 ThaliTest[2238:4293194] [CDVTimer][gesturehandler] 0.316978ms
,2016-09-13 16:32:47.808 ThaliTest[2238:4293194] [CDVTimer][TotalPluginStartup] 9.322047ms
,2016-09-13 16:32:54.325 ThaliTest[2238:4293194] Resetting plugins due to page load.
,2016-09-13 16:32:58.432 ThaliTest[2238:4293194] Finished load of: file:///var/mobile/Containers/Bundle/Application/6164D5B2-39E4-4825-BE80-82BF17306864/ThaliTest.app/www/index.html
,2016-09-13 16:32:58.622 ThaliTest[2238:4293194] JXcore Cordova plugin initializing
,2016-09-13 16:32:58.623 ThaliTest[2238:4293441] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 16:33:04.778 ThaliTest[2238:4293441] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 16:33:04.778 ThaliTest[2238:4293441] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-13 16:33:04.779 ThaliTest[2238:4293441] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 16:33:04.781 ThaliTest[2238:4293441] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
