#### Test 865221020889ce9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/6CC8D74F-917E-4351-A90D-8BF9E66EE122/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6CC8D74F-917E-4351-A90D-8BF9E66EE122/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A5B22D84-53DE-4B8D-8C0E-EFCF928106ED/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59266"
,(lldb)     command script import "/tmp/6CC8D74F-917E-4351-A90D-8BF9E66EE122/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 16:31:36.615 ThaliTest[3361:5970511] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CB6628C7-C5B4-4526-8140-FE7C71804B67/Library/Cookies/Cookies.binarycookies
,2016-09-26 16:31:36.975 ThaliTest[3361:5970511] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 16:31:36.976 ThaliTest[3361:5970511] Multi-tasking -> Device: YES, App: YES
,2016-09-26 16:31:36.998 ThaliTest[3361:5970511] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 16:31:38.946 ThaliTest[3361:5970511] Using UIWebView
,2016-09-26 16:31:38.953 ThaliTest[3361:5970511] [CDVTimer][handleopenurl] 0.446975ms
,2016-09-26 16:31:38.960 ThaliTest[3361:5970511] [CDVTimer][intentandnavigationfilter] 6.922960ms
,2016-09-26 16:31:38.961 ThaliTest[3361:5970511] [CDVTimer][gesturehandler] 0.321984ms
,2016-09-26 16:31:38.961 ThaliTest[3361:5970511] [CDVTimer][TotalPluginStartup] 9.374022ms
,2016-09-26 16:31:45.357 ThaliTest[3361:5970511] Resetting plugins due to page load.
,2016-09-26 16:31:48.376 ThaliTest[3361:5970511] Finished load of: file:///var/mobile/Containers/Bundle/Application/A5B22D84-53DE-4B8D-8C0E-EFCF928106ED/ThaliTest.app/www/index.html
,2016-09-26 16:31:48.644 ThaliTest[3361:5970511] JXcore Cordova plugin initializing
,2016-09-26 16:31:48.644 ThaliTest[3361:5970769] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x127fe8670>
,Optional("C5A3BB8E-4AE1-461F-8A79-7BA4A2B8F95A")
,nil
,nil
,Optional("6F1CC7F2-66C9-457D-9E75-1E65570C7234")
,Optional("954559D7-CC8F-4300-AE78-C0D16F4D7A16")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
,Number of passed tests:  54
Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  20.67703002691269
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
