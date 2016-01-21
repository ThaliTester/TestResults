#### Test 56672827b6f75d5_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56672827b6f75d5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A0761469-86ED-48B1-AC8B-B0DE8AEABE31/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A0761469-86ED-48B1-AC8B-B0DE8AEABE31/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56672827b6f75d5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56672827b6f75d5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/10A664B8-17FC-48A3-A49F-D49EEBA70E54/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59733"
,(lldb)     command script import "/tmp/A0761469-86ED-48B1-AC8B-B0DE8AEABE31/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 17:42:49.450 ThaliTest[2508:5414791] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BC017F2B-9980-4995-8CA1-A765D00070E8/Library/Cookies/Cookies.binarycookies
,2016-01-21 17:42:49.699 ThaliTest[2508:5414791] Apache Cordova native platform version 3.9.2 is starting.
2016-01-21 17:42:49.699 ThaliTest[2508:5414791] Multi-tasking -> Device: YES, App: YES
,2016-01-21 17:42:49.706 ThaliTest[2508:5414791] Unlimited access to network resources
,2016-01-21 17:42:49.711 ThaliTest[2508:5414791] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 17:42:53.953 ThaliTest[2508:5414791] Resetting plugins due to page load.
,2016-01-21 17:42:55.478 ThaliTest[2508:5414791] Finished load of: file:///var/mobile/Containers/Bundle/Application/10A664B8-17FC-48A3-A49F-D49EEBA70E54/ThaliTest.app/www/index.html
,2016-01-21 17:42:55.618 ThaliTest[2508:5414791] JXcore Cordova plugin initializing
2016-01-21 17:42:55.618 ThaliTest[2508:5414968] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10A664B8-17FC-48A3-A49F-D49EEBA70E54/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10A664B8-17FC-48A3-A49F-D49EEBA70E54/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10A664B8-17FC-48A3-A49F-D49EEBA70E54/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10A664B8-17FC-48A3-A49F-D49EEBA70E54/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10A664B8-17FC-48A3-A49F-D49EEBA70E54/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10A664B8-17FC-48A3-A49F-D49EEBA70E54/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10A664B8-17FC-48A3-A49F-D49EEBA70E54/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10A664B8-17FC-48A3-A49F-D49EEBA70E54/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
