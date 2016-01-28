#### Test 573480789efee08_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/75AF4F9A-6704-4C98-B80F-353C90E3F3BD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/75AF4F9A-6704-4C98-B80F-353C90E3F3BD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FDE3E7F4-ACD6-4C2D-A13E-57C8C487038F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62128"
,(lldb)     command script import "/tmp/75AF4F9A-6704-4C98-B80F-353C90E3F3BD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-28 12:45:19.041 ThaliTest[644:1119968] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2A88C4CD-0AA0-47BD-843F-61EAE8882302/Library/Cookies/Cookies.binarycookies
,2016-01-28 12:45:19.525 ThaliTest[644:1119968] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-28 12:45:19.526 ThaliTest[644:1119968] Multi-tasking -> Device: YES, App: YES
,2016-01-28 12:45:19.535 ThaliTest[644:1119968] Unlimited access to network resources
,2016-01-28 12:45:19.549 ThaliTest[644:1119968] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-28 12:45:29.795 ThaliTest[644:1119968] Resetting plugins due to page load.
,2016-01-28 12:45:33.565 ThaliTest[644:1119968] Finished load of: file:///var/mobile/Containers/Bundle/Application/FDE3E7F4-ACD6-4C2D-A13E-57C8C487038F/ThaliTest.app/www/index.html
,2016-01-28 12:45:33.751 ThaliTest[644:1119968] JXcore Cordova plugin initializing
2016-01-28 12:45:33.752 ThaliTest[644:1120405] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FDE3E7F4-ACD6-4C2D-A13E-57C8C487038F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FDE3E7F4-ACD6-4C2D-A13E-57C8C487038F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FDE3E7F4-ACD6-4C2D-A13E-57C8C487038F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FDE3E7F4-ACD6-4C2D-A13E-57C8C487038F/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FDE3E7F4-ACD6-4C2D-A13E-57C8C487038F/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FDE3E7F4-ACD6-4C2D-A13E-57C8C487038F/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FDE3E7F4-ACD6-4C2D-A13E-57C8C487038F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FDE3E7F4-ACD6-4C2D-A13E-57C8C487038F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,appEnteringBackground wasn't registered

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

,ok 6 secondPromise result

,ok 7 secondPromise testValue

,ok 8 thirdPromise in promise

,ok 9 thirdPromise result

,ok 10 thirdPromise testValue

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

,ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

,ok 39 should be equal

,ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

,ok 42 should be equal

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

,ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-28 12:49:59.775 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:49:59.791 ThaliTest[644:1120405] server: starting 1453981799774.644.loLXyA==
,2016-01-28 12:49:59.792 ThaliTest[644:1120405] multipeer session: start timer: 0x1a77e8b0
,2016-01-28 12:49:59.794 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981799774.644
,2016-01-28 12:49:59.795 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

2016-01-28 12:49:59.799 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:49:59.799 ThaliTest[64,4:1120405] THEMultipeerSession stopping peer
2016-01-28 12:49:59.799 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:49:59.800 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,ok 55 Should be able to call stopBroadcasting without error

2016-01-28 12:49:59.803 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:49:59.813 ThaliTest[644:1120405] server: starting 1453981799803.644.G86TDA==
2016-01-28 12:49:59.814 ThaliTest[644:1120405] multipeer session: start timer: 0x1a7816b0
2016-01-28 12:49:59.815 ThaliTest[644:1120405] THEMultipeerSession initia,lized peer 1453981799803.644
2016-01-28 12:49:59.815 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.819 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:49:59.823 ThaliTest[644:1120405] THEMultipeerSession stopping peer
2016-01-28 12:49:59.823 ThaliTest[644:1120405] multipeer session: stop timer
2016-01-28 12:49:59.824, ThaliTest[644:1120405] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

2016-01-28 12:49:59.826 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:49:59.833 ThaliTest[644:1120405] server: starting 1453981799826.644.m+73Hg==
2016-01-28 12:49:59.834 ThaliTest[644:1120405] multipeer session: start timer: 0x1a372a90
2016-01-28 12:49:59.835 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981799826.644
,2016-01-28 12:49:59.835 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-01-28 12:49:59.841 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:49:59.842 ThaliTest[64,4:1120405] THEMultipeerSession stopping peer
2016-01-28 12:49:59.842 ThaliTest[644:1120405] multipeer session: stop timer
2016-01-28 12:49:59.842 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting with,out error

2016-01-28 12:49:59.845 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:49:59.860 ThaliTest[644:1120405] server: starting 1453981799844.644.QMHfsQ==
,2016-01-28 12:49:59.862 ThaliTest[644:1120405] multipeer session: start timer: 0x1a374a20
,2016-01-28 12:49:59.865 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981799844.644
,2016-01-28 12:49:59.869 ThaliTest[644:1120405] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.874 ThaliTest[644:1120405] jxcore: stopBroadcasting
,2016-01-28 12:49:59.874 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.875 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:49:59.876 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-01-28 12:49:59.882 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:49:59.885 ThaliTest[644:1120405] server: starting 1453981799881.644.wHYJGA==
,2016-01-28 12:49:59.887 ThaliTest[644:1120405] multipeer session: start timer: 0x1a38d290
,2016-01-28 12:49:59.890 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981799881.644
,2016-01-28 12:49:59.892 ThaliTest[644:1120405] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.895 ThaliTest[644:1120405] jxcore: stopBroadcasting
,2016-01-28 12:49:59.896 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.896 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:49:59.897 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-01-28 12:49:59.903 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:49:59.906 ThaliTest[644:1120405] server: starting 1453981799902.644.E0zFVQ==
,2016-01-28 12:49:59.908 ThaliTest[644:1120405] multipeer session: start timer: 0x1a372ba0
,2016-01-28 12:49:59.911 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981799902.644
,2016-01-28 12:49:59.914 ThaliTest[644:1120405] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.917 ThaliTest[644:1120405] jxcore: stopBroadcasting
,2016-01-28 12:49:59.917 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.918 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:49:59.921 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-01-28 12:49:59.925 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:49:59.927 ThaliTest[644:1120405] server: starting 1453981799924.644.mOkdqQ==
,2016-01-28 12:49:59.929 ThaliTest[644:1120405] multipeer session: start timer: 0x1a3736b0
2016-01-28 12:49:59.931 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981799924.644
2016-01-28 12:49:59.932 ThaliTest[644:1120405] jxcore: startBr,oadcasting: success
ok 66 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.933 ThaliTest[644:1120405] jxcore: stopBroadcasting
,2016-01-28 12:49:59.935 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.937 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:49:59.939 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-01-28 12:49:59.945 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:49:59.948 ThaliTest[644:1120405] server: starting 1453981799944.644.H2+SMw==
,2016-01-28 12:49:59.950 ThaliTest[644:1120405] multipeer session: start timer: 0x1a783ca0
,2016-01-28 12:49:59.951 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981799944.644
,2016-01-28 12:49:59.953 ThaliTest[644:1120405] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.958 ThaliTest[644:1120405] jxcore: stopBroadcasting
,2016-01-28 12:49:59.959 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.960 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:49:59.962 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-01-28 12:49:59.966 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:49:59.968 ThaliTest[644:1120405] server: starting 1453981799965.644.vnC2bw==
,2016-01-28 12:49:59.970 ThaliTest[644:1120405] multipeer session: start timer: 0x1a375670
,2016-01-28 12:49:59.973 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981799965.644
,2016-01-28 12:49:59.976 ThaliTest[644:1120405] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.977 ThaliTest[644:1120405] jxcore: stopBroadcasting
,2016-01-28 12:49:59.978 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.978 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:49:59.980 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-01-28 12:49:59.983 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:49:59.986 ThaliTest[644:1120405] server: starting 1453981799983.644.DtAOvQ==
,2016-01-28 12:49:59.986 ThaliTest[644:1120405] multipeer session: start timer: 0x1a374be0
,2016-01-28 12:49:59.988 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981799983.644
,2016-01-28 12:49:59.989 ThaliTest[644:1120405] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error
,
,2016-01-28 12:49:59.993 ThaliTest[644:1120405] jxcore: stopBroadcasting
,2016-01-28 12:49:59.994 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.994 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:49:59.995 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-28 12:50:00.689 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:50:00.692 ThaliTest[644:1120405] server: starting 1453981800689.644.6tYb+Q==
2016-01-28 12:50:00.693 ThaliTest[644:1120405] multipeer session: start timer: 0x1a1c5850
2016-01-28 12:50:00.694 ThaliTest[644:1120405] THEMultipeerSession initia,lized peer 1453981800689.644
2016-01-28 12:50:00.694 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-28 12:50:00.696 ThaliTest[644:1120405] jxcore: startBroadcasting
2016-,01-28 12:50:00.696 ThaliTest[644:1120405] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-01-28 12:50:00.701 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:50:00.703 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:50:00.703 ThaliTest[644:1120405] multipeer session: stop timer
2016-01-28 12:50:00.707 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-28 12:50:01.816 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:50:01.820 ThaliTest[644:1120405] server: starting 1453981801815.644.Ko8ngw==
2016-01-28 12:50:01.820 ThaliTest[644:1120405] multipeer session: start timer: 0x1a1d8890
2016-01-28 12:50:01.821 ThaliTest[644:1120405] THEMultipeerSession initia,lized peer 1453981801815.644
2016-01-28 12:50:01.821 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-28 12:50:01.823 ThaliTest[644:1120405] jxcore: connect foobar
2016-01-,28 12:50:01.823 ThaliTest[644:1120405] client: unknown peer foobar
2016-01-28 12:50:01.824 ThaliTest[644:1120405] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

,2016-01-28 12:50:01.828 ThaliTest[644:1120405] jxcore: stopBroadcasting
,2016-01-28 12:50:01.829 ThaliTest[644:1120405] THEMultipeerSession stopping peer
2016-01-28 12:50:01.830 ThaliTest[644:1120405] multipeer session: stop timer
2016-01-28 12:50:01.831 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-28 12:50:02.797 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:50:02.801 ThaliTest[644:1120405] server: starting 1453981802797.644.epZtvQ==
2016-01-28 12:50:02.801 ThaliTest[644:1120405] multipeer session: start timer: 0x1970a6e0
2016-01-28 12:50:02.802 ThaliTest[644:1120405] THEMultipeerSession initia,lized peer 1453981802797.644
2016-01-28 12:50:02.802 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-28 12:50:02.804 ThaliTest[644:1120405] jxcore: disconnect
2016-01-28 1,2:50:02.805 ThaliTest[644:1120405] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-01-28 12:50:02.811 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:50:02.811 ThaliTest[644:1120405] THEMultipeerSession stopping peer
2016-01-28 12:50:02.811 ThaliTest[644:1120405] multipeer session: stop timer
2016-01-28 12:50:02.812 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-28 12:50:03.779 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:50:03.783 ThaliTest[644:1120405] server: starting 1453981803779.644.6MjRTg==
2016-01-28 12:50:03.784 ThaliTest[644:1120405] multipeer session: start timer: 0x1917fc00
2016-01-28 12:50:03.784 ThaliTest[644:1120405] THEMultipeerSession initia,lized peer 1453981803779.644
2016-01-28 12:50:03.785 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-28 12:50:05.098 ThaliTest[644:1119968] client: found peer: 1453981803751.2048.U+sK7A==
,2016-01-28 12:50:05.102 ThaliTest[644:1120405] jxcore: connect 1453981803751.2048.U+sK7A==
2016-01-28 12:50:05.102 ThaliTest[644:1120405] client session: connect
2016-01-28 12:50:05.103 ThaliTest[644:1120405] client session: stateChange:0->1 1453981803751.2048.U+sK7A==
,2016-01-28 12:50:05.305 ThaliTest[644:1119968] multipeer session: reset timer
2016-01-28 12:50:05.305 ThaliTest[644:1119968] multipeer session: stop timer
2016-01-28 12:50:05.306 ThaliTest[644:1119968] multipeer session: start timer: 0x1917fc00
2016-01-,28 12:50:05.306 ThaliTest[644:1119968] server session: connect
2016-01-28 12:50:05.308 ThaliTest[644:1119968] server session: stateChange:0->1 1453981803751.2048
,2016-01-28 12:50:05.316 ThaliTest[644:1119968] server: accepting invitation 1453981803751.2048
,2016-01-28 12:50:07.782 ThaliTest[644:1120969] client session: connected
2016-01-28 12:50:07.782 ThaliTest[644:1120969] client session: stateChange:1->2 1453981803751.2048.U+sK7A==
,2016-01-28 12:50:07.789 ThaliTest[644:1120967] client session: fireConnectCallback: 1453981803751.2048.U+sK7A==
2016-01-28 12:50:07.790 ThaliTest[644:1120967] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-01-28 12:50:07.795 ThaliTest[644:1120405] jxcore: disconnect
,2016-01-28 12:50:07.795 ThaliTest[644:1120405] client session: disconnectFromPeer: 1453981803751.2048.U+sK7A==
,2016-01-28 12:50:07.796 ThaliTest[644:1120405] client session: disconnect
,2016-01-28 12:50:07.796 ThaliTest[644:1120405] client session: stateChange:2->0 1453981803751.2048.U+sK7A==
,2016-01-28 12:50:07.875 ThaliTest[644:1120405] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-28 12:50:08.182 ThaliTest[644:1120973] server session: connected
2016-01-28 12:50:08.182 ThaliTest[644:1120973] server session: stateChange:1->2 1453981803751.2048
,2016-01-28 12:50:08.188 ThaliTest[644:1119968] server relay: socket disconnected
2016-01-28 12:50:08.188 ThaliTest[644:1119968] server relay: 0x17eb8920 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocal,izedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-28 12:50:08.244 ThaliTest[644:1120972] server session: not connected 1453981803751.2048
,calling stopBroadcasting

,2016-01-28 12:50:08.587 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:50:08.588 ThaliTest[644:1120405] THEMultipeerSession stopping peer
2016-01-28 12:50:08.588 ThaliTest[644:1120405] multipeer session: stop timer
2016-01-28 12:50:08.589, ThaliTest[644:1120405] server session: disconnect
2016-01-28 12:50:08.589 ThaliTest[644:1120405] server session: stateChange:2->0 1453981803751.2048
2016-01-28 12:50:08.590 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-28 12:50:09.100 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:50:09.104 ThaliTest[644:1120405] server: starting 1453981809100.644.hpMmFQ==
2016-01-28 12:50:09.105 ThaliTest[644:1120405] multipeer session: start timer: 0x17ebf870
2016-01-28 12:50:09.105 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981809100.644
2016-01-28 12:50:09.106 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-28 12:50:10.267 ThaliTest[644:1119968] client: found peer: 1453981809111.2048.Ixzgqw==
2016-01-28 12:50:10.269 ThaliTest[644:1120405] jxcore: connect 1453981809111.2048.Ixzgqw==
2016-01-28 12:50:10.269 ThaliTest[644:1120405] client session: connect
2016-01-28 12:50:10.270 ThaliTest[644:1120405] client session: stateChange:0->1 1453981809111.2048.Ixzgqw==
,2016-01-28 12:50:10.417 ThaliTest[644:1119968] multipeer session: reset timer
2016-01-28 12:50:10.418 ThaliTest[644:1119968] multipeer session: stop timer
2016-01-28 12:50:10.418 ThaliTest[644:1119968] multipeer session: start timer: 0x17ebf870
2016-01-,28 12:50:10.418 ThaliTest[644:1119968] server session: connect
2016-01-28 12:50:10.420 ThaliTest[644:1119968] server session: stateChange:0->1 1453981809111.2048
,2016-01-28 12:50:10.429 ThaliTest[644:1119968] server: accepting invitation 1453981809111.2048
,2016-01-28 12:50:13.029 ThaliTest[644:1120972] server session: connected
2016-01-28 12:50:13.030 ThaliTest[644:1120972] server session: stateChange:1->2 1453981809111.2048
2016-01-28 12:50:13.033 ThaliTest[644:1119968] server relay: socket disconnected
,2016-01-28 12:50:13.033 ThaliTest[644:1119968] server relay: 0x19567530 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-28 12:50:13.094 ThaliTest[644:1120969] server session: not connected 1453981809111.2048
,2016-01-28 12:50:13.495 ThaliTest[644:1120967] client session: connected
2016-01-28 12:50:13.497 ThaliTest[644:1120967] client session: stateChange:1->2 1453981809111.2048.Ixzgqw==
,2016-01-28 12:50:13.501 ThaliTest[644:1120967] client session: fireConnectCallback: 1453981809111.2048.Ixzgqw==
2016-01-28 12:50:13.501 ThaliTest[644:1120967] jxcore: connect: success
ok 88 Should be able to connect without error

ok 89 Port should be ,within range

2016-01-28 12:50:13.505 ThaliTest[644:1120405] jxcore: connect 1453981809111.2048.Ixzgqw==
2016-01-28 12:50:13.505 ThaliTest[644:1120405] client: already connect(ing/ed) to 1453981809111.2048.Ixzgqw==
2016-01-28 12:50:13.505 ThaliTest[644:1120405] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-01-28 12:50:13.510 ThaliTest[644:1120405] jxcore: disconnect
2016-01-28 12:50:13.510 ThaliTest[644:1120405] client session: disconnectFromPeer: 1453981809111.2048.Ixzgqw==
2016-01-28 12:50:13.511 ThaliTest[644:1120405] client session: disconnect
2016-01-28 12:50:13.511 ThaliTest[644:1120405] client session: stateChange:2->0 1453981809111.2048.Ixzgqw==
,2016-01-28 12:50:13.588 ThaliTest[644:1120405] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-28 12:50:13.847 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:50:13.847 ThaliTest[644:1120405] THEMultipeerSession stopping peer
2016-01-28 12:50:13.847 ThaliTest[644:1120405] multipeer session: stop timer
2016-01-28 12:50:13.848, ThaliTest[644:1120405] server session: disconnect
2016-01-28 12:50:13.848 ThaliTest[644:1120405] server session: stateChange:2->0 1453981809111.2048
2016-01-28 12:50:13.849 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-28 12:50:14.342 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:50:14.346 ThaliTest[644:1120405] server: starting 1453981814342.644.otjf6Q==
2016-01-28 12:50:14.347 ThaliTest[644:1120405] multipeer session: start timer: 0x19187860
2016-01-28 12:50:14.348 ThaliTest[644:1120405] THEMultipeerSession initia,lized peer 1453981814342.644
2016-01-28 12:50:14.348 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-28 12:50:15.588 ThaliTest[644:1119968] client: found peer: 1453981814349.2048.VHQOnA==
2016-01-28 12:50:15.589 ThaliTest[644:1120405] jxcore: connect 1453981814349.2048.VHQOnA==
2016-01-28 12:50:15.590 ThaliTest[644:1120405] client session: conne,ct
2016-01-28 12:50:15.590 ThaliTest[644:1120405] client session: stateChange:0->1 1453981814349.2048.VHQOnA==
,2016-01-28 12:50:15.647 ThaliTest[644:1119968] multipeer session: reset timer
2016-01-28 12:50:15.647 ThaliTest[644:1119968] multipeer session: stop timer
2016-01-28 12:50:15.647 ThaliTest[644:1119968] multipeer session: start timer: 0x19187860
2016-01-,28 12:50:15.648 ThaliTest[644:1119968] server session: connect
2016-01-28 12:50:15.648 ThaliTest[644:1119968] server session: stateChange:0->1 1453981814349.2048
,2016-01-28 12:50:15.659 ThaliTest[644:1119968] server: accepting invitation 1453981814349.2048
,2016-01-28 12:50:18.269 ThaliTest[644:1120973] server session: connected
2016-01-28 12:50:18.270 ThaliTest[644:1120973] server session: stateChange:1->2 1453981814349.2048
,2016-01-28 12:50:18.283 ThaliTest[644:1119968] server relay: socket disconnected
2016-01-28 12:50:18.284 ThaliTest[644:1119968] server relay: 0x192c3b70 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-28 12:50:18.306 ThaliTest[644:1120969] server session: not connected 1453981814349.2048
,2016-01-28 12:50:18.450 ThaliTest[644:1120967] client session: connected
2016-01-28 12:50:18.450 ThaliTest[644:1120967] client session: stateChange:1->2 1453981814349.2048.VHQOnA==
,2016-01-28 12:50:18.466 ThaliTest[644:1120973] client session: fireConnectCallback: 1453981814349.2048.VHQOnA==
2016-01-28 12:50:18.466 ThaliTest[644:1120973] jxcore: connect: success
,ok 93 Should be able to connect without error

ok 94 Port should be within range

2016-01-28 12:50:18.470 ThaliTest[644:1120405] jxcore: disconnect
,2016-01-28 12:50:18.471 ThaliTest[644:1120405] client session: disconnectFromPeer: 1453981814349.2048.VHQOnA==
2016-01-28 12:50:18.472 ThaliTest[644:1120405] client session: disconnect
2016-01-28 12:50:18.472 ThaliTest[644:1120405] client session: stateChange:2->0 1453981814349.2048.VHQOnA==
,2016-01-28 12:50:18.483 ThaliTest[644:1120405] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-01-28 12:50:18.485 ThaliTest[644:1120405] jxcore: disconnect
2016-01-28 12:50:18.485 ThaliTest[644:1120405] jxcore: disconnect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-28 12:50:18.563 ThaliTest[644:1120405] jxcore: stopBroadcasting
,2016-01-28 12:50:18.564 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:50:18.564 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:50:18.566 ThaliTest[644:1120405] server session: disconnect
,2016-01-28 12:50:18.573 ThaliTest[644:1120405] server session: stateChange:2->0 1453981814349.2048
,2016-01-28 12:50:18.756 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 52197

,2016-01-28 12:50:19.666 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:50:19.667 ThaliTest[644:1120405] server: starting 1453981819665.644.F/or/w==
2016-01-28 12:50:19.667 ThaliTest[644:1120405] multipeer session: start timer: 0x191e58d0
2016-01-28 12:50:19.668 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981819665.644
2016-01-28 12:50:19.668 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-01-28 12:50:21.311 ThaliTest[644:1119968] multipeer session: reset timer
2016-01-28 12:50:21.311 ThaliTest[644:1119968] multipeer session: stop timer
2016-01-28 12:50:21.311 ThaliTest[644:1119968] multipeer session: start timer: 0x191e58d0
2016-01-,28 12:50:21.312 ThaliTest[644:1119968] server session: connect
2016-01-28 12:50:21.312 ThaliTest[644:1119968] server session: stateChange:0->1 1453981820354.2048
,2016-01-28 12:50:21.322 ThaliTest[644:1119968] server: accepting invitation 1453981820354.2048
,2016-01-28 12:50:21.411 ThaliTest[644:1119968] client: found peer: 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:21.413 ThaliTest[644:1120405] jxcore: connect 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:21.413 ThaliTest[644:1120405] client session: connect
2016-01-28 12:50:21.413 ThaliTest[644:1120405] client session: stateChange:0->1 1453981820354.2048.JaM5Ig==
,2016-01-28 12:50:24.114 ThaliTest[644:1120969] server session: connected
2016-01-28 12:50:24.114 ThaliTest[644:1120969] server session: stateChange:1->2 1453981820354.2048
,2016-01-28 12:50:24.163 ThaliTest[644:1119968] server relay: connected (to port: 52197)
,2016-01-28 12:50:24.644 ThaliTest[644:1120972] client session: connected
2016-01-28 12:50:24.645 ThaliTest[644:1120972] client session: stateChange:1->2 1453981820354.2048.JaM5Ig==
,2016-01-28 12:50:24.668 ThaliTest[644:1120972] client session: fireConnectCallback: 1453981820354.2048.JaM5Ig==
,2016-01-28 12:50:24.669 ThaliTest[644:1120972] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-01-28 12:50:24.680 ThaliTest[644:1119968] client: relay established
2016-01-28 12:50:24.680 ThaliTest[644:1119968] client: new accepted socket: 0x1a1d9240
,2016-01-28 12:50:24.840 ThaliTest[644:1120972] server session: not connected 1453981820354.2048
data in 1024

,data in 2190

,data in 22995

,data in 39420

,data in 40515

,data in 41610

,data in 47085

,data in 59130

,data in 70080

,data in 74318

,data in 84315

,data in 94170

,data in 102930

,data in 104025

,data in 117165

,data in 124830

,data in 131072

,ok 100 the test messages should be equal

,2016-01-28 12:50:25.663 ThaliTest[644:1120405] jxcore: disconnect
,2016-01-28 12:50:25.664 ThaliTest[644:1120405] client session: disconnectFromPeer: 1453981820354.2048.JaM5Ig==
,2016-01-28 12:50:25.664 ThaliTest[644:1120405] client session: disconnect
,2016-01-28 12:50:25.665 ThaliTest[644:1120405] client session: stateChange:2->0 1453981820354.2048.JaM5Ig==
,2016-01-28 12:50:25.729 ThaliTest[644:1120405] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-28 12:50:25.882 ThaliTest[644:1120405] jxcore: stopBroadcasting
,2016-01-28 12:50:25.883 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:50:25.884 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:50:25.887 ThaliTest[644:1120405] server session: disconnect
,2016-01-28 12:50:25.897 ThaliTest[644:1120405] server session: stateChange:2->0 1453981820354.2048
,2016-01-28 12:50:25.901 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 52203

,2016-01-28 12:50:26.406 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:50:26.409 ThaliTest[644:1120405] server: starting 1453981826405.644.NvlxHg==
2016-01-28 12:50:26.410 ThaliTest[644:1120405] multipeer session: start timer: 0x17e89330
2016-01-28 12:50:26.410 ThaliTest[644:1120405] THEMultipeerSession initialized peer 1453981826405.644
2016-01-28 12:50:26.411 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-28 12:50:27.006 ThaliTest[644:1119968] client: found peer: 1453981820354.2048.JaM5Ig==
[{"peerIdentifier":"1453981820354.2048.JaM5Ig==","peerName":"(null)","peerAvailable":true}]

2016-01-28 12:50:27.009 ThaliTest[644:1120405] jxcore: connect 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:27.009 ThaliTest[644:1120405] client session: connect
,2016-01-28 12:50:27.010 ThaliTest[644:1120405] client session: stateChange:0->1 1453981820354.2048.JaM5Ig==
,2016-01-28 12:50:27.641 ThaliTest[644:1119968] client: found peer: 1453981826470.2048.JUV1sA==
[{"peerIdentifier":"1453981826470.2048.JUV1sA==","peerName":"(null)","peerAvailable":true}]

,2016-01-28 12:50:27.643 ThaliTest[644:1120405] jxcore: connect 1453981826470.2048.JUV1sA==
2016-01-28 12:50:27.644 ThaliTest[644:1120405] client session: connect
2016-01-28 12:50:27.644 ThaliTest[644:1120405] client session: stateChange:0->1 1453981826470.2048.JUV1sA==
,2016-01-28 12:50:27.837 ThaliTest[644:1119968] multipeer session: reset timer
,2016-01-28 12:50:27.838 ThaliTest[644:1119968] multipeer session: stop timer
,2016-01-28 12:50:27.838 ThaliTest[644:1119968] multipeer session: start timer: 0x17e89330
,2016-01-28 12:50:27.839 ThaliTest[644:1119968] server session: connect
,2016-01-28 12:50:27.840 ThaliTest[644:1119968] server session: stateChange:0->1 1453981826470.2048
,2016-01-28 12:50:27.850 ThaliTest[644:1119968] server: accepting invitation 1453981826470.2048
,2016-01-28 12:50:29.090 ThaliTest[644:1119968] client: lost peer: 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:29.090 ThaliTest[644:1119968] client session: onPeerLost: 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:29.090 ThaliTest[644:1119968] client ses,sion: onLinkFailure: 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:29.090 ThaliTest[644:1119968] client session: disconnect
2016-01-28 12:50:29.091 ThaliTest[644:1119968] client session: stateChange:1->0 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:29.09,1 ThaliTest[644:1119968] client session: fireConnectCallback: 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:29.092 ThaliTest[644:1119968] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1453981820354.2048.JaM5Ig==","peerName":"(null)","peerAvailable":false}]

,2016-01-28 12:50:30.096 ThaliTest[644:1120405] jxcore: connect 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:30.096 ThaliTest[644:1120405] client: connect: unreachable 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:30.096 ThaliTest[644:1120405] jxcore: connect: fail: Peer unreachable
,2016-01-28 12:50:30.400 ThaliTest[644:1120972] client session: connected
,2016-01-28 12:50:30.400 ThaliTest[644:1120972] client session: stateChange:1->2 1453981826470.2048.JUV1sA==
,2016-01-28 12:50:30.405 ThaliTest[644:1120972] client session: fireConnectCallback: 1453981826470.2048.JUV1sA==
2016-01-28 12:50:30.405 ThaliTest[644:1120972] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-01-28 12:50:30.481 ThaliTest[644:1119968] client: relay established
2016-01-28 12:50:30.482 ThaliTest[644:1119968] client: new accepted socket: 0x1941e730
,2016-01-28 12:50:30.531 ThaliTest[644:1120972] server session: connected
2016-01-28 12:50:30.531 ThaliTest[644:1120972] server session: stateChange:1->2 1453981826470.2048
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-01-28 12:50:30.554 ThaliTest[644:1119968] client: socket closed
2016-01-28 12:50:30.554 ThaliTest[644:1119968] client relay: socket disconnected
2016-01-28 12:50:30.555 ThaliTest[644:1119968] client relay: 0x1941e730 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-28 12:50:30.555 ThaliTest[644:1119968] client session: socket closed: 1453981826470.2048.JUV1sA==
2016-01-28 12:5,0:30.555 ThaliTest[644:1119968] client session: onLinkFailure: 1453981826470.2048.JUV1sA==
2016-01-28 12:50:30.555 ThaliTest[644:1119968] client session: disconnect
2016-01-28 12:50:30.556 ThaliTest[644:1119968] client session: stateChange:2->0 145398182,6470.2048.JUV1sA==
,2016-01-28 12:50:30.568 ThaliTest[644:1119968] client session: fireConnectionErrorEvent: 1453981826470.2048.JUV1sA==
,2016-01-28 12:50:30.588 ThaliTest[644:1119968] server relay: connected (to port: 52203)
,2016-01-28 12:50:30.582 ThaliTest[644:1120405] jxcore: connect 1453981826470.2048.JUV1sA==
,2016-01-28 12:50:30.598 ThaliTest[644:1120405] client session: connect
,2016-01-28 12:50:30.600 ThaliTest[644:1120405] client session: stateChange:0->1 1453981826470.2048.JUV1sA==
,2016-01-28 12:50:30.723 ThaliTest[644:1120971] server session: not connected 1453981826470.2048
,2016-01-28 12:50:31.047 ThaliTest[644:1119968] multipeer session: reset timer
2016-01-28 12:50:31.047 ThaliTest[644:1119968] multipeer session: stop timer
2016-01-28 12:50:31.047 ThaliTest[644:1119968] multipeer session: start timer: 0x17e89330
,2016-01-28 12:50:31.048 ThaliTest[644:1119968] server: disconnecting to refresh session (1453981826470.2048)
2016-01-28 12:50:31.049 ThaliTest[644:1119968] server session: disconnect
2016-01-28 12:50:31.050 ThaliTest[644:1119968] server session: stateChange:2->0 1453981826470.2048
,2016-01-28 12:50:31.054 ThaliTest[644:1119968] server session: connect
2016-01-28 12:50:31.054 ThaliTest[644:1119968] server session: stateChange:0->1 1453981826470.2048
,2016-01-28 12:50:31.067 ThaliTest[644:1119968] server: accepting invitation 1453981826470.2048
,2016-01-28 12:50:33.612 ThaliTest[644:1120973] client session: connected
2016-01-28 12:50:33.614 ThaliTest[644:1120973] client session: stateChange:1->2 1453981826470.2048.JUV1sA==
,2016-01-28 12:50:33.618 ThaliTest[644:1120973] client session: fireConnectCallback: 1453981826470.2048.JUV1sA==
2016-01-28 12:50:33.619 ThaliTest[644:1120973] jxcore: connect: success
ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-01-28 12:50:33.654 ThaliTest[644:1119968] client: relay established
,2016-01-28 12:50:33.655 ThaliTest[644:1119968] client: new accepted socket: 0x1b90e510
,ok 111 the test messages should be equal

ok 112 Second send should succeed

# setup

,2016-01-28 12:50:33.756 ThaliTest[644:1119968] client: socket closed
2016-01-28 12:50:33.757 ThaliTest[644:1119968] client relay: socket disconnected
2016-01-28 12:50:33.757 ThaliTest[644:1119968] client relay: 0x1b90e510 disconnected with error Error Do,main=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-28 12:50:33.758 ThaliTest[644:1119968] client session: socket closed: 1453981826470.2048.JUV1sA==
2016-01-28 12:5,0:33.758 ThaliTest[644:1119968] client session: onLinkFailure: 1453981826470.2048.JUV1sA==
2016-01-28 12:50:33.758 ThaliTest[644:1119968] client session: disconnect
2016-01-28 12:50:33.758 ThaliTest[644:1119968] client session: stateChange:2->0 145398182,6470.2048.JUV1sA==
,2016-01-28 12:50:33.770 ThaliTest[644:1119968] client session: fireConnectionErrorEvent: 1453981826470.2048.JUV1sA==
,2016-01-28 12:50:33.861 ThaliTest[644:1121087] server session: connected
2016-01-28 12:50:33.862 ThaliTest[644:1121087] server session: stateChange:1->2 1453981826470.2048
,2016-01-28 12:50:33.872 ThaliTest[644:1119968] server relay: connected (to port: 52203)
,2016-01-28 12:50:33.998 ThaliTest[644:1120969] server session: not connected 1453981826470.2048
,calling stopBroadcasting

,2016-01-28 12:50:34.807 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:50:34.808 ThaliTest[644:1120405] THEMultipeerSession stopping peer
2016-01-28 12:50:34.808 ThaliTest[644:1120405] multipeer session: stop timer
2016-01-28 12:50:34.808, ThaliTest[644:1120405] server session: disconnect
2016-01-28 12:50:34.809 ThaliTest[644:1120405] server session: stateChange:2->0 1453981826470.2048
,2016-01-28 12:50:35.543 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2A88C4CD-0AA0-47BD-843F-61EAE8882302/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-28 12:50:58.383 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:50:58.384 ThaliTest[644:1120405] server: starting Ta0VTXPdONhln0_rgJJe4Q.awiBVw==
2016-01-28 12:50:58.385 ThaliTest[644:1120405] multipeer session: start timer: 0x195966c0
2016-01-28 12:50:58.385 ThaliTest[644:1120405] THEMultipeerSession i,nitialized peer Ta0VTXPdONhln0_rgJJe4Q
2016-01-28 12:50:58.385 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

2016-01-28 12:50:58.386 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:50:58.387 ThaliTest[644:1120405] THEMultipeerSession stopping peer
2016-01-28 12:50:58.387 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:50:58.387 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2A88C4CD-0AA0-47BD-843F-61EAE8882302/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-28 12:51:03.162 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:51:03.166 ThaliTest[644:1120405] server: starting Ta0VTXPdONhln0_rgJJe4Q.+jQ+rA==
2016-01-28 12:51:03.167 ThaliTest[644:1120405] multipeer session: start timer: 0x194a43f0
2016-01-28 12:51:03.167 ThaliTest[644:1120405] THEMultipeerSession i,nitialized peer Ta0VTXPdONhln0_rgJJe4Q
2016-01-28 12:51:03.168 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._isSt,arted: true

About to call stopBroadcasting

,2016-01-28 12:51:03.171 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:51:03.171 ThaliTest[644:1120405] THEMultipeerSession stopping peer
,2016-01-28 12:51:03.172 ThaliTest[644:1120405] multipeer session: stop timer
,2016-01-28 12:51:03.173 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/2A88C4CD-0AA0-47BD-843F-61EAE8882302/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-28 12:51:06.570 ThaliTest[644:1120405] jxcore: startBroadcasting
,2016-01-28 12:51:06.572 ThaliTest[644:1120405] server: starting Ta0VTXPdONhln0_rgJJe4Q.f1M0Fg==
2016-01-28 12:51:06.572 ThaliTest[644:1120405] multipeer session: start timer: 0x1bbf33f0
2016-01-28 12:51:06.572 ThaliTest[644:1120405] THEMultipeerSession initialized peer Ta0VTXPdONhln0_rgJJe4Q
2016-01-28 12:51:06.573 ThaliTest[644:1120405] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-01-28 12:51:10.698 ThaliTest[644:1119968] client: found peer: 5lxph6z1iSKyTRJoLzZ-yg.pd8cJw==
,2016-01-28 12:51:11.321 ThaliTest[644:1120405] jxcore: connect 5lxph6z1iSKyTRJoLzZ-yg.pd8cJw==
2016-01-28 12:51:11.321 ThaliTest[644:1120405] client session: connect
2016-01-28 12:51:11.321 ThaliTest[644:1120405] client session: stateChange:0->1 5lxph6z1iSKyTRJoLzZ-yg.pd8cJw==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-01-28 12:51:18.848 ThaliTest[644:1120405] jxcore: stopBroadcasting
2016-01-28 12:51:18.849 ThaliTest[644:1120405] THEMultipeerSession stopping peer
2016-01-28 12:51:18.849 ThaliTest[644:1120405] multipeer session: stop timer
2016-01-28 12:51:18.849, ThaliTest[644:1120405] client session: disconnect
2016-01-28 12:51:18.849 ThaliTest[644:1120405] client session: stateChange:1->0 5lxph6z1iSKyTRJoLzZ-yg.pd8cJw==
2016-01-28 12:51:18.850 ThaliTest[644:1120405] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,appEnteredForeground wasn't registered


```
