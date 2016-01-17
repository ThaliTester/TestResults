#### Test 5615109319b4771_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5615109319b4771/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D238BDC1-EBA6-41D7-B6AB-48286A475574/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D238BDC1-EBA6-41D7-B6AB-48286A475574/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5615109319b4771/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5615109319b4771/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A5273F20-5780-467E-8867-9DE563772685/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57380"
,(lldb)     command script import "/tmp/D238BDC1-EBA6-41D7-B6AB-48286A475574/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-17 16:30:36.377 ThaliTest[1507:4930716] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8E6ACCAF-DB13-4AA1-BC1C-5FB66CEFB5F3/Library/Cookies/Cookies.binarycookies
,2016-01-17 16:30:36.487 ThaliTest[1507:4930716] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-17 16:30:36.489 ThaliTest[1507:4930716] Multi-tasking -> Device: YES, App: YES
,2016-01-17 16:30:36.494 ThaliTest[1507:4930716] Unlimited access to network resources
,2016-01-17 16:30:36.505 ThaliTest[1507:4930716] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-17 16:30:42.755 ThaliTest[1507:4930716] Resetting plugins due to page load.
,2016-01-17 16:30:45.145 ThaliTest[1507:4930716] Finished load of: file:///var/mobile/Containers/Bundle/Application/A5273F20-5780-467E-8867-9DE563772685/ThaliTest.app/www/index.html
,2016-01-17 16:30:45.350 ThaliTest[1507:4930716] JXcore Cordova plugin initializing
,2016-01-17 16:30:45.352 ThaliTest[1507:4930848] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5273F20-5780-467E-8867-9DE563772685/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5273F20-5780-467E-8867-9DE563772685/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5273F20-5780-467E-8867-9DE563772685/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5273F20-5780-467E-8867-9DE563772685/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5273F20-5780-467E-8867-9DE563772685/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5273F20-5780-467E-8867-9DE563772685/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5273F20-5780-467E-8867-9DE563772685/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test app app.js loaded
,TAP version 13
,# setup
,# multiplex can send data
,# teardown
,ok 1 String should be length:200
# setup
,# basic
,# teardown
,ok 2 sane
# setup
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
,# setup
,# #init should register the peerAvailabilityChanged event
,# teardown
,ok 16 should be equal
ok 17 should be equal
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
,ok 31 should be equal
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
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-17 16:37:19.351 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.361 ThaliTest[1507:4930848] server: starting 1453045039351.1507.9tm23Q==
2016-01-17 16:37:19.361 ThaliTest[1507:4930848] multipeer session: start timer: 0x1acfa9c0
2016-01-17 16:37:19.362 ThaliTest[1507:4930848] THEMultipeerSession in,itialized peer 1453045039351.1507
2016-01-17 16:37:19.364 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-17 16:37:19.366 ThaliTest[1507:4930848] jxcore: stopBroadcasting
2,016-01-17 16:37:19.366 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
2016-01-17 16:37:19.366 ThaliTest[1507:4930848] multipeer session: stop timer
2016-01-17 16:37:19.366 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
ok 46 Should, be able to call stopBroadcasting without error
2016-01-17 16:37:19.367 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.370 ThaliTest[1507:4930848] server: starting 1453045039367.1507.GVac9Q==
,2016-01-17 16:37:19.371 ThaliTest[1507:4930848] multipeer session: start timer: 0x1acf9510
2016-01-17 16:37:19.371 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039367.1507
2016-01-17 16:37:19.372 ThaliTest[1507:4930848] jxcore: sta,rtBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-17 16:37:19.373 ThaliTest[1507:4930848] jxcore: stopBroadcasting
2016-01-17 16:37:19.373 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.374 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:19.390 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.399 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.403 ThaliTest[1507:4930848] server: starting 1453045039399.1507.8PAJwA==
,2016-01-17 16:37:19.407 ThaliTest[1507:4930848] multipeer session: start timer: 0x1aba2b80
,2016-01-17 16:37:19.409 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039399.1507
,2016-01-17 16:37:19.412 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.421 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:19.422 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.424 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:19.429 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.432 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.436 ThaliTest[1507:4930848] server: starting 1453045039432.1507.U+tYnw==
,2016-01-17 16:37:19.443 ThaliTest[1507:4930848] multipeer session: start timer: 0x14e61220
,2016-01-17 16:37:19.446 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039432.1507
,2016-01-17 16:37:19.448 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.451 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:19.453 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.454 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:19.459 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.462 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.466 ThaliTest[1507:4930848] server: starting 1453045039462.1507.Igo05w==
,2016-01-17 16:37:19.469 ThaliTest[1507:4930848] multipeer session: start timer: 0x14d81e20
2016-01-17 16:37:19.474 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039462.1507
,2016-01-17 16:37:19.474 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.479 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:19.480 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.482 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:19.487 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.490 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.494 ThaliTest[1507:4930848] server: starting 1453045039490.1507.GvmUPA==
,2016-01-17 16:37:19.497 ThaliTest[1507:4930848] multipeer session: start timer: 0x14e71d80
,2016-01-17 16:37:19.503 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039490.1507
,2016-01-17 16:37:19.505 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.508 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:19.508 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.510 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:19.512 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.517 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.520 ThaliTest[1507:4930848] server: starting 1453045039517.1507.i71SmA==
,2016-01-17 16:37:19.521 ThaliTest[1507:4930848] multipeer session: start timer: 0x14e25e30
,2016-01-17 16:37:19.523 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039517.1507
,2016-01-17 16:37:19.525 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.533 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:19.533 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.534 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:19.538 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.541 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.544 ThaliTest[1507:4930848] server: starting 1453045039541.1507.hbjkew==
,2016-01-17 16:37:19.546 ThaliTest[1507:4930848] multipeer session: start timer: 0x1acf7400
,2016-01-17 16:37:19.547 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039541.1507
,2016-01-17 16:37:19.555 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.557 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:19.558 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.558 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:19.560 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.565 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.568 ThaliTest[1507:4930848] server: starting 1453045039565.1507.BE0b3g==
,2016-01-17 16:37:19.571 ThaliTest[1507:4930848] multipeer session: start timer: 0x1aba4f20
,2016-01-17 16:37:19.573 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039565.1507
,2016-01-17 16:37:19.574 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.580 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:19.581 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.582 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:19.583 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-17 16:37:19.590 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.593 ThaliTest[1507:4930848] server: starting 1453045039590.1507.wRQj5w==
,2016-01-17 16:37:19.597 ThaliTest[1507:4930848] multipeer session: start timer: 0x1ace78a0
,2016-01-17 16:37:19.600 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039590.1507
2016-01-17 16:37:19.602 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.605 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:19.605 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.606 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:19.608 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-17 16:37:19.739 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.742 ThaliTest[1507:4930848] server: starting 1453045039739.1507.iKy5UA==
2016-01-17 16:37:19.742 ThaliTest[1507:4930848] multipeer session: start timer: 0x1aba28b0
2016-01-17 16:37:19.743 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039739.1507
,2016-01-17 16:37:19.746 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-17 16:37:19.747 ThaliTest[1507:4930848] jxcore: startBroadcasting
2016-01-17 16:37:19.747 ThaliTest[1,507:4930848] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-17 16:37:19.749 ThaliTest[1507:4930848] jxcore: stopBroadcasting
2016-01-17 16:37:19.749 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
2016-01-17 16:37:19.749 ThaliTest[1507:4930848] multipeer session: stop timer
2016-01-17 16:37:19.749 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-17 16:37:19.803 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:19.805 ThaliTest[1507:4930848] server: starting 1453045039802.1507.L1o3Jw==
,2016-01-17 16:37:19.807 ThaliTest[1507:4930848] multipeer session: start timer: 0x1ab9acd0
,2016-01-17 16:37:19.810 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045039802.1507
,2016-01-17 16:37:19.813 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2016-01-17 16:37:19.817 ThaliTest[1507:4930848] jxcore: connect foobar
,2016-01-17 16:37:19.818 ThaliTest[1507:4930848] client: unknown peer foobar
,2016-01-17 16:37:19.819 ThaliTest[1507:4930848] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-17 16:37:19.822 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:19.822 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:19.824 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:19.828 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-17 16:37:20.155 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:20.159 ThaliTest[1507:4930848] server: starting 1453045040155.1507.WBEuxw==
2016-01-17 16:37:20.159 ThaliTest[1507:4930848] multipeer session: start timer: 0x1acf0710
2016-01-17 16:37:20.159 ThaliTest[1507:4930848] THEMultipeerSession in,itialized peer 1453045040155.1507
2016-01-17 16:37:20.159 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-17 16:37:20.161 ThaliTest[1507:4930848] jxcore: disconnect
2016-01,-17 16:37:20.161 ThaliTest[1507:4930848] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2016-01-17 16:37:20.162 ThaliTest[1507:4930848] jxcore: stopBroadcasting
2016-01-17 16:37:20.163 ThaliTest[1507:4930848] THEMultipeerS,ession stopping peer
2016-01-17 16:37:20.163 ThaliTest[1507:4930848] multipeer session: stop timer
2016-01-17 16:37:20.163 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-17 16:37:20.286 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:20.289 ThaliTest[1507:4930848] server: starting 1453045040286.1507.MdskSg==
2016-01-17 16:37:20.289 ThaliTest[1507:4930848] multipeer session: start timer: 0x1ab94ee0
2016-01-17 16:37:20.290 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045040286.1507
2016-01-17 16:37:20.290 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-17 16:37:21.556 ThaliTest[1507:4930716] client: found peer: 1453045040142.2112.yMbgNQ==
2016-01-17 16:37:21.557 ThaliTest[1507:4930848] jxcore: connect 1453045040142.2112.yMbgNQ==
2016-01-17 16:37:21.558 ThaliTest[1507:4930848] client session: co,nnect
2016-01-17 16:37:21.558 ThaliTest[1507:4930848] client session: stateChange:0->1 1453045040142.2112.yMbgNQ==
,2016-01-17 16:37:21.931 ThaliTest[1507:4930716] multipeer session: reset timer
,2016-01-17 16:37:21.931 ThaliTest[1507:4930716] multipeer session: stop timer
,2016-01-17 16:37:21.931 ThaliTest[1507:4930716] multipeer session: start timer: 0x1ab94ee0
,2016-01-17 16:37:21.931 ThaliTest[1507:4930716] server session: connect
,2016-01-17 16:37:21.932 ThaliTest[1507:4930716] server session: stateChange:0->1 1453045040142.2112
,2016-01-17 16:37:21.945 ThaliTest[1507:4930716] server: accepting invitation 1453045040142.2112
,2016-01-17 16:37:24.217 ThaliTest[1507:4931416] client session: connected
2016-01-17 16:37:24.217 ThaliTest[1507:4931416] client session: stateChange:1->2 1453045040142.2112.yMbgNQ==
,2016-01-17 16:37:24.228 ThaliTest[1507:4931414] client session: fireConnectCallback: 1453045040142.2112.yMbgNQ==
2016-01-17 16:37:24.228 ThaliTest[1507:4931414] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be ,within range
2016-01-17 16:37:24.230 ThaliTest[1507:4930848] jxcore: disconnect
2016-01-17 16:37:24.236 ThaliTest[1507:4930848] client session: disconnectFromPeer: 1453045040142.2112.yMbgNQ==
,2016-01-17 16:37:24.236 ThaliTest[1507:4930848] client session: disconnect
2016-01-17 16:37:24.236 ThaliTest[1507:4930848] client session: stateChange:2->0 1453045040142.2112.yMbgNQ==
,2016-01-17 16:37:24.322 ThaliTest[1507:4930848] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 16:37:24.358 ThaliTest[1507:4931410] server session: connected
2016-01-17 16:37:24.358 ThaliTest[1507:4931410] server session: stateChange:1->2 1453045040142.2112
,2016-01-17 16:37:24.432 ThaliTest[1507:4931414] server session: not connected 1453045040142.2112
,2016-01-17 16:37:24.434 ThaliTest[1507:4930716] server relay: socket disconnected
,2016-01-17 16:37:24.434 ThaliTest[1507:4930716] server relay: 0x1ab86dc0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting
,2016-01-17 16:37:24.539 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:24.539 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:24.539 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:24.540 ThaliTest[1507:4930848] server session: disconnect
2016-01-17 16:37:24.541 ThaliTest[1507:4930848] server session: stateChange:2->0 1453045040142.2112
,2016-01-17 16:37:24.543 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-17 16:37:25.528 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:25.530 ThaliTest[1507:4930848] server: starting 1453045045528.1507.2+89nQ==
2016-01-17 16:37:25.531 ThaliTest[1507:4930848] multipeer session: start timer: 0x1ace3f80
2016-01-17 16:37:25.531 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045045528.1507
2016-01-17 16:37:25.531 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-17 16:37:26.330 ThaliTest[1507:4930716] client: found peer: 1453045044924.2112.72qDhg==
2016-01-17 16:37:26.331 ThaliTest[1507:4930848] jxcore: connect 1453045044924.2112.72qDhg==
2016-01-17 16:37:26.331 ThaliTest[1507:4930848] client session: co,nnect
2016-01-17 16:37:26.331 ThaliTest[1507:4930848] client session: stateChange:0->1 1453045044924.2112.72qDhg==
,2016-01-17 16:37:26.963 ThaliTest[1507:4930716] multipeer session: reset timer
2016-01-17 16:37:26.964 ThaliTest[1507:4930716] multipeer session: stop timer
2016-01-17 16:37:26.964 ThaliTest[1507:4930716] multipeer session: start timer: 0x1ace3f80
2016-,01-17 16:37:26.965 ThaliTest[1507:4930716] server session: connect
2016-01-17 16:37:26.965 ThaliTest[1507:4930716] server session: stateChange:0->1 1453045044924.2112
,2016-01-17 16:37:26.970 ThaliTest[1507:4930716] server: accepting invitation 1453045044924.2112
,2016-01-17 16:37:29.291 ThaliTest[1507:4931415] client session: connected
2016-01-17 16:37:29.291 ThaliTest[1507:4931415] client session: stateChange:1->2 1453045044924.2112.72qDhg==
,2016-01-17 16:37:29.332 ThaliTest[1507:4931414] client session: fireConnectCallback: 1453045044924.2112.72qDhg==
2016-01-17 16:37:29.332 ThaliTest[1507:4931414] jxcore: connect: success
ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-17 16:37:29.335 ThaliTest[1507:4930848] jxcore: connect 1453045044924.2112.72qDhg==
2016-01-17 16:37:29.335 ThaliTest[1507:4930848] client: already connect(ing/ed) to 1453045044924.2112.72qDhg==
2016-01-17 16:37:29.335 ThaliTest[1507:4930848] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-17 16:37:29.337 ThaliTest[1507:4930848] jxcore: disconnect
2016-01-17 16:37:29.337 ThaliTest[1507:4930848] client session: disconnectFromPeer: 1453045044924.2112.72qDhg==
2016-01-17 16:37:29.337 ThaliTest[1507:4930848] client session: disconnect
,2016-01-17 16:37:29.337 ThaliTest[1507:4930848] client session: stateChange:2->0 1453045044924.2112.72qDhg==
,2016-01-17 16:37:29.348 ThaliTest[1507:4930848] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 16:37:29.457 ThaliTest[1507:4931414] server session: connected
2016-01-17 16:37:29.457 ThaliTest[1507:4931414] server session: stateChange:1->2 1453045044924.2112
,2016-01-17 16:37:29.525 ThaliTest[1507:4931410] server session: not connected 1453045044924.2112
2016-01-17 16:37:29.526 ThaliTest[1507:4930716] server relay: socket disconnected
2016-01-17 16:37:29.526 ThaliTest[1507:4930716] server relay: 0x1ace7020 di,sconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting
2016-01-17 16:37:29.719 ThaliTest[1507:4930848] jxcore: stopBroadcasting
2016-01-17 16:37:29.719 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
2016-01-17 16:37:29.719 ThaliTest[1507:4930848] multipeer session: stop t,imer
2016-01-17 16:37:29.720 ThaliTest[1507:4930848] server session: disconnect
2016-01-17 16:37:29.720 ThaliTest[1507:4930848] server session: stateChange:2->0 1453045044924.2112
,2016-01-17 16:37:29.725 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-17 16:37:29.771 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:29.774 ThaliTest[1507:4930848] server: starting 1453045049771.1507.EQpJBg==
,2016-01-17 16:37:29.776 ThaliTest[1507:4930848] multipeer session: start timer: 0x1acabd20
,2016-01-17 16:37:29.784 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045049771.1507
,2016-01-17 16:37:29.788 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
2016-01-17 16:37:29.788 ThaliTest[1507:4930716] client: found peer: 1453045044924.2112.72qDhg==
ok 83 Should be able to call startBroadcasting without error
2016-01-17 16:37:29.791 ThaliTest[1507:4930716] client: found peer: 1453045045528.1507.2+89nQ==
,2016-01-17 16:37:29.795 ThaliTest[1507:4930848] jxcore: connect 1453045044924.2112.72qDhg==
,2016-01-17 16:37:29.796 ThaliTest[1507:4930848] client session: connect
,2016-01-17 16:37:29.797 ThaliTest[1507:4930848] client session: stateChange:0->1 1453045044924.2112.72qDhg==
,2016-01-17 16:37:29.970 ThaliTest[1507:4930848] jxcore: connect 1453045045528.1507.2+89nQ==
2016-01-17 16:37:29.970 ThaliTest[1507:4930848] client session: connect
2016-01-17 16:37:29.971 ThaliTest[1507:4930848] client session: stateChange:0->1 1453045045528.1507.2+89nQ==
,2016-01-17 16:37:30.867 ThaliTest[1507:4930716] client: lost peer: 1453045044924.2112.72qDhg==
2016-01-17 16:37:30.867 ThaliTest[1507:4930716] client session: onPeerLost: 1453045044924.2112.72qDhg==
2016-01-17 16:37:30.867 ThaliTest[1507:4930716] client session: onLinkFailure: 1453045044924.2112.72qDhg==
2016-01-17 16:37:30.867 ThaliTest[1507:4930716] client session: disconnect
2016-01-17 16:37:30.867 ThaliTest[1507:4930716] client session: stateChange:1->0 1453045044924.2112.72qDhg==
2016-01-17 16:37:,30.868 ThaliTest[1507:4930716] client session: fireConnectCallback: 1453045044924.2112.72qDhg==
2016-01-17 16:37:30.868 ThaliTest[1507:4930716] jxcore: connect: fail: Peer disconnected
2016-01-17 16:37:30.868 ThaliTest[1507:4930716] client: lost peer: 14,53045045528.1507.2+89nQ==
2016-01-17 16:37:30.868 ThaliTest[1507:4930716] client session: onPeerLost: 1453045045528.1507.2+89nQ==
2016-01-17 16:37:30.868 ThaliTest[1507:4930716] client session: onLinkFailure: 1453045045528.1507.2+89nQ==
2016-01-17 16:3,7:30.869 ThaliTest[1507:4930716] client session: disconnect
2016-01-17 16:37:30.870 ThaliTest[1507:4930716] client session: stateChange:1->0 1453045045528.1507.2+89nQ==
2016-01-17 16:37:30.871 ThaliTest[1507:4930716] client session: fireConnectCallback: ,1453045045528.1507.2+89nQ==
2016-01-17 16:37:30.871 ThaliTest[1507:4930716] jxcore: connect: fail: Peer disconnected
,2016-01-17 16:37:30.997 ThaliTest[1507:4930716] multipeer session: reset timer
2016-01-17 16:37:30.998 ThaliTest[1507:4930716] multipeer session: stop timer
2016-01-17 16:37:30.998 ThaliTest[1507:4930716] multipeer session: start timer: 0x1acabd20
2016-01-17 16:37:30.998 ThaliTest[1507:4930716] server session: connect
2016-01-17 16:37:30.998 ThaliTest[1507:4930716] server session: stateChange:0->1 1453045049621.2112
,2016-01-17 16:37:31.007 ThaliTest[1507:4930716] server: accepting invitation 1453045049621.2112
2016-01-17 16:37:31.010 ThaliTest[1507:4930716] client: found peer: 1453045049621.2112.ZaRMOQ==
,2016-01-17 16:37:31.011 ThaliTest[1507:4930848] jxcore: connect 1453045049621.2112.ZaRMOQ==
2016-01-17 16:37:31.038 ThaliTest[1507:4930848] client session: connect
2016-01-17 16:37:31.038 ThaliTest[1507:4930848] client session: stateChange:0->1 1453045049621.2112.ZaRMOQ==
,2016-01-17 16:37:31.872 ThaliTest[1507:4930848] jxcore: connect 1453045044924.2112.72qDhg==
2016-01-17 16:37:31.873 ThaliTest[1507:4930848] client: connect: unreachable 1453045044924.2112.72qDhg==
2016-01-17 16:37:31.873 ThaliTest[1507:4930848] jxcore: connect: fail: Peer unreachable
,2016-01-17 16:37:31.886 ThaliTest[1507:4930848] jxcore: connect 1453045045528.1507.2+89nQ==
2016-01-17 16:37:31.886 ThaliTest[1507:4930848] client: connect: unreachable 1453045045528.1507.2+89nQ==
2016-01-17 16:37:31.886 ThaliTest[1507:4930848] jxcore: connect: fail: Peer unreachable
,2016-01-17 16:37:33.399 ThaliTest[1507:4931410] server session: connected
2016-01-17 16:37:33.400 ThaliTest[1507:4931410] server session: stateChange:1->2 1453045049621.2112
,2016-01-17 16:37:33.404 ThaliTest[1507:4930716] server relay: socket disconnected
2016-01-17 16:37:33.404 ThaliTest[1507:4930716] server relay: 0x1ab35c10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 16:37:33.461 ThaliTest[1507:4931415] server session: not connected 1453045049621.2112
,2016-01-17 16:37:33.799 ThaliTest[1507:4931415] client session: connected
2016-01-17 16:37:33.799 ThaliTest[1507:4931415] client session: stateChange:1->2 1453045049621.2112.ZaRMOQ==
2016-01-17 16:37:33.802 ThaliTest[1507:4931415] client session: fireConnectCallback: 1453045049621.2112.ZaRMOQ==
2016-01-17 16:37:33.802 ThaliTest[1507:4931415] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
2016-01-17 16:37:33.804 ThaliTest[1507:4930848] jxcore: d,isconnect
2016-01-17 16:37:33.804 ThaliTest[1507:4930848] client session: disconnectFromPeer: 1453045049621.2112.ZaRMOQ==
2016-01-17 16:37:33.804 ThaliTest[1507:4930848] client session: disconnect
,2016-01-17 16:37:33.804 ThaliTest[1507:4930848] client session: stateChange:2->0 1453045049621.2112.ZaRMOQ==
,2016-01-17 16:37:33.885 ThaliTest[1507:4930848] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-17 16:37:33.886 ThaliTest[1507:4930848] jxcore: disconnect
2016-01-17 16:37:33.886 ThaliTest[1507:4930848] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-17 16:37:33.918 ThaliTest[1507:4930848] jxcore: stopBroadcasting
2016-01-17 16:37:33.919 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
2016-01-17 16:37:33.919 ThaliTest[1507:4930848] multipeer session: stop timer
2016-01-17 16:37:33.919 ThaliTest[1507:4930848] server session: disconnect
2016-01-17 16:37:33.919 ThaliTest[1507:4930848] server session: stateChange:2->0 1453045049621.2112
,2016-01-17 16:37:33.924 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 54013
,2016-01-17 16:37:35.659 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:35.665 ThaliTest[1507:4930848] server: starting 1453045055659.1507.x6E6kw==
,2016-01-17 16:37:35.667 ThaliTest[1507:4930848] multipeer session: start timer: 0x1acb36c0
,2016-01-17 16:37:35.675 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045055659.1507
,2016-01-17 16:37:35.676 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,2016-01-17 16:37:35.739 ThaliTest[1507:4930716] client: found peer: 1453045054447.2112.2KXF3Q==
,2016-01-17 16:37:35.743 ThaliTest[1507:4930848] jxcore: connect 1453045054447.2112.2KXF3Q==
,2016-01-17 16:37:35.744 ThaliTest[1507:4930848] client session: connect
,2016-01-17 16:37:35.745 ThaliTest[1507:4930848] client session: stateChange:0->1 1453045054447.2112.2KXF3Q==
,2016-01-17 16:37:37.583 ThaliTest[1507:4930716] multipeer session: reset timer
2016-01-17 16:37:37.584 ThaliTest[1507:4930716] multipeer session: stop timer
2016-01-17 16:37:37.584 ThaliTest[1507:4930716] multipeer session: start timer: 0x1acb36c0
2016-01-17 16:37:37.584 ThaliTest[1507:4930716] server session: connect
2016-01-17 16:37:37.584 ThaliTest[1507:4930716] server session: stateChange:0->1 1453045054447.2112
,2016-01-17 16:37:37.592 ThaliTest[1507:4930716] server: accepting invitation 1453045054447.2112
,2016-01-17 16:37:38.374 ThaliTest[1507:4931414] client session: connected
2016-01-17 16:37:38.374 ThaliTest[1507:4931414] client session: stateChange:1->2 1453045054447.2112.2KXF3Q==
,2016-01-17 16:37:38.381 ThaliTest[1507:4931416] client session: fireConnectCallback: 1453045054447.2112.2KXF3Q==
,2016-01-17 16:37:38.381 ThaliTest[1507:4931416] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
2016-01-17 16:37:38.390 ThaliTest[1507:4930716] client: relay established
2016-01-17 16:37:38.390 ThaliTest[1507:4930716] client: new accepted socket: 0x1aca1470
,data in 2190
,data in 5475
,data in 16425
,data in 17520
,data in 18615
,data in 19710
,data in 27375
,data in 32850
,data in 49275
,data in 54750
,data in 55845
,data in 82125
,data in 88695
,data in 103954
,data in 108405
,data in 112785
,data in 131072
ok 91 the test messages should be equal
2016-01-17 16:37:39.254 ThaliTest[1507:4930848] jxcore: disconnect
2016-01-17 16:37:39.254 ThaliTest[1507:4930848] client session: disconnectFromPeer: 1453045054447.2112.2KXF3Q==
2016-01-17 16:37:3,9.254 ThaliTest[1507:4930848] client session: disconnect
2016-01-17 16:37:39.254 ThaliTest[1507:4930848] client session: stateChange:2->0 1453045054447.2112.2KXF3Q==
,2016-01-17 16:37:39.266 ThaliTest[1507:4930848] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
# setup
,2016-01-17 16:37:40.344 ThaliTest[1507:4931412] server session: connected
2016-01-17 16:37:40.344 ThaliTest[1507:4931412] server session: stateChange:1->2 1453045054447.2112
,2016-01-17 16:37:40.349 ThaliTest[1507:4930716] server relay: connected (to port: 54013)
,2016-01-17 16:37:41.005 ThaliTest[1507:4931410] server session: not connected 1453045054447.2112
,calling stopBroadcasting
,2016-01-17 16:37:41.779 ThaliTest[1507:4930848] jxcore: stopBroadcasting
2016-01-17 16:37:41.779 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
2016-01-17 16:37:41.779 ThaliTest[1507:4930848] multipeer session: stop timer
2016-01-17 16:37:41.779 ThaliTest[1507:4930848] server session: disconnect
2016-01-17 16:37:41.779 ThaliTest[1507:4930848] server session: stateChange:2->0 1453045054447.2112
,2016-01-17 16:37:41.790 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,echo server started on port: 54019
2016-01-17 16:37:42.104 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:42.107 ThaliTest[1507:4930848] server: starting 1453045062104.1507.mk1ICA==
2016-01-17 16:37:42.107 ThaliTest[1507:4930848] multipeer session: start timer: 0x1ab2b540
2016-01-17 16:37:42.108 ThaliTest[1507:4930848] THEMultipeerSession initialized peer 1453045062104.1507
2016-01-17 16:37:42.108 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-17 16:37:43.070 ThaliTest[1507:4930716] client: found peer: 1453045061749.2112.brdmwQ==
[{"peerIdentifier":"1453045061749.2112.brdmwQ==","peerName":"(null)","peerAvailable":true}]
2016-01-17 16:37:43.072 ThaliTest[1507:4930848] jxcore: connect 14,53045061749.2112.brdmwQ==
2016-01-17 16:37:43.073 ThaliTest[1507:4930848] client session: connect
,2016-01-17 16:37:43.073 ThaliTest[1507:4930848] client session: stateChange:0->1 1453045061749.2112.brdmwQ==
,2016-01-17 16:37:43.415 ThaliTest[1507:4930716] multipeer session: reset timer
2016-01-17 16:37:43.416 ThaliTest[1507:4930716] multipeer session: stop timer
2016-01-17 16:37:43.416 ThaliTest[1507:4930716] multipeer session: start timer: 0x1ab2b540
2016-,01-17 16:37:43.416 ThaliTest[1507:4930716] server session: connect
2016-01-17 16:37:43.417 ThaliTest[1507:4930716] server session: stateChange:0->1 1453045061749.2112
2016-01-17 16:37:43.424 ThaliTest[1507:4930716] server: accepting invitation 1453045061749.2112
,2016-01-17 16:37:45.961 ThaliTest[1507:4931414] client session: connected
2016-01-17 16:37:45.961 ThaliTest[1507:4931414] client session: stateChange:1->2 1453045061749.2112.brdmwQ==
,2016-01-17 16:37:45.969 ThaliTest[1507:4931415] client session: fireConnectCallback: 1453045061749.2112.brdmwQ==
2016-01-17 16:37:45.969 ThaliTest[1507:4931415] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 First connect should succeed
,2016-01-17 16:37:45.982 ThaliTest[1507:4931416] server session: connected
2016-01-17 16:37:45.983 ThaliTest[1507:4931416] server session: stateChange:1->2 1453045061749.2112
,2016-01-17 16:37:45.986 ThaliTest[1507:4930716] server relay: connected (to port: 54019)
,2016-01-17 16:37:46.011 ThaliTest[1507:4930716] client: relay established
2016-01-17 16:37:46.012 ThaliTest[1507:4930716] client: new accepted socket: 0x1a906ee0
,ok 97 the test messages should be equal
,ok 98 First send should succeed
,2016-01-17 16:37:46.055 ThaliTest[1507:4930716] client: socket closed
2016-01-17 16:37:46.056 ThaliTest[1507:4930716] client relay: socket disconnected
2016-01-17 16:37:46.056 ThaliTest[1507:4930716] client relay: 0x1a906ee0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-17 16:37:46.056 ThaliTest[1507:4930716] client session: socket closed: 1453045061749.2112.brdmwQ==
2016-01-17 ,16:37:46.056 ThaliTest[1507:4930716] client session: onLinkFailure: 1453045061749.2112.brdmwQ==
2016-01-17 16:37:46.056 ThaliTest[1507:4930716] client session: disconnect
2016-01-17 16:37:46.056 ThaliTest[1507:4930716] client session: stateChange:2->0 14,53045061749.2112.brdmwQ==
2016-01-17 16:37:46.069 ThaliTest[1507:4930716] client session: fireConnectionErrorEvent: 1453045061749.2112.brdmwQ==
2016-01-17 16:37:46.071 ThaliTest[1507:4930848] jxcore: connect 1453045061749.2112.brdmwQ==
2016-01-17 16:37,:,46.071 ThaliTest[1507:4930848] client session: connect
2016-01-17 16:37:46.077 ThaliTest[1507:4930848] client session: stateChange:0->1 1453045061749.2112.brdmwQ==
,2016-01-17 16:37:46.212 ThaliTest[1507:4931412] server session: not connected 1453045061749.2112
,2016-01-17 16:37:46.294 ThaliTest[1507:4930716] multipeer session: reset timer
2016-01-17 16:37:46.294 ThaliTest[1507:4930716] multipeer session: stop timer
2016-01-17 16:37:46.295 ThaliTest[1507:4930716] multipeer session: start timer: 0x1ab2b540
2016-,01-17 16:37:46.295 ThaliTest[1507:4930716] server: disconnecting to refresh session (1453045061749.2112)
2016-01-17 16:37:46.296 ThaliTest[1507:4930716] server session: disconnect
2016-01-17 16:37:46.296 ThaliTest[1507:4930716] server session: stateChang,e:2->0 1453045061749.2112
2016-01-17 16:37:46.299 ThaliTest[1507:4930716] server session: connect
2016-01-17 16:37:46.299 ThaliTest[1507:4930716] server session: stateChange:0->1 1453045061749.2112
,2016-01-17 16:37:46.310 ThaliTest[1507:4930716] server: accepting invitation 1453045061749.2112
,2016-01-17 16:37:49.054 ThaliTest[1507:4931416] server session: connected
2016-01-17 16:37:49.054 ThaliTest[1507:4931416] server session: stateChange:1->2 1453045061749.2112
,2016-01-17 16:37:49.059 ThaliTest[1507:4930716] server relay: connected (to port: 54019)
,2016-01-17 16:37:49.068 ThaliTest[1507:4931414] client session: connected
2016-01-17 16:37:49.068 ThaliTest[1507:4931414] client session: stateChange:1->2 1453045061749.2112.brdmwQ==
,2016-01-17 16:37:49.076 ThaliTest[1507:4931414] client session: fireConnectCallback: 1453045061749.2112.brdmwQ==
2016-01-17 16:37:49.076 ThaliTest[1507:4931414] jxcore: connect: success
ok 99 Should be able to connect without error
ok 100 Port should be within range
,ok 101 Second connect should succeed
,2016-01-17 16:37:49.100 ThaliTest[1507:4930716] client: relay established
,2016-01-17 16:37:49.101 ThaliTest[1507:4930716] client: new accepted socket: 0x1ac9a4d0
,ok 102 the test messages should be equal
,ok 103 Second send should succeed
,# setup
,2016-01-17 16:37:49.211 ThaliTest[1507:4930716] client: socket closed
,2016-01-17 16:37:49.211 ThaliTest[1507:4930716] client relay: socket disconnected
2016-01-17 16:37:49.212 ThaliTest[1507:4930716] client relay: 0x1ac9a4d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-17 16:37:49.212 ThaliTest[1507:4930716] client session: socket closed: 1453045061749.2112.brdmwQ==
2016-01-17 16:37:49.212 ThaliTest[1507:4930716] client session: onLinkFailure: 1453045061749.2112.brdmwQ==
2016-01-17 16:37:49.212 ThaliTest[1507:4,930716] client session: disconnect
2016-01-17 16:37:49.212 ThaliTest[1507:4930716] client session: stateChange:2->0 1453045061749.2112.brdmwQ==
,2016-01-17 16:37:49.227 ThaliTest[1507:4930716] client session: fireConnectionErrorEvent: 1453045061749.2112.brdmwQ==
,2016-01-17 16:37:49.245 ThaliTest[1507:4931414] server session: not connected 1453045061749.2112
,calling stopBroadcasting
,2016-01-17 16:37:49.711 ThaliTest[1507:4930848] jxcore: stopBroadcasting
2016-01-17 16:37:49.711 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
2016-01-17 16:37:49.712 ThaliTest[1507:4930848] multipeer session: stop timer
2016-01-17 16:37:49.,712 ThaliTest[1507:4930848] server session: disconnect
2016-01-17 16:37:49.712 ThaliTest[1507:4930848] server session: stateChange:2->0 1453045061749.2112
2016-01-17 16:37:49.716 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/8E6ACCAF-DB13-4AA1-BC1C-5FB66CEFB5F3/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 104 starting event should occur in right order
,2016-01-17 16:37:50.329 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:50.332 ThaliTest[1507:4930848] server: starting Ax-Mk3qZgsTZvBn-cUs3fQ.7xzF3w==
,2016-01-17 16:37:50.334 ThaliTest[1507:4930848] multipeer session: start timer: 0x1ab22a80
,2016-01-17 16:37:50.340 ThaliTest[1507:4930848] THEMultipeerSession initialized peer Ax-Mk3qZgsTZvBn-cUs3fQ
,2016-01-17 16:37:50.341 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,ok 105 started event should occur in right order
,Now in TRM stop
,State of this._isStarted: true
,ok 106 stopping event should occur in right order
,About to call stopBroadcasting
,2016-01-17 16:37:50.346 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:37:50.347 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:37:50.347 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:37:50.349 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,ok 107 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/8E6ACCAF-DB13-4AA1-BC1C-5FB66CEFB5F3/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-17 16:37:52.334 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:52.337 ThaliTest[1507:4930848] server: starting Ax-Mk3qZgsTZvBn-cUs3fQ.RRtRvw==
2016-01-17 16:37:52.338 ThaliTest[1507:4930848] multipeer session: start timer: 0x1ac7f160
2016-01-17 16:37:52.338 ThaliTest[1507:4930848] THEMultipeerSessio,n initialized peer Ax-Mk3qZgsTZvBn-cUs3fQ
2016-01-17 16:37:52.338 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error
ok 109 deviceName should not be null
Now in TRM stop
State of this._isStar,ted: true
About to call stopBroadcasting
2016-01-17 16:37:52.341 ThaliTest[1507:4930848] jxcore: stopBroadcasting
2016-01-17 16:37:52.341 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
2016-01-17 16:37:52.342 ThaliTest[1507:4930848] multipee,r session: stop timer
2016-01-17 16:37:52.342 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
# setup
,# ThaliReplicationManager replicates database
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/8E6ACCAF-DB13-4AA1-BC1C-5FB66CEFB5F3/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-17 16:37:55.638 ThaliTest[1507:4930848] jxcore: startBroadcasting
,2016-01-17 16:37:55.641 ThaliTest[1507:4930848] server: starting Ax-Mk3qZgsTZvBn-cUs3fQ.0vW7Ig==
2016-01-17 16:37:55.641 ThaliTest[1507:4930848] multipeer session: start timer: 0x1c1a8b90
2016-01-17 16:37:55.641 ThaliTest[1507:4930848] THEMultipeerSessio,n initialized peer Ax-Mk3qZgsTZvBn-cUs3fQ
2016-01-17 16:37:55.642 ThaliTest[1507:4930848] jxcore: startBroadcasting: success
,2016-01-17 16:37:55.653 ThaliTest[1507:4930716] client: found peer: wp4bNrcN9Doanl41wQLx1w.nD2stg==
,ok 110 getDeviceIdentity should not return an error
,ok 111 deviceName should not be null
,2016-01-17 16:38:06.021 ThaliTest[1507:4930716] multipeer session: reset timer
2016-01-17 16:38:06.021 ThaliTest[1507:4930716] multipeer session: stop timer
2016-01-17 16:38:06.022 ThaliTest[1507:4930716] multipeer session: start timer: 0x1c1a8b90
,2016-01-17 16:38:06.022 ThaliTest[1507:4930716] server session: connect
2016-01-17 16:38:06.024 ThaliTest[1507:4930716] server session: stateChange:0->1 wp4bNrcN9Doanl41wQLx1w
2016-01-17 16:38:06.032 ThaliTest[1507:4930848] jxcore: connect wp4bNrcN9Doanl,41wQLx1w.nD2stg==
2016-01-17 16:38:06.033 ThaliTest[1507:4930848] client session: connect
2016-01-17 16:38:06.034 ThaliTest[1507:4930848] client session: stateChange:0->1 wp4bNrcN9Doanl41wQLx1w.nD2stg==
2016-01-17 16:38:06.035 ThaliTest[1507:4930716] se,rver: accepting invitation wp4bNrcN9Doanl41wQLx1w
,ok 112 Should be able to put doc without error
,ok 113 1st change of local doc should contain local id
,2016-01-17 16:38:08.777 ThaliTest[1507:4931412] server session: connected
2016-01-17 16:38:08.778 ThaliTest[1507:4931412] server session: stateChange:1->2 wp4bNrcN9Doanl41wQLx1w
,2016-01-17 16:38:08.783 ThaliTest[1507:4930716] server relay: connected (to port: 54034)
,server bridge: new client socket
,2016-01-17 16:38:08.952 ThaliTest[1507:4931412] client session: connected
2016-01-17 16:38:08.953 ThaliTest[1507:4931412] client session: stateChange:1->2 wp4bNrcN9Doanl41wQLx1w.nD2stg==
,2016-01-17 16:38:08.955 ThaliTest[1507:4931412] client session: fireConnectCallback: wp4bNrcN9Doanl41wQLx1w.nD2stg==
2016-01-17 16:38:08.955 ThaliTest[1507:4931412] jxcore: connect: success
,2016-01-17 16:38:08.973 ThaliTest[1507:4930716] client: relay established
2016-01-17 16:38:08.974 ThaliTest[1507:4930716] client: new accepted socket: 0x1c03c5d0
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,ok 114 1st change of remote doc should contain remote id
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,ok 115 Can update remote doc without error
null
,{ ok: true,
  id: 'd8080832-6572-4145-85a0-e7807bd7b6cc',
  rev: '2-58e7a74dc86c359239278a04c62e5d94' }
,ok 116 Remote changes occur in strict order
,client bridge: socket closed
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
client bridge: socket closed
,client bridge: new client socket
,ok 117 Local changes occur in strict order
ok 118 2nd change of local doc should contain remote id
,# setup
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,Now in TRM stop
,State of this._isStarted: true
,About to call stopBroadcasting
,2016-01-17 16:38:29.517 ThaliTest[1507:4930848] jxcore: stopBroadcasting
,2016-01-17 16:38:29.517 ThaliTest[1507:4930848] THEMultipeerSession stopping peer
,2016-01-17 16:38:29.518 ThaliTest[1507:4930848] multipeer session: stop timer
,2016-01-17 16:38:29.519 ThaliTest[1507:4930848] client session: disconnect
,2016-01-17 16:38:29.520 ThaliTest[1507:4930848] client session: stateChange:2->0 wp4bNrcN9Doanl41wQLx1w.nD2stg==
,2016-01-17 16:38:29.547 ThaliTest[1507:4931558] server session: not connected wp4bNrcN9Doanl41wQLx1w
,2016-01-17 16:38:29.594 ThaliTest[1507:4930848] server session: disconnect
,2016-01-17 16:38:29.602 ThaliTest[1507:4930848] server session: stateChange:2->0 wp4bNrcN9Doanl41wQLx1w
,2016-01-17 16:38:29.668 ThaliTest[1507:4930848] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
,Error in mux client bridge Error: read ECONNRESET
,mux server bridge listener closed
syncRetry called when not started
server bridge: socket closed
client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,# teardown
,ok 119 should be equal
,# setup
,# #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
,# teardown
,ok 120 should not be equal
,# setup
,# verify that Thali-specific messages are filtered correctly
,# teardown
,ok 121 irrelevant messages should be ignored
ok 122 relevant messages should not be ignored
ok 123 messages from this device should be ignored
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
