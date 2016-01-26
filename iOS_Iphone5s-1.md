#### Test 5667282762e056f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5667282762e056f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/EF5A200A-5EF0-44DE-A7C9-4219EF4C53C2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EF5A200A-5EF0-44DE-A7C9-4219EF4C53C2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5667282762e056f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5667282762e056f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61170"
,(lldb)     command script import "/tmp/EF5A200A-5EF0-44DE-A7C9-4219EF4C53C2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-26 18:55:18.617 ThaliTest[2634:7477206] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B8446009-0AEC-4446-B20F-46A5EDF3CD27/Library/Cookies/Cookies.binarycookies
,2016-01-26 18:55:18.902 ThaliTest[2634:7477206] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-26 18:55:18.904 ThaliTest[2634:7477206] Multi-tasking -> Device: YES, App: YES
,2016-01-26 18:55:18.911 ThaliTest[2634:7477206] Unlimited access to network resources
,2016-01-26 18:55:18.923 ThaliTest[2634:7477206] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-26 18:55:23.580 ThaliTest[2634:7477206] Resetting plugins due to page load.
,2016-01-26 18:55:25.319 ThaliTest[2634:7477206] Finished load of: file:///var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/index.html
,2016-01-26 18:55:25.540 ThaliTest[2634:7477206] JXcore Cordova plugin initializing
2016-01-26 18:55:25.543 ThaliTest[2634:7477506] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

,ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

# setup

,# basic

,# teardown

,ok 11 sane

# setup

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

# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

ok 36 should be equal

ok 37 should be equal

# setup

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

ok 44 should be equal

,# setup

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

,2016-01-26 19:00:07.907 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:07.915 ThaliTest[2634:7477506] server: starting 1453831207907.2634.TyHDwg==
,2016-01-26 19:00:07.917 ThaliTest[2634:7477506] multipeer session: start timer: 0x16b6b2f0
,2016-01-26 19:00:07.921 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831207907.2634
,2016-01-26 19:00:07.923 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error
,
,2016-01-26 19:00:07.926 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:07.926 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:07.927 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:07.929 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 55 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:07.931 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:07.934 ThaliTest[2634:7477506] server: starting 1453831207931.2634.iaqQrA==
,2016-01-26 19:00:07.935 ThaliTest[2634:7477506] multipeer session: start timer: 0x17cecf40
,2016-01-26 19:00:07.939 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831207931.2634
,2016-01-26 19:00:07.939 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error
,
,2016-01-26 19:00:07.941 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:07.942 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:07.943 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:07.944 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:07.947 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:07.949 ThaliTest[2634:7477506] server: starting 1453831207946.2634.3oerDg==
,2016-01-26 19:00:07.951 ThaliTest[2634:7477506] multipeer session: start timer: 0x17cec850
2016-01-26 19:00:07.953 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831207946.2634
2016-01-26 19:00:07.953 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-01-26 19:00:07.955 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:07.955 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:07.956 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:07.958 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:07.960 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:07.962 ThaliTest[2634:7477506] server: starting 1453831207960.2634.o3sETQ==
,2016-01-26 19:00:07.967 ThaliTest[2634:7477506] multipeer session: start timer: 0x16b66f90
,2016-01-26 19:00:07.967 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831207960.2634
,2016-01-26 19:00:07.968 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-01-26 19:00:07.969 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:07.970 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:07.971 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:07.973 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error
,
,2016-01-26 19:00:07.977 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:07.984 ThaliTest[2634:7477506] server: starting 1453831207976.2634.KTVgVg==
,2016-01-26 19:00:07.990 ThaliTest[2634:7477506] multipeer session: start timer: 0x16b66910
,2016-01-26 19:00:07.992 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831207976.2634
,2016-01-26 19:00:07.992 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-01-26 19:00:07.994 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:07.995 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:07.995 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:07.998 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:08.000 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:08.003 ThaliTest[2634:7477506] server: starting 1453831208000.2634.u3b1CQ==
,2016-01-26 19:00:08.005 ThaliTest[2634:7477506] multipeer session: start timer: 0x17ce93f0
,2016-01-26 19:00:08.009 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831208000.2634
,2016-01-26 19:00:08.010 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.012 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:08.013 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.013 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:08.014 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:08.018 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:08.021 ThaliTest[2634:7477506] server: starting 1453831208018.2634.ZjO3RQ==
,2016-01-26 19:00:08.022 ThaliTest[2634:7477506] multipeer session: start timer: 0x16b5a1b0
,2016-01-26 19:00:08.028 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831208018.2634
,2016-01-26 19:00:08.029 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.031 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:08.031 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.032 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:08.035 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:08.037 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:08.039 ThaliTest[2634:7477506] server: starting 1453831208037.2634.7PmR3g==
,2016-01-26 19:00:08.040 ThaliTest[2634:7477506] multipeer session: start timer: 0x17ce98e0
,2016-01-26 19:00:08.045 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831208037.2634
,2016-01-26 19:00:08.048 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.049 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:08.050 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.051 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:08.053 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:08.056 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:08.058 ThaliTest[2634:7477506] server: starting 1453831208056.2634.k8PGog==
,2016-01-26 19:00:08.059 ThaliTest[2634:7477506] multipeer session: start timer: 0x16907c60
,2016-01-26 19:00:08.065 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831208056.2634
,2016-01-26 19:00:08.066 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.068 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:08.068 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.069 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:08.072 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-01-26 19:00:08.074 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:08.077 ThaliTest[2634:7477506] server: starting 1453831208074.2634.b1mR7w==
,2016-01-26 19:00:08.078 ThaliTest[2634:7477506] multipeer session: start timer: 0x17cebad0
,2016-01-26 19:00:08.081 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831208074.2634
,2016-01-26 19:00:08.083 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error
,
,2016-01-26 19:00:08.085 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:08.086 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.086 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:08.089 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-26 19:00:08.761 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:08.763 ThaliTest[2634:7477506] server: starting 1453831208761.2634.cDQFtQ==
2016-01-26 19:00:08.764 ThaliTest[2634:7477506] multipeer session: start timer: 0x17a93750
2016-01-26 19:00:08.764 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831208761.2634
2016-01-26 19:00:08.764 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-26 19:00:08.765 ThaliTest[2634:7477506] jxcore: startBroadcasting
2016-01-26 19:00:08.765 ThaliTest[2634:7477506] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

,2016-01-26 19:00:08.767 ThaliTest[2634:7477506] jxcore: stopBroadcasting
2016-01-26 19:00:08.771 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
2016-01-26 19:00:08.771 ThaliTest[2634:7477506] multipeer session: stop timer
2016-01-26 19:00:08.,771 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-26 19:00:08.879 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:08.882 ThaliTest[2634:7477506] server: starting 1453831208879.2634.W55plQ==
,2016-01-26 19:00:08.884 ThaliTest[2634:7477506] multipeer session: start timer: 0x17ce10a0
,2016-01-26 19:00:08.889 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831208879.2634
,2016-01-26 19:00:08.890 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-01-26 19:00:08.892 ThaliTest[2634:7477506] jxcore: connect foobar
,2016-01-26 19:00:08.893 ThaliTest[2634:7477506] client: unknown peer foobar
,2016-01-26 19:00:08.894 ThaliTest[2634:7477506] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer
,
,2016-01-26 19:00:08.898 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:08.899 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:08.900 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:08.902 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error
,
,# setup
,
,# ThaliEmitter throws on disconnect to bad peer
,
,# teardown

,2016-01-26 19:00:11.396 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:11.398 ThaliTest[2634:7477506] server: starting 1453831211396.2634.FvXOKg==
2016-01-26 19:00:11.398 ThaliTest[2634:7477506] multipeer session: start timer: 0x16e390f0
2016-01-26 19:00:11.398 ThaliTest[2634:7477506] THEMultipeerSession in,itialized peer 1453831211396.2634
2016-01-26 19:00:11.398 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-26 19:00:11.400 ThaliTest[2634:7477506] jxcore: disconnect
2016-01-26 19:00:11.400 ThaliTest[2634:7477506] jxcore: disconnect: fail
ok 81 Disconnect should fail to a non-existant peer 

,2016-01-26 19:00:11.402 ThaliTest[2634:7477506] jxcore: stopBroadcasting
2016-01-26 19:00:11.402 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
2016-01-26 19:00:11.403 ThaliTest[2634:7477506] multipeer session: stop timer
2016-01-26 19:00:11.403 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-26 19:00:11.547 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:11.549 ThaliTest[2634:7477506] server: starting 1453831211547.2634.tfIylQ==
2016-01-26 19:00:11.549 ThaliTest[2634:7477506] multipeer session: start timer: 0x17cd77d0
2016-01-26 19:00:11.549 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831211547.2634
2016-01-26 19:00:11.549 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-26 19:00:12.682 ThaliTest[2634:7477206] client: found peer: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:12.683 ThaliTest[2634:7477506] jxcore: connect 1453831212042.2767.U9cAKA==
2016-01-26 19:00:12.683 ThaliTest[2634:7477506] client session: co,nnect
2016-01-26 19:00:12.684 ThaliTest[2634:7477506] client session: stateChange:0->1 1453831212042.2767.U9cAKA==
,2016-01-26 19:00:12.886 ThaliTest[2634:7477206] multipeer session: reset timer
2016-01-26 19:00:12.886 ThaliTest[2634:7477206] multipeer session: stop timer
2016-01-26 19:00:12.887 ThaliTest[2634:7477206] multipeer session: start timer: 0x17cd77d0
2016-,01-26 19:00:12.887 ThaliTest[2634:7477206] server session: connect
2016-01-26 19:00:12.887 ThaliTest[2634:7477206] server session: stateChange:0->1 1453831212042.2767
2016-01-26 19:00:12.891 ThaliTest[2634:7477206] server: accepting invitation 1453831212042.2767
,2016-01-26 19:00:15.317 ThaliTest[2634:7478364] client session: connected
2016-01-26 19:00:15.317 ThaliTest[2634:7478364] client session: stateChange:1->2 1453831212042.2767.U9cAKA==
,2016-01-26 19:00:15.325 ThaliTest[2634:7478364] client session: fireConnectCallback: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:15.326 ThaliTest[2634:7478364] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should b,e within range

2016-01-26 19:00:15.328 ThaliTest[2634:7477506] jxcore: disconnect
2016-01-26 19:00:15.328 ThaliTest[2634:7477506] client session: disconnectFromPeer: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:15.328 ThaliTest[2634:7477506] client se,ssion: disconnect
2016-01-26 19:00:15.328 ThaliTest[2634:7477506] client session: stateChange:2->0 1453831212042.2767.U9cAKA==
,2016-01-26 19:00:15.376 ThaliTest[2634:7478365] server session: connected
2016-01-26 19:00:15.377 ThaliTest[2634:7478365] server session: stateChange:1->2 1453831212042.2767
,2016-01-26 19:00:15.380 ThaliTest[2634:7477206] server relay: socket disconnected
2016-01-26 19:00:15.381 ThaliTest[2634:7477206] server relay: 0x17cc9bb0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-26 19:00:15.394 ThaliTest[2634:7478361] server session: not connected 1453831212042.2767
,2016-01-26 19:00:15.399 ThaliTest[2634:7477506] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-26 19:00:15.634 ThaliTest[2634:7477506] jxcore: stopBroadcasting
2016-01-26 19:00:15.635 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
2016-01-26 19:00:15.635 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:15.635 ThaliTest[2634:7477506] server session: disconnect
2016-01-26 19:00:15.635 ThaliTest[2634:7477506] server session: stateChange:2->0 1453831212042.2767
2016-01-26 19:00:15.636 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-26 19:00:15.684 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:15.687 ThaliTest[2634:7477506] server: starting 1453831215684.2634.VzKvQg==
,2016-01-26 19:00:15.693 ThaliTest[2634:7477506] multipeer session: start timer: 0x17cd8d10
2016-01-26 19:00:15.694 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831215684.2634
,2016-01-26 19:00:15.696 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
2016-01-26 19:00:15.698 ThaliTest[2634:7477206] client: found peer: 1453831212042.2767.U9cAKA==
ok 87 Should be able to call startBroadcasting without error

2016-01-26 19:00:15.699 ThaliTest[2634:7477206] client: found peer: 1453831211547.2634.tfIylQ==
,2016-01-26 19:00:15.701 ThaliTest[2634:7477506] jxcore: connect 1453831212042.2767.U9cAKA==
,2016-01-26 19:00:15.702 ThaliTest[2634:7477506] client session: connect
,2016-01-26 19:00:15.703 ThaliTest[2634:7477506] client session: stateChange:0->1 1453831212042.2767.U9cAKA==
,2016-01-26 19:00:15.929 ThaliTest[2634:7477506] jxcore: connect 1453831211547.2634.tfIylQ==
2016-01-26 19:00:15.929 ThaliTest[2634:7477506] client session: connect
2016-01-26 19:00:15.930 ThaliTest[2634:7477506] client session: stateChange:0->1 1453831211547.2634.tfIylQ==
,2016-01-26 19:00:16.926 ThaliTest[2634:7477206] client: lost peer: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:16.926 ThaliTest[2634:7477206] client session: onPeerLost: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:16.927 ThaliTest[2634:7477206] client ,session: onLinkFailure: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:16.927 ThaliTest[2634:7477206] client session: disconnect
2016-01-26 19:00:16.927 ThaliTest[2634:7477206] client session: stateChange:1->0 1453831212042.2767.U9cAKA==
2016-01-26 19:00:16.927 ThaliTest[2634:7477206] client session: fireConnectCallback: 1453831212042.2767.U9cAKA==
2016-01-26 19:00:16.927 ThaliTest[2634:7477206] jxcore: connect: fail: Peer disconnected
,2016-01-26 19:00:16.941 ThaliTest[2634:7477206] client: lost peer: 1453831211547.2634.tfIylQ==
2016-01-26 19:00:16.941 ThaliTest[2634:7477206] client session: onPeerLost: 1453831211547.2634.tfIylQ==
2016-01-26 19:00:16.941 ThaliTest[2634:7477206] client session: onLinkFailure: 1453831211547.2634.tfIylQ==
2016-01-26 19:00:16.941 ThaliTest[2634:7477206] client session: disconnect
2016-01-26 19:00:16.941 ThaliTest[2634:7477206] client session: stateChange:1->0 1453831211547.2634.tfIylQ==
2016-01-26 19:00:,16.941 ThaliTest[2634:7477206] client session: fireConnectCallback: 1453831211547.2634.tfIylQ==
2016-01-26 19:00:16.942 ThaliTest[2634:7477206] jxcore: connect: fail: Peer disconnected
2016-01-26 19:00:16.942 ThaliTest[2634:7477206] client: found peer: 1453831215957.2767.1C4Pgg==
,2016-01-26 19:00:16.943 ThaliTest[2634:7477506] jxcore: connect 1453831215957.2767.1C4Pgg==
2016-01-26 19:00:16.947 ThaliTest[2634:7477506] client session: connect
2016-01-26 19:00:16.947 ThaliTest[2634:7477506] client session: stateChange:0->1 1453831215957.2767.1C4Pgg==
,2016-01-26 19:00:17.406 ThaliTest[2634:7477206] multipeer session: reset timer
2016-01-26 19:00:17.406 ThaliTest[2634:7477206] multipeer session: stop timer
2016-01-26 19:00:17.406 ThaliTest[2634:7477206] multipeer session: start timer: 0x17cd8d10
2016-01-26 19:00:17.407 ThaliTest[2634:7477206] server session: connect
2016-01-26 19:00:17.407 ThaliTest[2634:7477206] server session: stateChange:0->1 1453831215957.2767
2016-01-26 19:00:17.411 ThaliTest[2634:7477206] server: accepting invitation 1453831215957.2767
,2016-01-26 19:00:17.930 ThaliTest[2634:7477506] jxcore: connect 1453831212042.2767.U9cAKA==
2016-01-26 19:00:17.931 ThaliTest[2634:7477506] client: connect: unreachable 1453831212042.2767.U9cAKA==
2016-01-26 19:00:17.931 ThaliTest[2634:7477506] jxcore: connect: fail: Peer unreachable
,2016-01-26 19:00:17.944 ThaliTest[2634:7477506] jxcore: connect 1453831211547.2634.tfIylQ==
2016-01-26 19:00:17.945 ThaliTest[2634:7477506] client: connect: unreachable 1453831211547.2634.tfIylQ==
2016-01-26 19:00:17.945 ThaliTest[2634:7477506] jxcore: connect: fail: Peer unreachable
,2016-01-26 19:00:19.738 ThaliTest[2634:7478361] client session: connected
2016-01-26 19:00:19.738 ThaliTest[2634:7478361] client session: stateChange:1->2 1453831215957.2767.1C4Pgg==
,2016-01-26 19:00:19.746 ThaliTest[2634:7478364] client session: fireConnectCallback: 1453831215957.2767.1C4Pgg==
2016-01-26 19:00:19.746 ThaliTest[2634:7478364] jxcore: connect: success
,ok 88 Should be able to connect without error

ok 89 Port should be within range

,2016-01-26 19:00:19.748 ThaliTest[2634:7477506] jxcore: connect 1453831215957.2767.1C4Pgg==
2016-01-26 19:00:19.749 ThaliTest[2634:7477506] client: already connect(ing/ed) to 1453831215957.2767.1C4Pgg==
2016-01-26 19:00:19.749 ThaliTest[2634:7477506] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

2016-01-26 19:00:19.750 ThaliTest[2634:7477506] jxcore: disconnect
,2016-01-26 19:00:19.751 ThaliTest[2634:7477506] client session: disconnectFromPeer: 1453831215957.2767.1C4Pgg==
2016-01-26 19:00:19.751 ThaliTest[2634:7477506] client session: disconnect
2016-01-26 19:00:19.751 ThaliTest[2634:7477506] client session: stateChange:2->0 1453831215957.2767.1C4Pgg==
,2016-01-26 19:00:19.757 ThaliTest[2634:7477506] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-26 19:00:19.857 ThaliTest[2634:7478364] server session: connected
2016-01-26 19:00:19.857 ThaliTest[2634:7478364] server session: stateChange:1->2 1453831215957.2767
,2016-01-26 19:00:19.867 ThaliTest[2634:7477206] server relay: socket disconnected
2016-01-26 19:00:19.867 ThaliTest[2634:7477206] server relay: 0x17cd0520 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-26 19:00:19.876 ThaliTest[2634:7478363] server session: not connected 1453831215957.2767
,calling stopBroadcasting

,2016-01-26 19:00:20.359 ThaliTest[2634:7477506] jxcore: stopBroadcasting
2016-01-26 19:00:20.360 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
2016-01-26 19:00:20.360 ThaliTest[2634:7477506] multipeer session: stop timer
2016-01-26 19:00:20.,360 ThaliTest[2634:7477506] server session: disconnect
2016-01-26 19:00:20.360 ThaliTest[2634:7477506] server session: stateChange:2->0 1453831215957.2767
,2016-01-26 19:00:20.361 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-26 19:00:20.475 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:20.478 ThaliTest[2634:7477506] server: starting 1453831220475.2634.JAOXSQ==
2016-01-26 19:00:20.479 ThaliTest[2634:7477506] multipeer session: start timer: 0x17aa19c0
2016-01-26 19:00:20.479 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831220475.2634
2016-01-26 19:00:20.479 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-26 19:00:21.484 ThaliTest[2634:7477206] client: found peer: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.484 ThaliTest[2634:7477506] jxcore: connect 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.485 ThaliTest[2634:7477506] client session: connect
2016-01-26 19:00:21.485 ThaliTest[2634:7477506] client session: stateChange:0->1 1453831215684.2634.VzKvQg==
,2016-01-26 19:00:21.491 ThaliTest[2634:7477206] client: lost peer: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.493 ThaliTest[2634:7477206] client session: onPeerLost: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.493 ThaliTest[2634:7477206] client ,session: onLinkFailure: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.493 ThaliTest[2634:7477206] client session: disconnect
2016-01-26 19:00:21.493 ThaliTest[2634:7477206] client session: stateChange:1->0 1453831215684.2634.VzKvQg==
,2016-01-26 19:00:21.547 ThaliTest[2634:7477206] client session: fireConnectCallback: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.547 ThaliTest[2634:7477206] jxcore: connect: fail: Peer disconnected
,2016-01-26 19:00:21.550 ThaliTest[2634:7477206] client: lost peer: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.551 ThaliTest[2634:7477206] client session: onPeerLost: 1453831215684.2634.VzKvQg==
2016-01-26 19:00:21.551 ThaliTest[2634:7477206] client:, found peer: 1453831220752.2767.+VWqHg==
2016-01-26 19:00:21.552 ThaliTest[2634:7477506] jxcore: connect 1453831220752.2767.+VWqHg==
2016-01-26 19:00:21.553 ThaliTest[2634:7477506] client session: connect
2016-01-26 19:00:21.554 ThaliTest[2634:7477506] client session: stateChange:0->1 1453831220752.2767.+VWqHg==
,2016-01-26 19:00:21.607 ThaliTest[2634:7477206] multipeer session: reset timer
,2016-01-26 19:00:21.607 ThaliTest[2634:7477206] multipeer session: stop timer
2016-01-26 19:00:21.607 ThaliTest[2634:7477206] multipeer session: start timer: 0x17aa19c0
,2016-01-26 19:00:21.607 ThaliTest[2634:7477206] server session: connect
,2016-01-26 19:00:21.608 ThaliTest[2634:7477206] server session: stateChange:0->1 1453831220752.2767
,2016-01-26 19:00:21.612 ThaliTest[2634:7477206] server: accepting invitation 1453831220752.2767
,2016-01-26 19:00:22.564 ThaliTest[2634:7477506] jxcore: connect 1453831215684.2634.VzKvQg==
2016-01-26 19:00:22.564 ThaliTest[2634:7477506] client: connect: unreachable 1453831215684.2634.VzKvQg==
2016-01-26 19:00:22.564 ThaliTest[2634:7477506] jxcore: connect: fail: Peer unreachable
,2016-01-26 19:00:24.230 ThaliTest[2634:7478363] server session: connected
2016-01-26 19:00:24.231 ThaliTest[2634:7478363] server session: stateChange:1->2 1453831220752.2767
2016-01-26 19:00:24.232 ThaliTest[2634:7478400] client session: connected
,2016-01-26 19:00:24.232 ThaliTest[2634:7478400] client session: stateChange:1->2 1453831220752.2767.+VWqHg==
,2016-01-26 19:00:24.620 ThaliTest[2634:7478359] client session: fireConnectCallback: 1453831220752.2767.+VWqHg==
,2016-01-26 19:00:24.620 ThaliTest[2634:7478359] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be within range

2016-01-26 19:00:24.622 ThaliTest[2634:7477506] jxcore: disconnect
2016-01-26 19:00:24.622 ThaliTest[2634:7477506] client session: disconnectFromPeer: 1453831220752.2767.+VWqHg==
2016-01-26 19:00:24.622 ThaliTest[2634:7477506] client session: disconnect
2016-01-26 19:00:24.623 ThaliTest[2634:7477506] client session: stateChange:2->0 1453831220752.2767.+VWqHg==
,2016-01-26 19:00:24.632 ThaliTest[2634:7477206] server relay: socket disconnected
2016-01-26 19:00:24.632 ThaliTest[2634:7477206] server relay: 0x17ca2c20 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-26 19:00:24.639 ThaliTest[2634:7478363] server session: not connected 1453831220752.2767
,2016-01-26 19:00:24.641 ThaliTest[2634:7477506] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-01-26 19:00:24.642 ThaliTest[2634:7477506] jxcore: disconnect
2016-01-26 19:00:24.643 ThaliTest[2634:7477506] jxcore: disconnect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-26 19:00:25.067 ThaliTest[2634:7477506] jxcore: stopBroadcasting
2016-01-26 19:00:25.068 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
2016-01-26 19:00:25.068 ThaliTest[2634:7477506] multipeer session: stop timer
2016-01-26 19:00:25.,068 ThaliTest[2634:7477506] server session: disconnect
2016-01-26 19:00:25.068 ThaliTest[2634:7477506] server session: stateChange:2->0 1453831220752.2767
2016-01-26 19:00:25.069 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 64160

,2016-01-26 19:00:25.705 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:25.708 ThaliTest[2634:7477506] server: starting 1453831225705.2634.rlB6tQ==
,2016-01-26 19:00:25.709 ThaliTest[2634:7477506] multipeer session: start timer: 0x17aa51c0
,2016-01-26 19:00:25.713 ThaliTest[2634:7477506] THEMultipeerSession initialized peer 1453831225705.2634
,2016-01-26 19:00:25.714 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-01-26 19:00:26.372 ThaliTest[2634:7477206] client: found peer: 1453831225833.2767.P7WhYQ==
2016-01-26 19:00:26.373 ThaliTest[2634:7477506] jxcore: connect 1453831225833.2767.P7WhYQ==
2016-01-26 19:00:26.373 ThaliTest[2634:7477506] client session: co,nnect
2016-01-26 19:00:26.373 ThaliTest[2634:7477506] client session: stateChange:0->1 1453831225833.2767.P7WhYQ==
,2016-01-26 19:00:26.847 ThaliTest[2634:7477206] multipeer session: reset timer
2016-01-26 19:00:26.847 ThaliTest[2634:7477206] multipeer session: stop timer
,2016-01-26 19:00:26.847 ThaliTest[2634:7477206] multipeer session: start timer: 0x17aa51c0
,2016-01-26 19:00:26.848 ThaliTest[2634:7477206] server session: connect
2016-01-26 19:00:26.848 ThaliTest[2634:7477206] server session: stateChange:0->1 1453831225833.2767
,2016-01-26 19:00:26.853 ThaliTest[2634:7477206] server: accepting invitation 1453831225833.2767
,2016-01-26 19:00:29.402 ThaliTest[2634:7478359] server session: connected
2016-01-26 19:00:29.402 ThaliTest[2634:7478359] server session: stateChange:1->2 1453831225833.2767
,2016-01-26 19:00:29.407 ThaliTest[2634:7477206] server relay: connected (to port: 64160)
,2016-01-26 19:00:29.462 ThaliTest[2634:7478364] client session: connected
2016-01-26 19:00:29.462 ThaliTest[2634:7478364] client session: stateChange:1->2 1453831225833.2767.P7WhYQ==
2016-01-26 19:00:29.465 ThaliTest[2634:7478359] client session: fireConnectCallback: 1453831225833.2767.P7WhYQ==
2016-01-26 19:00:29.465 ThaliTest[2634:7478359] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-01-26 19:00:29.469 ThaliTest[2634:7477206] client: relay established
2016-01-26 19:00:29.470 ThaliTest[2634:7477206] client: new accepted socket: 0x178f8b60
,data in 18615

,data in 26138

,data in 40515

,data in 45990

,data in 49062

,data in 70080

,data in 81030

,data in 86505

,data in 113525

,data in 116070

,data in 118260

,data in 131072

,ok 100 the test messages should be equal

,2016-01-26 19:00:30.708 ThaliTest[2634:7477506] jxcore: disconnect
2016-01-26 19:00:30.708 ThaliTest[2634:7477506] client session: disconnectFromPeer: 1453831225833.2767.P7WhYQ==
2016-01-26 19:00:30.708 ThaliTest[2634:7477506] client session: disconnect,
2016-01-26 19:00:30.708 ThaliTest[2634:7477506] client session: stateChange:2->0 1453831225833.2767.P7WhYQ==
,2016-01-26 19:00:30.776 ThaliTest[2634:7477506] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.
,
,# setup

,2016-01-26 19:00:30.997 ThaliTest[2634:7478400] server session: not connected 1453831225833.2767
,calling stopBroadcasting

,2016-01-26 19:00:31.462 ThaliTest[2634:7477506] jxcore: stopBroadcasting
2016-01-26 19:00:31.462 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
2016-01-26 19:00:31.462 ThaliTest[2634:7477506] multipeer session: stop timer
2016-01-26 19:00:31.,463 ThaliTest[2634:7477506] server session: disconnect
2016-01-26 19:00:31.463 ThaliTest[2634:7477506] server session: stateChange:2->0 1453831225833.2767
,2016-01-26 19:00:31.607 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 64166

2016-01-26 19:00:31.960 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:31.963 ThaliTest[2634:7477506] server: starting 1453831231960.2634.E+fcfA==
2016-01-26 19:00:31.963 ThaliTest[2634:7477506] multipeer session: start timer: 0x17cb4020
2016-01-26 19:00:31.963 ThaliTest[2634:7477506] THEMultipeerSession in,itialized peer 1453831231960.2634
2016-01-26 19:00:31.963 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-26 19:00:33.106 ThaliTest[2634:7477206] client: found peer: 1453831232230.2767.Yr5kzg==
[{"peerIdentifier":"1453831232230.2767.Yr5kzg==","peerName":"(null)","peerAvailable":true}]

2016-01-26 19:00:33.108 ThaliTest[2634:7477506] jxcore: connect ,1453831232230.2767.Yr5kzg==
2016-01-26 19:00:33.108 ThaliTest[2634:7477506] client session: connect
2016-01-26 19:00:33.108 ThaliTest[2634:7477506] client session: stateChange:0->1 1453831232230.2767.Yr5kzg==
,2016-01-26 19:00:33.140 ThaliTest[2634:7477206] multipeer session: reset timer
2016-01-26 19:00:33.140 ThaliTest[2634:7477206] multipeer session: stop timer
2016-01-26 19:00:33.140 ThaliTest[2634:7477206] multipeer session: start timer: 0x17cb4020
2016-,01-26 19:00:33.141 ThaliTest[2634:7477206] server session: connect
2016-01-26 19:00:33.141 ThaliTest[2634:7477206] server session: stateChange:0->1 1453831232230.2767
2016-01-26 19:00:33.146 ThaliTest[2634:7477206] server: accepting invitation 1453831232230.2767
,2016-01-26 19:00:35.495 ThaliTest[2634:7478363] client session: connected
2016-01-26 19:00:35.496 ThaliTest[2634:7478363] client session: stateChange:1->2 1453831232230.2767.Yr5kzg==
,2016-01-26 19:00:35.518 ThaliTest[2634:7478400] client session: fireConnectCallback: 1453831232230.2767.Yr5kzg==
2016-01-26 19:00:35.518 ThaliTest[2634:7478400] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-01-26 19:00:35.532 ThaliTest[2634:7477206] client: relay established
2016-01-26 19:00:35.532 ThaliTest[2634:7477206] client: new accepted socket: 0x17abf020
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-01-26 19:00:35.570 ThaliTest[2634:7477206] client: socket closed
2016-01-26 19:00:35.570 ThaliTest[2634:7477206] client relay: socket disconnected
2016-01-26 19:00:35.571 ThaliTest[2634:7477206] client relay: 0x17abf020 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-26 19:00:35.571 ThaliTest[2634:7477206] client session: socket closed: 1453831232230.2767.Yr5kzg==
2016-01-26 19:00:35.571 ThaliTest[2634:7477206] client session: onLinkFailure: 1453831232230.2767.Yr5kzg==
2016-01-26 19:00:35.571 ThaliTest[2634:7477206] client session: disconnect
2016-01-26 19:00:35.571 ThaliTest[2634:7477206] client session: stateChange:2->0 14,53831232230.2767.Yr5kzg==
,2016-01-26 19:00:35.576 ThaliTest[2634:7477206] client session: fireConnectionErrorEvent: 1453831232230.2767.Yr5kzg==
2016-01-26 19:00:35.578 ThaliTest[2634:7477506] jxcore: connect 1453831232230.2767.Yr5kzg==
,2016-01-26 19:00:35.578 ThaliTest[2634:7477506] client session: connect
2016-01-26 19:00:35.580 ThaliTest[2634:7477506] client session: stateChange:0->1 1453831232230.2767.Yr5kzg==
,2016-01-26 19:00:35.682 ThaliTest[2634:7478359] server session: connected
2016-01-26 19:00:35.682 ThaliTest[2634:7478359] server session: stateChange:1->2 1453831232230.2767
,2016-01-26 19:00:35.691 ThaliTest[2634:7477206] server relay: connected (to port: 64166)
,2016-01-26 19:00:36.229 ThaliTest[2634:7478364] server session: not connected 1453831232230.2767
,2016-01-26 19:00:36.276 ThaliTest[2634:7477206] multipeer session: reset timer
2016-01-26 19:00:36.276 ThaliTest[2634:7477206] multipeer session: stop timer
2016-01-26 19:00:36.276 ThaliTest[2634:7477206] multipeer session: start timer: 0x17cb4020
2016-01-26 19:00:36.278 ThaliTest[2634:7477206] server: disconnecting to refresh session (1453831232230.2767)
2016-01-26 19:00:36.278 ThaliTest[2634:7477206] server session: disconnect
2016-01-26 19:00:36.278 ThaliTest[2634:7477206] server session: stateChange:2->0 1453831232230.2767
2016-01-26 19:00:36.282 ThaliTest[2634:7477206] server session: connect
2016-01-26 19:00:36.282 ThaliTest[2634:7477206] server session: stateChange:0->1 1453831232230.2767
,2016-01-26 19:00:36.294 ThaliTest[2634:7477206] server: accepting invitation 1453831232230.2767
,2016-01-26 19:00:38.532 ThaliTest[2634:7478361] client session: connected
2016-01-26 19:00:38.532 ThaliTest[2634:7478361] client session: stateChange:1->2 1453831232230.2767.Yr5kzg==
,2016-01-26 19:00:38.539 ThaliTest[2634:7478363] client session: fireConnectCallback: 1453831232230.2767.Yr5kzg==
2016-01-26 19:00:38.540 ThaliTest[2634:7478363] jxcore: connect: success
ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-01-26 19:00:38.553 ThaliTest[2634:7477206] client: relay established
2016-01-26 19:00:38.554 ThaliTest[2634:7477206] client: new accepted socket: 0x16e09570
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-01-26 19:00:38.596 ThaliTest[2634:7477206] client: socket closed
2016-01-26 19:00:38.596 ThaliTest[2634:7477206] client relay: socket disconnected
2016-01-26 19:00:38.596 ThaliTest[2634:7477206] client relay: 0x16e09570 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-26 19:00:38.597 ThaliTest[2634:7477206] client session: socket closed: 1453831232230.2767.Yr5kzg==
2016-01-26 ,19:00:38.597 ThaliTest[2634:7477206] client session: onLinkFailure: 1453831232230.2767.Yr5kzg==
2016-01-26 19:00:38.597 ThaliTest[2634:7477206] client session: disconnect
2016-01-26 19:00:38.597 ThaliTest[2634:7477206] client session: stateChange:2->0 14,53831232230.2767.Yr5kzg==
,2016-01-26 19:00:38.602 ThaliTest[2634:7477206] client session: fireConnectionErrorEvent: 1453831232230.2767.Yr5kzg==
,2016-01-26 19:00:38.620 ThaliTest[2634:7478363] server session: connected
2016-01-26 19:00:38.620 ThaliTest[2634:7478363] server session: stateChange:1->2 1453831232230.2767
,2016-01-26 19:00:38.635 ThaliTest[2634:7477206] server relay: connected (to port: 64166)
,calling stopBroadcasting

,2016-01-26 19:00:38.701 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:38.701 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:38.702 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:38.705 ThaliTest[2634:7477506] server session: disconnect
,2016-01-26 19:00:38.708 ThaliTest[2634:7477506] server session: stateChange:2->0 1453831232230.2767
,2016-01-26 19:00:38.711 ThaliTest[2634:7478361] server session: not connected 1453831232230.2767
,2016-01-26 19:00:38.723 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,
,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B8446009-0AEC-4446-B20F-46A5EDF3CD27/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-26 19:00:38.863 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:38.865 ThaliTest[2634:7477506] server: starting PoKEhA171ilI9rmiB4GaDg.+yk/GA==
,2016-01-26 19:00:38.867 ThaliTest[2634:7477506] multipeer session: start timer: 0x1781a250
,2016-01-26 19:00:38.871 ThaliTest[2634:7477506] THEMultipeerSession initialized peer PoKEhA171ilI9rmiB4GaDg
,2016-01-26 19:00:38.872 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

,Now in TRM stop

,State of this._isStarted: true

,ok 115 stopping event should occur in right order

,About to call stopBroadcasting
,
,2016-01-26 19:00:38.875 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:38.876 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:38.877 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:38.878 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B8446009-0AEC-4446-B20F-46A5EDF3CD27/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-26 19:00:39.241 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:39.243 ThaliTest[2634:7477506] server: starting PoKEhA171ilI9rmiB4GaDg.mqvyvA==
,2016-01-26 19:00:39.245 ThaliTest[2634:7477506] multipeer session: start timer: 0x17c7b670
,2016-01-26 19:00:39.249 ThaliTest[2634:7477506] THEMultipeerSession initialized peer PoKEhA171ilI9rmiB4GaDg
,2016-01-26 19:00:39.250 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

Now in TRM stop
,
,State of this._isStarted: true

,About to call stopBroadcasting

,2016-01-26 19:00:39.253 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:00:39.254 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:00:39.254 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:00:39.258 ThaliTest[2634:7477506] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/B8446009-0AEC-4446-B20F-46A5EDF3CD27/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-26 19:00:42.355 ThaliTest[2634:7477506] jxcore: startBroadcasting
,2016-01-26 19:00:42.358 ThaliTest[2634:7477506] server: starting PoKEhA171ilI9rmiB4GaDg.dRlGbw==
,2016-01-26 19:00:42.368 ThaliTest[2634:7477506] multipeer session: start timer: 0x17dd5ac0
,2016-01-26 19:00:42.370 ThaliTest[2634:7477506] THEMultipeerSession initialized peer PoKEhA171ilI9rmiB4GaDg
,2016-01-26 19:00:42.371 ThaliTest[2634:7477506] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

,ok 120 deviceName should not be null
,
,2016-01-26 19:00:42.667 ThaliTest[2634:7477206] client: found peer: j9QkXH0XmHT1VG2NqWImZA.hiyARg==
,2016-01-26 19:00:48.086 ThaliTest[2634:7477506] jxcore: connect j9QkXH0XmHT1VG2NqWImZA.hiyARg==
,2016-01-26 19:00:48.087 ThaliTest[2634:7477506] client session: connect
,2016-01-26 19:00:48.088 ThaliTest[2634:7477506] client session: stateChange:0->1 j9QkXH0XmHT1VG2NqWImZA.hiyARg==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-01-26 19:00:48.264 ThaliTest[2634:7477206] multipeer session: reset timer
2016-01-26 19:00:48.265 ThaliTest[2634:7477206] multipeer session: stop timer
2016-01-26 19:00:48.265 ThaliTest[2634:7477206] multipeer session: start timer: 0x17dd5ac0
2016-,01-26 19:00:48.265 ThaliTest[2634:7477206] server session: connect
2016-01-26 19:00:48.265 ThaliTest[2634:7477206] server session: stateChange:0->1 j9QkXH0XmHT1VG2NqWImZA
,2016-01-26 19:00:48.271 ThaliTest[2634:7477206] server: accepting invitation j9QkXH0XmHT1VG2NqWImZA
,2016-01-26 19:00:50.639 ThaliTest[2634:7478361] client session: connected
,2016-01-26 19:00:50.639 ThaliTest[2634:7478361] client session: stateChange:1->2 j9QkXH0XmHT1VG2NqWImZA.hiyARg==
,2016-01-26 19:00:50.652 ThaliTest[2634:7478359] client session: fireConnectCallback: j9QkXH0XmHT1VG2NqWImZA.hiyARg==
2016-01-26 19:00:50.652 ThaliTest[2634:7478359] jxcore: connect: success
,2016-01-26 19:00:50.658 ThaliTest[2634:7477206] client: relay established
2016-01-26 19:00:50.659 ThaliTest[2634:7477206] client: new accepted socket: 0x178bdea0
,client bridge: new client socket

,client bridge: new client socket
,
,2016-01-26 19:00:50.897 ThaliTest[2634:7478559] server session: connected
2016-01-26 19:00:50.897 ThaliTest[2634:7478559] server session: stateChange:1->2 j9QkXH0XmHT1VG2NqWImZA
,2016-01-26 19:00:50.953 ThaliTest[2634:7477206] server relay: connected (to port: 64181)
,server bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

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
onError@/private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:66:18
ajax/<@/private/var/mobile/Containers/Bundle/Applicati,on/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/node_modules/pouchdb/lib/deps/ajax.js:108:1
Request.prototype.init/self.callback@/private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/node_modules/pouchdb/node_modules/request/request.js:123:7
emit@events.js:82:1
Request.prototype.start/self.timeoutTimer<@/private/var/mobile/Containers/Bundle/Application/C95ED422-B89C-4524-973A-992F1D29642A/ThaliTest.app/www/jxcore/node_modules/pouc,hdb/node_modules/request/request.js:590:7
$9@timers.js:120:1


client bridge: socket closed

,client bridge: socket closed

,2016-01-26 19:01:05.728 ThaliTest[2634:7478359] client session: not connected j9QkXH0XmHT1VG2NqWImZA.hiyARg==
2016-01-26 19:01:05.728 ThaliTest[2634:7478359] client session: onLinkFailure: j9QkXH0XmHT1VG2NqWImZA.hiyARg==
2016-01-26 19:01:05.729 ThaliTest,[2634:7478359] client session: disconnect
2016-01-26 19:01:05.729 ThaliTest[2634:7478359] client session: stateChange:2->0 j9QkXH0XmHT1VG2NqWImZA.hiyARg==
2016-01-26 19:01:05.730 ThaliTest[2634:7478359] client session: fireConnectionErrorEvent: j9QkXH0XmHT1VG2NqWImZA.hiyARg==
,2016-01-26 19:01:05.745 ThaliTest[2634:7478559] server session: not connected j9QkXH0XmHT1VG2NqWImZA
,2016-01-26 19:01:05.810 ThaliTest[2634:7477506] jxcore: disconnect
,2016-01-26 19:01:05.820 ThaliTest[2634:7477506] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

,2016-01-26 19:01:05.823 ThaliTest[2634:7477506] jxcore: connect j9QkXH0XmHT1VG2NqWImZA.hiyARg==
,2016-01-26 19:01:05.824 ThaliTest[2634:7477506] client session: connect
,2016-01-26 19:01:05.825 ThaliTest[2634:7477506] client session: stateChange:0->1 j9QkXH0XmHT1VG2NqWImZA.hiyARg==
,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-01-26 19:01:05.833 ThaliTest[2634:7477506] jxcore: stopBroadcasting
,2016-01-26 19:01:05.833 ThaliTest[2634:7477506] THEMultipeerSession stopping peer
,2016-01-26 19:01:05.834 ThaliTest[2634:7477506] multipeer session: stop timer
,2016-01-26 19:01:05.835 ThaliTest[2634:7477506] client session: disconnect
,2016-01-26 19:01:05.836 ThaliTest[2634:7477506] client session: stateChange:1->0 j9QkXH0XmHT1VG2NqWImZA.hiyARg==
,2016-01-26 19:01:05.838 ThaliTest[2634:7477506] server session: disconnect
,2016-01-26 19:01:05.839 ThaliTest[2634:7477506] server session: stateChange:2->0 j9QkXH0XmHT1VG2NqWImZA
,Assertion failed: (_outputStream != nil), function -[THEMultipeerSocketRelay writeOutputStream], file /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerSocketRelay.m, line 170.
,Process 2634 stopped
* thread #1: tid = 0x7217d6, 0x346a3c84 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x346a3c84 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x346a3c84 <+8>:  blo    0x346a3c9c                ; <+32>
    0x346a3c88 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x346a3c8c <+16>: ldr    r12, [pc, r12]
    0x346a3c90 <+20>: b      0x346a3c98                ; <+28>
,* thread #1: tid = 0x7217d6, 0x346a3c84 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x346a3c84 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x34743b46 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x3463bf40 libsystem_c.dylib`abort + 108
    frame #3: 0x3461b6ce libsystem_c.dylib`__assert_rtn + 302
    frame #4: 0x00030e7c ThaliTest`-[THEMultipeerSocketRelay writeOutputStream] + 252
    frame #5: 0x000319d8 ThaliTest`-[THEMultipeerSocketRelay stream:handleEvent:] + 868
    frame #6: 0x2249a9aa CoreFoundation`<redacted> + 146
    frame #7: 0x224a50f8 CoreFoundation`<redacted> + 208
    frame #8: 0x2249a638 CoreFoundation`<redacted> + 320
    frame #9: 0x224d6e94 CoreFoundation`<redacted> + 432
    frame #10: 0x224eb7c6 CoreFoundation`<redacted> + 14
    frame #11: 0x224eb348 CoreFoundation`<redacted> + 344
    frame #12: 0x224e971e CoreFoundation`<redacted> + 806
    frame #13: 0x2243c0d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #14: 0x2243becc CoreFoundation`CFRunLoopRunInMode + 108
    frame #15: 0x2b771af8 GraphicsServices`GSEventRunModal + 160
    frame #16: 0x266c52dc UIKit`UIApplicationMain + 144
    frame #17: 0x0001b1f2 ThaliTest`main + 50

```
