#### Test 5065027881383b1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027881383b1/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/43872E45-C3BB-4DCC-A00A-B5B1D1922CDC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/43872E45-C3BB-4DCC-A00A-B5B1D1922CDC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027881383b1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027881383b1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/72D7C3D0-5FF1-41EB-A013-AF185DD6F92A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53343"
,(lldb)     command script import "/tmp/43872E45-C3BB-4DCC-A00A-B5B1D1922CDC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 14:06:56.972 ThaliTest[725:565284] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E4ADF3A9-468F-4DF1-A937-02F002B03047/Library/Cookies/Cookies.binarycookies
,2015-12-10 14:06:56.987 ThaliTest[725:565284] <CATransformLayer: 0x16538df0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-10 14:06:56.988 ThaliTest[725:565284] <CATransformLayer: 0x1672e330> - changing property ma,sksToBounds in transform-only layer, will have no effect
2015-12-10 14:06:56.989 ThaliTest[725:565284] <CATransformLayer: 0x1672f490> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-10 14:06:57.282 ThaliTest[725:565284] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 14:06:57.283 ThaliTest[725:565284] Multi-tasking -> Device: YES, App: YES
,2015-12-10 14:06:57.290 ThaliTest[725:565284] Unlimited access to network resources
,2015-12-10 14:06:57.296 ThaliTest[725:565284] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 14:07:06.342 ThaliTest[725:565284] Resetting plugins due to page load.
,2015-12-10 14:07:09.410 ThaliTest[725:565284] Finished load of: file:///var/mobile/Containers/Bundle/Application/72D7C3D0-5FF1-41EB-A013-AF185DD6F92A/ThaliTest.app/www/index.html
,2015-12-10 14:07:09.551 ThaliTest[725:565284] JXcore Cordova plugin initializing
,2015-12-10 14:07:09.552 ThaliTest[725:565535] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-10 14:07:10.562 ThaliTest[725:565284] THREAD WARNING: ['JXcore'] took '82.278076' ms. Plugin should use a background thread.

```
