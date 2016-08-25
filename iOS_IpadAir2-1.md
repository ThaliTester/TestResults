#### Test 7989656923d4b17_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7989656923d4b17/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4E09D012-B770-4E4C-890F-B5DF452647EC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4E09D012-B770-4E4C-890F-B5DF452647EC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7989656923d4b17/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7989656923d4b17/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2AB68681-0982-4729-B310-666DB5D3A7DC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56735"
,(lldb)     command script import "/tmp/4E09D012-B770-4E4C-890F-B5DF452647EC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 16:34:31.856 ThaliTest[953:1838567] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E3ECCCEE-1050-47B7-954A-71689F42412F/Library/Cookies/Cookies.binarycookies
,2016-08-25 16:34:32.250 ThaliTest[953:1838567] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 16:34:32.251 ThaliTest[953:1838567] Multi-tasking -> Device: YES, App: YES
,2016-08-25 16:34:32.271 ThaliTest[953:1838567] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 16:34:34.150 ThaliTest[953:1838567] Using UIWebView
,2016-08-25 16:34:34.157 ThaliTest[953:1838567] [CDVTimer][handleopenurl] 0.437021ms
,2016-08-25 16:34:34.164 ThaliTest[953:1838567] [CDVTimer][intentandnavigationfilter] 6.556034ms
,2016-08-25 16:34:34.165 ThaliTest[953:1838567] [CDVTimer][gesturehandler] 0.297964ms
,2016-08-25 16:34:34.165 ThaliTest[953:1838567] [CDVTimer][TotalPluginStartup] 9.057999ms
,2016-08-25 16:34:40.512 ThaliTest[953:1838567] Resetting plugins due to page load.
,2016-08-25 16:34:44.176 ThaliTest[953:1838567] Finished load of: file:///var/mobile/Containers/Bundle/Application/2AB68681-0982-4729-B310-666DB5D3A7DC/ThaliTest.app/www/index.html
,2016-08-25 16:34:44.393 ThaliTest[953:1838567] JXcore Cordova plugin initializing
,2016-08-25 16:34:44.393 ThaliTest[953:1838834] JXcore instance initializing
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
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
