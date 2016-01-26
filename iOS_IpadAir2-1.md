#### Test 5667282762e056f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5667282762e056f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/C4E19EA4-1348-459F-AC46-DE324E3E394E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C4E19EA4-1348-459F-AC46-DE324E3E394E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5667282762e056f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5667282762e056f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1EB6D788-C00F-42BA-B4CB-3951159797A2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61166"
,(lldb)     command script import "/tmp/C4E19EA4-1348-459F-AC46-DE324E3E394E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-26 18:54:27.722 ThaliTest[2767:6186646] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0269B49E-5F18-44A0-8C76-8F176A174406/Library/Cookies/Cookies.binarycookies
,2016-01-26 18:54:27.966 ThaliTest[2767:6186646] Apache Cordova native platform version 3.9.2 is starting.
2016-01-26 18:54:27.966 ThaliTest[2767:6186646] Multi-tasking -> Device: YES, App: YES
,2016-01-26 18:54:27.973 ThaliTest[2767:6186646] Unlimited access to network resources
,2016-01-26 18:54:27.979 ThaliTest[2767:6186646] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-26 18:54:32.179 ThaliTest[2767:6186646] Resetting plugins due to page load.
,2016-01-26 18:54:33.669 ThaliTest[2767:6186646] Finished load of: file:///var/mobile/Containers/Bundle/Application/1EB6D788-C00F-42BA-B4CB-3951159797A2/ThaliTest.app/www/index.html
,2016-01-26 18:54:33.810 ThaliTest[2767:6186646] JXcore Cordova plugin initializing
2016-01-26 18:54:33.810 ThaliTest[2767:6186814] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1EB6D788-C00F-42BA-B4CB-3951159797A2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1EB6D788-C00F-42BA-B4CB-3951159797A2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1EB6D788-C00F-42BA-B4CB-3951159797A2/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1EB6D788-C00F-42BA-B4CB-3951159797A2/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1EB6D788-C00F-42BA-B4CB-3951159797A2/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1EB6D788-C00F-42BA-B4CB-3951159797A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1EB6D788-C00F-42BA-B4CB-3951159797A2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1EB6D788-C00F-42BA-B4CB-3951159797A2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

,# setup

,# basic

,# teardown

,ok 11 sane

,# setup

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

ok 22 should be equal

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

,ok 26 should be equal

,ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 29 should throw

,# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

,# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 32 should throw

,# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 33 should throw

,# setup

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

,ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

,ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-26 19:00:08.188 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:08.194 ThaliTest[2767:6186814] server: starting 1453831208188.2767.Wo2XnA==
2016-01-26 19:00:08.194 ThaliTest[2767:6186814] multipeer session: start timer: 0x18647c60
,2016-01-26 19:00:08.194 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831208188.2767
2016-01-26 19:00:08.195 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.195 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:08.196 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 19:00:08.196 ThaliTest[2767:6186814] multipeer session: stop timer
2016-01-26 19:00:08.,196 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-01-26 19:00:08.196 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:08.198 ThaliTest[2767:6186814] server: starting 1453831208196.2767.VmXoIQ==
2016-01-26 19:00:08.200 ThaliTest[2767:6186814] multipeer session: start timer: 0x15d0d4d0
,2016-01-26 19:00:08.200 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831208196.2767
2016-01-26 19:00:08.200 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.201 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:08.201 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.201 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:08.201 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

2016-01-26 19:00:08.202 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:08.206 ThaliTest[2767:6186814] server: starting 1453831208202.2767.TsQjIg==
,2016-01-26 19:00:08.207 ThaliTest[2767:6186814] multipeer session: start timer: 0x17c794f0
,2016-01-26 19:00:08.207 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831208202.2767
,2016-01-26 19:00:08.208 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.209 ThaliTest[2767:6186814] jxcore: stopBroadcasting
,2016-01-26 19:00:08.209 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.209 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:08.210 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:08.211 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:08.212 ThaliTest[2767:6186814] server: starting 1453831208210.2767.2WgiuQ==
,2016-01-26 19:00:08.214 ThaliTest[2767:6186814] multipeer session: start timer: 0x182ccfe0
,2016-01-26 19:00:08.215 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831208210.2767
,2016-01-26 19:00:08.215 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.216 ThaliTest[2767:6186814] jxcore: stopBroadcasting
,2016-01-26 19:00:08.216 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.217 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:08.218 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:08.220 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:08.221 ThaliTest[2767:6186814] server: starting 1453831208219.2767.fUc6tQ==
,2016-01-26 19:00:08.222 ThaliTest[2767:6186814] multipeer session: start timer: 0x1864a900
,2016-01-26 19:00:08.224 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831208219.2767
,2016-01-26 19:00:08.224 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error
,
,2016-01-26 19:00:08.225 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:08.225 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.226 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:08.226 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error
,
2016-01-26 19:00:08.228 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:08.229 ThaliTest[2767:6186814] server: starting 1453831208228.2767.CMs9uA==
,2016-01-26 19:00:08.230 ThaliTest[2767:6186814] multipeer session: start timer: 0x182cc610
,2016-01-26 19:00:08.232 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831208228.2767
,2016-01-26 19:00:08.232 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.233 ThaliTest[2767:6186814] jxcore: stopBroadcasting
,2016-01-26 19:00:08.234 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.234 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:08.235 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:08.237 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:08.238 ThaliTest[2767:6186814] server: starting 1453831208236.2767.kR1DZg==
,2016-01-26 19:00:08.240 ThaliTest[2767:6186814] multipeer session: start timer: 0x182cd820
,2016-01-26 19:00:08.240 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831208236.2767
,2016-01-26 19:00:08.241 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.242 ThaliTest[2767:6186814] jxcore: stopBroadcasting
,2016-01-26 19:00:08.242 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.242 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:08.244 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:08.245 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:08.246 ThaliTest[2767:6186814] server: starting 1453831208245.2767.l1q9dA==
,2016-01-26 19:00:08.247 ThaliTest[2767:6186814] multipeer session: start timer: 0x15fd5d60
,2016-01-26 19:00:08.249 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831208245.2767
2016-01-26 19:00:08.249 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.250 ThaliTest[2767:6186814] jxcore: stopBroadcasting
,2016-01-26 19:00:08.250 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.250 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:08.251 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error
,
,2016-01-26 19:00:08.253 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:08.254 ThaliTest[2767:6186814] server: starting 1453831208253.2767.vhFIXw==
,2016-01-26 19:00:08.255 ThaliTest[2767:6186814] multipeer session: start timer: 0x1864cf50
,2016-01-26 19:00:08.257 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831208253.2767
,2016-01-26 19:00:08.257 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.258 ThaliTest[2767:6186814] jxcore: stopBroadcasting
,2016-01-26 19:00:08.259 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.259 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:08.260 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:08.261 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:08.263 ThaliTest[2767:6186814] server: starting 1453831208261.2767.OOPSkA==
,2016-01-26 19:00:08.263 ThaliTest[2767:6186814] multipeer session: start timer: 0x1864d1d0
,2016-01-26 19:00:08.265 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831208261.2767
,2016-01-26 19:00:08.266 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.267 ThaliTest[2767:6186814] jxcore: stopBroadcasting
,2016-01-26 19:00:08.267 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.267 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:08.268 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-26 19:00:08.999 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:09.001 ThaliTest[2767:6186814] server: starting 1453831208999.2767.HZ255g==
2016-01-26 19:00:09.001 ThaliTest[2767:6186814] multipeer session: start timer: 0x18669b70
2016-01-26 19:00:09.001 ThaliTest[2767:6186814] THEMultipeerSession in,itialized peer 1453831208999.2767
2016-01-26 19:00:09.001 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-26 19:00:09.002 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:09.002 ThaliTest[2767:6186814] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

2016-01-26 19:00:09.004 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:09.004 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 19:00:09.004 ThaliTest[2767:6186814] multipeer session: stop timer
2016-01-26 19:00:09.004 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-26 19:00:09.154 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:09.156 ThaliTest[2767:6186814] server: starting 1453831209154.2767.GE8JsQ==
2016-01-26 19:00:09.156 ThaliTest[2767:6186814] multipeer session: start timer: 0x17d9c2a0
2016-01-26 19:00:09.156 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831209154.2767
2016-01-26 19:00:09.156 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-26 19:00:09.157 ThaliTest[2767:6186814] jxcore: connect foobar
2016-01-26 19:00:09.157 ThaliTest[2767:6186814] client: unknown peer foobar
2016-01-26 19:00:09.157 ThaliTest[2767:6186814] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-01-26 19:00:09.159 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:09.159 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 19:00:09.159 ThaliTest[2767:6186814] multipeer session: stop timer
2016-01-26 19:00:09.159 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-26 19:00:11.511 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:11.513 ThaliTest[2767:6186814] server: starting 1453831211511.2767.sxroSA==
2016-01-26 19:00:11.513 ThaliTest[2767:6186814] multipeer session: start timer: 0x17caab10
2016-01-26 19:00:11.513 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831211511.2767
2016-01-26 19:00:11.513 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-26 19:00:11.514 ThaliTest[2767:6186814] jxcore: disconnect
2016-01-26 19:00:11.514 ThaliTest[2767:6186814] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-01-26 19:00:11.516 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:11.516 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 19:00:11.516 ThaliTest[2767:6186,814] multipeer session: stop timer
2016-01-26 19:00:11.516 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-26 19:00:12.042 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:12.043 ThaliTest[2767:6186814] server: starting 1453831212042.2767.U9cAKA==
,2016-01-26 19:00:12.043 ThaliTest[2767:6186814] multipeer session: start timer: 0x17cb9130
2016-01-26 19:00:12.044 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831212042.2767
2016-01-26 19:00:12.044 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-26 19:00:13.052 ThaliTest[2767:6186646] client: found peer: 1453831211547.2634.tfIylQ==
,2016-01-26 19:00:13.053 ThaliTest[2767:6186814] jxcore: connect 1453831211547.2634.tfIylQ==
2016-01-26 19:00:13.053 ThaliTest[2767:6186814] client session: connect
2016-01-26 19:00:13.053 ThaliTest[2767:6186814] client session: stateChange:0->1 1453831211547.2634.tfIylQ==
,2016-01-26 19:00:13.149 ThaliTest[2767:6186646] multipeer session: reset timer
2016-01-26 19:00:13.149 ThaliTest[2767:6186646] multipeer session: stop timer
2016-01-26 19:00:13.149 ThaliTest[2767:6186646] multipeer session: start timer: 0x17cb9130
2016-01-26 19:00:13.149 ThaliTest[2767:6186646] server session: connect
2016-01-26 19:00:13.149 ThaliTest[2767:6186646] server session: stateChange:0->1 1453831211547.2634
,2016-01-26 19:00:13.151 ThaliTest[2767:6186646] server: accepting invitation 1453831211547.2634
,2016-01-26 19:00:15.589 ThaliTest[2767:6187456] server session: connected
2016-01-26 19:00:15.589 ThaliTest[2767:6187456] server session: stateChange:1->2 1453831211547.2634
,2016-01-26 19:00:15.613 ThaliTest[2767:6186646] server relay: socket disconnected
2016-01-26 19:00:15.613 ThaliTest[2767:6186646] server relay: 0x186ef0b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-26 19:00:15.653 ThaliTest[2767:6187456] client session: connected
2016-01-26 19:00:15.653 ThaliTest[2767:6187456] client session: stateChange:1->2 1453831211547.2634.tfIylQ==
,2016-01-26 19:00:15.655 ThaliTest[2767:6187464] server session: not connected 1453831211547.2634
,2016-01-26 19:00:15.663 ThaliTest[2767:6187464] client session: fireConnectCallback: 1453831211547.2634.tfIylQ==
2016-01-26 19:00:15.663 ThaliTest[2767:6187464] jxcore: connect: success
,ok 84 Should be able to connect without error

ok 85 Port should be within range

,2016-01-26 19:00:15.665 ThaliTest[2767:6186814] jxcore: disconnect
2016-01-26 19:00:15.665 ThaliTest[2767:6186814] client session: disconnectFromPeer: 1453831211547.2634.tfIylQ==
2016-01-26 19:00:15.665 ThaliTest[2767:6186814] client session: disconnect
2016-01-26 19:00:15.665 ThaliTest[2767:6186814] client session: stateChange:2->0 1453831211547.2634.tfIylQ==
,2016-01-26 19:00:15.725 ThaliTest[2767:6186814] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-26 19:00:15.924 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:15.924 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 19:00:15.924 ThaliTest[2767:6186814] multipeer session: stop timer
2016-01-26 19:00:15.,924 ThaliTest[2767:6186814] server session: disconnect
2016-01-26 19:00:15.924 ThaliTest[2767:6186814] server session: stateChange:2->0 1453831211547.2634
2016-01-26 19:00:15.925 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-26 19:00:15.957 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:15.958 ThaliTest[2767:6186814] server: starting 1453831215957.2767.1C4Pgg==
2016-01-26 19:00:15.958 ThaliTest[2767:6186814] multipeer session: start timer: 0x186edb90
2016-01-26 19:00:15.958 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831215957.2767
,2016-01-26 19:00:15.960 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-26 19:00:15.963 ThaliTest[2767:6186646] client: found peer: 1453831211547.2634.tfIylQ==
2016-01-26 19:00:15.963 ThaliTest[2767:6186646] client: found peer: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:15.964 ThaliTest[2767:6186814] jxcore: connect 1453831211547.2634.tfIylQ==
,2016-01-26 19:00:15.964 ThaliTest[2767:6186814] client session: connect
2016-01-26 19:00:15.964 ThaliTest[2767:6186814] client session: stateChange:0->1 1453831211547.2634.tfIylQ==
,2016-01-26 19:00:15.967 ThaliTest[2767:6186814] jxcore: connect 1453831212042.2767.U9cAKA==
2016-01-26 19:00:15.968 ThaliTest[2767:6186814] client session: connect
2016-01-26 19:00:15.968 ThaliTest[2767:6186814] client session: stateChange:0->1 1453831212042.2767.U9cAKA==
,2016-01-26 19:00:17.145 ThaliTest[2767:6186646] client: lost peer: 1453831211547.2634.tfIylQ==
2016-01-26 19:00:17.145 ThaliTest[2767:6186646] client session: onPeerLost: 1453831211547.2634.tfIylQ==
2016-01-26 19:00:17.145 ThaliTest[2767:6186646] client session: onLinkFailure: 1453831211547.2634.tfIylQ==
2016-01-26 19:00:17.145 ThaliTest[2767:6186646] client session: disconnect
2016-01-26 19:00:17.145 ThaliTest[2767:6186646] client session: stateChange:1->0 1453831211547.2634.tfIylQ==
2016-01-26 19:00:17.145 ThaliTest[2767:6186646] client session: fireConnectCallback: 1453831211547.2634.tfIylQ==
,2016-01-26 19:00:17.145 ThaliTest[2767:6186646] jxcore: connect: fail: Peer disconnected
2016-01-26 19:00:17.146 ThaliTest[2767:6186646] client: lost peer: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:17.146 ThaliTest[2767:6186646] client session: onPeerLost: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:17.146 ThaliTest[2767:6186646] client session: onLinkFailure: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:17.146 ThaliTest[2767:6186646] client session: disconnect
2016-01-26 19:00:17.146 ThaliTest[276,7:6186646] client session: stateChange:1->0 1453831212042.2767.U9cAKA==
2016-01-26 19:00:17.146 ThaliTest[2767:6186646] client session: fireConnectCallback: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:17.147 ThaliTest[2767:6186646] jxcore: connect: fail: Peer disconnected
,2016-01-26 19:00:17.271 ThaliTest[2767:6186646] client: found peer: 1453831215684.2634.VzKvQg==
,2016-01-26 19:00:17.272 ThaliTest[2767:6186814] jxcore: connect 1453831215684.2634.VzKvQg==
2016-01-26 19:00:17.272 ThaliTest[2767:6186814] client session: connect
,2016-01-26 19:00:17.272 ThaliTest[2767:6186814] client session: stateChange:0->1 1453831215684.2634.VzKvQg==
,2016-01-26 19:00:17.685 ThaliTest[2767:6186646] multipeer session: reset timer
2016-01-26 19:00:17.685 ThaliTest[2767:6186646] multipeer session: stop timer
,2016-01-26 19:00:17.685 ThaliTest[2767:6186646] multipeer session: start timer: 0x186edb90
2016-01-26 19:00:17.685 ThaliTest[2767:6186646] server session: connect
,2016-01-26 19:00:17.685 ThaliTest[2767:6186646] server session: stateChange:0->1 1453831215684.2634
,2016-01-26 19:00:17.687 ThaliTest[2767:6186646] server: accepting invitation 1453831215684.2634
,2016-01-26 19:00:18.155 ThaliTest[2767:6186814] jxcore: connect 1453831211547.2634.tfIylQ==
2016-01-26 19:00:18.156 ThaliTest[2767:6186814] client: connect: unreachable 1453831211547.2634.tfIylQ==
,2016-01-26 19:00:18.156 ThaliTest[2767:6186814] jxcore: connect: fail: Peer unreachable
,2016-01-26 19:00:18.157 ThaliTest[2767:6186814] jxcore: connect 1453831212042.2767.U9cAKA==
,2016-01-26 19:00:18.157 ThaliTest[2767:6186814] client: connect: unreachable 1453831212042.2767.U9cAKA==
2016-01-26 19:00:18.157 ThaliTest[2767:6186814] jxcore: connect: fail: Peer unreachable
,2016-01-26 19:00:20.024 ThaliTest[2767:6187456] server session: connected
2016-01-26 19:00:20.024 ThaliTest[2767:6187456] server session: stateChange:1->2 1453831215684.2634
,2016-01-26 19:00:20.027 ThaliTest[2767:6186646] server relay: socket disconnected
2016-01-26 19:00:20.027 ThaliTest[2767:6186646] server relay: 0x186d0ac0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-26 19:00:20.051 ThaliTest[2767:6187455] server session: not connected 1453831215684.2634
,2016-01-26 19:00:20.141 ThaliTest[2767:6187455] client session: connected
2016-01-26 19:00:20.141 ThaliTest[2767:6187455] client session: stateChange:1->2 1453831215684.2634.VzKvQg==
,2016-01-26 19:00:20.144 ThaliTest[2767:6187450] client session: fireConnectCallback: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:20.144 ThaliTest[2767:6187450] jxcore: connect: success
ok 88 Should be able to connect without error

ok 89 Port should be within range

,2016-01-26 19:00:20.145 ThaliTest[2767:6186814] jxcore: connect 1453831215684.2634.VzKvQg==
2016-01-26 19:00:20.145 ThaliTest[2767:6186814] client: already connect(ing/ed) to 1453831215684.2634.VzKvQg==
2016-01-26 19:00:20.145 ThaliTest[2767:6186814] jxcore: connect: fail: Aleady connecting
ok 90 Should fail on double connect

,2016-01-26 19:00:20.146 ThaliTest[2767:6186814] jxcore: disconnect
2016-01-26 19:00:20.147 ThaliTest[2767:6186814] client session: disconnectFromPeer: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:20.147 ThaliTest[2767:6186814] client session: disconnect,
2016-01-26 19:00:20.147 ThaliTest[2767:6186814] client session: stateChange:2->0 1453831215684.2634.VzKvQg==
,2016-01-26 19:00:20.209 ThaliTest[2767:6186814] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-26 19:00:20.639 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:20.639 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 19:00:20.639 ThaliTest[2767:6186814] multipeer session: stop timer
2016-01-26 19:00:20.639 ThaliTest[2767:6186814] server session: disconnect
2016-01-26 19:00:20.639 ThaliTest[2767:6186814] server session: stateChange:2->0 1453831215684.2634
,2016-01-26 19:00:20.641 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-26 19:00:20.752 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:20.753 ThaliTest[2767:6186814] server: starting 1453831220752.2767.+VWqHg==
,2016-01-26 19:00:20.754 ThaliTest[2767:6186814] multipeer session: start timer: 0x17fce840
2016-01-26 19:00:20.754 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831220752.2767
2016-01-26 19:00:20.754 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-26 19:00:21.753 ThaliTest[2767:6186646] client: found peer: 1453831215684.2634.VzKvQg==
,2016-01-26 19:00:21.753 ThaliTest[2767:6186814] jxcore: connect 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.753 ThaliTest[2767:6186814] client session: connect
,2016-01-26 19:00:21.754 ThaliTest[2767:6186814] client session: stateChange:0->1 1453831215684.2634.VzKvQg==
,2016-01-26 19:00:21.773 ThaliTest[2767:6186646] client: lost peer: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.773 ThaliTest[2767:6186646] client session: onPeerLost: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.773 ThaliTest[2767:6186646] client ,session: onLinkFailure: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.773 ThaliTest[2767:6186646] client session: disconnect
2016-01-26 19:00:21.773 ThaliTest[2767:6186646] client session: stateChange:1->0 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.773 ThaliTest[2767:6186646] client session: fireConnectCallback: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.773 ThaliTest[2767:6186646] jxcore: connect: fail: Peer disconnected
,2016-01-26 19:00:21.809 ThaliTest[2767:6186646] client: found peer: 1453831220475.2634.JAOXSQ==
2016-01-26 19:00:21.810 ThaliTest[2767:6186814] jxcore: connect 1453831220475.2634.JAOXSQ==
,2016-01-26 19:00:21.810 ThaliTest[2767:6186814] client session: connect
2016-01-26 19:00:21.810 ThaliTest[2767:6186814] client session: stateChange:0->1 1453831220475.2634.JAOXSQ==
,2016-01-26 19:00:21.944 ThaliTest[2767:6186646] multipeer session: reset timer
2016-01-26 19:00:21.944 ThaliTest[2767:6186646] multipeer session: stop timer
2016-01-26 19:00:21.945 ThaliTest[2767:6186646] multipeer session: start timer: 0x17fce840
2016-,01-26 19:00:21.945 ThaliTest[2767:6186646] server session: connect
2016-01-26 19:00:21.945 ThaliTest[2767:6186646] server session: stateChange:0->1 1453831220475.2634
,2016-01-26 19:00:21.947 ThaliTest[2767:6186646] server: accepting invitation 1453831220475.2634
,2016-01-26 19:00:22.786 ThaliTest[2767:6186814] jxcore: connect 1453831215684.2634.VzKvQg==
2016-01-26 19:00:22.787 ThaliTest[2767:6186814] client: connect: unreachable 1453831215684.2634.VzKvQg==
2016-01-26 19:00:22.787 ThaliTest[2767:6186814] jxcore: connect: fail: Peer unreachable
,2016-01-26 19:00:24.705 ThaliTest[2767:6187455] server session: connected
2016-01-26 19:00:24.705 ThaliTest[2767:6187455] server session: stateChange:1->2 1453831220475.2634
2016-01-26 19:00:24.706 ThaliTest[2767:6187452] client session: connected
2016-,01-26 19:00:24.706 ThaliTest[2767:6187452] client session: stateChange:1->2 1453831220475.2634.JAOXSQ==
2016-01-26 19:00:24.707 ThaliTest[2767:6187452] client session: fireConnectCallback: 1453831220475.2634.JAOXSQ==
2016-01-26 19:00:24.707 ThaliTest[276,7:6187452] jxcore: connect: success
2016-01-26 19:00:24.707 ThaliTest[2767:6186646] server relay: socket disconnected
2016-01-26 19:00:24.707 ThaliTest[2767:6186646] server relay: 0x18083310 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
ok 93 Should be able to connect without error

ok 94 Port should be within range

,2016-01-26 19:00:24.709 ThaliTest[2767:6186814] jxcore: disconnect
2016-01-26 19:00:24.709 ThaliTest[2767:6186814] client session: disconnectFromPeer: 1453831220475.2634.JAOXSQ==
2016-01-26 19:00:24.709 ThaliTest[2767:6186814] client session: disconnect,
2016-01-26 19:00:24.709 ThaliTest[2767:6186814] client session: stateChange:2->0 1453831220475.2634.JAOXSQ==
,2016-01-26 19:00:24.766 ThaliTest[2767:6186814] jxcore: disconnect: success
ok 95 Should be able to disconnect without error
,
,2016-01-26 19:00:24.767 ThaliTest[2767:6186814] jxcore: disconnect
2016-01-26 19:00:24.768 ThaliTest[2767:6186814] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-26 19:00:24.942 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:24.943 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 19:00:24.943 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:24.943 ThaliTest[2767:6186814] server session: disconnect
2016-01-26 19:00:24.943 ThaliTest[2767:6186814] server session: stateChange:2->0 1453831220475.2634
,2016-01-26 19:00:24.948 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 57505

,2016-01-26 19:00:25.834 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:25.835 ThaliTest[2767:6186814] server: starting 1453831225833.2767.P7WhYQ==
2016-01-26 19:00:25.835 ThaliTest[2767:6186814] multipeer session: start timer: 0x186f1f00
2016-01-26 19:00:25.835 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831225833.2767
2016-01-26 19:00:25.835 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-01-26 19:00:26.745 ThaliTest[2767:6186646] client: found peer: 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:26.745 ThaliTest[2767:6186814] jxcore: connect 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:26.745 ThaliTest[2767:6186814] client session: connect
2016-01-26 19:00:26.745 ThaliTest[2767:6186814] client session: stateChange:0->1 1453831225705.2634.rlB6tQ==
,2016-01-26 19:00:27.158 ThaliTest[2767:6186646] multipeer session: reset timer
2016-01-26 19:00:27.158 ThaliTest[2767:6186646] multipeer session: stop timer
2016-01-26 19:00:27.158 ThaliTest[2767:6186646] multipeer session: start timer: 0x186f1f00
2016-01-26 19:00:27.158 ThaliTest[2767:6186646] server session: connect
2016-01-26 19:00:27.158 ThaliTest[2767:6186646] server session: stateChange:0->1 1453831225705.2634
,2016-01-26 19:00:27.160 ThaliTest[2767:6186646] server: accepting invitation 1453831225705.2634
,2016-01-26 19:00:29.676 ThaliTest[2767:6187454] client session: connected
2016-01-26 19:00:29.676 ThaliTest[2767:6187454] client session: stateChange:1->2 1453831225705.2634.rlB6tQ==
,2016-01-26 19:00:29.739 ThaliTest[2767:6187452] client session: fireConnectCallback: 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:29.739 ThaliTest[2767:6187452] jxcore: connect: success
,ok 98 Should be able to connect without error

ok 99 Port should be within range

,2016-01-26 19:00:29.741 ThaliTest[2767:6186646] client: relay established
2016-01-26 19:00:29.741 ThaliTest[2767:6186646] client: new accepted socket: 0x180e5d60
,2016-01-26 19:00:29.742 ThaliTest[2767:6187455] server session: connected
2016-01-26 19:00:29.742 ThaliTest[2767:6187455] server session: stateChange:1->2 1453831225705.2634
,2016-01-26 19:00:29.750 ThaliTest[2767:6186646] server relay: connected (to port: 57505)
,data in 26209

,data in 27375

,data in 30660

,data in 45990

,data in 62415

,data in 64605

,data in 70080

,data in 71175

,data in 85339

,data in 94170

,data in 112785

,data in 121474

,data in 131072

,ok 100 the test messages should be equal

,2016-01-26 19:00:31.191 ThaliTest[2767:6186814] jxcore: disconnect
,2016-01-26 19:00:31.191 ThaliTest[2767:6186814] client session: disconnectFromPeer: 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:31.191 ThaliTest[2767:6186814] client session: disconnect
,2016-01-26 19:00:31.191 ThaliTest[2767:6186814] client session: stateChange:2->0 1453831225705.2634.rlB6tQ==
,2016-01-26 19:00:31.195 ThaliTest[2767:6186814] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-26 19:00:31.452 ThaliTest[2767:6187450] server session: not connected 1453831225705.2634
,calling stopBroadcasting

2016-01-26 19:00:31.720 ThaliTest[2767:6186814] jxcore: stopBroadcasting
,2016-01-26 19:00:31.720 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
,2016-01-26 19:00:31.720 ThaliTest[2767:6186814] multipeer session: stop timer
,2016-01-26 19:00:31.720 ThaliTest[2767:6186814] server session: disconnect
2016-01-26 19:00:31.721 ThaliTest[2767:6186814] server session: stateChange:2->0 1453831225705.2634
,2016-01-26 19:00:31.723 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 57511

,2016-01-26 19:00:32.230 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:32.231 ThaliTest[2767:6186814] server: starting 1453831232230.2767.Yr5kzg==
2016-01-26 19:00:32.232 ThaliTest[2767:6186814] multipeer session: start timer: 0x18072590
2016-01-26 19:00:32.232 ThaliTest[2767:6186814] THEMultipeerSession initialized peer 1453831232230.2767
2016-01-26 19:00:32.232 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-26 19:00:32.833 ThaliTest[2767:6186646] client: found peer: 1453831225705.2634.rlB6tQ==
,[{"peerIdentifier":"1453831225705.2634.rlB6tQ==","peerName":"(null)","peerAvailable":true}]

,2016-01-26 19:00:32.834 ThaliTest[2767:6186814] jxcore: connect 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:32.834 ThaliTest[2767:6186814] client session: connect
2016-01-26 19:00:32.834 ThaliTest[2767:6186814] client session: stateChange:0->1 1453831225705.2634.rlB6tQ==
,2016-01-26 19:00:33.348 ThaliTest[2767:6186646] client: found peer: 1453831231960.2634.E+fcfA==
[{"peerIdentifier":"1453831231960.2634.E+fcfA==","peerName":"(null)","peerAvailable":true}]

2016-01-26 19:00:33.349 ThaliTest[2767:6186814] jxcore: connect ,1453831231960.2634.E+fcfA==
2016-01-26 19:00:33.349 ThaliTest[2767:6186814] client session: connect
2016-01-26 19:00:33.349 ThaliTest[2767:6186814] client session: stateChange:0->1 1453831231960.2634.E+fcfA==
,2016-01-26 19:00:33.490 ThaliTest[2767:6186646] multipeer session: reset timer
2016-01-26 19:00:33.490 ThaliTest[2767:6186646] multipeer session: stop timer
2016-01-26 19:00:33.490 ThaliTest[2767:6186646] multipeer session: start timer: 0x18072590
2016-01-26 19:00:33.490 ThaliTest[2767:6186646] server session: connect
2016-01-26 19:00:33.490 ThaliTest[2767:6186646] server session: stateChange:0->1 1453831231960.2634
,2016-01-26 19:00:33.492 ThaliTest[2767:6186646] server: accepting invitation 1453831231960.2634
,2016-01-26 19:00:35.781 ThaliTest[2767:6187450] server session: connected
2016-01-26 19:00:35.781 ThaliTest[2767:6187450] server session: stateChange:1->2 1453831231960.2634
,2016-01-26 19:00:35.800 ThaliTest[2767:6186646] server relay: connected (to port: 57511)
,2016-01-26 19:00:35.900 ThaliTest[2767:6187556] server session: not connected 1453831231960.2634
,2016-01-26 19:00:35.964 ThaliTest[2767:6186646] multipeer session: reset timer
2016-01-26 19:00:35.964 ThaliTest[2767:6186646] multipeer session: stop timer
2016-01-26 19:00:35.964 ThaliTest[2767:6186646] multipeer session: start timer: 0x18072590
2016-01-26 19:00:35.964 ThaliTest[2767:6186646] server: disconnecting to refresh session (1453831231960.2634)
2016-01-26 19:00:35.964 ThaliTest[2767:6186646] server session: disconnect
2016-01-26 19:00:35.964 ThaliTest[2767:6186646] server session: stateChange:2->0 1453831231960.2634
,2016-01-26 19:00:35.967 ThaliTest[2767:6187556] client session: connected
2016-01-26 19:00:35.967 ThaliTest[2767:6187556] client session: stateChange:1->2 1453831231960.2634.E+fcfA==
,2016-01-26 19:00:35.969 ThaliTest[2767:6187455] client session: fireConnectCallback: 1453831231960.2634.E+fcfA==
2016-01-26 19:00:35.969 ThaliTest[2767:6187455] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should be within range

ok 105 First connect should succeed

,2016-01-26 19:00:36.410 ThaliTest[2767:6186646] server session: connect
2016-01-26 19:00:36.410 ThaliTest[2767:6186646] server session: stateChange:0->1 1453831231960.2634
,2016-01-26 19:00:36.413 ThaliTest[2767:6186646] server: accepting invitation 1453831231960.2634
2016-01-26 19:00:36.413 ThaliTest[2767:6186646] client: relay established
2016-01-26 19:00:36.413 ThaliTest[2767:6186646] client: new accepted socket: 0x15fdd500
,ok 106 the test messages should be equal

ok 107 First send should succeed

,2016-01-26 19:00:36.445 ThaliTest[2767:6186646] client: socket closed
2016-01-26 19:00:36.445 ThaliTest[2767:6186646] client relay: socket disconnected
2016-01-26 19:00:36.445 ThaliTest[2767:6186646] client relay: 0x15fdd500 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-26 19:00:36.446 ThaliTest[2767:6186646] client session: socket closed: 1453831231960.2634.E+fcfA==
2016-01-26 19:00:36.446 ThaliTest[2767:6186646] client session: onLinkFailure: 1453831231960.2634.E+fcfA==
2016-01-26 19:00:36.446 ThaliTest[2767:6186646] client session: disconnect
2016-01-26 19:00:36.446 ThaliTest[2767:6186646] client session: stateChange:2->0 1453831231960.2634.E+fcfA==
2016-01-26 19:00:36.449 ThaliTest[2767:6186646] client session: fireConnectionErrorEvent: 1453831231960.2634.E+fcfA==
2016-01-26 19:00:36.451 ThaliTest[2767:6186814] jxcore: connect 1453831231960.2634.E+fcfA==
2016-01-26 19:00:,36.451 ThaliTest[2767:6186814] client session: connect
,2016-01-26 19:00:36.454 ThaliTest[2767:6186814] client session: stateChange:0->1 1453831231960.2634.E+fcfA==
,2016-01-26 19:00:37.030 ThaliTest[2767:6186646] client: lost peer: 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:37.030 ThaliTest[2767:6186646] client session: onPeerLost: 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:37.030 ThaliTest[2767:6186646] client session: onLinkFailure: 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:37.030 ThaliTest[2767:6186646] client session: disconnect
2016-01-26 19:00:37.030 ThaliTest[2767:6186646] client session: stateChange:1->0 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:37.030 ThaliTest[2767:6186646] client session: fireConnectCallback: 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:37.030 ThaliTest[2767:6186646] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1453831225705.2634.rlB6tQ==","peerName":"(null)","peerAvailable":false}]

,2016-01-26 19:00:38.036 ThaliTest[2767:6186814] jxcore: connect 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:38.037 ThaliTest[2767:6186814] client: connect: unreachable 1453831225705.2634.rlB6tQ==
2016-01-26 19:00:38.037 ThaliTest[2767:6186814] jxcore: connect: fail: Peer unreachable
,2016-01-26 19:00:38.817 ThaliTest[2767:6187454] server session: connected
2016-01-26 19:00:38.817 ThaliTest[2767:6187454] server session: stateChange:1->2 1453831231960.2634
,2016-01-26 19:00:38.820 ThaliTest[2767:6186646] server relay: connected (to port: 57511)
,2016-01-26 19:00:38.904 ThaliTest[2767:6187556] server session: not connected 1453831231960.2634
,2016-01-26 19:00:38.913 ThaliTest[2767:6187556] client session: connected
,2016-01-26 19:00:38.913 ThaliTest[2767:6187556] client session: stateChange:1->2 1453831231960.2634.E+fcfA==
,2016-01-26 19:00:38.915 ThaliTest[2767:6187556] client session: fireConnectCallback: 1453831231960.2634.E+fcfA==
2016-01-26 19:00:38.915 ThaliTest[2767:6187556] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-01-26 19:00:38.925 ThaliTest[2767:6186646] client: relay established
2016-01-26 19:00:38.925 ThaliTest[2767:6186646] client: new accepted socket: 0x186cbe40
,ok 111 the test messages should be equal

ok 112 Second send should succeed

,# setup

,2016-01-26 19:00:38.978 ThaliTest[2767:6186646] client: socket closed
,2016-01-26 19:00:38.978 ThaliTest[2767:6186646] client relay: socket disconnected
,2016-01-26 19:00:38.978 ThaliTest[2767:6186646] client relay: 0x186cbe40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-26 19:00:38.978 ThaliTest[2767:6186646] client session: socket closed: 1453831231960.2634.E+fcfA==
2016-01-26 19:00:38.978 ThaliTest[2767:6186646] client session: onLinkFailure: 1453831231960.2634.E+fcfA==
,2016-01-26 19:00:38.978 ThaliTest[2767:6186646] client session: disconnect
2016-01-26 19:00:38.978 ThaliTest[2767:6186646] client session: stateChange:2->0 1453831231960.2634.E+fcfA==
,2016-01-26 19:00:38.982 ThaliTest[2767:6186646] client session: fireConnectionErrorEvent: 1453831231960.2634.E+fcfA==
,calling stopBroadcasting

2016-01-26 19:00:38.984 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:38.984 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 19:00:38.984 ThaliTest[2767:6186814] multipeer session: stop timer
2016-01-26 19:00:38.984 ThaliTest[2767:6186814] server session: disconnect
2016-01-26 19:00:38.985 ThaliTest[2767:6186814] server session: stateChange:2->0 1453831231960.2634
,2016-01-26 19:00:38.989 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0269B49E-5F18-44A0-8C76-8F176A174406/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-26 19:00:39.132 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:39.133 ThaliTest[2767:6186814] server: starting j9QkXH0XmHT1VG2NqWImZA.fCVTeg==
,2016-01-26 19:00:39.133 ThaliTest[2767:6186814] multipeer session: start timer: 0x17d93130
2016-01-26 19:00:39.134 ThaliTest[2767:6186814] THEMultipeerSession initialized peer j9QkXH0XmHT1VG2NqWImZA
2016-01-26 19:00:39.134 ThaliTest[2767:6186814] jxcore:, startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

,2016-01-26 19:00:39.135 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:39.135 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 19:00:39.135 ThaliTest[2767:6186814] multipeer session: stop timer
2016-01-26 19:00:39.,135 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0269B49E-5F18-44A0-8C76-8F176A174406/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-26 19:00:39.520 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:39.521 ThaliTest[2767:6186814] server: starting j9QkXH0XmHT1VG2NqWImZA.dETwGg==
,2016-01-26 19:00:39.521 ThaliTest[2767:6186814] multipeer session: start timer: 0x1813c4f0
2016-01-26 19:00:39.521 ThaliTest[2767:6186814] THEMultipeerSession initialized peer j9QkXH0XmHT1VG2NqWImZA
2016-01-26 19:00:39.522 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
,ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-26 19:00:39.523 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:00:39.523 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 19:00:39.523 ThaliTest[2767:6186814] multipeer session: stop timer
2016-01-26 19:00:39.523 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/0269B49E-5F18-44A0-8C76-8F176A174406/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-26 19:00:41.973 ThaliTest[2767:6186814] jxcore: startBroadcasting
,2016-01-26 19:00:41.974 ThaliTest[2767:6186814] server: starting j9QkXH0XmHT1VG2NqWImZA.hiyARg==
2016-01-26 19:00:41.975 ThaliTest[2767:6186814] multipeer session: start timer: 0x185b7290
2016-01-26 19:00:41.975 ThaliTest[2767:6186814] THEMultipeerSession initialized peer j9QkXH0XmHT1VG2NqWImZA
2016-01-26 19:00:41.975 ThaliTest[2767:6186814] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-01-26 19:00:43.825 ThaliTest[2767:6186646] client: found peer: PoKEhA171ilI9rmiB4GaDg.dRlGbw==
,2016-01-26 19:00:46.107 ThaliTest[2767:6186814] jxcore: connect PoKEhA171ilI9rmiB4GaDg.dRlGbw==
2016-01-26 19:00:46.107 ThaliTest[2767:6186814] client session: connect
2016-01-26 19:00:46.107 ThaliTest[2767:6186814] client session: stateChange:0->1 PoKEh,A171ilI9rmiB4GaDg.dRlGbw==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-01-26 19:00:48.616 ThaliTest[2767:6186646] multipeer session: reset timer
,2016-01-26 19:00:48.616 ThaliTest[2767:6186646] multipeer session: stop timer
2016-01-26 19:00:48.616 ThaliTest[2767:6186646] multipeer session: start timer: 0x185b7290
2016-01-26 19:00:48.616 ThaliTest[2767:6186646] server session: connect
2016-01-26 19:00:48.616 ThaliTest[2767:6186646] server session: stateChange:0->1 PoKEhA171ilI9rmiB4GaDg
,2016-01-26 19:00:48.618 ThaliTest[2767:6186646] server: accepting invitation PoKEhA171ilI9rmiB4GaDg
,2016-01-26 19:00:50.929 ThaliTest[2767:6187454] server session: connected
2016-01-26 19:00:50.930 ThaliTest[2767:6187454] server session: stateChange:1->2 PoKEhA171ilI9rmiB4GaDg
,2016-01-26 19:00:50.931 ThaliTest[2767:6186646] server relay: connected (to port: 57527)
,server bridge: new client socket

,2016-01-26 19:00:51.230 ThaliTest[2767:6187573] client session: connected
2016-01-26 19:00:51.230 ThaliTest[2767:6187573] client session: stateChange:1->2 PoKEhA171ilI9rmiB4GaDg.dRlGbw==
,2016-01-26 19:00:51.231 ThaliTest[2767:6187573] client session: fireConnectCallback: PoKEhA171ilI9rmiB4GaDg.dRlGbw==
2016-01-26 19:00:51.231 ThaliTest[2767:6187573] jxcore: connect: success
,2016-01-26 19:00:51.236 ThaliTest[2767:6186646] client: relay established
2016-01-26 19:00:51.236 ThaliTest[2767:6186646] client: new accepted socket: 0x186ca640
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

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,2016-01-26 19:01:19.349 ThaliTest[2767:6187450] server session: not connected PoKEhA171ilI9rmiB4GaDg
,2016-01-26 19:01:19.406 ThaliTest[2767:6186646] client: lost peer: PoKEhA171ilI9rmiB4GaDg.dRlGbw==
2016-01-26 19:01:19.406 ThaliTest[2767:6186646] client session: onPeerLost: PoKEhA171ilI9rmiB4GaDg.dRlGbw==
2016-01-26 19:01:19.406 ThaliTest[2767:6186646], client session: onLinkFailure: PoKEhA171ilI9rmiB4GaDg.dRlGbw==
2016-01-26 19:01:19.406 ThaliTest[2767:6186646] client session: disconnect
2016-01-26 19:01:19.406 ThaliTest[2767:6186646] client session: stateChange:2->0 PoKEhA171ilI9rmiB4GaDg.dRlGbw==
,2016-01-26 19:01:19.409 ThaliTest[2767:6186646] client session: fireConnectionErrorEvent: PoKEhA171ilI9rmiB4GaDg.dRlGbw==
,2016-01-26 19:01:19.417 ThaliTest[2767:6186814] jxcore: disconnect
2016-01-26 19:01:19.417 ThaliTest[2767:6186814] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

2016-01-26 19:01:19.419 ThaliTest[2767:6186814] jxcore: connect PoKEhA171ilI9rmiB4GaDg.dRlGbw==
2016-01-26 19:01:19.419 ThaliTest[2767:6186814] client: connect: unreachable PoKEhA171ilI9rmiB4GaDg.dRlGbw==
,2016-01-26 19:01:19.420 ThaliTest[2767:6186814] jxcore: connect: fail: Peer unreachable
Connect error with error: Error: Peer unreachable

,client bridge: socket closed

,2016-01-26 19:01:19.452 ThaliTest[2767:6186814] jxcore: disconnect
2016-01-26 19:01:19.452 ThaliTest[2767:6186814] jxcore: disconnect: fail
Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available PoKEhA171ilI9rmiB4GaDg.dRlGbw==

,2016-01-26 19:01:19.501 ThaliTest[2767:6186646] multipeer session: restart
,client bridge: socket closed

,client bridge: socket closed

,2016-01-26 19:01:48.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:02:18.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:02:48.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:03:18.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:03:48.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:04:18.616 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:04:48.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:05:18.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:05:48.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:06:18.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:06:48.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:07:18.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:07:48.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:08:18.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:08:48.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:09:18.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:09:48.617 ThaliTest[2767:6186646] multipeer session: restart
,2016-01-26 19:10:18.617 ThaliTest[2767:6186646] multipeer session: restart
,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-26 19:10:24.742 ThaliTest[2767:6186814] jxcore: stopBroadcasting
2016-01-26 19:10:24.742 ThaliTest[2767:6186814] THEMultipeerSession stopping peer
2016-01-26 1,9:10:24.742 ThaliTest[2767:6186814] multipeer session: stop timer
2016-01-26 19:10:24.742 ThaliTest[2767:6186814] server session: disconnect
2016-01-26 19:10:24.742 ThaliTest[2767:6186814] server session: stateChange:2->0 PoKEhA171ilI9rmiB4GaDg
,2016-01-26 19:10:24.747 ThaliTest[2767:6186814] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

server bridge: socket closed

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered


```
