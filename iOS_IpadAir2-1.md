#### Test 82728424d2195a9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82728424d2195a9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/CC5EC8DF-2757-4C1E-B712-925AEA573F4C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CC5EC8DF-2757-4C1E-B712-925AEA573F4C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82728424d2195a9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82728424d2195a9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ED7ACE7C-CBB2-43BF-8EDE-6608C115B1C6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63911"
,(lldb)     command script import "/tmp/CC5EC8DF-2757-4C1E-B712-925AEA573F4C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 20:51:53.331 ThaliTest[982:1867294] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0A5C608-C327-4CE4-9094-3924C1AABC77/Library/Cookies/Cookies.binarycookies
,2016-08-25 20:51:53.705 ThaliTest[982:1867294] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 20:51:53.706 ThaliTest[982:1867294] Multi-tasking -> Device: YES, App: YES
,2016-08-25 20:51:53.725 ThaliTest[982:1867294] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 20:51:55.797 ThaliTest[982:1867294] Using UIWebView
,2016-08-25 20:51:55.803 ThaliTest[982:1867294] [CDVTimer][handleopenurl] 0.581026ms
,2016-08-25 20:51:55.811 ThaliTest[982:1867294] [CDVTimer][intentandnavigationfilter] 6.922007ms
,2016-08-25 20:51:55.811 ThaliTest[982:1867294] [CDVTimer][gesturehandler] 0.346005ms
,2016-08-25 20:51:55.812 ThaliTest[982:1867294] [CDVTimer][TotalPluginStartup] 9.859979ms
,2016-08-25 20:52:02.408 ThaliTest[982:1867294] Resetting plugins due to page load.
,2016-08-25 20:52:06.315 ThaliTest[982:1867294] Finished load of: file:///var/mobile/Containers/Bundle/Application/ED7ACE7C-CBB2-43BF-8EDE-6608C115B1C6/ThaliTest.app/www/index.html
,2016-08-25 20:52:06.554 ThaliTest[982:1867294] JXcore Cordova plugin initializing
,2016-08-25 20:52:06.555 ThaliTest[982:1867547] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were not executed*
,Number of passed tests:  undefined
,Total number of executed tests:  undefined
,Number of failed tests:  undefined
,Number of ignored tests:  undefined
Total duration:  undefined
,Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
