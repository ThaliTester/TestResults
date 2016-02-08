#### Test 58380500962e22b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500962e22b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/BB2B1200-668E-4A4D-ACFB-766ADD9CA208/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BB2B1200-668E-4A4D-ACFB-766ADD9CA208/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500962e22b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500962e22b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52295"
,(lldb)     command script import "/tmp/BB2B1200-668E-4A4D-ACFB-766ADD9CA208/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 00:14:52.242 ThaliTest[974:1653168] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6E4F1CA4-FCC2-4D21-8CA9-CBF864EC8B41/Library/Cookies/Cookies.binarycookies
,2016-02-09 00:14:52.641 ThaliTest[974:1653168] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 00:14:52.642 ThaliTest[974:1653168] Multi-tasking -> Device: YES, App: YES
,2016-02-09 00:14:52.651 ThaliTest[974:1653168] Unlimited access to network resources
,2016-02-09 00:14:52.660 ThaliTest[974:1653168] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 00:15:02.586 ThaliTest[974:1653168] Resetting plugins due to page load.
,2016-02-09 00:15:06.317 ThaliTest[974:1653168] Finished load of: file:///var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/index.html
,2016-02-09 00:15:06.495 ThaliTest[974:1653168] JXcore Cordova plugin initializing
,2016-02-09 00:15:06.496 ThaliTest[974:1653405] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal

# teardown

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,ok 2 should be equal

ok 3 should be equal

,ok 4 should be equal

,ok 5 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 6 should throw

# teardown

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 7 should throw

,# teardown

# setup

,# #parseBeacons no beacons returns null

,ok 8 should be equal

,# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 9 should throw

,# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 10 should be equal

# teardown
,
# setup

,# #parseBeacons addressBookCallback returns no matches

,ok 11 should be equal

ok 12 should be equal

# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 13 should be equal

,ok 14 (unnamed assert)

,# teardown

,# setup

,# #parseBeacons with beacons both for and not for the user

,ok 15 (unnamed assert)

# teardown

,# setup

,# multiplex can send data

,ok 16 String should be length:200

,# teardown

,# setup

,# enqueue and run in order

,ok 17 firstPromise setTimeout

,ok 18 firstPromise result

,ok 19 firstPromise testValue

,ok 20 secondPromise setTimeout

,ok 21 secondPromise result

,ok 22 secondPromise testValue

,ok 23 thirdPromise in promise

,ok 24 thirdPromise result

,ok 25 thirdPromise testValue

,# teardown

,# setup

,# basic

,ok 26 sane

,# teardown

,# setup

,# another

,ok 27 sane

,# teardown

,# setup

,# successfully create a new pkcs12 file and return hash value

,ok 28 should be equal

,ok 29 null

,ok 30 (unnamed assert)

,ok 31 should be equal

,ok 32 should not throw

# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 33 (unnamed assert)

,ok 34 (unnamed assert)

,ok 35 should not throw

,ok 36 should be equal

ok 37 should be equal

,# teardown

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,ok 38 should be equal

,# teardown

,# setup

,# failed to get mobile documents path

,ok 39 should be equal

,# teardown

,# setup

,# #init should register the peerAvailabilityChanged event

,ok 40 should be equal

,ok 41 should be equal

,ok 42 should be equal

,# teardown

,# setup

,# #init should register the networkChanged event

,ok 43 should be equal

,# teardown

,# setup

,# #startBroadcasting should throw on null device name

,ok 44 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on empty string device name

,ok 45 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on non-number port

,ok 46 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on NaN port

,ok 47 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on negative port

,ok 48 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on too large port

,ok 49 should throw

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,ok 50 should be equal

,ok 51 should be equal

ok 52 should be equal

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ok 53 should be equal

,ok 54 should be equal

,ok 55 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ok 56 should be equal

,ok 57 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ok 58 should be equal

,ok 59 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,ok 60 should be equal

,ok 61 should be equal

,ok 62 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") and handle an error

,ok 63 should be equal

,ok 64 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") without an error

,ok 65 should be equal

,ok 66 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") and handle an error

,ok 67 should be equal

,ok 68 should be equal

,# teardown

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,2016-02-09 00:19:24.762 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:24.778 ThaliTest[974:1653405] server: starting 1454973564761.974.XvHlMg==
,2016-02-09 00:19:24.780 ThaliTest[974:1653405] multipeer session: start timer: 0x167b1250
2016-02-09 00:19:24.780 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973564761.974
,2016-02-09 00:19:24.782 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

2016-02-09 00:19:24.787 ThaliTest[974:1653405] jxcore: stopBroadcasting
2016-02-09 00:19:24.787 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.787 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:24.789 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.792 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:24.797 ThaliTest[974:1653405] server: starting 1454973564792.974.J3u9vw==
,2016-02-09 00:19:24.797 ThaliTest[974:1653405] multipeer session: start timer: 0x167b0880
,2016-02-09 00:19:24.798 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973564792.974
,2016-02-09 00:19:24.799 ThaliTest[974:1653405] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.801 ThaliTest[974:1653405] jxcore: stopBroadcasting
2016-02-09 00:19:24.801 ThaliTest[974:1653405] THEMultipeerSession stopping peer
2016-02-09 00:19:24.802 ThaliTest[974:1653405] multipeer session: stop timer
2016-02-09 00:19:24.802 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.806 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:24.811 ThaliTest[974:1653405] server: starting 1454973564805.974.b2dLIQ==
2016-02-09 00:19:24.812 ThaliTest[974:1653405] multipeer session: start timer: 0x167bada0
2016-02-09 00:19:24.812 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973564805.974
,2016-02-09 00:19:24.813 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.819 ThaliTest[974:1653405] jxcore: stopBroadcasting
2016-02-09 00:19:24.820 ThaliTest[974:1653405] THEMultipeerSession stopping peer
2016-02-09 00:19:24.820 ThaliTest[974:1653405] multipeer session: stop timer
2016-02-09 00:19:24.821 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.824 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:24.830 ThaliTest[974:1653405] server: starting 1454973564822.974.QGcwpA==
2016-02-09 00:19:24.831 ThaliTest[974:1653405] multipeer session: start timer: 0x166ecda0
2016-02-09 00:19:24.831 ThaliTest[974:1653405] THEMultipeerSession initia,lized peer 1454973564822.974
2016-02-09 00:19:24.832 ThaliTest[974:1653405] jxcore: startBroadcasting: success
ok 75 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.834 ThaliTest[974:1653405] jxcore: stopBroadcasting
2016-02-09 00:19:24.834 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.835 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:24.836 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error
,
,2016-02-09 00:19:24.846 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:24.850 ThaliTest[974:1653405] server: starting 1454973564845.974.kjbg6g==
,2016-02-09 00:19:24.852 ThaliTest[974:1653405] multipeer session: start timer: 0x1939ea50
,2016-02-09 00:19:24.854 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973564845.974
,2016-02-09 00:19:24.855 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.859 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:19:24.860 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.861 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:24.864 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.866 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:24.868 ThaliTest[974:1653405] server: starting 1454973564865.974.58jWZg==
,2016-02-09 00:19:24.870 ThaliTest[974:1653405] multipeer session: start timer: 0x167bbb10
,2016-02-09 00:19:24.871 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973564865.974
,2016-02-09 00:19:24.874 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.876 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:19:24.876 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.877 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:24.878 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.881 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:24.883 ThaliTest[974:1653405] server: starting 1454973564881.974.b2V9eg==
,2016-02-09 00:19:24.884 ThaliTest[974:1653405] multipeer session: start timer: 0x166ce160
,2016-02-09 00:19:24.887 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973564881.974
,2016-02-09 00:19:24.889 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.891 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:19:24.892 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.893 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:24.895 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.898 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:24.900 ThaliTest[974:1653405] server: starting 1454973564897.974.basL/g==
,2016-02-09 00:19:24.901 ThaliTest[974:1653405] multipeer session: start timer: 0x167bbb10
,2016-02-09 00:19:24.903 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973564897.974
,2016-02-09 00:19:24.905 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.908 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:19:24.909 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.911 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:24.911 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,ok 84 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.915 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:24.918 ThaliTest[974:1653405] server: starting 1454973564915.974.M1PISw==
,2016-02-09 00:19:24.919 ThaliTest[974:1653405] multipeer session: start timer: 0x1678cfd0
,2016-02-09 00:19:24.921 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973564915.974
,2016-02-09 00:19:24.923 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 85 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.926 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:19:24.926 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.927 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:24.929 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,ok 86 Should be able to call stopBroadcasting without error

,2016-02-09 00:19:24.932 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:24.935 ThaliTest[974:1653405] server: starting 1454973564931.974.1xyAQg==
,2016-02-09 00:19:24.936 ThaliTest[974:1653405] multipeer session: start timer: 0x1678bf40
,2016-02-09 00:19:24.937 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973564931.974
,2016-02-09 00:19:24.938 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-09 00:19:24.941 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:19:24.941 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:19:24.941 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:24.944 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error
,
,2016-02-09 00:19:25.631 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:25.634 ThaliTest[974:1653405] server: starting 1454973565631.974.dH7CLA==
,2016-02-09 00:19:25.635 ThaliTest[974:1653405] multipeer session: start timer: 0x187b88a0
2016-02-09 00:19:25.636 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973565631.974
2016-02-09 00:19:25.636 ThaliTest[974:1653405] jxcore: startBroadcasting: success
ok 89 Should be able to call startBroadcasting without error

,2016-02-09 00:19:25.639 ThaliTest[974:1653405] jxcore: startBroadcasting
2016-02-09 00:19:25.640 ThaliTest[974:1653405] jxcore: startBroadcasting: failure
,ok 90 Cannot call startBroadcasting twice

,2016-02-09 00:19:25.644 ThaliTest[974:1653405] jxcore: stopBroadcasting
2016-02-09 00:19:25.645 ThaliTest[974:1653405] THEMultipeerSession stopping peer
2016-02-09 00:19:25.646 ThaliTest[974:1653405] multipeer session: stop timer
2016-02-09 00:19:25.646 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-09 00:19:26.650 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:26.653 ThaliTest[974:1653405] server: starting 1454973566649.974.4y7xTA==
,2016-02-09 00:19:26.654 ThaliTest[974:1653405] multipeer session: start timer: 0x18469e90
2016-02-09 00:19:26.655 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973566649.974
2016-02-09 00:19:26.655 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-09 00:19:26.658 ThaliTest[974:1653405] jxcore: connect foobar
2016-02-09 00:19:26.658 ThaliTest[974:1653405] client: unknown peer foobar
2016-02-09 00:19:26.659 ThaliTest[974:1653405] jxcore: connect: fail: Unknown peer
,ok 93 Should not connect to a bad peer

,2016-02-09 00:19:26.662 ThaliTest[974:1653405] jxcore: stopBroadcasting
2016-02-09 00:19:26.663 ThaliTest[974:1653405] THEMultipeerSession stopping peer
2016-02-09 00:19:26.664 ThaliTest[974:1653405] multipeer session: stop timer
2016-02-09 00:19:26.664 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
ok 94 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-09 00:19:27.182 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:27.185 ThaliTest[974:1653405] server: starting 1454973567182.974.+j8Gng==
,2016-02-09 00:19:27.186 ThaliTest[974:1653405] multipeer session: start timer: 0x19436a40
,2016-02-09 00:19:27.187 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973567182.974
,2016-02-09 00:19:27.188 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 95 Should be able to call startBroadcasting without error

2016-02-09 00:19:27.191 ThaliTest[974:1653405] jxcore: disconnect
2016-02-09 00:19:27.192 ThaliTest[974:1653405] jxcore: disconnect: fail
,ok 96 Disconnect should fail to a non-existant peer 

2016-02-09 00:19:27.197 ThaliTest[974:1653405] jxcore: stopBroadcasting
2016-02-09 00:19:27.197 ThaliTest[974:1653405] THEMultipeerSession stopping peer
2016-02-09 00:19:27.197 ThaliTest[974:1653405,] multipeer session: stop timer
2016-02-09 00:19:27.198 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,ok 97 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-09 00:19:27.389 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:27.392 ThaliTest[974:1653405] server: starting 1454973567388.974.cLlcMg==
,2016-02-09 00:19:27.393 ThaliTest[974:1653405] multipeer session: start timer: 0x19436ef0
,2016-02-09 00:19:27.394 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973567388.974
2016-02-09 00:19:27.394 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 98 Should be able to call startBroadcasting without error

,2016-02-09 00:19:28.972 ThaliTest[974:1653168] client: found peer: 1454973566947.1530.QPwF6Q==
,2016-02-09 00:19:28.975 ThaliTest[974:1653405] jxcore: connect 1454973566947.1530.QPwF6Q==
,2016-02-09 00:19:28.976 ThaliTest[974:1653405] client session: connect
,2016-02-09 00:19:28.976 ThaliTest[974:1653405] client session: stateChange:0->1 1454973566947.1530.QPwF6Q==
,2016-02-09 00:19:29.175 ThaliTest[974:1653168] multipeer session: reset timer
2016-02-09 00:19:29.175 ThaliTest[974:1653168] multipeer session: stop timer
2016-02-09 00:19:29.176 ThaliTest[974:1653168] multipeer session: start timer: 0x19436ef0
2016-02-09 00:19:29.176 ThaliTest[974:1653168] server session: connect
,2016-02-09 00:19:29.176 ThaliTest[974:1653168] server session: stateChange:0->1 1454973566947.1530
,2016-02-09 00:19:29.183 ThaliTest[974:1653168] server: accepting invitation 1454973566947.1530
,2016-02-09 00:19:31.606 ThaliTest[974:1653935] client session: connected
2016-02-09 00:19:31.606 ThaliTest[974:1653935] client session: stateChange:1->2 1454973566947.1530.QPwF6Q==
,2016-02-09 00:19:31.627 ThaliTest[974:1653931] client session: fireConnectCallback: 1454973566947.1530.QPwF6Q==
2016-02-09 00:19:31.628 ThaliTest[974:1653931] jxcore: connect: success
,ok 99 Should be able to connect without error

,ok 100 Port should be within range

,2016-02-09 00:19:31.633 ThaliTest[974:1653405] jxcore: disconnect
,2016-02-09 00:19:31.633 ThaliTest[974:1653405] client session: disconnectFromPeer: 1454973566947.1530.QPwF6Q==
2016-02-09 00:19:31.634 ThaliTest[974:1653405] client session: disconnect
2016-02-09 00:19:31.634 ThaliTest[974:1653405] client session: stateChange:2->0 1454973566947.1530.QPwF6Q==
,2016-02-09 00:19:31.707 ThaliTest[974:1653405] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-09 00:19:31.734 ThaliTest[974:1653927] server session: connected
2016-02-09 00:19:31.734 ThaliTest[974:1653927] server session: stateChange:1->2 1454973566947.1530
,2016-02-09 00:19:31.740 ThaliTest[974:1653168] server relay: socket disconnected
,2016-02-09 00:19:31.741 ThaliTest[974:1653168] server relay: 0x18413890 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 00:19:31.858 ThaliTest[974:1653935] server session: not connected 1454973566947.1530
,calling stopBroadcasting

,2016-02-09 00:19:32.002 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:19:32.003 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:19:32.003 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:32.004 ThaliTest[974:1653405] server session: disconnect
2016-02-09 00:19:32.005 ThaliTest[974:1653405] server session: stateChange:2->0 1454973566947.1530
,2016-02-09 00:19:32.189 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-09 00:19:33.918 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:33.921 ThaliTest[974:1653405] server: starting 1454973573917.974.PJWINg==
,2016-02-09 00:19:33.922 ThaliTest[974:1653405] multipeer session: start timer: 0x1945c810
2016-02-09 00:19:33.923 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973573917.974
2016-02-09 00:19:33.923 ThaliTest[974:1653405] jxcore: startBr,oadcasting: success
,ok 102 Should be able to call startBroadcasting without error

,2016-02-09 00:19:34.238 ThaliTest[974:1653168] client: found peer: 1454973572409.1530.8OL1AA==
,2016-02-09 00:19:34.239 ThaliTest[974:1653405] jxcore: connect 1454973572409.1530.8OL1AA==
2016-02-09 00:19:34.240 ThaliTest[974:1653405] client session: connect
2016-02-09 00:19:34.240 ThaliTest[974:1653405] client session: stateChange:0->1 1454973572409.1530.8OL1AA==
,2016-02-09 00:19:35.449 ThaliTest[974:1653168] multipeer session: reset timer
2016-02-09 00:19:35.449 ThaliTest[974:1653168] multipeer session: stop timer
2016-02-09 00:19:35.449 ThaliTest[974:1653168] multipeer session: start timer: 0x1945c810
,2016-02-09 00:19:35.450 ThaliTest[974:1653168] server session: connect
2016-02-09 00:19:35.450 ThaliTest[974:1653168] server session: stateChange:0->1 1454973572409.1530
,2016-02-09 00:19:35.456 ThaliTest[974:1653168] server: accepting invitation 1454973572409.1530
,2016-02-09 00:19:36.838 ThaliTest[974:1653931] client session: connected
2016-02-09 00:19:36.838 ThaliTest[974:1653931] client session: stateChange:1->2 1454973572409.1530.8OL1AA==
,2016-02-09 00:19:36.852 ThaliTest[974:1653935] client session: fireConnectCallback: 1454973572409.1530.8OL1AA==
2016-02-09 00:19:36.854 ThaliTest[974:1653935] jxcore: connect: success
,ok 103 Should be able to connect without error

ok 104 Port should be within range

,2016-02-09 00:19:36.858 ThaliTest[974:1653405] jxcore: connect 1454973572409.1530.8OL1AA==
2016-02-09 00:19:36.859 ThaliTest[974:1653405] client: already connect(ing/ed) to 1454973572409.1530.8OL1AA==
,2016-02-09 00:19:36.859 ThaliTest[974:1653405] jxcore: connect: fail: Aleady connecting
,ok 105 Should fail on double connect

,2016-02-09 00:19:36.863 ThaliTest[974:1653405] jxcore: disconnect
,2016-02-09 00:19:36.864 ThaliTest[974:1653405] client session: disconnectFromPeer: 1454973572409.1530.8OL1AA==
,2016-02-09 00:19:36.864 ThaliTest[974:1653405] client session: disconnect
2016-02-09 00:19:36.865 ThaliTest[974:1653405] client session: stateChange:2->0 1454973572409.1530.8OL1AA==
,2016-02-09 00:19:36.875 ThaliTest[974:1653405] jxcore: disconnect: success
ok 106 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-09 00:19:37.960 ThaliTest[974:1653935] server session: connected
2016-02-09 00:19:37.960 ThaliTest[974:1653935] server session: stateChange:1->2 1454973572409.1530
,2016-02-09 00:19:38.050 ThaliTest[974:1653168] server relay: socket disconnected
,2016-02-09 00:19:38.051 ThaliTest[974:1653168] server relay: 0x187c17e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 00:19:38.083 ThaliTest[974:1653935] server session: not connected 1454973572409.1530
,calling stopBroadcasting

,2016-02-09 00:19:38.295 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:19:38.296 ThaliTest[974:1653405] THEMultipeerSession stopping peer
2016-02-09 00:19:38.296 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:38.298 ThaliTest[974:1653405] server session: disconnect
2016-02-09 00:19:38.298 ThaliTest[974:1653405] server session: stateChange:2->0 1454973572409.1530
,2016-02-09 00:19:38.301 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-09 00:19:38.853 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:38.856 ThaliTest[974:1653405] server: starting 1454973578852.974.wGAwbw==
,2016-02-09 00:19:38.857 ThaliTest[974:1653405] multipeer session: start timer: 0x19413350
,2016-02-09 00:19:38.857 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973578852.974
,2016-02-09 00:19:38.858 ThaliTest[974:1653405] jxcore: startBroadcasting: success
ok 107 Should be able to call startBroadcasting without error

,2016-02-09 00:19:39.422 ThaliTest[974:1653168] client: found peer: 1454973572409.1530.8OL1AA==
,2016-02-09 00:19:39.424 ThaliTest[974:1653405] jxcore: connect 1454973572409.1530.8OL1AA==
2016-02-09 00:19:39.424 ThaliTest[974:1653405] client session: connect
2016-02-09 00:19:39.424 ThaliTest[974:1653405] client session: stateChange:0->1 1454973572409.1530.8OL1AA==
,2016-02-09 00:19:39.655 ThaliTest[974:1653168] client: found peer: 1454973578169.1530.fLQN+w==
,2016-02-09 00:19:39.656 ThaliTest[974:1653405] jxcore: connect 1454973578169.1530.fLQN+w==
2016-02-09 00:19:39.657 ThaliTest[974:1653405] client session: connect
2016-02-09 00:19:39.657 ThaliTest[974:1653405] client session: stateChange:0->1 1454973578169.1530.fLQN+w==
,2016-02-09 00:19:40.153 ThaliTest[974:1653168] multipeer session: reset timer
2016-02-09 00:19:40.154 ThaliTest[974:1653168] multipeer session: stop timer
2016-02-09 00:19:40.154 ThaliTest[974:1653168] multipeer session: start timer: 0x19413350
2016-02-09 00:19:40.154 ThaliTest[974:1653168] server session: connect
2016-02-09 00:19:40.155 ThaliTest[974:1653168] server session: stateChange:0->1 1454973578169.1530
,2016-02-09 00:19:40.161 ThaliTest[974:1653168] server: accepting invitation 1454973578169.1530
,2016-02-09 00:19:42.463 ThaliTest[974:1653935] client session: connected
2016-02-09 00:19:42.464 ThaliTest[974:1653935] client session: stateChange:1->2 1454973578169.1530.fLQN+w==
,2016-02-09 00:19:42.469 ThaliTest[974:1653932] client session: fireConnectCallback: 1454973578169.1530.fLQN+w==
2016-02-09 00:19:42.470 ThaliTest[974:1653932] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,2016-02-09 00:19:42.475 ThaliTest[974:1653405] jxcore: disconnect
,2016-02-09 00:19:42.476 ThaliTest[974:1653405] client session: disconnectFromPeer: 1454973578169.1530.fLQN+w==
,2016-02-09 00:19:42.476 ThaliTest[974:1653405] client session: disconnect
,2016-02-09 00:19:42.477 ThaliTest[974:1653405] client session: stateChange:2->0 1454973578169.1530.fLQN+w==
,2016-02-09 00:19:42.487 ThaliTest[974:1653405] jxcore: disconnect: success
,ok 110 Should be able to disconnect without error

,2016-02-09 00:19:42.490 ThaliTest[974:1653405] jxcore: disconnect
2016-02-09 00:19:42.491 ThaliTest[974:1653405] jxcore: disconnect: fail
,ok 111 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-09 00:19:42.615 ThaliTest[974:1653927] server session: connected
2016-02-09 00:19:42.616 ThaliTest[974:1653927] server session: stateChange:1->2 1454973578169.1530
,2016-02-09 00:19:42.619 ThaliTest[974:1653168] server relay: socket disconnected
2016-02-09 00:19:42.620 ThaliTest[974:1653168] server relay: 0x167d8600 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 00:19:42.672 ThaliTest[974:1653927] server session: not connected 1454973578169.1530
,calling stopBroadcasting

,2016-02-09 00:19:43.022 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:19:43.022 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:19:43.023 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:43.024 ThaliTest[974:1653405] client session: disconnect
2016-02-09 00:19:43.025 ThaliTest[974:1653405] client session: stateChange:1->0 1454973572409.1530.8OL1AA==
,2016-02-09 00:19:43.026 ThaliTest[974:1653405] server session: disconnect
2016-02-09 00:19:43.026 ThaliTest[974:1653405] server session: stateChange:2->0 1454973578169.1530
,2016-02-09 00:19:43.027 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 55059

,2016-02-09 00:19:43.695 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:43.696 ThaliTest[974:1653405] server: starting 1454973583695.974.SFONmA==
,2016-02-09 00:19:43.696 ThaliTest[974:1653405] multipeer session: start timer: 0x187c9580
2016-02-09 00:19:43.696 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973583695.974
2016-02-09 00:19:43.697 ThaliTest[974:1653405] jxcore: startBroadcasting: success
ok 112 Should be able to call startBroadcasting without error

,2016-02-09 00:19:44.242 ThaliTest[974:1653168] client: found peer: 1454973578169.1530.fLQN+w==
,2016-02-09 00:19:44.244 ThaliTest[974:1653405] jxcore: connect 1454973578169.1530.fLQN+w==
2016-02-09 00:19:44.245 ThaliTest[974:1653405] client session: connect
2016-02-09 00:19:44.245 ThaliTest[974:1653405] client session: stateChange:0->1 1454973578169.1530.fLQN+w==
,2016-02-09 00:19:44.776 ThaliTest[974:1653168] multipeer session: reset timer
2016-02-09 00:19:44.777 ThaliTest[974:1653168] multipeer session: stop timer
2016-02-09 00:19:44.777 ThaliTest[974:1653168] multipeer session: start timer: 0x187c9580
,2016-02-09 00:19:44.777 ThaliTest[974:1653168] server session: connect
,2016-02-09 00:19:44.778 ThaliTest[974:1653168] server session: stateChange:0->1 1454973583124.1530
,2016-02-09 00:19:44.784 ThaliTest[974:1653168] server: accepting invitation 1454973583124.1530
,2016-02-09 00:19:44.916 ThaliTest[974:1653168] client: found peer: 1454973583124.1530.X7t7sA==
,2016-02-09 00:19:44.917 ThaliTest[974:1653405] jxcore: connect 1454973583124.1530.X7t7sA==
,2016-02-09 00:19:44.918 ThaliTest[974:1653405] client session: connect
2016-02-09 00:19:44.919 ThaliTest[974:1653405] client session: stateChange:0->1 1454973583124.1530.X7t7sA==
,2016-02-09 00:19:47.329 ThaliTest[974:1653982] server session: connected
2016-02-09 00:19:47.330 ThaliTest[974:1653982] server session: stateChange:1->2 1454973583124.1530
,2016-02-09 00:19:47.338 ThaliTest[974:1653168] server relay: connected (to port: 55059)
,2016-02-09 00:19:47.531 ThaliTest[974:1654014] client session: connected
2016-02-09 00:19:47.531 ThaliTest[974:1654014] client session: stateChange:1->2 1454973583124.1530.X7t7sA==
,2016-02-09 00:19:47.534 ThaliTest[974:1654014] client session: fireConnectCallback: 1454973583124.1530.X7t7sA==
2016-02-09 00:19:47.534 ThaliTest[974:1654014] jxcore: connect: success
,ok 113 Should be able to connect without error

,ok 114 Port should be within range

,2016-02-09 00:19:47.537 ThaliTest[974:1653168] client: relay established
2016-02-09 00:19:47.537 ThaliTest[974:1653168] client: new accepted socket: 0x18334570
,2016-02-09 00:19:47.653 ThaliTest[974:1654014] server session: not connected 1454973583124.1530
,data in 12045

,data in 13140

,data in 14235

,data in 15330

,data in 35040

,data in 54750

,data in 71175

,data in 76650

,data in 86505

,data in 106215

,data in 116070

,data in 122640

,data in 131072

,ok 115 the test messages should be equal

,2016-02-09 00:19:48.651 ThaliTest[974:1653405] jxcore: disconnect
,2016-02-09 00:19:48.652 ThaliTest[974:1653405] client session: disconnectFromPeer: 1454973583124.1530.X7t7sA==
,2016-02-09 00:19:48.652 ThaliTest[974:1653405] client session: disconnect
,2016-02-09 00:19:48.653 ThaliTest[974:1653405] client session: stateChange:2->0 1454973583124.1530.X7t7sA==
,2016-02-09 00:19:48.663 ThaliTest[974:1653405] jxcore: disconnect: success
,ok 116 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.
,
,# teardown
,
,calling stopBroadcasting

,2016-02-09 00:19:48.777 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:19:48.777 ThaliTest[974:1653405] THEMultipeerSession stopping peer
2016-02-09 00:19:48.778 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:19:48.778 ThaliTest[974:1653405] client session: disconnect
2016-02-09 00:19:48.779 ThaliTest[974:1653405] client session: stateChange:1->0 1454973578169.1530.fLQN+w==
,2016-02-09 00:19:48.782 ThaliTest[974:1653405] server session: disconnect
2016-02-09 00:19:48.782 ThaliTest[974:1653405] server session: stateChange:2->0 1454973583124.1530
,2016-02-09 00:19:49.075 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# setup

,# ThaliEmitter handles socket disconnect correctly

,echo server started on port: 55066

,2016-02-09 00:19:49.337 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:19:49.341 ThaliTest[974:1653405] server: starting 1454973589337.974./QEt9Q==
,2016-02-09 00:19:49.342 ThaliTest[974:1653405] multipeer session: start timer: 0x167e07a0
2016-02-09 00:19:49.343 ThaliTest[974:1653405] THEMultipeerSession initialized peer 1454973589337.974
2016-02-09 00:19:49.343 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 117 Should be able to call startBroadcasting without error
,
,2016-02-09 00:19:50.255 ThaliTest[974:1653168] client: found peer: 1454973583124.1530.X7t7sA==
,[{"peerIdentifier":"1454973583124.1530.X7t7sA==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 00:19:50.259 ThaliTest[974:1653405] jxcore: connect 1454973583124.1530.X7t7sA==
,2016-02-09 00:19:50.259 ThaliTest[974:1653405] client session: connect
,2016-02-09 00:19:50.260 ThaliTest[974:1653405] client session: stateChange:0->1 1454973583124.1530.X7t7sA==
,2016-02-09 00:19:50.592 ThaliTest[974:1653168] client: found peer: 1454973588680.1530.6h94OA==
,[{"peerIdentifier":"1454973588680.1530.6h94OA==","peerName":"(null)","peerAvailable":true}]

2016-02-09 00:19:50.594 ThaliTest[974:1653405] jxcore: connect 1454973588680.1530.6h94OA==
2016-02-09 00:19:50.595 ThaliTest[974:1653405] client session: connec,t
2016-02-09 00:19:50.595 ThaliTest[974:1653405] client session: stateChange:0->1 1454973588680.1530.6h94OA==
,2016-02-09 00:19:50.802 ThaliTest[974:1653168] multipeer session: reset timer
2016-02-09 00:19:50.802 ThaliTest[974:1653168] multipeer session: stop timer
,2016-02-09 00:19:50.802 ThaliTest[974:1653168] multipeer session: start timer: 0x167e07a0
2016-02-09 00:19:50.803 ThaliTest[974:1653168] server session: connect
,2016-02-09 00:19:50.803 ThaliTest[974:1653168] server session: stateChange:0->1 1454973588680.1530
,2016-02-09 00:19:50.810 ThaliTest[974:1653168] server: accepting invitation 1454973588680.1530
,2016-02-09 00:19:50.893 ThaliTest[974:1653168] client: lost peer: 1454973583124.1530.X7t7sA==
2016-02-09 00:19:50.894 ThaliTest[974:1653168] client session: onPeerLost: 1454973583124.1530.X7t7sA==
2016-02-09 00:19:50.894 ThaliTest[974:1653168] client session: onLinkFailure: 1454973583124.1530.X7t7sA==
2016-02-09 00:19:50.894 ThaliTest[974:1653168] client session: disconnect
2016-02-09 00:19:50.895 ThaliTest[974:1653168] client session: stateChange:1->0 1454973583124.1530.X7t7sA==
2016-02-09 00:19:50.89,5 ThaliTest[974:1653168] client session: fireConnectCallback: 1454973583124.1530.X7t7sA==
2016-02-09 00:19:50.896 ThaliTest[974:1653168] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1454973583124.1530.X7t7sA==","peerName":"(null)","peerAvailable":false}]

,2016-02-09 00:19:51.905 ThaliTest[974:1653405] jxcore: connect 1454973583124.1530.X7t7sA==
,2016-02-09 00:19:51.906 ThaliTest[974:1653405] client: connect: unreachable 1454973583124.1530.X7t7sA==
,2016-02-09 00:19:51.906 ThaliTest[974:1653405] jxcore: connect: fail: Peer unreachable
,2016-02-09 00:19:53.487 ThaliTest[974:1653935] server session: connected
2016-02-09 00:19:53.487 ThaliTest[974:1653935] server session: stateChange:1->2 1454973588680.1530
,2016-02-09 00:19:53.522 ThaliTest[974:1653168] server relay: connected (to port: 55066)
,2016-02-09 00:19:53.803 ThaliTest[974:1653982] server session: not connected 1454973588680.1530
,2016-02-09 00:19:53.821 ThaliTest[974:1653982] client session: connected
2016-02-09 00:19:53.821 ThaliTest[974:1653982] client session: stateChange:1->2 1454973588680.1530.6h94OA==
,2016-02-09 00:19:53.878 ThaliTest[974:1653168] multipeer session: reset timer
2016-02-09 00:19:53.878 ThaliTest[974:1653168] multipeer session: stop timer
,2016-02-09 00:19:53.878 ThaliTest[974:1653168] multipeer session: start timer: 0x167e07a0
,2016-02-09 00:19:53.879 ThaliTest[974:1653168] server: disconnecting to refresh session (1454973588680.1530)
,2016-02-09 00:19:53.879 ThaliTest[974:1653168] server session: disconnect
2016-02-09 00:19:53.879 ThaliTest[974:1653168] server session: stateChange:2->0 1454973588680.1530
,2016-02-09 00:19:53.885 ThaliTest[974:1653168] server session: connect
2016-02-09 00:19:53.885 ThaliTest[974:1653168] server session: stateChange:0->1 1454973588680.1530
,2016-02-09 00:19:53.891 ThaliTest[974:1653935] client session: fireConnectCallback: 1454973588680.1530.6h94OA==
,2016-02-09 00:19:53.892 ThaliTest[974:1653935] jxcore: connect: success
,ok 118 Should be able to connect without error

,ok 119 Port should be within range

,ok 120 First connect should succeed

,2016-02-09 00:19:53.912 ThaliTest[974:1653168] server: accepting invitation 1454973588680.1530
,2016-02-09 00:19:53.960 ThaliTest[974:1653168] client: relay established
2016-02-09 00:19:53.960 ThaliTest[974:1653168] client: new accepted socket: 0x184e6ad0
,ok 121 the test messages should be equal

ok 122 First send should succeed
,
,2016-02-09 00:19:54.027 ThaliTest[974:1653168] client: socket closed
2016-02-09 00:19:54.028 ThaliTest[974:1653168] client relay: socket disconnected
2016-02-09 00:19:54.028 ThaliTest[974:1653168] client relay: 0x184e6ad0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 00:19:54.028 ThaliTest[974:1653168] client session: socket closed: 1454973588680.1530.6h94OA==
2016-02-09 00:1,9:54.028 ThaliTest[974:1653168] client session: onLinkFailure: 1454973588680.1530.6h94OA==
2016-02-09 00:19:54.028 ThaliTest[974:1653168] client session: disconnect
2016-02-09 00:19:54.028 ThaliTest[974:1653168] client session: stateChange:2->0 145497358,8680.1530.6h94OA==
,2016-02-09 00:19:54.040 ThaliTest[974:1653168] client session: fireConnectionErrorEvent: 1454973588680.1530.6h94OA==
,2016-02-09 00:19:54.051 ThaliTest[974:1653405] jxcore: connect 1454973588680.1530.6h94OA==
,2016-02-09 00:19:54.051 ThaliTest[974:1653405] client session: connect
,2016-02-09 00:19:54.052 ThaliTest[974:1653405] client session: stateChange:0->1 1454973588680.1530.6h94OA==
,2016-02-09 00:20:00.573 ThaliTest[974:1653931] server session: connected
2016-02-09 00:20:00.574 ThaliTest[974:1653931] server session: stateChange:1->2 1454973588680.1530
,2016-02-09 00:20:00.718 ThaliTest[974:1653932] client session: connected
2016-02-09 00:20:00.719 ThaliTest[974:1653932] client session: stateChange:1->2 1454973588680.1530.6h94OA==
,2016-02-09 00:20:01.115 ThaliTest[974:1653168] server relay: connected (to port: 55066)
,2016-02-09 00:20:01.651 ThaliTest[974:1654139] client session: fireConnectCallback: 1454973588680.1530.6h94OA==
2016-02-09 00:20:01.651 ThaliTest[974:1654139] jxcore: connect: success
,ok 123 Should be able to connect without error

,ok 124 Port should be within range

,ok 125 Second connect should succeed

,2016-02-09 00:20:01.687 ThaliTest[974:1653168] client: relay established
2016-02-09 00:20:01.688 ThaliTest[974:1653168] client: new accepted socket: 0x182c99a0
,ok 126 the test messages should be equal

,ok 127 Second send should succeed

,# teardown

,2016-02-09 00:20:05.849 ThaliTest[974:1653168] client: socket closed
,2016-02-09 00:20:05.849 ThaliTest[974:1653168] client relay: socket disconnected
2016-02-09 00:20:05.850 ThaliTest[974:1653168] client relay: 0x182c99a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" U,serInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-09 00:20:05.850 ThaliTest[974:1653168] client session: socket closed: 1454973588680.1530.6h94OA==
2016-02-09 00:20:05.850 ThaliTest[974:1653168] client session: onLinkFailure: 1454973588680.1530.6h94OA==
2016-02-09 00:20:05.850 ThaliTest[974:1653,168] client session: disconnect
2016-02-09 00:20:05.851 ThaliTest[974:1653168] client session: stateChange:2->0 1454973588680.1530.6h94OA==
,2016-02-09 00:20:05.856 ThaliTest[974:1653168] client session: fireConnectionErrorEvent: 1454973588680.1530.6h94OA==
,calling stopBroadcasting

,2016-02-09 00:20:05.875 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:20:05.875 ThaliTest[974:1653405] THEMultipeerSession stopping peer
,2016-02-09 00:20:05.876 ThaliTest[974:1653405] multipeer session: stop timer
,2016-02-09 00:20:05.877 ThaliTest[974:1653405] server session: disconnect
2016-02-09 00:20:05.877 ThaliTest[974:1653405] server session: stateChange:2->0 1454973588680.1530
,2016-02-09 00:20:05.887 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliReplicationManager can call start without error

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/6E4F1CA4-FCC2-4D21-8CA9-CBF864EC8B41/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 128 starting event should occur in right order

,2016-02-09 00:20:06.117 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:20:06.118 ThaliTest[974:1653405] server: starting YLI8N2rcDUla7VO39yhBFw.wEzVXQ==
,2016-02-09 00:20:06.119 ThaliTest[974:1653405] multipeer session: start timer: 0x18407120
2016-02-09 00:20:06.119 ThaliTest[974:1653405] THEMultipeerSession initialized peer YLI8N2rcDUla7VO39yhBFw
2016-02-09 00:20:06.119 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 129 started event should occur in right order

,Now in TRM stop

,State of this._isStarted: true

,ok 130 stopping event should occur in right order

About to call stopBroadcasting

2016-02-09 00:20:06.120 ThaliTest[974:1653405] jxcore: stopBroadcasting
2016-02-09 00:20:06.120 ThaliTest[974:1653405] THEMultipeerSession stopping peer
2016-02-09 00:,20:06.121 ThaliTest[974:1653405] multipeer session: stop timer
2016-02-09 00:20:06.121 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 131 stopped event should occur in right order

,mux server bridge listener closed

# teardown

,# setup

,# ThaliReplicationManager receives identity

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/6E4F1CA4-FCC2-4D21-8CA9-CBF864EC8B41/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 00:20:06.528 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:20:06.531 ThaliTest[974:1653405] server: starting YLI8N2rcDUla7VO39yhBFw.B5xtPg==
,2016-02-09 00:20:06.532 ThaliTest[974:1653405] multipeer session: start timer: 0x166213e0
2016-02-09 00:20:06.533 ThaliTest[974:1653405] THEMultipeerSession initialized peer YLI8N2rcDUla7VO39yhBFw
2016-02-09 00:20:06.533 ThaliTest[974:1653405] jxcore: startBroadcasting: success
,ok 132 getDeviceIdentity should not return an error

,ok 133 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-02-09 00:20:06.538 ThaliTest[974:1653405] jxcore: stopBroadcasting
,2016-02-09 00:20:06.539 ThaliTest[974:1653405] THEMultipeerSession stopping peer
2016-02-09 00:20:06.539 ThaliTest[974:1653405] multipeer session: stop timer
2016-02-09 00:20:06.540 ThaliTest[974:1653405] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# teardown

,# setup

,# ThaliReplicationManager replicates database

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/6E4F1CA4-FCC2-4D21-8CA9-CBF864EC8B41/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 00:20:10.911 ThaliTest[974:1653405] jxcore: startBroadcasting
,2016-02-09 00:20:10.912 ThaliTest[974:1653405] server: starting YLI8N2rcDUla7VO39yhBFw.1GXILg==
,2016-02-09 00:20:10.913 ThaliTest[974:1653405] multipeer session: start timer: 0x16786150
2016-02-09 00:20:10.913 ThaliTest[974:1653405] THEMultipeerSession initialized peer YLI8N2rcDUla7VO39yhBFw
2016-02-09 00:20:10.913 ThaliTest[974:1653405] jxcore: st,artBroadcasting: success
,ok 134 getDeviceIdentity should not return an error

,ok 135 deviceName should not be null

,2016-02-09 00:20:11.895 ThaliTest[974:1653168] client: found peer: 1454973588680.1530.6h94OA==
,2016-02-09 00:20:15.002 ThaliTest[974:1653168] client: lost peer: 1454973588680.1530.6h94OA==
2016-02-09 00:20:15.003 ThaliTest[974:1653168] client session: onPeerLost: 1454973588680.1530.6h94OA==
,2016-02-09 00:20:15.024 ThaliTest[974:1653168] client: found peer: IrWKtz0S2cYg9kvcczVTAA.WZ2KPg==
,2016-02-09 00:20:15.025 ThaliTest[974:1653405] jxcore: connect 1454973588680.1530.6h94OA==
2016-02-09 00:20:15.025 ThaliTest[974:1653405] client: connect: unreachable 1454973588680.1530.6h94OA==
2016-02-09 00:20:15.025 ThaliTest[974:1653405] jxcore: connect: fail: Peer unreachable
,Connect error with error: Error: Peer unreachable

,2016-02-09 00:20:15.026 ThaliTest[974:1653405] jxcore: connect IrWKtz0S2cYg9kvcczVTAA.WZ2KPg==
2016-02-09 00:20:15.027 ThaliTest[974:1653405] client session: connect
,2016-02-09 00:20:15.027 ThaliTest[974:1653405] client session: stateChange:0->1 IrWKtz0S2cYg9kvcczVTAA.WZ2KPg==
,2016-02-09 00:20:15.079 ThaliTest[974:1653405] jxcore: disconnect
2016-02-09 00:20:15.079 ThaliTest[974:1653405] jxcore: disconnect: fail
Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 1454973588680.1530.6h94OA==

,ok 136 Should be able to put doc without error

,ok 137 1st change of local doc should contain local id

,2016-02-09 00:20:15.636 ThaliTest[974:1653168] multipeer session: reset timer
2016-02-09 00:20:15.636 ThaliTest[974:1653168] multipeer session: stop timer
2016-02-09 00:20:15.636 ThaliTest[974:1653168] multipeer session: start timer: 0x16786150
2016-02-,09 00:20:15.637 ThaliTest[974:1653168] server session: connect
2016-02-09 00:20:15.637 ThaliTest[974:1653168] server session: stateChange:0->1 IrWKtz0S2cYg9kvcczVTAA
,2016-02-09 00:20:15.644 ThaliTest[974:1653168] server: accepting invitation IrWKtz0S2cYg9kvcczVTAA
,2016-02-09 00:20:18.326 ThaliTest[974:1654145] client session: connected
2016-02-09 00:20:18.327 ThaliTest[974:1654145] client session: stateChange:1->2 IrWKtz0S2cYg9kvcczVTAA.WZ2KPg==
,2016-02-09 00:20:18.623 ThaliTest[974:1653931] client session: fireConnectCallback: IrWKtz0S2cYg9kvcczVTAA.WZ2KPg==
2016-02-09 00:20:18.623 ThaliTest[974:1653931] jxcore: connect: success
,2016-02-09 00:20:18.636 ThaliTest[974:1653168] client: relay established
2016-02-09 00:20:18.636 ThaliTest[974:1653168] client: new accepted socket: 0x166490c0
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

,2016-02-09 00:20:19.652 ThaliTest[974:1654146] server session: connected
2016-02-09 00:20:19.653 ThaliTest[974:1654146] server session: stateChange:1->2 IrWKtz0S2cYg9kvcczVTAA
,client bridge: socket closed

,2016-02-09 00:20:19.925 ThaliTest[974:1653168] server relay: connected (to port: 55084)
,server bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,ok 138 1st change of remote doc should contain remote id

,client bridge: socket closed

,ok 139 Can update remote doc without error

,null

,{ ok: true,
  id: 'f47ac54c-6cba-4abe-9c46-4abd017375f7',
  rev: '2-995e079a9330b179207458ff1ed70baf' }

,client bridge: new client socket

,client bridge: new client socket

,ok 140 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

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

,ok 141 Local changes occur in strict order

,ok 142 2nd change of local doc should contain remote id

,# teardown

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

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

,2016-02-09 00:20:54.636 ThaliTest[974:1653405] Error!: cyclic object value
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"","_lineNum,ber":"36","_columnNumber":"48","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/lib/thali-tape.js:36:48"},{"_fileName":"events.js","_functionName":"emit","_lineNumber":"98","_co,lumnNumber":"1","_msg":"    at emit@events.js:98:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js","_functionName":"handlers.reject/<","_lineNumb,er":"128","_columnNumber":"11","_msg":"    at handlers.reject/<@/private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js:128:11"},{"_fileName":"/private/var/mobile/Contain,ers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js","_functionName":"nextTick","_lineNumber":"61","_columnNumber":"7","_msg":"    at nextTick@/private/var/mobile/Contain,ers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js:61:7"},{"_fileName":"node.js","_functionName":"$0a","_lineNumber":"917","_columnNumber":"1","_msg":"    at $0a@node.js,:917:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"unknown","_lineNumber":36,"_columnNumber":47,"_msg":""}]
Uncaught Exception: TypeErr,or: cyclic object value

,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: '',
    _lineNumber: '36',
    _columnNumber: '48',
    _msg: '    at @/private/var/m,obile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/lib/thali-tape.js:36:48' },
  { _fileName: 'events.js',
    _functionName: 'emit',
    _lineNumber: '98',
    _columnNumber: '1',
    _msg: '    at emit@,events.js:98:1' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js',
    _functionName: 'handlers.reject/<',
    _lineNumber: '128',
    _colu,mnNumber: '11',
    _msg: '    at handlers.reject/<@/private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js:128:11' },
  { _fileName: '/private/var/mobile/Containers/Bu,ndle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js',
    _functionName: 'nextTick',
    _lineNumber: '61',
    _columnNumber: '7',
    _msg: '    at nextTick@/private/var/,mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js:61:7' },
  { _fileName: 'node.js',
    _functionName: '$0a',
    _lineNumber: '917',
    _columnNumb,er: '1',
    _msg: '    at $0a@node.js:917:1' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/D49F43C9-A59F-4B11-B9DC-67F803A0880E/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'unknown',
    _lineNumber: 36,
   , _columnNumber: 47,
    _msg: '' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

TypeError: 
```
