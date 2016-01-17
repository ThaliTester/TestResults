#### Test 56151093914d164_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56151093914d164/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/EB248816-D713-46F7-BB0C-692F0D728E15/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EB248816-D713-46F7-BB0C-692F0D728E15/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/56151093914d164/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56151093914d164/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AC997050-C17F-451C-940F-D796B1027384/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57295"
,(lldb)     command script import "/tmp/EB248816-D713-46F7-BB0C-692F0D728E15/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-17 16:01:09.721 ThaliTest[2103:5141110] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1BC0BFF1-47A7-401A-B526-9E2B4085144F/Library/Cookies/Cookies.binarycookies
,2016-01-17 16:01:09.982 ThaliTest[2103:5141110] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-17 16:01:09.983 ThaliTest[2103:5141110] Multi-tasking -> Device: YES, App: YES
,2016-01-17 16:01:09.990 ThaliTest[2103:5141110] Unlimited access to network resources
,2016-01-17 16:01:10.001 ThaliTest[2103:5141110] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-17 16:01:14.323 ThaliTest[2103:5141110] Resetting plugins due to page load.
,2016-01-17 16:01:15.833 ThaliTest[2103:5141110] Finished load of: file:///var/mobile/Containers/Bundle/Application/AC997050-C17F-451C-940F-D796B1027384/ThaliTest.app/www/index.html
,2016-01-17 16:01:16.020 ThaliTest[2103:5141110] JXcore Cordova plugin initializing
,2016-01-17 16:01:16.021 ThaliTest[2103:5141257] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC997050-C17F-451C-940F-D796B1027384/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC997050-C17F-451C-940F-D796B1027384/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC997050-C17F-451C-940F-D796B1027384/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC997050-C17F-451C-940F-D796B1027384/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC997050-C17F-451C-940F-D796B1027384/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC997050-C17F-451C-940F-D796B1027384/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AC997050-C17F-451C-940F-D796B1027384/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
# setup
,# another
,# teardown
,ok 3 sane
# setup
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
# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,ok 32 should be equal
ok 33 should be equal
# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
,ok 35 should be equal
# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
ok 37 should be equal
ok 38 should be equal
,# setup
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
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-17 16:06:32.637 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.645 ThaliTest[2103:5141257] server: starting 1453043192637.2103.4RxBhw==
2016-01-17 16:06:32.646 ThaliTest[2103:5141257] multipeer session: start timer: 0x1931b330
2016-01-17 16:06:32.646 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043192637.2103
2016-01-17 16:06:32.646 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-17 16:06:32.647 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:32.647 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
2016-01-17 16:06:32.652 ThaliTest[2103:5141257] multipeer session: stop timer
2016-01-17 16:06:32.652 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-17 16:06:32.653 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.659 ThaliTest[2103:5141257] server: starting 1453043192653.2103.z7St8w==
2016-01-17 16:06:32.660 ThaliTest[2103:5141257] multipeer session: start timer: 0x1931f740
2016-01-17 16:06:32.660 ThaliTest[2103:5141257] THEMultipeerSession in,itialized peer 1453043192653.2103
2016-01-17 16:06:32.660 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2016-01-17 16:06:32.661 ThaliTest[2103:5141257] jxcore: stopBroadcasting
2016-01-17 16:06:32.667 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
2016-01-17 16:06:32.667 ThaliTest[2103:5141257] multipeer session: stop timer
2016-01-17 16:06:32.667 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2016-01-17 16:06:32.668 ThaliTest[2103:5141257] jxcore: startBroadcasting
2016-01-17 16:06:32.676 ThaliTest[2103:5141257] server: starting 1453043192668.2103.HkJarg==
2016-01-17 16:06:32.677 ThaliTest[2103:5141257] multipeer session: start timer: 0x19323,b80
2016-01-17 16:06:32.677 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043192668.2103
,2016-01-17 16:06:32.677 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2016-01-17 16:06:32.687 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:32.688 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:32.689 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:32.691 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2016-01-17 16:06:32.695 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.698 ThaliTest[2103:5141257] server: starting 1453043192695.2103.to0ewA==
,2016-01-17 16:06:32.702 ThaliTest[2103:5141257] multipeer session: start timer: 0x1931d9b0
,2016-01-17 16:06:32.705 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043192695.2103
,2016-01-17 16:06:32.706 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2016-01-17 16:06:32.708 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:32.709 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:32.710 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:32.712 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2016-01-17 16:06:32.725 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.728 ThaliTest[2103:5141257] server: starting 1453043192725.2103.NyoStQ==
,2016-01-17 16:06:32.734 ThaliTest[2103:5141257] multipeer session: start timer: 0x19424d40
,2016-01-17 16:06:32.737 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043192725.2103
,2016-01-17 16:06:32.738 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-17 16:06:32.740 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:32.741 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:32.741 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:32.742 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-17 16:06:32.746 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.748 ThaliTest[2103:5141257] server: starting 1453043192745.2103.NVur8A==
,2016-01-17 16:06:32.749 ThaliTest[2103:5141257] multipeer session: start timer: 0x1942cc50
,2016-01-17 16:06:32.753 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043192745.2103
,2016-01-17 16:06:32.754 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-17 16:06:32.756 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:32.756 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:32.757 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:32.759 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-17 16:06:32.761 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.763 ThaliTest[2103:5141257] server: starting 1453043192761.2103.RrOLVg==
,2016-01-17 16:06:32.766 ThaliTest[2103:5141257] multipeer session: start timer: 0x1942d730
,2016-01-17 16:06:32.770 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043192761.2103
,2016-01-17 16:06:32.771 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-17 16:06:32.772 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:32.773 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:32.773 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:32.777 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-17 16:06:32.778 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.781 ThaliTest[2103:5141257] server: starting 1453043192778.2103.u5krSw==
,2016-01-17 16:06:32.785 ThaliTest[2103:5141257] multipeer session: start timer: 0x1932a3b0
,2016-01-17 16:06:32.787 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043192778.2103
,2016-01-17 16:06:32.787 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-17 16:06:32.789 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:32.790 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:32.790 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:32.792 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-17 16:06:32.795 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.797 ThaliTest[2103:5141257] server: starting 1453043192795.2103.T9jz5A==
,2016-01-17 16:06:32.799 ThaliTest[2103:5141257] multipeer session: start timer: 0x19327df0
,2016-01-17 16:06:32.804 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043192795.2103
,2016-01-17 16:06:32.804 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-17 16:06:32.806 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:32.807 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:32.807 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:32.808 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-17 16:06:32.812 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.814 ThaliTest[2103:5141257] server: starting 1453043192812.2103.QxVZGg==
,2016-01-17 16:06:32.816 ThaliTest[2103:5141257] multipeer session: start timer: 0x1932c950
,2016-01-17 16:06:32.817 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043192812.2103
,2016-01-17 16:06:32.818 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-17 16:06:32.824 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:32.824 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:32.824 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:32.826 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-17 16:06:32.947 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.949 ThaliTest[2103:5141257] server: starting 1453043192947.2103.fda1UA==
,2016-01-17 16:06:32.951 ThaliTest[2103:5141257] multipeer session: start timer: 0x19429bd0
,2016-01-17 16:06:32.953 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043192947.2103
,2016-01-17 16:06:32.956 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2016-01-17 16:06:32.959 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:32.960 ThaliTest[2103:5141257] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2016-01-17 16:06:32.963 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:32.964 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:32.965 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:32.968 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-17 16:06:33.027 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:33.029 ThaliTest[2103:5141257] server: starting 1453043193027.2103.Xf8GPw==
,2016-01-17 16:06:33.031 ThaliTest[2103:5141257] multipeer session: start timer: 0x19436110
,2016-01-17 16:06:33.032 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043193027.2103
,2016-01-17 16:06:33.033 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2016-01-17 16:06:33.037 ThaliTest[2103:5141257] jxcore: connect foobar
,2016-01-17 16:06:33.039 ThaliTest[2103:5141257] client: unknown peer foobar
,2016-01-17 16:06:33.039 ThaliTest[2103:5141257] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-17 16:06:33.042 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:33.044 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:33.046 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:33.048 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-17 16:06:33.099 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:33.102 ThaliTest[2103:5141257] server: starting 1453043193099.2103.M4dPbg==
,2016-01-17 16:06:33.103 ThaliTest[2103:5141257] multipeer session: start timer: 0x194432a0
,2016-01-17 16:06:33.107 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043193099.2103
,2016-01-17 16:06:33.107 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
,2016-01-17 16:06:33.109 ThaliTest[2103:5141257] jxcore: disconnect
,2016-01-17 16:06:33.110 ThaliTest[2103:5141257] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2016-01-17 16:06:33.113 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:06:33.113 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:06:33.114 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:33.115 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-17 16:06:33.437 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:33.439 ThaliTest[2103:5141257] server: starting 1453043193437.2103.a7RiGw==
2016-01-17 16:06:33.439 ThaliTest[2103:5141257] multipeer session: start timer: 0x193f9950
2016-01-17 16:06:33.439 ThaliTest[2103:5141257] THEMultipeerSession in,itialized peer 1453043193437.2103
2016-01-17 16:06:33.439 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-17 16:06:34.391 ThaliTest[2103:5141110] client: found peer: 1453043193965.2208.NPzgDQ==
2016-01-17 16:06:34.392 ThaliTest[2103:5141257] jxcore: connect 1453043193965.2208.NPzgDQ==
2016-01-17 16:06:34.392 ThaliTest[2103:5141257] client session: connect
2016-01-17 16:06:34.392 ThaliTest[2103:5141257] client session: stateChange:0->1 1453043193965.2208.NPzgDQ==
,2016-01-17 16:06:34.811 ThaliTest[2103:5141110] multipeer session: reset timer
2016-01-17 16:06:34.812 ThaliTest[2103:5141110] multipeer session: stop timer
2016-01-17 16:06:34.812 ThaliTest[2103:5141110] multipeer session: start timer: 0x193f9950
2016-01-17 16:06:34.812 ThaliTest[2103:5141110] server session: connect
,2016-01-17 16:06:34.812 ThaliTest[2103:5141110] server session: stateChange:0->1 1453043193965.2208
,2016-01-17 16:06:34.817 ThaliTest[2103:5141110] server: accepting invitation 1453043193965.2208
,2016-01-17 16:06:38.592 ThaliTest[2103:5142051] server session: connected
2016-01-17 16:06:38.593 ThaliTest[2103:5142051] server session: stateChange:1->2 1453043193965.2208
,2016-01-17 16:06:38.626 ThaliTest[2103:5142050] server session: not connected 1453043193965.2208
,2016-01-17 16:06:38.854 ThaliTest[2103:5142051] client session: connected
2016-01-17 16:06:38.854 ThaliTest[2103:5142051] client session: stateChange:1->2 1453043193965.2208.NPzgDQ==
,2016-01-17 16:06:39.623 ThaliTest[2103:5142051] client session: fireConnectCallback: 1453043193965.2208.NPzgDQ==
2016-01-17 16:06:39.623 ThaliTest[2103:5142051] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-17 16:06:39.625 ThaliTest[2103:5141257] jxcore: disconnect
2016-01-17 16:06:39.628 ThaliTest[2103:5141257] client session: disconnectFromPeer: 1453043193965.2208.NPzgDQ==
2016-01-17 16:06:39.629 ThaliTest[2103:5141257] client session: disconnect
2016-01-17 16:06:39.629 ThaliTest[2103:5141257] client session: stateChange:2->0 1453043193965.2208.NPzgDQ==
,2016-01-17 16:06:39.636 ThaliTest[2103:5141257] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-17 16:06:39.840 ThaliTest[2103:5141257] jxcore: stopBroadcasting
2016-01-17 16:06:39.840 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
2016-01-17 16:06:39.840 ThaliTest[2103:5141257] multipeer session: stop t,imer
2016-01-17 16:06:39.840 ThaliTest[2103:5141257] server session: disconnect
2016-01-17 16:06:39.841 ThaliTest[2103:5141257] server session: stateChange:2->0 1453043193965.2208
,2016-01-17 16:06:40.448 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-17 16:06:40.722 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:40.724 ThaliTest[2103:5141257] server: starting 1453043200722.2103.c0vTZA==
2016-01-17 16:06:40.725 ThaliTest[2103:5141257] multipeer session: start timer: 0x193f06f0
2016-01-17 16:06:40.725 ThaliTest[2103:5141257] THEMultipeerSession in,itialized peer 1453043200722.2103
2016-01-17 16:06:40.725 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-17 16:06:41.621 ThaliTest[2103:5141110] client: found peer: 1453043201233.2208.WN97Sw==
2016-01-17 16:06:41.622 ThaliTest[2103:5141257] jxcore: connect 1453043201233.2208.WN97Sw==
2016-01-17 16:06:41.622 ThaliTest[2103:5141257] client session: connect
2016-01-17 16:06:41.622 ThaliTest[2103:5141257] client session: stateChange:0->1 1453043201233.2208.WN97Sw==
,2016-01-17 16:06:41.886 ThaliTest[2103:5141110] multipeer session: reset timer
2016-01-17 16:06:41.887 ThaliTest[2103:5141110] multipeer session: stop timer
2016-01-17 16:06:41.887 ThaliTest[2103:5141110] multipeer session: start timer: 0x193f06f0
2016-,01-17 16:06:41.887 ThaliTest[2103:5141110] server session: connect
2016-01-17 16:06:41.887 ThaliTest[2103:5141110] server session: stateChange:0->1 1453043201233.2208
2016-01-17 16:06:41.890 ThaliTest[2103:5141110] server: accepting invitation 1453043201233.2208
,2016-01-17 16:06:45.779 ThaliTest[2103:5142051] server session: connected
2016-01-17 16:06:45.779 ThaliTest[2103:5142051] server session: stateChange:1->2 1453043201233.2208
,2016-01-17 16:06:45.796 ThaliTest[2103:5141110] server relay: socket disconnected
2016-01-17 16:06:45.796 ThaliTest[2103:5141110] server relay: 0x194ca9b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 16:06:45.855 ThaliTest[2103:5142050] client session: connected
2016-01-17 16:06:45.855 ThaliTest[2103:5142050] client session: stateChange:1->2 1453043201233.2208.WN97Sw==
,2016-01-17 16:06:45.858 ThaliTest[2103:5142051] server session: not connected 1453043201233.2208
,2016-01-17 16:06:45.865 ThaliTest[2103:5142050] client session: fireConnectCallback: 1453043201233.2208.WN97Sw==
2016-01-17 16:06:45.865 ThaliTest[2103:5142050] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-17 16:06:45.867 ThaliTest[2103:5141257] jxcore: connect 1453043201233.2208.WN97Sw==
2016-01-17 16:06:45.867 ThaliTest[2103:5141257] client: already connect(ing/ed) to 1453043201233.2208.WN97Sw==
2016-01-17 16:06:45.868 ThaliTest[2103:5141257] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-17 16:06:45.868 ThaliTest[2103:5141257] jxcore: disconnect
,2016-01-17 16:06:45.869 ThaliTest[2103:5141257] client session: disconnectFromPeer: 1453043201233.2208.WN97Sw==
2016-01-17 16:06:45.869 ThaliTest[2103:5141257] client session: disconnect
2016-01-17 16:06:45.869 ThaliTest[2103:5141257] client session: stateChange:2->0 1453043201233.2208.WN97Sw==
,2016-01-17 16:06:45.873 ThaliTest[2103:5141257] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-17 16:06:46.165 ThaliTest[2103:5141257] jxcore: stopBroadcasting
2016-01-17 16:06:46.165 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
2016-01-17 16:06:46.166 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:06:46.166 ThaliTest[2103:5141257] server session: disconnect
2016-01-17 16:06:46.166 ThaliTest[2103:5141257] server session: stateChange:2->0 1453043201233.2208
,2016-01-17 16:06:46.170 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-17 16:06:48.033 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:48.035 ThaliTest[2103:5141257] server: starting 1453043208033.2103.DZrl4w==
2016-01-17 16:06:48.035 ThaliTest[2103:5141257] multipeer session: start timer: 0x194e52a0
2016-01-17 16:06:48.035 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043208033.2103
2016-01-17 16:06:48.035 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-17 16:06:48.562 ThaliTest[2103:5141110] client: found peer: 1453043208118.2208.Zx3ckA==
,2016-01-17 16:06:48.563 ThaliTest[2103:5141257] jxcore: connect 1453043208118.2208.Zx3ckA==
2016-01-17 16:06:48.563 ThaliTest[2103:5141257] client session: connect
2016-01-17 16:06:48.563 ThaliTest[2103:5141257] client session: stateChange:0->1 145304320,8118.2208.Zx3ckA==
,2016-01-17 16:06:49.459 ThaliTest[2103:5141110] multipeer session: reset timer
2016-01-17 16:06:49.460 ThaliTest[2103:5141110] multipeer session: stop timer
2016-01-17 16:06:49.460 ThaliTest[2103:5141110] multipeer session: start timer: 0x194e52a0
2016-01-17 16:06:49.460 ThaliTest[2103:5141110] server session: connect
2016-01-17 16:06:49.460 ThaliTest[2103:5141110] server session: stateChange:0->1 1453043208118.2208
2016-01-17 16:06:49.465 ThaliTest[2103:5141110] server: accepting invitation 1453043208118.2208
,2016-01-17 16:06:53.393 ThaliTest[2103:5142050] server session: connected
2016-01-17 16:06:53.393 ThaliTest[2103:5142050] server session: stateChange:1->2 1453043208118.2208
,2016-01-17 16:06:53.403 ThaliTest[2103:5141110] server relay: socket disconnected
2016-01-17 16:06:53.404 ThaliTest[2103:5141110] server relay: 0x193e60e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-17 16:06:53.423 ThaliTest[2103:5142052] server session: not connected 1453043208118.2208
,2016-01-17 16:06:53.593 ThaliTest[2103:5142050] client session: connected
2016-01-17 16:06:53.593 ThaliTest[2103:5142050] client session: stateChange:1->2 1453043208118.2208.Zx3ckA==
,2016-01-17 16:06:53.599 ThaliTest[2103:5142052] client session: fireConnectCallback: 1453043208118.2208.Zx3ckA==
2016-01-17 16:06:53.599 ThaliTest[2103:5142052] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
,2016-01-17 16:06:53.601 ThaliTest[2103:5141257] jxcore: disconnect
2016-01-17 16:06:53.601 ThaliTest[2103:5141257] client session: disconnectFromPeer: 1453043208118.2208.Zx3ckA==
2016-01-17 16:06:53.601 ThaliTest[2103:5141257] client session: disconnect,
2016-01-17 16:06:53.601 ThaliTest[2103:5141257] client session: stateChange:2->0 1453043208118.2208.Zx3ckA==
,2016-01-17 16:06:53.666 ThaliTest[2103:5141257] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2016-01-17 16:06:53.667 ThaliTest[2103:5141257] jxcore: disconnect
2016-01-17 16:06:53.667 ThaliTest[2103:5141257] jxcore: disconnect: fail
ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-17 16:06:54.055 ThaliTest[2103:5141257] jxcore: stopBroadcasting
2016-01-17 16:06:54.055 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
2016-01-17 16:06:54.055 ThaliTest[2103:5141257] multipeer session: stop timer
2016-01-17 16:06:54.055 ThaliTest[2103:5141257] server session: disconnect
2016-01-17 16:06:54.055 ThaliTest[2103:5141257] server session: stateChange:2->0 1453043208118.2208
,2016-01-17 16:06:54.056 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 60858
,2016-01-17 16:06:55.124 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:06:55.126 ThaliTest[2103:5141257] server: starting 1453043215124.2103.Q2LLJA==
,2016-01-17 16:06:55.128 ThaliTest[2103:5141257] multipeer session: start timer: 0x193dd3d0
,2016-01-17 16:06:55.132 ThaliTest[2103:5141257] THEMultipeerSession initialized peer 1453043215124.2103
,2016-01-17 16:06:55.132 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,2016-01-17 16:06:56.275 ThaliTest[2103:5141110] client: found peer: 1453043215490.2208.qThMYw==
2016-01-17 16:06:56.276 ThaliTest[2103:5141257] jxcore: connect 1453043215490.2208.qThMYw==
2016-01-17 16:06:56.276 ThaliTest[2103:5141257] client session: connect
2016-01-17 16:06:56.276 ThaliTest[2103:5141257] client session: stateChange:0->1 1453043215490.2208.qThMYw==
,2016-01-17 16:06:56.480 ThaliTest[2103:5141110] multipeer session: reset timer
,2016-01-17 16:06:56.480 ThaliTest[2103:5141110] multipeer session: stop timer
2016-01-17 16:06:56.480 ThaliTest[2103:5141110] multipeer session: start timer: 0x193dd3d0
,2016-01-17 16:06:56.480 ThaliTest[2103:5141110] server session: connect
2016-01-17 16:06:56.480 ThaliTest[2103:5141110] server session: stateChange:0->1 1453043215490.2208
,2016-01-17 16:06:56.484 ThaliTest[2103:5141110] server: accepting invitation 1453043215490.2208
,2016-01-17 16:07:00.463 ThaliTest[2103:5142046] server session: connected
2016-01-17 16:07:00.463 ThaliTest[2103:5142046] server session: stateChange:1->2 1453043215490.2208
,2016-01-17 16:07:00.469 ThaliTest[2103:5141110] server relay: connected (to port: 60858)
,2016-01-17 16:07:00.477 ThaliTest[2103:5142046] client session: connected
2016-01-17 16:07:00.477 ThaliTest[2103:5142046] client session: stateChange:1->2 1453043215490.2208.qThMYw==
,2016-01-17 16:07:00.479 ThaliTest[2103:5142046] client session: fireConnectCallback: 1453043215490.2208.qThMYw==
2016-01-17 16:07:00.479 ThaliTest[2103:5142046] jxcore: connect: success
ok 89 Should be able to connect without error
,ok 90 Port should be within range
,2016-01-17 16:07:00.482 ThaliTest[2103:5141110] client: relay established
2016-01-17 16:07:00.482 ThaliTest[2103:5141110] client: new accepted socket: 0x194c7680
,data in 9855
,data in 20805
,data in 86341
,data in 89790
,data in 90885
,data in 98550
,data in 114975
2016-01-17 16:07:01.537 ThaliTest[2103:5142046] server session: not connected 1453043215490.2208
,data in 131072
,ok 91 the test messages should be equal
,2016-01-17 16:07:01.548 ThaliTest[2103:5141257] jxcore: disconnect
2016-01-17 16:07:01.549 ThaliTest[2103:5141257] client session: disconnectFromPeer: 1453043215490.2208.qThMYw==
2016-01-17 16:07:01.549 ThaliTest[2103:5141257] client session: disconnect,
2016-01-17 16:07:01.549 ThaliTest[2103:5141257] client session: stateChange:2->0 1453043215490.2208.qThMYw==
,2016-01-17 16:07:01.554 ThaliTest[2103:5141257] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-17 16:07:03.751 ThaliTest[2103:5141110] client: lost peer: 1453043215490.2208.qThMYw==
2016-01-17 16:07:03.751 ThaliTest[2103:5141110] client session: onPeerLost: 1453043215490.2208.qThMYw==
,calling stopBroadcasting
,2016-01-17 16:07:03.869 ThaliTest[2103:5141257] jxcore: stopBroadcasting
2016-01-17 16:07:03.869 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
2016-01-17 16:07:03.869 ThaliTest[2103:5141257] multipeer session: stop timer
2016-01-17 16:07:03.869 ThaliTest[2103:5141257] server session: disconnect
2016-01-17 16:07:03.869 ThaliTest[2103:5141257] server session: stateChange:2->0 1453043215490.2208
,2016-01-17 16:07:03.882 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,echo server started on port: 60864
,2016-01-17 16:07:05.846 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:07:05.847 ThaliTest[2103:5141257] server: starting 1453043225845.2103.il9MVA==
2016-01-17 16:07:05.848 ThaliTest[2103:5141257] multipeer session: start timer: 0x193d86f0
2016-01-17 16:07:05.848 ThaliTest[2103:5141257] THEMultipeerSession in,itialized peer 1453043225845.2103
2016-01-17 16:07:05.848 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-17 16:07:07.228 ThaliTest[2103:5141110] client: found peer: 1453043226498.2208.4X1ntA==
[{"peerIdentifier":"1453043226498.2208.4X1ntA==","peerName":"(null)","peerAvailable":true}]
2016-01-17 16:07:07.229 ThaliTest[2103:5141257] jxcore: connect 14,53043226498.2208.4X1ntA==
2016-01-17 16:07:07.229 ThaliTest[2103:5141257] client session: connect
2016-01-17 16:07:07.229 ThaliTest[2103:5141257] client session: stateChange:0->1 1453043226498.2208.4X1ntA==
,2016-01-17 16:07:07.284 ThaliTest[2103:5141110] multipeer session: reset timer
2016-01-17 16:07:07.285 ThaliTest[2103:5141110] multipeer session: stop timer
2016-01-17 16:07:07.285 ThaliTest[2103:5141110] multipeer session: start timer: 0x193d86f0
2016-01-17 16:07:07.285 ThaliTest[2103:5141110] server session: connect
2016-01-17 16:07:07.285 ThaliTest[2103:5141110] server session: stateChange:0->1 1453043226498.2208
,2016-01-17 16:07:07.291 ThaliTest[2103:5141110] server: accepting invitation 1453043226498.2208
,2016-01-17 16:07:11.412 ThaliTest[2103:5142052] server session: connected
2016-01-17 16:07:11.412 ThaliTest[2103:5142052] server session: stateChange:1->2 1453043226498.2208
2016-01-17 16:07:11.412 ThaliTest[2103:5142052] client session: connected
2016-,01-17 16:07:11.412 ThaliTest[2103:5142052] client session: stateChange:1->2 1453043226498.2208.4X1ntA==
,2016-01-17 16:07:11.418 ThaliTest[2103:5141110] server relay: connected (to port: 60864)
,2016-01-17 16:07:11.428 ThaliTest[2103:5142050] client session: fireConnectCallback: 1453043226498.2208.4X1ntA==
2016-01-17 16:07:11.428 ThaliTest[2103:5142050] jxcore: connect: success
ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 First connect should succeed
,2016-01-17 16:07:11.441 ThaliTest[2103:5141110] client: relay established
2016-01-17 16:07:11.441 ThaliTest[2103:5141110] client: new accepted socket: 0x1938c6a0
,ok 97 the test messages should be equal
,ok 98 First send should succeed
,2016-01-17 16:07:11.495 ThaliTest[2103:5141110] client: socket closed
2016-01-17 16:07:11.495 ThaliTest[2103:5141110] client relay: socket disconnected
2016-01-17 16:07:11.495 ThaliTest[2103:5141110] client relay: 0x1938c6a0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-17 16:07:11.496 ThaliTest[2103:5141110] client session: socket closed: 1453043226498.2208.4X1ntA==
2016-01-17 ,16:07:11.496 ThaliTest[2103:5141110] client session: onLinkFailure: 1453043226498.2208.4X1ntA==
2016-01-17 16:07:11.496 ThaliTest[2103:5141110] client session: disconnect
2016-01-17 16:07:11.496 ThaliTest[2103:5141110] client session: stateChange:2->0 1453043226498.2208.4X1ntA==
,2016-01-17 16:07:11.500 ThaliTest[2103:5141110] client session: fireConnectionErrorEvent: 1453043226498.2208.4X1ntA==
,2016-01-17 16:07:11.503 ThaliTest[2103:5141257] jxcore: connect 1453043226498.2208.4X1ntA==
2016-01-17 16:07:11.504 ThaliTest[2103:5141257] client session: connect
2016-01-17 16:07:11.504 ThaliTest[2103:5141257] client session: stateChange:0->1 1453043226498.2208.4X1ntA==
,2016-01-17 16:07:11.545 ThaliTest[2103:5142052] server session: not connected 1453043226498.2208
,2016-01-17 16:07:11.604 ThaliTest[2103:5141110] multipeer session: reset timer
,2016-01-17 16:07:11.604 ThaliTest[2103:5141110] multipeer session: stop timer
2016-01-17 16:07:11.605 ThaliTest[2103:5141110] multipeer session: start timer: 0x193d86f0
,2016-01-17 16:07:11.605 ThaliTest[2103:5141110] server: disconnecting to refresh session (1453043226498.2208)
2016-01-17 16:07:11.605 ThaliTest[2103:5141110] server session: disconnect
,2016-01-17 16:07:11.605 ThaliTest[2103:5141110] server session: stateChange:2->0 1453043226498.2208
,2016-01-17 16:07:11.607 ThaliTest[2103:5141110] server session: connect
,2016-01-17 16:07:11.608 ThaliTest[2103:5141110] server session: stateChange:0->1 1453043226498.2208
,2016-01-17 16:07:11.615 ThaliTest[2103:5141110] server: accepting invitation 1453043226498.2208
,2016-01-17 16:07:15.738 ThaliTest[2103:5142050] server session: connected
2016-01-17 16:07:15.739 ThaliTest[2103:5142050] server session: stateChange:1->2 1453043226498.2208
,2016-01-17 16:07:15.749 ThaliTest[2103:5141110] server relay: connected (to port: 60864)
,2016-01-17 16:07:15.809 ThaliTest[2103:5142051] client session: connected
2016-01-17 16:07:15.809 ThaliTest[2103:5142051] client session: stateChange:1->2 1453043226498.2208.4X1ntA==
,2016-01-17 16:07:15.870 ThaliTest[2103:5142050] client session: fireConnectCallback: 1453043226498.2208.4X1ntA==
,2016-01-17 16:07:15.872 ThaliTest[2103:5142050] jxcore: connect: success
ok 99 Should be able to connect without error
ok 100 Port should be within range
ok 101 Second connect should succeed
2016-01-17 16:07:15.883 ThaliTest[2103:5142048] server session: not connected 1453043226498.2208
,2016-01-17 16:07:15.888 ThaliTest[2103:5141110] client: relay established
2016-01-17 16:07:15.888 ThaliTest[2103:5141110] client: new accepted socket: 0x193b92b0
,ok 102 the test messages should be equal
ok 103 Second send should succeed
# setup
,2016-01-17 16:07:15.953 ThaliTest[2103:5141110] client: socket closed
2016-01-17 16:07:15.953 ThaliTest[2103:5141110] client relay: socket disconnected
2016-01-17 16:07:15.953 ThaliTest[2103:5141110] client relay: 0x193b92b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-17 16:07:15.953 ThaliTest[2103:5141110] client session: socket closed: 1453043226498.2208.4X1ntA==
2016-01-17 ,16:07:15.953 ThaliTest[2103:5141110] client session: onLinkFailure: 1453043226498.2208.4X1ntA==
2016-01-17 16:07:15.954 ThaliTest[2103:5141110] client session: disconnect
2016-01-17 16:07:15.954 ThaliTest[2103:5141110] client session: stateChange:2->0 14,53043226498.2208.4X1ntA==
2016-01-17 16:07:15.959 ThaliTest[2103:5141110] client session: fireConnectionErrorEvent: 1453043226498.2208.4X1ntA==
,calling stopBroadcasting
,2016-01-17 16:07:16.007 ThaliTest[2103:5141257] jxcore: stopBroadcasting
,2016-01-17 16:07:16.008 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
,2016-01-17 16:07:16.008 ThaliTest[2103:5141257] multipeer session: stop timer
,2016-01-17 16:07:16.011 ThaliTest[2103:5141257] server session: disconnect
,2016-01-17 16:07:16.016 ThaliTest[2103:5141257] server session: stateChange:2->0 1453043226498.2208
,2016-01-17 16:07:16.294 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/1BC0BFF1-47A7-401A-B526-9E2B4085144F/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 104 starting event should occur in right order
,2016-01-17 16:07:16.657 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:07:16.659 ThaliTest[2103:5141257] server: starting HUkdoSUWUyMCz2U4yXOTzA.tcsFKw==
2016-01-17 16:07:16.659 ThaliTest[2103:5141257] multipeer session: start timer: 0x194a0740
2016-01-17 16:07:16.660 ThaliTest[2103:5141257] THEMultipeerSessio,n initialized peer HUkdoSUWUyMCz2U4yXOTzA
2016-01-17 16:07:16.660 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
ok 105 started event should occur in right order
,Now in TRM stop
State of this._isStarted: true
ok 106 stopping event should occur in right order
About to call stopBroadcasting
,2016-01-17 16:07:16.663 ThaliTest[2103:5141257] jxcore: stopBroadcasting
2016-01-17 16:07:16.663 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
2016-01-17 16:07:16.663 ThaliTest[2103:5141257] multipeer session: stop timer
2016-01-17 16:07:16.,663 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 107 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/1BC0BFF1-47A7-401A-B526-9E2B4085144F/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-17 16:07:17.005 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:07:17.007 ThaliTest[2103:5141257] server: starting HUkdoSUWUyMCz2U4yXOTzA.3VyUzw==
2016-01-17 16:07:17.007 ThaliTest[2103:5141257] multipeer session: start timer: 0x1949c7a0
2016-01-17 16:07:17.007 ThaliTest[2103:5141257] THEMultipeerSessio,n initialized peer HUkdoSUWUyMCz2U4yXOTzA
2016-01-17 16:07:17.007 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error
ok 109 deviceName should not be null
Now in TRM stop
State of this._isStar,ted: true
About to call stopBroadcasting
,2016-01-17 16:07:17.009 ThaliTest[2103:5141257] jxcore: stopBroadcasting
2016-01-17 16:07:17.010 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
2016-01-17 16:07:17.010 ThaliTest[2103:5141257] multipeer session: stop timer
2016-01-17 16:07:17.,010 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
# setup
,# ThaliReplicationManager replicates database
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/1BC0BFF1-47A7-401A-B526-9E2B4085144F/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-17 16:07:18.744 ThaliTest[2103:5141257] jxcore: startBroadcasting
,2016-01-17 16:07:18.748 ThaliTest[2103:5141257] server: starting HUkdoSUWUyMCz2U4yXOTzA.3sdKDA==
,2016-01-17 16:07:18.750 ThaliTest[2103:5141257] multipeer session: start timer: 0x1b187430
,2016-01-17 16:07:18.754 ThaliTest[2103:5141257] THEMultipeerSession initialized peer HUkdoSUWUyMCz2U4yXOTzA
,2016-01-17 16:07:18.754 ThaliTest[2103:5141257] jxcore: startBroadcasting: success
,ok 110 getDeviceIdentity should not return an error
,ok 111 deviceName should not be null
,2016-01-17 16:07:19.354 ThaliTest[2103:5141110] client: found peer: QE75ym5qNZcpaCgt1-Eowg.ldax6Q==
,2016-01-17 16:07:24.057 ThaliTest[2103:5141110] multipeer session: reset timer
2016-01-17 16:07:24.057 ThaliTest[2103:5141110] multipeer session: stop timer
2016-01-17 16:07:24.058 ThaliTest[2103:5141110] multipeer session: start timer: 0x1b187430
2016-01-17 16:07:24.058 ThaliTest[2103:5141110] server session: connect
2016-01-17 16:07:24.058 ThaliTest[2103:5141110] server session: stateChange:0->1 QE75ym5qNZcpaCgt1-Eowg
,2016-01-17 16:07:24.064 ThaliTest[2103:5141110] server: accepting invitation QE75ym5qNZcpaCgt1-Eowg
,2016-01-17 16:07:24.101 ThaliTest[2103:5141257] jxcore: connect QE75ym5qNZcpaCgt1-Eowg.ldax6Q==
,2016-01-17 16:07:24.105 ThaliTest[2103:5141257] client session: connect
,2016-01-17 16:07:24.107 ThaliTest[2103:5141257] client session: stateChange:0->1 QE75ym5qNZcpaCgt1-Eowg.ldax6Q==
,ok 112 Should be able to put doc without error
,ok 113 1st change of local doc should contain local id
,2016-01-17 16:07:28.193 ThaliTest[2103:5142050] client session: connected
2016-01-17 16:07:28.193 ThaliTest[2103:5142050] client session: stateChange:1->2 QE75ym5qNZcpaCgt1-Eowg.ldax6Q==
,2016-01-17 16:07:28.442 ThaliTest[2103:5142051] server session: connected
2016-01-17 16:07:28.442 ThaliTest[2103:5142051] server session: stateChange:1->2 QE75ym5qNZcpaCgt1-Eowg
,2016-01-17 16:07:28.581 ThaliTest[2103:5142048] client session: fireConnectCallback: QE75ym5qNZcpaCgt1-Eowg.ldax6Q==
2016-01-17 16:07:28.582 ThaliTest[2103:5142048] jxcore: connect: success
,2016-01-17 16:07:28.587 ThaliTest[2103:5141110] client: relay established
2016-01-17 16:07:28.588 ThaliTest[2103:5141110] client: new accepted socket: 0x194d7500
,client bridge: new client socket
,client bridge: new client socket
,2016-01-17 16:07:28.691 ThaliTest[2103:5141110] server relay: connected (to port: 60879)
,server bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
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
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: socket closed
,client bridge: socket closed
,ok 114 1st change of remote doc should contain remote id
,client bridge: new client socket
,client bridge: new client socket
,ok 115 Can update remote doc without error
,null
,{ ok: true,
  id: '5a52b4f0-4c4b-4736-bf8f-cf675a0ac77f',
  rev: '2-88d26b246300fc91010e4558ea3958b3' }
,client bridge: new client socket
,ok 116 Remote changes occur in strict order
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
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
,ok 117 Local changes occur in strict order
ok 118 2nd change of local doc should contain remote id
,client bridge: new client socket
,# setup
,client bridge: socket closed
,client bridge: new client socket
,2016-01-17 16:07:48.505 ThaliTest[2103:5142052] server session: not connected QE75ym5qNZcpaCgt1-Eowg
,Now in TRM stop
State of this._isStarted: true
,About to call stopBroadcasting
,2016-01-17 16:07:48.512 ThaliTest[2103:5141257] jxcore: stopBroadcasting
2016-01-17 16:07:48.512 ThaliTest[2103:5141257] THEMultipeerSession stopping peer
2016-01-17 16:07:48.512 ThaliTest[2103:5141257] multipeer session: stop timer
2016-01-17 16:07:48.512 ThaliTest[2103:5141257] client session: disconnect
2016-01-17 16:07:48.512 ThaliTest[2103:5141257] client session: stateChange:2->0 QE75ym5qNZcpaCgt1-Eowg.ldax6Q==
,2016-01-17 16:07:48.517 ThaliTest[2103:5141257] server session: disconnect
2016-01-17 16:07:48.518 ThaliTest[2103:5141257] server session: stateChange:2->0 QE75ym5qNZcpaCgt1-Eowg
,2016-01-17 16:07:48.527 ThaliTest[2103:5141257] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,Error in mux client bridge Error: write EPIPE
,incoming client socket error Error: read ECONNRESET
,mux server bridge listener closed
,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
,client bridge: socket closed
,server bridge: socket closed
,syncRetry called when not started
,# teardown
,ok 119 should be equal
,# setup
,client bridge: socket closed
,client bridge: socket closed

```
