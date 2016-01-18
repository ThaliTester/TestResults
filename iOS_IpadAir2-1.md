#### Test 5615109370bee58_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5615109370bee58/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1C1FBA48-9DCB-48AE-BB41-CC3D3BE10774/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1C1FBA48-9DCB-48AE-BB41-CC3D3BE10774/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5615109370bee58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5615109370bee58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0923E89B-8187-410B-9B72-A150B2BA0814/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57912"
,(lldb)     command script import "/tmp/1C1FBA48-9DCB-48AE-BB41-CC3D3BE10774/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-18 15:14:43.784 ThaliTest[2276:4903857] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2BBA5167-DFE6-492F-B26F-5AB6ADBCED8E/Library/Cookies/Cookies.binarycookies
,2016-01-18 15:14:44.014 ThaliTest[2276:4903857] Apache Cordova native platform version 3.9.2 is starting.
2016-01-18 15:14:44.015 ThaliTest[2276:4903857] Multi-tasking -> Device: YES, App: YES
,2016-01-18 15:14:44.021 ThaliTest[2276:4903857] Unlimited access to network resources
,2016-01-18 15:14:44.026 ThaliTest[2276:4903857] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-18 15:14:48.087 ThaliTest[2276:4903857] Resetting plugins due to page load.
,2016-01-18 15:14:49.582 ThaliTest[2276:4903857] Finished load of: file:///var/mobile/Containers/Bundle/Application/0923E89B-8187-410B-9B72-A150B2BA0814/ThaliTest.app/www/index.html
,2016-01-18 15:14:49.723 ThaliTest[2276:4903857] JXcore Cordova plugin initializing
,2016-01-18 15:14:49.724 ThaliTest[2276:4904014] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0923E89B-8187-410B-9B72-A150B2BA0814/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0923E89B-8187-410B-9B72-A150B2BA0814/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0923E89B-8187-410B-9B72-A150B2BA0814/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0923E89B-8187-410B-9B72-A150B2BA0814/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0923E89B-8187-410B-9B72-A150B2BA0814/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0923E89B-8187-410B-9B72-A150B2BA0814/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0923E89B-8187-410B-9B72-A150B2BA0814/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test app app.js loaded
,TAP version 13
,# setup
,# multiplex can send data
,# teardown
,ok 1 String should be length:200
,# setup
,# basic
,# teardown
,ok 2 sane
,# setup
,# another
,# teardown
,ok 3 sane
,# setup
,# successfully create a new pkcs12 file and return hash value
,# teardown
,ok 4 should be equal
,ok 5 null
,ok 6 (unnamed assert)
,ok 7 should be equal
,ok 8 should not throw
,# setup
,# successfully read a previous pkcs12 file and return hash value
,# teardown
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
ok 11 should not throw
,ok 12 should be equal
ok 13 should be equal
,# setup
,# failed to extract public key because of corrupt pkcs12 file
,# teardown
,ok 14 should be equal
,# setup
,# failed to get mobile documents path
,# teardown
,ok 15 should be equal
,# setup
,# #init should register the peerAvailabilityChanged event
,# teardown
,ok 16 should be equal
,ok 17 should be equal
ok 18 should be equal
,# setup
,# #init should register the networkChanged event
,# teardown
,ok 19 should be equal
,# setup
,# #startBroadcasting should throw on null device name
,# teardown
,ok 20 should throw
,# setup
,# #startBroadcasting should throw on empty string device name
,# teardown
,ok 21 should throw
,# setup
,# #startBroadcasting should throw on non-number port
,# teardown
,ok 22 should throw
,# setup
,# #startBroadcasting should throw on NaN port
,# teardown
,ok 23 should throw
,# setup
,# #startBroadcasting should throw on negative port
,# teardown
,ok 24 should throw
,# setup
,# #startBroadcasting should throw on too large port
,# teardown
,ok 25 should throw
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,ok 26 should be equal
,ok 27 should be equal
ok 28 should be equal
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
,ok 30 should be equal
ok 31 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,ok 32 should be equal
ok 33 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
,ok 35 should be equal
,# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
,ok 37 should be equal
,ok 38 should be equal
,# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
ok 40 should be equal
,# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
,ok 42 should be equal
,# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-18 15:20:03.791 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:03.796 ThaliTest[2276:4904014] server: starting 1453126803791.2276.i91I3Q==
2016-01-18 15:20:03.796 ThaliTest[2276:4904014] multipeer session: start timer: 0x17c11fd0
,2016-01-18 15:20:03.797 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126803791.2276
2016-01-18 15:20:03.797 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2016-01-18 15:20:03.798 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:03.798 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:03.798 ThaliTest[2276:4904014] multipeer session: stop timer
2016-01-18 15:20:03.798 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-18 15:20:03.799 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:03.801 ThaliTest[2276:4904014] server: starting 1453126803799.2276.NRKAyg==
2016-01-18 15:20:03.801 ThaliTest[2276:4904014] multipeer session: start timer: 0x17d0d6a0
2016-01-18 15:20:03.801 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126803799.2276
2016-01-18 15:20:03.801 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-18 15:20:03.802 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:03.803 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:03.803 ThaliTest[2276:4904014] multipeer session: stop timer
2016-01-18 15:20:03.803 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 48 Should, be able to call stopBroadcasting without error
2016-01-18 15:20:03.803 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:03.805 ThaliTest[2276:4904014] server: starting 1453126803803.2276.4RF0pA==
2016-01-18 15:20:03.806 ThaliTest[2276:4904014] multipeer session: start timer: 0x17c14910
2016-01-18 15:20:03.806 ThaliTest[2276:4904014] THEMultipeerSession in,itialized peer 1453126803803.2276
2016-01-18 15:20:03.806 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-18 15:20:03.806 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:03.807 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:03.807 ThaliTest[2276:4904014] multipeer session: stop timer
2016-01-18 15:20:03.807 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-18 15:20:03.807 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:03.809 ThaliTest[2276:4904014] server: starting 1453126803807.2276.RllKqQ==
2016-01-18 15:20:03.809 ThaliTest[2276:4904014] multipeer session: start timer: 0x17d1deb0
2016-01-18 15:20:03.809 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126803807.2276
,2016-01-18 15:20:03.809 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-18 15:20:03.811 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:03.811 ThaliTest[22,76:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:03.811 ThaliTest[2276:4904014] multipeer session: stop timer
2016-01-18 15:20:03.811 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-18 15:20:03.812 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:03.815 ThaliTest[2276:4904014] server: starting 1453126803812.2276.XfOHNQ==
2016-01-18 15:20:03.816 ThaliTest[2276:4904014] multipeer session: start timer: 0x17c20b60
2016-01-18 15:20:03.816 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126803812.2276
2016-01-18 15:20:03.816 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-18 15:20:03.817 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:03.817 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:03.817 ThaliTest[2276:4904014] multipeer session: stop timer
,2016-01-18 15:20:03.819 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
2016-01-18 15:20:03.820 ThaliTest[2276:4904014] jxcore: startBroadcasting
2016-01-18 15:20:03.822 ThaliTest[227,6:4904014] server: starting 1453126803820.2276.YJl6zw==
,2016-01-18 15:20:03.823 ThaliTest[2276:4904014] multipeer session: start timer: 0x17d0b110
2016-01-18 15:20:03.823 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126803820.2276
2016-01-18 15:20:03.823 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-18 15:20:03.824 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:03.824 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:03.824 ThaliTest[2276:4904014] multipeer session: stop timer
2016-01-18 15:20:03.824 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
,2016-01-18 15:20:03.825 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:03.827 ThaliTest[2276:4904014] server: starting 1453126803825.2276.hCwitg==
2016-01-18 15:20:03.827 ThaliTest[2276:4904014] multipeer session: start timer: 0x17d11820
2016-01-18 15:20:03.828 ThaliTest[2276:4904014] THEMultipeerSession in,itialized peer 1453126803825.2276
2016-01-18 15:20:03.828 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2016-01-18 15:20:03.829 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:03.829 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
,2016-01-18 15:20:03.829 ThaliTest[2276:4904014] multipeer session: stop timer
,2016-01-18 15:20:03.830 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
,2016-01-18 15:20:03.832 ThaliTest[2276:4904014] jxcore: startBroadcasting
2016-01-18 15:20:03.833 ThaliTest[2276:4904014] server: starting 1453126803832.2276.bIJimw==
2016-01-18 15:20:03.833 ThaliTest[2276:4904014] multipeer session: start timer: 0x17d1f9a0
2016-01-18 15:20:03.833 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126803832.2276
2016-01-18 15:20:03.834 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
2016-01-18 15:20:03.835 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:03.835 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:03.835 ThaliTest[227,6:4904014] multipeer session: stop timer
2016-01-18 15:20:03.835 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2016-01-18 15:20:03.836 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:03.839 ThaliTest[2276:4904014] server: starting 1453126803836.2276.Pp7x7Q==
2016-01-18 15:20:03.839 ThaliTest[2276:4904014] multipeer session: start timer: 0x17e78050
2016-01-18 15:20:03.839 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126803836.2276
2016-01-18 15:20:03.839 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
2016-01-18 15:20:03.840 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:03.840 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:03.840 ThaliTest[227,6:4904014] multipeer session: stop timer
2016-01-18 15:20:03.841 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 62 Should be able to call stopBroadcasting without error
,2016-01-18 15:20:03.841 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:03.844 ThaliTest[2276:4904014] server: starting 1453126803841.2276.2y2fSw==
2016-01-18 15:20:03.844 ThaliTest[2276:4904014] multipeer session: start timer: 0x17c1d540
2016-01-18 15:20:03.844 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126803841.2276
2016-01-18 15:20:03.844 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
2016-01-18 15:20:03.845 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:03.845 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:03.845 ThaliTest[2276:4904014] multipeer session: stop timer
2016-01-18 15:20:03.845 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 64 Should, be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-18 15:20:04.246 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:04.247 ThaliTest[2276:4904014] server: starting 1453126804246.2276.QxNoyA==
2016-01-18 15:20:04.247 ThaliTest[2276:4904014] multipeer session: start timer: 0x17c2c2e0
2016-01-18 15:20:04.247 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126804246.2276
2016-01-18 15:20:04.247 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-18 15:20:04.248 ThaliTest[2276:4904014] jxcore: startBroadcasting
2016-01-18 15:20:04.248 ThaliTest[2276:4904014] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-18 15:20:04.249 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:04.249 ThaliTest[2276:4904014] THEMult,ipeerSession stopping peer
2016-01-18 15:20:04.249 ThaliTest[2276:4904014] multipeer session: stop timer
2016-01-18 15:20:04.249 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-18 15:20:07.265 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:07.267 ThaliTest[2276:4904014] server: starting 1453126807265.2276.3xOT/Q==
,2016-01-18 15:20:07.267 ThaliTest[2276:4904014] multipeer session: start timer: 0x17d20e50
2016-01-18 15:20:07.267 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126807265.2276
2016-01-18 15:20:07.267 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2016-01-18 15:20:07.268 ThaliTest[2276:4904014] jxcore: connect foobar
2016-01-18 15:20:07.268 ThaliTest[2276:4904014] client: unknown peer foobar
2016-01-18 15:20:07.268 ThaliTest[2276:4904014] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2016-01-18 15:20:07.269 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:07.269 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:07.269 ThaliTest[2276:4904014] multipeer s,ession: stop timer
,2016-01-18 15:20:07.270 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-18 15:20:07.471 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:07.472 ThaliTest[2276:4904014] server: starting 1453126807470.2276.QnWsUg==
,2016-01-18 15:20:07.472 ThaliTest[2276:4904014] multipeer session: start timer: 0x17d2fed0
2016-01-18 15:20:07.472 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126807470.2276
,2016-01-18 15:20:07.473 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-18 15:20:07.474 ThaliTest[2276:4904014] jxcore: disconnect
2016-01-18 15:20:07.474 ThaliTest[2276:4904014] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2016-01-18 15:20:07.475 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:07.475 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:07.475 ThaliTest[2276:4904014] multipeer session: stop timer
,2016-01-18 15:20:07.475 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-18 15:20:07.908 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:07.909 ThaliTest[2276:4904014] server: starting 1453126807908.2276.hk1ulw==
,2016-01-18 15:20:07.910 ThaliTest[2276:4904014] multipeer session: start timer: 0x17c355f0
2016-01-18 15:20:07.910 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126807908.2276
2016-01-18 15:20:07.910 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2016-01-18 15:20:09.114 ThaliTest[2276:4903857] client: found peer: 1453126805701.2188.JqByZA==
,2016-01-18 15:20:09.115 ThaliTest[2276:4904014] jxcore: connect 1453126805701.2188.JqByZA==
2016-01-18 15:20:09.115 ThaliTest[2276:4904014] client session: connect
2016-01-18 15:20:09.115 ThaliTest[2276:4904014] client session: stateChange:0->1 1453126805701.2188.JqByZA==
,2016-01-18 15:20:09.313 ThaliTest[2276:4903857] multipeer session: reset timer
2016-01-18 15:20:09.313 ThaliTest[2276:4903857] multipeer session: stop timer
2016-01-18 15:20:09.313 ThaliTest[2276:4903857] multipeer session: start timer: 0x17c355f0
2016-01-18 15:20:09.313 ThaliTest[2276:4903857] server session: connect
2016-01-18 15:20:09.313 ThaliTest[2276:4903857] server session: stateChange:0->1 1453126805701.2188
2016-01-18 15:20:09.315 ThaliTest[2276:4903857] server: accepting invitation 1453126805701.2188
,2016-01-18 15:20:13.435 ThaliTest[2276:4904561] client session: connected
2016-01-18 15:20:13.436 ThaliTest[2276:4904561] client session: stateChange:1->2 1453126805701.2188.JqByZA==
2016-01-18 15:20:13.435 ThaliTest[2276:4904581] server session: connected
2016-01-18 15:20:13.436 ThaliTest[2276:4904581] server session: stateChange:1->2 1453126805701.2188
,2016-01-18 15:20:13.439 ThaliTest[2276:4904561] client session: fireConnectCallback: 1453126805701.2188.JqByZA==
2016-01-18 15:20:13.439 ThaliTest[2276:4904561] jxcore: connect: success
2016-01-18 15:20:13.439 ThaliTest[2276:4903857] server relay: socket disconnected
2016-01-18 15:20:13.440 ThaliTest[2276:4903857] server relay: 0x17d3a7f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-18 15:20:13.441 ThaliTest[2276:4904014] jxcore: disconnect
2016-01-18 15:20:13.441 ThaliTest[2276:4904014] client session: disconnectFromPeer: 1453126805701.2188.JqByZA==
2016-01-18 15:20:13.441 ThaliTest[2276:4904014] client session: disconnect
2016-01-18 15:20:13.441 ThaliTest[2276:4904014] client session: stateChange:2->0 1453126805701.2188.JqByZA==
,2016-01-18 15:20:13.499 ThaliTest[2276:4904624] server session: not connected 1453126805701.2188
2016-01-18 15:20:13.499 ThaliTest[2276:4904014] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-18 15:20:14.163 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:14.163 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:14.163 ThaliTest[2276:4904014] multipeer session: stop timer
2016-01-18 15:20:14.163 ThaliTest[2276:4904014] server session: disconnect
2016-01-18 15:20:14.164 ThaliTest[2276:4904014] server session: stateChange:2->0 1453126805701.2188
2016-01-18 15:20:14.164 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-18 15:20:15.788 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:15.790 ThaliTest[2276:4904014] server: starting 1453126815788.2276.TbYE7g==
2016-01-18 15:20:15.790 ThaliTest[2276:4904014] multipeer session: start timer: 0x15f08e10
2016-01-18 15:20:15.790 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126815788.2276
2016-01-18 15:20:15.790 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
,ok 78 Should be able to call startBroadcasting without error
,2016-01-18 15:20:17.035 ThaliTest[2276:4903857] client: found peer: 1453126813402.2188.j6gUNw==
2016-01-18 15:20:17.036 ThaliTest[2276:4904014] jxcore: connect 1453126813402.2188.j6gUNw==
2016-01-18 15:20:17.036 ThaliTest[2276:4904014] client session: connect
,2016-01-18 15:20:17.036 ThaliTest[2276:4904014] client session: stateChange:0->1 1453126813402.2188.j6gUNw==
,2016-01-18 15:20:17.171 ThaliTest[2276:4903857] multipeer session: reset timer
2016-01-18 15:20:17.171 ThaliTest[2276:4903857] multipeer session: stop timer
2016-01-18 15:20:17.171 ThaliTest[2276:4903857] multipeer session: start timer: 0x15f08e10
2016-,01-18 15:20:17.171 ThaliTest[2276:4903857] server session: connect
2016-01-18 15:20:17.171 ThaliTest[2276:4903857] server session: stateChange:0->1 1453126813402.2188
,2016-01-18 15:20:17.174 ThaliTest[2276:4903857] server: accepting invitation 1453126813402.2188
,2016-01-18 15:20:21.217 ThaliTest[2276:4904581] client session: connected
2016-01-18 15:20:21.217 ThaliTest[2276:4904581] client session: stateChange:1->2 1453126813402.2188.j6gUNw==
,2016-01-18 15:20:21.237 ThaliTest[2276:4904561] client session: fireConnectCallback: 1453126813402.2188.j6gUNw==
2016-01-18 15:20:21.237 ThaliTest[2276:4904561] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
2016-01-18 15:20:21.238 ThaliTest[2276:4904014] jxcore: connect 1453126813402.2188.j6gUNw==
,2016-01-18 15:20:21.238 ThaliTest[2276:4904014] client: already connect(ing/ed) to 1453126813402.2188.j6gUNw==
2016-01-18 15:20:21.239 ThaliTest[2276:4904014] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-18 15:20:21.240 ThaliTest[2276:4904014] jxcore: disconnect
2016-01-18 15:20:21.240 ThaliTest[2276:4904014] client session: disconnectFromPeer: 1453126813402.2188.j6gUNw==
2016-01-18 15:20:21.240 ThaliTest[2276:4904014] client session: disconnect
2016-01-18 15:20:21.240 ThaliTest[2276:4904014] client session: stateChange:2->0 1453126813402.2188.j6gUNw==
,2016-01-18 15:20:21.246 ThaliTest[2276:4904014] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 15:20:21.395 ThaliTest[2276:4904574] server session: connected
2016-01-18 15:20:21.395 ThaliTest[2276:4904574] server session: stateChange:1->2 1453126813402.2188
,2016-01-18 15:20:21.693 ThaliTest[2276:4904574] server session: not connected 1453126813402.2188
,2016-01-18 15:20:21.694 ThaliTest[2276:4903857] server relay: socket disconnected
2016-01-18 15:20:21.694 ThaliTest[2276:4903857] server relay: 0x17d451a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting
,2016-01-18 15:20:22.155 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:22.155 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:22.155 ThaliTest[2276:4904014] multipeer session: stop timer
2016-01-18 15:20:22.155 ThaliTest[2276:4904014] server session: disconnect
2016-01-18 15:20:22.155 ThaliTest[2276:4904014] server session: stateChange:2->0 1453126813402.2188
,2016-01-18 15:20:22.155 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-18 15:20:23.986 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:23.988 ThaliTest[2276:4904014] server: starting 1453126823986.2276.WdZ+jg==
2016-01-18 15:20:23.988 ThaliTest[2276:4904014] multipeer session: start timer: 0x17d3ee80
2016-01-18 15:20:23.988 ThaliTest[2276:4904014] THEMultipeerSession in,itialized peer 1453126823986.2276
2016-01-18 15:20:23.988 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-18 15:20:24.842 ThaliTest[2276:4903857] client: found peer: 1453126821387.2188.6r0KPA==
,2016-01-18 15:20:24.842 ThaliTest[2276:4904014] jxcore: connect 1453126821387.2188.6r0KPA==
2016-01-18 15:20:24.842 ThaliTest[2276:4904014] client session: connect
2016-01-18 15:20:24.843 ThaliTest[2276:4904014] client session: stateChange:0->1 1453126821387.2188.6r0KPA==
,2016-01-18 15:20:25.106 ThaliTest[2276:4903857] multipeer session: reset timer
2016-01-18 15:20:25.106 ThaliTest[2276:4903857] multipeer session: stop timer
2016-01-18 15:20:25.106 ThaliTest[2276:4903857] multipeer session: start timer: 0x17d3ee80
2016-01-18 15:20:25.106 ThaliTest[2276:4903857] server session: connect
2016-01-18 15:20:25.106 ThaliTest[2276:4903857] server session: stateChange:0->1 1453126821387.2188
2016-01-18 15:20:25.108 ThaliTest[2276:4903857] server: accepting invitation 1453126821387.2188
,2016-01-18 15:20:28.844 ThaliTest[2276:4904581] client session: connected
2016-01-18 15:20:28.845 ThaliTest[2276:4904581] client session: stateChange:1->2 1453126821387.2188.6r0KPA==
2016-01-18 15:20:28.846 ThaliTest[2276:4904583] client session: fireConnectCallback: 1453126821387.2188.6r0KPA==
2016-01-18 15:20:28.846 ThaliTest[2276:4904583] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
,2016-01-18 15:20:28.847 ThaliTest[2276:4904014] jxcore: disconnect
2016-01-18 15:20:28.848 ThaliTest[2276:4904014] client session: disconnectFromPeer: 1453126821387.2188.6r0KPA==
2016-01-18 15:20:28.848 ThaliTest[2276:4904014] client session: disconnect
2016-01-18 15:20:28.848 ThaliTest[2276:4904014] client session: stateChange:2->0 1453126821387.2188.6r0KPA==
,2016-01-18 15:20:28.908 ThaliTest[2276:4904014] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2016-01-18 15:20:28.909 ThaliTest[2276:4904014] jxcore: disconnect
,2016-01-18 15:20:28.909 ThaliTest[2276:4904014] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 15:20:29.172 ThaliTest[2276:4904581] server session: connected
2016-01-18 15:20:29.172 ThaliTest[2276:4904581] server session: stateChange:1->2 1453126821387.2188
,2016-01-18 15:20:29.175 ThaliTest[2276:4903857] server relay: socket disconnected
,2016-01-18 15:20:29.175 ThaliTest[2276:4903857] server relay: 0x15f1e9e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 15:20:29.224 ThaliTest[2276:4904624] server session: not connected 1453126821387.2188
,calling stopBroadcasting
,2016-01-18 15:20:29.430 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:29.430 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:29.430 ThaliTest[2276:4904014] multipeer session: stop timer
,2016-01-18 15:20:29.430 ThaliTest[2276:4904014] server session: disconnect
2016-01-18 15:20:29.430 ThaliTest[2276:4904014] server session: stateChange:2->0 1453126821387.2188
,2016-01-18 15:20:29.432 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 53862
,2016-01-18 15:20:29.952 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:29.953 ThaliTest[2276:4904014] server: starting 1453126829951.2276.pN9r8g==
2016-01-18 15:20:29.953 ThaliTest[2276:4904014] multipeer session: start timer: 0x17c462a0
2016-01-18 15:20:29.953 ThaliTest[2276:4904014] THEMultipeerSession initialized peer 1453126829951.2276
,2016-01-18 15:20:29.954 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,2016-01-18 15:20:31.168 ThaliTest[2276:4903857] client: found peer: 1453126827901.2188.Ro391g==
2016-01-18 15:20:31.168 ThaliTest[2276:4904014] jxcore: connect 1453126827901.2188.Ro391g==
2016-01-18 15:20:31.168 ThaliTest[2276:4904014] client session: connect
2016-01-18 15:20:31.168 ThaliTest[2276:4904014] client session: stateChange:0->1 1453126827901.2188.Ro391g==
,2016-01-18 15:20:31.255 ThaliTest[2276:4903857] multipeer session: reset timer
2016-01-18 15:20:31.255 ThaliTest[2276:4903857] multipeer session: stop timer
2016-01-18 15:20:31.255 ThaliTest[2276:4903857] multipeer session: start timer: 0x17c462a0
2016-01-18 15:20:31.255 ThaliTest[2276:4903857] server session: connect
2016-01-18 15:20:31.255 ThaliTest[2276:4903857] server session: stateChange:0->1 1453126827901.2188
,2016-01-18 15:20:31.259 ThaliTest[2276:4903857] server: accepting invitation 1453126827901.2188
,2016-01-18 15:20:35.385 ThaliTest[2276:4904561] client session: connected
2016-01-18 15:20:35.386 ThaliTest[2276:4904561] client session: stateChange:1->2 1453126827901.2188.Ro391g==
,2016-01-18 15:20:35.387 ThaliTest[2276:4904561] server session: connected
2016-01-18 15:20:35.387 ThaliTest[2276:4904561] server session: stateChange:1->2 1453126827901.2188
,2016-01-18 15:20:35.452 ThaliTest[2276:4904581] client session: fireConnectCallback: 1453126827901.2188.Ro391g==
2016-01-18 15:20:35.452 ThaliTest[2276:4904581] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
,2016-01-18 15:20:35.456 ThaliTest[2276:4903857] client: relay established
2016-01-18 15:20:35.456 ThaliTest[2276:4903857] client: new accepted socket: 0x17c55d00
,2016-01-18 15:20:35.457 ThaliTest[2276:4903857] server relay: connected (to port: 53862)
,data in 1095
,data in 2190
,data in 9855
,data in 10950
,data in 12045
,data in 14235
,data in 15259
,data in 35040
,data in 41610
,data in 58035
,data in 62415
,data in 65700
,data in 70080
,data in 74460
,data in 77674
,data in 100740
,data in 118260
,data in 129210
,data in 131072
,ok 91 the test messages should be equal
,2016-01-18 15:20:36.641 ThaliTest[2276:4904014] jxcore: disconnect
2016-01-18 15:20:36.641 ThaliTest[2276:4904014] client session: disconnectFromPeer: 1453126827901.2188.Ro391g==
,2016-01-18 15:20:36.641 ThaliTest[2276:4904014] client session: disconnect
2016-01-18 15:20:36.641 ThaliTest[2276:4904014] client session: stateChange:2->0 1453126827901.2188.Ro391g==
,2016-01-18 15:20:36.644 ThaliTest[2276:4904014] jxcore: disconnect: success
,ok 92 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 15:20:36.701 ThaliTest[2276:4904583] server session: not connected 1453126827901.2188
,calling stopBroadcasting
,2016-01-18 15:20:36.767 ThaliTest[2276:4904014] jxcore: stopBroadcasting
,2016-01-18 15:20:36.767 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:20:36.767 ThaliTest[2276:4904014] multipeer session: stop timer
,2016-01-18 15:20:36.767 ThaliTest[2276:4904014] server session: disconnect
2016-01-18 15:20:36.767 ThaliTest[2276:4904014] server session: stateChange:2->0 1453126827901.2188
,2016-01-18 15:20:36.770 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,echo server started on port: 53868
,2016-01-18 15:20:37.889 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:37.890 ThaliTest[2276:4904014] server: starting 1453126837889.2276.dyZ4xw==
2016-01-18 15:20:37.890 ThaliTest[2276:4904014] multipeer session: start timer: 0x17c4a2f0
2016-01-18 15:20:37.891 ThaliTest[2276:4904014] THEMultipeerSession in,itialized peer 1453126837889.2276
2016-01-18 15:20:37.891 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-18 15:20:38.802 ThaliTest[2276:4903857] client: found peer: 1453126835660.2188.0MBBkA==
[{"peerIdentifier":"1453126835660.2188.0MBBkA==","peerName":"(null)","peerAvailable":true}]
,2016-01-18 15:20:38.804 ThaliTest[2276:4904014] jxcore: connect 1453126835660.2188.0MBBkA==
2016-01-18 15:20:38.804 ThaliTest[2276:4904014] client session: connect
2016-01-18 15:20:38.804 ThaliTest[2276:4904014] client session: stateChange:0->1 1453126835660.2188.0MBBkA==
,2016-01-18 15:20:39.129 ThaliTest[2276:4903857] multipeer session: reset timer
2016-01-18 15:20:39.129 ThaliTest[2276:4903857] multipeer session: stop timer
2016-01-18 15:20:39.130 ThaliTest[2276:4903857] multipeer session: start timer: 0x17c4a2f0
2016-01-18 15:20:39.130 ThaliTest[2276:4903857] server session: connect
2016-01-18 15:20:39.130 ThaliTest[2276:4903857] server session: stateChange:0->1 1453126835660.2188
,2016-01-18 15:20:39.132 ThaliTest[2276:4903857] server: accepting invitation 1453126835660.2188
,2016-01-18 15:20:43.248 ThaliTest[2276:4904583] client session: connected
2016-01-18 15:20:43.248 ThaliTest[2276:4904583] client session: stateChange:1->2 1453126835660.2188.0MBBkA==
,2016-01-18 15:20:43.257 ThaliTest[2276:4904574] client session: fireConnectCallback: 1453126835660.2188.0MBBkA==
2016-01-18 15:20:43.257 ThaliTest[2276:4904574] jxcore: connect: success
ok 94 Should be able to connect without error
ok 95 Port should be within range
,ok 96 First connect should succeed
,2016-01-18 15:20:43.267 ThaliTest[2276:4903857] client: relay established
2016-01-18 15:20:43.267 ThaliTest[2276:4903857] client: new accepted socket: 0x17c38770
,ok 97 the test messages should be equal
ok 98 First send should succeed
,2016-01-18 15:20:43.404 ThaliTest[2276:4903857] client: socket closed
2016-01-18 15:20:43.404 ThaliTest[2276:4903857] client relay: socket disconnected
2016-01-18 15:20:43.404 ThaliTest[2276:4903857] client relay: 0x17c38770 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-18 15:20:43.404 ThaliTest[2276:4903857] client session: socket closed: 1453126835660.2188.0MBBkA==
2016-01-18 15:20:43.404 ThaliTest[2276:4903857] client session: onLinkFailure: 1453126835660.2188.0MBBkA==
2016-01-18 15:20:43.404 ThaliTest[2276:4903857] client session: disconnect
2016-01-18 15:20:43.404 ThaliTest[2276:4903857] client session: stateChange:2->0 1453126835660.2188.0MBBkA==
,2016-01-18 15:20:43.462 ThaliTest[2276:4903857] client session: fireConnectionErrorEvent: 1453126835660.2188.0MBBkA==
2016-01-18 15:20:43.462 ThaliTest[2276:4904014] jxcore: connect 1453126835660.2188.0MBBkA==
2016-01-18 15:20:43.462 ThaliTest[2276:4904014] client session: connect
2016-01-18 15:20:43.463 ThaliTest[2276:4904014] client session: stateChange:0->1 1453126835660.2188.0MBBkA==
,2016-01-18 15:20:43.480 ThaliTest[2276:4904574] server session: connected
2016-01-18 15:20:43.480 ThaliTest[2276:4904574] server session: stateChange:1->2 1453126835660.2188
,2016-01-18 15:20:43.513 ThaliTest[2276:4903857] server relay: connected (to port: 53868)
,2016-01-18 15:20:43.607 ThaliTest[2276:4904561] server session: not connected 1453126835660.2188
,2016-01-18 15:20:43.665 ThaliTest[2276:4903857] multipeer session: reset timer
2016-01-18 15:20:43.665 ThaliTest[2276:4903857] multipeer session: stop timer
2016-01-18 15:20:43.666 ThaliTest[2276:4903857] multipeer session: start timer: 0x17c4a2f0
2016-01-18 15:20:43.666 ThaliTest[2276:4903857] server: disconnecting to refresh session (1453126835660.2188)
2016-01-18 15:20:43.666 ThaliTest[2276:4903857] server session: disconnect
2016-01-18 15:20:43.666 ThaliTest[2276:4903857] server session: stateChange:2->0 1453126835660.2188
,2016-01-18 15:20:43.935 ThaliTest[2276:4903857] server session: connect
2016-01-18 15:20:43.935 ThaliTest[2276:4903857] server session: stateChange:0->1 1453126835660.2188
,2016-01-18 15:20:43.937 ThaliTest[2276:4903857] server: accepting invitation 1453126835660.2188
,2016-01-18 15:20:48.152 ThaliTest[2276:4904561] client session: connected
2016-01-18 15:20:48.152 ThaliTest[2276:4904561] client session: stateChange:1->2 1453126835660.2188.0MBBkA==
,2016-01-18 15:20:48.163 ThaliTest[2276:4904561] client session: fireConnectCallback: 1453126835660.2188.0MBBkA==
2016-01-18 15:20:48.164 ThaliTest[2276:4904561] jxcore: connect: success
ok 99 Should be able to connect without error
ok 100 Port should be, within range
ok 101 Second connect should succeed
,2016-01-18 15:20:48.174 ThaliTest[2276:4903857] client: relay established
2016-01-18 15:20:48.174 ThaliTest[2276:4903857] client: new accepted socket: 0x17cfbbb0
,ok 102 the test messages should be equal
,ok 103 Second send should succeed
# setup
,2016-01-18 15:20:48.247 ThaliTest[2276:4903857] client: socket closed
2016-01-18 15:20:48.247 ThaliTest[2276:4903857] client relay: socket disconnected
2016-01-18 15:20:48.247 ThaliTest[2276:4903857] client relay: 0x17cfbbb0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-18 15:20:48.247 ThaliTest[2276:4903857] client session: socket closed: 1453126835660.2188.0MBBkA==
2016-01-18 ,15:20:48.247 ThaliTest[2276:4903857] client session: onLinkFailure: 1453126835660.2188.0MBBkA==
2016-01-18 15:20:48.247 ThaliTest[2276:4903857] client session: disconnect
2016-01-18 15:20:48.247 ThaliTest[2276:4903857] client session: stateChange:2->0 1453126835660.2188.0MBBkA==
,2016-01-18 15:20:48.251 ThaliTest[2276:4903857] client session: fireConnectionErrorEvent: 1453126835660.2188.0MBBkA==
,2016-01-18 15:20:48.276 ThaliTest[2276:4904583] server session: connected
,2016-01-18 15:20:48.276 ThaliTest[2276:4904583] server session: stateChange:1->2 1453126835660.2188
,2016-01-18 15:20:48.301 ThaliTest[2276:4903857] server relay: connected (to port: 53868)
,2016-01-18 15:20:48.472 ThaliTest[2276:4904581] server session: not connected 1453126835660.2188
,calling stopBroadcasting
2016-01-18 15:20:48.829 ThaliTest[2276:4904014] jxcore: stopBroadcasting
,2016-01-18 15:20:48.829 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
,2016-01-18 15:20:48.829 ThaliTest[2276:4904014] multipeer session: stop timer
,2016-01-18 15:20:48.830 ThaliTest[2276:4904014] server session: disconnect
2016-01-18 15:20:48.830 ThaliTest[2276:4904014] server session: stateChange:2->0 1453126835660.2188
,2016-01-18 15:20:48.831 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2BBA5167-DFE6-492F-B26F-5AB6ADBCED8E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 104 starting event should occur in right order
,2016-01-18 15:20:49.025 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:49.026 ThaliTest[2276:4904014] server: starting MTKjIr_Wsl-Cvu9WXlF3Sg.72g4Eg==
,2016-01-18 15:20:49.026 ThaliTest[2276:4904014] multipeer session: start timer: 0x17cf3380
2016-01-18 15:20:49.026 ThaliTest[2276:4904014] THEMultipeerSession initialized peer MTKjIr_Wsl-Cvu9WXlF3Sg
2016-01-18 15:20:49.027 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
,ok 105 started event should occur in right order
,Now in TRM stop
State of this._isStarted: true
ok 106 stopping event should occur in right order
About to call stopBroadcasting
,2016-01-18 15:20:49.028 ThaliTest[2276:4904014] jxcore: stopBroadcasting
,2016-01-18 15:20:49.028 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
,2016-01-18 15:20:49.029 ThaliTest[2276:4904014] multipeer session: stop timer
,2016-01-18 15:20:49.030 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,ok 107 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2BBA5167-DFE6-492F-B26F-5AB6ADBCED8E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-18 15:20:49.838 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:49.840 ThaliTest[2276:4904014] server: starting MTKjIr_Wsl-Cvu9WXlF3Sg.60q/pg==
2016-01-18 15:20:49.840 ThaliTest[2276:4904014] multipeer session: start timer: 0x15f44c20
2016-01-18 15:20:49.840 ThaliTest[2276:4904014] THEMultipeerSession initialized peer MTKjIr_Wsl-Cvu9WXlF3Sg
2016-01-18 15:20:49.840 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error
ok 109 deviceName should not be null
Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
2016-01-18 15:20:49.841 ThaliTest[2276:4904014] jxcore: stopBroadcasting
2016-01-18 15:20:49.842 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
,2016-01-18 15:20:49.842 ThaliTest[2276:4904014] multipeer session: stop timer
2016-01-18 15:20:49.844 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
# setup
,# ThaliReplicationManager replicates database
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2BBA5167-DFE6-492F-B26F-5AB6ADBCED8E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-18 15:20:52.426 ThaliTest[2276:4904014] jxcore: startBroadcasting
,2016-01-18 15:20:52.427 ThaliTest[2276:4904014] server: starting MTKjIr_Wsl-Cvu9WXlF3Sg.cC8YmQ==
2016-01-18 15:20:52.428 ThaliTest[2276:4904014] multipeer session: start timer: 0x17e21ee0
2016-01-18 15:20:52.428 ThaliTest[2276:4904014] THEMultipeerSession initialized peer MTKjIr_Wsl-Cvu9WXlF3Sg
2016-01-18 15:20:52.428 ThaliTest[2276:4904014] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error
,ok 111 deviceName should not be null
,2016-01-18 15:20:53.843 ThaliTest[2276:4903857] client: found peer: zMpmdU7aW1fPi1IEYKNtPg.tqUl5g==
,2016-01-18 15:20:56.487 ThaliTest[2276:4904014] jxcore: connect zMpmdU7aW1fPi1IEYKNtPg.tqUl5g==
2016-01-18 15:20:56.487 ThaliTest[2276:4904014] client session: connect
,2016-01-18 15:20:56.487 ThaliTest[2276:4904014] client session: stateChange:0->1 zMpmdU7aW1fPi1IEYKNtPg.tqUl5g==
,ok 112 Should be able to put doc without error
,ok 113 1st change of local doc should contain local id
,2016-01-18 15:20:58.432 ThaliTest[2276:4903857] multipeer session: reset timer
2016-01-18 15:20:58.432 ThaliTest[2276:4903857] multipeer session: stop timer
2016-01-18 15:20:58.432 ThaliTest[2276:4903857] multipeer session: start timer: 0x17e21ee0
2016-,01-18 15:20:58.432 ThaliTest[2276:4903857] server session: connect
2016-01-18 15:20:58.432 ThaliTest[2276:4903857] server session: stateChange:0->1 zMpmdU7aW1fPi1IEYKNtPg
,2016-01-18 15:20:58.434 ThaliTest[2276:4903857] server: accepting invitation zMpmdU7aW1fPi1IEYKNtPg
,2016-01-18 15:21:02.288 ThaliTest[2276:4904624] server session: connected
2016-01-18 15:21:02.288 ThaliTest[2276:4904624] server session: stateChange:1->2 zMpmdU7aW1fPi1IEYKNtPg
,2016-01-18 15:21:02.292 ThaliTest[2276:4904694] client session: connected
2016-01-18 15:21:02.292 ThaliTest[2276:4904694] client session: stateChange:1->2 zMpmdU7aW1fPi1IEYKNtPg.tqUl5g==
,2016-01-18 15:21:02.294 ThaliTest[2276:4903857] server relay: connected (to port: 53883)
,2016-01-18 15:21:02.297 ThaliTest[2276:4904561] client session: fireConnectCallback: zMpmdU7aW1fPi1IEYKNtPg.tqUl5g==
2016-01-18 15:21:02.297 ThaliTest[2276:4904561] jxcore: connect: success
,server bridge: new client socket
,2016-01-18 15:21:02.303 ThaliTest[2276:4903857] client: relay established
2016-01-18 15:21:02.303 ThaliTest[2276:4903857] client: new accepted socket: 0x17f72e10
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,ok 114 1st change of remote doc should contain remote id
,ok 115 Can update remote doc without error
,null
,{ ok: true,
  id: '838d9066-59ff-478b-a1d5-f3eb8b35f610',
  rev: '2-63ea6c72c208d573bdeaac86e8071243' }
,client bridge: new client socket
,ok 116 Remote changes occur in strict order
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,ok 117 Local changes occur in strict order
ok 118 2nd change of local doc should contain remote id
,# setup
,Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
2016-01-18 15:21:21.926 ThaliTest[2276:4904014] jxcore: stopBroadcasting
,2016-01-18 15:21:21.926 ThaliTest[2276:4904014] THEMultipeerSession stopping peer
2016-01-18 15:21:21.926 ThaliTest[2276:4904014] multipeer session: stop timer
,2016-01-18 15:21:21.927 ThaliTest[2276:4904014] client session: disconnect
2016-01-18 15:21:21.927 ThaliTest[2276:4904014] client session: stateChange:2->0 zMpmdU7aW1fPi1IEYKNtPg.tqUl5g==
,2016-01-18 15:21:21.930 ThaliTest[2276:4904014] server session: disconnect
2016-01-18 15:21:21.930 ThaliTest[2276:4904014] server session: stateChange:2->0 zMpmdU7aW1fPi1IEYKNtPg
,2016-01-18 15:21:21.942 ThaliTest[2276:4904014] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
,mux server bridge listener closed
client bridge: socket closed
server bridge: socket closed
,# teardown
,client bridge: socket closed
,client bridge: socket closed

```
