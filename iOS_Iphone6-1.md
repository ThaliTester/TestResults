#### Test 564496606be5677_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/564496606be5677/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AAF1C1E5-79B3-4984-A904-04952A008550/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AAF1C1E5-79B3-4984-A904-04952A008550/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/564496606be5677/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/564496606be5677/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D2661542-A4A8-4220-9211-E7B658A14C3B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59011"
,(lldb)     command script import "/tmp/AAF1C1E5-79B3-4984-A904-04952A008550/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-20 12:14:05.717 ThaliTest[246:72376] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E78C1CC5-B15D-4A44-8669-F2A03C22268E/Library/Cookies/Cookies.binarycookies
,2016-01-20 12:14:06.198 ThaliTest[246:72376] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-20 12:14:06.200 ThaliTest[246:72376] Multi-tasking -> Device: YES, App: YES
,2016-01-20 12:14:06.210 ThaliTest[246:72376] Unlimited access to network resources
,2016-01-20 12:14:06.223 ThaliTest[246:72376] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-20 12:14:16.175 ThaliTest[246:72376] Resetting plugins due to page load.
,2016-01-20 12:14:20.089 ThaliTest[246:72376] Finished load of: file:///var/mobile/Containers/Bundle/Application/D2661542-A4A8-4220-9211-E7B658A14C3B/ThaliTest.app/www/index.html
,2016-01-20 12:14:20.280 ThaliTest[246:72376] JXcore Cordova plugin initializing
2016-01-20 12:14:20.281 ThaliTest[246:72609] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D2661542-A4A8-4220-9211-E7B658A14C3B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D2661542-A4A8-4220-9211-E7B658A14C3B/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D2661542-A4A8-4220-9211-E7B658A14C3B/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D2661542-A4A8-4220-9211-E7B658A14C3B/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D2661542-A4A8-4220-9211-E7B658A14C3B/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D2661542-A4A8-4220-9211-E7B658A14C3B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D2661542-A4A8-4220-9211-E7B658A14C3B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-01-20 12:19:08.841 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:08.857 ThaliTest[246:72609] server: starting 1453288748841.246.kRANrA==
,2016-01-20 12:19:08.860 ThaliTest[246:72609] multipeer session: start timer: 0x167a9750
,2016-01-20 12:19:08.864 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288748841.246
,2016-01-20 12:19:08.875 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error

,2016-01-20 12:19:08.881 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:08.883 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:08.884 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:08.887 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:08.894 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:08.899 ThaliTest[246:72609] server: starting 1453288748893.246.0k0HNg==
,2016-01-20 12:19:08.902 ThaliTest[246:72609] multipeer session: start timer: 0x162874e0
,2016-01-20 12:19:08.909 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288748893.246
,2016-01-20 12:19:08.911 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error

,2016-01-20 12:19:08.914 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:08.916 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:08.917 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:08.923 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:08.927 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:08.931 ThaliTest[246:72609] server: starting 1453288748927.246.WyJQwQ==
,2016-01-20 12:19:08.935 ThaliTest[246:72609] multipeer session: start timer: 0x162866c0
,2016-01-20 12:19:08.941 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288748927.246
,2016-01-20 12:19:08.942 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error

,2016-01-20 12:19:08.944 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:08.945 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:08.946 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:08.948 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:08.953 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:08.956 ThaliTest[246:72609] server: starting 1453288748953.246.AZRn3g==
,2016-01-20 12:19:08.958 ThaliTest[246:72609] multipeer session: start timer: 0x167b0810
,2016-01-20 12:19:08.964 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288748953.246
,2016-01-20 12:19:08.964 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error

,2016-01-20 12:19:08.967 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:08.968 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:08.969 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:08.971 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:08.977 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:08.980 ThaliTest[246:72609] server: starting 1453288748976.246.668YOw==
,2016-01-20 12:19:08.981 ThaliTest[246:72609] multipeer session: start timer: 0x167f6810
,2016-01-20 12:19:08.984 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288748976.246
,2016-01-20 12:19:08.985 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error

,2016-01-20 12:19:08.990 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:08.990 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:08.991 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:08.992 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:08.997 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:09.000 ThaliTest[246:72609] server: starting 1453288748997.246.lQ/L+A==
,2016-01-20 12:19:09.002 ThaliTest[246:72609] multipeer session: start timer: 0x167f1630
,2016-01-20 12:19:09.005 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288748997.246
,2016-01-20 12:19:09.007 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error

,2016-01-20 12:19:09.012 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:09.012 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:09.014 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:09.014 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,
,2016-01-20 12:19:09.020 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:09.023 ThaliTest[246:72609] server: starting 1453288749019.246.3RjQyw==
,2016-01-20 12:19:09.024 ThaliTest[246:72609] multipeer session: start timer: 0x16294270
,2016-01-20 12:19:09.025 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288749019.246
,2016-01-20 12:19:09.028 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error

,2016-01-20 12:19:09.033 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:09.034 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:09.035 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:09.036 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:09.041 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:09.043 ThaliTest[246:72609] server: starting 1453288749040.246.2iKKug==
,2016-01-20 12:19:09.044 ThaliTest[246:72609] multipeer session: start timer: 0x167f1300
,2016-01-20 12:19:09.045 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288749040.246
,2016-01-20 12:19:09.046 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error

,2016-01-20 12:19:09.050 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:09.051 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:09.052 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:09.052 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:09.056 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:09.058 ThaliTest[246:72609] server: starting 1453288749056.246.iMLjbA==
,2016-01-20 12:19:09.059 ThaliTest[246:72609] multipeer session: start timer: 0x167f30a0
,2016-01-20 12:19:09.061 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288749056.246
,2016-01-20 12:19:09.062 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error

,2016-01-20 12:19:09.066 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:09.066 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:09.067 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:09.069 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:09.072 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:09.074 ThaliTest[246:72609] server: starting 1453288749072.246.tor0aw==
,2016-01-20 12:19:09.075 ThaliTest[246:72609] multipeer session: start timer: 0x14d75800
,2016-01-20 12:19:09.077 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288749072.246
,2016-01-20 12:19:09.079 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,
,2016-01-20 12:19:09.082 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:09.083 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:09.083 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:09.084 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-20 12:19:09.147 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:09.149 ThaliTest[246:72609] server: starting 1453288749146.246.hAP0Iw==
,2016-01-20 12:19:09.152 ThaliTest[246:72609] multipeer session: start timer: 0x16295550
,2016-01-20 12:19:09.156 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288749146.246
,2016-01-20 12:19:09.157 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

,2016-01-20 12:19:09.160 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:09.161 ThaliTest[246:72609] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

,2016-01-20 12:19:09.165 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:09.165 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:09.166 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:09.171 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-20 12:19:09.236 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:09.239 ThaliTest[246:72609] server: starting 1453288749236.246.UD23EQ==
,2016-01-20 12:19:09.241 ThaliTest[246:72609] multipeer session: start timer: 0x172faba0
,2016-01-20 12:19:09.244 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288749236.246
,2016-01-20 12:19:09.247 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-20 12:19:09.250 ThaliTest[246:72609] jxcore: connect foobar
,2016-01-20 12:19:09.251 ThaliTest[246:72609] client: unknown peer foobar
,2016-01-20 12:19:09.252 ThaliTest[246:72609] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer

,2016-01-20 12:19:09.256 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:09.256 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:09.257 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:09.260 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-20 12:19:09.314 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:09.317 ThaliTest[246:72609] server: starting 1453288749314.246.SBq8RQ==
,2016-01-20 12:19:09.319 ThaliTest[246:72609] multipeer session: start timer: 0x162be430
,2016-01-20 12:19:09.323 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288749314.246
,2016-01-20 12:19:09.325 ThaliTest[246:72609] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-01-20 12:19:09.327 ThaliTest[246:72609] jxcore: disconnect
,2016-01-20 12:19:09.328 ThaliTest[246:72609] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 

,2016-01-20 12:19:09.332 ThaliTest[246:72609] jxcore: stopBroadcasting
,2016-01-20 12:19:09.333 ThaliTest[246:72609] THEMultipeerSession stopping peer
,2016-01-20 12:19:09.334 ThaliTest[246:72609] multipeer session: stop timer
,2016-01-20 12:19:09.336 ThaliTest[246:72609] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-20 12:19:10.314 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:10.317 ThaliTest[246:72609] server: starting 1453288750313.246.SLES3A==
2016-01-20 12:19:10.318 ThaliTest[246:72609] multipeer session: start timer: 0x162ea550
2016-01-20 12:19:10.318 ThaliTest[246:72609] THEMultipeerSession initialized ,peer 1453288750313.246
2016-01-20 12:19:10.319 ThaliTest[246:72609] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-01-20 12:19:11.600 ThaliTest[246:72376] client: found peer: 1453288750367.2419.yCQHqg==
,2016-01-20 12:19:11.602 ThaliTest[246:72609] jxcore: connect 1453288750367.2419.yCQHqg==
,2016-01-20 12:19:11.604 ThaliTest[246:72609] client session: connect
2016-01-20 12:19:11.604 ThaliTest[246:72609] client session: stateChange:0->1 1453288750367.2419.yCQHqg==
,2016-01-20 12:19:12.740 ThaliTest[246:72376] multipeer session: reset timer
2016-01-20 12:19:12.740 ThaliTest[246:72376] multipeer session: stop timer
2016-01-20 12:19:12.741 ThaliTest[246:72376] multipeer session: start timer: 0x162ea550
2016-01-20 12:,19:12.741 ThaliTest[246:72376] server session: connect
2016-01-20 12:19:12.742 ThaliTest[246:72376] server session: stateChange:0->1 1453288750367.2419
2016-01-20 12:19:12.749 ThaliTest[246:72376] server: accepting invitation 1453288750367.2419
,2016-01-20 12:19:15.729 ThaliTest[246:73108] client session: connected
2016-01-20 12:19:15.729 ThaliTest[246:73108] client session: stateChange:1->2 1453288750367.2419.yCQHqg==
,2016-01-20 12:19:15.742 ThaliTest[246:73107] client session: fireConnectCallback: 1453288750367.2419.yCQHqg==
,2016-01-20 12:19:15.742 ThaliTest[246:73107] jxcore: connect: success
,ok 75 Should be able to connect without error

,ok 76 Port should be within range

,2016-01-20 12:19:15.747 ThaliTest[246:72609] jxcore: disconnect
2016-01-20 12:19:15.748 ThaliTest[246:72609] client session: disconnectFromPeer: 1453288750367.2419.yCQHqg==
,2016-01-20 12:19:15.749 ThaliTest[246:72609] client session: disconnect
2016-01-20 12:19:15.749 ThaliTest[246:72609] client session: stateChange:2->0 1453288750367.2419.yCQHqg==
,2016-01-20 12:19:15.827 ThaliTest[246:72609] jxcore: disconnect: success
ok 77 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-20 12:19:16.452 ThaliTest[246:73108] server session: connected
2016-01-20 12:19:16.452 ThaliTest[246:73108] server session: stateChange:1->2 1453288750367.2419
,2016-01-20 12:19:16.467 ThaliTest[246:72376] server relay: socket disconnected
2016-01-20 12:19:16.467 ThaliTest[246:72376] server relay: 0x16462810 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalized,FailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-20 12:19:16.710 ThaliTest[246:73107] server session: not connected 1453288750367.2419
,calling stopBroadcasting

,2016-01-20 12:19:17.163 ThaliTest[246:72609] jxcore: stopBroadcasting
2016-01-20 12:19:17.164 ThaliTest[246:72609] THEMultipeerSession stopping peer
2016-01-20 12:19:17.164 ThaliTest[246:72609] multipeer session: stop timer
2016-01-20 12:19:17.165 Thali,Test[246:72609] server session: disconnect
2016-01-20 12:19:17.165 ThaliTest[246:72609] server session: stateChange:2->0 1453288750367.2419
2016-01-20 12:19:17.166 ThaliTest[246:72609] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-20 12:19:18.142 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:18.146 ThaliTest[246:72609] server: starting 1453288758142.246.YEBrRw==
2016-01-20 12:19:18.147 ThaliTest[246:72609] multipeer session: start timer: 0x162008d0
2016-01-20 12:19:18.147 ThaliTest[246:72609] THEMultipeerSession initialized ,peer 1453288758142.246
2016-01-20 12:19:18.147 ThaliTest[246:72609] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-20 12:19:19.443 ThaliTest[246:72376] multipeer session: reset timer
2016-01-20 12:19:19.443 ThaliTest[246:72376] multipeer session: stop timer
2016-01-20 12:19:19.444 ThaliTest[246:72376] multipeer session: start timer: 0x162008d0
2016-01-20 12:,19:19.444 ThaliTest[246:72376] server session: connect
2016-01-20 12:19:19.444 ThaliTest[246:72376] server session: stateChange:0->1 1453288759388.2419
,2016-01-20 12:19:19.454 ThaliTest[246:72376] server: accepting invitation 1453288759388.2419
,2016-01-20 12:19:20.374 ThaliTest[246:72376] client: found peer: 1453288759388.2419.HeaFFg==
2016-01-20 12:19:20.375 ThaliTest[246:72609] jxcore: connect 1453288759388.2419.HeaFFg==
2016-01-20 12:19:20.376 ThaliTest[246:72609] client session: connect
,2016-01-20 12:19:20.376 ThaliTest[246:72609] client session: stateChange:0->1 1453288759388.2419.HeaFFg==
,2016-01-20 12:19:24.243 ThaliTest[246:73107] server session: connected
,2016-01-20 12:19:24.243 ThaliTest[246:73107] server session: stateChange:1->2 1453288759388.2419
,2016-01-20 12:19:24.257 ThaliTest[246:72376] server relay: socket disconnected
,2016-01-20 12:19:24.258 ThaliTest[246:72376] server relay: 0x172bb310 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ref,used} 
,2016-01-20 12:19:24.320 ThaliTest[246:73151] server session: not connected 1453288759388.2419
,2016-01-20 12:19:25.171 ThaliTest[246:73151] client session: connected
2016-01-20 12:19:25.171 ThaliTest[246:73151] client session: stateChange:1->2 1453288759388.2419.HeaFFg==
,2016-01-20 12:19:25.290 ThaliTest[246:73108] client session: fireConnectCallback: 1453288759388.2419.HeaFFg==
2016-01-20 12:19:25.295 ThaliTest[246:73108] jxcore: connect: success
ok 79 Should be able to connect without error

ok 80 Port should be within range

,2016-01-20 12:19:25.298 ThaliTest[246:72609] jxcore: connect 1453288759388.2419.HeaFFg==
2016-01-20 12:19:25.299 ThaliTest[246:72609] client: already connect(ing/ed) to 1453288759388.2419.HeaFFg==
2016-01-20 12:19:25.299 ThaliTest[246:72609] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect

2016-01-20 12:19:25.304 ThaliTest[246:72609] jxcore: disconnect
2016-01-20 12:19:25.304 ThaliTest[246:72609] client session: disconnectFromPeer: 1453288759388.2419.HeaFFg==
2016-01-20 12:19:25.304 ThaliTest[246:72609] client session: disconnect
2016-01-20 12:19:25.305 ThaliTest[246:72609] client session: stateChange:2->0 1453288759388.2419.HeaFFg==
,2016-01-20 12:19:25.318 ThaliTest[246:72609] jxcore: disconnect: success
ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-20 12:19:25.501 ThaliTest[246:72609] jxcore: stopBroadcasting
2016-01-20 12:19:25.502 ThaliTest[246:72609] THEMultipeerSession stopping peer
2016-01-20 12:19:25.502 ThaliTest[246:72609] multipeer session: stop timer
2016-01-20 12:19:25.503 Thali,Test[246:72609] server session: disconnect
2016-01-20 12:19:25.503 ThaliTest[246:72609] server session: stateChange:2->0 1453288759388.2419
2016-01-20 12:19:25.504 ThaliTest[246:72609] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-20 12:19:41.510 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:19:41.514 ThaliTest[246:72609] server: starting 1453288781510.246.N3ukbw==
2016-01-20 12:19:41.515 ThaliTest[246:72609] multipeer session: start timer: 0x172b5c00
2016-01-20 12:19:41.515 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288781510.246
2016-01-20 12:19:41.515 ThaliTest[246:72609] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-20 12:19:43.116 ThaliTest[246:72376] multipeer session: reset timer
2016-01-20 12:19:43.116 ThaliTest[246:72376] multipeer session: stop timer
2016-01-20 12:19:43.117 ThaliTest[246:72376] multipeer session: start timer: 0x172b5c00
2016-01-20 12:,19:43.117 ThaliTest[246:72376] server session: connect
2016-01-20 12:19:43.117 ThaliTest[246:72376] server session: stateChange:0->1 1453288781606.2419
,2016-01-20 12:19:43.127 ThaliTest[246:72376] server: accepting invitation 1453288781606.2419
,2016-01-20 12:19:43.129 ThaliTest[246:72376] client: found peer: 1453288781606.2419.rEjssQ==
2016-01-20 12:19:43.135 ThaliTest[246:72609] jxcore: connect 1453288781606.2419.rEjssQ==
2016-01-20 12:19:43.135 ThaliTest[246:72609] client session: connect
2016-01-20 12:19:43.135 ThaliTest[246:72609] client session: stateChange:0->1 1453288781606.2419.rEjssQ==
,2016-01-20 12:19:48.294 ThaliTest[246:73201] server session: connected
,2016-01-20 12:19:48.295 ThaliTest[246:73201] server session: stateChange:1->2 1453288781606.2419
,2016-01-20 12:19:48.303 ThaliTest[246:72376] server relay: socket disconnected
,2016-01-20 12:19:48.304 ThaliTest[246:72376] server relay: 0x1645f170 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-20 12:19:48.369 ThaliTest[246:73216] server session: not connected 1453288781606.2419
,2016-01-20 12:19:48.689 ThaliTest[246:73216] client session: connected
2016-01-20 12:19:48.689 ThaliTest[246:73216] client session: stateChange:1->2 1453288781606.2419.rEjssQ==
,2016-01-20 12:19:48.745 ThaliTest[246:73200] client session: fireConnectCallback: 1453288781606.2419.rEjssQ==
2016-01-20 12:19:48.745 ThaliTest[246:73200] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

,2016-01-20 12:19:48.749 ThaliTest[246:72609] jxcore: disconnect
2016-01-20 12:19:48.750 ThaliTest[246:72609] client session: disconnectFromPeer: 1453288781606.2419.rEjssQ==
,2016-01-20 12:19:48.750 ThaliTest[246:72609] client session: disconnect
,2016-01-20 12:19:48.751 ThaliTest[246:72609] client session: stateChange:2->0 1453288781606.2419.rEjssQ==
,2016-01-20 12:19:48.762 ThaliTest[246:72609] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

2016-01-20 12:19:48.764 ThaliTest[246:72609] jxcore: disconnect
2016-01-20 12:19:48.764 ThaliTest[246:72609] jxcore: disconnect: fail
ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-20 12:19:49.152 ThaliTest[246:72609] jxcore: stopBroadcasting
2016-01-20 12:19:49.152 ThaliTest[246:72609] THEMultipeerSession stopping peer
2016-01-20 12:19:49.153 ThaliTest[246:72609] multipeer session: stop timer
2016-01-20 12:19:49.153 Thali,Test[246:72609] server session: disconnect
2016-01-20 12:19:49.153 ThaliTest[246:72609] server session: stateChange:2->0 1453288781606.2419
2016-01-20 12:19:49.154 ThaliTest[246:72609] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 49592

,2016-01-20 12:20:06.901 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:20:06.902 ThaliTest[246:72609] server: starting 1453288806901.246.KGpDfQ==
2016-01-20 12:20:06.903 ThaliTest[246:72609] multipeer session: start timer: 0x1729b930
2016-01-20 12:20:06.903 ThaliTest[246:72609] THEMultipeerSession initialized peer 1453288806901.246
,2016-01-20 12:20:06.903 ThaliTest[246:72609] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error

,2016-01-20 12:20:06.908 ThaliTest[246:72376] client: found peer: 1453288791925.2419.nu+pBg==
2016-01-20 12:20:06.909 ThaliTest[246:72609] jxcore: connect 1453288791925.2419.nu+pBg==
2016-01-20 12:20:06.910 ThaliTest[246:72609] client session: connect
2016-01-20 12:20:06.910 ThaliTest[246:72609] client session: stateChange:0->1 1453288791925.2419.nu+pBg==
,2016-01-20 12:20:07.900 ThaliTest[246:72376] multipeer session: reset timer
2016-01-20 12:20:07.901 ThaliTest[246:72376] multipeer session: stop timer
2016-01-20 12:20:07.901 ThaliTest[246:72376] multipeer session: start timer: 0x1729b930
,2016-01-20 12:20:07.902 ThaliTest[246:72376] server session: connect
2016-01-20 12:20:07.903 ThaliTest[246:72376] server session: stateChange:0->1 1453288791925.2419
,2016-01-20 12:20:07.913 ThaliTest[246:72376] server: accepting invitation 1453288791925.2419
,2016-01-20 12:20:11.161 ThaliTest[246:73273] client session: connected
,2016-01-20 12:20:11.162 ThaliTest[246:73273] client session: stateChange:1->2 1453288791925.2419.nu+pBg==
,2016-01-20 12:20:11.178 ThaliTest[246:73287] client session: fireConnectCallback: 1453288791925.2419.nu+pBg==
,2016-01-20 12:20:11.179 ThaliTest[246:73287] jxcore: connect: success
,ok 89 Should be able to connect without error

,ok 90 Port should be within range

,2016-01-20 12:20:11.187 ThaliTest[246:72376] client: relay established
2016-01-20 12:20:11.187 ThaliTest[246:72376] client: new accepted socket: 0x1648e520
,data in 2190
,
,data in 8760
,
,data in 13140

,data in 17520

,data in 39420

,data in 52560

,data in 63510

,data in 76650

,data in 79935

,data in 89790

,data in 109500

,data in 128115

,data in 131072

,ok 91 the test messages should be equal

,2016-01-20 12:20:11.551 ThaliTest[246:72609] jxcore: disconnect
2016-01-20 12:20:11.551 ThaliTest[246:72609] client session: disconnectFromPeer: 1453288791925.2419.nu+pBg==
2016-01-20 12:20:11.552 ThaliTest[246:72609] client session: disconnect
2016-01-20 12:20:11.552 ThaliTest[246:72609] client session: stateChange:2->0 1453288791925.2419.nu+pBg==
,2016-01-20 12:20:11.561 ThaliTest[246:72609] jxcore: disconnect: success
ok 92 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

# setup

,2016-01-20 12:20:11.778 ThaliTest[246:73287] server session: connected
2016-01-20 12:20:11.778 ThaliTest[246:73287] server session: stateChange:1->2 1453288791925.2419
,2016-01-20 12:20:11.822 ThaliTest[246:72376] server relay: connected (to port: 49592)
,2016-01-20 12:20:12.278 ThaliTest[246:73275] server session: not connected 1453288791925.2419
,2016-01-20 12:20:17.529 ThaliTest[246:72376] client: lost peer: 1453288791925.2419.nu+pBg==
2016-01-20 12:20:17.529 ThaliTest[246:72376] client session: onPeerLost: 1453288791925.2419.nu+pBg==
,calling stopBroadcasting

,2016-01-20 12:20:23.756 ThaliTest[246:72609] jxcore: stopBroadcasting
2016-01-20 12:20:23.756 ThaliTest[246:72609] THEMultipeerSession stopping peer
2016-01-20 12:20:23.757 ThaliTest[246:72609] multipeer session: stop timer
2016-01-20 12:20:23.757 ThaliTest[246:72609] server session: disconnect
2016-01-20 12:20:23.757 ThaliTest[246:72609] server session: stateChange:2->0 1453288791925.2419
,2016-01-20 12:20:23.828 ThaliTest[246:72609] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 49598

,2016-01-20 12:20:25.305 ThaliTest[246:72609] jxcore: startBroadcasting
,2016-01-20 12:20:25.308 ThaliTest[246:72609] server: starting 1453288825304.246.0OE3Cw==
2016-01-20 12:20:25.309 ThaliTest[246:72609] multipeer session: start timer: 0x172974b0
2016-01-20 12:20:25.310 ThaliTest[246:72609] THEMultipeerSession initialized ,peer 1453288825304.246
2016-01-20 12:20:25.310 ThaliTest[246:72609] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error

,2016-01-20 12:20:26.620 ThaliTest[246:72376] multipeer session: reset timer
2016-01-20 12:20:26.621 ThaliTest[246:72376] multipeer session: stop timer
2016-01-20 12:20:26.621 ThaliTest[246:72376] multipeer session: start timer: 0x172974b0
2016-01-20 12:,20:26.621 ThaliTest[246:72376] server session: connect
2016-01-20 12:20:26.622 ThaliTest[246:72376] server session: stateChange:0->1 1453288824790.2419
,2016-01-20 12:20:26.632 ThaliTest[246:72376] server: accepting invitation 1453288824790.2419
,2016-01-20 12:20:26.695 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
[{"peerIdentifier":"1453288824790.2419.1bE3uA==","peerName":"(null)","peerAvailable":true}]

2016-01-20 12:20:26.697 ThaliTest[246:72609] jxcore: connect 145328,8824790.2419.1bE3uA==
2016-01-20 12:20:26.697 ThaliTest[246:72609] client session: connect
2016-01-20 12:20:26.698 ThaliTest[246:72609] client session: stateChange:0->1 1453288824790.2419.1bE3uA==
,2016-01-20 12:20:31.285 ThaliTest[246:73322] server session: connected
,2016-01-20 12:20:31.286 ThaliTest[246:73322] server session: stateChange:1->2 1453288824790.2419
,2016-01-20 12:20:31.292 ThaliTest[246:72376] server relay: connected (to port: 49598)
,2016-01-20 12:20:31.419 ThaliTest[246:73324] server session: not connected 1453288824790.2419
,2016-01-20 12:20:31.674 ThaliTest[246:72376] multipeer session: reset timer
2016-01-20 12:20:31.675 ThaliTest[246:72376] multipeer session: stop timer
2016-01-20 12:20:31.675 ThaliTest[246:72376] multipeer session: start timer: 0x172974b0
2016-01-20 12:20:31.676 ThaliTest[246:72376] server: disconnecting to refresh session (1453288824790.2419)
2016-01-20 12:20:31.676 ThaliTest[246:72376] server session: disconnect
,2016-01-20 12:20:31.676 ThaliTest[246:72376] server session: stateChange:2->0 1453288824790.2419
,2016-01-20 12:20:31.684 ThaliTest[246:72376] server session: connect
2016-01-20 12:20:31.685 ThaliTest[246:72376] server session: stateChange:0->1 1453288824790.2419
,2016-01-20 12:20:31.700 ThaliTest[246:72376] server: accepting invitation 1453288824790.2419
,2016-01-20 12:20:31.756 ThaliTest[246:73274] client session: connected
2016-01-20 12:20:31.757 ThaliTest[246:73274] client session: stateChange:1->2 1453288824790.2419.1bE3uA==
2016-01-20 12:20:31.765 ThaliTest[246:73274] client session: fireConnectCallback: 1453288824790.2419.1bE3uA==
2016-01-20 12:20:31.765 ThaliTest[246:73274] jxcore: connect: success
ok 94 Should be able to connect without error

ok 95 Port should be within range

ok 96 First connect should succeed

,2016-01-20 12:20:31.805 ThaliTest[246:72376] client: relay established
2016-01-20 12:20:31.805 ThaliTest[246:72376] client: new accepted socket: 0x164b8030
,ok 97 the test messages should be equal

,ok 98 First send should succeed

,2016-01-20 12:20:31.881 ThaliTest[246:72376] client: socket closed
,2016-01-20 12:20:31.882 ThaliTest[246:72376] client relay: socket disconnected
,2016-01-20 12:20:31.882 ThaliTest[246:72376] client relay: 0x164b8030 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-20 12:20:31.883 ThaliTest[246:72376] client session: socket closed: 1453288824790.2419.1bE3uA==
2016-01-20 12:20:31.883 ThaliTest[246:72376] client session: onLinkFailure: 1453288824790.2419.1bE3uA==
,2016-01-20 12:20:31.883 ThaliTest[246:72376] client session: disconnect
,2016-01-20 12:20:31.883 ThaliTest[246:72376] client session: stateChange:2->0 1453288824790.2419.1bE3uA==
,2016-01-20 12:20:31.949 ThaliTest[246:72376] client session: fireConnectionErrorEvent: 1453288824790.2419.1bE3uA==
,2016-01-20 12:20:31.951 ThaliTest[246:72609] jxcore: connect 1453288824790.2419.1bE3uA==
2016-01-20 12:20:31.951 ThaliTest[246:72609] client session: connect
2016-01-20 12:20:31.951 ThaliTest[246:72609] client session: stateChange:0->1 1453288824790.2419.1bE3uA==
,appEnteredForeground wasn't registered

,2016-01-20 12:20:41.913 ThaliTest[246:73275] server session: not connected 1453288824790.2419
,2016-01-20 12:20:51.263 ThaliTest[246:73275] client session: not connected 1453288824790.2419.1bE3uA==
2016-01-20 12:20:51.263 ThaliTest[246:73275] client session: onLinkFailure: 1453288824790.2419.1bE3uA==
2016-01-20 12:20:51.263 ThaliTest[246:73275] cl,ient session: disconnect
2016-01-20 12:20:51.263 ThaliTest[246:73275] client session: stateChange:1->0 1453288824790.2419.1bE3uA==
,2016-01-20 12:20:51.276 ThaliTest[246:73275] client session: fireConnectCallback: 1453288824790.2419.1bE3uA==
2016-01-20 12:20:51.277 ThaliTest[246:73275] jxcore: connect: fail: Peer disconnected
,2016-01-20 12:20:52.279 ThaliTest[246:72609] jxcore: connect 1453288824790.2419.1bE3uA==
2016-01-20 12:20:52.280 ThaliTest[246:72609] client session: connect
2016-01-20 12:20:52.280 ThaliTest[246:72609] client session: stateChange:0->1 1453288824790.2419,.1bE3uA==
,2016-01-20 12:21:01.677 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:21:01.745 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
,2016-01-20 12:21:25.191 ThaliTest[246:73618] client session: not connected 1453288824790.2419.1bE3uA==
2016-01-20 12:21:25.191 ThaliTest[246:73618] client session: onLinkFailure: 1453288824790.2419.1bE3uA==
2016-01-20 12:21:25.191 ThaliTest[246:73618] cl,ient session: disconnect
2016-01-20 12:21:25.192 ThaliTest[246:73618] client session: stateChange:1->0 1453288824790.2419.1bE3uA==
2016-01-20 12:21:25.192 ThaliTest[246:73618] client session: fireConnectCallback: 1453288824790.2419.1bE3uA==
2016-01-20 1,2:21:25.192 ThaliTest[246:73618] jxcore: connect: fail: Peer disconnected
,2016-01-20 12:21:26.200 ThaliTest[246:72609] jxcore: connect 1453288824790.2419.1bE3uA==
2016-01-20 12:21:26.201 ThaliTest[246:72609] client session: connect
2016-01-20 12:21:26.201 ThaliTest[246:72609] client session: stateChange:0->1 1453288824790.2419.1bE3uA==
,2016-01-20 12:21:31.677 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:21:31.714 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
,2016-01-20 12:21:53.041 ThaliTest[246:72376] multipeer session: reset timer
2016-01-20 12:21:53.041 ThaliTest[246:72376] multipeer session: stop timer
2016-01-20 12:21:53.041 ThaliTest[246:72376] multipeer session: start timer: 0x172974b0
2016-01-20 12:,21:53.042 ThaliTest[246:72376] server: disconnecting to refresh session (1453288824790.2419)
2016-01-20 12:21:53.042 ThaliTest[246:72376] server session: disconnect
2016-01-20 12:21:53.042 ThaliTest[246:72376] server session: stateChange:1->0 1453288824790.2419
,2016-01-20 12:21:53.097 ThaliTest[246:72376] server session: connect
2016-01-20 12:21:53.097 ThaliTest[246:72376] server session: stateChange:0->1 1453288824790.2419
,2016-01-20 12:21:53.106 ThaliTest[246:72376] server: accepting invitation 1453288824790.2419
,2016-01-20 12:21:56.661 ThaliTest[246:73702] server session: connected
2016-01-20 12:21:56.662 ThaliTest[246:73702] server session: stateChange:1->2 1453288824790.2419
2016-01-20 12:21:56.665 ThaliTest[246:72376] server relay: connected (to port: 49598)
,2016-01-20 12:21:58.980 ThaliTest[246:73702] client session: not connected 1453288824790.2419.1bE3uA==
2016-01-20 12:21:58.981 ThaliTest[246:73702] client session: onLinkFailure: 1453288824790.2419.1bE3uA==
2016-01-20 12:21:58.981 ThaliTest[246:73702] cl,ient session: disconnect
2016-01-20 12:21:58.981 ThaliTest[246:73702] client session: stateChange:1->0 1453288824790.2419.1bE3uA==
2016-01-20 12:21:58.982 ThaliTest[246:73702] client session: fireConnectCallback: 1453288824790.2419.1bE3uA==
2016-01-20 1,2:21:58.982 ThaliTest[246:73702] jxcore: connect: fail: Peer disconnected
,2016-01-20 12:21:59.986 ThaliTest[246:72609] jxcore: connect 1453288824790.2419.1bE3uA==
2016-01-20 12:21:59.987 ThaliTest[246:72609] client session: connect
2016-01-20 12:21:59.987 ThaliTest[246:72609] client session: stateChange:0->1 1453288824790.2419.1bE3uA==
,2016-01-20 12:22:03.538 ThaliTest[246:73704] client session: connected
,2016-01-20 12:22:03.539 ThaliTest[246:73704] client session: stateChange:1->2 1453288824790.2419.1bE3uA==
,2016-01-20 12:22:03.544 ThaliTest[246:73704] client session: fireConnectCallback: 1453288824790.2419.1bE3uA==
2016-01-20 12:22:03.544 ThaliTest[246:73704] jxcore: connect: success
ok 99 Should be able to connect without error

ok 100 Port should be wit,hin range

ok 101 Second connect should succeed

,2016-01-20 12:22:03.580 ThaliTest[246:72376] client: relay established
2016-01-20 12:22:03.580 ThaliTest[246:72376] client: new accepted socket: 0x16396c70
,ok 102 the test messages should be equal

,ok 103 Second send should succeed

,# setup

,2016-01-20 12:22:03.686 ThaliTest[246:72376] client: socket closed
2016-01-20 12:22:03.686 ThaliTest[246:72376] client relay: socket disconnected
2016-01-20 12:22:03.686 ThaliTest[246:72376] client relay: 0x16396c70 disconnected with error Error Domain=G,CDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-20 12:22:03.687 ThaliTest[246:72376] client session: socket closed: 1453288824790.2419.1bE3uA==
2016-01-20 12:22:03.687, ThaliTest[246:72376] client session: onLinkFailure: 1453288824790.2419.1bE3uA==
2016-01-20 12:22:03.687 ThaliTest[246:72376] client session: disconnect
2016-01-20 12:22:03.687 ThaliTest[246:72376] client session: stateChange:2->0 1453288824790.2419.1bE3,uA==
,2016-01-20 12:22:03.698 ThaliTest[246:72376] client session: fireConnectionErrorEvent: 1453288824790.2419.1bE3uA==
,2016-01-20 12:22:07.810 ThaliTest[246:73702] server session: not connected 1453288824790.2419
,2016-01-20 12:22:23.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:22:53.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:22:53.070 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
,2016-01-20 12:23:23.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:23:53.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:23:53.069 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
,2016-01-20 12:24:23.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:24:23.070 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
,2016-01-20 12:24:53.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:24:53.070 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
,2016-01-20 12:25:23.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:25:23.072 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
,2016-01-20 12:25:53.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:25:53.070 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
,2016-01-20 12:26:23.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:26:23.072 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
,2016-01-20 12:26:53.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:27:23.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:27:23.071 ThaliTest[246:72376] client: found peer: 1453288824790.2419.1bE3uA==
,2016-01-20 12:27:36.346 ThaliTest[246:72376] client: lost peer: 1453288824790.2419.1bE3uA==
2016-01-20 12:27:36.347 ThaliTest[246:72376] client session: onPeerLost: 1453288824790.2419.1bE3uA==
[{"peerIdentifier":"1453288824790.2419.1bE3uA==","peerName":",(null)","peerAvailable":false}]

,2016-01-20 12:27:53.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:28:23.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:28:53.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:29:23.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:29:53.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:30:23.043 ThaliTest[246:72376] multipeer session: restart
,2016-01-20 12:30:53.043 ThaliTest[246:72376] multipeer session: restart

```
