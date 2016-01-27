#### Test 568182540458528_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/568182540458528/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F788F9DC-D918-416C-AF35-1366BBB50E97/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F788F9DC-D918-416C-AF35-1366BBB50E97/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/568182540458528/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/568182540458528/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61357"
,(lldb)     command script import "/tmp/F788F9DC-D918-416C-AF35-1366BBB50E97/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-27 02:07:49.359 ThaliTest[2999:6275272] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6230C79A-380B-4720-B711-4CD6A96753D8/Library/Cookies/Cookies.binarycookies
,2016-01-27 02:07:49.606 ThaliTest[2999:6275272] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-27 02:07:49.607 ThaliTest[2999:6275272] Multi-tasking -> Device: YES, App: YES
,2016-01-27 02:07:49.613 ThaliTest[2999:6275272] Unlimited access to network resources
,2016-01-27 02:07:49.619 ThaliTest[2999:6275272] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-27 02:07:53.788 ThaliTest[2999:6275272] Resetting plugins due to page load.
,2016-01-27 02:07:55.206 ThaliTest[2999:6275272] Finished load of: file:///var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/index.html
,2016-01-27 02:07:55.345 ThaliTest[2999:6275272] JXcore Cordova plugin initializing
,2016-01-27 02:07:55.346 ThaliTest[2999:6275449] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,ok 6 secondPromise result

,ok 7 secondPromise testValue

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

ok 36 should be equal

,ok 37 should be equal

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

ok 46 should be equal

,ok 47 should be equal

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

,2016-01-27 02:13:18.886 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:18.893 ThaliTest[2999:6275449] server: starting 1453857198886.2999.u/AgCA==
,2016-01-27 02:13:18.893 ThaliTest[2999:6275449] multipeer session: start timer: 0x18ed6aa0
2016-01-27 02:13:18.893 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857198886.2999
2016-01-27 02:13:18.893 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

2016-01-27 02:13:18.894 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:18.894 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:18.894 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:18.895 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-01-27 02:13:18.895 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:18.896 ThaliTest[2999:6275449] server: starting 1453857198895.2999.dyW5+w==
2016-01-27 02:13:18.897 ThaliTest[2999:6275449] multipeer session: start timer: 0x18c19d90
2016-01-27 02:13:18.897 ThaliTest[2999:6275449] THEMultipeerSession in,itialized peer 1453857198895.2999
2016-01-27 02:13:18.897 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error

2016-01-27 02:13:18.900 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:18.900 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:18.900 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:18.900 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-01-27 02:13:18.901 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:18.902 ThaliTest[2999:6275449] server: starting 1453857198901.2999.prOwFA==
,2016-01-27 02:13:18.902 ThaliTest[2999:6275449] multipeer session: start timer: 0x18966700
2016-01-27 02:13:18.903 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857198901.2999
2016-01-27 02:13:18.904 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-01-27 02:13:18.904 ThaliTest[2999:6275449] jxcore: stopBroadcasting
,2016-01-27 02:13:18.904 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:18.905 ThaliTest[2999:6275449] multipeer session: stop timer
,2016-01-27 02:13:18.905 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-01-27 02:13:18.906 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:18.907 ThaliTest[2999:6275449] server: starting 1453857198905.2999.ogdt3w==
,2016-01-27 02:13:18.907 ThaliTest[2999:6275449] multipeer session: start timer: 0x189672b0
,2016-01-27 02:13:18.908 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857198905.2999
,2016-01-27 02:13:18.908 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 60 Should be able to call startBroadcasting without error

,2016-01-27 02:13:18.909 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:18.909 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:18.910 ThaliTest[2999:6275449] multipeer session: stop timer
,2016-01-27 02:13:18.910 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-01-27 02:13:18.910 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:18.912 ThaliTest[2999:6275449] server: starting 1453857198910.2999.4caBuA==
,2016-01-27 02:13:18.912 ThaliTest[2999:6275449] multipeer session: start timer: 0x18c1ba50
2016-01-27 02:13:18.912 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857198910.2999
2016-01-27 02:13:18.912 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-01-27 02:13:18.913 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:18.913 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:18.913 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:18.913 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
ok 63 Should be able to call stopBroadcasting without error

2016-01-27 02:13:18.914 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:18.916 ThaliTest[2999:6275449] server: starting 1453857198914.2999.8X7yLg==
2016-01-27 02:13:18.916 ThaliTest[2999:6275449] multipeer session: start timer: 0x18968f80
2016-01-27 02:13:18.917 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857198914.2999
2016-01-27 02:13:18.917 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 64 Should be able to call startBroadcasting without error

2016-01-27 02:13:18.917 ThaliTest[2999:6275449] jxcore: stopBroadcasting,
2016-01-27 02:13:18.917 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:18.918 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:18.918 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
ok 65 Should be able to call stopBroadcasting without error

2016-01-27 02:13:18.918 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:18.922 ThaliTest[2999:6275449] server: starting 1453857198918.2999.OBPLTw==
2016-01-27 02:13:18.922 ThaliTest[2999:6275449] multipeer session: start timer: 0x18968f80
,2016-01-27 02:13:18.922 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857198918.2999
,2016-01-27 02:13:18.923 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 66 Should be able to call startBroadcasting without error

2016-01-27 02:13:18.923 ThaliTest[2999:6275449] jxcore: stopBroadcasting
,2016-01-27 02:13:18.923 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:18.923 ThaliTest[2999:6275449] multipeer session: stop timer
,2016-01-27 02:13:18.924 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error

2016-01-27 02:13:18.924 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:18.926 ThaliTest[2999:6275449] server: starting 1453857198924.2999.YzHExQ==
2016-01-27 02:13:18.926 ThaliTest[2999:6275449] multipeer session: start timer: 0x1896a450
2016-01-27 02:13:18.926 ThaliTest[2999:6275449] THEMultipeerSession in,itialized peer 1453857198924.2999
2016-01-27 02:13:18.926 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

2016-01-27 02:13:18.927 ThaliTest[2999:6275449] jxcore: stopBroadcasting,
2016-01-27 02:13:18.927 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:18.927 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:18.927 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
ok 69 Shou,ld be able to call stopBroadcasting without error

,2016-01-27 02:13:18.928 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:18.929 ThaliTest[2999:6275449] server: starting 1453857198927.2999.ZP8QsA==
,2016-01-27 02:13:18.929 ThaliTest[2999:6275449] multipeer session: start timer: 0x18ec44b0
,2016-01-27 02:13:18.931 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857198927.2999
2016-01-27 02:13:18.931 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-27 02:13:18.931 ThaliTest[2999:6275449] jxcore: stopBroadcasting
,2016-01-27 02:13:18.932 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
,2016-01-27 02:13:18.932 ThaliTest[2999:6275449] multipeer session: stop timer
,2016-01-27 02:13:18.932 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-01-27 02:13:18.933 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:18.934 ThaliTest[2999:6275449] server: starting 1453857198933.2999.U3meDQ==
,2016-01-27 02:13:18.934 ThaliTest[2999:6275449] multipeer session: start timer: 0x189694d0
,2016-01-27 02:13:18.934 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857198933.2999
2016-01-27 02:13:18.934 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 72 Should be able to call startBroadcasting without error

,2016-01-27 02:13:18.935 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:18.935 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:18.935 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:18.935 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-27 02:13:19.359 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:19.360 ThaliTest[2999:6275449] server: starting 1453857199359.2999.+EGd4w==
,2016-01-27 02:13:19.360 ThaliTest[2999:6275449] multipeer session: start timer: 0x18c1b180
2016-01-27 02:13:19.360 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857199359.2999
2016-01-27 02:13:19.360 ThaliTest[2999:6275449] jxcore: sta,rtBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-01-27 02:13:19.361 ThaliTest[2999:6275449] jxcore: startBroadcasting
2016-01-27 02:13:19.362 ThaliTest[2999:6275449] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-01-27 02:13:19.363 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:19.363 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:19.363 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:19.364 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-27 02:13:22.247 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:22.248 ThaliTest[2999:6275449] server: starting 1453857202247.2999.lRpF3w==
2016-01-27 02:13:22.248 ThaliTest[2999:6275449] multipeer session: start timer: 0x18ec6880
2016-01-27 02:13:22.248 ThaliTest[2999:6275449] THEMultipeerSession in,itialized peer 1453857202247.2999
2016-01-27 02:13:22.248 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-27 02:13:22.249 ThaliTest[2999:6275449] jxcore: connect foobar
2,016-01-27 02:13:22.249 ThaliTest[2999:6275449] client: unknown peer foobar
,2016-01-27 02:13:22.249 ThaliTest[2999:6275449] jxcore: connect: fail: Unknown peer
ok 78 Should not connect to a bad peer

2016-01-27 02:13:22.252 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:22.252 ThaliTest[2999:6275449] THEMult,ipeerSession stopping peer
2016-01-27 02:13:22.252 ThaliTest[2999:6275449] multipeer session: stop timer
,2016-01-27 02:13:22.253 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-27 02:13:22.385 ThaliTest[2999:6275449] jxcore: startBroadcasting
,01-27 02:13:22.387 ThaliTest[2999:6275449] jxcore: disconnect: fail
ok 81 Disconnect should fail to a non-existant peer 

2016-01-27 02:13:22.386 ThaliTest[2999:6275449] server: starting 1453857202385.2999.k4AOCg==
2016-01-27 02:13:22.386 ThaliTest[2999:6275449] multipeer session: start timer: 0x186e6980
2016-01-27 02:13:22.386 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857202385.2999
2016-01-27 02:13:22.386 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-27 02:13:22.387 ThaliTest[2999:6275449] jxcore: disconnect
2016-,2016-01-27 02:13:22.388 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:22.391 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:22.391 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:22.391 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-27 02:13:22.776 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:22.778 ThaliTest[2999:6275449] server: starting 1453857202776.2999.647KgA==
2016-01-27 02:13:22.778 ThaliTest[2999:6275449] multipeer session: start timer: 0x18ebb0c0
2016-01-27 02:13:22.778 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857202776.2999
,2016-01-27 02:13:22.779 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-27 02:13:23.713 ThaliTest[2999:6275272] client: found peer: 1453857201832.2663.u2wqlg==
,2016-01-27 02:13:23.714 ThaliTest[2999:6275449] jxcore: connect 1453857201832.2663.u2wqlg==
2016-01-27 02:13:23.714 ThaliTest[2999:6275449] client session: connect
2016-01-27 02:13:23.714 ThaliTest[2999:6275449] client session: stateChange:0->1 1453857201832.2663.u2wqlg==
,2016-01-27 02:13:24.141 ThaliTest[2999:6275272] multipeer session: reset timer
2016-01-27 02:13:24.141 ThaliTest[2999:6275272] multipeer session: stop timer
2016-01-27 02:13:24.142 ThaliTest[2999:6275272] multipeer session: start timer: 0x18ebb0c0
2016-01-27 02:13:24.142 ThaliTest[2999:6275272] server session: connect
2016-01-27 02:13:24.142 ThaliTest[2999:6275272] server session: stateChange:0->1 1453857201832.2663
,2016-01-27 02:13:24.144 ThaliTest[2999:6275272] server: accepting invitation 1453857201832.2663
,2016-01-27 02:13:26.476 ThaliTest[2999:6276184] server session: connected
2016-01-27 02:13:26.477 ThaliTest[2999:6276184] server session: stateChange:1->2 1453857201832.2663
,2016-01-27 02:13:26.479 ThaliTest[2999:6275272] server relay: socket disconnected
2016-01-27 02:13:26.479 ThaliTest[2999:6275272] server relay: 0x16602fa0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 02:13:26.535 ThaliTest[2999:6276184] server session: not connected 1453857201832.2663
,2016-01-27 02:13:26.603 ThaliTest[2999:6276184] client session: connected
2016-01-27 02:13:26.603 ThaliTest[2999:6276184] client session: stateChange:1->2 1453857201832.2663.u2wqlg==
,2016-01-27 02:13:26.605 ThaliTest[2999:6276185] client session: fireConnectCallback: 1453857201832.2663.u2wqlg==
2016-01-27 02:13:26.605 ThaliTest[2999:6276185] jxcore: connect: success
ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-01-27 02:13:26.607 ThaliTest[2999:6275449] jxcore: disconnect
2016-01-27 02:13:26.607 ThaliTest[2999:6275449] client session: disconnectFromPeer: 1453857201832.2663.u2wqlg==
2016-01-27 02:13:26.607 ThaliTest[2999:6275449] client session: disconnect
2016-01-27 02:13:26.607 ThaliTest[2999:6275449] client session: stateChange:2->0 1453857201832.2663.u2wqlg==
,2016-01-27 02:13:26.670 ThaliTest[2999:6275449] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-27 02:13:27.429 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:27.429 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:27.429 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:27.,429 ThaliTest[2999:6275449] server session: disconnect
2016-01-27 02:13:27.429 ThaliTest[2999:6275449] server session: stateChange:2->0 1453857201832.2663
,2016-01-27 02:13:27.433 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-27 02:13:28.257 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:28.258 ThaliTest[2999:6275449] server: starting 1453857208256.2999.US3igQ==
2016-01-27 02:13:28.258 ThaliTest[2999:6275449] multipeer session: start timer: 0x18b56dc0
2016-01-27 02:13:28.258 ThaliTest[2999:6275449] THEMultipeerSession in,itialized peer 1453857208256.2999
2016-01-27 02:13:28.258 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-27 02:13:29.346 ThaliTest[2999:6275272] client: found peer: 1453857207583.2663.YIoGXQ==
,2016-01-27 02:13:29.346 ThaliTest[2999:6275449] jxcore: connect 1453857207583.2663.YIoGXQ==
2016-01-27 02:13:29.346 ThaliTest[2999:6275449] client session: connect
2016-01-27 02:13:29.347 ThaliTest[2999:6275449] client session: stateChange:0->1 145385720,7583.2663.YIoGXQ==
,2016-01-27 02:13:29.616 ThaliTest[2999:6275272] multipeer session: reset timer
2016-01-27 02:13:29.616 ThaliTest[2999:6275272] multipeer session: stop timer
2016-01-27 02:13:29.617 ThaliTest[2999:6275272] multipeer session: start timer: 0x18b56dc0
2016-01-27 02:13:29.617 ThaliTest[2999:6275272] server session: connect
2016-01-27 02:13:29.617 ThaliTest[2999:6275272] server session: stateChange:0->1 1453857207583.2663
,2016-01-27 02:13:29.619 ThaliTest[2999:6275272] server: accepting invitation 1453857207583.2663
,2016-01-27 02:13:31.850 ThaliTest[2999:6276183] client session: connected
2016-01-27 02:13:31.850 ThaliTest[2999:6276183] client session: stateChange:1->2 1453857207583.2663.YIoGXQ==
2016-01-27 02:13:31.852 ThaliTest[2999:6276184] client session: fireConnectCallback: 1453857207583.2663.YIoGXQ==
2016-01-27 02:13:31.852 ThaliTest[2999:6276184] jxcore: connect: success
,ok 88 Should be able to connect without error

ok 89 Port should be within range

,2016-01-27 02:13:31.853 ThaliTest[2999:6275449] jxcore: connect 1453857207583.2663.YIoGXQ==
2016-01-27 02:13:31.854 ThaliTest[2999:6275449] client: already connect(ing/ed) to 1453857207583.2663.YIoGXQ==
2016-01-27 02:13:31.854 ThaliTest[2999:6275449] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-01-27 02:13:31.855 ThaliTest[2999:6275449] jxcore: disconnect
2016-01-27 02:13:31.855 ThaliTest[2999:6275449] client session: disconnectFromPeer: 1453857207583.2663.YIoGXQ==
2016-01-27 02:13:31.855 ThaliTest[2999:6275449] client session: disconnect
2016-01-27 02:13:31.855 ThaliTest[2999:6275449] client session: stateChange:2->0 1453857207583.2663.YIoGXQ==
,2016-01-27 02:13:31.916 ThaliTest[2999:6275449] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-27 02:13:32.000 ThaliTest[2999:6276183] server session: connected
2016-01-27 02:13:32.000 ThaliTest[2999:6276183] server session: stateChange:1->2 1453857207583.2663
2016-01-27 02:13:32.001 ThaliTest[2999:6275272] server relay: socket disconnected
,2016-01-27 02:13:32.002 ThaliTest[2999:6275272] server relay: 0x18e853a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 02:13:32.178 ThaliTest[2999:6276184] server session: not connected 1453857207583.2663
,calling stopBroadcasting

,2016-01-27 02:13:32.386 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:32.386 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:32.386 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:32.,386 ThaliTest[2999:6275449] server session: disconnect
2016-01-27 02:13:32.387 ThaliTest[2999:6275449] server session: stateChange:2->0 1453857207583.2663
,2016-01-27 02:13:32.390 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-27 02:13:32.742 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:32.743 ThaliTest[2999:6275449] server: starting 1453857212742.2999.cY6xGw==
,2016-01-27 02:13:32.743 ThaliTest[2999:6275449] multipeer session: start timer: 0x1856bc90
,2016-01-27 02:13:32.744 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857212742.2999
2016-01-27 02:13:32.744 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-27 02:13:33.722 ThaliTest[2999:6275272] multipeer session: reset timer
2016-01-27 02:13:33.722 ThaliTest[2999:6275272] multipeer session: stop timer
2016-01-27 02:13:33.722 ThaliTest[2999:6275272] multipeer session: start timer: 0x1856bc90
2016-,01-27 02:13:33.722 ThaliTest[2999:6275272] server session: connect
2016-01-27 02:13:33.722 ThaliTest[2999:6275272] server session: stateChange:0->1 1453857212209.2663
2016-01-27 02:13:33.724 ThaliTest[2999:6275272] server: accepting invitation 1453857212209.2663
,2016-01-27 02:13:33.832 ThaliTest[2999:6275272] client: found peer: 1453857212209.2663.FU+7eQ==
,2016-01-27 02:13:33.833 ThaliTest[2999:6275449] jxcore: connect 1453857212209.2663.FU+7eQ==
2016-01-27 02:13:33.833 ThaliTest[2999:6275449] client session: connect
2016-01-27 02:13:33.833 ThaliTest[2999:6275449] client session: stateChange:0->1 1453857212209.2663.FU+7eQ==
,2016-01-27 02:13:36.174 ThaliTest[2999:6276184] server session: connected
2016-01-27 02:13:36.174 ThaliTest[2999:6276184] server session: stateChange:1->2 1453857212209.2663
,2016-01-27 02:13:36.193 ThaliTest[2999:6275272] server relay: socket disconnected
2016-01-27 02:13:36.193 ThaliTest[2999:6275272] server relay: 0x1853c4f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-27 02:13:36.228 ThaliTest[2999:6276183] server session: not connected 1453857212209.2663
,2016-01-27 02:13:36.436 ThaliTest[2999:6276184] client session: connected
2016-01-27 02:13:36.436 ThaliTest[2999:6276184] client session: stateChange:1->2 1453857212209.2663.FU+7eQ==
,2016-01-27 02:13:36.454 ThaliTest[2999:6276187] client session: fireConnectCallback: 1453857212209.2663.FU+7eQ==
2016-01-27 02:13:36.455 ThaliTest[2999:6276187] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should b,e within range

,2016-01-27 02:13:36.456 ThaliTest[2999:6275449] jxcore: disconnect
2016-01-27 02:13:36.456 ThaliTest[2999:6275449] client session: disconnectFromPeer: 1453857212209.2663.FU+7eQ==
2016-01-27 02:13:36.456 ThaliTest[2999:6275449] client session: disconnect,
2016-01-27 02:13:36.456 ThaliTest[2999:6275449] client session: stateChange:2->0 1453857212209.2663.FU+7eQ==
,2016-01-27 02:13:36.459 ThaliTest[2999:6275449] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-01-27 02:13:36.460 ThaliTest[2999:6275449] jxcore: disconnect
2016-01-27 02:13:36.460 ThaliTest[2999:6275449] jxcore: disconnect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-27 02:13:36.591 ThaliTest[2999:6275449] jxcore: stopBroadcasting
,2016-01-27 02:13:36.592 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
,2016-01-27 02:13:36.592 ThaliTest[2999:6275449] multipeer session: stop timer
,2016-01-27 02:13:36.592 ThaliTest[2999:6275449] server session: disconnect
2016-01-27 02:13:36.592 ThaliTest[2999:6275449] server session: stateChange:2->0 1453857212209.2663
,2016-01-27 02:13:36.695 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 57980

,2016-01-27 02:13:38.072 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:38.073 ThaliTest[2999:6275449] server: starting 1453857218072.2999.0tixUw==
2016-01-27 02:13:38.073 ThaliTest[2999:6275449] multipeer session: start timer: 0x166f69b0
2016-01-27 02:13:38.073 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857218072.2999
2016-01-27 02:13:38.074 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-01-27 02:13:39.478 ThaliTest[2999:6275272] client: found peer: 1453857217561.2663.akxSTg==
,2016-01-27 02:13:39.478 ThaliTest[2999:6275449] jxcore: connect 1453857217561.2663.akxSTg==
2016-01-27 02:13:39.479 ThaliTest[2999:6275449] client session: connect
2016-01-27 02:13:39.479 ThaliTest[2999:6275449] client session: stateChange:0->1 1453857217561.2663.akxSTg==
,2016-01-27 02:13:39.841 ThaliTest[2999:6275272] multipeer session: reset timer
2016-01-27 02:13:39.841 ThaliTest[2999:6275272] multipeer session: stop timer
2016-01-27 02:13:39.841 ThaliTest[2999:6275272] multipeer session: start timer: 0x166f69b0
2016-,01-27 02:13:39.842 ThaliTest[2999:6275272] server session: connect
2016-01-27 02:13:39.842 ThaliTest[2999:6275272] server session: stateChange:0->1 1453857217561.2663
2016-01-27 02:13:39.844 ThaliTest[2999:6275272] server: accepting invitation 1453857217561.2663
,2016-01-27 02:13:41.940 ThaliTest[2999:6276184] client session: connected
,2016-01-27 02:13:41.940 ThaliTest[2999:6276184] client session: stateChange:1->2 1453857217561.2663.akxSTg==
,2016-01-27 02:13:41.978 ThaliTest[2999:6276185] client session: fireConnectCallback: 1453857217561.2663.akxSTg==
2016-01-27 02:13:41.978 ThaliTest[2999:6276185] jxcore: connect: success
,ok 98 Should be able to connect without error

ok 99 Port should be within range

,2016-01-27 02:13:41.980 ThaliTest[2999:6275272] client: relay established
2016-01-27 02:13:41.980 ThaliTest[2999:6275272] client: new accepted socket: 0x18c41ec0
,data in 2190

,data in 3285

,data in 4380

,data in 13140

,data in 33945

,data in 56940

,data in 70080

,data in 83220

,2016-01-27 02:13:42.171 ThaliTest[2999:6276184] server session: connected
2016-01-27 02:13:42.171 ThaliTest[2999:6276184] server session: stateChange:1->2 1453857217561.2663
,data in 91980

,2016-01-27 02:13:42.186 ThaliTest[2999:6275272] server relay: connected (to port: 57980)
,data in 94170

,data in 95265

,data in 101835

,data in 109500

,data in 119355

,data in 131072

,ok 100 the test messages should be equal

,2016-01-27 02:13:42.249 ThaliTest[2999:6275449] jxcore: disconnect
,2016-01-27 02:13:42.250 ThaliTest[2999:6275449] client session: disconnectFromPeer: 1453857217561.2663.akxSTg==
,2016-01-27 02:13:42.250 ThaliTest[2999:6275449] client session: disconnect
2016-01-27 02:13:42.250 ThaliTest[2999:6275449] client session: stateChange:2->0 1453857217561.2663.akxSTg==
,2016-01-27 02:13:42.255 ThaliTest[2999:6275449] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-27 02:13:42.444 ThaliTest[2999:6276184] server session: not connected 1453857217561.2663
,calling stopBroadcasting

2016-01-27 02:13:42.850 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:42.850 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
,2016-01-27 02:13:42.850 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:42.851 ThaliTest[2999:6275449] server session: disconnect
2016-01-27 02:13:42.851 ThaliTest[2999:6275449] server session: stateChange:2->0 1453857217561.2663
,2016-01-27 02:13:42.854 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 57986

,2016-01-27 02:13:44.279 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:44.280 ThaliTest[2999:6275449] server: starting 1453857224278.2999.fHgzCg==
2016-01-27 02:13:44.280 ThaliTest[2999:6275449] multipeer session: start timer: 0x18e8acf0
2016-01-27 02:13:44.280 ThaliTest[2999:6275449] THEMultipeerSession initialized peer 1453857224278.2999
2016-01-27 02:13:44.280 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-27 02:13:45.670 ThaliTest[2999:6275272] multipeer session: reset timer
2016-01-27 02:13:45.670 ThaliTest[2999:6275272] multipeer session: stop timer
2016-01-27 02:13:45.670 ThaliTest[2999:6275272] multipeer session: start timer: 0x18e8acf0
2016-,01-27 02:13:45.671 ThaliTest[2999:6275272] server session: connect
2016-01-27 02:13:45.671 ThaliTest[2999:6275272] server session: stateChange:0->1 1453857223604.2663
,2016-01-27 02:13:45.673 ThaliTest[2999:6275272] server: accepting invitation 1453857223604.2663
,2016-01-27 02:13:45.693 ThaliTest[2999:6275272] client: found peer: 1453857223604.2663.qQMTwQ==
[{"peerIdentifier":"1453857223604.2663.qQMTwQ==","peerName":"(null)","peerAvailable":true}]

,2016-01-27 02:13:45.694 ThaliTest[2999:6275449] jxcore: connect 1453857223604.2663.qQMTwQ==
2016-01-27 02:13:45.695 ThaliTest[2999:6275449] client session: connect
2016-01-27 02:13:45.695 ThaliTest[2999:6275449] client session: stateChange:0->1 1453857223604.2663.qQMTwQ==
,2016-01-27 02:13:48.224 ThaliTest[2999:6276187] client session: connected
2016-01-27 02:13:48.224 ThaliTest[2999:6276187] client session: stateChange:1->2 1453857223604.2663.qQMTwQ==
,2016-01-27 02:13:48.226 ThaliTest[2999:6276187] client session: fireConnectCallback: 1453857223604.2663.qQMTwQ==
2016-01-27 02:13:48.227 ThaliTest[2999:6276187] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should be within range

ok 105 First connect should succeed

,2016-01-27 02:13:48.229 ThaliTest[2999:6276184] server session: connected
2016-01-27 02:13:48.229 ThaliTest[2999:6276184] server session: stateChange:1->2 1453857223604.2663
,2016-01-27 02:13:48.237 ThaliTest[2999:6275272] client: relay established
2016-01-27 02:13:48.237 ThaliTest[2999:6275272] client: new accepted socket: 0x1853ba20
2016-01-27 02:13:48.238 ThaliTest[2999:6275272] server relay: connected (to port: 57986)
,ok 106 the test messages should be equal

ok 107 First send should succeed

,2016-01-27 02:13:48.311 ThaliTest[2999:6275272] client: socket closed
2016-01-27 02:13:48.311 ThaliTest[2999:6275272] client relay: socket disconnected
2016-01-27 02:13:48.311 ThaliTest[2999:6275272] client relay: 0x1853ba20 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-27 02:13:48.311 ThaliTest[2999:6275272] client session: socket closed: 1453857223604.2663.qQMTwQ==
2016-01-27 ,02:13:48.311 ThaliTest[2999:6275272] client session: onLinkFailure: 1453857223604.2663.qQMTwQ==
2016-01-27 02:13:48.311 ThaliTest[2999:6275272] client session: disconnect
2016-01-27 02:13:48.311 ThaliTest[2999:6275272] client session: stateChange:2->0 1453857223604.2663.qQMTwQ==
,2016-01-27 02:13:48.316 ThaliTest[2999:6275272] client session: fireConnectionErrorEvent: 1453857223604.2663.qQMTwQ==
2016-01-27 02:13:48.317 ThaliTest[2999:6275449] jxcore: connect 1453857223604.2663.qQMTwQ==
2016-01-27 02:13:48.317 ThaliTest[2999:6275449] client session: connect
2016-01-27 02:13:48.317 ThaliTest[2999:6275449] client session: stateChange:0->1 1453857223604.2663.qQMTwQ==
,2016-01-27 02:13:48.416 ThaliTest[2999:6276183] server session: not connected 1453857223604.2663
,2016-01-27 02:13:48.620 ThaliTest[2999:6275272] multipeer session: reset timer
2016-01-27 02:13:48.620 ThaliTest[2999:6275272] multipeer session: stop timer
2016-01-27 02:13:48.620 ThaliTest[2999:6275272] multipeer session: start timer: 0x18e8acf0
2016-,01-27 02:13:48.621 ThaliTest[2999:6275272] server: disconnecting to refresh session (1453857223604.2663)
2016-01-27 02:13:48.621 ThaliTest[2999:6275272] server session: disconnect
2016-01-27 02:13:48.621 ThaliTest[2999:6275272] server session: stateChange:2->0 1453857223604.2663
,2016-01-27 02:13:48.622 ThaliTest[2999:6275272] server session: connect
2016-01-27 02:13:48.622 ThaliTest[2999:6275272] server session: stateChange:0->1 1453857223604.2663
,2016-01-27 02:13:48.625 ThaliTest[2999:6275272] server: accepting invitation 1453857223604.2663
,2016-01-27 02:13:50.779 ThaliTest[2999:6276183] client session: connected
2016-01-27 02:13:50.779 ThaliTest[2999:6276183] client session: stateChange:1->2 1453857223604.2663.qQMTwQ==
,2016-01-27 02:13:50.782 ThaliTest[2999:6276184] client session: fireConnectCallback: 1453857223604.2663.qQMTwQ==
2016-01-27 02:13:50.782 ThaliTest[2999:6276184] jxcore: connect: success
ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-01-27 02:13:50.792 ThaliTest[2999:6275272] client: relay established
2016-01-27 02:13:50.792 ThaliTest[2999:6275272] client: new accepted socket: 0x1853b490
,ok 111 the test messages should be equal

ok 112 Second send should succeed

,# setup

,2016-01-27 02:13:50.851 ThaliTest[2999:6275272] client: socket closed
2016-01-27 02:13:50.852 ThaliTest[2999:6275272] client relay: socket disconnected
2016-01-27 02:13:50.852 ThaliTest[2999:6275272] client relay: 0x1853b490 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-27 02:13:50.852 ThaliTest[2999:6275272] client session: socket closed: 1453857223604.2663.qQMTwQ==
2016-01-27 02:13:50.852 ThaliTest[2999:6275272] client session: onLinkFailure: 1453857223604.2663.qQMTwQ==
2016-01-27 02:13:50.852 ThaliTest[2999:6275272] client session: disconnect
2016-01-27 02:13:50.852 ThaliTest[2999:6275272] client session: stateChange:2->0 1453857223604.2663.qQMTwQ==
,2016-01-27 02:13:50.854 ThaliTest[2999:6275272] client session: fireConnectionErrorEvent: 1453857223604.2663.qQMTwQ==
,2016-01-27 02:13:50.981 ThaliTest[2999:6276183] server session: connected
2016-01-27 02:13:50.981 ThaliTest[2999:6276183] server session: stateChange:1->2 1453857223604.2663
,2016-01-27 02:13:50.983 ThaliTest[2999:6275272] server relay: connected (to port: 57986)
,2016-01-27 02:13:51.068 ThaliTest[2999:6276183] server session: not connected 1453857223604.2663
,calling stopBroadcasting

,2016-01-27 02:13:51.312 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:51.312 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:51.312 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:51.312 ThaliTest[2999:6275449] server session: disconnect
2016-01-27 02:13:51.312 ThaliTest[2999:6275449] server session: stateChange:2->0 1453857223604.2663
,2016-01-27 02:13:51.314 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/6230C79A-380B-4720-B711-4CD6A96753D8/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-27 02:13:51.933 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:51.934 ThaliTest[2999:6275449] server: starting EprTNOFbJ45Lbb90mJwazA.YlXcmw==
2016-01-27 02:13:51.934 ThaliTest[2999:6275449] multipeer session: start timer: 0x183270d0
2016-01-27 02:13:51.934 ThaliTest[2999:6275449] THEMultipeerSession initialized peer EprTNOFbJ45Lbb90mJwazA
2016-01-27 02:13:51.934 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

,2016-01-27 02:13:51.936 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:51.936 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:13:51.936 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:51.936 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/6230C79A-380B-4720-B711-4CD6A96753D8/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-27 02:13:52.305 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:52.306 ThaliTest[2999:6275449] server: starting EprTNOFbJ45Lbb90mJwazA.TvgJbQ==
2016-01-27 02:13:52.306 ThaliTest[2999:6275449] multipeer session: start timer: 0x18c98e50
2016-01-27 02:13:52.307 ThaliTest[2999:6275449] THEMultipeerSession initialized peer EprTNOFbJ45Lbb90mJwazA
2016-01-27 02:13:52.307 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-27 02:13:52.308 ThaliTest[2999:6275449] jxcore: stopBroadcasting
2016-01-27 02:13:52.308 ThaliTest[2999:6275449] THEMult,ipeerSession stopping peer
2016-01-27 02:13:52.308 ThaliTest[2999:6275449] multipeer session: stop timer
2016-01-27 02:13:52.309 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/6230C79A-380B-4720-B711-4CD6A96753D8/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-27 02:13:54.911 ThaliTest[2999:6275449] jxcore: startBroadcasting
,2016-01-27 02:13:54.912 ThaliTest[2999:6275449] server: starting EprTNOFbJ45Lbb90mJwazA.wPmZ9g==
2016-01-27 02:13:54.912 ThaliTest[2999:6275449] multipeer session: start timer: 0x18917270
2016-01-27 02:13:54.913 ThaliTest[2999:6275449] THEMultipeerSession initialized peer EprTNOFbJ45Lbb90mJwazA
2016-01-27 02:13:54.913 ThaliTest[2999:6275449] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

,ok 120 deviceName should not be null

,2016-01-27 02:13:57.267 ThaliTest[2999:6275272] client: found peer: K8bnHAzhbDwdDVvV28g_Uw.K+L3Xw==
,2016-01-27 02:13:59.049 ThaliTest[2999:6275449] jxcore: connect K8bnHAzhbDwdDVvV28g_Uw.K+L3Xw==
2016-01-27 02:13:59.049 ThaliTest[2999:6275449] client session: connect
2016-01-27 02:13:59.050 ThaliTest[2999:6275449] client session: stateChange:0->1 K8bnH,AzhbDwdDVvV28g_Uw.K+L3Xw==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-01-27 02:14:01.863 ThaliTest[2999:6275272] multipeer session: reset timer
2016-01-27 02:14:01.863 ThaliTest[2999:6275272] multipeer session: stop timer
2016-01-27 02:14:01.863 ThaliTest[2999:6275272] multipeer session: start timer: 0x18917270
2016-01-27 02:14:01.863 ThaliTest[2999:6275272] server session: connect
2016-01-27 02:14:01.863 ThaliTest[2999:6275272] server session: stateChange:0->1 K8bnHAzhbDwdDVvV28g_Uw
,2016-01-27 02:14:01.865 ThaliTest[2999:6275272] server: accepting invitation K8bnHAzhbDwdDVvV28g_Uw
,2016-01-27 02:14:04.237 ThaliTest[2999:6276336] client session: connected
2016-01-27 02:14:04.237 ThaliTest[2999:6276336] client session: stateChange:1->2 K8bnHAzhbDwdDVvV28g_Uw.K+L3Xw==
,2016-01-27 02:14:04.796 ThaliTest[2999:6276262] client session: fireConnectCallback: K8bnHAzhbDwdDVvV28g_Uw.K+L3Xw==
,2016-01-27 02:14:04.798 ThaliTest[2999:6276262] jxcore: connect: success
,2016-01-27 02:14:04.804 ThaliTest[2999:6275272] client: relay established
2016-01-27 02:14:04.805 ThaliTest[2999:6275272] client: new accepted socket: 0x16552360
,client bridge: new client socket

,client bridge: new client socket

,2016-01-27 02:14:05.056 ThaliTest[2999:6276262] server session: connected
2016-01-27 02:14:05.056 ThaliTest[2999:6276262] server session: stateChange:1->2 K8bnHAzhbDwdDVvV28g_Uw
,2016-01-27 02:14:05.066 ThaliTest[2999:6275272] server relay: connected (to port: 58001)
,server bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

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

,client bridge: new client socket

,Possibly unhandled Error. ETIMEDOUT
onError@/private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:66:18
ajax/<@/private/var/mobile/Containers/Bundle/Applicati,on/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:108:1
Request.prototype.init/self.callback@/private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/node_modules/pouchdb/node_modules/request/request.js:123:7
emit@events.js:82:1
Request.prototype.start/self.timeoutTimer<@/private/var/mobile/Containers/Bundle/Application/50C7A809-9923-4A79-A68F-AAFF3674DD39/ThaliTest.app/www/jxcore/node_modules/pouc,hdb/node_modules/request/request.js:590:7
$9@timers.js:120:1


,client bridge: socket closed

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 123 1st change of remote doc should contain remote id

,ok 124 Can update remote doc without error

null

,{ ok: true,
  id: '1a134c10-277e-4318-bbb9-feab7defc28e',
  rev: '2-54d5a2fc6a2c61023f5c5ab454abfd64' }

,client bridge: new client socket

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

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

,ok 126 Local changes occur in strict order

ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-01-27 02:14:25.913 ThaliTest[2999:6275449] jxcore: stopBroadcasting
,2016-01-27 02:14:25.914 ThaliTest[2999:6275449] THEMultipeerSession stopping peer
2016-01-27 02:14:25.914 ThaliTest[2999:6275449] multipeer session: stop timer
,2016-01-27 02:14:25.914 ThaliTest[2999:6275449] client session: disconnect
2016-01-27 02:14:25.914 ThaliTest[2999:6275449] client session: stateChange:2->0 K8bnHAzhbDwdDVvV28g_Uw.K+L3Xw==
,2016-01-27 02:14:25.917 ThaliTest[2999:6275449] server session: disconnect
,2016-01-27 02:14:25.917 ThaliTest[2999:6275449] server session: stateChange:2->0 K8bnHAzhbDwdDVvV28g_Uw
,2016-01-27 02:14:25.922 ThaliTest[2999:6275449] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,incoming client socket error Error: read ECONNRESET

mux server bridge listener closed

,client bridge: socket closed

server bridge: socket closed

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,# teardown

,client bridge: socket closed

,client bridge: socket closed


```
