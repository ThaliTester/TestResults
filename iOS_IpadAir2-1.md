#### Test 564496607226f84_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/564496607226f84/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/C5B58438-C978-4EEE-8CD7-2F0B08CF943D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C5B58438-C978-4EEE-8CD7-2F0B08CF943D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/564496607226f84/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/564496607226f84/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/565C3ADD-30D5-422B-A2D4-9BB4020A4C66/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58504"
,(lldb)     command script import "/tmp/C5B58438-C978-4EEE-8CD7-2F0B08CF943D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-19 12:11:27.929 ThaliTest[2347:5044653] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DAB83158-66F2-4D69-A12D-D1AAFD81B6C4/Library/Cookies/Cookies.binarycookies
,2016-01-19 12:11:28.155 ThaliTest[2347:5044653] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-19 12:11:28.156 ThaliTest[2347:5044653] Multi-tasking -> Device: YES, App: YES
,2016-01-19 12:11:28.162 ThaliTest[2347:5044653] Unlimited access to network resources
,2016-01-19 12:11:28.167 ThaliTest[2347:5044653] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-19 12:11:32.382 ThaliTest[2347:5044653] Resetting plugins due to page load.
,2016-01-19 12:11:33.850 ThaliTest[2347:5044653] Finished load of: file:///var/mobile/Containers/Bundle/Application/565C3ADD-30D5-422B-A2D4-9BB4020A4C66/ThaliTest.app/www/index.html
,2016-01-19 12:11:33.988 ThaliTest[2347:5044653] JXcore Cordova plugin initializing
,2016-01-19 12:11:33.989 ThaliTest[2347:5044825] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/565C3ADD-30D5-422B-A2D4-9BB4020A4C66/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/565C3ADD-30D5-422B-A2D4-9BB4020A4C66/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/565C3ADD-30D5-422B-A2D4-9BB4020A4C66/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/565C3ADD-30D5-422B-A2D4-9BB4020A4C66/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/565C3ADD-30D5-422B-A2D4-9BB4020A4C66/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/565C3ADD-30D5-422B-A2D4-9BB4020A4C66/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/565C3ADD-30D5-422B-A2D4-9BB4020A4C66/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 28 should be equal

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

,2016-01-19 12:16:57.841 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:57.847 ThaliTest[2347:5044825] server: starting 1453202217841.2347.6Drl+g==
,2016-01-19 12:16:57.847 ThaliTest[2347:5044825] multipeer session: start timer: 0x19f45b50
,2016-01-19 12:16:57.847 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202217841.2347
2016-01-19 12:16:57.847 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error

2016-01-19 12:16:57.848 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:57.848 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:57.848 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:57.849 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:57.849 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:57.851 ThaliTest[2347:5044825] server: starting 1453202217849.2347.CSHEfg==
2016-01-19 12:16:57.851 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a5ccf60
2016-01-19 12:16:57.851 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202217849.2347
2016-01-19 12:16:57.851 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error

,2016-01-19 12:16:57.852 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:57.854 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:57.854 ThaliTest[2347:5044825] multipeer session: stop timer
,2016-01-19 12:16:57.857 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error

2016-01-19 12:16:57.858 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:57.859 ThaliTest[2347:5044825] server: starting 1453202217858.2347.4nmefA==
2016-01-19 12:16:57.859 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a3d1dc0
2016-01-19 12:16:57.859 ThaliTest[2347:5044825] THEMultipeerSession in,itialized peer 1453202217858.2347
2016-01-19 12:16:57.859 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error

2016-01-19 12:16:57.860 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:57.860 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:57.860 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:57.860 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:57.862 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:57.864 ThaliTest[2347:5044825] server: starting 1453202217861.2347.2XjdZQ==
2016-01-19 12:16:57.864 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a5cd530
2016-01-19 12:16:57.864 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202217861.2347
2016-01-19 12:16:57.864 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error

2016-01-19 12:16:57.865 ThaliTest[2347:5044825] jxcore: stopBroadcasting,
2016-01-19 12:16:57.865 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:57.865 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:57.865 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
ok 52 Shou,ld be able to call stopBroadcasting without error

2016-01-19 12:16:57.865 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:57.867 ThaliTest[2347:5044825] server: starting 1453202217865.2347.1OPrEg==
2016-01-19 12:16:57.867 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a5cea50
2016-01-19 12:16:57.867 ThaliTest[2347:5044825] THEMultipeerSession in,itialized peer 1453202217865.2347
2016-01-19 12:16:57.868 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error

2016-01-19 12:16:57.868 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:57.868 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
,2016-01-19 12:16:57.868 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:57.871 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error

2016-01-19 12:16:57.871 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:57.874 ThaliTest[2347:5044825] server: starting 1453202217871.2347.1MH8uw==
,2016-01-19 12:16:57.876 ThaliTest[2347:5044825] multipeer session: start timer: 0x19f3e2e0
2016-01-19 12:16:57.876 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202217871.2347
2016-01-19 12:16:57.876 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error

2016-01-19 12:16:57.876 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:57.876 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
,2016-01-19 12:16:57.876 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:57.878 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error

2016-01-19 12:16:57.879 ThaliTe,st[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:57.880 ThaliTest[2347:5044825] server: starting 1453202217878.2347.0E57FQ==
2016-01-19 12:16:57.881 ThaliTest[2347:5044825] multipeer session: start timer: 0x19f3f2c0
2016-01-19 12:16:57.881 ThaliTest[2347:5044825] THEMultipeerSession in,itialized peer 1453202217878.2347
2016-01-19 12:16:57.881 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error

2016-01-19 12:16:57.882 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:57.882 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:57.882 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:57.882 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
ok 58 Shou,ld be able to call stopBroadcasting without error

2016-01-19 12:16:57.882 ThaliTest[2347:5044825] jxcore: startBroadcasting
2016-01-19 12:16:57.883 ThaliTest[2347:5044825] server: starting 1453202217882.2347.q9561A==
2016-01-19 12:16:57.884 ThaliTest[,2347:5044825] multipeer session: start timer: 0x19f40a50
2016-01-19 12:16:57.885 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202217882.2347
2016-01-19 12:16:57.885 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 59 Sho,uld be able to call startBroadcasting without error

2016-01-19 12:16:57.885 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:57.886 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:57.886 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:57.886 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error

,2016-01-19 12:16:57.886 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:57.889 ThaliTest[2347:5044825] server: starting 1453202217886.2347.gBOuuQ==
2016-01-19 12:16:57.889 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a3a9b40
2016-01-19 12:16:57.890 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202217886.2347
2016-01-19 12:16:57.890 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error

2016-01-19 12:16:57.891 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:57.891 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:57.891 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:57.891 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
ok 62 Shou,ld be able to call stopBroadcasting without error

2016-01-19 12:16:57.891 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:57.893 ThaliTest[2347:5044825] server: starting 1453202217891.2347.dXNexg==
2016-01-19 12:16:57.893 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a5cf0e0
2016-01-19 12:16:57.893 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202217891.2347
2016-01-19 12:16:57.894 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error

2016-01-19 12:16:57.894 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:57.894 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:57.894 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:57.894 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-19 12:16:58.272 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:58.273 ThaliTest[2347:5044825] server: starting 1453202218272.2347.9nyp1w==
2016-01-19 12:16:58.273 ThaliTest[2347:5044825] multipeer session: start timer: 0x19f41030
2016-01-19 12:16:58.273 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202218272.2347
2016-01-19 12:16:58.273 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-01-19 12:16:58.274 ThaliTest[2347:5044825] jxcore: startBroadcasting
2016-01-19 12:16:58.274 ThaliTest[2347:5044825] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

2016-01-19 12:16:58.275 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:58.275 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:58.276 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:58.276 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-19 12:16:59.682 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:59.683 ThaliTest[2347:5044825] server: starting 1453202219682.2347.IkIC6Q==
2016-01-19 12:16:59.683 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a5d24d0
2016-01-19 12:16:59.683 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202219682.2347
2016-01-19 12:16:59.683 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

,2016-01-19 12:16:59.684 ThaliTest[2347:5044825] jxcore: connect foobar
2016-01-19 12:16:59.684 ThaliTest[2347:5044825] client: unknown peer foobar
2016-01-19 12:16:59.684 ThaliTest[2347:5044825] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer

2016-01-19 12:16:59.686 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:59.686 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:59.686 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:59.686 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-19 12:16:59.794 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:59.795 ThaliTest[2347:5044825] server: starting 1453202219794.2347.5Yi6AA==
,2016-01-19 12:16:59.795 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a5d52f0
,2016-01-19 12:16:59.795 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202219794.2347
,2016-01-19 12:16:59.796 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

,2016-01-19 12:16:59.796 ThaliTest[2347:5044825] jxcore: disconnect
2016-01-19 12:16:59.797 ThaliTest[2347:5044825] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 

2016-01-19 12:16:59.798 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:16:59.798 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:16:59.798 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:16:59.798 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-19 12:16:59.855 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:16:59.856 ThaliTest[2347:5044825] server: starting 1453202219855.2347.LJcwKA==
,2016-01-19 12:16:59.856 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a5d6f50
2016-01-19 12:16:59.857 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202219855.2347
,2016-01-19 12:16:59.857 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-01-19 12:17:00.583 ThaliTest[2347:5044653] client: found peer: 1453202216968.1652.4HZheQ==
,2016-01-19 12:17:00.585 ThaliTest[2347:5044825] jxcore: connect 1453202216968.1652.4HZheQ==
,2016-01-19 12:17:00.585 ThaliTest[2347:5044825] client session: connect
2016-01-19 12:17:00.585 ThaliTest[2347:5044825] client session: stateChange:0->1 1453202216968.1652.4HZheQ==
,2016-01-19 12:17:01.825 ThaliTest[2347:5044653] multipeer session: reset timer
2016-01-19 12:17:01.825 ThaliTest[2347:5044653] multipeer session: stop timer
2016-01-19 12:17:01.825 ThaliTest[2347:5044653] multipeer session: start timer: 0x1a5d6f50
2016-,01-19 12:17:01.825 ThaliTest[2347:5044653] server session: connect
2016-01-19 12:17:01.825 ThaliTest[2347:5044653] server session: stateChange:0->1 1453202216968.1652
,2016-01-19 12:17:01.827 ThaliTest[2347:5044653] server: accepting invitation 1453202216968.1652
,2016-01-19 12:17:05.996 ThaliTest[2347:5045412] client session: connected
2016-01-19 12:17:05.996 ThaliTest[2347:5045412] client session: stateChange:1->2 1453202216968.1652.4HZheQ==
,2016-01-19 12:17:06.030 ThaliTest[2347:5045424] client session: fireConnectCallback: 1453202216968.1652.4HZheQ==
2016-01-19 12:17:06.030 ThaliTest[2347:5045424] jxcore: connect: success
ok 75 Should be able to connect without error

ok 76 Port should be within range

,2016-01-19 12:17:06.031 ThaliTest[2347:5044825] jxcore: disconnect
2016-01-19 12:17:06.031 ThaliTest[2347:5044825] client session: disconnectFromPeer: 1453202216968.1652.4HZheQ==
2016-01-19 12:17:06.031 ThaliTest[2347:5044825] client session: disconnect
2016-01-19 12:17:06.031 ThaliTest[2347:5044825] client session: stateChange:2->0 1453202216968.1652.4HZheQ==
,2016-01-19 12:17:06.089 ThaliTest[2347:5044825] jxcore: disconnect: success
ok 77 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-19 12:17:06.129 ThaliTest[2347:5045412] server session: connected
2016-01-19 12:17:06.129 ThaliTest[2347:5045412] server session: stateChange:1->2 1453202216968.1652
,2016-01-19 12:17:06.130 ThaliTest[2347:5044653] server relay: socket disconnected
2016-01-19 12:17:06.130 ThaliTest[2347:5044653] server relay: 0x17e04110 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 12:17:06.206 ThaliTest[2347:5045417] server session: not connected 1453202216968.1652
,calling stopBroadcasting

,2016-01-19 12:17:07.013 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:17:07.014 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:17:07.014 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:17:07.014 ThaliTest[2347:5044825] server session: disconnect
2016-01-19 12:17:07.014 ThaliTest[2347:5044825] server session: stateChange:2->0 1453202216968.1652
,2016-01-19 12:17:07.016 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-19 12:17:08.051 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:17:08.052 ThaliTest[2347:5044825] server: starting 1453202228051.2347.NX/3vw==
2016-01-19 12:17:08.053 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a375fa0
2016-01-19 12:17:08.053 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202228051.2347
2016-01-19 12:17:08.053 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-19 12:17:08.917 ThaliTest[2347:5044653] client: found peer: 1453202225159.1652.roQP/w==
2016-01-19 12:17:08.917 ThaliTest[2347:5044825] jxcore: connect 1453202225159.1652.roQP/w==
2016-01-19 12:17:08.917 ThaliTest[2347:5044825] client session: connect
2016-01-19 12:17:08.917 ThaliTest[2347:5044825] client session: stateChange:0->1 1453202225159.1652.roQP/w==
,2016-01-19 12:17:09.240 ThaliTest[2347:5044653] multipeer session: reset timer
2016-01-19 12:17:09.240 ThaliTest[2347:5044653] multipeer session: stop timer
2016-01-19 12:17:09.240 ThaliTest[2347:5044653] multipeer session: start timer: 0x1a375fa0
2016-01-19 12:17:09.240 ThaliTest[2347:5044653] server session: connect
2016-01-19 12:17:09.241 ThaliTest[2347:5044653] server session: stateChange:0->1 1453202225159.1652
,2016-01-19 12:17:09.243 ThaliTest[2347:5044653] server: accepting invitation 1453202225159.1652
,2016-01-19 12:17:13.697 ThaliTest[2347:5045431] client session: connected
2016-01-19 12:17:13.697 ThaliTest[2347:5045431] client session: stateChange:1->2 1453202225159.1652.roQP/w==
,2016-01-19 12:17:13.699 ThaliTest[2347:5045431] client session: fireConnectCallback: 1453202225159.1652.roQP/w==
2016-01-19 12:17:13.699 ThaliTest[2347:5045431] jxcore: connect: success
,ok 79 Should be able to connect without error

,ok 80 Port should be within range

,2016-01-19 12:17:13.701 ThaliTest[2347:5044825] jxcore: connect 1453202225159.1652.roQP/w==
,2016-01-19 12:17:13.701 ThaliTest[2347:5044825] client: already connect(ing/ed) to 1453202225159.1652.roQP/w==
,2016-01-19 12:17:13.701 ThaliTest[2347:5044825] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect

,2016-01-19 12:17:13.702 ThaliTest[2347:5044825] jxcore: disconnect
2016-01-19 12:17:13.702 ThaliTest[2347:5044825] client session: disconnectFromPeer: 1453202225159.1652.roQP/w==
,2016-01-19 12:17:13.702 ThaliTest[2347:5044825] client session: disconnect
,2016-01-19 12:17:13.702 ThaliTest[2347:5044825] client session: stateChange:2->0 1453202225159.1652.roQP/w==
,2016-01-19 12:17:13.759 ThaliTest[2347:5044825] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-19 12:17:13.959 ThaliTest[2347:5045424] server session: connected
2016-01-19 12:17:13.959 ThaliTest[2347:5045424] server session: stateChange:1->2 1453202225159.1652
,2016-01-19 12:17:13.960 ThaliTest[2347:5044653] server relay: socket disconnected
,2016-01-19 12:17:13.960 ThaliTest[2347:5044653] server relay: 0x1a59d3c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-01-19 12:17:14.026 ThaliTest[2347:5045431] server session: not connected 1453202225159.1652
,calling stopBroadcasting

,2016-01-19 12:17:14.036 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:17:14.036 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
,2016-01-19 12:17:14.036 ThaliTest[2347:5044825] multipeer session: stop timer
,2016-01-19 12:17:14.036 ThaliTest[2347:5044825] server session: disconnect
2016-01-19 12:17:14.036 ThaliTest[2347:5044825] server session: stateChange:2->0 1453202225159.1652
,2016-01-19 12:17:14.038 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-19 12:17:14.529 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:17:14.530 ThaliTest[2347:5044825] server: starting 1453202234529.2347.hGE8XQ==
2016-01-19 12:17:14.531 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a59afb0
2016-01-19 12:17:14.531 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202234529.2347
2016-01-19 12:17:14.531 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-19 12:17:15.677 ThaliTest[2347:5044653] client: found peer: 1453202231666.1652.IIgVBA==
,2016-01-19 12:17:15.678 ThaliTest[2347:5044825] jxcore: connect 1453202231666.1652.IIgVBA==
2016-01-19 12:17:15.678 ThaliTest[2347:5044825] client session: connect
2016-01-19 12:17:15.678 ThaliTest[2347:5044825] client session: stateChange:0->1 1453202231666.1652.IIgVBA==
,2016-01-19 12:17:16.128 ThaliTest[2347:5044653] multipeer session: reset timer
2016-01-19 12:17:16.128 ThaliTest[2347:5044653] multipeer session: stop timer
2016-01-19 12:17:16.128 ThaliTest[2347:5044653] multipeer session: start timer: 0x1a59afb0
2016-,01-19 12:17:16.128 ThaliTest[2347:5044653] server session: connect
2016-01-19 12:17:16.128 ThaliTest[2347:5044653] server session: stateChange:0->1 1453202231666.1652
,2016-01-19 12:17:16.130 ThaliTest[2347:5044653] server: accepting invitation 1453202231666.1652
,2016-01-19 12:17:20.384 ThaliTest[2347:5045414] client session: connected
2016-01-19 12:17:20.384 ThaliTest[2347:5045414] client session: stateChange:1->2 1453202231666.1652.IIgVBA==
,2016-01-19 12:17:20.413 ThaliTest[2347:5045414] client session: fireConnectCallback: 1453202231666.1652.IIgVBA==
2016-01-19 12:17:20.413 ThaliTest[2347:5045414] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should b,e within range

,2016-01-19 12:17:20.414 ThaliTest[2347:5044825] jxcore: disconnect
2016-01-19 12:17:20.415 ThaliTest[2347:5044825] client session: disconnectFromPeer: 1453202231666.1652.IIgVBA==
2016-01-19 12:17:20.415 ThaliTest[2347:5044825] client session: disconnect
2016-01-19 12:17:20.415 ThaliTest[2347:5044825] client session: stateChange:2->0 1453202231666.1652.IIgVBA==
,2016-01-19 12:17:20.418 ThaliTest[2347:5044825] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

,2016-01-19 12:17:20.419 ThaliTest[2347:5044825] jxcore: disconnect
2016-01-19 12:17:20.419 ThaliTest[2347:5044825] jxcore: disconnect: fail
,ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-19 12:17:20.908 ThaliTest[2347:5045414] server session: connected
2016-01-19 12:17:20.909 ThaliTest[2347:5045414] server session: stateChange:1->2 1453202231666.1652
,2016-01-19 12:17:20.935 ThaliTest[2347:5044653] server relay: socket disconnected
2016-01-19 12:17:20.936 ThaliTest[2347:5044653] server relay: 0x1a353180 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 12:17:20.970 ThaliTest[2347:5045414] server session: not connected 1453202231666.1652
,calling stopBroadcasting

,2016-01-19 12:17:21.309 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:17:21.310 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:17:21.310 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:17:21.310 ThaliTest[2347:5044825] server session: disconnect
2016-01-19 12:17:21.310 ThaliTest[2347:5044825] server session: stateChange:2->0 1453202231666.1652
2016-01-19 12:17:21.310 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 54775

,2016-01-19 12:17:21.882 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:17:21.883 ThaliTest[2347:5044825] server: starting 1453202241882.2347.pKmhzQ==
,2016-01-19 12:17:21.883 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a3faa80
2016-01-19 12:17:21.884 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202241882.2347
2016-01-19 12:17:21.884 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error

,2016-01-19 12:17:23.132 ThaliTest[2347:5044653] multipeer session: reset timer
2016-01-19 12:17:23.132 ThaliTest[2347:5044653] multipeer session: stop timer
2016-01-19 12:17:23.132 ThaliTest[2347:5044653] multipeer session: start timer: 0x1a3faa80
2016-01-19 12:17:23.132 ThaliTest[2347:5044653] server session: connect
2016-01-19 12:17:23.133 ThaliTest[2347:5044653] server session: stateChange:0->1 1453202240054.1652
2016-01-19 12:17:23.134 ThaliTest[2347:5044653] server: accepting invitation 1453202240054.1652
,2016-01-19 12:17:24.084 ThaliTest[2347:5044653] client: found peer: 1453202240054.1652.x95b4Q==
,2016-01-19 12:17:24.085 ThaliTest[2347:5044825] jxcore: connect 1453202240054.1652.x95b4Q==
2016-01-19 12:17:24.085 ThaliTest[2347:5044825] client session: connect
2016-01-19 12:17:24.085 ThaliTest[2347:5044825] client session: stateChange:0->1 1453202240054.1652.x95b4Q==
,2016-01-19 12:17:26.460 ThaliTest[2347:5045414] server session: connected
2016-01-19 12:17:26.460 ThaliTest[2347:5045414] server session: stateChange:1->2 1453202240054.1652
,2016-01-19 12:17:26.479 ThaliTest[2347:5044653] server relay: connected (to port: 54775)
,2016-01-19 12:17:26.911 ThaliTest[2347:5045417] server session: not connected 1453202240054.1652
,2016-01-19 12:17:27.464 ThaliTest[2347:5045516] client session: connected
2016-01-19 12:17:27.464 ThaliTest[2347:5045516] client session: stateChange:1->2 1453202240054.1652.x95b4Q==
,2016-01-19 12:17:27.488 ThaliTest[2347:5045417] client session: fireConnectCallback: 1453202240054.1652.x95b4Q==
2016-01-19 12:17:27.488 ThaliTest[2347:5045417] jxcore: connect: success
,ok 89 Should be able to connect without error

ok 90 Port should be within range

,2016-01-19 12:17:27.490 ThaliTest[2347:5044653] client: relay established
2016-01-19 12:17:27.490 ThaliTest[2347:5044653] client: new accepted socket: 0x19c435f0
,data in 3285

,data in 27375

,data in 28470

,data in 30660

,data in 33945

,data in 53655

,data in 63510

,data in 66795

,data in 73365

,2016-01-19 12:17:27.892 ThaliTest[2347:5044653] multipeer session: restart
,data in 79935
,
,data in 106215

,data in 128115

,data in 129210

,data in 131072

,ok 91 the test messages should be equal

,2016-01-19 12:17:28.019 ThaliTest[2347:5044825] jxcore: disconnect
,2016-01-19 12:17:28.019 ThaliTest[2347:5044825] client session: disconnectFromPeer: 1453202240054.1652.x95b4Q==
2016-01-19 12:17:28.020 ThaliTest[2347:5044825] client session: disconnect
2016-01-19 12:17:28.020 ThaliTest[2347:5044825] client session: stateChange:2->0 1453202240054.1652.x95b4Q==
,2016-01-19 12:17:28.022 ThaliTest[2347:5044825] jxcore: disconnect: success
ok 92 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-19 12:17:28.124 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:17:28.124 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:17:28.124 ThaliTest[2347:5044825] multipeer session: stop timer
,2016-01-19 12:17:28.124 ThaliTest[2347:5044825] server session: disconnect
2016-01-19 12:17:28.124 ThaliTest[2347:5044825] server session: stateChange:2->0 1453202240054.1652
,2016-01-19 12:17:28.127 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 54781

,2016-01-19 12:17:29.606 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:17:29.607 ThaliTest[2347:5044825] server: starting 1453202249606.2347.3ZDcdg==
2016-01-19 12:17:29.607 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a5a4780
2016-01-19 12:17:29.607 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 1453202249606.2347
2016-01-19 12:17:29.608 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error

,2016-01-19 12:17:31.058 ThaliTest[2347:5044653] client: found peer: 1453202246772.1652.9JbJyg==
,[{"peerIdentifier":"1453202246772.1652.9JbJyg==","peerName":"(null)","peerAvailable":true}]

2016-01-19 12:17:31.059 ThaliTest[2347:5044825] jxcore: connect 1453202246772.1652.9JbJyg==
,2016-01-19 12:17:31.060 ThaliTest[2347:5044825] client session: connect
2016-01-19 12:17:31.060 ThaliTest[2347:5044825] client session: stateChange:0->1 1453202246772.1652.9JbJyg==
,2016-01-19 12:17:31.126 ThaliTest[2347:5044653] multipeer session: reset timer
2016-01-19 12:17:31.126 ThaliTest[2347:5044653] multipeer session: stop timer
2016-01-19 12:17:31.126 ThaliTest[2347:5044653] multipeer session: start timer: 0x1a5a4780
2016-01-19 12:17:31.126 ThaliTest[2347:5044653] server session: connect
2016-01-19 12:17:31.126 ThaliTest[2347:5044653] server session: stateChange:0->1 1453202246772.1652
,2016-01-19 12:17:31.128 ThaliTest[2347:5044653] server: accepting invitation 1453202246772.1652
,2016-01-19 12:17:35.320 ThaliTest[2347:5045516] client session: connected
2016-01-19 12:17:35.321 ThaliTest[2347:5045516] client session: stateChange:1->2 1453202246772.1652.9JbJyg==
,2016-01-19 12:17:35.322 ThaliTest[2347:5045516] server session: connected
2016-01-19 12:17:35.322 ThaliTest[2347:5045516] server session: stateChange:1->2 1453202246772.1652
,2016-01-19 12:17:35.388 ThaliTest[2347:5045516] client session: fireConnectCallback: 1453202246772.1652.9JbJyg==
2016-01-19 12:17:35.388 ThaliTest[2347:5045516] jxcore: connect: success
,2016-01-19 12:17:35.390 ThaliTest[2347:5044653] server relay: connected (to port: 54781)
ok 94 Should be able to connect without error

ok 95 Port should be within range

ok 96 First connect should succeed

,2016-01-19 12:17:35.400 ThaliTest[2347:5044653] client: relay established
2016-01-19 12:17:35.400 ThaliTest[2347:5044653] client: new accepted socket: 0x19c1a800
,ok 97 the test messages should be equal

ok 98 First send should succeed

,2016-01-19 12:17:35.478 ThaliTest[2347:5044653] client: socket closed
2016-01-19 12:17:35.478 ThaliTest[2347:5044653] client relay: socket disconnected
2016-01-19 12:17:35.478 ThaliTest[2347:5044653] client relay: 0x19c1a800 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 12:17:35.478 ThaliTest[2347:5044653] client session: socket closed: 1453202246772.1652.9JbJyg==
2016-01-19 12:17:35.478 ThaliTest[2347:5044653] client session: onLinkFailure: 1453202246772.1652.9JbJyg==
2016-01-19 12:17:35.478 ThaliTest[2347:5044653] client session: disconnect
2016-01-19 12:17:35.478 ThaliTest[2347:5044653] client session: stateChange:2->0 1453202246772.1652.9JbJyg==
,2016-01-19 12:17:35.482 ThaliTest[2347:5044653] client session: fireConnectionErrorEvent: 1453202246772.1652.9JbJyg==
,2016-01-19 12:17:35.484 ThaliTest[2347:5044825] jxcore: connect 1453202246772.1652.9JbJyg==
2016-01-19 12:17:35.484 ThaliTest[2347:5044825] client session: connect
2016-01-19 12:17:35.484 ThaliTest[2347:5044825] client session: stateChange:0->1 1453202246772.1652.9JbJyg==
,2016-01-19 12:17:35.506 ThaliTest[2347:5045417] server session: not connected 1453202246772.1652
,2016-01-19 12:17:35.713 ThaliTest[2347:5044653] multipeer session: reset timer
,2016-01-19 12:17:35.713 ThaliTest[2347:5044653] multipeer session: stop timer
2016-01-19 12:17:35.713 ThaliTest[2347:5044653] multipeer session: start timer: 0x1a5a4780
2016-01-19 12:17:35.713 ThaliTest[2347:5044653] server: disconnecting to refresh session (1453202246772.1652)
2016-01-19 12:17:35.713 ThaliTest[2347:5044653] server session: disconnect
,2016-01-19 12:17:35.714 ThaliTest[2347:5044653] server session: stateChange:2->0 1453202246772.1652
,2016-01-19 12:17:35.715 ThaliTest[2347:5044653] server session: connect
2016-01-19 12:17:35.715 ThaliTest[2347:5044653] server session: stateChange:0->1 1453202246772.1652
,2016-01-19 12:17:35.717 ThaliTest[2347:5044653] server: accepting invitation 1453202246772.1652
,2016-01-19 12:17:39.577 ThaliTest[2347:5045412] server session: connected
,2016-01-19 12:17:39.577 ThaliTest[2347:5045412] server session: stateChange:1->2 1453202246772.1652
,2016-01-19 12:17:39.581 ThaliTest[2347:5045516] client session: connected
2016-01-19 12:17:39.581 ThaliTest[2347:5045516] client session: stateChange:1->2 1453202246772.1652.9JbJyg==
,2016-01-19 12:17:39.707 ThaliTest[2347:5044653] server relay: connected (to port: 54781)
,2016-01-19 12:17:39.709 ThaliTest[2347:5045431] client session: fireConnectCallback: 1453202246772.1652.9JbJyg==
2016-01-19 12:17:39.709 ThaliTest[2347:5045431] jxcore: connect: success
,ok 99 Should be able to connect without error

,ok 100 Port should be within range

,ok 101 Second connect should succeed

,2016-01-19 12:17:39.719 ThaliTest[2347:5044653] client: relay established
2016-01-19 12:17:39.719 ThaliTest[2347:5044653] client: new accepted socket: 0x1a5b7d50
,ok 102 the test messages should be equal

,ok 103 Second send should succeed

,# setup

,2016-01-19 12:17:39.795 ThaliTest[2347:5044653] client: socket closed
,2016-01-19 12:17:39.795 ThaliTest[2347:5044653] client relay: socket disconnected
,2016-01-19 12:17:39.796 ThaliTest[2347:5044653] client relay: 0x1a5b7d50 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 12:17:39.796 ThaliTest[2347:5044653] client session: socket closed: 1453202246772.1652.9JbJyg==
2016-01-19 12:17:39.796 ThaliTest[2347:5044653] client session: onLinkFailure: 1453202246772.1652.9JbJyg==
2016-01-19 12:17:39.796 ThaliTest[2347:5044653] client session: disconnect
2016-01-19 12:17:39.796 ThaliTest[2347:5044653] client session: stateChange:2->0 1453202246772.1652.9JbJyg==
,2016-01-19 12:17:39.843 ThaliTest[2347:5045431] server session: not connected 1453202246772.1652
,2016-01-19 12:17:39.853 ThaliTest[2347:5044653] client session: fireConnectionErrorEvent: 1453202246772.1652.9JbJyg==
,calling stopBroadcasting

,2016-01-19 12:17:41.274 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:17:41.275 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:17:41.275 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:17:41.275 ThaliTest[2347:5044825] server session: disconnect
2016-01-19 12:17:41.275 ThaliTest[2347:5044825] server session: stateChange:2->0 1453202246772.1652
,2016-01-19 12:17:41.276 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/DAB83158-66F2-4D69-A12D-D1AAFD81B6C4/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 104 starting event should occur in right order

,2016-01-19 12:17:41.736 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:17:41.737 ThaliTest[2347:5044825] server: starting 2FMISDbp3IDib7dtBEIkVg.4Noe2g==
2016-01-19 12:17:41.737 ThaliTest[2347:5044825] multipeer session: start timer: 0x19c1c260
2016-01-19 12:17:41.737 ThaliTest[2347:5044825] THEMultipeerSessio,n initialized peer 2FMISDbp3IDib7dtBEIkVg
2016-01-19 12:17:41.737 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 105 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 106 stopping event sh,ould occur in right order

About to call stopBroadcasting

2016-01-19 12:17:41.738 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:17:41.738 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
2016-01-19 12:17:41.739 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:17:41.739 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 107 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/DAB83158-66F2-4D69-A12D-D1AAFD81B6C4/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 12:17:41.880 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:17:41.881 ThaliTest[2347:5044825] server: starting 2FMISDbp3IDib7dtBEIkVg.Te8hMg==
2016-01-19 12:17:41.881 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a5bb7a0
,2016-01-19 12:17:41.881 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 2FMISDbp3IDib7dtBEIkVg
2016-01-19 12:17:41.883 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error

ok 109 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-19 12:17:41.884 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:17:41.884 ThaliTest[2347:5044825] THEMultipeerSes,sion stopping peer
2016-01-19 12:17:41.884 ThaliTest[2347:5044825] multipeer session: stop timer
2016-01-19 12:17:41.884 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/DAB83158-66F2-4D69-A12D-D1AAFD81B6C4/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 12:17:44.280 ThaliTest[2347:5044825] jxcore: startBroadcasting
,2016-01-19 12:17:44.282 ThaliTest[2347:5044825] server: starting 2FMISDbp3IDib7dtBEIkVg.C+Woiw==
2016-01-19 12:17:44.282 ThaliTest[2347:5044825] multipeer session: start timer: 0x1a76dc10
2016-01-19 12:17:44.282 ThaliTest[2347:5044825] THEMultipeerSession initialized peer 2FMISDbp3IDib7dtBEIkVg
2016-01-19 12:17:44.282 ThaliTest[2347:5044825] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error

ok 111 deviceName should not be null

,2016-01-19 12:17:48.159 ThaliTest[2347:5044653] client: found peer: WmTqlEsC6-WPOc6VpbrhxQ.+7evPw==
,2016-01-19 12:17:48.531 ThaliTest[2347:5044825] jxcore: connect WmTqlEsC6-WPOc6VpbrhxQ.+7evPw==
2016-01-19 12:17:48.531 ThaliTest[2347:5044825] client session: connect
2016-01-19 12:17:48.531 ThaliTest[2347:5044825] client session: stateChange:0->1 WmTqlEsC6-WPOc6VpbrhxQ.+7evPw==
,ok 112 Should be able to put doc without error

,ok 113 1st change of local doc should contain local id

,2016-01-19 12:17:57.181 ThaliTest[2347:5044653] multipeer session: reset timer
2016-01-19 12:17:57.181 ThaliTest[2347:5044653] multipeer session: stop timer
2016-01-19 12:17:57.181 ThaliTest[2347:5044653] multipeer session: start timer: 0x1a76dc10
2016-01-19 12:17:57.181 ThaliTest[2347:5044653] server session: connect
2016-01-19 12:17:57.181 ThaliTest[2347:5044653] server session: stateChange:0->1 WmTqlEsC6-WPOc6VpbrhxQ
2016-01-19 12:17:57.184 ThaliTest[2347:5044653] server: accepting invitation WmTqlEsC6-WPOc6VpbrhxQ
,2016-01-19 12:17:57.892 ThaliTest[2347:5044653] multipeer session: restart
,2016-01-19 12:18:01.346 ThaliTest[2347:5045412] client session: connected
2016-01-19 12:18:01.346 ThaliTest[2347:5045412] client session: stateChange:1->2 WmTqlEsC6-WPOc6VpbrhxQ.+7evPw==
,2016-01-19 12:18:01.396 ThaliTest[2347:5045517] client session: fireConnectCallback: WmTqlEsC6-WPOc6VpbrhxQ.+7evPw==
2016-01-19 12:18:01.396 ThaliTest[2347:5045517] jxcore: connect: success
,2016-01-19 12:18:01.400 ThaliTest[2347:5044653] client: relay established
2016-01-19 12:18:01.400 ThaliTest[2347:5044653] client: new accepted socket: 0x17dcaac0
,client bridge: new client socket

,client bridge: new client socket

,2016-01-19 12:18:01.542 ThaliTest[2347:5045517] server session: connected
2016-01-19 12:18:01.542 ThaliTest[2347:5045517] server session: stateChange:1->2 WmTqlEsC6-WPOc6VpbrhxQ
,2016-01-19 12:18:01.558 ThaliTest[2347:5044653] server relay: connected (to port: 54796)
,server bridge: new client socket

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

,client bridge: socket closed

,ok 114 1st change of remote doc should contain remote id

,client bridge: new client socket

,ok 115 Can update remote doc without error

null

,{ ok: true,
  id: '7ebae1b3-c02a-49f8-95f9-f158f9578794',
  rev: '2-6f1582f07a1278d8b00ccead6e3acd73' }

,client bridge: new client socket

,ok 116 Remote changes occur in strict order

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

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,ok 117 Local changes occur in strict order

ok 118 2nd change of local doc should contain remote id

,# setup

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-01-19 12:18:18.493 ThaliTest[2347:5044825] jxcore: stopBroadcasting
2016-01-19 12:18:18.493 ThaliTest[2347:5044825] THEMultipeerSession stopping peer
,2016-01-19 12:18:18.494 ThaliTest[2347:5044825] multipeer session: stop timer
,2016-01-19 12:18:18.494 ThaliTest[2347:5044825] client session: disconnect
,2016-01-19 12:18:18.495 ThaliTest[2347:5044825] client session: stateChange:2->0 WmTqlEsC6-WPOc6VpbrhxQ.+7evPw==
,2016-01-19 12:18:18.501 ThaliTest[2347:5044825] server session: disconnect
2016-01-19 12:18:18.502 ThaliTest[2347:5044825] server session: stateChange:2->0 WmTqlEsC6-WPOc6VpbrhxQ
,2016-01-19 12:18:18.507 ThaliTest[2347:5044825] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,
,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,client bridge: new client socket

,Error in mux client bridge Error: read ECONNRESET

,mux server bridge listener closed

,syncRetry called when not started

client bridge: socket closed

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

,ok 123 messages from this device should be ignored

,# setup

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

,ok 127 should still be in stopped state

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
