#### Test 57132760f6ec045_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57132760f6ec045/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/77651871-191F-4081-A464-C9EA65332B73/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/77651871-191F-4081-A464-C9EA65332B73/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57132760f6ec045/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57132760f6ec045/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/60B90E9B-2A8E-41C9-AB60-02366230672A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60786"
,(lldb)     command script import "/tmp/77651871-191F-4081-A464-C9EA65332B73/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-25 22:41:46.265 ThaliTest[493:739146] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/723C710E-6947-4548-8AE7-217DE51F718E/Library/Cookies/Cookies.binarycookies
,2016-01-25 22:41:46.784 ThaliTest[493:739146] Apache Cordova native platform version 3.9.2 is starting.
2016-01-25 22:41:46.786 ThaliTest[493:739146] Multi-tasking -> Device: YES, App: YES
,2016-01-25 22:41:46.796 ThaliTest[493:739146] Unlimited access to network resources
,2016-01-25 22:41:46.809 ThaliTest[493:739146] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-25 22:41:56.969 ThaliTest[493:739146] Resetting plugins due to page load.
,2016-01-25 22:42:00.203 ThaliTest[493:739146] Finished load of: file:///var/mobile/Containers/Bundle/Application/60B90E9B-2A8E-41C9-AB60-02366230672A/ThaliTest.app/www/index.html
,2016-01-25 22:42:00.356 ThaliTest[493:739146] JXcore Cordova plugin initializing
2016-01-25 22:42:00.357 ThaliTest[493:739409] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60B90E9B-2A8E-41C9-AB60-02366230672A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60B90E9B-2A8E-41C9-AB60-02366230672A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60B90E9B-2A8E-41C9-AB60-02366230672A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60B90E9B-2A8E-41C9-AB60-02366230672A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60B90E9B-2A8E-41C9-AB60-02366230672A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60B90E9B-2A8E-41C9-AB60-02366230672A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/60B90E9B-2A8E-41C9-AB60-02366230672A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-01-25 22:48:02.037 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.052 ThaliTest[493:739409] server: starting 1453758482037.493.NyPwMg==
,2016-01-25 22:48:02.053 ThaliTest[493:739409] multipeer session: start timer: 0x19631e70
,2016-01-25 22:48:02.055 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758482037.493
2016-01-25 22:48:02.055 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error

2016-01-,25 22:48:02.059 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 22:48:02.059 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:02.059 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:02.060 ThaliTest[,493:739409] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error

2016-01-25 22:48:02.062 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.067 ThaliTest[493:739409] server: starting 1453758482061.493.v4JL+Q==
2016-01-25 22:48:02.068 ThaliTest[493:739409] multipeer session: start timer: 0x19638f80
2016-01-25 22:48:02.068 ThaliTest[493:739409] THEMultipeerSession initializ,ed peer 1453758482061.493
2016-01-25 22:48:02.069 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error

2016-01-25 22:48:02.077 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 ,22:48:02.077 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:02.077 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:02.078 ThaliTest[493:739409] jxcore: stopBroadcasting: success
ok 48 Should be able to call, stopBroadcasting without error

2016-01-25 22:48:02.080 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.093 ThaliTest[493:739409] server: starting 1453758482080.493.kOugyA==
2016-01-25 22:48:02.095 ThaliTest[493:739409] multipeer session: start timer: 0x1963a1a0
2016-01-25 22:48:02.095 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758482080.493
2016-01-25 22:48:02.096 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error

2016-01-25 22:48:02.099 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 ,22:48:02.099 ThaliTest[493:739409] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.100 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:02.106 ThaliTest[493:739409] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.108 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.117 ThaliTest[493:739409] server: starting 1453758482108.493.v0lOhQ==
2016-01-25 22:48:02.118 ThaliTest[493:739409] multipeer session: start timer: 0x1963a1a0
2016-01-25 22:48:02.118 ThaliTest[493:739409] THEMultipeerSession initializ,ed peer 1453758482108.493
2016-01-25 22:48:02.119 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error

2016-01-25 22:48:02.121 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 ,22:48:02.121 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:02.121 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:02.122 ThaliTest[493:739409] jxcore: stopBroadcasting: success
ok 52 Should be able to call, stopBroadcasting without error

2016-01-25 22:48:02.123 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.142 ThaliTest[493:739409] server: starting 1453758482123.493.LSNwFw==
,2016-01-25 22:48:02.146 ThaliTest[493:739409] multipeer session: start timer: 0x1963b880
,2016-01-25 22:48:02.148 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758482123.493
,2016-01-25 22:48:02.153 ThaliTest[493:739409] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,
,2016-01-25 22:48:02.156 ThaliTest[493:739409] jxcore: stopBroadcasting
,2016-01-25 22:48:02.157 ThaliTest[493:739409] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.158 ThaliTest[493:739409] multipeer session: stop timer
,2016-01-25 22:48:02.159 ThaliTest[493:739409] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.165 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.167 ThaliTest[493:739409] server: starting 1453758482164.493.Gf2Miw==
,2016-01-25 22:48:02.169 ThaliTest[493:739409] multipeer session: start timer: 0x192a88b0
,2016-01-25 22:48:02.175 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758482164.493
,2016-01-25 22:48:02.176 ThaliTest[493:739409] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.178 ThaliTest[493:739409] jxcore: stopBroadcasting
,2016-01-25 22:48:02.179 ThaliTest[493:739409] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.179 ThaliTest[493:739409] multipeer session: stop timer
,2016-01-25 22:48:02.181 ThaliTest[493:739409] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,
,2016-01-25 22:48:02.186 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.188 ThaliTest[493:739409] server: starting 1453758482185.493.AGxeNQ==
,2016-01-25 22:48:02.190 ThaliTest[493:739409] multipeer session: start timer: 0x19637a60
,2016-01-25 22:48:02.194 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758482185.493
,2016-01-25 22:48:02.195 ThaliTest[493:739409] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.200 ThaliTest[493:739409] jxcore: stopBroadcasting
,2016-01-25 22:48:02.200 ThaliTest[493:739409] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.201 ThaliTest[493:739409] multipeer session: stop timer
,2016-01-25 22:48:02.202 ThaliTest[493:739409] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.208 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.211 ThaliTest[493:739409] server: starting 1453758482207.493.rK1E8A==
,2016-01-25 22:48:02.214 ThaliTest[493:739409] multipeer session: start timer: 0x19638450
,2016-01-25 22:48:02.220 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758482207.493
,2016-01-25 22:48:02.220 ThaliTest[493:739409] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.223 ThaliTest[493:739409] jxcore: stopBroadcasting
,2016-01-25 22:48:02.223 ThaliTest[493:739409] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.225 ThaliTest[493:739409] multipeer session: stop timer
,2016-01-25 22:48:02.230 ThaliTest[493:739409] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error

,2016-01-25 22:48:02.232 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.235 ThaliTest[493:739409] server: starting 1453758482232.493.heKm6g==
,2016-01-25 22:48:02.237 ThaliTest[493:739409] multipeer session: start timer: 0x1927ef30
,2016-01-25 22:48:02.240 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758482232.493
,2016-01-25 22:48:02.242 ThaliTest[493:739409] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.244 ThaliTest[493:739409] jxcore: stopBroadcasting
,2016-01-25 22:48:02.245 ThaliTest[493:739409] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.245 ThaliTest[493:739409] multipeer session: stop timer
,2016-01-25 22:48:02.246 ThaliTest[493:739409] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,
,2016-01-25 22:48:02.250 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.252 ThaliTest[493:739409] server: starting 1453758482250.493.ktUZrQ==
,2016-01-25 22:48:02.254 ThaliTest[493:739409] multipeer session: start timer: 0x184bfb40
,2016-01-25 22:48:02.256 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758482250.493
,2016-01-25 22:48:02.258 ThaliTest[493:739409] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.260 ThaliTest[493:739409] jxcore: stopBroadcasting
,2016-01-25 22:48:02.261 ThaliTest[493:739409] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.261 ThaliTest[493:739409] multipeer session: stop timer
,2016-01-25 22:48:02.263 ThaliTest[493:739409] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-25 22:48:02.407 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.412 ThaliTest[493:739409] server: starting 1453758482407.493.y7uDrw==
,2016-01-25 22:48:02.415 ThaliTest[493:739409] multipeer session: start timer: 0x1844cfa0
2016-01-25 22:48:02.419 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758482407.493
,2016-01-25 22:48:02.420 ThaliTest[493:739409] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

,2016-01-25 22:48:02.426 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.428 ThaliTest[493:739409] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

,2016-01-25 22:48:02.434 ThaliTest[493:739409] jxcore: stopBroadcasting
,2016-01-25 22:48:02.435 ThaliTest[493:739409] THEMultipeerSession stopping peer
,2016-01-25 22:48:02.437 ThaliTest[493:739409] multipeer session: stop timer
,2016-01-25 22:48:02.442 ThaliTest[493:739409] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-25 22:48:02.845 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:02.849 ThaliTest[493:739409] server: starting 1453758482845.493.WomGbQ==
2016-01-25 22:48:02.850 ThaliTest[493:739409] multipeer session: start timer: 0x1965f050
,2016-01-25 22:48:02.850 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758482845.493
2016-01-25 22:48:02.854 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

2016-01-,25 22:48:02.856 ThaliTest[493:739409] jxcore: connect foobar
2016-01-25 22:48:02.857 ThaliTest[493:739409] client: unknown peer foobar
2016-01-25 22:48:02.857 ThaliTest[493:739409] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer

2016-01-25 22:48:02.862 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 22:48:02.862 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:02.862 ThaliTest[493:739409] multipeer sessi,on: stop timer
2016-01-25 22:48:02.863 ThaliTest[493:739409] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-25 22:48:03.034 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:03.038 ThaliTest[493:739409] server: starting 1453758483034.493.R5BUWg==
2016-01-25 22:48:03.039 ThaliTest[493:739409] multipeer session: start timer: 0x1847fc40
2016-01-25 22:48:03.039 ThaliTest[493:739409] THEMultipeerSession initializ,ed peer 1453758483034.493
2016-01-25 22:48:03.039 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-01-25 22:48:03.041 ThaliTest[493:739409] jxcore: disconnect
2016-01-25 22:48:,03.042 ThaliTest[493:739409] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 

,2016-01-25 22:48:03.046 ThaliTest[493:739409] jxcore: stopBroadcasting
,2016-01-25 22:48:03.047 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:03.047 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:03.048 ThaliTest[493:739409] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-25 22:48:03.518 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:03.521 ThaliTest[493:739409] server: starting 1453758483517.493.6i8lLA==
2016-01-25 22:48:03.522 ThaliTest[493:739409] multipeer session: start timer: 0x196e1350
2016-01-25 22:48:03.523 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758483517.493
2016-01-25 22:48:03.523 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-01-25 22:48:04.831 ThaliTest[493:739146] client: found peer: 1453758483479.2573.JQH/bg==
,2016-01-25 22:48:04.835 ThaliTest[493:739409] jxcore: connect 1453758483479.2573.JQH/bg==
2016-01-25 22:48:04.835 ThaliTest[493:739409] client session: connect
2016-01-25 22:48:04.836 ThaliTest[493:739409] client session: stateChange:0->1 1453758483479.2573.JQH/bg==
,2016-01-25 22:48:05.193 ThaliTest[493:739146] multipeer session: reset timer
2016-01-25 22:48:05.194 ThaliTest[493:739146] multipeer session: stop timer
2016-01-25 22:48:05.194 ThaliTest[493:739146] multipeer session: start timer: 0x196e1350
,2016-01-25 22:48:05.196 ThaliTest[493:739146] server session: connect
2016-01-25 22:48:05.196 ThaliTest[493:739146] server session: stateChange:0->1 1453758483479.2573
,2016-01-25 22:48:05.205 ThaliTest[493:739146] server: accepting invitation 1453758483479.2573
,2016-01-25 22:48:07.631 ThaliTest[493:740029] client session: connected
2016-01-25 22:48:07.631 ThaliTest[493:740029] client session: stateChange:1->2 1453758483479.2573.JQH/bg==
,2016-01-25 22:48:07.668 ThaliTest[493:740014] client session: fireConnectCallback: 1453758483479.2573.JQH/bg==
2016-01-25 22:48:07.668 ThaliTest[493:740014] jxcore: connect: success
,ok 75 Should be able to connect without error

,ok 76 Port should be within range

,2016-01-25 22:48:07.673 ThaliTest[493:739409] jxcore: disconnect
2016-01-25 22:48:07.674 ThaliTest[493:739409] client session: disconnectFromPeer: 1453758483479.2573.JQH/bg==
2016-01-25 22:48:07.674 ThaliTest[493:739409] client session: disconnect
2016-,01-25 22:48:07.675 ThaliTest[493:739409] client session: stateChange:2->0 1453758483479.2573.JQH/bg==
,2016-01-25 22:48:07.687 ThaliTest[493:739409] jxcore: disconnect: success
ok 77 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-25 22:48:07.893 ThaliTest[493:740014] server session: connected
2016-01-25 22:48:07.894 ThaliTest[493:740014] server session: stateChange:1->2 1453758483479.2573
2016-01-25 22:48:07.897 ThaliTest[493:739146] server relay: socket disconnected
201,6-01-25 22:48:07.897 ThaliTest[493:739146] server relay: 0x1848add0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-25 22:48:07.936 ThaliTest[493:740018] server session: not connected 1453758483479.2573
,calling stopBroadcasting

,2016-01-25 22:48:08.540 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 22:48:08.541 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:08.541 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:08.541 Th,aliTest[493:739409] server session: disconnect
2016-01-25 22:48:08.542 ThaliTest[493:739409] server session: stateChange:2->0 1453758483479.2573
2016-01-25 22:48:08.543 ThaliTest[493:739409] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-25 22:48:10.707 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:10.711 ThaliTest[493:739409] server: starting 1453758490707.493.6LlK6w==
2016-01-25 22:48:10.712 ThaliTest[493:739409] multipeer session: start timer: 0x1849df70
2016-01-25 22:48:10.712 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758490707.493
2016-01-25 22:48:10.712 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-25 22:48:11.615 ThaliTest[493:739146] client: found peer: 1453758490639.2573.VXkvvQ==
2016-01-25 22:48:11.617 ThaliTest[493:739409] jxcore: connect 1453758490639.2573.VXkvvQ==
2016-01-25 22:48:11.617 ThaliTest[493:739409] client session: connect,
2016-01-25 22:48:11.617 ThaliTest[493:739409] client session: stateChange:0->1 1453758490639.2573.VXkvvQ==
,2016-01-25 22:48:12.014 ThaliTest[493:739146] multipeer session: reset timer
2016-01-25 22:48:12.015 ThaliTest[493:739146] multipeer session: stop timer
2016-01-25 22:48:12.015 ThaliTest[493:739146] multipeer session: start timer: 0x1849df70
2016-01-25 ,22:48:12.016 ThaliTest[493:739146] server session: connect
2016-01-25 22:48:12.016 ThaliTest[493:739146] server session: stateChange:0->1 1453758490639.2573
,2016-01-25 22:48:12.026 ThaliTest[493:739146] server: accepting invitation 1453758490639.2573
,2016-01-25 22:48:14.579 ThaliTest[493:740014] client session: connected
,2016-01-25 22:48:14.579 ThaliTest[493:740014] client session: stateChange:1->2 1453758490639.2573.VXkvvQ==
,2016-01-25 22:48:14.645 ThaliTest[493:740029] server session: connected
2016-01-25 22:48:14.645 ThaliTest[493:740029] server session: stateChange:1->2 1453758490639.2573
,2016-01-25 22:48:14.651 ThaliTest[493:740018] client session: fireConnectCallback: 1453758490639.2573.VXkvvQ==
2016-01-25 22:48:14.651 ThaliTest[493:740018] jxcore: connect: success
ok 79 Should be able to connect without error

,ok 80 Port should be within range

,2016-01-25 22:48:14.657 ThaliTest[493:739409] jxcore: connect 1453758490639.2573.VXkvvQ==
,2016-01-25 22:48:14.658 ThaliTest[493:739409] client: already connect(ing/ed) to 1453758490639.2573.VXkvvQ==
2016-01-25 22:48:14.663 ThaliTest[493:739409] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect

,2016-01-25 22:48:14.666 ThaliTest[493:739409] jxcore: disconnect
,2016-01-25 22:48:14.668 ThaliTest[493:739146] server relay: socket disconnected
,2016-01-25 22:48:14.669 ThaliTest[493:739409] client session: disconnectFromPeer: 1453758490639.2573.VXkvvQ==
,2016-01-25 22:48:14.670 ThaliTest[493:739146] server relay: 0x184d49a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-25 22:48:14.671 ThaliTest[493:739409] client session: disconnect
,2016-01-25 22:48:14.673 ThaliTest[493:739409] client session: stateChange:2->0 1453758490639.2573.VXkvvQ==
,2016-01-25 22:48:14.684 ThaliTest[493:739409] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-25 22:48:14.712 ThaliTest[493:740017] server session: not connected 1453758490639.2573
,calling stopBroadcasting

,2016-01-25 22:48:15.095 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 22:48:15.096 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:15.096 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:15.096 Th,aliTest[493:739409] server session: disconnect
2016-01-25 22:48:15.097 ThaliTest[493:739409] server session: stateChange:2->0 1453758490639.2573
2016-01-25 22:48:15.098 ThaliTest[493:739409] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-25 22:48:17.007 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:17.011 ThaliTest[493:739409] server: starting 1453758497006.493.XIyKWg==
2016-01-25 22:48:17.011 ThaliTest[493:739409] multipeer session: start timer: 0x196e1450
2016-01-25 22:48:17.012 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758497006.493
2016-01-25 22:48:17.012 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-25 22:48:17.945 ThaliTest[493:739146] client: found peer: 1453758495607.2573.yyw6pw==
2016-01-25 22:48:17.947 ThaliTest[493:739409] jxcore: connect 1453758495607.2573.yyw6pw==
2016-01-25 22:48:17.947 ThaliTest[493:739409] client session: connect
2016-01-25 22:48:17.948 ThaliTest[493:739409] client session: stateChange:0->1 1453758495607.2573.yyw6pw==
,2016-01-25 22:48:18.690 ThaliTest[493:739146] multipeer session: reset timer
2016-01-25 22:48:18.690 ThaliTest[493:739146] multipeer session: stop timer
2016-01-25 22:48:18.690 ThaliTest[493:739146] multipeer session: start timer: 0x196e1450
2016-01-25 ,22:48:18.691 ThaliTest[493:739146] server session: connect
2016-01-25 22:48:18.691 ThaliTest[493:739146] server session: stateChange:0->1 1453758495607.2573
,2016-01-25 22:48:18.709 ThaliTest[493:739146] server: accepting invitation 1453758495607.2573
,2016-01-25 22:48:21.124 ThaliTest[493:740023] client session: connected
2016-01-25 22:48:21.125 ThaliTest[493:740023] client session: stateChange:1->2 1453758495607.2573.yyw6pw==
,2016-01-25 22:48:21.162 ThaliTest[493:740089] client session: fireConnectCallback: 1453758495607.2573.yyw6pw==
2016-01-25 22:48:21.162 ThaliTest[493:740089] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

,2016-01-25 22:48:21.166 ThaliTest[493:739409] jxcore: disconnect
2016-01-25 22:48:21.167 ThaliTest[493:739409] client session: disconnectFromPeer: 1453758495607.2573.yyw6pw==
2016-01-25 22:48:21.167 ThaliTest[493:739409] client session: disconnect
2016-01-25 22:48:21.167 ThaliTest[493:739409] client session: stateChange:2->0 1453758495607.2573.yyw6pw==
,2016-01-25 22:48:21.181 ThaliTest[493:739409] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

2016-01-25 22:48:21.183 ThaliTest[493:739409] jxcore: disconnect
2016-01-25 22:48:21.183 ThaliTest[493:739409] jxcore: disconnect: fail
,ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-25 22:48:21.389 ThaliTest[493:740018] server session: connected
2016-01-25 22:48:21.389 ThaliTest[493:740018] server session: stateChange:1->2 1453758495607.2573
,2016-01-25 22:48:21.405 ThaliTest[493:739146] server relay: socket disconnected
2016-01-25 22:48:21.405 ThaliTest[493:739146] server relay: 0x196c6030 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-25 22:48:21.434 ThaliTest[493:740017] server session: not connected 1453758495607.2573
,calling stopBroadcasting

,2016-01-25 22:48:21.842 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 22:48:21.843 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:21.843 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:21.843 Th,aliTest[493:739409] server session: disconnect
2016-01-25 22:48:21.844 ThaliTest[493:739409] server session: stateChange:2->0 1453758495607.2573
2016-01-25 22:48:21.845 ThaliTest[493:739409] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 50814

,2016-01-25 22:48:22.986 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:22.988 ThaliTest[493:739409] server: starting 1453758502986.493.FryYxg==
2016-01-25 22:48:22.988 ThaliTest[493:739409] multipeer session: start timer: 0x184e4780
2016-01-25 22:48:22.989 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758502986.493
2016-01-25 22:48:22.989 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error

,2016-01-25 22:48:24.650 ThaliTest[493:739146] client: found peer: 1453758503142.2573.KND68g==
2016-01-25 22:48:24.652 ThaliTest[493:739409] jxcore: connect 1453758503142.2573.KND68g==
2016-01-25 22:48:24.652 ThaliTest[493:739409] client session: connect,
2016-01-25 22:48:24.652 ThaliTest[493:739409] client session: stateChange:0->1 1453758503142.2573.KND68g==
,2016-01-25 22:48:24.848 ThaliTest[493:739146] multipeer session: reset timer
2016-01-25 22:48:24.848 ThaliTest[493:739146] multipeer session: stop timer
2016-01-25 22:48:24.848 ThaliTest[493:739146] multipeer session: start timer: 0x184e4780
2016-01-25 ,22:48:24.849 ThaliTest[493:739146] server session: connect
2016-01-25 22:48:24.849 ThaliTest[493:739146] server session: stateChange:0->1 1453758503142.2573
2016-01-25 22:48:24.857 ThaliTest[493:739146] server: accepting invitation 1453758503142.2573
,2016-01-25 22:48:27.349 ThaliTest[493:740017] client session: connected
,2016-01-25 22:48:27.350 ThaliTest[493:740017] client session: stateChange:1->2 1453758503142.2573.KND68g==
,2016-01-25 22:48:27.353 ThaliTest[493:740017] client session: fireConnectCallback: 1453758503142.2573.KND68g==
,2016-01-25 22:48:27.353 ThaliTest[493:740017] jxcore: connect: success
,ok 89 Should be able to connect without error

,ok 90 Port should be within range

,2016-01-25 22:48:27.361 ThaliTest[493:739146] client: relay established
2016-01-25 22:48:27.361 ThaliTest[493:739146] client: new accepted socket: 0x184db160
,data in 4380
,
,data in 11619
,
,data in 25996

,data in 33945

,data in 39420

,data in 50370

,data in 52560

,data in 65700

,data in 70080

,data in 74460

,data in 83220

,data in 91980

,data in 96360

,data in 108405

,data in 109500

,data in 111690
,
,data in 122640

,data in 131072

,ok 91 the test messages should be equal

,2016-01-25 22:48:27.840 ThaliTest[493:739409] jxcore: disconnect
,2016-01-25 22:48:27.840 ThaliTest[493:739409] client session: disconnectFromPeer: 1453758503142.2573.KND68g==
,2016-01-25 22:48:27.841 ThaliTest[493:739409] client session: disconnect
,2016-01-25 22:48:27.842 ThaliTest[493:739409] client session: stateChange:2->0 1453758503142.2573.KND68g==
,2016-01-25 22:48:27.860 ThaliTest[493:739409] jxcore: disconnect: success
,ok 92 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.
,
,# setup
,
,2016-01-25 22:48:27.887 ThaliTest[493:740023] server session: connected
,2016-01-25 22:48:27.888 ThaliTest[493:740023] server session: stateChange:1->2 1453758503142.2573
,2016-01-25 22:48:27.903 ThaliTest[493:739146] server relay: connected (to port: 50814)
,2016-01-25 22:48:28.572 ThaliTest[493:740017] server session: not connected 1453758503142.2573
,calling stopBroadcasting

,2016-01-25 22:48:28.660 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 22:48:28.661 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:28.661 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:28.662 Th,aliTest[493:739409] server session: disconnect
2016-01-25 22:48:28.662 ThaliTest[493:739409] server session: stateChange:2->0 1453758503142.2573
,2016-01-25 22:48:28.672 ThaliTest[493:739409] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 50820

,2016-01-25 22:48:28.774 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:28.778 ThaliTest[493:739409] server: starting 1453758508774.493.PEbBJQ==
,2016-01-25 22:48:28.781 ThaliTest[493:739409] multipeer session: start timer: 0x184e1a00
,2016-01-25 22:48:28.785 ThaliTest[493:739409] THEMultipeerSession initialized peer 1453758508774.493
,2016-01-25 22:48:28.790 ThaliTest[493:739409] jxcore: startBroadcasting: success
,ok 93 Should be able to call startBroadcasting without error

,2016-01-25 22:48:29.682 ThaliTest[493:739146] client: found peer: 1453758502986.493.FryYxg==
2016-01-25 22:48:29.682 ThaliTest[493:739146] client: found peer: 1453758503142.2573.KND68g==
[{"peerIdentifier":"1453758502986.493.FryYxg==","peerName":"(null)",,"peerAvailable":true}]

2016-01-25 22:48:29.685 ThaliTest[493:739409] jxcore: connect 1453758502986.493.FryYxg==
2016-01-25 22:48:29.685 ThaliTest[493:739409] client session: connect
2016-01-25 22:48:29.685 ThaliTest[493:739409] client session: stateChange:0->1 1453758502986.493.FryYxg==
,[{"peerIdentifier":"1453758503142.2573.KND68g==","peerName":"(null)","peerAvailable":true}]

2016-01-25 22:48:29.699 ThaliTest[493:739409] jxcore: connect 1453758503142.2573.KND68g==
2016-01-25 22:48:29.700 ThaliTest[493:739409] client session: connect
2016-01-25 22:48:29.702 ThaliTest[493:739409] client session: stateChange:0->1 1453758503142.2573.KND68g==
,2016-01-25 22:48:29.896 ThaliTest[493:739146] client: lost peer: 1453758502986.493.FryYxg==
2016-01-25 22:48:29.897 ThaliTest[493:739146] client session: onPeerLost: 1453758502986.493.FryYxg==
2016-01-25 22:48:29.897 ThaliTest[493:739146] client session:, onLinkFailure: 1453758502986.493.FryYxg==
2016-01-25 22:48:29.897 ThaliTest[493:739146] client session: disconnect
2016-01-25 22:48:29.897 ThaliTest[493:739146] client session: stateChange:1->0 1453758502986.493.FryYxg==
2016-01-25 22:48:29.898 ThaliTe,st[493:739146] client session: fireConnectCallback: 1453758502986.493.FryYxg==
2016-01-25 22:48:29.898 ThaliTest[493:739146] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1453758502986.493.FryYxg==","peerName":"(null)","peerAvailable":false}]

,2016-01-25 22:48:29.907 ThaliTest[493:739146] client: lost peer: 1453758503142.2573.KND68g==
2016-01-25 22:48:29.907 ThaliTest[493:739146] client session: onPeerLost: 1453758503142.2573.KND68g==
2016-01-25 22:48:29.908 ThaliTest[493:739146] client session: onLinkFailure: 1453758503142.2573.KND68g==
2016-01-25 22:48:29.908 ThaliTest[493:739146] client session: disconnect
,2016-01-25 22:48:29.908 ThaliTest[493:739146] client session: stateChange:1->0 1453758503142.2573.KND68g==
2016-01-25 22:48:29.909 ThaliTest[493:739146] client session: fireConnectCallback: 1453758503142.2573.KND68g==
2016-01-25 22:48:29.909 ThaliTest[493:739146] jxcore: connect: fail: Peer disconnected
,2016-01-25 22:48:29.911 ThaliTest[493:739146] client: found peer: 1453758508742.2573.8F72Rw==
,[{"peerIdentifier":"1453758503142.2573.KND68g==","peerName":"(null)","peerAvailable":false}]

[{"peerIdentifier":"1453758508742.2573.8F72Rw==","peerName":"(null)","peerAvailable":true}]

2016-01-25 22:48:29.915 ThaliTest[493:739409] jxcore: connect 145,3758508742.2573.8F72Rw==
2016-01-25 22:48:29.915 ThaliTest[493:739409] client session: connect
2016-01-25 22:48:29.916 ThaliTest[493:739409] client session: stateChange:0->1 1453758508742.2573.8F72Rw==
,2016-01-25 22:48:30.090 ThaliTest[493:739146] multipeer session: reset timer
2016-01-25 22:48:30.090 ThaliTest[493:739146] multipeer session: stop timer
2016-01-25 22:48:30.091 ThaliTest[493:739146] multipeer session: start timer: 0x184e1a00
,2016-01-25 22:48:30.091 ThaliTest[493:739146] server session: connect
2016-01-25 22:48:30.093 ThaliTest[493:739146] server session: stateChange:0->1 1453758508742.2573
,2016-01-25 22:48:30.103 ThaliTest[493:739146] server: accepting invitation 1453758508742.2573
,2016-01-25 22:48:30.903 ThaliTest[493:739409] jxcore: connect 1453758502986.493.FryYxg==
2016-01-25 22:48:30.903 ThaliTest[493:739409] client: connect: unreachable 1453758502986.493.FryYxg==
2016-01-25 22:48:30.903 ThaliTest[493:739409] jxcore: connect: fail: Peer unreachable
,2016-01-25 22:48:30.918 ThaliTest[493:739409] jxcore: connect 1453758503142.2573.KND68g==
2016-01-25 22:48:30.919 ThaliTest[493:739409] client: connect: unreachable 1453758503142.2573.KND68g==
2016-01-25 22:48:30.919 ThaliTest[493:739409] jxcore: connect: fail: Peer unreachable
,2016-01-25 22:48:32.483 ThaliTest[493:740023] client session: connected
2016-01-25 22:48:32.484 ThaliTest[493:740023] client session: stateChange:1->2 1453758508742.2573.8F72Rw==
,2016-01-25 22:48:32.489 ThaliTest[493:740023] client session: fireConnectCallback: 1453758508742.2573.8F72Rw==
2016-01-25 22:48:32.489 ThaliTest[493:740023] jxcore: connect: success
ok 94 Should be able to connect without error

ok 95 Port should be wi,thin range

ok 96 First connect should succeed

,2016-01-25 22:48:32.525 ThaliTest[493:739146] client: relay established
2016-01-25 22:48:32.526 ThaliTest[493:739146] client: new accepted socket: 0x196abd80
,ok 97 the test messages should be equal

ok 98 First send should succeed

,2016-01-25 22:48:32.579 ThaliTest[493:739146] client: socket closed
,2016-01-25 22:48:32.581 ThaliTest[493:739146] client relay: socket disconnected
2016-01-25 22:48:32.581 ThaliTest[493:739146] client relay: 0x196abd80 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-25 22:48:32.582 ThaliTest[493:739146] client session: socket closed: 1453758508742.2573.8F72Rw==
2016-01-25 22:48:32.582 ThaliTest[493:739146] client session: onLinkFailure: 14537585087,42.2573.8F72Rw==
2016-01-25 22:48:32.582 ThaliTest[493:739146] client session: disconnect
2016-01-25 22:48:32.582 ThaliTest[493:739146] client session: stateChange:2->0 1453758508742.2573.8F72Rw==
,2016-01-25 22:48:32.597 ThaliTest[493:739146] client session: fireConnectionErrorEvent: 1453758508742.2573.8F72Rw==
,2016-01-25 22:48:32.601 ThaliTest[493:739409] jxcore: connect 1453758508742.2573.8F72Rw==
2016-01-25 22:48:32.602 ThaliTest[493:739409] client session: connect
2016-01-25 22:48:32.603 ThaliTest[493:739409] client session: stateChange:0->1 1453758508742.2573.8F72Rw==
,2016-01-25 22:48:32.732 ThaliTest[493:740023] server session: connected
,2016-01-25 22:48:32.733 ThaliTest[493:740023] server session: stateChange:1->2 1453758508742.2573
,2016-01-25 22:48:32.782 ThaliTest[493:739146] server relay: connected (to port: 50820)
,2016-01-25 22:48:32.913 ThaliTest[493:740014] server session: not connected 1453758508742.2573
,2016-01-25 22:48:33.173 ThaliTest[493:739146] multipeer session: reset timer
2016-01-25 22:48:33.174 ThaliTest[493:739146] multipeer session: stop timer
2016-01-25 22:48:33.174 ThaliTest[493:739146] multipeer session: start timer: 0x184e1a00
2016-01-25 ,22:48:33.175 ThaliTest[493:739146] server: disconnecting to refresh session (1453758508742.2573)
2016-01-25 22:48:33.175 ThaliTest[493:739146] server session: disconnect
2016-01-25 22:48:33.175 ThaliTest[493:739146] server session: stateChange:2->0 1453758508742.2573
2016-01-25 22:48:33.181 ThaliTest[493:739146] server session: connect
2016-01-25 22:48:33.181 ThaliTest[493:739146] server session: stateChange:0->1 1453758508742.2573
2016-01-25 22:48:33.202 ThaliTest[493:739146] server: accepting invitation 1453758508742.2573
,2016-01-25 22:48:35.435 ThaliTest[493:740089] client session: connected
,2016-01-25 22:48:35.435 ThaliTest[493:740089] client session: stateChange:1->2 1453758508742.2573.8F72Rw==
,2016-01-25 22:48:35.442 ThaliTest[493:740089] client session: fireConnectCallback: 1453758508742.2573.8F72Rw==
,2016-01-25 22:48:35.445 ThaliTest[493:740089] jxcore: connect: success
,ok 99 Should be able to connect without error

,ok 100 Port should be within range

,ok 101 Second connect should succeed

,2016-01-25 22:48:35.482 ThaliTest[493:739146] client: relay established
,2016-01-25 22:48:35.484 ThaliTest[493:739146] client: new accepted socket: 0x1848a7d0
,ok 102 the test messages should be equal

,ok 103 Second send should succeed

,# setup

,2016-01-25 22:48:35.556 ThaliTest[493:739146] client: socket closed
,2016-01-25 22:48:35.556 ThaliTest[493:739146] client relay: socket disconnected
2016-01-25 22:48:35.557 ThaliTest[493:739146] client relay: 0x1848a7d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-25 22:48:35.557 ThaliTest[493:739146] client session: socket closed: 1453758508742.2573.8F72Rw==
2016-01-25 22:48:35.557 ThaliTest[493:739146] client session: onLinkFailure: 1453758508742.2573.8F72Rw==
2016-01-25 22:48:35.558 ThaliTest[493:739146] client session: disconnect
,2016-01-25 22:48:35.558 ThaliTest[493:739146] client session: stateChange:2->0 1453758508742.2573.8F72Rw==
,2016-01-25 22:48:35.572 ThaliTest[493:739146] client session: fireConnectionErrorEvent: 1453758508742.2573.8F72Rw==
,2016-01-25 22:48:35.741 ThaliTest[493:740018] server session: connected
2016-01-25 22:48:35.741 ThaliTest[493:740018] server session: stateChange:1->2 1453758508742.2573
,2016-01-25 22:48:35.789 ThaliTest[493:739146] server relay: connected (to port: 50820)
,2016-01-25 22:48:35.914 ThaliTest[493:740017] server session: not connected 1453758508742.2573
,calling stopBroadcasting

,2016-01-25 22:48:35.991 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 22:48:35.992 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:35.992 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:35.993 ThaliTest[493:739409] server session: disconnect
2016-01-25 22:48:35.993 ThaliTest[493:739409] server session: stateChange:2->0 1453758508742.2573
,2016-01-25 22:48:36.001 ThaliTest[493:739409] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/723C710E-6947-4548-8AE7-217DE51F718E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 104 starting event should occur in right order

,2016-01-25 22:48:36.650 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:36.652 ThaliTest[493:739409] server: starting NqTluJzHtE2jMQ4WW3MIsw.V38/QQ==
2016-01-25 22:48:36.652 ThaliTest[493:739409] multipeer session: start timer: 0x196c0350
2016-01-25 22:48:36.652 ThaliTest[493:739409] THEMultipeerSession initialized peer NqTluJzHtE2jMQ4WW3MIsw
2016-01-25 22:48:36.652 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 105 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

,ok 106 stopping event should occur in right order

About to call stopBroadcasting

2016-01-25 22:48:36.654 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 22:48:36.654 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:36.655 ThaliTest[493:739409] multipeer session: stop timer
,2016-01-25 22:48:36.655 ThaliTest[493:739409] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 107 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/723C710E-6947-4548-8AE7-217DE51F718E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-25 22:48:37.479 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:37.484 ThaliTest[493:739409] server: starting NqTluJzHtE2jMQ4WW3MIsw.mm72TQ==
2016-01-25 22:48:37.484 ThaliTest[493:739409] multipeer session: start timer: 0x19278d10
2016-01-25 22:48:37.485 ThaliTest[493:739409] THEMultipeerSession init,ialized peer NqTluJzHtE2jMQ4WW3MIsw
2016-01-25 22:48:37.485 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error

ok 109 deviceName should not be null

Now in TRM stop

State of this._isStarte,d: true

About to call stopBroadcasting

,2016-01-25 22:48:37.488 ThaliTest[493:739409] jxcore: stopBroadcasting
2016-01-25 22:48:37.490 ThaliTest[493:739409] THEMultipeerSession stopping peer
2016-01-25 22:48:37.490 ThaliTest[493:739409] multipeer session: stop timer
2016-01-25 22:48:37.491 Th,aliTest[493:739409] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/723C710E-6947-4548-8AE7-217DE51F718E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-25 22:48:40.356 ThaliTest[493:739409] jxcore: startBroadcasting
,2016-01-25 22:48:40.357 ThaliTest[493:739409] server: starting NqTluJzHtE2jMQ4WW3MIsw.4mR9sg==
2016-01-25 22:48:40.357 ThaliTest[493:739409] multipeer session: start timer: 0x1821c590
2016-01-25 22:48:40.357 ThaliTest[493:739409] THEMultipeerSession initialized peer NqTluJzHtE2jMQ4WW3MIsw
2016-01-25 22:48:40.357 ThaliTest[493:739409] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error

ok 111 deviceName should not be null

,2016-01-25 22:48:44.575 ThaliTest[493:739146] client: found peer: m0DogFG2ls-s2IDbNWmIyA.a+MVCQ==
,2016-01-25 22:48:45.123 ThaliTest[493:739409] jxcore: connect m0DogFG2ls-s2IDbNWmIyA.a+MVCQ==
2016-01-25 22:48:45.124 ThaliTest[493:739409] client session: connect
2016-01-25 22:48:45.124 ThaliTest[493:739409] client session: stateChange:0->1 m0DogFG2ls-s2IDbNWmIyA.a+MVCQ==
,ok 112 Should be able to put doc without error

,ok 113 1st change of local doc should contain local id

,2016-01-25 22:48:46.669 ThaliTest[493:739146] multipeer session: reset timer
2016-01-25 22:48:46.670 ThaliTest[493:739146] multipeer session: stop timer
2016-01-25 22:48:46.670 ThaliTest[493:739146] multipeer session: start timer: 0x1821c590
2016-01-25 22:48:46.671 ThaliTest[493:739146] server session: connect
2016-01-25 22:48:46.671 ThaliTest[493:739146] server session: stateChange:0->1 m0DogFG2ls-s2IDbNWmIyA
,2016-01-25 22:48:46.681 ThaliTest[493:739146] server: accepting invitation m0DogFG2ls-s2IDbNWmIyA
,2016-01-25 22:48:49.339 ThaliTest[493:740089] client session: connected
,2016-01-25 22:48:49.339 ThaliTest[493:740089] client session: stateChange:1->2 m0DogFG2ls-s2IDbNWmIyA.a+MVCQ==
,2016-01-25 22:48:49.356 ThaliTest[493:740018] client session: fireConnectCallback: m0DogFG2ls-s2IDbNWmIyA.a+MVCQ==
2016-01-25 22:48:49.356 ThaliTest[493:740018] jxcore: connect: success
,2016-01-25 22:48:49.370 ThaliTest[493:739146] client: relay established
2016-01-25 22:48:49.370 ThaliTest[493:739146] client: new accepted socket: 0x192f6090
,client bridge: new client socket

,client bridge: new client socket

2016-01-25 22:48:49.482 ThaliTest[493:740180] server session: connected
2016-01-25 22:48:49.482 ThaliTest[493:740180] server session: stateChange:1->2 m0DogFG2ls-s2IDbNWmIyA
,2016-01-25 22:48:49.500 ThaliTest[493:739146] server relay: connected (to port: 50839)
,server bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

,client bridge: socket closed
,
,ok 114 1st change of remote doc should contain remote id

,client bridge: new client socket

,ok 115 Can update remote doc without error

,null

,{ ok: true,
  id: 'dd189988-00d1-4f67-9f1e-55ec50d1659d',
  rev: '2-fee56e4aaf9f0afe846de6d48d466f15' }

,client bridge: new client socket

,ok 116 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed

,ok 117 Local changes occur in strict order

ok 118 2nd change of local doc should contain remote id

,client bridge: new client socket

,# setup

client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket

,2016-01-25 22:49:03.840 ThaliTest[493:740014] server session: not connected m0DogFG2ls-s2IDbNWmIyA
,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-01-25 22:49:03.852 ThaliTest[493:739409] jxcore: stopBroadcasting
,2016-01-25 22:49:03.854 ThaliTest[493:739409] THEMultipeerSession stopping peer
,2016-01-25 22:49:03.855 ThaliTest[493:739409] multipeer session: stop timer
,2016-01-25 22:49:03.857 ThaliTest[493:739409] client session: disconnect
,2016-01-25 22:49:03.860 ThaliTest[493:739409] client session: stateChange:2->0 m0DogFG2ls-s2IDbNWmIyA.a+MVCQ==
,2016-01-25 22:49:03.948 ThaliTest[493:739409] server session: disconnect
,2016-01-25 22:49:03.950 ThaliTest[493:739409] server session: stateChange:2->0 m0DogFG2ls-s2IDbNWmIyA
,2016-01-25 22:49:04.016 ThaliTest[493:739409] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,client bridge: socket closed

,server bridge: socket closed

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

,ok 122 relevant messages should not be ignored

,ok 123 messages from this device should be ignored

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****
,
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
