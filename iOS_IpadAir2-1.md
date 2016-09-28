#### Test 85046911920cb66_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/69444E8E-B727-44D5-B7E2-7F198913B12E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/69444E8E-B727-44D5-B7E2-7F198913B12E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A710E9AC-2285-4266-A95A-727847AD0CB0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61282"
,(lldb)     command script import "/tmp/69444E8E-B727-44D5-B7E2-7F198913B12E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 10:04:48.749 ThaliTest[3511:6194237] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/96BE25B3-E052-40AE-840E-F3F49D0D7694/Library/Cookies/Cookies.binarycookies
,2016-09-28 10:04:49.082 ThaliTest[3511:6194237] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 10:04:49.083 ThaliTest[3511:6194237] Multi-tasking -> Device: YES, App: YES
,2016-09-28 10:04:49.099 ThaliTest[3511:6194237] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 10:04:51.222 ThaliTest[3511:6194237] Using UIWebView
,2016-09-28 10:04:51.229 ThaliTest[3511:6194237] [CDVTimer][handleopenurl] 0.366032ms
,2016-09-28 10:04:51.237 ThaliTest[3511:6194237] [CDVTimer][intentandnavigationfilter] 7.404983ms
,2016-09-28 10:04:51.238 ThaliTest[3511:6194237] [CDVTimer][gesturehandler] 0.329971ms
,2016-09-28 10:04:51.238 ThaliTest[3511:6194237] [CDVTimer][TotalPluginStartup] 9.881020ms
,2016-09-28 10:04:58.225 ThaliTest[3511:6194237] Resetting plugins due to page load.
,2016-09-28 10:05:01.483 ThaliTest[3511:6194237] Finished load of: file:///var/mobile/Containers/Bundle/Application/A710E9AC-2285-4266-A95A-727847AD0CB0/ThaliTest.app/www/index.html
,2016-09-28 10:05:01.630 ThaliTest[3511:6194237] JXcore Cordova plugin initializing
,2016-09-28 10:05:01.631 ThaliTest[3511:6194477] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,received session: <ThaliCore.Session: 0x126e23b50>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("4EF2C29D-7DA2-4BAC-9E77-0B6D295782FE")
,nil
,nil
,Optional("CD8BD0D1-8884-4F6E-BF35-C6B83B83B870")
,Optional("BEFBC9FD-141A-4903-A14C-E7F381C8A51D")
,*Native tests were executed*
,Total number of executed tests:  55
Number of passed tests:  53
,Number of failed tests:  2
,Number of ignored tests:  0
Total duration:  19.80320399999619
,Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
