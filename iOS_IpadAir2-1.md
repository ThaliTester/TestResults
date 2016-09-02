#### Test 832688936f8f85f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832688936f8f85f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/4B7B11FC-CDA9-48B0-B46C-D455934817BB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4B7B11FC-CDA9-48B0-B46C-D455934817BB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/832688936f8f85f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832688936f8f85f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0CE61747-AEBC-40F5-860B-4B70D8B1CFF2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53313"
,(lldb)     command script import "/tmp/4B7B11FC-CDA9-48B0-B46C-D455934817BB/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 11:34:12.616 ThaliTest[1583:2865250] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8670628F-2C96-4EDA-8786-36D2F9C28846/Library/Cookies/Cookies.binarycookies
,2016-09-02 11:34:12.971 ThaliTest[1583:2865250] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 11:34:12.972 ThaliTest[1583:2865250] Multi-tasking -> Device: YES, App: YES
,2016-09-02 11:34:12.990 ThaliTest[1583:2865250] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 11:34:15.010 ThaliTest[1583:2865250] Using UIWebView
,2016-09-02 11:34:15.017 ThaliTest[1583:2865250] [CDVTimer][handleopenurl] 0.421047ms
,2016-09-02 11:34:15.024 ThaliTest[1583:2865250] [CDVTimer][intentandnavigationfilter] 6.698966ms
,2016-09-02 11:34:15.025 ThaliTest[1583:2865250] [CDVTimer][gesturehandler] 0.312030ms
,2016-09-02 11:34:15.025 ThaliTest[1583:2865250] [CDVTimer][TotalPluginStartup] 9.216964ms
,2016-09-02 11:34:22.243 ThaliTest[1583:2865250] Resetting plugins due to page load.
,2016-09-02 11:34:26.316 ThaliTest[1583:2865250] Finished load of: file:///var/mobile/Containers/Bundle/Application/0CE61747-AEBC-40F5-860B-4B70D8B1CFF2/ThaliTest.app/www/index.html
,2016-09-02 11:34:26.534 ThaliTest[1583:2865250] JXcore Cordova plugin initializing
,2016-09-02 11:34:26.535 ThaliTest[1583:2865509] JXcore instance initializing
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
Total number of executed tests:  25
Number of passed tests:  25
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  43.20557200908661
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
