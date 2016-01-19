#### Test 564496607226f84_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/564496607226f84/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BC396AAF-B12B-41C8-B1D4-20A2016D1A9A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/BC396AAF-B12B-41C8-B1D4-20A2016D1A9A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/564496607226f84/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/564496607226f84/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/85F84E56-10A2-4B44-85C1-717DE558171C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58501"
,(lldb)     command script import "/tmp/BC396AAF-B12B-41C8-B1D4-20A2016D1A9A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-19 12:11:20.453 ThaliTest[1652:5224187] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EE0FBA5D-5554-4C87-8948-81A317432512/Library/Cookies/Cookies.binarycookies
,2016-01-19 12:11:20.576 ThaliTest[1652:5224187] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-19 12:11:20.578 ThaliTest[1652:5224187] Multi-tasking -> Device: YES, App: YES
,2016-01-19 12:11:20.583 ThaliTest[1652:5224187] Unlimited access to network resources
,2016-01-19 12:11:20.595 ThaliTest[1652:5224187] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-19 12:11:26.143 ThaliTest[1652:5224187] Resetting plugins due to page load.
,2016-01-19 12:11:28.277 ThaliTest[1652:5224187] Finished load of: file:///var/mobile/Containers/Bundle/Application/85F84E56-10A2-4B44-85C1-717DE558171C/ThaliTest.app/www/index.html
,2016-01-19 12:11:28.472 ThaliTest[1652:5224187] JXcore Cordova plugin initializing
2016-01-19 12:11:28.473 ThaliTest[1652:5224370] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/85F84E56-10A2-4B44-85C1-717DE558171C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/85F84E56-10A2-4B44-85C1-717DE558171C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/85F84E56-10A2-4B44-85C1-717DE558171C/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/85F84E56-10A2-4B44-85C1-717DE558171C/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/85F84E56-10A2-4B44-85C1-717DE558171C/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/85F84E56-10A2-4B44-85C1-717DE558171C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/85F84E56-10A2-4B44-85C1-717DE558171C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,
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
,
ok 7 should be equal

ok 8 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 9 (unnamed assert)

,ok 10 (unnamed assert)
,
,ok 11 should not throw

,ok 12 should be equal

ok 13 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 14 should be equal

# setup

,# failed to get mobile documents path

,# teardown

,ok 15 should be equal

# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 16 should be equal

ok 17 should be equal

ok 18 should be equal

# setup

,# #init should register the networkChanged event

,# teardown

,ok 19 should be equal

# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 20 should throw

# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 21 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 22 should throw

# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 23 should throw

# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 24 should throw

,# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 25 should throw

# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 26 should be equal

ok 27 should be equal

ok 28 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 29 should be equal

ok 30 should be equal

ok 31 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 32 should be equal

ok 33 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 34 should be equal

ok 35 should be equal

# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 36 should be equal

ok 37 should be equal

ok 38 should be equal

# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 39 should be equal

,ok 40 should be equal

# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-19 12:16:54.951 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:54.961 ThaliTest[1652:5224370] server: starting 1453202214950.1652.k+a4BQ==
,2016-01-19 12:16:54.964 ThaliTest[1652:5224370] multipeer session: start timer: 0x1b28af00
,2016-01-19 12:16:54.970 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202214950.1652
,2016-01-19 12:16:54.971 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error

,2016-01-19 12:16:54.973 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:16:54.974 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:16:54.975 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:54.978 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:54.982 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:54.985 ThaliTest[1652:5224370] server: starting 1453202214981.1652.HKiIww==
,2016-01-19 12:16:54.986 ThaliTest[1652:5224370] multipeer session: start timer: 0x1b028f60
,2016-01-19 12:16:54.991 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202214981.1652
,2016-01-19 12:16:54.992 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error

,2016-01-19 12:16:54.995 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:16:54.995 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:16:54.996 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:54.999 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:55.003 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:55.007 ThaliTest[1652:5224370] server: starting 1453202215002.1652.hcI9JA==
,2016-01-19 12:16:55.013 ThaliTest[1652:5224370] multipeer session: start timer: 0x1b1dc680
,2016-01-19 12:16:55.017 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202215002.1652
,2016-01-19 12:16:55.018 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error

,2016-01-19 12:16:55.020 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:16:55.020 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:16:55.021 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:55.025 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:55.028 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:55.031 ThaliTest[1652:5224370] server: starting 1453202215027.1652.y/Keyw==
,2016-01-19 12:16:55.033 ThaliTest[1652:5224370] multipeer session: start timer: 0x1b1a1a20
,2016-01-19 12:16:55.040 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202215027.1652
,2016-01-19 12:16:55.041 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error

,2016-01-19 12:16:55.044 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:16:55.045 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:16:55.046 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:55.047 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:55.053 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:55.056 ThaliTest[1652:5224370] server: starting 1453202215052.1652.7ung0A==
,2016-01-19 12:16:55.059 ThaliTest[1652:5224370] multipeer session: start timer: 0x1b1a1c10
,2016-01-19 12:16:55.065 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202215052.1652
,2016-01-19 12:16:55.066 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error

,2016-01-19 12:16:55.068 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:16:55.069 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:16:55.069 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:55.074 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:55.076 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:55.079 ThaliTest[1652:5224370] server: starting 1453202215076.1652.kIGgbQ==
,2016-01-19 12:16:55.084 ThaliTest[1652:5224370] multipeer session: start timer: 0x1b0ed260
,2016-01-19 12:16:55.089 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202215076.1652
,2016-01-19 12:16:55.089 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error

,2016-01-19 12:16:55.092 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:16:55.092 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:16:55.093 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:55.097 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:55.100 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:55.102 ThaliTest[1652:5224370] server: starting 1453202215099.1652.JzTezA==
,2016-01-19 12:16:55.103 ThaliTest[1652:5224370] multipeer session: start timer: 0x1b1a40a0
,2016-01-19 12:16:55.107 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202215099.1652
,2016-01-19 12:16:55.112 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error

,2016-01-19 12:16:55.115 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:16:55.116 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:16:55.116 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:55.117 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,
,2016-01-19 12:16:55.123 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:55.125 ThaliTest[1652:5224370] server: starting 1453202215123.1652.f3Km6g==
,2016-01-19 12:16:55.129 ThaliTest[1652:5224370] multipeer session: start timer: 0x1b1a4680
,2016-01-19 12:16:55.133 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202215123.1652
,2016-01-19 12:16:55.135 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error

,2016-01-19 12:16:55.139 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:16:55.139 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:16:55.140 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:55.145 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:55.149 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:55.151 ThaliTest[1652:5224370] server: starting 1453202215148.1652.3o0AtQ==
,2016-01-19 12:16:55.155 ThaliTest[1652:5224370] multipeer session: start timer: 0x1b187d40
,2016-01-19 12:16:55.157 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202215148.1652
,2016-01-19 12:16:55.159 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error

,2016-01-19 12:16:55.163 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:16:55.164 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:16:55.164 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:55.166 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:55.173 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:55.175 ThaliTest[1652:5224370] server: starting 1453202215172.1652.qP6g5Q==
,2016-01-19 12:16:55.176 ThaliTest[1652:5224370] multipeer session: start timer: 0x1b0ecdb0
,2016-01-19 12:16:55.178 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202215172.1652
,2016-01-19 12:16:55.179 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

,2016-01-19 12:16:55.187 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:16:55.188 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:16:55.188 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:55.193 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-19 12:16:55.379 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:55.381 ThaliTest[1652:5224370] server: starting 1453202215378.1652.Ne6RLw==
2016-01-19 12:16:55.382 ThaliTest[1652:5224370] multipeer session: start timer: 0x1ae08480
2016-01-19 12:16:55.382 ThaliTest[1652:5224370] THEMultipeerSession in,itialized peer 1453202215378.1652
2016-01-19 12:16:55.382 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-01-19 12:16:55.384 ThaliTest[1652:5224370] jxcore: startBroadcasting,
2016-01-19 12:16:55.384 ThaliTest[1652:5224370] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice

,2016-01-19 12:16:55.386 ThaliTest[1652:5224370] jxcore: stopBroadcasting
2016-01-19 12:16:55.393 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
2016-01-19 12:16:55.394 ThaliTest[1652:5224370] multipeer session: stop timer
2016-01-19 12:16:55.,394 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-19 12:16:56.793 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:56.795 ThaliTest[1652:5224370] server: starting 1453202216793.1652.Dy9+6A==
2016-01-19 12:16:56.796 ThaliTest[1652:5224370] multipeer session: start timer: 0x1ae247d0
2016-01-19 12:16:56.796 ThaliTest[1652:5224370] THEMultipeerSession in,itialized peer 1453202216793.1652
2016-01-19 12:16:56.796 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

2016-01-19 12:16:56.797 ThaliTest[1652:5224370] jxcore: connect foobar
2016-01-19 12:16:56.798 ThaliTest[1652:5224370] client: unknown peer foobar
,2016-01-19 12:16:56.798 ThaliTest[1652:5224370] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer

2016-01-19 12:16:56.807 ThaliTest[1652:5224370] jxcore: stopBroadcasting
2016-01-19 12:16:56.807 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
2016-01-19 12:16:56.808 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:16:56.808 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-19 12:16:56.903 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:56.906 ThaliTest[1652:5224370] server: starting 1453202216902.1652.XtvbrA==
2016-01-19 12:16:56.906 ThaliTest[1652:5224370] multipeer session: start timer: 0x1aeb85d0
2016-01-19 12:16:56.906 ThaliTest[1652:5224370] THEMultipeerSession in,itialized peer 1453202216902.1652
2016-01-19 12:16:56.907 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-01-19 12:16:56.908 ThaliTest[1652:5224370] jxcore: disconnect
2016-,01-19 12:16:56.908 ThaliTest[1652:5224370] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 

,2016-01-19 12:16:56.911 ThaliTest[1652:5224370] jxcore: stopBroadcasting
2016-01-19 12:16:56.916 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
2016-01-19 12:16:56.916 ThaliTest[1652:5224370] multipeer session: stop timer
2016-01-19 12:16:56.,916 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-19 12:16:56.969 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:16:56.972 ThaliTest[1652:5224370] server: starting 1453202216968.1652.4HZheQ==
2016-01-19 12:16:56.973 ThaliTest[1652:5224370] multipeer session: start timer: 0x1af1fa30
2016-01-19 12:16:56.973 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202216968.1652
2016-01-19 12:16:56.973 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-01-19 12:16:58.297 ThaliTest[1652:5224187] client: found peer: 1453202219855.2347.LJcwKA==
2016-01-19 12:16:58.298 ThaliTest[1652:5224370] jxcore: connect 1453202219855.2347.LJcwKA==
2016-01-19 12:16:58.299 ThaliTest[1652:5224370] client session: co,nnect
2016-01-19 12:16:58.299 ThaliTest[1652:5224370] client session: stateChange:0->1 1453202219855.2347.LJcwKA==
,2016-01-19 12:16:59.012 ThaliTest[1652:5224187] multipeer session: reset timer
2016-01-19 12:16:59.013 ThaliTest[1652:5224187] multipeer session: stop timer
2016-01-19 12:16:59.013 ThaliTest[1652:5224187] multipeer session: start timer: 0x1af1fa30
2016-,01-19 12:16:59.013 ThaliTest[1652:5224187] server session: connect
2016-01-19 12:16:59.015 ThaliTest[1652:5224187] server session: stateChange:0->1 1453202219855.2347
2016-01-19 12:16:59.022 ThaliTest[1652:5224187] server: accepting invitation 1453202219855.2347
,2016-01-19 12:17:03.104 ThaliTest[1652:5225102] server session: connected
2016-01-19 12:17:03.104 ThaliTest[1652:5225102] server session: stateChange:1->2 1453202219855.2347
,2016-01-19 12:17:03.164 ThaliTest[1652:5224187] server relay: socket disconnected
2016-01-19 12:17:03.165 ThaliTest[1652:5224187] server relay: 0x1b1dc270 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 12:17:03.191 ThaliTest[1652:5225100] server session: not connected 1453202219855.2347
,2016-01-19 12:17:03.224 ThaliTest[1652:5225100] client session: connected
,2016-01-19 12:17:03.228 ThaliTest[1652:5225100] client session: stateChange:1->2 1453202219855.2347.LJcwKA==
,2016-01-19 12:17:03.273 ThaliTest[1652:5225100] client session: fireConnectCallback: 1453202219855.2347.LJcwKA==
,2016-01-19 12:17:03.273 ThaliTest[1652:5225100] jxcore: connect: success
,ok 75 Should be able to connect without error

,ok 76 Port should be within range

,2016-01-19 12:17:03.277 ThaliTest[1652:5224370] jxcore: disconnect
,2016-01-19 12:17:03.278 ThaliTest[1652:5224370] client session: disconnectFromPeer: 1453202219855.2347.LJcwKA==
,2016-01-19 12:17:03.278 ThaliTest[1652:5224370] client session: disconnect
,2016-01-19 12:17:03.279 ThaliTest[1652:5224370] client session: stateChange:2->0 1453202219855.2347.LJcwKA==
,2016-01-19 12:17:03.296 ThaliTest[1652:5224370] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-19 12:17:03.804 ThaliTest[1652:5224370] jxcore: stopBroadcasting
2016-01-19 12:17:03.804 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
2016-01-19 12:17:03.804 ThaliTest[1652:5224370] multipeer session: stop timer
2016-01-19 12:17:03.,805 ThaliTest[1652:5224370] server session: disconnect
2016-01-19 12:17:03.805 ThaliTest[1652:5224370] server session: stateChange:2->0 1453202219855.2347
,2016-01-19 12:17:04.917 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-19 12:17:05.159 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:17:05.162 ThaliTest[1652:5224370] server: starting 1453202225159.1652.roQP/w==
2016-01-19 12:17:05.162 ThaliTest[1652:5224370] multipeer session: start timer: 0x14d9fc80
2016-01-19 12:17:05.163 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202225159.1652
2016-01-19 12:17:05.163 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-19 12:17:06.120 ThaliTest[1652:5224187] client: found peer: 1453202228051.2347.NX/3vw==
2016-01-19 12:17:06.121 ThaliTest[1652:5224370] jxcore: connect 1453202228051.2347.NX/3vw==
2016-01-19 12:17:06.121 ThaliTest[1652:5224370] client session: connect
2016-01-19 12:17:06.121 ThaliTest[1652:5224370] client session: stateChange:0->1 1453202228051.2347.NX/3vw==
,2016-01-19 12:17:06.221 ThaliTest[1652:5224187] multipeer session: reset timer
2016-01-19 12:17:06.221 ThaliTest[1652:5224187] multipeer session: stop timer
2016-01-19 12:17:06.221 ThaliTest[1652:5224187] multipeer session: start timer: 0x14d9fc80
2016-01-19 12:17:06.221 ThaliTest[1652:5224187] server session: connect
2016-01-19 12:17:06.222 ThaliTest[1652:5224187] server session: stateChange:0->1 1453202228051.2347
,2016-01-19 12:17:06.227 ThaliTest[1652:5224187] server: accepting invitation 1453202228051.2347
,2016-01-19 12:17:10.789 ThaliTest[1652:5225100] server session: connected
,2016-01-19 12:17:10.789 ThaliTest[1652:5225100] server session: stateChange:1->2 1453202228051.2347
,2016-01-19 12:17:10.816 ThaliTest[1652:5224187] server relay: socket disconnected
2016-01-19 12:17:10.817 ThaliTest[1652:5224187] server relay: 0x1ae77a10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 12:17:10.831 ThaliTest[1652:5225134] server session: not connected 1453202228051.2347
,2016-01-19 12:17:11.025 ThaliTest[1652:5225134] client session: connected
2016-01-19 12:17:11.025 ThaliTest[1652:5225134] client session: stateChange:1->2 1453202228051.2347.NX/3vw==
,2016-01-19 12:17:11.081 ThaliTest[1652:5225097] client session: fireConnectCallback: 1453202228051.2347.NX/3vw==
2016-01-19 12:17:11.081 ThaliTest[1652:5225097] jxcore: connect: success
ok 79 Should be able to connect without error

ok 80 Port should b,e within range

2016-01-19 12:17:11.083 ThaliTest[1652:5224370] jxcore: connect 1453202228051.2347.NX/3vw==
2016-01-19 12:17:11.083 ThaliTest[1652:5224370] client: already connect(ing/ed) to 1453202228051.2347.NX/3vw==
2016-01-19 12:17:11.083 ThaliTest,[1652:5224370] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect

2016-01-19 12:17:11.085 ThaliTest[1652:5224370] jxcore: disconnect
,2016-01-19 12:17:11.085 ThaliTest[1652:5224370] client session: disconnectFromPeer: 1453202228051.2347.NX/3vw==
2016-01-19 12:17:11.089 ThaliTest[1652:5224370] client session: disconnect
2016-01-19 12:17:11.089 ThaliTest[1652:5224370] client session: sta,teChange:2->0 1453202228051.2347.NX/3vw==
,2016-01-19 12:17:11.104 ThaliTest[1652:5224370] jxcore: disconnect: success
ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-19 12:17:11.147 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:17:11.147 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
2016-01-19 12:17:11.147 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:17:11.150 ThaliTest[1652:5224370] server session: disconnect
,2016-01-19 12:17:11.153 ThaliTest[1652:5224370] server session: stateChange:2->0 1453202228051.2347
,2016-01-19 12:17:11.299 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-19 12:17:11.666 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:17:11.669 ThaliTest[1652:5224370] server: starting 1453202231666.1652.IIgVBA==
2016-01-19 12:17:11.670 ThaliTest[1652:5224370] multipeer session: start timer: 0x1af79240
2016-01-19 12:17:11.670 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202231666.1652
2016-01-19 12:17:11.670 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-19 12:17:12.904 ThaliTest[1652:5224187] multipeer session: reset timer
2016-01-19 12:17:12.905 ThaliTest[1652:5224187] multipeer session: stop timer
2016-01-19 12:17:12.905 ThaliTest[1652:5224187] multipeer session: start timer: 0x1af79240
2016-,01-19 12:17:12.905 ThaliTest[1652:5224187] server session: connect
2016-01-19 12:17:12.905 ThaliTest[1652:5224187] server session: stateChange:0->1 1453202234529.2347
,2016-01-19 12:17:12.912 ThaliTest[1652:5224187] server: accepting invitation 1453202234529.2347
,2016-01-19 12:17:13.063 ThaliTest[1652:5224187] client: found peer: 1453202234529.2347.hGE8XQ==
,2016-01-19 12:17:13.065 ThaliTest[1652:5224370] jxcore: connect 1453202234529.2347.hGE8XQ==
2016-01-19 12:17:13.065 ThaliTest[1652:5224370] client session: connect
2016-01-19 12:17:13.065 ThaliTest[1652:5224370] client session: stateChange:0->1 145320223,4529.2347.hGE8XQ==
,2016-01-19 12:17:17.505 ThaliTest[1652:5225097] server session: connected
2016-01-19 12:17:17.506 ThaliTest[1652:5225097] server session: stateChange:1->2 1453202234529.2347
,2016-01-19 12:17:17.512 ThaliTest[1652:5224187] server relay: socket disconnected
2016-01-19 12:17:17.512 ThaliTest[1652:5224187] server relay: 0x1ae54c10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 12:17:17.566 ThaliTest[1652:5225100] server session: not connected 1453202234529.2347
,2016-01-19 12:17:18.027 ThaliTest[1652:5225100] client session: connected
2016-01-19 12:17:18.027 ThaliTest[1652:5225100] client session: stateChange:1->2 1453202234529.2347.hGE8XQ==
,2016-01-19 12:17:18.034 ThaliTest[1652:5225100] client session: fireConnectCallback: 1453202234529.2347.hGE8XQ==
2016-01-19 12:17:18.034 ThaliTest[1652:5225100] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should b,e within range

2016-01-19 12:17:18.036 ThaliTest[1652:5224370] jxcore: disconnect
2016-01-19 12:17:18.037 ThaliTest[1652:5224370] client session: disconnectFromPeer: 1453202234529.2347.hGE8XQ==
2016-01-19 12:17:18.037 ThaliTest[1652:5224370] client se,ssion: disconnect
2016-01-19 12:17:18.037 ThaliTest[1652:5224370] client session: stateChange:2->0 1453202234529.2347.hGE8XQ==
,2016-01-19 12:17:18.112 ThaliTest[1652:5224370] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,2016-01-19 12:17:18.114 ThaliTest[1652:5224370] jxcore: disconnect
,2016-01-19 12:17:18.114 ThaliTest[1652:5224370] jxcore: disconnect: fail
,ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-19 12:17:18.418 ThaliTest[1652:5224370] jxcore: stopBroadcasting
2016-01-19 12:17:18.419 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
2016-01-19 12:17:18.419 ThaliTest[1652:5224370] multipeer session: stop timer
2016-01-19 12:17:18.419 ThaliTest[1652:5224370] server session: disconnect
2016-01-19 12:17:18.419 ThaliTest[1652:5224370] server session: stateChange:2->0 1453202234529.2347
,2016-01-19 12:17:18.423 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data
,
,# teardown

,echo server started on port: 55225

,2016-01-19 12:17:20.054 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:17:20.063 ThaliTest[1652:5224370] server: starting 1453202240054.1652.x95b4Q==
,2016-01-19 12:17:20.065 ThaliTest[1652:5224370] multipeer session: start timer: 0x1af73800
,2016-01-19 12:17:20.071 ThaliTest[1652:5224370] THEMultipeerSession initialized peer 1453202240054.1652
,2016-01-19 12:17:20.072 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error

,2016-01-19 12:17:20.116 ThaliTest[1652:5224187] client: found peer: 1453202241882.2347.pKmhzQ==
2016-01-19 12:17:20.117 ThaliTest[1652:5224370] jxcore: connect 1453202241882.2347.pKmhzQ==
,2016-01-19 12:17:20.117 ThaliTest[1652:5224370] client session: connect
,2016-01-19 12:17:20.120 ThaliTest[1652:5224370] client session: stateChange:0->1 1453202241882.2347.pKmhzQ==
,2016-01-19 12:17:21.298 ThaliTest[1652:5224187] multipeer session: reset timer
,2016-01-19 12:17:21.299 ThaliTest[1652:5224187] multipeer session: stop timer
2016-01-19 12:17:21.299 ThaliTest[1652:5224187] multipeer session: start timer: 0x1af73800
2016-01-19 12:17:21.300 ThaliTest[1652:5224187] server session: connect
2016-01-19 12:17:21.300 ThaliTest[1652:5224187] server session: stateChange:0->1 1453202241882.2347
2016-01-19 12:17:21.305 ThaliTest[1652:5224187] server: accepting invitation 1453202241882.2347
,2016-01-19 12:17:23.576 ThaliTest[1652:5225100] client session: connected
2016-01-19 12:17:23.582 ThaliTest[1652:5225100] client session: stateChange:1->2 1453202241882.2347.pKmhzQ==
,2016-01-19 12:17:23.585 ThaliTest[1652:5225100] client session: fireConnectCallback: 1453202241882.2347.pKmhzQ==
2016-01-19 12:17:23.587 ThaliTest[1652:5225100] jxcore: connect: success
,ok 89 Should be able to connect without error

ok 90 Port should be within range

2016-01-19 12:17:23.594 ThaliTest[1652:5224187] client: relay established
2016-01-19 12:17:23.594 ThaliTest[1652:5224187] client: new accepted socket: 0x1aba0e50
,data in 36064
,
,data in 42705

,data in 64605
,
,data in 73294

,data in 78840

,data in 79935

,data in 85410

,data in 89790

,data in 95265

,data in 108192

,data in 127020

,data in 131072

ok 91 the test messages should be equal

2016-01-19 12:17:23.990 ThaliTest[1652:5224370] jxcore: disconnect
2016-01-19 12:17:23.991 ThaliTest[1652:5224370] client session: disconnectFromPeer: 1453202241882.2347.pKmhzQ==
2016-01-19 12:17:23.991 ThaliTest[1652:5224370] client session: disconnect
2016-01-19 12:17:23.991 ThaliTest[1652:5224370] client session: stateChange:2->0 1453202241882.2347.pKmhzQ==
,2016-01-19 12:17:24.005 ThaliTest[1652:5224370] jxcore: disconnect: success
,ok 92 Should be able to disconnect without error
,
,setting stopBroadcasting callback and ending test.
,
,# setup

,2016-01-19 12:17:24.576 ThaliTest[1652:5225097] server session: connected
2016-01-19 12:17:24.576 ThaliTest[1652:5225097] server session: stateChange:1->2 1453202241882.2347
,2016-01-19 12:17:24.594 ThaliTest[1652:5224187] server relay: connected (to port: 55225)
,2016-01-19 12:17:25.162 ThaliTest[1652:5225134] server session: not connected 1453202241882.2347
,calling stopBroadcasting

,2016-01-19 12:17:25.234 ThaliTest[1652:5224370] jxcore: stopBroadcasting
2016-01-19 12:17:25.234 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
2016-01-19 12:17:25.235 ThaliTest[1652:5224370] multipeer session: stop timer
2016-01-19 12:17:25.,235 ThaliTest[1652:5224370] server session: disconnect
2016-01-19 12:17:25.235 ThaliTest[1652:5224370] server session: stateChange:2->0 1453202241882.2347
,2016-01-19 12:17:25.240 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 55231

2016-01-19 12:17:26.772 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:17:26.775 ThaliTest[1652:5224370] server: starting 1453202246772.1652.9JbJyg==
2016-01-19 12:17:26.775 ThaliTest[1652:5224370] multipeer session: start timer: 0x1ad07020
2016-01-19 12:17:26.775 ThaliTest[1652:5224370] THEMultipeerSession in,itialized peer 1453202246772.1652
2016-01-19 12:17:26.776 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error

,2016-01-19 12:17:27.591 ThaliTest[1652:5224187] client: found peer: 1453202249606.2347.3ZDcdg==
[{"peerIdentifier":"1453202249606.2347.3ZDcdg==","peerName":"(null)","peerAvailable":true}]

2016-01-19 12:17:27.593 ThaliTest[1652:5224370] jxcore: connect ,1453202249606.2347.3ZDcdg==
2016-01-19 12:17:27.593 ThaliTest[1652:5224370] client session: connect
2016-01-19 12:17:27.594 ThaliTest[1652:5224370] client session: stateChange:0->1 1453202249606.2347.3ZDcdg==
,2016-01-19 12:17:28.364 ThaliTest[1652:5224187] multipeer session: reset timer
2016-01-19 12:17:28.364 ThaliTest[1652:5224187] multipeer session: stop timer
2016-01-19 12:17:28.364 ThaliTest[1652:5224187] multipeer session: start timer: 0x1ad07020
2016-,01-19 12:17:28.364 ThaliTest[1652:5224187] server session: connect
2016-01-19 12:17:28.364 ThaliTest[1652:5224187] server session: stateChange:0->1 1453202249606.2347
,2016-01-19 12:17:28.370 ThaliTest[1652:5224187] server: accepting invitation 1453202249606.2347
,2016-01-19 12:17:32.449 ThaliTest[1652:5225134] server session: connected
2016-01-19 12:17:32.450 ThaliTest[1652:5225134] server session: stateChange:1->2 1453202249606.2347
,2016-01-19 12:17:32.458 ThaliTest[1652:5225100] client session: connected
,2016-01-19 12:17:32.459 ThaliTest[1652:5225100] client session: stateChange:1->2 1453202249606.2347.3ZDcdg==
,2016-01-19 12:17:32.462 ThaliTest[1652:5225100] client session: fireConnectCallback: 1453202249606.2347.3ZDcdg==
,2016-01-19 12:17:32.464 ThaliTest[1652:5225100] jxcore: connect: success
,2016-01-19 12:17:32.464 ThaliTest[1652:5224187] server relay: connected (to port: 55231)
ok 94 Should be able to connect without error

,ok 95 Port should be within range

,ok 96 First connect should succeed

,2016-01-19 12:17:32.492 ThaliTest[1652:5224187] client: relay established
2016-01-19 12:17:32.492 ThaliTest[1652:5224187] client: new accepted socket: 0x1ae91e60
,ok 97 the test messages should be equal

,ok 98 First send should succeed

,2016-01-19 12:17:32.580 ThaliTest[1652:5224187] client: socket closed
2016-01-19 12:17:32.580 ThaliTest[1652:5224187] client relay: socket disconnected
2016-01-19 12:17:32.581 ThaliTest[1652:5224187] client relay: 0x1ae91e60 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 12:17:32.581 ThaliTest[1652:5224187] client session: socket closed: 1453202249606.2347.3ZDcdg==
2016-01-19 ,12:17:32.581 ThaliTest[1652:5224187] client session: onLinkFailure: 1453202249606.2347.3ZDcdg==
2016-01-19 12:17:32.581 ThaliTest[1652:5224187] client session: disconnect
2016-01-19 12:17:32.581 ThaliTest[1652:5224187] client session: stateChange:2->0 1453202249606.2347.3ZDcdg==
,2016-01-19 12:17:32.594 ThaliTest[1652:5224187] client session: fireConnectionErrorEvent: 1453202249606.2347.3ZDcdg==
2016-01-19 12:17:32.596 ThaliTest[1652:5224370] jxcore: connect 1453202249606.2347.3ZDcdg==
2016-01-19 12:17:32.596 ThaliTest[1652:5224370] client session: connect
,2016-01-19 12:17:32.596 ThaliTest[1652:5224370] client session: stateChange:0->1 1453202249606.2347.3ZDcdg==
,2016-01-19 12:17:32.653 ThaliTest[1652:5225100] server session: not connected 1453202249606.2347
,2016-01-19 12:17:32.770 ThaliTest[1652:5224187] multipeer session: reset timer
2016-01-19 12:17:32.770 ThaliTest[1652:5224187] multipeer session: stop timer
2016-01-19 12:17:32.770 ThaliTest[1652:5224187] multipeer session: start timer: 0x1ad07020
2016-,01-19 12:17:32.770 ThaliTest[1652:5224187] server: disconnecting to refresh session (1453202249606.2347)
2016-01-19 12:17:32.770 ThaliTest[1652:5224187] server session: disconnect
2016-01-19 12:17:32.770 ThaliTest[1652:5224187] server session: stateChang,e:2->0 1453202249606.2347
2016-01-19 12:17:32.774 ThaliTest[1652:5224187] server session: connect
2016-01-19 12:17:32.775 ThaliTest[1652:5224187] server session: stateChange:0->1 1453202249606.2347
,2016-01-19 12:17:32.787 ThaliTest[1652:5224187] server: accepting invitation 1453202249606.2347
,2016-01-19 12:17:36.705 ThaliTest[1652:5225097] client session: connected
2016-01-19 12:17:36.705 ThaliTest[1652:5225097] client session: stateChange:1->2 1453202249606.2347.3ZDcdg==
,2016-01-19 12:17:36.715 ThaliTest[1652:5225098] server session: connected
2016-01-19 12:17:36.715 ThaliTest[1652:5225098] server session: stateChange:1->2 1453202249606.2347
2016-01-19 12:17:36.719 ThaliTest[1652:5225097] client session: fireConnectCallback: 1453202249606.2347.3ZDcdg==
2016-01-19 12:17:36.719 ThaliTest[1652:5225097] jxcore: connect: success
ok 99 Should be able to connect without error

ok 100 Port should be within range

ok 101 Second connect should succeed

,2016-01-19 12:17:36.748 ThaliTest[1652:5224187] server relay: connected (to port: 55231)
,2016-01-19 12:17:36.752 ThaliTest[1652:5224187] client: relay established
2016-01-19 12:17:36.753 ThaliTest[1652:5224187] client: new accepted socket: 0x1ab3fb90
,ok 102 the test messages should be equal

,ok 103 Second send should succeed

,# setup

,2016-01-19 12:17:36.915 ThaliTest[1652:5224187] client: socket closed
2016-01-19 12:17:36.915 ThaliTest[1652:5224187] client relay: socket disconnected
2016-01-19 12:17:36.916 ThaliTest[1652:5224187] client relay: 0x1ab3fb90 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 12:17:36.916 ThaliTest[1652:5224187] client session: socket closed: 1453202249606.2347.3ZDcdg==
2016-01-19 ,12:17:36.916 ThaliTest[1652:5224187] client session: onLinkFailure: 1453202249606.2347.3ZDcdg==
2016-01-19 12:17:36.916 ThaliTest[1652:5224187] client session: disconnect
2016-01-19 12:17:36.916 ThaliTest[1652:5224187] client session: stateChange:2->0 1453202249606.2347.3ZDcdg==
,2016-01-19 12:17:36.935 ThaliTest[1652:5224187] client session: fireConnectionErrorEvent: 1453202249606.2347.3ZDcdg==
,2016-01-19 12:17:36.940 ThaliTest[1652:5225100] server session: not connected 1453202249606.2347
,calling stopBroadcasting

2016-01-19 12:17:38.398 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:17:38.399 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:17:38.399 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:17:38.400 ThaliTest[1652:5224370] server session: disconnect
2016-01-19 12:17:38.400 ThaliTest[1652:5224370] server session: stateChange:2->0 1453202249606.2347
2016-01-19 12:17:38.404 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/EE0FBA5D-5554-4C87-8948-81A317432512/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 104 starting event should occur in right order

,2016-01-19 12:17:38.850 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:17:38.853 ThaliTest[1652:5224370] server: starting WmTqlEsC6-WPOc6VpbrhxQ.YmrqZg==
2016-01-19 12:17:38.854 ThaliTest[1652:5224370] multipeer session: start timer: 0x1ab977b0
2016-01-19 12:17:38.854 ThaliTest[1652:5224370] THEMultipeerSessio,n initialized peer WmTqlEsC6-WPOc6VpbrhxQ
2016-01-19 12:17:38.854 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
ok 105 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 106 stopping event sh,ould occur in right order

About to call stopBroadcasting

2016-01-19 12:17:38.856 ThaliTest[1652:5224370] jxcore: stopBroadcasting
2016-01-19 12:17:38.856 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:17:38.857 ThaliTest[1652:5224370] multipeer session: stop timer
2016-01-19 12:17:38.861 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 107 stopped event should occur in ,right order

mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/EE0FBA5D-5554-4C87-8948-81A317432512/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 12:17:39.000 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:17:39.003 ThaliTest[1652:5224370] server: starting WmTqlEsC6-WPOc6VpbrhxQ.BBcPWg==
2016-01-19 12:17:39.003 ThaliTest[1652:5224370] multipeer session: start timer: 0x1aba5c90
2016-01-19 12:17:39.004 ThaliTest[1652:5224370] THEMultipeerSession initialized peer WmTqlEsC6-WPOc6VpbrhxQ
2016-01-19 12:17:39.004 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error

ok 109 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-01-19 12:17:39.006 ThaliTest[1652:5224370] jxcore: stopBroadcasting
2016-01-19 12:17:39.006 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:17:39.006 ThaliTest[1652:5224370] multipeer session: stop timer
2016-01-19 12:17:39.013 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/EE0FBA5D-5554-4C87-8948-81A317432512/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 12:17:43.980 ThaliTest[1652:5224370] jxcore: startBroadcasting
,2016-01-19 12:17:43.983 ThaliTest[1652:5224370] server: starting WmTqlEsC6-WPOc6VpbrhxQ.+7evPw==
2016-01-19 12:17:43.984 ThaliTest[1652:5224370] multipeer session: start timer: 0x1c862de0
2016-01-19 12:17:43.984 ThaliTest[1652:5224370] THEMultipeerSessio,n initialized peer WmTqlEsC6-WPOc6VpbrhxQ
2016-01-19 12:17:43.984 ThaliTest[1652:5224370] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error

ok 111 deviceName should not be null

,2016-01-19 12:17:44.045 ThaliTest[1652:5224187] client: found peer: 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
,2016-01-19 12:17:54.166 ThaliTest[1652:5224370] jxcore: connect 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
,2016-01-19 12:17:54.176 ThaliTest[1652:5224370] client session: connect
,2016-01-19 12:17:54.177 ThaliTest[1652:5224370] client session: stateChange:0->1 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
,2016-01-19 12:17:54.257 ThaliTest[1652:5224187] multipeer session: reset timer
2016-01-19 12:17:54.257 ThaliTest[1652:5224187] multipeer session: stop timer
2016-01-19 12:17:54.257 ThaliTest[1652:5224187] multipeer session: start timer: 0x1c862de0
2016-01-19 12:17:54.258 ThaliTest[1652:5224187] server session: connect
2016-01-19 12:17:54.258 ThaliTest[1652:5224187] server session: stateChange:0->1 2FMISDbp3IDib7dtBEIkVg
,2016-01-19 12:17:54.267 ThaliTest[1652:5224187] server: accepting invitation 2FMISDbp3IDib7dtBEIkVg
,ok 112 Should be able to put doc without error

,ok 113 1st change of local doc should contain local id

,2016-01-19 12:17:58.453 ThaliTest[1652:5225283] server session: connected
2016-01-19 12:17:58.454 ThaliTest[1652:5225283] server session: stateChange:1->2 2FMISDbp3IDib7dtBEIkVg
,2016-01-19 12:17:58.650 ThaliTest[1652:5225097] client session: connected
2016-01-19 12:17:58.650 ThaliTest[1652:5225097] client session: stateChange:1->2 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
,2016-01-19 12:17:58.906 ThaliTest[1652:5224187] server relay: connected (to port: 55246)
server bridge: new client socket

,2016-01-19 12:17:59.078 ThaliTest[1652:5225263] client session: fireConnectCallback: 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
2016-01-19 12:17:59.078 ThaliTest[1652:5225263] jxcore: connect: success
2016-01-19 12:17:59.083 ThaliTest[1652:5224187] client: relay established
,2016-01-19 12:17:59.084 ThaliTest[1652:5224187] client: new accepted socket: 0x1b076a10
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

client bridge: socket closed
,
,client bridge: new client socket
,
,ok 114 1st change of remote doc should contain remote id

,ok 115 Can update remote doc without error

,null

,{ ok: true,
  id: '257dfbe5-7aeb-4f70-aa23-95f671e24f46',
  rev: '2-c13dd5798b63eacfba874081694a30fa' }

,client bridge: new client socket

,ok 116 Remote changes occur in strict order

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed

,client bridge: new client socket

,ok 117 Local changes occur in strict order

ok 118 2nd change of local doc should contain remote id

,# setup

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket
,
,2016-01-19 12:18:15.621 ThaliTest[1652:5225283] server session: not connected 2FMISDbp3IDib7dtBEIkVg
,2016-01-19 12:18:15.645 ThaliTest[1652:5225283] client session: not connected 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
2016-01-19 12:18:15.646 ThaliTest[1652:5225283] client session: onLinkFailure: 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
,2016-01-19 12:18:15.647 ThaliTest[1652:5225283] client session: disconnect
,2016-01-19 12:18:15.647 ThaliTest[1652:5225283] client session: stateChange:2->0 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
,2016-01-19 12:18:15.808 ThaliTest[1652:5225283] client session: fireConnectionErrorEvent: 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
,2016-01-19 12:18:15.814 ThaliTest[1652:5224370] jxcore: disconnect
,2016-01-19 12:18:15.815 ThaliTest[1652:5224370] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer
,
,2016-01-19 12:18:15.822 ThaliTest[1652:5224370] jxcore: connect 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
,2016-01-19 12:18:15.823 ThaliTest[1652:5224370] client session: connect
,2016-01-19 12:18:15.823 ThaliTest[1652:5224370] client session: stateChange:0->1 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
,client bridge: socket closed
,
,Now in TRM stop

,State of this._isStarted: true

About to call stopBroadcasting

,2016-01-19 12:18:16.339 ThaliTest[1652:5224370] jxcore: stopBroadcasting
,2016-01-19 12:18:16.340 ThaliTest[1652:5224370] THEMultipeerSession stopping peer
,2016-01-19 12:18:16.340 ThaliTest[1652:5224370] multipeer session: stop timer
,2016-01-19 12:18:16.341 ThaliTest[1652:5224370] client session: disconnect
,2016-01-19 12:18:16.341 ThaliTest[1652:5224370] client session: stateChange:1->0 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
,2016-01-19 12:18:16.342 ThaliTest[1652:5224370] server session: disconnect
,2016-01-19 12:18:16.343 ThaliTest[1652:5224370] server session: stateChange:2->0 2FMISDbp3IDib7dtBEIkVg
,2016-01-19 12:18:16.414 ThaliTest[1652:5224370] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,mux server bridge listener closed

,server bridge: socket closed

,# teardown

,ok 119 should be equal

,# setup

,# #startUpdateAdvertisingAndListening should use different USN after every invocation

,# teardown

,ok 120 should not be equal

,# setup

,# verify that Thali-specific messages are filtered correctly

,# teardown

,ok 121 irrelevant messages should be ignored

ok 122 relevant messages should not be ignored

ok 123 messages from this device should be ignored

# setup

,# #start should fail if called twice in a row

,# teardown

,ok 124 specific error should be received

,# setup

,# #start should start hosting given router object

,# teardown

,ok 125 server should respond with code 200

,# setup

,# #stop can be called multiple times in a row

,# teardown

,ok 126 should be in stopped state

ok 127 should still be in stopped state

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
