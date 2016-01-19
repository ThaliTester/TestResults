#### Test 565307121a686b7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/565307121a686b7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8C744564-5864-4ACB-A308-8682084B8108/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8C744564-5864-4ACB-A308-8682084B8108/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/565307121a686b7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/565307121a686b7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4BF47B2E-6EDB-4492-B186-C2ED3EE234B3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58821"
,(lldb)     command script import "/tmp/8C744564-5864-4ACB-A308-8682084B8108/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-19 23:05:50.332 ThaliTest[202:5016] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B65BAD01-E102-4379-811E-00E458B14B3B/Library/Cookies/Cookies.binarycookies
,2016-01-19 23:05:51.000 ThaliTest[202:5016] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-19 23:05:51.002 ThaliTest[202:5016] Multi-tasking -> Device: YES, App: YES
,2016-01-19 23:05:51.017 ThaliTest[202:5016] Unlimited access to network resources
,2016-01-19 23:05:51.034 ThaliTest[202:5016] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-19 23:06:00.531 ThaliTest[202:5016] Resetting plugins due to page load.
,2016-01-19 23:06:02.927 ThaliTest[202:5016] Finished load of: file:///var/mobile/Containers/Bundle/Application/4BF47B2E-6EDB-4492-B186-C2ED3EE234B3/ThaliTest.app/www/index.html
,2016-01-19 23:06:03.090 ThaliTest[202:5016] JXcore Cordova plugin initializing
2016-01-19 23:06:03.091 ThaliTest[202:5332] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BF47B2E-6EDB-4492-B186-C2ED3EE234B3/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BF47B2E-6EDB-4492-B186-C2ED3EE234B3/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BF47B2E-6EDB-4492-B186-C2ED3EE234B3/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BF47B2E-6EDB-4492-B186-C2ED3EE234B3/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BF47B2E-6EDB-4492-B186-C2ED3EE234B3/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BF47B2E-6EDB-4492-B186-C2ED3EE234B3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BF47B2E-6EDB-4492-B186-C2ED3EE234B3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 7 should be equal

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

,ok 18 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 19 should be equal

# setup

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
,
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

,2016-01-19 23:10:41.953 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:41.976 ThaliTest[202:5332] server: starting 1453241441953.202.YjbTyQ==
,2016-01-19 23:10:41.982 ThaliTest[202:5332] multipeer session: start timer: 0x19212790
,2016-01-19 23:10:41.982 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241441953.202
2016-01-19 23:10:41.985 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error

2016-01-19 2,3:10:41.988 ThaliTest[202:5332] jxcore: stopBroadcasting
2016-01-19 23:10:41.989 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:10:41.989 ThaliTest[202:5332] multipeer session: stop timer
2016-01-19 23:10:41.989 ThaliTest[202:5332] ,jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error

2016-01-19 23:10:41.991 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.006 ThaliTest[202:5332] server: starting 1453241441991.202.9Fv5sA==
2016-01-19 23:10:42.009 ThaliTest[202:5332] multipeer session: start timer: 0x190d52f0
,2016-01-19 23:10:42.010 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241441991.202
2016-01-19 23:10:42.018 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error

2016-01-19 2,3:10:42.020 ThaliTest[202:5332] jxcore: stopBroadcasting
2016-01-19 23:10:42.020 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:10:42.021 ThaliTest[202:5332] multipeer session: stop timer
2016-01-19 23:10:42.021 ThaliTest[202:5332] ,jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error

2016-01-19 23:10:42.023 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.034 ThaliTest[202:5332] server: starting 1453241442023.202.ipLacQ==
2016-01-19 23:10:42.035 ThaliTest[202:5332] multipeer session: start timer: 0x190d85a0
2016-01-19 23:10:42.035 ThaliTest[202:5332] THEMultipeerSession initialized pee,r 1453241442023.202
2016-01-19 23:10:42.036 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.038 ThaliTest[202:5332] jxcore: stopBroadcasting
2016-01-19 23:10:42.0,41 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:10:42.042 ThaliTest[202:5332] multipeer session: stop timer
2016-01-19 23:10:42.042 ThaliTest[202:5332] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcastin,g without error

2016-01-19 23:10:42.044 ThaliTest[202:5332] jxcore: startBroadcasting
2016-01-19 23:10:42.048 ThaliTest[202:5332] server: starting 1453241442044.202.uZlZkg==
2016-01-19 23:10:42.049 ThaliTest[202:5332] multipeer session: start timer: 0,x19218f80
2016-01-19 23:10:42.054 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241442044.202
2016-01-19 23:10:42.054 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error

2,016-01-19 23:10:42.056 ThaliTest[202:5332] jxcore: stopBroadcasting
2016-01-19 23:10:42.056 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:10:42.056 ThaliTest[202:5332] multipeer session: stop timer
2016-01-19 23:10:42.057 ThaliTest[202:5332] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error

2016-01-19 23:10:42.058 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.064 ThaliTest[202:5332] server: starting 1453241442058.202.6QSwTQ==
,2016-01-19 23:10:42.065 ThaliTest[202:5332] multipeer session: start timer: 0x190db5e0
,2016-01-19 23:10:42.072 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241442058.202
,2016-01-19 23:10:42.078 ThaliTest[202:5332] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.098 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:10:42.098 ThaliTest[202:5332] THEMultipeerSession stopping peer
,2016-01-19 23:10:42.099 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:10:42.101 ThaliTest[202:5332] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error

,2016-01-19 23:10:42.106 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.109 ThaliTest[202:5332] server: starting 1453241442105.202.MsIwzw==
,2016-01-19 23:10:42.111 ThaliTest[202:5332] multipeer session: start timer: 0x193a3c20
,2016-01-19 23:10:42.116 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241442105.202
,2016-01-19 23:10:42.118 ThaliTest[202:5332] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.121 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:10:42.121 ThaliTest[202:5332] THEMultipeerSession stopping peer
,2016-01-19 23:10:42.122 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:10:42.124 ThaliTest[202:5332] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error

,2016-01-19 23:10:42.128 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.131 ThaliTest[202:5332] server: starting 1453241442128.202.a5OWqw==
,2016-01-19 23:10:42.133 ThaliTest[202:5332] multipeer session: start timer: 0x190db7e0
,2016-01-19 23:10:42.135 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241442128.202
,2016-01-19 23:10:42.139 ThaliTest[202:5332] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.141 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:10:42.142 ThaliTest[202:5332] THEMultipeerSession stopping peer
,2016-01-19 23:10:42.143 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:10:42.144 ThaliTest[202:5332] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error

,2016-01-19 23:10:42.149 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.151 ThaliTest[202:5332] server: starting 1453241442148.202.FQwkRw==
,2016-01-19 23:10:42.153 ThaliTest[202:5332] multipeer session: start timer: 0x190da3c0
,2016-01-19 23:10:42.158 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241442148.202
,2016-01-19 23:10:42.159 ThaliTest[202:5332] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.162 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:10:42.162 ThaliTest[202:5332] THEMultipeerSession stopping peer
,2016-01-19 23:10:42.163 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:10:42.166 ThaliTest[202:5332] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error

,2016-01-19 23:10:42.170 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.172 ThaliTest[202:5332] server: starting 1453241442169.202.AOC+cw==
,2016-01-19 23:10:42.175 ThaliTest[202:5332] multipeer session: start timer: 0x19219a50
,2016-01-19 23:10:42.178 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241442169.202
,2016-01-19 23:10:42.179 ThaliTest[202:5332] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.182 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:10:42.183 ThaliTest[202:5332] THEMultipeerSession stopping peer
,2016-01-19 23:10:42.184 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:10:42.187 ThaliTest[202:5332] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error

,2016-01-19 23:10:42.190 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.192 ThaliTest[202:5332] server: starting 1453241442189.202.OIPKdA==
,2016-01-19 23:10:42.193 ThaliTest[202:5332] multipeer session: start timer: 0x190dd750
,2016-01-19 23:10:42.197 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241442189.202
,2016-01-19 23:10:42.198 ThaliTest[202:5332] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.200 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:10:42.201 ThaliTest[202:5332] THEMultipeerSession stopping peer
,2016-01-19 23:10:42.201 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:10:42.203 ThaliTest[202:5332] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-19 23:10:42.282 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.285 ThaliTest[202:5332] server: starting 1453241442282.202.IlCR0Q==
,2016-01-19 23:10:42.287 ThaliTest[202:5332] multipeer session: start timer: 0x190e48e0
,2016-01-19 23:10:42.288 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241442282.202
,2016-01-19 23:10:42.290 ThaliTest[202:5332] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.295 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.297 ThaliTest[202:5332] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

,2016-01-19 23:10:42.301 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:10:42.302 ThaliTest[202:5332] THEMultipeerSession stopping peer
,2016-01-19 23:10:42.302 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:10:42.305 ThaliTest[202:5332] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-19 23:10:42.361 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.365 ThaliTest[202:5332] server: starting 1453241442361.202.R4hw/Q==
,2016-01-19 23:10:42.368 ThaliTest[202:5332] multipeer session: start timer: 0x190e0f20
,2016-01-19 23:10:42.373 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241442361.202
,2016-01-19 23:10:42.376 ThaliTest[202:5332] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-19 23:10:42.381 ThaliTest[202:5332] jxcore: connect foobar
,2016-01-19 23:10:42.383 ThaliTest[202:5332] client: unknown peer foobar
,2016-01-19 23:10:42.384 ThaliTest[202:5332] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer

,2016-01-19 23:10:42.392 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:10:42.393 ThaliTest[202:5332] THEMultipeerSession stopping peer
,2016-01-19 23:10:42.395 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:10:42.401 ThaliTest[202:5332] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-19 23:10:42.777 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.781 ThaliTest[202:5332] server: starting 1453241442777.202.iuCYNg==
2016-01-19 23:10:42.782 ThaliTest[202:5332] multipeer session: start timer: 0x16d3caf0
2016-01-19 23:10:42.782 ThaliTest[202:5332] THEMultipeerSession initialized pee,r 1453241442777.202
2016-01-19 23:10:42.782 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-01-19 23:10:42.784 ThaliTest[202:5332] jxcore: disconnect
2016-01-19 23:10:42.785 Tha,liTest[202:5332] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 

2016-01-19 23:10:42.789 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:10:42.790 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:10:42.791 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:10:42.794 ThaliTest[202:5332] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-19 23:10:42.857 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:10:42.861 ThaliTest[202:5332] server: starting 1453241442856.202.eAYUYA==
2016-01-19 23:10:42.862 ThaliTest[202:5332] multipeer session: start timer: 0x192424b0
2016-01-19 23:10:42.863 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241442856.202
2016-01-19 23:10:42.863 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-01-19 23:10:44.026 ThaliTest[202:5016] client: found peer: 1453241443263.2390.AJfD5A==
2016-01-19 23:10:44.028 ThaliTest[202:5332] jxcore: connect 1453241443263.2390.AJfD5A==
2016-01-19 23:10:44.029 ThaliTest[202:5332] client session: connect
2016-,01-19 23:10:44.029 ThaliTest[202:5332] client session: stateChange:0->1 1453241443263.2390.AJfD5A==
,2016-01-19 23:10:44.234 ThaliTest[202:5016] multipeer session: reset timer
2016-01-19 23:10:44.234 ThaliTest[202:5016] multipeer session: stop timer
2016-01-19 23:10:44.235 ThaliTest[202:5016] multipeer session: start timer: 0x192424b0
,2016-01-19 23:10:44.237 ThaliTest[202:5016] server session: connect
2016-01-19 23:10:44.238 ThaliTest[202:5016] server session: stateChange:0->1 1453241443263.2390
,2016-01-19 23:10:44.247 ThaliTest[202:5016] server: accepting invitation 1453241443263.2390
,2016-01-19 23:10:48.917 ThaliTest[202:6026] client session: connected
2016-01-19 23:10:48.918 ThaliTest[202:6026] client session: stateChange:1->2 1453241443263.2390.AJfD5A==
,2016-01-19 23:10:48.931 ThaliTest[202:6026] server session: connected
2016-01-19 23:10:48.931 ThaliTest[202:6026] server session: stateChange:1->2 1453241443263.2390
,2016-01-19 23:10:48.957 ThaliTest[202:6029] server session: not connected 1453241443263.2390
,2016-01-19 23:10:49.276 ThaliTest[202:6022] client session: fireConnectCallback: 1453241443263.2390.AJfD5A==
2016-01-19 23:10:49.276 ThaliTest[202:6022] jxcore: connect: success
,ok 75 Should be able to connect without error

,ok 76 Port should be within range

,2016-01-19 23:10:49.281 ThaliTest[202:5332] jxcore: disconnect
2016-01-19 23:10:49.282 ThaliTest[202:5332] client session: disconnectFromPeer: 1453241443263.2390.AJfD5A==
2016-01-19 23:10:49.282 ThaliTest[202:5332] client session: disconnect
2016-01-19 ,23:10:49.282 ThaliTest[202:5332] client session: stateChange:2->0 1453241443263.2390.AJfD5A==
,2016-01-19 23:10:49.294 ThaliTest[202:5332] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-19 23:10:54.847 ThaliTest[202:5332] jxcore: stopBroadcasting
2016-01-19 23:10:54.847 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:10:54.847 ThaliTest[202:5332] multipeer session: stop timer
2016-01-19 23:10:54.848 ThaliTest[202:5332] server session: disconnect
2016-01-19 23:10:54.848 ThaliTest[202:5332] server session: stateChange:2->0 1453241443263.2390
,2016-01-19 23:10:54.918 ThaliTest[202:5332] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-19 23:11:03.218 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:11:03.221 ThaliTest[202:5332] server: starting 1453241463217.202.IN5W+g==
2016-01-19 23:11:03.222 ThaliTest[202:5332] multipeer session: start timer: 0x181dd470
2016-01-19 23:11:03.223 ThaliTest[202:5332] THEMultipeerSession initialized pee,r 1453241463217.202
2016-01-19 23:11:03.223 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-19 23:11:04.582 ThaliTest[202:5016] multipeer session: reset timer
2016-01-19 23:11:04.582 ThaliTest[202:5016] multipeer session: stop timer
2016-01-19 23:11:04.583 ThaliTest[202:5016] multipeer session: start timer: 0x181dd470
2016-01-19 23:11:,04.583 ThaliTest[202:5016] server session: connect
2016-01-19 23:11:04.583 ThaliTest[202:5016] server session: stateChange:0->1 1453241464075.2390
,2016-01-19 23:11:04.593 ThaliTest[202:5016] server: accepting invitation 1453241464075.2390
,2016-01-19 23:11:04.613 ThaliTest[202:5016] client: found peer: 1453241464075.2390.3YBbOA==
2016-01-19 23:11:04.614 ThaliTest[202:5332] jxcore: connect 1453241464075.2390.3YBbOA==
2016-01-19 23:11:04.615 ThaliTest[202:5332] client session: connect
2016-01-19 23:11:04.615 ThaliTest[202:5332] client session: stateChange:0->1 1453241464075.2390.3YBbOA==
,2016-01-19 23:11:09.331 ThaliTest[202:6022] client session: connected
2016-01-19 23:11:09.332 ThaliTest[202:6022] client session: stateChange:1->2 1453241464075.2390.3YBbOA==
,2016-01-19 23:11:09.392 ThaliTest[202:6016] client session: fireConnectCallback: 1453241464075.2390.3YBbOA==
2016-01-19 23:11:09.392 ThaliTest[202:6016] jxcore: connect: success
ok 79 Should be able to connect without error

,ok 80 Port should be within range

,2016-01-19 23:11:09.397 ThaliTest[202:5332] jxcore: connect 1453241464075.2390.3YBbOA==
2016-01-19 23:11:09.397 ThaliTest[202:5332] client: already connect(ing/ed) to 1453241464075.2390.3YBbOA==
2016-01-19 23:11:09.398 ThaliTest[202:5332] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect

,2016-01-19 23:11:09.402 ThaliTest[202:5332] jxcore: disconnect
2016-01-19 23:11:09.402 ThaliTest[202:5332] client session: disconnectFromPeer: 1453241464075.2390.3YBbOA==
2016-01-19 23:11:09.403 ThaliTest[202:5332] client session: disconnect
2016-01-19 23:11:09.403 ThaliTest[202:5332] client session: stateChange:2->0 1453241464075.2390.3YBbOA==
,2016-01-19 23:11:09.416 ThaliTest[202:5332] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.
,
,# setup

,2016-01-19 23:11:09.846 ThaliTest[202:6016] server session: connected
2016-01-19 23:11:09.846 ThaliTest[202:6016] server session: stateChange:1->2 1453241464075.2390
,2016-01-19 23:11:09.861 ThaliTest[202:5016] server relay: socket disconnected
2016-01-19 23:11:09.861 ThaliTest[202:5016] server relay: 0x19074270 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 23:11:09.924 ThaliTest[202:6022] server session: not connected 1453241464075.2390
,calling stopBroadcasting

,2016-01-19 23:11:10.174 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:11:10.174 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:11:10.175 ThaliTest[202:5332] multipeer session: stop timer
2016-01-19 23:11:10.176 ThaliTest[202:5332] server session: disconnect
2016-01-19 23:11:10.176 ThaliTest[202:5332] server session: stateChange:2->0 1453241464075.2390
2016-01-19 23:11:10.180 ThaliTest[202:5332] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-19 23:11:29.281 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:11:29.285 ThaliTest[202:5332] server: starting 1453241489281.202.T5NPaA==
2016-01-19 23:11:29.286 ThaliTest[202:5332] multipeer session: start timer: 0x19242a20
2016-01-19 23:11:29.286 ThaliTest[202:5332] THEMultipeerSession initialized pee,r 1453241489281.202
2016-01-19 23:11:29.287 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-19 23:11:30.076 ThaliTest[202:5016] client: found peer: 1453241471625.2390.rYOlgg==
2016-01-19 23:11:30.078 ThaliTest[202:5332] jxcore: connect 1453241471625.2390.rYOlgg==
2016-01-19 23:11:30.078 ThaliTest[202:5332] client session: connect
2016-01-19 23:11:30.078 ThaliTest[202:5332] client session: stateChange:0->1 1453241471625.2390.rYOlgg==
,2016-01-19 23:11:30.355 ThaliTest[202:5016] multipeer session: reset timer
2016-01-19 23:11:30.355 ThaliTest[202:5016] multipeer session: stop timer
2016-01-19 23:11:30.356 ThaliTest[202:5016] multipeer session: start timer: 0x19242a20
2016-01-19 23:11:,30.356 ThaliTest[202:5016] server session: connect
2016-01-19 23:11:30.357 ThaliTest[202:5016] server session: stateChange:0->1 1453241471625.2390
,2016-01-19 23:11:30.367 ThaliTest[202:5016] server: accepting invitation 1453241471625.2390
,2016-01-19 23:11:34.487 ThaliTest[202:6016] server session: connected
2016-01-19 23:11:34.487 ThaliTest[202:6016] server session: stateChange:1->2 1453241471625.2390
,2016-01-19 23:11:34.545 ThaliTest[202:5016] server relay: socket disconnected
2016-01-19 23:11:34.546 ThaliTest[202:5016] server relay: 0x19075630 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 23:11:34.556 ThaliTest[202:6171] server session: not connected 1453241471625.2390
,2016-01-19 23:11:34.676 ThaliTest[202:6171] client session: connected
2016-01-19 23:11:34.676 ThaliTest[202:6171] client session: stateChange:1->2 1453241471625.2390.rYOlgg==
,2016-01-19 23:11:34.692 ThaliTest[202:6171] client session: fireConnectCallback: 1453241471625.2390.rYOlgg==
2016-01-19 23:11:34.692 ThaliTest[202:6171] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

,2016-01-19 23:11:34.696 ThaliTest[202:5332] jxcore: disconnect
,2016-01-19 23:11:34.696 ThaliTest[202:5332] client session: disconnectFromPeer: 1453241471625.2390.rYOlgg==
,2016-01-19 23:11:34.697 ThaliTest[202:5332] client session: disconnect
,2016-01-19 23:11:34.698 ThaliTest[202:5332] client session: stateChange:2->0 1453241471625.2390.rYOlgg==
,2016-01-19 23:11:34.712 ThaliTest[202:5332] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,2016-01-19 23:11:34.714 ThaliTest[202:5332] jxcore: disconnect
,2016-01-19 23:11:34.715 ThaliTest[202:5332] jxcore: disconnect: fail
,ok 87 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-19 23:11:34.814 ThaliTest[202:5332] jxcore: stopBroadcasting
,2016-01-19 23:11:34.814 ThaliTest[202:5332] THEMultipeerSession stopping peer
,2016-01-19 23:11:34.815 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:11:34.816 ThaliTest[202:5332] server session: disconnect
2016-01-19 23:11:34.816 ThaliTest[202:5332] server session: stateChange:2->0 1453241471625.2390
,2016-01-19 23:11:34.818 ThaliTest[202:5332] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data
,
,# teardown

,echo server started on port: 49391

,2016-01-19 23:11:35.894 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:11:35.896 ThaliTest[202:5332] server: starting 1453241495894.202.ROPpZA==
2016-01-19 23:11:35.896 ThaliTest[202:5332] multipeer session: start timer: 0x184365c0
2016-01-19 23:11:35.896 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241495894.202
,2016-01-19 23:11:35.898 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error

,2016-01-19 23:11:35.950 ThaliTest[202:5016] client: found peer: 1453241471625.2390.rYOlgg==
2016-01-19 23:11:35.950 ThaliTest[202:5332] jxcore: connect 1453241471625.2390.rYOlgg==
,2016-01-19 23:11:35.951 ThaliTest[202:5332] client session: connect
2016-01-19 23:11:35.951 ThaliTest[202:5332] client session: stateChange:0->1 1453241471625.2390.rYOlgg==
,2016-01-19 23:11:37.029 ThaliTest[202:5016] client: found peer: 1453241496201.2390.YDpGQg==
2016-01-19 23:11:37.030 ThaliTest[202:5332] jxcore: connect 1453241496201.2390.YDpGQg==
2016-01-19 23:11:37.031 ThaliTest[202:5332] client session: connect
2016-,01-19 23:11:37.031 ThaliTest[202:5332] client session: stateChange:0->1 1453241496201.2390.YDpGQg==
,2016-01-19 23:11:37.171 ThaliTest[202:5016] multipeer session: reset timer
,2016-01-19 23:11:37.171 ThaliTest[202:5016] multipeer session: stop timer
,2016-01-19 23:11:37.171 ThaliTest[202:5016] multipeer session: start timer: 0x184365c0
,2016-01-19 23:11:37.172 ThaliTest[202:5016] server session: connect
,2016-01-19 23:11:37.173 ThaliTest[202:5016] server session: stateChange:0->1 1453241496201.2390
,2016-01-19 23:11:37.184 ThaliTest[202:5016] server: accepting invitation 1453241496201.2390
,2016-01-19 23:11:38.584 ThaliTest[202:5016] client: lost peer: 1453241471625.2390.rYOlgg==
2016-01-19 23:11:38.584 ThaliTest[202:5016] client session: onPeerLost: 1453241471625.2390.rYOlgg==
2016-01-19 23:11:38.585 ThaliTest[202:5016] client session: onL,inkFailure: 1453241471625.2390.rYOlgg==
2016-01-19 23:11:38.585 ThaliTest[202:5016] client session: disconnect
2016-01-19 23:11:38.585 ThaliTest[202:5016] client session: stateChange:1->0 1453241471625.2390.rYOlgg==
2016-01-19 23:11:38.586 ThaliTest[202,:5016] client session: fireConnectCallback: 1453241471625.2390.rYOlgg==
2016-01-19 23:11:38.586 ThaliTest[202:5016] jxcore: connect: fail: Peer disconnected
,2016-01-19 23:11:39.595 ThaliTest[202:5332] jxcore: connect 1453241471625.2390.rYOlgg==
2016-01-19 23:11:39.596 ThaliTest[202:5332] client: connect: unreachable 1453241471625.2390.rYOlgg==
2016-01-19 23:11:39.596 ThaliTest[202:5332] jxcore: connect: fail: Peer unreachable
,2016-01-19 23:11:41.295 ThaliTest[202:6170] server session: connected
2016-01-19 23:11:41.295 ThaliTest[202:6170] server session: stateChange:1->2 1453241496201.2390
,2016-01-19 23:11:41.315 ThaliTest[202:5016] server relay: connected (to port: 49391)
,2016-01-19 23:11:41.400 ThaliTest[202:6187] client session: connected
,2016-01-19 23:11:41.402 ThaliTest[202:6187] client session: stateChange:1->2 1453241496201.2390.YDpGQg==
,2016-01-19 23:11:41.425 ThaliTest[202:6187] client session: fireConnectCallback: 1453241496201.2390.YDpGQg==
,2016-01-19 23:11:41.426 ThaliTest[202:6187] jxcore: connect: success
,ok 89 Should be able to connect without error

,ok 90 Port should be within range

,2016-01-19 23:11:41.432 ThaliTest[202:5016] client: relay established
,2016-01-19 23:11:41.434 ThaliTest[202:5016] client: new accepted socket: 0x18324a50
,data in 52560

,data in 65700

,data in 73892

,data in 76650
,
,data in 83220

,data in 104025

,2016-01-19 23:11:41.653 ThaliTest[202:6220] server session: not connected 1453241496201.2390
,data in 108405

,data in 130305

,data in 131072

,ok 91 the test messages should be equal

,2016-01-19 23:11:41.677 ThaliTest[202:5332] jxcore: disconnect
,2016-01-19 23:11:41.678 ThaliTest[202:5332] client session: disconnectFromPeer: 1453241496201.2390.YDpGQg==
,2016-01-19 23:11:41.678 ThaliTest[202:5332] client session: disconnect
,2016-01-19 23:11:41.678 ThaliTest[202:5332] client session: stateChange:2->0 1453241496201.2390.YDpGQg==
,2016-01-19 23:11:41.682 ThaliTest[202:5332] jxcore: disconnect: success
,ok 92 Should be able to disconnect without error
,
setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-19 23:11:42.101 ThaliTest[202:5332] jxcore: stopBroadcasting
2016-01-19 23:11:42.101 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:11:42.101 ThaliTest[202:5332] multipeer session: stop timer
2016-01-19 23:11:42.102 ThaliTest[202:5332] server session: disconnect
2016-01-19 23:11:42.102 ThaliTest[202:5332] server session: stateChange:2->0 1453241496201.2390
,2016-01-19 23:11:42.115 ThaliTest[202:5332] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 49398

,2016-01-19 23:11:43.245 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:11:43.248 ThaliTest[202:5332] server: starting 1453241503244.202.A/iYNg==
2016-01-19 23:11:43.249 ThaliTest[202:5332] multipeer session: start timer: 0x1817b0a0
2016-01-19 23:11:43.250 ThaliTest[202:5332] THEMultipeerSession initialized peer 1453241503244.202
2016-01-19 23:11:43.250 ThaliTest[202:5332] jxcore: startBroadcasting: success
,ok 93 Should be able to call startBroadcasting without error

,2016-01-19 23:11:44.827 ThaliTest[202:5016] client: found peer: 1453241503891.2390.iIDXbw==
[{"peerIdentifier":"1453241503891.2390.iIDXbw==","peerName":"(null)","peerAvailable":true}]

2016-01-19 23:11:44.831 ThaliTest[202:5332] jxcore: connect 14532415,03891.2390.iIDXbw==
2016-01-19 23:11:44.833 ThaliTest[202:5332] client session: connect
2016-01-19 23:11:44.835 ThaliTest[202:5016] multipeer session: reset timer
2016-01-19 23:11:44.836 ThaliTest[202:5016] multipeer session: stop timer
,2016-01-19 23:11:44.836 ThaliTest[202:5016] multipeer session: start timer: 0x1817b0a0
2016-01-19 23:11:44.840 ThaliTest[202:5016] server session: connect
2016-01-19 23:11:44.841 ThaliTest[202:5016] server session: stateChange:0->1 1453241503891.2390
2016-01-19 23:11:44.836 ThaliTest[202:5332] client session: stateChange:0->1 1453241503891.2390.iIDXbw==
,2016-01-19 23:11:44.854 ThaliTest[202:5016] server: accepting invitation 1453241503891.2390
,2016-01-19 23:11:48.993 ThaliTest[202:6016] client session: connected
,2016-01-19 23:11:48.994 ThaliTest[202:6016] client session: stateChange:1->2 1453241503891.2390.iIDXbw==
,2016-01-19 23:11:49.002 ThaliTest[202:6016] client session: fireConnectCallback: 1453241503891.2390.iIDXbw==
2016-01-19 23:11:49.002 ThaliTest[202:6016] jxcore: connect: success
ok 94 Should be able to connect without error

,ok 95 Port should be within range

,ok 96 First connect should succeed

,2016-01-19 23:11:49.043 ThaliTest[202:6016] server session: connected
,2016-01-19 23:11:49.047 ThaliTest[202:5016] client: relay established
2016-01-19 23:11:49.047 ThaliTest[202:5016] client: new accepted socket: 0x1817d4e0
2016-01-19 23:11:49.043 ThaliTest[202:6016] server session: stateChange:1->2 1453241503891.2390
,2016-01-19 23:11:49.054 ThaliTest[202:5016] server relay: connected (to port: 49398)
,ok 97 the test messages should be equal

,ok 98 First send should succeed

,2016-01-19 23:11:49.117 ThaliTest[202:5016] client: socket closed
2016-01-19 23:11:49.117 ThaliTest[202:5016] client relay: socket disconnected
2016-01-19 23:11:49.118 ThaliTest[202:5016] client relay: 0x1817d4e0 disconnected with error Error Domain=GCDA,syncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 23:11:49.118 ThaliTest[202:5016] client session: socket closed: 1453241503891.2390.iIDXbw==
2016-01-19 23:11:49.118 Tha,liTest[202:5016] client session: onLinkFailure: 1453241503891.2390.iIDXbw==
2016-01-19 23:11:49.118 ThaliTest[202:5016] client session: disconnect
2016-01-19 23:11:49.119 ThaliTest[202:5016] client session: stateChange:2->0 1453241503891.2390.iIDXbw==
,2016-01-19 23:11:49.130 ThaliTest[202:5016] client session: fireConnectionErrorEvent: 1453241503891.2390.iIDXbw==
,2016-01-19 23:11:49.133 ThaliTest[202:5332] jxcore: connect 1453241503891.2390.iIDXbw==
,2016-01-19 23:11:49.136 ThaliTest[202:5332] client session: connect
2016-01-19 23:11:49.137 ThaliTest[202:5332] client session: stateChange:0->1 1453241503891.2390.iIDXbw==
,2016-01-19 23:11:49.300 ThaliTest[202:6220] server session: not connected 1453241503891.2390
,2016-01-19 23:11:49.421 ThaliTest[202:5016] multipeer session: reset timer
2016-01-19 23:11:49.422 ThaliTest[202:5016] multipeer session: stop timer
2016-01-19 23:11:49.422 ThaliTest[202:5016] multipeer session: start timer: 0x1817b0a0
2016-01-19 23:11:,49.422 ThaliTest[202:5016] server: disconnecting to refresh session (1453241503891.2390)
2016-01-19 23:11:49.422 ThaliTest[202:5016] server session: disconnect
2016-01-19 23:11:49.423 ThaliTest[202:5016] server session: stateChange:2->0 1453241503891.2390
,2016-01-19 23:11:49.429 ThaliTest[202:5016] server session: connect
2016-01-19 23:11:49.430 ThaliTest[202:5016] server session: stateChange:0->1 1453241503891.2390
,2016-01-19 23:11:49.440 ThaliTest[202:5016] server: accepting invitation 1453241503891.2390
,2016-01-19 23:11:53.495 ThaliTest[202:6016] server session: connected
2016-01-19 23:11:53.495 ThaliTest[202:6016] server session: stateChange:1->2 1453241503891.2390
,2016-01-19 23:11:53.503 ThaliTest[202:5016] server relay: connected (to port: 49398)
,2016-01-19 23:11:53.624 ThaliTest[202:6187] client session: connected
2016-01-19 23:11:53.625 ThaliTest[202:6187] client session: stateChange:1->2 1453241503891.2390.iIDXbw==
,2016-01-19 23:11:53.629 ThaliTest[202:6187] client session: fireConnectCallback: 1453241503891.2390.iIDXbw==
2016-01-19 23:11:53.629 ThaliTest[202:6187] jxcore: connect: success
ok 99 Should be able to connect without error

ok 100 Port should be within range

,ok 101 Second connect should succeed

,2016-01-19 23:11:53.663 ThaliTest[202:5016] client: relay established
2016-01-19 23:11:53.664 ThaliTest[202:5016] client: new accepted socket: 0x1824d060
,2016-01-19 23:11:53.675 ThaliTest[202:6170] server session: not connected 1453241503891.2390
,ok 102 the test messages should be equal

,ok 103 Second send should succeed

,# setup

,2016-01-19 23:11:53.761 ThaliTest[202:5016] client: socket closed
,2016-01-19 23:11:53.762 ThaliTest[202:5016] client relay: socket disconnected
,2016-01-19 23:11:53.762 ThaliTest[202:5016] client relay: 0x1824d060 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-19 23:11:53.763 ThaliTest[202:5016] client session: socket closed: 1453241503891.2390.iIDXbw==
2016-01-19 23:11:53.763 ThaliTest[202:5016] client session: onLinkFailure: 1453241503891.2390.iIDXbw==
2016-01-19 23:11:53.763 ThaliTest[202:5016] clie,nt session: disconnect
,2016-01-19 23:11:53.764 ThaliTest[202:5016] client session: stateChange:2->0 1453241503891.2390.iIDXbw==
,2016-01-19 23:11:53.836 ThaliTest[202:5016] client session: fireConnectionErrorEvent: 1453241503891.2390.iIDXbw==
,calling stopBroadcasting

,2016-01-19 23:11:54.141 ThaliTest[202:5332] jxcore: stopBroadcasting
2016-01-19 23:11:54.141 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:11:54.142 ThaliTest[202:5332] multipeer session: stop timer
2016-01-19 23:11:54.142 ThaliTes,t[202:5332] server session: disconnect
2016-01-19 23:11:54.142 ThaliTest[202:5332] server session: stateChange:2->0 1453241503891.2390
2016-01-19 23:11:54.148 ThaliTest[202:5332] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B65BAD01-E102-4379-811E-00E458B14B3B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 104 starting event should occur in right order

,2016-01-19 23:11:54.348 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:11:54.349 ThaliTest[202:5332] server: starting 4puYn3EKNDEaiqA4XO46jQ.3rN/nQ==
2016-01-19 23:11:54.350 ThaliTest[202:5332] multipeer session: start timer: 0x18239290
2016-01-19 23:11:54.350 ThaliTest[202:5332] THEMultipeerSession initialize,d peer 4puYn3EKNDEaiqA4XO46jQ
2016-01-19 23:11:54.350 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 105 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 106 stopping event should occur in right order

About to call stopBroadcasting

2016-01-19 23:11:54.351 ThaliTest[202:5332] jxcore: stopBroadcasting
2016-01-19 23:11:54.352 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:11:54.352 ThaliTest[202:5332] multipeer session: stop timer
,2016-01-19 23:11:54.352 ThaliTest[202:5332] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 107 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B65BAD01-E102-4379-811E-00E458B14B3B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 23:11:54.664 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:11:54.666 ThaliTest[202:5332] server: starting 4puYn3EKNDEaiqA4XO46jQ.fpHwLw==
,2016-01-19 23:11:54.667 ThaliTest[202:5332] multipeer session: start timer: 0x183d28d0
2016-01-19 23:11:54.668 ThaliTest[202:5332] THEMultipeerSession initialized peer 4puYn3EKNDEaiqA4XO46jQ
2016-01-19 23:11:54.668 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error

ok 109 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-19 23:11:54.671 ThaliTest[202:5332] jxcore: stopB,roadcasting
2016-01-19 23:11:54.671 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:11:54.672 ThaliTest[202:5332] multipeer session: stop timer
2016-01-19 23:11:54.672 ThaliTest[202:5332] jxcore: stopBroadcasting: success
Got callba,ck from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B65BAD01-E102-4379-811E-00E458B14B3B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 23:11:57.469 ThaliTest[202:5332] jxcore: startBroadcasting
,2016-01-19 23:11:57.471 ThaliTest[202:5332] server: starting 4puYn3EKNDEaiqA4XO46jQ.en4jxg==
2016-01-19 23:11:57.471 ThaliTest[202:5332] multipeer session: start timer: 0x184807f0
2016-01-19 23:11:57.471 ThaliTest[202:5332] THEMultipeerSession initialized peer 4puYn3EKNDEaiqA4XO46jQ
2016-01-19 23:11:57.471 ThaliTest[202:5332] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error

ok 111 deviceName should not be null

,2016-01-19 23:11:58.063 ThaliTest[202:5016] client: found peer: tEvNKtmcCdPiswO4AZQjcw.wcui9A==
,2016-01-19 23:12:02.057 ThaliTest[202:5332] jxcore: connect tEvNKtmcCdPiswO4AZQjcw.wcui9A==
2016-01-19 23:12:02.058 ThaliTest[202:5332] client session: connect
2016-01-19 23:12:02.058 ThaliTest[202:5332] client session: stateChange:0->1 tEvNKtmcCdPiswO4AZQjcw.wcui9A==
,2016-01-19 23:12:02.130 ThaliTest[202:5016] multipeer session: reset timer
2016-01-19 23:12:02.130 ThaliTest[202:5016] multipeer session: stop timer
2016-01-19 23:12:02.130 ThaliTest[202:5016] multipeer session: start timer: 0x184807f0
2016-01-19 23:12:02.130 ThaliTest[202:5016] server session: connect
2016-01-19 23:12:02.130 ThaliTest[202:5016] server session: stateChange:0->1 tEvNKtmcCdPiswO4AZQjcw
,2016-01-19 23:12:02.135 ThaliTest[202:5016] server: accepting invitation tEvNKtmcCdPiswO4AZQjcw
,ok 112 Should be able to put doc without error
,
,ok 113 1st change of local doc should contain local id
,
,2016-01-19 23:12:06.464 ThaliTest[202:6220] server session: connected
2016-01-19 23:12:06.467 ThaliTest[202:6220] server session: stateChange:1->2 tEvNKtmcCdPiswO4AZQjcw
,2016-01-19 23:12:06.475 ThaliTest[202:5016] server relay: connected (to port: 49413)
,server bridge: new client socket

,2016-01-19 23:12:06.493 ThaliTest[202:6016] client session: connected
,2016-01-19 23:12:06.494 ThaliTest[202:6016] client session: stateChange:1->2 tEvNKtmcCdPiswO4AZQjcw.wcui9A==
,2016-01-19 23:12:06.500 ThaliTest[202:6016] client session: fireConnectCallback: tEvNKtmcCdPiswO4AZQjcw.wcui9A==
,2016-01-19 23:12:06.501 ThaliTest[202:6016] jxcore: connect: success
,2016-01-19 23:12:06.506 ThaliTest[202:5016] client: relay established
2016-01-19 23:12:06.506 ThaliTest[202:5016] client: new accepted socket: 0x191c4ee0
,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,appEnteredForeground wasn't registered

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-19 23:12:15.576 ThaliTest[202:5332] jxcore: stopBroadcasting
2016-01-19 23:12:15.576 ThaliTest[202:5332] THEMultipeerSession stopping peer
2016-01-19 23:12:15.,576 ThaliTest[202:5332] multipeer session: stop timer
2016-01-19 23:12:15.576 ThaliTest[202:5332] client session: disconnect
2016-01-19 23:12:15.576 ThaliTest[202:5332] client session: stateChange:2->0 tEvNKtmcCdPiswO4AZQjcw.wcui9A==
,2016-01-19 23:12:15.596 ThaliTest[202:5332] server session: disconnect
2016-01-19 23:12:15.596 ThaliTest[202:5332] server session: stateChange:2->0 tEvNKtmcCdPiswO4AZQjcw
,2016-01-19 23:12:15.611 ThaliTest[202:5332] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,Process 202 stopped
* thread #18: tid = 0x1780, 0x387b7ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCSession.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x1181b66c)
    frame #0: 0x387b7ae6 libobjc.A.dylib`objc_msgSend + 6
libobjc.A.dylib`objc_msgSend:
->  0x387b7ae6 <+6>:  ldrh.w r12, [r9, #0xc]
    0x387b7aea <+10>: ldr.w  r9, [r9, #0x8]
    0x387b7aee <+14>: and.w  r12, r12, r1
    0x387b7af2 <+18>: add.w  r9, r9, r12, lsl #3
,* thread #18: tid = 0x1780, 0x387b7ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCSession.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x1181b66c)
  * frame #0: 0x387b7ae6 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x2929685e MultipeerConnectivity`<redacted> + 1334
    frame #2: 0x38ee272a libdispatch.dylib`<redacted> + 2042
    frame #3: 0x38ed1d6e libdispatch.dylib`<redacted> + 738
    frame #4: 0x38ed9b5c libdispatch.dylib`<redacted> + 592
    frame #5: 0x38ed2f86 libdispatch.dylib`<redacted> + 282
    frame #6: 0x38edb37c libdispatch.dylib`<redacted> + 400
    frame #7: 0x38edb1ea libdispatch.dylib`<redacted> + 94
    frame #8: 0x39064e0c libsystem_pthread.dylib`_pthread_wqthread + 1024
    frame #9: 0x390649fc libsystem_pthread.dylib`start_wqthread + 8

```
