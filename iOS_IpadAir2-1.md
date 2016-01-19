#### Test 565307121a686b7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/565307121a686b7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DAF85B30-93D1-47DA-A598-E0C8A4FB9795/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DAF85B30-93D1-47DA-A598-E0C8A4FB9795/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/565307121a686b7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/565307121a686b7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58811"
,(lldb)     command script import "/tmp/DAF85B30-93D1-47DA-A598-E0C8A4FB9795/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-19 23:05:15.050 ThaliTest[2390:5118108] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B2759DC7-9C43-4BE9-AE47-A530560819AC/Library/Cookies/Cookies.binarycookies
,2016-01-19 23:05:15.298 ThaliTest[2390:5118108] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-19 23:05:15.299 ThaliTest[2390:5118108] Multi-tasking -> Device: YES, App: YES
,2016-01-19 23:05:15.305 ThaliTest[2390:5118108] Unlimited access to network resources
,2016-01-19 23:05:15.311 ThaliTest[2390:5118108] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-19 23:05:19.425 ThaliTest[2390:5118108] Resetting plugins due to page load.
,2016-01-19 23:05:20.873 ThaliTest[2390:5118108] Finished load of: file:///var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/index.html
,2016-01-19 23:05:21.012 ThaliTest[2390:5118108] JXcore Cordova plugin initializing
,2016-01-19 23:05:21.013 ThaliTest[2390:5119329] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 43 should be equal

ok 44 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-19 23:10:42.359 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.364 ThaliTest[2390:5119329] server: starting 1453241442359.2390.p1fbww==
,2016-01-19 23:10:42.365 ThaliTest[2390:5119329] multipeer session: start timer: 0x17719520
2016-01-19 23:10:42.365 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241442359.2390
2016-01-19 23:10:42.365 ThaliTest[2390:5119329] jxcore: sta,rtBroadcasting: success
ok 45 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.366 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:42.366 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.366 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.366 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error

2016-01-19 23:10:42.367 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.368 ThaliTest[2390:5119329] server: starting 1453241442367.2390.+1lrhQ==
2016-01-19 23:10:42.369 ThaliTest[2390:5119329] multipeer session: start timer: 0x17a57230
2016-01-19 23:10:42.369 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241442367.2390
,2016-01-19 23:10:42.372 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.373 ThaliTest[2390:5119329] jxcore: stopBroadcasting
,2016-01-19 23:10:42.373 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.373 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.373 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error

2016-01-19 23:10:42.374 ThaliTest[2390:5119329] jxcore: startBroadcasting
2016-01-19 23:10:42.375 ThaliTest[2390:5119329] server: starting 1453241442373.2390.IY/PCQ==
2016-01-19 23:10:42.375 ThaliTest[2,390:5119329] multipeer session: start timer: 0x1741d0d0
2016-01-19 23:10:42.375 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241442373.2390
2016-01-19 23:10:42.375 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.376 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:42.376 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.376 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.,376 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error

2016-01-19 23:10:42.377 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.379 ThaliTest[2390:5119329] server: starting 1453241442377.2390.Jrqirg==
2016-01-19 23:10:42.379 ThaliTest[2390:5119329] multipeer session: start timer: 0x17a52c90
2016-01-19 23:10:42.379 ThaliTest[2390:5119329] THEMultipeerSession in,itialized peer 1453241442377.2390
2016-01-19 23:10:42.379 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.380 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:42.380 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.380 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.380 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error

2016-01-19 23:10:42.381 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.383 ThaliTest[2390:5119329] server: starting 1453241442381.2390.aBPS+Q==
2016-01-19 23:10:42.383 ThaliTest[2390:5119329] multipeer session: start timer: 0x17a53cc0
2016-01-19 23:10:42.383 ThaliTest[2390:5119329] THEMultipeerSession in,itialized peer 1453241442381.2390
2016-01-19 23:10:42.383 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.384 ThaliTest[2390:5119329] jxcore: stopBroadcasting,
2016-01-19 23:10:42.384 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.384 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.384 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error

2016-01-19 23:10:42.385 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.387 ThaliTest[2390:5119329] server: starting 1453241442385.2390.GJRNow==
2016-01-19 23:10:42.387 ThaliTest[2390:5119329] multipeer session: start timer: 0x17357d60
2016-01-19 23:10:42.387 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241442385.2390
2016-01-19 23:10:42.387 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.388 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:42.389 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.389 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.390 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error

2016-01-19 23:10:42.390 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.393 ThaliTest[2390:5119329] server: starting 1453241442390.2390.zLIMdQ==
2016-01-19 23:10:42.394 ThaliTest[2390:5119329] multipeer session: start timer: 0x17af7860
2016-01-19 23:10:42.394 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241442390.2390
2016-01-19 23:10:42.394 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.395 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:42.395 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.395 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.395 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error

2016-01-19 23:10:42.395 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.398 ThaliTest[2390:5119329] server: starting 1453241442395.2390.8egwYQ==
2016-01-19 23:10:42.398 ThaliTest[2390:5119329] multipeer session: start timer: 0x17355760
2016-01-19 23:10:42.398 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241442395.2390
2016-01-19 23:10:42.398 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.399 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:42.400 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.400 ThaliTest[2390:5119329] multipeer session: stop timer
,2016-01-19 23:10:42.400 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error

,2016-01-19 23:10:42.401 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.403 ThaliTest[2390:5119329] server: starting 1453241442401.2390.0Eu80g==
2016-01-19 23:10:42.404 ThaliTest[2390:5119329] multipeer session: start timer: 0x17a53580
2016-01-19 23:10:42.404 ThaliTest[2390:5119329] THEMultipeerSession in,itialized peer 1453241442401.2390
2016-01-19 23:10:42.404 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.405 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:42.405 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
,2016-01-19 23:10:42.405 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.406 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 62 Should be able to call stopBroadcasting without error

2016-01-19 23:10:42.406 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.409 ThaliTest[2390:5119329] server: starting 1453241442406.2390.rk7tIg==
2016-01-19 23:10:42.409 ThaliTest[2390:5119329] multipeer session: start timer: 0x17355b40
2016-01-19 23:10:42.409 ThaliTest[2390:5119329] THEMultipeerSession in,itialized peer 1453241442406.2390
2016-01-19 23:10:42.409 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.410 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:42.410 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.410 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.410 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-19 23:10:42.699 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.700 ThaliTest[2390:5119329] server: starting 1453241442699.2390.UplukQ==
2016-01-19 23:10:42.700 ThaliTest[2390:5119329] multipeer session: start timer: 0x17787100
2016-01-19 23:10:42.700 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241442699.2390
,2016-01-19 23:10:42.702 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.703 ThaliTest[2390:5119329] jxcore: startBroadcasting
2016-01-19 23:10:42.703 ThaliTest,[2390:5119329] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

,2016-01-19 23:10:42.704 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:42.705 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.705 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.705 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-19 23:10:42.760 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:42.761 ThaliTest[2390:5119329] server: starting 1453241442760.2390.7g6j1Q==
2016-01-19 23:10:42.761 ThaliTest[2390:5119329] multipeer session: start timer: 0x17683310
2016-01-19 23:10:42.761 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241442760.2390
,2016-01-19 23:10:42.763 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.763 ThaliTest[2390:5119329] jxcore: connect foobar
2016-01-19 23:10:42.763 ThaliTest[2390:5119329] client: unknown peer foobar
2016-01-19 23:10:42.764 ThaliTest[2390:5119329] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer

2016-01-19 23:10:42.765 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:,10:42.765 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:42.765 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:42.765 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-19 23:10:43.145 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:43.146 ThaliTest[2390:5119329] server: starting 1453241443145.2390.WBpgTw==
2016-01-19 23:10:43.146 ThaliTest[2390:5119329] multipeer session: start timer: 0x17687ff0
2016-01-19 23:10:43.146 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241443145.2390
,2016-01-19 23:10:43.148 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-01-19 23:10:43.149 ThaliTest[2390:5119329] jxcore: disconnect
2016-01-19 23:10:43.149 ThaliTest[2390:5,119329] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 

,2016-01-19 23:10:43.150 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:43.151 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:43.151 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:43.151 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-19 23:10:43.263 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:10:43.264 ThaliTest[2390:5119329] server: starting 1453241443263.2390.AJfD5A==
2016-01-19 23:10:43.264 ThaliTest[2390:5119329] multipeer session: start timer: 0x17641fd0
2016-01-19 23:10:43.264 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241443263.2390
2016-01-19 23:10:43.264 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-01-19 23:10:44.117 ThaliTest[2390:5118108] client: found peer: 1453241442856.202.eAYUYA==
2016-01-19 23:10:44.118 ThaliTest[2390:5119329] jxcore: connect 1453241442856.202.eAYUYA==
2016-01-19 23:10:44.118 ThaliTest[2390:5119329] client session: conn,ect
2016-01-19 23:10:44.118 ThaliTest[2390:5119329] client session: stateChange:0->1 1453241442856.202.eAYUYA==
,2016-01-19 23:10:44.692 ThaliTest[2390:5118108] server session: connect
2016-01-19 23:10:44.693 ThaliTest[2390:5118108] server session: stateChange:0->1 1453241442856.202
2016-01-19 23:10:44.692 ThaliTest[2390:5118108] multipeer session: reset timer
2016-01-19 23:10:44.692 ThaliTest[2390:5118108] multipeer session: stop timer
2016-01-19 23:10:44.692 ThaliTest[2390:5118108] multipeer session: start timer: 0x17641fd0
,2016-01-19 23:10:44.694 ThaliTest[2390:5118108] server: accepting invitation 1453241442856.202
,2016-01-19 23:10:49.162 ThaliTest[2390:5119932] server session: connected
2016-01-19 23:10:49.162 ThaliTest[2390:5119932] server session: stateChange:1->2 1453241442856.202
,2016-01-19 23:10:49.179 ThaliTest[2390:5119932] client session: connected
2016-01-19 23:10:49.179 ThaliTest[2390:5119932] client session: stateChange:1->2 1453241442856.202.eAYUYA==
,2016-01-19 23:10:49.346 ThaliTest[2390:5118108] server relay: socket disconnected
2016-01-19 23:10:49.346 ThaliTest[2390:5118108] server relay: 0x177cc130 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
2016-01-19 23:10:49.346 ThaliTest[2390:5119927] client session: fireConnectCallback: 1453241442856.202.eAYUYA==
2016-01-19 23:10:49.346 ThaliTest[2390:5119927] jxcore: connect: success
,ok 75 Should be able to connect without error

,ok 76 Port should be within range

,2016-01-19 23:10:49.347 ThaliTest[2390:5119329] jxcore: disconnect
,2016-01-19 23:10:49.348 ThaliTest[2390:5119329] client session: disconnectFromPeer: 1453241442856.202.eAYUYA==
2016-01-19 23:10:49.348 ThaliTest[2390:5119329] client session: disconnect
2016-01-19 23:10:49.348 ThaliTest[2390:5119329] client session: stateChange:2->0 1453241442856.202.eAYUYA==
,2016-01-19 23:10:49.406 ThaliTest[2390:5119329] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-19 23:10:49.728 ThaliTest[2390:5119927] server session: not connected 1453241442856.202
,calling stopBroadcasting

,2016-01-19 23:10:54.894 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:10:54.895 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:10:54.895 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:10:54.895 ThaliTest[2390:5119329] server session: disconnect
2016-01-19 23:10:54.895 ThaliTest[2390:5119329] server session: stateChange:2->0 1453241442856.202
2016-01-19 23:10:54.895 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-19 23:11:04.075 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:11:04.077 ThaliTest[2390:5119329] server: starting 1453241464075.2390.3YBbOA==
2016-01-19 23:11:04.077 ThaliTest[2390:5119329] multipeer session: start timer: 0x177d1b80
2016-01-19 23:11:04.077 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241464075.2390
2016-01-19 23:11:04.077 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-19 23:11:04.938 ThaliTest[2390:5118108] client: found peer: 1453241463217.202.IN5W+g==
,2016-01-19 23:11:04.939 ThaliTest[2390:5119329] jxcore: connect 1453241463217.202.IN5W+g==
2016-01-19 23:11:04.939 ThaliTest[2390:5119329] client session: connect
2016-01-19 23:11:04.939 ThaliTest[2390:5119329] client session: stateChange:0->1 1453241463217.202.IN5W+g==
,2016-01-19 23:11:05.107 ThaliTest[2390:5118108] multipeer session: reset timer
2016-01-19 23:11:05.107 ThaliTest[2390:5118108] multipeer session: stop timer
2016-01-19 23:11:05.107 ThaliTest[2390:5118108] multipeer session: start timer: 0x177d1b80
2016-,01-19 23:11:05.107 ThaliTest[2390:5118108] server session: connect
2016-01-19 23:11:05.108 ThaliTest[2390:5118108] server session: stateChange:0->1 1453241463217.202
2016-01-19 23:11:05.109 ThaliTest[2390:5118108] server: accepting invitation 1453241463217.202
,2016-01-19 23:11:09.786 ThaliTest[2390:5119923] server session: connected
2016-01-19 23:11:09.786 ThaliTest[2390:5119923] server session: stateChange:1->2 1453241463217.202
,2016-01-19 23:11:09.788 ThaliTest[2390:5118108] server relay: socket disconnected
2016-01-19 23:11:09.788 ThaliTest[2390:5118108] server relay: 0x1754c380 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 23:11:09.852 ThaliTest[2390:5120007] server session: not connected 1453241463217.202
,2016-01-19 23:11:10.254 ThaliTest[2390:5120007] client session: connected
2016-01-19 23:11:10.254 ThaliTest[2390:5120007] client session: stateChange:1->2 1453241463217.202.IN5W+g==
,2016-01-19 23:11:10.310 ThaliTest[2390:5119937] client session: fireConnectCallback: 1453241463217.202.IN5W+g==
2016-01-19 23:11:10.310 ThaliTest[2390:5119937] jxcore: connect: success
,ok 79 Should be able to connect without error

ok 80 Port should be within range

,2016-01-19 23:11:10.311 ThaliTest[2390:5119329] jxcore: connect 1453241463217.202.IN5W+g==
2016-01-19 23:11:10.312 ThaliTest[2390:5119329] client: already connect(ing/ed) to 1453241463217.202.IN5W+g==
2016-01-19 23:11:10.312 ThaliTest[2390:5119329] jxcor,e: connect: fail: Aleady connecting
ok 81 Should fail on double connect

,2016-01-19 23:11:10.313 ThaliTest[2390:5119329] jxcore: disconnect
2016-01-19 23:11:10.313 ThaliTest[2390:5119329] client session: disconnectFromPeer: 1453241463217.202.IN5W+g==
2016-01-19 23:11:10.313 ThaliTest[2390:5119329] client session: disconnect
2016-01-19 23:11:10.313 ThaliTest[2390:5119329] client session: stateChange:2->0 1453241463217.202.IN5W+g==
,2016-01-19 23:11:10.316 ThaliTest[2390:5119329] jxcore: disconnect: success
ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-19 23:11:10.565 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:11:10.565 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:11:10.566 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:11:10.566 ThaliTest[2390:5119329] server session: disconnect
2016-01-19 23:11:10.566 ThaliTest[2390:5119329] server session: stateChange:2->0 1453241463217.202
,2016-01-19 23:11:10.567 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-19 23:11:11.626 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:11:11.627 ThaliTest[2390:5119329] server: starting 1453241471625.2390.rYOlgg==
2016-01-19 23:11:11.627 ThaliTest[2390:5119329] multipeer session: start timer: 0x1784f820
2016-01-19 23:11:11.627 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241471625.2390
2016-01-19 23:11:11.627 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-19 23:11:30.636 ThaliTest[2390:5118108] client: found peer: 1453241489281.202.T5NPaA==
,2016-01-19 23:11:30.636 ThaliTest[2390:5119329] jxcore: connect 1453241489281.202.T5NPaA==
2016-01-19 23:11:30.637 ThaliTest[2390:5119329] client session: connect
2016-01-19 23:11:30.637 ThaliTest[2390:5119329] client session: stateChange:0->1 1453241489281.202.T5NPaA==
,2016-01-19 23:11:30.703 ThaliTest[2390:5118108] multipeer session: reset timer
2016-01-19 23:11:30.703 ThaliTest[2390:5118108] multipeer session: stop timer
2016-01-19 23:11:30.703 ThaliTest[2390:5118108] multipeer session: start timer: 0x1784f820
2016-01-19 23:11:30.703 ThaliTest[2390:5118108] server session: connect
2016-01-19 23:11:30.703 ThaliTest[2390:5118108] server session: stateChange:0->1 1453241489281.202
,2016-01-19 23:11:30.705 ThaliTest[2390:5118108] server: accepting invitation 1453241489281.202
,2016-01-19 23:11:34.894 ThaliTest[2390:5120074] client session: connected
2016-01-19 23:11:34.894 ThaliTest[2390:5120074] client session: stateChange:1->2 1453241489281.202.T5NPaA==
,2016-01-19 23:11:34.934 ThaliTest[2390:5120067] client session: fireConnectCallback: 1453241489281.202.T5NPaA==
2016-01-19 23:11:34.934 ThaliTest[2390:5120067] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-01-19 23:11:34.935 ThaliTest[2390:5119329] jxcore: disconnect
,2016-01-19 23:11:34.935 ThaliTest[2390:5119329] client session: disconnectFromPeer: 1453241489281.202.T5NPaA==
2016-01-19 23:11:34.935 ThaliTest[2390:5119329] client session: disconnect
,2016-01-19 23:11:34.935 ThaliTest[2390:5119329] client session: stateChange:2->0 1453241489281.202.T5NPaA==
,2016-01-19 23:11:34.994 ThaliTest[2390:5119329] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

2016-01-19 23:11:34.995 ThaliTest[2390:5119329] jxcore: disconnect
2016-01-19 23:11:34.995 ThaliTest[2390:5119329] jxcore: disconnect: fail
,ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-19 23:11:35.082 ThaliTest[2390:5120074] server session: connected
,2016-01-19 23:11:35.082 ThaliTest[2390:5120074] server session: stateChange:1->2 1453241489281.202
,2016-01-19 23:11:35.088 ThaliTest[2390:5118108] server relay: socket disconnected
,2016-01-19 23:11:35.088 ThaliTest[2390:5118108] server relay: 0x177d9090 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 23:11:35.144 ThaliTest[2390:5120027] server session: not connected 1453241489281.202
,calling stopBroadcasting

2016-01-19 23:11:35.670 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:11:35.670 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:11:35.670 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:11:35.671 ThaliTest[2390:5119329] server session: disconnect
2016-01-19 23:11:35.671 ThaliTest[2390:5119329] server session: stateChange:2->0 1453241489281.202
,2016-01-19 23:11:35.671 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 55185

,2016-01-19 23:11:36.201 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:11:36.202 ThaliTest[2390:5119329] server: starting 1453241496201.2390.YDpGQg==
2016-01-19 23:11:36.202 ThaliTest[2390:5119329] multipeer session: start timer: 0x1754c4e0
2016-01-19 23:11:36.202 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241496201.2390
2016-01-19 23:11:36.202 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error

,2016-01-19 23:11:37.487 ThaliTest[2390:5118108] client: found peer: 1453241495894.202.ROPpZA==
,2016-01-19 23:11:37.488 ThaliTest[2390:5119329] jxcore: connect 1453241495894.202.ROPpZA==
2016-01-19 23:11:37.488 ThaliTest[2390:5119329] client session: connect
,2016-01-19 23:11:37.488 ThaliTest[2390:5119329] client session: stateChange:0->1 1453241495894.202.ROPpZA==
,2016-01-19 23:11:37.572 ThaliTest[2390:5118108] multipeer session: reset timer
2016-01-19 23:11:37.572 ThaliTest[2390:5118108] multipeer session: stop timer
2016-01-19 23:11:37.572 ThaliTest[2390:5118108] multipeer session: start timer: 0x1754c4e0
2016-01-19 23:11:37.572 ThaliTest[2390:5118108] server session: connect
2016-01-19 23:11:37.572 ThaliTest[2390:5118108] server session: stateChange:0->1 1453241495894.202
2016-01-19 23:11:37.574 ThaliTest[2390:5118108] server: accepting invitation 1453241495894.202
,2016-01-19 23:11:41.701 ThaliTest[2390:5120072] client session: connected
2016-01-19 23:11:41.701 ThaliTest[2390:5120072] client session: stateChange:1->2 1453241495894.202.ROPpZA==
,2016-01-19 23:11:41.707 ThaliTest[2390:5120090] client session: fireConnectCallback: 1453241495894.202.ROPpZA==
2016-01-19 23:11:41.708 ThaliTest[2390:5120090] jxcore: connect: success
ok 89 Should be able to connect without error

,ok 90 Port should be within range

,2016-01-19 23:11:41.710 ThaliTest[2390:5118108] client: relay established
2016-01-19 23:11:41.710 ThaliTest[2390:5118108] client: new accepted socket: 0x17700760
,data in 2190

,data in 4380

,data in 7665

,2016-01-19 23:11:41.800 ThaliTest[2390:5120072] server session: connected
2016-01-19 23:11:41.800 ThaliTest[2390:5120072] server session: stateChange:1->2 1453241495894.202
,data in 9855

,2016-01-19 23:11:41.817 ThaliTest[2390:5118108] server relay: connected (to port: 55185)
,data in 13140

,data in 17520

,data in 20805

,data in 30660

,data in 39420

,data in 45990

,data in 54750

,data in 55845

,data in 63510

,data in 67890

,data in 87944

,data in 114224

,data in 126269

,data in 131072

,ok 91 the test messages should be equal

2016-01-19 23:11:42.040 ThaliTest[2390:5119329] jxcore: disconnect
,2016-01-19 23:11:42.041 ThaliTest[2390:5119329] client session: disconnectFromPeer: 1453241495894.202.ROPpZA==
2016-01-19 23:11:42.041 ThaliTest[2390:5119329] client session: disconnect
,2016-01-19 23:11:42.041 ThaliTest[2390:5119329] client session: stateChange:2->0 1453241495894.202.ROPpZA==
,2016-01-19 23:11:42.046 ThaliTest[2390:5119329] jxcore: disconnect: success
,ok 92 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-19 23:11:42.102 ThaliTest[2390:5120067] server session: not connected 1453241495894.202
,calling stopBroadcasting

,2016-01-19 23:11:42.500 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:11:42.500 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:11:42.501 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:11:42.,501 ThaliTest[2390:5119329] server session: disconnect
2016-01-19 23:11:42.501 ThaliTest[2390:5119329] server session: stateChange:2->0 1453241495894.202
,2016-01-19 23:11:43.453 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 55191

2016-01-19 23:11:43.891 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:11:43.892 ThaliTest[2390:5119329] server: starting 1453241503891.2390.iIDXbw==
2016-01-19 23:11:43.893 ThaliTest[2390:5119329] multipeer session: start timer: 0x17a70010
2016-01-19 23:11:43.893 ThaliTest[2390:5119329] THEMultipeerSession initialized peer 1453241503891.2390
,2016-01-19 23:11:43.894 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error

,2016-01-19 23:11:44.827 ThaliTest[2390:5118108] client: found peer: 1453241503244.202.A/iYNg==
[{"peerIdentifier":"1453241503244.202.A/iYNg==","peerName":"(null)","peerAvailable":true}]

2016-01-19 23:11:44.828 ThaliTest[2390:5119329] jxcore: connect 1453241503244.202.A/iYNg==
2016-01-19 23:11:44.828 ThaliTest[2390:5119329] client session: connect
2016-01-19 23:11:44.828 ThaliTest[2390:5119329] client session: stateChange:0->1 1453241503244.202.A/iYNg==
,2016-01-19 23:11:45.367 ThaliTest[2390:5118108] multipeer session: reset timer
2016-01-19 23:11:45.367 ThaliTest[2390:5118108] multipeer session: stop timer
2016-01-19 23:11:45.367 ThaliTest[2390:5118108] multipeer session: start timer: 0x17a70010
2016-01-19 23:11:45.367 ThaliTest[2390:5118108] server session: connect
2016-01-19 23:11:45.368 ThaliTest[2390:5118108] server session: stateChange:0->1 1453241503244.202
2016-01-19 23:11:45.369 ThaliTest[2390:5118108] server: accepting invitation 1453241503244.202
,2016-01-19 23:11:49.375 ThaliTest[2390:5120067] server session: connected
2016-01-19 23:11:49.375 ThaliTest[2390:5120067] server session: stateChange:1->2 1453241503244.202
,2016-01-19 23:11:49.428 ThaliTest[2390:5118108] server relay: connected (to port: 55191)
,2016-01-19 23:11:49.434 ThaliTest[2390:5120091] client session: connected
2016-01-19 23:11:49.434 ThaliTest[2390:5120091] client session: stateChange:1->2 1453241503244.202.A/iYNg==
,2016-01-19 23:11:49.493 ThaliTest[2390:5120067] client session: fireConnectCallback: 1453241503244.202.A/iYNg==
2016-01-19 23:11:49.493 ThaliTest[2390:5120067] jxcore: connect: success
,ok 94 Should be able to connect without error

ok 95 Port should be within range

ok 96 First connect should succeed

,2016-01-19 23:11:49.503 ThaliTest[2390:5118108] client: relay established
2016-01-19 23:11:49.503 ThaliTest[2390:5118108] client: new accepted socket: 0x179bd5b0
,2016-01-19 23:11:49.564 ThaliTest[2390:5120091] server session: not connected 1453241503244.202
,ok 97 the test messages should be equal

ok 98 First send should succeed

,2016-01-19 23:11:49.644 ThaliTest[2390:5118108] client: socket closed
2016-01-19 23:11:49.645 ThaliTest[2390:5118108] client relay: socket disconnected
,2016-01-19 23:11:49.645 ThaliTest[2390:5118108] client relay: 0x179bd5b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-19 23:11:49.645 ThaliTest[2390:5118108] client session: socket closed: 1453241503244.202.A/iYNg==
2016-01-19 23:11:49.645 ThaliTest[2390:5118108] client session: onLinkFailure: 1453241503244.202.A/iYNg==
2016-01-19 23:11:49.645 ThaliTest[2390:5118108] client session: disconnect
2016-01-19 23:11:49.645 ThaliTest[2390:5118108] client session: stateChange:2->0 1453241503244.202.A/iYNg==
,2016-01-19 23:11:49.703 ThaliTest[2390:5118108] client session: fireConnectionErrorEvent: 1453241503244.202.A/iYNg==
,2016-01-19 23:11:49.704 ThaliTest[2390:5119329] jxcore: connect 1453241503244.202.A/iYNg==
2016-01-19 23:11:49.704 ThaliTest[2390:5119329] client session: connect
2016-01-19 23:11:49.704 ThaliTest[2390:5119329] client session: stateChange:0->1 1453241503,244.202.A/iYNg==
2016-01-19 23:11:49.704 ThaliTest[2390:5118108] multipeer session: reset timer
2016-01-19 23:11:49.704 ThaliTest[2390:5118108] multipeer session: stop timer
,2016-01-19 23:11:49.704 ThaliTest[2390:5118108] multipeer session: start timer: 0x17a70010
2016-01-19 23:11:49.705 ThaliTest[2390:5118108] server: disconnecting to refresh session (1453241503244.202)
2016-01-19 23:11:49.705 ThaliTest[2390:5118108] server, session: disconnect
2016-01-19 23:11:49.705 ThaliTest[2390:5118108] server session: stateChange:2->0 1453241503244.202
,2016-01-19 23:11:49.706 ThaliTest[2390:5118108] server session: connect
2016-01-19 23:11:49.706 ThaliTest[2390:5118108] server session: stateChange:0->1 1453241503244.202
,2016-01-19 23:11:49.708 ThaliTest[2390:5118108] server: accepting invitation 1453241503244.202
,2016-01-19 23:11:53.893 ThaliTest[2390:5120090] client session: connected
2016-01-19 23:11:53.893 ThaliTest[2390:5120090] client session: stateChange:1->2 1453241503244.202.A/iYNg==
,2016-01-19 23:11:53.951 ThaliTest[2390:5120067] client session: fireConnectCallback: 1453241503244.202.A/iYNg==
2016-01-19 23:11:53.952 ThaliTest[2390:5120067] jxcore: connect: success
,ok 99 Should be able to connect without error

ok 100 Port should be within range

ok 101 Second connect should succeed

,2016-01-19 23:11:53.961 ThaliTest[2390:5118108] client: relay established
2016-01-19 23:11:53.962 ThaliTest[2390:5118108] client: new accepted socket: 0x17700650
,2016-01-19 23:11:54.022 ThaliTest[2390:5120067] server session: connected
2016-01-19 23:11:54.023 ThaliTest[2390:5120067] server session: stateChange:1->2 1453241503244.202
,ok 102 the test messages should be equal

,ok 103 Second send should succeed

,# setup

,2016-01-19 23:11:54.051 ThaliTest[2390:5118108] client: socket closed
2016-01-19 23:11:54.051 ThaliTest[2390:5118108] client relay: socket disconnected
2016-01-19 23:11:54.051 ThaliTest[2390:5118108] client relay: 0x17700650 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 23:11:54.051 ThaliTest[2390:5118108] client session: socket closed: 1453241503244.202.A/iYNg==
2016-01-19 2,3:11:54.051 ThaliTest[2390:5118108] client session: onLinkFailure: 1453241503244.202.A/iYNg==
2016-01-19 23:11:54.051 ThaliTest[2390:5118108] client session: disconnect
2016-01-19 23:11:54.051 ThaliTest[2390:5118108] client session: stateChange:2->0 1453,241503244.202.A/iYNg==
,2016-01-19 23:11:54.054 ThaliTest[2390:5118108] client session: fireConnectionErrorEvent: 1453241503244.202.A/iYNg==
,2016-01-19 23:11:54.078 ThaliTest[2390:5118108] server relay: connected (to port: 55191)
,2016-01-19 23:11:54.209 ThaliTest[2390:5120067] server session: not connected 1453241503244.202
,calling stopBroadcasting

2016-01-19 23:11:54.556 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:11:54.556 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:11:54.556 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:11:54.556 ThaliTest[2390:5119329] server session: disconnect
2016-01-19 23:11:54.556 ThaliTest[2390:5119329] server session: stateChange:2->0 1453241503244.202
,2016-01-19 23:11:54.560 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B2759DC7-9C43-4BE9-AE47-A530560819AC/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 104 starting event should occur in right order

,2016-01-19 23:11:54.714 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:11:54.716 ThaliTest[2390:5119329] server: starting tEvNKtmcCdPiswO4AZQjcw.mYcXGQ==
2016-01-19 23:11:54.716 ThaliTest[2390:5119329] multipeer session: start timer: 0x17d32860
2016-01-19 23:11:54.716 ThaliTest[2390:5119329] THEMultipeerSession initialized peer tEvNKtmcCdPiswO4AZQjcw
,2016-01-19 23:11:54.718 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 105 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 106 stopping event should occur in right order

About to call stopBroadcasting

2016-01-19 23:11:54.719 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:11:54.719 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
2016-01-19 23:11:54.719 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:11:54.719 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 107 stopped event should occur in right order

mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B2759DC7-9C43-4BE9-AE47-A530560819AC/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 23:11:55.086 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:11:55.087 ThaliTest[2390:5119329] server: starting tEvNKtmcCdPiswO4AZQjcw.IzI5Ig==
2016-01-19 23:11:55.088 ThaliTest[2390:5119329] multipeer session: start timer: 0x17c86330
2016-01-19 23:11:55.088 ThaliTest[2390:5119329] THEMultipeerSession initialized peer tEvNKtmcCdPiswO4AZQjcw
,2016-01-19 23:11:55.088 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error

ok 109 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-19 23:11:55.089 ThaliTest[2390:5119329] jxcore: stopBroadcasting
2016-01-19 23:11:55.089 ThaliTest[2390:5119329] THEMultipeerSession stopping peer
,2016-01-19 23:11:55.089 ThaliTest[2390:5119329] multipeer session: stop timer
2016-01-19 23:11:55.089 ThaliTest[2390:5119329] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B2759DC7-9C43-4BE9-AE47-A530560819AC/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 23:11:57.503 ThaliTest[2390:5119329] jxcore: startBroadcasting
,2016-01-19 23:11:57.505 ThaliTest[2390:5119329] server: starting tEvNKtmcCdPiswO4AZQjcw.wcui9A==
2016-01-19 23:11:57.505 ThaliTest[2390:5119329] multipeer session: start timer: 0x17a71760
2016-01-19 23:11:57.505 ThaliTest[2390:5119329] THEMultipeerSessio,n initialized peer tEvNKtmcCdPiswO4AZQjcw
2016-01-19 23:11:57.505 ThaliTest[2390:5119329] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error

ok 111 deviceName should not be null

,2016-01-19 23:11:59.911 ThaliTest[2390:5118108] client: found peer: 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
,2016-01-19 23:12:01.529 ThaliTest[2390:5119329] jxcore: connect 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
2016-01-19 23:12:01.529 ThaliTest[2390:5119329] client session: connect
2016-01-19 23:12:01.530 ThaliTest[2390:5119329] client session: stateChange:0->1 4puYn,3EKNDEaiqA4XO46jQ.en4jxg==
,ok 112 Should be able to put doc without error

,ok 113 1st change of local doc should contain local id

,2016-01-19 23:12:02.601 ThaliTest[2390:5118108] multipeer session: reset timer
2016-01-19 23:12:02.601 ThaliTest[2390:5118108] multipeer session: stop timer
2016-01-19 23:12:02.601 ThaliTest[2390:5118108] multipeer session: start timer: 0x17a71760
2016-01-19 23:12:02.601 ThaliTest[2390:5118108] server session: connect
,2016-01-19 23:12:02.601 ThaliTest[2390:5118108] server session: stateChange:0->1 4puYn3EKNDEaiqA4XO46jQ
,2016-01-19 23:12:02.604 ThaliTest[2390:5118108] server: accepting invitation 4puYn3EKNDEaiqA4XO46jQ
,2016-01-19 23:12:06.863 ThaliTest[2390:5120067] client session: connected
2016-01-19 23:12:06.863 ThaliTest[2390:5120067] client session: stateChange:1->2 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
,2016-01-19 23:12:06.868 ThaliTest[2390:5120072] server session: connected
2016-01-19 23:12:06.868 ThaliTest[2390:5120072] server session: stateChange:1->2 4puYn3EKNDEaiqA4XO46jQ
,2016-01-19 23:12:06.924 ThaliTest[2390:5120090] client session: fireConnectCallback: 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
2016-01-19 23:12:06.924 ThaliTest[2390:5120090] jxcore: connect: success
,2016-01-19 23:12:06.928 ThaliTest[2390:5118108] client: relay established
2016-01-19 23:12:06.928 ThaliTest[2390:5118108] client: new accepted socket: 0x174efe60
,2016-01-19 23:12:06.930 ThaliTest[2390:5118108] server relay: connected (to port: 55206)
,server bridge: new client socket

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

,2016-01-19 23:12:16.187 ThaliTest[2390:5118108] ERROR: Writing to output stream
2016-01-19 23:12:16.187 ThaliTest[2390:5118108] Exception writing to outputstream: Error writing to outputstream
,2016-01-19 23:12:16.192 ThaliTest[2390:5120072] server session: not connected 4puYn3EKNDEaiqA4XO46jQ
,2016-01-19 23:12:16.197 ThaliTest[2390:5120027] client session: not connected 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
2016-01-19 23:12:16.197 ThaliTest[2390:5120027] client session: onLinkFailure: 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
2016-01-19 23:12:16.197 ThaliTest[2390:5120027] client session: disconnect
2016-01-19 23:12:16.197 ThaliTest[2390:5120027] client session: stateChange:2->0 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
,2016-01-19 23:12:16.199 ThaliTest[2390:5120027] client session: fireConnectionErrorEvent: 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
,server bridge: socket closed

,2016-01-19 23:12:16.204 ThaliTest[2390:5119329] jxcore: disconnect
,2016-01-19 23:12:16.204 ThaliTest[2390:5119329] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

,2016-01-19 23:12:16.205 ThaliTest[2390:5119329] jxcore: connect 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
,2016-01-19 23:12:16.205 ThaliTest[2390:5119329] client session: connect
2016-01-19 23:12:16.205 ThaliTest[2390:5119329] client session: stateChange:0->1 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
,client bridge: socket closed

,2016-01-19 23:12:17.330 ThaliTest[2390:5118108] client: lost peer: 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
2016-01-19 23:12:17.330 ThaliTest[2390:5118108] client session: onPeerLost: 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
2016-01-19 23:12:17.330 ThaliTest[2390:5118108], client session: onLinkFailure: 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
2016-01-19 23:12:17.330 ThaliTest[2390:5118108] client session: disconnect
2016-01-19 23:12:17.330 ThaliTest[2390:5118108] client session: stateChange:1->0 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
2016-01-19 23:12:17.330 ThaliTest[2390:5118108] client session: fireConnectCallback: 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
2016-01-19 23:12:17.330 ThaliTest[2390:5118108] jxcore: connect: fail: Peer disconnected
Connect error with error: Error: Peer disconnecte,d

,2016-01-19 23:12:17.344 ThaliTest[2390:5119329] jxcore: disconnect
2016-01-19 23:12:17.344 ThaliTest[2390:5119329] jxcore: disconnect: fail
Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 4puYn3EKNDEaiqA4XO46jQ.en4jxg==

,client bridge: socket closed

,Possibly unhandled Error. ETIMEDOUT
onError@/private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:66:18
ajax/<@/private/var/mobile/Containers/Bundle/Applicati,on/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:108:1
Request.prototype.init/self.callback@/private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/node_modules/pouchdb/node_modules/request/request.js:123:7
emit@events.js:82:1
Request.prototype.start/self.timeoutTimer<@/private/var/mobile/Containers/Bundle/Application/86BB23D9-10CD-45B7-990F-50FC8FC80EF0/ThaliTest.app/www/jxcore/node_modules/pouc,hdb/node_modules/request/request.js:590:7
$9@timers.js:120:1


client bridge: socket closed

,client bridge: socket closed

,2016-01-19 23:12:32.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:13:02.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:13:32.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:14:02.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:14:32.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:15:02.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:15:32.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:16:02.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:16:32.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:17:02.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:17:32.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:18:02.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:18:32.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:19:02.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:19:32.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:20:02.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:20:32.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:21:02.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:21:32.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:22:02.602 ThaliTest[2390:5118108] multipeer session: restart
,2016-01-19 23:22:32.602 ThaliTest[2390:5118108] multipeer session: restart

```
