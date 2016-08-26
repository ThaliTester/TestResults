#### Test 82728424c383411_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82728424c383411/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/61006ACD-2A40-450C-B8DC-AD37DD5D705F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/61006ACD-2A40-450C-B8DC-AD37DD5D705F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82728424c383411/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82728424c383411/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C85E06F2-5E2E-40ED-A51A-A49F9E16C8F3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52844"
,(lldb)     command script import "/tmp/61006ACD-2A40-450C-B8DC-AD37DD5D705F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 10:50:38.774 ThaliTest[1025:1953523] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/04ABCC00-62FD-4B8A-B5A5-B1E0F771D90E/Library/Cookies/Cookies.binarycookies
,2016-08-26 10:50:39.186 ThaliTest[1025:1953523] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 10:50:39.187 ThaliTest[1025:1953523] Multi-tasking -> Device: YES, App: YES
,2016-08-26 10:50:39.207 ThaliTest[1025:1953523] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 10:50:41.160 ThaliTest[1025:1953523] Using UIWebView
,2016-08-26 10:50:41.171 ThaliTest[1025:1953523] [CDVTimer][handleopenurl] 0.792980ms
,2016-08-26 10:50:41.179 ThaliTest[1025:1953523] [CDVTimer][intentandnavigationfilter] 6.704032ms
,2016-08-26 10:50:41.180 ThaliTest[1025:1953523] [CDVTimer][gesturehandler] 0.316024ms
,2016-08-26 10:50:41.180 ThaliTest[1025:1953523] [CDVTimer][TotalPluginStartup] 10.816991ms
,2016-08-26 10:50:48.213 ThaliTest[1025:1953523] Resetting plugins due to page load.
,2016-08-26 10:50:51.857 ThaliTest[1025:1953523] Finished load of: file:///var/mobile/Containers/Bundle/Application/C85E06F2-5E2E-40ED-A51A-A49F9E16C8F3/ThaliTest.app/www/index.html
,2016-08-26 10:50:52.071 ThaliTest[1025:1953523] JXcore Cordova plugin initializing
,2016-08-26 10:50:52.072 ThaliTest[1025:1953786] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  5
Number of passed tests:  5
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.006655991077423096
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
