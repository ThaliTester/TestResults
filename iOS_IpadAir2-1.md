#### Test 56151093f6e24ff_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56151093f6e24ff/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F6233AB4-E449-44EB-ABD3-43271CCFDF4C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F6233AB4-E449-44EB-ABD3-43271CCFDF4C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/56151093f6e24ff/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56151093f6e24ff/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2DFEBAE1-3CFB-49C3-B242-1B809E99A134/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57796"
,(lldb)     command script import "/tmp/F6233AB4-E449-44EB-ABD3-43271CCFDF4C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-18 14:52:02.648 ThaliTest[2265:4898787] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/263095D6-9D99-4290-BC9C-21C191F94A02/Library/Cookies/Cookies.binarycookies
,2016-01-18 14:52:02.889 ThaliTest[2265:4898787] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-18 14:52:02.890 ThaliTest[2265:4898787] Multi-tasking -> Device: YES, App: YES
,2016-01-18 14:52:02.896 ThaliTest[2265:4898787] Unlimited access to network resources
,2016-01-18 14:52:02.901 ThaliTest[2265:4898787] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-18 14:52:06.973 ThaliTest[2265:4898787] Resetting plugins due to page load.
,2016-01-18 14:52:08.194 ThaliTest[2265:4898787] Finished load of: file:///var/mobile/Containers/Bundle/Application/2DFEBAE1-3CFB-49C3-B242-1B809E99A134/ThaliTest.app/www/index.html
,2016-01-18 14:52:08.333 ThaliTest[2265:4898787] JXcore Cordova plugin initializing
,2016-01-18 14:52:08.334 ThaliTest[2265:4898956] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2DFEBAE1-3CFB-49C3-B242-1B809E99A134/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2DFEBAE1-3CFB-49C3-B242-1B809E99A134/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2DFEBAE1-3CFB-49C3-B242-1B809E99A134/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2DFEBAE1-3CFB-49C3-B242-1B809E99A134/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2DFEBAE1-3CFB-49C3-B242-1B809E99A134/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2DFEBAE1-3CFB-49C3-B242-1B809E99A134/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2DFEBAE1-3CFB-49C3-B242-1B809E99A134/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
ok 30 should be equal
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
,2016-01-18 14:57:56.565 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:57:56.570 ThaliTest[2265:4898956] server: starting 1453125476564.2265.MnQMiQ==
,2016-01-18 14:57:56.570 ThaliTest[2265:4898956] multipeer session: start timer: 0x16f62d80
2016-01-18 14:57:56.571 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125476564.2265
2016-01-18 14:57:56.571 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2016-01-18 14:57:56.572 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2016-01-18 14:57:56.572 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
2016-01-18 14:57:56.572 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:57:56.,573 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-18 14:57:56.573 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:57:56.574 ThaliTest[2265:4898956] server: starting 1453125476573.2265.hskI4Q==
2016-01-18 14:57:56.575 ThaliTest[2265:4898956] multipeer session: start timer: 0x16d62380
2016-01-18 14:57:56.575 ThaliTest[2265:4898956] THEMultipeerSession in,itialized peer 1453125476573.2265
2016-01-18 14:57:56.575 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2016-01-18 14:57:56.575 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2016-01-18 14:57:56.578 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
,2016-01-18 14:57:56.579 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:57:56.579 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-18 14:57:56.580 ThaliTest,[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:57:56.582 ThaliTest[2265:4898956] server: starting 1453125476579.2265.Idl8Vw==
2016-01-18 14:57:56.583 ThaliTest[2265:4898956] multipeer session: start timer: 0x16c008e0
2016-01-18 14:57:56.583 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125476579.2265
,2016-01-18 14:57:56.584 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-18 14:57:56.585 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2016-01-18 14:57:56.585 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
2016-01-18 14:57:56.585 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:57:56.585 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:56.586 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:57:56.588 ThaliTest[2265:4898956] server: starting 1453125476586.2265.upMcMw==
2016-01-18 14:57:56.588 ThaliTest[2265:4898956] multipeer session: start timer: 0x14f01d00
2016-01-18 14:57:56.588 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125476586.2265
2016-01-18 14:57:56.588 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-18 14:57:56.589 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2,016-01-18 14:57:56.589 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
2016-01-18 14:57:56.589 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:57:56.589 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-18 14:57:56.590 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:57:56.592 ThaliTest[2265:4898956] server: starting 1453125476590.2265.oOkrRw==
2016-01-18 14:57:56.592 ThaliTest[2265:4898956] multipeer session: start timer: 0x16e414c0
2016-01-18 14:57:56.592 ThaliTest[2265:4898956] THEMultipeerSession in,itialized peer 1453125476590.2265
2016-01-18 14:57:56.592 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-18 14:57:56.593 ThaliTest[2265:4898956] jxcore: stopBroadcasting
,2016-01-18 14:57:56.593 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
2016-01-18 14:57:56.595 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:57:56.595 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
,2016-01-18 14:57:56.595 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:57:56.599 ThaliTest[2265:4898956] server: starting 1453125476595.2265.NgMYhw==
,2016-01-18 14:57:56.600 ThaliTest[2265:4898956] multipeer session: start timer: 0x14f01870
2016-01-18 14:57:56.600 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125476595.2265
2016-01-18 14:57:56.600 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-18 14:57:56.601 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2016-01-18 14:57:56.601 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
2016-01-18 1,4:57:56.601 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:57:56.601 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
2016-01-18 14:57:56.602 ThaliTest[2265:489895,6] jxcore: startBroadcasting
,2016-01-18 14:57:56.604 ThaliTest[2265:4898956] server: starting 1453125476602.2265.7KBzZg==
2016-01-18 14:57:56.604 ThaliTest[2265:4898956] multipeer session: start timer: 0x16e3d740
2016-01-18 14:57:56.604 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125476602.2265
2016-01-18 14:57:56.604 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
2016-01-18 14:57:56.605 ThaliTest[2265:4898956] jxcore: stopBroadcasting
,2016-01-18 14:57:56.605 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
2016-01-18 14:57:56.605 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:57:56.605 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2016-01-18 14:57:56.606 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:57:56.610 ThaliTest[2265:4898956] server: starting 1453125476606.2265.DydoHA==
2016-01-18 14:57:56.610 ThaliTest[2265:4898956] multipeer session: start timer: 0x16e46090
2016-01-18 14:57:56.611 ThaliTest[2265:4898956] THEMultipeerSession in,itialized peer 1453125476606.2265
2016-01-18 14:57:56.611 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
2016-01-18 14:57:56.611 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2016-01-18 14:57:56.611 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
,2016-01-18 14:57:56.611 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:57:56.613 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
2016-01-18 14:57:56.614 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:57:56.616 ThaliTest[2265:4898956] server: starting 1453125476614.2265.B88m7Q==
2016-01-18 14:57:56.617 ThaliTest[2265:4898956] multipeer session: start timer: 0x16c0ce00
2016-01-18 14:57:56.617 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125476614.2265
2016-01-18 14:57:56.617 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2016-01-18 14:57:56.618 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2,016-01-18 14:57:56.618 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
2016-01-18 14:57:56.618 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:57:56.618 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
2016-01-18 14:57:56.619 ThaliTest[2265:4898956] jxcore: startBroadcasting
2016-01-18 14:57:56.620 ThaliTest[2265:4898956] server: starting 1453125476619.2265.D5TBoA==
2016-01-18 14:57:56.620 Th,aliTest[2265:4898956] multipeer session: start timer: 0x16e4c490
2016-01-18 14:57:56.620 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125476619.2265
2016-01-18 14:57:56.620 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
o,k 63 Should be able to call startBroadcasting without error
,2016-01-18 14:57:56.621 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2016-01-18 14:57:56.621 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
,2016-01-18 14:57:56.621 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:57:56.621 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-18 14:58:00.384 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:58:00.385 ThaliTest[2265:4898956] server: starting 1453125480383.2265.p/k32A==
2016-01-18 14:58:00.385 ThaliTest[2265:4898956] multipeer session: start timer: 0x16e4ff20
2016-01-18 14:58:00.385 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125480383.2265
2016-01-18 14:58:00.385 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-18 14:58:00.386 ThaliTest[2265:4898956] jxcore: startBroadcasting
2016-01-18 14:58:00.386 ThaliTest[2265:4898956] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2016-01-18 14:58:00.387 ThaliTest[2265:4898956] jxcore: stopBroadcasting
,2016-01-18 14:58:00.387 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
,2016-01-18 14:58:00.387 ThaliTest[2265:4898956] multipeer session: stop timer
,2016-01-18 14:58:00.387 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-18 14:58:01.832 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:58:01.833 ThaliTest[2265:4898956] server: starting 1453125481832.2265.WyX4oA==
2016-01-18 14:58:01.834 ThaliTest[2265:4898956] multipeer session: start timer: 0x16c0d210
2016-01-18 14:58:01.834 ThaliTest[2265:4898956] THEMultipeerSession in,itialized peer 1453125481832.2265
2016-01-18 14:58:01.834 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
,2016-01-18 14:58:01.835 ThaliTest[2265:4898956] jxcore: connect foobar
2016-01-18 14:58:01.835 ThaliTest[2265:4898956] client: unknown peer foobar
2016-01-18 14:58:01.835 ThaliTest[2265:4898956] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-18 14:58:01.836 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2016-01-18 14:58:01.836 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
2016-01-18 14:58:01.836 ThaliTest[2265:4898956] multipeer session: stop timer
20,16-01-18 14:58:01.836 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-18 14:58:04.854 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:58:04.855 ThaliTest[2265:4898956] server: starting 1453125484853.2265.PAm2kw==
2016-01-18 14:58:04.855 ThaliTest[2265:4898956] multipeer session: start timer: 0x16c096b0
2016-01-18 14:58:04.855 ThaliTest[2265:4898956] THEMultipeerSession in,itialized peer 1453125484853.2265
2016-01-18 14:58:04.855 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-18 14:58:04.856 ThaliTest[2265:4898956] jxcore: disconnect
2016-01-18 14:58:04.856 ThaliTest[2265:4898956] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-18 14:58:04.857 ThaliTest[2265:4898956] jxcore: stopBroadcasting
,2016-01-18 14:58:04.859 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
2016-01-18 14:58:04.859 ThaliTest[2265:4898956] multipeer session: stop timer
2016-01-18 14:58:04.859 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-18 14:58:07.971 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:58:07.972 ThaliTest[2265:4898956] server: starting 1453125487971.2265.oxrw5w==
2016-01-18 14:58:07.972 ThaliTest[2265:4898956] multipeer session: start timer: 0x16e5c430
2016-01-18 14:58:07.972 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125487971.2265
2016-01-18 14:58:07.973 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-18 14:58:09.009 ThaliTest[2265:4898787] client: found peer: 1453125486121.2206.edWCkA==
,2016-01-18 14:58:09.010 ThaliTest[2265:4898956] jxcore: connect 1453125486121.2206.edWCkA==
2016-01-18 14:58:09.010 ThaliTest[2265:4898956] client session: connect
2016-01-18 14:58:09.011 ThaliTest[2265:4898956] client session: stateChange:0->1 1453125486121.2206.edWCkA==
,2016-01-18 14:58:09.272 ThaliTest[2265:4898787] multipeer session: reset timer
2016-01-18 14:58:09.272 ThaliTest[2265:4898787] multipeer session: stop timer
2016-01-18 14:58:09.273 ThaliTest[2265:4898787] multipeer session: start timer: 0x16e5c430
,2016-01-18 14:58:09.273 ThaliTest[2265:4898787] server session: connect
,2016-01-18 14:58:09.273 ThaliTest[2265:4898787] server session: stateChange:0->1 1453125486121.2206
,2016-01-18 14:58:09.275 ThaliTest[2265:4898787] server: accepting invitation 1453125486121.2206
,2016-01-18 14:58:13.270 ThaliTest[2265:4899654] server session: connected
2016-01-18 14:58:13.270 ThaliTest[2265:4899654] server session: stateChange:1->2 1453125486121.2206
,2016-01-18 14:58:13.279 ThaliTest[2265:4898787] server relay: socket disconnected
,2016-01-18 14:58:13.280 ThaliTest[2265:4898787] server relay: 0x16efbbe0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-01-18 14:58:13.305 ThaliTest[2265:4899654] server session: not connected 1453125486121.2206
,2016-01-18 14:58:13.350 ThaliTest[2265:4899653] client session: connected
2016-01-18 14:58:13.350 ThaliTest[2265:4899653] client session: stateChange:1->2 1453125486121.2206.edWCkA==
,2016-01-18 14:58:13.357 ThaliTest[2265:4899654] client session: fireConnectCallback: 1453125486121.2206.edWCkA==
2016-01-18 14:58:13.357 ThaliTest[2265:4899654] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-18 14:58:13.359 ThaliTest[2265:4898956] jxcore: disconnect
,2016-01-18 14:58:13.359 ThaliTest[2265:4898956] client session: disconnectFromPeer: 1453125486121.2206.edWCkA==
,2016-01-18 14:58:13.359 ThaliTest[2265:4898956] client session: disconnect
,2016-01-18 14:58:13.359 ThaliTest[2265:4898956] client session: stateChange:2->0 1453125486121.2206.edWCkA==
,2016-01-18 14:58:13.362 ThaliTest[2265:4898956] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-18 14:58:13.618 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2016-01-18 14:58:13.618 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
,2016-01-18 14:58:13.618 ThaliTest[2265:4898956] multipeer session: stop timer
,2016-01-18 14:58:13.619 ThaliTest[2265:4898956] server session: disconnect
2016-01-18 14:58:13.619 ThaliTest[2265:4898956] server session: stateChange:2->0 1453125486121.2206
,2016-01-18 14:58:13.619 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-18 14:58:31.158 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:58:31.160 ThaliTest[2265:4898956] server: starting 1453125511158.2265.q5t90Q==
2016-01-18 14:58:31.160 ThaliTest[2265:4898956] multipeer session: start timer: 0x14f0aec0
2016-01-18 14:58:31.160 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125511158.2265
2016-01-18 14:58:31.160 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-18 14:58:46.319 ThaliTest[2265:4898787] multipeer session: reset timer
2016-01-18 14:58:46.319 ThaliTest[2265:4898787] multipeer session: stop timer
2016-01-18 14:58:46.319 ThaliTest[2265:4898787] multipeer session: start timer: 0x14f0aec0
2016-01-18 14:58:46.320 ThaliTest[2265:4898787] server session: connect
2016-01-18 14:58:46.320 ThaliTest[2265:4898787] server session: stateChange:0->1 1453125524156.2206
,2016-01-18 14:58:46.322 ThaliTest[2265:4898787] server: accepting invitation 1453125524156.2206
,2016-01-18 14:58:46.957 ThaliTest[2265:4898787] client: found peer: 1453125524156.2206.0Wl3fg==
2016-01-18 14:58:46.958 ThaliTest[2265:4898956] jxcore: connect 1453125524156.2206.0Wl3fg==
2016-01-18 14:58:46.958 ThaliTest[2265:4898956] client session: connect
2016-01-18 14:58:46.958 ThaliTest[2265:4898956] client session: stateChange:0->1 1453125524156.2206.0Wl3fg==
,2016-01-18 14:58:49.487 ThaliTest[2265:4899721] server session: connected
2016-01-18 14:58:49.487 ThaliTest[2265:4899721] server session: stateChange:1->2 1453125524156.2206
,2016-01-18 14:58:49.503 ThaliTest[2265:4898787] server relay: socket disconnected
2016-01-18 14:58:49.503 ThaliTest[2265:4898787] server relay: 0x16c2f5c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 14:58:49.913 ThaliTest[2265:4899721] server session: not connected 1453125524156.2206
,2016-01-18 14:58:50.435 ThaliTest[2265:4899738] client session: connected
2016-01-18 14:58:50.435 ThaliTest[2265:4899738] client session: stateChange:1->2 1453125524156.2206.0Wl3fg==
,2016-01-18 14:58:50.453 ThaliTest[2265:4899746] client session: fireConnectCallback: 1453125524156.2206.0Wl3fg==
2016-01-18 14:58:50.453 ThaliTest[2265:4899746] jxcore: connect: success
ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-18 14:58:50.454 ThaliTest[2265:4898956] jxcore: connect 1453125524156.2206.0Wl3fg==
2016-01-18 14:58:50.455 ThaliTest[2265:4898956] client: already connect(ing/ed) to 1453125524156.2206.0Wl3fg==
2016-01-18 14:58:50.455 ThaliTest[2265:4898956] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-18 14:58:50.455 ThaliTest[2265:4898956] jxcore: disconnect
2016-01-18 14:58:50.455 ThaliTest[2265:4898956] client session: disconnectFromPeer: 1453125524156.2206.0Wl3fg==
,2016-01-18 14:58:50.455 ThaliTest[2265:4898956] client session: disconnect
2016-01-18 14:58:50.456 ThaliTest[2265:4898956] client session: stateChange:2->0 1453125524156.2206.0Wl3fg==
,2016-01-18 14:58:50.517 ThaliTest[2265:4898956] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-18 14:58:50.838 ThaliTest[2265:4898956] jxcore: stopBroadcasting
2016-01-18 14:58:50.838 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
,2016-01-18 14:58:50.838 ThaliTest[2265:4898956] multipeer session: stop timer
,2016-01-18 14:58:50.838 ThaliTest[2265:4898956] server session: disconnect
2016-01-18 14:58:50.839 ThaliTest[2265:4898956] server session: stateChange:2->0 1453125524156.2206
,2016-01-18 14:58:50.841 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-18 14:59:02.838 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:59:02.840 ThaliTest[2265:4898956] server: starting 1453125542838.2265.J1/WMw==
2016-01-18 14:59:02.840 ThaliTest[2265:4898956] multipeer session: start timer: 0x14f09dc0
2016-01-18 14:59:02.840 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125542838.2265
2016-01-18 14:59:02.840 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-18 14:59:11.525 ThaliTest[2265:4898787] multipeer session: reset timer
2016-01-18 14:59:11.525 ThaliTest[2265:4898787] multipeer session: stop timer
2016-01-18 14:59:11.525 ThaliTest[2265:4898787] multipeer session: start timer: 0x14f09dc0
2016-,01-18 14:59:11.525 ThaliTest[2265:4898787] server session: connect
2016-01-18 14:59:11.525 ThaliTest[2265:4898787] server session: stateChange:0->1 1453125549393.2206
,2016-01-18 14:59:11.527 ThaliTest[2265:4898787] server: accepting invitation 1453125549393.2206
,2016-01-18 14:59:12.468 ThaliTest[2265:4898787] client: found peer: 1453125549393.2206.4lt+gQ==
,2016-01-18 14:59:12.469 ThaliTest[2265:4898956] jxcore: connect 1453125549393.2206.4lt+gQ==
2016-01-18 14:59:12.469 ThaliTest[2265:4898956] client session: connect
2016-01-18 14:59:12.469 ThaliTest[2265:4898956] client session: stateChange:0->1 1453125549393.2206.4lt+gQ==
,2016-01-18 14:59:14.673 ThaliTest[2265:4899808] server session: connected
2016-01-18 14:59:14.673 ThaliTest[2265:4899808] server session: stateChange:1->2 1453125549393.2206
,2016-01-18 14:59:14.732 ThaliTest[2265:4898787] server relay: socket disconnected
2016-01-18 14:59:14.732 ThaliTest[2265:4898787] server relay: 0x16c318c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-18 14:59:14.735 ThaliTest[2265:4899722] server session: not connected 1453125549393.2206
,2016-01-18 14:59:16.153 ThaliTest[2265:4899831] client session: connected
2016-01-18 14:59:16.153 ThaliTest[2265:4899831] client session: stateChange:1->2 1453125549393.2206.4lt+gQ==
,2016-01-18 14:59:16.175 ThaliTest[2265:4899722] client session: fireConnectCallback: 1453125549393.2206.4lt+gQ==
2016-01-18 14:59:16.175 ThaliTest[2265:4899722] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-18 14:59:16.177 ThaliTest[2265:4898956] jxcore: disconnect
,2016-01-18 14:59:16.177 ThaliTest[2265:4898956] client session: disconnectFromPeer: 1453125549393.2206.4lt+gQ==
,2016-01-18 14:59:16.177 ThaliTest[2265:4898956] client session: disconnect
,2016-01-18 14:59:16.177 ThaliTest[2265:4898956] client session: stateChange:2->0 1453125549393.2206.4lt+gQ==
,2016-01-18 14:59:16.180 ThaliTest[2265:4898956] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-18 14:59:16.180 ThaliTest[2265:4898956] jxcore: disconnect
2016-01-18 14:59:16.180 ThaliTest[2265:4898956] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-18 14:59:16.506 ThaliTest[2265:4898956] jxcore: stopBroadcasting
,2016-01-18 14:59:16.506 ThaliTest[2265:4898956] THEMultipeerSession stopping peer
2016-01-18 14:59:16.506 ThaliTest[2265:4898956] multipeer session: stop timer
,2016-01-18 14:59:16.507 ThaliTest[2265:4898956] server session: disconnect
2016-01-18 14:59:16.507 ThaliTest[2265:4898956] server session: stateChange:2->0 1453125549393.2206
,2016-01-18 14:59:16.883 ThaliTest[2265:4898956] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 53703
,2016-01-18 14:59:25.287 ThaliTest[2265:4898956] jxcore: startBroadcasting
,2016-01-18 14:59:25.289 ThaliTest[2265:4898956] server: starting 1453125565287.2265.OitIKQ==
2016-01-18 14:59:25.289 ThaliTest[2265:4898956] multipeer session: start timer: 0x14f0a9e0
2016-01-18 14:59:25.289 ThaliTest[2265:4898956] THEMultipeerSession initialized peer 1453125565287.2265
2016-01-18 14:59:25.289 ThaliTest[2265:4898956] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,2016-01-18 14:59:28.758 ThaliTest[2265:4898787] multipeer session: reset timer
2016-01-18 14:59:28.758 ThaliTest[2265:4898787] multipeer session: stop timer
2016-01-18 14:59:28.758 ThaliTest[2265:4898787] multipeer session: start timer: 0x14f0a9e0
,2016-01-18 14:59:28.758 ThaliTest[2265:4898787] server session: connect
2016-01-18 14:59:28.759 ThaliTest[2265:4898787] server session: stateChange:0->1 1453125566351.2206
,2016-01-18 14:59:28.761 ThaliTest[2265:4898787] server: accepting invitation 1453125566351.2206
,2016-01-18 14:59:29.351 ThaliTest[2265:4898787] client: found peer: 1453125566351.2206.HK9+tg==
2016-01-18 14:59:29.351 ThaliTest[2265:4898956] jxcore: connect 1453125566351.2206.HK9+tg==
,2016-01-18 14:59:29.351 ThaliTest[2265:4898956] client session: connect
2016-01-18 14:59:29.351 ThaliTest[2265:4898956] client session: stateChange:0->1 1453125566351.2206.HK9+tg==
,2016-01-18 14:59:34.989 ThaliTest[2265:4899868] server session: connected
2016-01-18 14:59:34.989 ThaliTest[2265:4899868] server session: stateChange:1->2 1453125566351.2206
,2016-01-18 14:59:35.044 ThaliTest[2265:4898787] server relay: connected (to port: 53703)
,2016-01-18 14:59:38.921 ThaliTest[2265:4899817] client session: connected
2016-01-18 14:59:38.921 ThaliTest[2265:4899817] client session: stateChange:1->2 1453125566351.2206.HK9+tg==
,2016-01-18 14:59:38.971 ThaliTest[2265:4899846] client session: fireConnectCallback: 1453125566351.2206.HK9+tg==
2016-01-18 14:59:38.971 ThaliTest[2265:4899846] jxcore: connect: success
ok 89 Should be able to connect without error
,ok 90 Port should be within range
,2016-01-18 14:59:38.973 ThaliTest[2265:4898787] client: relay established
2016-01-18 14:59:38.974 ThaliTest[2265:4898787] client: new accepted socket: 0x16ed3a60
,data in 50370
,2016-01-18 14:59:40.808 ThaliTest[2265:4899834] server session: not connected 1453125566351.2206
,2016-01-18 14:59:50.489 ThaliTest[2265:4899817] client session: not connected 1453125566351.2206.HK9+tg==
2016-01-18 14:59:50.489 ThaliTest[2265:4899817] client session: onLinkFailure: 1453125566351.2206.HK9+tg==
2016-01-18 14:59:50.489 ThaliTest[2265:4899817] client session: disconnect
2016-01-18 14:59:50.489 ThaliTest[2265:4899817] client session: stateChange:2->0 1453125566351.2206.HK9+tg==
,2016-01-18 14:59:50.490 ThaliTest[2265:4899817] client session: fireConnectionErrorEvent: 1453125566351.2206.HK9+tg==
,2016-01-18 14:59:58.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 14:59:58.766 ThaliTest[2265:4898787] client: found peer: 1453125566351.2206.HK9+tg==
,2016-01-18 15:00:28.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:00:28.767 ThaliTest[2265:4898787] client: found peer: 1453125566351.2206.HK9+tg==
,2016-01-18 15:00:58.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:00:58.766 ThaliTest[2265:4898787] client: found peer: 1453125566351.2206.HK9+tg==
,2016-01-18 15:01:28.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:01:28.767 ThaliTest[2265:4898787] client: found peer: 1453125566351.2206.HK9+tg==
,2016-01-18 15:01:58.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:01:58.767 ThaliTest[2265:4898787] client: found peer: 1453125566351.2206.HK9+tg==
,2016-01-18 15:02:16.929 ThaliTest[2265:4898787] client: lost peer: 1453125566351.2206.HK9+tg==
2016-01-18 15:02:16.929 ThaliTest[2265:4898787] client session: onPeerLost: 1453125566351.2206.HK9+tg==
,2016-01-18 15:02:28.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:02:58.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:03:28.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:03:58.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:04:28.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:04:58.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:05:28.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:05:58.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:06:28.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:06:58.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:07:28.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:07:58.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:08:28.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:08:58.760 ThaliTest[2265:4898787] multipeer session: restart
,2016-01-18 15:09:28.760 ThaliTest[2265:4898787] multipeer session: restart

```
