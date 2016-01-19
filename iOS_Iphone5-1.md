#### Test 564317025f150b2_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/564317025f150b2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/EB42F464-075F-4A56-9515-6EA8386E1FBC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/EB42F464-075F-4A56-9515-6EA8386E1FBC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/564317025f150b2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/564317025f150b2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/256F24A3-823C-41A4-A012-7909BE4587E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58354"
,(lldb)     command script import "/tmp/EB42F464-075F-4A56-9515-6EA8386E1FBC/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-19 09:03:35.443 ThaliTest[1630:5200938] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0BA9FDF-2843-41E6-B72F-6E7E9AC90D99/Library/Cookies/Cookies.binarycookies
,2016-01-19 09:03:35.556 ThaliTest[1630:5200938] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-19 09:03:35.558 ThaliTest[1630:5200938] Multi-tasking -> Device: YES, App: YES
,2016-01-19 09:03:35.563 ThaliTest[1630:5200938] Unlimited access to network resources
,2016-01-19 09:03:35.577 ThaliTest[1630:5200938] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-19 09:03:41.865 ThaliTest[1630:5200938] Resetting plugins due to page load.
,2016-01-19 09:03:44.655 ThaliTest[1630:5200938] Finished load of: file:///var/mobile/Containers/Bundle/Application/256F24A3-823C-41A4-A012-7909BE4587E2/ThaliTest.app/www/index.html
,2016-01-19 09:03:44.916 ThaliTest[1630:5200938] JXcore Cordova plugin initializing
,2016-01-19 09:03:44.917 ThaliTest[1630:5201389] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/256F24A3-823C-41A4-A012-7909BE4587E2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/256F24A3-823C-41A4-A012-7909BE4587E2/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/256F24A3-823C-41A4-A012-7909BE4587E2/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/256F24A3-823C-41A4-A012-7909BE4587E2/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/256F24A3-823C-41A4-A012-7909BE4587E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/256F24A3-823C-41A4-A012-7909BE4587E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/256F24A3-823C-41A4-A012-7909BE4587E2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test app app.js loaded
,appEnteringBackground wasn't registered
,TAP version 13
,# setup
,# multiplex can send data
,# teardown
,ok 1 String should be length:200
,# setup
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
ok 8 should not throw
# setup
,# successfully read a previous pkcs12 file and return hash value
,# teardown
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
,ok 11 should not throw
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
# setup
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
# setup
,# #startBroadcasting should throw on too large port
,# teardown
,ok 25 should throw
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,ok 26 should be equal
ok 27 should be equal
,ok 28 should be equal
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
,ok 30 should be equal
ok 31 should be equal
# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,ok 32 should be equal
,ok 33 should be equal
# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
ok 35 should be equal
,# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
ok 37 should be equal
,ok 38 should be equal
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
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-19 09:09:25.289 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.299 ThaliTest[1630:5201389] server: starting 1453190965288.1630.85MKIA==
2016-01-19 09:09:25.299 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b278100
2016-01-19 09:09:25.300 ThaliTest[1630:5201389] THEMultipeerSession in,itialized peer 1453190965288.1630
2016-01-19 09:09:25.300 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-19 09:09:25.302 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2,016-01-19 09:09:25.303 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:09:25.303 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:25.303 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
ok 46 Should, be able to call stopBroadcasting without error
2016-01-19 09:09:25.304 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.310 ThaliTest[1630:5201389] server: starting 1453190965304.1630.mWgmOQ==
2016-01-19 09:09:25.311 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b73be10
2016-01-19 09:09:25.311 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190965304.1630
,2016-01-19 09:09:25.311 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-19 09:09:25.318 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:25.319 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:09:25.319 ThaliTest[1630:5201389] multipeer session: stop timer
,2016-01-19 09:09:25.328 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-19 09:09:25.330 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.335 ThaliTest[1630:5201389] server: starting 1453190965329.1630.yxQi7A==
2016-01-19 09:09:25.336 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b739840
2016-01-19 09:09:25.336 ThaliTest[1630:5201389] THEMultipeerSession in,itialized peer 1453190965329.1630
2016-01-19 09:09:25.336 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-19 09:09:25.338 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2,016-01-19 09:09:25.338 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
,2016-01-19 09:09:25.338 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:25.344 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-19 09:09:25.346 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.355 ThaliTest[1630:5201389] server: starting 1453190965345.1630.oJ/2RA==
2016-01-19 09:09:25.356 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b277710
2016-01-19 09:09:25.356 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190965345.1630
,2016-01-19 09:09:25.356 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-19 09:09:25.362 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:25.362 ThaliTest[16,30:5201389] THEMultipeerSession stopping peer
2016-01-19 09:09:25.364 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:25.364 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting w,ithout error
2016-01-19 09:09:25.367 ThaliTest[1630:5201389] jxcore: startBroadcasting
2016-01-19 09:09:25.375 ThaliTest[1630:5201389] server: starting 1453190965367.1630.Vru8uQ==
2016-01-19 09:09:25.375 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b274c10
,2016-01-19 09:09:25.376 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190965367.1630
2016-01-19 09:09:25.385 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-,01-19 09:09:25.387 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:25.387 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:09:25.387 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:25.387 T,haliTest[1630:5201389] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
,2016-01-19 09:09:25.389 ThaliTest[1630:5201389] jxcore: startBroadcasting
2016-01-19 09:09:25.400 ThaliTest[1630:5201389] server: starting 1453190965388.1630.5iQX2g==
2016-01-19 09:09:25.401 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b523,800
2016-01-19 09:09:25.401 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190965388.1630
2016-01-19 09:09:25.401 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
,2016-01-19 09:09:25.403 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:25.403 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:09:25.403 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:25.,404 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-19 09:09:25.426 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.429 ThaliTest[1630:5201389] server: starting 1453190965425.1630.drBLew==
,2016-01-19 09:09:25.432 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b5acdc0
,2016-01-19 09:09:25.434 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190965425.1630
,2016-01-19 09:09:25.435 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-19 09:09:25.442 ThaliTest[1630:5201389] jxcore: stopBroadcasting
,2016-01-19 09:09:25.444 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
,2016-01-19 09:09:25.445 ThaliTest[1630:5201389] multipeer session: stop timer
,2016-01-19 09:09:25.446 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-19 09:09:25.452 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.456 ThaliTest[1630:5201389] server: starting 1453190965452.1630.MJoPAQ==
,2016-01-19 09:09:25.458 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b2902b0
,2016-01-19 09:09:25.459 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190965452.1630
,2016-01-19 09:09:25.462 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-19 09:09:25.470 ThaliTest[1630:5201389] jxcore: stopBroadcasting
,2016-01-19 09:09:25.472 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
,2016-01-19 09:09:25.473 ThaliTest[1630:5201389] multipeer session: stop timer
,2016-01-19 09:09:25.474 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-19 09:09:25.481 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.484 ThaliTest[1630:5201389] server: starting 1453190965480.1630.aNVrHA==
,2016-01-19 09:09:25.485 ThaliTest[1630:5201389] multipeer session: start timer: 0x1565c600
,2016-01-19 09:09:25.495 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190965480.1630
,2016-01-19 09:09:25.497 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-19 09:09:25.500 ThaliTest[1630:5201389] jxcore: stopBroadcasting
,2016-01-19 09:09:25.501 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
,2016-01-19 09:09:25.503 ThaliTest[1630:5201389] multipeer session: stop timer
,2016-01-19 09:09:25.504 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-19 09:09:25.511 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.514 ThaliTest[1630:5201389] server: starting 1453190965511.1630.dJU+uw==
,2016-01-19 09:09:25.516 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b1bee80
,2016-01-19 09:09:25.519 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190965511.1630
,2016-01-19 09:09:25.521 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-19 09:09:25.529 ThaliTest[1630:5201389] jxcore: stopBroadcasting
,2016-01-19 09:09:25.530 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
,2016-01-19 09:09:25.530 ThaliTest[1630:5201389] multipeer session: stop timer
,2016-01-19 09:09:25.531 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-19 09:09:25.659 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.661 ThaliTest[1630:5201389] server: starting 1453190965659.1630.bU6CLA==
2016-01-19 09:09:25.662 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b52a700
2016-01-19 09:09:25.662 ThaliTest[1630:5201389] THEMultipeerSession in,itialized peer 1453190965659.1630
2016-01-19 09:09:25.662 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-19 09:09:25.664 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.664 ThaliTest[1630:5201389] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2016-01-19 09:09:25.665 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:25.670 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:09:25.670 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:25.,671 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-19 09:09:25.791 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:25.796 ThaliTest[1630:5201389] server: starting 1453190965791.1630.O6+IwA==
2016-01-19 09:09:25.796 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b5a6e00
2016-01-19 09:09:25.796 ThaliTest[1630:5201389] THEMultipeerSession in,itialized peer 1453190965791.1630
2016-01-19 09:09:25.796 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-19 09:09:25.798 ThaliTest[1630:5201389] jxcore: connect foobar
2016-01-19 09:09:25.798 ThaliTest[1630:5201389] client: unknown peer foobar
,2016-01-19 09:09:25.798 ThaliTest[1630:5201389] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-19 09:09:25.807 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:25.807 ThaliTest[1630:5201389] THEMultip,eerSession stopping peer
2016-01-19 09:09:25.807 ThaliTest[1630:5201389] multipeer session: stop timer
,2016-01-19 09:09:25.808 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-19 09:09:27.183 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:27.186 ThaliTest[1630:5201389] server: starting 1453190967183.1630.8pCW+g==
2016-01-19 09:09:27.186 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b7286c0
2016-01-19 09:09:27.187 ThaliTest[1630:5201389] THEMultipeerSession in,itialized peer 1453190967183.1630
2016-01-19 09:09:27.187 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-19 09:09:27.188 ThaliTest[1630:5201389] jxcore: disconnect
2016-01,-19 09:09:27.188 ThaliTest[1630:5201389] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2016-01-19 09:09:27.189 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:27.190 ThaliTest[1630:5201389] THEMultipeerS,ession stopping peer
2016-01-19 09:09:27.191 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:27.191 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-19 09:09:27.269 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:27.271 ThaliTest[1630:5201389] server: starting 1453190967268.1630.W1YW5w==
2016-01-19 09:09:27.272 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b263a90
2016-01-19 09:09:27.272 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190967268.1630
2016-01-19 09:09:27.272 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-19 09:09:29.013 ThaliTest[1630:5200938] client: found peer: 1453190970021.2335.ofaeGQ==
2016-01-19 09:09:29.014 ThaliTest[1630:5201389] jxcore: connect 1453190970021.2335.ofaeGQ==
2016-01-19 09:09:29.014 ThaliTest[1630:5201389] client session: connect
2016-01-19 09:09:29.014 ThaliTest[1630:5201389] client session: stateChange:0->1 1453190970021.2335.ofaeGQ==
,2016-01-19 09:09:29.647 ThaliTest[1630:5200938] multipeer session: reset timer
2016-01-19 09:09:29.648 ThaliTest[1630:5200938] multipeer session: stop timer
2016-01-19 09:09:29.648 ThaliTest[1630:5200938] multipeer session: start timer: 0x1b263a90
2016-01-19 09:09:29.648 ThaliTest[1630:5200938] server session: connect
2016-01-19 09:09:29.648 ThaliTest[1630:5200938] server session: stateChange:0->1 1453190970021.2335
,2016-01-19 09:09:29.655 ThaliTest[1630:5200938] server: accepting invitation 1453190970021.2335
,2016-01-19 09:09:33.725 ThaliTest[1630:5203104] client session: connected
2016-01-19 09:09:33.725 ThaliTest[1630:5203104] client session: stateChange:1->2 1453190970021.2335.ofaeGQ==
,2016-01-19 09:09:33.785 ThaliTest[1630:5203099] server session: connected
2016-01-19 09:09:33.785 ThaliTest[1630:5203099] server session: stateChange:1->2 1453190970021.2335
2016-01-19 09:09:33.793 ThaliTest[1630:5203099] client session: fireConnectCallback: 1453190970021.2335.ofaeGQ==
2016-01-19 09:09:33.793 ThaliTest[1630:5203099] jxcore: connect: success
,ok 75 Should be able to connect without error
ok 76 Port should be within range
2016-01-19 09:09:33.799 ThaliTest[1630:5201389] jxcore: disconnect
2016-01-19 09:09:33.799 ThaliTest[1630:5201389] client session: disconnectFromPeer: 1453190970021.2335.ofa,eGQ==
2016-01-19 09:09:33.799 ThaliTest[1630:5201389] client session: disconnect
2016-01-19 09:09:33.800 ThaliTest[1630:5201389] client session: stateChange:2->0 1453190970021.2335.ofaeGQ==
,2016-01-19 09:09:33.811 ThaliTest[1630:5201389] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,2016-01-19 09:09:33.820 ThaliTest[1630:5200938] server relay: socket disconnected
,2016-01-19 09:09:33.820 ThaliTest[1630:5200938] server relay: 0x1b181480 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
# setup
,2016-01-19 09:09:33.838 ThaliTest[1630:5203102] server session: not connected 1453190970021.2335
,calling stopBroadcasting
2016-01-19 09:09:34.583 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:34.583 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:09:34.583 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:34.583 ThaliTest[1630:5201389] server session: disconnect
2016-01-19 09:09:34.584 ThaliTest[1630:5201389] server session: stateChange:2->0 1453190970021.2335
,2016-01-19 09:09:34.587 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-19 09:09:35.133 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:35.137 ThaliTest[1630:5201389] server: starting 1453190975133.1630.HOv04Q==
2016-01-19 09:09:35.137 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b181420
2016-01-19 09:09:35.137 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190975133.1630
2016-01-19 09:09:35.138 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-19 09:09:36.271 ThaliTest[1630:5200938] client: found peer: 1453190977873.2335.tKKIAA==
2016-01-19 09:09:36.271 ThaliTest[1630:5201389] jxcore: connect 1453190977873.2335.tKKIAA==
2016-01-19 09:09:36.272 ThaliTest[1630:5201389] client session: co,nnect
2016-01-19 09:09:36.272 ThaliTest[1630:5201389] client session: stateChange:0->1 1453190977873.2335.tKKIAA==
,2016-01-19 09:09:36.417 ThaliTest[1630:5200938] multipeer session: reset timer
2016-01-19 09:09:36.417 ThaliTest[1630:5200938] multipeer session: stop timer
2016-01-19 09:09:36.418 ThaliTest[1630:5200938] multipeer session: start timer: 0x1b181420
2016-,01-19 09:09:36.418 ThaliTest[1630:5200938] server session: connect
2016-01-19 09:09:36.418 ThaliTest[1630:5200938] server session: stateChange:0->1 1453190977873.2335
,2016-01-19 09:09:36.428 ThaliTest[1630:5200938] server: accepting invitation 1453190977873.2335
,2016-01-19 09:09:40.604 ThaliTest[1630:5203107] server session: connected
2016-01-19 09:09:40.604 ThaliTest[1630:5203107] server session: stateChange:1->2 1453190977873.2335
,2016-01-19 09:09:40.671 ThaliTest[1630:5200938] server relay: socket disconnected
2016-01-19 09:09:40.672 ThaliTest[1630:5200938] server relay: 0x1b261a80 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 09:09:40.729 ThaliTest[1630:5203099] server session: not connected 1453190977873.2335
,2016-01-19 09:09:40.741 ThaliTest[1630:5203102] client session: connected
,2016-01-19 09:09:40.741 ThaliTest[1630:5203102] client session: stateChange:1->2 1453190977873.2335.tKKIAA==
,2016-01-19 09:09:40.800 ThaliTest[1630:5203099] client session: fireConnectCallback: 1453190977873.2335.tKKIAA==
2016-01-19 09:09:40.800 ThaliTest[1630:5203099] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-19 09:09:40.803 ThaliTest[1630:5201389] jxcore: connect 1453190977873.2335.tKKIAA==
,2016-01-19 09:09:40.803 ThaliTest[1630:5201389] client: already connect(ing/ed) to 1453190977873.2335.tKKIAA==
,2016-01-19 09:09:40.803 ThaliTest[1630:5201389] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2016-01-19 09:09:40.805 ThaliTest[1630:5201389] jxcore: disconnect
,2016-01-19 09:09:40.805 ThaliTest[1630:5201389] client session: disconnectFromPeer: 1453190977873.2335.tKKIAA==
,2016-01-19 09:09:40.806 ThaliTest[1630:5201389] client session: disconnect
,2016-01-19 09:09:40.806 ThaliTest[1630:5201389] client session: stateChange:2->0 1453190977873.2335.tKKIAA==
,2016-01-19 09:09:40.814 ThaliTest[1630:5201389] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-19 09:09:41.400 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:41.400 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:09:41.400 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:41.,401 ThaliTest[1630:5201389] server session: disconnect
2016-01-19 09:09:41.401 ThaliTest[1630:5201389] server session: stateChange:2->0 1453190977873.2335
2016-01-19 09:09:41.402 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-19 09:09:41.990 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:41.992 ThaliTest[1630:5201389] server: starting 1453190981990.1630.EJAjVw==
2016-01-19 09:09:41.992 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b5b9aa0
2016-01-19 09:09:41.992 ThaliTest[1630:5201389] THEMultipeerSession in,itialized peer 1453190981990.1630
2016-01-19 09:09:41.993 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-19 09:09:42.539 ThaliTest[1630:5200938] client: found peer: 1453190977873.2335.tKKIAA==
2016-01-19 09:09:42.540 ThaliTest[1630:5201389] jxcore: connect 1453190977873.2335.tKKIAA==
2016-01-19 09:09:42.540 ThaliTest[1630:5201389] client session: connect
2016-01-19 09:09:42.542 ThaliTest[1630:5201389] client session: stateChange:0->1 1453190977873.2335.tKKIAA==
,2016-01-19 09:09:43.081 ThaliTest[1630:5200938] client: found peer: 1453190984722.2335.2y+qhQ==
2016-01-19 09:09:43.082 ThaliTest[1630:5201389] jxcore: connect 1453190984722.2335.2y+qhQ==
2016-01-19 09:09:43.082 ThaliTest[1630:5201389] client session: connect
2016-01-19 09:09:43.083 ThaliTest[1630:5201389] client session: stateChange:0->1 1453190984722.2335.2y+qhQ==
,2016-01-19 09:09:43.352 ThaliTest[1630:5200938] multipeer session: reset timer
2016-01-19 09:09:43.352 ThaliTest[1630:5200938] multipeer session: stop timer
2016-01-19 09:09:43.352 ThaliTest[1630:5200938] multipeer session: start timer: 0x1b5b9aa0
2016-,01-19 09:09:43.353 ThaliTest[1630:5200938] server session: connect
2016-01-19 09:09:43.353 ThaliTest[1630:5200938] server session: stateChange:0->1 1453190984722.2335
2016-01-19 09:09:43.360 ThaliTest[1630:5200938] server: accepting invitation 1453190984722.2335
,2016-01-19 09:09:44.723 ThaliTest[1630:5200938] client: lost peer: 1453190977873.2335.tKKIAA==
2016-01-19 09:09:44.723 ThaliTest[1630:5200938] client session: onPeerLost: 1453190977873.2335.tKKIAA==
2016-01-19 09:09:44.723 ThaliTest[1630:5200938] client session: onLinkFailure: 1453190977873.2335.tKKIAA==
2016-01-19 09:09:44.723 ThaliTest[1630:5200938] client session: disconnect
2016-01-19 09:09:44.723 ThaliTest[1630:5200938] client session: stateChange:1->0 1453190977873.2335.tKKIAA==
2016-01-19 09:09:44.724 ThaliTest[1630:5200938] client session: fireConnectCallback: 1453190977873.2335.tKKIAA==
2016-01-19 09:09:44.724 ThaliTest[1630:5200938] jxcore: connect: fail: Peer disconnected
,2016-01-19 09:09:45.728 ThaliTest[1630:5201389] jxcore: connect 1453190977873.2335.tKKIAA==
2016-01-19 09:09:45.728 ThaliTest[1630:5201389] client: connect: unreachable 1453190977873.2335.tKKIAA==
2016-01-19 09:09:45.729 ThaliTest[1630:5201389] jxcore: connect: fail: Peer unreachable
,2016-01-19 09:09:47.165 ThaliTest[1630:5203103] client session: connected
2016-01-19 09:09:47.165 ThaliTest[1630:5203103] client session: stateChange:1->2 1453190984722.2335.2y+qhQ==
,2016-01-19 09:09:47.305 ThaliTest[1630:5203106] server session: connected
2016-01-19 09:09:47.305 ThaliTest[1630:5203106] server session: stateChange:1->2 1453190984722.2335
,2016-01-19 09:09:47.311 ThaliTest[1630:5203104] client session: fireConnectCallback: 1453190984722.2335.2y+qhQ==
2016-01-19 09:09:47.311 ThaliTest[1630:5203104] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be ,within range
,2016-01-19 09:09:47.313 ThaliTest[1630:5201389] jxcore: disconnect
2016-01-19 09:09:47.313 ThaliTest[1630:5201389] client session: disconnectFromPeer: 1453190984722.2335.2y+qhQ==
2016-01-19 09:09:47.313 ThaliTest[1630:5201389] client session: disconnect
,2016-01-19 09:09:47.314 ThaliTest[1630:5201389] client session: stateChange:2->0 1453190984722.2335.2y+qhQ==
,2016-01-19 09:09:47.320 ThaliTest[1630:5201389] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-19 09:09:47.322 ThaliTest[1630:5201389] jxcore: disconnect
2016-01-19 09:09:47.322 ThaliTest[1630:5201389] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-19 09:09:47.349 ThaliTest[1630:5200938] server relay: socket disconnected
2016-01-19 09:09:47.349 ThaliTest[1630:5200938] server relay: 0x1b3aae10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 09:09:47.376 ThaliTest[1630:5203106] server session: not connected 1453190984722.2335
,calling stopBroadcasting
2016-01-19 09:09:47.684 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:47.685 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:09:47.685 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:47.685 ThaliTest[1630:5201389] server session: disconnect
2016-01-19 09:09:47.686 ThaliTest[1630:5201389] server session: stateChange:2->0 1453190984722.2335
,2016-01-19 09:09:47.689 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 54993
,2016-01-19 09:09:49.471 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:49.474 ThaliTest[1630:5201389] server: starting 1453190989471.1630.faRcUw==
,2016-01-19 09:09:49.476 ThaliTest[1630:5201389] multipeer session: start timer: 0x15606e40
,2016-01-19 09:09:49.482 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190989471.1630
,2016-01-19 09:09:49.483 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,2016-01-19 09:09:49.958 ThaliTest[1630:5200938] client: found peer: 1453190991433.2335.u+MAlg==
,2016-01-19 09:09:49.960 ThaliTest[1630:5201389] jxcore: connect 1453190991433.2335.u+MAlg==
,2016-01-19 09:09:49.962 ThaliTest[1630:5201389] client session: connect
,2016-01-19 09:09:49.963 ThaliTest[1630:5201389] client session: stateChange:0->1 1453190991433.2335.u+MAlg==
,2016-01-19 09:09:50.533 ThaliTest[1630:5200938] multipeer session: reset timer
2016-01-19 09:09:50.533 ThaliTest[1630:5200938] multipeer session: stop timer
2016-01-19 09:09:50.533 ThaliTest[1630:5200938] multipeer session: start timer: 0x15606e40
2016-01-19 09:09:50.534 ThaliTest[1630:5200938] server session: connect
2016-01-19 09:09:50.534 ThaliTest[1630:5200938] server session: stateChange:0->1 1453190991433.2335
,2016-01-19 09:09:50.540 ThaliTest[1630:5200938] server: accepting invitation 1453190991433.2335
,2016-01-19 09:09:53.836 ThaliTest[1630:5203104] client session: connected
2016-01-19 09:09:53.836 ThaliTest[1630:5203104] client session: stateChange:1->2 1453190991433.2335.u+MAlg==
,2016-01-19 09:09:53.845 ThaliTest[1630:5203099] client session: fireConnectCallback: 1453190991433.2335.u+MAlg==
2016-01-19 09:09:53.848 ThaliTest[1630:5203099] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
,2016-01-19 09:09:53.853 ThaliTest[1630:5200938] client: relay established
2016-01-19 09:09:53.853 ThaliTest[1630:5200938] client: new accepted socket: 0x155cbb70
,data in 7665
,data in 12045
,data in 17520
,data in 27831
,data in 36135
,data in 60225
,data in 67393
,data in 70080
,data in 72270
,data in 75555
,data in 82125
,data in 110595
,data in 112785
2016-01-19 09:09:54.443 ThaliTest[1630:5203107] server session: connected
,2016-01-19 09:09:54.443 ThaliTest[1630:5203107] server session: stateChange:1->2 1453190991433.2335
,data in 131072
,ok 91 the test messages should be equal
2016-01-19 09:09:54.453 ThaliTest[1630:5201389] jxcore: disconnect
2016-01-19 09:09:54.453 ThaliTest[1630:5201389] client session: disconnectFromPeer: 1453190991433.2335.u+MAlg==
2016-01-19 09:09:54.454 ThaliTest[1630:5201389] client session: disconnect
2016-01-19 09:09:54.454 ThaliTest[1630:5201389] client session: stateChange:2->0 1453190991433.2335.u+MAlg==
,2016-01-19 09:09:54.466 ThaliTest[1630:5201389] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
# setup
,2016-01-19 09:09:54.510 ThaliTest[1630:5200938] server relay: connected (to port: 54993)
,2016-01-19 09:09:55.159 ThaliTest[1630:5203099] server session: not connected 1453190991433.2335
,calling stopBroadcasting
,2016-01-19 09:09:55.612 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:09:55.612 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:09:55.612 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:09:55.,613 ThaliTest[1630:5201389] server session: disconnect
2016-01-19 09:09:55.613 ThaliTest[1630:5201389] server session: stateChange:2->0 1453190991433.2335
,2016-01-19 09:09:55.838 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,echo server started on port: 54999
2016-01-19 09:09:58.199 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:09:58.201 ThaliTest[1630:5201389] server: starting 1453190998198.1630.TpvP9A==
2016-01-19 09:09:58.202 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b123e20
2016-01-19 09:09:58.202 ThaliTest[1630:5201389] THEMultipeerSession initialized peer 1453190998198.1630
2016-01-19 09:09:58.202 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-19 09:09:59.485 ThaliTest[1630:5200938] client: found peer: 1453191001230.2335.n2a+/A==
[{"peerIdentifier":"1453191001230.2335.n2a+/A==","peerName":"(null)","peerAvailable":true}]
2016-01-19 09:09:59.486 ThaliTest[1630:5201389] jxcore: connect 14,53191001230.2335.n2a+/A==
2016-01-19 09:09:59.486 ThaliTest[1630:5201389] client session: connect
2016-01-19 09:09:59.486 ThaliTest[1630:5201389] client session: stateChange:0->1 1453191001230.2335.n2a+/A==
,2016-01-19 09:09:59.868 ThaliTest[1630:5200938] multipeer session: reset timer
2016-01-19 09:09:59.868 ThaliTest[1630:5200938] multipeer session: stop timer
2016-01-19 09:09:59.868 ThaliTest[1630:5200938] multipeer session: start timer: 0x1b123e20
2016-,01-19 09:09:59.868 ThaliTest[1630:5200938] server session: connect
2016-01-19 09:09:59.869 ThaliTest[1630:5200938] server session: stateChange:0->1 1453191001230.2335
,2016-01-19 09:09:59.875 ThaliTest[1630:5200938] server: accepting invitation 1453191001230.2335
,2016-01-19 09:10:04.109 ThaliTest[1630:5203099] server session: connected
2016-01-19 09:10:04.109 ThaliTest[1630:5203099] server session: stateChange:1->2 1453191001230.2335
,2016-01-19 09:10:04.115 ThaliTest[1630:5200938] server relay: connected (to port: 54999)
,2016-01-19 09:10:04.192 ThaliTest[1630:5203106] server session: not connected 1453191001230.2335
,2016-01-19 09:10:04.226 ThaliTest[1630:5200938] multipeer session: reset timer
2016-01-19 09:10:04.227 ThaliTest[1630:5200938] multipeer session: stop timer
2016-01-19 09:10:04.227 ThaliTest[1630:5200938] multipeer session: start timer: 0x1b123e20
2016-,01-19 09:10:04.227 ThaliTest[1630:5200938] server: disconnecting to refresh session (1453191001230.2335)
2016-01-19 09:10:04.228 ThaliTest[1630:5200938] server session: disconnect
2016-01-19 09:10:04.228 ThaliTest[1630:5200938] server session: stateChang,e:2->0 1453191001230.2335
2016-01-19 09:10:04.232 ThaliTest[1630:5200938] server session: connect
2016-01-19 09:10:04.232 ThaliTest[1630:5200938] server session: stateChange:0->1 1453191001230.2335
,2016-01-19 09:10:04.249 ThaliTest[1630:5200938] server: accepting invitation 1453191001230.2335
,2016-01-19 09:10:04.301 ThaliTest[1630:5203099] client session: connected
,2016-01-19 09:10:04.304 ThaliTest[1630:5203099] client session: stateChange:1->2 1453191001230.2335.n2a+/A==
,2016-01-19 09:10:04.317 ThaliTest[1630:5203099] client session: fireConnectCallback: 1453191001230.2335.n2a+/A==
2016-01-19 09:10:04.317 ThaliTest[1630:5203099] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
ok 96 First connect should succeed
,2016-01-19 09:10:04.344 ThaliTest[1630:5200938] client: relay established
2016-01-19 09:10:04.345 ThaliTest[1630:5200938] client: new accepted socket: 0x156de3b0
,ok 97 the test messages should be equal
ok 98 First send should succeed
,2016-01-19 09:10:04.397 ThaliTest[1630:5200938] client: socket closed
2016-01-19 09:10:04.398 ThaliTest[1630:5200938] client relay: socket disconnected
2016-01-19 09:10:04.398 ThaliTest[1630:5200938] client relay: 0x156de3b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 09:10:04.398 ThaliTest[1630:5200938] client session: socket closed: 1453191001230.2335.n2a+/A==
,2016-01-19 09:10:04.398 ThaliTest[1630:5200938] client session: onLinkFailure: 1453191001230.2335.n2a+/A==
2016-01-19 09:10:04.398 ThaliTest[1630:5200938] client session: disconnect
2016-01-19 09:10:04.398 ThaliTest[1630:5200938] client session: stateChange:2->0 1453191001230.2335.n2a+/A==
,2016-01-19 09:10:04.413 ThaliTest[1630:5200938] client session: fireConnectionErrorEvent: 1453191001230.2335.n2a+/A==
,2016-01-19 09:10:04.415 ThaliTest[1630:5201389] jxcore: connect 1453191001230.2335.n2a+/A==
2016-01-19 09:10:04.424 ThaliTest[1630:5201389] client session: connect
,2016-01-19 09:10:04.426 ThaliTest[1630:5201389] client session: stateChange:0->1 1453191001230.2335.n2a+/A==
,2016-01-19 09:10:08.259 ThaliTest[1630:5203239] server session: connected
2016-01-19 09:10:08.259 ThaliTest[1630:5203239] server session: stateChange:1->2 1453191001230.2335
,2016-01-19 09:10:08.267 ThaliTest[1630:5200938] server relay: connected (to port: 54999)
,2016-01-19 09:10:08.365 ThaliTest[1630:5203104] server session: not connected 1453191001230.2335
,2016-01-19 09:10:08.798 ThaliTest[1630:5203104] client session: connected
2016-01-19 09:10:08.798 ThaliTest[1630:5203104] client session: stateChange:1->2 1453191001230.2335.n2a+/A==
,2016-01-19 09:10:08.808 ThaliTest[1630:5203107] client session: fireConnectCallback: 1453191001230.2335.n2a+/A==
2016-01-19 09:10:08.808 ThaliTest[1630:5203107] jxcore: connect: success
ok 99 Should be able to connect without error
ok 100 Port should be within range
ok 101 Second connect should succeed
,2016-01-19 09:10:08.832 ThaliTest[1630:5200938] client: relay established
2016-01-19 09:10:08.832 ThaliTest[1630:5200938] client: new accepted socket: 0x156f1200
,ok 102 the test messages should be equal
,ok 103 Second send should succeed
,# setup
,2016-01-19 09:10:08.899 ThaliTest[1630:5200938] client: socket closed
2016-01-19 09:10:08.899 ThaliTest[1630:5200938] client relay: socket disconnected
2016-01-19 09:10:08.899 ThaliTest[1630:5200938] client relay: 0x156f1200 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 09:10:08.899 ThaliTest[1630:5200938] client session: socket closed: 1453191001230.2335.n2a+/A==
2016-01-19 ,09:10:08.899 ThaliTest[1630:5200938] client session: onLinkFailure: 1453191001230.2335.n2a+/A==
2016-01-19 09:10:08.899 ThaliTest[1630:5200938] client session: disconnect
2016-01-19 09:10:08.900 ThaliTest[1630:5200938] client session: stateChange:2->0 14,53191001230.2335.n2a+/A==
,2016-01-19 09:10:08.907 ThaliTest[1630:5200938] client session: fireConnectionErrorEvent: 1453191001230.2335.n2a+/A==
,calling stopBroadcasting
2016-01-19 09:10:09.173 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:10:09.173 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:10:09.173 ThaliTest[1630:5201389] multipeer session: stop timer
,2016-01-19 09:10:09.173 ThaliTest[1630:5201389] server session: disconnect
2016-01-19 09:10:09.174 ThaliTest[1630:5201389] server session: stateChange:2->0 1453191001230.2335
2016-01-19 09:10:09.178 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C0BA9FDF-2843-41E6-B72F-6E7E9AC90D99/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 104 starting event should occur in right order
2016-01-19 09:10:10.832 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:10:10.840 ThaliTest[1630:5201389] server: starting jhtZruJZ3UIZw5wMArQ0mw.EQi6XA==
,2016-01-19 09:10:10.843 ThaliTest[1630:5201389] multipeer session: start timer: 0x156d8440
2016-01-19 09:10:10.845 ThaliTest[1630:5201389] THEMultipeerSession initialized peer jhtZruJZ3UIZw5wMArQ0mw
2016-01-19 09:10:10.845 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
,2016-01-19 09:10:10.851 ThaliTest[1630:5200938] client: found peer: 1453191001230.2335.n2a+/A==
ok 105 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 106 stopping event should occur in right order
About to ,call stopBroadcasting
2016-01-19 09:10:10.854 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:10:10.854 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
2016-01-19 09:10:10.854 ThaliTest[1630:5201389] multipeer session: stop time,r
2016-01-19 09:10:10.855 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 107 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C0BA9FDF-2843-41E6-B72F-6E7E9AC90D99/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-19 09:10:11.945 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:10:11.948 ThaliTest[1630:5201389] server: starting jhtZruJZ3UIZw5wMArQ0mw.JbAWHQ==
2016-01-19 09:10:11.948 ThaliTest[1630:5201389] multipeer session: start timer: 0x1b38f100
2016-01-19 09:10:11.948 ThaliTest[1630:5201389] THEMultipeerSessio,n initialized peer jhtZruJZ3UIZw5wMArQ0mw
2016-01-19 09:10:11.949 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error
ok 109 deviceName should not be null
Now in TRM stop
State of this._isStar,ted: true
About to call stopBroadcasting
2016-01-19 09:10:11.951 ThaliTest[1630:5201389] jxcore: stopBroadcasting
2016-01-19 09:10:11.951 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
,2016-01-19 09:10:11.951 ThaliTest[1630:5201389] multipeer session: stop timer
2016-01-19 09:10:11.956 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
# setup
,# ThaliReplicationManager replicates database
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C0BA9FDF-2843-41E6-B72F-6E7E9AC90D99/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-19 09:10:14.614 ThaliTest[1630:5201389] jxcore: startBroadcasting
,2016-01-19 09:10:14.616 ThaliTest[1630:5201389] server: starting jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
2016-01-19 09:10:14.617 ThaliTest[1630:5201389] multipeer session: start timer: 0x1d136000
2016-01-19 09:10:14.617 ThaliTest[1630:5201389] THEMultipeerSessio,n initialized peer jhtZruJZ3UIZw5wMArQ0mw
2016-01-19 09:10:14.617 ThaliTest[1630:5201389] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error
ok 111 deviceName should not be null
,2016-01-19 09:10:15.065 ThaliTest[1630:5200938] client: found peer: ZTHUoh1ZkhpN3fJwV-fsPw.VOnTzg==
,2016-01-19 09:10:25.337 ThaliTest[1630:5201389] jxcore: connect ZTHUoh1ZkhpN3fJwV-fsPw.VOnTzg==
,2016-01-19 09:10:25.339 ThaliTest[1630:5201389] client session: connect
,2016-01-19 09:10:25.341 ThaliTest[1630:5201389] client session: stateChange:0->1 ZTHUoh1ZkhpN3fJwV-fsPw.VOnTzg==
,ok 112 Should be able to put doc without error
,ok 113 1st change of local doc should contain local id
,2016-01-19 09:10:25.611 ThaliTest[1630:5200938] multipeer session: reset timer
2016-01-19 09:10:25.611 ThaliTest[1630:5200938] multipeer session: stop timer
2016-01-19 09:10:25.612 ThaliTest[1630:5200938] multipeer session: start timer: 0x1d136000
2016-,01-19 09:10:25.612 ThaliTest[1630:5200938] server session: connect
2016-01-19 09:10:25.612 ThaliTest[1630:5200938] server session: stateChange:0->1 ZTHUoh1ZkhpN3fJwV-fsPw
2016-01-19 09:10:25.618 ThaliTest[1630:5200938] server: accepting invitation ZTHUoh1ZkhpN3fJwV-fsPw
,2016-01-19 09:10:29.805 ThaliTest[1630:5203261] client session: connected
2016-01-19 09:10:29.806 ThaliTest[1630:5203261] client session: stateChange:1->2 ZTHUoh1ZkhpN3fJwV-fsPw.VOnTzg==
,2016-01-19 09:10:29.815 ThaliTest[1630:5203239] client session: fireConnectCallback: ZTHUoh1ZkhpN3fJwV-fsPw.VOnTzg==
2016-01-19 09:10:29.815 ThaliTest[1630:5203239] jxcore: connect: success
,2016-01-19 09:10:29.827 ThaliTest[1630:5200938] client: relay established
2016-01-19 09:10:29.827 ThaliTest[1630:5200938] client: new accepted socket: 0x1b6608e0
,2016-01-19 09:10:29.876 ThaliTest[1630:5203284] server session: connected
2016-01-19 09:10:29.876 ThaliTest[1630:5203284] server session: stateChange:1->2 ZTHUoh1ZkhpN3fJwV-fsPw
,client bridge: new client socket
client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,2016-01-19 09:10:30.785 ThaliTest[1630:5200938] server relay: connected (to port: 55014)
,server bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: socket closed
,ok 114 1st change of remote doc should contain remote id
,client bridge: new client socket
,ok 115 Can update remote doc without error
,null
,{ ok: true,
  id: '4e7acb4d-4ea5-4924-af57-289cfe45b3b0',
  rev: '2-ae718117cf08c07928858dafc26b4d40' }
,client bridge: new client socket
,ok 116 Remote changes occur in strict order
,client bridge: socket closed
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
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
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,ok 117 Local changes occur in strict order
ok 118 2nd change of local doc should contain remote id
,client bridge: socket closed
,client bridge: new client socket
# setup
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,appEnteredForeground wasn't registered
,Now in TRM stop
,State of this._isStarted: true
About to call stopBroadcasting
,2016-01-19 09:10:45.261 ThaliTest[1630:5201389] jxcore: stopBroadcasting
,2016-01-19 09:10:45.262 ThaliTest[1630:5201389] THEMultipeerSession stopping peer
,2016-01-19 09:10:45.262 ThaliTest[1630:5201389] multipeer session: stop timer
,2016-01-19 09:10:45.263 ThaliTest[1630:5201389] client session: disconnect
,2016-01-19 09:10:45.267 ThaliTest[1630:5201389] client session: stateChange:2->0 ZTHUoh1ZkhpN3fJwV-fsPw.VOnTzg==
,2016-01-19 09:10:45.393 ThaliTest[1630:5201389] server session: disconnect
,2016-01-19 09:10:45.400 ThaliTest[1630:5201389] server session: stateChange:2->0 ZTHUoh1ZkhpN3fJwV-fsPw
,2016-01-19 09:10:46.307 ThaliTest[1630:5201389] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,Process 1630 stopped
* thread #17: tid = 0x4f6590, 0x38ef3ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCSession.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x81b2c3f9)
    frame #0: 0x38ef3ae6 libobjc.A.dylib`objc_msgSend + 6
libobjc.A.dylib`objc_msgSend:
->  0x38ef3ae6 <+6>:  ldrh.w r12, [r9, #0xc]
    0x38ef3aea <+10>: ldr.w  r9, [r9, #0x8]
    0x38ef3aee <+14>: and.w  r12, r12, r1
    0x38ef3af2 <+18>: add.w  r9, r9, r12, lsl #3
,* thread #17: tid = 0x4f6590, 0x38ef3ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCSession.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x81b2c3f9)
  * frame #0: 0x38ef3ae6 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x29d3f85e MultipeerConnectivity`<redacted> + 1334
    frame #2: 0x3961e72a libdispatch.dylib`<redacted> + 2042
    frame #3: 0x3960dd6e libdispatch.dylib`<redacted> + 738
    frame #4: 0x39615b5c libdispatch.dylib`<redacted> + 592
    frame #5: 0x3960ef86 libdispatch.dylib`<redacted> + 282
    frame #6: 0x3961737c libdispatch.dylib`<redacted> + 400
    frame #7: 0x396171ea libdispatch.dylib`<redacted> + 94
    frame #8: 0x397a0e0c libsystem_pthread.dylib`_pthread_wqthread + 1024
    frame #9: 0x397a09fc libsystem_pthread.dylib`start_wqthread + 8

```
