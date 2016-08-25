#### Test 82728424cc1b7f1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82728424cc1b7f1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/940DCA6F-E242-4113-91E6-F4EBA86AC050/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/940DCA6F-E242-4113-91E6-F4EBA86AC050/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82728424cc1b7f1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82728424cc1b7f1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B89BE5C2-869B-4205-AC7C-91176F5B2E73/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65448"
,(lldb)     command script import "/tmp/940DCA6F-E242-4113-91E6-F4EBA86AC050/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-25 21:48:09.507 ThaliTest[991:1873636] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CCE4E3E8-B454-4FFD-AB27-AB5E09ED99D5/Library/Cookies/Cookies.binarycookies
,2016-08-25 21:48:09.890 ThaliTest[991:1873636] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 21:48:09.891 ThaliTest[991:1873636] Multi-tasking -> Device: YES, App: YES
,2016-08-25 21:48:09.910 ThaliTest[991:1873636] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 21:48:11.964 ThaliTest[991:1873636] Using UIWebView
,2016-08-25 21:48:11.971 ThaliTest[991:1873636] [CDVTimer][handleopenurl] 0.417948ms
,2016-08-25 21:48:11.978 ThaliTest[991:1873636] [CDVTimer][intentandnavigationfilter] 6.671011ms
,2016-08-25 21:48:11.979 ThaliTest[991:1873636] [CDVTimer][gesturehandler] 0.299037ms
,2016-08-25 21:48:11.979 ThaliTest[991:1873636] [CDVTimer][TotalPluginStartup] 9.330988ms
,2016-08-25 21:48:18.777 ThaliTest[991:1873636] Resetting plugins due to page load.
,2016-08-25 21:48:22.714 ThaliTest[991:1873636] Finished load of: file:///var/mobile/Containers/Bundle/Application/B89BE5C2-869B-4205-AC7C-91176F5B2E73/ThaliTest.app/www/index.html
,2016-08-25 21:48:22.934 ThaliTest[991:1873636] JXcore Cordova plugin initializing
,2016-08-25 21:48:22.934 ThaliTest[991:1873870] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  5
Number of passed tests:  5
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.006796956062316895
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
