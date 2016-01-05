#### Test 549702610263d9b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702610263d9b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F67CAEA9-4BD0-4404-B757-2AD996B4CD69/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F67CAEA9-4BD0-4404-B757-2AD996B4CD69/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702610263d9b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702610263d9b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/38823D28-3F0C-4422-90F8-8AF51FFCE5C9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65311"
,(lldb)     command script import "/tmp/F67CAEA9-4BD0-4404-B757-2AD996B4CD69/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 18:31:14.081 ThaliTest[1336:2832172] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F7361BEC-A0AB-4021-B4D4-D8745DBD38C5/Library/Cookies/Cookies.binarycookies
,2016-01-05 18:31:14.460 ThaliTest[1336:2832172] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 18:31:14.462 ThaliTest[1336:2832172] Multi-tasking -> Device: YES, App: YES
,2016-01-05 18:31:14.472 ThaliTest[1336:2832172] Unlimited access to network resources
,2016-01-05 18:31:14.487 ThaliTest[1336:2832172] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 18:31:23.641 ThaliTest[1336:2832172] Resetting plugins due to page load.
,2016-01-05 18:31:27.154 ThaliTest[1336:2832172] Finished load of: file:///var/mobile/Containers/Bundle/Application/38823D28-3F0C-4422-90F8-8AF51FFCE5C9/ThaliTest.app/www/index.html
,2016-01-05 18:31:27.344 ThaliTest[1336:2832172] JXcore Cordova plugin initializing
2016-01-05 18:31:27.345 ThaliTest[1336:2832374] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
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
,ok 17 should be equal
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
,ok 27 should be equal
,ok 28 should be equal
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
,ok 30 should be equal
,ok 31 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,ok 32 should be equal
,ok 33 should be equal
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
,ok 40 should be equal
,# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
,ok 42 should be equal
,# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
,ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-05 18:36:43.311 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:43.327 ThaliTest[1336:2832374] server: starting 1452015403311.1336.OU28Cg==
,2016-01-05 18:36:43.328 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a979cd0
,2016-01-05 18:36:43.330 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015403311.1336
2016-01-05 18:36:43.331 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.338 ThaliTest[1336:2832374] jxcore: stopBroadcasting
2016-01-05 18:36:43.343 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
2016-01-05 18:36:43.343 ThaliTest[1336:2832374] multipeer session: stop timer
2016-01-05 18:36:43.,344 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-05 18:36:43.347 ThaliTest[1336:2832374] jxcore: startBroadcasting
2016-01-05 18:36:43.351 ThaliTest[1336:2832374] server: s,tarting 1452015403347.1336.w2pirw==
,2016-01-05 18:36:43.354 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a849850
2016-01-05 18:36:43.355 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015403347.1336
2016-01-05 18:36:43.356 ThaliTest[1336:2832374] jxcore: sta,rtBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-05 18:36:43.361 ThaliTest[1336:2832374] jxcore: stopBroadcasting
,2016-01-05 18:36:43.362 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.362 ThaliTest[1336:2832374] multipeer session: stop timer
2016-01-05 18:36:43.364 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-05 18:36:43.366 ThaliTest,[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:43.375 ThaliTest[1336:2832374] server: starting 1452015403366.1336.htkErw==
,2016-01-05 18:36:43.389 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a97e340
,2016-01-05 18:36:43.391 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015403366.1336
,2016-01-05 18:36:43.394 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.399 ThaliTest[1336:2832374] jxcore: stopBroadcasting
,2016-01-05 18:36:43.400 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.401 ThaliTest[1336:2832374] multipeer session: stop timer
,2016-01-05 18:36:43.402 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.411 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:43.414 ThaliTest[1336:2832374] server: starting 1452015403410.1336.0shcVw==
,2016-01-05 18:36:43.416 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a848a50
,2016-01-05 18:36:43.422 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015403410.1336
,2016-01-05 18:36:43.423 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.425 ThaliTest[1336:2832374] jxcore: stopBroadcasting
,2016-01-05 18:36:43.426 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.427 ThaliTest[1336:2832374] multipeer session: stop timer
,2016-01-05 18:36:43.428 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.434 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:43.436 ThaliTest[1336:2832374] server: starting 1452015403433.1336.9oUsVw==
,2016-01-05 18:36:43.441 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a97e750
,2016-01-05 18:36:43.443 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015403433.1336
,2016-01-05 18:36:43.445 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.448 ThaliTest[1336:2832374] jxcore: stopBroadcasting
,2016-01-05 18:36:43.448 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.449 ThaliTest[1336:2832374] multipeer session: stop timer
,2016-01-05 18:36:43.450 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.456 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:43.459 ThaliTest[1336:2832374] server: starting 1452015403456.1336.EZbkgQ==
,2016-01-05 18:36:43.462 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a8474b0
,2016-01-05 18:36:43.466 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015403456.1336
,2016-01-05 18:36:43.467 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.470 ThaliTest[1336:2832374] jxcore: stopBroadcasting
,2016-01-05 18:36:43.471 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.472 ThaliTest[1336:2832374] multipeer session: stop timer
,2016-01-05 18:36:43.473 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.478 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:43.481 ThaliTest[1336:2832374] server: starting 1452015403478.1336.HttiCQ==
,2016-01-05 18:36:43.484 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a846e20
,2016-01-05 18:36:43.489 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015403478.1336
,2016-01-05 18:36:43.490 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.493 ThaliTest[1336:2832374] jxcore: stopBroadcasting
,2016-01-05 18:36:43.494 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.494 ThaliTest[1336:2832374] multipeer session: stop timer
,2016-01-05 18:36:43.496 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.501 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:43.504 ThaliTest[1336:2832374] server: starting 1452015403501.1336.sxA8cQ==
,2016-01-05 18:36:43.506 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a97fdc0
,2016-01-05 18:36:43.508 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015403501.1336
,2016-01-05 18:36:43.510 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.515 ThaliTest[1336:2832374] jxcore: stopBroadcasting
,2016-01-05 18:36:43.515 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.516 ThaliTest[1336:2832374] multipeer session: stop timer
,2016-01-05 18:36:43.517 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.521 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:43.523 ThaliTest[1336:2832374] server: starting 1452015403521.1336./51e7w==
,2016-01-05 18:36:43.524 ThaliTest[1336:2832374] multipeer session: start timer: 0x176d90a0
,2016-01-05 18:36:43.527 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015403521.1336
,2016-01-05 18:36:43.527 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.531 ThaliTest[1336:2832374] jxcore: stopBroadcasting
,2016-01-05 18:36:43.531 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.532 ThaliTest[1336:2832374] multipeer session: stop timer
,2016-01-05 18:36:43.533 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.537 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:43.539 ThaliTest[1336:2832374] server: starting 1452015403537.1336.gmixLQ==
,2016-01-05 18:36:43.540 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a844f60
,2016-01-05 18:36:43.543 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015403537.1336
,2016-01-05 18:36:43.545 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.547 ThaliTest[1336:2832374] jxcore: stopBroadcasting
,2016-01-05 18:36:43.548 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.548 ThaliTest[1336:2832374] multipeer session: stop timer
,2016-01-05 18:36:43.549 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-05 18:36:44.147 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:44.149 ThaliTest[1336:2832374] server: starting 1452015404146.1336.eIqXoA==
2016-01-05 18:36:44.150 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a9837b0
2016-01-05 18:36:44.150 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015404146.1336
2016-01-05 18:36:44.150 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
,2016-01-05 18:36:44.153 ThaliTest[1336:2832374] jxcore: startBroadcasting
2016-01-05 18:36:44.153 ThaliTest[1336:2832374] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-05 18:36:44.155 ThaliTest[1336:2832374] jxcore,: stopBroadcasting
2016-01-05 18:36:44.155 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
2016-01-05 18:36:44.155 ThaliTest[1336:2832374] multipeer session: stop timer
2016-01-05 18:36:44.156 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-05 18:36:45.199 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:45.203 ThaliTest[1336:2832374] server: starting 1452015405199.1336.sUQT4Q==
2016-01-05 18:36:45.203 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a987650
2016-01-05 18:36:45.204 ThaliTest[1336:2832374] THEMultipeerSession in,itialized peer 1452015405199.1336
2016-01-05 18:36:45.204 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-05 18:36:45.206 ThaliTest[1336:2832374] jxcore: connect foobar
201,6-01-05 18:36:45.208 ThaliTest[1336:2832374] client: unknown peer foobar
2016-01-05 18:36:45.208 ThaliTest[1336:2832374] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2016-01-05 18:36:45.211 ThaliTest[1336:2832374] jxcore: stopBroadcasting
2016-01-05 18:36:45.212 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
2016-01-05 18:36:45.212 ThaliTest[1336:2832374] multipeer s,ession: stop timer
2016-01-05 18:36:45.212 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-05 18:36:45.727 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:45.730 ThaliTest[1336:2832374] server: starting 1452015405726.1336.CYqmow==
2016-01-05 18:36:45.731 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a98a150
2016-01-05 18:36:45.732 ThaliTest[1336:2832374] THEMultipeerSession in,itialized peer 1452015405726.1336
2016-01-05 18:36:45.732 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-05 18:36:45.734 ThaliTest[1336:2832374] jxcore: disconnect
2016-01,-05 18:36:45.735 ThaliTest[1336:2832374] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-05 18:36:45.737 ThaliTest[1336:2832374] jxcore: stopBroadcasting
2016-01-05 18:36:45.738 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:36:45.738 ThaliTest[1336:2832374] multipeer session: stop timer
,2016-01-05 18:36:45.739 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-05 18:36:46.369 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:46.372 ThaliTest[1336:2832374] server: starting 1452015406368.1336.86tKTw==
2016-01-05 18:36:46.373 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a98cd10
2016-01-05 18:36:46.374 ThaliTest[1336:2832374] THEMultipeerSession in,itialized peer 1452015406368.1336
2016-01-05 18:36:46.374 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-05 18:36:48.162 ThaliTest[1336:2832172] client: found peer: 1452015406387.1319.AajjwA==
,2016-01-05 18:36:48.166 ThaliTest[1336:2832374] jxcore: connect 1452015406387.1319.AajjwA==
2016-01-05 18:36:48.166 ThaliTest[1336:2832374] client session: connect
2016-01-05 18:36:48.167 ThaliTest[1336:2832374] client session: stateChange:0->1 145201540,6387.1319.AajjwA==
,2016-01-05 18:36:49.569 ThaliTest[1336:2832172] multipeer session: reset timer
2016-01-05 18:36:49.570 ThaliTest[1336:2832172] multipeer session: stop timer
2016-01-05 18:36:49.570 ThaliTest[1336:2832172] multipeer session: start timer: 0x1a98cd10
2016-01-05 18:36:49.571 ThaliTest[1336:2832172] server session: connect
2016-01-05 18:36:49.571 ThaliTest[1336:2832172] server session: stateChange:0->1 1452015406387.1319
2016-01-05 18:36:49.584 ThaliTest[1336:2832172] server: accepting invitation 1452015406387.1319
,2016-01-05 18:36:52.036 ThaliTest[1336:2832879] client session: connected
2016-01-05 18:36:52.036 ThaliTest[1336:2832879] client session: stateChange:1->2 1452015406387.1319.AajjwA==
,2016-01-05 18:36:52.067 ThaliTest[1336:2832891] client session: fireConnectCallback: 1452015406387.1319.AajjwA==
2016-01-05 18:36:52.068 ThaliTest[1336:2832891] jxcore: connect: success
ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-05 18:36:52.073 ThaliTest[1336:2832374] jxcore: disconnect
2016-01-05 18:36:52.073 ThaliTest[1336:2832374] client session: disconnectFromPeer: 1452015406387.1319.AajjwA==
2016-01-05 18:36:52.073 ThaliTest[1336:2832374] client session: disconnect,
2016-01-05 18:36:52.074 ThaliTest[1336:2832374] client session: stateChange:2->0 1452015406387.1319.AajjwA==
,2016-01-05 18:36:52.086 ThaliTest[1336:2832374] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-05 18:36:52.171 ThaliTest[1336:2832879] server session: connected
,2016-01-05 18:36:52.171 ThaliTest[1336:2832879] server session: stateChange:1->2 1452015406387.1319
,2016-01-05 18:36:52.198 ThaliTest[1336:2832172] server relay: socket disconnected
,2016-01-05 18:36:52.199 ThaliTest[1336:2832172] server relay: 0x1a83a730 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 18:36:52.246 ThaliTest[1336:2832891] server session: not connected 1452015406387.1319
,calling stopBroadcasting
,2016-01-05 18:36:52.662 ThaliTest[1336:2832374] jxcore: stopBroadcasting
2016-01-05 18:36:52.663 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
2016-01-05 18:36:52.663 ThaliTest[1336:2832374] multipeer session: stop timer
2016-01-05 18:36:52.,663 ThaliTest[1336:2832374] server session: disconnect
2016-01-05 18:36:52.664 ThaliTest[1336:2832374] server session: stateChange:2->0 1452015406387.1319
2016-01-05 18:36:52.665 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-05 18:36:54.040 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:54.043 ThaliTest[1336:2832374] server: starting 1452015414039.1336.n2tyeg==
2016-01-05 18:36:54.044 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a994cf0
2016-01-05 18:36:54.044 ThaliTest[1336:2832374] THEMultipeerSession initialized peer 1452015414039.1336
2016-01-05 18:36:54.045 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-05 18:36:55.002 ThaliTest[1336:2832172] client: found peer: 1452015414092.1319.6etPIw==
,2016-01-05 18:36:55.004 ThaliTest[1336:2832374] jxcore: connect 1452015414092.1319.6etPIw==
2016-01-05 18:36:55.005 ThaliTest[1336:2832374] client session: connect
2016-01-05 18:36:55.005 ThaliTest[1336:2832374] client session: stateChange:0->1 145201541,4092.1319.6etPIw==
,2016-01-05 18:36:55.508 ThaliTest[1336:2832172] multipeer session: reset timer
2016-01-05 18:36:55.509 ThaliTest[1336:2832172] multipeer session: stop timer
,2016-01-05 18:36:55.509 ThaliTest[1336:2832172] multipeer session: start timer: 0x1a994cf0
2016-01-05 18:36:55.511 ThaliTest[1336:2832172] server session: connect
2016-01-05 18:36:55.511 ThaliTest[1336:2832172] server session: stateChange:0->1 1452015414092.1319
,2016-01-05 18:36:55.520 ThaliTest[1336:2832172] server: accepting invitation 1452015414092.1319
,2016-01-05 18:36:58.006 ThaliTest[1336:2832879] server session: connected
2016-01-05 18:36:58.007 ThaliTest[1336:2832879] server session: stateChange:1->2 1452015414092.1319
,2016-01-05 18:36:58.137 ThaliTest[1336:2832172] server relay: socket disconnected
2016-01-05 18:36:58.138 ThaliTest[1336:2832172] server relay: 0x1a98fc60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 18:36:58.169 ThaliTest[1336:2832881] client session: connected
2016-01-05 18:36:58.169 ThaliTest[1336:2832881] client session: stateChange:1->2 1452015414092.1319.6etPIw==
2016-01-05 18:36:58.170 ThaliTest[1336:2832879] server session: not connected 1452015414092.1319
,2016-01-05 18:36:58.263 ThaliTest[1336:2832881] client session: fireConnectCallback: 1452015414092.1319.6etPIw==
2016-01-05 18:36:58.264 ThaliTest[1336:2832881] jxcore: connect: success
ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-05 18:36:58.269 ThaliTest[1336:2832374] jxcore: connect 1452015414092.1319.6etPIw==
2016-01-05 18:36:58.269 ThaliTest[1336:2832374] client: already connect(ing/ed) to 1452015414092.1319.6etPIw==
2016-01-05 18:36:58.270 ThaliTest[1336:2832374] jxc,ore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2016-01-05 18:36:58.273 ThaliTest[1336:2832374] jxcore: disconnect
2016-01-05 18:36:58.273 ThaliTest[1336:2832374] client session: disconnectFromPeer: 1452015414092.1319.6etPIw==
2016-01-05 18:36:58.274 ThaliTest[1336:2832374] client session: disconnect
2016-01-05 18:36:58.274 ThaliTest[1336:2832374] client session: stateChange:2->0 1452015414092.1319.6etPIw==
,2016-01-05 18:36:58.288 ThaliTest[1336:2832374] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-05 18:36:58.504 ThaliTest[1336:2832374] jxcore: stopBroadcasting
2016-01-05 18:36:58.505 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
2016-01-05 18:36:58.505 ThaliTest[1336:2832374] multipeer session: stop timer
2016-01-05 18:36:58.506 ThaliTest[1336:2832374] server session: disconnect
2016-01-05 18:36:58.506 ThaliTest[1336:2832374] server session: stateChange:2->0 1452015414092.1319
2016-01-05 18:36:58.507 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-05 18:36:58.905 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:36:58.909 ThaliTest[1336:2832374] server: starting 1452015418905.1336.xGPM4g==
2016-01-05 18:36:58.910 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a99f720
2016-01-05 18:36:58.910 ThaliTest[1336:2832374] THEMultipeerSession in,itialized peer 1452015418905.1336
2016-01-05 18:36:58.911 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-05 18:36:59.659 ThaliTest[1336:2832172] client: found peer: 1452015414092.1319.6etPIw==
2016-01-05 18:36:59.661 ThaliTest[1336:2832374] jxcore: connect 1452015414092.1319.6etPIw==
2016-01-05 18:36:59.661 ThaliTest[1336:2832374] client session: co,nnect
2016-01-05 18:36:59.662 ThaliTest[1336:2832374] client session: stateChange:0->1 1452015414092.1319.6etPIw==
,2016-01-05 18:37:00.086 ThaliTest[1336:2832172] client: found peer: 1452015418916.1319.obKNlg==
2016-01-05 18:37:00.088 ThaliTest[1336:2832374] jxcore: connect 1452015418916.1319.obKNlg==
2016-01-05 18:37:00.088 ThaliTest[1336:2832374] client session: co,nnect
2016-01-05 18:37:00.089 ThaliTest[1336:2832374] client session: stateChange:0->1 1452015418916.1319.obKNlg==
,2016-01-05 18:37:00.205 ThaliTest[1336:2832172] multipeer session: reset timer
2016-01-05 18:37:00.205 ThaliTest[1336:2832172] multipeer session: stop timer
2016-01-05 18:37:00.205 ThaliTest[1336:2832172] multipeer session: start timer: 0x1a99f720
2016-,01-05 18:37:00.206 ThaliTest[1336:2832172] server session: connect
2016-01-05 18:37:00.206 ThaliTest[1336:2832172] server session: stateChange:0->1 1452015418916.1319
,2016-01-05 18:37:00.217 ThaliTest[1336:2832172] server: accepting invitation 1452015418916.1319
,2016-01-05 18:37:01.782 ThaliTest[1336:2832172] client: lost peer: 1452015414092.1319.6etPIw==
2016-01-05 18:37:01.783 ThaliTest[1336:2832172] client session: onPeerLost: 1452015414092.1319.6etPIw==
2016-01-05 18:37:01.783 ThaliTest[1336:2832172] client ,session: onLinkFailure: 1452015414092.1319.6etPIw==
2016-01-05 18:37:01.783 ThaliTest[1336:2832172] client session: disconnect
2016-01-05 18:37:01.784 ThaliTest[1336:2832172] client session: stateChange:1->0 1452015414092.1319.6etPIw==
2016-01-05 18:37:,01.784 ThaliTest[1336:2832172] client session: fireConnectCallback: 1452015414092.1319.6etPIw==
2016-01-05 18:37:01.784 ThaliTest[1336:2832172] jxcore: connect: fail: Peer disconnected
,2016-01-05 18:37:02.659 ThaliTest[1336:2832879] server session: connected
,2016-01-05 18:37:02.660 ThaliTest[1336:2832879] server session: stateChange:1->2 1452015418916.1319
,2016-01-05 18:37:02.670 ThaliTest[1336:2832879] client session: connected
,2016-01-05 18:37:02.672 ThaliTest[1336:2832879] client session: stateChange:1->2 1452015418916.1319.obKNlg==
,2016-01-05 18:37:02.688 ThaliTest[1336:2832172] server relay: socket disconnected
,2016-01-05 18:37:02.689 ThaliTest[1336:2832172] server relay: 0x1a9988d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 18:37:02.717 ThaliTest[1336:2832891] client session: fireConnectCallback: 1452015418916.1319.obKNlg==
,2016-01-05 18:37:02.718 ThaliTest[1336:2832891] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-05 18:37:02.723 ThaliTest[1336:2832374] jxcore: disconnect
2016-01-05 18:37:02.724 ThaliTest[1336:2832374] client session: disconnectFromPeer: 1452015418916.1319.obKNlg==
2016-01-05 18:37:02.724 ThaliTest[1336:2832374] client session: disconnect
,2016-01-05 18:37:02.724 ThaliTest[1336:2832374] client session: stateChange:2->0 1452015418916.1319.obKNlg==
,2016-01-05 18:37:02.741 ThaliTest[1336:2832374] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2016-01-05 18:37:02.745 ThaliTest[1336:2832374] jxcore: disconnect
,2016-01-05 18:37:02.747 ThaliTest[1336:2832374] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-05 18:37:02.763 ThaliTest[1336:2832891] server session: not connected 1452015418916.1319
,calling stopBroadcasting
,2016-01-05 18:37:03.158 ThaliTest[1336:2832374] jxcore: stopBroadcasting
2016-01-05 18:37:03.159 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
2016-01-05 18:37:03.159 ThaliTest[1336:2832374] multipeer session: stop timer
2016-01-05 18:37:03.,160 ThaliTest[1336:2832374] server session: disconnect
2016-01-05 18:37:03.160 ThaliTest[1336:2832374] server session: stateChange:2->0 1452015418916.1319
2016-01-05 18:37:03.161 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-05 18:37:04.189 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:37:04.193 ThaliTest[1336:2832374] server: starting 1452015424189.1336.YigYPw==
2016-01-05 18:37:04.194 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a828550
2016-01-05 18:37:04.195 ThaliTest[1336:2832374] THEMultipeerSession in,itialized peer 1452015424189.1336
2016-01-05 18:37:04.195 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,echo server started
,2016-01-05 18:37:05.404 ThaliTest[1336:2832172] client: found peer: 1452015424215.1319.2rPyww==
[{"peerIdentifier":"1452015424215.1319.2rPyww==","peerName":"(null)","peerAvailable":true}]
,2016-01-05 18:37:05.407 ThaliTest[1336:2832374] jxcore: connect 1452015424215.1319.2rPyww==
2016-01-05 18:37:05.410 ThaliTest[1336:2832374] client session: connect
2016-01-05 18:37:05.410 ThaliTest[1336:2832374] client session: stateChange:0->1 1452015424215.1319.2rPyww==
,2016-01-05 18:37:05.470 ThaliTest[1336:2832172] multipeer session: reset timer
2016-01-05 18:37:05.470 ThaliTest[1336:2832172] multipeer session: stop timer
2016-01-05 18:37:05.471 ThaliTest[1336:2832172] multipeer session: start timer: 0x1a828550
2016-01-05 18:37:05.471 ThaliTest[1336:2832172] server session: connect
2016-01-05 18:37:05.472 ThaliTest[1336:2832172] server session: stateChange:0->1 1452015424215.1319
,2016-01-05 18:37:05.481 ThaliTest[1336:2832172] server: accepting invitation 1452015424215.1319
,2016-01-05 18:37:08.481 ThaliTest[1336:2832879] server session: connected
2016-01-05 18:37:08.482 ThaliTest[1336:2832879] server session: stateChange:1->2 1452015424215.1319
,2016-01-05 18:37:08.495 ThaliTest[1336:2832172] server relay: connected (to port: 5001)
,2016-01-05 18:37:08.618 ThaliTest[1336:2832883] client session: connected
2016-01-05 18:37:08.619 ThaliTest[1336:2832883] client session: stateChange:1->2 1452015424215.1319.2rPyww==
,2016-01-05 18:37:08.635 ThaliTest[1336:2832879] client session: fireConnectCallback: 1452015424215.1319.2rPyww==
2016-01-05 18:37:08.636 ThaliTest[1336:2832879] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
,2016-01-05 18:37:08.694 ThaliTest[1336:2832172] client: relay established
2016-01-05 18:37:08.694 ThaliTest[1336:2832172] client: new accepted socket: 0x1a822dd0
,ok 92 the test messages should be equal
,2016-01-05 18:37:08.796 ThaliTest[1336:2832891] server session: not connected 1452015424215.1319
,ok 93 First send should succeed
,2016-01-05 18:37:08.822 ThaliTest[1336:2832172] client: socket closed
2016-01-05 18:37:08.823 ThaliTest[1336:2832172] client relay: socket disconnected
2016-01-05 18:37:08.823 ThaliTest[1336:2832172] client relay: 0x1a822dd0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-05 18:37:08.823 ThaliTest[1336:2832172] client session: socket closed: 1452015424215.1319.2rPyww==
2016-01-05 ,18:37:08.824 ThaliTest[1336:2832172] client session: onLinkFailure: 1452015424215.1319.2rPyww==
2016-01-05 18:37:08.824 ThaliTest[1336:2832172] client session: disconnect
,2016-01-05 18:37:08.824 ThaliTest[1336:2832172] client session: stateChange:2->0 1452015424215.1319.2rPyww==
,2016-01-05 18:37:08.836 ThaliTest[1336:2832172] client session: fireConnectionErrorEvent: 1452015424215.1319.2rPyww==
,2016-01-05 18:37:08.854 ThaliTest[1336:2832374] jxcore: connect 1452015424215.1319.2rPyww==
,2016-01-05 18:37:08.855 ThaliTest[1336:2832374] client session: connect
,2016-01-05 18:37:08.856 ThaliTest[1336:2832374] client session: stateChange:0->1 1452015424215.1319.2rPyww==
,2016-01-05 18:37:09.074 ThaliTest[1336:2832172] multipeer session: reset timer
2016-01-05 18:37:09.074 ThaliTest[1336:2832172] multipeer session: stop timer
2016-01-05 18:37:09.075 ThaliTest[1336:2832172] multipeer session: start timer: 0x1a828550
,2016-01-05 18:37:09.075 ThaliTest[1336:2832172] server: disconnecting to refresh session (1452015424215.1319)
2016-01-05 18:37:09.076 ThaliTest[1336:2832172] server session: disconnect
2016-01-05 18:37:09.077 ThaliTest[1336:2832172] server session: state,Change:2->0 1452015424215.1319
,2016-01-05 18:37:09.081 ThaliTest[1336:2832172] server session: connect
,2016-01-05 18:37:09.081 ThaliTest[1336:2832172] server session: stateChange:0->1 1452015424215.1319
,2016-01-05 18:37:09.104 ThaliTest[1336:2832172] server: accepting invitation 1452015424215.1319
,2016-01-05 18:37:11.638 ThaliTest[1336:2832891] client session: connected
,2016-01-05 18:37:11.639 ThaliTest[1336:2832891] client session: stateChange:1->2 1452015424215.1319.2rPyww==
,2016-01-05 18:37:11.646 ThaliTest[1336:2832891] client session: fireConnectCallback: 1452015424215.1319.2rPyww==
,2016-01-05 18:37:11.647 ThaliTest[1336:2832891] jxcore: connect: success
,ok 94 Should be able to connect without error
ok 95 Port should be within range
,ok 96 Second connect should succeed
,2016-01-05 18:37:11.681 ThaliTest[1336:2832172] client: relay established
2016-01-05 18:37:11.681 ThaliTest[1336:2832172] client: new accepted socket: 0x1a9a0160
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2016-01-05 18:37:11.744 ThaliTest[1336:2832172] client: socket closed
,2016-01-05 18:37:11.744 ThaliTest[1336:2832172] client relay: socket disconnected
,2016-01-05 18:37:11.744 ThaliTest[1336:2832172] client relay: 0x1a9a0160 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-05 18:37:,11.745 ThaliTest[1336:2832172] client session: socket closed: 1452015424215.1319.2rPyww==
,2016-01-05 18:37:11.745 ThaliTest[1336:2832172] client session: onLinkFailure: 1452015424215.1319.2rPyww==
2016-01-05 18:37:11.745 ThaliTest[1336:2832172] client session: disconnect
2016-01-05 18:37:11.746 ThaliTest[1336:2832172] client session: stateChange:2->0 1452015424215.1319.2rPyww==
,2016-01-05 18:37:11.761 ThaliTest[1336:2832172] client session: fireConnectionErrorEvent: 1452015424215.1319.2rPyww==
,2016-01-05 18:37:11.875 ThaliTest[1336:2832883] server session: connected
2016-01-05 18:37:11.876 ThaliTest[1336:2832883] server session: stateChange:1->2 1452015424215.1319
,2016-01-05 18:37:11.885 ThaliTest[1336:2832172] server relay: connected (to port: 5001)
,2016-01-05 18:37:12.038 ThaliTest[1336:2832883] server session: not connected 1452015424215.1319
,calling stopBroadcasting
2016-01-05 18:37:12.587 ThaliTest[1336:2832374] jxcore: stopBroadcasting
2016-01-05 18:37:12.587 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
2016-01-05 18:37:12.588 ThaliTest[1336:2832374] multipeer session: stop timer
2016-01-05 18:37:12.588 ThaliTest[1336:2832374] server session: disconnect
2016-01-05 18:37:12.588 ThaliTest[1336:2832374] server session: stateChange:2->0 1452015424215.1319
,2016-01-05 18:37:12.596 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F7361BEC-A0AB-4021-B4D4-D8745DBD38C5/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-05 18:37:13.849 ThaliTest[1336:2832374] jxcore: startBroadcasting
,2016-01-05 18:37:13.850 ThaliTest[1336:2832374] server: starting ir2OMNx-cY2eMy9wTy8Z9Q.Y+/OVw==
2016-01-05 18:37:13.850 ThaliTest[1336:2832374] multipeer session: start timer: 0x1a9aefd0
2016-01-05 18:37:13.850 ThaliTest[1336:2832374] THEMultipeerSession initialized peer ir2OMNx-cY2eMy9wTy8Z9Q
2016-01-05 18:37:13.851 ThaliTest[1336:2832374] jxcore: startBroadcasting: success
,ok 100 started event should occur in right order
,Now in TRM stop
State of this._isStarted: true
,ok 101 stopping event should occur in right order
,About to call stopBroadcasting
,2016-01-05 18:37:13.856 ThaliTest[1336:2832374] jxcore: stopBroadcasting
,2016-01-05 18:37:13.857 ThaliTest[1336:2832374] THEMultipeerSession stopping peer
,2016-01-05 18:37:13.857 ThaliTest[1336:2832374] multipeer session: stop timer
,2016-01-05 18:37:13.859 ThaliTest[1336:2832374] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,ok 102 stopped event should occur in right order
,mux server bridge listener closed
,# setup

```
