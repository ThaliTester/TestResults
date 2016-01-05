#### Test 549702610263d9b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/549702610263d9b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/462E0CF6-8313-4455-AA04-33C58C8335BE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/462E0CF6-8313-4455-AA04-33C58C8335BE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/549702610263d9b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/549702610263d9b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8891A6E4-C583-4811-9E6D-BE3A064E4CBD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65314"
,(lldb)     command script import "/tmp/462E0CF6-8313-4455-AA04-33C58C8335BE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 18:31:20.279 ThaliTest[1319:2798489] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C65AC1D8-1CDC-40F0-B044-D59B1EA4F29C/Library/Cookies/Cookies.binarycookies
,2016-01-05 18:31:20.710 ThaliTest[1319:2798489] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 18:31:20.711 ThaliTest[1319:2798489] Multi-tasking -> Device: YES, App: YES
,2016-01-05 18:31:20.720 ThaliTest[1319:2798489] Unlimited access to network resources
,2016-01-05 18:31:20.731 ThaliTest[1319:2798489] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 18:31:29.508 ThaliTest[1319:2798489] Resetting plugins due to page load.
,2016-01-05 18:31:33.534 ThaliTest[1319:2798489] Finished load of: file:///var/mobile/Containers/Bundle/Application/8891A6E4-C583-4811-9E6D-BE3A064E4CBD/ThaliTest.app/www/index.html
,2016-01-05 18:31:33.740 ThaliTest[1319:2798489] JXcore Cordova plugin initializing
,2016-01-05 18:31:33.742 ThaliTest[1319:2799358] JXcore instance initializing
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
,2016-01-05 18:36:43.321 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:43.338 ThaliTest[1319:2799358] server: starting 1452015403320.1319.MeG/gw==
,2016-01-05 18:36:43.339 ThaliTest[1319:2799358] multipeer session: start timer: 0x166242e0
2016-01-05 18:36:43.340 ThaliTest[1319:2799358] THEMultipeerSession initialized peer 1452015403320.1319
2016-01-05 18:36:43.341 ThaliTest[1319:2799358] jxcore: sta,rtBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-05 18:36:43.345 ThaliTest[1319:2799358] jxcore: stopBroadcasting
2016-01-05 18:36:43.345 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
2016-01-05 1,8:36:43.345 ThaliTest[1319:2799358] multipeer session: stop timer
2016-01-05 18:36:43.346 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-05 18:36:43.348 ThaliTest[1319:279935,8] jxcore: startBroadcasting
,2016-01-05 18:36:43.355 ThaliTest[1319:2799358] server: starting 1452015403348.1319.ltTucQ==
,2016-01-05 18:36:43.367 ThaliTest[1319:2799358] multipeer session: start timer: 0x16620bf0
2016-01-05 18:36:43.371 ThaliTest[1319:2799358] THEMultipeerSession initialized peer 1452015403348.1319
,2016-01-05 18:36:43.372 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.382 ThaliTest[1319:2799358] jxcore: stopBroadcasting
2016-01-05 18:36:43.383 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
2016-01-05 18:36:43.383 ThaliTest[1319:2799358] multipeer session: stop timer
2016-01-05 18:36:43.,384 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-05 18:36:43.387 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:43.393 ThaliTest[1319:2799358] server: starting 1452015403386.1319.MosCvA==
2016-01-05 18:36:43.394 ThaliTest[1319:2799358] multipeer session: start timer: 0x18022cd0
2016-01-05 18:36:43.398 ThaliTest[1319:2799358] THEMultipeerSession in,itialized peer 1452015403386.1319
2016-01-05 18:36:43.398 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.401 ThaliTest[1319:2799358] jxcore: stopBroadcasting
2016-01-05 18:36:43.402 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.402 ThaliTest[1319:2799358] multipeer session: stop timer
,2016-01-05 18:36:43.413 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.420 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:43.423 ThaliTest[1319:2799358] server: starting 1452015403420.1319.Jbi2Wg==
,2016-01-05 18:36:43.426 ThaliTest[1319:2799358] multipeer session: start timer: 0x16620940
,2016-01-05 18:36:43.430 ThaliTest[1319:2799358] THEMultipeerSession initialized peer 1452015403420.1319
,2016-01-05 18:36:43.431 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.434 ThaliTest[1319:2799358] jxcore: stopBroadcasting
,2016-01-05 18:36:43.435 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.436 ThaliTest[1319:2799358] multipeer session: stop timer
,2016-01-05 18:36:43.437 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.443 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:43.446 ThaliTest[1319:2799358] server: starting 1452015403442.1319.PyTDVw==
,2016-01-05 18:36:43.449 ThaliTest[1319:2799358] multipeer session: start timer: 0x1661f820
,2016-01-05 18:36:43.450 ThaliTest[1319:2799358] THEMultipeerSession initialized peer 1452015403442.1319
,2016-01-05 18:36:43.451 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.455 ThaliTest[1319:2799358] jxcore: stopBroadcasting
,2016-01-05 18:36:43.456 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.457 ThaliTest[1319:2799358] multipeer session: stop timer
,2016-01-05 18:36:43.460 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.464 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:43.467 ThaliTest[1319:2799358] server: starting 1452015403464.1319.jThrDw==
,2016-01-05 18:36:43.471 ThaliTest[1319:2799358] multipeer session: start timer: 0x18022700
,2016-01-05 18:36:43.473 ThaliTest[1319:2799358] THEMultipeerSession initialized peer 1452015403464.1319
,2016-01-05 18:36:43.476 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.481 ThaliTest[1319:2799358] jxcore: stopBroadcasting
,2016-01-05 18:36:43.482 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.484 ThaliTest[1319:2799358] multipeer session: stop timer
,2016-01-05 18:36:43.486 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.493 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:43.497 ThaliTest[1319:2799358] server: starting 1452015403492.1319.ug5Baw==
,2016-01-05 18:36:43.502 ThaliTest[1319:2799358] multipeer session: start timer: 0x18020e00
,2016-01-05 18:36:43.506 ThaliTest[1319:2799358] THEMultipeerSession initialized peer 1452015403492.1319
,2016-01-05 18:36:43.508 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.514 ThaliTest[1319:2799358] jxcore: stopBroadcasting
,2016-01-05 18:36:43.516 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.519 ThaliTest[1319:2799358] multipeer session: stop timer
,2016-01-05 18:36:43.525 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.531 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:43.544 ThaliTest[1319:2799358] server: starting 1452015403531.1319.gtF4Kw==
,2016-01-05 18:36:43.548 ThaliTest[1319:2799358] multipeer session: start timer: 0x1661dc50
,2016-01-05 18:36:43.553 ThaliTest[1319:2799358] THEMultipeerSession initialized peer 1452015403531.1319
,2016-01-05 18:36:43.554 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.557 ThaliTest[1319:2799358] jxcore: stopBroadcasting
,2016-01-05 18:36:43.557 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.559 ThaliTest[1319:2799358] multipeer session: stop timer
,2016-01-05 18:36:43.559 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.565 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:43.568 ThaliTest[1319:2799358] server: starting 1452015403564.1319.vCjBOw==
,2016-01-05 18:36:43.571 ThaliTest[1319:2799358] multipeer session: start timer: 0x1661dc90
,2016-01-05 18:36:43.572 ThaliTest[1319:2799358] THEMultipeerSession initialized peer 1452015403564.1319
,2016-01-05 18:36:43.575 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.579 ThaliTest[1319:2799358] jxcore: stopBroadcasting
,2016-01-05 18:36:43.580 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.581 ThaliTest[1319:2799358] multipeer session: stop timer
,2016-01-05 18:36:43.583 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-05 18:36:43.588 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:43.591 ThaliTest[1319:2799358] server: starting 1452015403587.1319.aXSO4g==
,2016-01-05 18:36:43.593 ThaliTest[1319:2799358] multipeer session: start timer: 0x1661be20
,2016-01-05 18:36:43.596 ThaliTest[1319:2799358] THEMultipeerSession initialized peer 1452015403587.1319
,2016-01-05 18:36:43.598 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-05 18:36:43.604 ThaliTest[1319:2799358] jxcore: stopBroadcasting
,2016-01-05 18:36:43.604 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
,2016-01-05 18:36:43.605 ThaliTest[1319:2799358] multipeer session: stop timer
,2016-01-05 18:36:43.607 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-05 18:36:44.264 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:44.268 ThaliTest[1319:2799358] server: starting 1452015404263.1319.3Sykgw==
2016-01-05 18:36:44.268 ThaliTest[1319:2799358] multipeer session: start timer: 0x1661ce70
2016-01-05 18:36:44.269 ThaliTest[1319:2799358] THEMultipeerSession in,itialized peer 1452015404263.1319
2016-01-05 18:36:44.269 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-05 18:36:44.272 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:44.272 ThaliTest[1319:2799358] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-05 18:36:44.275 ThaliTest[1319:2799358] jxcore: stopBroadcasting
2016-01-05 18:36:44.275 ThaliTest[1319:2799358] THEMult,ipeerSession stopping peer
2016-01-05 18:36:44.275 ThaliTest[1319:2799358] multipeer session: stop timer
2016-01-05 18:36:44.276 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-05 18:36:44.952 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:44.956 ThaliTest[1319:2799358] server: starting 1452015404952.1319.cFaaxA==
2016-01-05 18:36:44.957 ThaliTest[1319:2799358] multipeer session: start timer: 0x1801aa20
2016-01-05 18:36:44.958 ThaliTest[1319:2799358] THEMultipeerSession in,itialized peer 1452015404952.1319
2016-01-05 18:36:44.958 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-05 18:36:44.961 ThaliTest[1319:2799358] jxcore: connect foobar
201,6-01-05 18:36:44.961 ThaliTest[1319:2799358] client: unknown peer foobar
2016-01-05 18:36:44.961 ThaliTest[1319:2799358] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-05 18:36:44.964 ThaliTest[1319:2799358] jxcore: s,topBroadcasting
2016-01-05 18:36:44.964 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
2016-01-05 18:36:44.965 ThaliTest[1319:2799358] multipeer session: stop timer
,2016-01-05 18:36:44.966 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-05 18:36:45.842 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:45.846 ThaliTest[1319:2799358] server: starting 1452015405841.1319.3v9KcQ==
2016-01-05 18:36:45.847 ThaliTest[1319:2799358] multipeer session: start timer: 0x166165c0
2016-01-05 18:36:45.847 ThaliTest[1319:2799358] THEMultipeerSession in,itialized peer 1452015405841.1319
2016-01-05 18:36:45.847 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-05 18:36:45.850 ThaliTest[1319:2799358] jxcore: disconnect
2016-01,-05 18:36:45.851 ThaliTest[1319:2799358] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2016-01-05 18:36:45.854 ThaliTest[1319:2799358] jxcore: stopBroadcasting
2016-01-05 18:36:45.854 ThaliTest[1319:2799358] THEMultipeerS,ession stopping peer
2016-01-05 18:36:45.854 ThaliTest[1319:2799358] multipeer session: stop timer
2016-01-05 18:36:45.855 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-05 18:36:46.387 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:46.392 ThaliTest[1319:2799358] server: starting 1452015406387.1319.AajjwA==
2016-01-05 18:36:46.393 ThaliTest[1319:2799358] multipeer session: start timer: 0x16612090
2016-01-05 18:36:46.393 ThaliTest[1319:2799358] THEMultipeerSession in,itialized peer 1452015406387.1319
2016-01-05 18:36:46.394 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-05 18:36:48.760 ThaliTest[1319:2798489] client: found peer: 1452015406368.1336.86tKTw==
2016-01-05 18:36:48.767 ThaliTest[1319:2799358] jxcore: connect 1452015406368.1336.86tKTw==
,2016-01-05 18:36:48.768 ThaliTest[1319:2799358] client session: connect
2016-01-05 18:36:48.769 ThaliTest[1319:2799358] client session: stateChange:0->1 1452015406368.1336.86tKTw==
,2016-01-05 18:36:49.310 ThaliTest[1319:2798489] multipeer session: reset timer
2016-01-05 18:36:49.311 ThaliTest[1319:2798489] multipeer session: stop timer
2016-01-05 18:36:49.311 ThaliTest[1319:2798489] multipeer session: start timer: 0x16612090
2016-,01-05 18:36:49.311 ThaliTest[1319:2798489] server session: connect
2016-01-05 18:36:49.312 ThaliTest[1319:2798489] server session: stateChange:0->1 1452015406368.1336
,2016-01-05 18:36:49.325 ThaliTest[1319:2798489] server: accepting invitation 1452015406368.1336
,2016-01-05 18:36:52.061 ThaliTest[1319:2799923] server session: connected
2016-01-05 18:36:52.062 ThaliTest[1319:2799923] server session: stateChange:1->2 1452015406368.1336
,2016-01-05 18:36:52.081 ThaliTest[1319:2798489] server relay: socket disconnected
2016-01-05 18:36:52.081 ThaliTest[1319:2798489] server relay: 0x1800e580 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 18:36:52.132 ThaliTest[1319:2799919] server session: not connected 1452015406368.1336
,2016-01-05 18:36:52.194 ThaliTest[1319:2799923] client session: connected
,2016-01-05 18:36:52.194 ThaliTest[1319:2799923] client session: stateChange:1->2 1452015406368.1336.86tKTw==
,2016-01-05 18:36:52.210 ThaliTest[1319:2799919] client session: fireConnectCallback: 1452015406368.1336.86tKTw==
2016-01-05 18:36:52.210 ThaliTest[1319:2799919] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-05 18:36:52.216 ThaliTest[1319:2799358] jxcore: disconnect
2016-01-05 18:36:52.217 ThaliTest[1319:2799358] client session: disconnectFromPeer: 1452015406368.1336.86tKTw==
2016-01-05 18:36:52.217 ThaliTest[1319:2799358] client session: disconnect,
2016-01-05 18:36:52.217 ThaliTest[1319:2799358] client session: stateChange:2->0 1452015406368.1336.86tKTw==
,2016-01-05 18:36:52.235 ThaliTest[1319:2799358] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-05 18:36:52.688 ThaliTest[1319:2799358] jxcore: stopBroadcasting
2016-01-05 18:36:52.688 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
2016-01-05 18:36:52.689 ThaliTest[1319:2799358] multipeer session: stop timer
2016-01-05 18:36:52.,689 ThaliTest[1319:2799358] server session: disconnect
2016-01-05 18:36:52.690 ThaliTest[1319:2799358] server session: stateChange:2->0 1452015406368.1336
2016-01-05 18:36:52.691 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-05 18:36:54.092 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:54.096 ThaliTest[1319:2799358] server: starting 1452015414092.1319.6etPIw==
2016-01-05 18:36:54.097 ThaliTest[1319:2799358] multipeer session: start timer: 0x1660abb0
2016-01-05 18:36:54.097 ThaliTest[1319:2799358] THEMultipeerSession in,itialized peer 1452015414092.1319
2016-01-05 18:36:54.098 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-05 18:36:54.854 ThaliTest[1319:2798489] client: found peer: 1452015406368.1336.86tKTw==
2016-01-05 18:36:54.856 ThaliTest[1319:2799358] jxcore: connect 1452015406368.1336.86tKTw==
2016-01-05 18:36:54.857 ThaliTest[1319:2799358] client session: co,nnect
2016-01-05 18:36:54.859 ThaliTest[1319:2799358] client session: stateChange:0->1 1452015406368.1336.86tKTw==
,2016-01-05 18:36:55.028 ThaliTest[1319:2798489] client: found peer: 1452015414039.1336.n2tyeg==
2016-01-05 18:36:55.030 ThaliTest[1319:2799358] jxcore: connect 1452015414039.1336.n2tyeg==
2016-01-05 18:36:55.031 ThaliTest[1319:2799358] client session: co,nnect
2016-01-05 18:36:55.031 ThaliTest[1319:2799358] client session: stateChange:0->1 1452015414039.1336.n2tyeg==
,2016-01-05 18:36:55.529 ThaliTest[1319:2798489] multipeer session: reset timer
2016-01-05 18:36:55.530 ThaliTest[1319:2798489] multipeer session: stop timer
2016-01-05 18:36:55.530 ThaliTest[1319:2798489] multipeer session: start timer: 0x1660abb0
2016-,01-05 18:36:55.530 ThaliTest[1319:2798489] server session: connect
2016-01-05 18:36:55.531 ThaliTest[1319:2798489] server session: stateChange:0->1 1452015414039.1336
,2016-01-05 18:36:55.542 ThaliTest[1319:2798489] server: accepting invitation 1452015414039.1336
,2016-01-05 18:36:58.094 ThaliTest[1319:2799968] client session: connected
2016-01-05 18:36:58.094 ThaliTest[1319:2799968] client session: stateChange:1->2 1452015414039.1336.n2tyeg==
,2016-01-05 18:36:58.108 ThaliTest[1319:2799968] client session: fireConnectCallback: 1452015414039.1336.n2tyeg==
2016-01-05 18:36:58.108 ThaliTest[1319:2799968] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-05 18:36:58.114 ThaliTest[1319:2799358] jxcore: connect 1452015414039.1336.n2tyeg==
2016-01-05 18:36:58.114 ThaliTest[1319:2799358] client: already connect(ing/ed) to 1452015414039.1336.n2tyeg==
2016-01-05 18:36:58.114 ThaliTest[1319:2799358] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-05 18:36:58.117 ThaliTest[1319:2799358] jxcore: disconnect
2016-01-05 18:36:58.117 ThaliTest[1319:2799358] client session: disconnectFromPeer: 1452015414039.1336.n2tyeg==
,2016-01-05 18:36:58.118 ThaliTest[1319:2799358] client session: disconnect
,2016-01-05 18:36:58.119 ThaliTest[1319:2799358] client session: stateChange:2->0 1452015414039.1336.n2tyeg==
,2016-01-05 18:36:58.209 ThaliTest[1319:2799922] server session: connected
2016-01-05 18:36:58.210 ThaliTest[1319:2799922] server session: stateChange:1->2 1452015414039.1336
,2016-01-05 18:36:58.215 ThaliTest[1319:2798489] server relay: socket disconnected
,2016-01-05 18:36:58.217 ThaliTest[1319:2798489] server relay: 0x16605fd0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 18:36:58.219 ThaliTest[1319:2799358] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-05 18:36:58.345 ThaliTest[1319:2799919] server session: not connected 1452015414039.1336
,calling stopBroadcasting
,2016-01-05 18:36:58.551 ThaliTest[1319:2799358] jxcore: stopBroadcasting
2016-01-05 18:36:58.552 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
2016-01-05 18:36:58.552 ThaliTest[1319:2799358] multipeer session: stop timer
2016-01-05 18:36:58.,553 ThaliTest[1319:2799358] client session: disconnect
2016-01-05 18:36:58.553 ThaliTest[1319:2799358] client session: stateChange:1->0 1452015406368.1336.86tKTw==
2016-01-05 18:36:58.554 ThaliTest[1319:2799358] server session: disconnect
2016-01-05 18:,36:58.554 ThaliTest[1319:2799358] server session: stateChange:2->0 1452015414039.1336
2016-01-05 18:36:58.556 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-05 18:36:58.916 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:36:58.921 ThaliTest[1319:2799358] server: starting 1452015418916.1319.obKNlg==
,2016-01-05 18:36:58.923 ThaliTest[1319:2799358] multipeer session: start timer: 0x180009e0
2016-01-05 18:36:58.924 ThaliTest[1319:2799358] THEMultipeerSession initialized peer 1452015418916.1319
2016-01-05 18:36:58.925 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-05 18:37:00.105 ThaliTest[1319:2798489] client: found peer: 1452015418905.1336.xGPM4g==
,2016-01-05 18:37:00.108 ThaliTest[1319:2799358] jxcore: connect 1452015418905.1336.xGPM4g==
2016-01-05 18:37:00.109 ThaliTest[1319:2799358] client session: connect
2016-01-05 18:37:00.109 ThaliTest[1319:2799358] client session: stateChange:0->1 1452015418905.1336.xGPM4g==
,2016-01-05 18:37:00.218 ThaliTest[1319:2798489] multipeer session: reset timer
2016-01-05 18:37:00.219 ThaliTest[1319:2798489] multipeer session: stop timer
2016-01-05 18:37:00.219 ThaliTest[1319:2798489] multipeer session: start timer: 0x180009e0
2016-01-05 18:37:00.219 ThaliTest[1319:2798489] server session: connect
2016-01-05 18:37:00.219 ThaliTest[1319:2798489] server session: stateChange:0->1 1452015418905.1336
,2016-01-05 18:37:00.227 ThaliTest[1319:2798489] server: accepting invitation 1452015418905.1336
,2016-01-05 18:37:02.674 ThaliTest[1319:2799919] client session: connected
,2016-01-05 18:37:02.675 ThaliTest[1319:2799919] client session: stateChange:1->2 1452015418905.1336.xGPM4g==
,2016-01-05 18:37:02.690 ThaliTest[1319:2799919] client session: fireConnectCallback: 1452015418905.1336.xGPM4g==
,2016-01-05 18:37:02.691 ThaliTest[1319:2799919] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-05 18:37:02.698 ThaliTest[1319:2799358] jxcore: disconnect
,2016-01-05 18:37:02.700 ThaliTest[1319:2799358] client session: disconnectFromPeer: 1452015418905.1336.xGPM4g==
,2016-01-05 18:37:02.701 ThaliTest[1319:2799358] client session: disconnect
,2016-01-05 18:37:02.703 ThaliTest[1319:2799358] client session: stateChange:2->0 1452015418905.1336.xGPM4g==
,2016-01-05 18:37:02.721 ThaliTest[1319:2799919] server session: connected
,2016-01-05 18:37:02.722 ThaliTest[1319:2799919] server session: stateChange:1->2 1452015418905.1336
,2016-01-05 18:37:02.731 ThaliTest[1319:2798489] server relay: socket disconnected
,2016-01-05 18:37:02.732 ThaliTest[1319:2798489] server relay: 0x16606330 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 18:37:02.797 ThaliTest[1319:2799930] server session: not connected 1452015418905.1336
,2016-01-05 18:37:02.800 ThaliTest[1319:2799358] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2016-01-05 18:37:02.803 ThaliTest[1319:2799358] jxcore: disconnect
,2016-01-05 18:37:02.804 ThaliTest[1319:2799358] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-05 18:37:03.179 ThaliTest[1319:2799358] jxcore: stopBroadcasting
2016-01-05 18:37:03.180 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
2016-01-05 18:37:03.180 ThaliTest[1319:2799358] multipeer session: stop timer
2016-01-05 18:37:03.,181 ThaliTest[1319:2799358] server session: disconnect
2016-01-05 18:37:03.181 ThaliTest[1319:2799358] server session: stateChange:2->0 1452015418905.1336
2016-01-05 18:37:03.182 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-05 18:37:04.216 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:37:04.220 ThaliTest[1319:2799358] server: starting 1452015424215.1319.2rPyww==
2016-01-05 18:37:04.221 ThaliTest[1319:2799358] multipeer session: start timer: 0x180166e0
2016-01-05 18:37:04.221 ThaliTest[1319:2799358] THEMultipeerSession in,itialized peer 1452015424215.1319
2016-01-05 18:37:04.221 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-05 18:37:05.348 ThaliTest[1319:2798489] client: found peer: 1452015424189.1336.YigYPw==
[{"peerIdentifier":"1452015424189.1336.YigYPw==","peerName":"(null)","peerAvailable":true}]
,2016-01-05 18:37:05.354 ThaliTest[1319:2799358] jxcore: connect 1452015424189.1336.YigYPw==
2016-01-05 18:37:05.355 ThaliTest[1319:2799358] client session: connect
2016-01-05 18:37:05.355 ThaliTest[1319:2799358] client session: stateChange:0->1 1452015424189.1336.YigYPw==
,2016-01-05 18:37:05.884 ThaliTest[1319:2798489] multipeer session: reset timer
2016-01-05 18:37:05.887 ThaliTest[1319:2798489] multipeer session: stop timer
2016-01-05 18:37:05.887 ThaliTest[1319:2798489] multipeer session: start timer: 0x180166e0
2016-,01-05 18:37:05.888 ThaliTest[1319:2798489] server session: connect
2016-01-05 18:37:05.889 ThaliTest[1319:2798489] server session: stateChange:0->1 1452015424189.1336
2016-01-05 18:37:05.902 ThaliTest[1319:2798489] server: accepting invitation 1452015424189.1336
,2016-01-05 18:37:08.495 ThaliTest[1319:2799930] client session: connected
2016-01-05 18:37:08.496 ThaliTest[1319:2799930] client session: stateChange:1->2 1452015424189.1336.YigYPw==
,2016-01-05 18:37:08.535 ThaliTest[1319:2799919] client session: fireConnectCallback: 1452015424189.1336.YigYPw==
2016-01-05 18:37:08.536 ThaliTest[1319:2799919] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
,ok 91 First connect should succeed
,2016-01-05 18:37:08.600 ThaliTest[1319:2798489] client: relay established
2016-01-05 18:37:08.600 ThaliTest[1319:2798489] client: new accepted socket: 0x1660e0c0
,2016-01-05 18:37:08.637 ThaliTest[1319:2800009] server session: connected
,2016-01-05 18:37:08.638 ThaliTest[1319:2800009] server session: stateChange:1->2 1452015424189.1336
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2016-01-05 18:37:08.705 ThaliTest[1319:2798489] server relay: connected (to port: 5001)
,2016-01-05 18:37:08.718 ThaliTest[1319:2798489] client: socket closed
,2016-01-05 18:37:08.719 ThaliTest[1319:2798489] client relay: socket disconnected
2016-01-05 18:37:08.719 ThaliTest[1319:2798489] client relay: 0x1660e0c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-05 18:37:08.720 ThaliTest[1319:2798489] client session: socket closed: 1452015424189.1336.YigYPw==
2016-01-05 18:37:08.720 ThaliTest[1319:2798489] client session: onLinkFailure: 1452015424189.1336.YigYPw==
2016-01-05 18:37:08.720 ThaliTest[1319:2,798489] client session: disconnect
2016-01-05 18:37:08.721 ThaliTest[1319:2798489] client session: stateChange:2->0 1452015424189.1336.YigYPw==
,2016-01-05 18:37:08.742 ThaliTest[1319:2798489] client session: fireConnectionErrorEvent: 1452015424189.1336.YigYPw==
,2016-01-05 18:37:08.752 ThaliTest[1319:2799358] jxcore: connect 1452015424189.1336.YigYPw==
,2016-01-05 18:37:08.755 ThaliTest[1319:2799358] client session: connect
,2016-01-05 18:37:08.759 ThaliTest[1319:2799358] client session: stateChange:0->1 1452015424189.1336.YigYPw==
,2016-01-05 18:37:09.041 ThaliTest[1319:2800009] server session: not connected 1452015424189.1336
,2016-01-05 18:37:09.095 ThaliTest[1319:2798489] multipeer session: reset timer
2016-01-05 18:37:09.096 ThaliTest[1319:2798489] multipeer session: stop timer
,2016-01-05 18:37:09.097 ThaliTest[1319:2798489] multipeer session: start timer: 0x180166e0
,2016-01-05 18:37:09.097 ThaliTest[1319:2798489] server: disconnecting to refresh session (1452015424189.1336)
2016-01-05 18:37:09.099 ThaliTest[1319:2798489] server session: disconnect
2016-01-05 18:37:09.099 ThaliTest[1319:2798489] server session: state,Change:2->0 1452015424189.1336
,2016-01-05 18:37:09.104 ThaliTest[1319:2798489] server session: connect
2016-01-05 18:37:09.104 ThaliTest[1319:2798489] server session: stateChange:0->1 1452015424189.1336
,2016-01-05 18:37:09.123 ThaliTest[1319:2798489] server: accepting invitation 1452015424189.1336
,2016-01-05 18:37:11.646 ThaliTest[1319:2800009] server session: connected
2016-01-05 18:37:11.647 ThaliTest[1319:2800009] server session: stateChange:1->2 1452015424189.1336
,2016-01-05 18:37:11.669 ThaliTest[1319:2798489] server relay: connected (to port: 5001)
,2016-01-05 18:37:11.808 ThaliTest[1319:2800009] server session: not connected 1452015424189.1336
,2016-01-05 18:37:11.888 ThaliTest[1319:2799968] client session: connected
,2016-01-05 18:37:11.888 ThaliTest[1319:2799968] client session: stateChange:1->2 1452015424189.1336.YigYPw==
,2016-01-05 18:37:11.905 ThaliTest[1319:2799919] client session: fireConnectCallback: 1452015424189.1336.YigYPw==
2016-01-05 18:37:11.909 ThaliTest[1319:2799919] jxcore: connect: success
ok 94 Should be able to connect without error
ok 95 Port should be within range
,ok 96 Second connect should succeed
,2016-01-05 18:37:11.946 ThaliTest[1319:2798489] client: relay established
2016-01-05 18:37:11.946 ThaliTest[1319:2798489] client: new accepted socket: 0x180056a0
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2016-01-05 18:37:12.006 ThaliTest[1319:2798489] client: socket closed
2016-01-05 18:37:12.007 ThaliTest[1319:2798489] client relay: socket disconnected
2016-01-05 18:37:12.007 ThaliTest[1319:2798489] client relay: 0x180056a0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-05 18:37:12.007 ThaliTest[1319:2798489] client session: socket closed: 1452015424189.1336.YigYPw==
2016-01-05 ,18:37:12.008 ThaliTest[1319:2798489] client session: onLinkFailure: 1452015424189.1336.YigYPw==
2016-01-05 18:37:12.008 ThaliTest[1319:2798489] client session: disconnect
2016-01-05 18:37:12.008 ThaliTest[1319:2798489] client session: stateChange:2->0 1452015424189.1336.YigYPw==
,2016-01-05 18:37:12.022 ThaliTest[1319:2798489] client session: fireConnectionErrorEvent: 1452015424189.1336.YigYPw==
,calling stopBroadcasting
,2016-01-05 18:37:12.606 ThaliTest[1319:2799358] jxcore: stopBroadcasting
2016-01-05 18:37:12.606 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
2016-01-05 18:37:12.607 ThaliTest[1319:2799358] multipeer session: stop timer
2016-01-05 18:37:12.,607 ThaliTest[1319:2799358] server session: disconnect
2016-01-05 18:37:12.608 ThaliTest[1319:2799358] server session: stateChange:2->0 1452015424189.1336
,2016-01-05 18:37:12.617 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C65AC1D8-1CDC-40F0-B044-D59B1EA4F29C/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-05 18:37:13.853 ThaliTest[1319:2799358] jxcore: startBroadcasting
,2016-01-05 18:37:13.855 ThaliTest[1319:2799358] server: starting hiddCuxz5_lCi0VB1702wA.seUrqQ==
2016-01-05 18:37:13.855 ThaliTest[1319:2799358] multipeer session: start timer: 0x1815e610
2016-01-05 18:37:13.855 ThaliTest[1319:2799358] THEMultipeerSession initialized peer hiddCuxz5_lCi0VB1702wA
2016-01-05 18:37:13.855 ThaliTest[1319:2799358] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should o,ccur in right order
About to call stopBroadcasting
2016-01-05 18:37:13.857 ThaliTest[1319:2799358] jxcore: stopBroadcasting
,2016-01-05 18:37:13.858 ThaliTest[1319:2799358] THEMultipeerSession stopping peer
2016-01-05 18:37:13.858 ThaliTest[1319:2799358] multipeer session: stop timer
2016-01-05 18:37:13.858 ThaliTest[1319:2799358] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
,mux server bridge listener closed
# setup
,Process 1319 stopped
* thread #1: tid = 0x2ab399, 0x33e93ae2 libobjc.A.dylib`objc_msgSend + 2, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x2)
    frame #0: 0x33e93ae2 libobjc.A.dylib`objc_msgSend + 2
libobjc.A.dylib`objc_msgSend:
->  0x33e93ae2 <+2>:  ldr.w  r9, [r0]
    0x33e93ae6 <+6>:  ldrh.w r12, [r9, #0xc]
    0x33e93aea <+10>: ldr.w  r9, [r9, #0x8]
    0x33e93aee <+14>: and.w  r12, r12, r1
,* thread #1: tid = 0x2ab399, 0x33e93ae2 libobjc.A.dylib`objc_msgSend + 2, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x2)
  * frame #0: 0x33e93ae2 libobjc.A.dylib`objc_msgSend + 2
    frame #1: 0x21e16c3c CFNetwork`<redacted> + 816
    frame #2: 0x21e1632c CFNetwork`<redacted> + 36
    frame #3: 0x21d73df0 CFNetwork`<redacted> + 668
    frame #4: 0x34670bcc libsystem_dnssd.dylib`<redacted> + 128
    frame #5: 0x3466f490 libsystem_dnssd.dylib`DNSServiceProcessResult + 528
    frame #6: 0x21d73798 CFNetwork`<redacted> + 20
    frame #7: 0x224ef4f6 CoreFoundation`<redacted> + 818
    frame #8: 0x224eb7c6 CoreFoundation`<redacted> + 14
    frame #9: 0x224eb3b6 CoreFoundation`<redacted> + 454
    frame #10: 0x224e971e CoreFoundation`<redacted> + 806
    frame #11: 0x2243c0d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #12: 0x2243becc CoreFoundation`CFRunLoopRunInMode + 108
    frame #13: 0x2b771af8 GraphicsServices`GSEventRunModal + 160
    frame #14: 0x266c52dc UIKit`UIApplicationMain + 144
    frame #15: 0x000e4602 ThaliTest`main + 50

```
