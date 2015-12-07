#### Test 5065027860d2bae_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/60ADE464-AC1E-4CAC-9EB7-3894D0AF0A8D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/60ADE464-AC1E-4CAC-9EB7-3894D0AF0A8D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50340"
,(lldb)     command script import "/tmp/60ADE464-AC1E-4CAC-9EB7-3894D0AF0A8D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 18:47:01.154 ThaliTest[416:167996] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/475EB9BB-65E6-4975-BCF6-73E1E9D3071C/Library/Cookies/Cookies.binarycookies
,2015-12-07 18:47:01.487 ThaliTest[416:167996] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 18:47:01.488 ThaliTest[416:167996] Multi-tasking -> Device: YES, App: YES
,2015-12-07 18:47:01.497 ThaliTest[416:167996] Unlimited access to network resources
,2015-12-07 18:47:01.506 ThaliTest[416:167996] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 18:47:10.495 ThaliTest[416:167996] Resetting plugins due to page load.
,2015-12-07 18:47:13.543 ThaliTest[416:167996] Finished load of: file:///var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/index.html
,2015-12-07 18:47:13.726 ThaliTest[416:167996] JXcore Cordova plugin initializing
2015-12-07 18:47:13.727 ThaliTest[416:168220] JXcore instance initializing
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
,2015-12-07 18:47:36.946 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:37.217 ThaliTest[416:168220] server: starting 1449510456946.416.ZUQUaQ==
,2015-12-07 18:47:37.218 ThaliTest[416:168220] multipeer session: start timer: 0x18eb4f40
2015-12-07 18:47:37.220 ThaliTest[416:168220] THEMultipeerSession initialized peer 1449510456946.416
2015-12-07 18:47:37.220 ThaliTest[416:168220] jxcore: startBroad,casting: success
ok 45 Should be able to call startBroadcasting without error
2015-12-07 18:47:37.224 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:47:37.224 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:37.225, ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:47:37.225 ThaliTest[416:168220] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.232 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:37.265 ThaliTest[416:168220] server: starting 1449510457230.416.+z0kKg==
2015-12-07 18:47:37.266 ThaliTest[416:168220] multipeer session: start timer: 0x18eb8050
2015-12-07 18:47:37.266 ThaliTest[416:168220] THEMultipeerSession initializ,ed peer 1449510457230.416
2015-12-07 18:47:37.267 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-07 18:47:37.269 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18,:47:37.269 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:37.270 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:47:37.270 ThaliTest[416:168220] jxcore: stopBroadcasting: success
ok 48 Should be able to call s,topBroadcasting without error
2015-12-07 18:47:37.272 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:37.280 ThaliTest[416:168220] server: starting 1449510457272.416.85J4nA==
2015-12-07 18:47:37.280 ThaliTest[416:168220] multipeer session: start timer: 0x18eb9270
2015-12-07 18:47:37.280 ThaliTest[416:168220] THEMultipeerSession initializ,ed peer 1449510457272.416
2015-12-07 18:47:37.281 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2015-12-07 18:47:37.282 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18,:47:37.282 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:37.282 ThaliTest[416:168220] multipeer session: stop timer
,2015-12-07 18:47:37.283 ThaliTest[416:168220] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
2015-12-07 18:47:37.285 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:37.294 ThaliTest[416:168220] server: starting 1449510457284.416.ad/Zwg==
2015-12-07 18:47:37.295 ThaliTest[416:168220] multipeer session: start timer: 0x18eba000
2015-12-07 18:47:37.296 ThaliTest[416:168220] THEMultipeerSession initializ,ed peer 1449510457284.416
2015-12-07 18:47:37.296 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-07 18:47:37.298 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18,:47:37.298 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:37.298 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:47:37.299 ThaliTest[416:168220] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.300 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:37.305 ThaliTest[416:168220] server: starting 1449510457299.416.Bie1tw==
2015-12-07 18:47:37.305 ThaliTest[416:168220] multipeer session: start timer: 0x18eba000
2015-12-07 18:47:37.305 ThaliTest[416:168220] THEMultipeerSession initializ,ed peer 1449510457299.416
2015-12-07 18:47:37.307 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2015-12-07 18:47:37.308 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18,:47:37.308 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:37.308 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:47:37.308 ThaliTest[416:168220] jxcore: stopBroadcasting: success
ok 54 Should be able to call s,topBroadcasting without error
2015-12-07 18:47:37.309 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:37.313 ThaliTest[416:168220] server: starting 1449510457309.416.I8yoGg==
2015-12-07 18:47:37.313 ThaliTest[416:168220] multipeer session: start timer: 0x18ebd6c0
2015-12-07 18:47:37.313 ThaliTest[416:168220] THEMultipeerSession initialized peer 1449510457309.416
2015-12-07 18:47:37.314 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2015-12-07 18:47:37.315 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18,:47:37.315 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:37.315 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:47:37.315 ThaliTest[416:168220] jxcore: stopBroadcasting: success
ok 56 Should be able to call s,topBroadcasting without error
2015-12-07 18:47:37.316 ThaliTest[416:168220] jxcore: startBroadcasting
2015-12-07 18:47:37.317 ThaliTest[416:168220] server: starting 1449510457316.416.JfB2aA==
2015-12-07 18:47:37.317 ThaliTest[416:168220] multipeer sessi,on: start timer: 0x18ebf1d0
2015-12-07 18:47:37.320 ThaliTest[416:168220] THEMultipeerSession initialized peer 1449510457316.416
2015-12-07 18:47:37.320 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcast,ing without error
2015-12-07 18:47:37.321 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:47:37.321 ThaliTest[416:168220] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.321 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:47:37.323 ThaliTest[416:168220] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2015-12-07 18:47:37.324 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:37.327 ThaliTest[416:168220] server: starting 1449510457324.416.UKCfFg==
,2015-12-07 18:47:37.331 ThaliTest[416:168220] multipeer session: start timer: 0x1a88ef80
2015-12-07 18:47:37.331 ThaliTest[416:168220] THEMultipeerSession initialized peer 1449510457324.416
2015-12-07 18:47:37.331 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
2015-12-07 18:47:37.332 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:47:37.332 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:37.332, ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:47:37.332 ThaliTest[416:168220] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2015-12-07 18:47:37.333 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:37.336 ThaliTest[416:168220] server: starting 1449510457333.416.9RvTFA==
2015-12-07 18:47:37.336 ThaliTest[416:168220] multipeer session: start timer: 0x18ec13c0
2015-12-07 18:47:37.336 ThaliTest[416:168220] THEMultipeerSession initializ,ed peer 1449510457333.416
2015-12-07 18:47:37.336 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.340 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:47:37.340 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:37.340 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:47:37.340 ThaliTest[416:168220] jxcore: stopBroadcasting: success
ok 62 Should be able to call stopBroadcasting without error
2015-12-07 18:47:37.341 ThaliTest[416:168220] jxcore: startBroadcasting
2015-12-07 18:47:37.343 ThaliTest[416:168220] server: starting 1449,510457341.416.pvpr/w==
2015-12-07 18:47:37.343 ThaliTest[416:168220] multipeer session: start timer: 0x18ec0740
,2015-12-07 18:47:37.343 ThaliTest[416:168220] THEMultipeerSession initialized peer 1449510457341.416
,2015-12-07 18:47:37.346 ThaliTest[416:168220] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.351 ThaliTest[416:168220] jxcore: stopBroadcasting
,2015-12-07 18:47:37.351 ThaliTest[416:168220] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.352 ThaliTest[416:168220] multipeer session: stop timer
,2015-12-07 18:47:37.352 ThaliTest[416:168220] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-07 18:47:38.092 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:38.096 ThaliTest[416:168220] server: starting 1449510458092.416.opQS0Q==
2015-12-07 18:47:38.097 ThaliTest[416:168220] multipeer session: start timer: 0x1a88e750
2015-12-07 18:47:38.097 ThaliTest[416:168220] THEMultipeerSession initializ,ed peer 1449510458092.416
2015-12-07 18:47:38.097 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2015-12-07 18:47:38.100 ThaliTest[416:168220] jxcore: startBroadcasting
2015-12-07 1,8:47:38.100 ThaliTest[416:168220] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2015-12-07 18:47:38.102 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:47:38.103 ThaliTest[416:168220] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.103 ThaliTest[416:168220] multipeer session: stop timer
,2015-12-07 18:47:38.104 ThaliTest[416:168220] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-07 18:47:41.175 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:41.180 ThaliTest[416:168220] server: starting 1449510461175.416.0UaNhA==
2015-12-07 18:47:41.180 ThaliTest[416:168220] multipeer session: start timer: 0x18ec2570
2015-12-07 18:47:41.181 ThaliTest[416:168220] THEMultipeerSession initializ,ed peer 1449510461175.416
2015-12-07 18:47:41.182 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-07 18:47:41.185 ThaliTest[416:168220] jxcore: connect foobar
2015-12-07 18:47:41.185 ThaliTest[416:168220] client: unknown peer foobar
,2015-12-07 18:47:41.185 ThaliTest[416:168220] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2015-12-07 18:47:41.193 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:47:41.197 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:41.198 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:47:41.198 ThaliTest[416:168220] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-07 18:47:44.589 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:44.592 ThaliTest[416:168220] server: starting 1449510464588.416.sK8aLg==
2015-12-07 18:47:44.593 ThaliTest[416:168220] multipeer session: start timer: 0x1a8927d0
2015-12-07 18:47:44.594 ThaliTest[416:168220] THEMultipeerSession initializ,ed peer 1449510464588.416
2015-12-07 18:47:44.594 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-07 18:47:44.596 ThaliTest[416:168220] jxcore: disconnect
2015-12-07 18:47:44,.597 ThaliTest[416:168220] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2015-12-07 18:47:44.599 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:47:44.599 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:44.600 ThaliTest[416:168220] multipeer session: stop timer
,2015-12-07 18:47:44.601 ThaliTest[416:168220] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-07 18:47:48.489 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:48.493 ThaliTest[416:168220] server: starting 1449510468488.416.gJkiTg==
2015-12-07 18:47:48.494 ThaliTest[416:168220] multipeer session: start timer: 0x1a894950
2015-12-07 18:47:48.495 ThaliTest[416:168220] THEMultipeerSession initialized peer 1449510468488.416
2015-12-07 18:47:48.495 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2015-12-07 18:47:49.698 ThaliTest[416:167996] client: found peer: 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:49.701 ThaliTest[416:168220] jxcore: connect 1449510469411.383.Wmi/Ew==
2015-12-07 18:47:49.702 ThaliTest[416:168220] client session: connect
2015-12-07 18:47:49.702 ThaliTest[416:168220] client session: stateChange:0->1 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:49.920 ThaliTest[416:167996] client: found peer: 1449510468177.375.Xvfalg==
2015-12-07 18:47:49.922 ThaliTest[416:168220] jxcore: connect 1449510468177.375.Xvfalg==
2015-12-07 18:47:49.922 ThaliTest[416:168220] client session: connect
2015-12-07 18:47:49.923 ThaliTest[416:168220] client session: stateChange:0->1 1449510468177.375.Xvfalg==
,2015-12-07 18:47:49.978 ThaliTest[416:167996] client: found peer: 1449510468363.408.sJcxPg==
2015-12-07 18:47:49.980 ThaliTest[416:168220] jxcore: connect 1449510468363.408.sJcxPg==
,2015-12-07 18:47:49.980 ThaliTest[416:168220] client session: connect
2015-12-07 18:47:49.981 ThaliTest[416:168220] client session: stateChange:0->1 1449510468363.408.sJcxPg==
,2015-12-07 18:47:50.092 ThaliTest[416:167996] multipeer session: reset timer
,2015-12-07 18:47:50.092 ThaliTest[416:167996] multipeer session: stop timer
,2015-12-07 18:47:50.094 ThaliTest[416:167996] multipeer session: start timer: 0x1a894950
,2015-12-07 18:47:50.095 ThaliTest[416:167996] server session: connect
,2015-12-07 18:47:50.096 ThaliTest[416:167996] server session: stateChange:0->1 1449510468177.375
,2015-12-07 18:47:50.112 ThaliTest[416:167996] server: accepting invitation 1449510468177.375
,2015-12-07 18:47:50.351 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:47:50.351 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:47:50.352 ThaliTest[416:167996] multipeer session: start timer: 0x1a894950
2015-12-07 ,18:47:50.352 ThaliTest[416:167996] server session: connect
2015-12-07 18:47:50.352 ThaliTest[416:167996] server session: stateChange:0->1 1449510468363.408
,2015-12-07 18:47:50.358 ThaliTest[416:167996] server: accepting invitation 1449510468363.408
,2015-12-07 18:47:50.876 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:47:50.876 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:47:50.877 ThaliTest[416:167996] multipeer session: start timer: 0x1a894950
2015-12-07 18:47:50.877 ThaliTest[416:167996] server session: connect
2015-12-07 18:47:50.877 ThaliTest[416:167996] server session: stateChange:0->1 1449510469411.383
,2015-12-07 18:47:50.883 ThaliTest[416:167996] server: accepting invitation 1449510469411.383
,2015-12-07 18:47:52.932 ThaliTest[416:168070] client session: connected
2015-12-07 18:47:52.932 ThaliTest[416:168070] client session: stateChange:1->2 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:52.961 ThaliTest[416:168070] client session: fireConnectCallback: 1449510469411.383.Wmi/Ew==
2015-12-07 18:47:52.961 ThaliTest[416:168070] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-07 18:47:52.967 ThaliTest[416:168220] jxcore: disconnect
2015-12-07 18:47:52.967 ThaliTest[416:168220] client session: disconnectFromPeer: 1449510469411.383.Wmi/Ew==
2015-12-07 18:47:52.968 ThaliTest[416:168220] client session: disconnect
2015-1,2-07 18:47:52.968 ThaliTest[416:168220] client session: stateChange:2->0 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:52.984 ThaliTest[416:168220] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-07 18:47:53.494 ThaliTest[416:168070] server session: connected
,2015-12-07 18:47:53.495 ThaliTest[416:168070] server session: stateChange:1->2 1449510468363.408
,2015-12-07 18:47:53.523 ThaliTest[416:168263] server session: connected
2015-12-07 18:47:53.523 ThaliTest[416:168263] server session: stateChange:1->2 1449510469411.383
,2015-12-07 18:47:53.545 ThaliTest[416:167996] server relay: socket disconnected
,2015-12-07 18:47:53.546 ThaliTest[416:167996] server relay: 0x1a8b0030 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:53.558 ThaliTest[416:167996] server relay: socket disconnected
,2015-12-07 18:47:53.559 ThaliTest[416:167996] server relay: 0x18ee48c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:53.570 ThaliTest[416:168282] server session: connected
,2015-12-07 18:47:53.570 ThaliTest[416:168282] server session: stateChange:1->2 1449510468177.375
,2015-12-07 18:47:53.603 ThaliTest[416:168282] server session: not connected 1449510469411.383
,2015-12-07 18:47:53.608 ThaliTest[416:167996] server relay: socket disconnected
,2015-12-07 18:47:53.609 ThaliTest[416:167996] server relay: 0x1a8a12a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection re,fused} 
,2015-12-07 18:47:53.622 ThaliTest[416:168263] server session: not connected 1449510468177.375
,2015-12-07 18:47:53.704 ThaliTest[416:168263] client session: connected
,2015-12-07 18:47:53.705 ThaliTest[416:168263] client session: stateChange:1->2 1449510468177.375.Xvfalg==
,2015-12-07 18:47:53.735 ThaliTest[416:168263] client session: fireConnectCallback: 1449510468177.375.Xvfalg==
,2015-12-07 18:47:53.735 ThaliTest[416:168263] jxcore: connect: success
,ok 78 Should be able to connect without error
,ok 79 Port should be within range
,2015-12-07 18:47:53.740 ThaliTest[416:168220] jxcore: disconnect
,2015-12-07 18:47:53.740 ThaliTest[416:168220] client session: disconnectFromPeer: 1449510468177.375.Xvfalg==
,2015-12-07 18:47:53.742 ThaliTest[416:168220] client session: disconnect
,2015-12-07 18:47:53.743 ThaliTest[416:168220] client session: stateChange:2->0 1449510468177.375.Xvfalg==
,2015-12-07 18:47:53.758 ThaliTest[416:168263] client session: connected
,2015-12-07 18:47:53.759 ThaliTest[416:168263] client session: stateChange:1->2 1449510468363.408.sJcxPg==
,2015-12-07 18:47:53.763 ThaliTest[416:168220] jxcore: disconnect: success
ok 80 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,not ok 81 .end() called twice
,  ---
    operator: fail
  ...
,2015-12-07 18:47:53.800 ThaliTest[416:168263] client session: fireConnectCallback: 1449510468363.408.sJcxPg==
2015-12-07 18:47:53.800 ThaliTest[416:168263] jxcore: connect: success
,ok 82 Should be able to connect without error
,ok 83 Port should be within range
,2015-12-07 18:47:53.805 ThaliTest[416:168220] jxcore: disconnect
,2015-12-07 18:47:53.805 ThaliTest[416:168220] client session: disconnectFromPeer: 1449510468363.408.sJcxPg==
,2015-12-07 18:47:53.805 ThaliTest[416:168220] client session: disconnect
,2015-12-07 18:47:53.806 ThaliTest[416:168220] client session: stateChange:2->0 1449510468363.408.sJcxPg==
,2015-12-07 18:47:53.813 ThaliTest[416:168220] jxcore: disconnect: success
,ok 84 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,not ok 85 .end() called twice
  ---
,    operator: fail
,  ...
,2015-12-07 18:47:54.078 ThaliTest[416:168315] server session: not connected 1449510468363.408
,calling stopBroadcasting
,2015-12-07 18:47:54.187 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:47:54.187 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:47:54.187 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:47:54.188 Th,aliTest[416:168220] server session: disconnect
2015-12-07 18:47:54.188 ThaliTest[416:168220] server session: stateChange:2->0 1449510468177.375
,2015-12-07 18:47:54.189 ThaliTest[416:168220] server session: disconnect
2015-12-07 18:47:54.192 ThaliTest[416:168220] server session: stateChange:2->0 1449510469411.383
2015-12-07 18:47:54.193 ThaliTest[416:168220] server session: disconnect
2015-12-07 18:47:54.194 ThaliTest[416:168220] server session: stateChange:2->0 1449510468363.408
,2015-12-07 18:47:54.198 ThaliTest[416:168220] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-07 18:47:55.581 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:47:55.585 ThaliTest[416:168220] server: starting 1449510475581.416.zFnyqQ==
2015-12-07 18:47:55.586 ThaliTest[416:168220] multipeer session: start timer: 0x1a89ffc0
2015-12-07 18:47:55.586 ThaliTest[416:168220] THEMultipeerSession initialized peer 1449510475581.416
2015-12-07 18:47:55.587 ThaliTest[416:168220] jxcore: startBroadcasting: success
,ok 86 Should be able to call startBroadcasting without error
,2015-12-07 18:47:56.324 ThaliTest[416:167996] client: found peer: 1449510468363.408.sJcxPg==
,2015-12-07 18:47:56.326 ThaliTest[416:168220] jxcore: connect 1449510468363.408.sJcxPg==
2015-12-07 18:47:56.328 ThaliTest[416:168220] client session: connect
2015-12-07 18:47:56.329 ThaliTest[416:168220] client session: stateChange:0->1 1449510468363.40,8.sJcxPg==
,2015-12-07 18:47:56.558 ThaliTest[416:167996] client: found peer: 1449510475496.408.7GdpBQ==
,2015-12-07 18:47:56.560 ThaliTest[416:168220] jxcore: connect 1449510475496.408.7GdpBQ==
2015-12-07 18:47:56.561 ThaliTest[416:168220] client session: connect
2015-12-07 18:47:56.561 ThaliTest[416:168220] client session: stateChange:0->1 1449510475496.408.7GdpBQ==
,2015-12-07 18:47:57.029 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:47:57.029 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:47:57.030 ThaliTest[416:167996] multipeer session: start timer: 0x1a89ffc0
2015-12-07 18:47:57.030 ThaliTest[416:167996] server session: connect
2015-12-07 18:47:57.030 ThaliTest[416:167996] server session: stateChange:0->1 1449510475496.408
,2015-12-07 18:47:57.044 ThaliTest[416:167996] server: accepting invitation 1449510475496.408
2015-12-07 18:47:57.046 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:47:57.046 ThaliTest[416:167996] multipeer session: stop timer
2015-12,-07 18:47:57.047 ThaliTest[416:167996] multipeer session: start timer: 0x1a89ffc0
2015-12-07 18:47:57.049 ThaliTest[416:167996] server session: connect
2015-12-07 18:47:57.049 ThaliTest[416:167996] server session: stateChange:0->1 1449510476527.383
2015-12-07 18:47:57.067 ThaliTest[416:167996] server: accepting invitation 1449510476527.383
2015-12-07 18:47:57.068 ThaliTest[416:167996] client: found peer: 1449510476527.383.t1iPAw==
2015-12-07 18:47:57.069 ThaliTest[416:168220] jxcore: connect 1449510476527.383.t1iPAw==
2015-12-07 18:47:57.071 ThaliTest[416:168220] client session: connect
2015-12-07 18:47:57.072 ThaliTest[416:168220] client session: stateChange:0->1 1449510476527.383.t1iPAw==
,2015-12-07 18:47:57.546 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:47:57.546 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:47:57.546 ThaliTest[416:167996] multipeer session: start timer: 0x1a89ffc0
2015-12-07 18:47:57.547 ThaliTest[416:167996] server session: connect
2015-12-07 18:47:57.547 ThaliTest[416:167996] server session: stateChange:0->1 1449510476485.375
2015-12-07 18:47:57.552 ThaliTest[416:167996] server: accepting invitation 1449510476485.375
,2015-12-07 18:47:57.759 ThaliTest[416:167996] client: found peer: 1449510476485.375./zzCMA==
2015-12-07 18:47:57.760 ThaliTest[416:168220] jxcore: connect 1449510476485.375./zzCMA==
2015-12-07 18:47:57.760 ThaliTest[416:168220] client session: connect
2015-12-07 18:47:57.760 ThaliTest[416:168220] client session: stateChange:0->1 1449510476485.375./zzCMA==
,2015-12-07 18:47:59.799 ThaliTest[416:168070] server session: connected
2015-12-07 18:47:59.799 ThaliTest[416:168070] server session: stateChange:1->2 1449510475496.408
,2015-12-07 18:47:59.848 ThaliTest[416:168334] client session: connected
,2015-12-07 18:47:59.848 ThaliTest[416:168334] client session: stateChange:1->2 1449510475496.408.7GdpBQ==
,2015-12-07 18:47:59.944 ThaliTest[416:168070] client session: fireConnectCallback: 1449510475496.408.7GdpBQ==
2015-12-07 18:47:59.953 ThaliTest[416:167996] server relay: socket disconnected
2015-12-07 18:47:59.953 ThaliTest[416:168070] jxcore: connect: s,uccess
ok 87 Should be able to connect without error
ok 88 Port should be within range
2015-12-07 18:47:59.955 ThaliTest[416:167996] server relay: 0x1a8aa610 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={,NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
2015-12-07 18:47:59.960 ThaliTest[416:168220] jxcore: connect 1449510475496.408.7GdpBQ==
2015-12-07 18:47:59.964 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510475496.408.7GdpBQ==
2015-12-07 18:47:59.967 ThaliTest[416:168220] jxcore: connect: fail: Aleady connecting
ok 89 Should fail on double connect
2015-12-07 18:47:59.972 ThaliTest[416:168220] jxcore: disconnect
2015-12-07 18:47:59.974, ThaliTest[416:168220] client session: disconnectFromPeer: 1449510475496.408.7GdpBQ==
2015-12-07 18:47:59.986 ThaliTest[416:168220] client session: disconnect
2015-12-07 18:47:59.988 ThaliTest[416:168220] client session: stateChange:2->0 1449510475496.408.7GdpBQ==
,2015-12-07 18:48:00.031 ThaliTest[416:168343] server session: not connected 1449510475496.408
,2015-12-07 18:48:00.058 ThaliTest[416:168220] jxcore: disconnect: success
,ok 90 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-07 18:48:00.359 ThaliTest[416:168343] server session: connected
,2015-12-07 18:48:00.360 ThaliTest[416:168343] server session: stateChange:1->2 1449510476527.383
,2015-12-07 18:48:00.371 ThaliTest[416:167996] server relay: socket disconnected
2015-12-07 18:48:00.371 ThaliTest[416:167996] server relay: 0x18ecca60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:00.388 ThaliTest[416:168361] server session: not connected 1449510476527.383
,2015-12-07 18:48:00.484 ThaliTest[416:168361] client session: connected
2015-12-07 18:48:00.485 ThaliTest[416:168361] client session: stateChange:1->2 1449510476527.383.t1iPAw==
,2015-12-07 18:48:00.495 ThaliTest[416:168343] client session: fireConnectCallback: 1449510476527.383.t1iPAw==
2015-12-07 18:48:00.495 ThaliTest[416:168343] jxcore: connect: success
ok 91 Should be able to connect without error
ok 92 Port should be within range
,2015-12-07 18:48:00.498 ThaliTest[416:168220] jxcore: connect 1449510476527.383.t1iPAw==
2015-12-07 18:48:00.499 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510476527.383.t1iPAw==
2015-12-07 18:48:00.499 ThaliTest[416:168220] jxcore: con,nect: fail: Aleady connecting
ok 93 Should fail on double connect
2015-12-07 18:48:00.500 ThaliTest[416:168220] jxcore: disconnect
,2015-12-07 18:48:00.501 ThaliTest[416:168220] client session: disconnectFromPeer: 1449510476527.383.t1iPAw==
2015-12-07 18:48:00.501 ThaliTest[416:168220] client session: disconnect
2015-12-07 18:48:00.501 ThaliTest[416:168220] client session: stateChange:2->0 1449510476527.383.t1iPAw==
,2015-12-07 18:48:00.511 ThaliTest[416:168220] jxcore: disconnect: success
ok 94 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
not ok 95 .end() called twice
  ---
    operator: fail
  ...
,2015-12-07 18:48:01.161 ThaliTest[416:168361] server session: connected
,2015-12-07 18:48:01.162 ThaliTest[416:168361] server session: stateChange:1->2 1449510476485.375
,2015-12-07 18:48:01.174 ThaliTest[416:167996] server relay: socket disconnected
,2015-12-07 18:48:01.174 ThaliTest[416:167996] server relay: 0x18ed0b10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection re,fused} 
,2015-12-07 18:48:01.224 ThaliTest[416:168361] server session: not connected 1449510476485.375
,calling stopBroadcasting
,2015-12-07 18:48:01.529 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:48:01.530 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:48:01.530 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:48:01.530 Th,aliTest[416:168220] client session: disconnect
2015-12-07 18:48:01.531 ThaliTest[416:168220] client session: stateChange:1->0 1449510468363.408.sJcxPg==
2015-12-07 18:48:01.532 ThaliTest[416:168220] client session: disconnect
2015-12-07 18:48:01.532 Tha,liTest[416:168220] client session: stateChange:1->0 1449510476485.375./zzCMA==
,2015-12-07 18:48:01.613 ThaliTest[416:168220] server session: disconnect
2015-12-07 18:48:01.613 ThaliTest[416:168220] server session: stateChange:2->0 1449510476527.383
2015-12-07 18:48:01.614 ThaliTest[416:168220] server session: disconnect
2015-12-07, 18:48:01.614 ThaliTest[416:168220] server session: stateChange:2->0 1449510475496.408
,2015-12-07 18:48:01.621 ThaliTest[416:168220] server session: disconnect
2015-12-07 18:48:01.622 ThaliTest[416:168220] server session: stateChange:2->0 1449510476485.375
2015-12-07 18:48:01.625 ThaliTest[416:168220] jxcore: stopBroadcasting: success
sto,pBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-07 18:48:11.053 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:48:11.058 ThaliTest[416:168220] server: starting 1449510491053.416.ZCqZnQ==
2015-12-07 18:48:11.059 ThaliTest[416:168220] multipeer session: start timer: 0x1a8a3ac0
2015-12-07 18:48:11.059 ThaliTest[416:168220] THEMultipeerSession initialized peer 1449510491053.416
2015-12-07 18:48:11.059 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error
,2015-12-07 18:48:11.840 ThaliTest[416:167996] client: found peer: 1449510489481.375.tffILg==
2015-12-07 18:48:11.841 ThaliTest[416:167996] client: found peer: 1449510489175.408.1RR9xA==
2015-12-07 18:48:11.842 ThaliTest[416:168220] jxcore: connect 144951,0489481.375.tffILg==
2015-12-07 18:48:11.843 ThaliTest[416:168220] client session: connect
2015-12-07 18:48:11.843 ThaliTest[416:168220] client session: stateChange:0->1 1449510489481.375.tffILg==
,2015-12-07 18:48:11.858 ThaliTest[416:168220] jxcore: connect 1449510489175.408.1RR9xA==
2015-12-07 18:48:11.859 ThaliTest[416:168220] client session: connect
2015-12-07 18:48:11.859 ThaliTest[416:168220] client session: stateChange:0->1 1449510489175.40,8.1RR9xA==
,2015-12-07 18:48:12.020 ThaliTest[416:167996] client: found peer: 1449510491347.383.nrOfbw==
2015-12-07 18:48:12.022 ThaliTest[416:168220] jxcore: connect 1449510491347.383.nrOfbw==
2015-12-07 18:48:12.022 ThaliTest[416:168220] client session: connect
2,015-12-07 18:48:12.023 ThaliTest[416:168220] client session: stateChange:0->1 1449510491347.383.nrOfbw==
,2015-12-07 18:48:12.291 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:48:12.292 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:48:12.292 ThaliTest[416:167996] multipeer session: start timer: 0x1a8a3ac0
2015-12-07 18:48:12.292 ThaliTest[416:167996] server session: connect
2015-12-07 18:48:12.293 ThaliTest[416:167996] server session: stateChange:0->1 1449510491347.383
,2015-12-07 18:48:12.301 ThaliTest[416:167996] server: accepting invitation 1449510491347.383
,2015-12-07 18:48:12.327 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:48:12.328 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:48:12.329 ThaliTest[416:167996] multipeer session: start timer: 0x1a8a3ac0
2015-12-07 ,18:48:12.329 ThaliTest[416:167996] server session: connect
2015-12-07 18:48:12.330 ThaliTest[416:167996] server session: stateChange:0->1 1449510489175.408
2015-12-07 18:48:12.343 ThaliTest[416:167996] server: accepting invitation 1449510489175.408
,2015-12-07 18:48:12.679 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:48:12.680 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:48:12.680 ThaliTest[416:167996] multipeer session: start timer: 0x1a8a3ac0
2015-12-07 18:48:12.680 ThaliTest[416:167996] server session: connect
2015-12-07 18:48:12.680 ThaliTest[416:167996] server session: stateChange:0->1 1449510489481.375
,2015-12-07 18:48:12.690 ThaliTest[416:167996] server: accepting invitation 1449510489481.375
,2015-12-07 18:48:15.340 ThaliTest[416:168402] client session: connected
2015-12-07 18:48:15.341 ThaliTest[416:168402] client session: stateChange:1->2 1449510491347.383.nrOfbw==
2015-12-07 18:48:15.343 ThaliTest[416:168070] client session: connected
201,5-12-07 18:48:15.343 ThaliTest[416:168070] client session: stateChange:1->2 1449510489175.408.1RR9xA==
,2015-12-07 18:48:15.352 ThaliTest[416:168070] client session: fireConnectCallback: 1449510489175.408.1RR9xA==
2015-12-07 18:48:15.354 ThaliTest[416:168070] jxcore: connect: success
,ok 97 Should be able to connect without error
ok 98 Port should be within range
2015-12-07 18:48:15.362 ThaliTest[416:168220] jxcore: disconnect
2015-12-07 18:48:15.362 ThaliTest[416:168220] client session: disconnectFromPeer: 1449510489175.408.1RR9xA==
2015-12-07 18:48:15.362 ThaliTest[416:168220] client session: disconnect
2015-12-07 18:48:15.363 ThaliTest[416:168220] client session: stateChange:2->0 1449510489175.408.1RR9xA==
,2015-12-07 18:48:15.372 ThaliTest[416:168282] client session: fireConnectCallback: 1449510491347.383.nrOfbw==
2015-12-07 18:48:15.374 ThaliTest[416:168282] jxcore: connect: success
,2015-12-07 18:48:15.384 ThaliTest[416:168220] jxcore: disconnect: success
ok 99 Should be able to disconnect without error
2015-12-07 18:48:15.386 ThaliTest[416:168220] jxcore: disconnect
2015-12-07 18:48:15.386 ThaliTest[416:168220] jxcore: disconnect:, fail
ok 100 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,ok 101 Should be able to connect without error
ok 102 Port should be within range
2015-12-07 18:48:15.391 ThaliTest[416:168220] jxcore: disconnect
,2015-12-07 18:48:15.391 ThaliTest[416:168220] client session: disconnectFromPeer: 1449510491347.383.nrOfbw==
,2015-12-07 18:48:15.392 ThaliTest[416:168220] client session: disconnect
2015-12-07 18:48:15.393 ThaliTest[416:168220] client session: stateChange:2->0 1449510491347.383.nrOfbw==
,2015-12-07 18:48:15.402 ThaliTest[416:168220] jxcore: disconnect: success
ok 103 Should be able to disconnect without error
,2015-12-07 18:48:15.406 ThaliTest[416:168220] jxcore: disconnect
,2015-12-07 18:48:15.409 ThaliTest[416:168220] jxcore: disconnect: fail
,ok 104 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,2015-12-07 18:48:15.420 ThaliTest[416:168070] server session: connected
,2015-12-07 18:48:15.421 ThaliTest[416:168070] server session: stateChange:1->2 1449510491347.383
,2015-12-07 18:48:15.428 ThaliTest[416:167996] server relay: socket disconnected
,not ok 105 .end() called twice
,  ---
,2015-12-07 18:48:15.430 ThaliTest[416:167996] server relay: 0x18ef23b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:15.434 ThaliTest[416:168070] client session: connected
,    operator: fail
,2015-12-07 18:48:15.435 ThaliTest[416:168070] client session: stateChange:1->2 1449510489481.375.tffILg==
,  ...
,2015-12-07 18:48:15.443 ThaliTest[416:168070] client session: fireConnectCallback: 1449510489481.375.tffILg==
,2015-12-07 18:48:15.444 ThaliTest[416:168070] jxcore: connect: success
,# setup
,ok 106 Should be able to connect without error
,2015-12-07 18:48:15.456 ThaliTest[416:168070] server session: not connected 1449510491347.383
,ok 107 Port should be within range
,2015-12-07 18:48:15.459 ThaliTest[416:168220] jxcore: disconnect
,2015-12-07 18:48:15.460 ThaliTest[416:168220] client session: disconnectFromPeer: 1449510489481.375.tffILg==
,2015-12-07 18:48:15.460 ThaliTest[416:168220] client session: disconnect
,2015-12-07 18:48:15.461 ThaliTest[416:168220] client session: stateChange:2->0 1449510489481.375.tffILg==
,2015-12-07 18:48:15.528 ThaliTest[416:168220] jxcore: disconnect: success
,ok 108 Should be able to disconnect without error
,2015-12-07 18:48:15.530 ThaliTest[416:168220] jxcore: disconnect
,2015-12-07 18:48:15.531 ThaliTest[416:168220] jxcore: disconnect: fail
,ok 109 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,not ok 110 .end() called twice
  ---
,    operator: fail
,  ...
,2015-12-07 18:48:15.562 ThaliTest[416:168343] server session: connected
2015-12-07 18:48:15.563 ThaliTest[416:168343] server session: stateChange:1->2 1449510489175.408
,2015-12-07 18:48:15.621 ThaliTest[416:167996] server relay: socket disconnected
,2015-12-07 18:48:15.622 ThaliTest[416:167996] server relay: 0x1a8a4d20 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection re,fused} 
,2015-12-07 18:48:15.632 ThaliTest[416:168343] server session: not connected 1449510489175.408
,calling stopBroadcasting
,2015-12-07 18:48:15.675 ThaliTest[416:168220] jxcore: stopBroadcasting
,2015-12-07 18:48:15.676 ThaliTest[416:168220] THEMultipeerSession stopping peer
,2015-12-07 18:48:15.677 ThaliTest[416:168220] multipeer session: stop timer
,2015-12-07 18:48:15.681 ThaliTest[416:168220] server session: disconnect
,2015-12-07 18:48:15.685 ThaliTest[416:168220] server session: stateChange:2->0 1449510489175.408
,2015-12-07 18:48:15.833 ThaliTest[416:168343] server session: connected
2015-12-07 18:48:15.833 ThaliTest[416:168343] server session: stateChange:1->2 1449510489481.375
,2015-12-07 18:48:15.837 ThaliTest[416:167996] server relay: socket disconnected
2015-12-07 18:48:15.838 ThaliTest[416:167996] server relay: 0x18ede560 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:15.884 ThaliTest[416:168315] server session: not connected 1449510489481.375
,2015-12-07 18:48:16.047 ThaliTest[416:168220] server session: disconnect
2015-12-07 18:48:16.048 ThaliTest[416:168220] server session: stateChange:2->0 1449510489481.375
2015-12-07 18:48:16.049 ThaliTest[416:168220] server session: disconnect
2015-12-07, 18:48:16.050 ThaliTest[416:168220] server session: stateChange:2->0 1449510491347.383
2015-12-07 18:48:16.051 ThaliTest[416:168220] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly,
,# teardown
,2015-12-07 18:48:26.166 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:48:26.169 ThaliTest[416:168220] server: starting 1449510506165.416.wWLXyQ==
2015-12-07 18:48:26.170 ThaliTest[416:168220] multipeer session: start timer: 0x18ef2a40
2015-12-07 18:48:26.171 ThaliTest[416:168220] THEMultipeerSession initialized peer 1449510506165.416
2015-12-07 18:48:26.171 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error
echo server started
,2015-12-07 18:48:26.838 ThaliTest[416:167996] client: found peer: 1449510489175.408.1RR9xA==
2015-12-07 18:48:26.838 ThaliTest[416:167996] client: found peer: 1449510506003.383.i2Azhg==
[{"peerIdentifier":"1449510489175.408.1RR9xA==","peerName":"(null)",,"peerAvailable":true}]
2015-12-07 18:48:26.840 ThaliTest[416:168220] jxcore: connect 1449510489175.408.1RR9xA==
2015-12-07 18:48:26.840 ThaliTest[416:168220] client session: connect
2015-12-07 18:48:26.840 ThaliTest[416:168220] client session: stateChange:0->1 1449510489175.408.1RR9xA==
,[{"peerIdentifier":"1449510506003.383.i2Azhg==","peerName":"(null)","peerAvailable":true}]
2015-12-07 18:48:26.849 ThaliTest[416:168220] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:26.850 ThaliTest[416:168220] client session: connect
2015-12-07 18:48:26.850 ThaliTest[416:168220] client session: stateChange:0->1 1449510506003.383.i2Azhg==
,2015-12-07 18:48:27.373 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:48:27.374 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:48:27.374 ThaliTest[416:167996] multipeer session: start timer: 0x18ef2a40
2015-12-07 ,18:48:27.374 ThaliTest[416:167996] server session: connect
2015-12-07 18:48:27.374 ThaliTest[416:167996] server session: stateChange:0->1 1449510506003.383
,2015-12-07 18:48:27.383 ThaliTest[416:167996] server: accepting invitation 1449510506003.383
,2015-12-07 18:48:28.131 ThaliTest[416:167996] client: found peer: 1449510506999.375.Lduuig==
[{"peerIdentifier":"1449510506999.375.Lduuig==","peerName":"(null)","peerAvailable":true}]
2015-12-07 18:48:28.133 ThaliTest[416:168220] jxcore: connect 14495105,06999.375.Lduuig==
2015-12-07 18:48:28.133 ThaliTest[416:168220] client session: connect
2015-12-07 18:48:28.133 ThaliTest[416:168220] client session: stateChange:0->1 1449510506999.375.Lduuig==
,2015-12-07 18:48:28.339 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:48:28.340 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:48:28.341 ThaliTest[416:167996] multipeer session: start timer: 0x18ef2a40
2015-12-07 ,18:48:28.341 ThaliTest[416:167996] server session: connect
2015-12-07 18:48:28.344 ThaliTest[416:167996] server session: stateChange:0->1 1449510507109.408
2015-12-07 18:48:28.353 ThaliTest[416:167996] server: accepting invitation 1449510507109.408
2015,-12-07 18:48:28.353 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:48:28.353 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:48:28.354 ThaliTest[416:167996] multipeer session: start timer: 0x18ef2a40
,2015-12-07 18:48:28.355 ThaliTest[416:167996] server session: connect
,2015-12-07 18:48:28.356 ThaliTest[416:167996] server session: stateChange:0->1 1449510506999.375
,2015-12-07 18:48:28.364 ThaliTest[416:167996] server: accepting invitation 1449510506999.375
,2015-12-07 18:48:29.370 ThaliTest[416:167996] client: found peer: 1449510507109.408.rby7cA==
[{"peerIdentifier":"1449510507109.408.rby7cA==","peerName":"(null)","peerAvailable":true}]
2015-12-07 18:48:29.374 ThaliTest[416:168220] jxcore: connect 14495105,07109.408.rby7cA==
2015-12-07 18:48:29.375 ThaliTest[416:168220] client session: connect
2015-12-07 18:48:29.375 ThaliTest[416:168220] client session: stateChange:0->1 1449510507109.408.rby7cA==
,2015-12-07 18:48:29.906 ThaliTest[416:168541] server session: connected
2015-12-07 18:48:29.906 ThaliTest[416:168541] server session: stateChange:1->2 1449510506003.383
,2015-12-07 18:48:29.923 ThaliTest[416:167996] server relay: connected (to port: 5001)
,2015-12-07 18:48:30.077 ThaliTest[416:168282] server session: not connected 1449510506003.383
2015-12-07 18:48:30.083 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:48:30.083 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:48:30.083 ThaliTest[416:167996] multipeer session: start timer: 0x18ef2a40
2015-12-07 18:48:30.083 ThaliTest[416:167996] server: disconnecting to refresh session (1449510506003.383)
2015-12-07 18:48:30.084 ThaliTest[416:167996] server session: di,sconnect
2015-12-07 18:48:30.084 ThaliTest[416:167996] server session: stateChange:2->0 1449510506003.383
2015-12-07 18:48:30.090 ThaliTest[416:167996] server session: connect
2015-12-07 18:48:30.090 ThaliTest[416:167996] server session: stateChange:0->,1 1449510506003.383
,2015-12-07 18:48:30.111 ThaliTest[416:167996] server: accepting invitation 1449510506003.383
,2015-12-07 18:48:30.740 ThaliTest[416:168541] client session: connected
,2015-12-07 18:48:30.742 ThaliTest[416:168541] client session: stateChange:1->2 1449510506003.383.i2Azhg==
,2015-12-07 18:48:30.748 ThaliTest[416:168541] client session: fireConnectCallback: 1449510506003.383.i2Azhg==
2015-12-07 18:48:30.749 ThaliTest[416:168541] jxcore: connect: success
,ok 112 Should be able to connect without error
ok 113 Port should be within range
ok 114 First connect should succeed
,2015-12-07 18:48:30.812 ThaliTest[416:167996] client: relay established
2015-12-07 18:48:30.814 ThaliTest[416:167996] client: new accepted socket: 0x18ed4cd0
,ok 115 the test messages should be equal
,ok 116 First send should succeed
,2015-12-07 18:48:30.891 ThaliTest[416:167996] client: socket closed
,2015-12-07 18:48:30.893 ThaliTest[416:167996] client relay: socket disconnected
,2015-12-07 18:48:30.894 ThaliTest[416:167996] client relay: 0x18ed4cd0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-07 18:48:30.895 ThaliTest[416:167996] client session: socket closed: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:30.897 ThaliTest[416:167996] client session: onLinkFailure: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:30.898 ThaliTest[416:167996] client session: disconnect
,2015-12-07 18:48:30.899 ThaliTest[416:167996] client session: stateChange:2->0 1449510506003.383.i2Azhg==
,2015-12-07 18:48:30.972 ThaliTest[416:167996] client session: fireConnectionErrorEvent: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:30.978 ThaliTest[416:168220] jxcore: connect 1449510506003.383.i2Azhg==
,2015-12-07 18:48:30.986 ThaliTest[416:168220] client session: connect
,2015-12-07 18:48:30.988 ThaliTest[416:168220] client session: stateChange:0->1 1449510506003.383.i2Azhg==
,2015-12-07 18:48:31.187 ThaliTest[416:167996] client: lost peer: 1449510489175.408.1RR9xA==
,2015-12-07 18:48:31.188 ThaliTest[416:167996] client session: onPeerLost: 1449510489175.408.1RR9xA==
,2015-12-07 18:48:31.190 ThaliTest[416:167996] client session: onLinkFailure: 1449510489175.408.1RR9xA==
,2015-12-07 18:48:31.191 ThaliTest[416:167996] client session: disconnect
,2015-12-07 18:48:31.196 ThaliTest[416:167996] client session: stateChange:1->0 1449510489175.408.1RR9xA==
,2015-12-07 18:48:31.203 ThaliTest[416:167996] client session: fireConnectCallback: 1449510489175.408.1RR9xA==
,2015-12-07 18:48:31.204 ThaliTest[416:167996] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1449510489175.408.1RR9xA==","peerName":"(null)","peerAvailable":false}]
,2015-12-07 18:48:31.336 ThaliTest[416:168540] client session: connected
2015-12-07 18:48:31.337 ThaliTest[416:168540] client session: stateChange:1->2 1449510506999.375.Lduuig==
,2015-12-07 18:48:31.400 ThaliTest[416:168541] client session: fireConnectCallback: 1449510506999.375.Lduuig==
2015-12-07 18:48:31.401 ThaliTest[416:168541] jxcore: connect: success
,ok 117 Should be able to connect without error
,ok 118 Port should be within range
ok 119 First connect should succeed
,2015-12-07 18:48:31.422 ThaliTest[416:167996] client: relay established
2015-12-07 18:48:31.422 ThaliTest[416:167996] client: new accepted socket: 0x1a8aa8f0
,ok 120 the test messages should be equal
ok 121 First send should succeed
,2015-12-07 18:48:31.502 ThaliTest[416:167996] client: socket closed
,2015-12-07 18:48:31.504 ThaliTest[416:167996] client relay: socket disconnected
,2015-12-07 18:48:31.505 ThaliTest[416:167996] client relay: 0x1a8aa8f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-07 18:48:31.506 ThaliTest[416:167996] client session: socket closed: 1449510506999.375.Lduuig==
,2015-12-07 18:48:31.507 ThaliTest[416:167996] client session: onLinkFailure: 1449510506999.375.Lduuig==
,2015-12-07 18:48:31.508 ThaliTest[416:167996] client session: disconnect
,2015-12-07 18:48:31.509 ThaliTest[416:167996] client session: stateChange:2->0 1449510506999.375.Lduuig==
,2015-12-07 18:48:31.535 ThaliTest[416:167996] client session: fireConnectionErrorEvent: 1449510506999.375.Lduuig==
,2015-12-07 18:48:31.537 ThaliTest[416:168220] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:31.538 ThaliTest[416:168220] client session: connect
,2015-12-07 18:48:31.538 ThaliTest[416:168220] client session: stateChange:0->1 1449510506999.375.Lduuig==
,2015-12-07 18:48:31.559 ThaliTest[416:168315] server session: connected
,2015-12-07 18:48:31.559 ThaliTest[416:168315] server session: stateChange:1->2 1449510507109.408
,2015-12-07 18:48:31.566 ThaliTest[416:168220] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:31.572 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
,2015-12-07 18:48:31.573 ThaliTest[416:168220] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:31.576 ThaliTest[416:167996] server relay: connected (to port: 5001)
,2015-12-07 18:48:32.107 ThaliTest[416:168587] server session: connected
2015-12-07 18:48:32.107 ThaliTest[416:168587] server session: stateChange:1->2 1449510506999.375
,2015-12-07 18:48:32.122 ThaliTest[416:168315] server session: not connected 1449510507109.408
,2015-12-07 18:48:32.177 ThaliTest[416:167996] multipeer session: reset timer
2015-12-07 18:48:32.177 ThaliTest[416:167996] multipeer session: stop timer
2015-12-07 18:48:32.177 ThaliTest[416:167996] multipeer session: start timer: 0x18ef2a40
2015-12-07 ,18:48:32.177 ThaliTest[416:167996] server: disconnecting to refresh session (1449510507109.408)
2015-12-07 18:48:32.178 ThaliTest[416:167996] server session: disconnect
2015-12-07 18:48:32.178 ThaliTest[416:167996] server session: stateChange:2->0 1449510507109.408
2015-12-07 18:48:32.181 ThaliTest[416:167996] server session: connect
2015-12-07 18:48:32.182 ThaliTest[416:167996] server session: stateChange:0->1 1449510507109.408
,2015-12-07 18:48:32.192 ThaliTest[416:167996] server: accepting invitation 1449510507109.408
,2015-12-07 18:48:32.218 ThaliTest[416:168220] jxcore: connect 1449510489175.408.1RR9xA==
2015-12-07 18:48:32.219 ThaliTest[416:168220] client: connect: unreachable 1449510489175.408.1RR9xA==
2015-12-07 18:48:32.220 ThaliTest[416:168220] jxcore: connect: fail: Peer unreachable
,2015-12-07 18:48:32.576 ThaliTest[416:168220] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:32.576 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
,2015-12-07 18:48:32.579 ThaliTest[416:168220] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:32.645 ThaliTest[416:168587] client session: connected
,2015-12-07 18:48:32.646 ThaliTest[416:168587] client session: stateChange:1->2 1449510507109.408.rby7cA==
,2015-12-07 18:48:32.652 ThaliTest[416:168587] client session: fireConnectCallback: 1449510507109.408.rby7cA==
2015-12-07 18:48:32.652 ThaliTest[416:168587] jxcore: connect: success
,ok 122 Should be able to connect without error
,ok 123 Port should be within range
,ok 124 First connect should succeed
,2015-12-07 18:48:32.674 ThaliTest[416:167996] client: relay established
2015-12-07 18:48:32.674 ThaliTest[416:167996] client: new accepted socket: 0x18efb410
,2015-12-07 18:48:32.763 ThaliTest[416:168315] server session: connected
,2015-12-07 18:48:32.764 ThaliTest[416:168315] server session: stateChange:1->2 1449510506003.383
,2015-12-07 18:48:32.781 ThaliTest[416:167996] server relay: connected (to port: 5001)
,2015-12-07 18:48:33.054 ThaliTest[416:167996] server relay: connected (to port: 5001)
,ok 125 the test messages should be equal
ok 126 First send should succeed
,2015-12-07 18:48:33.082 ThaliTest[416:167996] client: socket closed
2015-12-07 18:48:33.082 ThaliTest[416:167996] client relay: socket disconnected
2015-12-07 18:48:33.083 ThaliTest[416:167996] client relay: 0x18efb410 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:33.083 ThaliTest[416:167996] client session: socket closed: 1449510507109.408.rby7cA==
2015-12-07 18:48:33.,083 ThaliTest[416:167996] client session: onLinkFailure: 1449510507109.408.rby7cA==
2015-12-07 18:48:33.083 ThaliTest[416:167996] client session: disconnect
2015-12-07 18:48:33.084 ThaliTest[416:167996] client session: stateChange:2->0 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.099 ThaliTest[416:167996] client session: fireConnectionErrorEvent: 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.100 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:33.102 ThaliTest[416:168220] client session: connect
2015-12-07 18:48:33.102 ThaliTest[416:168220] client session: stateChange:0->1 1449510507109.40,8.rby7cA==
,2015-12-07 18:48:33.213 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:33.214 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:33.214 ThaliTest[416:168220] jxcore: con,nect: fail: Aleady connecting
2015-12-07 18:48:33.215 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:33.215 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:33.215 ThaliTest[416:168220] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:33.311 ThaliTest[416:168562] server session: not connected 1449510506003.383
,2015-12-07 18:48:33.344 ThaliTest[416:168315] server session: not connected 1449510506999.375
,2015-12-07 18:48:33.587 ThaliTest[416:168220] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:33.587 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:33.588 ThaliTest[416:168220] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:33.772 ThaliTest[416:168562] client session: connected
2015-12-07 18:48:33.772 ThaliTest[416:168562] client session: stateChange:1->2 1449510506003.383.i2Azhg==
,2015-12-07 18:48:33.794 ThaliTest[416:168562] client session: fireConnectCallback: 1449510506003.383.i2Azhg==
2015-12-07 18:48:33.794 ThaliTest[416:168562] jxcore: connect: success
,ok 127 Should be able to connect without error
,ok 128 Port should be within range
,ok 129 Second connect should succeed
,2015-12-07 18:48:33.832 ThaliTest[416:167996] client: relay established
2015-12-07 18:48:33.833 ThaliTest[416:167996] client: new accepted socket: 0x18eed3f0
,ok 130 the test messages should be equal
,ok 131 Second send should succeed
,# setup
,2015-12-07 18:48:33.891 ThaliTest[416:167996] client: socket closed
,2015-12-07 18:48:33.892 ThaliTest[416:167996] client relay: socket disconnected
2015-12-07 18:48:33.892 ThaliTest[416:167996] client relay: 0x18eed3f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-07 18:48:33.893 ThaliTest[416:167996] client session: socket closed: 1449510506003.383.i2Azhg==
2015-12-07 18:48:33.893 ThaliTest[416:167996] client session: onLinkFailure: 1449510506003.383.i2Azhg==
2015-12-07 18:48:33.893 ThaliTest[416:167996] ,client session: disconnect
,2015-12-07 18:48:33.894 ThaliTest[416:167996] client session: stateChange:2->0 1449510506003.383.i2Azhg==
,2015-12-07 18:48:33.909 ThaliTest[416:167996] client session: fireConnectionErrorEvent: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:34.213 ThaliTest[416:167996] client: found peer: Apple-Iphone5-1_PT94.0IbCHA==
,[{"peerIdentifier":"Apple-Iphone5-1_PT94.0IbCHA==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 18:48:34.220 ThaliTest[416:168220] jxcore: connect Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 18:48:34.224 ThaliTest[416:168220] client session: connect
,2015-12-07 18:48:34.230 ThaliTest[416:168220] client session: stateChange:0->1 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 18:48:34.241 ThaliTest[416:167996] multipeer session: reset timer
,2015-12-07 18:48:34.242 ThaliTest[416:167996] multipeer session: stop timer
,2015-12-07 18:48:34.243 ThaliTest[416:167996] multipeer session: start timer: 0x18ef2a40
,2015-12-07 18:48:34.245 ThaliTest[416:167996] server: disconnecting to refresh session (1449510506999.375)
,2015-12-07 18:48:34.246 ThaliTest[416:167996] server session: disconnect
,2015-12-07 18:48:34.247 ThaliTest[416:167996] server session: stateChange:2->0 1449510506999.375
,2015-12-07 18:48:34.253 ThaliTest[416:167996] server session: connect
,2015-12-07 18:48:34.254 ThaliTest[416:167996] server session: stateChange:0->1 1449510506999.375
,2015-12-07 18:48:34.292 ThaliTest[416:167996] server: accepting invitation 1449510506999.375
,2015-12-07 18:48:34.298 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:34.299 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
,2015-12-07 18:48:34.301 ThaliTest[416:168220] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:34.305 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:34.307 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
,2015-12-07 18:48:34.310 ThaliTest[416:168220] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:34.598 ThaliTest[416:168220] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:34.598 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:34.599 ThaliTest[416:168220] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:34.677 ThaliTest[416:168562] client session: connected
2015-12-07 18:48:34.677 ThaliTest[416:168562] client session: stateChange:1->2 1449510506999.375.Lduuig==
,2015-12-07 18:48:34.742 ThaliTest[416:168562] client session: fireConnectCallback: 1449510506999.375.Lduuig==
2015-12-07 18:48:34.743 ThaliTest[416:168562] jxcore: connect: success
ok 132 Should be able to connect without error
ok 133 Port should be wit,hin range
ok 134 Second connect should succeed
,2015-12-07 18:48:34.780 ThaliTest[416:167996] client: relay established
2015-12-07 18:48:34.780 ThaliTest[416:167996] client: new accepted socket: 0x1a8d9bc0
,ok 135 the test messages should be equal
,ok 136 Second send should succeed
,not ok 137 .end() called twice
,  ---
,    operator: fail
,  ...
,2015-12-07 18:48:34.839 ThaliTest[416:167996] client: socket closed
2015-12-07 18:48:34.840 ThaliTest[416:167996] client relay: socket disconnected
2015-12-07 18:48:34.840 ThaliTest[416:167996] client relay: 0x1a8d9bc0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:34.840 ThaliTest[416:167996] client session: socket closed: 1449510506999.375.Lduuig==
2015-12-07 18:48:34.,841 ThaliTest[416:167996] client session: onLinkFailure: 1449510506999.375.Lduuig==
2015-12-07 18:48:34.841 ThaliTest[416:167996] client session: disconnect
2015-12-07 18:48:34.841 ThaliTest[416:167996] client session: stateChange:2->0 1449510506999.375.Lduuig==
,2015-12-07 18:48:34.854 ThaliTest[416:167996] client session: fireConnectionErrorEvent: 1449510506999.375.Lduuig==
,2015-12-07 18:48:35.316 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:35.316 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:35.316 ThaliTest[416:168220] jxcore: connect: fail: Aleady connecting
2015-12-07 18:48:35.317 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:35.317 ThaliTest[416:168220] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:35.317 Th,aliTest[416:168220] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:35.389 ThaliTest[416:168562] server session: connected
2015-12-07 18:48:35.390 ThaliTest[416:168562] server session: stateChange:1->2 1449510507109.408
,2015-12-07 18:48:35.399 ThaliTest[416:167996] server relay: connected (to port: 5001)
,2015-12-07 18:48:35.608 ThaliTest[416:168220] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:35.608 ThaliTest[416:168220] client session: connect
2015-12-07 18:48:35.609 ThaliTest[416:168220] client session: stateChange:0->1 1449510506999.375.Lduuig==
,2015-12-07 18:48:35.787 ThaliTest[416:168070] server session: not connected 1449510507109.408
,calling stopBroadcasting
,2015-12-07 18:48:36.201 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:48:36.201 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:48:36.201 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:48:36.202 Th,aliTest[416:168220] client session: disconnect
2015-12-07 18:48:36.202 ThaliTest[416:168220] client session: stateChange:1->0 1449510506999.375.Lduuig==
2015-12-07 18:48:36.203 ThaliTest[416:168220] client session: disconnect
2015-12-07 18:48:36.203 Tha,liTest[416:168220] client session: stateChange:1->0 1449510507109.408.rby7cA==
,2015-12-07 18:48:36.288 ThaliTest[416:168220] client session: disconnect
2015-12-07 18:48:36.289 ThaliTest[416:168220] client session: stateChange:1->0 Apple-Iphone5-1_PT94.0IbCHA==
,2015-12-07 18:48:36.294 ThaliTest[416:168220] server session: disconnect
,2015-12-07 18:48:36.313 ThaliTest[416:168220] server session: stateChange:1->0 1449510506999.375
,2015-12-07 18:48:36.396 ThaliTest[416:168220] server session: disconnect
,2015-12-07 18:48:36.397 ThaliTest[416:168220] server session: stateChange:2->0 1449510507109.408
,2015-12-07 18:48:36.990 ThaliTest[416:168220] server session: disconnect
2015-12-07 18:48:36.990 ThaliTest[416:168220] server session: stateChange:2->0 1449510506003.383
,2015-12-07 18:48:36.995 ThaliTest[416:168220] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,2015-12-07 18:48:37.010 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:37.012 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:37.013 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:37.014 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:37.015 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:37.015 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:38.020 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:38.021 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:38.021 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:38.022 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:38.023 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:38.023 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
,# teardown
,2015-12-07 18:48:39.034 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:39.035 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:39.035 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:39.036 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:39.036 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:39.036 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:40.047 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:40.048 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:40.048 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:40.050 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:40.050 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:40.050 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/475EB9BB-65E6-4975-BCF6-73E1E9D3071C/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2015-12-07 18:48:41.060 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:41.061 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:41.061 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:41.062 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:41.062 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:41.063 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
,ok 138 starting event should occur in right order
,2015-12-07 18:48:41.090 ThaliTest[416:168220] jxcore: startBroadcasting
,2015-12-07 18:48:41.091 ThaliTest[416:168220] server: starting uEHYIPDO3HoegiJ6nKQ-NQ.qHNmZw==
2015-12-07 18:48:41.091 ThaliTest[416:168220] multipeer session: start timer: 0x1a8c5bd0
2015-12-07 18:48:41.092 ThaliTest[416:168220] THEMultipeerSession init,ialized peer uEHYIPDO3HoegiJ6nKQ-NQ
2015-12-07 18:48:41.092 ThaliTest[416:168220] jxcore: startBroadcasting: success
ok 139 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
,ok 140 stopping event should occur in right order
,About to call stopBroadcasting
,2015-12-07 18:48:41.094 ThaliTest[416:168220] jxcore: stopBroadcasting
2015-12-07 18:48:41.095 ThaliTest[416:168220] THEMultipeerSession stopping peer
2015-12-07 18:48:41.095 ThaliTest[416:168220] multipeer session: stop timer
2015-12-07 18:48:41.095 ThaliTest[416:168220] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 141 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,2015-12-07 18:48:42.066 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:42.066 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:42.066 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:42.068 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:42.068 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:42.068 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
,# ThaliReplicationManager receives identity
,2015-12-07 18:48:43.075 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:43.076 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:43.076 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:43.077 ThaliTest[416:168220] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:43.078 ThaliTest[416:168220] Communications not enabled
2015-12-07 18:48:43.078 ThaliTest[416:168220] jxcore: connect: fail: app: Not initialised
,# teardown
,not ok 142 Second connect should succeed
,  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,not ok 143 Second connect should succeed
  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,2015-12-07 18:48:44.168 ThaliTest[416:168220] Error!: connect EADDRNOTAVAIL
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_functi,onName":"connect","_lineNumber":"707","_columnNumber":"19","_msg":"    at connect@net.js:707:19"},{"_fileName":"net.js","_functionName":"Socket.prototype.connect","_lineNumber":"756","_columnNumber":"5","_msg":"    at Socket.prototype.connect@net.js:756:5",},{"_fileName":"net.js","_functionName":"exports.createConnection","_lineNumber":"72","_columnNumber":"10","_msg":"    at exports.createConnection@net.js:72:10"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F,6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"sendData","_lineNumber":"277","_columnNumber":"24","_msg":"    at sendData@/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.a,pp/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"325",",_columnNumber":"17","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B2,FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer","_lineNumber":"251","_columnNumber":"9","_msg":"    at connectWithRetry/connectToPeer@/private/var/mobile/Contain,ers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_t,ests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer/</<","_lineNumber":"260","_columnNumber":"45","_msg":"    at connectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6D,D123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45"},{"_fileName":"timers.js","_functionName":"listOnTimeout","_lineNumber":"112","_columnNumber":"9","_msg":"    at listOnTimeout@timers.js:112:9"},{"_fileName":"net.js","_functionName":"u,nknown","_lineNumber":835,"_columnNumber":10,"_msg":"    at "}]
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
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B2FDED11-230,3-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'sendData',
    _lineNumber: '277',
    _columnNumber: '24',
    _msg: '    at sendData@/private/var/mobile/Containers/Bundle/Application/B2FDED11-2,303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.j,s',
    _functionName: '',
    _lineNumber: '325',
    _columnNumber: '17',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17' },
,  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer',
    _lineNumber: '251',
    _columnNu,mber: '9',
    _msg: '    at connectWithRetry/connectToPeer@/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9' },
  { _fileName: '/private/var/mobile/Con,tainers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer/</<',
    _lineNumber: '260',
    _columnNumber: '45',
    _msg: '    at conn,ectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/B2FDED11-2303-4650-94D1-968C9F6DD123/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45' },
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
