#### Test 5635717154d1b6f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5635717154d1b6f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A636C40D-85B0-47E7-B1B9-974DAB79EFEC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A636C40D-85B0-47E7-B1B9-974DAB79EFEC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5635717154d1b6f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5635717154d1b6f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FB19C3F8-6BE0-4AC9-8DA9-452FD5457F6E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58053"
,(lldb)     command script import "/tmp/A636C40D-85B0-47E7-B1B9-974DAB79EFEC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-18 16:53:51.882 ThaliTest[2234:4667387] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C38BE19C-11CF-4525-A356-C71F2550FF81/Library/Cookies/Cookies.binarycookies
,2016-01-18 16:53:52.109 ThaliTest[2234:4667387] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-18 16:53:52.110 ThaliTest[2234:4667387] Multi-tasking -> Device: YES, App: YES
,2016-01-18 16:53:52.117 ThaliTest[2234:4667387] Unlimited access to network resources
,2016-01-18 16:53:52.124 ThaliTest[2234:4667387] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-18 16:53:56.072 ThaliTest[2234:4667387] Resetting plugins due to page load.
,2016-01-18 16:53:57.439 ThaliTest[2234:4667387] Finished load of: file:///var/mobile/Containers/Bundle/Application/FB19C3F8-6BE0-4AC9-8DA9-452FD5457F6E/ThaliTest.app/www/index.html
,2016-01-18 16:53:57.599 ThaliTest[2234:4667387] JXcore Cordova plugin initializing
,2016-01-18 16:53:57.600 ThaliTest[2234:4667536] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB19C3F8-6BE0-4AC9-8DA9-452FD5457F6E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB19C3F8-6BE0-4AC9-8DA9-452FD5457F6E/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB19C3F8-6BE0-4AC9-8DA9-452FD5457F6E/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB19C3F8-6BE0-4AC9-8DA9-452FD5457F6E/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB19C3F8-6BE0-4AC9-8DA9-452FD5457F6E/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB19C3F8-6BE0-4AC9-8DA9-452FD5457F6E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB19C3F8-6BE0-4AC9-8DA9-452FD5457F6E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
ok 6 (unnamed assert)
ok 7 should be equal
ok 8 should not throw
# setup
,# successfully read a previous pkcs12 file and return hash value
,# teardown
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
ok 11 should not throw
,ok 12 should be equal
,ok 13 should be equal
# setup
,# failed to extract public key because of corrupt pkcs12 file
,# teardown
,ok 14 should be equal
,# setup
,# failed to get mobile documents path
,# teardown
,ok 15 should be equal
# setup
,# #init should register the peerAvailabilityChanged event
,# teardown
,ok 16 should be equal
ok 17 should be equal
ok 18 should be equal
# setup
,# #init should register the networkChanged event
,# teardown
,ok 19 should be equal
,# setup
,# #startBroadcasting should throw on null device name
,# teardown
,ok 20 should throw
# setup
,# #startBroadcasting should throw on empty string device name
,# teardown
,ok 21 should throw
,# setup
,# #startBroadcasting should throw on non-number port
,# teardown
,ok 22 should throw
# setup
,# #startBroadcasting should throw on NaN port
,# teardown
,ok 23 should throw
# setup
,# #startBroadcasting should throw on negative port
,# teardown
,ok 24 should throw
,# setup
,# #startBroadcasting should throw on too large port
,# teardown
,ok 25 should throw
# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,ok 26 should be equal
,ok 27 should be equal
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
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
ok 35 should be equal
,# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
ok 37 should be equal
ok 38 should be equal
,# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
ok 40 should be equal
# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
ok 42 should be equal
# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
ok 44 should be equal
# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-18 16:59:20.252 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:20.259 ThaliTest[2234:4667536] server: starting 1453132760252.2234.UMgEWw==
2016-01-18 16:59:20.259 ThaliTest[2234:4667536] multipeer session: start timer: 0x14643a20
2016-01-18 16:59:20.259 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132760252.2234
2016-01-18 16:59:20.261 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-18 16:59:20.262 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 16:59:20.262 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:20.262 ThaliTest[2234:4667536] multipeer session: stop timer
2016-01-18 16:59:20.264 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-18 16:59:20.265 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:20.270 ThaliTest[2234:4667536] server: starting 1453132760265.2234.nisLgw==
,2016-01-18 16:59:20.270 ThaliTest[2234:4667536] multipeer session: start timer: 0x15af3540
,2016-01-18 16:59:20.273 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132760265.2234
2016-01-18 16:59:20.274 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2016-01-18 16:59:20.276 ThaliTest[2234:4667536] jxcore: stopBroadcasting
,2016-01-18 16:59:20.277 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:20.277 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 16:59:20.280 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:20.284 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:20.286 ThaliTest[2234:4667536] server: starting 1453132760284.2234.k+bztw==
,2016-01-18 16:59:20.287 ThaliTest[2234:4667536] multipeer session: start timer: 0x15830e90
,2016-01-18 16:59:20.291 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132760284.2234
,2016-01-18 16:59:20.291 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-18 16:59:20.292 ThaliTest[2234:4667536] jxcore: stopBroadcasting
,2016-01-18 16:59:20.293 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:20.293 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 16:59:20.294 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:20.296 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:20.298 ThaliTest[2234:4667536] server: starting 1453132760296.2234.ZCqd8g==
,2016-01-18 16:59:20.299 ThaliTest[2234:4667536] multipeer session: start timer: 0x159628a0
,2016-01-18 16:59:20.302 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132760296.2234
,2016-01-18 16:59:20.303 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-18 16:59:20.304 ThaliTest[2234:4667536] jxcore: stopBroadcasting
,2016-01-18 16:59:20.304 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:20.305 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 16:59:20.306 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:20.309 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:20.311 ThaliTest[2234:4667536] server: starting 1453132760308.2234.fK8WQQ==
,2016-01-18 16:59:20.312 ThaliTest[2234:4667536] multipeer session: start timer: 0x146e5140
,2016-01-18 16:59:20.315 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132760308.2234
,2016-01-18 16:59:20.315 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-18 16:59:20.316 ThaliTest[2234:4667536] jxcore: stopBroadcasting
,2016-01-18 16:59:20.317 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:20.318 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 16:59:20.319 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:20.322 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:20.323 ThaliTest[2234:4667536] server: starting 1453132760321.2234.WhlGXA==
,2016-01-18 16:59:20.324 ThaliTest[2234:4667536] multipeer session: start timer: 0x146e59a0
,2016-01-18 16:59:20.327 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132760321.2234
,2016-01-18 16:59:20.327 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-18 16:59:20.329 ThaliTest[2234:4667536] jxcore: stopBroadcasting
,2016-01-18 16:59:20.330 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:20.330 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 16:59:20.332 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:20.333 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:20.335 ThaliTest[2234:4667536] server: starting 1453132760333.2234.wGZrjg==
,2016-01-18 16:59:20.336 ThaliTest[2234:4667536] multipeer session: start timer: 0x15843d40
,2016-01-18 16:59:20.339 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132760333.2234
,2016-01-18 16:59:20.340 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-18 16:59:20.341 ThaliTest[2234:4667536] jxcore: stopBroadcasting
,2016-01-18 16:59:20.342 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:20.343 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 16:59:20.344 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:20.346 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:20.348 ThaliTest[2234:4667536] server: starting 1453132760346.2234.9h3jiw==
,2016-01-18 16:59:20.349 ThaliTest[2234:4667536] multipeer session: start timer: 0x15d41200
,2016-01-18 16:59:20.351 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132760346.2234
,2016-01-18 16:59:20.352 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-18 16:59:20.353 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 16:59:20.354 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:20.354 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 16:59:20.356 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:20.358 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:20.359 ThaliTest[2234:4667536] server: starting 1453132760358.2234.617FuA==
,2016-01-18 16:59:20.360 ThaliTest[2234:4667536] multipeer session: start timer: 0x15d41420
,2016-01-18 16:59:20.363 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132760358.2234
,2016-01-18 16:59:20.364 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-18 16:59:20.365 ThaliTest[2234:4667536] jxcore: stopBroadcasting
,2016-01-18 16:59:20.365 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:20.366 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 16:59:20.367 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-18 16:59:20.369 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:20.370 ThaliTest[2234:4667536] server: starting 1453132760369.2234.xvtF7g==
,2016-01-18 16:59:20.371 ThaliTest[2234:4667536] multipeer session: start timer: 0x15840130
,2016-01-18 16:59:20.374 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132760369.2234
,2016-01-18 16:59:20.374 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-18 16:59:20.376 ThaliTest[2234:4667536] jxcore: stopBroadcasting
,2016-01-18 16:59:20.377 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:20.377 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 16:59:20.378 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-18 16:59:21.080 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:21.081 ThaliTest[2234:4667536] server: starting 1453132761079.2234.gGBCGg==
2016-01-18 16:59:21.082 ThaliTest[2234:4667536] multipeer session: start timer: 0x15847a20
2016-01-18 16:59:21.082 ThaliTest[2234:4667536] THEMultipeerSession in,itialized peer 1453132761079.2234
2016-01-18 16:59:21.082 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-18 16:59:21.083 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:21.083 ThaliTest[2234:4667536] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2016-01-18 16:59:21.083 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 16:59:21.086 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
2016-01-18 16:59:21.087 ThaliTest[2234:4667536] multipeer session: stop timer
2016-01-18 16:59:21.087 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-18 16:59:21.190 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:21.192 ThaliTest[2234:4667536] server: starting 1453132761190.2234.APHEOw==
2016-01-18 16:59:21.192 ThaliTest[2234:4667536] multipeer session: start timer: 0x158524e0
2016-01-18 16:59:21.193 ThaliTest[2234:4667536] THEMultipeerSession in,itialized peer 1453132761190.2234
2016-01-18 16:59:21.193 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-18 16:59:21.193 ThaliTest[2234:4667536] jxcore: connect foobar
2016-01-18 16:59:21.194 ThaliTest[2234:4667536] client: unknown peer foobar
,2016-01-18 16:59:21.194 ThaliTest[2234:4667536] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-18 16:59:21.198 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 16:59:21.198 ThaliTest[2234:4667536] THEMultip,eerSession stopping peer
2016-01-18 16:59:21.198 ThaliTest[2234:4667536] multipeer session: stop timer
2016-01-18 16:59:21.198 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-18 16:59:21.257 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:21.259 ThaliTest[2234:4667536] server: starting 1453132761257.2234.sEFeDQ==
2016-01-18 16:59:21.259 ThaliTest[2234:4667536] multipeer session: start timer: 0x15dcfca0
2016-01-18 16:59:21.259 ThaliTest[2234:4667536] THEMultipeerSession in,itialized peer 1453132761257.2234
2016-01-18 16:59:21.259 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-18 16:59:21.260 ThaliTest[2234:4667536] jxcore: disconnect
2016-01,-18 16:59:21.260 ThaliTest[2234:4667536] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-18 16:59:21.260 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 16:59:21.264 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
2016-01-18 16:59:21.264 ThaliTest[2234:4667536] multipeer session: stop timer
2016-01-18 16:59:21.264 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-18 16:59:21.605 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:21.607 ThaliTest[2234:4667536] server: starting 1453132761605.2234.zN5HjQ==
2016-01-18 16:59:21.607 ThaliTest[2234:4667536] multipeer session: start timer: 0x158efc00
2016-01-18 16:59:21.607 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132761605.2234
2016-01-18 16:59:21.608 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-18 16:59:22.562 ThaliTest[2234:4667387] client: found peer: 1453132763621.2288.QMQnBw==
2016-01-18 16:59:22.563 ThaliTest[2234:4667536] jxcore: connect 1453132763621.2288.QMQnBw==
2016-01-18 16:59:22.563 ThaliTest[2234:4667536] client session: connect
2016-01-18 16:59:22.563 ThaliTest[2234:4667536] client session: stateChange:0->1 1453132763621.2288.QMQnBw==
,2016-01-18 16:59:22.998 ThaliTest[2234:4667387] multipeer session: reset timer
2016-01-18 16:59:22.998 ThaliTest[2234:4667387] multipeer session: stop timer
2016-01-18 16:59:22.998 ThaliTest[2234:4667387] multipeer session: start timer: 0x158efc00
2016-,01-18 16:59:22.998 ThaliTest[2234:4667387] server session: connect
2016-01-18 16:59:22.999 ThaliTest[2234:4667387] server session: stateChange:0->1 1453132763621.2288
2016-01-18 16:59:23.002 ThaliTest[2234:4667387] server: accepting invitation 1453132763621.2288
,2016-01-18 16:59:27.120 ThaliTest[2234:4668062] server session: connected
2016-01-18 16:59:27.120 ThaliTest[2234:4668062] server session: stateChange:1->2 1453132763621.2288
,2016-01-18 16:59:27.185 ThaliTest[2234:4667387] server relay: socket disconnected
2016-01-18 16:59:27.185 ThaliTest[2234:4667387] server relay: 0x159faf40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 16:59:27.188 ThaliTest[2234:4668062] server session: not connected 1453132763621.2288
,2016-01-18 16:59:27.196 ThaliTest[2234:4668062] client session: connected
2016-01-18 16:59:27.196 ThaliTest[2234:4668062] client session: stateChange:1->2 1453132763621.2288.QMQnBw==
,2016-01-18 16:59:27.256 ThaliTest[2234:4668062] client session: fireConnectCallback: 1453132763621.2288.QMQnBw==
2016-01-18 16:59:27.256 ThaliTest[2234:4668062] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-18 16:59:27.258 ThaliTest[2234:4667536] jxcore: disconnect
2016-01-18 16:59:27.258 ThaliTest[2234:4667536] client session: disconnectFromPeer: 1453132763621.2288.QMQnBw==
2016-01-18 16:59:27.258 ThaliTest[2234:4667536] client session: disconnect
2016-01-18 16:59:27.258 ThaliTest[2234:4667536] client session: stateChange:2->0 1453132763621.2288.QMQnBw==
,2016-01-18 16:59:27.261 ThaliTest[2234:4667536] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-18 16:59:27.447 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 16:59:27.447 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
2016-01-18 16:59:27.447 ThaliTest[2234:4667536] multipeer session: stop timer
2016-01-18 16:59:27.447 ThaliTest[2234:4667536] server session: disconnect
2016-01-18 16:59:27.448 ThaliTest[2234:4667536] server session: stateChange:2->0 1453132763621.2288
2016-01-18 16:59:27.448 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-18 16:59:27.965 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:27.966 ThaliTest[2234:4667536] server: starting 1453132767965.2234.EvrA9A==
2016-01-18 16:59:27.967 ThaliTest[2234:4667536] multipeer session: start timer: 0x159decc0
2016-01-18 16:59:27.967 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132767965.2234
2016-01-18 16:59:27.967 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-18 16:59:28.575 ThaliTest[2234:4667387] client: found peer: 1453132763621.2288.QMQnBw==
,2016-01-18 16:59:28.575 ThaliTest[2234:4667536] jxcore: connect 1453132763621.2288.QMQnBw==
2016-01-18 16:59:28.576 ThaliTest[2234:4667536] client session: connect
2016-01-18 16:59:28.576 ThaliTest[2234:4667536] client session: stateChange:0->1 1453132763621.2288.QMQnBw==
,2016-01-18 16:59:29.287 ThaliTest[2234:4667387] multipeer session: reset timer
,2016-01-18 16:59:29.288 ThaliTest[2234:4667387] multipeer session: stop timer
2016-01-18 16:59:29.289 ThaliTest[2234:4667387] multipeer session: start timer: 0x159decc0
,2016-01-18 16:59:29.289 ThaliTest[2234:4667387] server session: connect
2016-01-18 16:59:29.289 ThaliTest[2234:4667387] server session: stateChange:0->1 1453132769979.2288
,2016-01-18 16:59:29.292 ThaliTest[2234:4667387] server: accepting invitation 1453132769979.2288
,2016-01-18 16:59:29.437 ThaliTest[2234:4667387] client: found peer: 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:29.437 ThaliTest[2234:4667536] jxcore: connect 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:29.437 ThaliTest[2234:4667536] client session: connect
2016-01-18 16:59:29.437 ThaliTest[2234:4667536] client session: stateChange:0->1 1453132769979.2288.pRS7Rg==
,2016-01-18 16:59:33.287 ThaliTest[2234:4668063] server session: connected
2016-01-18 16:59:33.287 ThaliTest[2234:4668063] server session: stateChange:1->2 1453132769979.2288
,2016-01-18 16:59:33.341 ThaliTest[2234:4667387] server relay: socket disconnected
2016-01-18 16:59:33.341 ThaliTest[2234:4667387] server relay: 0x158be590 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 16:59:33.356 ThaliTest[2234:4668058] server session: not connected 1453132769979.2288
,2016-01-18 16:59:33.613 ThaliTest[2234:4668063] client session: connected
2016-01-18 16:59:33.613 ThaliTest[2234:4668063] client session: stateChange:1->2 1453132769979.2288.pRS7Rg==
,2016-01-18 16:59:33.667 ThaliTest[2234:4668063] client session: fireConnectCallback: 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:33.667 ThaliTest[2234:4668063] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-18 16:59:33.669 ThaliTest[2234:4667536] jxcore: connect 1453132769979.2288.pRS7Rg==
,2016-01-18 16:59:33.669 ThaliTest[2234:4667536] client: already connect(ing/ed) to 1453132769979.2288.pRS7Rg==
,2016-01-18 16:59:33.669 ThaliTest[2234:4667536] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2016-01-18 16:59:33.670 ThaliTest[2234:4667536] jxcore: disconnect
2016-01-18 16:59:33.670 ThaliTest[2234:4667536] client session: disconnectFromPeer: 1453132769979.2288.pRS7Rg==
,2016-01-18 16:59:33.670 ThaliTest[2234:4667536] client session: disconnect
,2016-01-18 16:59:33.670 ThaliTest[2234:4667536] client session: stateChange:2->0 1453132769979.2288.pRS7Rg==
,2016-01-18 16:59:33.673 ThaliTest[2234:4667536] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-18 16:59:34.152 ThaliTest[2234:4667387] client: lost peer: 1453132763621.2288.QMQnBw==
2016-01-18 16:59:34.152 ThaliTest[2234:4667387] client session: onPeerLost: 1453132763621.2288.QMQnBw==
2016-01-18 16:59:34.152 ThaliTest[2234:4667387] client ,session: onLinkFailure: 1453132763621.2288.QMQnBw==
2016-01-18 16:59:34.152 ThaliTest[2234:4667387] client session: disconnect
2016-01-18 16:59:34.152 ThaliTest[2234:4667387] client session: stateChange:1->0 1453132763621.2288.QMQnBw==
2016-01-18 16:59:34.152 ThaliTest[2234:4667387] client session: fireConnectCallback: 1453132763621.2288.QMQnBw==
2016-01-18 16:59:34.152 ThaliTest[2234:4667387] jxcore: connect: fail: Peer disconnected
,calling stopBroadcasting
,2016-01-18 16:59:35.318 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 16:59:35.318 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
2016-01-18 16:59:35.318 ThaliTest[2234:4667536] multipeer session: stop timer
2016-01-18 16:59:35.318 ThaliTest[2234:4667536] server session: disconnect
2016-01-18 16:59:35.318 ThaliTest[2234:4667536] server session: stateChange:2->0 1453132769979.2288
,2016-01-18 16:59:35.320 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-18 16:59:36.967 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:36.969 ThaliTest[2234:4667536] server: starting 1453132776967.2234.KfmYXw==
2016-01-18 16:59:36.969 ThaliTest[2234:4667536] multipeer session: start timer: 0x15981700
2016-01-18 16:59:36.969 ThaliTest[2234:4667536] THEMultipeerSession in,itialized peer 1453132776967.2234
2016-01-18 16:59:36.969 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-18 16:59:37.553 ThaliTest[2234:4667387] client: found peer: 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:37.554 ThaliTest[2234:4667536] jxcore: connect 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:37.554 ThaliTest[2234:4667536] client session: connect
2016-01-18 16:59:37.554 ThaliTest[2234:4667536] client session: stateChange:0->1 1453132769979.2288.pRS7Rg==
,2016-01-18 16:59:38.016 ThaliTest[2234:4667387] client: lost peer: 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:38.016 ThaliTest[2234:4667387] client session: onPeerLost: 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:38.016 ThaliTest[2234:4667387] client session: onLinkFailure: 1453132769979.2288.pRS7Rg==
,2016-01-18 16:59:38.018 ThaliTest[2234:4667387] client session: disconnect
2016-01-18 16:59:38.018 ThaliTest[2234:4667387] client session: stateChange:1->0 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:38.018 ThaliTest[2234:4667387] client session: fireConnectCallback: 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:38.018 ThaliTest[2234:4667387] jxcore: connect: fail: Peer disconnected
,2016-01-18 16:59:38.195 ThaliTest[2234:4667387] multipeer session: reset timer
2016-01-18 16:59:38.195 ThaliTest[2234:4667387] multipeer session: stop timer
2016-01-18 16:59:38.195 ThaliTest[2234:4667387] multipeer session: start timer: 0x15981700
2016-01-18 16:59:38.195 ThaliTest[2234:4667387] server session: connect
2016-01-18 16:59:38.195 ThaliTest[2234:4667387] server session: stateChange:0->1 1453132779006.2288
2016-01-18 16:59:38.198 ThaliTest[2234:4667387] server: accepting invitation 1453132779006.2288
,2016-01-18 16:59:39.023 ThaliTest[2234:4667536] jxcore: connect 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:39.023 ThaliTest[2234:4667536] client: connect: unreachable 1453132769979.2288.pRS7Rg==
2016-01-18 16:59:39.023 ThaliTest[2234:4667536] jxcore: connect: fail: Peer unreachable
,2016-01-18 16:59:39.925 ThaliTest[2234:4667387] client: found peer: 1453132779006.2288.yAkOuA==
,2016-01-18 16:59:39.926 ThaliTest[2234:4667536] jxcore: connect 1453132779006.2288.yAkOuA==
2016-01-18 16:59:39.926 ThaliTest[2234:4667536] client session: connect
2016-01-18 16:59:39.926 ThaliTest[2234:4667536] client session: stateChange:0->1 1453132779006.2288.yAkOuA==
,2016-01-18 16:59:41.798 ThaliTest[2234:4668058] server session: connected
2016-01-18 16:59:41.798 ThaliTest[2234:4668058] server session: stateChange:1->2 1453132779006.2288
,2016-01-18 16:59:41.805 ThaliTest[2234:4667387] server relay: socket disconnected
,2016-01-18 16:59:41.806 ThaliTest[2234:4667387] server relay: 0x15aa5a40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 16:59:43.511 ThaliTest[2234:4668062] client session: connected
2016-01-18 16:59:43.512 ThaliTest[2234:4668062] client session: stateChange:1->2 1453132779006.2288.yAkOuA==
,2016-01-18 16:59:43.565 ThaliTest[2234:4668058] client session: fireConnectCallback: 1453132779006.2288.yAkOuA==
2016-01-18 16:59:43.565 ThaliTest[2234:4668058] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-18 16:59:43.568 ThaliTest[2234:4667536] jxcore: disconnect
,2016-01-18 16:59:43.568 ThaliTest[2234:4667536] client session: disconnectFromPeer: 1453132779006.2288.yAkOuA==
,2016-01-18 16:59:43.568 ThaliTest[2234:4667536] client session: disconnect
,2016-01-18 16:59:43.568 ThaliTest[2234:4667536] client session: stateChange:2->0 1453132779006.2288.yAkOuA==
,2016-01-18 16:59:43.573 ThaliTest[2234:4667536] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
,2016-01-18 16:59:43.574 ThaliTest[2234:4667536] jxcore: disconnect
,2016-01-18 16:59:43.574 ThaliTest[2234:4667536] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-18 16:59:43.776 ThaliTest[2234:4667536] jxcore: stopBroadcasting
,2016-01-18 16:59:43.776 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 16:59:43.777 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 16:59:43.779 ThaliTest[2234:4667536] server session: disconnect
,2016-01-18 16:59:43.779 ThaliTest[2234:4667536] server session: stateChange:2->0 1453132779006.2288
,2016-01-18 16:59:43.846 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 53721
,2016-01-18 16:59:46.004 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:46.014 ThaliTest[2234:4667536] server: starting 1453132786004.2234.Z6nxng==
,2016-01-18 16:59:46.015 ThaliTest[2234:4667536] multipeer session: start timer: 0x15968810
,2016-01-18 16:59:46.019 ThaliTest[2234:4667536] THEMultipeerSession initialized peer 1453132786004.2234
,2016-01-18 16:59:46.019 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,2016-01-18 16:59:46.452 ThaliTest[2234:4667387] client: found peer: 1453132787216.2288.Wqfi3Q==
,2016-01-18 16:59:46.453 ThaliTest[2234:4667536] jxcore: connect 1453132787216.2288.Wqfi3Q==
,2016-01-18 16:59:46.454 ThaliTest[2234:4667536] client session: connect
,2016-01-18 16:59:46.454 ThaliTest[2234:4667536] client session: stateChange:0->1 1453132787216.2288.Wqfi3Q==
,2016-01-18 16:59:47.234 ThaliTest[2234:4667387] multipeer session: reset timer
,2016-01-18 16:59:47.234 ThaliTest[2234:4667387] multipeer session: stop timer
2016-01-18 16:59:47.234 ThaliTest[2234:4667387] multipeer session: start timer: 0x15968810
,2016-01-18 16:59:47.235 ThaliTest[2234:4667387] server session: connect
2016-01-18 16:59:47.235 ThaliTest[2234:4667387] server session: stateChange:0->1 1453132787216.2288
,2016-01-18 16:59:47.238 ThaliTest[2234:4667387] server: accepting invitation 1453132787216.2288
,2016-01-18 16:59:50.916 ThaliTest[2234:4668070] server session: connected
2016-01-18 16:59:50.916 ThaliTest[2234:4668070] server session: stateChange:1->2 1453132787216.2288
,2016-01-18 16:59:50.923 ThaliTest[2234:4667387] server relay: connected (to port: 53721)
,2016-01-18 16:59:50.980 ThaliTest[2234:4668070] client session: connected
2016-01-18 16:59:50.981 ThaliTest[2234:4668070] client session: stateChange:1->2 1453132787216.2288.Wqfi3Q==
,2016-01-18 16:59:51.310 ThaliTest[2234:4668070] client session: fireConnectCallback: 1453132787216.2288.Wqfi3Q==
2016-01-18 16:59:51.310 ThaliTest[2234:4668070] jxcore: connect: success
,ok 89 Should be able to connect without error
ok 90 Port should be within range
,2016-01-18 16:59:51.316 ThaliTest[2234:4667387] client: relay established
2016-01-18 16:59:51.317 ThaliTest[2234:4667387] client: new accepted socket: 0x15dc9120
,data in 5262
,data in 38325
,2016-01-18 16:59:52.220 ThaliTest[2234:4668063] server session: not connected 1453132787216.2288
,data in 103861
,data in 108405
,data in 131072
,ok 91 the test messages should be equal
,2016-01-18 16:59:52.483 ThaliTest[2234:4667536] jxcore: disconnect
2016-01-18 16:59:52.484 ThaliTest[2234:4667536] client session: disconnectFromPeer: 1453132787216.2288.Wqfi3Q==
2016-01-18 16:59:52.484 ThaliTest[2234:4667536] client session: disconnect
2016-01-18 16:59:52.484 ThaliTest[2234:4667536] client session: stateChange:2->0 1453132787216.2288.Wqfi3Q==
,2016-01-18 16:59:52.490 ThaliTest[2234:4667536] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-18 16:59:56.912 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 16:59:56.913 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
2016-01-18 16:59:56.913 ThaliTest[2234:4667536] multipeer session: stop timer
2016-01-18 16:59:56.913 ThaliTest[2234:4667536] server session: disconnect
2016-01-18 16:59:56.913 ThaliTest[2234:4667536] server session: stateChange:2->0 1453132787216.2288
,2016-01-18 16:59:56.916 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,echo server started on port: 53727
,2016-01-18 16:59:57.208 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 16:59:57.209 ThaliTest[2234:4667536] server: starting 1453132797207.2234.jwEahg==
2016-01-18 16:59:57.209 ThaliTest[2234:4667536] multipeer session: start timer: 0x15de5640
2016-01-18 16:59:57.209 ThaliTest[2234:4667536] THEMultipeerSession in,itialized peer 1453132797207.2234
2016-01-18 16:59:57.209 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-18 16:59:58.648 ThaliTest[2234:4667387] multipeer session: reset timer
2016-01-18 16:59:58.648 ThaliTest[2234:4667387] multipeer session: stop timer
2016-01-18 16:59:58.648 ThaliTest[2234:4667387] multipeer session: start timer: 0x15de5640
2016-,01-18 16:59:58.648 ThaliTest[2234:4667387] server session: connect
2016-01-18 16:59:58.648 ThaliTest[2234:4667387] server session: stateChange:0->1 1453132799222.2288
,2016-01-18 16:59:58.652 ThaliTest[2234:4667387] server: accepting invitation 1453132799222.2288
,2016-01-18 16:59:58.673 ThaliTest[2234:4667387] client: found peer: 1453132799222.2288.nlY6Iw==
[{"peerIdentifier":"1453132799222.2288.nlY6Iw==","peerName":"(null)","peerAvailable":true}]
2016-01-18 16:59:58.675 ThaliTest[2234:4667536] jxcore: connect 1453132799222.2288.nlY6Iw==
2016-01-18 16:59:58.675 ThaliTest[2234:4667536] client session: connect
2016-01-18 16:59:58.675 ThaliTest[2234:4667536] client session: stateChange:0->1 1453132799222.2288.nlY6Iw==
,2016-01-18 17:00:02.828 ThaliTest[2234:4668070] server session: connected
2016-01-18 17:00:02.828 ThaliTest[2234:4668070] server session: stateChange:1->2 1453132799222.2288
,2016-01-18 17:00:02.830 ThaliTest[2234:4667387] server relay: connected (to port: 53727)
,2016-01-18 17:00:02.837 ThaliTest[2234:4668070] client session: connected
2016-01-18 17:00:02.837 ThaliTest[2234:4668070] client session: stateChange:1->2 1453132799222.2288.nlY6Iw==
,2016-01-18 17:00:02.839 ThaliTest[2234:4668070] client session: fireConnectCallback: 1453132799222.2288.nlY6Iw==
2016-01-18 17:00:02.839 ThaliTest[2234:4668070] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 First connect should succeed
,2016-01-18 17:00:02.852 ThaliTest[2234:4667387] client: relay established
2016-01-18 17:00:02.852 ThaliTest[2234:4667387] client: new accepted socket: 0x15dcc630
,ok 97 the test messages should be equal
,ok 98 First send should succeed
,2016-01-18 17:00:02.926 ThaliTest[2234:4667387] client: socket closed
2016-01-18 17:00:02.926 ThaliTest[2234:4667387] client relay: socket disconnected
2016-01-18 17:00:02.927 ThaliTest[2234:4667387] client relay: 0x15dcc630 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-18 17:00:02.927 ThaliTest[2234:4667387] client session: socket closed: 1453132799222.2288.nlY6Iw==
2016-01-18 ,17:00:02.927 ThaliTest[2234:4667387] client session: onLinkFailure: 1453132799222.2288.nlY6Iw==
2016-01-18 17:00:02.927 ThaliTest[2234:4667387] client session: disconnect
2016-01-18 17:00:02.927 ThaliTest[2234:4667387] client session: stateChange:2->0 14,53132799222.2288.nlY6Iw==
,2016-01-18 17:00:02.931 ThaliTest[2234:4667387] client session: fireConnectionErrorEvent: 1453132799222.2288.nlY6Iw==
,2016-01-18 17:00:02.933 ThaliTest[2234:4667536] jxcore: connect 1453132799222.2288.nlY6Iw==
,2016-01-18 17:00:02.934 ThaliTest[2234:4667536] client session: connect
2016-01-18 17:00:02.935 ThaliTest[2234:4667536] client session: stateChange:0->1 1453132799222.2288.nlY6Iw==
,2016-01-18 17:00:03.026 ThaliTest[2234:4668058] server session: not connected 1453132799222.2288
,2016-01-18 17:00:03.088 ThaliTest[2234:4667387] multipeer session: reset timer
2016-01-18 17:00:03.089 ThaliTest[2234:4667387] multipeer session: stop timer
2016-01-18 17:00:03.090 ThaliTest[2234:4667387] multipeer session: start timer: 0x15de5640
2016-,01-18 17:00:03.090 ThaliTest[2234:4667387] server: disconnecting to refresh session (1453132799222.2288)
2016-01-18 17:00:03.090 ThaliTest[2234:4667387] server session: disconnect
2016-01-18 17:00:03.090 ThaliTest[2234:4667387] server session: stateChange:2->0 1453132799222.2288
,2016-01-18 17:00:03.277 ThaliTest[2234:4667387] server session: connect
2016-01-18 17:00:03.277 ThaliTest[2234:4667387] server session: stateChange:0->1 1453132799222.2288
2016-01-18 17:00:03.279 ThaliTest[2234:4667387] server: accepting invitation 1453132799222.2288
,2016-01-18 17:00:06.825 ThaliTest[2234:4668057] client session: connected
2016-01-18 17:00:06.825 ThaliTest[2234:4668057] client session: stateChange:1->2 1453132799222.2288.nlY6Iw==
,2016-01-18 17:00:07.086 ThaliTest[2234:4668197] client session: fireConnectCallback: 1453132799222.2288.nlY6Iw==
,2016-01-18 17:00:07.086 ThaliTest[2234:4668197] jxcore: connect: success
ok 99 Should be able to connect without error
ok 100 Port should be within range
ok 101 Second connect should succeed
,2016-01-18 17:00:07.100 ThaliTest[2234:4667387] client: relay established
2016-01-18 17:00:07.100 ThaliTest[2234:4667387] client: new accepted socket: 0x15dd7480
,2016-01-18 17:00:07.157 ThaliTest[2234:4668197] server session: connected
2016-01-18 17:00:07.157 ThaliTest[2234:4668197] server session: stateChange:1->2 1453132799222.2288
2016-01-18 17:00:07.159 ThaliTest[2234:4667387] server relay: connected (to port: 53727)
,ok 102 the test messages should be equal
,ok 103 Second send should succeed
,# setup
,2016-01-18 17:00:07.176 ThaliTest[2234:4667387] client: socket closed
2016-01-18 17:00:07.176 ThaliTest[2234:4667387] client relay: socket disconnected
2016-01-18 17:00:07.177 ThaliTest[2234:4667387] client relay: 0x15dd7480 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-18 17:00:07.177 ThaliTest[2234:4667387] client session: socket closed: 1453132799222.2288.nlY6Iw==
2016-01-18 ,17:00:07.177 ThaliTest[2234:4667387] client session: onLinkFailure: 1453132799222.2288.nlY6Iw==
2016-01-18 17:00:07.177 ThaliTest[2234:4667387] client session: disconnect
2016-01-18 17:00:07.177 ThaliTest[2234:4667387] client session: stateChange:2->0 14,53132799222.2288.nlY6Iw==
,2016-01-18 17:00:07.180 ThaliTest[2234:4667387] client session: fireConnectionErrorEvent: 1453132799222.2288.nlY6Iw==
,2016-01-18 17:00:07.283 ThaliTest[2234:4668070] server session: not connected 1453132799222.2288
,calling stopBroadcasting
2016-01-18 17:00:07.820 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 17:00:07.820 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 17:00:07.820 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 17:00:07.820 ThaliTest[2234:4667536] server session: disconnect
2016-01-18 17:00:07.820 ThaliTest[2234:4667536] server session: stateChange:2->0 1453132799222.2288
2016-01-18 17:00:07.822 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C38BE19C-11CF-4525-A356-C71F2550FF81/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 104 starting event should occur in right order
2016-01-18 17:00:14.064 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 17:00:14.066 ThaliTest[2234:4667536] server: starting eZmb8BwK0mIYuCnydkHhJA.ncyemw==
2016-01-18 17:00:14.066 ThaliTest[2234:4667536] multipeer session: start timer: 0x158a02c0
2016-01-18 17:00:14.067 ThaliTest[2234:4667536] THEMultipeerSessio,n initialized peer eZmb8BwK0mIYuCnydkHhJA
2016-01-18 17:00:14.067 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
ok 105 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 106 stopping event should occur in right order
About to call stopBroadcasting
2016-01-18 17:00:14.068 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 17:00:14.068 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 17:00:14.068 ThaliTest[2234:4667536] multipeer session: stop timer
2016-01-18 17:00:14.071 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 107 stopped event should occur in right order
mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C38BE19C-11CF-4525-A356-C71F2550FF81/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-18 17:00:15.166 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 17:00:15.168 ThaliTest[2234:4667536] server: starting eZmb8BwK0mIYuCnydkHhJA.fCrUkA==
2016-01-18 17:00:15.168 ThaliTest[2234:4667536] multipeer session: start timer: 0x158af140
2016-01-18 17:00:15.169 ThaliTest[2234:4667536] THEMultipeerSession initialized peer eZmb8BwK0mIYuCnydkHhJA
2016-01-18 17:00:15.169 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error
ok 109 deviceName should not be null
Now in TRM stop
State of this._isStar,ted: true
About to call stopBroadcasting
2016-01-18 17:00:15.170 ThaliTest[2234:4667536] jxcore: stopBroadcasting
2016-01-18 17:00:15.170 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 17:00:15.170 ThaliTest[2234:4667536] multipeer session: stop timer
2016-01-18 17:00:15.173 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
# setup
,# ThaliReplicationManager replicates database
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C38BE19C-11CF-4525-A356-C71F2550FF81/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-18 17:00:16.781 ThaliTest[2234:4667536] jxcore: startBroadcasting
,2016-01-18 17:00:16.783 ThaliTest[2234:4667536] server: starting eZmb8BwK0mIYuCnydkHhJA.5GIvug==
,2016-01-18 17:00:16.786 ThaliTest[2234:4667536] multipeer session: start timer: 0x18181620
,2016-01-18 17:00:16.787 ThaliTest[2234:4667536] THEMultipeerSession initialized peer eZmb8BwK0mIYuCnydkHhJA
,2016-01-18 17:00:16.788 ThaliTest[2234:4667536] jxcore: startBroadcasting: success
,ok 110 getDeviceIdentity should not return an error
,ok 111 deviceName should not be null
,2016-01-18 17:00:17.976 ThaliTest[2234:4667387] client: found peer: yCstZ4Sd0RTetg_9toXX5w.0pWsNA==
,2016-01-18 17:00:21.471 ThaliTest[2234:4667536] jxcore: connect yCstZ4Sd0RTetg_9toXX5w.0pWsNA==
,2016-01-18 17:00:21.472 ThaliTest[2234:4667536] client session: connect
,2016-01-18 17:00:21.473 ThaliTest[2234:4667536] client session: stateChange:0->1 yCstZ4Sd0RTetg_9toXX5w.0pWsNA==
,ok 112 Should be able to put doc without error
,2016-01-18 17:00:21.571 ThaliTest[2234:4667387] multipeer session: reset timer
2016-01-18 17:00:21.571 ThaliTest[2234:4667387] multipeer session: stop timer
2016-01-18 17:00:21.571 ThaliTest[2234:4667387] multipeer session: start timer: 0x18181620
2016-01-18 17:00:21.571 ThaliTest[2234:4667387] server session: connect
2016-01-18 17:00:21.572 ThaliTest[2234:4667387] server session: stateChange:0->1 yCstZ4Sd0RTetg_9toXX5w
2016-01-18 17:00:21.574 ThaliTest[2234:4667387] server: accepting invitation yCstZ4Sd0RTetg_9toXX5w
,ok 113 1st change of local doc should contain local id
,2016-01-18 17:00:25.774 ThaliTest[2234:4668063] server session: connected
2016-01-18 17:00:25.774 ThaliTest[2234:4668063] server session: stateChange:1->2 yCstZ4Sd0RTetg_9toXX5w
,2016-01-18 17:00:25.825 ThaliTest[2234:4667387] server relay: connected (to port: 53742)
,server bridge: new client socket
,2016-01-18 17:00:25.894 ThaliTest[2234:4668070] client session: connected
2016-01-18 17:00:25.894 ThaliTest[2234:4668070] client session: stateChange:1->2 yCstZ4Sd0RTetg_9toXX5w.0pWsNA==
,2016-01-18 17:00:25.904 ThaliTest[2234:4668070] client session: fireConnectCallback: yCstZ4Sd0RTetg_9toXX5w.0pWsNA==
2016-01-18 17:00:25.905 ThaliTest[2234:4668070] jxcore: connect: success
2016-01-18 17:00:25.909 ThaliTest[2234:4667387] client: relay es,tablished
2016-01-18 17:00:25.909 ThaliTest[2234:4667387] client: new accepted socket: 0x15aaf6c0
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
,ok 114 1st change of remote doc should contain remote id
,ok 115 Can update remote doc without error
,null
,{ ok: true,
  id: '3990b48d-53a6-4446-88ac-110c6983e5c2',
  rev: '2-0498dec918d14fba76a783a101cc2256' }
,ok 116 Remote changes occur in strict order
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
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
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,2016-01-18 17:01:51.567 ThaliTest[2234:4667387] multipeer session: restart
,2016-01-18 17:01:51.774 ThaliTest[2234:4667387] client: found peer: yCstZ4Sd0RTetg_9toXX5w.0pWsNA==
,2016-01-18 17:01:52.260 ThaliTest[2234:4667387] client: found peer: yCstZ4Sd0RTetg_9toXX5w.0pWsNA==
2016-01-18 17:01:52.260 ThaliTest[2234:4667387] multipeer session: restart
,2016-01-18 17:01:52.276 ThaliTest[2234:4667387] client: found peer: yCstZ4Sd0RTetg_9toXX5w.0pWsNA==
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,ok 117 Local changes occur in strict order
,ok 118 2nd change of local doc should contain remote id
,# setup
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,Now in TRM stop
State of this._isStarted: true
,About to call stopBroadcasting
,2016-01-18 17:01:57.961 ThaliTest[2234:4667536] jxcore: stopBroadcasting
,2016-01-18 17:01:57.961 ThaliTest[2234:4667536] THEMultipeerSession stopping peer
,2016-01-18 17:01:57.961 ThaliTest[2234:4667536] multipeer session: stop timer
,2016-01-18 17:01:57.962 ThaliTest[2234:4667536] client session: disconnect
,2016-01-18 17:01:57.964 ThaliTest[2234:4667536] client session: stateChange:2->0 yCstZ4Sd0RTetg_9toXX5w.0pWsNA==
,2016-01-18 17:01:57.968 ThaliTest[2234:4667536] server session: disconnect
,2016-01-18 17:01:57.974 ThaliTest[2234:4667536] server session: stateChange:2->0 yCstZ4Sd0RTetg_9toXX5w
,2016-01-18 17:01:58.036 ThaliTest[2234:4667536] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
,mux server bridge listener closed
,client bridge: socket closed
,server bridge: socket closed
,# teardown
,ok 119 should be equal
,# setup
,# #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
,client bridge: socket closed
,client bridge: socket closed
,# teardown
,ok 120 should not be equal
# setup
,appEnteredForeground wasn't registered

```
