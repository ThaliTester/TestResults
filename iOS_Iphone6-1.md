#### Test 56151093c886730_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56151093c886730/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/EDAD85C7-DD24-49D5-B132-71FBDEF3F580/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/EDAD85C7-DD24-49D5-B132-71FBDEF3F580/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56151093c886730/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56151093c886730/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/05C8DB10-A683-46A0-B61B-9910C4E35ACC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57157"
,(lldb)     command script import "/tmp/EDAD85C7-DD24-49D5-B132-71FBDEF3F580/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-17 13:37:00.096 ThaliTest[2121:4495720] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/32140C38-65BC-4E04-A21E-5CF69EB7CF5D/Library/Cookies/Cookies.binarycookies
,2016-01-17 13:37:00.335 ThaliTest[2121:4495720] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-17 13:37:00.336 ThaliTest[2121:4495720] Multi-tasking -> Device: YES, App: YES
,2016-01-17 13:37:00.343 ThaliTest[2121:4495720] Unlimited access to network resources
,2016-01-17 13:37:00.350 ThaliTest[2121:4495720] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-17 13:37:04.534 ThaliTest[2121:4495720] Resetting plugins due to page load.
,2016-01-17 13:37:06.010 ThaliTest[2121:4495720] Finished load of: file:///var/mobile/Containers/Bundle/Application/05C8DB10-A683-46A0-B61B-9910C4E35ACC/ThaliTest.app/www/index.html
,2016-01-17 13:37:06.170 ThaliTest[2121:4495720] JXcore Cordova plugin initializing
,2016-01-17 13:37:06.171 ThaliTest[2121:4495865] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05C8DB10-A683-46A0-B61B-9910C4E35ACC/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05C8DB10-A683-46A0-B61B-9910C4E35ACC/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05C8DB10-A683-46A0-B61B-9910C4E35ACC/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05C8DB10-A683-46A0-B61B-9910C4E35ACC/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05C8DB10-A683-46A0-B61B-9910C4E35ACC/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05C8DB10-A683-46A0-B61B-9910C4E35ACC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/05C8DB10-A683-46A0-B61B-9910C4E35ACC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
# setup
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
,ok 11 should not throw
,ok 12 should be equal
,ok 13 should be equal
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
ok 17 should be equal
,ok 18 should be equal
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
ok 27 should be equal
ok 28 should be equal
# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
ok 30 should be equal
ok 31 should be equal
# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,ok 32 should be equal
ok 33 should be equal
# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
ok 35 should be equal
# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
ok 37 should be equal
ok 38 should be equal
# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
ok 40 should be equal
,# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
,ok 42 should be equal
# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
,ok 44 should be equal
# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-17 13:42:07.226 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.232 ThaliTest[2121:4495865] server: starting 1453034527226.2121.ftnTcw==
2016-01-17 13:42:07.232 ThaliTest[2121:4495865] multipeer session: start timer: 0x186e4e10
2016-01-17 13:42:07.232 ThaliTest[2121:4495865] THEMultipeerSession in,itialized peer 1453034527226.2121
2016-01-17 13:42:07.233 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.234 ThaliTest[2121:4495865] jxcore: stopBroadcasting
,2016-01-17 13:42:07.234 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
2016-01-17 13:42:07.237 ThaliTest[2121:4495865] multipeer session: stop timer
2016-01-17 13:42:07.238 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.238 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.245 ThaliTest[2121:4495865] server: starting 1453034527238.2121.tSZs3A==
,2016-01-17 13:42:07.247 ThaliTest[2121:4495865] multipeer session: start timer: 0x1a084560
2016-01-17 13:42:07.247 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527238.2121
2016-01-17 13:42:07.248 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.249 ThaliTest[2121:4495865] jxcore: stopBroadcasting
2016-01-17 13:42:07.249 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
2016-01-17 13:42:07.249 ThaliTest[2121:4495865] multipeer session: stop timer
,2016-01-17 13:42:07.250 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.253 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.257 ThaliTest[2121:4495865] server: starting 1453034527253.2121.vA2K/Q==
,2016-01-17 13:42:07.257 ThaliTest[2121:4495865] multipeer session: start timer: 0x1a082170
,2016-01-17 13:42:07.260 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527253.2121
2016-01-17 13:42:07.262 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.263 ThaliTest[2121:4495865] jxcore: stopBroadcasting
2016-01-17 13:42:07.263 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
,2016-01-17 13:42:07.263 ThaliTest[2121:4495865] multipeer session: stop timer
2016-01-17 13:42:07.270 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.270 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.273 ThaliTest[2121:4495865] server: starting 1453034527270.2121.bxgA+A==
2016-01-17 13:42:07.274 ThaliTest[2121:4495865] multipeer session: start timer: 0x186ee780
2016-01-17 13:42:07.274 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527270.2121
2016-01-17 13:42:07.274 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.275 ThaliTest[2121:4495865] jxcore: stopBroadcasting
2,016-01-17 13:42:07.275 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
,2016-01-17 13:42:07.275 ThaliTest[2121:4495865] multipeer session: stop timer
2016-01-17 13:42:07.278 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.279 ThaliTest,[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.282 ThaliTest[2121:4495865] server: starting 1453034527279.2121.sduGtw==
2016-01-17 13:42:07.282 ThaliTest[2121:4495865] multipeer session: start timer: 0x1a083bd0
2016-01-17 13:42:07.282 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527279.2121
,2016-01-17 13:42:07.282 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.286 ThaliTest[2121:4495865] jxcore: stopBroadcasting
2016-01-17 13:42:07.287 ThaliTest[21,21:4495865] THEMultipeerSession stopping peer
2016-01-17 13:42:07.287 ThaliTest[2121:4495865] multipeer session: stop timer
2016-01-17 13:42:07.287 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting w,ithout error
2016-01-17 13:42:07.287 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.291 ThaliTest[2121:4495865] server: starting 1453034527287.2121.bVs9PA==
2016-01-17 13:42:07.292 ThaliTest[2121:4495865] multipeer session: start timer: 0x1863d160
2016-01-17 13:42:07.292 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527287.2121
2016-01-17 13:42:07.292 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.293 ThaliTest[2121:4495865] jxcore: stopBroadcasting
2,016-01-17 13:42:07.293 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
2016-01-17 13:42:07.293 ThaliTest[2121:4495865] multipeer session: stop timer
2016-01-17 13:42:07.293 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
ok 56 Should, be able to call stopBroadcasting without error
2016-01-17 13:42:07.294 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.297 ThaliTest[2121:4495865] server: starting 1453034527293.2121.jImpQQ==
2016-01-17 13:42:07.298 ThaliTest[2121:4495865] multipeer session: start timer: 0x1863c8c0
2016-01-17 13:42:07.298 ThaliTest[2121:4495865] THEMultipeerSession in,itialized peer 1453034527293.2121
2016-01-17 13:42:07.298 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.299 ThaliTest[2121:4495865] jxcore: stopBroadcasting
2,016-01-17 13:42:07.299 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
2016-01-17 13:42:07.299 ThaliTest[2121:4495865] multipeer session: stop timer
2016-01-17 13:42:07.299 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
,2016-01-17 13:42:07.300 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.308 ThaliTest[2121:4495865] server: starting 1453034527300.2121.hMIlBw==
2016-01-17 13:42:07.308 ThaliTest[2121:4495865] multipeer session: start timer: 0x1a07f890
2016-01-17 13:42:07.308 ThaliTest[2121:4495865] THEMultipeerSession in,itialized peer 1453034527300.2121
2016-01-17 13:42:07.309 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.310 ThaliTest[2121:4495865] jxcore: stopBroadcasting
2016-01-17 13:42:07.310 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
2016-01-17 13:42:07.310 ThaliTest[2121:4495865] multipeer session: stop timer
,2016-01-17 13:42:07.313 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2016-01-17 13:42:07.314 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.319 ThaliTest[2121:4495865] server: starting 1453034527314.2121.HsCWIQ==
2016-01-17 13:42:07.319 ThaliTest[2121:4495865] multipeer session: start timer: 0x1a0800d0
,2016-01-17 13:42:07.319 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527314.2121
2016-01-17 13:42:07.322 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2016-,01-17 13:42:07.323 ThaliTest[2121:4495865] jxcore: stopBroadcasting
2016-01-17 13:42:07.323 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
2016-01-17 13:42:07.323 ThaliTest[2121:4495865] multipeer session: stop timer
2016-01-17 13:42:07.323 T,haliTest[2121:4495865] jxcore: stopBroadcasting: success
ok 62 Should be able to call stopBroadcasting without error
,2016-01-17 13:42:07.323 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.332 ThaliTest[2121:4495865] server: starting 1453034527323.2121.BqX8zQ==
2016-01-17 13:42:07.332 ThaliTest[2121:4495865] multipeer session: start timer: 0x1863c370
2016-01-17 13:42:07.333 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527323.2121
2016-01-17 13:42:07.333 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
2016-01-17 13:42:07.334 ThaliTest[2121:4495865] jxcore: stopBroadcasting
,2016-01-17 13:42:07.334 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
2016-01-17 13:42:07.336 ThaliTest[2121:4495865] multipeer session: stop timer
2016-01-17 13:42:07.336 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-17 13:42:07.516 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.518 ThaliTest[2121:4495865] server: starting 1453034527516.2121.SxLjNw==
,2016-01-17 13:42:07.519 ThaliTest[2121:4495865] multipeer session: start timer: 0x1a080d50
,2016-01-17 13:42:07.521 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527516.2121
,2016-01-17 13:42:07.522 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2016-01-17 13:42:07.524 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.524 ThaliTest[2121:4495865] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2016-01-17 13:42:07.525 ThaliTest[2121:4495865] jxcore: stopBroadcasting
,2016-01-17 13:42:07.526 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
,2016-01-17 13:42:07.526 ThaliTest[2121:4495865] multipeer session: stop timer
,2016-01-17 13:42:07.526 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-17 13:42:07.583 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.585 ThaliTest[2121:4495865] server: starting 1453034527583.2121.lsHCQw==
,2016-01-17 13:42:07.586 ThaliTest[2121:4495865] multipeer session: start timer: 0x1a0836d0
,2016-01-17 13:42:07.588 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527583.2121
,2016-01-17 13:42:07.589 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2016-01-17 13:42:07.590 ThaliTest[2121:4495865] jxcore: connect foobar
,2016-01-17 13:42:07.591 ThaliTest[2121:4495865] client: unknown peer foobar
,2016-01-17 13:42:07.591 ThaliTest[2121:4495865] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-17 13:42:07.593 ThaliTest[2121:4495865] jxcore: stopBroadcasting
,2016-01-17 13:42:07.593 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
,2016-01-17 13:42:07.593 ThaliTest[2121:4495865] multipeer session: stop timer
,2016-01-17 13:42:07.594 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-17 13:42:07.641 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.643 ThaliTest[2121:4495865] server: starting 1453034527641.2121.GvliJQ==
,2016-01-17 13:42:07.644 ThaliTest[2121:4495865] multipeer session: start timer: 0x1a075ee0
2016-01-17 13:42:07.646 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527641.2121
,2016-01-17 13:42:07.647 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
,2016-01-17 13:42:07.648 ThaliTest[2121:4495865] jxcore: disconnect
,2016-01-17 13:42:07.648 ThaliTest[2121:4495865] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2016-01-17 13:42:07.650 ThaliTest[2121:4495865] jxcore: stopBroadcasting
,2016-01-17 13:42:07.650 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
,2016-01-17 13:42:07.651 ThaliTest[2121:4495865] multipeer session: stop timer
,2016-01-17 13:42:07.653 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-17 13:42:07.721 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:07.723 ThaliTest[2121:4495865] server: starting 1453034527721.2121.CjYwww==
,2016-01-17 13:42:07.724 ThaliTest[2121:4495865] multipeer session: start timer: 0x1a076850
,2016-01-17 13:42:07.726 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034527721.2121
,2016-01-17 13:42:07.726 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2016-01-17 13:42:08.916 ThaliTest[2121:4495720] client: found peer: 1453034527663.2091.H4vJTQ==
,2016-01-17 13:42:08.918 ThaliTest[2121:4495865] jxcore: connect 1453034527663.2091.H4vJTQ==
2016-01-17 13:42:08.918 ThaliTest[2121:4495865] client session: connect
2016-01-17 13:42:08.918 ThaliTest[2121:4495865] client session: stateChange:0->1 1453034527663.2091.H4vJTQ==
,2016-01-17 13:42:09.242 ThaliTest[2121:4495720] multipeer session: reset timer
2016-01-17 13:42:09.242 ThaliTest[2121:4495720] multipeer session: stop timer
2016-01-17 13:42:09.242 ThaliTest[2121:4495720] multipeer session: start timer: 0x1a076850
2016-,01-17 13:42:09.242 ThaliTest[2121:4495720] server session: connect
2016-01-17 13:42:09.242 ThaliTest[2121:4495720] server session: stateChange:0->1 1453034527663.2091
2016-01-17 13:42:09.245 ThaliTest[2121:4495720] server: accepting invitation 1453034527663.2091
,2016-01-17 13:42:11.801 ThaliTest[2121:4496347] client session: connected
2016-01-17 13:42:11.801 ThaliTest[2121:4496347] client session: stateChange:1->2 1453034527663.2091.H4vJTQ==
,2016-01-17 13:42:11.805 ThaliTest[2121:4496323] client session: fireConnectCallback: 1453034527663.2091.H4vJTQ==
2016-01-17 13:42:11.805 ThaliTest[2121:4496323] jxcore: connect: success
,ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-17 13:42:11.807 ThaliTest[2121:4495865] jxcore: disconnect
2016-01-17 13:42:11.808 ThaliTest[2121:4495865] client session: disconnectFromPeer: 1453034527663.2091.H4vJTQ==
2016-01-17 13:42:11.808 ThaliTest[2121:4495865] client session: disconnect
2016-01-17 13:42:11.808 ThaliTest[2121:4495865] client session: stateChange:2->0 1453034527663.2091.H4vJTQ==
,2016-01-17 13:42:11.812 ThaliTest[2121:4496323] server session: connected
2016-01-17 13:42:11.812 ThaliTest[2121:4496323] server session: stateChange:1->2 1453034527663.2091
,2016-01-17 13:42:11.815 ThaliTest[2121:4495865] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 13:42:11.863 ThaliTest[2121:4495720] server relay: socket disconnected
2016-01-17 13:42:11.863 ThaliTest[2121:4495720] server relay: 0x1a063650 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 13:42:11.929 ThaliTest[2121:4496324] server session: not connected 1453034527663.2091
,calling stopBroadcasting
,2016-01-17 13:42:12.404 ThaliTest[2121:4495865] jxcore: stopBroadcasting
2016-01-17 13:42:12.404 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
2016-01-17 13:42:12.404 ThaliTest[2121:4495865] multipeer session: stop timer
2016-01-17 13:42:12.,404 ThaliTest[2121:4495865] server session: disconnect
2016-01-17 13:42:12.405 ThaliTest[2121:4495865] server session: stateChange:2->0 1453034527663.2091
2016-01-17 13:42:12.405 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-17 13:42:25.253 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:25.255 ThaliTest[2121:4495865] server: starting 1453034545253.2121.vcInqQ==
2016-01-17 13:42:25.255 ThaliTest[2121:4495865] multipeer session: start timer: 0x1861b150
2016-01-17 13:42:25.255 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034545253.2121
2016-01-17 13:42:25.255 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-17 13:42:25.988 ThaliTest[2121:4495720] client: found peer: 1453034543319.2091.H54WmQ==
2016-01-17 13:42:25.989 ThaliTest[2121:4495865] jxcore: connect 1453034543319.2091.H54WmQ==
2016-01-17 13:42:25.989 ThaliTest[2121:4495865] client session: connect
2016-01-17 13:42:25.989 ThaliTest[2121:4495865] client session: stateChange:0->1 1453034543319.2091.H54WmQ==
,2016-01-17 13:42:26.741 ThaliTest[2121:4495720] multipeer session: reset timer
2016-01-17 13:42:26.741 ThaliTest[2121:4495720] multipeer session: stop timer
2016-01-17 13:42:26.741 ThaliTest[2121:4495720] multipeer session: start timer: 0x1861b150
2016-01-17 13:42:26.742 ThaliTest[2121:4495720] server session: connect
2016-01-17 13:42:26.742 ThaliTest[2121:4495720] server session: stateChange:0->1 1453034543319.2091
2016-01-17 13:42:26.744 ThaliTest[2121:4495720] server: accepting invitation 1453034543319.2091
,2016-01-17 13:42:28.845 ThaliTest[2121:4496411] client session: connected
2016-01-17 13:42:28.845 ThaliTest[2121:4496411] client session: stateChange:1->2 1453034543319.2091.H54WmQ==
,2016-01-17 13:42:28.899 ThaliTest[2121:4496411] client session: fireConnectCallback: 1453034543319.2091.H54WmQ==
2016-01-17 13:42:28.900 ThaliTest[2121:4496411] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
2016-01-17 13:42:28.902 ThaliTest[2121:4495865] jxcore: connect 1453034543319.2091.H54WmQ==
2016-01-17 13:42:28.902 ThaliTest[2121:4495865] client: already connect(ing/ed) to 1453034543319.2091.H54WmQ==
2016-01-17 13:42:28.902 ThaliTest[2121:4495865] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-17 13:42:28.903 ThaliTest[2121:4495865] jxcore: disconnect
2016-01-17 13:42:28.903 ThaliTest[2121:4495865] client session: disconnectFromPeer: 1453034543319.,2091.H54WmQ==
2016-01-17 13:42:28.903 ThaliTest[2121:4495865] client session: disconnect
2016-01-17 13:42:28.903 ThaliTest[2121:4495865] client session: stateChange:2->0 1453034543319.2091.H54WmQ==
,2016-01-17 13:42:28.912 ThaliTest[2121:4495865] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 13:42:29.297 ThaliTest[2121:4496436] server session: connected
2016-01-17 13:42:29.297 ThaliTest[2121:4496436] server session: stateChange:1->2 1453034543319.2091
,2016-01-17 13:42:29.357 ThaliTest[2121:4496409] server session: not connected 1453034543319.2091
,2016-01-17 13:42:29.357 ThaliTest[2121:4495720] server relay: socket disconnected
2016-01-17 13:42:29.358 ThaliTest[2121:4495720] server relay: 0x1a078000 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 13:42:32.458 ThaliTest[2121:4495720] client: lost peer: 1453034543319.2091.H54WmQ==
2016-01-17 13:42:32.458 ThaliTest[2121:4495720] client session: onPeerLost: 1453034543319.2091.H54WmQ==
,calling stopBroadcasting
,2016-01-17 13:42:41.527 ThaliTest[2121:4495865] jxcore: stopBroadcasting
2016-01-17 13:42:41.528 ThaliTest[2121:4495865] THEMultipeerSession stopping peer
2016-01-17 13:42:41.528 ThaliTest[2121:4495865] multipeer session: stop timer
2016-01-17 13:42:41.528 ThaliTest[2121:4495865] server session: disconnect
2016-01-17 13:42:41.528 ThaliTest[2121:4495865] server session: stateChange:2->0 1453034543319.2091
2016-01-17 13:42:41.528 ThaliTest[2121:4495865] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-17 13:42:45.249 ThaliTest[2121:4495865] jxcore: startBroadcasting
,2016-01-17 13:42:45.251 ThaliTest[2121:4495865] server: starting 1453034565249.2121.UrKUjg==
2016-01-17 13:42:45.251 ThaliTest[2121:4495865] multipeer session: start timer: 0x18612230
2016-01-17 13:42:45.251 ThaliTest[2121:4495865] THEMultipeerSession initialized peer 1453034565249.2121
2016-01-17 13:42:45.251 ThaliTest[2121:4495865] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-17 13:42:45.551 ThaliTest[2121:4495720] client: found peer: 1453034564327.2091.5p4ccQ==
2016-01-17 13:42:45.551 ThaliTest[2121:4495865] jxcore: connect 1453034564327.2091.5p4ccQ==
2016-01-17 13:42:45.551 ThaliTest[2121:4495865] client session: connect
2016-01-17 13:42:45.551 ThaliTest[2121:4495865] client session: stateChange:0->1 1453034564327.2091.5p4ccQ==
,2016-01-17 13:42:48.103 ThaliTest[2121:4495720] multipeer session: reset timer
2016-01-17 13:42:48.103 ThaliTest[2121:4495720] multipeer session: stop timer
2016-01-17 13:42:48.103 ThaliTest[2121:4495720] multipeer session: start timer: 0x18612230
2016-01-17 13:42:48.103 ThaliTest[2121:4495720] server session: connect
2016-01-17 13:42:48.104 ThaliTest[2121:4495720] server session: stateChange:0->1 1453034564327.2091
,2016-01-17 13:42:48.107 ThaliTest[2121:4495720] server: accepting invitation 1453034564327.2091
,2016-01-17 13:42:48.303 ThaliTest[2121:4496409] client session: connected
2016-01-17 13:42:48.303 ThaliTest[2121:4496409] client session: stateChange:1->2 1453034564327.2091.5p4ccQ==
,2016-01-17 13:42:48.342 ThaliTest[2121:4496488] client session: fireConnectCallback: 1453034564327.2091.5p4ccQ==
2016-01-17 13:42:48.342 ThaliTest[2121:4496488] jxcore: connect: success
,ok 84 Should be able to connect without error
ok 85 Port should be within range
,2016-01-17 13:42:48.344 ThaliTest[2121:4495865] jxcore: disconnect
2016-01-17 13:42:48.344 ThaliTest[2121:4495865] client session: disconnectFromPeer: 1453034564327.2091.5p4ccQ==
2016-01-17 13:42:48.344 ThaliTest[2121:4495865] client session: disconnect,
2016-01-17 13:42:48.344 ThaliTest[2121:4495865] client session: stateChange:2->0 1453034564327.2091.5p4ccQ==
,2016-01-17 13:42:48.348 ThaliTest[2121:4495865] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-17 13:42:48.349 ThaliTest[2121:4495865] jxcore: disconnect
,2016-01-17 13:42:48.349 ThaliTest[2121:4495865] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 13:42:50.786 ThaliTest[2121:4496488] server session: connected
,2016-01-17 13:42:50.786 ThaliTest[2121:4496488] server session: stateChange:1->2 1453034564327.2091
,2016-01-17 13:42:50.789 ThaliTest[2121:4495720] server relay: socket disconnected
2016-01-17 13:42:50.790 ThaliTest[2121:4495720] server relay: 0x18611b30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 13:42:50.817 ThaliTest[2121:4496517] server session: not connected 1453034564327.2091
,2016-01-17 13:42:52.932 ThaliTest[2121:4495720] client: lost peer: 1453034564327.2091.5p4ccQ==
2016-01-17 13:42:52.932 ThaliTest[2121:4495720] client session: onPeerLost: 1453034564327.2091.5p4ccQ==
,appEnteredForeground wasn't registered
,2016-01-17 13:43:18.105 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:43:48.104 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:44:18.104 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:44:48.104 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:45:18.104 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:45:48.104 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:46:18.105 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:46:48.104 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:47:18.105 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:47:48.104 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:48:18.104 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:48:48.104 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:49:18.104 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:49:48.059 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:50:18.059 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:50:48.059 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:51:18.059 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:51:48.059 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:52:18.059 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:52:48.059 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:53:18.059 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:53:48.059 ThaliTest[2121:4495720] multipeer session: restart
,2016-01-17 13:54:18.059 ThaliTest[2121:4495720] multipeer session: restart

```
