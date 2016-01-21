#### Test 56672827b6f75d5_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56672827b6f75d5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FB5360C2-859F-49B3-823E-CD6097980B41/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FB5360C2-859F-49B3-823E-CD6097980B41/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56672827b6f75d5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56672827b6f75d5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59737"
,(lldb)     command script import "/tmp/FB5360C2-859F-49B3-823E-CD6097980B41/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 17:44:22.615 ThaliTest[2417:6196526] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AA07B46B-AE3B-4729-BF8A-9D973EA39741/Library/Cookies/Cookies.binarycookies
,2016-01-21 17:44:22.915 ThaliTest[2417:6196526] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-21 17:44:22.916 ThaliTest[2417:6196526] Multi-tasking -> Device: YES, App: YES
,2016-01-21 17:44:22.924 ThaliTest[2417:6196526] Unlimited access to network resources
,2016-01-21 17:44:22.934 ThaliTest[2417:6196526] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 17:44:27.538 ThaliTest[2417:6196526] Resetting plugins due to page load.
,2016-01-21 17:44:29.180 ThaliTest[2417:6196526] Finished load of: file:///var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/index.html
,2016-01-21 17:44:29.398 ThaliTest[2417:6196526] JXcore Cordova plugin initializing
2016-01-21 17:44:29.402 ThaliTest[2417:6196681] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout expected 0 and got 0

,ok 3 firstPromise result expected 10 and got 10

,ok 4 firstPromise testValue expected 10 and got 10

,ok 5 secondPromise setTimeout expected 10 and got 10

,ok 6 secondPromise result expected 100 and got 100

,ok 7 secondPromise testValue expected 100 and got 100

,ok 8 thirdPromise in promise expected 100 and got 100

,ok 9 thirdPromise result expected 1000 and got 1000

,ok 10 thirdPromise result expected 1000 and got 1000

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

,ok 16 should be equal

,ok 17 should not throw

,# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

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

# setup

,# #init should register the networkChanged event

,# teardown

,ok 28 should be equal

# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 29 should throw

# setup

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

# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

ok 36 should be equal

ok 37 should be equal

# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

,ok 39 should be equal

ok 40 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

,ok 42 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

ok 46 should be equal

ok 47 should be equal

# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

ok 49 should be equal

,# setup
,
,# should call Mobile("Disconnect") without an error
,
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

,2016-01-21 17:48:20.832 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:20.841 ThaliTest[2417:6196681] server: starting 1453394900832.2417.dXgLBA==
,2016-01-21 17:48:20.843 ThaliTest[2417:6196681] multipeer session: start timer: 0x16bebab0
,2016-01-21 17:48:20.847 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394900832.2417
,2016-01-21 17:48:20.848 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.850 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:20.851 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.852 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:20.854 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,ok 55 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:20.856 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:20.859 ThaliTest[2417:6196681] server: starting 1453394900856.2417.qrcK5Q==
,2016-01-21 17:48:20.861 ThaliTest[2417:6196681] multipeer session: start timer: 0x15eb05a0
2016-01-21 17:48:20.863 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394900856.2417
,2016-01-21 17:48:20.863 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.865 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:20.866 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.866 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:20.867 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:20.870 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:20.873 ThaliTest[2417:6196681] server: starting 1453394900870.2417.I+UvHQ==
,2016-01-21 17:48:20.874 ThaliTest[2417:6196681] multipeer session: start timer: 0x16bc9410
,2016-01-21 17:48:20.876 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394900870.2417
,2016-01-21 17:48:20.876 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.878 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:20.879 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.879 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:20.880 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:20.883 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:20.885 ThaliTest[2417:6196681] server: starting 1453394900883.2417./g1v8Q==
,2016-01-21 17:48:20.886 ThaliTest[2417:6196681] multipeer session: start timer: 0x15eab270
,2016-01-21 17:48:20.889 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394900883.2417
,2016-01-21 17:48:20.889 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.891 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:20.891 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.891 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:20.893 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:20.895 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:20.897 ThaliTest[2417:6196681] server: starting 1453394900895.2417.GVahqg==
,2016-01-21 17:48:20.898 ThaliTest[2417:6196681] multipeer session: start timer: 0x16bc9a70
,2016-01-21 17:48:20.901 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394900895.2417
,2016-01-21 17:48:20.901 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.903 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:20.903 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.904 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:20.905 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:20.908 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:20.909 ThaliTest[2417:6196681] server: starting 1453394900907.2417.m4FGKQ==
,2016-01-21 17:48:20.911 ThaliTest[2417:6196681] multipeer session: start timer: 0x16bcb200
,2016-01-21 17:48:20.913 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394900907.2417
,2016-01-21 17:48:20.914 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.915 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:20.916 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.916 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:20.917 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:20.920 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:20.922 ThaliTest[2417:6196681] server: starting 1453394900919.2417.0glirA==
,2016-01-21 17:48:20.923 ThaliTest[2417:6196681] multipeer session: start timer: 0x16bca820
,2016-01-21 17:48:20.925 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394900919.2417
,2016-01-21 17:48:20.925 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.927 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:20.927 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.928 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:20.930 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:20.932 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:20.933 ThaliTest[2417:6196681] server: starting 1453394900932.2417.q8kGwQ==
,2016-01-21 17:48:20.935 ThaliTest[2417:6196681] multipeer session: start timer: 0x15ea9af0
,2016-01-21 17:48:20.936 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394900932.2417
,2016-01-21 17:48:20.937 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.939 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:20.940 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.940 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:20.942 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error
,
,2016-01-21 17:48:20.943 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:20.945 ThaliTest[2417:6196681] server: starting 1453394900943.2417.Di0ztg==
,2016-01-21 17:48:20.947 ThaliTest[2417:6196681] multipeer session: start timer: 0x15eaa250
,2016-01-21 17:48:20.948 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394900943.2417
,2016-01-21 17:48:20.948 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.950 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:20.951 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.951 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:20.954 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:20.956 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:20.957 ThaliTest[2417:6196681] server: starting 1453394900955.2417.GqEMdQ==
,2016-01-21 17:48:20.958 ThaliTest[2417:6196681] multipeer session: start timer: 0x15eaa820
,2016-01-21 17:48:20.961 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394900955.2417
,2016-01-21 17:48:20.962 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.964 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:20.964 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.965 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:20.966 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-21 17:48:21.308 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:21.310 ThaliTest[2417:6196681] server: starting 1453394901308.2417.HJzQ0A==
2016-01-21 17:48:21.311 ThaliTest[2417:6196681] multipeer session: start timer: 0x16bcf510
2016-01-21 17:48:21.311 ThaliTest[2417:6196681] THEMultipeerSession in,itialized peer 1453394901308.2417
2016-01-21 17:48:21.311 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-21 17:48:21.312 ThaliTest[2417:6196681] jxcore: startBroadcasting
2016-01-21 17:48:21.312 ThaliTest[2417:6196681] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-01-21 17:48:21.314 ThaliTest[2417:6196681] jxcore: stopBroadcasting
2016-01-21 17:48:21.315 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
2016-01-21 17:48:21.315 ThaliTest[2417:6196681] multipeer session: stop timer
2016-01-21 17:48:21.315 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-21 17:48:21.810 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:21.813 ThaliTest[2417:6196681] server: starting 1453394901810.2417.AiFR0g==
2016-01-21 17:48:21.813 ThaliTest[2417:6196681] multipeer session: start timer: 0x16bbd940
2016-01-21 17:48:21.813 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394901810.2417
2016-01-21 17:48:21.813 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-21 17:48:21.814 ThaliTest[2417:6196681] jxcore: connect foobar
2,016-01-21 17:48:21.815 ThaliTest[2417:6196681] client: unknown peer foobar
,2016-01-21 17:48:21.815 ThaliTest[2417:6196681] jxcore: connect: fail: Unknown peer
ok 78 Should not connect to a bad peer

2016-01-21 17:48:21.820 ThaliTest[2417:6196681] jxcore: stopBroadcasting
2016-01-21 17:48:21.820 ThaliTest[2417:6196681] THEMult,ipeerSession stopping peer
2016-01-21 17:48:21.820 ThaliTest[2417:6196681] multipeer session: stop timer
2016-01-21 17:48:21.820 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

# s,etup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-21 17:48:23.360 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:23.363 ThaliTest[2417:6196681] server: starting 1453394903360.2417.LypXKw==
2016-01-21 17:48:23.363 ThaliTest[2417:6196681] multipeer session: start timer: 0x16bad030
2016-01-21 17:48:23.363 ThaliTest[2417:6196681] THEMultipeerSession in,itialized peer 1453394903360.2417
2016-01-21 17:48:23.364 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-21 17:48:23.365 ThaliTest[2417:6196681] jxcore: disconnect
2016-,01-21 17:48:23.365 ThaliTest[2417:6196681] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

,2016-01-21 17:48:23.367 ThaliTest[2417:6196681] jxcore: stopBroadcasting
2016-01-21 17:48:23.368 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
2016-01-21 17:48:23.368 ThaliTest[2417:6196681] multipeer session: stop timer
2016-01-21 17:48:23.368 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-21 17:48:26.370 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:26.372 ThaliTest[2417:6196681] server: starting 1453394906370.2417.pTTmAA==
2016-01-21 17:48:26.372 ThaliTest[2417:6196681] multipeer session: start timer: 0x16ba7be0
2016-01-21 17:48:26.372 ThaliTest[2417:6196681] THEMultipeerSession in,itialized peer 1453394906370.2417
2016-01-21 17:48:26.372 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-21 17:48:27.506 ThaliTest[2417:6196526] client: found peer: 1453394906446.1784.e3FjXw==
2016-01-21 17:48:27.507 ThaliTest[2417:6196681] jxcore: connect 1453394906446.1784.e3FjXw==
2016-01-21 17:48:27.508 ThaliTest[2417:6196681] client session: co,nnect
2016-01-21 17:48:27.508 ThaliTest[2417:6196681] client session: stateChange:0->1 1453394906446.1784.e3FjXw==
,2016-01-21 17:48:27.763 ThaliTest[2417:6196526] multipeer session: reset timer
2016-01-21 17:48:27.764 ThaliTest[2417:6196526] multipeer session: stop timer
2016-01-21 17:48:27.764 ThaliTest[2417:6196526] multipeer session: start timer: 0x16ba7be0
2016-,01-21 17:48:27.764 ThaliTest[2417:6196526] server session: connect
2016-01-21 17:48:27.764 ThaliTest[2417:6196526] server session: stateChange:0->1 1453394906446.1784
2016-01-21 17:48:27.768 ThaliTest[2417:6196526] server: accepting invitation 1453394906,446.1784
,2016-01-21 17:48:30.181 ThaliTest[2417:6197360] server session: connected
2016-01-21 17:48:30.181 ThaliTest[2417:6197360] server session: stateChange:1->2 1453394906446.1784
,2016-01-21 17:48:30.190 ThaliTest[2417:6196526] server relay: socket disconnected
2016-01-21 17:48:30.191 ThaliTest[2417:6196526] server relay: 0x16b9a450 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
2016-01-21 17:48:30.191 ThaliTest[2417:6197358] client session: connected
,2016-01-21 17:48:30.191 ThaliTest[2417:6197358] client session: stateChange:1->2 1453394906446.1784.e3FjXw==
2016-01-21 17:48:30.196 ThaliTest[2417:6197358] client session: fireConnectCallback: 1453394906446.1784.e3FjXw==
,2016-01-21 17:48:30.196 ThaliTest[2417:6197358] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

2016-01-21 17:48:30.200 ThaliTest[2417:6196681] jxcore: disconnect
2016-01-21 17:48:30.200 ThaliTest[2417:6196681] client session: disconnectFromPeer: 1453394906446.1784.e3FjXw==
2016-01-21 17:48:30.200 ThaliTest[2417:6196681] client session: disconnect
2016-01-21 17:48:30.200 ThaliTest[2417:6196681] client session: stateChange:2->0 1453394906446.,1784.e3FjXw==
,2016-01-21 17:48:30.231 ThaliTest[2417:6197358] server session: not connected 1453394906446.1784
,2016-01-21 17:48:30.267 ThaliTest[2417:6196681] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-21 17:48:31.042 ThaliTest[2417:6196681] jxcore: stopBroadcasting
2016-01-21 17:48:31.042 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
2016-01-21 17:48:31.042 ThaliTest[2417:6196681] multipeer session: stop timer
2016-01-21 17:48:31.043 ThaliTest[2417:6196681] server session: disconnect
2016-01-21 17:48:31.043 ThaliTest[2417:6196681] server session: stateChange:2->0 1453394906446.1784
,2016-01-21 17:48:31.043 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-21 17:48:33.196 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:33.199 ThaliTest[2417:6196681] server: starting 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:33.199 ThaliTest[2417:6196681] multipeer session: start timer: 0x16953e00
2016-01-21 17:48:33.199 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394913196.2417
2016-01-21 17:48:33.199 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-21 17:48:34.309 ThaliTest[2417:6196526] client: found peer: 1453394913286.1784.d06l1w==
2016-01-21 17:48:34.310 ThaliTest[2417:6196681] jxcore: connect 1453394913286.1784.d06l1w==
2016-01-21 17:48:34.310 ThaliTest[2417:6196681] client session: co,nnect
2016-01-21 17:48:34.310 ThaliTest[2417:6196681] client session: stateChange:0->1 1453394913286.1784.d06l1w==
,2016-01-21 17:48:34.452 ThaliTest[2417:6196526] multipeer session: reset timer
2016-01-21 17:48:34.452 ThaliTest[2417:6196526] multipeer session: stop timer
2016-01-21 17:48:34.452 ThaliTest[2417:6196526] multipeer session: start timer: 0x16953e00
2016-,01-21 17:48:34.453 ThaliTest[2417:6196526] server session: connect
2016-01-21 17:48:34.453 ThaliTest[2417:6196526] server session: stateChange:0->1 1453394913286.1784
2016-01-21 17:48:34.457 ThaliTest[2417:6196526] server: accepting invitation 1453394913286.1784
,2016-01-21 17:48:37.095 ThaliTest[2417:6197356] server session: connected
2016-01-21 17:48:37.096 ThaliTest[2417:6197356] server session: stateChange:1->2 1453394913286.1784
,2016-01-21 17:48:37.098 ThaliTest[2417:6196526] server relay: socket disconnected
2016-01-21 17:48:37.098 ThaliTest[2417:6196526] server relay: 0x16b96200 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-21 17:48:37.204 ThaliTest[2417:6197358] server session: not connected 1453394913286.1784
,2016-01-21 17:48:37.265 ThaliTest[2417:6197360] client session: connected
,2016-01-21 17:48:37.267 ThaliTest[2417:6197360] client session: stateChange:1->2 1453394913286.1784.d06l1w==
,2016-01-21 17:48:37.270 ThaliTest[2417:6197360] client session: fireConnectCallback: 1453394913286.1784.d06l1w==
2016-01-21 17:48:37.270 ThaliTest[2417:6197360] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-01-21 17:48:37.272 ThaliTest[2417:6196681] jxcore: connect 1453394913286.1784.d06l1w==
,2016-01-21 17:48:37.272 ThaliTest[2417:6196681] client: already connect(ing/ed) to 1453394913286.1784.d06l1w==
,2016-01-21 17:48:37.273 ThaliTest[2417:6196681] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

2016-01-21 17:48:37.275 ThaliTest[2417:6196681] jxcore: disconnect
,2016-01-21 17:48:37.275 ThaliTest[2417:6196681] client session: disconnectFromPeer: 1453394913286.1784.d06l1w==
,2016-01-21 17:48:37.276 ThaliTest[2417:6196681] client session: disconnect
,2016-01-21 17:48:37.276 ThaliTest[2417:6196681] client session: stateChange:2->0 1453394913286.1784.d06l1w==
,2016-01-21 17:48:37.337 ThaliTest[2417:6196681] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-21 17:48:37.392 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:48:37.392 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:37.392 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:48:37.393 ThaliTest[2417:6196681] server session: disconnect
,2016-01-21 17:48:37.395 ThaliTest[2417:6196681] server session: stateChange:2->0 1453394913286.1784
,2016-01-21 17:48:37.691 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-21 17:48:38.444 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:38.447 ThaliTest[2417:6196681] server: starting 1453394918444.2417.sYcs3Q==
2016-01-21 17:48:38.447 ThaliTest[2417:6196681] multipeer session: start timer: 0x16b97080
2016-01-21 17:48:38.447 ThaliTest[2417:6196681] THEMultipeerSession in,itialized peer 1453394918444.2417
2016-01-21 17:48:38.447 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-21 17:48:39.583 ThaliTest[2417:6196526] client: found peer: 1453394918547.1784.a8jYwA==
2016-01-21 17:48:39.584 ThaliTest[2417:6196681] jxcore: connect 1453394918547.1784.a8jYwA==
2016-01-21 17:48:39.584 ThaliTest[2417:6196681] client session: co,nnect
2016-01-21 17:48:39.584 ThaliTest[2417:6196681] client session: stateChange:0->1 1453394918547.1784.a8jYwA==
,2016-01-21 17:48:39.752 ThaliTest[2417:6196526] multipeer session: reset timer
2016-01-21 17:48:39.752 ThaliTest[2417:6196526] multipeer session: stop timer
2016-01-21 17:48:39.753 ThaliTest[2417:6196526] multipeer session: start timer: 0x16b97080
2016-01-21 17:48:39.753 ThaliTest[2417:6196526] server session: connect
2016-01-21 17:48:39.753 ThaliTest[2417:6196526] server session: stateChange:0->1 1453394918547.1784
,2016-01-21 17:48:39.758 ThaliTest[2417:6196526] server: accepting invitation 1453394918547.1784
,2016-01-21 17:48:42.050 ThaliTest[2417:6197356] client session: connected
2016-01-21 17:48:42.050 ThaliTest[2417:6197356] client session: stateChange:1->2 1453394918547.1784.a8jYwA==
,2016-01-21 17:48:42.117 ThaliTest[2417:6197358] client session: fireConnectCallback: 1453394918547.1784.a8jYwA==
2016-01-21 17:48:42.117 ThaliTest[2417:6197358] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should b,e within range

2016-01-21 17:48:42.119 ThaliTest[2417:6196681] jxcore: disconnect
2016-01-21 17:48:42.119 ThaliTest[2417:6196681] client session: disconnectFromPeer: 1453394918547.1784.a8jYwA==
2016-01-21 17:48:42.119 ThaliTest[2417:6196681] client session: disconnect
,2016-01-21 17:48:42.119 ThaliTest[2417:6196681] client session: stateChange:2->0 1453394918547.1784.a8jYwA==
,2016-01-21 17:48:42.132 ThaliTest[2417:6196681] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-01-21 17:48:42.133 ThaliTest[2417:6196681] jxcore: disconnect
,2016-01-21 17:48:42.135 ThaliTest[2417:6196681] jxcore: disconnect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-21 17:48:42.238 ThaliTest[2417:6197356] server session: connected
2016-01-21 17:48:42.238 ThaliTest[2417:6197356] server session: stateChange:1->2 1453394918547.1784
,2016-01-21 17:48:42.249 ThaliTest[2417:6196526] server relay: socket disconnected
2016-01-21 17:48:42.249 ThaliTest[2417:6196526] server relay: 0x16b91cb0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-21 17:48:42.298 ThaliTest[2417:6197356] server session: not connected 1453394918547.1784
,calling stopBroadcasting

,2016-01-21 17:48:43.110 ThaliTest[2417:6196681] jxcore: stopBroadcasting
2016-01-21 17:48:43.111 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
2016-01-21 17:48:43.111 ThaliTest[2417:6196681] multipeer session: stop timer
2016-01-21 17:48:43.,111 ThaliTest[2417:6196681] server session: disconnect
2016-01-21 17:48:43.111 ThaliTest[2417:6196681] server session: stateChange:2->0 1453394918547.1784
2016-01-21 17:48:43.112 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 63169

,2016-01-21 17:48:43.777 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:43.779 ThaliTest[2417:6196681] server: starting 1453394923776.2417.xwn/7Q==
,2016-01-21 17:48:43.781 ThaliTest[2417:6196681] multipeer session: start timer: 0x16b84660
,2016-01-21 17:48:43.785 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394923776.2417
,2016-01-21 17:48:43.786 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-01-21 17:48:44.935 ThaliTest[2417:6196526] multipeer session: reset timer
2016-01-21 17:48:44.935 ThaliTest[2417:6196526] multipeer session: stop timer
2016-01-21 17:48:44.936 ThaliTest[2417:6196526] multipeer session: start timer: 0x16b84660
2016-,01-21 17:48:44.936 ThaliTest[2417:6196526] server session: connect
2016-01-21 17:48:44.936 ThaliTest[2417:6196526] server session: stateChange:0->1 1453394924736.1784
,2016-01-21 17:48:44.941 ThaliTest[2417:6196526] server: accepting invitation 1453394924736.1784
,2016-01-21 17:48:45.663 ThaliTest[2417:6196526] client: found peer: 1453394924736.1784.egjnUA==
2016-01-21 17:48:45.664 ThaliTest[2417:6196681] jxcore: connect 1453394924736.1784.egjnUA==
2016-01-21 17:48:45.664 ThaliTest[2417:6196681] client session: connect
2016-01-21 17:48:45.664 ThaliTest[2417:6196681] client session: stateChange:0->1 1453394924736.1784.egjnUA==
,2016-01-21 17:48:47.491 ThaliTest[2417:6197356] server session: connected
2016-01-21 17:48:47.491 ThaliTest[2417:6197356] server session: stateChange:1->2 1453394924736.1784
,2016-01-21 17:48:47.517 ThaliTest[2417:6196526] server relay: connected (to port: 63169)
,2016-01-21 17:48:47.940 ThaliTest[2417:6197381] server session: not connected 1453394924736.1784
,2016-01-21 17:48:48.471 ThaliTest[2417:6197381] client session: connected
2016-01-21 17:48:48.472 ThaliTest[2417:6197381] client session: stateChange:1->2 1453394924736.1784.egjnUA==
,2016-01-21 17:48:48.542 ThaliTest[2417:6197360] client session: fireConnectCallback: 1453394924736.1784.egjnUA==
2016-01-21 17:48:48.542 ThaliTest[2417:6197360] jxcore: connect: success
ok 98 Should be able to connect without error

ok 99 Port should b,e within range

2016-01-21 17:48:48.546 ThaliTest[2417:6196526] client: relay established
2016-01-21 17:48:48.546 ThaliTest[2417:6196526] client: new accepted socket: 0x16b6fdb0
,data in 2190

,data in 9855

,data in 26280

,data in 44895

,data in 50370

,data in 64605

,data in 82125

,data in 84315

,data in 88695

,data in 89790

,data in 99645
,
,data in 120450

,data in 128115

,data in 131072

,ok 100 the test messages should be equal

,2016-01-21 17:48:48.954 ThaliTest[2417:6196681] jxcore: disconnect
2016-01-21 17:48:48.954 ThaliTest[2417:6196681] client session: disconnectFromPeer: 1453394924736.1784.egjnUA==
2016-01-21 17:48:48.954 ThaliTest[2417:6196681] client session: disconnect,
2016-01-21 17:48:48.955 ThaliTest[2417:6196681] client session: stateChange:2->0 1453394924736.1784.egjnUA==
,2016-01-21 17:48:48.961 ThaliTest[2417:6196681] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-21 17:48:49.975 ThaliTest[2417:6196681] jxcore: stopBroadcasting
2016-01-21 17:48:49.976 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
2016-01-21 17:48:49.976 ThaliTest[2417:6196681] multipeer session: stop, timer
2016-01-21 17:48:49.976 ThaliTest[2417:6196681] server session: disconnect
2016-01-21 17:48:49.976 ThaliTest[2417:6196681] server session: stateChange:2->0 1453394924736.1784
,2016-01-21 17:48:49.983 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 63175

2016-01-21 17:48:50.396 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:50.399 ThaliTest[2417:6196681] server: starting 1453394930396.2417.fmxBLA==
2016-01-21 17:48:50.399 ThaliTest[2417:6196681] multipeer session: start timer: 0x1698be40
2016-01-21 17:48:50.399 ThaliTest[2417:6196681] THEMultipeerSession initialized peer 1453394930396.2417
,2016-01-21 17:48:50.402 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-21 17:48:51.730 ThaliTest[2417:6196526] client: found peer: 1453394930482.1784.TAWkpA==
[{"peerIdentifier":"1453394930482.1784.TAWkpA==","peerName":"(null)","peerAvailable":true}]

2016-01-21 17:48:51.732 ThaliTest[2417:6196681] jxcore: connect 1453394930482.1784.TAWkpA==
2016-01-21 17:48:51.732 ThaliTest[2417:6196681] client session: connect
2016-01-21 17:48:51.732 ThaliTest[2417:6196681] client session: stateChange:0->1 1453394930482.1784.TAWkpA==
,2016-01-21 17:48:51.772 ThaliTest[2417:6196526] multipeer session: reset timer
2016-01-21 17:48:51.772 ThaliTest[2417:6196526] multipeer session: stop timer
2016-01-21 17:48:51.772 ThaliTest[2417:6196526] multipeer session: start timer: 0x1698be40
2016-01-21 17:48:51.772 ThaliTest[2417:6196526] server session: connect
2016-01-21 17:48:51.772 ThaliTest[2417:6196526] server session: stateChange:0->1 1453394930482.1784
2016-01-21 17:48:51.778 ThaliTest[2417:6196526] server: accepting invitation 1453394930482.1784
,2016-01-21 17:48:54.502 ThaliTest[2417:6197493] server session: connected
,2016-01-21 17:48:54.502 ThaliTest[2417:6197493] server session: stateChange:1->2 1453394930482.1784
,2016-01-21 17:48:54.555 ThaliTest[2417:6196526] server relay: connected (to port: 63175)
,2016-01-21 17:48:54.564 ThaliTest[2417:6197396] client session: connected
2016-01-21 17:48:54.564 ThaliTest[2417:6197396] client session: stateChange:1->2 1453394930482.1784.TAWkpA==
,2016-01-21 17:48:54.628 ThaliTest[2417:6197356] client session: fireConnectCallback: 1453394930482.1784.TAWkpA==
2016-01-21 17:48:54.628 ThaliTest[2417:6197356] jxcore: connect: success
ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-01-21 17:48:54.642 ThaliTest[2417:6196526] client: relay established
2016-01-21 17:48:54.642 ThaliTest[2417:6196526] client: new accepted socket: 0x1698a600
,2016-01-21 17:48:54.692 ThaliTest[2417:6197396] server session: not connected 1453394930482.1784
,ok 106 the test messages should be equal

ok 107 First send should succeed

,2016-01-21 17:48:54.781 ThaliTest[2417:6196526] client: socket closed
2016-01-21 17:48:54.781 ThaliTest[2417:6196526] client relay: socket disconnected
2016-01-21 17:48:54.781 ThaliTest[2417:6196526] client relay: 0x1698a600 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-21 17:48:54.781 ThaliTest[2417:6196526] client session: socket closed: 1453394930482.1784.TAWkpA==
2016-01-21 ,17:48:54.781 ThaliTest[2417:6196526] client session: onLinkFailure: 1453394930482.1784.TAWkpA==
2016-01-21 17:48:54.782 ThaliTest[2417:6196526] client session: disconnect
2016-01-21 17:48:54.782 ThaliTest[2417:6196526] client session: stateChange:2->0 14,53394930482.1784.TAWkpA==
,2016-01-21 17:48:54.787 ThaliTest[2417:6196526] client session: fireConnectionErrorEvent: 1453394930482.1784.TAWkpA==
,2016-01-21 17:48:54.790 ThaliTest[2417:6196681] jxcore: connect 1453394930482.1784.TAWkpA==
2016-01-21 17:48:54.792 ThaliTest[2417:6196681] client session: connect
,2016-01-21 17:48:54.792 ThaliTest[2417:6196681] client session: stateChange:0->1 1453394930482.1784.TAWkpA==
,2016-01-21 17:48:54.887 ThaliTest[2417:6196526] multipeer session: reset timer
2016-01-21 17:48:54.887 ThaliTest[2417:6196526] multipeer session: stop timer
2016-01-21 17:48:54.888 ThaliTest[2417:6196526] multipeer session: start timer: 0x1698be40
2016-,01-21 17:48:54.888 ThaliTest[2417:6196526] server: disconnecting to refresh session (1453394930482.1784)
2016-01-21 17:48:54.888 ThaliTest[2417:6196526] server session: disconnect
2016-01-21 17:48:54.888 ThaliTest[2417:6196526] server session: stateChange:2->0 1453394930482.1784
,2016-01-21 17:48:54.890 ThaliTest[2417:6196526] server session: connect
2016-01-21 17:48:54.890 ThaliTest[2417:6196526] server session: stateChange:0->1 1453394930482.1784
,2016-01-21 17:48:54.896 ThaliTest[2417:6196526] server: accepting invitation 1453394930482.1784
,2016-01-21 17:48:57.543 ThaliTest[2417:6197360] server session: connected
,2016-01-21 17:48:57.543 ThaliTest[2417:6197360] server session: stateChange:1->2 1453394930482.1784
,2016-01-21 17:48:57.605 ThaliTest[2417:6197358] client session: connected
2016-01-21 17:48:57.605 ThaliTest[2417:6197358] client session: stateChange:1->2 1453394930482.1784.TAWkpA==
,2016-01-21 17:48:57.635 ThaliTest[2417:6196526] server relay: connected (to port: 63175)
,2016-01-21 17:48:57.735 ThaliTest[2417:6197356] client session: fireConnectCallback: 1453394930482.1784.TAWkpA==
2016-01-21 17:48:57.735 ThaliTest[2417:6197356] jxcore: connect: success
ok 108 Should be able to connect without error

ok 109 Port should be within range

ok 110 Second connect should succeed

,2016-01-21 17:48:57.750 ThaliTest[2417:6196526] client: relay established
2016-01-21 17:48:57.750 ThaliTest[2417:6196526] client: new accepted socket: 0x169dc610
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-01-21 17:48:57.814 ThaliTest[2417:6196526] client: socket closed
2016-01-21 17:48:57.814 ThaliTest[2417:6196526] client relay: socket disconnected
2016-01-21 17:48:57.815 ThaliTest[2417:6196526] client relay: 0x169dc610 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-21 17:48:57.815 ThaliTest[2417:6196526] client session: socket closed: 1453394930482.1784.TAWkpA==
2016-01-21 ,17:48:57.815 ThaliTest[2417:6196526] client session: onLinkFailure: 1453394930482.1784.TAWkpA==
2016-01-21 17:48:57.815 ThaliTest[2417:6196526] client session: disconnect
2016-01-21 17:48:57.815 ThaliTest[2417:6196526] client session: stateChange:2->0 1453394930482.1784.TAWkpA==
,2016-01-21 17:48:57.820 ThaliTest[2417:6196526] client session: fireConnectionErrorEvent: 1453394930482.1784.TAWkpA==
,2016-01-21 17:48:57.833 ThaliTest[2417:6197396] server session: not connected 1453394930482.1784
,calling stopBroadcasting

,2016-01-21 17:48:57.847 ThaliTest[2417:6196681] jxcore: stopBroadcasting
2016-01-21 17:48:57.847 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
2016-01-21 17:48:57.847 ThaliTest[2417:6196681] multipeer session: stop timer
2016-01-21 17:48:57.,847 ThaliTest[2417:6196681] server session: disconnect
2016-01-21 17:48:57.847 ThaliTest[2417:6196681] server session: stateChange:2->0 1453394930482.1784
,2016-01-21 17:48:57.850 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/AA07B46B-AE3B-4729-BF8A-9D973EA39741/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-21 17:48:58.481 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:58.484 ThaliTest[2417:6196681] server: starting -FhetZcCv7KJMzbq9EHhmw.T2YE1w==
2016-01-21 17:48:58.484 ThaliTest[2417:6196681] multipeer session: start timer: 0x169dc700
2016-01-21 17:48:58.484 ThaliTest[2417:6196681] THEMultipeerSessio,n initialized peer -FhetZcCv7KJMzbq9EHhmw
2016-01-21 17:48:58.484 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event sh,ould occur in right order

About to call stopBroadcasting

2016-01-21 17:48:58.486 ThaliTest[2417:6196681] jxcore: stopBroadcasting
2016-01-21 17:48:58.486 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:58.486 ThaliTest[2417:6196681] multipeer session: stop timer
2016-01-21 17:48:58.491 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in ,right order

mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/AA07B46B-AE3B-4729-BF8A-9D973EA39741/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-21 17:48:59.456 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:48:59.458 ThaliTest[2417:6196681] server: starting -FhetZcCv7KJMzbq9EHhmw.J37Wlg==
2016-01-21 17:48:59.459 ThaliTest[2417:6196681] multipeer session: start timer: 0x16b4d8b0
2016-01-21 17:48:59.459 ThaliTest[2417:6196681] THEMultipeerSessio,n initialized peer -FhetZcCv7KJMzbq9EHhmw
2016-01-21 17:48:59.459 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-01-21 17:48:59.461 ThaliTest[2417:6196681] jxcore: stopBroadcasting
2016-01-21 17:48:59.461 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:48:59.461 ThaliTest[2417:6196681] multipeer session: stop timer
2016-01-21 17:48:59.466 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/AA07B46B-AE3B-4729-BF8A-9D973EA39741/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-21 17:49:02.775 ThaliTest[2417:6196681] jxcore: startBroadcasting
,2016-01-21 17:49:02.778 ThaliTest[2417:6196681] server: starting -FhetZcCv7KJMzbq9EHhmw.QS6PJw==
,2016-01-21 17:49:02.778 ThaliTest[2417:6196681] multipeer session: start timer: 0x15a9f630
,2016-01-21 17:49:02.783 ThaliTest[2417:6196681] THEMultipeerSession initialized peer -FhetZcCv7KJMzbq9EHhmw
,2016-01-21 17:49:02.785 ThaliTest[2417:6196681] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error
,
,ok 120 deviceName should not be null
,
,2016-01-21 17:49:05.462 ThaliTest[2417:6196526] client: found peer: 7CmZmRa2LOtPuthCwLFqow.X62ZIQ==
,2016-01-21 17:49:08.419 ThaliTest[2417:6196681] jxcore: connect 7CmZmRa2LOtPuthCwLFqow.X62ZIQ==
,2016-01-21 17:49:08.420 ThaliTest[2417:6196681] client session: connect
,2016-01-21 17:49:08.421 ThaliTest[2417:6196681] client session: stateChange:0->1 7CmZmRa2LOtPuthCwLFqow.X62ZIQ==
,ok 121 Should be able to put doc without error
,
,ok 122 1st change of local doc should contain local id
,
,2016-01-21 17:49:14.803 ThaliTest[2417:6196526] multipeer session: reset timer
2016-01-21 17:49:14.803 ThaliTest[2417:6196526] multipeer session: stop timer
2016-01-21 17:49:14.803 ThaliTest[2417:6196526] multipeer session: start timer: 0x15a9f630
2016-,01-21 17:49:14.803 ThaliTest[2417:6196526] server session: connect
2016-01-21 17:49:14.804 ThaliTest[2417:6196526] server session: stateChange:0->1 7CmZmRa2LOtPuthCwLFqow
2016-01-21 17:49:14.809 ThaliTest[2417:6196526] server: accepting invitation 7CmZmRa2LOtPuthCwLFqow
,2016-01-21 17:49:17.430 ThaliTest[2417:6197356] client session: connected
2016-01-21 17:49:17.430 ThaliTest[2417:6197356] client session: stateChange:1->2 7CmZmRa2LOtPuthCwLFqow.X62ZIQ==
,2016-01-21 17:49:17.433 ThaliTest[2417:6197557] server session: connected
,2016-01-21 17:49:17.433 ThaliTest[2417:6197557] server session: stateChange:1->2 7CmZmRa2LOtPuthCwLFqow
,2016-01-21 17:49:17.454 ThaliTest[2417:6197557] client session: fireConnectCallback: 7CmZmRa2LOtPuthCwLFqow.X62ZIQ==
,2016-01-21 17:49:17.455 ThaliTest[2417:6197557] jxcore: connect: success
,2016-01-21 17:49:17.461 ThaliTest[2417:6196526] client: relay established
,2016-01-21 17:49:17.463 ThaliTest[2417:6196526] client: new accepted socket: 0x16990b90
,2016-01-21 17:49:17.464 ThaliTest[2417:6196526] server relay: connected (to port: 63190)
,server bridge: new client socket

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

client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,Possibly unhandled Error. ETIMEDOUT
onError@/private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:66:18
ajax/<@/private/var/mobile/Containers/Bundle/Applicati,on/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:108:1
Request.prototype.init/self.callback@/private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxco,re/node_modules/pouchdb/node_modules/request/request.js:123:7
emit@events.js:82:1
Request.prototype.start/self.timeoutTimer<@/private/var/mobile/Containers/Bundle/Application/66E5AA20-7B32-4170-84AF-E1413AB34363/ThaliTest.app/www/jxcore/node_modules/pouc,hdb/node_modules/request/request.js:590:7
$9@timers.js:120:1


,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: socket closed

,client bridge: new client socket

,ok 123 1st change of remote doc should contain remote id

,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: 'b780bc55-4212-4571-9385-b354955eeb0c',
  rev: '2-6b3aea41727e2e971257addb189f9614' }

,client bridge: new client socket

,ok 125 Remote changes occur in strict order

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

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
client bridge: socket closed

,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

,2016-01-21 17:49:40.774 ThaliTest[2417:6196681] jxcore: stopBroadcasting
,2016-01-21 17:49:40.775 ThaliTest[2417:6196681] THEMultipeerSession stopping peer
,2016-01-21 17:49:40.776 ThaliTest[2417:6196681] multipeer session: stop timer
,2016-01-21 17:49:40.776 ThaliTest[2417:6196681] client session: disconnect
,2016-01-21 17:49:40.780 ThaliTest[2417:6196681] client session: stateChange:2->0 7CmZmRa2LOtPuthCwLFqow.X62ZIQ==
,2016-01-21 17:49:40.808 ThaliTest[2417:6197356] server session: not connected 7CmZmRa2LOtPuthCwLFqow
,2016-01-21 17:49:40.853 ThaliTest[2417:6196681] server session: disconnect
,2016-01-21 17:49:40.853 ThaliTest[2417:6196681] server session: stateChange:2->0 7CmZmRa2LOtPuthCwLFqow
,2016-01-21 17:49:40.857 ThaliTest[2417:6196681] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,Error in mux client bridge Error: write EPIPE

,mux server bridge listener closed

,syncRetry called when not started

client bridge: socket closed
,
,server bridge: socket closed

,# teardown

,ok 128 should be equal

,# setup

,# #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

,# teardown

,client bridge: socket closed

,client bridge: socket closed


```
