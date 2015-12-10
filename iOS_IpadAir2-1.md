#### Test 50650278b86327b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/4DEDE7EE-38A1-4F84-9919-C1F62B1DB1D9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4DEDE7EE-38A1-4F84-9919-C1F62B1DB1D9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/124C2C1D-71AC-4391-8723-A36974B69B84/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53605"
,(lldb)     command script import "/tmp/4DEDE7EE-38A1-4F84-9919-C1F62B1DB1D9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 15:09:52.022 ThaliTest[747:573639] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0D9888D9-60BE-4E1B-A649-5E19DDD4C960/Library/Cookies/Cookies.binarycookies
,2015-12-10 15:09:52.036 ThaliTest[747:573639] <CATransformLayer: 0x16582ee0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-10 15:09:52.036 ThaliTest[747:573639] <CATransformLayer: 0x1666ff60> - changing property ma,sksToBounds in transform-only layer, will have no effect
2015-12-10 15:09:52.037 ThaliTest[747:573639] <CATransformLayer: 0x1656ef90> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-10 15:09:52.344 ThaliTest[747:573639] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 15:09:52.345 ThaliTest[747:573639] Multi-tasking -> Device: YES, App: YES
,2015-12-10 15:09:52.353 ThaliTest[747:573639] Unlimited access to network resources
,2015-12-10 15:09:52.360 ThaliTest[747:573639] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 15:10:01.405 ThaliTest[747:573639] Resetting plugins due to page load.
,2015-12-10 15:10:04.701 ThaliTest[747:573639] Finished load of: file:///var/mobile/Containers/Bundle/Application/124C2C1D-71AC-4391-8723-A36974B69B84/ThaliTest.app/www/index.html
,2015-12-10 15:10:04.844 ThaliTest[747:573639] JXcore Cordova plugin initializing
2015-12-10 15:10:04.845 ThaliTest[747:573888] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-10 15:10:05.864 ThaliTest[747:573639] THREAD WARNING: ['JXcore'] took '82.289307' ms. Plugin should use a background thread.
,Connected to the server!

```
