#### Test 58741471ee11130_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58741471ee11130/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/18FCCC4E-391E-4E3D-8D6E-0064FB5ACECC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/18FCCC4E-391E-4E3D-8D6E-0064FB5ACECC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58741471ee11130/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58741471ee11130/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53158"
,(lldb)     command script import "/tmp/18FCCC4E-391E-4E3D-8D6E-0064FB5ACECC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 14:05:06.113 ThaliTest[1638:2960665] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/767CEAEA-D665-48F5-A5D3-FDB15FFA0578/Library/Cookies/Cookies.binarycookies
,2016-02-09 14:05:06.461 ThaliTest[1638:2960665] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 14:05:06.462 ThaliTest[1638:2960665] Multi-tasking -> Device: YES, App: YES
,2016-02-09 14:05:06.471 ThaliTest[1638:2960665] Unlimited access to network resources
,2016-02-09 14:05:06.479 ThaliTest[1638:2960665] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 14:05:16.478 ThaliTest[1638:2960665] Resetting plugins due to page load.
,2016-02-09 14:05:19.953 ThaliTest[1638:2960665] Finished load of: file:///var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/index.html
,2016-02-09 14:05:20.125 ThaliTest[1638:2960665] JXcore Cordova plugin initializing
2016-02-09 14:05:20.127 ThaliTest[1638:2960995] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

# setup

,# #start should fail if called twice in a row

,# teardown

,ok 54 specific error should be received

,# setup

,# #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 55 specific error should be returned

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,# setup

,# should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 58 error should be null

,ok 59 error should be null

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 60 error should be null

,ok 61 error should be null

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 62 specific error should be returned

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 14:10:04.764 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:04.780 ThaliTest[1638:2960995] server: starting 1455023404763.1638.F7gZfw==
,2016-02-09 14:10:04.781 ThaliTest[1638:2960995] multipeer session: start timer: 0x1747a480
2016-02-09 14:10:04.782 ThaliTest[1638:2960995] THEMultipeerSession initialized peer 1455023404763.1638
2016-02-09 14:10:04.783 ThaliTest[1638:2960995] jxcore: sta,rtBroadcasting: success
ok 63 Should be able to call startBroadcasting without error

,2016-02-09 14:10:04.785 ThaliTest[1638:2960995] jxcore: stopBroadcasting
2016-02-09 14:10:04.786 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
2016-02-09 14:10:04.786 ThaliTest[1638:2960995] multipeer session: stop timer
2016-02-09 14:10:04.,787 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

2016-02-09 14:10:04.789 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:04.795 ThaliTest[1638:2960995] server: starting 1455023404789.1638.cVxdiA==
2016-02-09 14:10:04.796 ThaliTest[1638:2960995] multipeer session: start timer: 0x1747a480
2016-02-09 14:10:04.796 ThaliTest[1638:2960995] THEMultipeerSession in,itialized peer 1455023404789.1638
2016-02-09 14:10:04.796 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-02-09 14:10:04.798 ThaliTest[1638:2960995] jxcore: stopBroadcasting,
2016-02-09 14:10:04.798 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
2016-02-09 14:10:04.799 ThaliTest[1638:2960995] multipeer session: stop timer
2016-02-09 14:10:04.799 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
ok 66 Shou,ld be able to call stopBroadcasting without error

2016-02-09 14:10:04.801 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:04.822 ThaliTest[1638:2960995] server: starting 1455023404800.1638.+ftgLw==
,2016-02-09 14:10:04.824 ThaliTest[1638:2960995] multipeer session: start timer: 0x163ea3c0
,2016-02-09 14:10:04.830 ThaliTest[1638:2960995] THEMultipeerSession initialized peer 1455023404800.1638
,2016-02-09 14:10:04.836 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
,ok 67 Should be able to call startBroadcasting without error

,2016-02-09 14:10:04.841 ThaliTest[1638:2960995] jxcore: stopBroadcasting
,2016-02-09 14:10:04.842 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:04.843 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:04.848 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 68 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:04.853 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:04.857 ThaliTest[1638:2960995] server: starting 1455023404852.1638.5FzhvQ==
,2016-02-09 14:10:04.860 ThaliTest[1638:2960995] multipeer session: start timer: 0x14d157d0
,2016-02-09 14:10:04.868 ThaliTest[1638:2960995] THEMultipeerSession initialized peer 1455023404852.1638
,2016-02-09 14:10:04.870 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-09 14:10:04.874 ThaliTest[1638:2960995] jxcore: stopBroadcasting
,2016-02-09 14:10:04.875 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:04.876 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:04.879 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:04.882 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:04.884 ThaliTest[1638:2960995] server: starting 1455023404882.1638.STJG/w==
,2016-02-09 14:10:04.890 ThaliTest[1638:2960995] multipeer session: start timer: 0x174944f0
,2016-02-09 14:10:04.892 ThaliTest[1638:2960995] THEMultipeerSession initialized peer 1455023404882.1638
,2016-02-09 14:10:04.893 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 14:10:04.896 ThaliTest[1638:2960995] jxcore: stopBroadcasting
,2016-02-09 14:10:04.896 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:04.897 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:04.899 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:04.903 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:04.906 ThaliTest[1638:2960995] server: starting 1455023404903.1638.ozzq+A==
,2016-02-09 14:10:04.908 ThaliTest[1638:2960995] multipeer session: start timer: 0x17494cd0
,2016-02-09 14:10:04.913 ThaliTest[1638:2960995] THEMultipeerSession initialized peer 1455023404903.1638
,2016-02-09 14:10:04.915 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-09 14:10:04.917 ThaliTest[1638:2960995] jxcore: stopBroadcasting
,2016-02-09 14:10:04.917 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:04.919 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:04.920 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:04.925 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:04.928 ThaliTest[1638:2960995] server: starting 1455023404925.1638.Rfl8Aw==
,2016-02-09 14:10:04.929 ThaliTest[1638:2960995] multipeer session: start timer: 0x17495a50
,2016-02-09 14:10:04.931 ThaliTest[1638:2960995] THEMultipeerSession initialized peer 1455023404925.1638
,2016-02-09 14:10:04.933 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-09 14:10:04.939 ThaliTest[1638:2960995] jxcore: stopBroadcasting
,2016-02-09 14:10:04.939 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:04.940 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:04.941 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error
,
,2016-02-09 14:10:04.947 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:04.950 ThaliTest[1638:2960995] server: starting 1455023404946.1638.Lo90rQ==
,2016-02-09 14:10:04.952 ThaliTest[1638:2960995] multipeer session: start timer: 0x14d15570
,2016-02-09 14:10:04.955 ThaliTest[1638:2960995] THEMultipeerSession initialized peer 1455023404946.1638
,2016-02-09 14:10:04.956 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 14:10:04.961 ThaliTest[1638:2960995] jxcore: stopBroadcasting
,2016-02-09 14:10:04.961 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:04.962 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:04.963 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 14:10:04.969 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:04.972 ThaliTest[1638:2960995] server: starting 1455023404969.1638.S1tJ4Q==
,2016-02-09 14:10:04.974 ThaliTest[1638:2960995] multipeer session: start timer: 0x174966a0
,2016-02-09 14:10:04.975 ThaliTest[1638:2960995] THEMultipeerSession initialized peer 1455023404969.1638
,2016-02-09 14:10:04.977 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 14:10:04.980 ThaliTest[1638:2960995] jxcore: stopBroadcasting
,2016-02-09 14:10:04.980 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:04.981 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:04.982 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error
,
,2016-02-09 14:10:04.986 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:04.988 ThaliTest[1638:2960995] server: starting 1455023404985.1638.KGkgaQ==
,2016-02-09 14:10:04.989 ThaliTest[1638:2960995] multipeer session: start timer: 0x17497550
,2016-02-09 14:10:04.992 ThaliTest[1638:2960995] THEMultipeerSession initialized peer 1455023404985.1638
,2016-02-09 14:10:04.993 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 14:10:04.995 ThaliTest[1638:2960995] jxcore: stopBroadcasting
,2016-02-09 14:10:04.996 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:04.996 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:04.997 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 14:10:05.801 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:05.805 ThaliTest[1638:2960995] server: starting 1455023405801.1638.GZfCxw==
2016-02-09 14:10:05.806 ThaliTest[1638:2960995] multipeer session: start timer: 0x171a8440
2016-02-09 14:10:05.807 ThaliTest[1638:2960995] THEMultipeerSession in,itialized peer 1455023405801.1638
2016-02-09 14:10:05.807 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

2016-02-09 14:10:05.809 ThaliTest[1638:2960995] jxcore: startBroadcasting,
2016-02-09 14:10:05.810 ThaliTest[1638:2960995] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

,2016-02-09 14:10:05.823 ThaliTest[1638:2960995] jxcore: stopBroadcasting
,2016-02-09 14:10:05.824 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:05.825 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:05.832 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 14:10:07.218 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:07.222 ThaliTest[1638:2960995] server: starting 1455023407218.1638.sh/xng==
2016-02-09 14:10:07.222 ThaliTest[1638:2960995] multipeer session: start timer: 0x16212860
2016-02-09 14:10:07.223 ThaliTest[1638:2960995] THEMultipeerSession in,itialized peer 1455023407218.1638
2016-02-09 14:10:07.223 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

2016-02-09 14:10:07.225 ThaliTest[1638:2960995] jxcore: connect foobar
,2016-02-09 14:10:07.226 ThaliTest[1638:2960995] client: unknown peer foobar
2016-02-09 14:10:07.227 ThaliTest[1638:2960995] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

2016-02-09 14:10:07.231 ThaliTest[1638:2960995] jxcore: stopBroadcasting
2016-02-09 14:10:07.231 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
2016-02-09 14:10:07.232 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:07.232 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 14:10:07.775 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:07.778 ThaliTest[1638:2960995] server: starting 1455023407774.1638.npHeHg==
2016-02-09 14:10:07.780 ThaliTest[1638:2960995] multipeer session: start timer: 0x1748e570
2016-02-09 14:10:07.780 ThaliTest[1638:2960995] THEMultipeerSession in,itialized peer 1455023407774.1638
2016-02-09 14:10:07.780 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 89 Should be able to call startBroadcasting without error

2016-02-09 14:10:07.782 ThaliTest[1638:2960995] jxcore: disconnect
2016-,02-09 14:10:07.783 ThaliTest[1638:2960995] jxcore: disconnect: fail
ok 90 Disconnect should fail to a non-existant peer 

2016-02-09 14:10:07.786 ThaliTest[1638:2960995] jxcore: stopBroadcasting
2016-02-09 14:10:07.786 ThaliTest[1638:2960995] THEMultip,eerSession stopping peer
2016-02-09 14:10:07.787 ThaliTest[1638:2960995] multipeer session: stop timer
2016-02-09 14:10:07.787 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 14:10:08.175 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:08.179 ThaliTest[1638:2960995] server: starting 1455023408175.1638.F4ep7w==
2016-02-09 14:10:08.179 ThaliTest[1638:2960995] multipeer session: start timer: 0x161297e0
2016-02-09 14:10:08.180 ThaliTest[1638:2960995] THEMultipeerSession in,itialized peer 1455023408175.1638
2016-02-09 14:10:08.180 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-09 14:10:09.484 ThaliTest[1638:2960665] client: found peer: 1455023409681.1093.cIjK6g==
,2016-02-09 14:10:09.487 ThaliTest[1638:2960995] jxcore: connect 1455023409681.1093.cIjK6g==
2016-02-09 14:10:09.488 ThaliTest[1638:2960995] client session: connect
2016-02-09 14:10:09.488 ThaliTest[1638:2960995] client session: stateChange:0->1 1455023409681.1093.cIjK6g==
,2016-02-09 14:10:09.744 ThaliTest[1638:2960665] multipeer session: reset timer
2016-02-09 14:10:09.744 ThaliTest[1638:2960665] multipeer session: stop timer
2016-02-09 14:10:09.745 ThaliTest[1638:2960665] multipeer session: start timer: 0x161297e0
2016-,02-09 14:10:09.745 ThaliTest[1638:2960665] server session: connect
2016-02-09 14:10:09.745 ThaliTest[1638:2960665] server session: stateChange:0->1 1455023409681.1093
,2016-02-09 14:10:09.755 ThaliTest[1638:2960665] server: accepting invitation 1455023409681.1093
,2016-02-09 14:10:12.295 ThaliTest[1638:2961493] server session: connected
2016-02-09 14:10:12.296 ThaliTest[1638:2961493] server session: stateChange:1->2 1455023409681.1093
,2016-02-09 14:10:12.356 ThaliTest[1638:2960665] server relay: socket disconnected
2016-02-09 14:10:12.357 ThaliTest[1638:2960665] server relay: 0x1668fc70 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 14:10:12.367 ThaliTest[1638:2961506] server session: not connected 1455023409681.1093
,2016-02-09 14:10:12.430 ThaliTest[1638:2961506] client session: connected
2016-02-09 14:10:12.430 ThaliTest[1638:2961506] client session: stateChange:1->2 1455023409681.1093.cIjK6g==
,2016-02-09 14:10:12.489 ThaliTest[1638:2961493] client session: fireConnectCallback: 1455023409681.1093.cIjK6g==
2016-02-09 14:10:12.490 ThaliTest[1638:2961493] jxcore: connect: success
ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 14:10:12.495 ThaliTest[1638:2960995] jxcore: disconnect
2016-02-09 14:10:12.495 ThaliTest[1638:2960995] client session: disconnectFromPeer: 1455023409681.1093.cIjK6g==
,2016-02-09 14:10:12.496 ThaliTest[1638:2960995] client session: disconnect
2016-02-09 14:10:12.497 ThaliTest[1638:2960995] client session: stateChange:2->0 1455023409681.1093.cIjK6g==
,2016-02-09 14:10:12.510 ThaliTest[1638:2960995] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 14:10:12.549 ThaliTest[1638:2960995] jxcore: stopBroadcasting
2016-02-09 14:10:12.549 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
2016-02-09 14:10:12.549 ThaliTest[1638:2960995] multipeer session: stop timer
2016-02-09 14:10:12.,550 ThaliTest[1638:2960995] server session: disconnect
2016-02-09 14:10:12.550 ThaliTest[1638:2960995] server session: stateChange:2->0 1455023409681.1093
2016-02-09 14:10:12.551 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 14:10:13.050 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:13.053 ThaliTest[1638:2960995] server: starting 1455023413049.1638.U7kpqQ==
2016-02-09 14:10:13.054 ThaliTest[1638:2960995] multipeer session: start timer: 0x171c03a0
2016-02-09 14:10:13.055 ThaliTest[1638:2960995] THEMultipeerSession in,itialized peer 1455023413049.1638
2016-02-09 14:10:13.055 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error

,2016-02-09 14:10:14.186 ThaliTest[1638:2960665] client: found peer: 1455023414576.1093.jAuJVA==
2016-02-09 14:10:14.188 ThaliTest[1638:2960995] jxcore: connect 1455023414576.1093.jAuJVA==
2016-02-09 14:10:14.188 ThaliTest[1638:2960995] client session: co,nnect
2016-02-09 14:10:14.188 ThaliTest[1638:2960995] client session: stateChange:0->1 1455023414576.1093.jAuJVA==
,2016-02-09 14:10:14.449 ThaliTest[1638:2960665] multipeer session: reset timer
2016-02-09 14:10:14.450 ThaliTest[1638:2960665] multipeer session: stop timer
2016-02-09 14:10:14.450 ThaliTest[1638:2960665] multipeer session: start timer: 0x171c03a0
2016-,02-09 14:10:14.450 ThaliTest[1638:2960665] server session: connect
2016-02-09 14:10:14.451 ThaliTest[1638:2960665] server session: stateChange:0->1 1455023414576.1093
,2016-02-09 14:10:14.459 ThaliTest[1638:2960665] server: accepting invitation 1455023414576.1093
,2016-02-09 14:10:16.889 ThaliTest[1638:2961493] client session: connected
2016-02-09 14:10:16.889 ThaliTest[1638:2961493] client session: stateChange:1->2 1455023414576.1093.jAuJVA==
,2016-02-09 14:10:16.904 ThaliTest[1638:2961506] client session: fireConnectCallback: 1455023414576.1093.jAuJVA==
2016-02-09 14:10:16.904 ThaliTest[1638:2961506] jxcore: connect: success
ok 97 Should be able to connect without error

ok 98 Port should be within range

,2016-02-09 14:10:16.908 ThaliTest[1638:2960995] jxcore: connect 1455023414576.1093.jAuJVA==
2016-02-09 14:10:16.909 ThaliTest[1638:2960995] client: already connect(ing/ed) to 1455023414576.1093.jAuJVA==
2016-02-09 14:10:16.909 ThaliTest[1638:2960995] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

2016-02-09 14:10:16.913 ThaliTest[1638:2960995] jxcore: disconnect
2016-02-09 14:10:16.913 ThaliTest[1638:2960995] client session: disconnectFromPeer: 1455023414576.1093.jAuJVA==
2016-02-09 14:10:16.914 ThaliTest[1638:2960995] client session: disconnect
,2016-02-09 14:10:16.914 ThaliTest[1638:2960995] client session: stateChange:2->0 1455023414576.1093.jAuJVA==
,2016-02-09 14:10:16.994 ThaliTest[1638:2960995] jxcore: disconnect: success
,ok 100 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.
,
,# setup

,2016-02-09 14:10:17.151 ThaliTest[1638:2961544] server session: connected
2016-02-09 14:10:17.152 ThaliTest[1638:2961544] server session: stateChange:1->2 1455023414576.1093
,2016-02-09 14:10:17.168 ThaliTest[1638:2960665] server relay: socket disconnected
2016-02-09 14:10:17.168 ThaliTest[1638:2960665] server relay: 0x1621d350 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 14:10:17.272 ThaliTest[1638:2961544] server session: not connected 1455023414576.1093
,calling stopBroadcasting

,2016-02-09 14:10:17.290 ThaliTest[1638:2960995] jxcore: stopBroadcasting
2016-02-09 14:10:17.291 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
2016-02-09 14:10:17.291 ThaliTest[1638:2960995] multipeer session: stop timer
2016-02-09 14:10:17.,291 ThaliTest[1638:2960995] server session: disconnect
2016-02-09 14:10:17.292 ThaliTest[1638:2960995] server session: stateChange:2->0 1455023414576.1093
,2016-02-09 14:10:17.295 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 14:10:18.115 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:18.118 ThaliTest[1638:2960995] server: starting 1455023418114.1638.LjXq2A==
2016-02-09 14:10:18.119 ThaliTest[1638:2960995] multipeer session: start timer: 0x16354c20
2016-02-09 14:10:18.120 ThaliTest[1638:2960995] THEMultipeerSession in,itialized peer 1455023418114.1638
2016-02-09 14:10:18.120 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-09 14:10:19.429 ThaliTest[1638:2960665] client: found peer: 1455023419773.1093./aaIFg==
,2016-02-09 14:10:19.434 ThaliTest[1638:2960995] jxcore: connect 1455023419773.1093./aaIFg==
2016-02-09 14:10:19.434 ThaliTest[1638:2960995] client session: connect
2016-02-09 14:10:19.435 ThaliTest[1638:2960995] client session: stateChange:0->1 1455023419773.1093./aaIFg==
,2016-02-09 14:10:19.515 ThaliTest[1638:2960665] multipeer session: reset timer
2016-02-09 14:10:19.515 ThaliTest[1638:2960665] multipeer session: stop timer
2016-02-09 14:10:19.515 ThaliTest[1638:2960665] multipeer session: start timer: 0x16354c20
2016-02-09 14:10:19.516 ThaliTest[1638:2960665] server session: connect
2016-02-09 14:10:19.516 ThaliTest[1638:2960665] server session: stateChange:0->1 1455023419773.1093
,2016-02-09 14:10:19.525 ThaliTest[1638:2960665] server: accepting invitation 1455023419773.1093
,2016-02-09 14:10:22.124 ThaliTest[1638:2961544] server session: connected
2016-02-09 14:10:22.124 ThaliTest[1638:2961544] server session: stateChange:1->2 1455023419773.1093
,2016-02-09 14:10:22.145 ThaliTest[1638:2960665] server relay: socket disconnected
2016-02-09 14:10:22.145 ThaliTest[1638:2960665] server relay: 0x163617f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 14:10:22.228 ThaliTest[1638:2961494] server session: not connected 1455023419773.1093
,2016-02-09 14:10:22.379 ThaliTest[1638:2961494] client session: connected
2016-02-09 14:10:22.379 ThaliTest[1638:2961494] client session: stateChange:1->2 1455023419773.1093./aaIFg==
,2016-02-09 14:10:22.393 ThaliTest[1638:2961544] client session: fireConnectCallback: 1455023419773.1093./aaIFg==
2016-02-09 14:10:22.394 ThaliTest[1638:2961544] jxcore: connect: success
ok 102 Should be able to connect without error

ok 103 Port should be within range

,2016-02-09 14:10:22.397 ThaliTest[1638:2960995] jxcore: disconnect
2016-02-09 14:10:22.399 ThaliTest[1638:2960995] client session: disconnectFromPeer: 1455023419773.1093./aaIFg==
2016-02-09 14:10:22.399 ThaliTest[1638:2960995] client session: disconnect
2016-02-09 14:10:22.399 ThaliTest[1638:2960995] client session: stateChange:2->0 1455023419773.1093./aaIFg==
,2016-02-09 14:10:22.410 ThaliTest[1638:2960995] jxcore: disconnect: success
ok 104 Should be able to disconnect without error

2016-02-09 14:10:22.412 ThaliTest[1638:2960995] jxcore: disconnect
2016-02-09 14:10:22.412 ThaliTest[1638:2960995] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

,setting stopBroadcasting callback and ending test.
,
,# setup

,calling stopBroadcasting

,2016-02-09 14:10:22.487 ThaliTest[1638:2960995] jxcore: stopBroadcasting
,2016-02-09 14:10:22.488 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:22.489 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:22.497 ThaliTest[1638:2960995] server session: disconnect
,2016-02-09 14:10:22.504 ThaliTest[1638:2960995] server session: stateChange:2->0 1455023419773.1093
,2016-02-09 14:10:22.511 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,
,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 59939

,2016-02-09 14:10:24.486 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:24.488 ThaliTest[1638:2960995] server: starting 1455023424486.1638.M6bZVQ==
2016-02-09 14:10:24.488 ThaliTest[1638:2960995] multipeer session: start timer: 0x14e48550
2016-02-09 14:10:24.488 ThaliTest[1638:2960995] THEMultipeerSession in,itialized peer 1455023424486.1638
2016-02-09 14:10:24.489 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 106 Should be able to call startBroadcasting without error

,2016-02-09 14:10:24.494 ThaliTest[1638:2960665] client: found peer: 1455023419773.1093./aaIFg==
2016-02-09 14:10:24.494 ThaliTest[1638:2960995] jxcore: connect 1455023419773.1093./aaIFg==
2016-02-09 14:10:24.494 ThaliTest[1638:2960995] client session: connect
2016-02-09 14:10:24.495 ThaliTest[1638:2960995] client session: stateChange:0->1 1455023419773.1093./aaIFg==
,2016-02-09 14:10:25.719 ThaliTest[1638:2960665] client: lost peer: 1455023419773.1093./aaIFg==
2016-02-09 14:10:25.719 ThaliTest[1638:2960665] client session: onPeerLost: 1455023419773.1093./aaIFg==
2016-02-09 14:10:25.719 ThaliTest[1638:2960665] client ,session: onLinkFailure: 1455023419773.1093./aaIFg==
2016-02-09 14:10:25.720 ThaliTest[1638:2960665] client session: disconnect
2016-02-09 14:10:25.720 ThaliTest[1638:2960665] client session: stateChange:1->0 1455023419773.1093./aaIFg==
2016-02-09 14:10:25.721 ThaliTest[1638:2960665] client session: fireConnectCallback: 1455023419773.1093./aaIFg==
,2016-02-09 14:10:25.721 ThaliTest[1638:2960665] jxcore: connect: fail: Peer disconnected
,2016-02-09 14:10:26.726 ThaliTest[1638:2960995] jxcore: connect 1455023419773.1093./aaIFg==
2016-02-09 14:10:26.726 ThaliTest[1638:2960995] client: connect: unreachable 1455023419773.1093./aaIFg==
2016-02-09 14:10:26.726 ThaliTest[1638:2960995] jxcore: connect: fail: Peer unreachable
,2016-02-09 14:10:27.362 ThaliTest[1638:2960665] client: found peer: 1455023427853.1093.8Cv6/Q==
2016-02-09 14:10:27.368 ThaliTest[1638:2960995] jxcore: connect 1455023427853.1093.8Cv6/Q==
,2016-02-09 14:10:27.370 ThaliTest[1638:2960995] client session: connect
2016-02-09 14:10:27.372 ThaliTest[1638:2960995] client session: stateChange:0->1 1455023427853.1093.8Cv6/Q==
,2016-02-09 14:10:27.401 ThaliTest[1638:2960665] multipeer session: reset timer
,2016-02-09 14:10:27.401 ThaliTest[1638:2960665] multipeer session: stop timer
2016-02-09 14:10:27.405 ThaliTest[1638:2960665] multipeer session: start timer: 0x14e48550
2016-02-09 14:10:27.406 ThaliTest[1638:2960665] server session: connect
2016-02-09 14:10:27.406 ThaliTest[1638:2960665] server session: stateChange:0->1 1455023427853.1093
,2016-02-09 14:10:27.419 ThaliTest[1638:2960665] server: accepting invitation 1455023427853.1093
,2016-02-09 14:10:29.987 ThaliTest[1638:2961544] server session: connected
,2016-02-09 14:10:29.988 ThaliTest[1638:2961544] server session: stateChange:1->2 1455023427853.1093
,2016-02-09 14:10:29.997 ThaliTest[1638:2960665] server relay: connected (to port: 59939)
,2016-02-09 14:10:30.265 ThaliTest[1638:2961494] client session: connected
2016-02-09 14:10:30.265 ThaliTest[1638:2961494] client session: stateChange:1->2 1455023427853.1093.8Cv6/Q==
,2016-02-09 14:10:30.275 ThaliTest[1638:2961494] client session: fireConnectCallback: 1455023427853.1093.8Cv6/Q==
2016-02-09 14:10:30.280 ThaliTest[1638:2961494] jxcore: connect: success
ok 107 Should be able to connect without error

,ok 108 Port should be within range

2016-02-09 14:10:30.292 ThaliTest[1638:2960665] client: relay established
2016-02-09 14:10:30.292 ThaliTest[1638:2960665] client: new accepted socket: 0x1673abf0
,data in 10950
,
,data in 13140

,data in 19710
,
,data in 26280

,data in 36135

,data in 47085

,data in 59130

,data in 60225

,2016-02-09 14:10:30.933 ThaliTest[1638:2961506] server session: not connected 1455023427853.1093
,data in 66795

,data in 68985

,data in 83220

,data in 93075

,data in 105120

,data in 114975
,
,data in 127020

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 14:10:31.246 ThaliTest[1638:2960995] jxcore: disconnect
,2016-02-09 14:10:31.248 ThaliTest[1638:2960995] client session: disconnectFromPeer: 1455023427853.1093.8Cv6/Q==
,2016-02-09 14:10:31.249 ThaliTest[1638:2960995] client session: disconnect
,2016-02-09 14:10:31.249 ThaliTest[1638:2960995] client session: stateChange:2->0 1455023427853.1093.8Cv6/Q==
,2016-02-09 14:10:31.264 ThaliTest[1638:2960995] jxcore: disconnect: success
,ok 110 Should be able to disconnect without error
,
,setting stopBroadcasting callback and ending test.
,
,# setup
,
,calling stopBroadcasting

,2016-02-09 14:10:31.368 ThaliTest[1638:2960995] jxcore: stopBroadcasting
2016-02-09 14:10:31.368 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
2016-02-09 14:10:31.369 ThaliTest[1638:2960995] multipeer session: stop timer
2016-02-09 14:10:31.,369 ThaliTest[1638:2960995] server session: disconnect
2016-02-09 14:10:31.370 ThaliTest[1638:2960995] server session: stateChange:2->0 1455023427853.1093
,2016-02-09 14:10:31.379 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 59946

,2016-02-09 14:10:31.895 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:31.898 ThaliTest[1638:2960995] server: starting 1455023431894.1638.5uy/6Q==
2016-02-09 14:10:31.899 ThaliTest[1638:2960995] multipeer session: start timer: 0x173cc460
2016-02-09 14:10:31.900 ThaliTest[1638:2960995] THEMultipeerSession in,itialized peer 1455023431894.1638
2016-02-09 14:10:31.900 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error

,2016-02-09 14:10:33.197 ThaliTest[1638:2960665] multipeer session: reset timer
2016-02-09 14:10:33.197 ThaliTest[1638:2960665] multipeer session: stop timer
2016-02-09 14:10:33.198 ThaliTest[1638:2960665] multipeer session: start timer: 0x173cc460
2016-,02-09 14:10:33.198 ThaliTest[1638:2960665] server session: connect
2016-02-09 14:10:33.198 ThaliTest[1638:2960665] server session: stateChange:0->1 1455023433406.1093
,2016-02-09 14:10:33.208 ThaliTest[1638:2960665] server: accepting invitation 1455023433406.1093
,2016-02-09 14:10:33.260 ThaliTest[1638:2960665] client: found peer: 1455023433406.1093.alYVuw==
[{"peerIdentifier":"1455023433406.1093.alYVuw==","peerName":"(null)","peerAvailable":true}]

2016-02-09 14:10:33.264 ThaliTest[1638:2960995] jxcore: connect 1455023433406.1093.alYVuw==
2016-02-09 14:10:33.266 ThaliTest[1638:2960995] client session: connect
2016-02-09 14:10:33.266 ThaliTest[1638:2960995] client session: stateChange:0->1 1455023433406.1093.alYVuw==
,2016-02-09 14:10:35.821 ThaliTest[1638:2961505] server session: connected
2016-02-09 14:10:35.821 ThaliTest[1638:2961505] server session: stateChange:1->2 1455023433406.1093
,2016-02-09 14:10:35.836 ThaliTest[1638:2960665] server relay: connected (to port: 59946)
,2016-02-09 14:10:36.011 ThaliTest[1638:2961505] client session: connected
2016-02-09 14:10:36.011 ThaliTest[1638:2961505] client session: stateChange:1->2 1455023433406.1093.alYVuw==
,2016-02-09 14:10:36.049 ThaliTest[1638:2961543] server session: not connected 1455023433406.1093
,2016-02-09 14:10:36.060 ThaliTest[1638:2961543] client session: fireConnectCallback: 1455023433406.1093.alYVuw==
2016-02-09 14:10:36.061 ThaliTest[1638:2961543] jxcore: connect: success
,ok 112 Should be able to connect without error

ok 113 Port should be within range

,ok 114 First connect should succeed

,2016-02-09 14:10:36.133 ThaliTest[1638:2960665] multipeer session: reset timer
2016-02-09 14:10:36.133 ThaliTest[1638:2960665] multipeer session: stop timer
2016-02-09 14:10:36.135 ThaliTest[1638:2960665] multipeer session: start timer: 0x173cc460
2016-02-09 14:10:36.136 ThaliTest[1638:2960665] server: disconnecting to refresh session (1455023433406.1093)
2016-02-09 14:10:36.136 ThaliTest[1638:2960665] server session: disconnect
2016-02-09 14:10:36.136 ThaliTest[1638:2960665] server session: stateChang,e:2->0 1455023433406.1093
,2016-02-09 14:10:36.434 ThaliTest[1638:2960665] server session: connect
2016-02-09 14:10:36.435 ThaliTest[1638:2960665] server session: stateChange:0->1 1455023433406.1093
,2016-02-09 14:10:36.443 ThaliTest[1638:2960665] server: accepting invitation 1455023433406.1093
2016-02-09 14:10:36.444 ThaliTest[1638:2960665] client: relay established
2016-02-09 14:10:36.445 ThaliTest[1638:2960665] client: new accepted socket: 0x166c93e0
,ok 115 the test messages should be equal

ok 116 First send should succeed

,2016-02-09 14:10:36.502 ThaliTest[1638:2960665] client: socket closed
2016-02-09 14:10:36.502 ThaliTest[1638:2960665] client relay: socket disconnected
2016-02-09 14:10:36.502 ThaliTest[1638:2960665] client relay: 0x166c93e0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 14:10:36.503 ThaliTest[1638:2960665] client session: socket closed: 1455023433406.1093.alYVuw==
2016-02-09 ,14:10:36.503 ThaliTest[1638:2960665] client session: onLinkFailure: 1455023433406.1093.alYVuw==
2016-02-09 14:10:36.503 ThaliTest[1638:2960665] client session: disconnect
2016-02-09 14:10:36.504 ThaliTest[1638:2960665] client session: stateChange:2->0 14,55023433406.1093.alYVuw==
,2016-02-09 14:10:36.527 ThaliTest[1638:2960665] client session: fireConnectionErrorEvent: 1455023433406.1093.alYVuw==
,2016-02-09 14:10:36.531 ThaliTest[1638:2960995] jxcore: connect 1455023433406.1093.alYVuw==
,2016-02-09 14:10:36.545 ThaliTest[1638:2960995] client session: connect
,2016-02-09 14:10:36.546 ThaliTest[1638:2960995] client session: stateChange:0->1 1455023433406.1093.alYVuw==
,2016-02-09 14:10:39.146 ThaliTest[1638:2961494] server session: connected
2016-02-09 14:10:39.147 ThaliTest[1638:2961494] server session: stateChange:1->2 1455023433406.1093
,2016-02-09 14:10:39.165 ThaliTest[1638:2960665] server relay: connected (to port: 59946)
,2016-02-09 14:10:39.287 ThaliTest[1638:2961505] server session: not connected 1455023433406.1093
,2016-02-09 14:10:39.355 ThaliTest[1638:2961505] client session: connected
,2016-02-09 14:10:39.355 ThaliTest[1638:2961505] client session: stateChange:1->2 1455023433406.1093.alYVuw==
,2016-02-09 14:10:39.384 ThaliTest[1638:2961543] client session: fireConnectCallback: 1455023433406.1093.alYVuw==
2016-02-09 14:10:39.385 ThaliTest[1638:2961543] jxcore: connect: success
ok 117 Should be able to connect without error

ok 118 Port should be within range
,
,ok 119 Second connect should succeed

,2016-02-09 14:10:39.420 ThaliTest[1638:2960665] client: relay established
2016-02-09 14:10:39.420 ThaliTest[1638:2960665] client: new accepted socket: 0x164b0ec0
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,# setup

,2016-02-09 14:10:39.508 ThaliTest[1638:2960665] client: socket closed
2016-02-09 14:10:39.508 ThaliTest[1638:2960665] client relay: socket disconnected
2016-02-09 14:10:39.509 ThaliTest[1638:2960665] client relay: 0x164b0ec0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 14:10:39.510 ThaliTest[1638:2960665] client session: socket closed: 1455023433406.1093.alYVuw==
2016-02-09 ,14:10:39.510 ThaliTest[1638:2960665] client session: onLinkFailure: 1455023433406.1093.alYVuw==
2016-02-09 14:10:39.510 ThaliTest[1638:2960665] client session: disconnect
2016-02-09 14:10:39.510 ThaliTest[1638:2960665] client session: stateChange:2->0 14,55023433406.1093.alYVuw==
,2016-02-09 14:10:39.524 ThaliTest[1638:2960665] client session: fireConnectionErrorEvent: 1455023433406.1093.alYVuw==
,calling stopBroadcasting

,2016-02-09 14:10:39.755 ThaliTest[1638:2960995] jxcore: stopBroadcasting
2016-02-09 14:10:39.756 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
2016-02-09 14:10:39.756 ThaliTest[1638:2960995] multipeer session: stop timer
2016-02-09 14:10:39.,757 ThaliTest[1638:2960995] server session: disconnect
2016-02-09 14:10:39.757 ThaliTest[1638:2960995] server session: stateChange:2->0 1455023433406.1093
,2016-02-09 14:10:39.764 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/767CEAEA-D665-48F5-A5D3-FDB15FFA0578/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 122 starting event should occur in right order

,2016-02-09 14:10:40.229 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:40.230 ThaliTest[1638:2960995] server: starting 6Vf7gCVRpsisNTWLkBikvg.KHnsAQ==
2016-02-09 14:10:40.231 ThaliTest[1638:2960995] multipeer session: start timer: 0x16415c50
2016-02-09 14:10:40.231 ThaliTest[1638:2960995] THEMultipeerSessio,n initialized peer 6Vf7gCVRpsisNTWLkBikvg
2016-02-09 14:10:40.231 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 123 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 124 stopping event should occur in right order

About to call stopBroadcasting

2016-02-09 14:10:40.232 ThaliTest[1638:2960995] jxcore: stopBroadcasting
2016-02-09 14:10:40.232 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
2016-02-09 14:10:40.232 ThaliTest[16,38:2960995] multipeer session: stop timer
2016-02-09 14:10:40.233 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 125 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/767CEAEA-D665-48F5-A5D3-FDB15FFA0578/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 14:10:40.829 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:40.833 ThaliTest[1638:2960995] server: starting 6Vf7gCVRpsisNTWLkBikvg.CfCsWQ==
2016-02-09 14:10:40.834 ThaliTest[1638:2960995] multipeer session: start timer: 0x14ebf740
2016-02-09 14:10:40.834 ThaliTest[1638:2960995] THEMultipeerSessio,n initialized peer 6Vf7gCVRpsisNTWLkBikvg
2016-02-09 14:10:40.835 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 126 getDeviceIdentity should not return an error

ok 127 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

,2016-02-09 14:10:40.838 ThaliTest[1638:2960995] jxcore: stopBroadcasting
2016-02-09 14:10:40.839 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
,2016-02-09 14:10:40.840 ThaliTest[1638:2960995] multipeer session: stop timer
,2016-02-09 14:10:40.841 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/767CEAEA-D665-48F5-A5D3-FDB15FFA0578/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 14:10:42.997 ThaliTest[1638:2960995] jxcore: startBroadcasting
,2016-02-09 14:10:42.999 ThaliTest[1638:2960995] server: starting 6Vf7gCVRpsisNTWLkBikvg.Qw4lbA==
2016-02-09 14:10:42.999 ThaliTest[1638:2960995] multipeer session: start timer: 0x17428730
2016-02-09 14:10:42.999 ThaliTest[1638:2960995] THEMultipeerSession initialized peer 6Vf7gCVRpsisNTWLkBikvg
2016-02-09 14:10:42.999 ThaliTest[1638:2960995] jxcore: startBroadcasting: success
ok 128 getDeviceIdentity should not return an error

ok 129 deviceName should not be null

,2016-02-09 14:10:44.755 ThaliTest[1638:2960665] client: found peer: slE-aU4rW0no9FdL8Wi02w.M6Hc4g==
,2016-02-09 14:10:47.510 ThaliTest[1638:2960995] jxcore: connect slE-aU4rW0no9FdL8Wi02w.M6Hc4g==
2016-02-09 14:10:47.510 ThaliTest[1638:2960995] client session: connect
2016-02-09 14:10:47.510 ThaliTest[1638:2960995] client session: stateChange:0->1 slE-aU4rW0no9FdL8Wi02w.M6Hc4g==
,ok 130 Should be able to put doc without error

,ok 131 1st change of local doc should contain local id

,2016-02-09 14:10:48.817 ThaliTest[1638:2960665] multipeer session: reset timer
2016-02-09 14:10:48.818 ThaliTest[1638:2960665] multipeer session: stop timer
2016-02-09 14:10:48.818 ThaliTest[1638:2960665] multipeer session: start timer: 0x17428730
2016-02-09 14:10:48.818 ThaliTest[1638:2960665] server session: connect
2016-02-09 14:10:48.819 ThaliTest[1638:2960665] server session: stateChange:0->1 slE-aU4rW0no9FdL8Wi02w
,2016-02-09 14:10:48.828 ThaliTest[1638:2960665] server: accepting invitation slE-aU4rW0no9FdL8Wi02w
,2016-02-09 14:10:50.685 ThaliTest[1638:2961493] client session: connected
,2016-02-09 14:10:50.685 ThaliTest[1638:2961493] client session: stateChange:1->2 slE-aU4rW0no9FdL8Wi02w.M6Hc4g==
,2016-02-09 14:10:50.816 ThaliTest[1638:2961543] client session: fireConnectCallback: slE-aU4rW0no9FdL8Wi02w.M6Hc4g==
2016-02-09 14:10:50.816 ThaliTest[1638:2961543] jxcore: connect: success
,2016-02-09 14:10:50.831 ThaliTest[1638:2960665] client: relay established
2016-02-09 14:10:50.832 ThaliTest[1638:2960665] client: new accepted socket: 0x17493e70
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
,
,client bridge: socket closed

,client bridge: new client socket

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,2016-02-09 14:10:52.912 ThaliTest[1638:2961506] server session: connected
2016-02-09 14:10:52.912 ThaliTest[1638:2961506] server session: stateChange:1->2 slE-aU4rW0no9FdL8Wi02w
,2016-02-09 14:10:52.920 ThaliTest[1638:2960665] server relay: connected (to port: 59961)
,server bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

,ok 132 1st change of remote doc should contain remote id

,ok 133 Can update remote doc without error

,null

,{ ok: true,
  id: 'd619ab5a-e71b-490e-b87b-975b2e9c5160',
  rev: '2-4ebb88eaa80cd77276d309d34fa11ac5' }

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,ok 134 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,ok 135 Local changes occur in strict order

,ok 136 2nd change of local doc should contain remote id

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,# setup

,client bridge: socket closed

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-02-09 14:10:59.158 ThaliTest[1638:2960995] jxcore: stopBroadcasting
2016-02-09 14:10:59.158 ThaliTest[1638:2960995] THEMultipeerSession stopping peer
2016-02-09 1,4:10:59.158 ThaliTest[1638:2960995] multipeer session: stop timer
2016-02-09 14:10:59.158 ThaliTest[1638:2960995] client session: disconnect
2016-02-09 14:10:59.158 ThaliTest[1638:2960995] client session: stateChange:2->0 slE-aU4rW0no9FdL8Wi02w.M6Hc4g==
,2016-02-09 14:10:59.171 ThaliTest[1638:2960995] server session: disconnect
2016-02-09 14:10:59.171 ThaliTest[1638:2960995] server session: stateChange:2->0 slE-aU4rW0no9FdL8Wi02w
,2016-02-09 14:10:59.199 ThaliTest[1638:2960995] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,client bridge: socket closed

server bridge: socket closed

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,2016-02-09 14:10:59.281 ThaliTest[1638:2960995] Error!: stream.push() after EOF
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/,node_modules/readable-stream/lib/_stream_readable.js","_functionName":"readableAddChunk","_lineNumber":"187","_columnNumber":"15","_msg":"    at readableAddChunk@/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTe,st.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:187:15"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js","_functionName":"Readable.prototype.push","_lineNumber":"165","_columnNumber":"10","_msg":"    at Readable.prototype.push@/private/var/mobile/Containers/Bundle/Applicat,ion/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:165:10"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC,4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Multiplex.prototype._send","_lineNumber":"197","_columnNumber":"13","_msg":"    at Multiplex.prototype._send@/private/var/mobile/Containers/Bundle/,Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:197:13"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Channel.prototype._open","_lineNumber":"109","_columnNumber":"3","_msg":"    at Channel.prototype._open@/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0E,BCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:109:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multi,plex/index.js","_functionName":"Channel.prototype.open","_lineNumber":"117","_columnNumber":"38","_msg":"    at Channel.prototype.open@/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modu,les/thali/node_modules/multiplex/index.js:117:38"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Multiplex.,prototype._addChannel","_lineNumber":"215","_columnNumber":"3","_msg":"    at Multiplex.prototype._addChannel@/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/mu,ltiplex/index.js:215:3"}]
Uncaught Exception: Error: stream.push() after EOF

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js',
    _functionName: 'readableAd,dChunk',
    _lineNumber: '187',
    _columnNumber: '15',
    _msg: '    at readableAddChunk@/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:187:15' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-strea,m/lib/_stream_readable.js',
    _functionName: 'Readable.prototype.push',
    _lineNumber: '165',
    _columnNumber: '10',
    _msg: '    at Readable.prototype.push@/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/,ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:165:10' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxc,ore/node_modules/thali/node_modules/multiplex/index.js',
    _functionName: 'Multiplex.prototype._send',
    _lineNumber: '197',
    _columnNumber: '13',
    _msg: '    at Multiplex.prototype._send@/private/var/mobile/Containers/Bundle/Application/FB6C,163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:197:13' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_mo,dules/thali/node_modules/multiplex/index.js',
    _functionName: 'Channel.prototype._open',
    _lineNumber: '109',
    _columnNumber: '3',
    _msg: '    at Channel.prototype._open@/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8,DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:109:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_,modules/multiplex/index.js',
    _functionName: 'Channel.prototype.open',
    _lineNumber: '117',
    _columnNumber: '38',
    _msg: '    at Channel.prototype.open@/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/T,haliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:117:38' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex,/index.js',
    _functionName: 'Multiplex.prototype._addChannel',
    _lineNumber: '215',
    _columnNumber: '3',
    _msg: '    at Multiplex.prototype._addChannel@/private/var/mobile/Containers/Bundle/Application/FB6C163B-8103-4787-8DC4-AF0EBCD0EF92/T,haliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:215:3' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

Error: stream.push() after EOF (/private/var/mobile/Containers/Bund
```
