#### Test 581356550b07fff_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/581356550b07fff/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/06B574FE-8B30-4B49-BA49-9ECF68D216BB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/06B574FE-8B30-4B49-BA49-9ECF68D216BB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/581356550b07fff/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/581356550b07fff/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52005"
,(lldb)     command script import "/tmp/06B574FE-8B30-4B49-BA49-9ECF68D216BB/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-08 17:51:32.577 ThaliTest[919:1604240] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D56A650B-96F4-42DC-94C4-184020E84159/Library/Cookies/Cookies.binarycookies
,2016-02-08 17:51:32.943 ThaliTest[919:1604240] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-08 17:51:32.944 ThaliTest[919:1604240] Multi-tasking -> Device: YES, App: YES
,2016-02-08 17:51:32.952 ThaliTest[919:1604240] Unlimited access to network resources
,2016-02-08 17:51:32.959 ThaliTest[919:1604240] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-08 17:51:43.100 ThaliTest[919:1604240] Resetting plugins due to page load.
,2016-02-08 17:51:46.504 ThaliTest[919:1604240] Finished load of: file:///var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/index.html
,2016-02-08 17:51:46.660 ThaliTest[919:1604240] JXcore Cordova plugin initializing
,2016-02-08 17:51:46.661 ThaliTest[919:1604497] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-02-08 17:56:56.818 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:56.833 ThaliTest[919:1604497] server: starting 1454950616817.919.v812Ag==
,2016-02-08 17:56:56.835 ThaliTest[919:1604497] multipeer session: start timer: 0x15fabfe0
2016-02-08 17:56:56.835 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950616817.919
,2016-02-08 17:56:56.836 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

2016-02-08 17:56:56.840 ThaliTest[919:1604497] jxcore: stopBroadcasting
2016-02-08 17:56:56.840 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:56:56.841 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:56:56.843 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.846 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:56.852 ThaliTest[919:1604497] server: starting 1454950616846.919.Y1GfxQ==
,2016-02-08 17:56:56.853 ThaliTest[919:1604497] multipeer session: start timer: 0x17ee7050
2016-02-08 17:56:56.853 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950616846.919
2016-02-08 17:56:56.854 ThaliTest[919:1604497] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.856 ThaliTest[919:1604497] jxcore: stopBroadcasting
2016-02-08 17:56:56.857 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:56:56.857 ThaliTest[919:1604497] multipeer session: stop timer
2016-02-08 17:56:56.858, ThaliTest[919:1604497] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.860 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:56.864 ThaliTest[919:1604497] server: starting 1454950616859.919.9SjScg==
2016-02-08 17:56:56.864 ThaliTest[919:1604497] multipeer session: start timer: 0x15f04f80
2016-02-08 17:56:56.865 ThaliTest[919:1604497] THEMultipeerSession initia,lized peer 1454950616859.919
2016-02-08 17:56:56.865 ThaliTest[919:1604497] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-02-08 17:56:56.867 ThaliTest[919:1604497] jxcore: stopBroadcasting
2016-0,2-08 17:56:56.867 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:56:56.869 ThaliTest[919:1604497] multipeer session: stop timer
2016-02-08 17:56:56.869 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
ok 59 Should be able, to call stopBroadcasting without error

2016-02-08 17:56:56.871 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:56.876 ThaliTest[919:1604497] server: starting 1454950616871.919.wvBdPg==
2016-02-08 17:56:56.877 ThaliTest[919:1604497] multipeer session: start timer: 0x18c46b00
2016-02-08 17:56:56.877 ThaliTest[919:1604497] THEMultipeerSession initia,lized peer 1454950616871.919
2016-02-08 17:56:56.878 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

2016-02-08 17:56:56.880 ThaliTest[919:1604497] jxcore: stopBroadcasting
2016-02-08 17:56:56.882 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:56:56.884 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:56:56.885 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.890 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:56.899 ThaliTest[919:1604497] server: starting 1454950616889.919.+UzZ0A==
,2016-02-08 17:56:56.900 ThaliTest[919:1604497] multipeer session: start timer: 0x15f053e0
2016-02-08 17:56:56.900 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950616889.919
,2016-02-08 17:56:56.901 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

2016-02-08 17:56:56.904 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:56:56.904 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:56:56.905 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:56:56.907 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

2016-02-08 17:56:56.909 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:56.912 ThaliTest[919:1604497] server: starting 1454950616909.919.IVYARg==
2016-02-08 17:56:56.913 ThaliTest[919:1604497] multipeer session: start timer: 0x18c48450
2016-02-08 17:56:56.913 ThaliTest[919:1604497] THEMultipeerSession initia,lized peer 1454950616909.919
2016-02-08 17:56:56.913 ThaliTest[919:1604497] jxcore: startBroadcasting: success
ok 64 Should be able to call startBroadcasting without error

2016-02-08 17:56:56.914 ThaliTest[919:1604497] jxcore: stopBroadcasting
2016-0,2-08 17:56:56.915 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:56:56.915 ThaliTest[919:1604497] multipeer session: stop timer
2016-02-08 17:56:56.915 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.919 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:56.924 ThaliTest[919:1604497] server: starting 1454950616917.919.2yQHjw==
,2016-02-08 17:56:56.926 ThaliTest[919:1604497] multipeer session: start timer: 0x15f00150
,2016-02-08 17:56:56.929 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950616917.919
,2016-02-08 17:56:56.930 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.932 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:56:56.933 ThaliTest[919:1604497] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.933 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:56:56.934 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.938 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:56.941 ThaliTest[919:1604497] server: starting 1454950616938.919.UgZtXQ==
,2016-02-08 17:56:56.942 ThaliTest[919:1604497] multipeer session: start timer: 0x18c48010
,2016-02-08 17:56:56.942 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950616938.919
,2016-02-08 17:56:56.944 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.948 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:56:56.949 ThaliTest[919:1604497] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.949 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:56:56.950 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.954 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:56.957 ThaliTest[919:1604497] server: starting 1454950616954.919.TWDnJA==
,2016-02-08 17:56:56.958 ThaliTest[919:1604497] multipeer session: start timer: 0x15f05180
,2016-02-08 17:56:56.960 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950616954.919
,2016-02-08 17:56:56.961 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.964 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:56:56.965 ThaliTest[919:1604497] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.966 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:56:56.968 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-08 17:56:56.970 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:56.973 ThaliTest[919:1604497] server: starting 1454950616970.919.4+Y3Qw==
,2016-02-08 17:56:56.974 ThaliTest[919:1604497] multipeer session: start timer: 0x15f00460
2016-02-08 17:56:56.974 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950616970.919
,2016-02-08 17:56:56.976 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-08 17:56:56.980 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:56:56.981 ThaliTest[919:1604497] THEMultipeerSession stopping peer
,2016-02-08 17:56:56.981 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:56:56.982 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-08 17:56:57.659 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:57.662 ThaliTest[919:1604497] server: starting 1454950617658.919.qZcmBw==
,2016-02-08 17:56:57.663 ThaliTest[919:1604497] multipeer session: start timer: 0x17e7fb70
,2016-02-08 17:56:57.664 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950617658.919
2016-02-08 17:56:57.664 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

2016-02-08 17:56:57.668 ThaliTest[919:1604497] jxcore: startBroadcasting
2016-02-08 17:56:57.668 ThaliTest[919:1604497] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-02-08 17:56:57.675 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:56:57.676 ThaliTest[919:1604497] THEMultipeerSession stopping peer
,2016-02-08 17:56:57.677 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:56:57.680 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-08 17:56:58.354 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:58.358 ThaliTest[919:1604497] server: starting 1454950618354.919.pw+ieg==
,2016-02-08 17:56:58.359 ThaliTest[919:1604497] multipeer session: start timer: 0x18c042b0
,2016-02-08 17:56:58.359 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950618354.919
,2016-02-08 17:56:58.360 ThaliTest[919:1604497] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-08 17:56:58.362 ThaliTest[919:1604497] jxcore: connect foobar
2016-02-08 17:56:58.363 ThaliTest[919:,1604497] client: unknown peer foobar
2016-02-08 17:56:58.363 ThaliTest[919:1604497] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

,2016-02-08 17:56:58.367 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:56:58.367 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:56:58.368 ThaliTest[919:1604497] multipeer session: stop timer
2016-02-08 17:56:58.368 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-08 17:56:59.237 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:59.240 ThaliTest[919:1604497] server: starting 1454950619236.919.9DsMhA==
,2016-02-08 17:56:59.241 ThaliTest[919:1604497] multipeer session: start timer: 0x18a4eda0
2016-02-08 17:56:59.241 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950619236.919
2016-02-08 17:56:59.242 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

2016-02-08 17:56:59.245 ThaliTest[919:1604497] jxcore: disconnect
2016-02-08 17:56:59.245 ThaliTest[919:1604497] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

2016-02-08 17:56:59.250 ThaliTest[919:1604497] jxcore: stopBroadcasting
2016-02-08 17:56:59.250 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:56:59.251 ThaliTest[919:1604497,] multipeer session: stop timer
2016-02-08 17:56:59.251 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-08 17:56:59.856 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:56:59.859 ThaliTest[919:1604497] server: starting 1454950619855.919.SaL/Jw==
,2016-02-08 17:56:59.860 ThaliTest[919:1604497] multipeer session: start timer: 0x18a56ac0
,2016-02-08 17:56:59.861 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950619855.919
2016-02-08 17:56:59.861 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-08 17:57:01.678 ThaliTest[919:1604240] client: found peer: 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:01.680 ThaliTest[919:1604497] jxcore: connect 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:01.681 ThaliTest[919:1604497] client session: connect
,2016-02-08 17:57:01.682 ThaliTest[919:1604497] client session: stateChange:0->1 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:03.332 ThaliTest[919:1604240] multipeer session: reset timer
2016-02-08 17:57:03.332 ThaliTest[919:1604240] multipeer session: stop timer
,2016-02-08 17:57:03.333 ThaliTest[919:1604240] multipeer session: start timer: 0x18a56ac0
2016-02-08 17:57:03.333 ThaliTest[919:1604240] server session: connect
,2016-02-08 17:57:03.333 ThaliTest[919:1604240] server session: stateChange:0->1 1454950619565.1482
,2016-02-08 17:57:03.340 ThaliTest[919:1604240] server: accepting invitation 1454950619565.1482
,2016-02-08 17:57:05.471 ThaliTest[919:1605071] client session: connected
,2016-02-08 17:57:05.471 ThaliTest[919:1605071] client session: stateChange:1->2 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:05.511 ThaliTest[919:1605063] client session: fireConnectCallback: 1454950619565.1482.VpSvQQ==
2016-02-08 17:57:05.512 ThaliTest[919:1605063] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-08 17:57:05.516 ThaliTest[919:1604497] jxcore: disconnect
,2016-02-08 17:57:05.517 ThaliTest[919:1604497] client session: disconnectFromPeer: 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:05.517 ThaliTest[919:1604497] client session: disconnect
,2016-02-08 17:57:05.517 ThaliTest[919:1604497] client session: stateChange:2->0 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:05.590 ThaliTest[919:1604497] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-08 17:57:05.923 ThaliTest[919:1605065] server session: connected
,2016-02-08 17:57:05.924 ThaliTest[919:1605065] server session: stateChange:1->2 1454950619565.1482
,2016-02-08 17:57:05.929 ThaliTest[919:1604240] server relay: socket disconnected
,2016-02-08 17:57:05.929 ThaliTest[919:1604240] server relay: 0x17d86350 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 17:57:05.989 ThaliTest[919:1605065] server session: not connected 1454950619565.1482
,calling stopBroadcasting

,2016-02-08 17:57:06.639 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:57:06.640 ThaliTest[919:1604497] THEMultipeerSession stopping peer
,2016-02-08 17:57:06.640 ThaliTest[919:1604497] multipeer session: stop timer
2016-02-08 17:57:06.641 ThaliTest[919:1604497] server session: disconnect
2016-02-08 17:57:06.642 ThaliTest[919:1604497] server session: stateChange:2->0 1454950619565.1482
,2016-02-08 17:57:06.643 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-08 17:57:06.747 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:57:06.750 ThaliTest[919:1604497] server: starting 1454950626746.919.9GyzhA==
,2016-02-08 17:57:06.751 ThaliTest[919:1604497] multipeer session: start timer: 0x18df2c40
2016-02-08 17:57:06.752 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950626746.919
2016-02-08 17:57:06.752 ThaliTest[919:1604497] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-08 17:57:06.763 ThaliTest[919:1604240] client: found peer: 1454950619855.919.SaL/Jw==
,2016-02-08 17:57:06.765 ThaliTest[919:1604240] client: found peer: 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:06.767 ThaliTest[919:1604497] jxcore: connect 1454950619855.919.SaL/Jw==
2016-02-08 17:57:06.768 ThaliTest[919:1604497] client session: connect
2016-02-08 17:57:06.768 ThaliTest[919:1604497] client session: stateChange:0->1 1454950619855,.919.SaL/Jw==
,2016-02-08 17:57:07.588 ThaliTest[919:1604497] jxcore: connect 1454950619565.1482.VpSvQQ==
2016-02-08 17:57:07.588 ThaliTest[919:1604497] client session: connect
,2016-02-08 17:57:07.589 ThaliTest[919:1604497] client session: stateChange:0->1 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:07.874 ThaliTest[919:1604240] client: lost peer: 1454950619855.919.SaL/Jw==
2016-02-08 17:57:07.875 ThaliTest[919:1604240] client session: onPeerLost: 1454950619855.919.SaL/Jw==
,2016-02-08 17:57:07.876 ThaliTest[919:1604240] client session: onLinkFailure: 1454950619855.919.SaL/Jw==
,2016-02-08 17:57:07.876 ThaliTest[919:1604240] client session: disconnect
2016-02-08 17:57:07.876 ThaliTest[919:1604240] client session: stateChange:1->0 1454950619855.919.SaL/Jw==
,2016-02-08 17:57:07.878 ThaliTest[919:1604240] client session: fireConnectCallback: 1454950619855.919.SaL/Jw==
,2016-02-08 17:57:07.878 ThaliTest[919:1604240] jxcore: connect: fail: Peer disconnected
,2016-02-08 17:57:07.879 ThaliTest[919:1604240] client: lost peer: 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:07.879 ThaliTest[919:1604240] client session: onPeerLost: 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:07.879 ThaliTest[919:1604240] client session: onLinkFailure: 1454950619565.1482.VpSvQQ==
2016-02-08 17:57:07.879 ThaliTest[919:1604240] client session: disconnect
,2016-02-08 17:57:07.880 ThaliTest[919:1604240] client session: stateChange:1->0 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:07.882 ThaliTest[919:1604240] client session: fireConnectCallback: 1454950619565.1482.VpSvQQ==
2016-02-08 17:57:07.882 ThaliTest[919:1604240] jxcore: connect: fail: Peer disconnected
,2016-02-08 17:57:07.885 ThaliTest[919:1604240] client: found peer: 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:07.886 ThaliTest[919:1604497] jxcore: connect 1454950626470.1482.JNUGZg==
2016-02-08 17:57:07.887 ThaliTest[919:1604497] client session: connect
2016-02-08 17:57:07.887 ThaliTest[919:1604497] client session: stateChange:0->1 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:08.078 ThaliTest[919:1604240] multipeer session: reset timer
,2016-02-08 17:57:08.078 ThaliTest[919:1604240] multipeer session: stop timer
,2016-02-08 17:57:08.079 ThaliTest[919:1604240] multipeer session: start timer: 0x18df2c40
,2016-02-08 17:57:08.079 ThaliTest[919:1604240] server session: connect
,2016-02-08 17:57:08.080 ThaliTest[919:1604240] server session: stateChange:0->1 1454950626470.1482
,2016-02-08 17:57:08.086 ThaliTest[919:1604240] server: accepting invitation 1454950626470.1482
,2016-02-08 17:57:08.886 ThaliTest[919:1604497] jxcore: connect 1454950619855.919.SaL/Jw==
2016-02-08 17:57:08.887 ThaliTest[919:1604497] client: connect: unreachable 1454950619855.919.SaL/Jw==
,2016-02-08 17:57:08.887 ThaliTest[919:1604497] jxcore: connect: fail: Peer unreachable
,2016-02-08 17:57:08.891 ThaliTest[919:1604497] jxcore: connect 1454950619565.1482.VpSvQQ==
2016-02-08 17:57:08.891 ThaliTest[919:1604497] client: connect: unreachable 1454950619565.1482.VpSvQQ==
,2016-02-08 17:57:08.892 ThaliTest[919:1604497] jxcore: connect: fail: Peer unreachable
,2016-02-08 17:57:10.712 ThaliTest[919:1605065] server session: connected
2016-02-08 17:57:10.712 ThaliTest[919:1605065] server session: stateChange:1->2 1454950626470.1482
,2016-02-08 17:57:10.734 ThaliTest[919:1604240] server relay: socket disconnected
2016-02-08 17:57:10.735 ThaliTest[919:1604240] server relay: 0x17da9e80 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 17:57:10.739 ThaliTest[919:1605063] client session: connected
2016-02-08 17:57:10.740 ThaliTest[919:1605063] client session: stateChange:1->2 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:10.753 ThaliTest[919:1605065] client session: fireConnectCallback: 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:10.753 ThaliTest[919:1605065] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-08 17:57:10.757 ThaliTest[919:1604497] jxcore: connect 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:10.758 ThaliTest[919:1604497] client: already connect(ing/ed) to 1454950626470.1482.JNUGZg==
2016-02-08 17:57:10.758 ThaliTest[919:1604497] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-08 17:57:10.762 ThaliTest[919:1604497] jxcore: disconnect
,2016-02-08 17:57:10.763 ThaliTest[919:1604497] client session: disconnectFromPeer: 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:10.763 ThaliTest[919:1604497] client session: disconnect
,2016-02-08 17:57:10.764 ThaliTest[919:1604497] client session: stateChange:2->0 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:10.837 ThaliTest[919:1604497] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-08 17:57:10.953 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:57:10.953 ThaliTest[919:1604497] THEMultipeerSession stopping peer
,2016-02-08 17:57:10.954 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:57:10.955 ThaliTest[919:1604497] server session: disconnect
2016-02-08 17:57:10.957 ThaliTest[919:1604497] server session: stateChange:2->0 1454950626470.1482
,2016-02-08 17:57:10.974 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-08 17:57:11.890 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:57:11.893 ThaliTest[919:1604497] server: starting 1454950631889.919.NlWxwg==
,2016-02-08 17:57:11.894 ThaliTest[919:1604497] multipeer session: start timer: 0x18cfbe70
,2016-02-08 17:57:11.895 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950631889.919
2016-02-08 17:57:11.895 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-08 17:57:12.138 ThaliTest[919:1604240] client: found peer: 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:12.140 ThaliTest[919:1604497] jxcore: connect 1454950626470.1482.JNUGZg==
2016-02-08 17:57:12.140 ThaliTest[919:1604497] client session: connect
2016-02-08 17:57:12.140 ThaliTest[919:1604497] client session: stateChange:0->1 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:13.136 ThaliTest[919:1604240] client: found peer: 1454950631694.1482.2LX/7A==
,2016-02-08 17:57:13.138 ThaliTest[919:1604497] jxcore: connect 1454950631694.1482.2LX/7A==
,2016-02-08 17:57:13.139 ThaliTest[919:1604497] client session: connect
,2016-02-08 17:57:13.139 ThaliTest[919:1604497] client session: stateChange:0->1 1454950631694.1482.2LX/7A==
,2016-02-08 17:57:13.586 ThaliTest[919:1604240] multipeer session: reset timer
2016-02-08 17:57:13.587 ThaliTest[919:1604240] multipeer session: stop timer
2016-02-08 17:57:13.587 ThaliTest[919:1604240] multipeer session: start timer: 0x18cfbe70
2016-02-08 17:57:13.588 ThaliTest[919:1604240] server session: connect
,2016-02-08 17:57:13.588 ThaliTest[919:1604240] server session: stateChange:0->1 1454950631694.1482
,2016-02-08 17:57:13.598 ThaliTest[919:1604240] server: accepting invitation 1454950631694.1482
,2016-02-08 17:57:15.944 ThaliTest[919:1605069] client session: connected
2016-02-08 17:57:15.944 ThaliTest[919:1605069] client session: stateChange:1->2 1454950631694.1482.2LX/7A==
,2016-02-08 17:57:15.949 ThaliTest[919:1605069] client session: fireConnectCallback: 1454950631694.1482.2LX/7A==
2016-02-08 17:57:15.950 ThaliTest[919:1605069] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-08 17:57:15.955 ThaliTest[919:1604497] jxcore: disconnect
,2016-02-08 17:57:15.955 ThaliTest[919:1604497] client session: disconnectFromPeer: 1454950631694.1482.2LX/7A==
,2016-02-08 17:57:15.956 ThaliTest[919:1604497] client session: disconnect
2016-02-08 17:57:15.957 ThaliTest[919:1604497] client session: stateChange:2->0 1454950631694.1482.2LX/7A==
,2016-02-08 17:57:15.967 ThaliTest[919:1604497] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

2016-02-08 17:57:15.973 ThaliTest[919:1604497] jxcore: disconnect
2016-02-08 17:57:15.973 ThaliTest[919:1604497] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-08 17:57:16.264 ThaliTest[919:1605069] server session: connected
2016-02-08 17:57:16.265 ThaliTest[919:1605069] server session: stateChange:1->2 1454950631694.1482
,2016-02-08 17:57:16.271 ThaliTest[919:1604240] server relay: socket disconnected
2016-02-08 17:57:16.272 ThaliTest[919:1604240] server relay: 0x15f74d10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 17:57:16.321 ThaliTest[919:1605068] server session: not connected 1454950631694.1482
,calling stopBroadcasting

,2016-02-08 17:57:16.605 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:57:16.605 ThaliTest[919:1604497] THEMultipeerSession stopping peer
,2016-02-08 17:57:16.606 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:57:16.607 ThaliTest[919:1604497] client session: disconnect
2016-02-08 17:57:16.607 ThaliTest[919:1604497] client session: stateChange:1->0 1454950626470.1482.JNUGZg==
,2016-02-08 17:57:16.608 ThaliTest[919:1604497] server session: disconnect
2016-02-08 17:57:16.611 ThaliTest[919:1604497] server session: stateChange:2->0 1454950631694.1482
,2016-02-08 17:57:16.613 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 54621

,2016-02-08 17:57:18.175 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:57:18.176 ThaliTest[919:1604497] server: starting 1454950638175.919.9EiIoQ==
,2016-02-08 17:57:18.177 ThaliTest[919:1604497] multipeer session: start timer: 0x18deb670
,2016-02-08 17:57:18.178 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950638175.919
,2016-02-08 17:57:18.178 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-02-08 17:57:19.485 ThaliTest[919:1604240] client: found peer: 1454950638025.1482.nOGF8A==
,2016-02-08 17:57:19.487 ThaliTest[919:1604497] jxcore: connect 1454950638025.1482.nOGF8A==
,2016-02-08 17:57:19.488 ThaliTest[919:1604497] client session: connect
2016-02-08 17:57:19.489 ThaliTest[919:1604497] client session: stateChange:0->1 1454950638025.1482.nOGF8A==
,2016-02-08 17:57:19.955 ThaliTest[919:1604240] multipeer session: reset timer
2016-02-08 17:57:19.955 ThaliTest[919:1604240] multipeer session: stop timer
2016-02-08 17:57:19.956 ThaliTest[919:1604240] multipeer session: start timer: 0x18deb670
2016-02-08 17:57:19.956 ThaliTest[919:1604240] server session: connect
,2016-02-08 17:57:19.956 ThaliTest[919:1604240] server session: stateChange:0->1 1454950638025.1482
,2016-02-08 17:57:19.963 ThaliTest[919:1604240] server: accepting invitation 1454950638025.1482
,2016-02-08 17:57:22.505 ThaliTest[919:1605063] client session: connected
,2016-02-08 17:57:22.506 ThaliTest[919:1605063] client session: stateChange:1->2 1454950638025.1482.nOGF8A==
,2016-02-08 17:57:22.510 ThaliTest[919:1605063] server session: connected
2016-02-08 17:57:22.510 ThaliTest[919:1605063] server session: stateChange:1->2 1454950638025.1482
,2016-02-08 17:57:22.515 ThaliTest[919:1605065] client session: fireConnectCallback: 1454950638025.1482.nOGF8A==
2016-02-08 17:57:22.516 ThaliTest[919:1605065] jxcore: connect: success
,2016-02-08 17:57:22.518 ThaliTest[919:1604240] server relay: connected (to port: 54621)
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-08 17:57:22.527 ThaliTest[919:1604240] client: relay established
2016-02-08 17:57:22.528 ThaliTest[919:1604240] client: new accepted socket: 0x18c5ac30
,data in 5475

,data in 10950

,data in 16425

,data in 27375

,data in 39349

,data in 50370

,data in 57964

,data in 123500

,data in 131072

,ok 100 the test messages should be equal

,2016-02-08 17:57:23.093 ThaliTest[919:1604497] jxcore: disconnect
,2016-02-08 17:57:23.094 ThaliTest[919:1604497] client session: disconnectFromPeer: 1454950638025.1482.nOGF8A==
,2016-02-08 17:57:23.095 ThaliTest[919:1604497] client session: disconnect
,2016-02-08 17:57:23.095 ThaliTest[919:1604497] client session: stateChange:2->0 1454950638025.1482.nOGF8A==
,2016-02-08 17:57:23.161 ThaliTest[919:1604497] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-08 17:57:23.482 ThaliTest[919:1605140] server session: not connected 1454950638025.1482
,calling stopBroadcasting

,2016-02-08 17:57:23.948 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:57:23.949 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:57:23.949 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:57:23.951 ThaliTest[919:1604497] server session: disconnect
,2016-02-08 17:57:23.951 ThaliTest[919:1604497] server session: stateChange:2->0 1454950638025.1482
,2016-02-08 17:57:23.959 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 54627

,2016-02-08 17:57:25.084 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:57:25.088 ThaliTest[919:1604497] server: starting 1454950645083.919.WulMow==
,2016-02-08 17:57:25.088 ThaliTest[919:1604497] multipeer session: start timer: 0x15f70ea0
2016-02-08 17:57:25.089 ThaliTest[919:1604497] THEMultipeerSession initialized peer 1454950645083.919
2016-02-08 17:57:25.089 ThaliTest[919:1604497] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-08 17:57:26.432 ThaliTest[919:1604240] multipeer session: reset timer
2016-02-08 17:57:26.432 ThaliTest[919:1604240] multipeer session: stop timer
2016-02-08 17:57:26.433 ThaliTest[919:1604240] multipeer session: start timer: 0x15f70ea0
2016-02-,08 17:57:26.433 ThaliTest[919:1604240] server session: connect
2016-02-08 17:57:26.433 ThaliTest[919:1604240] server session: stateChange:0->1 1454950645667.1482
,2016-02-08 17:57:26.440 ThaliTest[919:1604240] server: accepting invitation 1454950645667.1482
,2016-02-08 17:57:26.801 ThaliTest[919:1604240] client: found peer: 1454950645667.1482.mZpgYA==
,[{"peerIdentifier":"1454950645667.1482.mZpgYA==","peerName":"(null)","peerAvailable":true}]

,2016-02-08 17:57:26.804 ThaliTest[919:1604497] jxcore: connect 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:26.805 ThaliTest[919:1604497] client session: connect
,2016-02-08 17:57:26.805 ThaliTest[919:1604497] client session: stateChange:0->1 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:28.896 ThaliTest[919:1605063] server session: connected
2016-02-08 17:57:28.897 ThaliTest[919:1605063] server session: stateChange:1->2 1454950645667.1482
,2016-02-08 17:57:28.901 ThaliTest[919:1604240] server relay: connected (to port: 54627)
,2016-02-08 17:57:29.091 ThaliTest[919:1605140] server session: not connected 1454950645667.1482
,2016-02-08 17:57:29.148 ThaliTest[919:1604240] multipeer session: reset timer
2016-02-08 17:57:29.148 ThaliTest[919:1604240] multipeer session: stop timer
2016-02-08 17:57:29.149 ThaliTest[919:1604240] multipeer session: start timer: 0x15f70ea0
,2016-02-08 17:57:29.149 ThaliTest[919:1604240] server: disconnecting to refresh session (1454950645667.1482)
2016-02-08 17:57:29.149 ThaliTest[919:1604240] server session: disconnect
,2016-02-08 17:57:29.150 ThaliTest[919:1604240] server session: stateChange:2->0 1454950645667.1482
,2016-02-08 17:57:29.154 ThaliTest[919:1604240] server session: connect
2016-02-08 17:57:29.154 ThaliTest[919:1604240] server session: stateChange:0->1 1454950645667.1482
,2016-02-08 17:57:29.162 ThaliTest[919:1604240] server: accepting invitation 1454950645667.1482
,2016-02-08 17:57:29.390 ThaliTest[919:1605068] client session: connected
2016-02-08 17:57:29.390 ThaliTest[919:1605068] client session: stateChange:1->2 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:29.426 ThaliTest[919:1605068] client session: fireConnectCallback: 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:29.427 ThaliTest[919:1605068] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-08 17:57:29.504 ThaliTest[919:1604240] client: relay established
2016-02-08 17:57:29.504 ThaliTest[919:1604240] client: new accepted socket: 0x18a5ce00
,ok 106 the test messages should be equal

ok 107 First send should succeed

,2016-02-08 17:57:29.571 ThaliTest[919:1604240] client: socket closed
,2016-02-08 17:57:29.571 ThaliTest[919:1604240] client relay: socket disconnected
,2016-02-08 17:57:29.572 ThaliTest[919:1604240] client relay: 0x18a5ce00 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-08 17:57:2,9.572 ThaliTest[919:1604240] client session: socket closed: 1454950645667.1482.mZpgYA==
2016-02-08 17:57:29.572 ThaliTest[919:1604240] client session: onLinkFailure: 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:29.572 ThaliTest[919:1604240] client session: disconnect
2016-02-08 17:57:29.573 ThaliTest[919:1604240] client session: stateChange:2->0 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:29.582 ThaliTest[919:1604240] client session: fireConnectionErrorEvent: 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:29.585 ThaliTest[919:1604497] jxcore: connect 1454950645667.1482.mZpgYA==
2016-02-08 17:57:29.586 ThaliTest[919:1604497] client session: connect
2016-02-08 17:57:29.587 ThaliTest[919:1604497] client session: stateChange:0->1 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:31.668 ThaliTest[919:1605068] server session: connected
2016-02-08 17:57:31.668 ThaliTest[919:1605068] server session: stateChange:1->2 1454950645667.1482
,2016-02-08 17:57:31.676 ThaliTest[919:1604240] server relay: connected (to port: 54627)
,2016-02-08 17:57:31.814 ThaliTest[919:1605063] server session: not connected 1454950645667.1482
,2016-02-08 17:57:32.201 ThaliTest[919:1605068] client session: connected
2016-02-08 17:57:32.201 ThaliTest[919:1605068] client session: stateChange:1->2 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:32.205 ThaliTest[919:1605068] client session: fireConnectCallback: 1454950645667.1482.mZpgYA==
2016-02-08 17:57:32.205 ThaliTest[919:1605068] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-08 17:57:32.241 ThaliTest[919:1604240] client: relay established
2016-02-08 17:57:32.241 ThaliTest[919:1604240] client: new accepted socket: 0x18b19660
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-08 17:57:32.303 ThaliTest[919:1604240] client: socket closed
,2016-02-08 17:57:32.304 ThaliTest[919:1604240] client relay: socket disconnected
,2016-02-08 17:57:32.304 ThaliTest[919:1604240] client relay: 0x18b19660 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-08 17:57:32.304 ThaliTest[919:1604240] client session: socket closed: 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:32.305 ThaliTest[919:1604240] client session: onLinkFailure: 1454950645667.1482.mZpgYA==
2016-02-08 17:57:32.305 ThaliTest[919:1604240] client session: disconnect
,2016-02-08 17:57:32.306 ThaliTest[919:1604240] client session: stateChange:2->0 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:32.315 ThaliTest[919:1604240] client session: fireConnectionErrorEvent: 1454950645667.1482.mZpgYA==
,calling stopBroadcasting

,2016-02-08 17:57:33.392 ThaliTest[919:1604497] jxcore: stopBroadcasting
,2016-02-08 17:57:33.392 ThaliTest[919:1604497] THEMultipeerSession stopping peer
,2016-02-08 17:57:33.393 ThaliTest[919:1604497] multipeer session: stop timer
,2016-02-08 17:57:33.394 ThaliTest[919:1604497] server session: disconnect
2016-02-08 17:57:33.394 ThaliTest[919:1604497] server session: stateChange:2->0 1454950645667.1482
,2016-02-08 17:57:33.409 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D56A650B-96F4-42DC-94C4-184020E84159/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-08 17:57:33.888 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:57:33.890 ThaliTest[919:1604497] server: starting RwJLtZ5s_sJcUxQ5zha7Ng.9ioVbA==
,2016-02-08 17:57:33.890 ThaliTest[919:1604497] multipeer session: start timer: 0x18885d60
2016-02-08 17:57:33.890 ThaliTest[919:1604497] THEMultipeerSession initialized peer RwJLtZ5s_sJcUxQ5zha7Ng
2016-02-08 17:57:33.890 ThaliTest[919:1604497] jxcore: st,artBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

,ok 115 stopping event should occur in right order

About to call stopBroadcasting
,
,2016-02-08 17:57:33.892 ThaliTest[919:1604497] jxcore: stopBroadcasting
2016-02-08 17:57:33.892 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:57:33.892 ThaliTest[919:1604497] multipeer session: stop timer
2016-02-08 17:57:33.892 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D56A650B-96F4-42DC-94C4-184020E84159/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 17:57:34.089 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:57:34.091 ThaliTest[919:1604497] server: starting RwJLtZ5s_sJcUxQ5zha7Ng.nBatFg==
,2016-02-08 17:57:34.091 ThaliTest[919:1604497] multipeer session: start timer: 0x15f6de50
2016-02-08 17:57:34.092 ThaliTest[919:1604497] THEMultipeerSession initialized peer RwJLtZ5s_sJcUxQ5zha7Ng
2016-02-08 17:57:34.092 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

,Now in TRM stop

,State of this._isStarted: true
,
About to call stopBroadcasting

2016-02-08 17:57:34.095 ThaliTest[919:1604497] jxcore: stopBroadcasting
2016-02-08 17:57:34.095 ThaliTest[919:1604497] THEMultipeerSession stopping peer
2016-02-08 17:57:34.095 ThaliTest[919:1604497] multipeer session: stop timer
2016-02-08 17:57:34.096 ThaliTest[919:1604497] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D56A650B-96F4-42DC-94C4-184020E84159/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 17:57:36.107 ThaliTest[919:1604497] jxcore: startBroadcasting
,2016-02-08 17:57:36.108 ThaliTest[919:1604497] server: starting RwJLtZ5s_sJcUxQ5zha7Ng.rcLn1Q==
,2016-02-08 17:57:36.109 ThaliTest[919:1604497] multipeer session: start timer: 0x18c83c60
2016-02-08 17:57:36.109 ThaliTest[919:1604497] THEMultipeerSession initialized peer RwJLtZ5s_sJcUxQ5zha7Ng
2016-02-08 17:57:36.109 ThaliTest[919:1604497] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

,ok 120 deviceName should not be null

,2016-02-08 17:57:36.113 ThaliTest[919:1604240] client: found peer: 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:40.145 ThaliTest[919:1604240] client: found peer: jU_ckbs6yVKCZOTnccdusw.ol1x1Q==
,2016-02-08 17:57:40.168 ThaliTest[919:1604497] jxcore: connect 1454950645667.1482.mZpgYA==
2016-02-08 17:57:40.168 ThaliTest[919:1604497] client session: connect
2016-02-08 17:57:40.168 ThaliTest[919:1604497] client session: stateChange:0->1 1454950645667.1482.mZpgYA==
,2016-02-08 17:57:40.171 ThaliTest[919:1604497] jxcore: connect jU_ckbs6yVKCZOTnccdusw.ol1x1Q==
,2016-02-08 17:57:40.172 ThaliTest[919:1604497] client session: connect
2016-02-08 17:57:40.172 ThaliTest[919:1604497] client session: stateChange:0->1 jU_ckbs6yVKCZOTnccdusw.ol1x1Q==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-08 17:57:40.875 ThaliTest[919:1604240] multipeer session: reset timer
,2016-02-08 17:57:40.875 ThaliTest[919:1604240] multipeer session: stop timer
2016-02-08 17:57:40.875 ThaliTest[919:1604240] multipeer session: start timer: 0x18c83c60
,2016-02-08 17:57:40.876 ThaliTest[919:1604240] server session: connect
2016-02-08 17:57:40.876 ThaliTest[919:1604240] server session: stateChange:0->1 jU_ckbs6yVKCZOTnccdusw
,2016-02-08 17:57:40.883 ThaliTest[919:1604240] server: accepting invitation jU_ckbs6yVKCZOTnccdusw
,2016-02-08 17:57:43.375 ThaliTest[919:1605140] client session: connected
2016-02-08 17:57:43.375 ThaliTest[919:1605140] client session: stateChange:1->2 jU_ckbs6yVKCZOTnccdusw.ol1x1Q==
,2016-02-08 17:57:43.395 ThaliTest[919:1605295] client session: fireConnectCallback: jU_ckbs6yVKCZOTnccdusw.ol1x1Q==
2016-02-08 17:57:43.395 ThaliTest[919:1605295] jxcore: connect: success
,2016-02-08 17:57:43.408 ThaliTest[919:1604240] client: relay established
2016-02-08 17:57:43.409 ThaliTest[919:1604240] client: new accepted socket: 0x17f174e0
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

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,2016-02-08 17:57:46.396 ThaliTest[919:1605295] server session: connected
2016-02-08 17:57:46.397 ThaliTest[919:1605295] server session: stateChange:1->2 jU_ckbs6yVKCZOTnccdusw
,2016-02-08 17:57:46.712 ThaliTest[919:1604240] server relay: connected (to port: 54642)
,server bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

,client bridge: socket closed

,ok 123 1st change of remote doc should contain remote id
,
,client bridge: new client socket

,ok 124 Can update remote doc without error

null

,{ ok: true,
  id: 'ccf2adaa-d682-4b1e-bada-f96acd1ad7c5',
  rev: '2-114e53e2320d4edb8583d0bcd90a9720' }

,client bridge: new client socket

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

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
,
,client bridge: new client socket

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

,client bridge: new client socket

,2016-02-08 17:58:10.745 ThaliTest[919:1605068] client session: not connected jU_ckbs6yVKCZOTnccdusw.ol1x1Q==
2016-02-08 17:58:10.746 ThaliTest[919:1605068] client session: onLinkFailure: jU_ckbs6yVKCZOTnccdusw.ol1x1Q==
2016-02-08 17:58:10.746 ThaliTest[9,19:1605068] client session: disconnect
2016-02-08 17:58:10.746 ThaliTest[919:1605068] client session: stateChange:2->0 jU_ckbs6yVKCZOTnccdusw.ol1x1Q==
,2016-02-08 17:58:10.750 ThaliTest[919:1605068] client session: fireConnectionErrorEvent: jU_ckbs6yVKCZOTnccdusw.ol1x1Q==
,2016-02-08 17:58:11.110 ThaliTest[919:1605296] client session: not connected 1454950645667.1482.mZpgYA==
2016-02-08 17:58:11.111 ThaliTest[919:1605296] client session: onLinkFailure: 1454950645667.1482.mZpgYA==
2016-02-08 17:58:11.112 ThaliTest[919:16052,96] client session: disconnect
2016-02-08 17:58:11.112 ThaliTest[919:1605296] client session: stateChange:1->0 1454950645667.1482.mZpgYA==
2016-02-08 17:58:11.113 ThaliTest[919:1605296] client session: fireConnectCallback: 1454950645667.1482.mZpgYA==
,2016-02-08 17:58:11.113 ThaliTest[919:1605296] jxcore: connect: fail: Peer disconnected
,Connect error with error: Error: Peer disconnected

,2016-02-08 17:58:11.131 ThaliTest[919:1604497] jxcore: disconnect
,2016-02-08 17:58:11.131 ThaliTest[919:1604497] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

,2016-02-08 17:58:11.134 ThaliTest[919:1604497] jxcore: connect 1454950645667.1482.mZpgYA==
,2016-02-08 17:58:11.135 ThaliTest[919:1604497] client session: connect
,2016-02-08 17:58:11.136 ThaliTest[919:1604497] client session: stateChange:0->1 1454950645667.1482.mZpgYA==
,client bridge: socket closed

,2016-02-08 17:58:11.669 ThaliTest[919:1604497] Error!: stream.push() after EOF
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/n,ode_modules/readable-stream/lib/_stream_readable.js","_functionName":"readableAddChunk","_lineNumber":"187","_columnNumber":"15","_msg":"    at readableAddChunk@/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTes,t.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:187:15"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modu,les/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js","_functionName":"Readable.prototype.push","_lineNumber":"165","_columnNumber":"10","_msg":"    at Readable.prototype.push@/private/var/mobile/Containers/Bundle/Applicati,on/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:165:10"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169,-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Multiplex.prototype._send","_lineNumber":"197","_columnNumber":"13","_msg":"    at Multiplex.prototype._send@/private/var/mobile/Containers/Bundle/A,pplication/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:197:13"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxco,re/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Channel.prototype._open","_lineNumber":"109","_columnNumber":"3","_msg":"    at Channel.prototype._open@/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F,17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:109:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multipl,ex/index.js","_functionName":"Channel.prototype.open","_lineNumber":"117","_columnNumber":"38","_msg":"    at Channel.prototype.open@/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_module,s/thali/node_modules/multiplex/index.js:117:38"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js","_functionName":"Multiplex.pr,ototype._addChannel","_lineNumber":"215","_columnNumber":"3","_msg":"    at Multiplex.prototype._addChannel@/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/mult,iplex/index.js:215:3"}]
Uncaught Exception: Error: stream.push() after EOF

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js',
    _functionName: 'readableAd,dChunk',
    _lineNumber: '187',
    _columnNumber: '15',
    _msg: '    at readableAddChunk@/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_m,odules/readable-stream/lib/_stream_readable.js:187:15' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-strea,m/lib/_stream_readable.js',
    _functionName: 'Readable.prototype.push',
    _lineNumber: '165',
    _columnNumber: '10',
    _msg: '    at Readable.prototype.push@/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/,ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/node_modules/readable-stream/lib/_stream_readable.js:165:10' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxc,ore/node_modules/thali/node_modules/multiplex/index.js',
    _functionName: 'Multiplex.prototype._send',
    _lineNumber: '197',
    _columnNumber: '13',
    _msg: '    at Multiplex.prototype._send@/private/var/mobile/Containers/Bundle/Application/1630,6D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:197:13' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_mo,dules/thali/node_modules/multiplex/index.js',
    _functionName: 'Channel.prototype._open',
    _lineNumber: '109',
    _columnNumber: '3',
    _msg: '    at Channel.prototype._open@/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9,169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:109:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_,modules/multiplex/index.js',
    _functionName: 'Channel.prototype.open',
    _lineNumber: '117',
    _columnNumber: '38',
    _msg: '    at Channel.prototype.open@/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/T,haliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:117:38' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/ThaliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex,/index.js',
    _functionName: 'Multiplex.prototype._addChannel',
    _lineNumber: '215',
    _columnNumber: '3',
    _msg: '    at Multiplex.prototype._addChannel@/private/var/mobile/Containers/Bundle/Application/16306D9B-4755-46F1-9169-F1F42F17A21A/T,haliTest.app/www/jxcore/node_modules/thali/node_modules/multiplex/index.js:215:3' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

Error: stream.push() after EOF (/private/var/mobile/Containers/Bund
```
