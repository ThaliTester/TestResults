#### Test 5644966031ce140_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5644966031ce140/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/128988CD-E6E4-4658-B241-63024D7C7D00/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/128988CD-E6E4-4658-B241-63024D7C7D00/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5644966031ce140/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5644966031ce140/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/25CAC04D-F01D-4720-A101-1A0651AF6C2F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58616"
,(lldb)     command script import "/tmp/128988CD-E6E4-4658-B241-63024D7C7D00/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-19 13:00:53.474 ThaliTest[1663:5230708] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F3672BBA-5B4D-4E54-A592-17A8864E25D2/Library/Cookies/Cookies.binarycookies
,2016-01-19 13:00:53.586 ThaliTest[1663:5230708] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-19 13:00:53.588 ThaliTest[1663:5230708] Multi-tasking -> Device: YES, App: YES
,2016-01-19 13:00:53.593 ThaliTest[1663:5230708] Unlimited access to network resources
,2016-01-19 13:00:53.604 ThaliTest[1663:5230708] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-19 13:00:59.581 ThaliTest[1663:5230708] Resetting plugins due to page load.
,2016-01-19 13:01:02.091 ThaliTest[1663:5230708] Finished load of: file:///var/mobile/Containers/Bundle/Application/25CAC04D-F01D-4720-A101-1A0651AF6C2F/ThaliTest.app/www/index.html
,2016-01-19 13:01:02.292 ThaliTest[1663:5230708] JXcore Cordova plugin initializing
2016-01-19 13:01:02.296 ThaliTest[1663:5230915] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25CAC04D-F01D-4720-A101-1A0651AF6C2F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25CAC04D-F01D-4720-A101-1A0651AF6C2F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25CAC04D-F01D-4720-A101-1A0651AF6C2F/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25CAC04D-F01D-4720-A101-1A0651AF6C2F/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25CAC04D-F01D-4720-A101-1A0651AF6C2F/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25CAC04D-F01D-4720-A101-1A0651AF6C2F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25CAC04D-F01D-4720-A101-1A0651AF6C2F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,
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

ok 7 should be equal

,ok 8 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 9 (unnamed assert)

,ok 10 (unnamed assert)

ok 11 should not throw

,ok 12 should be equal
,
ok 13 should be equal

# setup

,# failed to extract public key because of corrupt pkcs12 file
,
,# teardown

,ok 14 should be equal

# setup

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

,# setup

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

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 29 should be equal

ok 30 should be equal

ok 31 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 32 should be equal

ok 33 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 34 should be equal

,ok 35 should be equal

,# setup
,
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

,2016-01-19 13:06:34.616 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:34.627 ThaliTest[1663:5230915] server: starting 1453205194616.1663.bTyd8Q==
2016-01-19 13:06:34.627 ThaliTest[1663:5230915] multipeer session: start timer: 0x1db8b6e0
2016-01-19 13:06:34.628 ThaliTest[1663:5230915] THEMultipeerSession in,itialized peer 1453205194616.1663
2016-01-19 13:06:34.628 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.629 ThaliTest[1663:5230915] jxcore: stopBroadcasting
2016-01-19 13:06:34.629 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:06:34.629 ThaliTest[1663:5230915] multipeer session: stop timer
2016-01-19 13:06:34.637 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error

2016-01-19 13:06:34.638 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:34.642 ThaliTest[1663:5230915] server: starting 1453205194638.1663.9RUi6Q==
2016-01-19 13:06:34.643 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d6a2a30
2016-01-19 13:06:34.643 ThaliTest[1663:5230915] THEMultipeerSession in,itialized peer 1453205194638.1663
2016-01-19 13:06:34.643 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.644 ThaliTest[1663:5230915] jxcore: stopBroadcasting,
2016-01-19 13:06:34.644 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
2016-01-19 13:06:34.645 ThaliTest[1663:5230915] multipeer session: stop timer
2016-01-19 13:06:34.645 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
ok 48 Shou,ld be able to call stopBroadcasting without error

2016-01-19 13:06:34.646 ThaliTest[1663:5230915] jxcore: startBroadcasting
2016-01-19 13:06:34.648 ThaliTest[1663:5230915] server: starting 1453205194646.1663.mf7QGw==
2016-01-19 13:06:34.649 ThaliTest[,1663:5230915] multipeer session: start timer: 0x1d69d7b0
2016-01-19 13:06:34.660 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205194646.1663
2016-01-19 13:06:34.660 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error

,2016-01-19 13:06:34.662 ThaliTest[1663:5230915] jxcore: stopBroadcasting
2016-01-19 13:06:34.667 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
2016-01-19 13:06:34.667 ThaliTest[1663:5230915] multipeer session: stop timer
2016-01-19 13:06:34.,668 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error

2016-01-19 13:06:34.669 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:34.675 ThaliTest[1663:5230915] server: starting 1453205194669.1663.G/L5BQ==
,2016-01-19 13:06:34.683 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d69a390
2016-01-19 13:06:34.683 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205194669.1663
2016-01-19 13:06:34.683 ThaliTest[1663:5230915] jxcore: sta,rtBroadcasting: success
ok 51 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.685 ThaliTest[1663:5230915] jxcore: stopBroadcasting
2016-01-19 13:06:34.685 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
2016-01-19, 13:06:34.685 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:06:34.685 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error

2016-01-19 13:06:34.694 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:34.701 ThaliTest[1663:5230915] server: starting 1453205194694.1663.gL7hvg==
2016-01-19 13:06:34.702 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d69c240
2016-01-19 13:06:34.702 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205194694.1663
2016-01-19 13:06:34.703 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.704 ThaliTest[1663:5230915] jxcore: stopBroadcasting,
2016-01-19 13:06:34.704 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
2016-01-19 13:06:34.704 ThaliTest[1663:5230915] multipeer session: stop timer
2016-01-19 13:06:34.705 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
ok 54 Shou,ld be able to call stopBroadcasting without error

2016-01-19 13:06:34.708 ThaliTest[1663:5230915] jxcore: startBroadcasting
2016-01-19 13:06:34.712 ThaliTest[1663:5230915] server: starting 1453205194707.1663.OED1Kg==
2016-01-19 13:06:34.712 ThaliTest[,1663:5230915] multipeer session: start timer: 0x1db8e130
2016-01-19 13:06:34.726 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205194707.1663
2016-01-19 13:06:34.726 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error

2016-01-19 13:06:34.728 ThaliTest[1663:5230915] jxcore: stopBroadcasting
,2016-01-19 13:06:34.728 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:06:34.739 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:06:34.745 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error

,2016-01-19 13:06:34.749 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:34.753 ThaliTest[1663:5230915] server: starting 1453205194749.1663.9nTcXA==
,2016-01-19 13:06:34.757 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d6a1c90
,2016-01-19 13:06:34.759 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205194749.1663
,2016-01-19 13:06:34.767 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error

,2016-01-19 13:06:34.770 ThaliTest[1663:5230915] jxcore: stopBroadcasting
,2016-01-19 13:06:34.772 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:06:34.772 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:06:34.775 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,
,2016-01-19 13:06:34.780 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:34.784 ThaliTest[1663:5230915] server: starting 1453205194779.1663.oIV0Sw==
,2016-01-19 13:06:34.786 ThaliTest[1663:5230915] multipeer session: start timer: 0x1db8d4d0
,2016-01-19 13:06:34.788 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205194779.1663
,2016-01-19 13:06:34.789 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error

,2016-01-19 13:06:34.795 ThaliTest[1663:5230915] jxcore: stopBroadcasting
,2016-01-19 13:06:34.797 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:06:34.797 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:06:34.801 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,
,2016-01-19 13:06:34.804 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:34.807 ThaliTest[1663:5230915] server: starting 1453205194804.1663.X0iqdw==
,2016-01-19 13:06:34.810 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d69b2d0
,2016-01-19 13:06:34.812 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205194804.1663
,2016-01-19 13:06:34.816 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error

,2016-01-19 13:06:34.819 ThaliTest[1663:5230915] jxcore: stopBroadcasting
,2016-01-19 13:06:34.820 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:06:34.820 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:06:34.825 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error

,2016-01-19 13:06:34.827 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:34.830 ThaliTest[1663:5230915] server: starting 1453205194827.1663.PSrFnw==
,2016-01-19 13:06:34.833 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d69a4c0
,2016-01-19 13:06:34.835 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205194827.1663
,2016-01-19 13:06:34.839 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,
,2016-01-19 13:06:34.842 ThaliTest[1663:5230915] jxcore: stopBroadcasting
,2016-01-19 13:06:34.843 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:06:34.843 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:06:34.848 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-19 13:06:35.019 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:35.021 ThaliTest[1663:5230915] server: starting 1453205195018.1663.8e2lnQ==
,2016-01-19 13:06:35.024 ThaliTest[1663:5230915] multipeer session: start timer: 0x1db7e630
,2016-01-19 13:06:35.025 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205195018.1663
,2016-01-19 13:06:35.029 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,
,2016-01-19 13:06:35.033 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:35.034 ThaliTest[1663:5230915] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice

,2016-01-19 13:06:35.038 ThaliTest[1663:5230915] jxcore: stopBroadcasting
,2016-01-19 13:06:35.039 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:06:35.040 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:06:35.045 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-19 13:06:35.522 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:35.524 ThaliTest[1663:5230915] server: starting 1453205195521.1663.W78WQw==
2016-01-19 13:06:35.524 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d682490
2016-01-19 13:06:35.524 ThaliTest[1663:5230915] THEMultipeerSession in,itialized peer 1453205195521.1663
2016-01-19 13:06:35.524 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error

2016-01-19 13:06:35.526 ThaliTest[1663:5230915] jxcore: connect foobar
2,016-01-19 13:06:35.526 ThaliTest[1663:5230915] client: unknown peer foobar
2016-01-19 13:06:35.526 ThaliTest[1663:5230915] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer

2016-01-19 13:06:35.528 ThaliTest[1663:5230915] jxcor,e: stopBroadcasting
2016-01-19 13:06:35.529 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
2016-01-19 13:06:35.529 ThaliTest[1663:5230915] multipeer session: stop timer
2016-01-19 13:06:35.529 ThaliTest[1663:5230915] jxcore: stopBroadcasting:, success
ok 70 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-19 13:06:35.999 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:36.001 ThaliTest[1663:5230915] server: starting 1453205195999.1663.PPn+RQ==
2016-01-19 13:06:36.001 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d428c60
2016-01-19 13:06:36.002 ThaliTest[1663:5230915] THEMultipeerSession in,itialized peer 1453205195999.1663
2016-01-19 13:06:36.002 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-01-19 13:06:36.003 ThaliTest[1663:5230915] jxcore: disconnect
2016-01-19 13:06:36.003 ThaliTest[1663:5230915] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 

2016-01-19 13:06:36.007 ThaliTest[1663:5230915] jxcore: stopBroadcasting
2016-01-19 13:06:36.007 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
2016-01-19 13:06:36.008 ThaliTest[1663:5230,915] multipeer session: stop timer
2016-01-19 13:06:36.008 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-19 13:06:37.093 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:06:37.095 ThaliTest[1663:5230915] server: starting 1453205197093.1663.ldRvCg==
2016-01-19 13:06:37.095 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d449ba0
2016-01-19 13:06:37.095 ThaliTest[1663:5230915] THEMultipeerSession in,itialized peer 1453205197093.1663
2016-01-19 13:06:37.096 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-01-19 13:06:37.831 ThaliTest[1663:5230708] client: found peer: 1453205197097.2303.SAyIXg==
2016-01-19 13:06:37.832 ThaliTest[1663:5230915] jxcore: connect 1453205197097.2303.SAyIXg==
2016-01-19 13:06:37.833 ThaliTest[1663:5230915] client session: connect
2016-01-19 13:06:37.833 ThaliTest[1663:5230915] client session: stateChange:0->1 1453205197097.2303.SAyIXg==
,2016-01-19 13:06:38.992 ThaliTest[1663:5230708] multipeer session: reset timer
2016-01-19 13:06:38.992 ThaliTest[1663:5230708] multipeer session: stop timer
2016-01-19 13:06:38.992 ThaliTest[1663:5230708] multipeer session: start timer: 0x1d449ba0
,2016-01-19 13:06:38.994 ThaliTest[1663:5230708] server session: connect
2016-01-19 13:06:38.994 ThaliTest[1663:5230708] server session: stateChange:0->1 1453205197097.2303
,2016-01-19 13:06:39.000 ThaliTest[1663:5230708] server: accepting invitation 1453205197097.2303
,2016-01-19 13:06:41.754 ThaliTest[1663:5232141] client session: connected
2016-01-19 13:06:41.754 ThaliTest[1663:5232141] client session: stateChange:1->2 1453205197097.2303.SAyIXg==
,2016-01-19 13:06:41.760 ThaliTest[1663:5232141] client session: fireConnectCallback: 1453205197097.2303.SAyIXg==
2016-01-19 13:06:41.760 ThaliTest[1663:5232141] jxcore: connect: success
ok 75 Should be able to connect without error

ok 76 Port should be within range

,2016-01-19 13:06:41.762 ThaliTest[1663:5230915] jxcore: disconnect
2016-01-19 13:06:41.764 ThaliTest[1663:5230915] client session: disconnectFromPeer: 1453205197097.2303.SAyIXg==
2016-01-19 13:06:41.764 ThaliTest[1663:5230915] client session: disconnect
,2016-01-19 13:06:41.764 ThaliTest[1663:5230915] client session: stateChange:2->0 1453205197097.2303.SAyIXg==
,2016-01-19 13:06:41.842 ThaliTest[1663:5230915] jxcore: disconnect: success
ok 77 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-19 13:06:42.477 ThaliTest[1663:5232140] server session: connected
2016-01-19 13:06:42.477 ThaliTest[1663:5232140] server session: stateChange:1->2 1453205197097.2303
,2016-01-19 13:06:42.486 ThaliTest[1663:5230708] server relay: socket disconnected
2016-01-19 13:06:42.486 ThaliTest[1663:5230708] server relay: 0x1d468ee0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 13:06:44.109 ThaliTest[1663:5232141] server session: not connected 1453205197097.2303
,2016-01-19 13:06:49.338 ThaliTest[1663:5230708] client: lost peer: 1453205197097.2303.SAyIXg==
2016-01-19 13:06:49.338 ThaliTest[1663:5230708] client session: onPeerLost: 1453205197097.2303.SAyIXg==
,calling stopBroadcasting

2016-01-19 13:06:50.092 ThaliTest[1663:5230915] jxcore: stopBroadcasting
2016-01-19 13:06:50.092 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
2016-01-19 13:06:50.092 ThaliTest[1663:5230915] multipeer session: stop timer
2016-01-19 13:06:50.093 ThaliTest[1663:5230915] server session: disconnect
2016-01-19 13:06:50.093 ThaliTest[1663:5230915] server session: stateChange:2->0 1453205197097.2303
,2016-01-19 13:06:50.097 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-19 13:07:20.801 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:07:20.804 ThaliTest[1663:5230915] server: starting 1453205240801.1663.7f7vhQ==
2016-01-19 13:07:20.804 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d3f6a00
2016-01-19 13:07:20.805 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205240801.1663
2016-01-19 13:07:20.805 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error

,2016-01-19 13:07:22.385 ThaliTest[1663:5230708] client: found peer: 1453205240706.2303.QbT7Mg==
,2016-01-19 13:07:22.388 ThaliTest[1663:5230915] jxcore: connect 1453205240706.2303.QbT7Mg==
2016-01-19 13:07:22.389 ThaliTest[1663:5230915] client session: connect
2016-01-19 13:07:22.389 ThaliTest[1663:5230915] client session: stateChange:0->1 1453205240706.2303.QbT7Mg==
,2016-01-19 13:07:25.261 ThaliTest[1663:5230708] multipeer session: reset timer
2016-01-19 13:07:25.261 ThaliTest[1663:5230708] multipeer session: stop timer
2016-01-19 13:07:25.261 ThaliTest[1663:5230708] multipeer session: start timer: 0x1d3f6a00
,2016-01-19 13:07:25.261 ThaliTest[1663:5230708] server session: connect
2016-01-19 13:07:25.262 ThaliTest[1663:5230708] server session: stateChange:0->1 1453205240706.2303
,2016-01-19 13:07:25.268 ThaliTest[1663:5230708] server: accepting invitation 1453205240706.2303
,2016-01-19 13:07:28.156 ThaliTest[1663:5232241] server session: connected
2016-01-19 13:07:28.158 ThaliTest[1663:5232241] server session: stateChange:1->2 1453205240706.2303
,2016-01-19 13:07:28.163 ThaliTest[1663:5230708] server relay: socket disconnected
2016-01-19 13:07:28.163 ThaliTest[1663:5230708] server relay: 0x1764edd0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 13:07:28.164 ThaliTest[1663:5232241] client session: connected
2016-01-19 13:07:28.167 ThaliTest[1663:5232241] client session: stateChange:1->2 1453205240706.2303.QbT7Mg==
2016-01-19 13:07:28.169 ThaliTest[1663:5232241] client session: fireCon,nectCallback: 1453205240706.2303.QbT7Mg==
2016-01-19 13:07:28.169 ThaliTest[1663:5232241] jxcore: connect: success
ok 79 Should be able to connect without error

ok 80 Port should be within range

2016-01-19 13:07:28.171 ThaliTest[1663:5230915] jxcor,e: connect 1453205240706.2303.QbT7Mg==
2016-01-19 13:07:28.171 ThaliTest[1663:5230915] client: already connect(ing/ed) to 1453205240706.2303.QbT7Mg==
2016-01-19 13:07:28.172 ThaliTest[1663:5230915] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect

2016-01-19 13:07:28.173 ThaliTest[1663:5230915] jxcore: disconnect
2016-01-19 13:07:28.174 ThaliTest[1663:5230915] client session: disconnectFromPeer: 1453205240706.2303.QbT7Mg==
2016-01-19 13:07:28.174 ThaliTest[16,63:5230915] client session: disconnect
2016-01-19 13:07:28.174 ThaliTest[1663:5230915] client session: stateChange:2->0 1453205240706.2303.QbT7Mg==
,2016-01-19 13:07:28.238 ThaliTest[1663:5232263] server session: not connected 1453205240706.2303
,2016-01-19 13:07:28.244 ThaliTest[1663:5230915] jxcore: disconnect: success
ok 82 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-19 13:07:31.011 ThaliTest[1663:5230915] jxcore: stopBroadcasting
2016-01-19 13:07:31.012 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
2016-01-19 13:07:31.012 ThaliTest[1663:5230915] multipeer session: stop, timer
2016-01-19 13:07:31.012 ThaliTest[1663:5230915] server session: disconnect
2016-01-19 13:07:31.012 ThaliTest[1663:5230915] server session: stateChange:2->0 1453205240706.2303
,2016-01-19 13:07:31.017 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-19 13:07:37.830 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:07:37.833 ThaliTest[1663:5230915] server: starting 1453205257830.1663.xeMcdw==
2016-01-19 13:07:37.833 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d467100
2016-01-19 13:07:37.833 ThaliTest[1663:5230915] THEMultipeerSession in,itialized peer 1453205257830.1663
2016-01-19 13:07:37.833 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-19 13:07:39.274 ThaliTest[1663:5230708] client: found peer: 1453205257869.2303.XGx20g==
2016-01-19 13:07:39.275 ThaliTest[1663:5230915] jxcore: connect 1453205257869.2303.XGx20g==
2016-01-19 13:07:39.275 ThaliTest[1663:5230915] client session: co,nnect
2016-01-19 13:07:39.275 ThaliTest[1663:5230915] client session: stateChange:0->1 1453205257869.2303.XGx20g==
,2016-01-19 13:07:39.362 ThaliTest[1663:5230708] multipeer session: reset timer
2016-01-19 13:07:39.362 ThaliTest[1663:5230708] multipeer session: stop timer
2016-01-19 13:07:39.363 ThaliTest[1663:5230708] multipeer session: start timer: 0x1d467100
2016-01-19 13:07:39.363 ThaliTest[1663:5230708] server session: connect
,2016-01-19 13:07:39.363 ThaliTest[1663:5230708] server session: stateChange:0->1 1453205257869.2303
,2016-01-19 13:07:39.373 ThaliTest[1663:5230708] server: accepting invitation 1453205257869.2303
,2016-01-19 13:07:41.848 ThaliTest[1663:5232263] server session: connected
,2016-01-19 13:07:41.849 ThaliTest[1663:5232263] server session: stateChange:1->2 1453205257869.2303
,2016-01-19 13:07:41.911 ThaliTest[1663:5232263] server session: not connected 1453205257869.2303
2016-01-19 13:07:41.912 ThaliTest[1663:5230708] server relay: socket disconnected
2016-01-19 13:07:41.912 ThaliTest[1663:5230708] server relay: 0x176108e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 13:07:42.041 ThaliTest[1663:5232292] client session: connected
2016-01-19 13:07:42.041 ThaliTest[1663:5232292] client session: stateChange:1->2 1453205257869.2303.XGx20g==
,2016-01-19 13:07:42.051 ThaliTest[1663:5232292] client session: fireConnectCallback: 1453205257869.2303.XGx20g==
2016-01-19 13:07:42.052 ThaliTest[1663:5232292] jxcore: connect: success
ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-01-19 13:07:42.055 ThaliTest[1663:5230915] jxcore: disconnect
,2016-01-19 13:07:42.055 ThaliTest[1663:5230915] client session: disconnectFromPeer: 1453205257869.2303.XGx20g==
,2016-01-19 13:07:42.056 ThaliTest[1663:5230915] client session: disconnect
,2016-01-19 13:07:42.058 ThaliTest[1663:5230915] client session: stateChange:2->0 1453205257869.2303.XGx20g==
,2016-01-19 13:07:42.069 ThaliTest[1663:5230915] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,2016-01-19 13:07:42.071 ThaliTest[1663:5230915] jxcore: disconnect
,2016-01-19 13:07:42.072 ThaliTest[1663:5230915] jxcore: disconnect: fail
,ok 87 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-19 13:07:42.243 ThaliTest[1663:5230915] jxcore: stopBroadcasting
,2016-01-19 13:07:42.243 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:07:42.244 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:07:42.248 ThaliTest[1663:5230915] server session: disconnect
,2016-01-19 13:07:42.252 ThaliTest[1663:5230915] server session: stateChange:2->0 1453205257869.2303
,2016-01-19 13:07:42.253 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,
,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 55453

,2016-01-19 13:07:45.030 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:07:45.040 ThaliTest[1663:5230915] server: starting 1453205265030.1663./j16aQ==
,2016-01-19 13:07:45.042 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d4b33d0
,2016-01-19 13:07:45.048 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205265030.1663
,2016-01-19 13:07:45.049 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error

,2016-01-19 13:08:07.007 ThaliTest[1663:5230708] multipeer session: reset timer
2016-01-19 13:08:07.007 ThaliTest[1663:5230708] multipeer session: stop timer
2016-01-19 13:08:07.007 ThaliTest[1663:5230708] multipeer session: start timer: 0x1d4b33d0
2016-01-19 13:08:07.007 ThaliTest[1663:5230708] server session: connect
2016-01-19 13:08:07.007 ThaliTest[1663:5230708] server session: stateChange:0->1 1453205286647.2303
,2016-01-19 13:08:07.013 ThaliTest[1663:5230708] server: accepting invitation 1453205286647.2303
,2016-01-19 13:08:07.584 ThaliTest[1663:5230708] client: found peer: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:07.586 ThaliTest[1663:5230915] jxcore: connect 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:07.586 ThaliTest[1663:5230915] client session: connect
2016-01-19 13:08:07.587 ThaliTest[1663:5230915] client session: stateChange:0->1 1453205286647.2303.1bqqgQ==
,2016-01-19 13:08:09.632 ThaliTest[1663:5232349] server session: connected
2016-01-19 13:08:09.632 ThaliTest[1663:5232349] server session: stateChange:1->2 1453205286647.2303
,2016-01-19 13:08:09.689 ThaliTest[1663:5230708] server relay: connected (to port: 55453)
,2016-01-19 13:08:11.138 ThaliTest[1663:5232362] server session: not connected 1453205286647.2303
,2016-01-19 13:08:11.204 ThaliTest[1663:5232362] client session: connected
2016-01-19 13:08:11.205 ThaliTest[1663:5232362] client session: stateChange:1->2 1453205286647.2303.1bqqgQ==
,2016-01-19 13:08:11.266 ThaliTest[1663:5232350] client session: fireConnectCallback: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:11.267 ThaliTest[1663:5232350] jxcore: connect: success
ok 89 Should be able to connect without error

ok 90 Port should be within range

2016-01-19 13:08:11.272 ThaliTest[1663:5230708] client: relay established
2016-01-19 13:08:11.272 ThaliTest[1663:5230708] client: new accepted socket: 0x1d2f0a90
,data in 6570

,data in 29565

,data in 36135

,data in 45990

,data in 47085

,data in 58035

,data in 70080

,data in 71175

,data in 78840

,data in 86505

,data in 95265

,data in 99645

,data in 106073

,data in 106215

,data in 114975

,data in 116070

,data in 119355

,data in 121545

,data in 131072

ok 91 the test messages should be equal

2016-01-19 13:08:12.717 ThaliTest[1663:5230915] jxcore: disconnect
2016-01-19 13:08:12.717 ThaliTest[1663:5230915] client session: disconnectFromPeer: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:12.717 ThaliTest[1663:5230915] client session: disconnect
2016-01-19 13:08:12.717 ThaliTest[1663:5230915] client session: stateChange:2->0 1453205286647.2303.1bqqgQ==
,2016-01-19 13:08:12.733 ThaliTest[1663:5230915] jxcore: disconnect: success
ok 92 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

# setup

,calling stopBroadcasting

2016-01-19 13:08:13.159 ThaliTest[1663:5230915] jxcore: stopBroadcasting
2016-01-19 13:08:13.159 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
2016-01-19 13:08:13.159 ThaliTest[1663:5230915] multipeer session: stop timer
2016-01-19 13:08:13.159 ThaliTest[1663:5230915] server session: disconnect
2016-01-19 13:08:13.159 ThaliTest[1663:5230915] server session: stateChange:2->0 1453205286647.2303
,2016-01-19 13:08:13.163 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 55459

2016-01-19 13:08:18.240 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:08:18.243 ThaliTest[1663:5230915] server: starting 1453205298240.1663.Ai0/lA==
2016-01-19 13:08:18.244 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d4a4d50
2016-01-19 13:08:18.244 ThaliTest[1663:5230915] THEMultipeerSession initialized peer 1453205298240.1663
2016-01-19 13:08:18.244 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error

,2016-01-19 13:08:19.136 ThaliTest[1663:5230708] client: found peer: 1453205286647.2303.1bqqgQ==
[{"peerIdentifier":"1453205286647.2303.1bqqgQ==","peerName":"(null)","peerAvailable":true}]

2016-01-19 13:08:19.138 ThaliTest[1663:5230915] jxcore: connect 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:19.138 ThaliTest[1663:5230915] client session: connect
,2016-01-19 13:08:19.138 ThaliTest[1663:5230915] client session: stateChange:0->1 1453205286647.2303.1bqqgQ==
,2016-01-19 13:08:20.125 ThaliTest[1663:5230708] client: found peer: 1453205298295.2303.TUJ6lA==
[{"peerIdentifier":"1453205298295.2303.TUJ6lA==","peerName":"(null)","peerAvailable":true}]

2016-01-19 13:08:20.126 ThaliTest[1663:5230915] jxcore: connect ,1453205298295.2303.TUJ6lA==
2016-01-19 13:08:20.126 ThaliTest[1663:5230915] client session: connect
2016-01-19 13:08:20.126 ThaliTest[1663:5230915] client session: stateChange:0->1 1453205298295.2303.TUJ6lA==
,2016-01-19 13:08:21.606 ThaliTest[1663:5230708] multipeer session: reset timer
2016-01-19 13:08:21.606 ThaliTest[1663:5230708] multipeer session: stop timer
2016-01-19 13:08:21.606 ThaliTest[1663:5230708] multipeer session: start timer: 0x1d4a4d50
2016-,01-19 13:08:21.606 ThaliTest[1663:5230708] server session: connect
2016-01-19 13:08:21.606 ThaliTest[1663:5230708] server session: stateChange:0->1 1453205298295.2303
2016-01-19 13:08:21.612 ThaliTest[1663:5230708] server: accepting invitation 1453205298295.2303
,2016-01-19 13:08:22.955 ThaliTest[1663:5232349] client session: connected
,2016-01-19 13:08:22.955 ThaliTest[1663:5232349] client session: stateChange:1->2 1453205298295.2303.TUJ6lA==
,2016-01-19 13:08:22.960 ThaliTest[1663:5232349] client session: fireConnectCallback: 1453205298295.2303.TUJ6lA==
2016-01-19 13:08:22.960 ThaliTest[1663:5232349] jxcore: connect: success
ok 94 Should be able to connect without error

ok 95 Port should be within range

ok 96 First connect should succeed

,2016-01-19 13:08:22.990 ThaliTest[1663:5230708] client: relay established
2016-01-19 13:08:22.990 ThaliTest[1663:5230708] client: new accepted socket: 0x1d9613f0
,ok 97 the test messages should be equal

,ok 98 First send should succeed

,2016-01-19 13:08:23.040 ThaliTest[1663:5230708] client: socket closed
2016-01-19 13:08:23.040 ThaliTest[1663:5230708] client relay: socket disconnected
2016-01-19 13:08:23.041 ThaliTest[1663:5230708] client relay: 0x1d9613f0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 13:08:23.041 ThaliTest[1663:5230708] client session: socket closed: 1453205298295.2303.TUJ6lA==
2016-01-19 ,13:08:23.041 ThaliTest[1663:5230708] client session: onLinkFailure: 1453205298295.2303.TUJ6lA==
2016-01-19 13:08:23.042 ThaliTest[1663:5230708] client session: disconnect
2016-01-19 13:08:23.042 ThaliTest[1663:5230708] client session: stateChange:2->0 14,53205298295.2303.TUJ6lA==
2016-01-19 13:08:23.049 ThaliTest[1663:5230708] client session: fireConnectionErrorEvent: 1453205298295.2303.TUJ6lA==
2016-01-19 13:08:23.052 ThaliTest[1663:5230915] jxcore: connect 1453205298295.2303.TUJ6lA==
2016-01-19 13:08,:23.052 ThaliTest[1663:5230915] client session: connect
,2016-01-19 13:08:23.057 ThaliTest[1663:5230915] client session: stateChange:0->1 1453205298295.2303.TUJ6lA==
,2016-01-19 13:08:24.014 ThaliTest[1663:5230708] client: lost peer: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:24.014 ThaliTest[1663:5230708] client session: onPeerLost: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:24.014 ThaliTest[1663:5230708] client ,session: onLinkFailure: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:24.014 ThaliTest[1663:5230708] client session: disconnect
2016-01-19 13:08:24.014 ThaliTest[1663:5230708] client session: stateChange:1->0 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:,24.015 ThaliTest[1663:5230708] client session: fireConnectCallback: 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:24.015 ThaliTest[1663:5230708] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1453205286647.2303.1bqqgQ==","peerName":"(null)","peerAvailable":false}]

,2016-01-19 13:08:24.233 ThaliTest[1663:5232362] server session: connected
,2016-01-19 13:08:24.234 ThaliTest[1663:5232362] server session: stateChange:1->2 1453205298295.2303
,2016-01-19 13:08:24.239 ThaliTest[1663:5230708] server relay: connected (to port: 55459)
,2016-01-19 13:08:24.371 ThaliTest[1663:5232349] server session: not connected 1453205298295.2303
,2016-01-19 13:08:24.426 ThaliTest[1663:5230708] multipeer session: reset timer
2016-01-19 13:08:24.426 ThaliTest[1663:5230708] multipeer session: stop timer
2016-01-19 13:08:24.426 ThaliTest[1663:5230708] multipeer session: start timer: 0x1d4a4d50
2016-,01-19 13:08:24.426 ThaliTest[1663:5230708] server: disconnecting to refresh session (1453205298295.2303)
2016-01-19 13:08:24.426 ThaliTest[1663:5230708] server session: disconnect
2016-01-19 13:08:24.426 ThaliTest[1663:5230708] server session: stateChang,e:2->0 1453205298295.2303
2016-01-19 13:08:24.429 ThaliTest[1663:5230708] server session: connect
2016-01-19 13:08:24.429 ThaliTest[1663:5230708] server session: stateChange:0->1 1453205298295.2303
2016-01-19 13:08:24.438 ThaliTest[1663:5230708] server:, accepting invitation 1453205298295.2303
,2016-01-19 13:08:25.022 ThaliTest[1663:5230915] jxcore: connect 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:25.022 ThaliTest[1663:5230915] client: connect: unreachable 1453205286647.2303.1bqqgQ==
2016-01-19 13:08:25.022 ThaliTest[1663:5230915] jxcore: c,onnect: fail: Peer unreachable
,2016-01-19 13:08:25.543 ThaliTest[1663:5232373] client session: connected
2016-01-19 13:08:25.543 ThaliTest[1663:5232373] client session: stateChange:1->2 1453205298295.2303.TUJ6lA==
,2016-01-19 13:08:25.547 ThaliTest[1663:5232373] client session: fireConnectCallback: 1453205298295.2303.TUJ6lA==
2016-01-19 13:08:25.548 ThaliTest[1663:5232373] jxcore: connect: success
,ok 99 Should be able to connect without error

,ok 100 Port should be within range

,ok 101 Second connect should succeed

,2016-01-19 13:08:25.570 ThaliTest[1663:5230708] client: relay established
2016-01-19 13:08:25.570 ThaliTest[1663:5230708] client: new accepted socket: 0x1d961a80
,ok 102 the test messages should be equal

,ok 103 Second send should succeed

,# setup

,2016-01-19 13:08:25.636 ThaliTest[1663:5230708] client: socket closed
2016-01-19 13:08:25.636 ThaliTest[1663:5230708] client relay: socket disconnected
,2016-01-19 13:08:25.636 ThaliTest[1663:5230708] client relay: 0x1d961a80 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 13:08:,25.636 ThaliTest[1663:5230708] client session: socket closed: 1453205298295.2303.TUJ6lA==
2016-01-19 13:08:25.636 ThaliTest[1663:5230708] client session: onLinkFailure: 1453205298295.2303.TUJ6lA==
,2016-01-19 13:08:25.637 ThaliTest[1663:5230708] client session: disconnect
2016-01-19 13:08:25.637 ThaliTest[1663:5230708] client session: stateChange:2->0 1453205298295.2303.TUJ6lA==
,2016-01-19 13:08:25.653 ThaliTest[1663:5230708] client session: fireConnectionErrorEvent: 1453205298295.2303.TUJ6lA==
,2016-01-19 13:08:26.920 ThaliTest[1663:5232349] server session: connected
2016-01-19 13:08:26.921 ThaliTest[1663:5232349] server session: stateChange:1->2 1453205298295.2303
2016-01-19 13:08:26.925 ThaliTest[1663:5230708] server relay: connected (to port: 55459)
,2016-01-19 13:08:27.047 ThaliTest[1663:5232349] server session: not connected 1453205298295.2303
,calling stopBroadcasting

,2016-01-19 13:08:27.246 ThaliTest[1663:5230915] jxcore: stopBroadcasting
2016-01-19 13:08:27.246 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
2016-01-19 13:08:27.246 ThaliTest[1663:5230915] multipeer session: stop timer
2016-01-19 13:08:27.,247 ThaliTest[1663:5230915] server session: disconnect
2016-01-19 13:08:27.247 ThaliTest[1663:5230915] server session: stateChange:2->0 1453205298295.2303
2016-01-19 13:08:27.250 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F3672BBA-5B4D-4E54-A592-17A8864E25D2/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 104 starting event should occur in right order

,2016-01-19 13:08:27.719 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:08:27.722 ThaliTest[1663:5230915] server: starting ZALoHjYW3sRDixBUBWPxWw.Z2kyJw==
,2016-01-19 13:08:27.724 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d4445c0
,2016-01-19 13:08:27.730 ThaliTest[1663:5230915] THEMultipeerSession initialized peer ZALoHjYW3sRDixBUBWPxWw
,2016-01-19 13:08:27.731 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
,ok 105 started event should occur in right order

Now in TRM stop

,State of this._isStarted: true
,
,ok 106 stopping event should occur in right order

,About to call stopBroadcasting

,2016-01-19 13:08:27.736 ThaliTest[1663:5230915] jxcore: stopBroadcasting
,2016-01-19 13:08:27.737 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:08:27.738 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:08:27.741 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 107 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F3672BBA-5B4D-4E54-A592-17A8864E25D2/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 13:08:41.343 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:08:41.345 ThaliTest[1663:5230915] server: starting ZALoHjYW3sRDixBUBWPxWw.Zkqddw==
2016-01-19 13:08:41.345 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d967090
2016-01-19 13:08:41.346 ThaliTest[1663:5230915] THEMultipeerSession initialized peer ZALoHjYW3sRDixBUBWPxWw
2016-01-19 13:08:41.346 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
,ok 108 getDeviceIdentity should not return an error

,ok 109 deviceName should not be null

Now in TRM stop
,
,State of this._isStarted: true

About to call stopBroadcasting

,2016-01-19 13:08:41.359 ThaliTest[1663:5230915] jxcore: stopBroadcasting
,2016-01-19 13:08:41.360 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:08:41.361 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:08:41.365 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,
,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F3672BBA-5B4D-4E54-A592-17A8864E25D2/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-19 13:09:02.068 ThaliTest[1663:5230915] jxcore: startBroadcasting
,2016-01-19 13:09:02.070 ThaliTest[1663:5230915] server: starting ZALoHjYW3sRDixBUBWPxWw.+7ZUbA==
,2016-01-19 13:09:02.072 ThaliTest[1663:5230915] multipeer session: start timer: 0x1d437150
,2016-01-19 13:09:02.078 ThaliTest[1663:5230915] THEMultipeerSession initialized peer ZALoHjYW3sRDixBUBWPxWw
,2016-01-19 13:09:02.081 ThaliTest[1663:5230708] client: found peer: 6gP7M22GtxeQW1i5FtSKJw.IJ9dOQ==
2016-01-19 13:09:02.082 ThaliTest[1663:5230915] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error

ok 111 deviceNam,e should not be null

,2016-01-19 13:09:11.983 ThaliTest[1663:5230915] jxcore: connect 6gP7M22GtxeQW1i5FtSKJw.IJ9dOQ==
,2016-01-19 13:09:11.990 ThaliTest[1663:5230915] client session: connect
,2016-01-19 13:09:11.991 ThaliTest[1663:5230915] client session: stateChange:0->1 6gP7M22GtxeQW1i5FtSKJw.IJ9dOQ==
,2016-01-19 13:09:12.059 ThaliTest[1663:5230708] multipeer session: reset timer
2016-01-19 13:09:12.060 ThaliTest[1663:5230708] multipeer session: stop timer
2016-01-19 13:09:12.061 ThaliTest[1663:5230708] multipeer session: start timer: 0x1d437150
2016-,01-19 13:09:12.061 ThaliTest[1663:5230708] server session: connect
2016-01-19 13:09:12.061 ThaliTest[1663:5230708] server session: stateChange:0->1 6gP7M22GtxeQW1i5FtSKJw
2016-01-19 13:09:12.067 ThaliTest[1663:5230708] server: accepting invitation 6gP7M22GtxeQW1i5FtSKJw
,ok 112 Should be able to put doc without error
,
,ok 113 1st change of local doc should contain local id
,
,2016-01-19 13:09:14.642 ThaliTest[1663:5232472] server session: connected
2016-01-19 13:09:14.642 ThaliTest[1663:5232472] server session: stateChange:1->2 6gP7M22GtxeQW1i5FtSKJw
,2016-01-19 13:09:14.693 ThaliTest[1663:5232520] client session: connected
2016-01-19 13:09:14.697 ThaliTest[1663:5232520] client session: stateChange:1->2 6gP7M22GtxeQW1i5FtSKJw.IJ9dOQ==
,2016-01-19 13:09:14.703 ThaliTest[1663:5230708] server relay: connected (to port: 55476)
,server bridge: new client socket

,2016-01-19 13:09:14.752 ThaliTest[1663:5232472] client session: fireConnectCallback: 6gP7M22GtxeQW1i5FtSKJw.IJ9dOQ==
2016-01-19 13:09:14.752 ThaliTest[1663:5232472] jxcore: connect: success
2016-01-19 13:09:14.756 ThaliTest[1663:5230708] client: relay es,tablished
2016-01-19 13:09:14.757 ThaliTest[1663:5230708] client: new accepted socket: 0x1da8fc90
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

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: socket closed

,ok 114 1st change of remote doc should contain remote id

,client bridge: new client socket

,ok 115 Can update remote doc without error

,null

,{ ok: true,
  id: '9c2c3b56-9092-4277-b06f-56a75500fa93',
  rev: '2-2c2563071a82def527061a1a7567a67e' }

,client bridge: new client socket

,ok 116 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
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
,
,client bridge: new client socket
,
,client bridge: socket closed

,ok 117 Local changes occur in strict order

,ok 118 2nd change of local doc should contain remote id
,
,# setup
,
,client bridge: new client socket

,Now in TRM stop

,State of this._isStarted: true
,
,About to call stopBroadcasting
,
,2016-01-19 13:09:33.302 ThaliTest[1663:5230915] jxcore: stopBroadcasting
,2016-01-19 13:09:33.304 ThaliTest[1663:5230915] THEMultipeerSession stopping peer
,2016-01-19 13:09:33.304 ThaliTest[1663:5230915] multipeer session: stop timer
,2016-01-19 13:09:33.305 ThaliTest[1663:5230915] client session: disconnect
,2016-01-19 13:09:33.305 ThaliTest[1663:5230915] client session: stateChange:2->0 6gP7M22GtxeQW1i5FtSKJw.IJ9dOQ==
,2016-01-19 13:09:33.357 ThaliTest[1663:5232473] server session: not connected 6gP7M22GtxeQW1i5FtSKJw
,2016-01-19 13:09:33.379 ThaliTest[1663:5230915] server session: disconnect
,2016-01-19 13:09:33.380 ThaliTest[1663:5230915] server session: stateChange:2->0 6gP7M22GtxeQW1i5FtSKJw
,2016-01-19 13:09:33.447 ThaliTest[1663:5230915] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,mux server bridge listener closed

2016-01-19 13:09:33.474 ThaliTest[1663:5230915] Error!: connect ECONNRESET
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$09","_lineNumber":"829","_columnNumber":"13","_msg":"    at $09@net.js:829:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
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
    _msg: ',    at $09@net.js:829:13' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
