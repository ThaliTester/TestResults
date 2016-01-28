#### Test 573480784751f5c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/573480784751f5c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DEAD1A37-34C4-4D15-867A-A09BDB5950E0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DEAD1A37-34C4-4D15-867A-A09BDB5950E0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/573480784751f5c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/573480784751f5c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62262"
,(lldb)     command script import "/tmp/DEAD1A37-34C4-4D15-867A-A09BDB5950E0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-28 13:51:00.187 ThaliTest[4112:6708838] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7B669B5E-2BB6-4329-9F90-6251F59F0C3E/Library/Cookies/Cookies.binarycookies
,2016-01-28 13:51:00.420 ThaliTest[4112:6708838] Apache Cordova native platform version 3.9.2 is starting.
2016-01-28 13:51:00.421 ThaliTest[4112:6708838] Multi-tasking -> Device: YES, App: YES
,2016-01-28 13:51:00.427 ThaliTest[4112:6708838] Unlimited access to network resources
,2016-01-28 13:51:00.433 ThaliTest[4112:6708838] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-28 13:51:04.673 ThaliTest[4112:6708838] Resetting plugins due to page load.
,2016-01-28 13:51:06.124 ThaliTest[4112:6708838] Finished load of: file:///var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/index.html
,2016-01-28 13:51:06.262 ThaliTest[4112:6708838] JXcore Cordova plugin initializing
,2016-01-28 13:51:06.263 ThaliTest[4112:6709023] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

,ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

# setup

,# basic

,# teardown

,ok 11 sane

# setup

,# another

,# teardown

,ok 12 sane

,# setup

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

ok 16 should be equal

,ok 17 should not throw

,# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

ok 20 should not throw

,ok 21 should be equal

ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 23 should be equal

,# setup

,# failed to get mobile documents path

,# teardown

,ok 24 should be equal

# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 25 should be equal

ok 26 should be equal

ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 28 should be equal

# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 29 should throw

# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 32 should throw

,# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 33 should throw

# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

ok 36 should be equal

ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

ok 39 should be equal

ok 40 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

ok 44 should be equal

# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

ok 46 should be equal

ok 47 should be equal

# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

ok 49 should be equal

# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

ok 51 should be equal

# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

ok 53 should be equal

# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-28 13:56:43.103 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:43.108 ThaliTest[4112:6709023] server: starting 1453985803103.4112.5e6irA==
2016-01-28 13:56:43.109 ThaliTest[4112:6709023] multipeer session: start timer: 0x17496d40
2016-01-28 13:56:43.109 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985803103.4112
2016-01-28 13:56:43.109 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

2016-01-28 13:56:43.110 ThaliTest[4112:6709023] jxcore: stopBroadcasting,
2016-01-28 13:56:43.110 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:56:43.111 ThaliTest[4112:6709023] multipeer session: stop timer
2016-01-28 13:56:43.111 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
ok 55 Shou,ld be able to call stopBroadcasting without error

2016-01-28 13:56:43.111 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:43.113 ThaliTest[4112:6709023] server: starting 1453985803111.4112.cQsrQA==
2016-01-28 13:56:43.114 ThaliTest[4112:6709023] multipeer session: start timer: 0x17463560
2016-01-28 13:56:43.114 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985803111.4112
,2016-01-28 13:56:43.114 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

,2016-01-28 13:56:43.116 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:56:43.118 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:56:43.118 ThaliTest[4112:6709023] multipeer session: stop timer
,2016-01-28 13:56:43.119 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

2016-01-28 13:56:43.120 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:43.121 ThaliTest[4112:6709023] server: starting 1453985803120.4112.f4fK9A==
2016-01-28 13:56:43.121 ThaliTest[4112:6709023] multipeer session: start timer: 0x1936a690
2016-01-28 13:56:43.121 ThaliTest[4112:6709023] THEMultipeerSession in,itialized peer 1453985803120.4112
2016-01-28 13:56:43.121 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

,2016-01-28 13:56:43.122 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:56:43.124 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:56:43.124 ThaliTest[4112:6709023] multipeer session: stop timer
2016-01-28 13:56:43.124 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting without error

2016-01-28 13:56:43.125 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:43.128 ThaliTest[4112:6709023] server: starting 1453985803125.4112.hatY9w==
2016-01-28 13:56:43.128 ThaliTest[4112:6709023] multipeer session: start timer: 0x17474d40
2016-01-28 13:56:43.128 ThaliTest[4112:6709023] THEMultipeerSession in,itialized peer 1453985803125.4112
,2016-01-28 13:56:43.128 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 60 Should be able to call startBroadcasting without error

2016-01-28 13:56:43.130 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:56:43.131 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:56:43.131 ThaliTest[4112:6709023] multipeer session: stop timer
2016-01-28 13:56:43.131 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
ok 61 Should be able to call stopBroadcasting, without error

,2016-01-28 13:56:43.131 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:43.136 ThaliTest[4112:6709023] server: starting 1453985803131.4112.tX/ltg==
2016-01-28 13:56:43.136 ThaliTest[4112:6709023] multipeer session: start timer: 0x175127b0
2016-01-28 13:56:43.136 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985803131.4112
2016-01-28 13:56:43.136 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 62 Should be able to call startBroadcasting without error

2016-01-28 13:56:43.137 ThaliTest[4112:6709023] jxcore: stopBroadcasting
,2016-01-28 13:56:43.137 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:56:43.140 ThaliTest[4112:6709023] multipeer session: stop timer
2016-01-28 13:56:43.140 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
ok 63 Should be able to call stopBroadcasting without error

2016-01-28 13:56:43.140 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:43.143 ThaliTest[4112:6709023] server: starting 1453985803140.4112.pEu6/w==
2016-01-28 13:56:43.144 ThaliTest[4112:6709023] multipeer session: start timer: 0x1936cf80
2016-01-28 13:56:43.144 ThaliTest[4112:6709023] THEMultipeerSession in,itialized peer 1453985803140.4112
2016-01-28 13:56:43.144 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 64 Should be able to call startBroadcasting without error

2016-01-28 13:56:43.145 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:56:43.145 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:56:43.145 ThaliTest[4112:6709023] multipeer session: stop timer
,2016-01-28 13:56:43.147 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
ok 65 Should be able to call stopBroadcasting without error

2016-01-28 13:56:43.147 ThaliTest[4112:6709023] jxcore: startBroadcasting
2016-01-28 13:56:43.149 ThaliTest[4112:6709023] server: starting 1453985803147.4112.QkQ40g==
2016-01-28 13:56:43.149 ThaliTest[4112:6709023] multipeer session: start timer: 0x1936daf0
2016-01-28 13:56:43.149 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985803147.4112
,2016-01-28 13:56:43.153 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 66 Should be able to call startBroadcasting without error

2016-01-28 13:56:43.153 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:56:43.153 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:56:43.153 ThaliTest[4112:6709023] multipeer session: stop timer
2016-01-28 13:56:43.154 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

2016-01-28 13:56:43.156 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:43.159 ThaliTest[4112:6709023] server: starting 1453985803155.4112.IHWJcQ==
,2016-01-28 13:56:43.160 ThaliTest[4112:6709023] multipeer session: start timer: 0x1751b3a0
2016-01-28 13:56:43.162 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985803155.4112
,2016-01-28 13:56:43.162 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-28 13:56:43.163 ThaliTest[4112:6709023] jxcore: stopBroadcasting
,2016-01-28 13:56:43.163 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
,2016-01-28 13:56:43.163 ThaliTest[4112:6709023] multipeer session: stop timer
,2016-01-28 13:56:43.164 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-01-28 13:56:43.165 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:43.167 ThaliTest[4112:6709023] server: starting 1453985803165.4112.egrU1Q==
,2016-01-28 13:56:43.167 ThaliTest[4112:6709023] multipeer session: start timer: 0x1747a6e0
2016-01-28 13:56:43.169 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985803165.4112
,2016-01-28 13:56:43.170 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-28 13:56:43.171 ThaliTest[4112:6709023] jxcore: stopBroadcasting
,2016-01-28 13:56:43.171 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
,2016-01-28 13:56:43.171 ThaliTest[4112:6709023] multipeer session: stop timer
,2016-01-28 13:56:43.173 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-01-28 13:56:43.174 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:43.175 ThaliTest[4112:6709023] server: starting 1453985803174.4112.GMyvMw==
,2016-01-28 13:56:43.176 ThaliTest[4112:6709023] multipeer session: start timer: 0x174749c0
,2016-01-28 13:56:43.178 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985803174.4112
,2016-01-28 13:56:43.178 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-01-28 13:56:43.179 ThaliTest[4112:6709023] jxcore: stopBroadcasting
,2016-01-28 13:56:43.179 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
,2016-01-28 13:56:43.180 ThaliTest[4112:6709023] multipeer session: stop timer
,2016-01-28 13:56:43.181 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-28 13:56:43.548 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:43.549 ThaliTest[4112:6709023] server: starting 1453985803548.4112.Hppung==
,2016-01-28 13:56:43.549 ThaliTest[4112:6709023] multipeer session: start timer: 0x1742e420
,2016-01-28 13:56:43.550 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985803548.4112
2016-01-28 13:56:43.550 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-01-28 13:56:43.551 ThaliTest[4112:6709023] jxcore: startBroadcasting
2016-01-28 13:56:43.551 ThaliTest[4112:6709023] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

,2016-01-28 13:56:43.553 ThaliTest[4112:6709023] jxcore: stopBroadcasting
,2016-01-28 13:56:43.553 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
,2016-01-28 13:56:43.553 ThaliTest[4112:6709023] multipeer session: stop timer
,2016-01-28 13:56:43.553 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-28 13:56:44.401 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:44.402 ThaliTest[4112:6709023] server: starting 1453985804401.4112.RuMu4Q==
2016-01-28 13:56:44.403 ThaliTest[4112:6709023] multipeer session: start timer: 0x17429520
2016-01-28 13:56:44.403 ThaliTest[4112:6709023] THEMultipeerSession in,itialized peer 1453985804401.4112
2016-01-28 13:56:44.403 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-28 13:56:44.404 ThaliTest[4112:6709023] jxcore: connect foobar
2016-01-28 13:56:44.404 ThaliTest[4112:6709023] client: unknown peer foobar
2016-01-28 13:56:44.404 ThaliTest[4112:6709023] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-01-28 13:56:44.405 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:56:44.405 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:56:44.405 ThaliTest[4112:6709023] multipeer session: stop timer
2016-01-28 13:56:44.406 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-28 13:56:44.981 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:44.982 ThaliTest[4112:6709023] server: starting 1453985804980.4112.yvUsGQ==
2016-01-28 13:56:44.982 ThaliTest[4112:6709023] multipeer session: start timer: 0x157d4590
2016-01-28 13:56:44.982 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985804980.4112
2016-01-28 13:56:44.982 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-28 13:56:44.983 ThaliTest[4112:6709023] jxcore: disconnect
2016-01-28 13:56:44.983 ThaliTest[4112:6709023] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-01-28 13:56:44.985 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:56:44.985 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:56:44.985 ThaliTest[4112:6709,023] multipeer session: stop timer
2016-01-28 13:56:44.985 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-28 13:56:46.000 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:46.002 ThaliTest[4112:6709023] server: starting 1453985806000.4112.rKeQtQ==
2016-01-28 13:56:46.002 ThaliTest[4112:6709023] multipeer session: start timer: 0x1753a530
2016-01-28 13:56:46.002 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985806000.4112
2016-01-28 13:56:46.002 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-28 13:56:47.360 ThaliTest[4112:6708838] client: found peer: 1453985803139.2793.GwKgxQ==
,2016-01-28 13:56:47.361 ThaliTest[4112:6709023] jxcore: connect 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:47.361 ThaliTest[4112:6709023] client session: connect
2016-01-28 13:56:47.361 ThaliTest[4112:6709023] client session: stateChange:0->1 1453985803139.2793.GwKgxQ==
,2016-01-28 13:56:47.475 ThaliTest[4112:6708838] server: accepting invitation 1453985803139.2793
2016-01-28 13:56:47.473 ThaliTest[4112:6708838] multipeer session: reset timer
2016-01-28 13:56:47.473 ThaliTest[4112:6708838] multipeer session: stop timer
2016-01-28 13:56:47.473 ThaliTest[4112:6708838] multipeer session: start timer: 0x1753a530
2016-01-28 13:56:47.473 ThaliTest[4112:6708838] server session: connect
2016-01-28 13:56:47.473 ThaliTest[4112:6708838] server session: stateChange:0->1 1453985803139.2793
,2016-01-28 13:56:49.918 ThaliTest[4112:6709727] server session: connected
2016-01-28 13:56:49.918 ThaliTest[4112:6709727] server session: stateChange:1->2 1453985803139.2793
,2016-01-28 13:56:49.921 ThaliTest[4112:6708838] server relay: socket disconnected
2016-01-28 13:56:49.921 ThaliTest[4112:6708838] server relay: 0x157967f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-28 13:56:49.968 ThaliTest[4112:6709727] client session: connected
2016-01-28 13:56:49.968 ThaliTest[4112:6709727] client session: stateChange:1->2 1453985803139.2793.GwKgxQ==
,2016-01-28 13:56:49.968 ThaliTest[4112:6709722] server session: not connected 1453985803139.2793
,2016-01-28 13:56:49.970 ThaliTest[4112:6709727] client session: fireConnectCallback: 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:49.970 ThaliTest[4112:6709727] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

2016-01-28 13:56:49.972 ThaliTest[4112:6709023] jxcore: disconnect
,2016-01-28 13:56:49.972 ThaliTest[4112:6709023] client session: disconnectFromPeer: 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:49.972 ThaliTest[4112:6709023] client session: disconnect
2016-01-28 13:56:49.972 ThaliTest[4112:6709023] client session: stateChange:2->0 1453985803139.2793.GwKgxQ==
,2016-01-28 13:56:50.034 ThaliTest[4112:6709023] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-28 13:56:50.375 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:56:50.375 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:56:50.375 ThaliTest[4112:6709023] multipeer session: stop timer
2016-01-28 13:56:50.,376 ThaliTest[4112:6709023] server session: disconnect
2016-01-28 13:56:50.376 ThaliTest[4112:6709023] server session: stateChange:2->0 1453985803139.2793
2016-01-28 13:56:50.376 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-28 13:56:50.907 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:50.908 ThaliTest[4112:6709023] server: starting 1453985810907.4112.shXuLA==
2016-01-28 13:56:50.908 ThaliTest[4112:6709023] multipeer session: start timer: 0x19379300
2016-01-28 13:56:50.908 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985810907.4112
2016-01-28 13:56:50.908 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-28 13:56:51.673 ThaliTest[4112:6708838] client: found peer: 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:51.673 ThaliTest[4112:6709023] jxcore: connect 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:51.673 ThaliTest[4112:6709023] client session: connect
2016-01-28 13:56:51.673 ThaliTest[4112:6709023] client session: stateChange:0->1 1453985803139.2793.GwKgxQ==
,2016-01-28 13:56:52.056 ThaliTest[4112:6708838] client: lost peer: 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:52.056 ThaliTest[4112:6708838] client session: onPeerLost: 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:52.056 ThaliTest[4112:6708838] client session: onLinkFailure: 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:52.056 ThaliTest[4112:6708838] client session: disconnect
2016-01-28 13:56:52.056 ThaliTest[4112:6708838] client session: stateChange:1->0 1453985803139.2793.GwKgxQ==
,2016-01-28 13:56:52.057 ThaliTest[4112:6708838] client session: fireConnectCallback: 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:52.057 ThaliTest[4112:6708838] jxcore: connect: fail: Peer disconnected
,2016-01-28 13:56:52.144 ThaliTest[4112:6708838] client: found peer: 1453985807853.2793.U9eTAQ==
,2016-01-28 13:56:52.144 ThaliTest[4112:6709023] jxcore: connect 1453985807853.2793.U9eTAQ==
2016-01-28 13:56:52.144 ThaliTest[4112:6709023] client session: connect
,2016-01-28 13:56:52.145 ThaliTest[4112:6709023] client session: stateChange:0->1 1453985807853.2793.U9eTAQ==
,2016-01-28 13:56:52.172 ThaliTest[4112:6708838] multipeer session: reset timer
2016-01-28 13:56:52.172 ThaliTest[4112:6708838] multipeer session: stop timer
2016-01-28 13:56:52.173 ThaliTest[4112:6708838] multipeer session: start timer: 0x19379300
2016-01-28 13:56:52.173 ThaliTest[4112:6708838] server session: connect
,2016-01-28 13:56:52.173 ThaliTest[4112:6708838] server session: stateChange:0->1 1453985807853.2793
,2016-01-28 13:56:52.175 ThaliTest[4112:6708838] server: accepting invitation 1453985807853.2793
,2016-01-28 13:56:53.064 ThaliTest[4112:6709023] jxcore: connect 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:53.064 ThaliTest[4112:6709023] client: connect: unreachable 1453985803139.2793.GwKgxQ==
2016-01-28 13:56:53.064 ThaliTest[4112:6709023] jxcore: connect: fail: Peer unreachable
,2016-01-28 13:56:55.159 ThaliTest[4112:6709728] server session: connected
2016-01-28 13:56:55.159 ThaliTest[4112:6709728] server session: stateChange:1->2 1453985807853.2793
,2016-01-28 13:56:55.167 ThaliTest[4112:6708838] server relay: socket disconnected
2016-01-28 13:56:55.167 ThaliTest[4112:6708838] server relay: 0x17c598b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-28 13:56:55.191 ThaliTest[4112:6709722] server session: not connected 1453985807853.2793
,2016-01-28 13:56:55.219 ThaliTest[4112:6709728] client session: connected
2016-01-28 13:56:55.219 ThaliTest[4112:6709728] client session: stateChange:1->2 1453985807853.2793.U9eTAQ==
,2016-01-28 13:56:55.229 ThaliTest[4112:6709759] client session: fireConnectCallback: 1453985807853.2793.U9eTAQ==
2016-01-28 13:56:55.230 ThaliTest[4112:6709759] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-01-28 13:56:55.231 ThaliTest[4112:6709023] jxcore: connect 1453985807853.2793.U9eTAQ==
,2016-01-28 13:56:55.231 ThaliTest[4112:6709023] client: already connect(ing/ed) to 1453985807853.2793.U9eTAQ==
,2016-01-28 13:56:55.231 ThaliTest[4112:6709023] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-01-28 13:56:55.232 ThaliTest[4112:6709023] jxcore: disconnect
,2016-01-28 13:56:55.232 ThaliTest[4112:6709023] client session: disconnectFromPeer: 1453985807853.2793.U9eTAQ==
,2016-01-28 13:56:55.232 ThaliTest[4112:6709023] client session: disconnect
,2016-01-28 13:56:55.233 ThaliTest[4112:6709023] client session: stateChange:2->0 1453985807853.2793.U9eTAQ==
,2016-01-28 13:56:55.238 ThaliTest[4112:6709023] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-28 13:56:55.573 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:56:55.573 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
,2016-01-28 13:56:55.573 ThaliTest[4112:6709023] multipeer session: stop timer
,2016-01-28 13:56:55.574 ThaliTest[4112:6709023] server session: disconnect
2016-01-28 13:56:55.574 ThaliTest[4112:6709023] server session: stateChange:2->0 1453985807853.2793
,2016-01-28 13:56:55.574 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-28 13:56:56.152 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:56:56.154 ThaliTest[4112:6709023] server: starting 1453985816152.4112.vSyajA==
,2016-01-28 13:56:56.154 ThaliTest[4112:6709023] multipeer session: start timer: 0x175a6490
2016-01-28 13:56:56.154 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985816152.4112
,2016-01-28 13:56:56.155 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-01-28 13:56:57.425 ThaliTest[4112:6708838] client: found peer: 1453985813100.2793.qdPuCw==
,2016-01-28 13:56:57.426 ThaliTest[4112:6709023] jxcore: connect 1453985813100.2793.qdPuCw==
2016-01-28 13:56:57.426 ThaliTest[4112:6709023] client session: connect
2016-01-28 13:56:57.426 ThaliTest[4112:6709023] client session: stateChange:0->1 1453985813100.2793.qdPuCw==
,2016-01-28 13:56:57.432 ThaliTest[4112:6708838] multipeer session: reset timer
2016-01-28 13:56:57.433 ThaliTest[4112:6708838] multipeer session: stop timer
2016-01-28 13:56:57.433 ThaliTest[4112:6708838] multipeer session: start timer: 0x175a6490
2016-,01-28 13:56:57.433 ThaliTest[4112:6708838] server session: connect
2016-01-28 13:56:57.433 ThaliTest[4112:6708838] server session: stateChange:0->1 1453985813100.2793
2016-01-28 13:56:57.435 ThaliTest[4112:6708838] server: accepting invitation 1453985813100.2793
,2016-01-28 13:57:00.529 ThaliTest[4112:6709724] client session: connected
2016-01-28 13:57:00.529 ThaliTest[4112:6709724] client session: stateChange:1->2 1453985813100.2793.qdPuCw==
,2016-01-28 13:57:00.531 ThaliTest[4112:6709728] server session: connected
2016-01-28 13:57:00.531 ThaliTest[4112:6709728] server session: stateChange:1->2 1453985813100.2793
,2016-01-28 13:57:00.600 ThaliTest[4112:6709724] client session: fireConnectCallback: 1453985813100.2793.qdPuCw==
2016-01-28 13:57:00.600 ThaliTest[4112:6709724] jxcore: connect: success
,2016-01-28 13:57:00.601 ThaliTest[4112:6708838] server relay: socket disconnected
,2016-01-28 13:57:00.601 ThaliTest[4112:6708838] server relay: 0x17c2d6f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,ok 93 Should be able to connect without error

ok 94 Port should be within range

,2016-01-28 13:57:00.602 ThaliTest[4112:6709023] jxcore: disconnect
2016-01-28 13:57:00.602 ThaliTest[4112:6709023] client session: disconnectFromPeer: 1453985813100.2793.qdPuCw==
2016-01-28 13:57:00.602 ThaliTest[4112:6709023] client session: disconnect,
2016-01-28 13:57:00.602 ThaliTest[4112:6709023] client session: stateChange:2->0 1453985813100.2793.qdPuCw==
,2016-01-28 13:57:00.607 ThaliTest[4112:6709023] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-01-28 13:57:00.608 ThaliTest[4112:6709023] jxcore: disconnect
2016-01-28 13:57:00.608 ThaliTest[4112:6709023] jxcore: disconnect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,2016-01-28 13:57:00.611 ThaliTest[4112:6709722] server session: not connected 1453985813100.2793
,# setup

,calling stopBroadcasting

,2016-01-28 13:57:01.906 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:57:01.906 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:57:01.906 ThaliTest[4112:6709023] multipeer session: stop timer
2016-01-28 13:57:01.,906 ThaliTest[4112:6709023] server session: disconnect
2016-01-28 13:57:01.906 ThaliTest[4112:6709023] server session: stateChange:2->0 1453985813100.2793
,2016-01-28 13:57:01.908 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 59980

,2016-01-28 13:57:02.406 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:57:02.408 ThaliTest[4112:6709023] server: starting 1453985822406.4112.ZpquvA==
2016-01-28 13:57:02.408 ThaliTest[4112:6709023] multipeer session: start timer: 0x175d8f90
2016-01-28 13:57:02.408 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985822406.4112
2016-01-28 13:57:02.408 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-01-28 13:57:03.621 ThaliTest[4112:6708838] multipeer session: reset timer
2016-01-28 13:57:03.621 ThaliTest[4112:6708838] multipeer session: stop timer
2016-01-28 13:57:03.621 ThaliTest[4112:6708838] multipeer session: start timer: 0x175d8f90
2016-01-28 13:57:03.621 ThaliTest[4112:6708838] server session: connect
2016-01-28 13:57:03.622 ThaliTest[4112:6708838] server session: stateChange:0->1 1453985819496.2793
,2016-01-28 13:57:03.624 ThaliTest[4112:6708838] server: accepting invitation 1453985819496.2793
,2016-01-28 13:57:03.853 ThaliTest[4112:6708838] client: found peer: 1453985819496.2793.cX8SPA==
2016-01-28 13:57:03.854 ThaliTest[4112:6709023] jxcore: connect 1453985819496.2793.cX8SPA==
,2016-01-28 13:57:03.854 ThaliTest[4112:6709023] client session: connect
2016-01-28 13:57:03.854 ThaliTest[4112:6709023] client session: stateChange:0->1 1453985819496.2793.cX8SPA==
,2016-01-28 13:57:06.047 ThaliTest[4112:6709724] server session: connected
2016-01-28 13:57:06.047 ThaliTest[4112:6709724] server session: stateChange:1->2 1453985819496.2793
,2016-01-28 13:57:06.101 ThaliTest[4112:6708838] server relay: connected (to port: 59980)
,2016-01-28 13:57:06.567 ThaliTest[4112:6709759] server session: not connected 1453985819496.2793
,2016-01-28 13:57:06.631 ThaliTest[4112:6709724] client session: connected
2016-01-28 13:57:06.631 ThaliTest[4112:6709724] client session: stateChange:1->2 1453985819496.2793.cX8SPA==
,2016-01-28 13:57:06.639 ThaliTest[4112:6709726] client session: fireConnectCallback: 1453985819496.2793.cX8SPA==
2016-01-28 13:57:06.639 ThaliTest[4112:6709726] jxcore: connect: success
ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-01-28 13:57:06.641 ThaliTest[4112:6708838] client: relay established
2016-01-28 13:57:06.641 ThaliTest[4112:6708838] client: new accepted socket: 0x17c5c760
,data in 1095

,data in 8689

,data in 19710

,data in 25185

,data in 28470

,data in 35040

,data in 39420

,data in 49275

,data in 54750

,data in 59130

,data in 78840

,data in 84315

,data in 89506

,data in 103741

,data in 112501

,data in 131072

,ok 100 the test messages should be equal

,2016-01-28 13:57:07.285 ThaliTest[4112:6709023] jxcore: disconnect
2016-01-28 13:57:07.285 ThaliTest[4112:6709023] client session: disconnectFromPeer: 1453985819496.2793.cX8SPA==
2016-01-28 13:57:07.285 ThaliTest[4112:6709023] client session: disconnect
2016-01-28 13:57:07.285 ThaliTest[4112:6709023] client session: stateChange:2->0 1453985819496.2793.cX8SPA==
,2016-01-28 13:57:07.289 ThaliTest[4112:6709023] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-28 13:57:07.622 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:57:07.623 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:57:07.623 ThaliTest[4112:6709023] multipeer session: stop timer
2016-01-28 13:57:07.623 ThaliTest[4112:6709023] server session: disconnect
2016-01-28 13:57:07.623 ThaliTest[4112:6709023] server session: stateChange:2->0 1453985819496.2793
,2016-01-28 13:57:07.626 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 59986

,2016-01-28 13:57:08.139 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:57:08.140 ThaliTest[4112:6709023] server: starting 1453985828139.4112.qquF1Q==
2016-01-28 13:57:08.140 ThaliTest[4112:6709023] multipeer session: start timer: 0x17c5de50
2016-01-28 13:57:08.140 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 1453985828139.4112
2016-01-28 13:57:08.141 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-28 13:57:09.306 ThaliTest[4112:6708838] client: found peer: 1453985825107.2793.GJZaDQ==
,[{"peerIdentifier":"1453985825107.2793.GJZaDQ==","peerName":"(null)","peerAvailable":true}]

2016-01-28 13:57:09.307 ThaliTest[4112:6709023] jxcore: connect 1453985825107.2793.GJZaDQ==
2016-01-28 13:57:09.307 ThaliTest[4112:6709023] client session: connect
,2016-01-28 13:57:09.307 ThaliTest[4112:6709023] client session: stateChange:0->1 1453985825107.2793.GJZaDQ==
,2016-01-28 13:57:09.517 ThaliTest[4112:6708838] multipeer session: reset timer
2016-01-28 13:57:09.517 ThaliTest[4112:6708838] multipeer session: stop timer
2016-01-28 13:57:09.517 ThaliTest[4112:6708838] multipeer session: start timer: 0x17c5de50
2016-01-28 13:57:09.517 ThaliTest[4112:6708838] server session: connect
2016-01-28 13:57:09.517 ThaliTest[4112:6708838] server session: stateChange:0->1 1453985825107.2793
,2016-01-28 13:57:09.521 ThaliTest[4112:6708838] server: accepting invitation 1453985825107.2793
,2016-01-28 13:57:11.808 ThaliTest[4112:6709726] server session: connected
2016-01-28 13:57:11.808 ThaliTest[4112:6709726] server session: stateChange:1->2 1453985825107.2793
,2016-01-28 13:57:11.812 ThaliTest[4112:6709726] client session: connected
2016-01-28 13:57:11.812 ThaliTest[4112:6709726] client session: stateChange:1->2 1453985825107.2793.GJZaDQ==
,2016-01-28 13:57:11.815 ThaliTest[4112:6708838] server relay: connected (to port: 59986)
,2016-01-28 13:57:11.923 ThaliTest[4112:6709728] client session: fireConnectCallback: 1453985825107.2793.GJZaDQ==
2016-01-28 13:57:11.924 ThaliTest[4112:6709728] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should be within range

ok 105 First connect should succeed

,2016-01-28 13:57:11.940 ThaliTest[4112:6708838] client: relay established
2016-01-28 13:57:11.940 ThaliTest[4112:6708838] client: new accepted socket: 0x17c8e980
,2016-01-28 13:57:11.999 ThaliTest[4112:6709728] server session: not connected 1453985825107.2793
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-01-28 13:57:12.061 ThaliTest[4112:6708838] client: socket closed
2016-01-28 13:57:12.061 ThaliTest[4112:6708838] client relay: socket disconnected
,2016-01-28 13:57:12.061 ThaliTest[4112:6708838] client relay: 0x17c8e980 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-28 13:57:12.061 ThaliTest[4112:6708838] client session: socket closed: 1453985825107.2793.GJZaDQ==
,2016-01-28 13:57:12.061 ThaliTest[4112:6708838] client session: onLinkFailure: 1453985825107.2793.GJZaDQ==
2016-01-28 13:57:12.061 ThaliTest[4112:6708838] client session: disconnect
2016-01-28 13:57:12.062 ThaliTest[4112:6708838] client session: stateChange:2->0 1453985825107.2793.GJZaDQ==
,2016-01-28 13:57:12.065 ThaliTest[4112:6708838] client session: fireConnectionErrorEvent: 1453985825107.2793.GJZaDQ==
,2016-01-28 13:57:12.066 ThaliTest[4112:6709023] jxcore: connect 1453985825107.2793.GJZaDQ==
2016-01-28 13:57:12.066 ThaliTest[4112:6709023] client session: connect
,2016-01-28 13:57:12.067 ThaliTest[4112:6709023] client session: stateChange:0->1 1453985825107.2793.GJZaDQ==
,2016-01-28 13:57:12.134 ThaliTest[4112:6708838] multipeer session: reset timer
2016-01-28 13:57:12.134 ThaliTest[4112:6708838] multipeer session: stop timer
2016-01-28 13:57:12.134 ThaliTest[4112:6708838] multipeer session: start timer: 0x17c5de50
,2016-01-28 13:57:12.134 ThaliTest[4112:6708838] server: disconnecting to refresh session (1453985825107.2793)
2016-01-28 13:57:12.134 ThaliTest[4112:6708838] server session: disconnect
2016-01-28 13:57:12.134 ThaliTest[4112:6708838] server session: stateChange:2->0 1453985825107.2793
,2016-01-28 13:57:12.136 ThaliTest[4112:6708838] server session: connect
2016-01-28 13:57:12.136 ThaliTest[4112:6708838] server session: stateChange:0->1 1453985825107.2793
,2016-01-28 13:57:12.138 ThaliTest[4112:6708838] server: accepting invitation 1453985825107.2793
,2016-01-28 13:57:14.650 ThaliTest[4112:6709726] server session: connected
,2016-01-28 13:57:14.650 ThaliTest[4112:6709726] server session: stateChange:1->2 1453985825107.2793
,2016-01-28 13:57:14.693 ThaliTest[4112:6708838] server relay: connected (to port: 59986)
,2016-01-28 13:57:14.758 ThaliTest[4112:6709728] client session: connected
2016-01-28 13:57:14.758 ThaliTest[4112:6709728] client session: stateChange:1->2 1453985825107.2793.GJZaDQ==
,2016-01-28 13:57:14.779 ThaliTest[4112:6709728] client session: fireConnectCallback: 1453985825107.2793.GJZaDQ==
2016-01-28 13:57:14.779 ThaliTest[4112:6709728] jxcore: connect: success
ok 108 Should be able to connect without error

ok 109 Port should be within range

ok 110 Second connect should succeed

,2016-01-28 13:57:14.788 ThaliTest[4112:6708838] client: relay established
2016-01-28 13:57:14.788 ThaliTest[4112:6708838] client: new accepted socket: 0x17f929b0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-01-28 13:57:14.902 ThaliTest[4112:6708838] client: socket closed
2016-01-28 13:57:14.902 ThaliTest[4112:6708838] client relay: socket disconnected
2016-01-28 13:57:14.902 ThaliTest[4112:6708838] client relay: 0x17f929b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-28 13:57:14.902 ThaliTest[4112:6708838] client session: socket closed: 1453985825107.2793.GJZaDQ==
2016-01-28 13:57:14.902 ThaliTest[4112:6708838] client session: onLinkFailure: 1453985825107.2793.GJZaDQ==
2016-01-28 13:57:14.902 ThaliTest[4112:6708838] client session: disconnect
2016-01-28 13:57:14.902 ThaliTest[4112:6708838] client session: stateChange:2->0 1453985825107.2793.GJZaDQ==
,2016-01-28 13:57:14.905 ThaliTest[4112:6708838] client session: fireConnectionErrorEvent: 1453985825107.2793.GJZaDQ==
,2016-01-28 13:57:14.944 ThaliTest[4112:6709759] server session: not connected 1453985825107.2793
,calling stopBroadcasting

,2016-01-28 13:57:14.953 ThaliTest[4112:6709023] jxcore: stopBroadcasting
,2016-01-28 13:57:14.953 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
,2016-01-28 13:57:14.954 ThaliTest[4112:6709023] multipeer session: stop timer
,2016-01-28 13:57:14.955 ThaliTest[4112:6709023] server session: disconnect
,2016-01-28 13:57:14.957 ThaliTest[4112:6709023] server session: stateChange:2->0 1453985825107.2793
,2016-01-28 13:57:15.234 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/7B669B5E-2BB6-4329-9F90-6251F59F0C3E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-28 13:57:15.623 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:57:15.624 ThaliTest[4112:6709023] server: starting 8vk05J_k2lTBa3VjxkGkbg.0OrEEQ==
2016-01-28 13:57:15.624 ThaliTest[4112:6709023] multipeer session: start timer: 0x1763cb60
2016-01-28 13:57:15.624 ThaliTest[4112:6709023] THEMultipeerSessio,n initialized peer 8vk05J_k2lTBa3VjxkGkbg
2016-01-28 13:57:15.624 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

2016-01-28 13:57:15.626 ThaliTest[4112:6709023] jxcore: stopBroadcasting
,2016-01-28 13:57:15.626 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
,2016-01-28 13:57:15.626 ThaliTest[4112:6709023] multipeer session: stop timer
,2016-01-28 13:57:15.626 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/7B669B5E-2BB6-4329-9F90-6251F59F0C3E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-28 13:57:16.191 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:57:16.192 ThaliTest[4112:6709023] server: starting 8vk05J_k2lTBa3VjxkGkbg.5dgugg==
2016-01-28 13:57:16.193 ThaliTest[4112:6709023] multipeer session: start timer: 0x156f3640
2016-01-28 13:57:16.193 ThaliTest[4112:6709023] THEMultipeerSessio,n initialized peer 8vk05J_k2lTBa3VjxkGkbg
2016-01-28 13:57:16.193 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-28 13:57:16.194 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:57:16.194 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:57:16.194 ThaliTest[4112:6709023,] multipeer session: stop timer
2016-01-28 13:57:16.194 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/7B669B5E-2BB6-4329-9F90-6251F59F0C3E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-28 13:57:18.628 ThaliTest[4112:6709023] jxcore: startBroadcasting
,2016-01-28 13:57:18.629 ThaliTest[4112:6709023] server: starting 8vk05J_k2lTBa3VjxkGkbg.i3zmOg==
2016-01-28 13:57:18.629 ThaliTest[4112:6709023] multipeer session: start timer: 0x1919de80
2016-01-28 13:57:18.630 ThaliTest[4112:6709023] THEMultipeerSession initialized peer 8vk05J_k2lTBa3VjxkGkbg
2016-01-28 13:57:18.630 ThaliTest[4112:6709023] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-01-28 13:57:20.391 ThaliTest[4112:6708838] client: found peer: XA-z6oLuveEaSVM6G2JelA.E1pQ0g==
,2016-01-28 13:57:22.848 ThaliTest[4112:6709023] jxcore: connect XA-z6oLuveEaSVM6G2JelA.E1pQ0g==
,2016-01-28 13:57:22.848 ThaliTest[4112:6709023] client session: connect
,2016-01-28 13:57:22.849 ThaliTest[4112:6709023] client session: stateChange:0->1 XA-z6oLuveEaSVM6G2JelA.E1pQ0g==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-01-28 13:57:25.164 ThaliTest[4112:6708838] multipeer session: reset timer
2016-01-28 13:57:25.164 ThaliTest[4112:6708838] multipeer session: stop timer
2016-01-28 13:57:25.164 ThaliTest[4112:6708838] multipeer session: start timer: 0x1919de80
2016-01-28 13:57:25.164 ThaliTest[4112:6708838] server session: connect
2016-01-28 13:57:25.164 ThaliTest[4112:6708838] server session: stateChange:0->1 XA-z6oLuveEaSVM6G2JelA
,2016-01-28 13:57:25.167 ThaliTest[4112:6708838] server: accepting invitation XA-z6oLuveEaSVM6G2JelA
,2016-01-28 13:57:27.659 ThaliTest[4112:6709868] server session: connected
2016-01-28 13:57:27.659 ThaliTest[4112:6709868] server session: stateChange:1->2 XA-z6oLuveEaSVM6G2JelA
,2016-01-28 13:57:27.667 ThaliTest[4112:6708838] server relay: connected (to port: 60001)
,server bridge: new client socket

,2016-01-28 13:57:27.687 ThaliTest[4112:6709759] client session: connected
2016-01-28 13:57:27.687 ThaliTest[4112:6709759] client session: stateChange:1->2 XA-z6oLuveEaSVM6G2JelA.E1pQ0g==
,2016-01-28 13:57:27.688 ThaliTest[4112:6709759] client session: fireConnectCallback: XA-z6oLuveEaSVM6G2JelA.E1pQ0g==
2016-01-28 13:57:27.688 ThaliTest[4112:6709759] jxcore: connect: success
,2016-01-28 13:57:27.690 ThaliTest[4112:6708838] client: relay established
2016-01-28 13:57:27.690 ThaliTest[4112:6708838] client: new accepted socket: 0x17390790
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,Possibly unhandled Error. ETIMEDOUT
onError@/private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:66:18
ajax/<@/private/var/mobile/Containers/Bundle/Applicati,on/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:108:1
Request.prototype.init/self.callback@/private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/node_modules/pouchdb/node_modules/request/request.js:123:7
emit@events.js:82:1
Request.prototype.start/self.timeoutTimer<@/private/var/mobile/Containers/Bundle/Application/AEB1B87A-CF8B-49AB-B9D1-4580B2243DBA/ThaliTest.app/www/jxcore/node_modules/pouchdb/node_modules/request/request.js:590:7
$9@timers.js:120:1


,client bridge: socket closed

,ok 123 1st change of remote doc should contain remote id

,ok 124 Can update remote doc without error

null

,{ ok: true,
  id: '08d0e19a-88c0-4957-b0f9-b72a0a1bca47',
  rev: '2-5384693e0fadfcdf44a0fa2deadd6191' }

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-01-28 13:57:53.753 ThaliTest[4112:6709023] jxcore: stopBroadcasting
2016-01-28 13:57:53.754 ThaliTest[4112:6709023] THEMultipeerSession stopping peer
2016-01-28 13:57:53.754 ThaliTest[4112:6709023] multipeer session: stop timer
2016-01-28 13:57:53.754 ThaliTest[4112:6709023] client session: disconnect
2016-01-28 13:57:53.754 ThaliTest[4112:6709023] client session: stateChange:2->0 XA-z6oLuveEaSVM6G2JelA.E1pQ0g==
,2016-01-28 13:57:53.757 ThaliTest[4112:6709023] server session: disconnect
2016-01-28 13:57:53.757 ThaliTest[4112:6709023] server session: stateChange:2->0 XA-z6oLuveEaSVM6G2JelA
,2016-01-28 13:57:53.766 ThaliTest[4112:6709023] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,mux server bridge listener closed

,client bridge: socket closed

server bridge: socket closed

,# teardown

,ok 128 host address should match

,ok 129 port should match

ok 130 peer should be available

,ok 131 peer should be unavailable

,# setup

,# #startUpdateAdvertisingAndListening should use different USN after every invocation

,# teardown

,ok 132 when receiving the first byebye, the second USN should not be set yet

,ok 133 USN should have changed from the first one

,ok 134 when receiving the second byebye, the first USN should be already set

,# setup

,# messages with invalid location or USN should be ignored

,# teardown

,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000

,ok 135 should not have emitted with invalid port

,WARN thaliWifiInfrastructure Received an invalid USN value: 

,ok 136 should not have emitted with invalid USN

,# setup

,# verify that Thali-specific messages are filtered correctly

,# teardown

,ok 137 irrelevant messages should be ignored

ok 138 relevant messages should not be ignored

ok 139 messages from this device should be ignored

,# setup

,# #start should fail if called twice in a row

,# teardown

,ok 140 specific error should be received

# setup

,# #startUpdateAdvertisingAndListening should fail invalid router has been passed

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

,ok 141 specific error should be received

,# setup

,# #startUpdateAdvertisingAndListening should fail if router server starting fails

,# teardown

,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE

,ok 142 specific error expected

,# setup

,# #startUpdateAdvertisingAndListening should start hosting given router object

,# teardown

,client bridge: socket closed

,Error in mux client bridge Error: write EPIPE

syncRetry called when not started

,ok 143 server should respond with code 200

,# setup

,# #stop can be called multiple times in a row

,# teardown

,ok 144 should be in stopped state

ok 145 should still be in stopped state

,# setup

,# #startListeningForAdvertisements can be called multiple times in a row

,client bridge: socket closed

,# teardown

,ok 146 should be in listening state

,ok 147 should still be in listening state

,# setup

,# #stopListeningForAdvertisements can be called multiple times in a row

,# teardown

,ok 148 should not be in listening state

ok 149 should still not be in listening state

,# setup

,# #stopAdvertisingAndListening can be called multiple times in a row

,# teardown

,ok 150 should not be in advertising state

ok 151 should still not be in advertising state

# setup

,# functions are run from a queue in the right order

,# teardown

,ok 152 call order must match

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
