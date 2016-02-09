#### Test 583805004251330_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/583805004251330/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/66CBDBAC-E935-41EA-822D-BAA9EFBE75BC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/66CBDBAC-E935-41EA-822D-BAA9EFBE75BC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/583805004251330/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/583805004251330/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53572"
,(lldb)     command script import "/tmp/66CBDBAC-E935-41EA-822D-BAA9EFBE75BC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 17:05:13.079 ThaliTest[1146:1784188] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/32EC96DB-1149-4BC6-8D6D-B01B7AC2DE9B/Library/Cookies/Cookies.binarycookies
,2016-02-09 17:05:13.557 ThaliTest[1146:1784188] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 17:05:13.558 ThaliTest[1146:1784188] Multi-tasking -> Device: YES, App: YES
,2016-02-09 17:05:13.567 ThaliTest[1146:1784188] Unlimited access to network resources
,2016-02-09 17:05:13.576 ThaliTest[1146:1784188] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 17:05:23.438 ThaliTest[1146:1784188] Resetting plugins due to page load.
,2016-02-09 17:05:27.355 ThaliTest[1146:1784188] Finished load of: file:///var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/index.html
,2016-02-09 17:05:27.520 ThaliTest[1146:1784188] JXcore Cordova plugin initializing
,2016-02-09 17:05:27.520 ThaliTest[1146:1784443] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7A8CBB64-4F65-4870-8C84-6FB06750414B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout

,ok 3 firstPromise result

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

,ok 6 secondPromise result

,ok 7 secondPromise testValue

,ok 8 thirdPromise in promise

,ok 9 thirdPromise result

,ok 10 thirdPromise testValue

,# setup

,# basic

,# teardown

,ok 11 sane

,# setup

,# another

,# teardown

,ok 12 sane

,# setup

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

,ok 16 should be equal

,ok 17 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

,ok 21 should be equal

ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 23 should be equal

,# setup

,# failed to get mobile documents path

,# teardown

,ok 24 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 25 should be equal

,ok 26 should be equal

,ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 29 should throw

,# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

,# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 32 should throw

,# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 33 should throw

,# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

,ok 36 should be equal

,ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

,ok 39 should be equal

,ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

,ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

,ok 46 should be equal

,ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

,ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

,ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# #start should fail if called twice in a row

,# teardown

,ok 54 specific error should be received

,# setup

,# #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 55 specific error should be returned

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,# setup

,# should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 58 error should be null

,ok 59 error should be null

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 60 error should be null

,ok 61 error should be null

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 62 specific error should be returned

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 17:09:51.235 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.251 ThaliTest[1146:1784443] server: starting 1455034191234.1146.A/Es3A==
,2016-02-09 17:09:51.253 ThaliTest[1146:1784443] multipeer session: start timer: 0x188dc260
,2016-02-09 17:09:51.253 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034191234.1146
,2016-02-09 17:09:51.254 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

2016-02-09 17:09:51.257 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:51.258 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
2016-02-09 17:09:51.258 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:51.259 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

2016-02-09 17:09:51.261 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.266 ThaliTest[1146:1784443] server: starting 1455034191261.1146.a5pfiQ==
2016-02-09 17:09:51.267 ThaliTest[1146:1784443] multipeer session: start timer: 0x18915150
2016-02-09 17:09:51.267 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034191261.1146
2016-02-09 17:09:51.268 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

2016-02-09 17:09:51.271 ThaliTest[1146:1784443] jxcore: stopBroadcasting
2016-02-09 17:09:51.272 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
2016-02-09 17:09:51.272 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:51.273 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
ok 66 Should be able to call stopBroadcasting without error

2016-02-09 17:09:51.275 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.280 ThaliTest[1146:1784443] server: starting 1455034191275.1146.0dJS5A==
2016-02-09 17:09:51.281 ThaliTest[1146:1784443] multipeer session: start timer: 0x17edcf00
2016-02-09 17:09:51.282 ThaliTest[1146:1784443] THEMultipeerSession in,itialized peer 1455034191275.1146
2016-02-09 17:09:51.282 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
ok 67 Should be able to call startBroadcasting without error

2016-02-09 17:09:51.284 ThaliTest[1146:1784443] jxcore: stopBroadcasting,
2016-02-09 17:09:51.284 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
2016-02-09 17:09:51.284 ThaliTest[1146:1784443] multipeer session: stop timer
2016-02-09 17:09:51.285 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
ok 68 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:51.288 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.297 ThaliTest[1146:1784443] server: starting 1455034191287.1146.RvVUFg==
,2016-02-09 17:09:51.299 ThaliTest[1146:1784443] multipeer session: start timer: 0x188def20
,2016-02-09 17:09:51.306 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034191287.1146
,2016-02-09 17:09:51.307 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-09 17:09:51.309 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:51.310 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:09:51.311 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:51.315 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:51.318 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.323 ThaliTest[1146:1784443] server: starting 1455034191317.1146.7u130g==
,2016-02-09 17:09:51.325 ThaliTest[1146:1784443] multipeer session: start timer: 0x188dccf0
,2016-02-09 17:09:51.327 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034191317.1146
,2016-02-09 17:09:51.330 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 17:09:51.335 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:51.335 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:09:51.336 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:51.338 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:51.344 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.346 ThaliTest[1146:1784443] server: starting 1455034191343.1146.Paen5g==
,2016-02-09 17:09:51.347 ThaliTest[1146:1784443] multipeer session: start timer: 0x188df3d0
,2016-02-09 17:09:51.351 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034191343.1146
,2016-02-09 17:09:51.352 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-09 17:09:51.354 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:51.355 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:09:51.355 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:51.357 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:51.360 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.363 ThaliTest[1146:1784443] server: starting 1455034191360.1146.lL8UgA==
,2016-02-09 17:09:51.364 ThaliTest[1146:1784443] multipeer session: start timer: 0x188df3d0
,2016-02-09 17:09:51.367 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034191360.1146
,2016-02-09 17:09:51.368 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-09 17:09:51.371 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:51.371 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:09:51.372 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:51.373 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:51.377 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.379 ThaliTest[1146:1784443] server: starting 1455034191376.1146.K5bn4Q==
,2016-02-09 17:09:51.380 ThaliTest[1146:1784443] multipeer session: start timer: 0x18d40e70
,2016-02-09 17:09:51.384 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034191376.1146
,2016-02-09 17:09:51.385 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 17:09:51.387 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:51.388 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:09:51.388 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:51.389 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:51.392 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.395 ThaliTest[1146:1784443] server: starting 1455034191392.1146.eCIYrw==
,2016-02-09 17:09:51.396 ThaliTest[1146:1784443] multipeer session: start timer: 0x18d42310
,2016-02-09 17:09:51.400 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034191392.1146
,2016-02-09 17:09:51.401 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 17:09:51.403 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:51.404 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:09:51.404 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:51.406 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 17:09:51.409 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.412 ThaliTest[1146:1784443] server: starting 1455034191409.1146.y/QPPQ==
,2016-02-09 17:09:51.414 ThaliTest[1146:1784443] multipeer session: start timer: 0x18d41760
,2016-02-09 17:09:51.416 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034191409.1146
,2016-02-09 17:09:51.417 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 17:09:51.419 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:51.420 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:09:51.420 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:51.421 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 17:09:51.707 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.711 ThaliTest[1146:1784443] server: starting 1455034191707.1146.pBBMAg==
,2016-02-09 17:09:51.713 ThaliTest[1146:1784443] multipeer session: start timer: 0x188df070
,2016-02-09 17:09:51.720 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034191707.1146
,2016-02-09 17:09:51.720 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-09 17:09:51.724 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:51.726 ThaliTest[1146:1784443] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

,2016-02-09 17:09:51.730 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:51.731 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:09:51.732 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:51.734 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 17:09:52.183 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:52.187 ThaliTest[1146:1784443] server: starting 1455034192183.1146.xmbtQg==
,2016-02-09 17:09:52.188 ThaliTest[1146:1784443] multipeer session: start timer: 0x189e7da0
,2016-02-09 17:09:52.188 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034192183.1146
,2016-02-09 17:09:52.189 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

,2016-02-09 17:09:52.192 ThaliTest[1146:1784443] jxcore: connect foobar
2016-02-09 17:09:52.193 ThaliTest[1146:1784443] client: unknown peer foobar
2016-02-09 17:09:52.193 ThaliTest[1146:1784443] jxcore: connect: fail: Unknown peer
ok 87 Should not connect to a bad peer

,2016-02-09 17:09:52.197 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:52.197 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:09:52.198 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:09:52.199 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 17:09:52.689 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:52.693 ThaliTest[1146:1784443] server: starting 1455034192689.1146.Vubr5g==
,2016-02-09 17:09:52.694 ThaliTest[1146:1784443] multipeer session: start timer: 0x18d471b0
2016-02-09 17:09:52.694 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034192689.1146
2016-02-09 17:09:52.695 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

,2016-02-09 17:09:52.697 ThaliTest[1146:1784443] jxcore: disconnect
,2016-02-09 17:09:52.697 ThaliTest[1146:1784443] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

2016-02-09 17:09:52.701 ThaliTest[1146:1784443] jxcore: stopBroadcasting
2016-02-09 17:09:52.701 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
2016-02-09 17:09:52.701 ThaliTest[1146:1784443] multipeer session: stop timer
2016-02-09 17:09:52.702 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 17:09:54.627 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:54.631 ThaliTest[1146:1784443] server: starting 1455034194626.1146.c45i5A==
,2016-02-09 17:09:54.632 ThaliTest[1146:1784443] multipeer session: start timer: 0x18d4a450
2016-02-09 17:09:54.632 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034194626.1146
2016-02-09 17:09:54.633 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-09 17:09:55.429 ThaliTest[1146:1784188] client: found peer: 1455034192601.1679.6iRk8g==
,2016-02-09 17:09:55.432 ThaliTest[1146:1784443] jxcore: connect 1455034192601.1679.6iRk8g==
,2016-02-09 17:09:55.433 ThaliTest[1146:1784443] client session: connect
,2016-02-09 17:09:55.433 ThaliTest[1146:1784443] client session: stateChange:0->1 1455034192601.1679.6iRk8g==
,2016-02-09 17:09:56.066 ThaliTest[1146:1784188] multipeer session: reset timer
2016-02-09 17:09:56.066 ThaliTest[1146:1784188] multipeer session: stop timer
,2016-02-09 17:09:56.067 ThaliTest[1146:1784188] multipeer session: start timer: 0x18d4a450
2016-02-09 17:09:56.068 ThaliTest[1146:1784188] server session: connect
2016-02-09 17:09:56.068 ThaliTest[1146:1784188] server session: stateChange:0->1 1455034192601.1679
,2016-02-09 17:09:56.074 ThaliTest[1146:1784188] server: accepting invitation 1455034192601.1679
,2016-02-09 17:09:58.152 ThaliTest[1146:1784949] client session: connected
2016-02-09 17:09:58.152 ThaliTest[1146:1784949] client session: stateChange:1->2 1455034192601.1679.6iRk8g==
,2016-02-09 17:09:58.158 ThaliTest[1146:1784949] client session: fireConnectCallback: 1455034192601.1679.6iRk8g==
2016-02-09 17:09:58.158 ThaliTest[1146:1784949] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 17:09:58.164 ThaliTest[1146:1784443] jxcore: disconnect
,2016-02-09 17:09:58.165 ThaliTest[1146:1784443] client session: disconnectFromPeer: 1455034192601.1679.6iRk8g==
2016-02-09 17:09:58.165 ThaliTest[1146:1784443] client session: disconnect
2016-02-09 17:09:58.166 ThaliTest[1146:1784443] client session: stateChange:2->0 1455034192601.1679.6iRk8g==
,2016-02-09 17:09:58.238 ThaliTest[1146:1784443] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 17:09:58.548 ThaliTest[1146:1784950] server session: connected
2016-02-09 17:09:58.549 ThaliTest[1146:1784950] server session: stateChange:1->2 1455034192601.1679
,2016-02-09 17:09:58.552 ThaliTest[1146:1784188] server relay: socket disconnected
2016-02-09 17:09:58.553 ThaliTest[1146:1784188] server relay: 0x188e7230 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 17:09:58.608 ThaliTest[1146:1784917] server session: not connected 1455034192601.1679
,calling stopBroadcasting

,2016-02-09 17:09:58.986 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:09:58.986 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:09:58.987 ThaliTest[1146:1784443] multipeer session: stop timer
2016-02-09 17:09:58.988 ThaliTest[1146:1784443] server session: disconnect
2016-02-09 17:09:58.988 ThaliTest[1146:1784443] server session: stateChange:2->0 1455034192601.1679
,2016-02-09 17:09:58.992 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 17:09:59.495 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:09:59.499 ThaliTest[1146:1784443] server: starting 1455034199495.1146.2BDUpA==
,2016-02-09 17:09:59.500 ThaliTest[1146:1784443] multipeer session: start timer: 0x18d4b6f0
2016-02-09 17:09:59.500 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034199495.1146
2016-02-09 17:09:59.501 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error

,2016-02-09 17:10:00.225 ThaliTest[1146:1784188] client: found peer: 1455034192601.1679.6iRk8g==
,2016-02-09 17:10:00.228 ThaliTest[1146:1784443] jxcore: connect 1455034192601.1679.6iRk8g==
2016-02-09 17:10:00.228 ThaliTest[1146:1784443] client session: connect
,2016-02-09 17:10:00.229 ThaliTest[1146:1784443] client session: stateChange:0->1 1455034192601.1679.6iRk8g==
,2016-02-09 17:10:00.665 ThaliTest[1146:1784188] client: found peer: 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:00.667 ThaliTest[1146:1784443] jxcore: connect 1455034197797.1679.+BHUCA==
2016-02-09 17:10:00.667 ThaliTest[1146:1784443] client session: connect
2016-02-09 17:10:00.668 ThaliTest[1146:1784443] client session: stateChange:0->1 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:00.756 ThaliTest[1146:1784188] multipeer session: reset timer
2016-02-09 17:10:00.756 ThaliTest[1146:1784188] multipeer session: stop timer
,2016-02-09 17:10:00.757 ThaliTest[1146:1784188] multipeer session: start timer: 0x18d4b6f0
2016-02-09 17:10:00.757 ThaliTest[1146:1784188] server session: connect
,2016-02-09 17:10:00.758 ThaliTest[1146:1784188] server session: stateChange:0->1 1455034197797.1679
,2016-02-09 17:10:00.764 ThaliTest[1146:1784188] server: accepting invitation 1455034197797.1679
,2016-02-09 17:10:03.171 ThaliTest[1146:1784916] server session: connected
2016-02-09 17:10:03.171 ThaliTest[1146:1784916] server session: stateChange:1->2 1455034197797.1679
,2016-02-09 17:10:03.204 ThaliTest[1146:1784916] client session: connected
2016-02-09 17:10:03.204 ThaliTest[1146:1784916] client session: stateChange:1->2 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:03.207 ThaliTest[1146:1784188] server relay: socket disconnected
2016-02-09 17:10:03.208 ThaliTest[1146:1784188] server relay: 0x18d53e60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 17:10:03.222 ThaliTest[1146:1784949] client session: fireConnectCallback: 1455034197797.1679.+BHUCA==
2016-02-09 17:10:03.222 ThaliTest[1146:1784949] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-09 17:10:03.226 ThaliTest[1146:1784443] jxcore: connect 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:03.227 ThaliTest[1146:1784443] client: already connect(ing/ed) to 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:03.228 ThaliTest[1146:1784443] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

2016-02-09 17:10:03.231 ThaliTest[1146:1784443] jxcore: disconnect
,2016-02-09 17:10:03.231 ThaliTest[1146:1784443] client session: disconnectFromPeer: 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:03.232 ThaliTest[1146:1784443] client session: disconnect
,2016-02-09 17:10:03.233 ThaliTest[1146:1784443] client session: stateChange:2->0 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:03.261 ThaliTest[1146:1784949] server session: not connected 1455034197797.1679
,2016-02-09 17:10:03.277 ThaliTest[1146:1784443] jxcore: disconnect: success
ok 100 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 17:10:03.694 ThaliTest[1146:1784443] jxcore: stopBroadcasting
2016-02-09 17:10:03.695 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
2016-02-09 17:10:03.695 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:10:03.696 ThaliTest[1146:1784443] client session: disconnect
2016-02-09 17:10:03.696 ThaliTest[1146:1784443] client session: stateChange:1->0 1455034192601.1679.6iRk8g==
,2016-02-09 17:10:03.697 ThaliTest[1146:1784443] server session: disconnect
2016-02-09 17:10:03.697 ThaliTest[1146:1784443] server session: stateChange:2->0 1455034197797.1679
,2016-02-09 17:10:03.699 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 17:10:04.213 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:10:04.216 ThaliTest[1146:1784443] server: starting 1455034204212.1146.ULzrQg==
,2016-02-09 17:10:04.217 ThaliTest[1146:1784443] multipeer session: start timer: 0x18d523a0
2016-02-09 17:10:04.218 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034204212.1146
2016-02-09 17:10:04.218 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-09 17:10:04.810 ThaliTest[1146:1784188] client: found peer: 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:04.812 ThaliTest[1146:1784443] jxcore: connect 1455034197797.1679.+BHUCA==
2016-02-09 17:10:04.812 ThaliTest[1146:1784443] client session: connect
2016-02-09 17:10:04.813 ThaliTest[1146:1784443] client session: stateChange:0->1 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:05.549 ThaliTest[1146:1784188] client: lost peer: 1455034197797.1679.+BHUCA==
2016-02-09 17:10:05.549 ThaliTest[1146:1784188] client session: onPeerLost: 1455034197797.1679.+BHUCA==
2016-02-09 17:10:05.550 ThaliTest[1146:1784188] client ,session: onLinkFailure: 1455034197797.1679.+BHUCA==
2016-02-09 17:10:05.550 ThaliTest[1146:1784188] client session: disconnect
2016-02-09 17:10:05.550 ThaliTest[1146:1784188] client session: stateChange:1->0 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:05.551 ThaliTest[1146:1784188] client session: fireConnectCallback: 1455034197797.1679.+BHUCA==
2016-02-09 17:10:05.551 ThaliTest[1146:1784188] jxcore: connect: fail: Peer disconnected
,2016-02-09 17:10:06.505 ThaliTest[1146:1784188] client: found peer: 1455034202518.1679.ZGlmpQ==
,2016-02-09 17:10:06.507 ThaliTest[1146:1784443] jxcore: connect 1455034202518.1679.ZGlmpQ==
2016-02-09 17:10:06.508 ThaliTest[1146:1784443] client session: connect
,2016-02-09 17:10:06.508 ThaliTest[1146:1784443] client session: stateChange:0->1 1455034202518.1679.ZGlmpQ==
,2016-02-09 17:10:06.554 ThaliTest[1146:1784443] jxcore: connect 1455034197797.1679.+BHUCA==
2016-02-09 17:10:06.555 ThaliTest[1146:1784443] client: connect: unreachable 1455034197797.1679.+BHUCA==
,2016-02-09 17:10:06.556 ThaliTest[1146:1784443] jxcore: connect: fail: Peer unreachable
,2016-02-09 17:10:06.701 ThaliTest[1146:1784188] multipeer session: reset timer
2016-02-09 17:10:06.702 ThaliTest[1146:1784188] multipeer session: stop timer
2016-02-09 17:10:06.702 ThaliTest[1146:1784188] multipeer session: start timer: 0x18d523a0
2016-02-09 17:10:06.702 ThaliTest[1146:1784188] server session: connect
2016-02-09 17:10:06.703 ThaliTest[1146:1784188] server session: stateChange:0->1 1455034202518.1679
,2016-02-09 17:10:06.709 ThaliTest[1146:1784188] server: accepting invitation 1455034202518.1679
,2016-02-09 17:10:09.191 ThaliTest[1146:1784912] client session: connected
2016-02-09 17:10:09.191 ThaliTest[1146:1784912] client session: stateChange:1->2 1455034202518.1679.ZGlmpQ==
,2016-02-09 17:10:09.209 ThaliTest[1146:1784917] client session: fireConnectCallback: 1455034202518.1679.ZGlmpQ==
2016-02-09 17:10:09.210 ThaliTest[1146:1784917] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-09 17:10:09.214 ThaliTest[1146:1784443] jxcore: disconnect
,2016-02-09 17:10:09.214 ThaliTest[1146:1784443] client session: disconnectFromPeer: 1455034202518.1679.ZGlmpQ==
,2016-02-09 17:10:09.214 ThaliTest[1146:1784443] client session: disconnect
,2016-02-09 17:10:09.215 ThaliTest[1146:1784443] client session: stateChange:2->0 1455034202518.1679.ZGlmpQ==
,2016-02-09 17:10:09.293 ThaliTest[1146:1784443] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error

,2016-02-09 17:10:09.295 ThaliTest[1146:1784443] jxcore: disconnect
2016-02-09 17:10:09.296 ThaliTest[1146:1784443] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 17:10:11.726 ThaliTest[1146:1784916] server session: connected
2016-02-09 17:10:11.726 ThaliTest[1146:1784916] server session: stateChange:1->2 1455034202518.1679
,2016-02-09 17:10:11.938 ThaliTest[1146:1784188] server relay: socket disconnected
,2016-02-09 17:10:11.939 ThaliTest[1146:1784188] server relay: 0x17ff8a70 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting

,2016-02-09 17:10:11.977 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:10:11.978 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:10:11.979 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:10:11.979 ThaliTest[1146:1784443] server session: disconnect
,2016-02-09 17:10:11.981 ThaliTest[1146:1784443] server session: stateChange:2->0 1455034202518.1679
,2016-02-09 17:10:12.066 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 56567

,2016-02-09 17:10:14.042 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:10:14.043 ThaliTest[1146:1784443] server: starting 1455034214042.1146.fCKSEg==
,2016-02-09 17:10:14.043 ThaliTest[1146:1784443] multipeer session: start timer: 0x189c46a0
2016-02-09 17:10:14.044 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034214042.1146
,2016-02-09 17:10:14.044 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 106 Should be able to call startBroadcasting without error

,2016-02-09 17:10:15.459 ThaliTest[1146:1784188] client: found peer: 1455034212406.1679.OOTR4g==
,2016-02-09 17:10:15.460 ThaliTest[1146:1784443] jxcore: connect 1455034212406.1679.OOTR4g==
2016-02-09 17:10:15.460 ThaliTest[1146:1784443] client session: connect
2016-02-09 17:10:15.461 ThaliTest[1146:1784443] client session: stateChange:0->1 1455034212406.1679.OOTR4g==
,2016-02-09 17:10:15.854 ThaliTest[1146:1784188] multipeer session: reset timer
2016-02-09 17:10:15.855 ThaliTest[1146:1784188] multipeer session: stop timer
,2016-02-09 17:10:15.855 ThaliTest[1146:1784188] multipeer session: start timer: 0x189c46a0
,2016-02-09 17:10:15.855 ThaliTest[1146:1784188] server session: connect
,2016-02-09 17:10:15.856 ThaliTest[1146:1784188] server session: stateChange:0->1 1455034212406.1679
,2016-02-09 17:10:15.863 ThaliTest[1146:1784188] server: accepting invitation 1455034212406.1679
,2016-02-09 17:10:18.467 ThaliTest[1146:1784917] client session: connected
,2016-02-09 17:10:18.468 ThaliTest[1146:1784917] client session: stateChange:1->2 1455034212406.1679.OOTR4g==
,2016-02-09 17:10:18.533 ThaliTest[1146:1785077] client session: fireConnectCallback: 1455034212406.1679.OOTR4g==
2016-02-09 17:10:18.533 ThaliTest[1146:1785077] jxcore: connect: success
,ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 17:10:18.539 ThaliTest[1146:1784188] client: relay established
2016-02-09 17:10:18.540 ThaliTest[1146:1784188] client: new accepted socket: 0x17e9a7e0
,2016-02-09 17:10:18.600 ThaliTest[1146:1784912] server session: connected
2016-02-09 17:10:18.601 ThaliTest[1146:1784912] server session: stateChange:1->2 1455034212406.1679
,2016-02-09 17:10:18.607 ThaliTest[1146:1784188] server relay: connected (to port: 56567)
,data in 1095

,data in 2190

,data in 3285

,data in 4380

,data in 5475

,data in 6570

,data in 7665

,data in 8760

,data in 9855

,data in 10950

,data in 12045

,data in 13140

,data in 14235

,data in 15330

,data in 16425

,data in 17520

,data in 18615

,data in 19710

,data in 20805

,data in 21900

,data in 22995

,data in 25185

,data in 45990

,data in 47085

,data in 49275

,data in 50370

,2016-02-09 17:10:45.857 ThaliTest[1146:1784188] multipeer session: restart
,2016-02-09 17:10:45.892 ThaliTest[1146:1784188] client: found peer: 1455034212406.1679.OOTR4g==
,data in 51465

,data in 52560

,data in 53655

,data in 54750

,data in 55845

,data in 56940

,data in 58035

,2016-02-09 17:11:15.857 ThaliTest[1146:1784188] multipeer session: restart
,2016-02-09 17:11:15.883 ThaliTest[1146:1784188] client: found peer: 1455034212406.1679.OOTR4g==
,data in 59130

,data in 63510

,data in 97455

,data in 98550

,data in 99645

,data in 100740

,data in 101835

,data in 102930

,data in 104025

,data in 105120

,data in 106215

,data in 107310

,data in 108405

,data in 109500

,data in 110595

,data in 111690

,data in 117165

,data in 118260

,data in 119355

,data in 123735

,data in 124830

,data in 125925

,data in 127020

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 17:11:43.008 ThaliTest[1146:1784443] jxcore: disconnect
,2016-02-09 17:11:43.008 ThaliTest[1146:1784443] client session: disconnectFromPeer: 1455034212406.1679.OOTR4g==
,2016-02-09 17:11:43.009 ThaliTest[1146:1784443] client session: disconnect
,2016-02-09 17:11:43.009 ThaliTest[1146:1784443] client session: stateChange:2->0 1455034212406.1679.OOTR4g==
,2016-02-09 17:11:43.016 ThaliTest[1146:1784443] jxcore: disconnect: success
ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 17:11:45.857 ThaliTest[1146:1784188] multipeer session: restart
,2016-02-09 17:11:45.884 ThaliTest[1146:1784188] client: found peer: 1455034212406.1679.OOTR4g==
,calling stopBroadcasting

,2016-02-09 17:11:47.388 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:11:47.389 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:11:47.390 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:11:47.391 ThaliTest[1146:1784443] server session: disconnect
2016-02-09 17:11:47.391 ThaliTest[1146:1784443] server session: stateChange:2->0 1455034212406.1679
,2016-02-09 17:11:47.408 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 56576

,2016-02-09 17:11:47.563 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:11:47.567 ThaliTest[1146:1784443] server: starting 1455034307562.1146.BAatuA==
,2016-02-09 17:11:47.567 ThaliTest[1146:1784443] multipeer session: start timer: 0x18853030
,2016-02-09 17:11:47.568 ThaliTest[1146:1784443] THEMultipeerSession initialized peer 1455034307562.1146
2016-02-09 17:11:47.569 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error

,2016-02-09 17:11:48.520 ThaliTest[1146:1784188] client: found peer: 1455034212406.1679.OOTR4g==
,[{"peerIdentifier":"1455034212406.1679.OOTR4g==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 17:11:48.524 ThaliTest[1146:1784443] jxcore: connect 1455034212406.1679.OOTR4g==
,2016-02-09 17:11:48.525 ThaliTest[1146:1784443] client session: connect
,2016-02-09 17:11:48.525 ThaliTest[1146:1784443] client session: stateChange:0->1 1455034212406.1679.OOTR4g==
,2016-02-09 17:11:48.660 ThaliTest[1146:1784188] client: found peer: 1455034305863.1679.uEOCMQ==
,[{"peerIdentifier":"1455034305863.1679.uEOCMQ==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 17:11:48.662 ThaliTest[1146:1784443] jxcore: connect 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:48.662 ThaliTest[1146:1784443] client session: connect
2016-02-09 17:11:48.663 ThaliTest[1146:1784443] client session: stateChange:0->1 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:48.916 ThaliTest[1146:1784188] multipeer session: reset timer
2016-02-09 17:11:48.917 ThaliTest[1146:1784188] multipeer session: stop timer
,2016-02-09 17:11:48.917 ThaliTest[1146:1784188] multipeer session: start timer: 0x18853030
,2016-02-09 17:11:48.917 ThaliTest[1146:1784188] server session: connect
2016-02-09 17:11:48.918 ThaliTest[1146:1784188] server session: stateChange:0->1 1455034305863.1679
,2016-02-09 17:11:48.924 ThaliTest[1146:1784188] server: accepting invitation 1455034305863.1679
,2016-02-09 17:11:51.534 ThaliTest[1146:1785227] client session: connected
,2016-02-09 17:11:51.534 ThaliTest[1146:1785227] client session: stateChange:1->2 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:51.564 ThaliTest[1146:1785078] client session: fireConnectCallback: 1455034305863.1679.uEOCMQ==
2016-02-09 17:11:51.564 ThaliTest[1146:1785078] jxcore: connect: success
,ok 112 Should be able to connect without error

,ok 113 Port should be within range

,ok 114 First connect should succeed

,2016-02-09 17:11:51.623 ThaliTest[1146:1784188] client: relay established
,2016-02-09 17:11:51.623 ThaliTest[1146:1784188] client: new accepted socket: 0x17fba7a0
,ok 115 the test messages should be equal

,ok 116 First send should succeed

,2016-02-09 17:11:51.692 ThaliTest[1146:1784188] client: socket closed
,2016-02-09 17:11:51.692 ThaliTest[1146:1784188] client relay: socket disconnected
,2016-02-09 17:11:51.693 ThaliTest[1146:1784188] client relay: 0x17fba7a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 17:11:,51.693 ThaliTest[1146:1784188] client session: socket closed: 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:51.693 ThaliTest[1146:1784188] client session: onLinkFailure: 1455034305863.1679.uEOCMQ==
2016-02-09 17:11:51.693 ThaliTest[1146:1784188] client session: disconnect
2016-02-09 17:11:51.694 ThaliTest[1146:1784188] client session: stateChange:2->0 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:51.715 ThaliTest[1146:1784188] client session: fireConnectionErrorEvent: 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:51.720 ThaliTest[1146:1784443] jxcore: connect 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:51.722 ThaliTest[1146:1785237] server session: connected
,2016-02-09 17:11:51.723 ThaliTest[1146:1785237] server session: stateChange:1->2 1455034305863.1679
,2016-02-09 17:11:51.723 ThaliTest[1146:1784443] client session: connect
,2016-02-09 17:11:51.726 ThaliTest[1146:1784443] client session: stateChange:0->1 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:51.870 ThaliTest[1146:1784188] server relay: connected (to port: 56576)
,2016-02-09 17:11:52.301 ThaliTest[1146:1784188] multipeer session: reset timer
2016-02-09 17:11:52.302 ThaliTest[1146:1784188] multipeer session: stop timer
2016-02-09 17:11:52.302 ThaliTest[1146:1784188] multipeer session: start timer: 0x18853030
2016-02-09 17:11:52.302 ThaliTest[1146:1784188] server: disconnecting to refresh session (1455034305863.1679)
2016-02-09 17:11:52.302 ThaliTest[1146:1784188] server session: disconnect
2016-02-09 17:11:52.303 ThaliTest[1146:1784188] server session: stateChange:2->0 1455034305863.1679
,2016-02-09 17:11:52.314 ThaliTest[1146:1784188] server session: connect
,2016-02-09 17:11:52.314 ThaliTest[1146:1784188] server session: stateChange:0->1 1455034305863.1679
,2016-02-09 17:11:52.322 ThaliTest[1146:1784188] server: accepting invitation 1455034305863.1679
,2016-02-09 17:11:54.611 ThaliTest[1146:1785251] client session: connected
,2016-02-09 17:11:54.612 ThaliTest[1146:1785251] client session: stateChange:1->2 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:54.642 ThaliTest[1146:1785238] client session: fireConnectCallback: 1455034305863.1679.uEOCMQ==
2016-02-09 17:11:54.643 ThaliTest[1146:1785238] jxcore: connect: success
,ok 117 Should be able to connect without error

,ok 118 Port should be within range

,ok 119 Second connect should succeed

,2016-02-09 17:11:54.677 ThaliTest[1146:1784188] client: relay established
,2016-02-09 17:11:54.678 ThaliTest[1146:1784188] client: new accepted socket: 0x18d4d5e0
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,# setup

,2016-02-09 17:11:54.779 ThaliTest[1146:1784188] client: socket closed
,2016-02-09 17:11:54.780 ThaliTest[1146:1784188] client relay: socket disconnected
,2016-02-09 17:11:54.780 ThaliTest[1146:1784188] client relay: 0x18d4d5e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 17:11:,54.781 ThaliTest[1146:1784188] client session: socket closed: 1455034305863.1679.uEOCMQ==
2016-02-09 17:11:54.781 ThaliTest[1146:1784188] client session: onLinkFailure: 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:54.781 ThaliTest[1146:1784188] client session: disconnect
2016-02-09 17:11:54.781 ThaliTest[1146:1784188] client session: stateChange:2->0 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:54.792 ThaliTest[1146:1784188] client session: fireConnectionErrorEvent: 1455034305863.1679.uEOCMQ==
,2016-02-09 17:11:54.995 ThaliTest[1146:1785251] server session: connected
,2016-02-09 17:11:54.995 ThaliTest[1146:1785251] server session: stateChange:1->2 1455034305863.1679
,2016-02-09 17:11:55.012 ThaliTest[1146:1784188] server relay: connected (to port: 56576)
,2016-02-09 17:11:55.177 ThaliTest[1146:1785237] server session: not connected 1455034305863.1679
,calling stopBroadcasting

,2016-02-09 17:11:55.340 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:11:55.341 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
,2016-02-09 17:11:55.341 ThaliTest[1146:1784443] multipeer session: stop timer
,2016-02-09 17:11:55.342 ThaliTest[1146:1784443] client session: disconnect
2016-02-09 17:11:55.342 ThaliTest[1146:1784443] client session: stateChange:1->0 1455034212406.1679.OOTR4g==
,2016-02-09 17:11:55.344 ThaliTest[1146:1784443] server session: disconnect
2016-02-09 17:11:55.344 ThaliTest[1146:1784443] server session: stateChange:2->0 1455034305863.1679
,2016-02-09 17:11:55.356 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# #generatePreambleAndBeacons null ECDH for local device

,# teardown

,ok 122 ecdhForLocalDevice cannot be null

,# setup

,# #generatePreambleAndBeacons expiration out of range lower

,# teardown

,ok 123 secondsUntilExpiration out of range.

,# setup

,# #generatePreambleAndBeacons expiration out of range upper

,# teardown

,ok 124 secondsUntilExpiration out of range.

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 125 should be equal

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 126 should be equal

ok 127 should be equal

,ok 128 should be equal

,ok 129 should be equal

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 130 should throw

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 131 Preamble expiration must be a 64 bit integer

,# setup

,# #parseBeacons expiration out of range lower

,# teardown

,ok 132 Expiration out of range

,# setup

,# #parseBeacons no beacons returns null

,# teardown

,ok 133 should be equal

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 134 Malformed encrypted beacon key ID

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 135 should be equal

,# setup

,# #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 136 should be equal

ok 137 should be equal

,# setup

,# #parseBeacons addressBookCallback returns public key

,# teardown

,ok 138 should be equal

,ok 139 (unnamed assert)

,# setup

,# #parseBeacons with beacons both for and not for the user

,# teardown

,ok 140 (unnamed assert)

,# setup

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/32EC96DB-1149-4BC6-8D6D-B01B7AC2DE9B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 141 starting event should occur in right order

,2016-02-09 17:12:00.556 ThaliTest[1146:1784443] jxcore: startBroadcasting
,2016-02-09 17:12:00.557 ThaliTest[1146:1784443] server: starting qpED_RLNEQP_iHZvwGYosg.pVPSIg==
,2016-02-09 17:12:00.557 ThaliTest[1146:1784443] multipeer session: start timer: 0x17c05f50
,2016-02-09 17:12:00.557 ThaliTest[1146:1784443] THEMultipeerSession initialized peer qpED_RLNEQP_iHZvwGYosg
2016-02-09 17:12:00.558 ThaliTest[1146:1784443] jxcore: startBroadcasting: success
,ok 142 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 143 stopping event should occur in right order

About to call stopBroadcasting

2016-02-09 17:12:00.559 ThaliTest[1146:1784443] jxcore: stopBroadcasting
,2016-02-09 17:12:00.560 ThaliTest[1146:1784443] THEMultipeerSession stopping peer
2016-02-09 17:12:00.560 ThaliTest[1146:1784443] multipeer session: stop timer
2016-02-09 17:12:00.560 ThaliTest[1146:1784443] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 144 stopped event should occur in right order

,Process 1146 stopped
* thread #18: tid = 0x1b3d96, 0x362c3ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCNearbyServiceBrowser.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x1000000c)
    frame #0: 0x362c3ae6 libobjc.A.dylib`objc_msgSend + 6
libobjc.A.dylib`objc_msgSend:
->  0x362c3ae6 <+6>:  ldrh.w r12, [r9, #0xc]
    0x362c3aea <+10>: ldr.w  r9, [r9, #0x8]
    0x362c3aee <+14>: and.w  r12, r12, r1
    0x362c3af2 <+18>: add.w  r9, r9, r12, lsl #3
,* thread #18: tid = 0x1b3d96, 0x362c3ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCNearbyServiceBrowser.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x1000000c)
  * frame #0: 0x362c3ae6 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x26d07526 MultipeerConnectivity`<redacted> + 34
    frame #2: 0x369dbe2e libdispatch.dylib`<redacted> + 10
    frame #3: 0x369e5fee libdispatch.dylib`<redacted> + 1762
    frame #4: 0x369def86 libdispatch.dylib`<redacted> + 282
    frame #5: 0x369e737c libdispatch.dylib`<redacted> + 400
    frame #6: 0x369e71ea libdispatch.dylib`<redacted> + 94
    frame #7: 0x36b70e0c libsystem_pthread.dylib`_pthread_wqthread + 1024
    frame #8: 0x36b709fc libsystem_pthread.dylib`start_wqthread + 8

```
