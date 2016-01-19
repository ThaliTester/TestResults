#### Test 5644966031ce140_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5644966031ce140/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8B2AD76C-D2DD-40CB-9F37-D93133AD5FF6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8B2AD76C-D2DD-40CB-9F37-D93133AD5FF6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5644966031ce140/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5644966031ce140/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6CDF8EED-F579-421F-B858-DBDBA28D61E9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58646"
,(lldb)     command script import "/tmp/8B2AD76C-D2DD-40CB-9F37-D93133AD5FF6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-19 13:01:25.178 ThaliTest[2303:4793239] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D8A44167-9991-4AAE-BEA3-00FB4F91B37B/Library/Cookies/Cookies.binarycookies
,2016-01-19 13:01:25.413 ThaliTest[2303:4793239] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-19 13:01:25.414 ThaliTest[2303:4793239] Multi-tasking -> Device: YES, App: YES
,2016-01-19 13:01:25.421 ThaliTest[2303:4793239] Unlimited access to network resources
,2016-01-19 13:01:25.428 ThaliTest[2303:4793239] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-19 13:01:29.685 ThaliTest[2303:4793239] Resetting plugins due to page load.
,2016-01-19 13:01:31.146 ThaliTest[2303:4793239] Finished load of: file:///var/mobile/Containers/Bundle/Application/6CDF8EED-F579-421F-B858-DBDBA28D61E9/ThaliTest.app/www/index.html
,2016-01-19 13:01:31.307 ThaliTest[2303:4793239] JXcore Cordova plugin initializing
2016-01-19 13:01:31.308 ThaliTest[2303:4793394] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CDF8EED-F579-421F-B858-DBDBA28D61E9/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CDF8EED-F579-421F-B858-DBDBA28D61E9/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CDF8EED-F579-421F-B858-DBDBA28D61E9/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CDF8EED-F579-421F-B858-DBDBA28D61E9/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CDF8EED-F579-421F-B858-DBDBA28D61E9/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CDF8EED-F579-421F-B858-DBDBA28D61E9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CDF8EED-F579-421F-B858-DBDBA28D61E9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

# setup

,# basic

,# teardown

,ok 2 sane

,# setup

,# another

,# teardown

,ok 3 sane

# setup

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 4 should be equal

,ok 5 null

,ok 6 (unnamed assert)

ok 7 should be equal

ok 8 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 9 (unnamed assert)

,ok 10 (unnamed assert)

ok 11 should not throw

,ok 12 should be equal

ok 13 should be equal

# setup

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

# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 22 should throw

,# setup

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

# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 29 should be equal

ok 30 should be equal

ok 31 should be equal

# setup

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

ok 40 should be equal

# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 43 should be equal

ok 44 should be equal

# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-19 13:06:34.691 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:34.697 ThaliTest[2303:4793394] server: starting 1453205194691.2303.7qrAwg==
2016-01-19 13:06:34.698 ThaliTest[2303:4793394] multipeer session: start timer: 0x18204f10
2016-01-19 13:06:34.698 ThaliTest[2303:4793394] THEMultipeerSession in,itialized peer 1453205194691.2303
2016-01-19 13:06:34.698 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.699 ThaliTest[2303:4793394] jxcore: stopBroadcasting
,2016-01-19 13:06:34.699 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:34.703 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:06:34.703 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error

2016-01-19 13:06:34.704 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:34.714 ThaliTest[2303:4793394] server: starting 1453205194703.2303.tu6vOA==
2016-01-19 13:06:34.715 ThaliTest[2303:4793394] multipeer session: start timer: 0x18205c70
2016-01-19 13:06:34.715 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205194703.2303
2016-01-19 13:06:34.715 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.716 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:34.716 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
,2016-01-19 13:06:34.716 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:06:34.721 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error

2016-01-19 13:06:34.722 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:34.725 ThaliTest[2303:4793394] server: starting 1453205194721.2303.SUvmEg==
2016-01-19 13:06:34.725 ThaliTest[2303:4793394] multipeer session: start timer: 0x18202500
2016-01-19 13:06:34.726 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205194721.2303
2016-01-19 13:06:34.726 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.726 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:34.726 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:34.727 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:06:34.727 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error

,2016-01-19 13:06:34.727 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:34.738 ThaliTest[2303:4793394] server: starting 1453205194727.2303.+JdINg==
2016-01-19 13:06:34.738 ThaliTest[2303:4793394] multipeer session: start timer: 0x180f49f0
2016-01-19 13:06:34.738 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205194727.2303
2016-01-19 13:06:34.738 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.739 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:34.739 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:34.740 ThaliTest[2303:4793394] multipeer session: stop timer
,2016-01-19 13:06:34.740 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error

2016-01-19 13:06:34.744 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:34.747 ThaliTest[2303:4793394] server: starting 1453205194744.2303.2dE5IQ==
2016-01-19 13:06:34.747 ThaliTest[2303:4793394] multipeer session: start timer: 0x18207700
2016-01-19 13:06:34.747 ThaliTest[2303:4793394] THEMultipeerSession in,itialized peer 1453205194744.2303
,2016-01-19 13:06:34.747 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.751 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:34.751 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:34.751 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:06:34.751 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error

2016-01-19 13:06:34.752 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:34.756 ThaliTest[2303:4793394] server: starting 1453205194752.2303.iRU8Cg==
2016-01-19 13:06:34.756 ThaliTest[2303:4793394] multipeer session: start timer: 0x18067c50
2016-01-19 13:06:34.756 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205194752.2303
2016-01-19 13:06:34.756 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.758 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:34.758 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:34.759 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:06:34.759 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error

2016-01-19 13:06:34.759 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:34.763 ThaliTest[2303:4793394] server: starting 1453205194759.2303.ckif0w==
,2016-01-19 13:06:34.766 ThaliTest[2303:4793394] multipeer session: start timer: 0x18052ed0
2016-01-19 13:06:34.766 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205194759.2303
2016-01-19 13:06:34.767 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.767 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:34.767 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19, 13:06:34.767 ThaliTest[2303:4793394] multipeer session: stop timer
,2016-01-19 13:06:34.768 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error

2016-01-19 13:06:34.771 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:34.775 ThaliTest[2303:4793394] server: starting 1453205194771.2303.ndznlQ==
2016-01-19 13:06:34.775 ThaliTest[2303:4793394] multipeer session: start timer: 0x1820a030
2016-01-19 13:06:34.775 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205194771.2303
,2016-01-19 13:06:34.778 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.778 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:34.778 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:34.779 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:06:34.779 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error

2016-01-19 13:06:34.779 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:34.784 ThaliTest[2303:4793394] server: starting 1453205194779.2303.sh29tA==
,2016-01-19 13:06:34.786 ThaliTest[2303:4793394] multipeer session: start timer: 0x1820af20
2016-01-19 13:06:34.786 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205194779.2303
2016-01-19 13:06:34.786 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.787 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:34.787 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:34.787 ThaliTest[2303:4793394] multipeer session: stop timer
,2016-01-19 13:06:34.787 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,
,2016-01-19 13:06:34.795 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:34.796 ThaliTest[2303:4793394] server: starting 1453205194795.2303.dtfQ0A==
,2016-01-19 13:06:34.798 ThaliTest[2303:4793394] multipeer session: start timer: 0x18052f60
,2016-01-19 13:06:34.801 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205194795.2303
,2016-01-19 13:06:34.802 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,
,2016-01-19 13:06:34.803 ThaliTest[2303:4793394] jxcore: stopBroadcasting
,2016-01-19 13:06:34.804 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
,2016-01-19 13:06:34.804 ThaliTest[2303:4793394] multipeer session: stop timer
,2016-01-19 13:06:34.805 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-19 13:06:35.084 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:35.085 ThaliTest[2303:4793394] server: starting 1453205195084.2303.a9Zngg==
2016-01-19 13:06:35.086 ThaliTest[2303:4793394] multipeer session: start timer: 0x1804baa0
2016-01-19 13:06:35.086 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205195084.2303
2016-01-19 13:06:35.086 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-01-19 13:06:35.087 ThaliTest[2303:4793394] jxcore: startBroadcasting
2016-01-19 13:06:35.087 ThaliTest[2303:4793394] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

2016-01-19 13:06:35.089 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:35.089 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:35.089 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:06:35.089 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-19 13:06:35.594 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:35.596 ThaliTest[2303:4793394] server: starting 1453205195594.2303.1gNrPg==
2016-01-19 13:06:35.596 ThaliTest[2303:4793394] multipeer session: start timer: 0x1822a520
2016-01-19 13:06:35.596 ThaliTest[2303:4793394] THEMultipeerSession in,itialized peer 1453205195594.2303
2016-01-19 13:06:35.596 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

2016-01-19 13:06:35.597 ThaliTest[2303:4793394] jxcore: connect foobar
2,016-01-19 13:06:35.597 ThaliTest[2303:4793394] client: unknown peer foobar
2016-01-19 13:06:35.598 ThaliTest[2303:4793394] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer

2016-01-19 13:06:35.600 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:35.600 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:35.600 ThaliTest[2303:4793394] multipeer, session: stop timer
2016-01-19 13:06:35.600 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-19 13:06:36.122 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:36.123 ThaliTest[2303:4793394] server: starting 1453205196122.2303.RUy0Ug==
2016-01-19 13:06:36.124 ThaliTest[2303:4793394] multipeer session: start timer: 0x1822ef40
2016-01-19 13:06:36.124 ThaliTest[2303:4793394] THEMultipeerSession in,itialized peer 1453205196122.2303
2016-01-19 13:06:36.124 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-01-19 13:06:36.124 ThaliTest[2303:4793394] jxcore: disconnect
2016-01-19 13:06:36.125 ThaliTest[2303:4793394] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 

,2016-01-19 13:06:36.126 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:36.129 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:36.129 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:06:36.130 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-19 13:06:37.097 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:06:37.098 ThaliTest[2303:4793394] server: starting 1453205197097.2303.SAyIXg==
2016-01-19 13:06:37.099 ThaliTest[2303:4793394] multipeer session: start timer: 0x1823da80
2016-01-19 13:06:37.099 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205197097.2303
2016-01-19 13:06:37.099 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-01-19 13:06:38.490 ThaliTest[2303:4793239] client: found peer: 1453205197093.1663.ldRvCg==
2016-01-19 13:06:38.491 ThaliTest[2303:4793394] jxcore: connect 1453205197093.1663.ldRvCg==
,2016-01-19 13:06:38.491 ThaliTest[2303:4793394] client session: connect
2016-01-19 13:06:38.491 ThaliTest[2303:4793394] client session: stateChange:0->1 1453205197093.1663.ldRvCg==
,2016-01-19 13:06:39.013 ThaliTest[2303:4793239] multipeer session: reset timer
2016-01-19 13:06:39.013 ThaliTest[2303:4793239] multipeer session: stop timer
2016-01-19 13:06:39.013 ThaliTest[2303:4793239] multipeer session: start timer: 0x1823da80
2016-,01-19 13:06:39.013 ThaliTest[2303:4793239] server session: connect
2016-01-19 13:06:39.013 ThaliTest[2303:4793239] server session: stateChange:0->1 1453205197093.1663
2016-01-19 13:06:39.017 ThaliTest[2303:4793239] server: accepting invitation 1453205197093.1663
,2016-01-19 13:06:41.816 ThaliTest[2303:4794854] server session: connected
2016-01-19 13:06:41.816 ThaliTest[2303:4794854] server session: stateChange:1->2 1453205197093.1663
,2016-01-19 13:06:41.832 ThaliTest[2303:4793239] server relay: socket disconnected
2016-01-19 13:06:41.832 ThaliTest[2303:4793239] server relay: 0x18026270 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 13:06:41.896 ThaliTest[2303:4794853] server session: not connected 1453205197093.1663
,2016-01-19 13:06:42.544 ThaliTest[2303:4794854] client session: connected
2016-01-19 13:06:42.544 ThaliTest[2303:4794854] client session: stateChange:1->2 1453205197093.1663.ldRvCg==
,2016-01-19 13:06:44.122 ThaliTest[2303:4794853] client session: fireConnectCallback: 1453205197093.1663.ldRvCg==
2016-01-19 13:06:44.122 ThaliTest[2303:4794853] jxcore: connect: success
ok 75 Should be able to connect without error

ok 76 Port should be within range

,2016-01-19 13:06:44.123 ThaliTest[2303:4793394] jxcore: disconnect
2016-01-19 13:06:44.125 ThaliTest[2303:4793394] client session: disconnectFromPeer: 1453205197093.1663.ldRvCg==
2016-01-19 13:06:44.125 ThaliTest[2303:4793394] client session: disconnect
2016-01-19 13:06:44.125 ThaliTest[2303:4793394] client session: stateChange:2->0 1453205197093.1663.ldRvCg==
,2016-01-19 13:06:44.131 ThaliTest[2303:4793394] jxcore: disconnect: success
ok 77 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-19 13:06:48.150 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:06:48.150 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:06:48.150 ThaliTest[2303:4793394] multipeer session: stop, timer
2016-01-19 13:06:48.150 ThaliTest[2303:4793394] server session: disconnect
2016-01-19 13:06:48.150 ThaliTest[2303:4793394] server session: stateChange:2->0 1453205197093.1663
,2016-01-19 13:06:48.150 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-19 13:07:20.706 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:07:20.708 ThaliTest[2303:4793394] server: starting 1453205240706.2303.QbT7Mg==
2016-01-19 13:07:20.708 ThaliTest[2303:4793394] multipeer session: start timer: 0x18208e20
2016-01-19 13:07:20.709 ThaliTest[2303:4793394] THEMultipeerSession in,itialized peer 1453205240706.2303
2016-01-19 13:07:20.709 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-19 13:07:24.547 ThaliTest[2303:4793239] client: found peer: 1453205240801.1663.7f7vhQ==
2016-01-19 13:07:24.548 ThaliTest[2303:4793394] jxcore: connect 1453205240801.1663.7f7vhQ==
2016-01-19 13:07:24.548 ThaliTest[2303:4793394] client session: connect
2016-01-19 13:07:24.548 ThaliTest[2303:4793394] client session: stateChange:0->1 1453205240801.1663.7f7vhQ==
,2016-01-19 13:07:25.276 ThaliTest[2303:4793239] multipeer session: reset timer
2016-01-19 13:07:25.276 ThaliTest[2303:4793239] multipeer session: stop timer
2016-01-19 13:07:25.277 ThaliTest[2303:4793239] multipeer session: start timer: 0x18208e20
2016-,01-19 13:07:25.277 ThaliTest[2303:4793239] server session: connect
2016-01-19 13:07:25.277 ThaliTest[2303:4793239] server session: stateChange:0->1 1453205240801.1663
2016-01-19 13:07:25.280 ThaliTest[2303:4793239] server: accepting invitation 1453205240801.1663
,2016-01-19 13:07:28.216 ThaliTest[2303:4794960] client session: connected
2016-01-19 13:07:28.216 ThaliTest[2303:4794960] client session: stateChange:1->2 1453205240801.1663.7f7vhQ==
,2016-01-19 13:07:28.219 ThaliTest[2303:4794962] server session: connected
2016-01-19 13:07:28.220 ThaliTest[2303:4794962] server session: stateChange:1->2 1453205240801.1663
,2016-01-19 13:07:28.279 ThaliTest[2303:4794961] client session: fireConnectCallback: 1453205240801.1663.7f7vhQ==
,2016-01-19 13:07:28.279 ThaliTest[2303:4794961] jxcore: connect: success
ok 79 Should be able to connect without error

ok 80 Port should be within range

,2016-01-19 13:07:28.281 ThaliTest[2303:4793394] jxcore: connect 1453205240801.1663.7f7vhQ==
2016-01-19 13:07:28.282 ThaliTest[2303:4793394] client: already connect(ing/ed) to 1453205240801.1663.7f7vhQ==
2016-01-19 13:07:28.282 ThaliTest[2303:4793394] jxcore: connect: fail: Aleady connecting
,2016-01-19 13:07:28.284 ThaliTest[2303:4793239] server relay: socket disconnected
2016-01-19 13:07:28.284 ThaliTest[2303:4793239] server relay: 0x1826a4a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
ok 81 Should fail on double connect

2016-01-19 13:07:28.284 ThaliTest[2303:4793394] jxcore: disconnect
,2016-01-19 13:07:28.284 ThaliTest[2303:4793394] client session: disconnectFromPeer: 1453205240801.1663.7f7vhQ==
,2016-01-19 13:07:28.286 ThaliTest[2303:4793394] client session: disconnect
2016-01-19 13:07:28.287 ThaliTest[2303:4793394] client session: stateChange:2->0 1453205240801.1663.7f7vhQ==
,2016-01-19 13:07:28.290 ThaliTest[2303:4794996] server session: not connected 1453205240801.1663
,2016-01-19 13:07:28.292 ThaliTest[2303:4793394] jxcore: disconnect: success
ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-19 13:07:32.469 ThaliTest[2303:4793239] client: lost peer: 1453205240801.1663.7f7vhQ==
2016-01-19 13:07:32.469 ThaliTest[2303:4793239] client session: onPeerLost: 1453205240801.1663.7f7vhQ==
,calling stopBroadcasting

,2016-01-19 13:07:35.532 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:07:35.532 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:07:35.532 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:07:35.532 ThaliTest[2303:4793394] server session: disconnect
2016-01-19 13:07:35.532 ThaliTest[2303:4793394] server session: stateChange:2->0 1453205240801.1663
2016-01-19 13:07:35.533 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-19 13:07:37.869 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:07:37.871 ThaliTest[2303:4793394] server: starting 1453205257869.2303.XGx20g==
2016-01-19 13:07:37.871 ThaliTest[2303:4793394] multipeer session: start timer: 0x1826a1c0
2016-01-19 13:07:37.871 ThaliTest[2303:4793394] THEMultipeerSession in,itialized peer 1453205257869.2303
2016-01-19 13:07:37.871 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-19 13:07:39.281 ThaliTest[2303:4793239] client: found peer: 1453205257830.1663.xeMcdw==
,2016-01-19 13:07:39.282 ThaliTest[2303:4793394] jxcore: connect 1453205257830.1663.xeMcdw==
2016-01-19 13:07:39.282 ThaliTest[2303:4793394] client session: connect
2016-01-19 13:07:39.282 ThaliTest[2303:4793394] client session: stateChange:0->1 145320525,7830.1663.xeMcdw==
,2016-01-19 13:07:39.479 ThaliTest[2303:4793239] multipeer session: reset timer
2016-01-19 13:07:39.479 ThaliTest[2303:4793239] multipeer session: stop timer
2016-01-19 13:07:39.480 ThaliTest[2303:4793239] multipeer session: start timer: 0x1826a1c0
2016-01-19 13:07:39.480 ThaliTest[2303:4793239] server session: connect
2016-01-19 13:07:39.480 ThaliTest[2303:4793239] server session: stateChange:0->1 1453205257830.1663
,2016-01-19 13:07:39.483 ThaliTest[2303:4793239] server: accepting invitation 1453205257830.1663
,2016-01-19 13:07:41.937 ThaliTest[2303:4794961] client session: connected
2016-01-19 13:07:41.937 ThaliTest[2303:4794961] client session: stateChange:1->2 1453205257830.1663.xeMcdw==
2016-01-19 13:07:41.938 ThaliTest[2303:4794961] client session: fireCon,nectCallback: 1453205257830.1663.xeMcdw==
2016-01-19 13:07:41.938 ThaliTest[2303:4794961] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

2016-01-19 13:07:41.939 ThaliTest[2303:4793394] jxcore: disconnect
2016-01-19 13:07:41.939 ThaliTest[2303:4793394] client session: disconnectFromPeer: 1453205257830.1663.xeMcdw==
2016-01-19 13:07:41.939 ThaliTest[2303:4793394] client session: disconnect
2016-01-19 13:07:41.939 ThaliTest[2303:4793394] client session: stateChange:2->0 1453205257830.1663.xeMcdw==
,2016-01-19 13:07:42.000 ThaliTest[2303:4793394] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

,2016-01-19 13:07:42.002 ThaliTest[2303:4793394] jxcore: disconnect
2016-01-19 13:07:42.002 ThaliTest[2303:4793394] jxcore: disconnect: fail
,ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-19 13:07:42.114 ThaliTest[2303:4794996] server session: connected
2016-01-19 13:07:42.114 ThaliTest[2303:4794996] server session: stateChange:1->2 1453205257830.1663
,2016-01-19 13:07:42.118 ThaliTest[2303:4793239] server relay: socket disconnected
2016-01-19 13:07:42.118 ThaliTest[2303:4793239] server relay: 0x180027c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 13:07:42.165 ThaliTest[2303:4794960] server session: not connected 1453205257830.1663
,calling stopBroadcasting

,2016-01-19 13:07:42.313 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:07:42.313 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:07:42.313 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:07:42.,313 ThaliTest[2303:4793394] server session: disconnect
2016-01-19 13:07:42.313 ThaliTest[2303:4793394] server session: stateChange:2->0 1453205257830.1663
2016-01-19 13:07:42.314 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 54436

,2016-01-19 13:08:06.647 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:08:06.653 ThaliTest[2303:4793394] server: starting 1453205286647.2303.1bqqgQ==
,2016-01-19 13:08:06.664 ThaliTest[2303:4793394] multipeer session: start timer: 0x1826d250
2016-01-19 13:08:06.668 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205286647.2303
2016-01-19 13:08:06.668 ThaliTest[2303:4793239] client: found peer: 1453205265030.1663./j16aQ==
2016-01-19 13:08:06.668 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error

,2016-01-19 13:08:06.673 ThaliTest[2303:4793394] jxcore: connect 1453205265030.1663./j16aQ==
,2016-01-19 13:08:06.674 ThaliTest[2303:4793394] client session: connect
,2016-01-19 13:08:06.675 ThaliTest[2303:4793394] client session: stateChange:0->1 1453205265030.1663./j16aQ==
,2016-01-19 13:08:08.054 ThaliTest[2303:4793239] multipeer session: reset timer
2016-01-19 13:08:08.054 ThaliTest[2303:4793239] multipeer session: stop timer
2016-01-19 13:08:08.054 ThaliTest[2303:4793239] multipeer session: start timer: 0x1826d250
2016-,01-19 13:08:08.054 ThaliTest[2303:4793239] server session: connect
2016-01-19 13:08:08.054 ThaliTest[2303:4793239] server session: stateChange:0->1 1453205265030.1663
,2016-01-19 13:08:08.058 ThaliTest[2303:4793239] server: accepting invitation 1453205265030.1663
,2016-01-19 13:08:09.753 ThaliTest[2303:4795081] client session: connected
2016-01-19 13:08:09.753 ThaliTest[2303:4795081] client session: stateChange:1->2 1453205265030.1663./j16aQ==
,2016-01-19 13:08:09.755 ThaliTest[2303:4795081] client session: fireConnectCallback: 1453205265030.1663./j16aQ==
2016-01-19 13:08:09.755 ThaliTest[2303:4795081] jxcore: connect: success
,ok 89 Should be able to connect without error

ok 90 Port should be within range

,2016-01-19 13:08:09.758 ThaliTest[2303:4793239] client: relay established
2016-01-19 13:08:09.758 ThaliTest[2303:4793239] client: new accepted socket: 0x1826e750
,data in 38912

,data in 41468

,data in 49275

,data in 68985

,data in 78840

,data in 88695

,data in 96360

,data in 102930

,data in 110595

,data in 118260

,data in 127020

,data in 131072

ok 91 the test messages should be equal

2016-01-19 13:08:10.948 ThaliTest[2303:4793394] jxcore: disconnect
2016-01-19 13:08:10.948 ThaliTest[2303:4793394] client session: disconnectFromPeer: 1453205265030.1663./j16aQ==
2016-01-19 13:08:10.948 ThaliTest[2303:4793394] client session: disconnect
2016-01-19 13:08:10.948 ThaliTest[2303:4793394] client session: stateChange:2->0 1453205265030.1663./j16aQ==
,2016-01-19 13:08:10.954 ThaliTest[2303:4793394] jxcore: disconnect: success
ok 92 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

# setup

,2016-01-19 13:08:11.328 ThaliTest[2303:4795053] server session: connected
2016-01-19 13:08:11.328 ThaliTest[2303:4795053] server session: stateChange:1->2 1453205265030.1663
,2016-01-19 13:08:11.330 ThaliTest[2303:4793239] server relay: connected (to port: 54436)
,2016-01-19 13:08:12.911 ThaliTest[2303:4795052] server session: not connected 1453205265030.1663
,2016-01-19 13:08:14.983 ThaliTest[2303:4793239] client: lost peer: 1453205265030.1663./j16aQ==
2016-01-19 13:08:14.983 ThaliTest[2303:4793239] client session: onPeerLost: 1453205265030.1663./j16aQ==
,calling stopBroadcasting

,2016-01-19 13:08:18.209 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:08:18.209 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:08:18.210 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:08:18.210 ThaliTest[2303:4793394] server session: disconnect
2016-01-19 13:08:18.210 ThaliTest[2303:4793394] server session: stateChange:2->0 1453205265030.1663
2016-01-19 13:08:18.212 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 54442

,2016-01-19 13:08:18.295 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:08:18.296 ThaliTest[2303:4793394] server: starting 1453205298295.2303.TUJ6lA==
2016-01-19 13:08:18.297 ThaliTest[2303:4793394] multipeer session: start timer: 0x183cf720
2016-01-19 13:08:18.297 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 1453205298295.2303
2016-01-19 13:08:18.297 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error

,2016-01-19 13:08:19.341 ThaliTest[2303:4793239] client: found peer: 1453205286647.2303.1bqqgQ==
[{"peerIdentifier":"1453205286647.2303.1bqqgQ==","peerName":"(null)","peerAvailable":true}]

2016-01-19 13:08:19.342 ThaliTest[2303:4793394] jxcore: connect ,1453205286647.2303.1bqqgQ==
2016-01-19 13:08:19.342 ThaliTest[2303:4793394] client session: connect
2016-01-19 13:08:19.342 ThaliTest[2303:4793394] client session: stateChange:0->1 1453205286647.2303.1bqqgQ==
,2016-01-19 13:08:19.424 ThaliTest[2303:4793239] client: lost peer: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:19.424 ThaliTest[2303:4793239] client session: onPeerLost: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:19.424 ThaliTest[2303:4793239] client ,session: onLinkFailure: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:19.424 ThaliTest[2303:4793239] client session: disconnect
2016-01-19 13:08:19.424 ThaliTest[2303:4793239] client session: stateChange:1->0 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:19.424 ThaliTest[2303:4793239] client session: fireConnectCallback: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:19.425 ThaliTest[2303:4793239] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1453205286647.2303.1bqqgQ==","peerName":"(null)","peerAvailable":false}]

,2016-01-19 13:08:20.301 ThaliTest[2303:4793239] multipeer session: reset timer
2016-01-19 13:08:20.301 ThaliTest[2303:4793239] multipeer session: stop timer
2016-01-19 13:08:20.301 ThaliTest[2303:4793239] multipeer session: start timer: 0x183cf720
2016-01-19 13:08:20.301 ThaliTest[2303:4793239] server session: connect
2016-01-19 13:08:20.301 ThaliTest[2303:4793239] server session: stateChange:0->1 1453205298240.1663
,2016-01-19 13:08:20.305 ThaliTest[2303:4793239] server: accepting invitation 1453205298240.1663
,2016-01-19 13:08:20.426 ThaliTest[2303:4793394] jxcore: connect 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:20.426 ThaliTest[2303:4793394] client: connect: unreachable 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:20.426 ThaliTest[2303:4793394] jxcore: connect: fail: Peer unreachable
,2016-01-19 13:08:21.170 ThaliTest[2303:4793239] client: found peer: 1453205298240.1663.Ai0/lA==
[{"peerIdentifier":"1453205298240.1663.Ai0/lA==","peerName":"(null)","peerAvailable":true}]

2016-01-19 13:08:21.171 ThaliTest[2303:4793394] jxcore: connect 1453205298240.1663.Ai0/lA==
2016-01-19 13:08:21.171 ThaliTest[2303:4793394] client session: connect
2016-01-19 13:08:21.171 ThaliTest[2303:4793394] client session: stateChange:0->1 1453205298240.1663.Ai0/lA==
,2016-01-19 13:08:23.005 ThaliTest[2303:4794962] server session: connected
2016-01-19 13:08:23.006 ThaliTest[2303:4794962] server session: stateChange:1->2 1453205298240.1663
,2016-01-19 13:08:23.053 ThaliTest[2303:4793239] server relay: connected (to port: 54442)
,2016-01-19 13:08:23.163 ThaliTest[2303:4795052] server session: not connected 1453205298240.1663
,2016-01-19 13:08:23.199 ThaliTest[2303:4793239] multipeer session: reset timer
2016-01-19 13:08:23.199 ThaliTest[2303:4793239] multipeer session: stop timer
2016-01-19 13:08:23.199 ThaliTest[2303:4793239] multipeer session: start timer: 0x183cf720
2016-,01-19 13:08:23.200 ThaliTest[2303:4793239] server: disconnecting to refresh session (1453205298240.1663)
2016-01-19 13:08:23.200 ThaliTest[2303:4793239] server session: disconnect
2016-01-19 13:08:23.200 ThaliTest[2303:4793239] server session: stateChange:2->0 1453205298240.1663
2016-01-19 13:08:23.202 ThaliTest[2303:4793239] server session: connect
2016-01-19 13:08:23.202 ThaliTest[2303:4793239] server session: stateChange:0->1 1453205298240.1663
2016-01-19 13:08:23.206 ThaliTest[2303:4793239] server: accepting invitation 1453205298240.1663
,2016-01-19 13:08:24.300 ThaliTest[2303:4795081] client session: connected
2016-01-19 13:08:24.300 ThaliTest[2303:4795081] client session: stateChange:1->2 1453205298240.1663.Ai0/lA==
,2016-01-19 13:08:24.312 ThaliTest[2303:4795094] client session: fireConnectCallback: 1453205298240.1663.Ai0/lA==
2016-01-19 13:08:24.312 ThaliTest[2303:4795094] jxcore: connect: success
,ok 94 Should be able to connect without error

ok 95 Port should be within range

ok 96 First connect should succeed

,2016-01-19 13:08:24.324 ThaliTest[2303:4793239] client: relay established
2016-01-19 13:08:24.324 ThaliTest[2303:4793239] client: new accepted socket: 0x185532e0
,ok 97 the test messages should be equal

ok 98 First send should succeed

,2016-01-19 13:08:24.396 ThaliTest[2303:4793239] client: socket closed
2016-01-19 13:08:24.396 ThaliTest[2303:4793239] client relay: socket disconnected
2016-01-19 13:08:24.396 ThaliTest[2303:4793239] client relay: 0x185532e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 13:08:24.396 ThaliTest[2303:4793239] client session: socket closed: 1453205298240.1663.Ai0/lA==
2016-01-19 ,13:08:24.396 ThaliTest[2303:4793239] client session: onLinkFailure: 1453205298240.1663.Ai0/lA==
2016-01-19 13:08:24.396 ThaliTest[2303:4793239] client session: disconnect
2016-01-19 13:08:24.396 ThaliTest[2303:4793239] client session: stateChange:2->0 1453205298240.1663.Ai0/lA==
,2016-01-19 13:08:24.400 ThaliTest[2303:4793239] client session: fireConnectionErrorEvent: 1453205298240.1663.Ai0/lA==
,2016-01-19 13:08:24.406 ThaliTest[2303:4793394] jxcore: connect 1453205298240.1663.Ai0/lA==
,2016-01-19 13:08:24.406 ThaliTest[2303:4793394] client session: connect
,2016-01-19 13:08:24.406 ThaliTest[2303:4793394] client session: stateChange:0->1 1453205298240.1663.Ai0/lA==
,2016-01-19 13:08:25.609 ThaliTest[2303:4794962] server session: connected
2016-01-19 13:08:25.609 ThaliTest[2303:4794962] server session: stateChange:1->2 1453205298240.1663
,2016-01-19 13:08:25.622 ThaliTest[2303:4793239] server relay: connected (to port: 54442)
,2016-01-19 13:08:25.740 ThaliTest[2303:4795053] server session: not connected 1453205298240.1663
,2016-01-19 13:08:26.984 ThaliTest[2303:4795052] client session: connected
,2016-01-19 13:08:26.984 ThaliTest[2303:4795052] client session: stateChange:1->2 1453205298240.1663.Ai0/lA==
,2016-01-19 13:08:26.997 ThaliTest[2303:4794962] client session: fireConnectCallback: 1453205298240.1663.Ai0/lA==
2016-01-19 13:08:26.997 ThaliTest[2303:4794962] jxcore: connect: success
ok 99 Should be able to connect without error

ok 100 Port should be within range

ok 101 Second connect should succeed

,2016-01-19 13:08:27.008 ThaliTest[2303:4793239] client: relay established
2016-01-19 13:08:27.009 ThaliTest[2303:4793239] client: new accepted socket: 0x18121b00
,ok 102 the test messages should be equal

ok 103 Second send should succeed

,# setup

,2016-01-19 13:08:27.081 ThaliTest[2303:4793239] client: socket closed
2016-01-19 13:08:27.081 ThaliTest[2303:4793239] client relay: socket disconnected
2016-01-19 13:08:27.081 ThaliTest[2303:4793239] client relay: 0x18121b00 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 13:08:27.081 ThaliTest[2303:4793239] client session: socket closed: 1453205298240.1663.Ai0/lA==
2016-01-19 ,13:08:27.081 ThaliTest[2303:4793239] client session: onLinkFailure: 1453205298240.1663.Ai0/lA==
2016-01-19 13:08:27.082 ThaliTest[2303:4793239] client session: disconnect
2016-01-19 13:08:27.082 ThaliTest[2303:4793239] client session: stateChange:2->0 14,53205298240.1663.Ai0/lA==
,2016-01-19 13:08:27.086 ThaliTest[2303:4793239] client session: fireConnectionErrorEvent: 1453205298240.1663.Ai0/lA==
,calling stopBroadcasting

,2016-01-19 13:08:27.317 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:08:27.317 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:08:27.318 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:08:27.318 ThaliTest[2303:4793394] server session: disconnect
2016-01-19 13:08:27.318 ThaliTest[2303:4793394] server session: stateChange:2->0 1453205298240.1663
,2016-01-19 13:08:27.321 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D8A44167-9991-4AAE-BEA3-00FB4F91B37B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 104 starting event should occur in right order

,2016-01-19 13:08:27.949 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:08:27.950 ThaliTest[2303:4793394] server: starting 6gP7M22GtxeQW1i5FtSKJw.KdnIcg==
2016-01-19 13:08:27.950 ThaliTest[2303:4793394] multipeer session: start timer: 0x182ae690
2016-01-19 13:08:27.950 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 6gP7M22GtxeQW1i5FtSKJw
2016-01-19 13:08:27.950 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 105 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 106 stopping event sh,ould occur in right order

About to call stopBroadcasting

2016-01-19 13:08:27.952 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:08:27.952 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
2016-01-19 13:08:27.952 ThaliTest[2303:4793394] multipeer session: stop timer
,2016-01-19 13:08:27.953 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 107 stopped event should occur in right order

mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D8A44167-9991-4AAE-BEA3-00FB4F91B37B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 13:08:56.834 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:08:56.835 ThaliTest[2303:4793394] server: starting 6gP7M22GtxeQW1i5FtSKJw.ElG5Tw==
2016-01-19 13:08:56.836 ThaliTest[2303:4793394] multipeer session: start timer: 0x1811ee50
2016-01-19 13:08:56.836 ThaliTest[2303:4793394] THEMultipeerSessio,n initialized peer 6gP7M22GtxeQW1i5FtSKJw
2016-01-19 13:08:56.836 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error

ok 109 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-19 13:08:56.837 ThaliTest[2303:4793394] jxcore: stopBroadcasting
2016-01-19 13:08:56.837 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
,2016-01-19 13:08:56.837 ThaliTest[2303:4793394] multipeer session: stop timer
2016-01-19 13:08:56.840 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D8A44167-9991-4AAE-BEA3-00FB4F91B37B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 13:09:00.027 ThaliTest[2303:4793394] jxcore: startBroadcasting
,2016-01-19 13:09:00.028 ThaliTest[2303:4793394] server: starting 6gP7M22GtxeQW1i5FtSKJw.IJ9dOQ==
,2016-01-19 13:09:00.029 ThaliTest[2303:4793394] multipeer session: start timer: 0x1a048f40
,2016-01-19 13:09:00.033 ThaliTest[2303:4793394] THEMultipeerSession initialized peer 6gP7M22GtxeQW1i5FtSKJw
,2016-01-19 13:09:00.034 ThaliTest[2303:4793394] jxcore: startBroadcasting: success
,ok 110 getDeviceIdentity should not return an error

,ok 111 deviceName should not be null

,2016-01-19 13:09:03.224 ThaliTest[2303:4793239] client: found peer: ZALoHjYW3sRDixBUBWPxWw.+7ZUbA==
,2016-01-19 13:09:05.709 ThaliTest[2303:4793394] jxcore: connect ZALoHjYW3sRDixBUBWPxWw.+7ZUbA==
,2016-01-19 13:09:05.710 ThaliTest[2303:4793394] client session: connect
,2016-01-19 13:09:05.711 ThaliTest[2303:4793394] client session: stateChange:0->1 ZALoHjYW3sRDixBUBWPxWw.+7ZUbA==
,ok 112 Should be able to put doc without error

,ok 113 1st change of local doc should contain local id

,2016-01-19 13:09:12.211 ThaliTest[2303:4793239] multipeer session: reset timer
2016-01-19 13:09:12.211 ThaliTest[2303:4793239] multipeer session: stop timer
2016-01-19 13:09:12.211 ThaliTest[2303:4793239] multipeer session: start timer: 0x1a048f40
2016-01-19 13:09:12.211 ThaliTest[2303:4793239] server session: connect
2016-01-19 13:09:12.211 ThaliTest[2303:4793239] server session: stateChange:0->1 ZALoHjYW3sRDixBUBWPxWw
,2016-01-19 13:09:12.214 ThaliTest[2303:4793239] server: accepting invitation ZALoHjYW3sRDixBUBWPxWw
,2016-01-19 13:09:14.718 ThaliTest[2303:4795145] client session: connected
2016-01-19 13:09:14.718 ThaliTest[2303:4795145] client session: stateChange:1->2 ZALoHjYW3sRDixBUBWPxWw.+7ZUbA==
,2016-01-19 13:09:14.754 ThaliTest[2303:4795202] server session: connected
2016-01-19 13:09:14.754 ThaliTest[2303:4795202] server session: stateChange:1->2 ZALoHjYW3sRDixBUBWPxWw
,2016-01-19 13:09:14.813 ThaliTest[2303:4793239] server relay: connected (to port: 54460)
,server bridge: new client socket

,2016-01-19 13:09:15.206 ThaliTest[2303:4795202] client session: fireConnectCallback: ZALoHjYW3sRDixBUBWPxWw.+7ZUbA==
2016-01-19 13:09:15.206 ThaliTest[2303:4795202] jxcore: connect: success
,2016-01-19 13:09:15.209 ThaliTest[2303:4793239] client: relay established
2016-01-19 13:09:15.210 ThaliTest[2303:4793239] client: new accepted socket: 0x190bdde0
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

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

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 114 1st change of remote doc should contain remote id

,ok 115 Can update remote doc without error
,
null

,{ ok: true,
  id: '7802b954-5f6c-4873-b053-130558fb6045',
  rev: '2-112fdd709d802037a1b578263162d0d9' }

,client bridge: new client socket

,ok 116 Remote changes occur in strict order

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

client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
client bridge: socket closed
,
,ok 117 Local changes occur in strict order

,ok 118 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,Now in TRM stop
,
,State of this._isStarted: true

,About to call stopBroadcasting

,2016-01-19 13:09:33.375 ThaliTest[2303:4793394] jxcore: stopBroadcasting
,2016-01-19 13:09:33.376 ThaliTest[2303:4793394] THEMultipeerSession stopping peer
,2016-01-19 13:09:33.376 ThaliTest[2303:4793394] multipeer session: stop timer
,2016-01-19 13:09:33.377 ThaliTest[2303:4793394] client session: disconnect
,2016-01-19 13:09:33.379 ThaliTest[2303:4793394] client session: stateChange:2->0 ZALoHjYW3sRDixBUBWPxWw.+7ZUbA==
,2016-01-19 13:09:33.426 ThaliTest[2303:4795239] server session: not connected ZALoHjYW3sRDixBUBWPxWw
,2016-01-19 13:09:33.453 ThaliTest[2303:4793394] server session: disconnect
,2016-01-19 13:09:33.458 ThaliTest[2303:4793394] server session: stateChange:2->0 ZALoHjYW3sRDixBUBWPxWw
,2016-01-19 13:09:33.523 ThaliTest[2303:4793394] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,Error in mux client bridge Error: write EPIPE

,mux server bridge listener closed

,client bridge: new client socket

,2016-01-19 13:09:33.549 ThaliTest[2303:4793394] Error!: connect ECONNRESET
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$09","_lineNumber",:"829","_columnNumber":"13","_msg":"    at $09@net.js:829:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
Uncaught Exception: Error: connect ECONNRESET

,[ { _fileName: 'net.js',
    _functionName: '$c',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '    at $c@net.js:837:7' },
  { _fileName: 'net.js',
    _functionName: '$09',
    _lineNumber: '829',
    _columnNumber: '13',
    _msg: '    at $09@net.js:829:13' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

syncRetry called when not started

client bridge: socket closed

server bridge: socket closed


```
