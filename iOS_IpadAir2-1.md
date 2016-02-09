#### Test 587523534d3a10e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/587523534d3a10e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/5500E254-BEE4-471E-8E22-FF7187D234A7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5500E254-BEE4-471E-8E22-FF7187D234A7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/587523534d3a10e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/587523534d3a10e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53415"
,(lldb)     command script import "/tmp/5500E254-BEE4-471E-8E22-FF7187D234A7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 15:48:42.480 ThaliTest[1125:1773128] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DC70BAF4-D162-4E03-B9D1-718DDEEEEEF7/Library/Cookies/Cookies.binarycookies
,2016-02-09 15:48:42.909 ThaliTest[1125:1773128] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 15:48:42.910 ThaliTest[1125:1773128] Multi-tasking -> Device: YES, App: YES
,2016-02-09 15:48:42.919 ThaliTest[1125:1773128] Unlimited access to network resources
,2016-02-09 15:48:42.927 ThaliTest[1125:1773128] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 15:48:52.576 ThaliTest[1125:1773128] Resetting plugins due to page load.
,2016-02-09 15:48:56.172 ThaliTest[1125:1773128] Finished load of: file:///var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app/www/index.html
,2016-02-09 15:48:56.328 ThaliTest[1125:1773128] JXcore Cordova plugin initializing
2016-02-09 15:48:56.328 ThaliTest[1125:1773392] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/373EC980-593F-49AF-A3DB-1F88EA44EDA0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded


```
