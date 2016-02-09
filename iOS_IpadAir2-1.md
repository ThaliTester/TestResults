#### Test 58741471ee11130_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58741471ee11130/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/A91BE906-3F5D-4597-9D94-C12B75BE0B9C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A91BE906-3F5D-4597-9D94-C12B75BE0B9C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58741471ee11130/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58741471ee11130/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53156"
,(lldb)     command script import "/tmp/A91BE906-3F5D-4597-9D94-C12B75BE0B9C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 14:05:07.433 ThaliTest[1093:1757025] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5A7F8F5B-B29A-42DC-8165-C5CD24545D3E/Library/Cookies/Cookies.binarycookies
,2016-02-09 14:05:07.877 ThaliTest[1093:1757025] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 14:05:07.878 ThaliTest[1093:1757025] Multi-tasking -> Device: YES, App: YES
,2016-02-09 14:05:07.887 ThaliTest[1093:1757025] Unlimited access to network resources
,2016-02-09 14:05:07.896 ThaliTest[1093:1757025] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 14:05:18.213 ThaliTest[1093:1757025] Resetting plugins due to page load.
,2016-02-09 14:05:22.045 ThaliTest[1093:1757025] Finished load of: file:///var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app/www/index.html
,2016-02-09 14:05:22.212 ThaliTest[1093:1757025] JXcore Cordova plugin initializing
2016-02-09 14:05:22.213 ThaliTest[1093:1757300] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1482FFAD-3ED8-4204-9968-BF47CE8270D3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,ok 22 should be equal

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

ok 53 should be equal

# setup

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

,2016-02-09 14:10:06.276 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:06.291 ThaliTest[1093:1757300] server: starting 1455023406275.1093.4Ckl3Q==
,2016-02-09 14:10:06.293 ThaliTest[1093:1757300] multipeer session: start timer: 0x18a4daf0
2016-02-09 14:10:06.293 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023406275.1093
2016-02-09 14:10:06.293 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

2016-02-09 14:10:06.297 ThaliTest[1093:1757300] jxcore: stopBroadcasting
2016-02-09 14:10:06.297 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
2016-02-09 14:10:06.297 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:06.298 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

2016-02-09 14:10:06.302 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:06.308 ThaliTest[1093:1757300] server: starting 1455023406301.1093.nR4WDQ==
2016-02-09 14:10:06.309 ThaliTest[1093:1757300] multipeer session: start timer: 0x18a70e70
,2016-02-09 14:10:06.310 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023406301.1093
2016-02-09 14:10:06.310 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

,2016-02-09 14:10:06.313 ThaliTest[1093:1757300] jxcore: stopBroadcasting
2016-02-09 14:10:06.313 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
2016-02-09 14:10:06.314 ThaliTest[1093:1757300] multipeer session: stop timer
2016-02-09 14:10:06.314 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
ok 66 Should be able to call stopBroadcasting without error

2016-02-09 14:10:06.316 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:06.321 ThaliTest[1093:1757300] server: starting 1455023406316.1093.i7j9rQ==
2016-02-09 14:10:06.325 ThaliTest[1093:1757300] multipeer session: start timer: 0x18a70e70
2016-02-09 14:10:06.325 ThaliTest[1093:1757300] THEMultipeerSession in,itialized peer 1455023406316.1093
2016-02-09 14:10:06.326 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 67 Should be able to call startBroadcasting without error

,2016-02-09 14:10:06.329 ThaliTest[1093:1757300] jxcore: stopBroadcasting
2016-02-09 14:10:06.329 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
2016-02-09 14:10:06.330 ThaliTest[1093:1757300] multipeer session: stop timer
2016-02-09 14:10:06.331 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
ok 68 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:06.333 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:06.340 ThaliTest[1093:1757300] server: starting 1455023406332.1093.iOVKpQ==
2016-02-09 14:10:06.341 ThaliTest[1093:1757300] multipeer session: start timer: 0x18a71c90
2016-02-09 14:10:06.341 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023406332.1093
,2016-02-09 14:10:06.343 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-09 14:10:06.350 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:06.350 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:06.351 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:06.352 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:06.357 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:06.361 ThaliTest[1093:1757300] server: starting 1455023406357.1093.z334pA==
,2016-02-09 14:10:06.363 ThaliTest[1093:1757300] multipeer session: start timer: 0x18efabb0
,2016-02-09 14:10:06.366 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023406357.1093
,2016-02-09 14:10:06.369 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 14:10:06.372 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:06.373 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:06.374 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:06.377 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:06.380 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:06.382 ThaliTest[1093:1757300] server: starting 1455023406379.1093.saeeUQ==
,2016-02-09 14:10:06.384 ThaliTest[1093:1757300] multipeer session: start timer: 0x18a71560
,2016-02-09 14:10:06.385 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023406379.1093
,2016-02-09 14:10:06.386 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-09 14:10:06.389 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:06.389 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:06.390 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:06.392 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:06.394 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:06.396 ThaliTest[1093:1757300] server: starting 1455023406394.1093.3sGyVg==
,2016-02-09 14:10:06.398 ThaliTest[1093:1757300] multipeer session: start timer: 0x18a72090
,2016-02-09 14:10:06.399 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023406394.1093
,2016-02-09 14:10:06.401 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-09 14:10:06.404 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:06.404 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:06.405 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:06.406 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:06.410 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:06.412 ThaliTest[1093:1757300] server: starting 1455023406409.1093.xgpTNQ==
,2016-02-09 14:10:06.413 ThaliTest[1093:1757300] multipeer session: start timer: 0x15e4fb30
,2016-02-09 14:10:06.417 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023406409.1093
,2016-02-09 14:10:06.419 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 14:10:06.421 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:06.422 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:06.422 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:06.424 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:06.427 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:06.429 ThaliTest[1093:1757300] server: starting 1455023406427.1093.V2XtpQ==
,2016-02-09 14:10:06.431 ThaliTest[1093:1757300] multipeer session: start timer: 0x18a72160
,2016-02-09 14:10:06.432 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023406427.1093
,2016-02-09 14:10:06.435 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 14:10:06.438 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:06.438 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:06.439 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:06.442 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:06.444 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:06.447 ThaliTest[1093:1757300] server: starting 1455023406444.1093.KIs/5g==
,2016-02-09 14:10:06.448 ThaliTest[1093:1757300] multipeer session: start timer: 0x189b04d0
,2016-02-09 14:10:06.450 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023406444.1093
,2016-02-09 14:10:06.452 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 14:10:06.454 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:06.454 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:06.455 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:06.456 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 14:10:07.097 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:07.100 ThaliTest[1093:1757300] server: starting 1455023407097.1093.WW98aA==
,2016-02-09 14:10:07.101 ThaliTest[1093:1757300] multipeer session: start timer: 0x18e056f0
2016-02-09 14:10:07.102 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023407097.1093
2016-02-09 14:10:07.102 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-09 14:10:07.105 ThaliTest[1093:1757300] jxcore: startBroadcasting
2016-02-09 14:10:07.106 ThaliTest[1093:1757300] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

,2016-02-09 14:10:07.113 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:07.113 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:07.114 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:07.116 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 14:10:08.829 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:08.832 ThaliTest[1093:1757300] server: starting 1455023408829.1093.HeY7Mg==
,2016-02-09 14:10:08.834 ThaliTest[1093:1757300] multipeer session: start timer: 0x18e00a00
2016-02-09 14:10:08.834 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023408829.1093
2016-02-09 14:10:08.834 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

2016-02-09 14:10:08.836 ThaliTest[1093:1757300] jxcore: connect foobar
,2016-02-09 14:10:08.837 ThaliTest[1093:1757300] client: unknown peer foobar
2016-02-09 14:10:08.837 ThaliTest[1093:1757300] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

,2016-02-09 14:10:08.842 ThaliTest[1093:1757300] jxcore: stopBroadcasting
2016-02-09 14:10:08.842 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
2016-02-09 14:10:08.843 ThaliTest[1093:1757300] multipeer session: stop timer
2016-02-09 14:10:08.844 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 14:10:09.281 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:09.285 ThaliTest[1093:1757300] server: starting 1455023409281.1093.sJ0kZQ==
,2016-02-09 14:10:09.285 ThaliTest[1093:1757300] multipeer session: start timer: 0x18a746c0
,2016-02-09 14:10:09.286 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023409281.1093
2016-02-09 14:10:09.286 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

2016-02-09 14:10:09.289 ThaliTest[1093:1757300] jxcore: disconnect
2016-02-09 14:10:09.289 ThaliTest[1093:1757300] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

2016-02-09 14:10:09.293 ThaliTest[1093:1757300] jxcore: stopBroadcasting
2016-02-09 14:10:09.294 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
2016-02-09 14:10:09.294 ThaliTest[1093:1757,300] multipeer session: stop timer
2016-02-09 14:10:09.295 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 14:10:09.682 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:09.685 ThaliTest[1093:1757300] server: starting 1455023409681.1093.cIjK6g==
,2016-02-09 14:10:09.686 ThaliTest[1093:1757300] multipeer session: start timer: 0x18f0db40
,2016-02-09 14:10:09.686 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023409681.1093
,2016-02-09 14:10:09.687 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-09 14:10:11.055 ThaliTest[1093:1757025] client: found peer: 1455023408175.1638.F4ep7w==
,2016-02-09 14:10:11.057 ThaliTest[1093:1757300] jxcore: connect 1455023408175.1638.F4ep7w==
,2016-02-09 14:10:11.058 ThaliTest[1093:1757300] client session: connect
,2016-02-09 14:10:11.059 ThaliTest[1093:1757300] client session: stateChange:0->1 1455023408175.1638.F4ep7w==
,2016-02-09 14:10:11.260 ThaliTest[1093:1757025] multipeer session: reset timer
2016-02-09 14:10:11.260 ThaliTest[1093:1757025] multipeer session: stop timer
2016-02-09 14:10:11.260 ThaliTest[1093:1757025] multipeer session: start timer: 0x18f0db40
2016-02-09 14:10:11.261 ThaliTest[1093:1757025] server session: connect
,2016-02-09 14:10:11.261 ThaliTest[1093:1757025] server session: stateChange:0->1 1455023408175.1638
,2016-02-09 14:10:11.268 ThaliTest[1093:1757025] server: accepting invitation 1455023408175.1638
,2016-02-09 14:10:13.817 ThaliTest[1093:1757794] client session: connected
2016-02-09 14:10:13.819 ThaliTest[1093:1757794] client session: stateChange:1->2 1455023408175.1638.F4ep7w==
,2016-02-09 14:10:13.823 ThaliTest[1093:1757794] client session: fireConnectCallback: 1455023408175.1638.F4ep7w==
2016-02-09 14:10:13.824 ThaliTest[1093:1757794] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 14:10:13.828 ThaliTest[1093:1757300] jxcore: disconnect
,2016-02-09 14:10:13.829 ThaliTest[1093:1757300] client session: disconnectFromPeer: 1455023408175.1638.F4ep7w==
2016-02-09 14:10:13.829 ThaliTest[1093:1757300] client session: disconnect
,2016-02-09 14:10:13.830 ThaliTest[1093:1757300] client session: stateChange:2->0 1455023408175.1638.F4ep7w==
,2016-02-09 14:10:13.841 ThaliTest[1093:1757300] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 14:10:13.951 ThaliTest[1093:1757779] server session: connected
,2016-02-09 14:10:13.952 ThaliTest[1093:1757779] server session: stateChange:1->2 1455023408175.1638
,2016-02-09 14:10:13.966 ThaliTest[1093:1757025] server relay: socket disconnected
,2016-02-09 14:10:13.966 ThaliTest[1093:1757025] server relay: 0x18f1b490 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 14:10:14.057 ThaliTest[1093:1757797] server session: not connected 1455023408175.1638
,calling stopBroadcasting

2016-02-09 14:10:14.060 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:14.060 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
2016-02-09 14:10:14.061 ThaliTest[1093:1757300] multipeer session: stop timer
2016-02-09 14:10:14.061 ThaliTest[1093:1757300] server session: disconnect
2016-02-09 14:10:1,4.061 ThaliTest[1093:1757300] server session: stateChange:2->0 1455023408175.1638
2016-02-09 14:10:14.062 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 14:10:14.577 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:14.580 ThaliTest[1093:1757300] server: starting 1455023414576.1093.jAuJVA==
,2016-02-09 14:10:14.581 ThaliTest[1093:1757300] multipeer session: start timer: 0x17b21f50
2016-02-09 14:10:14.582 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023414576.1093
2016-02-09 14:10:14.582 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 96 Should be able to call startBroadcasting without error

,2016-02-09 14:10:15.787 ThaliTest[1093:1757025] multipeer session: reset timer
2016-02-09 14:10:15.787 ThaliTest[1093:1757025] multipeer session: stop timer
2016-02-09 14:10:15.787 ThaliTest[1093:1757025] multipeer session: start timer: 0x17b21f50
,2016-02-09 14:10:15.788 ThaliTest[1093:1757025] server session: connect
2016-02-09 14:10:15.788 ThaliTest[1093:1757025] server session: stateChange:0->1 1455023413049.1638
,2016-02-09 14:10:15.794 ThaliTest[1093:1757025] server: accepting invitation 1455023413049.1638
,2016-02-09 14:10:15.830 ThaliTest[1093:1757025] client: found peer: 1455023413049.1638.U7kpqQ==
,2016-02-09 14:10:15.834 ThaliTest[1093:1757300] jxcore: connect 1455023413049.1638.U7kpqQ==
2016-02-09 14:10:15.835 ThaliTest[1093:1757300] client session: connect
2016-02-09 14:10:15.835 ThaliTest[1093:1757300] client session: stateChange:0->1 1455023413049.1638.U7kpqQ==
,2016-02-09 14:10:18.401 ThaliTest[1093:1757797] server session: connected
2016-02-09 14:10:18.401 ThaliTest[1093:1757797] server session: stateChange:1->2 1455023413049.1638
,2016-02-09 14:10:18.426 ThaliTest[1093:1757025] server relay: socket disconnected
2016-02-09 14:10:18.427 ThaliTest[1093:1757025] server relay: 0x18f1aa60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 14:10:18.465 ThaliTest[1093:1757779] server session: not connected 1455023413049.1638
,2016-02-09 14:10:18.663 ThaliTest[1093:1757779] client session: connected
2016-02-09 14:10:18.664 ThaliTest[1093:1757779] client session: stateChange:1->2 1455023413049.1638.U7kpqQ==
,2016-02-09 14:10:18.704 ThaliTest[1093:1757797] client session: fireConnectCallback: 1455023413049.1638.U7kpqQ==
2016-02-09 14:10:18.704 ThaliTest[1093:1757797] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-09 14:10:18.708 ThaliTest[1093:1757300] jxcore: connect 1455023413049.1638.U7kpqQ==
,2016-02-09 14:10:18.709 ThaliTest[1093:1757300] client: already connect(ing/ed) to 1455023413049.1638.U7kpqQ==
,2016-02-09 14:10:18.709 ThaliTest[1093:1757300] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-09 14:10:18.714 ThaliTest[1093:1757300] jxcore: disconnect
,2016-02-09 14:10:18.714 ThaliTest[1093:1757300] client session: disconnectFromPeer: 1455023413049.1638.U7kpqQ==
,2016-02-09 14:10:18.715 ThaliTest[1093:1757300] client session: disconnect
,2016-02-09 14:10:18.715 ThaliTest[1093:1757300] client session: stateChange:2->0 1455023413049.1638.U7kpqQ==
,2016-02-09 14:10:18.725 ThaliTest[1093:1757300] jxcore: disconnect: success
ok 100 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 14:10:18.800 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:18.801 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:18.801 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:18.802 ThaliTest[1093:1757300] server session: disconnect
2016-02-09 14:10:18.802 ThaliTest[1093:1757300] server session: stateChange:2->0 1455023413049.1638
,2016-02-09 14:10:18.807 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 14:10:19.774 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:19.777 ThaliTest[1093:1757300] server: starting 1455023419773.1093./aaIFg==
,2016-02-09 14:10:19.779 ThaliTest[1093:1757300] multipeer session: start timer: 0x18f0eed0
2016-02-09 14:10:19.779 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023419773.1093
2016-02-09 14:10:19.780 ThaliTest[1093:1757300] jxcore: sta,rtBroadcasting: success
,ok 101 Should be able to call startBroadcasting without error

,2016-02-09 14:10:20.586 ThaliTest[1093:1757025] client: found peer: 1455023418114.1638.LjXq2A==
,2016-02-09 14:10:20.588 ThaliTest[1093:1757300] jxcore: connect 1455023418114.1638.LjXq2A==
2016-02-09 14:10:20.588 ThaliTest[1093:1757300] client session: connect
2016-02-09 14:10:20.589 ThaliTest[1093:1757300] client session: stateChange:0->1 145502341,8114.1638.LjXq2A==
,2016-02-09 14:10:21.084 ThaliTest[1093:1757025] multipeer session: reset timer
2016-02-09 14:10:21.084 ThaliTest[1093:1757025] multipeer session: stop timer
2016-02-09 14:10:21.084 ThaliTest[1093:1757025] multipeer session: start timer: 0x18f0eed0
,2016-02-09 14:10:21.085 ThaliTest[1093:1757025] server session: connect
2016-02-09 14:10:21.085 ThaliTest[1093:1757025] server session: stateChange:0->1 1455023418114.1638
,2016-02-09 14:10:21.091 ThaliTest[1093:1757025] server: accepting invitation 1455023418114.1638
,2016-02-09 14:10:23.644 ThaliTest[1093:1757845] client session: connected
2016-02-09 14:10:23.644 ThaliTest[1093:1757845] client session: stateChange:1->2 1455023418114.1638.LjXq2A==
,2016-02-09 14:10:23.698 ThaliTest[1093:1757845] client session: fireConnectCallback: 1455023418114.1638.LjXq2A==
2016-02-09 14:10:23.699 ThaliTest[1093:1757845] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-09 14:10:23.703 ThaliTest[1093:1757300] jxcore: disconnect
,2016-02-09 14:10:23.704 ThaliTest[1093:1757300] client session: disconnectFromPeer: 1455023418114.1638.LjXq2A==
,2016-02-09 14:10:23.705 ThaliTest[1093:1757300] client session: disconnect
,2016-02-09 14:10:23.705 ThaliTest[1093:1757300] client session: stateChange:2->0 1455023418114.1638.LjXq2A==
,2016-02-09 14:10:23.714 ThaliTest[1093:1757300] jxcore: disconnect: success
ok 104 Should be able to disconnect without error

2016-02-09 14:10:23.716 ThaliTest[1093:1757300] jxcore: disconnect
2016-02-09 14:10:23.716 ThaliTest[1093:1757300] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 14:10:23.902 ThaliTest[1093:1757797] server session: connected
2016-02-09 14:10:23.902 ThaliTest[1093:1757797] server session: stateChange:1->2 1455023418114.1638
,2016-02-09 14:10:23.905 ThaliTest[1093:1757025] server relay: socket disconnected
2016-02-09 14:10:23.906 ThaliTest[1093:1757025] server relay: 0x18ab24c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 14:10:23.972 ThaliTest[1093:1757845] server session: not connected 1455023418114.1638
,calling stopBroadcasting

,2016-02-09 14:10:23.981 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:23.981 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:23.982 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:23.982 ThaliTest[1093:1757300] server session: disconnect
,2016-02-09 14:10:23.984 ThaliTest[1093:1757300] server session: stateChange:2->0 1455023418114.1638
,2016-02-09 14:10:23.986 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 56071

,2016-02-09 14:10:27.853 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:27.854 ThaliTest[1093:1757300] server: starting 1455023427853.1093.8Cv6/Q==
,2016-02-09 14:10:27.855 ThaliTest[1093:1757300] multipeer session: start timer: 0x18f0d810
2016-02-09 14:10:27.855 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023427853.1093
2016-02-09 14:10:27.855 ThaliTest[1093:1757300] jxcore: sta,rtBroadcasting: success
ok 106 Should be able to call startBroadcasting without error

,2016-02-09 14:10:28.585 ThaliTest[1093:1757025] client: found peer: 1455023424486.1638.M6bZVQ==
,2016-02-09 14:10:28.587 ThaliTest[1093:1757300] jxcore: connect 1455023424486.1638.M6bZVQ==
2016-02-09 14:10:28.588 ThaliTest[1093:1757300] client session: connect
2016-02-09 14:10:28.588 ThaliTest[1093:1757300] client session: stateChange:0->1 1455023424486.1638.M6bZVQ==
,2016-02-09 14:10:28.997 ThaliTest[1093:1757025] multipeer session: reset timer
2016-02-09 14:10:28.997 ThaliTest[1093:1757025] multipeer session: stop timer
,2016-02-09 14:10:28.997 ThaliTest[1093:1757025] multipeer session: start timer: 0x18f0d810
,2016-02-09 14:10:28.998 ThaliTest[1093:1757025] server session: connect
2016-02-09 14:10:28.998 ThaliTest[1093:1757025] server session: stateChange:0->1 1455023424486.1638
,2016-02-09 14:10:29.005 ThaliTest[1093:1757025] server: accepting invitation 1455023424486.1638
,2016-02-09 14:10:31.497 ThaliTest[1093:1757794] client session: connected
2016-02-09 14:10:31.497 ThaliTest[1093:1757794] client session: stateChange:1->2 1455023424486.1638.M6bZVQ==
,2016-02-09 14:10:31.526 ThaliTest[1093:1757844] client session: fireConnectCallback: 1455023424486.1638.M6bZVQ==
2016-02-09 14:10:31.527 ThaliTest[1093:1757844] jxcore: connect: success
,ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 14:10:31.533 ThaliTest[1093:1757025] client: relay established
2016-02-09 14:10:31.533 ThaliTest[1093:1757025] client: new accepted socket: 0x17dc8440
,data in 7665

,data in 8760

,2016-02-09 14:10:31.768 ThaliTest[1093:1757794] server session: connected
2016-02-09 14:10:31.768 ThaliTest[1093:1757794] server session: stateChange:1->2 1455023424486.1638
,data in 9855

,2016-02-09 14:10:31.810 ThaliTest[1093:1757025] server relay: connected (to port: 56071)
,data in 10950

,data in 18615

,data in 19710

,data in 22995

,data in 33945

,data in 43800

,data in 45990

,data in 58035

,data in 68985

,data in 70080

,data in 74460
,
,data in 78840

,data in 85410

,data in 121545

,data in 122640

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 14:10:32.409 ThaliTest[1093:1757300] jxcore: disconnect
,2016-02-09 14:10:32.409 ThaliTest[1093:1757300] client session: disconnectFromPeer: 1455023424486.1638.M6bZVQ==
,2016-02-09 14:10:32.410 ThaliTest[1093:1757300] client session: disconnect
,2016-02-09 14:10:32.411 ThaliTest[1093:1757300] client session: stateChange:2->0 1455023424486.1638.M6bZVQ==
,2016-02-09 14:10:32.421 ThaliTest[1093:1757300] jxcore: disconnect: success
ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 14:10:32.814 ThaliTest[1093:1757794] server session: not connected 1455023424486.1638
,calling stopBroadcasting

,2016-02-09 14:10:32.882 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:32.883 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:32.883 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:32.884 ThaliTest[1093:1757300] server session: disconnect
,2016-02-09 14:10:32.885 ThaliTest[1093:1757300] server session: stateChange:2->0 1455023424486.1638
,2016-02-09 14:10:32.901 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,
,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 56077

,2016-02-09 14:10:33.407 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:33.410 ThaliTest[1093:1757300] server: starting 1455023433406.1093.alYVuw==
,2016-02-09 14:10:33.411 ThaliTest[1093:1757300] multipeer session: start timer: 0x18a0a860
,2016-02-09 14:10:33.412 ThaliTest[1093:1757300] THEMultipeerSession initialized peer 1455023433406.1093
,2016-02-09 14:10:33.412 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 111 Should be able to call startBroadcasting without error

,2016-02-09 14:10:34.103 ThaliTest[1093:1757025] client: found peer: 1455023424486.1638.M6bZVQ==
,[{"peerIdentifier":"1455023424486.1638.M6bZVQ==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 14:10:34.106 ThaliTest[1093:1757300] jxcore: connect 1455023424486.1638.M6bZVQ==
2016-02-09 14:10:34.107 ThaliTest[1093:1757300] client session: connect
,2016-02-09 14:10:34.108 ThaliTest[1093:1757300] client session: stateChange:0->1 1455023424486.1638.M6bZVQ==
,2016-02-09 14:10:34.575 ThaliTest[1093:1757025] client: found peer: 1455023431894.1638.5uy/6Q==
,[{"peerIdentifier":"1455023431894.1638.5uy/6Q==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 14:10:34.577 ThaliTest[1093:1757300] jxcore: connect 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:34.578 ThaliTest[1093:1757300] client session: connect
,2016-02-09 14:10:34.579 ThaliTest[1093:1757300] client session: stateChange:0->1 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:34.926 ThaliTest[1093:1757025] multipeer session: reset timer
2016-02-09 14:10:34.927 ThaliTest[1093:1757025] multipeer session: stop timer
2016-02-09 14:10:34.928 ThaliTest[1093:1757025] multipeer session: start timer: 0x18a0a860
,2016-02-09 14:10:34.928 ThaliTest[1093:1757025] server session: connect
,2016-02-09 14:10:34.928 ThaliTest[1093:1757025] server session: stateChange:0->1 1455023431894.1638
,2016-02-09 14:10:34.936 ThaliTest[1093:1757025] server: accepting invitation 1455023431894.1638
,2016-02-09 14:10:37.341 ThaliTest[1093:1757794] client session: connected
2016-02-09 14:10:37.342 ThaliTest[1093:1757794] client session: stateChange:1->2 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:37.347 ThaliTest[1093:1757794] client session: fireConnectCallback: 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:37.348 ThaliTest[1093:1757794] jxcore: connect: success
,ok 112 Should be able to connect without error

,ok 113 Port should be within range

,ok 114 First connect should succeed

,2016-02-09 14:10:37.407 ThaliTest[1093:1757025] client: relay established
,2016-02-09 14:10:37.408 ThaliTest[1093:1757025] client: new accepted socket: 0x15df1fe0
,ok 115 the test messages should be equal

ok 116 First send should succeed

,2016-02-09 14:10:37.516 ThaliTest[1093:1757025] client: socket closed
,2016-02-09 14:10:37.517 ThaliTest[1093:1757025] client relay: socket disconnected
,2016-02-09 14:10:37.517 ThaliTest[1093:1757025] client relay: 0x15df1fe0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-09 14:10:37.518 ThaliTest[1093:1757025] client session: socket closed: 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:37.518 ThaliTest[1093:1757025] client session: onLinkFailure: 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:37.518 ThaliTest[1093:1757025] client session: disconnect
,2016-02-09 14:10:37.519 ThaliTest[1093:1757025] client session: stateChange:2->0 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:37.530 ThaliTest[1093:1757025] client session: fireConnectionErrorEvent: 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:37.532 ThaliTest[1093:1757300] jxcore: connect 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:37.533 ThaliTest[1093:1757300] client session: connect
2016-02-09 14:10:37.534 ThaliTest[1093:1757300] client session: stateChange:0->1 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:37.550 ThaliTest[1093:1757845] server session: connected
2016-02-09 14:10:37.550 ThaliTest[1093:1757845] server session: stateChange:1->2 1455023431894.1638
,2016-02-09 14:10:37.558 ThaliTest[1093:1757025] server relay: connected (to port: 56077)
,2016-02-09 14:10:38.111 ThaliTest[1093:1757794] server session: not connected 1455023431894.1638
,2016-02-09 14:10:38.183 ThaliTest[1093:1757025] multipeer session: reset timer
2016-02-09 14:10:38.183 ThaliTest[1093:1757025] multipeer session: stop timer
2016-02-09 14:10:38.184 ThaliTest[1093:1757025] multipeer session: start timer: 0x18a0a860
2016-02-09 14:10:38.184 ThaliTest[1093:1757025] server: disconnecting to refresh session (1455023431894.1638)
2016-02-09 14:10:38.184 ThaliTest[1093:1757025] server session: disconnect
,2016-02-09 14:10:38.185 ThaliTest[1093:1757025] server session: stateChange:2->0 1455023431894.1638
,2016-02-09 14:10:38.193 ThaliTest[1093:1757025] server session: connect
2016-02-09 14:10:38.194 ThaliTest[1093:1757025] server session: stateChange:0->1 1455023431894.1638
2016-02-09 14:10:38.205 ThaliTest[1093:1757025] server: accepting invitation 14550,23431894.1638
,2016-02-09 14:10:40.667 ThaliTest[1093:1757937] client session: connected
2016-02-09 14:10:40.667 ThaliTest[1093:1757937] client session: stateChange:1->2 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:40.672 ThaliTest[1093:1757937] client session: fireConnectCallback: 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:40.672 ThaliTest[1093:1757937] jxcore: connect: success
,ok 117 Should be able to connect without error

,ok 118 Port should be within range

,ok 119 Second connect should succeed

,2016-02-09 14:10:40.709 ThaliTest[1093:1757025] client: relay established
2016-02-09 14:10:40.710 ThaliTest[1093:1757025] client: new accepted socket: 0x17b44450
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,# setup

,2016-02-09 14:10:40.769 ThaliTest[1093:1757025] client: socket closed
,2016-02-09 14:10:40.769 ThaliTest[1093:1757025] client relay: socket disconnected
,2016-02-09 14:10:40.770 ThaliTest[1093:1757025] client relay: 0x17b44450 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-09 14:10:40.770 ThaliTest[1093:1757025] client session: socket closed: 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:40.771 ThaliTest[1093:1757025] client session: onLinkFailure: 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:40.771 ThaliTest[1093:1757025] client session: disconnect
2016-02-09 14:10:40.771 ThaliTest[1093:1757025] client session: stateChange:2->0 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:40.780 ThaliTest[1093:1757025] client session: fireConnectionErrorEvent: 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:40.876 ThaliTest[1093:1757779] server session: connected
2016-02-09 14:10:40.876 ThaliTest[1093:1757779] server session: stateChange:1->2 1455023431894.1638
,2016-02-09 14:10:40.882 ThaliTest[1093:1757025] server relay: connected (to port: 56077)
,2016-02-09 14:10:41.066 ThaliTest[1093:1757937] server session: not connected 1455023431894.1638
,calling stopBroadcasting

,2016-02-09 14:10:41.270 ThaliTest[1093:1757300] jxcore: stopBroadcasting
,2016-02-09 14:10:41.271 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:10:41.272 ThaliTest[1093:1757300] multipeer session: stop timer
,2016-02-09 14:10:41.272 ThaliTest[1093:1757300] client session: disconnect
,2016-02-09 14:10:41.273 ThaliTest[1093:1757300] client session: stateChange:1->0 1455023424486.1638.M6bZVQ==
,2016-02-09 14:10:41.274 ThaliTest[1093:1757300] server session: disconnect
2016-02-09 14:10:41.275 ThaliTest[1093:1757300] server session: stateChange:2->0 1455023431894.1638
,2016-02-09 14:10:41.281 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/5A7F8F5B-B29A-42DC-8165-C5CD24545D3E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 122 starting event should occur in right order

,2016-02-09 14:10:41.926 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:41.928 ThaliTest[1093:1757300] server: starting slE-aU4rW0no9FdL8Wi02w.V8bdeg==
,2016-02-09 14:10:41.928 ThaliTest[1093:1757300] multipeer session: start timer: 0x15f5afe0
,2016-02-09 14:10:41.928 ThaliTest[1093:1757300] THEMultipeerSession initialized peer slE-aU4rW0no9FdL8Wi02w
2016-02-09 14:10:41.929 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 123 started event should occur in right order

,Now in TRM stop

State of this._isStarted: true

ok 124 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-09 14:10:41.930 ThaliTest[1093:1757300] jxcore: stopBroadcasting
2016-02-09 14:10:41.931 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
2016-02-09 14:10:41.931 ThaliTest[1093:1757300] multipeer session: stop timer
2016-02-09 14:10:41.931 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 125 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/5A7F8F5B-B29A-42DC-8165-C5CD24545D3E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 14:10:42.319 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:42.321 ThaliTest[1093:1757300] server: starting slE-aU4rW0no9FdL8Wi02w.ASf1bA==
,2016-02-09 14:10:42.322 ThaliTest[1093:1757300] multipeer session: start timer: 0x18e5f770
2016-02-09 14:10:42.322 ThaliTest[1093:1757300] THEMultipeerSession initialized peer slE-aU4rW0no9FdL8Wi02w
2016-02-09 14:10:42.322 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
ok 126 getDeviceIdentity should not return an error

,ok 127 deviceName should not be null

Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-09 14:10:42.326 ThaliTest[1093:1757300] jxcore: stopBroadcasting
2016-02-09 14:10:42.326 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
2016-02-09 14:10:42.326 ThaliTest[1093:1757300] multipeer session: stop timer
2016-02-09 14:10:42.327 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/5A7F8F5B-B29A-42DC-8165-C5CD24545D3E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 14:10:44.503 ThaliTest[1093:1757300] jxcore: startBroadcasting
,2016-02-09 14:10:44.504 ThaliTest[1093:1757300] server: starting slE-aU4rW0no9FdL8Wi02w.M6Hc4g==
,2016-02-09 14:10:44.505 ThaliTest[1093:1757300] multipeer session: start timer: 0x15ede2a0
,2016-02-09 14:10:44.505 ThaliTest[1093:1757300] THEMultipeerSession initialized peer slE-aU4rW0no9FdL8Wi02w
2016-02-09 14:10:44.505 ThaliTest[1093:1757300] jxcore: startBroadcasting: success
,ok 128 getDeviceIdentity should not return an error

ok 129 deviceName should not be null

,2016-02-09 14:10:44.509 ThaliTest[1093:1757025] client: found peer: 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:48.471 ThaliTest[1093:1757025] client: found peer: 6Vf7gCVRpsisNTWLkBikvg.Qw4lbA==
,2016-02-09 14:10:48.494 ThaliTest[1093:1757300] jxcore: connect 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:48.494 ThaliTest[1093:1757300] client session: connect
2016-02-09 14:10:48.495 ThaliTest[1093:1757300] client session: stateChange:0->1 1455023431894.1638.5uy/6Q==
,2016-02-09 14:10:48.497 ThaliTest[1093:1757300] jxcore: connect 6Vf7gCVRpsisNTWLkBikvg.Qw4lbA==
,2016-02-09 14:10:48.497 ThaliTest[1093:1757300] client session: connect
,2016-02-09 14:10:48.498 ThaliTest[1093:1757300] client session: stateChange:0->1 6Vf7gCVRpsisNTWLkBikvg.Qw4lbA==
,ok 130 Should be able to put doc without error

,ok 131 1st change of local doc should contain local id

,2016-02-09 14:10:49.285 ThaliTest[1093:1757025] multipeer session: reset timer
2016-02-09 14:10:49.285 ThaliTest[1093:1757025] multipeer session: stop timer
2016-02-09 14:10:49.286 ThaliTest[1093:1757025] multipeer session: start timer: 0x15ede2a0
,2016-02-09 14:10:49.286 ThaliTest[1093:1757025] server session: connect
2016-02-09 14:10:49.286 ThaliTest[1093:1757025] server session: stateChange:0->1 6Vf7gCVRpsisNTWLkBikvg
,2016-02-09 14:10:49.294 ThaliTest[1093:1757025] server: accepting invitation 6Vf7gCVRpsisNTWLkBikvg
,2016-02-09 14:10:52.304 ThaliTest[1093:1757846] server session: connected
,2016-02-09 14:10:52.305 ThaliTest[1093:1757846] server session: stateChange:1->2 6Vf7gCVRpsisNTWLkBikvg
,2016-02-09 14:10:52.625 ThaliTest[1093:1757025] server relay: connected (to port: 56093)
,server bridge: new client socket

,2016-02-09 14:10:52.910 ThaliTest[1093:1757025] client: lost peer: 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:52.911 ThaliTest[1093:1757025] client session: onPeerLost: 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:52.911 ThaliTest[1093:1757025] client ,session: onLinkFailure: 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:52.911 ThaliTest[1093:1757025] client session: disconnect
2016-02-09 14:10:52.912 ThaliTest[1093:1757025] client session: stateChange:1->0 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:,52.912 ThaliTest[1093:1757025] client session: fireConnectCallback: 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:52.913 ThaliTest[1093:1757025] jxcore: connect: fail: Peer disconnected
,Connect error with error: Error: Peer disconnected

,2016-02-09 14:10:52.934 ThaliTest[1093:1757300] jxcore: disconnect
,2016-02-09 14:10:52.936 ThaliTest[1093:1757300] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 1455023431894.1638.5uy/6Q==
,
,2016-02-09 14:10:54.431 ThaliTest[1093:1757794] client session: connected
2016-02-09 14:10:54.432 ThaliTest[1093:1757794] client session: stateChange:1->2 6Vf7gCVRpsisNTWLkBikvg.Qw4lbA==
,2016-02-09 14:10:54.434 ThaliTest[1093:1757846] client session: fireConnectCallback: 6Vf7gCVRpsisNTWLkBikvg.Qw4lbA==
,2016-02-09 14:10:54.434 ThaliTest[1093:1757846] jxcore: connect: success
,2016-02-09 14:10:54.535 ThaliTest[1093:1757025] client: relay established
2016-02-09 14:10:54.535 ThaliTest[1093:1757025] client: new accepted socket: 0x17d589d0
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,ok 132 1st change of remote doc should contain remote id

,client bridge: new client socket

,ok 133 Can update remote doc without error

,null

,{ ok: true,
  id: 'e2741d29-e357-4b84-8653-ab5016761f3f',
  rev: '2-79287ed2bc97730df2584aceae50db80' }

,ok 134 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,ok 135 Local changes occur in strict order

ok 136 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-09 14:11:00.663 ThaliTest[1093:1757300] jxcore: stopBroadcasting
2016-02-09 14:11:00.664 ThaliTest[1093:1757300] THEMultipeerSession stopping peer
,2016-02-09 14:11:00.664 ThaliTest[1093:1757300] multipeer session: stop timer
2016-02-09 14:11:00.664 ThaliTest[1093:1757300] client session: disconnect
2016-02-09 14:11:00.664 ThaliTest[1093:1757300] client session: stateChange:2->0 6Vf7gCVRpsisNTWLkBikvg.Qw4lbA==
,2016-02-09 14:11:00.672 ThaliTest[1093:1757300] server session: disconnect
2016-02-09 14:11:00.672 ThaliTest[1093:1757300] server session: stateChange:2->0 6Vf7gCVRpsisNTWLkBikvg
,2016-02-09 14:11:00.683 ThaliTest[1093:1757300] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,client bridge: new client socket

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,server bridge: socket closed

,Error in mux client bridge Error: read ECONNRESET

,client bridge: socket closed

,syncRetry called when not started

,# teardown

,client bridge: socket closed

,client bridge: socket closed


```
