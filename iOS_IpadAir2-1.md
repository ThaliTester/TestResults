#### Test 57321924b5e4f25_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57321924b5e4f25/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/552128E9-E70A-4D22-BBA8-8A64C78DE33A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/552128E9-E70A-4D22-BBA8-8A64C78DE33A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57321924b5e4f25/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57321924b5e4f25/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61519"
,(lldb)     command script import "/tmp/552128E9-E70A-4D22-BBA8-8A64C78DE33A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-27 08:28:11.460 ThaliTest[3183:6349641] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C34A6825-926B-40DD-98C5-D261210E1C2E/Library/Cookies/Cookies.binarycookies
,2016-01-27 08:28:11.701 ThaliTest[3183:6349641] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-27 08:28:11.701 ThaliTest[3183:6349641] Multi-tasking -> Device: YES, App: YES
,2016-01-27 08:28:11.708 ThaliTest[3183:6349641] Unlimited access to network resources
,2016-01-27 08:28:11.713 ThaliTest[3183:6349641] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-27 08:28:15.932 ThaliTest[3183:6349641] Resetting plugins due to page load.
,2016-01-27 08:28:17.373 ThaliTest[3183:6349641] Finished load of: file:///var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/index.html
,2016-01-27 08:28:17.523 ThaliTest[3183:6349641] JXcore Cordova plugin initializing
,2016-01-27 08:28:17.524 ThaliTest[3183:6349819] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 3 firstPromise result

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

ok 6 secondPromise result

,ok 7 secondPromise testValue

,ok 8 thirdPromise in promise

,ok 9 thirdPromise result

,ok 10 thirdPromise testValue

,# setup

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

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

ok 20 should not throw

,ok 21 should be equal

,ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 23 should be equal

,# setup

,# failed to get mobile documents path

,# teardown

,ok 24 should be equal

,# setup

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

,# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 30 should throw

# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 32 should throw

# setup

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

,ok 36 should be equal

ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

ok 39 should be equal

ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

,ok 46 should be equal

ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

ok 53 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-27 08:33:20.201 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.207 ThaliTest[3183:6349819] server: starting 1453880000201.3183.PlKrBw==
,2016-01-27 08:33:20.207 ThaliTest[3183:6349819] multipeer session: start timer: 0x19fd40c0
2016-01-27 08:33:20.208 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880000201.3183
,2016-01-27 08:33:20.208 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

,2016-01-27 08:33:20.209 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:20.210 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.210 ThaliTest[3183:6349819] multipeer session: stop timer
,2016-01-27 08:33:20.211 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
,ok 55 Should be able to call stopBroadcasting without error

,2016-01-27 08:33:20.212 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.213 ThaliTest[3183:6349819] server: starting 1453880000211.3183.pvsVkQ==
2016-01-27 08:33:20.214 ThaliTest[3183:6349819] multipeer session: start timer: 0x1c106480
2016-01-27 08:33:20.214 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880000211.3183
,2016-01-27 08:33:20.214 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error

2016-01-27 08:33:20.215 ThaliTest[3183:6349819] jxcore: stopBroadcasting
,2016-01-27 08:33:20.215 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.215 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:20.215 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-01-27 08:33:20.216 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.217 ThaliTest[3183:6349819] server: starting 1453880000216.3183.seHRTw==
,2016-01-27 08:33:20.218 ThaliTest[3183:6349819] multipeer session: start timer: 0x1c105de0
2016-01-27 08:33:20.218 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880000216.3183
2016-01-27 08:33:20.218 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

2016-01-27 08:33:20.219 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:20.219 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.219 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:20.219 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

2016-01-27 08:33:20.221 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.223 ThaliTest[3183:6349819] server: starting 1453880000220.3183.cdfMiQ==
,2016-01-27 08:33:20.224 ThaliTest[3183:6349819] multipeer session: start timer: 0x19fd70b0
2016-01-27 08:33:20.224 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880000220.3183
2016-01-27 08:33:20.224 ThaliTest[3183:6349819] jxcore: sta,rtBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

2016-01-27 08:33:20.225 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:20.225 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.225 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:20.225 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

2016-01-27 08:33:20.226 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.228 ThaliTest[3183:6349819] server: starting 1453880000225.3183.PczLHA==
2016-01-27 08:33:20.228 ThaliTest[3183:6349819] multipeer session: start timer: 0x1c286600
2016-01-27 08:33:20.228 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880000225.3183
2016-01-27 08:33:20.228 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 62 Should be able to call startBroadcasting without error

2016-01-27 08:33:20.229 ThaliTest[3183:6349819] jxcore: stopBroadcasting
,2016-01-27 08:33:20.229 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.229 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:20.230 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

2016-01-27 08:33:20.231 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.233 ThaliTest[3183:6349819] server: starting 1453880000230.3183.9Di+WA==
2016-01-27 08:33:20.233 ThaliTest[3183:6349819] multipeer session: start timer: 0x1c2869d0
,2016-01-27 08:33:20.233 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880000230.3183
2016-01-27 08:33:20.234 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 64 Should be able to call startBroadcasting without error

,2016-01-27 08:33:20.235 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:20.235 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.235 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:20.,235 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
ok 65 Should be able to call stopBroadcasting without error

2016-01-27 08:33:20.236 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.238 ThaliTest[3183:6349819] server: starting 1453880000236.3183.nRL1sw==
,2016-01-27 08:33:20.239 ThaliTest[3183:6349819] multipeer session: start timer: 0x19fd8a70
2016-01-27 08:33:20.240 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880000236.3183
2016-01-27 08:33:20.240 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 66 Should be able to call startBroadcasting without error

,2016-01-27 08:33:20.240 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:20.241 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.241 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:20.241 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error

2016-01-27 08:33:20.242 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.243 ThaliTest[3183:6349819] server: starting 1453880000242.3183.AtQ24w==
2016-01-27 08:33:20.244 ThaliTest[3183:6349819] multipeer session: start timer: 0x1c286f20
2016-01-27 08:33:20.244 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880000242.3183
2016-01-27 08:33:20.244 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

2016-01-27 08:33:20.244 ThaliTest[3183:6349819] jxcore: stopBroadcasting,
2016-01-27 08:33:20.244 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.244 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:20.245 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
ok 69 Shou,ld be able to call stopBroadcasting without error

,2016-01-27 08:33:20.245 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.247 ThaliTest[3183:6349819] server: starting 1453880000245.3183.SqRzew==
2016-01-27 08:33:20.247 ThaliTest[3183:6349819] multipeer session: start timer: 0x19fd7b00
2016-01-27 08:33:20.247 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880000245.3183
2016-01-27 08:33:20.247 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 70 Should be able to call startBroadcasting without error

2016-01-27 08:33:20.248 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:20.248 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.248 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:20.248 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
ok 71 Shou,ld be able to call stopBroadcasting without error

2016-01-27 08:33:20.249 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.251 ThaliTest[3183:6349819] server: starting 1453880000249.3183.u3YZ3w==
2016-01-27 08:33:20.251 ThaliTest[3183:6349819] multipeer session: start timer: 0x19fd8580
,2016-01-27 08:33:20.251 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880000249.3183
,2016-01-27 08:33:20.251 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 72 Should be able to call startBroadcasting without error

2016-01-27 08:33:20.252 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:20.252 ThaliTest[,3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.252 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:20.253 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-27 08:33:20.683 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:20.684 ThaliTest[3183:6349819] server: starting 1453880000683.3183.FYqwzQ==
2016-01-27 08:33:20.685 ThaliTest[3183:6349819] multipeer session: start timer: 0x1c28a080
2016-01-27 08:33:20.685 ThaliTest[3183:6349819] THEMultipeerSession in,itialized peer 1453880000683.3183
2016-01-27 08:33:20.685 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-27 08:33:20.686 ThaliTest[3183:6349819] jxcore: startBroadcasting
2016-01-27 08:33:20.686 ThaliTest[3183:6349819] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

2016-01-27 08:33:20.687 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:20.687 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:20.687 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:20.688 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-27 08:33:22.756 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:22.757 ThaliTest[3183:6349819] server: starting 1453880002756.3183.vZUVxg==
2016-01-27 08:33:22.757 ThaliTest[3183:6349819] multipeer session: start timer: 0x1c28c450
2016-01-27 08:33:22.758 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880002756.3183
2016-01-27 08:33:22.758 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-27 08:33:22.758 ThaliTest[3183:6349819] jxcore: connect foobar
2,016-01-27 08:33:22.758 ThaliTest[3183:6349819] client: unknown peer foobar
2016-01-27 08:33:22.758 ThaliTest[3183:6349819] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-01-27 08:33:22.760 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:22.760 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:22.760 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:22.760 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-27 08:33:23.566 ThaliTest[3183:6349819] jxcore: startBroadcasting
,01-27 08:33:23.568 ThaliTest[3183:6349819] jxcore: disconnect: fail
2016-01-27 08:33:23.567 ThaliTest[3183:6349819] server: starting 1453880003566.3183.AyQFwg==
2016-01-27 08:33:23.567 ThaliTest[3183:6349819] multipeer session: start timer: 0x1c364630
2016-01-27 08:33:23.568 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880003566.3183
2016-01-27 08:33:23.568 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-27 08:33:23.568 ThaliTest[3183:6349819] jxcore: disconnect
2016-,ok 81 Disconnect should fail to a non-existant peer 

2016-01-27 08:33:23.570 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:23.570 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:23.570 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:23.570 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-27 08:33:24.056 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:24.057 ThaliTest[3183:6349819] server: starting 1453880004056.3183.QThslw==
,2016-01-27 08:33:24.057 ThaliTest[3183:6349819] multipeer session: start timer: 0x19fe0c80
2016-01-27 08:33:24.058 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880004056.3183
,2016-01-27 08:33:24.058 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-27 08:33:25.416 ThaliTest[3183:6349641] client: found peer: 1453880003008.2688.Ek/XhA==
,2016-01-27 08:33:25.417 ThaliTest[3183:6349819] jxcore: connect 1453880003008.2688.Ek/XhA==
2016-01-27 08:33:25.417 ThaliTest[3183:6349819] client session: connect
2016-01-27 08:33:25.417 ThaliTest[3183:6349819] client session: stateChange:0->1 1453880003008.2688.Ek/XhA==
,2016-01-27 08:33:25.614 ThaliTest[3183:6349641] multipeer session: reset timer
2016-01-27 08:33:25.615 ThaliTest[3183:6349641] multipeer session: stop timer
2016-01-27 08:33:25.615 ThaliTest[3183:6349641] multipeer session: start timer: 0x19fe0c80
2016-01-27 08:33:25.615 ThaliTest[3183:6349641] server session: connect
2016-01-27 08:33:25.615 ThaliTest[3183:6349641] server session: stateChange:0->1 1453880003008.2688
,2016-01-27 08:33:25.617 ThaliTest[3183:6349641] server: accepting invitation 1453880003008.2688
,2016-01-27 08:33:27.846 ThaliTest[3183:6350506] client session: connected
2016-01-27 08:33:27.846 ThaliTest[3183:6350506] client session: stateChange:1->2 1453880003008.2688.Ek/XhA==
,2016-01-27 08:33:27.971 ThaliTest[3183:6350502] client session: fireConnectCallback: 1453880003008.2688.Ek/XhA==
2016-01-27 08:33:27.971 ThaliTest[3183:6350502] jxcore: connect: success
ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-01-27 08:33:27.972 ThaliTest[3183:6349819] jxcore: disconnect
2016-01-27 08:33:27.972 ThaliTest[3183:6349819] client session: disconnectFromPeer: 1453880003008.2688.Ek/XhA==
2016-01-27 08:33:27.972 ThaliTest[3183:6349819] client session: disconnect
2016-01-27 08:33:27.973 ThaliTest[3183:6349819] client session: stateChange:2->0 1453880003008.2688.Ek/XhA==
,2016-01-27 08:33:27.976 ThaliTest[3183:6349819] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-27 08:33:28.108 ThaliTest[3183:6350559] server session: connected
2016-01-27 08:33:28.108 ThaliTest[3183:6350559] server session: stateChange:1->2 1453880003008.2688
,2016-01-27 08:33:28.167 ThaliTest[3183:6349641] server relay: socket disconnected
,2016-01-27 08:33:28.167 ThaliTest[3183:6349641] server relay: 0x1c366d40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 08:33:28.170 ThaliTest[3183:6350559] server session: not connected 1453880003008.2688
,calling stopBroadcasting

,2016-01-27 08:33:28.443 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:28.443 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
,2016-01-27 08:33:28.443 ThaliTest[3183:6349819] multipeer session: stop timer
,2016-01-27 08:33:28.443 ThaliTest[3183:6349819] server session: disconnect
2016-01-27 08:33:28.443 ThaliTest[3183:6349819] server session: stateChange:2->0 1453880003008.2688
2016-01-27 08:33:28.444 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-27 08:33:29.033 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:29.035 ThaliTest[3183:6349819] server: starting 1453880009033.3183.xw7pIw==
2016-01-27 08:33:29.035 ThaliTest[3183:6349819] multipeer session: start timer: 0x1c291d00
2016-01-27 08:33:29.035 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880009033.3183
2016-01-27 08:33:29.035 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-27 08:33:30.287 ThaliTest[3183:6349641] client: found peer: 1453880007957.2688.CgYDVQ==
2016-01-27 08:33:30.287 ThaliTest[3183:6349819] jxcore: connect 1453880007957.2688.CgYDVQ==
,2016-01-27 08:33:30.288 ThaliTest[3183:6349819] client session: connect
2016-01-27 08:33:30.288 ThaliTest[3183:6349819] client session: stateChange:0->1 1453880007957.2688.CgYDVQ==
,2016-01-27 08:33:30.788 ThaliTest[3183:6349641] multipeer session: reset timer
2016-01-27 08:33:30.788 ThaliTest[3183:6349641] multipeer session: stop timer
2016-01-27 08:33:30.788 ThaliTest[3183:6349641] multipeer session: start timer: 0x1c291d00
2016-01-27 08:33:30.788 ThaliTest[3183:6349641] server session: connect
2016-01-27 08:33:30.788 ThaliTest[3183:6349641] server session: stateChange:0->1 1453880007957.2688
,2016-01-27 08:33:30.790 ThaliTest[3183:6349641] server: accepting invitation 1453880007957.2688
,2016-01-27 08:33:33.086 ThaliTest[3183:6350502] client session: connected
2016-01-27 08:33:33.086 ThaliTest[3183:6350502] client session: stateChange:1->2 1453880007957.2688.CgYDVQ==
,2016-01-27 08:33:33.088 ThaliTest[3183:6350511] client session: fireConnectCallback: 1453880007957.2688.CgYDVQ==
2016-01-27 08:33:33.088 ThaliTest[3183:6350511] jxcore: connect: success
ok 88 Should be able to connect without error

,ok 89 Port should be within range

2016-01-27 08:33:33.089 ThaliTest[3183:6349819] jxcore: connect 1453880007957.2688.CgYDVQ==
2016-01-27 08:33:33.089 ThaliTest[3183:6349819] client: already connect(ing/ed) to 1453880007957.2688.CgYDVQ==
2016-01-27 08:33:33.089 ThaliTest[3183:6349819] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-01-27 08:33:33.090 ThaliTest[3183:6349819] jxcore: disconnect
2016-01-27 08:33:33.092 ThaliTest[3183:6349819] client session: disconnectFromPeer: 1453880007957.2688.CgYDVQ==
2016-01-27 08:33:33.092 ThaliTest[3183:6349819] client session: disconnect
2016-01-27 08:33:33.093 ThaliTest[3183:6349819] client session: stateChange:2->0 1453880007957.2688.CgYDVQ==
,2016-01-27 08:33:33.095 ThaliTest[3183:6350511] server session: connected
2016-01-27 08:33:33.095 ThaliTest[3183:6350511] server session: stateChange:1->2 1453880007957.2688
,2016-01-27 08:33:33.098 ThaliTest[3183:6349641] server relay: socket disconnected
2016-01-27 08:33:33.098 ThaliTest[3183:6349641] server relay: 0x1c294c80 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 08:33:33.137 ThaliTest[3183:6350505] server session: not connected 1453880007957.2688
,2016-01-27 08:33:33.157 ThaliTest[3183:6349819] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-27 08:33:33.198 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:33.198 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:33.198 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:33.,198 ThaliTest[3183:6349819] server session: disconnect
2016-01-27 08:33:33.198 ThaliTest[3183:6349819] server session: stateChange:2->0 1453880007957.2688
,2016-01-27 08:33:33.200 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-27 08:33:33.676 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:33.677 ThaliTest[3183:6349819] server: starting 1453880013676.3183.rPNufw==
2016-01-27 08:33:33.677 ThaliTest[3183:6349819] multipeer session: start timer: 0x1c36db90
2016-01-27 08:33:33.678 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880013676.3183
2016-01-27 08:33:33.678 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-27 08:33:34.864 ThaliTest[3183:6349641] multipeer session: reset timer
2016-01-27 08:33:34.865 ThaliTest[3183:6349641] multipeer session: stop timer
2016-01-27 08:33:34.865 ThaliTest[3183:6349641] multipeer session: start timer: 0x1c36db90
2016-01-27 08:33:34.865 ThaliTest[3183:6349641] server session: connect
2016-01-27 08:33:34.865 ThaliTest[3183:6349641] server session: stateChange:0->1 1453880012638.2688
2016-01-27 08:33:34.867 ThaliTest[3183:6349641] server: accepting invitation 1453880012,638.2688
2016-01-27 08:33:34.867 ThaliTest[3183:6349641] client: found peer: 1453880012638.2688.ZPC0Yg==
2016-01-27 08:33:34.867 ThaliTest[3183:6349819] jxcore: connect 1453880012638.2688.ZPC0Yg==
2016-01-27 08:33:34.868 ThaliTest[3183:6349819] client session: connect
2016-01-27 08:33:34.868 ThaliTest[3183:6349819] client session: stateChange:0->1 1453880012638.2688.ZPC0Yg==
,2016-01-27 08:33:37.440 ThaliTest[3183:6350502] client session: connected
2016-01-27 08:33:37.440 ThaliTest[3183:6350511] server session: connected
2016-01-27 08:33:37.440 ThaliTest[3183:6350502] client session: stateChange:1->2 1453880012638.2688.ZPC0Yg==
2016-01-27 08:33:37.440 ThaliTest[3183:6350511] server session: stateChange:1->2 1453880012638.2688
,2016-01-27 08:33:37.475 ThaliTest[3183:6349641] server relay: socket disconnected
,2016-01-27 08:33:37.476 ThaliTest[3183:6349641] server relay: 0x19fef810 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 08:33:37.478 ThaliTest[3183:6350506] client session: fireConnectCallback: 1453880012638.2688.ZPC0Yg==
2016-01-27 08:33:37.478 ThaliTest[3183:6350506] jxcore: connect: success
,ok 93 Should be able to connect without error

ok 94 Port should be within range

,2016-01-27 08:33:37.480 ThaliTest[3183:6349819] jxcore: disconnect
,2016-01-27 08:33:37.480 ThaliTest[3183:6349819] client session: disconnectFromPeer: 1453880012638.2688.ZPC0Yg==
,2016-01-27 08:33:37.480 ThaliTest[3183:6349819] client session: disconnect
,2016-01-27 08:33:37.480 ThaliTest[3183:6349819] client session: stateChange:2->0 1453880012638.2688.ZPC0Yg==
,2016-01-27 08:33:37.482 ThaliTest[3183:6349819] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-01-27 08:33:37.483 ThaliTest[3183:6349819] jxcore: disconnect
2016-01-27 08:33:37.483 ThaliTest[3183:6349819] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-27 08:33:37.537 ThaliTest[3183:6350511] server session: not connected 1453880012638.2688
,calling stopBroadcasting

2016-01-27 08:33:37.966 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:37.966 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
,2016-01-27 08:33:37.966 ThaliTest[3183:6349819] multipeer session: stop timer
,2016-01-27 08:33:37.966 ThaliTest[3183:6349819] server session: disconnect
,2016-01-27 08:33:37.966 ThaliTest[3183:6349819] server session: stateChange:2->0 1453880012638.2688
,2016-01-27 08:33:37.967 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 58389

,2016-01-27 08:33:39.553 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:39.555 ThaliTest[3183:6349819] server: starting 1453880019553.3183.US4PAw==
,2016-01-27 08:33:39.555 ThaliTest[3183:6349819] multipeer session: start timer: 0x19354810
,2016-01-27 08:33:39.557 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880019553.3183
,2016-01-27 08:33:39.558 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-01-27 08:33:40.824 ThaliTest[3183:6349641] client: found peer: 1453880018838.2688.8mHVeA==
2016-01-27 08:33:40.825 ThaliTest[3183:6349819] jxcore: connect 1453880018838.2688.8mHVeA==
2016-01-27 08:33:40.825 ThaliTest[3183:6349819] client session: connect
2016-01-27 08:33:40.825 ThaliTest[3183:6349819] client session: stateChange:0->1 1453880018838.2688.8mHVeA==
,2016-01-27 08:33:41.218 ThaliTest[3183:6349641] multipeer session: reset timer
2016-01-27 08:33:41.218 ThaliTest[3183:6349641] multipeer session: stop timer
2016-01-27 08:33:41.218 ThaliTest[3183:6349641] multipeer session: start timer: 0x19354810
2016-,01-27 08:33:41.218 ThaliTest[3183:6349641] server session: connect
2016-01-27 08:33:41.218 ThaliTest[3183:6349641] server session: stateChange:0->1 1453880018838.2688
,2016-01-27 08:33:41.220 ThaliTest[3183:6349641] server: accepting invitation 1453880018838.2688
,2016-01-27 08:33:43.770 ThaliTest[3183:6350511] server session: connected
2016-01-27 08:33:43.770 ThaliTest[3183:6350511] server session: stateChange:1->2 1453880018838.2688
,2016-01-27 08:33:43.794 ThaliTest[3183:6350505] client session: connected
2016-01-27 08:33:43.794 ThaliTest[3183:6350505] client session: stateChange:1->2 1453880018838.2688.8mHVeA==
,2016-01-27 08:33:43.811 ThaliTest[3183:6350561] client session: fireConnectCallback: 1453880018838.2688.8mHVeA==
,2016-01-27 08:33:43.811 ThaliTest[3183:6350561] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-01-27 08:33:43.813 ThaliTest[3183:6349641] server relay: connected (to port: 58389)
,2016-01-27 08:33:43.814 ThaliTest[3183:6349641] client: relay established
2016-01-27 08:33:43.815 ThaliTest[3183:6349641] client: new accepted socket: 0x19534590
,data in 1095

,data in 5120

,data in 7310

,data in 8405

,data in 12785

,data in 67322

,data in 69725

,data in 77390

,data in 80675

,data in 86150

,data in 104765

,data in 117905

,data in 120095

,data in 131072

ok 100 the test messages should be equal

2016-01-27 08:33:44.833 ThaliTest[3183:6349819] jxcore: disconnect
2016-01-27 08:33:44.833 ThaliTest[3183:6349819] client session: disconnectFromPeer: 1453880018838.2688.8mHVeA==
2016-01-27 08:33:44.833 ThaliTest[3183:6349819] client session: disconnect
2016-01-27 08:33:44.833 ThaliTest[3183:6349819] client session: stateChange:2->0 1453880018838.2688.8mHVeA==
,2016-01-27 08:33:44.838 ThaliTest[3183:6349819] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

# setup

,2016-01-27 08:33:44.882 ThaliTest[3183:6350562] server session: not connected 1453880018838.2688
,calling stopBroadcasting

2016-01-27 08:33:45.209 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:45.209 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:45.209 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:45.209 ThaliTest[3183:6349819] server session: disconnect
2016-01-27 08:33:45.209 ThaliTest[3183:6349819] server session: stateChange:2->0 1453880018838.2688
,2016-01-27 08:33:45.214 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 58395

,2016-01-27 08:33:46.274 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:46.275 ThaliTest[3183:6349819] server: starting 1453880026274.3183.HGmA8A==
2016-01-27 08:33:46.276 ThaliTest[3183:6349819] multipeer session: start timer: 0x19685ff0
2016-01-27 08:33:46.276 ThaliTest[3183:6349819] THEMultipeerSession initialized peer 1453880026274.3183
2016-01-27 08:33:46.276 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-27 08:33:46.328 ThaliTest[3183:6349641] client: found peer: 1453880018838.2688.8mHVeA==
[{"peerIdentifier":"1453880018838.2688.8mHVeA==","peerName":"(null)","peerAvailable":true}]

,2016-01-27 08:33:46.329 ThaliTest[3183:6349819] jxcore: connect 1453880018838.2688.8mHVeA==
2016-01-27 08:33:46.329 ThaliTest[3183:6349819] client session: connect
2016-01-27 08:33:46.329 ThaliTest[3183:6349819] client session: stateChange:0->1 145388001,8838.2688.8mHVeA==
,2016-01-27 08:33:47.508 ThaliTest[3183:6349641] multipeer session: reset timer
2016-01-27 08:33:47.508 ThaliTest[3183:6349641] multipeer session: stop timer
2016-01-27 08:33:47.508 ThaliTest[3183:6349641] multipeer session: start timer: 0x19685ff0
2016-,01-27 08:33:47.508 ThaliTest[3183:6349641] server session: connect
2016-01-27 08:33:47.508 ThaliTest[3183:6349641] server session: stateChange:0->1 1453880025246.2688
2016-01-27 08:33:47.510 ThaliTest[3183:6349641] server: accepting invitation 1453880025246.2688
,2016-01-27 08:33:48.431 ThaliTest[3183:6349641] client: lost peer: 1453880018838.2688.8mHVeA==
2016-01-27 08:33:48.431 ThaliTest[3183:6349641] client session: onPeerLost: 1453880018838.2688.8mHVeA==
2016-01-27 08:33:48.431 ThaliTest[3183:6349641] client ,session: onLinkFailure: 1453880018838.2688.8mHVeA==
2016-01-27 08:33:48.431 ThaliTest[3183:6349641] client session: disconnect
2016-01-27 08:33:48.431 ThaliTest[3183:6349641] client session: stateChange:1->0 1453880018838.2688.8mHVeA==
2016-01-27 08:33:48.432 ThaliTest[3183:6349641] client session: fireConnectCallback: 1453880018838.2688.8mHVeA==
2016-01-27 08:33:48.432 ThaliTest[3183:6349641] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1453880018838.2688.8mHVeA==","peerName":"(null)","peerAvailable":false}]

,2016-01-27 08:33:48.434 ThaliTest[3183:6349641] client: found peer: 1453880025246.2688.urxjdw==
[{"peerIdentifier":"1453880025246.2688.urxjdw==","peerName":"(null)","peerAvailable":true}]

,2016-01-27 08:33:48.435 ThaliTest[3183:6349819] jxcore: connect 1453880025246.2688.urxjdw==
2016-01-27 08:33:48.435 ThaliTest[3183:6349819] client session: connect
2016-01-27 08:33:48.435 ThaliTest[3183:6349819] client session: stateChange:0->1 1453880025246.2688.urxjdw==
,2016-01-27 08:33:49.443 ThaliTest[3183:6349819] jxcore: connect 1453880018838.2688.8mHVeA==
2016-01-27 08:33:49.443 ThaliTest[3183:6349819] client: connect: unreachable 1453880018838.2688.8mHVeA==
,2016-01-27 08:33:49.443 ThaliTest[3183:6349819] jxcore: connect: fail: Peer unreachable
,2016-01-27 08:33:49.946 ThaliTest[3183:6350505] server session: connected
2016-01-27 08:33:49.946 ThaliTest[3183:6350505] server session: stateChange:1->2 1453880025246.2688
,2016-01-27 08:33:49.948 ThaliTest[3183:6349641] server relay: connected (to port: 58395)
,2016-01-27 08:33:50.105 ThaliTest[3183:6350561] server session: not connected 1453880025246.2688
,2016-01-27 08:33:50.148 ThaliTest[3183:6349641] multipeer session: reset timer
2016-01-27 08:33:50.148 ThaliTest[3183:6349641] multipeer session: stop timer
2016-01-27 08:33:50.149 ThaliTest[3183:6349641] multipeer session: start timer: 0x19685ff0
2016-,01-27 08:33:50.149 ThaliTest[3183:6349641] server: disconnecting to refresh session (1453880025246.2688)
2016-01-27 08:33:50.149 ThaliTest[3183:6349641] server session: disconnect
2016-01-27 08:33:50.149 ThaliTest[3183:6349641] server session: stateChange:2->0 1453880025246.2688
,2016-01-27 08:33:50.150 ThaliTest[3183:6349641] server session: connect
2016-01-27 08:33:50.150 ThaliTest[3183:6349641] server session: stateChange:0->1 1453880025246.2688
,2016-01-27 08:33:50.153 ThaliTest[3183:6349641] server: accepting invitation 1453880025246.2688
,2016-01-27 08:33:50.911 ThaliTest[3183:6350506] client session: connected
,2016-01-27 08:33:50.912 ThaliTest[3183:6350506] client session: stateChange:1->2 1453880025246.2688.urxjdw==
,2016-01-27 08:33:50.914 ThaliTest[3183:6350505] client session: fireConnectCallback: 1453880025246.2688.urxjdw==
2016-01-27 08:33:50.915 ThaliTest[3183:6350505] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-01-27 08:33:50.924 ThaliTest[3183:6349641] client: relay established
2016-01-27 08:33:50.925 ThaliTest[3183:6349641] client: new accepted socket: 0x19534590
,ok 106 the test messages should be equal

ok 107 First send should succeed

,2016-01-27 08:33:51.255 ThaliTest[3183:6349641] client: socket closed
2016-01-27 08:33:51.255 ThaliTest[3183:6349641] client relay: socket disconnected
2016-01-27 08:33:51.255 ThaliTest[3183:6349641] client relay: 0x19534590 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-27 08:33:,51.255 ThaliTest[3183:6349641] client session: socket closed: 1453880025246.2688.urxjdw==
,2016-01-27 08:33:51.255 ThaliTest[3183:6349641] client session: onLinkFailure: 1453880025246.2688.urxjdw==
2016-01-27 08:33:51.255 ThaliTest[3183:6349641] client session: disconnect
2016-01-27 08:33:51.255 ThaliTest[3183:6349641] client session: stateChange:2->0 1453880025246.2688.urxjdw==
,2016-01-27 08:33:51.258 ThaliTest[3183:6349641] client session: fireConnectionErrorEvent: 1453880025246.2688.urxjdw==
,2016-01-27 08:33:51.259 ThaliTest[3183:6349819] jxcore: connect 1453880025246.2688.urxjdw==
2016-01-27 08:33:51.259 ThaliTest[3183:6349819] client session: connect
2016-01-27 08:33:51.260 ThaliTest[3183:6349819] client session: stateChange:0->1 1453880025246.2688.urxjdw==
,2016-01-27 08:33:52.487 ThaliTest[3183:6350506] server session: connected
2016-01-27 08:33:52.487 ThaliTest[3183:6350506] server session: stateChange:1->2 1453880025246.2688
,2016-01-27 08:33:52.508 ThaliTest[3183:6349641] server relay: connected (to port: 58395)
,2016-01-27 08:33:52.658 ThaliTest[3183:6350505] server session: not connected 1453880025246.2688
,2016-01-27 08:33:54.651 ThaliTest[3183:6350505] client session: connected
2016-01-27 08:33:54.651 ThaliTest[3183:6350505] client session: stateChange:1->2 1453880025246.2688.urxjdw==
,2016-01-27 08:33:54.654 ThaliTest[3183:6350560] client session: fireConnectCallback: 1453880025246.2688.urxjdw==
2016-01-27 08:33:54.654 ThaliTest[3183:6350560] jxcore: connect: success
ok 108 Should be able to connect without error

ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-01-27 08:33:54.664 ThaliTest[3183:6349641] client: relay established
2016-01-27 08:33:54.665 ThaliTest[3183:6349641] client: new accepted socket: 0x1c1423a0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-01-27 08:33:54.798 ThaliTest[3183:6349641] client: socket closed
2016-01-27 08:33:54.798 ThaliTest[3183:6349641] client relay: socket disconnected
2016-01-27 08:33:54.798 ThaliTest[3183:6349641] client relay: 0x1c1423a0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-27 08:33:54.798 ThaliTest[3183:6349641] client session: socket closed: 1453880025246.2688.urxjdw==
2016-01-27 08:33:54.798 ThaliTest[3183:6349641] client session: onLinkFailure: 1453880025246.2688.urxjdw==
2016-01-27 08:33:54.798 ThaliTest[3183:6349641] client session: disconnect
2016-01-27 08:33:54.798 ThaliTest[3183:6349641] client session: stateChange:2->0 1453880025246.2688.urxjdw==
,2016-01-27 08:33:54.801 ThaliTest[3183:6349641] client session: fireConnectionErrorEvent: 1453880025246.2688.urxjdw==
,calling stopBroadcasting

2016-01-27 08:33:55.173 ThaliTest[3183:6349819] jxcore: stopBroadcasting
,2016-01-27 08:33:55.173 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
,2016-01-27 08:33:55.173 ThaliTest[3183:6349819] multipeer session: stop timer
,2016-01-27 08:33:55.174 ThaliTest[3183:6349819] server session: disconnect
2016-01-27 08:33:55.174 ThaliTest[3183:6349819] server session: stateChange:2->0 1453880025246.2688
,2016-01-27 08:33:55.856 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C34A6825-926B-40DD-98C5-D261210E1C2E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-27 08:33:56.760 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:56.761 ThaliTest[3183:6349819] server: starting HLQyXwiCWbGpHCzR88ORyQ.+qV2og==
2016-01-27 08:33:56.761 ThaliTest[3183:6349819] multipeer session: start timer: 0x19841f20
2016-01-27 08:33:56.761 ThaliTest[3183:6349819] THEMultipeerSession initialized peer HLQyXwiCWbGpHCzR88ORyQ
2016-01-27 08:33:56.761 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

2016-01-27 08:33:56.763 ThaliTest[3183:6349819] jxcore: stopBroadcasting
,2016-01-27 08:33:56.763 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:33:56.763 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:56.763 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C34A6825-926B-40DD-98C5-D261210E1C2E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-27 08:33:57.915 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:33:57.916 ThaliTest[3183:6349819] server: starting HLQyXwiCWbGpHCzR88ORyQ.Yobg2A==
2016-01-27 08:33:57.916 ThaliTest[3183:6349819] multipeer session: start timer: 0x1772f300
2016-01-27 08:33:57.917 ThaliTest[3183:6349819] THEMultipeerSession initialized peer HLQyXwiCWbGpHCzR88ORyQ
2016-01-27 08:33:57.917 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-27 08:33:57.918 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:33:57.918 ThaliTest[3183:6349819] THEMult,ipeerSession stopping peer
2016-01-27 08:33:57.918 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:33:57.918 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C34A6825-926B-40DD-98C5-D261210E1C2E/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-27 08:34:01.393 ThaliTest[3183:6349819] jxcore: startBroadcasting
,2016-01-27 08:34:01.394 ThaliTest[3183:6349819] server: starting HLQyXwiCWbGpHCzR88ORyQ.TdpHJg==
2016-01-27 08:34:01.394 ThaliTest[3183:6349819] multipeer session: start timer: 0x177066b0
2016-01-27 08:34:01.394 ThaliTest[3183:6349819] THEMultipeerSessio,n initialized peer HLQyXwiCWbGpHCzR88ORyQ
2016-01-27 08:34:01.394 ThaliTest[3183:6349819] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-01-27 08:34:03.822 ThaliTest[3183:6349641] client: found peer: 9XwvBGLtp95yQVbibKCgjA.xSu9ag==
,2016-01-27 08:34:05.581 ThaliTest[3183:6349819] jxcore: connect 9XwvBGLtp95yQVbibKCgjA.xSu9ag==
2016-01-27 08:34:05.581 ThaliTest[3183:6349819] client session: connect
2016-01-27 08:34:05.581 ThaliTest[3183:6349819] client session: stateChange:0->1 9XwvBGLtp95yQVbibKCgjA.xSu9ag==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-01-27 08:34:08.672 ThaliTest[3183:6349641] multipeer session: reset timer
2016-01-27 08:34:08.672 ThaliTest[3183:6349641] multipeer session: stop timer
,2016-01-27 08:34:08.672 ThaliTest[3183:6349641] multipeer session: start timer: 0x177066b0
,2016-01-27 08:34:08.672 ThaliTest[3183:6349641] server session: connect
,2016-01-27 08:34:08.672 ThaliTest[3183:6349641] server session: stateChange:0->1 9XwvBGLtp95yQVbibKCgjA
,2016-01-27 08:34:08.674 ThaliTest[3183:6349641] server: accepting invitation 9XwvBGLtp95yQVbibKCgjA
,2016-01-27 08:34:11.085 ThaliTest[3183:6350506] client session: connected
2016-01-27 08:34:11.085 ThaliTest[3183:6350506] client session: stateChange:1->2 9XwvBGLtp95yQVbibKCgjA.xSu9ag==
2016-01-27 08:34:11.086 ThaliTest[3183:6350506] client session: fir,eConnectCallback: 9XwvBGLtp95yQVbibKCgjA.xSu9ag==
2016-01-27 08:34:11.086 ThaliTest[3183:6350506] jxcore: connect: success
,2016-01-27 08:34:11.090 ThaliTest[3183:6349641] client: relay established
2016-01-27 08:34:11.090 ThaliTest[3183:6349641] client: new accepted socket: 0x194a8320
,client bridge: new client socket

,client bridge: new client socket

,2016-01-27 08:34:11.220 ThaliTest[3183:6350505] server session: connected
,2016-01-27 08:34:11.220 ThaliTest[3183:6350505] server session: stateChange:1->2 9XwvBGLtp95yQVbibKCgjA
,2016-01-27 08:34:11.223 ThaliTest[3183:6349641] server relay: connected (to port: 58411)
,server bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,Possibly unhandled Error. ETIMEDOUT
onError@/private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:66:18
ajax/<@/private/var/mobile/Containers/Bundle/Applicati,on/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:108:1
Request.prototype.init/self.callback@/private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/node_modules/pouchdb/node_modules/request/request.js:123:7
emit@events.js:82:1
Request.prototype.start/self.timeoutTimer<@/private/var/mobile/Containers/Bundle/Application/C4BB457C-F711-4CCF-9902-06F0C65E7F68/ThaliTest.app/www/jxcore/node_modules/pouchdb/node_modules/request/request.js:590:7
$9@timers.js:120:1


,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 123 1st change of remote doc should contain remote id

,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: '7c0bf192-f13d-425e-b464-aca0eea61812',
  rev: '2-3c8b5be179711603f6a74c3769a9ad36' }

,client bridge: new client socket

,ok 125 Remote changes occur in strict order

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

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,ok 126 Local changes occur in strict order

ok 127 2nd change of local doc should contain remote id

,# setup

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-27 08:34:30.296 ThaliTest[3183:6349819] jxcore: stopBroadcasting
2016-01-27 08:34:30.296 ThaliTest[3183:6349819] THEMultipeerSession stopping peer
2016-01-27 08:34:30.296 ThaliTest[3183:6349819] multipeer session: stop timer
2016-01-27 08:34:30.296 ThaliTest[3183:6349819] client session: disconnect
,2016-01-27 08:34:30.296 ThaliTest[3183:6349819] client session: stateChange:2->0 9XwvBGLtp95yQVbibKCgjA.xSu9ag==
,2016-01-27 08:34:30.303 ThaliTest[3183:6349819] server session: disconnect
2016-01-27 08:34:30.303 ThaliTest[3183:6349819] server session: stateChange:2->0 9XwvBGLtp95yQVbibKCgjA
,2016-01-27 08:34:30.312 ThaliTest[3183:6349819] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,client bridge: socket closed

,server bridge: socket closed

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,# teardown

,client bridge: socket closed

,client bridge: socket closed

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered


```
