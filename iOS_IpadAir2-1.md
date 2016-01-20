#### Test 564496606be5677_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/564496606be5677/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/EF15AEB9-E815-4886-A34E-7E369D0E7AD2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/EF15AEB9-E815-4886-A34E-7E369D0E7AD2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/564496606be5677/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/564496606be5677/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/929ABE9E-87E4-437C-8377-C4CEB8102F68/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59009"
,(lldb)     command script import "/tmp/EF15AEB9-E815-4886-A34E-7E369D0E7AD2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-20 12:13:36.448 ThaliTest[2419:5206412] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/07904C23-BD5E-4D24-A3BE-2BE5507667A5/Library/Cookies/Cookies.binarycookies
,2016-01-20 12:13:36.690 ThaliTest[2419:5206412] Apache Cordova native platform version 3.9.2 is starting.
2016-01-20 12:13:36.690 ThaliTest[2419:5206412] Multi-tasking -> Device: YES, App: YES
,2016-01-20 12:13:36.696 ThaliTest[2419:5206412] Unlimited access to network resources
,2016-01-20 12:13:36.702 ThaliTest[2419:5206412] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-20 12:13:40.821 ThaliTest[2419:5206412] Resetting plugins due to page load.
,2016-01-20 12:13:42.242 ThaliTest[2419:5206412] Finished load of: file:///var/mobile/Containers/Bundle/Application/929ABE9E-87E4-437C-8377-C4CEB8102F68/ThaliTest.app/www/index.html
,2016-01-20 12:13:42.390 ThaliTest[2419:5206412] JXcore Cordova plugin initializing
,2016-01-20 12:13:42.392 ThaliTest[2419:5206578] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/929ABE9E-87E4-437C-8377-C4CEB8102F68/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/929ABE9E-87E4-437C-8377-C4CEB8102F68/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/929ABE9E-87E4-437C-8377-C4CEB8102F68/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/929ABE9E-87E4-437C-8377-C4CEB8102F68/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/929ABE9E-87E4-437C-8377-C4CEB8102F68/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/929ABE9E-87E4-437C-8377-C4CEB8102F68/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/929ABE9E-87E4-437C-8377-C4CEB8102F68/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 17 should be equal

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

ok 27 should be equal

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

ok 33 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 34 should be equal

,ok 35 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 36 should be equal

,ok 37 should be equal

ok 38 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 39 should be equal

ok 40 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-20 12:19:08.921 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:08.930 ThaliTest[2419:5206578] server: starting 1453288748920.2419.iI9UVQ==
,2016-01-20 12:19:08.930 ThaliTest[2419:5206578] multipeer session: start timer: 0x184b7d50
2016-01-20 12:19:08.930 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288748920.2419
,2016-01-20 12:19:08.932 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error

2016-01-20 12:19:08.934 ThaliTest[2419:5206578] jxcore: stopBroadcasting
2016-01-20 12:19:08.934 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:19:08.934 ThaliTest[2419:5206578] multipeer session: stop timer
2016-01-20 12:19:08.935 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:08.936 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:08.938 ThaliTest[2419:5206578] server: starting 1453288748936.2419.Ty8ldw==
,2016-01-20 12:19:08.938 ThaliTest[2419:5206578] multipeer session: start timer: 0x17e03df0
,2016-01-20 12:19:08.938 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288748936.2419
2016-01-20 12:19:08.939 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error

,2016-01-20 12:19:08.940 ThaliTest[2419:5206578] jxcore: stopBroadcasting
,2016-01-20 12:19:08.940 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
,2016-01-20 12:19:08.940 ThaliTest[2419:5206578] multipeer session: stop timer
,2016-01-20 12:19:08.943 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:08.944 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:08.945 ThaliTest[2419:5206578] server: starting 1453288748943.2419.KNa9eQ==
,2016-01-20 12:19:08.945 ThaliTest[2419:5206578] multipeer session: start timer: 0x180184d0
2016-01-20 12:19:08.945 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288748943.2419
2016-01-20 12:19:08.945 ThaliTest[2419:5206578] jxcore: sta,rtBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error

,2016-01-20 12:19:08.946 ThaliTest[2419:5206578] jxcore: stopBroadcasting
2016-01-20 12:19:08.946 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:19:08.946 ThaliTest[2419:5206578] multipeer session: stop timer
2016-01-20 12:19:08.947 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error

,2016-01-20 12:19:08.948 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:08.950 ThaliTest[2419:5206578] server: starting 1453288748947.2419.kh9ARA==
2016-01-20 12:19:08.950 ThaliTest[2419:5206578] multipeer session: start timer: 0x186351f0
2016-01-20 12:19:08.950 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288748947.2419
2016-01-20 12:19:08.950 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error

,2016-01-20 12:19:08.951 ThaliTest[2419:5206578] jxcore: stopBroadcasting
2016-01-20 12:19:08.952 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:19:08.952 ThaliTest[2419:5206578] multipeer session: stop timer
2016-01-20 12:19:08.952 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error

2016-01-20 12:19:08.953 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:08.956 ThaliTest[2419:5206578] server: starting 1453288748953.2419.ZnDhuw==
2016-01-20 12:19:08.956 ThaliTest[2419:5206578] multipeer session: start timer: 0x184c1b40
2016-01-20 12:19:08.956 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288748953.2419
2016-01-20 12:19:08.957 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error

2016-01-20 12:19:08.958 ThaliTest[2419:5206578] jxcore: stopBroadcasting
,2016-01-20 12:19:08.958 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:19:08.959 ThaliTest[2419:5206578] multipeer session: stop timer
2016-01-20 12:19:08.959 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error

2016-01-20 12:19:08.961 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:08.962 ThaliTest[2419:5206578] server: starting 1453288748960.2419.O/7V7g==
2016-01-20 12:19:08.962 ThaliTest[2419:5206578] multipeer session: start timer: 0x18011cc0
2016-01-20 12:19:08.962 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288748960.2419
,2016-01-20 12:19:08.964 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error

,2016-01-20 12:19:08.965 ThaliTest[2419:5206578] jxcore: stopBroadcasting
,2016-01-20 12:19:08.966 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
,2016-01-20 12:19:08.966 ThaliTest[2419:5206578] multipeer session: stop timer
2016-01-20 12:19:08.966 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error

2016-01-20 12:19:08.967 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:08.968 ThaliTest[2419:5206578] server: starting 1453288748967.2419.WGvgiw==
,2016-01-20 12:19:08.969 ThaliTest[2419:5206578] multipeer session: start timer: 0x18637880
2016-01-20 12:19:08.969 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288748967.2419
2016-01-20 12:19:08.969 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error

2016-01-20 12:19:08.970 ThaliTest[2419:5206578] jxcore: stopBroadcasting
2016-01-20 12:19:08.970 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:19:08.970 ThaliTest[2419:5206578] multipeer session: stop timer
2016-01-20 12:19:08.970 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error

2016-01-20 12:19:08.970 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:08.974 ThaliTest[2419:5206578] server: starting 1453288748970.2419.3dCR2A==
2016-01-20 12:19:08.974 ThaliTest[2419:5206578] multipeer session: start timer: 0x184c1150
2016-01-20 12:19:08.974 ThaliTest[2419:5206578] THEMultipeerSession in,itialized peer 1453288748970.2419
2016-01-20 12:19:08.974 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error

2016-01-20 12:19:08.975 ThaliTest[2419:5206578] jxcore: stopBroadcasting
,2016-01-20 12:19:08.975 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:19:08.976 ThaliTest[2419:5206578] multipeer session: stop timer
2016-01-20 12:19:08.976 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
ok 60 Shoul,d be able to call stopBroadcasting without error

2016-01-20 12:19:08.977 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:08.980 ThaliTest[2419:5206578] server: starting 1453288748977.2419.a+5oDg==
,2016-01-20 12:19:08.981 ThaliTest[2419:5206578] multipeer session: start timer: 0x186391b0
2016-01-20 12:19:08.981 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288748977.2419
2016-01-20 12:19:08.981 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error

2016-01-20 12:19:08.982 ThaliTest[2419:5206578] jxcore: stopBroadcasting
2016-01-20 12:19:08.982 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:19:08.983 ThaliTest[2419:5206578] multipeer session: stop timer
2016-01-20 12:19:08.983 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error

2016-01-20 12:19:08.984 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:08.985 ThaliTest[2419:5206578] server: starting 1453288748983.2419.arzwzw==
2016-01-20 12:19:08.985 ThaliTest[2419:5206578] multipeer session: start timer: 0x186366d0
2016-01-20 12:19:08.985 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288748983.2419
2016-01-20 12:19:08.985 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error

2016-01-20 12:19:08.986 ThaliTest[2419:5206578] jxcore: stopBroadcasting
,2016-01-20 12:19:08.986 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:19:08.986 ThaliTest[2419:5206578] multipeer session: stop timer
2016-01-20 12:19:08.986 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
ok 64 Shoul,d be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-20 12:19:09.225 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:09.226 ThaliTest[2419:5206578] server: starting 1453288749225.2419.7y7C8A==
,2016-01-20 12:19:09.227 ThaliTest[2419:5206578] multipeer session: start timer: 0x18639a60
,2016-01-20 12:19:09.229 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288749225.2419
,2016-01-20 12:19:09.230 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

,2016-01-20 12:19:09.231 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:09.231 ThaliTest[2419:5206578] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

,2016-01-20 12:19:09.233 ThaliTest[2419:5206578] jxcore: stopBroadcasting
,2016-01-20 12:19:09.233 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
,2016-01-20 12:19:09.233 ThaliTest[2419:5206578] multipeer session: stop timer
,2016-01-20 12:19:09.235 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-20 12:19:09.323 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:09.325 ThaliTest[2419:5206578] server: starting 1453288749323.2419.5aCxSA==
,2016-01-20 12:19:09.325 ThaliTest[2419:5206578] multipeer session: start timer: 0x18050730
,2016-01-20 12:19:09.326 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288749323.2419
,2016-01-20 12:19:09.327 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-20 12:19:09.329 ThaliTest[2419:5206578] jxcore: connect foobar
,2016-01-20 12:19:09.329 ThaliTest[2419:5206578] client: unknown peer foobar
,2016-01-20 12:19:09.329 ThaliTest[2419:5206578] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer

2016-01-20 12:19:09.331 ThaliTest[2419:5206578] jxcore: stopBroadcasting
,2016-01-20 12:19:09.331 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
,2016-01-20 12:19:09.332 ThaliTest[2419:5206578] multipeer session: stop timer
,2016-01-20 12:19:09.333 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-20 12:19:09.408 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:09.409 ThaliTest[2419:5206578] server: starting 1453288749408.2419.NnECRA==
,2016-01-20 12:19:09.410 ThaliTest[2419:5206578] multipeer session: start timer: 0x1863c800
,2016-01-20 12:19:09.411 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288749408.2419
,2016-01-20 12:19:09.412 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-01-20 12:19:09.413 ThaliTest[2419:5206578] jxcore: disconnect
,2016-01-20 12:19:09.414 ThaliTest[2419:5206578] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 

2016-01-20 12:19:09.415 ThaliTest[2419:5206578] jxcore: stopBroadcasting
2016-01-20 12:19:09.415 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:19:09.415 ThaliTest[2419:5206578] multipeer session: stop timer
,2016-01-20 12:19:09.416 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-20 12:19:10.367 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:10.378 ThaliTest[2419:5206578] server: starting 1453288750367.2419.yCQHqg==
2016-01-20 12:19:10.379 ThaliTest[2419:5206578] multipeer session: start timer: 0x184995f0
2016-01-20 12:19:10.379 ThaliTest[2419:5206578] THEMultipeerSession in,itialized peer 1453288750367.2419
2016-01-20 12:19:10.379 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-01-20 12:19:11.715 ThaliTest[2419:5206412] client: found peer: 1453288750313.246.SLES3A==
2016-01-20 12:19:11.716 ThaliTest[2419:5206578] jxcore: connect 1453288750313.246.SLES3A==
,2016-01-20 12:19:11.717 ThaliTest[2419:5206578] client session: connect
2016-01-20 12:19:11.717 ThaliTest[2419:5206578] client session: stateChange:0->1 1453288750313.246.SLES3A==
,2016-01-20 12:19:11.818 ThaliTest[2419:5206412] multipeer session: reset timer
2016-01-20 12:19:11.818 ThaliTest[2419:5206412] multipeer session: stop timer
2016-01-20 12:19:11.818 ThaliTest[2419:5206412] multipeer session: start timer: 0x184995f0
2016-01-20 12:19:11.818 ThaliTest[2419:5206412] server session: connect
2016-01-20 12:19:11.818 ThaliTest[2419:5206412] server session: stateChange:0->1 1453288750313.246
,2016-01-20 12:19:11.821 ThaliTest[2419:5206412] server: accepting invitation 1453288750313.246
,2016-01-20 12:19:15.816 ThaliTest[2419:5207227] server session: connected
2016-01-20 12:19:15.816 ThaliTest[2419:5207227] server session: stateChange:1->2 1453288750313.246
,2016-01-20 12:19:15.823 ThaliTest[2419:5206412] server relay: socket disconnected
2016-01-20 12:19:15.823 ThaliTest[2419:5206412] server relay: 0x1806f8f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-20 12:19:15.869 ThaliTest[2419:5207227] server session: not connected 1453288750313.246
,2016-01-20 12:19:16.540 ThaliTest[2419:5207229] client session: connected
2016-01-20 12:19:16.540 ThaliTest[2419:5207229] client session: stateChange:1->2 1453288750313.246.SLES3A==
,2016-01-20 12:19:16.563 ThaliTest[2419:5207227] client session: fireConnectCallback: 1453288750313.246.SLES3A==
2016-01-20 12:19:16.563 ThaliTest[2419:5207227] jxcore: connect: success
,ok 75 Should be able to connect without error

,ok 76 Port should be within range

,2016-01-20 12:19:16.564 ThaliTest[2419:5206578] jxcore: disconnect
,2016-01-20 12:19:16.565 ThaliTest[2419:5206578] client session: disconnectFromPeer: 1453288750313.246.SLES3A==
,2016-01-20 12:19:16.565 ThaliTest[2419:5206578] client session: disconnect
,2016-01-20 12:19:16.565 ThaliTest[2419:5206578] client session: stateChange:2->0 1453288750313.246.SLES3A==
,2016-01-20 12:19:16.570 ThaliTest[2419:5206578] jxcore: disconnect: success
ok 77 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-20 12:19:17.215 ThaliTest[2419:5206578] jxcore: stopBroadcasting
2016-01-20 12:19:17.215 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
,2016-01-20 12:19:17.215 ThaliTest[2419:5206578] multipeer session: stop timer
,2016-01-20 12:19:17.216 ThaliTest[2419:5206578] server session: disconnect
2016-01-20 12:19:17.216 ThaliTest[2419:5206578] server session: stateChange:2->0 1453288750313.246
,2016-01-20 12:19:17.216 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-20 12:19:19.388 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:19.389 ThaliTest[2419:5206578] server: starting 1453288759388.2419.HeaFFg==
,2016-01-20 12:19:19.390 ThaliTest[2419:5206578] multipeer session: start timer: 0x180b6e10
2016-01-20 12:19:19.390 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288759388.2419
2016-01-20 12:19:19.390 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-20 12:19:19.421 ThaliTest[2419:5206412] client: found peer: 1453288758142.246.YEBrRw==
,2016-01-20 12:19:19.421 ThaliTest[2419:5206578] jxcore: connect 1453288758142.246.YEBrRw==
2016-01-20 12:19:19.422 ThaliTest[2419:5206578] client session: connect
2016-01-20 12:19:19.422 ThaliTest[2419:5206578] client session: stateChange:0->1 1453288758142.246.YEBrRw==
,2016-01-20 12:19:20.579 ThaliTest[2419:5206412] multipeer session: reset timer
2016-01-20 12:19:20.579 ThaliTest[2419:5206412] multipeer session: stop timer
2016-01-20 12:19:20.579 ThaliTest[2419:5206412] multipeer session: start timer: 0x180b6e10
2016-,01-20 12:19:20.579 ThaliTest[2419:5206412] server session: connect
2016-01-20 12:19:20.580 ThaliTest[2419:5206412] server session: stateChange:0->1 1453288758142.246
,2016-01-20 12:19:20.582 ThaliTest[2419:5206412] server: accepting invitation 1453288758142.246
,2016-01-20 12:19:24.334 ThaliTest[2419:5207230] client session: connected
2016-01-20 12:19:24.334 ThaliTest[2419:5207230] client session: stateChange:1->2 1453288758142.246.YEBrRw==
,2016-01-20 12:19:24.337 ThaliTest[2419:5207230] client session: fireConnectCallback: 1453288758142.246.YEBrRw==
2016-01-20 12:19:24.337 ThaliTest[2419:5207230] jxcore: connect: success
ok 79 Should be able to connect without error

,ok 80 Port should be within range

,2016-01-20 12:19:24.338 ThaliTest[2419:5206578] jxcore: connect 1453288758142.246.YEBrRw==
,2016-01-20 12:19:24.339 ThaliTest[2419:5206578] client: already connect(ing/ed) to 1453288758142.246.YEBrRw==
2016-01-20 12:19:24.339 ThaliTest[2419:5206578] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect

2016-01-20 12:19:24.340 ThaliTest[2419:5206578] jxcore: disconnect
,2016-01-20 12:19:24.340 ThaliTest[2419:5206578] client session: disconnectFromPeer: 1453288758142.246.YEBrRw==
2016-01-20 12:19:24.340 ThaliTest[2419:5206578] client session: disconnect
2016-01-20 12:19:24.341 ThaliTest[2419:5206578] client session: stateChange:2->0 1453288758142.246.YEBrRw==
,2016-01-20 12:19:24.401 ThaliTest[2419:5206578] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-20 12:19:25.322 ThaliTest[2419:5207229] server session: connected
2016-01-20 12:19:25.322 ThaliTest[2419:5207229] server session: stateChange:1->2 1453288758142.246
2016-01-20 12:19:25.325 ThaliTest[2419:5206412] server relay: socket disconnected
2016-01-20 12:19:25.326 ThaliTest[2419:5206412] server relay: 0x1849cdc0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-20 12:19:25.442 ThaliTest[2419:5207231] server session: not connected 1453288758142.246
,calling stopBroadcasting

,2016-01-20 12:19:25.661 ThaliTest[2419:5206578] jxcore: stopBroadcasting
2016-01-20 12:19:25.661 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
,2016-01-20 12:19:25.661 ThaliTest[2419:5206578] multipeer session: stop timer
,2016-01-20 12:19:25.662 ThaliTest[2419:5206578] server session: disconnect
2016-01-20 12:19:25.662 ThaliTest[2419:5206578] server session: stateChange:2->0 1453288758142.246
2016-01-20 12:19:25.662 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-20 12:19:41.606 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:41.615 ThaliTest[2419:5206578] server: starting 1453288781606.2419.rEjssQ==
2016-01-20 12:19:41.617 ThaliTest[2419:5206578] multipeer session: start timer: 0x186437e0
2016-01-20 12:19:41.617 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288781606.2419
2016-01-20 12:19:41.617 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-20 12:19:43.074 ThaliTest[2419:5206412] client: found peer: 1453288781510.246.N3ukbw==
2016-01-20 12:19:43.075 ThaliTest[2419:5206578] jxcore: connect 1453288781510.246.N3ukbw==
2016-01-20 12:19:43.075 ThaliTest[2419:5206578] client session: conn,ect
2016-01-20 12:19:43.075 ThaliTest[2419:5206578] client session: stateChange:0->1 1453288781510.246.N3ukbw==
,2016-01-20 12:19:43.363 ThaliTest[2419:5206412] multipeer session: reset timer
,2016-01-20 12:19:43.363 ThaliTest[2419:5206412] multipeer session: stop timer
2016-01-20 12:19:43.363 ThaliTest[2419:5206412] multipeer session: start timer: 0x186437e0
2016-01-20 12:19:43.363 ThaliTest[2419:5206412] server session: connect
,2016-01-20 12:19:43.364 ThaliTest[2419:5206412] server session: stateChange:0->1 1453288781510.246
,2016-01-20 12:19:43.366 ThaliTest[2419:5206412] server: accepting invitation 1453288781510.246
,2016-01-20 12:19:48.380 ThaliTest[2419:5207325] client session: connected
,2016-01-20 12:19:48.380 ThaliTest[2419:5207325] client session: stateChange:1->2 1453288781510.246.N3ukbw==
,2016-01-20 12:19:48.438 ThaliTest[2419:5207325] client session: fireConnectCallback: 1453288781510.246.N3ukbw==
2016-01-20 12:19:48.438 ThaliTest[2419:5207325] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-01-20 12:19:48.440 ThaliTest[2419:5206578] jxcore: disconnect
,2016-01-20 12:19:48.440 ThaliTest[2419:5206578] client session: disconnectFromPeer: 1453288781510.246.N3ukbw==
2016-01-20 12:19:48.440 ThaliTest[2419:5206578] client session: disconnect
,2016-01-20 12:19:48.440 ThaliTest[2419:5206578] client session: stateChange:2->0 1453288781510.246.N3ukbw==
,2016-01-20 12:19:48.443 ThaliTest[2419:5206578] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,2016-01-20 12:19:48.445 ThaliTest[2419:5206578] jxcore: disconnect
2016-01-20 12:19:48.445 ThaliTest[2419:5206578] jxcore: disconnect: fail
,ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-20 12:19:48.779 ThaliTest[2419:5207326] server session: connected
2016-01-20 12:19:48.779 ThaliTest[2419:5207326] server session: stateChange:1->2 1453288781510.246
,2016-01-20 12:19:48.784 ThaliTest[2419:5206412] server relay: socket disconnected
,2016-01-20 12:19:48.784 ThaliTest[2419:5206412] server relay: 0x180c1980 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting

,2016-01-20 12:19:49.268 ThaliTest[2419:5206578] jxcore: stopBroadcasting
,2016-01-20 12:19:49.268 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:19:49.268 ThaliTest[2419:5206578] multipeer session: stop timer
,2016-01-20 12:19:49.268 ThaliTest[2419:5206578] server session: disconnect
2016-01-20 12:19:49.270 ThaliTest[2419:5206578] server session: stateChange:2->0 1453288781510.246
,2016-01-20 12:19:49.275 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 55433

,2016-01-20 12:19:51.925 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:19:51.927 ThaliTest[2419:5206578] server: starting 1453288791925.2419.nu+pBg==
,2016-01-20 12:19:51.928 ThaliTest[2419:5206578] multipeer session: start timer: 0x18644c50
,2016-01-20 12:19:51.930 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288791925.2419
,2016-01-20 12:19:51.931 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error

,2016-01-20 12:20:07.212 ThaliTest[2419:5206412] multipeer session: reset timer
2016-01-20 12:20:07.212 ThaliTest[2419:5206412] multipeer session: stop timer
2016-01-20 12:20:07.212 ThaliTest[2419:5206412] multipeer session: start timer: 0x18644c50
2016-,01-20 12:20:07.212 ThaliTest[2419:5206412] server session: connect
2016-01-20 12:20:07.212 ThaliTest[2419:5206412] server session: stateChange:0->1 1453288806901.246
,2016-01-20 12:20:07.214 ThaliTest[2419:5206412] server: accepting invitation 1453288806901.246
,2016-01-20 12:20:07.842 ThaliTest[2419:5206412] client: found peer: 1453288806901.246.KGpDfQ==
2016-01-20 12:20:07.843 ThaliTest[2419:5206578] jxcore: connect 1453288806901.246.KGpDfQ==
2016-01-20 12:20:07.843 ThaliTest[2419:5206578] client session: conn,ect
2016-01-20 12:20:07.843 ThaliTest[2419:5206578] client session: stateChange:0->1 1453288806901.246.KGpDfQ==
,2016-01-20 12:20:11.247 ThaliTest[2419:5207371] server session: connected
2016-01-20 12:20:11.247 ThaliTest[2419:5207371] server session: stateChange:1->2 1453288806901.246
,2016-01-20 12:20:11.274 ThaliTest[2419:5206412] server relay: connected (to port: 55433)
,2016-01-20 12:20:11.684 ThaliTest[2419:5207371] server session: not connected 1453288806901.246
,2016-01-20 12:20:11.897 ThaliTest[2419:5207421] client session: connected
2016-01-20 12:20:11.897 ThaliTest[2419:5207421] client session: stateChange:1->2 1453288806901.246.KGpDfQ==
,2016-01-20 12:20:11.897 ThaliTest[2419:5207421] client session: fireConnectCallback: 1453288806901.246.KGpDfQ==
2016-01-20 12:20:11.898 ThaliTest[2419:5207421] jxcore: connect: success
,ok 89 Should be able to connect without error

,ok 90 Port should be within range

,2016-01-20 12:20:11.900 ThaliTest[2419:5206412] client: relay established
2016-01-20 12:20:11.900 ThaliTest[2419:5206412] client: new accepted socket: 0x180ce2b0
,data in 8760

,data in 15330

,data in 37230

,data in 42705

,data in 64463

,data in 85410

,data in 113880

,data in 117165

,data in 130305

,data in 131072

,ok 91 the test messages should be equal

,2016-01-20 12:20:12.305 ThaliTest[2419:5206578] jxcore: disconnect
2016-01-20 12:20:12.306 ThaliTest[2419:5206578] client session: disconnectFromPeer: 1453288806901.246.KGpDfQ==
2016-01-20 12:20:12.306 ThaliTest[2419:5206578] client session: disconnect
2016-01-20 12:20:12.306 ThaliTest[2419:5206578] client session: stateChange:2->0 1453288806901.246.KGpDfQ==
,2016-01-20 12:20:12.309 ThaliTest[2419:5206578] jxcore: disconnect: success
ok 92 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-20 12:20:14.353 ThaliTest[2419:5206578] jxcore: stopBroadcasting
2016-01-20 12:20:14.353 ThaliTest[2419:5206578] THEMultipeerSession stopping peer
2016-01-20 12:20:14.353 ThaliTest[2419:5206578] multipeer session: stop timer
2016-01-20 12:20:14.353 ThaliTest[2419:5206578] server session: disconnect
2016-01-20 12:20:14.354 ThaliTest[2419:5206578] server session: stateChange:2->0 1453288806901.246
,2016-01-20 12:20:14.489 ThaliTest[2419:5206578] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 55439

,2016-01-20 12:20:24.790 ThaliTest[2419:5206578] jxcore: startBroadcasting
,2016-01-20 12:20:24.792 ThaliTest[2419:5206578] server: starting 1453288824790.2419.1bE3uA==
2016-01-20 12:20:24.792 ThaliTest[2419:5206578] multipeer session: start timer: 0x186462c0
2016-01-20 12:20:24.792 ThaliTest[2419:5206578] THEMultipeerSession initialized peer 1453288824790.2419
2016-01-20 12:20:24.792 ThaliTest[2419:5206578] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error

,2016-01-20 12:20:26.540 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
[{"peerIdentifier":"1453288825304.246.0OE3Cw==","peerName":"(null)","peerAvailable":true}]

,2016-01-20 12:20:26.541 ThaliTest[2419:5206578] jxcore: connect 1453288825304.246.0OE3Cw==
2016-01-20 12:20:26.541 ThaliTest[2419:5206578] client session: connect
2016-01-20 12:20:26.541 ThaliTest[2419:5206578] client session: stateChange:0->1 1453288825304.246.0OE3Cw==
,2016-01-20 12:20:27.149 ThaliTest[2419:5206412] multipeer session: reset timer
2016-01-20 12:20:27.149 ThaliTest[2419:5206412] multipeer session: stop timer
2016-01-20 12:20:27.150 ThaliTest[2419:5206412] multipeer session: start timer: 0x186462c0
2016-,01-20 12:20:27.150 ThaliTest[2419:5206412] server session: connect
2016-01-20 12:20:27.150 ThaliTest[2419:5206412] server session: stateChange:0->1 1453288825304.246
,2016-01-20 12:20:27.153 ThaliTest[2419:5206412] server: accepting invitation 1453288825304.246
,2016-01-20 12:20:31.364 ThaliTest[2419:5207469] client session: connected
2016-01-20 12:20:31.364 ThaliTest[2419:5207469] client session: stateChange:1->2 1453288825304.246.0OE3Cw==
,2016-01-20 12:20:31.386 ThaliTest[2419:5207435] client session: fireConnectCallback: 1453288825304.246.0OE3Cw==
2016-01-20 12:20:31.386 ThaliTest[2419:5207435] jxcore: connect: success
ok 94 Should be able to connect without error

,ok 95 Port should be within range

ok 96 First connect should succeed

,2016-01-20 12:20:31.396 ThaliTest[2419:5206412] client: relay established
2016-01-20 12:20:31.396 ThaliTest[2419:5206412] client: new accepted socket: 0x180c10e0
,ok 97 the test messages should be equal

ok 98 First send should succeed

,2016-01-20 12:20:31.457 ThaliTest[2419:5206412] client: socket closed
2016-01-20 12:20:31.457 ThaliTest[2419:5206412] client relay: socket disconnected
2016-01-20 12:20:31.457 ThaliTest[2419:5206412] client relay: 0x180c10e0 disconnected with error Error,288825304.246.0OE3Cw==
 Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-20 12:20:31.457 ThaliTest[2419:5206412] client session: socket closed: 1453288825304.246.0OE3Cw==
2016-01-20 12:20:31.457 ThaliTest[2419:5206412] client session: onLinkFailure: 1453288825304.246.0OE3Cw==
2016-01-20 12:20:31.457 ThaliTest[2419:5206412] client session: disconnect
2016-01-20 12:20:31.457 ThaliTest[2419:5206412] client session: stateChange:2->0 1453,2016-01-20 12:20:31.460 ThaliTest[2419:5206412] client session: fireConnectionErrorEvent: 1453288825304.246.0OE3Cw==
2016-01-20 12:20:31.462 ThaliTest[2419:5206578] jxcore: connect 1453288825304.246.0OE3Cw==
2016-01-20 12:20:31.462 ThaliTest[2419:5206578] client session: connect
2016-01-20 12:20:31.462 ThaliTest[2419:5206578] client session: stateChange:0->1 1453288825304.246.0OE3Cw==
,2016-01-20 12:20:31.825 ThaliTest[2419:5207470] server session: connected
2016-01-20 12:20:31.825 ThaliTest[2419:5207470] server session: stateChange:1->2 1453288825304.246
,2016-01-20 12:20:31.882 ThaliTest[2419:5206412] server relay: connected (to port: 55439)
,2016-01-20 12:20:32.019 ThaliTest[2419:5207435] server session: not connected 1453288825304.246
,2016-01-20 12:20:32.342 ThaliTest[2419:5206412] multipeer session: reset timer
2016-01-20 12:20:32.343 ThaliTest[2419:5206412] multipeer session: stop timer
2016-01-20 12:20:32.343 ThaliTest[2419:5206412] multipeer session: start timer: 0x186462c0
2016-,01-20 12:20:32.343 ThaliTest[2419:5206412] server: disconnecting to refresh session (1453288825304.246)
2016-01-20 12:20:32.343 ThaliTest[2419:5206412] server session: disconnect
2016-01-20 12:20:32.343 ThaliTest[2419:5206412] server session: stateChange:2->0 1453288825304.246
,2016-01-20 12:20:32.344 ThaliTest[2419:5206412] server session: connect
2016-01-20 12:20:32.344 ThaliTest[2419:5206412] server session: stateChange:0->1 1453288825304.246
,2016-01-20 12:20:32.347 ThaliTest[2419:5206412] server: accepting invitation 1453288825304.246
,2016-01-20 12:20:43.821 ThaliTest[2419:5207469] client session: not connected 1453288825304.246.0OE3Cw==
2016-01-20 12:20:43.821 ThaliTest[2419:5207469] client session: onLinkFailure: 1453288825304.246.0OE3Cw==
2016-01-20 12:20:43.822 ThaliTest[2419:5207469] client session: disconnect
2016-01-20 12:20:43.822 ThaliTest[2419:5207469] client session: stateChange:1->0 1453288825304.246.0OE3Cw==
,2016-01-20 12:20:43.828 ThaliTest[2419:5207469] client session: fireConnectCallback: 1453288825304.246.0OE3Cw==
2016-01-20 12:20:43.828 ThaliTest[2419:5207469] jxcore: connect: fail: Peer disconnected
,2016-01-20 12:20:44.123 ThaliTest[2419:5207436] server session: not connected 1453288825304.246
,2016-01-20 12:20:44.835 ThaliTest[2419:5206578] jxcore: connect 1453288825304.246.0OE3Cw==
,2016-01-20 12:20:44.835 ThaliTest[2419:5206578] client session: connect
2016-01-20 12:20:44.836 ThaliTest[2419:5206578] client session: stateChange:0->1 1453288825304.246.0OE3Cw==
,2016-01-20 12:21:02.344 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:21:02.405 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:21:17.772 ThaliTest[2419:5207639] client session: not connected 1453288825304.246.0OE3Cw==
2016-01-20 12:21:17.772 ThaliTest[2419:5207639] client session: onLinkFailure: 1453288825304.246.0OE3Cw==
2016-01-20 12:21:17.773 ThaliTest[2419:5207639] client session: disconnect
2016-01-20 12:21:17.773 ThaliTest[2419:5207639] client session: stateChange:1->0 1453288825304.246.0OE3Cw==
2016-01-20 12:21:17.773 ThaliTest[2419:5207639] client session: fireConnectCallback: 1453288825304.246.0OE3Cw==
2016-01-20 12:21:17.773 ThaliTest[2419:5207639] jxcore: connect: fail: Peer disconnected
,2016-01-20 12:21:18.777 ThaliTest[2419:5206578] jxcore: connect 1453288825304.246.0OE3Cw==
2016-01-20 12:21:18.778 ThaliTest[2419:5206578] client session: connect
2016-01-20 12:21:18.778 ThaliTest[2419:5206578] client session: stateChange:0->1 1453288825304.246.0OE3Cw==
,2016-01-20 12:21:32.344 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:21:32.353 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:21:51.672 ThaliTest[2419:5207721] client session: not connected 1453288825304.246.0OE3Cw==
2016-01-20 12:21:51.672 ThaliTest[2419:5207721] client session: onLinkFailure: 1453288825304.246.0OE3Cw==
2016-01-20 12:21:51.672 ThaliTest[2419:5207721] client session: disconnect
2016-01-20 12:21:51.673 ThaliTest[2419:5207721] client session: stateChange:1->0 1453288825304.246.0OE3Cw==
2016-01-20 12:21:51.673 ThaliTest[2419:5207721] client session: fireConnectCallback: 1453288825304.246.0OE3Cw==
2016-01-20 12:21:51.673 ThaliTest[2419:5207721] jxcore: connect: fail: Peer disconnected
,2016-01-20 12:21:52.675 ThaliTest[2419:5206578] jxcore: connect 1453288825304.246.0OE3Cw==
2016-01-20 12:21:52.675 ThaliTest[2419:5206578] client session: connect
2016-01-20 12:21:52.675 ThaliTest[2419:5206578] client session: stateChange:0->1 1453288825,304.246.0OE3Cw==
,2016-01-20 12:21:56.739 ThaliTest[2419:5207721] client session: connected
2016-01-20 12:21:56.739 ThaliTest[2419:5207721] client session: stateChange:1->2 1453288825304.246.0OE3Cw==
,2016-01-20 12:21:56.797 ThaliTest[2419:5207742] client session: fireConnectCallback: 1453288825304.246.0OE3Cw==
2016-01-20 12:21:56.797 ThaliTest[2419:5207742] jxcore: connect: success
,ok 99 Should be able to connect without error

ok 100 Port should be within range

ok 101 Second connect should succeed

,2016-01-20 12:21:56.807 ThaliTest[2419:5206412] client: relay established
2016-01-20 12:21:56.807 ThaliTest[2419:5206412] client: new accepted socket: 0x1848d860
,ok 102 the test messages should be equal

ok 103 Second send should succeed

,# setup

,2016-01-20 12:21:56.872 ThaliTest[2419:5206412] client: socket closed
2016-01-20 12:21:56.872 ThaliTest[2419:5206412] client relay: socket disconnected
2016-01-20 12:21:56.873 ThaliTest[2419:5206412] client relay: 0x1848d860 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-20 12:21:56.873 ThaliTest[2419:5206412] client session: socket closed: 1453288825304.246.0OE3Cw==
2016-01-20 1,2:21:56.873 ThaliTest[2419:5206412] client session: onLinkFailure: 1453288825304.246.0OE3Cw==
2016-01-20 12:21:56.873 ThaliTest[2419:5206412] client session: disconnect
2016-01-20 12:21:56.873 ThaliTest[2419:5206412] client session: stateChange:2->0 1453288825304.246.0OE3Cw==
,2016-01-20 12:21:56.876 ThaliTest[2419:5206412] client session: fireConnectionErrorEvent: 1453288825304.246.0OE3Cw==
,2016-01-20 12:22:00.405 ThaliTest[2419:5206412] multipeer session: reset timer
2016-01-20 12:22:00.406 ThaliTest[2419:5206412] multipeer session: stop timer
2016-01-20 12:22:00.406 ThaliTest[2419:5206412] multipeer session: start timer: 0x186462c0
2016-,01-20 12:22:00.406 ThaliTest[2419:5206412] server: disconnecting to refresh session (1453288825304.246)
2016-01-20 12:22:00.406 ThaliTest[2419:5206412] server session: disconnect
2016-01-20 12:22:00.406 ThaliTest[2419:5206412] server session: stateChange:1->0 1453288825304.246
2016-01-20 12:22:00.406 ThaliTest[2419:5206412] server session: connect
2016-01-20 12:22:00.406 ThaliTest[2419:5206412] server session: stateChange:0->1 1453288825304.246
,2016-01-20 12:22:00.408 ThaliTest[2419:5206412] server: accepting invitation 1453288825304.246
,2016-01-20 12:22:03.620 ThaliTest[2419:5207743] server session: connected
2016-01-20 12:22:03.620 ThaliTest[2419:5207743] server session: stateChange:1->2 1453288825304.246
,2016-01-20 12:22:03.681 ThaliTest[2419:5206412] server relay: connected (to port: 55439)
,2016-01-20 12:22:03.813 ThaliTest[2419:5207721] server session: not connected 1453288825304.246
,2016-01-20 12:22:30.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:22:30.415 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:23:00.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:23:00.414 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:23:30.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:23:30.414 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:24:00.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:24:00.414 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:24:30.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:24:30.415 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:25:00.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:25:00.776 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:25:30.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:25:30.415 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:26:00.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:26:00.418 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:26:30.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:26:30.414 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:27:00.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:27:00.414 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:27:30.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:27:30.414 ThaliTest[2419:5206412] client: found peer: 1453288825304.246.0OE3Cw==
,2016-01-20 12:27:36.512 ThaliTest[2419:5206412] client: lost peer: 1453288825304.246.0OE3Cw==
2016-01-20 12:27:36.512 ThaliTest[2419:5206412] client session: onPeerLost: 1453288825304.246.0OE3Cw==
[{"peerIdentifier":"1453288825304.246.0OE3Cw==","peerName":"(null)","peerAvailable":false}]

,2016-01-20 12:28:00.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:28:30.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:29:00.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:29:30.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:30:00.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:30:30.407 ThaliTest[2419:5206412] multipeer session: restart
,2016-01-20 12:31:00.407 ThaliTest[2419:5206412] multipeer session: restart

```
