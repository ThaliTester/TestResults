#### Test 75789268a22e351_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268a22e351/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/29A064E1-FED1-4F9C-A0FF-ECF9C99E8D12/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/29A064E1-FED1-4F9C-A0FF-ECF9C99E8D12/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268a22e351/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268a22e351/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/81516319-203F-444A-82F0-BEBAABB575C2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51341"
,(lldb)     command script import "/tmp/29A064E1-FED1-4F9C-A0FF-ECF9C99E8D12/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-07 15:09:08.326 ThaliTest[3823:13922811] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0410A502-4AC7-46D7-A4E8-358CA763F2F8/Library/Cookies/Cookies.binarycookies
,2016-07-07 15:09:08.552 ThaliTest[3823:13922811] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-07 15:09:08.553 ThaliTest[3823:13922811] Multi-tasking -> Device: YES, App: YES
,2016-07-07 15:09:08.566 ThaliTest[3823:13922811] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-07 15:09:09.400 ThaliTest[3823:13922811] Using UIWebView
,2016-07-07 15:09:09.403 ThaliTest[3823:13922811] [CDVTimer][handleopenurl] 0.120997ms
,2016-07-07 15:09:09.405 ThaliTest[3823:13922811] [CDVTimer][intentandnavigationfilter] 1.821995ms
2016-07-07 15:09:09.405 ThaliTest[3823:13922811] [CDVTimer][gesturehandler] 0.086010ms
2016-07-07 15:09:09.405 ThaliTest[3823:13922811] [CDVTimer][TotalPlug,inStartup] 2.457976ms
,2016-07-07 15:09:12.600 ThaliTest[3823:13922811] Resetting plugins due to page load.
,2016-07-07 15:09:14.045 ThaliTest[3823:13922811] Finished load of: file:///var/mobile/Containers/Bundle/Application/81516319-203F-444A-82F0-BEBAABB575C2/ThaliTest.app/www/index.html
,2016-07-07 15:09:14.182 ThaliTest[3823:13922811] JXcore Cordova plugin initializing
,2016-07-07 15:09:14.183 ThaliTest[3823:13922984] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,appEnteredForeground wasn't registered

```
