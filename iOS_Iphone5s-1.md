#### Test 5065027860d2bae_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/90999898-7B5C-48A3-91EA-136AB804A47F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/90999898-7B5C-48A3-91EA-136AB804A47F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50342"
,(lldb)     command script import "/tmp/90999898-7B5C-48A3-91EA-136AB804A47F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 18:47:04.309 ThaliTest[408:170140] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5D92D36D-0DC3-43DC-A68D-C83238ED9224/Library/Cookies/Cookies.binarycookies
,2015-12-07 18:47:04.743 ThaliTest[408:170140] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 18:47:04.745 ThaliTest[408:170140] Multi-tasking -> Device: YES, App: YES
,2015-12-07 18:47:04.754 ThaliTest[408:170140] Unlimited access to network resources
,2015-12-07 18:47:04.766 ThaliTest[408:170140] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 18:47:13.712 ThaliTest[408:170140] Resetting plugins due to page load.
,2015-12-07 18:47:17.621 ThaliTest[408:170140] Finished load of: file:///var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/index.html
,2015-12-07 18:47:17.848 ThaliTest[408:170140] JXcore Cordova plugin initializing
,2015-12-07 18:47:17.850 ThaliTest[408:170365] JXcore instance initializing
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
# setup
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
,2015-12-07 18:47:36.824 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:37.093 ThaliTest[408:170365] server: starting 1449510456823.408.VRgppw==
,2015-12-07 18:47:37.095 ThaliTest[408:170365] multipeer session: start timer: 0x15f64300
,2015-12-07 18:47:37.096 ThaliTest[408:170365] THEMultipeerSession initialized peer 1449510456823.408
2015-12-07 18:47:37.097 ThaliTest[408:170365] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.101 ThaliTest[408:170365] jxcore: stopBroadcasting
2015-12-07 18:47:37.103 ThaliTest[408:170365] THEMultipeerSession stopping peer
2015-12-07 18:47:37.105 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:47:37.106 ThaliTest[408:170365] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
2015-12-07 18:47:37.109 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:37.121 ThaliTest[408:170365] server: starting 1449510457108.408./H79zg==
2015-12-07 18:47:37.122 ThaliTest[408:170365] multipeer session: start timer: 0x178d1860
2015-12-07 18:47:37.123 ThaliTest[408:170365] THEMultipeerSession initializ,ed peer 1449510457108.408
2015-12-07 18:47:37.123 ThaliTest[408:170365] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-07 18:47:37.126 ThaliTest[408:170365] jxcore: stopBroadcasting
2015-12-07 18,:47:37.126 ThaliTest[408:170365] THEMultipeerSession stopping peer
2015-12-07 18:47:37.126 ThaliTest[408:170365] multipeer session: stop timer
2015-12-07 18:47:37.127 ThaliTest[408:170365] jxcore: stopBroadcasting: success
ok 48 Should be able to call s,topBroadcasting without error
2015-12-07 18:47:37.129 ThaliTest[408:170365] jxcore: startBroadcasting
2015-12-07 18:47:37.136 ThaliTest[408:170365] server: starting 1449510457129.408.yjMgYQ==
2015-12-07 18:47:37.137 ThaliTest[408:170365] multipeer sessi,on: start timer: 0x15f67830
2015-12-07 18:47:37.149 ThaliTest[408:170365] THEMultipeerSession initialized peer 1449510457129.408
2015-12-07 18:47:37.150 ThaliTest[408:170365] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcast,ing without error
2015-12-07 18:47:37.154 ThaliTest[408:170365] jxcore: stopBroadcasting
,2015-12-07 18:47:37.154 ThaliTest[408:170365] THEMultipeerSession stopping peer
2015-12-07 18:47:37.158 ThaliTest[408:170365] multipeer session: stop timer
2015-12-07 18:47:37.159 ThaliTest[408:170365] jxcore: stopBroadcasting: success
ok 50 Should be a,ble to call stopBroadcasting without error
2015-12-07 18:47:37.163 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:37.177 ThaliTest[408:170365] server: starting 1449510457162.408.Hendhw==
,2015-12-07 18:47:37.190 ThaliTest[408:170365] multipeer session: start timer: 0x178d38f0
2015-12-07 18:47:37.191 ThaliTest[408:170365] THEMultipeerSession initialized peer 1449510457162.408
2015-12-07 18:47:37.191 ThaliTest[408:170365] jxcore: startBroad,casting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-07 18:47:37.195 ThaliTest[408:170365] jxcore: stopBroadcasting
2015-12-07 18:47:37.195 ThaliTest[408:170365] THEMultipeerSession stopping peer
2015-12-07 18:47:37.195, ThaliTest[408:170365] multipeer session: stop timer
2015-12-07 18:47:37.196 ThaliTest[408:170365] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2015-12-07 18:47:37.198 ThaliTest[408:170365] jxcore: startB,roadcasting
,2015-12-07 18:47:37.204 ThaliTest[408:170365] server: starting 1449510457198.408.i5PGSQ==
2015-12-07 18:47:37.205 ThaliTest[408:170365] multipeer session: start timer: 0x15f68540
2015-12-07 18:47:37.206 ThaliTest[408:170365] THEMultipeerSession initializ,ed peer 1449510457198.408
2015-12-07 18:47:37.206 ThaliTest[408:170365] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.223 ThaliTest[408:170365] jxcore: stopBroadcasting
,2015-12-07 18:47:37.230 ThaliTest[408:170365] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.232 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:47:37.235 ThaliTest[408:170365] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.244 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:37.251 ThaliTest[408:170365] server: starting 1449510457243.408.QqQ9yw==
,2015-12-07 18:47:37.253 ThaliTest[408:170365] multipeer session: start timer: 0x15f694e0
,2015-12-07 18:47:37.257 ThaliTest[408:170365] THEMultipeerSession initialized peer 1449510457243.408
,2015-12-07 18:47:37.263 ThaliTest[408:170365] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.268 ThaliTest[408:170365] jxcore: stopBroadcasting
,2015-12-07 18:47:37.269 ThaliTest[408:170365] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.270 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:47:37.272 ThaliTest[408:170365] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.281 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:37.285 ThaliTest[408:170365] server: starting 1449510457280.408.3ALwvA==
,2015-12-07 18:47:37.286 ThaliTest[408:170365] multipeer session: start timer: 0x15f69300
,2015-12-07 18:47:37.290 ThaliTest[408:170365] THEMultipeerSession initialized peer 1449510457280.408
,2015-12-07 18:47:37.294 ThaliTest[408:170365] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.303 ThaliTest[408:170365] jxcore: stopBroadcasting
,2015-12-07 18:47:37.303 ThaliTest[408:170365] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.304 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:47:37.305 ThaliTest[408:170365] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.312 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:37.315 ThaliTest[408:170365] server: starting 1449510457311.408.yWNuKg==
,2015-12-07 18:47:37.317 ThaliTest[408:170365] multipeer session: start timer: 0x178d3540
,2015-12-07 18:47:37.320 ThaliTest[408:170365] THEMultipeerSession initialized peer 1449510457311.408
,2015-12-07 18:47:37.324 ThaliTest[408:170365] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.326 ThaliTest[408:170365] jxcore: stopBroadcasting
,2015-12-07 18:47:37.327 ThaliTest[408:170365] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.328 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:47:37.329 ThaliTest[408:170365] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.336 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:37.339 ThaliTest[408:170365] server: starting 1449510457335.408.Z5qP9w==
,2015-12-07 18:47:37.340 ThaliTest[408:170365] multipeer session: start timer: 0x178d32e0
,2015-12-07 18:47:37.342 ThaliTest[408:170365] THEMultipeerSession initialized peer 1449510457335.408
,2015-12-07 18:47:37.346 ThaliTest[408:170365] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.350 ThaliTest[408:170365] jxcore: stopBroadcasting
,2015-12-07 18:47:37.351 ThaliTest[408:170365] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.352 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:47:37.353 ThaliTest[408:170365] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.359 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:37.362 ThaliTest[408:170365] server: starting 1449510457359.408.u7pPAQ==
,2015-12-07 18:47:37.364 ThaliTest[408:170365] multipeer session: start timer: 0x178d5f70
,2015-12-07 18:47:37.367 ThaliTest[408:170365] THEMultipeerSession initialized peer 1449510457359.408
,2015-12-07 18:47:37.369 ThaliTest[408:170365] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.374 ThaliTest[408:170365] jxcore: stopBroadcasting
,2015-12-07 18:47:37.375 ThaliTest[408:170365] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.376 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:47:37.376 ThaliTest[408:170365] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-07 18:47:37.963 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:37.968 ThaliTest[408:170365] server: starting 1449510457963.408.Gh9qQg==
2015-12-07 18:47:37.969 ThaliTest[408:170365] multipeer session: start timer: 0x178d5930
2015-12-07 18:47:37.969 ThaliTest[408:170365] THEMultipeerSession initializ,ed peer 1449510457963.408
2015-12-07 18:47:37.970 ThaliTest[408:170365] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.988 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:37.990 ThaliTest[408:170365] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2015-12-07 18:47:37.998 ThaliTest[408:170365] jxcore: stopBroadcasting
,2015-12-07 18:47:38.000 ThaliTest[408:170365] THEMultipeerSession stopping peer
,2015-12-07 18:47:38.003 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:47:38.008 ThaliTest[408:170365] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-07 18:47:42.674 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:42.678 ThaliTest[408:170365] server: starting 1449510462674.408.MgWX9g==
2015-12-07 18:47:42.679 ThaliTest[408:170365] multipeer session: start timer: 0x15f70830
2015-12-07 18:47:42.679 ThaliTest[408:170365] THEMultipeerSession initializ,ed peer 1449510462674.408
2015-12-07 18:47:42.680 ThaliTest[408:170365] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-07 18:47:42.682 ThaliTest[408:170365] jxcore: connect foobar
2015-12-07 18:4,7:42.683 ThaliTest[408:170365] client: unknown peer foobar
2015-12-07 18:47:42.684 ThaliTest[408:170365] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2015-12-07 18:47:42.688 ThaliTest[408:170365] jxcore: stopBroadcasting
,2015-12-07 18:47:42.688 ThaliTest[408:170365] THEMultipeerSession stopping peer
,2015-12-07 18:47:42.689 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:47:42.690 ThaliTest[408:170365] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-07 18:47:43.522 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:43.526 ThaliTest[408:170365] server: starting 1449510463521.408.hfylJQ==
2015-12-07 18:47:43.527 ThaliTest[408:170365] multipeer session: start timer: 0x178daaf0
2015-12-07 18:47:43.528 ThaliTest[408:170365] THEMultipeerSession initializ,ed peer 1449510463521.408
2015-12-07 18:47:43.528 ThaliTest[408:170365] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-07 18:47:43.531 ThaliTest[408:170365] jxcore: disconnect
2015-12-07 18:47:43,.531 ThaliTest[408:170365] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2015-12-07 18:47:43.534 ThaliTest[408:170365] jxcore: stopBroadcasting
2015-12-07 18:47:43.537 ThaliTest[408:170365] THEMultipeerSession stopping peer
2015-12-07 18:47:43.538 ThaliTest[408:170365] multipeer session: stop timer
2015-12-07 18:47:43.538 Th,aliTest[408:170365] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-07 18:47:48.363 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:48.367 ThaliTest[408:170365] server: starting 1449510468363.408.sJcxPg==
2015-12-07 18:47:48.368 ThaliTest[408:170365] multipeer session: start timer: 0x178ddd10
2015-12-07 18:47:48.369 ThaliTest[408:170365] THEMultipeerSession initializ,ed peer 1449510468363.408
2015-12-07 18:47:48.369 ThaliTest[408:170365] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2015-12-07 18:47:49.501 ThaliTest[408:170140] client: found peer: 1449510468488.416.gJkiTg==
2015-12-07 18:47:49.505 ThaliTest[408:170365] jxcore: connect 1449510468488.416.gJkiTg==
,2015-12-07 18:47:49.506 ThaliTest[408:170365] client session: connect
,2015-12-07 18:47:49.508 ThaliTest[408:170365] client session: stateChange:0->1 1449510468488.416.gJkiTg==
,2015-12-07 18:47:49.563 ThaliTest[408:170140] client: found peer: 1449510469411.383.Wmi/Ew==
2015-12-07 18:47:49.566 ThaliTest[408:170365] jxcore: connect 1449510469411.383.Wmi/Ew==
2015-12-07 18:47:49.567 ThaliTest[408:170365] client session: connect
2,015-12-07 18:47:49.570 ThaliTest[408:170365] client session: stateChange:0->1 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:49.770 ThaliTest[408:170140] client: found peer: 1449510468177.375.Xvfalg==
,2015-12-07 18:47:49.771 ThaliTest[408:170365] jxcore: connect 1449510468177.375.Xvfalg==
2015-12-07 18:47:49.773 ThaliTest[408:170365] client session: connect
2015-12-07 18:47:49.773 ThaliTest[408:170365] client session: stateChange:0->1 1449510468177.375.Xvfalg==
,2015-12-07 18:47:50.101 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:47:50.101 ThaliTest[408:170140] multipeer session: stop timer
2015-12-07 18:47:50.102 ThaliTest[408:170140] multipeer session: start timer: 0x178ddd10
,2015-12-07 18:47:50.102 ThaliTest[408:170140] server session: connect
,2015-12-07 18:47:50.109 ThaliTest[408:170140] server session: stateChange:0->1 1449510468177.375
,2015-12-07 18:47:50.131 ThaliTest[408:170140] server: accepting invitation 1449510468177.375
,2015-12-07 18:47:50.239 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:47:50.239 ThaliTest[408:170140] multipeer session: stop timer
2015-12-07 18:47:50.240 ThaliTest[408:170140] multipeer session: start timer: 0x178ddd10
2015-12-07 18:47:50.240 ThaliTest[408:170140] server session: connect
2015-12-07 18:47:50.240 ThaliTest[408:170140] server session: stateChange:0->1 1449510469411.383
,2015-12-07 18:47:50.249 ThaliTest[408:170140] server: accepting invitation 1449510469411.383
,2015-12-07 18:47:50.535 ThaliTest[408:170140] multipeer session: reset timer
,2015-12-07 18:47:50.536 ThaliTest[408:170140] multipeer session: stop timer
,2015-12-07 18:47:50.538 ThaliTest[408:170140] multipeer session: start timer: 0x178ddd10
,2015-12-07 18:47:50.538 ThaliTest[408:170140] server session: connect
,2015-12-07 18:47:50.538 ThaliTest[408:170140] server session: stateChange:0->1 1449510468488.416
,2015-12-07 18:47:50.544 ThaliTest[408:170140] server: accepting invitation 1449510468488.416
,2015-12-07 18:47:53.255 ThaliTest[408:170491] client session: connected
,2015-12-07 18:47:53.259 ThaliTest[408:170491] client session: stateChange:1->2 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:53.341 ThaliTest[408:170422] client session: fireConnectCallback: 1449510469411.383.Wmi/Ew==
2015-12-07 18:47:53.342 ThaliTest[408:170422] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-07 18:47:53.347 ThaliTest[408:170365] jxcore: disconnect
,2015-12-07 18:47:53.348 ThaliTest[408:170365] client session: disconnectFromPeer: 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:53.349 ThaliTest[408:170365] client session: disconnect
,2015-12-07 18:47:53.349 ThaliTest[408:170365] client session: stateChange:2->0 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:53.385 ThaliTest[408:170491] client session: connected
,2015-12-07 18:47:53.386 ThaliTest[408:170491] client session: stateChange:1->2 1449510468488.416.gJkiTg==
,2015-12-07 18:47:53.389 ThaliTest[408:170495] server session: connected
,2015-12-07 18:47:53.390 ThaliTest[408:170495] server session: stateChange:1->2 1449510469411.383
,2015-12-07 18:47:53.392 ThaliTest[408:170365] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2015-12-07 18:47:53.466 ThaliTest[408:170140] server relay: socket disconnected
,2015-12-07 18:47:53.467 ThaliTest[408:170140] server relay: 0x15f82810 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:53.480 ThaliTest[408:170495] server session: not connected 1449510469411.383
,2015-12-07 18:47:53.639 ThaliTest[408:170495] server session: connected
,2015-12-07 18:47:53.641 ThaliTest[408:170495] server session: stateChange:1->2 1449510468488.416
,2015-12-07 18:47:53.647 ThaliTest[408:170140] server relay: socket disconnected
2015-12-07 18:47:53.647 ThaliTest[408:170140] server relay: 0x15f80e60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:53.715 ThaliTest[408:170422] server session: not connected 1449510468488.416
,2015-12-07 18:47:53.844 ThaliTest[408:170422] client session: fireConnectCallback: 1449510468488.416.gJkiTg==
,2015-12-07 18:47:53.845 ThaliTest[408:170422] jxcore: connect: success
ok 78 Should be able to connect without error
ok 79 Port should be within range
,2015-12-07 18:47:53.854 ThaliTest[408:170365] jxcore: disconnect
,2015-12-07 18:47:53.855 ThaliTest[408:170365] client session: disconnectFromPeer: 1449510468488.416.gJkiTg==
,2015-12-07 18:47:53.857 ThaliTest[408:170365] client session: disconnect
,2015-12-07 18:47:53.861 ThaliTest[408:170365] client session: stateChange:2->0 1449510468488.416.gJkiTg==
,2015-12-07 18:47:53.889 ThaliTest[408:170365] jxcore: disconnect: success
ok 80 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,not ok 81 .end() called twice
  ---
    operator: fail
  ...
,2015-12-07 18:47:53.968 ThaliTest[408:170462] server session: connected
2015-12-07 18:47:53.968 ThaliTest[408:170462] server session: stateChange:1->2 1449510468177.375
,2015-12-07 18:47:53.975 ThaliTest[408:170491] client session: connected
,2015-12-07 18:47:53.976 ThaliTest[408:170491] client session: stateChange:1->2 1449510468177.375.Xvfalg==
,2015-12-07 18:47:53.991 ThaliTest[408:170140] server relay: socket disconnected
,2015-12-07 18:47:53.991 ThaliTest[408:170140] server relay: 0x15f7f0f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:54.017 ThaliTest[408:170491] client session: fireConnectCallback: 1449510468177.375.Xvfalg==
,2015-12-07 18:47:54.017 ThaliTest[408:170491] jxcore: connect: success
,ok 82 Should be able to connect without error
,ok 83 Port should be within range
,2015-12-07 18:47:54.022 ThaliTest[408:170365] jxcore: disconnect
,2015-12-07 18:47:54.022 ThaliTest[408:170365] client session: disconnectFromPeer: 1449510468177.375.Xvfalg==
,2015-12-07 18:47:54.023 ThaliTest[408:170365] client session: disconnect
,2015-12-07 18:47:54.023 ThaliTest[408:170365] client session: stateChange:2->0 1449510468177.375.Xvfalg==
,2015-12-07 18:47:54.034 ThaliTest[408:170365] jxcore: disconnect: success
,ok 84 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,not ok 85 .end() called twice
,  ---
,    operator: fail
,  ...
,2015-12-07 18:47:54.064 ThaliTest[408:170475] server session: not connected 1449510468177.375
,calling stopBroadcasting
,2015-12-07 18:47:54.095 ThaliTest[408:170365] jxcore: stopBroadcasting
2015-12-07 18:47:54.096 ThaliTest[408:170365] THEMultipeerSession stopping peer
,2015-12-07 18:47:54.096 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:47:54.101 ThaliTest[408:170365] server session: disconnect
,2015-12-07 18:47:54.118 ThaliTest[408:170365] server session: stateChange:2->0 1449510468177.375
,2015-12-07 18:47:54.126 ThaliTest[408:170365] server session: disconnect
,2015-12-07 18:47:54.128 ThaliTest[408:170365] server session: stateChange:2->0 1449510468488.416
,2015-12-07 18:47:54.358 ThaliTest[408:170365] server session: disconnect
2015-12-07 18:47:54.358 ThaliTest[408:170365] server session: stateChange:2->0 1449510469411.383
2015-12-07 18:47:54.360 ThaliTest[408:170365] jxcore: stopBroadcasting: success
sto,pBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-07 18:47:55.496 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:47:55.500 ThaliTest[408:170365] server: starting 1449510475496.408.7GdpBQ==
2015-12-07 18:47:55.501 ThaliTest[408:170365] multipeer session: start timer: 0x15f7a350
2015-12-07 18:47:55.502 ThaliTest[408:170365] THEMultipeerSession initializ,ed peer 1449510475496.408
2015-12-07 18:47:55.502 ThaliTest[408:170365] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error
,2015-12-07 18:47:56.217 ThaliTest[408:170140] client: found peer: 1449510468488.416.gJkiTg==
2015-12-07 18:47:56.220 ThaliTest[408:170365] jxcore: connect 1449510468488.416.gJkiTg==
2015-12-07 18:47:56.221 ThaliTest[408:170365] client session: connect
2,015-12-07 18:47:56.221 ThaliTest[408:170365] client session: stateChange:0->1 1449510468488.416.gJkiTg==
,2015-12-07 18:47:56.373 ThaliTest[408:170140] client: found peer: 1449510475581.416.zFnyqQ==
,2015-12-07 18:47:56.375 ThaliTest[408:170365] jxcore: connect 1449510475581.416.zFnyqQ==
,2015-12-07 18:47:56.376 ThaliTest[408:170365] client session: connect
2015-12-07 18:47:56.377 ThaliTest[408:170365] client session: stateChange:0->1 1449510475581.416.zFnyqQ==
,2015-12-07 18:47:56.852 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:47:56.853 ThaliTest[408:170140] multipeer session: stop timer
2015-12-07 18:47:56.853 ThaliTest[408:170140] multipeer session: start timer: 0x15f7a350
2015-12-07 ,18:47:56.854 ThaliTest[408:170140] server session: connect
2015-12-07 18:47:56.854 ThaliTest[408:170140] server session: stateChange:0->1 1449510475581.416
,2015-12-07 18:47:56.866 ThaliTest[408:170140] server: accepting invitation 1449510475581.416
2015-12-07 18:47:56.866 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:47:56.867 ThaliTest[408:170140] multipeer session: stop timer
2015-12,-07 18:47:56.867 ThaliTest[408:170140] multipeer session: start timer: 0x15f7a350
2015-12-07 18:47:56.867 ThaliTest[408:170140] server session: connect
2015-12-07 18:47:56.867 ThaliTest[408:170140] server session: stateChange:0->1 1449510476527.383
,2015-12-07 18:47:56.885 ThaliTest[408:170140] server: accepting invitation 1449510476527.383
,2015-12-07 18:47:56.920 ThaliTest[408:170140] client: found peer: 1449510476527.383.t1iPAw==
2015-12-07 18:47:56.921 ThaliTest[408:170365] jxcore: connect 1449510476527.383.t1iPAw==
2015-12-07 18:47:56.922 ThaliTest[408:170365] client session: connect
2015-12-07 18:47:56.922 ThaliTest[408:170365] client session: stateChange:0->1 1449510476527.383.t1iPAw==
,2015-12-07 18:47:57.617 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:47:57.618 ThaliTest[408:170140] multipeer session: stop timer
2015-12-07 18:47:57.618 ThaliTest[408:170140] multipeer session: start timer: 0x15f7a350
,2015-12-07 18:47:57.618 ThaliTest[408:170140] server session: connect
2015-12-07 18:47:57.618 ThaliTest[408:170140] server session: stateChange:0->1 1449510476485.375
,2015-12-07 18:47:57.622 ThaliTest[408:170140] server: accepting invitation 1449510476485.375
,2015-12-07 18:47:57.701 ThaliTest[408:170140] client: found peer: 1449510476485.375./zzCMA==
,2015-12-07 18:47:57.702 ThaliTest[408:170365] jxcore: connect 1449510476485.375./zzCMA==
2015-12-07 18:47:57.702 ThaliTest[408:170365] client session: connect
,2015-12-07 18:47:57.702 ThaliTest[408:170365] client session: stateChange:0->1 1449510476485.375./zzCMA==
,2015-12-07 18:47:59.728 ThaliTest[408:170422] client session: connected
2015-12-07 18:47:59.729 ThaliTest[408:170422] client session: stateChange:1->2 1449510475581.416.zFnyqQ==
,2015-12-07 18:47:59.739 ThaliTest[408:170422] client session: fireConnectCallback: 1449510475581.416.zFnyqQ==
2015-12-07 18:47:59.742 ThaliTest[408:170422] jxcore: connect: success
ok 87 Should be able to connect without error
ok 88 Port should be withi,n range
2015-12-07 18:47:59.747 ThaliTest[408:170365] jxcore: connect 1449510475581.416.zFnyqQ==
2015-12-07 18:47:59.749 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510475581.416.zFnyqQ==
2015-12-07 18:47:59.750 ThaliTest[408:170365] jx,core: connect: fail: Aleady connecting
,ok 89 Should fail on double connect
2015-12-07 18:47:59.752 ThaliTest[408:170365] jxcore: disconnect
2015-12-07 18:47:59.753 ThaliTest[408:170365] client session: disconnectFromPeer: 1449510475581.416.zFnyqQ==
,2015-12-07 18:47:59.754 ThaliTest[408:170365] client session: disconnect
2015-12-07 18:47:59.754 ThaliTest[408:170365] client session: stateChange:2->0 1449510475581.416.zFnyqQ==
,2015-12-07 18:47:59.757 ThaliTest[408:170422] server session: connected
2015-12-07 18:47:59.757 ThaliTest[408:170422] server session: stateChange:1->2 1449510475581.416
,2015-12-07 18:47:59.802 ThaliTest[408:170140] server relay: socket disconnected
,2015-12-07 18:47:59.805 ThaliTest[408:170140] server relay: 0x15f80490 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:59.879 ThaliTest[408:170365] jxcore: disconnect: success
,ok 90 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2015-12-07 18:47:59.975 ThaliTest[408:170424] server session: not connected 1449510475581.416
,2015-12-07 18:48:00.383 ThaliTest[408:170475] client session: connected
2015-12-07 18:48:00.383 ThaliTest[408:170475] client session: stateChange:1->2 1449510476527.383.t1iPAw==
,2015-12-07 18:48:00.446 ThaliTest[408:170475] client session: fireConnectCallback: 1449510476527.383.t1iPAw==
2015-12-07 18:48:00.447 ThaliTest[408:170475] jxcore: connect: success
,ok 91 Should be able to connect without error
,ok 92 Port should be within range
,2015-12-07 18:48:00.451 ThaliTest[408:170365] jxcore: connect 1449510476527.383.t1iPAw==
2015-12-07 18:48:00.451 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510476527.383.t1iPAw==
2015-12-07 18:48:00.451 ThaliTest[408:170365] jxcore: connect: fail: Aleady connecting
ok 93 Should fail on double connect
,2015-12-07 18:48:00.453 ThaliTest[408:170365] jxcore: disconnect
,2015-12-07 18:48:00.454 ThaliTest[408:170365] client session: disconnectFromPeer: 1449510476527.383.t1iPAw==
2015-12-07 18:48:00.455 ThaliTest[408:170365] client session: disconnect
2015-12-07 18:48:00.455 ThaliTest[408:170365] client session: stateChange:2->0 1449510476527.383.t1iPAw==
,2015-12-07 18:48:00.465 ThaliTest[408:170365] jxcore: disconnect: success
ok 94 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
not ok 95 .end() called twice
  ---
    operator: fail
  ...
,2015-12-07 18:48:00.645 ThaliTest[408:170475] server session: connected
2015-12-07 18:48:00.645 ThaliTest[408:170475] server session: stateChange:1->2 1449510476527.383
,2015-12-07 18:48:00.712 ThaliTest[408:170140] server relay: socket disconnected
,2015-12-07 18:48:00.712 ThaliTest[408:170140] server relay: 0x15f90660 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting
,2015-12-07 18:48:01.436 ThaliTest[408:170365] jxcore: stopBroadcasting
2015-12-07 18:48:01.437 ThaliTest[408:170365] THEMultipeerSession stopping peer
2015-12-07 18:48:01.437 ThaliTest[408:170365] multipeer session: stop timer
2015-12-07 18:48:01.437 Th,aliTest[408:170365] client session: disconnect
2015-12-07 18:48:01.438 ThaliTest[408:170365] client session: stateChange:1->0 1449510468488.416.gJkiTg==
2015-12-07 18:48:01.439 ThaliTest[408:170365] client session: disconnect
2015-12-07 18:48:01.439 Tha,liTest[408:170365] client session: stateChange:1->0 1449510476485.375./zzCMA==
,2015-12-07 18:48:01.547 ThaliTest[408:170365] server session: disconnect
,2015-12-07 18:48:01.567 ThaliTest[408:170365] server session: stateChange:2->0 1449510476527.383
,2015-12-07 18:48:01.583 ThaliTest[408:170365] server session: disconnect
2015-12-07 18:48:01.583 ThaliTest[408:170365] server session: stateChange:1->0 1449510476485.375
,2015-12-07 18:48:01.684 ThaliTest[408:170365] server session: disconnect
2015-12-07 18:48:01.684 ThaliTest[408:170365] server session: stateChange:2->0 1449510475581.416
2015-12-07 18:48:01.685 ThaliTest[408:170365] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-07 18:48:09.176 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:48:09.180 ThaliTest[408:170365] server: starting 1449510489175.408.1RR9xA==
2015-12-07 18:48:09.181 ThaliTest[408:170365] multipeer session: start timer: 0x17831480
2015-12-07 18:48:09.181 ThaliTest[408:170365] THEMultipeerSession initializ,ed peer 1449510489175.408
2015-12-07 18:48:09.181 ThaliTest[408:170365] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error
,2015-12-07 18:48:10.538 ThaliTest[408:170140] client: found peer: 1449510489481.375.tffILg==
2015-12-07 18:48:10.539 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:48:10.539 ThaliTest[408:170140] multipeer session: stop timer
2015-12,-07 18:48:10.540 ThaliTest[408:170140] multipeer session: start timer: 0x17831480
2015-12-07 18:48:10.541 ThaliTest[408:170140] server session: connect
2015-12-07 18:48:10.541 ThaliTest[408:170140] server session: stateChange:0->1 1449510491347.383
2015,-12-07 18:48:10.540 ThaliTest[408:170365] jxcore: connect 1449510489481.375.tffILg==
2015-12-07 18:48:10.542 ThaliTest[408:170365] client session: connect
2015-12-07 18:48:10.544 ThaliTest[408:170365] client session: stateChange:0->1 1449510489481.375.tf,fILg==
2015-12-07 18:48:10.551 ThaliTest[408:170140] server: accepting invitation 1449510491347.383
,2015-12-07 18:48:10.602 ThaliTest[408:170140] multipeer session: reset timer
,2015-12-07 18:48:10.603 ThaliTest[408:170140] multipeer session: stop timer
,2015-12-07 18:48:10.605 ThaliTest[408:170140] multipeer session: start timer: 0x17831480
,2015-12-07 18:48:10.607 ThaliTest[408:170140] server session: connect
,2015-12-07 18:48:10.612 ThaliTest[408:170140] server session: stateChange:0->1 1449510489481.375
,2015-12-07 18:48:10.629 ThaliTest[408:170140] server: accepting invitation 1449510489481.375
,2015-12-07 18:48:11.688 ThaliTest[408:170140] client: found peer: 1449510491347.383.nrOfbw==
,2015-12-07 18:48:11.691 ThaliTest[408:170365] jxcore: connect 1449510491347.383.nrOfbw==
,2015-12-07 18:48:11.692 ThaliTest[408:170365] client session: connect
2015-12-07 18:48:11.693 ThaliTest[408:170365] client session: stateChange:0->1 1449510491347.383.nrOfbw==
,2015-12-07 18:48:12.031 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:48:12.032 ThaliTest[408:170140] multipeer session: stop timer
2015-12-07 18:48:12.032 ThaliTest[408:170140] multipeer session: start timer: 0x17831480
2015-12-07 ,18:48:12.033 ThaliTest[408:170140] server session: connect
2015-12-07 18:48:12.033 ThaliTest[408:170140] server session: stateChange:0->1 1449510491053.416
,2015-12-07 18:48:12.047 ThaliTest[408:170140] server: accepting invitation 1449510491053.416
,2015-12-07 18:48:12.049 ThaliTest[408:170140] client: found peer: 1449510491053.416.ZCqZnQ==
2015-12-07 18:48:12.059 ThaliTest[408:170365] jxcore: connect 1449510491053.416.ZCqZnQ==
2015-12-07 18:48:12.059 ThaliTest[408:170365] client session: connect
2,015-12-07 18:48:12.060 ThaliTest[408:170365] client session: stateChange:0->1 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:13.524 ThaliTest[408:170422] server session: connected
2015-12-07 18:48:13.526 ThaliTest[408:170422] server session: stateChange:1->2 1449510491347.383
,2015-12-07 18:48:13.534 ThaliTest[408:170140] server relay: socket disconnected
2015-12-07 18:48:13.535 ThaliTest[408:170140] server relay: 0x15f85ce0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:13.571 ThaliTest[408:170424] server session: not connected 1449510491347.383
,2015-12-07 18:48:14.656 ThaliTest[408:170424] server session: connected
2015-12-07 18:48:14.657 ThaliTest[408:170424] server session: stateChange:1->2 1449510489481.375
,2015-12-07 18:48:14.700 ThaliTest[408:170140] server relay: socket disconnected
2015-12-07 18:48:14.700 ThaliTest[408:170140] server relay: 0x15f90730 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:14.720 ThaliTest[408:170422] server session: not connected 1449510489481.375
,2015-12-07 18:48:14.879 ThaliTest[408:170422] client session: connected
2015-12-07 18:48:14.881 ThaliTest[408:170422] client session: stateChange:1->2 1449510491347.383.nrOfbw==
,2015-12-07 18:48:14.887 ThaliTest[408:170422] client session: fireConnectCallback: 1449510491347.383.nrOfbw==
2015-12-07 18:48:14.887 ThaliTest[408:170422] jxcore: connect: success
ok 97 Should be able to connect without error
,ok 98 Port should be within range
,2015-12-07 18:48:14.892 ThaliTest[408:170365] jxcore: disconnect
2015-12-07 18:48:14.893 ThaliTest[408:170365] client session: disconnectFromPeer: 1449510491347.383.nrOfbw==
2015-12-07 18:48:14.893 ThaliTest[408:170365] client session: disconnect
2015-1,2-07 18:48:14.894 ThaliTest[408:170365] client session: stateChange:2->0 1449510491347.383.nrOfbw==
,2015-12-07 18:48:14.974 ThaliTest[408:170365] jxcore: disconnect: success
ok 99 Should be able to disconnect without error
,2015-12-07 18:48:14.977 ThaliTest[408:170365] jxcore: disconnect
2015-12-07 18:48:14.978 ThaliTest[408:170365] jxcore: disconnect: fail
ok 100 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,2015-12-07 18:48:15.176 ThaliTest[408:170422] server session: connected
2015-12-07 18:48:15.176 ThaliTest[408:170422] server session: stateChange:1->2 1449510491053.416
,2015-12-07 18:48:15.190 ThaliTest[408:170495] client session: connected
2015-12-07 18:48:15.190 ThaliTest[408:170495] client session: stateChange:1->2 1449510489481.375.tffILg==
,2015-12-07 18:48:15.243 ThaliTest[408:170140] server relay: socket disconnected
,2015-12-07 18:48:15.244 ThaliTest[408:170140] server relay: 0x178fb9d0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:15.251 ThaliTest[408:170422] client session: fireConnectCallback: 1449510489481.375.tffILg==
,2015-12-07 18:48:15.252 ThaliTest[408:170422] jxcore: connect: success
ok 101 Should be able to connect without error
,ok 102 Port should be within range
,2015-12-07 18:48:15.259 ThaliTest[408:170365] jxcore: disconnect
,2015-12-07 18:48:15.260 ThaliTest[408:170365] client session: disconnectFromPeer: 1449510489481.375.tffILg==
,2015-12-07 18:48:15.260 ThaliTest[408:170365] client session: disconnect
2015-12-07 18:48:15.262 ThaliTest[408:170365] client session: stateChange:2->0 1449510489481.375.tffILg==
,2015-12-07 18:48:15.278 ThaliTest[408:170365] jxcore: disconnect: success
,ok 103 Should be able to disconnect without error
,2015-12-07 18:48:15.282 ThaliTest[408:170365] jxcore: disconnect
,2015-12-07 18:48:15.283 ThaliTest[408:170365] jxcore: disconnect: fail
,ok 104 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,not ok 105 .end() called twice
,  ---
,    operator: fail
,  ...
,2015-12-07 18:48:15.337 ThaliTest[408:170424] server session: not connected 1449510491053.416
,2015-12-07 18:48:15.437 ThaliTest[408:170422] client session: connected
,2015-12-07 18:48:15.439 ThaliTest[408:170422] client session: stateChange:1->2 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:15.453 ThaliTest[408:170424] client session: fireConnectCallback: 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:15.455 ThaliTest[408:170424] jxcore: connect: success
,ok 106 Should be able to connect without error
,ok 107 Port should be within range
,2015-12-07 18:48:15.462 ThaliTest[408:170365] jxcore: disconnect
,2015-12-07 18:48:15.463 ThaliTest[408:170365] client session: disconnectFromPeer: 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:15.464 ThaliTest[408:170365] client session: disconnect
,2015-12-07 18:48:15.465 ThaliTest[408:170365] client session: stateChange:2->0 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:15.550 ThaliTest[408:170365] jxcore: disconnect: success
,ok 108 Should be able to disconnect without error
,2015-12-07 18:48:15.556 ThaliTest[408:170365] jxcore: disconnect
,2015-12-07 18:48:15.556 ThaliTest[408:170365] jxcore: disconnect: fail
,ok 109 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,not ok 110 .end() called twice
,  ---
,    operator: fail
,  ...
,calling stopBroadcasting
,2015-12-07 18:48:15.621 ThaliTest[408:170365] jxcore: stopBroadcasting
,2015-12-07 18:48:15.621 ThaliTest[408:170365] THEMultipeerSession stopping peer
,2015-12-07 18:48:15.622 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:48:15.659 ThaliTest[408:170365] server session: disconnect
,2015-12-07 18:48:15.661 ThaliTest[408:170365] server session: stateChange:2->0 1449510489481.375
,2015-12-07 18:48:16.454 ThaliTest[408:170365] server session: disconnect
2015-12-07 18:48:16.455 ThaliTest[408:170365] server session: stateChange:2->0 1449510491053.416
2015-12-07 18:48:16.456 ThaliTest[408:170365] server session: disconnect
2015-12-07, 18:48:16.458 ThaliTest[408:170365] server session: stateChange:2->0 1449510491347.383
,2015-12-07 18:48:16.465 ThaliTest[408:170365] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-07 18:48:27.110 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:48:27.114 ThaliTest[408:170365] server: starting 1449510507109.408.rby7cA==
2015-12-07 18:48:27.115 ThaliTest[408:170365] multipeer session: start timer: 0x15f7f3a0
2015-12-07 18:48:27.115 ThaliTest[408:170365] THEMultipeerSession initialized peer 1449510507109.408
,2015-12-07 18:48:27.118 ThaliTest[408:170365] jxcore: startBroadcasting: success
,ok 111 Should be able to call startBroadcasting without error
echo server started
,2015-12-07 18:48:27.905 ThaliTest[408:170140] client: found peer: 1449510506003.383.i2Azhg==
[{"peerIdentifier":"1449510506003.383.i2Azhg==","peerName":"(null)","peerAvailable":true}]
2015-12-07 18:48:27.908 ThaliTest[408:170140] client: found peer: 1449,510506165.416.wWLXyQ==
2015-12-07 18:48:27.910 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:27.911 ThaliTest[408:170365] client session: connect
2015-12-07 18:48:27.912 ThaliTest[408:170365] client session: stateChan,ge:0->1 1449510506003.383.i2Azhg==
,[{"peerIdentifier":"1449510506165.416.wWLXyQ==","peerName":"(null)","peerAvailable":true}]
2015-12-07 18:48:27.938 ThaliTest[408:170365] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:27.939 ThaliTest[408:170365] client session: connect
201,5-12-07 18:48:27.939 ThaliTest[408:170365] client session: stateChange:0->1 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:28.226 ThaliTest[408:170140] client: found peer: 1449510506999.375.Lduuig==
[{"peerIdentifier":"1449510506999.375.Lduuig==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 18:48:28.230 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:28.231 ThaliTest[408:170365] client session: connect
,2015-12-07 18:48:28.232 ThaliTest[408:170365] client session: stateChange:0->1 1449510506999.375.Lduuig==
,2015-12-07 18:48:29.326 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:48:29.326 ThaliTest[408:170140] multipeer session: stop timer
2015-12-07 18:48:29.327 ThaliTest[408:170140] multipeer session: start timer: 0x15f7f3a0
2015-12-07 ,18:48:29.327 ThaliTest[408:170140] server session: connect
2015-12-07 18:48:29.327 ThaliTest[408:170140] server session: stateChange:0->1 1449510506165.416
,2015-12-07 18:48:29.347 ThaliTest[408:170140] server: accepting invitation 1449510506165.416
,2015-12-07 18:48:29.392 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:48:29.393 ThaliTest[408:170140] multipeer session: stop timer
2015-12-07 18:48:29.393 ThaliTest[408:170140] multipeer session: start timer: 0x15f7f3a0
2015-12-07 18:48:29.393 ThaliTest[408:170140] server session: connect
2015-12-07 18:48:29.394 ThaliTest[408:170140] server session: stateChange:0->1 1449510506003.383
,2015-12-07 18:48:29.414 ThaliTest[408:170140] server: accepting invitation 1449510506003.383
,2015-12-07 18:48:29.903 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:48:29.904 ThaliTest[408:170140] multipeer session: stop timer
2015-12-07 18:48:29.904 ThaliTest[408:170140] multipeer session: start timer: 0x15f7f3a0
2015-12-07 18:48:29.904 ThaliTest[408:170140] server session: connect
2015-12-07 18:48:29.904 ThaliTest[408:170140] server session: stateChange:0->1 1449510506999.375
2015-12-07 18:48:29.913 ThaliTest[408:170140] server: accepting invitation 1449510506999.375
,2015-12-07 18:48:31.418 ThaliTest[408:170711] client session: connected
2015-12-07 18:48:31.419 ThaliTest[408:170711] client session: stateChange:1->2 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:31.480 ThaliTest[408:170709] client session: fireConnectCallback: 1449510506165.416.wWLXyQ==
2015-12-07 18:48:31.480 ThaliTest[408:170709] jxcore: connect: success
,ok 112 Should be able to connect without error
,ok 113 Port should be within range
,ok 114 First connect should succeed
,2015-12-07 18:48:31.509 ThaliTest[408:170140] client: relay established
2015-12-07 18:48:31.510 ThaliTest[408:170140] client: new accepted socket: 0x17837660
,ok 115 the test messages should be equal
ok 116 First send should succeed
,2015-12-07 18:48:31.889 ThaliTest[408:170710] client session: connected
2015-12-07 18:48:31.890 ThaliTest[408:170710] client session: stateChange:1->2 1449510506003.383.i2Azhg==
,2015-12-07 18:48:31.895 ThaliTest[408:170140] client: socket closed
2015-12-07 18:48:31.895 ThaliTest[408:170140] client relay: socket disconnected
2015-12-07 18:48:31.896 ThaliTest[408:170140] client relay: 0x17837660 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:31.896 ThaliTest[408:170140] client session: socket closed: 1449510506165.416.wWLXyQ==
2015-12-07 18:48:31.,896 ThaliTest[408:170140] client session: onLinkFailure: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:31.896 ThaliTest[408:170140] client session: disconnect
,2015-12-07 18:48:31.899 ThaliTest[408:170140] client session: stateChange:2->0 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:31.918 ThaliTest[408:170140] client session: fireConnectionErrorEvent: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:31.924 ThaliTest[408:170365] jxcore: connect 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:31.924 ThaliTest[408:170365] client session: connect
,2015-12-07 18:48:31.925 ThaliTest[408:170365] client session: stateChange:0->1 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:31.938 ThaliTest[408:170708] client session: fireConnectCallback: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:31.938 ThaliTest[408:170708] jxcore: connect: success
,ok 117 Should be able to connect without error
ok 118 Port should be within range
ok 119 First connect should succeed
,2015-12-07 18:48:31.968 ThaliTest[408:170140] client: relay established
2015-12-07 18:48:31.968 ThaliTest[408:170140] client: new accepted socket: 0x15faaed0
,ok 120 the test messages should be equal
,ok 121 First send should succeed
,2015-12-07 18:48:32.086 ThaliTest[408:170140] client: socket closed
2015-12-07 18:48:32.086 ThaliTest[408:170140] client relay: socket disconnected
2015-12-07 18:48:32.087 ThaliTest[408:170140] client relay: 0x15faaed0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:32.087 ThaliTest[408:170140] client session: socket closed: 1449510506003.383.i2Azhg==
2015-12-07 18:48:32.,087 ThaliTest[408:170140] client session: onLinkFailure: 1449510506003.383.i2Azhg==
2015-12-07 18:48:32.087 ThaliTest[408:170140] client session: disconnect
2015-12-07 18:48:32.087 ThaliTest[408:170140] client session: stateChange:2->0 1449510506003.383.i2Azhg==
,2015-12-07 18:48:32.094 ThaliTest[408:170140] client session: fireConnectionErrorEvent: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:32.096 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
,2015-12-07 18:48:32.099 ThaliTest[408:170365] client session: connect
,2015-12-07 18:48:32.101 ThaliTest[408:170365] client session: stateChange:0->1 1449510506003.383.i2Azhg==
,2015-12-07 18:48:32.110 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
,2015-12-07 18:48:32.111 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506003.383.i2Azhg==
,2015-12-07 18:48:32.113 ThaliTest[408:170365] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:32.160 ThaliTest[408:170708] server session: connected
2015-12-07 18:48:32.160 ThaliTest[408:170708] server session: stateChange:1->2 1449510506003.383
,2015-12-07 18:48:32.434 ThaliTest[408:170140] server relay: connected (to port: 5001)
,2015-12-07 18:48:32.491 ThaliTest[408:170710] server session: not connected 1449510506003.383
,2015-12-07 18:48:32.512 ThaliTest[408:170710] server session: connected
2015-12-07 18:48:32.512 ThaliTest[408:170710] server session: stateChange:1->2 1449510506165.416
,2015-12-07 18:48:32.524 ThaliTest[408:170707] client session: connected
2015-12-07 18:48:32.524 ThaliTest[408:170707] client session: stateChange:1->2 1449510506999.375.Lduuig==
,2015-12-07 18:48:32.531 ThaliTest[408:170140] server relay: connected (to port: 5001)
,2015-12-07 18:48:32.609 ThaliTest[408:170707] client session: fireConnectCallback: 1449510506999.375.Lduuig==
,2015-12-07 18:48:32.609 ThaliTest[408:170707] jxcore: connect: success
ok 122 Should be able to connect without error
,ok 123 Port should be within range
,ok 124 First connect should succeed
,2015-12-07 18:48:32.626 ThaliTest[408:170140] client: relay established
2015-12-07 18:48:32.627 ThaliTest[408:170140] client: new accepted socket: 0x15f8ba00
,ok 125 the test messages should be equal
ok 126 First send should succeed
,2015-12-07 18:48:32.937 ThaliTest[408:170140] client: socket closed
2015-12-07 18:48:32.938 ThaliTest[408:170140] client relay: socket disconnected
2015-12-07 18:48:32.938 ThaliTest[408:170140] client relay: 0x15f8ba00 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-07 18:48:32.939 ThaliTest[408:170140] client session: socket closed: 1449510506999.375.Lduuig==
2015-12-07 18:48:32.939 ThaliTest[408:170140] client session: onLinkFailure: 1449510506999.375.Lduuig==
,2015-12-07 18:48:32.939 ThaliTest[408:170140] client session: disconnect
2015-12-07 18:48:32.941 ThaliTest[408:170140] client session: stateChange:2->0 1449510506999.375.Lduuig==
,2015-12-07 18:48:32.946 ThaliTest[408:170140] client session: fireConnectionErrorEvent: 1449510506999.375.Lduuig==
,2015-12-07 18:48:32.949 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
,2015-12-07 18:48:32.949 ThaliTest[408:170365] client session: connect
2015-12-07 18:48:32.950 ThaliTest[408:170365] client session: stateChange:0->1 1449510506999.375.Lduuig==
,2015-12-07 18:48:32.960 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:32.960 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:32.960 ThaliTest[408:170365] jxcore: con,nect: fail: Aleady connecting
2015-12-07 18:48:32.961 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:32.961 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:32.961 ThaliTest[408:170365] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:32.990 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:48:32.991 ThaliTest[408:170140] multipeer session: stop timer
2015-12-07 18:48:32.991 ThaliTest[408:170140] multipeer session: start timer: 0x15f7f3a0
2015-12-07 ,18:48:32.992 ThaliTest[408:170140] server: disconnecting to refresh session (1449510506003.383)
2015-12-07 18:48:32.992 ThaliTest[408:170140] server session: disconnect
2015-12-07 18:48:32.992 ThaliTest[408:170140] server session: stateChange:2->0 1449510506003.383
,2015-12-07 18:48:32.996 ThaliTest[408:170140] server session: connect
2015-12-07 18:48:32.997 ThaliTest[408:170140] server session: stateChange:0->1 1449510506003.383
,2015-12-07 18:48:33.005 ThaliTest[408:170708] server session: not connected 1449510506165.416
,2015-12-07 18:48:33.014 ThaliTest[408:170140] server: accepting invitation 1449510506003.383
,2015-12-07 18:48:33.052 ThaliTest[408:170630] server session: connected
,2015-12-07 18:48:33.052 ThaliTest[408:170630] server session: stateChange:1->2 1449510506999.375
,2015-12-07 18:48:33.083 ThaliTest[408:170140] server relay: connected (to port: 5001)
,2015-12-07 18:48:33.124 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:33.125 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506003.383.i2Azhg==
,2015-12-07 18:48:33.125 ThaliTest[408:170365] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:33.212 ThaliTest[408:170140] multipeer session: reset timer
,2015-12-07 18:48:33.212 ThaliTest[408:170140] multipeer session: stop timer
,2015-12-07 18:48:33.213 ThaliTest[408:170140] multipeer session: start timer: 0x15f7f3a0
,2015-12-07 18:48:33.214 ThaliTest[408:170140] server: disconnecting to refresh session (1449510506165.416)
,2015-12-07 18:48:33.214 ThaliTest[408:170140] server session: disconnect
,2015-12-07 18:48:33.215 ThaliTest[408:170140] server session: stateChange:2->0 1449510506165.416
,2015-12-07 18:48:33.963 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:33.963 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:33.964 ThaliTest[408:170365] jxcore: con,nect: fail: Aleady connecting
2015-12-07 18:48:33.965 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:33.965 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:33.966 Th,aliTest[408:170365] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:34.111 ThaliTest[408:170708] server session: not connected 1449510506999.375
,2015-12-07 18:48:34.134 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:34.135 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506003.383.i2Azhg==
2015-12-07 18:48:34.136 ThaliTest[408:170365] jxcore: con,nect: fail: Aleady connecting
,2015-12-07 18:48:34.222 ThaliTest[408:170140] server session: connect
2015-12-07 18:48:34.222 ThaliTest[408:170140] server session: stateChange:0->1 1449510506165.416
,2015-12-07 18:48:34.241 ThaliTest[408:170140] server: accepting invitation 1449510506165.416
,2015-12-07 18:48:34.533 ThaliTest[408:170140] multipeer session: reset timer
2015-12-07 18:48:34.534 ThaliTest[408:170140] multipeer session: stop timer
,2015-12-07 18:48:34.534 ThaliTest[408:170140] multipeer session: start timer: 0x15f7f3a0
,2015-12-07 18:48:34.535 ThaliTest[408:170140] server: disconnecting to refresh session (1449510506999.375)
,2015-12-07 18:48:34.536 ThaliTest[408:170140] server session: disconnect
,2015-12-07 18:48:34.536 ThaliTest[408:170140] server session: stateChange:2->0 1449510506999.375
,2015-12-07 18:48:34.541 ThaliTest[408:170140] server session: connect
,2015-12-07 18:48:34.541 ThaliTest[408:170140] server session: stateChange:0->1 1449510506999.375
,2015-12-07 18:48:34.558 ThaliTest[408:170140] server: accepting invitation 1449510506999.375
,2015-12-07 18:48:34.968 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:34.968 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:34.968 ThaliTest[408:170365] jxcore: con,nect: fail: Aleady connecting
2015-12-07 18:48:34.968 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:34.969 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:34.969 ThaliTest[408:170365] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:35.150 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
,2015-12-07 18:48:35.150 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506003.383.i2Azhg==
2015-12-07 18:48:35.152 ThaliTest[408:170365] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:35.150 ThaliTest[408:170630] client session: connected
,2015-12-07 18:48:35.154 ThaliTest[408:170630] client session: stateChange:1->2 1449510506003.383.i2Azhg==
,2015-12-07 18:48:35.185 ThaliTest[408:170671] client session: fireConnectCallback: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:35.186 ThaliTest[408:170671] jxcore: connect: success
,ok 127 Should be able to connect without error
,ok 128 Port should be within range
,ok 129 Second connect should succeed
,2015-12-07 18:48:35.208 ThaliTest[408:170140] client: relay established
,2015-12-07 18:48:35.208 ThaliTest[408:170140] client: new accepted socket: 0x15f98050
,2015-12-07 18:48:35.246 ThaliTest[408:170707] client session: connected
2015-12-07 18:48:35.246 ThaliTest[408:170707] client session: stateChange:1->2 1449510506165.416.wWLXyQ==
,ok 130 the test messages should be equal
,ok 131 Second send should succeed
,# setup
,2015-12-07 18:48:35.283 ThaliTest[408:170671] client session: fireConnectCallback: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:35.284 ThaliTest[408:170671] jxcore: connect: success
,ok 132 Should be able to connect without error
,ok 133 Port should be within range
2015-12-07 18:48:35.287 ThaliTest[408:170140] client: socket closed
2015-12-07 18:48:35.288 ThaliTest[408:170140] client relay: socket disconnected
2015-12-07 18:48:35.288 ThaliTest[408:170140] client relay: 0x15f98050, disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
ok 134 Second connect should succeed
2015-12-07 18:48:35.288 ThaliTest[408:170140] clien,t session: socket closed: 1449510506003.383.i2Azhg==
2015-12-07 18:48:35.288 ThaliTest[408:170140] client session: onLinkFailure: 1449510506003.383.i2Azhg==
2015-12-07 18:48:35.288 ThaliTest[408:170140] client session: disconnect
2015-12-07 18:48:35.288, ThaliTest[408:170140] client session: stateChange:2->0 1449510506003.383.i2Azhg==
,2015-12-07 18:48:35.302 ThaliTest[408:170140] client session: fireConnectionErrorEvent: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:35.312 ThaliTest[408:170140] client: relay established
,2015-12-07 18:48:35.312 ThaliTest[408:170140] client: new accepted socket: 0x17826080
,ok 135 the test messages should be equal
,ok 136 Second send should succeed
,not ok 137 .end() called twice
,  ---
,    operator: fail
,  ...
,2015-12-07 18:48:35.604 ThaliTest[408:170140] client: socket closed
,2015-12-07 18:48:35.605 ThaliTest[408:170140] client relay: socket disconnected
,2015-12-07 18:48:35.607 ThaliTest[408:170140] client relay: 0x17826080 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:35,.607 ThaliTest[408:170140] client session: socket closed: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:35.607 ThaliTest[408:170140] client session: onLinkFailure: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:35.609 ThaliTest[408:170140] client session: disconnect
,2015-12-07 18:48:35.611 ThaliTest[408:170140] client session: stateChange:2->0 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:35.635 ThaliTest[408:170140] client session: fireConnectionErrorEvent: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:35.979 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:35.979 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:35.980 ThaliTest[408:170365] jxcore: con,nect: fail: Aleady connecting
2015-12-07 18:48:35.982 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:35.982 ThaliTest[408:170365] client: already connect(ing/ed) to 1449510506999.375.Lduuig==
2015-12-07 18:48:35.982 Th,aliTest[408:170365] jxcore: connect: fail: Aleady connecting
,calling stopBroadcasting
,2015-12-07 18:48:36.089 ThaliTest[408:170365] jxcore: stopBroadcasting
2015-12-07 18:48:36.089 ThaliTest[408:170365] THEMultipeerSession stopping peer
2015-12-07 18:48:36.089 ThaliTest[408:170365] multipeer session: stop timer
2015-12-07 18:48:36.090 Th,aliTest[408:170365] client session: disconnect
,2015-12-07 18:48:36.090 ThaliTest[408:170365] client session: stateChange:1->0 1449510506999.375.Lduuig==
,2015-12-07 18:48:36.133 ThaliTest[408:170630] server session: connected
2015-12-07 18:48:36.134 ThaliTest[408:170630] server session: stateChange:1->2 1449510506165.416
,2015-12-07 18:48:36.201 ThaliTest[408:170365] server session: disconnect
2015-12-07 18:48:36.201 ThaliTest[408:170365] server session: stateChange:1->0 1449510506999.375
,2015-12-07 18:48:36.287 ThaliTest[408:170707] server session: not connected 1449510506165.416
,2015-12-07 18:48:36.316 ThaliTest[408:170365] server session: disconnect
2015-12-07 18:48:36.318 ThaliTest[408:170365] server session: stateChange:2->0 1449510506165.416
,2015-12-07 18:48:36.428 ThaliTest[408:170365] server session: disconnect
2015-12-07 18:48:36.429 ThaliTest[408:170365] server session: stateChange:1->0 1449510506003.383
,2015-12-07 18:48:36.513 ThaliTest[408:170365] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,2015-12-07 18:48:36.533 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
,2015-12-07 18:48:36.536 ThaliTest[408:170365] Communications not enabled
,2015-12-07 18:48:36.537 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:36.982 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:36.983 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:36.983 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:36.985 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:36.985 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:36.985 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:37.550 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:37.551 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:37.551 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,# teardown
,2015-12-07 18:48:37.990 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:37.990 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:37.991 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:37.992 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:37.992 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:37.993 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:38.555 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:38.556 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:38.556 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:39.002 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:39.003 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:39.004 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:39.005 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:39.006 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:39.006 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:39.566 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:39.567 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:39.567 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:40.013 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:40.014 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:40.014 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:40.015 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:40.016 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:40.016 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:40.576 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:40.577 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:40.577 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/5D92D36D-0DC3-43DC-A68D-C83238ED9224/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 138 starting event should occur in right order
,2015-12-07 18:48:40.772 ThaliTest[408:170365] jxcore: startBroadcasting
,2015-12-07 18:48:40.773 ThaliTest[408:170365] server: starting WdFN6vsj7u9vyVW_hrDw6Q.ech9pg==
2015-12-07 18:48:40.774 ThaliTest[408:170365] multipeer session: start timer: 0x15fb88a0
2015-12-07 18:48:40.774 ThaliTest[408:170365] THEMultipeerSession init,ialized peer WdFN6vsj7u9vyVW_hrDw6Q
2015-12-07 18:48:40.774 ThaliTest[408:170365] jxcore: startBroadcasting: success
ok 139 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 140 stopping event should occur in right order
About to call stopBroadcasting
,2015-12-07 18:48:40.776 ThaliTest[408:170365] jxcore: stopBroadcasting
2015-12-07 18:48:40.777 ThaliTest[408:170365] THEMultipeerSession stopping peer
2015-12-07 18:48:40.777 ThaliTest[408:170365] multipeer session: stop timer
,2015-12-07 18:48:40.777 ThaliTest[408:170365] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
ok 141 stopped event should occur in right order
,mux server bridge listener closed
# setup
,2015-12-07 18:48:41.025 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:41.025 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:41.025 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
2015-12-07 18:48:41.026 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:41.026 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:41.026 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:41.581 ThaliTest[408:170365] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:41.581 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:41.582 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,# ThaliReplicationManager receives identity
,2015-12-07 18:48:42.033 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:42.033 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:42.034 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:42.035 ThaliTest[408:170365] jxcore: connect 1449510506999.375.Lduuig==
2015-12-07 18:48:42.035 ThaliTest[408:170365] Communications not enabled
2015-12-07 18:48:42.036 ThaliTest[408:170365] jxcore: connect: fail: app: Not initialised
,not ok 142 Second connect should succeed
,  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,2015-12-07 18:48:42.633 ThaliTest[408:170365] Error!: connect EADDRNOTAVAIL
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_functi,onName":"connect","_lineNumber":"707","_columnNumber":"19","_msg":"    at connect@net.js:707:19"},{"_fileName":"net.js","_functionName":"Socket.prototype.connect","_lineNumber":"756","_columnNumber":"5","_msg":"    at Socket.prototype.connect@net.js:756:5",},{"_fileName":"net.js","_functionName":"exports.createConnection","_lineNumber":"72","_columnNumber":"10","_msg":"    at exports.createConnection@net.js:72:10"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F,3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"sendData","_lineNumber":"277","_columnNumber":"24","_msg":"    at sendData@/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.a,pp/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"325",",_columnNumber":"17","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B0,BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer","_lineNumber":"251","_columnNumber":"9","_msg":"    at connectWithRetry/connectToPeer@/private/var/mobile/Contain,ers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_,tests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer/</<","_lineNumber":"260","_columnNumber":"45","_msg":"    at connectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3,F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45"},{"_fileName":"timers.js","_functionName":"listOnTimeout","_lineNumber":"112","_columnNumber":"9","_msg":"    at listOnTimeout@timers.js:112:9"},{"_fileName":"net.js","_functionName":",unknown","_lineNumber":835,"_columnNumber":10,"_msg":"    at "}]
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
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B0BED311-062,0-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'sendData',
    _lineNumber: '277',
    _columnNumber: '24',
    _msg: '    at sendData@/private/var/mobile/Containers/Bundle/Application/B0BED311-0,620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.j,s',
    _functionName: '',
    _lineNumber: '325',
    _columnNumber: '17',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17' },
,  { _fileName: '/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer',
    _lineNumber: '251',
    _columnNu,mber: '9',
    _msg: '    at connectWithRetry/connectToPeer@/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9' },
  { _fileName: '/private/var/mobile/Con,tainers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer/</<',
    _lineNumber: '260',
    _columnNumber: '45',
    _msg: '    at conn,ectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/B0BED311-0620-448F-B3D8-13252F3F5B91/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45' },
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
