#### Test 83070177a758936_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/60BD2A62-77CD-402A-A06B-EBE50645B8D8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/60BD2A62-77CD-402A-A06B-EBE50645B8D8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BD7D62BD-66B1-41C6-933D-C686C263E958/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56619"
,(lldb)     command script import "/tmp/60BD2A62-77CD-402A-A06B-EBE50645B8D8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 13:48:33.177 ThaliTest[2103:4141472] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1EDE785A-7693-45CE-B33C-28165A72073E/Library/Cookies/Cookies.binarycookies
,2016-09-12 13:48:33.420 ThaliTest[2103:4141472] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 13:48:33.420 ThaliTest[2103:4141472] Multi-tasking -> Device: YES, App: YES
,2016-09-12 13:48:33.434 ThaliTest[2103:4141472] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 13:48:34.253 ThaliTest[2103:4141472] Using UIWebView
,2016-09-12 13:48:34.255 ThaliTest[2103:4141472] [CDVTimer][handleopenurl] 0.102997ms
,2016-09-12 13:48:34.257 ThaliTest[2103:4141472] [CDVTimer][intentandnavigationfilter] 1.835048ms
2016-09-12 13:48:34.257 ThaliTest[2103:4141472] [CDVTimer][gesturehandler] 0.091016ms
2016-09-12 13:48:34.257 ThaliTest[2103:4141472] [CDVTimer][TotalPluginS,tartup] 2.449036ms
,2016-09-12 13:48:37.385 ThaliTest[2103:4141472] Resetting plugins due to page load.
,2016-09-12 13:48:38.825 ThaliTest[2103:4141472] Finished load of: file:///var/mobile/Containers/Bundle/Application/BD7D62BD-66B1-41C6-933D-C686C263E958/ThaliTest.app/www/index.html
,2016-09-12 13:48:38.954 ThaliTest[2103:4141472] JXcore Cordova plugin initializing
,2016-09-12 13:48:38.955 ThaliTest[2103:4141662] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  16
Number of passed tests:  16
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  38.40275400876999
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
