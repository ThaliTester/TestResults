#### Test 583805004f2b042_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/583805004f2b042/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/8EDC4DC4-4CF6-46A4-8E11-8696C3DAF06A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8EDC4DC4-4CF6-46A4-8E11-8696C3DAF06A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/583805004f2b042/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/583805004f2b042/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53704"
,(lldb)     command script import "/tmp/8EDC4DC4-4CF6-46A4-8E11-8696C3DAF06A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 17:34:51.823 ThaliTest[1160:1788737] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D644989E-4375-48D4-81CC-4360F92468FF/Library/Cookies/Cookies.binarycookies
,2016-02-09 17:34:52.200 ThaliTest[1160:1788737] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 17:34:52.201 ThaliTest[1160:1788737] Multi-tasking -> Device: YES, App: YES
,2016-02-09 17:34:52.210 ThaliTest[1160:1788737] Unlimited access to network resources
,2016-02-09 17:34:52.219 ThaliTest[1160:1788737] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 17:35:02.271 ThaliTest[1160:1788737] Resetting plugins due to page load.
,2016-02-09 17:35:06.009 ThaliTest[1160:1788737] Finished load of: file:///var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/index.html
,2016-02-09 17:35:06.166 ThaliTest[1160:1788737] JXcore Cordova plugin initializing
,2016-02-09 17:35:06.167 ThaliTest[1160:1788986] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88966876-5789-4E6C-9B8B-03652506BF03/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# #generatePreambleAndBeacons null ECDH for local device

,ok 1 publicKeysToNotify cannot be null

# teardown

,# setup

,# #generatePreambleAndBeacons null ECDH for local device

,ok 2 ecdhForLocalDevice cannot be null

# teardown

# setup

# #generatePreambleAndBeacons expiration out of range lower

,ok 3 secondsUntilExpiration out of range.

# teardown

,# setup

,# #generatePreambleAndBeacons expiration out of range upper

,ok 4 secondsUntilExpiration out of range.

# teardown

# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 5 should be equal

,# teardown

# setup

,# #generatePreambleAndBeacons multiple keys to notify

,ok 6 should be equal

,ok 7 should be equal

,ok 8 should be equal

ok 9 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 10 should throw

# teardown

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 11 Preamble expiration must be a 64 bit integer

# teardown

# setup

,# #parseBeacons expiration out of range lower

,ok 12 Expiration out of range

# teardown

,# setup

# #parseBeacons expiration out of range lower
,
,ok 13 Expiration out of range

# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 14 should be equal

# teardown

# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 15 Malformed encrypted beacon key ID

# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 16 should be equal

# teardown

,# setup

# #parseBeacons addressBookCallback returns no matches

,ok 17 should be equal

ok 18 should be equal

,# teardown

# setup

,# #parseBeacons addressBookCallback returns public key

,ok 19 should be equal

,ok 20 (unnamed assert)

# teardown

# setup

,# #parseBeacons with beacons both for and not for the user

,ok 21 (unnamed assert)

# teardown

,# setup

,# multiplex can send data

,ok 22 String should be length:200

,# teardown

,# setup

,# enqueue and run in order

,ok 23 firstPromise setTimeout

,ok 24 firstPromise result

,ok 25 firstPromise testValue

,ok 26 secondPromise setTimeout

,ok 27 secondPromise result

,ok 28 secondPromise testValue

,ok 29 thirdPromise in promise

,ok 30 thirdPromise result

,ok 31 thirdPromise testValue

,# teardown

,# setup

,# basic

,ok 32 sane

,# teardown

,# setup

,# another

,ok 33 sane

,# teardown

,# setup

,# successfully create a new pkcs12 file and return hash value

,ok 34 should be equal

,ok 35 null

,ok 36 (unnamed assert)

,ok 37 should be equal

,ok 38 should not throw

,# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 39 (unnamed assert)

,ok 40 (unnamed assert)

,ok 41 should not throw

,ok 42 should be equal

ok 43 should be equal

,# teardown

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,ok 44 should be equal

,# teardown

,# setup

,# failed to get mobile documents path

,ok 45 should be equal

,# teardown

,# setup

,# #init should register the peerAvailabilityChanged event

,ok 46 should be equal

,ok 47 should be equal

,ok 48 should be equal

,# teardown

,# setup

,# #init should register the networkChanged event

,ok 49 should be equal

,# teardown

,# setup

,# #startBroadcasting should throw on null device name

,ok 50 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on empty string device name

,ok 51 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on non-number port

,ok 52 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on NaN port

,ok 53 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on negative port

,ok 54 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on too large port

,ok 55 should throw

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,ok 56 should be equal

,ok 57 should be equal

,ok 58 should be equal

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ok 59 should be equal

,ok 60 should be equal

,ok 61 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ok 62 should be equal

,ok 63 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ok 64 should be equal

,ok 65 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,ok 66 should be equal

,ok 67 should be equal

,ok 68 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") and handle an error

,ok 69 should be equal

,ok 70 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") without an error

,ok 71 should be equal

,ok 72 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") and handle an error

,ok 73 should be equal

,ok 74 should be equal

,# teardown

,# setup

,# #start should fail if called twice in a row

,ok 75 specific error should be received

,# teardown

,# setup

,# #startListeningForAdvertisements should fail if start not called

,ok 76 specific error should be returned

,# teardown

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,ok 77 error should be null

,ok 78 error should be null

,# teardown

,# setup

,# should be able to call #startListeningForAdvertisements many times

,ok 79 error should be null

,ok 80 error should be null

,# teardown

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,ok 81 error should be null

,ok 82 error should be null

,# teardown

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,ok 83 specific error should be returned

,# teardown

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,2016-02-09 17:39:17.722 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:17.739 ThaliTest[1160:1788986] server: starting 1455035957722.1160.auh54Q==
,2016-02-09 17:39:17.740 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a05fdb0
2016-02-09 17:39:17.741 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035957722.1160
,2016-02-09 17:39:17.741 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
ok 84 Should be able to call startBroadcasting without error

2016-02-09 17:39:17.746 ThaliTest[1160:1788986] jxcore: stopBroadcasting
2016-02-09 17:39:17.746 ThaliTest[,1160:1788986] THEMultipeerSession stopping peer
2016-02-09 17:39:17.746 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:17.747 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

2016-02-09 17:39:17.752 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:17.755 ThaliTest[1160:1788986] server: starting 1455035957751.1160.q1iPMw==
2016-02-09 17:39:17.756 ThaliTest[1160:1788986] multipeer session: start timer: 0x177f7050
2016-02-09 17:39:17.757 ThaliTest[1160:1788986] THEMultipeerSession in,itialized peer 1455035957751.1160
2016-02-09 17:39:17.757 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

2016-02-09 17:39:17.759 ThaliTest[1160:1788986] jxcore: stopBroadcasting,
2016-02-09 17:39:17.759 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
2016-02-09 17:39:17.759 ThaliTest[1160:1788986] multipeer session: stop timer
2016-02-09 17:39:17.760 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
ok 87 Shou,ld be able to call stopBroadcasting without error

2016-02-09 17:39:17.762 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:17.766 ThaliTest[1160:1788986] server: starting 1455035957761.1160.vP77Wg==
2016-02-09 17:39:17.767 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a76dc20
2016-02-09 17:39:17.768 ThaliTest[1160:1788986] THEMultipeerSession in,itialized peer 1455035957761.1160
2016-02-09 17:39:17.769 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error

2016-02-09 17:39:17.771 ThaliTest[1160:1788986] jxcore: stopBroadcasting,
2016-02-09 17:39:17.772 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
2016-02-09 17:39:17.772 ThaliTest[1160:1788986] multipeer session: stop timer
2016-02-09 17:39:17.772 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
,ok 89 Should be able to call stopBroadcasting without error

,2016-02-09 17:39:17.774 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:17.779 ThaliTest[1160:1788986] server: starting 1455035957773.1160.Jh8hcg==
2016-02-09 17:39:17.780 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a077dd0
2016-02-09 17:39:17.781 ThaliTest[1160:1788986] THEMultipeerSession in,itialized peer 1455035957773.1160
2016-02-09 17:39:17.781 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
ok 90 Should be able to call startBroadcasting without error

,2016-02-09 17:39:17.785 ThaliTest[1160:1788986] jxcore: stopBroadcasting
2016-02-09 17:39:17.785 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
2016-02-09 17:39:17.785 ThaliTest[1160:1788986] multipeer session: stop timer
2016-02-09 17:39:17.,785 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
ok 91 Should be able to call stopBroadcasting without error

2016-02-09 17:39:17.787 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:17.793 ThaliTest[1160:1788986] server: starting 1455035957787.1160.3LuWew==
2016-02-09 17:39:17.794 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a079be0
2016-02-09 17:39:17.794 ThaliTest[1160:1788986] THEMultipeerSession in,itialized peer 1455035957787.1160
2016-02-09 17:39:17.795 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

2016-02-09 17:39:17.797 ThaliTest[1160:1788986] jxcore: stopBroadcasting
,2016-02-09 17:39:17.798 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
2016-02-09 17:39:17.803 ThaliTest[1160:1788986] multipeer session: stop timer
2016-02-09 17:39:17.803 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
ok 93 Shoul,d be able to call stopBroadcasting without error

2016-02-09 17:39:17.805 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:17.809 ThaliTest[1160:1788986] server: starting 1455035957804.1160.7zZDyA==
,2016-02-09 17:39:17.810 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a76e430
,2016-02-09 17:39:17.811 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035957804.1160
2016-02-09 17:39:17.811 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
,ok 94 Should be able to call startBroadcasting without error

,2016-02-09 17:39:17.819 ThaliTest[1160:1788986] jxcore: stopBroadcasting
,2016-02-09 17:39:17.820 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
,2016-02-09 17:39:17.821 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:17.822 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
,ok 95 Should be able to call stopBroadcasting without error

,2016-02-09 17:39:17.825 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:17.828 ThaliTest[1160:1788986] server: starting 1455035957825.1160.MgenEA==
,2016-02-09 17:39:17.829 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a76e740
,2016-02-09 17:39:17.832 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035957825.1160
,2016-02-09 17:39:17.833 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
,ok 96 Should be able to call startBroadcasting without error
,
,2016-02-09 17:39:17.836 ThaliTest[1160:1788986] jxcore: stopBroadcasting
,2016-02-09 17:39:17.837 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
,2016-02-09 17:39:17.838 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:17.840 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
,ok 97 Should be able to call stopBroadcasting without error

,2016-02-09 17:39:17.843 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:17.845 ThaliTest[1160:1788986] server: starting 1455035957842.1160.wd3RFw==
,2016-02-09 17:39:17.846 ThaliTest[1160:1788986] multipeer session: start timer: 0x177f73e0
,2016-02-09 17:39:17.848 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035957842.1160
,2016-02-09 17:39:17.850 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
,ok 98 Should be able to call startBroadcasting without error

,2016-02-09 17:39:17.853 ThaliTest[1160:1788986] jxcore: stopBroadcasting
2016-02-09 17:39:17.853 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
2016-02-09 17:39:17.853 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:17.855 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
,ok 99 Should be able to call stopBroadcasting without error

,2016-02-09 17:39:17.858 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:17.861 ThaliTest[1160:1788986] server: starting 1455035957858.1160.PsIlMA==
,2016-02-09 17:39:17.862 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a6e84f0
,2016-02-09 17:39:17.865 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035957858.1160
,2016-02-09 17:39:17.866 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
,ok 100 Should be able to call startBroadcasting without error
,
,2016-02-09 17:39:17.869 ThaliTest[1160:1788986] jxcore: stopBroadcasting
,2016-02-09 17:39:17.869 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
,2016-02-09 17:39:17.870 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:17.874 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
,ok 101 Should be able to call stopBroadcasting without error

,2016-02-09 17:39:17.876 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:17.879 ThaliTest[1160:1788986] server: starting 1455035957876.1160.N4CflQ==
,2016-02-09 17:39:17.880 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a077f00
,2016-02-09 17:39:17.882 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035957876.1160
,2016-02-09 17:39:17.883 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
,ok 102 Should be able to call startBroadcasting without error

,2016-02-09 17:39:17.886 ThaliTest[1160:1788986] jxcore: stopBroadcasting
,2016-02-09 17:39:17.887 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
,2016-02-09 17:39:17.888 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:17.890 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
,ok 103 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-09 17:39:18.200 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:18.203 ThaliTest[1160:1788986] server: starting 1455035958199.1160.88Ag1Q==
,2016-02-09 17:39:18.204 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a7720b0
2016-02-09 17:39:18.204 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035958199.1160
2016-02-09 17:39:18.205 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
,ok 104 Should be able to call startBroadcasting without error

,2016-02-09 17:39:18.207 ThaliTest[1160:1788986] jxcore: startBroadcasting
2016-02-09 17:39:18.208 ThaliTest[1160:1788986] jxcore: startBroadcasting: failure
ok 105 Cannot call startBroadcasting twice

2016-02-09 17:39:18.212 ThaliTest[1160:1788986] jxc,ore: stopBroadcasting
2016-02-09 17:39:18.212 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
2016-02-09 17:39:18.212 ThaliTest[1160:1788986] multipeer session: stop timer
2016-02-09 17:39:18.213 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
ok 106 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-09 17:39:27.636 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:27.639 ThaliTest[1160:1788986] server: starting 1455035967635.1160.ZHw7QQ==
,2016-02-09 17:39:27.640 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a077190
2016-02-09 17:39:27.641 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035967635.1160
,2016-02-09 17:39:27.641 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
ok 107 Should be able to call startBroadcasting without error

,2016-02-09 17:39:27.644 ThaliTest[1160:1788986] jxcore: connect foobar
2016-02-09 17:39:27.645 ThaliTest[1160:1788986] client: unknown peer foobar
2016-02-09 17:39:27.645 ThaliTest[1160:1788986] jxcore: connect: fail: Unknown peer
ok 108 Should not connect to a bad peer

,2016-02-09 17:39:27.649 ThaliTest[1160:1788986] jxcore: stopBroadcasting
2016-02-09 17:39:27.650 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
2016-02-09 17:39:27.650 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:27.652 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
ok 109 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-09 17:39:30.838 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:30.842 ThaliTest[1160:1788986] server: starting 1455035970838.1160.sgi4Gg==
,2016-02-09 17:39:30.842 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a6ecfa0
2016-02-09 17:39:30.843 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035970838.1160
2016-02-09 17:39:30.844 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
,ok 110 Should be able to call startBroadcasting without error

,2016-02-09 17:39:30.851 ThaliTest[1160:1788986] jxcore: disconnect
,2016-02-09 17:39:30.853 ThaliTest[1160:1788986] jxcore: disconnect: fail
,ok 111 Disconnect should fail to a non-existant peer 

,2016-02-09 17:39:30.858 ThaliTest[1160:1788986] jxcore: stopBroadcasting
,2016-02-09 17:39:30.859 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
,2016-02-09 17:39:30.860 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:30.863 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
,ok 112 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-09 17:39:35.314 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:35.318 ThaliTest[1160:1788986] server: starting 1455035975314.1160.ssJGLg==
,2016-02-09 17:39:35.319 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a77ae70
2016-02-09 17:39:35.320 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035975314.1160
,2016-02-09 17:39:35.321 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
,ok 113 Should be able to call startBroadcasting without error

,2016-02-09 17:39:36.496 ThaliTest[1160:1788737] client: found peer: 1455035972720.1699.u2Muug==
,2016-02-09 17:39:36.499 ThaliTest[1160:1788986] jxcore: connect 1455035972720.1699.u2Muug==
,2016-02-09 17:39:36.500 ThaliTest[1160:1788986] client session: connect
2016-02-09 17:39:36.501 ThaliTest[1160:1788986] client session: stateChange:0->1 1455035972720.1699.u2Muug==
,2016-02-09 17:39:37.115 ThaliTest[1160:1788737] multipeer session: reset timer
2016-02-09 17:39:37.116 ThaliTest[1160:1788737] multipeer session: stop timer
,2016-02-09 17:39:37.116 ThaliTest[1160:1788737] multipeer session: start timer: 0x1a77ae70
,2016-02-09 17:39:37.116 ThaliTest[1160:1788737] server session: connect
,2016-02-09 17:39:37.117 ThaliTest[1160:1788737] server session: stateChange:0->1 1455035972720.1699
,2016-02-09 17:39:37.123 ThaliTest[1160:1788737] server: accepting invitation 1455035972720.1699
,2016-02-09 17:39:39.206 ThaliTest[1160:1789469] client session: connected
2016-02-09 17:39:39.206 ThaliTest[1160:1789469] client session: stateChange:1->2 1455035972720.1699.u2Muug==
,2016-02-09 17:39:39.212 ThaliTest[1160:1789469] client session: fireConnectCallback: 1455035972720.1699.u2Muug==
2016-02-09 17:39:39.212 ThaliTest[1160:1789469] jxcore: connect: success
,ok 114 Should be able to connect without error

,ok 115 Port should be within range

,2016-02-09 17:39:39.218 ThaliTest[1160:1788986] jxcore: disconnect
,2016-02-09 17:39:39.219 ThaliTest[1160:1788986] client session: disconnectFromPeer: 1455035972720.1699.u2Muug==
,2016-02-09 17:39:39.219 ThaliTest[1160:1788986] client session: disconnect
,2016-02-09 17:39:39.220 ThaliTest[1160:1788986] client session: stateChange:2->0 1455035972720.1699.u2Muug==
,2016-02-09 17:39:39.294 ThaliTest[1160:1788986] jxcore: disconnect: success
,ok 116 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-09 17:39:40.280 ThaliTest[1160:1789470] server session: connected
2016-02-09 17:39:40.280 ThaliTest[1160:1789470] server session: stateChange:1->2 1455035972720.1699
,2016-02-09 17:39:40.286 ThaliTest[1160:1788737] server relay: socket disconnected
,2016-02-09 17:39:40.287 ThaliTest[1160:1788737] server relay: 0x1a7815f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-02-09 17:39:40.341 ThaliTest[1160:1789470] server session: not connected 1455035972720.1699
,calling stopBroadcasting

,2016-02-09 17:39:40.475 ThaliTest[1160:1788986] jxcore: stopBroadcasting
,2016-02-09 17:39:40.476 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
,2016-02-09 17:39:40.477 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:40.478 ThaliTest[1160:1788986] server session: disconnect
2016-02-09 17:39:40.479 ThaliTest[1160:1788986] server session: stateChange:2->0 1455035972720.1699
,2016-02-09 17:39:40.783 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-09 17:39:42.338 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:42.341 ThaliTest[1160:1788986] server: starting 1455035982337.1160.xnLe7Q==
,2016-02-09 17:39:42.342 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a6f6c30
2016-02-09 17:39:42.343 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035982337.1160
2016-02-09 17:39:42.344 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
,ok 117 Should be able to call startBroadcasting without error

,2016-02-09 17:39:42.355 ThaliTest[1160:1788737] client: found peer: 1455035972720.1699.u2Muug==
,2016-02-09 17:39:42.357 ThaliTest[1160:1788986] jxcore: connect 1455035972720.1699.u2Muug==
2016-02-09 17:39:42.357 ThaliTest[1160:1788986] client session: connect
2016-02-09 17:39:42.358 ThaliTest[1160:1788986] client session: stateChange:0->1 145503597,2720.1699.u2Muug==
,2016-02-09 17:39:43.248 ThaliTest[1160:1788737] client: found peer: 1455035980192.1699.WaSZTQ==
,2016-02-09 17:39:43.250 ThaliTest[1160:1788986] jxcore: connect 1455035980192.1699.WaSZTQ==
2016-02-09 17:39:43.250 ThaliTest[1160:1788986] client session: connect
,2016-02-09 17:39:43.251 ThaliTest[1160:1788986] client session: stateChange:0->1 1455035980192.1699.WaSZTQ==
,2016-02-09 17:39:43.496 ThaliTest[1160:1788737] multipeer session: reset timer
,2016-02-09 17:39:43.496 ThaliTest[1160:1788737] multipeer session: stop timer
,2016-02-09 17:39:43.497 ThaliTest[1160:1788737] multipeer session: start timer: 0x1a6f6c30
,2016-02-09 17:39:43.497 ThaliTest[1160:1788737] server session: connect
,2016-02-09 17:39:43.498 ThaliTest[1160:1788737] server session: stateChange:0->1 1455035980192.1699
,2016-02-09 17:39:43.505 ThaliTest[1160:1788737] server: accepting invitation 1455035980192.1699
,2016-02-09 17:39:45.861 ThaliTest[1160:1789513] client session: connected
2016-02-09 17:39:45.861 ThaliTest[1160:1789513] client session: stateChange:1->2 1455035980192.1699.WaSZTQ==
,2016-02-09 17:39:45.891 ThaliTest[1160:1789513] client session: fireConnectCallback: 1455035980192.1699.WaSZTQ==
2016-02-09 17:39:45.891 ThaliTest[1160:1789513] jxcore: connect: success
,ok 118 Should be able to connect without error

,ok 119 Port should be within range

,2016-02-09 17:39:45.896 ThaliTest[1160:1788986] jxcore: connect 1455035980192.1699.WaSZTQ==
,2016-02-09 17:39:45.896 ThaliTest[1160:1788986] client: already connect(ing/ed) to 1455035980192.1699.WaSZTQ==
,2016-02-09 17:39:45.897 ThaliTest[1160:1788986] jxcore: connect: fail: Aleady connecting
,ok 120 Should fail on double connect

,2016-02-09 17:39:45.901 ThaliTest[1160:1788986] jxcore: disconnect
,2016-02-09 17:39:45.901 ThaliTest[1160:1788986] client session: disconnectFromPeer: 1455035980192.1699.WaSZTQ==
2016-02-09 17:39:45.902 ThaliTest[1160:1788986] client session: disconnect
,2016-02-09 17:39:45.903 ThaliTest[1160:1788986] client session: stateChange:2->0 1455035980192.1699.WaSZTQ==
,2016-02-09 17:39:45.911 ThaliTest[1160:1788986] jxcore: disconnect: success
ok 121 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-09 17:39:46.094 ThaliTest[1160:1789513] server session: connected
2016-02-09 17:39:46.095 ThaliTest[1160:1789513] server session: stateChange:1->2 1455035980192.1699
,2016-02-09 17:39:46.112 ThaliTest[1160:1788737] server relay: socket disconnected
,2016-02-09 17:39:46.113 ThaliTest[1160:1788737] server relay: 0x1a6f7450 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 17:39:46.157 ThaliTest[1160:1789471] server session: not connected 1455035980192.1699
,calling stopBroadcasting

,2016-02-09 17:39:46.244 ThaliTest[1160:1788986] jxcore: stopBroadcasting
,2016-02-09 17:39:46.245 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
2016-02-09 17:39:46.245 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:46.246 ThaliTest[1160:1788986] client session: disconnect
,2016-02-09 17:39:46.246 ThaliTest[1160:1788986] client session: stateChange:1->0 1455035972720.1699.u2Muug==
,2016-02-09 17:39:46.249 ThaliTest[1160:1788986] server session: disconnect
2016-02-09 17:39:46.250 ThaliTest[1160:1788986] server session: stateChange:2->0 1455035980192.1699
,2016-02-09 17:39:46.563 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-09 17:39:46.779 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:46.784 ThaliTest[1160:1788986] server: starting 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:46.787 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a784b10
,2016-02-09 17:39:46.793 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035986775.1160
,2016-02-09 17:39:46.800 ThaliTest[1160:1788986] jxcore: startBroadcasting: success
,ok 122 Should be able to call startBroadcasting without error

,2016-02-09 17:39:47.468 ThaliTest[1160:1788737] client: found peer: 1455035980192.1699.WaSZTQ==
,2016-02-09 17:39:47.470 ThaliTest[1160:1788986] jxcore: connect 1455035980192.1699.WaSZTQ==
2016-02-09 17:39:47.470 ThaliTest[1160:1788986] client session: connect
2016-02-09 17:39:47.470 ThaliTest[1160:1788986] client session: stateChange:0->1 145503598,0192.1699.WaSZTQ==
,2016-02-09 17:39:47.875 ThaliTest[1160:1788737] client: found peer: 1455035985077.1699.X332/g==
,2016-02-09 17:39:47.877 ThaliTest[1160:1788986] jxcore: connect 1455035985077.1699.X332/g==
2016-02-09 17:39:47.878 ThaliTest[1160:1788986] client session: connect
2016-02-09 17:39:47.878 ThaliTest[1160:1788986] client session: stateChange:0->1 1455035985077.1699.X332/g==
,2016-02-09 17:39:47.969 ThaliTest[1160:1788737] multipeer session: reset timer
,2016-02-09 17:39:47.970 ThaliTest[1160:1788737] multipeer session: stop timer
,2016-02-09 17:39:47.970 ThaliTest[1160:1788737] multipeer session: start timer: 0x1a784b10
2016-02-09 17:39:47.970 ThaliTest[1160:1788737] server session: connect
,2016-02-09 17:39:47.971 ThaliTest[1160:1788737] server session: stateChange:0->1 1455035985077.1699
,2016-02-09 17:39:47.977 ThaliTest[1160:1788737] server: accepting invitation 1455035985077.1699
,2016-02-09 17:39:50.424 ThaliTest[1160:1789510] server session: connected
2016-02-09 17:39:50.424 ThaliTest[1160:1789510] server session: stateChange:1->2 1455035985077.1699
,2016-02-09 17:39:50.432 ThaliTest[1160:1788737] server relay: socket disconnected
2016-02-09 17:39:50.432 ThaliTest[1160:1788737] server relay: 0x1a0d6680 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 17:39:50.436 ThaliTest[1160:1789510] client session: connected
2016-02-09 17:39:50.437 ThaliTest[1160:1789510] client session: stateChange:1->2 1455035985077.1699.X332/g==
,2016-02-09 17:39:50.443 ThaliTest[1160:1789513] client session: fireConnectCallback: 1455035985077.1699.X332/g==
2016-02-09 17:39:50.443 ThaliTest[1160:1789513] jxcore: connect: success
,ok 123 Should be able to connect without error

,ok 124 Port should be within range

,2016-02-09 17:39:50.447 ThaliTest[1160:1788986] jxcore: disconnect
,2016-02-09 17:39:50.447 ThaliTest[1160:1788986] client session: disconnectFromPeer: 1455035985077.1699.X332/g==
,2016-02-09 17:39:50.448 ThaliTest[1160:1788986] client session: disconnect
,2016-02-09 17:39:50.448 ThaliTest[1160:1788986] client session: stateChange:2->0 1455035985077.1699.X332/g==
,2016-02-09 17:39:50.458 ThaliTest[1160:1788986] jxcore: disconnect: success
ok 125 Should be able to disconnect without error

,2016-02-09 17:39:50.461 ThaliTest[1160:1788986] jxcore: disconnect
,2016-02-09 17:39:50.463 ThaliTest[1160:1788986] jxcore: disconnect: fail
,ok 126 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-09 17:39:50.520 ThaliTest[1160:1789470] server session: not connected 1455035985077.1699
,calling stopBroadcasting

,2016-02-09 17:39:50.906 ThaliTest[1160:1788986] jxcore: stopBroadcasting
,2016-02-09 17:39:50.906 ThaliTest[1160:1788986] THEMultipeerSession stopping peer
,2016-02-09 17:39:50.906 ThaliTest[1160:1788986] multipeer session: stop timer
,2016-02-09 17:39:50.907 ThaliTest[1160:1788986] client session: disconnect
,2016-02-09 17:39:50.907 ThaliTest[1160:1788986] client session: stateChange:1->0 1455035980192.1699.WaSZTQ==
,2016-02-09 17:39:50.909 ThaliTest[1160:1788986] server session: disconnect
2016-02-09 17:39:50.909 ThaliTest[1160:1788986] server session: stateChange:2->0 1455035985077.1699
,2016-02-09 17:39:50.912 ThaliTest[1160:1788986] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 56706

,2016-02-09 17:39:51.992 ThaliTest[1160:1788986] jxcore: startBroadcasting
,2016-02-09 17:39:51.994 ThaliTest[1160:1788986] server: starting 1455035991992.1160.dYOKkQ==
,2016-02-09 17:39:51.994 ThaliTest[1160:1788986] multipeer session: start timer: 0x1a771de0
2016-02-09 17:39:51.994 ThaliTest[1160:1788986] THEMultipeerSession initialized peer 1455035991992.1160
2016-02-09 17:39:51.994 ThaliTest[1160:1788986] jxcore: sta,rtBroadcasting: success
,ok 127 Should be able to call startBroadcasting without error

,2016-02-09 17:39:51.998 ThaliTest[1160:1788737] client: found peer: 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:51.999 ThaliTest[1160:1788737] client: found peer: 1455035985077.1699.X332/g==
,2016-02-09 17:39:52.000 ThaliTest[1160:1788986] jxcore: connect 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:52.000 ThaliTest[1160:1788986] client session: connect
,2016-02-09 17:39:52.000 ThaliTest[1160:1788986] client session: stateChange:0->1 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:52.004 ThaliTest[1160:1788986] jxcore: connect 1455035985077.1699.X332/g==
,2016-02-09 17:39:52.005 ThaliTest[1160:1788986] client session: connect
,2016-02-09 17:39:52.005 ThaliTest[1160:1788986] client session: stateChange:0->1 1455035985077.1699.X332/g==
,2016-02-09 17:39:53.384 ThaliTest[1160:1788737] client: lost peer: 1455035986775.1160.2Cwjhw==
2016-02-09 17:39:53.384 ThaliTest[1160:1788737] client session: onPeerLost: 1455035986775.1160.2Cwjhw==
2016-02-09 17:39:53.384 ThaliTest[1160:1788737] client ,session: onLinkFailure: 1455035986775.1160.2Cwjhw==
2016-02-09 17:39:53.385 ThaliTest[1160:1788737] client session: disconnect
2016-02-09 17:39:53.385 ThaliTest[1160:1788737] client session: stateChange:1->0 1455035986775.1160.2Cwjhw==
2016-02-09 17:39:53.386 ThaliTest[1160:1788737] client session: fireConnectCallback: 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:53.386 ThaliTest[1160:1788737] jxcore: connect: fail: Peer disconnected
,2016-02-09 17:39:54.160 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:39:54.162 ThaliTest[1160:1788986] jxcore: connect 1455035990350.1699.a0DoHA==
2016-02-09 17:39:54.162 ThaliTest[1160:1788986] client session: connect
2016-02-09 17:39:54.162 ThaliTest[1160:1788986] client session: stateChange:0->1 1455035990350.1699.a0DoHA==
,2016-02-09 17:39:54.392 ThaliTest[1160:1788986] jxcore: connect 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:54.393 ThaliTest[1160:1788986] client: connect: unreachable 1455035986775.1160.2Cwjhw==
,2016-02-09 17:39:54.394 ThaliTest[1160:1788986] jxcore: connect: fail: Peer unreachable
,2016-02-09 17:39:54.894 ThaliTest[1160:1788737] multipeer session: reset timer
2016-02-09 17:39:54.894 ThaliTest[1160:1788737] multipeer session: stop timer
,2016-02-09 17:39:54.894 ThaliTest[1160:1788737] multipeer session: start timer: 0x1a771de0
2016-02-09 17:39:54.895 ThaliTest[1160:1788737] server session: connect
,2016-02-09 17:39:54.896 ThaliTest[1160:1788737] server session: stateChange:0->1 1455035990350.1699
,2016-02-09 17:39:54.902 ThaliTest[1160:1788737] server: accepting invitation 1455035990350.1699
,2016-02-09 17:40:01.430 ThaliTest[1160:1789510] client session: connected
2016-02-09 17:40:01.431 ThaliTest[1160:1789510] client session: stateChange:1->2 1455035990350.1699.a0DoHA==
,2016-02-09 17:40:01.434 ThaliTest[1160:1789510] client session: fireConnectCallback: 1455035990350.1699.a0DoHA==
2016-02-09 17:40:01.435 ThaliTest[1160:1789510] jxcore: connect: success
,ok 128 Should be able to connect without error

,ok 129 Port should be within range

,2016-02-09 17:40:01.441 ThaliTest[1160:1788737] client: relay established
2016-02-09 17:40:01.442 ThaliTest[1160:1788737] client: new accepted socket: 0x1a76f150
,2016-02-09 17:40:02.609 ThaliTest[1160:1789510] server session: connected
2016-02-09 17:40:02.609 ThaliTest[1160:1789510] server session: stateChange:1->2 1455035990350.1699
,2016-02-09 17:40:04.294 ThaliTest[1160:1788737] server relay: connected (to port: 56706)
2016-02-09 17:40:04.295 ThaliTest[1160:1788737] client: lost peer: 1455035985077.1699.X332/g==
2016-02-09 17:40:04.296 ThaliTest[1160:1788737] client session: onPeerLost: 1455035985077.1699.X332/g==
2016-02-09 17:40:04.296 ThaliTest[1160:1788737] client session: onLinkFailure: 1455035985077.1699.X332/g==
,2016-02-09 17:40:04.296 ThaliTest[1160:1788737] client session: disconnect
2016-02-09 17:40:04.296 ThaliTest[1160:1788737] client session: stateChange:1->0 1455035985077.1699.X332/g==
,2016-02-09 17:40:04.301 ThaliTest[1160:1788737] client session: fireConnectCallback: 1455035985077.1699.X332/g==
2016-02-09 17:40:04.301 ThaliTest[1160:1788737] jxcore: connect: fail: Peer disconnected
,2016-02-09 17:40:05.316 ThaliTest[1160:1788986] jxcore: connect 1455035985077.1699.X332/g==
,2016-02-09 17:40:05.317 ThaliTest[1160:1788986] client: connect: unreachable 1455035985077.1699.X332/g==
2016-02-09 17:40:05.317 ThaliTest[1160:1788986] jxcore: connect: fail: Peer unreachable
,2016-02-09 17:40:19.477 ThaliTest[1160:1789687] client session: not connected 1455035990350.1699.a0DoHA==
2016-02-09 17:40:19.478 ThaliTest[1160:1789687] client session: onLinkFailure: 1455035990350.1699.a0DoHA==
2016-02-09 17:40:19.478 ThaliTest[1160:17,89687] client session: disconnect
2016-02-09 17:40:19.478 ThaliTest[1160:1789687] client session: stateChange:2->0 1455035990350.1699.a0DoHA==
,2016-02-09 17:40:19.481 ThaliTest[1160:1789687] client session: fireConnectionErrorEvent: 1455035990350.1699.a0DoHA==
,2016-02-09 17:40:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:40:24.920 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:40:48.998 ThaliTest[1160:1789687] server session: not connected 1455035990350.1699
,2016-02-09 17:40:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:40:54.922 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:41:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:41:24.922 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:41:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:41:54.922 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:42:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:42:24.922 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:42:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:42:54.923 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:43:24.895 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:43:24.920 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:43:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:44:24.895 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:44:24.921 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:44:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:44:54.922 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:45:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:45:24.921 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:45:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:45:54.921 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:46:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:46:24.923 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:46:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:46:54.920 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:47:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:47:24.921 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:47:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:47:54.924 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:48:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:48:24.920 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:48:54.895 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:48:54.922 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:49:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:49:24.920 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:49:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:49:54.921 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:50:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:50:24.920 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:50:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:50:54.923 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:51:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:51:24.922 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:51:54.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:51:54.921 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==
,2016-02-09 17:52:24.896 ThaliTest[1160:1788737] multipeer session: restart
,2016-02-09 17:52:24.922 ThaliTest[1160:1788737] client: found peer: 1455035990350.1699.a0DoHA==

```
