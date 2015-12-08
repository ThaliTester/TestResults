#### Test 506502785032ad1_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/385EB0C7-885C-48EB-B755-7D32638E7BD4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/385EB0C7-885C-48EB-B755-7D32638E7BD4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50470"
,(lldb)     command script import "/tmp/385EB0C7-885C-48EB-B755-7D32638E7BD4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 03:55:04.291 ThaliTest[439:220047] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BB228851-A920-4934-832C-BE223C8EFD2C/Library/Cookies/Cookies.binarycookies
,2015-12-08 03:55:04.633 ThaliTest[439:220047] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 03:55:04.634 ThaliTest[439:220047] Multi-tasking -> Device: YES, App: YES
,2015-12-08 03:55:04.642 ThaliTest[439:220047] Unlimited access to network resources
,2015-12-08 03:55:04.651 ThaliTest[439:220047] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 03:55:13.396 ThaliTest[439:220047] Resetting plugins due to page load.
,2015-12-08 03:55:16.788 ThaliTest[439:220047] Finished load of: file:///var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/index.html
,2015-12-08 03:55:16.969 ThaliTest[439:220047] JXcore Cordova plugin initializing
,2015-12-08 03:55:16.970 ThaliTest[439:220274] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,2015-12-08 03:56:44.066 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:44.317 ThaliTest[439:220274] server: starting 1449543404065.439.3/6FhQ==
,2015-12-08 03:56:44.318 ThaliTest[439:220274] multipeer session: start timer: 0x1a898d20
,2015-12-08 03:56:44.319 ThaliTest[439:220274] THEMultipeerSession initialized peer 1449543404065.439
,2015-12-08 03:56:44.319 ThaliTest[439:220274] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.323 ThaliTest[439:220274] jxcore: stopBroadcasting
2015-12-08 03:56:44.323 ThaliTest[439:220274] THEMultipeerSession stopping peer
2015-12-08 03:56:44.324 ThaliTest[439:220274] multipeer session: stop timer
2015-12-08 03:56:44.325 ThaliTest[439:220274] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.327 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:44.332 ThaliTest[439:220274] server: starting 1449543404326.439.1SHQKQ==
2015-12-08 03:56:44.333 ThaliTest[439:220274] multipeer session: start timer: 0x18f530f0
2015-12-08 03:56:44.333 ThaliTest[439:220274] THEMultipeerSession initializ,ed peer 1449543404326.439
2015-12-08 03:56:44.333 ThaliTest[439:220274] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-08 03:56:44.337 ThaliTest[439:220274] jxcore: stopBroadcasting
2015-12-08 03,:56:44.338 ThaliTest[439:220274] THEMultipeerSession stopping peer
2015-12-08 03:56:44.338 ThaliTest[439:220274] multipeer session: stop timer
,2015-12-08 03:56:44.342 ThaliTest[439:220274] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2015-12-08 03:56:44.346 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:44.356 ThaliTest[439:220274] server: starting 1449543404346.439.aHQL+Q==
2015-12-08 03:56:44.357 ThaliTest[439:220274] multipeer session: start timer: 0x18f55690
2015-12-08 03:56:44.358 ThaliTest[439:220274] THEMultipeerSession initializ,ed peer 1449543404346.439
2015-12-08 03:56:44.358 ThaliTest[439:220274] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2015-12-08 03:56:44.360 ThaliTest[439:220274] jxcore: stopBroadcasting
2015-12-08 03,:56:44.361 ThaliTest[439:220274] THEMultipeerSession stopping peer
2015-12-08 03:56:44.361 ThaliTest[439:220274] multipeer session: stop timer
2015-12-08 03:56:44.361 ThaliTest[439:220274] jxcore: stopBroadcasting: success
ok 50 Should be able to call s,topBroadcasting without error
2015-12-08 03:56:44.364 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:44.379 ThaliTest[439:220274] server: starting 1449543404363.439.+gxR4Q==
,2015-12-08 03:56:44.391 ThaliTest[439:220274] multipeer session: start timer: 0x18f56e20
,2015-12-08 03:56:44.398 ThaliTest[439:220274] THEMultipeerSession initialized peer 1449543404363.439
,2015-12-08 03:56:44.402 ThaliTest[439:220274] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.405 ThaliTest[439:220274] jxcore: stopBroadcasting
,2015-12-08 03:56:44.406 ThaliTest[439:220274] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.406 ThaliTest[439:220274] multipeer session: stop timer
,2015-12-08 03:56:44.408 ThaliTest[439:220274] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.412 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:44.415 ThaliTest[439:220274] server: starting 1449543404412.439.ZapgDA==
,2015-12-08 03:56:44.417 ThaliTest[439:220274] multipeer session: start timer: 0x1a89c3c0
,2015-12-08 03:56:44.421 ThaliTest[439:220274] THEMultipeerSession initialized peer 1449543404412.439
,2015-12-08 03:56:44.421 ThaliTest[439:220274] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.425 ThaliTest[439:220274] jxcore: stopBroadcasting
,2015-12-08 03:56:44.426 ThaliTest[439:220274] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.426 ThaliTest[439:220274] multipeer session: stop timer
,2015-12-08 03:56:44.429 ThaliTest[439:220274] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.433 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:44.436 ThaliTest[439:220274] server: starting 1449543404432.439.hi4Msw==
,2015-12-08 03:56:44.438 ThaliTest[439:220274] multipeer session: start timer: 0x1a89e720
,2015-12-08 03:56:44.442 ThaliTest[439:220274] THEMultipeerSession initialized peer 1449543404432.439
,2015-12-08 03:56:44.443 ThaliTest[439:220274] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.446 ThaliTest[439:220274] jxcore: stopBroadcasting
,2015-12-08 03:56:44.446 ThaliTest[439:220274] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.447 ThaliTest[439:220274] multipeer session: stop timer
,2015-12-08 03:56:44.449 ThaliTest[439:220274] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.454 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:44.459 ThaliTest[439:220274] server: starting 1449543404454.439.Te1EtQ==
,2015-12-08 03:56:44.461 ThaliTest[439:220274] multipeer session: start timer: 0x18f56ff0
,2015-12-08 03:56:44.465 ThaliTest[439:220274] THEMultipeerSession initialized peer 1449543404454.439
,2015-12-08 03:56:44.467 ThaliTest[439:220274] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.470 ThaliTest[439:220274] jxcore: stopBroadcasting
,2015-12-08 03:56:44.470 ThaliTest[439:220274] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.471 ThaliTest[439:220274] multipeer session: stop timer
,2015-12-08 03:56:44.476 ThaliTest[439:220274] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.479 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:44.481 ThaliTest[439:220274] server: starting 1449543404478.439.lkSyrQ==
,2015-12-08 03:56:44.484 ThaliTest[439:220274] multipeer session: start timer: 0x18f571d0
,2015-12-08 03:56:44.488 ThaliTest[439:220274] THEMultipeerSession initialized peer 1449543404478.439
,2015-12-08 03:56:44.489 ThaliTest[439:220274] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.493 ThaliTest[439:220274] jxcore: stopBroadcasting
,2015-12-08 03:56:44.494 ThaliTest[439:220274] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.495 ThaliTest[439:220274] multipeer session: stop timer
,2015-12-08 03:56:44.497 ThaliTest[439:220274] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.501 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:44.504 ThaliTest[439:220274] server: starting 1449543404501.439.L6hxmQ==
,2015-12-08 03:56:44.505 ThaliTest[439:220274] multipeer session: start timer: 0x1a89f3e0
,2015-12-08 03:56:44.507 ThaliTest[439:220274] THEMultipeerSession initialized peer 1449543404501.439
,2015-12-08 03:56:44.509 ThaliTest[439:220274] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.512 ThaliTest[439:220274] jxcore: stopBroadcasting
,2015-12-08 03:56:44.512 ThaliTest[439:220274] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.513 ThaliTest[439:220274] multipeer session: stop timer
,2015-12-08 03:56:44.514 ThaliTest[439:220274] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.518 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:44.520 ThaliTest[439:220274] server: starting 1449543404517.439.BtHiLg==
,2015-12-08 03:56:44.522 ThaliTest[439:220274] multipeer session: start timer: 0x18f57a50
,2015-12-08 03:56:44.525 ThaliTest[439:220274] THEMultipeerSession initialized peer 1449543404517.439
,2015-12-08 03:56:44.526 ThaliTest[439:220274] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.528 ThaliTest[439:220274] jxcore: stopBroadcasting
,2015-12-08 03:56:44.528 ThaliTest[439:220274] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.528 ThaliTest[439:220274] multipeer session: stop timer
,2015-12-08 03:56:44.529 ThaliTest[439:220274] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-08 03:56:48.030 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:48.034 ThaliTest[439:220274] server: starting 1449543408030.439.u+sz1A==
2015-12-08 03:56:48.035 ThaliTest[439:220274] multipeer session: start timer: 0x1a8a3930
2015-12-08 03:56:48.035 ThaliTest[439:220274] THEMultipeerSession initializ,ed peer 1449543408030.439
2015-12-08 03:56:48.036 ThaliTest[439:220274] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2015-12-08 03:56:48.038 ThaliTest[439:220274] jxcore: startBroadcasting
2015-12-08 0,3:56:48.039 ThaliTest[439:220274] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2015-12-08 03:56:48.042 ThaliTest[439:220274] jxcore: stopBroadcasting
2015-12-08 03:56:48.043 ThaliTest[439:220274] THEMultipeerSession stopping peer
2015-12-08 03:56:48.043 ThaliTest[439:220274] multipeer session: stop timer
2015-12-08 03:56:48.044 Th,aliTest[439:220274] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-08 03:56:52.334 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:52.337 ThaliTest[439:220274] server: starting 1449543412333.439.uuhSyg==
2015-12-08 03:56:52.338 ThaliTest[439:220274] multipeer session: start timer: 0x1a8a5be0
2015-12-08 03:56:52.339 ThaliTest[439:220274] THEMultipeerSession initializ,ed peer 1449543412333.439
2015-12-08 03:56:52.339 ThaliTest[439:220274] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-08 03:56:52.341 ThaliTest[439:220274] jxcore: connect foobar
2015-12-08 03:5,6:52.342 ThaliTest[439:220274] client: unknown peer foobar
2015-12-08 03:56:52.342 ThaliTest[439:220274] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2015-12-08 03:56:52.345 ThaliTest[439:220274] jxcore: stopBroadcasting
2015-12-08 03:56:52.347 ThaliTest[439:220274] THEMultipeerSession stopping peer
2015-12-08 03:56:52.347 ThaliTest[439:220274] multipeer session: stop timer
2015-12-08 03:56:52.348 Th,aliTest[439:220274] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-08 03:56:56.724 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:56:56.727 ThaliTest[439:220274] server: starting 1449543416723.439.CkjE8w==
2015-12-08 03:56:56.728 ThaliTest[439:220274] multipeer session: start timer: 0x1a8a8f80
2015-12-08 03:56:56.728 ThaliTest[439:220274] THEMultipeerSession initializ,ed peer 1449543416723.439
2015-12-08 03:56:56.729 ThaliTest[439:220274] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-08 03:56:56.731 ThaliTest[439:220274] jxcore: disconnect
2015-12-08 03:56:56,.732 ThaliTest[439:220274] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2015-12-08 03:56:56.734 ThaliTest[439:220274] jxcore: stopBroadcasting
2015-12-08 03:56:56.734 ThaliTest[439:220274] THEMultipeerSession stopping pe,er
2015-12-08 03:56:56.734 ThaliTest[439:220274] multipeer session: stop timer
2015-12-08 03:56:56.735 ThaliTest[439:220274] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-08 03:57:01.775 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:57:01.779 ThaliTest[439:220274] server: starting 1449543421775.439.IbqVaQ==
2015-12-08 03:57:01.780 ThaliTest[439:220274] multipeer session: start timer: 0x1a8ac8e0
2015-12-08 03:57:01.780 ThaliTest[439:220274] THEMultipeerSession initializ,ed peer 1449543421775.439
2015-12-08 03:57:01.781 ThaliTest[439:220274] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2015-12-08 03:57:04.077 ThaliTest[439:220047] client: found peer: 1449543422873.405.4eQM3Q==
2015-12-08 03:57:04.080 ThaliTest[439:220274] jxcore: connect 1449543422873.405.4eQM3Q==
2015-12-08 03:57:04.081 ThaliTest[439:220274] client session: connect
2015-12-08 03:57:04.081 ThaliTest[439:220274] client session: stateChange:0->1 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:04.956 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:57:04.956 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:57:04.957 ThaliTest[439:220047] multipeer session: start timer: 0x1a8ac8e0
2015-12-08 03:57:04.957 ThaliTest[439:220047] server session: connect
,2015-12-08 03:57:04.958 ThaliTest[439:220047] server session: stateChange:0->1 1449543421260.391
,2015-12-08 03:57:04.968 ThaliTest[439:220047] server: accepting invitation 1449543421260.391
,2015-12-08 03:57:05.123 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:57:05.123 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:57:05.123 ThaliTest[439:220047] multipeer session: start timer: 0x1a8ac8e0
,2015-12-08 03:57:05.124 ThaliTest[439:220047] server session: connect
,2015-12-08 03:57:05.124 ThaliTest[439:220047] server session: stateChange:0->1 1449543421593.431
,2015-12-08 03:57:05.131 ThaliTest[439:220047] server: accepting invitation 1449543421593.431
,2015-12-08 03:57:05.565 ThaliTest[439:220047] client: found peer: 1449543421593.431.+h1/ug==
,2015-12-08 03:57:05.566 ThaliTest[439:220274] jxcore: connect 1449543421593.431.+h1/ug==
2015-12-08 03:57:05.567 ThaliTest[439:220274] client session: connect
2015-12-08 03:57:05.567 ThaliTest[439:220274] client session: stateChange:0->1 1449543421593.431.+h1/ug==
,2015-12-08 03:57:05.714 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:57:05.714 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:57:05.714 ThaliTest[439:220047] multipeer session: start timer: 0x1a8ac8e0
2015-12-08 ,03:57:05.714 ThaliTest[439:220047] server session: connect
2015-12-08 03:57:05.714 ThaliTest[439:220047] server session: stateChange:0->1 1449543422873.405
,2015-12-08 03:57:05.718 ThaliTest[439:220047] server: accepting invitation 1449543422873.405
,2015-12-08 03:57:05.865 ThaliTest[439:220047] client: found peer: 1449543421260.391.hpKQLw==
2015-12-08 03:57:05.865 ThaliTest[439:220274] jxcore: connect 1449543421260.391.hpKQLw==
2015-12-08 03:57:05.865 ThaliTest[439:220274] client session: connect
2015-12-08 03:57:05.865 ThaliTest[439:220274] client session: stateChange:0->1 1449543421260.391.hpKQLw==
,2015-12-08 03:57:08.010 ThaliTest[439:220488] client session: connected
2015-12-08 03:57:08.011 ThaliTest[439:220488] client session: stateChange:1->2 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:08.067 ThaliTest[439:220554] client session: fireConnectCallback: 1449543422873.405.4eQM3Q==
2015-12-08 03:57:08.068 ThaliTest[439:220554] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be withi,n range
2015-12-08 03:57:08.073 ThaliTest[439:220274] jxcore: disconnect
2015-12-08 03:57:08.073 ThaliTest[439:220274] client session: disconnectFromPeer: 1449543422873.405.4eQM3Q==
2015-12-08 03:57:08.073 ThaliTest[439:220274] client session: disconnect
,2015-12-08 03:57:08.074 ThaliTest[439:220274] client session: stateChange:2->0 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:08.087 ThaliTest[439:220274] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-08 03:57:08.542 ThaliTest[439:220554] server session: connected
,2015-12-08 03:57:08.543 ThaliTest[439:220554] server session: stateChange:1->2 1449543421260.391
,2015-12-08 03:57:08.607 ThaliTest[439:220047] server relay: socket disconnected
,2015-12-08 03:57:08.608 ThaliTest[439:220047] server relay: 0x1a8cc780 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:08.658 ThaliTest[439:220554] server session: connected
,2015-12-08 03:57:08.659 ThaliTest[439:220554] server session: stateChange:1->2 1449543421593.431
,2015-12-08 03:57:08.732 ThaliTest[439:220047] server relay: socket disconnected
,2015-12-08 03:57:08.733 ThaliTest[439:220047] server relay: 0x1a8b8390 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:08.742 ThaliTest[439:220554] server session: not connected 1449543421593.431
,2015-12-08 03:57:08.978 ThaliTest[439:220543] server session: connected
2015-12-08 03:57:08.979 ThaliTest[439:220543] server session: stateChange:1->2 1449543422873.405
,2015-12-08 03:57:09.006 ThaliTest[439:220047] server relay: socket disconnected
,2015-12-08 03:57:09.006 ThaliTest[439:220047] server relay: 0x1a8d0af0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:09.050 ThaliTest[439:220483] server session: not connected 1449543422873.405
,2015-12-08 03:57:09.147 ThaliTest[439:220483] client session: connected
2015-12-08 03:57:09.147 ThaliTest[439:220483] client session: stateChange:1->2 1449543421593.431.+h1/ug==
2015-12-08 03:57:09.148 ThaliTest[439:220483] client session: connected
2015-12-08 03:57:09.149 ThaliTest[439:220483] client session: stateChange:1->2 1449543421260.391.hpKQLw==
,2015-12-08 03:57:09.189 ThaliTest[439:220543] client session: fireConnectCallback: 1449543421260.391.hpKQLw==
2015-12-08 03:57:09.190 ThaliTest[439:220543] jxcore: connect: success
2015-12-08 03:57:09.190 ThaliTest[439:220554] client session: fireConnect,Callback: 1449543421593.431.+h1/ug==
2015-12-08 03:57:09.191 ThaliTest[439:220554] jxcore: connect: success
ok 78 Should be able to connect without error
ok 79 Port should be within range
,2015-12-08 03:57:09.194 ThaliTest[439:220274] jxcore: disconnect
2015-12-08 03:57:09.195 ThaliTest[439:220274] client session: disconnectFromPeer: 1449543421260.391.hpKQLw==
2015-12-08 03:57:09.195 ThaliTest[439:220274] client session: disconnect
2015-12-08 03:57:09.196 ThaliTest[439:220274] client session: stateChange:2->0 1449543421260.391.hpKQLw==
,2015-12-08 03:57:09.210 ThaliTest[439:220274] jxcore: disconnect: success
ok 80 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,not ok 81 .end() called twice
  ---
    operator: fail
  ...
ok 82 Should be able to connect without error
ok 83 Port should be within range
2015-12-08 03:57:09.221 ThaliTest[439:220274] jxcore: disconnect
2015-12-08 03:57:09.221 ThaliTest[439:22027,4] client session: disconnectFromPeer: 1449543421593.431.+h1/ug==
2015-12-08 03:57:09.221 ThaliTest[439:220274] client session: disconnect
2015-12-08 03:57:09.222 ThaliTest[439:220274] client session: stateChange:2->0 1449543421593.431.+h1/ug==
,2015-12-08 03:57:09.241 ThaliTest[439:220274] jxcore: disconnect: success
ok 84 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
not ok 85 .end() called twice
  ---
    operator: fail
  ...
,2015-12-08 03:57:09.535 ThaliTest[439:220554] server session: not connected 1449543421260.391
,calling stopBroadcasting
,2015-12-08 03:57:11.094 ThaliTest[439:220274] jxcore: stopBroadcasting
2015-12-08 03:57:11.096 ThaliTest[439:220274] THEMultipeerSession stopping peer
2015-12-08 03:57:11.096 ThaliTest[439:220274] multipeer session: stop timer
2015-12-08 03:57:11.096 ThaliTest[439:220274] server session: disconnect
,2015-12-08 03:57:11.097 ThaliTest[439:220274] server session: stateChange:2->0 1449543421593.431
,2015-12-08 03:57:11.806 ThaliTest[439:220274] server session: disconnect
2015-12-08 03:57:11.807 ThaliTest[439:220274] server session: stateChange:2->0 1449543422873.405
2015-12-08 03:57:11.808 ThaliTest[439:220274] server session: disconnect
2015-12-08, 03:57:11.808 ThaliTest[439:220274] server session: stateChange:2->0 1449543421260.391
2015-12-08 03:57:11.809 ThaliTest[439:220274] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-08 03:57:25.470 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:57:25.474 ThaliTest[439:220274] server: starting 1449543445470.439.9bQ4gA==
2015-12-08 03:57:25.475 ThaliTest[439:220274] multipeer session: start timer: 0x1a8afee0
2015-12-08 03:57:25.475 ThaliTest[439:220274] THEMultipeerSession initializ,ed peer 1449543445470.439
2015-12-08 03:57:25.476 ThaliTest[439:220274] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error
,2015-12-08 03:57:26.231 ThaliTest[439:220047] client: found peer: 1449543421260.391.hpKQLw==
2015-12-08 03:57:26.232 ThaliTest[439:220274] jxcore: connect 1449543421260.391.hpKQLw==
2015-12-08 03:57:26.233 ThaliTest[439:220274] client session: connect
2015-12-08 03:57:26.233 ThaliTest[439:220274] client session: stateChange:0->1 1449543421260.391.hpKQLw==
,2015-12-08 03:57:26.343 ThaliTest[439:220047] client: found peer: 1449543444583.391.Wxk+bw==
2015-12-08 03:57:26.345 ThaliTest[439:220274] jxcore: connect 1449543444583.391.Wxk+bw==
2015-12-08 03:57:26.345 ThaliTest[439:220274] client session: connect
2015-12-08 03:57:26.345 ThaliTest[439:220274] client session: stateChange:0->1 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:26.809 ThaliTest[439:220047] client: found peer: 1449543445467.431.nUNHmA==
2015-12-08 03:57:26.811 ThaliTest[439:220274] jxcore: connect 1449543445467.431.nUNHmA==
2015-12-08 03:57:26.811 ThaliTest[439:220274] client session: connect
2,015-12-08 03:57:26.812 ThaliTest[439:220274] client session: stateChange:0->1 1449543445467.431.nUNHmA==
,2015-12-08 03:57:26.820 ThaliTest[439:220047] client: found peer: 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:26.829 ThaliTest[439:220274] jxcore: connect 1449543446505.405.XRtx8Q==
2015-12-08 03:57:26.830 ThaliTest[439:220274] client session: connect
2015-12-08 03:57:26.830 ThaliTest[439:220274] client session: stateChange:0->1 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:26.952 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:57:26.952 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:57:26.953 ThaliTest[439:220047] multipeer session: start timer: 0x1a8afee0
2015-12-08 03:57:26.953 ThaliTest[439:220047] server session: connect
,2015-12-08 03:57:26.954 ThaliTest[439:220047] server session: stateChange:0->1 1449543446505.405
,2015-12-08 03:57:26.963 ThaliTest[439:220047] server: accepting invitation 1449543446505.405
,2015-12-08 03:57:27.001 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:57:27.001 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:57:27.001 ThaliTest[439:220047] multipeer session: start timer: 0x1a8afee0
,2015-12-08 03:57:27.003 ThaliTest[439:220047] server session: connect
2015-12-08 03:57:27.003 ThaliTest[439:220047] server session: stateChange:0->1 1449543445467.431
2015-12-08 03:57:27.021 ThaliTest[439:220047] server: accepting invitation 1449543445467.431
,2015-12-08 03:57:27.519 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:57:27.520 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:57:27.520 ThaliTest[439:220047] multipeer session: start timer: 0x1a8afee0
2015-12-08 03:57:27.520 ThaliTest[439:220047] server session: connect
2015-12-08 03:57:27.520 ThaliTest[439:220047] server session: stateChange:0->1 1449543444583.391
2015-12-08 03:57:27.526 ThaliTest[439:220047] server: accepting invitation 1449543444583.391
,2015-12-08 03:57:30.027 ThaliTest[439:220047] client: lost peer: 1449543421260.391.hpKQLw==
,2015-12-08 03:57:30.028 ThaliTest[439:220047] client session: onPeerLost: 1449543421260.391.hpKQLw==
,2015-12-08 03:57:30.029 ThaliTest[439:220047] client session: onLinkFailure: 1449543421260.391.hpKQLw==
,2015-12-08 03:57:30.029 ThaliTest[439:220047] client session: disconnect
,2015-12-08 03:57:30.030 ThaliTest[439:220047] client session: stateChange:1->0 1449543421260.391.hpKQLw==
,2015-12-08 03:57:30.032 ThaliTest[439:220047] client session: fireConnectCallback: 1449543421260.391.hpKQLw==
,2015-12-08 03:57:30.032 ThaliTest[439:220047] jxcore: connect: fail: Peer disconnected
,2015-12-08 03:57:30.156 ThaliTest[439:220678] server session: connected
,2015-12-08 03:57:30.157 ThaliTest[439:220678] server session: stateChange:1->2 1449543446505.405
,2015-12-08 03:57:30.161 ThaliTest[439:220047] server relay: socket disconnected
,2015-12-08 03:57:30.162 ThaliTest[439:220047] server relay: 0x1a8d5a30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:30.208 ThaliTest[439:220619] server session: not connected 1449543446505.405
,2015-12-08 03:57:30.585 ThaliTest[439:220619] client session: connected
2015-12-08 03:57:30.585 ThaliTest[439:220619] client session: stateChange:1->2 1449543446505.405.XRtx8Q==
2015-12-08 03:57:30.592 ThaliTest[439:220678] client session: fireConnectCallback: 1449543446505.405.XRtx8Q==
2015-12-08 03:57:30.592 ThaliTest[439:220678] jxcore: connect: success
,ok 87 Should be able to connect without error
,ok 88 Port should be within range
2015-12-08 03:57:30.598 ThaliTest[439:220274] jxcore: connect 1449543446505.405.XRtx8Q==
2015-12-08 03:57:30.598 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543446505.405.XRtx8Q==
2015-12-08 03:57:30.59,9 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
ok 89 Should fail on double connect
2015-12-08 03:57:30.600 ThaliTest[439:220274] jxcore: disconnect
,2015-12-08 03:57:30.601 ThaliTest[439:220274] client session: disconnectFromPeer: 1449543446505.405.XRtx8Q==
2015-12-08 03:57:30.601 ThaliTest[439:220274] client session: disconnect
2015-12-08 03:57:30.601 ThaliTest[439:220274] client session: stateChange:2->0 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:30.673 ThaliTest[439:220274] jxcore: disconnect: success
,ok 90 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2015-12-08 03:57:31.224 ThaliTest[439:220619] client session: connected
2015-12-08 03:57:31.225 ThaliTest[439:220619] client session: stateChange:1->2 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:31.231 ThaliTest[439:220619] client session: fireConnectCallback: 1449543444583.391.Wxk+bw==
2015-12-08 03:57:31.231 ThaliTest[439:220619] jxcore: connect: success
ok 91 Should be able to connect without error
ok 92 Port should be withi,n range
,2015-12-08 03:57:31.235 ThaliTest[439:220274] jxcore: connect 1449543444583.391.Wxk+bw==
2015-12-08 03:57:31.235 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543444583.391.Wxk+bw==
2015-12-08 03:57:31.235 ThaliTest[439:220274] jxcore: con,nect: fail: Aleady connecting
ok 93 Should fail on double connect
,2015-12-08 03:57:31.237 ThaliTest[439:220274] jxcore: disconnect
,2015-12-08 03:57:31.237 ThaliTest[439:220274] client session: disconnectFromPeer: 1449543444583.391.Wxk+bw==
2015-12-08 03:57:31.238 ThaliTest[439:220274] client session: disconnect
2015-12-08 03:57:31.238 ThaliTest[439:220274] client session: stateChange:2->0 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:31.307 ThaliTest[439:220274] jxcore: disconnect: success
ok 94 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
not ok 95 .end() called twice
  ---
    operator: fail
  ...
,2015-12-08 03:57:31.568 ThaliTest[439:220619] server session: connected
,2015-12-08 03:57:31.568 ThaliTest[439:220620] client session: connected
,2015-12-08 03:57:31.569 ThaliTest[439:220619] server session: stateChange:1->2 1449543445467.431
,2015-12-08 03:57:31.570 ThaliTest[439:220620] client session: stateChange:1->2 1449543445467.431.nUNHmA==
,2015-12-08 03:57:31.577 ThaliTest[439:220047] server relay: socket disconnected
,2015-12-08 03:57:31.578 ThaliTest[439:220047] server relay: 0x1a8cdc10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:31.581 ThaliTest[439:220620] client session: fireConnectCallback: 1449543445467.431.nUNHmA==
2015-12-08 03:57:31.581 ThaliTest[439:220620] jxcore: connect: success
,ok 96 Should be able to connect without error
,ok 97 Port should be within range
,2015-12-08 03:57:31.586 ThaliTest[439:220274] jxcore: connect 1449543445467.431.nUNHmA==
,2015-12-08 03:57:31.586 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543445467.431.nUNHmA==
,2015-12-08 03:57:31.586 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,ok 98 Should fail on double connect
,2015-12-08 03:57:31.588 ThaliTest[439:220274] jxcore: disconnect
,2015-12-08 03:57:31.589 ThaliTest[439:220274] client session: disconnectFromPeer: 1449543445467.431.nUNHmA==
,2015-12-08 03:57:31.589 ThaliTest[439:220274] client session: disconnect
,2015-12-08 03:57:31.590 ThaliTest[439:220274] client session: stateChange:2->0 1449543445467.431.nUNHmA==
,2015-12-08 03:57:31.653 ThaliTest[439:220619] server session: not connected 1449543445467.431
,2015-12-08 03:57:31.655 ThaliTest[439:220274] jxcore: disconnect: success
,ok 99 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,not ok 100 .end() called twice
  ---
    operator: fail
  ...
,2015-12-08 03:57:31.778 ThaliTest[439:220647] server session: connected
,2015-12-08 03:57:31.779 ThaliTest[439:220647] server session: stateChange:1->2 1449543444583.391
,2015-12-08 03:57:32.056 ThaliTest[439:220647] server session: not connected 1449543444583.391
,2015-12-08 03:57:32.059 ThaliTest[439:220047] server relay: socket disconnected
2015-12-08 03:57:32.060 ThaliTest[439:220047] server relay: 0x1a8c0dc0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting
,2015-12-08 03:57:54.081 ThaliTest[439:220274] jxcore: stopBroadcasting
2015-12-08 03:57:54.082 ThaliTest[439:220274] THEMultipeerSession stopping peer
2015-12-08 03:57:54.082 ThaliTest[439:220274] multipeer session: stop timer
2015-12-08 03:57:54.082 Th,aliTest[439:220274] server session: disconnect
2015-12-08 03:57:54.083 ThaliTest[439:220274] server session: stateChange:2->0 1449543444583.391
2015-12-08 03:57:54.084 ThaliTest[439:220274] server session: disconnect
2015-12-08 03:57:54.084 ThaliTest[43,9:220274] server session: stateChange:2->0 1449543446505.405
2015-12-08 03:57:54.085 ThaliTest[439:220274] server session: disconnect
2015-12-08 03:57:54.086 ThaliTest[439:220274] server session: stateChange:2->0 1449543445467.431
,2015-12-08 03:57:54.094 ThaliTest[439:220274] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-08 03:57:57.672 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:57:57.675 ThaliTest[439:220274] server: starting 1449543477671.439.01rxOw==
2015-12-08 03:57:57.676 ThaliTest[439:220274] multipeer session: start timer: 0x1a8bf3c0
2015-12-08 03:57:57.676 ThaliTest[439:220274] THEMultipeerSession initialized peer 1449543477671.439
2015-12-08 03:57:57.677 ThaliTest[439:220274] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error
,2015-12-08 03:57:59.033 ThaliTest[439:220047] client: found peer: 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:59.035 ThaliTest[439:220274] jxcore: connect 1449543444583.391.Wxk+bw==
2015-12-08 03:57:59.036 ThaliTest[439:220274] client session: connect
2015-12-08 03:57:59.036 ThaliTest[439:220274] client session: stateChange:0->1 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:59.048 ThaliTest[439:220047] client: found peer: 1449543445467.431.nUNHmA==
,2015-12-08 03:57:59.050 ThaliTest[439:220274] jxcore: connect 1449543445467.431.nUNHmA==
2015-12-08 03:57:59.051 ThaliTest[439:220274] client session: connect
2015-12-08 03:57:59.051 ThaliTest[439:220274] client session: stateChange:0->1 1449543445467.43,1.nUNHmA==
,2015-12-08 03:57:59.069 ThaliTest[439:220047] client: found peer: 1449543477155.391.TQsX1A==
2015-12-08 03:57:59.070 ThaliTest[439:220274] jxcore: connect 1449543477155.391.TQsX1A==
,2015-12-08 03:57:59.071 ThaliTest[439:220274] client session: connect
2015-12-08 03:57:59.072 ThaliTest[439:220274] client session: stateChange:0->1 1449543477155.391.TQsX1A==
,2015-12-08 03:57:59.237 ThaliTest[439:220047] client: found peer: 1449543478008.431.8PN9MA==
2015-12-08 03:57:59.239 ThaliTest[439:220274] jxcore: connect 1449543478008.431.8PN9MA==
2015-12-08 03:57:59.239 ThaliTest[439:220274] client session: connect
2,015-12-08 03:57:59.239 ThaliTest[439:220274] client session: stateChange:0->1 1449543478008.431.8PN9MA==
,2015-12-08 03:57:59.628 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:57:59.629 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:57:59.629 ThaliTest[439:220047] multipeer session: start timer: 0x1a8bf3c0
2015-12-08 ,03:57:59.629 ThaliTest[439:220047] server session: connect
2015-12-08 03:57:59.630 ThaliTest[439:220047] server session: stateChange:0->1 1449543480460.405
,2015-12-08 03:57:59.639 ThaliTest[439:220047] server: accepting invitation 1449543480460.405
,2015-12-08 03:58:00.152 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:58:00.153 ThaliTest[439:220047] multipeer session: stop timer
,2015-12-08 03:58:00.153 ThaliTest[439:220047] multipeer session: start timer: 0x1a8bf3c0
2015-12-08 03:58:00.153 ThaliTest[439:220047] server session: connect
2015-12-08 03:58:00.154 ThaliTest[439:220047] server session: stateChange:0->1 1449543478008.431
,2015-12-08 03:58:00.160 ThaliTest[439:220047] server: accepting invitation 1449543478008.431
,2015-12-08 03:58:00.324 ThaliTest[439:220047] client: found peer: 1449543480460.405.wRZudQ==
2015-12-08 03:58:00.325 ThaliTest[439:220274] jxcore: connect 1449543480460.405.wRZudQ==
2015-12-08 03:58:00.325 ThaliTest[439:220274] client session: connect
2015-12-08 03:58:00.325 ThaliTest[439:220274] client session: stateChange:0->1 1449543480460.405.wRZudQ==
,2015-12-08 03:58:00.477 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:58:00.477 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:58:00.477 ThaliTest[439:220047] multipeer session: start timer: 0x1a8bf3c0
2015-12-08 03:58:00.478 ThaliTest[439:220047] server session: connect
2015-12-08 03:58:00.478 ThaliTest[439:220047] server session: stateChange:0->1 1449543477155.391
2015-12-08 03:58:00.485 ThaliTest[439:220047] server: accepting invitation 1449543477155.391
,2015-12-08 03:58:02.264 ThaliTest[439:220761] server session: connected
,2015-12-08 03:58:02.265 ThaliTest[439:220761] server session: stateChange:1->2 1449543480460.405
,2015-12-08 03:58:02.276 ThaliTest[439:220047] server relay: socket disconnected
,2015-12-08 03:58:02.276 ThaliTest[439:220047] server relay: 0x18fa0830 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:58:02.320 ThaliTest[439:220758] server session: not connected 1449543480460.405
,2015-12-08 03:58:02.719 ThaliTest[439:220761] client session: connected
,2015-12-08 03:58:02.720 ThaliTest[439:220761] client session: stateChange:1->2 1449543478008.431.8PN9MA==
,2015-12-08 03:58:02.940 ThaliTest[439:220762] client session: fireConnectCallback: 1449543478008.431.8PN9MA==
2015-12-08 03:58:02.940 ThaliTest[439:220762] jxcore: connect: success
ok 102 Should be able to connect without error
ok 103 Port should be within range
,2015-12-08 03:58:02.944 ThaliTest[439:220274] jxcore: disconnect
2015-12-08 03:58:02.945 ThaliTest[439:220274] client session: disconnectFromPeer: 1449543478008.431.8PN9MA==
2015-12-08 03:58:02.946 ThaliTest[439:220274] client session: disconnect
2015-1,2-08 03:58:02.946 ThaliTest[439:220274] client session: stateChange:2->0 1449543478008.431.8PN9MA==
,2015-12-08 03:58:02.964 ThaliTest[439:220274] jxcore: disconnect: success
ok 104 Should be able to disconnect without error
2015-12-08 03:58:02.966 ThaliTest[439:220274] jxcore: disconnect
2015-12-08 03:58:02.966 ThaliTest[439:220274] jxcore: disconnect: fail
ok 105 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-08 03:58:03.117 ThaliTest[439:220764] client session: connected
2015-12-08 03:58:03.117 ThaliTest[439:220764] client session: stateChange:1->2 1449543477155.391.TQsX1A==
,2015-12-08 03:58:03.122 ThaliTest[439:220764] client session: fireConnectCallback: 1449543477155.391.TQsX1A==
2015-12-08 03:58:03.123 ThaliTest[439:220764] jxcore: connect: success
,ok 106 Should be able to connect without error
,ok 107 Port should be within range
,2015-12-08 03:58:03.126 ThaliTest[439:220274] jxcore: disconnect
2015-12-08 03:58:03.127 ThaliTest[439:220274] client session: disconnectFromPeer: 1449543477155.391.TQsX1A==
2015-12-08 03:58:03.127 ThaliTest[439:220274] client session: disconnect
2015-1,2-08 03:58:03.127 ThaliTest[439:220274] client session: stateChange:2->0 1449543477155.391.TQsX1A==
,2015-12-08 03:58:03.202 ThaliTest[439:220274] jxcore: disconnect: success
ok 108 Should be able to disconnect without error
,2015-12-08 03:58:03.204 ThaliTest[439:220274] jxcore: disconnect
,2015-12-08 03:58:03.205 ThaliTest[439:220274] jxcore: disconnect: fail
ok 109 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,not ok 110 .end() called twice
  ---
,    operator: fail
,  ...
,2015-12-08 03:58:03.310 ThaliTest[439:220764] server session: connected
2015-12-08 03:58:03.310 ThaliTest[439:220764] server session: stateChange:1->2 1449543478008.431
,2015-12-08 03:58:03.364 ThaliTest[439:220047] server relay: socket disconnected
2015-12-08 03:58:03.364 ThaliTest[439:220047] server relay: 0x18f8a270 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:58:03.444 ThaliTest[439:220764] server session: not connected 1449543478008.431
,2015-12-08 03:58:03.508 ThaliTest[439:220764] client session: connected
2015-12-08 03:58:03.509 ThaliTest[439:220764] client session: stateChange:1->2 1449543480460.405.wRZudQ==
2015-12-08 03:58:03.516 ThaliTest[439:220764] client session: fireConnectCallback: 1449543480460.405.wRZudQ==
2015-12-08 03:58:03.516 ThaliTest[439:220764] jxcore: connect: success
ok 111 Should be able to connect without error
,ok 112 Port should be within range
,2015-12-08 03:58:03.521 ThaliTest[439:220274] jxcore: disconnect
2015-12-08 03:58:03.521 ThaliTest[439:220274] client session: disconnectFromPeer: 1449543480460.405.wRZudQ==
2015-12-08 03:58:03.522 ThaliTest[439:220274] client session: disconnect
2015-1,2-08 03:58:03.522 ThaliTest[439:220274] client session: stateChange:2->0 1449543480460.405.wRZudQ==
,2015-12-08 03:58:03.616 ThaliTest[439:220274] jxcore: disconnect: success
,ok 113 Should be able to disconnect without error
,2015-12-08 03:58:03.619 ThaliTest[439:220274] jxcore: disconnect
,2015-12-08 03:58:03.619 ThaliTest[439:220274] jxcore: disconnect: fail
,ok 114 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,not ok 115 .end() called twice
  ---
,    operator: fail
,  ...
,calling stopBroadcasting
,2015-12-08 03:58:05.092 ThaliTest[439:220274] jxcore: stopBroadcasting
2015-12-08 03:58:05.093 ThaliTest[439:220274] THEMultipeerSession stopping peer
2015-12-08 03:58:05.093 ThaliTest[439:220274] multipeer session: stop timer
2015-12-08 03:58:05.094 Th,aliTest[439:220274] client session: disconnect
2015-12-08 03:58:05.094 ThaliTest[439:220274] client session: stateChange:1->0 1449543444583.391.Wxk+bw==
2015-12-08 03:58:05.095 ThaliTest[439:220274] client session: disconnect
2015-12-08 03:58:05.095 Tha,liTest[439:220274] client session: stateChange:1->0 1449543445467.431.nUNHmA==
2015-12-08 03:58:05.096 ThaliTest[439:220274] server session: disconnect
2015-12-08 03:58:05.096 ThaliTest[439:220274] server session: stateChange:2->0 1449543480460.405
,2015-12-08 03:58:05.099 ThaliTest[439:220274] server session: disconnect
2015-12-08 03:58:05.101 ThaliTest[439:220274] server session: stateChange:2->0 1449543478008.431
,2015-12-08 03:58:05.109 ThaliTest[439:220274] server session: disconnect
2015-12-08 03:58:05.109 ThaliTest[439:220274] server session: stateChange:1->0 1449543477155.391
,2015-12-08 03:58:05.586 ThaliTest[439:220274] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-08 03:58:10.182 ThaliTest[439:220274] jxcore: startBroadcasting
,2015-12-08 03:58:10.186 ThaliTest[439:220274] server: starting 1449543490182.439.HczcmQ==
2015-12-08 03:58:10.187 ThaliTest[439:220274] multipeer session: start timer: 0x1a8d5200
2015-12-08 03:58:10.187 ThaliTest[439:220274] THEMultipeerSession initialized peer 1449543490182.439
2015-12-08 03:58:10.187 ThaliTest[439:220274] jxcore: startBroadcasting: success
ok 116 Should be able to call startBroadcasting without error
echo server started
,2015-12-08 03:58:11.363 ThaliTest[439:220047] client: found peer: 1449543491366.405.MuCjBg==
[{"peerIdentifier":"1449543491366.405.MuCjBg==","peerName":"(null)","peerAvailable":true}]
2015-12-08 03:58:11.366 ThaliTest[439:220274] jxcore: connect 14495434,91366.405.MuCjBg==
2015-12-08 03:58:11.367 ThaliTest[439:220274] client session: connect
2015-12-08 03:58:11.367 ThaliTest[439:220274] client session: stateChange:0->1 1449543491366.405.MuCjBg==
,2015-12-08 03:58:11.427 ThaliTest[439:220047] client: found peer: 1449543489999.431.1e3a9w==
[{"peerIdentifier":"1449543489999.431.1e3a9w==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 03:58:11.430 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:11.431 ThaliTest[439:220274] client session: connect
2015-12-08 03:58:11.431 ThaliTest[439:220274] client session: stateChange:0->1 1449543489999.431.1e3a9w==
,2015-12-08 03:58:11.457 ThaliTest[439:220047] client: found peer: 1449543489757.391.iXbQJw==
[{"peerIdentifier":"1449543489757.391.iXbQJw==","peerName":"(null)","peerAvailable":true}]
2015-12-08 03:58:11.459 ThaliTest[439:220274] jxcore: connect 14495434,89757.391.iXbQJw==
2015-12-08 03:58:11.459 ThaliTest[439:220274] client session: connect
2015-12-08 03:58:11.460 ThaliTest[439:220274] client session: stateChange:0->1 1449543489757.391.iXbQJw==
,2015-12-08 03:58:12.022 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:58:12.024 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:58:12.024 ThaliTest[439:220047] multipeer session: start timer: 0x1a8d5200
2015-12-08 03:58:12.024 ThaliTest[439:220047] server session: connect
2015-12-08 03:58:12.025 ThaliTest[439:220047] server session: stateChange:0->1 1449543489757.391
,2015-12-08 03:58:12.035 ThaliTest[439:220047] server: accepting invitation 1449543489757.391
,2015-12-08 03:58:12.124 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:58:12.124 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:58:12.124 ThaliTest[439:220047] multipeer session: start timer: 0x1a8d5200
2015-12-08 03:58:12.124 ThaliTest[439:220047] server session: connect
2015-12-08 03:58:12.126 ThaliTest[439:220047] server session: stateChange:0->1 1449543489999.431
2015-12-08 03:58:12.136 ThaliTest[439:220047] server: accepting invitation 1449543489999.431
,2015-12-08 03:58:13.287 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:58:13.288 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:58:13.288 ThaliTest[439:220047] multipeer session: start timer: 0x1a8d5200
,2015-12-08 03:58:13.289 ThaliTest[439:220047] server session: connect
2015-12-08 03:58:13.290 ThaliTest[439:220047] server session: stateChange:0->1 1449543491366.405
,2015-12-08 03:58:13.300 ThaliTest[439:220047] server: accepting invitation 1449543491366.405
,2015-12-08 03:58:15.119 ThaliTest[439:220756] client session: connected
2015-12-08 03:58:15.119 ThaliTest[439:220756] client session: stateChange:1->2 1449543491366.405.MuCjBg==
,2015-12-08 03:58:15.178 ThaliTest[439:220761] client session: fireConnectCallback: 1449543491366.405.MuCjBg==
2015-12-08 03:58:15.178 ThaliTest[439:220761] jxcore: connect: success
ok 117 Should be able to connect without error
ok 118 Port should be within range
ok 119 First connect should succeed
,2015-12-08 03:58:15.227 ThaliTest[439:220047] client: relay established
,2015-12-08 03:58:15.230 ThaliTest[439:220047] client: new accepted socket: 0x18f7f6e0
,ok 120 the test messages should be equal
,ok 121 First send should succeed
,2015-12-08 03:58:15.296 ThaliTest[439:220047] client: socket closed
2015-12-08 03:58:15.296 ThaliTest[439:220047] client relay: socket disconnected
2015-12-08 03:58:15.296 ThaliTest[439:220047] client relay: 0x18f7f6e0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:15.297 ThaliTest[439:220047] client session: socket closed: 1449543491366.405.MuCjBg==
2015-12-08 03:58:15.,297 ThaliTest[439:220047] client session: onLinkFailure: 1449543491366.405.MuCjBg==
2015-12-08 03:58:15.297 ThaliTest[439:220047] client session: disconnect
2015-12-08 03:58:15.297 ThaliTest[439:220047] client session: stateChange:2->0 1449543491366.405.MuCjBg==
,2015-12-08 03:58:15.341 ThaliTest[439:220764] client session: connected
2015-12-08 03:58:15.341 ThaliTest[439:220764] client session: stateChange:1->2 1449543489999.431.1e3a9w==
2015-12-08 03:58:15.347 ThaliTest[439:220764] client session: fireConnectCal,lback: 1449543489999.431.1e3a9w==
2015-12-08 03:58:15.348 ThaliTest[439:220764] jxcore: connect: success
ok 122 Should be able to connect without error
ok 123 Port should be within range
ok 124 First connect should succeed
,2015-12-08 03:58:15.382 ThaliTest[439:220047] client session: fireConnectionErrorEvent: 1449543491366.405.MuCjBg==
2015-12-08 03:58:15.382 ThaliTest[439:220047] client: relay established
2015-12-08 03:58:15.382 ThaliTest[439:220047] client: new accepted socket: 0x1a8d9ca0
,2015-12-08 03:58:15.385 ThaliTest[439:220274] jxcore: connect 1449543491366.405.MuCjBg==
,2015-12-08 03:58:15.386 ThaliTest[439:220274] client session: connect
2015-12-08 03:58:15.386 ThaliTest[439:220274] client session: stateChange:0->1 1449543491366.405.MuCjBg==
,2015-12-08 03:58:15.393 ThaliTest[439:220274] jxcore: connect 1449543491366.405.MuCjBg==
2015-12-08 03:58:15.393 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543491366.405.MuCjBg==
2015-12-08 03:58:15.394 ThaliTest[439:220274] jxcore: con,nect: fail: Aleady connecting
,2015-12-08 03:58:15.688 ThaliTest[439:220758] server session: connected
2015-12-08 03:58:15.689 ThaliTest[439:220758] server session: stateChange:1->2 1449543489999.431
,2015-12-08 03:58:15.696 ThaliTest[439:220047] server relay: connected (to port: 5001)
,2015-12-08 03:58:16.149 ThaliTest[439:220756] server session: connected
2015-12-08 03:58:16.152 ThaliTest[439:220756] server session: stateChange:1->2 1449543491366.405
,2015-12-08 03:58:16.183 ThaliTest[439:220047] server relay: connected (to port: 5001)
,2015-12-08 03:58:16.277 ThaliTest[439:220756] server session: not connected 1449543489999.431
,2015-12-08 03:58:16.285 ThaliTest[439:220756] server session: not connected 1449543491366.405
,2015-12-08 03:58:16.401 ThaliTest[439:220274] jxcore: connect 1449543491366.405.MuCjBg==
2015-12-08 03:58:16.401 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543491366.405.MuCjBg==
2015-12-08 03:58:16.402 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:16.605 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:58:16.606 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:58:16.606 ThaliTest[439:220047] multipeer session: start timer: 0x1a8d5200
2015-12-08 ,03:58:16.606 ThaliTest[439:220047] server: disconnecting to refresh session (1449543489999.431)
2015-12-08 03:58:16.607 ThaliTest[439:220047] server session: disconnect
2015-12-08 03:58:16.607 ThaliTest[439:220047] server session: stateChange:2->0 1449543489999.431
,2015-12-08 03:58:16.611 ThaliTest[439:220047] server session: connect
2015-12-08 03:58:16.611 ThaliTest[439:220047] server session: stateChange:0->1 1449543489999.431
,2015-12-08 03:58:16.619 ThaliTest[439:220047] server: accepting invitation 1449543489999.431
,ok 125 the test messages should be equal
ok 126 First send should succeed
,2015-12-08 03:58:16.698 ThaliTest[439:220047] client: socket closed
,2015-12-08 03:58:16.699 ThaliTest[439:220047] client relay: socket disconnected
,2015-12-08 03:58:16.701 ThaliTest[439:220047] client relay: 0x1a8d9ca0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-08 03:58:16.703 ThaliTest[439:220047] client session: socket closed: 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.705 ThaliTest[439:220047] client session: onLinkFailure: 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.707 ThaliTest[439:220047] client session: disconnect
,2015-12-08 03:58:16.711 ThaliTest[439:220047] client session: stateChange:2->0 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.737 ThaliTest[439:220047] client session: fireConnectionErrorEvent: 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.739 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.741 ThaliTest[439:220274] client session: connect
,2015-12-08 03:58:16.742 ThaliTest[439:220274] client session: stateChange:0->1 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.858 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:58:16.858 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:58:16.858 ThaliTest[439:220047] multipeer session: start timer: 0x1a8d5200
2015-12-08 03:58:16.858 ThaliTest[439:220047] server: disconnecting to refresh session (1449543491366.405)
2015-12-08 03:58:16.859 ThaliTest[439:220047] server session: disconnect
,2015-12-08 03:58:16.859 ThaliTest[439:220047] server session: stateChange:2->0 1449543491366.405
,2015-12-08 03:58:16.861 ThaliTest[439:220047] server session: connect
2015-12-08 03:58:16.862 ThaliTest[439:220047] server session: stateChange:0->1 1449543491366.405
,2015-12-08 03:58:17.918 ThaliTest[439:220760] client session: connected
,2015-12-08 03:58:17.919 ThaliTest[439:220760] client session: stateChange:1->2 1449543489757.391.iXbQJw==
,2015-12-08 03:58:17.968 ThaliTest[439:220047] server: accepting invitation 1449543491366.405
,2015-12-08 03:58:17.976 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
,2015-12-08 03:58:17.978 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
,2015-12-08 03:58:17.980 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:17.997 ThaliTest[439:220274] jxcore: connect 1449543491366.405.MuCjBg==
2015-12-08 03:58:18.002 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543491366.405.MuCjBg==
2015-12-08 03:58:18.004 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:18.251 ThaliTest[439:220764] client session: fireConnectCallback: 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.252 ThaliTest[439:220764] jxcore: connect: success
ok 127 Should be able to connect without error
ok 128 Port should be within range
ok 129 First connect should succeed
,2015-12-08 03:58:18.268 ThaliTest[439:220047] client: relay established
2015-12-08 03:58:18.268 ThaliTest[439:220047] client: new accepted socket: 0x1a8ba950
,2015-12-08 03:58:18.303 ThaliTest[439:220764] server session: connected
2015-12-08 03:58:18.303 ThaliTest[439:220764] server session: stateChange:1->2 1449543489757.391
2015-12-08 03:58:18.307 ThaliTest[439:220047] server relay: connected (to port: 5001),
,ok 130 the test messages should be equal
,ok 131 First send should succeed
,2015-12-08 03:58:18.396 ThaliTest[439:220047] client: socket closed
2015-12-08 03:58:18.396 ThaliTest[439:220047] client relay: socket disconnected
,2015-12-08 03:58:18.397 ThaliTest[439:220047] client relay: 0x1a8ba950 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:18.397 ThaliTest[439:220047] client session: socket closed: 1449543489757.391.iXbQJw==
2015-12-08 03:58:18.397 ThaliTest[439:220047] client session: onLinkFailure: 1449543489757.391.iXbQJw==
2015-12-08 03:58:18.397 ThaliTest[439:220047] client session: disconnect
,2015-12-08 03:58:18.397 ThaliTest[439:220047] client session: stateChange:2->0 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.404 ThaliTest[439:220047] client session: fireConnectionErrorEvent: 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.406 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.407 ThaliTest[439:220274] client session: connect
,2015-12-08 03:58:18.407 ThaliTest[439:220274] client session: stateChange:0->1 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.417 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.417 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.417 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:18.422 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.424 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:18.427 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:18.719 ThaliTest[439:220760] server session: not connected 1449543489757.391
,2015-12-08 03:58:18.836 ThaliTest[439:220760] client session: connected
,2015-12-08 03:58:18.836 ThaliTest[439:220760] client session: stateChange:1->2 1449543491366.405.MuCjBg==
,2015-12-08 03:58:18.850 ThaliTest[439:220760] client session: fireConnectCallback: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:18.850 ThaliTest[439:220760] jxcore: connect: success
,ok 132 Should be able to connect without error
,ok 133 Port should be within range
,ok 134 Second connect should succeed
,2015-12-08 03:58:18.886 ThaliTest[439:220047] client: relay established
2015-12-08 03:58:18.886 ThaliTest[439:220047] client: new accepted socket: 0x18f532d0
,2015-12-08 03:58:18.897 ThaliTest[439:220047] multipeer session: reset timer
,2015-12-08 03:58:18.897 ThaliTest[439:220047] multipeer session: stop timer
,2015-12-08 03:58:18.898 ThaliTest[439:220047] multipeer session: start timer: 0x1a8d5200
,2015-12-08 03:58:18.898 ThaliTest[439:220047] server: disconnecting to refresh session (1449543489757.391)
,2015-12-08 03:58:18.899 ThaliTest[439:220047] server session: disconnect
,2015-12-08 03:58:18.899 ThaliTest[439:220047] server session: stateChange:2->0 1449543489757.391
,2015-12-08 03:58:18.903 ThaliTest[439:220047] server session: connect
,2015-12-08 03:58:18.904 ThaliTest[439:220047] server session: stateChange:0->1 1449543489757.391
,2015-12-08 03:58:18.923 ThaliTest[439:220047] server: accepting invitation 1449543489757.391
,ok 135 the test messages should be equal
,ok 136 Second send should succeed
,# setup
,2015-12-08 03:58:18.972 ThaliTest[439:220047] client: socket closed
2015-12-08 03:58:18.972 ThaliTest[439:220047] client relay: socket disconnected
2015-12-08 03:58:18.973 ThaliTest[439:220047] client relay: 0x18f532d0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:18.973 ThaliTest[439:220047] client session: socket closed: 1449543491366.405.MuCjBg==
2015-12-08 03:58:18.,973 ThaliTest[439:220047] client session: onLinkFailure: 1449543491366.405.MuCjBg==
2015-12-08 03:58:18.973 ThaliTest[439:220047] client session: disconnect
2015-12-08 03:58:18.973 ThaliTest[439:220047] client session: stateChange:2->0 1449543491366.405.MuCjBg==
,2015-12-08 03:58:18.983 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
,2015-12-08 03:58:18.984 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
,2015-12-08 03:58:18.985 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:18.997 ThaliTest[439:220047] client session: fireConnectionErrorEvent: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:19.013 ThaliTest[439:220274] jxcore: connect 1449543491366.405.MuCjBg==
,2015-12-08 03:58:19.015 ThaliTest[439:220274] client session: connect
,2015-12-08 03:58:19.017 ThaliTest[439:220274] client session: stateChange:0->1 1449543491366.405.MuCjBg==
,2015-12-08 03:58:19.612 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:19.613 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:19.613 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:19.614 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:19.615 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:19.615 ThaliTest[439:220274] jxcore: con,nect: fail: Aleady connecting
,2015-12-08 03:58:19.988 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:19.989 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
2015-12-08 03:58:19.989 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:20.621 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:20.622 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:20.622 ThaliTest[439:220274] jxcore: con,nect: fail: Aleady connecting
2015-12-08 03:58:20.623 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:20.623 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:20.624 Th,aliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:20.919 ThaliTest[439:220766] server session: connected
,2015-12-08 03:58:20.920 ThaliTest[439:220766] server session: stateChange:1->2 1449543491366.405
,2015-12-08 03:58:20.994 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:20.994 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
,2015-12-08 03:58:20.995 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:21.052 ThaliTest[439:220047] server relay: connected (to port: 5001)
,2015-12-08 03:58:21.362 ThaliTest[439:220760] server session: not connected 1449543491366.405
,2015-12-08 03:58:21.436 ThaliTest[439:220760] server session: connected
2015-12-08 03:58:21.436 ThaliTest[439:220760] server session: stateChange:1->2 1449543489999.431
,2015-12-08 03:58:21.445 ThaliTest[439:220047] server relay: connected (to port: 5001)
,2015-12-08 03:58:21.626 ThaliTest[439:220758] server session: not connected 1449543489999.431
,2015-12-08 03:58:21.632 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:21.632 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:21.633 ThaliTest[439:220274] jxcore: con,nect: fail: Aleady connecting
2015-12-08 03:58:21.633 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:21.634 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:21.634 Th,aliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:21.912 ThaliTest[439:220760] client session: connected
,2015-12-08 03:58:21.914 ThaliTest[439:220760] client session: stateChange:1->2 1449543489999.431.1e3a9w==
,2015-12-08 03:58:21.921 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:58:21.921 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:58:21.922 ThaliTest[439:220047] multipeer session: start timer: 0x1a8d5200
2015-12-08 ,03:58:21.922 ThaliTest[439:220047] server: disconnecting to refresh session (1449543491366.405)
2015-12-08 03:58:21.922 ThaliTest[439:220047] server session: disconnect
2015-12-08 03:58:21.923 ThaliTest[439:220047] server session: stateChange:2->0 1449543491366.405
,2015-12-08 03:58:21.925 ThaliTest[439:220760] client session: fireConnectCallback: 1449543489999.431.1e3a9w==
,2015-12-08 03:58:21.926 ThaliTest[439:220760] jxcore: connect: success
,ok 137 Should be able to connect without error
,ok 138 Port should be within range
,ok 139 Second connect should succeed
,2015-12-08 03:58:21.997 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
,2015-12-08 03:58:21.999 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
,2015-12-08 03:58:22.000 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:22.637 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:22.638 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:22.638 ThaliTest[439:220274] jxcore: con,nect: fail: Aleady connecting
2015-12-08 03:58:22.639 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:22.639 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:22.640 Th,aliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:22.645 ThaliTest[439:220047] server session: connect
,2015-12-08 03:58:22.646 ThaliTest[439:220047] server session: stateChange:0->1 1449543491366.405
,2015-12-08 03:58:22.658 ThaliTest[439:220047] server: accepting invitation 1449543491366.405
2015-12-08 03:58:22.658 ThaliTest[439:220047] client: relay established
2015-12-08 03:58:22.658 ThaliTest[439:220047] client: new accepted socket: 0x1a8e1fc0
,2015-12-08 03:58:22.896 ThaliTest[439:220047] multipeer session: reset timer
2015-12-08 03:58:22.896 ThaliTest[439:220047] multipeer session: stop timer
2015-12-08 03:58:22.896 ThaliTest[439:220047] multipeer session: start timer: 0x1a8d5200
2015-12-08 03:58:22.896 ThaliTest[439:220047] server: disconnecting to refresh session (1449543489999.431)
2015-12-08 03:58:22.896 ThaliTest[439:220047] server session: disconnect
2015-12-08 03:58:22.896 ThaliTest[439:220047] server session: stateChange:2->0 1449543489999.431
,2015-12-08 03:58:23.003 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:23.003 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
2015-12-08 03:58:23.003 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:23.165 ThaliTest[439:220047] server session: connect
2015-12-08 03:58:23.166 ThaliTest[439:220047] server session: stateChange:0->1 1449543489999.431
,2015-12-08 03:58:23.172 ThaliTest[439:220047] server: accepting invitation 1449543489999.431
,ok 140 the test messages should be equal
ok 141 Second send should succeed
not ok 142 .end() called twice
  ---
    operator: fail
  ...
,2015-12-08 03:58:23.195 ThaliTest[439:220047] client: socket closed
2015-12-08 03:58:23.195 ThaliTest[439:220047] client relay: socket disconnected
,2015-12-08 03:58:23.196 ThaliTest[439:220047] client relay: 0x1a8e1fc0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:23,.196 ThaliTest[439:220047] client session: socket closed: 1449543489999.431.1e3a9w==
2015-12-08 03:58:23.197 ThaliTest[439:220047] client session: onLinkFailure: 1449543489999.431.1e3a9w==
2015-12-08 03:58:23.197 ThaliTest[439:220047] client session: disconnect
2015-12-08 03:58:23.197 ThaliTest[439:220047] client session: stateChange:2->0 1449543489999.431.1e3a9w==
,2015-12-08 03:58:23.211 ThaliTest[439:220047] client session: fireConnectionErrorEvent: 1449543489999.431.1e3a9w==
,2015-12-08 03:58:23.421 ThaliTest[439:220761] server session: connected
2015-12-08 03:58:23.421 ThaliTest[439:220761] server session: stateChange:1->2 1449543489757.391
,2015-12-08 03:58:23.425 ThaliTest[439:220047] server relay: connected (to port: 5001)
,2015-12-08 03:58:23.450 ThaliTest[439:220766] client session: connected
2015-12-08 03:58:23.451 ThaliTest[439:220766] client session: stateChange:1->2 1449543491366.405.MuCjBg==
,2015-12-08 03:58:23.460 ThaliTest[439:220760] client session: fireConnectCallback: 1449543491366.405.MuCjBg==
2015-12-08 03:58:23.460 ThaliTest[439:220760] jxcore: connect: success
ok 143 Should be able to connect without error
ok 144 Port should be within range
ok 145 Second connect should succeed
,2015-12-08 03:58:23.472 ThaliTest[439:220047] client: relay established
2015-12-08 03:58:23.472 ThaliTest[439:220047] client: new accepted socket: 0x1a8071b0
,ok 146 the test messages should be equal
,ok 147 Second send should succeed
,not ok 148 .end() called twice
,  ---
    operator: fail
,  ...
,2015-12-08 03:58:23.539 ThaliTest[439:220047] client: socket closed
2015-12-08 03:58:23.540 ThaliTest[439:220047] client relay: socket disconnected
,2015-12-08 03:58:23.540 ThaliTest[439:220047] client relay: 0x1a8071b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:23,.540 ThaliTest[439:220047] client session: socket closed: 1449543491366.405.MuCjBg==
2015-12-08 03:58:23.540 ThaliTest[439:220047] client session: onLinkFailure: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:23.541 ThaliTest[439:220047] client session: disconnect
2015-12-08 03:58:23.541 ThaliTest[439:220047] client session: stateChange:2->0 1449543491366.405.MuCjBg==
,2015-12-08 03:58:23.554 ThaliTest[439:220047] client session: fireConnectionErrorEvent: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:23.593 ThaliTest[439:220756] client session: connected
,2015-12-08 03:58:23.593 ThaliTest[439:220756] client session: stateChange:1->2 1449543489757.391.iXbQJw==
,2015-12-08 03:58:23.603 ThaliTest[439:220760] client session: fireConnectCallback: 1449543489757.391.iXbQJw==
2015-12-08 03:58:23.603 ThaliTest[439:220760] jxcore: connect: success
,ok 149 Should be able to connect without error
,ok 150 Port should be within range
,ok 151 Second connect should succeed
,2015-12-08 03:58:23.621 ThaliTest[439:220047] client: relay established
2015-12-08 03:58:23.621 ThaliTest[439:220047] client: new accepted socket: 0x1a8b5ee0
,2015-12-08 03:58:23.647 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:23.647 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:23.647 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
2015-12-08 03:58:23.648 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:23.648 ThaliTest[439:220274] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:23.648 ThaliTest[439:220274] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:23.666 ThaliTest[439:220766] server session: not connected 1449543489757.391
,calling stopBroadcasting
,2015-12-08 03:58:23.924 ThaliTest[439:220274] jxcore: stopBroadcasting
2015-12-08 03:58:23.925 ThaliTest[439:220274] THEMultipeerSession stopping peer
2015-12-08 03:58:23.925 ThaliTest[439:220274] multipeer session: stop timer
2015-12-08 03:58:23.925 Th,aliTest[439:220274] client session: disconnect
2015-12-08 03:58:23.926 ThaliTest[439:220274] client session: stateChange:2->0 1449543489757.391.iXbQJw==
,2015-12-08 03:58:23.961 ThaliTest[439:220274] server session: disconnect
2015-12-08 03:58:23.963 ThaliTest[439:220274] server session: stateChange:1->0 1449543491366.405
,2015-12-08 03:58:24.075 ThaliTest[439:220274] server session: disconnect
,2015-12-08 03:58:24.076 ThaliTest[439:220274] server session: stateChange:1->0 1449543489999.431
,2015-12-08 03:58:24.163 ThaliTest[439:220274] server session: disconnect
,2015-12-08 03:58:24.164 ThaliTest[439:220274] server session: stateChange:2->0 1449543489757.391
,2015-12-08 03:58:24.955 ThaliTest[439:220274] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,2015-12-08 03:58:24.972 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:24.973 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:24.973 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
2,015-12-08 03:58:24.974 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:24.974 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:24.975 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:24.976 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:24.977 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:24.977 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:25.982 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:25.983 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:25.983 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
2,015-12-08 03:58:25.984 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:25.985 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:25.985 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
20,15-12-08 03:58:25.986 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:25.986 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:25.986 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:26.985 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:26.986 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:26.986 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
2,015-12-08 03:58:26.987 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:26.987 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:26.988 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
20,15-12-08 03:58:26.988 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:26.989 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:26.989 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:27.998 ThaliTest[439:220274] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:27.998 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:27.999 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
2,015-12-08 03:58:28.000 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:28.000 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:28.000 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
20,15-12-08 03:58:28.001 ThaliTest[439:220274] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:28.002 ThaliTest[439:220274] Communications not enabled
2015-12-08 03:58:28.002 ThaliTest[439:220274] jxcore: connect: fail: app: Not initialised
,not ok 152 Second connect should succeed
  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,not ok 153 Second connect should succeed
  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,not ok 154 Second connect should succeed
  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,2015-12-08 03:58:29.121 ThaliTest[439:220274] Error!: connect EADDRNOTAVAIL
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_functionName":"connect","_lineNumber":"707","_columnNumber":"19","_msg":"    at connect@net.js:707:19"},{"_fileName":"net.js","_functionName":"Socket.prototype.connect","_lineNumber":"756","_columnNumber":"5","_msg":"    at Socket.prototype.connect@net.js:756:5"},{"_fileName":"net.js","_functionName":"exports.createConnection","_lineNumber":"72","_columnNumber":"10","_msg":"    at exports.createConnection@net.js:72:10"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"sendData","_lineNumber":"277","_columnNumber":"24","_msg":"    at sendData@/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"325","_columnNumber":"17","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer","_lineNumber":"251","_columnNumber":"9","_msg":"    at connectWithRetry/connectToPeer@/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer/</<","_lineNumber":"260","_columnNumber":"45","_msg":"    at connectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45"},{"_fileName":"timers.js","_functionName":"listOnTimeout","_lineNumber":"112","_columnNumber":"9","_msg":"    at listOnTimeout@timers.js:112:9"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":835,"_columnNumber":10,"_msg":"    at "}]
Uncaught Exception: Error: connect EADDRNOTAVAIL
,[ { _fileName: 'net.js',
    _functionName: 'errnoException',
    _lineNumber: '835',
    _columnNumber: '11',
    _msg: '    at errnoException@net.js:835:11' },
  { _fileName: 'net.js',
    _functionName: 'connect',
    _lineNumber: '707',
    _co,lumnNumber: '19',
    _msg: '    at connect@net.js:707:19' },
  { _fileName: 'net.js',
    _functionName: 'Socket.prototype.connect',
    _lineNumber: '756',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.connect@net.js:756:5' },
  { _fi,leName: 'net.js',
    _functionName: 'exports.createConnection',
    _lineNumber: '72',
    _columnNumber: '10',
    _msg: '    at exports.createConnection@net.js:72:10' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/D183E64C-5C7,3-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'sendData',
    _lineNumber: '277',
    _columnNumber: '24',
    _msg: '    at sendData@/private/var/mobile/Containers/Bundle/Application/D183E64C-5,C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.j,s',
    _functionName: '',
    _lineNumber: '325',
    _columnNumber: '17',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17' },
,  { _fileName: '/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer',
    _lineNumber: '251',
    _columnNu,mber: '9',
    _msg: '    at connectWithRetry/connectToPeer@/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9' },
  { _fileName: '/private/var/mobile/Con,tainers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer/</<',
    _lineNumber: '260',
    _columnNumber: '45',
    _msg: '    at conn,ectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/D183E64C-5C73-4315-B2A9-44AA1D554399/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45' },
  { _fileName: 'timers.js',
    _functionName: 'listOnTimeout',
  ,  _lineNumber: '112',
    _columnNumber: '9',
    _msg: '    at listOnTimeout@timers.js:112:9' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber: 835,
    _columnNumber: 10,
    _msg: '    at ' },
  toString: [Function] ]
*,***TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
