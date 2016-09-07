#### Test 82914073126c10a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073126c10a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B7125EEE-AFFE-4682-BC95-4254B0D49985/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B7125EEE-AFFE-4682-BC95-4254B0D49985/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073126c10a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073126c10a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C15FA491-8A33-42C1-899A-7EBACF8BDD45/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55554"
,(lldb)     command script import "/tmp/B7125EEE-AFFE-4682-BC95-4254B0D49985/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-07 15:28:18.891 ThaliTest[1398:2317694] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CCB3302D-6F46-4B54-B157-86F17F1FE190/Library/Cookies/Cookies.binarycookies
,2016-09-07 15:28:19.362 ThaliTest[1398:2317694] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 15:28:19.364 ThaliTest[1398:2317694] Multi-tasking -> Device: YES, App: YES
,2016-09-07 15:28:19.386 ThaliTest[1398:2317694] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 15:28:21.712 ThaliTest[1398:2317694] Using UIWebView
,2016-09-07 15:28:21.720 ThaliTest[1398:2317694] [CDVTimer][handleopenurl] 1.594961ms
,2016-09-07 15:28:21.728 ThaliTest[1398:2317694] [CDVTimer][intentandnavigationfilter] 7.318020ms
2016-09-07 15:28:21.729 ThaliTest[1398:2317694] [CDVTimer][gesturehandler] 0.340998ms
2016-09-07 15:28:21.730 ThaliTest[1398:2317694] [CDVTimer][TotalPluginStartup] 11.421025ms
,2016-09-07 15:28:28.984 ThaliTest[1398:2317694] Resetting plugins due to page load.
,2016-09-07 15:28:32.909 ThaliTest[1398:2317694] Finished load of: file:///var/mobile/Containers/Bundle/Application/C15FA491-8A33-42C1-899A-7EBACF8BDD45/ThaliTest.app/www/index.html
,2016-09-07 15:28:33.135 ThaliTest[1398:2317694] JXcore Cordova plugin initializing
,2016-09-07 15:28:33.136 ThaliTest[1398:2317964] JXcore instance initializing
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
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  38
Number of passed tests:  38
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  12.1847739815712
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
