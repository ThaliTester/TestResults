#### Test 573480789efee08_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/69E2B1EA-295F-4D90-B3D4-3A19F0B64E00/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/69E2B1EA-295F-4D90-B3D4-3A19F0B64E00/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B9B409D6-EBA1-4069-8092-7E42EB307D4C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62093"
,(lldb)     command script import "/tmp/69E2B1EA-295F-4D90-B3D4-3A19F0B64E00/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-28 12:43:58.848 ThaliTest[2048:6603180] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C6D9761A-C8B8-49D9-BB7B-5546DE2B8A7B/Library/Cookies/Cookies.binarycookies
,2016-01-28 12:43:58.983 ThaliTest[2048:6603180] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-28 12:43:58.985 ThaliTest[2048:6603180] Multi-tasking -> Device: YES, App: YES
,2016-01-28 12:43:58.990 ThaliTest[2048:6603180] Unlimited access to network resources
,2016-01-28 12:43:59.004 ThaliTest[2048:6603180] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-28 12:44:05.385 ThaliTest[2048:6603180] Resetting plugins due to page load.
,2016-01-28 12:44:07.663 ThaliTest[2048:6603180] Finished load of: file:///var/mobile/Containers/Bundle/Application/B9B409D6-EBA1-4069-8092-7E42EB307D4C/ThaliTest.app/www/index.html
,2016-01-28 12:44:07.856 ThaliTest[2048:6603180] JXcore Cordova plugin initializing
,2016-01-28 12:44:07.857 ThaliTest[2048:6603556] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9B409D6-EBA1-4069-8092-7E42EB307D4C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9B409D6-EBA1-4069-8092-7E42EB307D4C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9B409D6-EBA1-4069-8092-7E42EB307D4C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9B409D6-EBA1-4069-8092-7E42EB307D4C/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9B409D6-EBA1-4069-8092-7E42EB307D4C/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9B409D6-EBA1-4069-8092-7E42EB307D4C/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9B409D6-EBA1-4069-8092-7E42EB307D4C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B9B409D6-EBA1-4069-8092-7E42EB307D4C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

# setup

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

ok 16 should be equal

,ok 17 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

,ok 21 should be equal

,ok 22 should be equal

# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 23 should be equal

# setup

,# failed to get mobile documents path

,# teardown

,ok 24 should be equal

# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 25 should be equal

ok 26 should be equal

ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 29 should throw

,# setup
,
,# #startBroadcasting should throw on empty string device name
,
,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

# setup

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

ok 39 should be equal

ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

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

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

,ok 51 should be equal

# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

ok 53 should be equal

# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-28 12:49:59.786 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:49:59.796 ThaliTest[2048:6603556] server: starting 1453981799786.2048.1502cw==
2016-01-28 12:49:59.797 ThaliTest[2048:6603556] multipeer session: start timer: 0x1d932230
2016-01-28 12:49:59.797 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981799786.2048
2016-01-28 12:49:59.797 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

2016-01-28 12:49:59.799 ThaliTest[2048:6603556] jxcore: stopBroadcasting,
2016-01-28 12:49:59.799 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
2016-01-28 12:49:59.799 ThaliTest[2048:6603556] multipeer session: stop timer
2016-01-28 12:49:59.800 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
ok 55 Shou,ld be able to call stopBroadcasting without error

2016-01-28 12:49:59.801 ThaliTest[2048:6603556] jxcore: startBroadcasting
2016-01-28 12:49:59.804 ThaliTest[2048:6603556] server: starting 1453981799801.2048.h4YPSw==
2016-01-28 12:49:59.805 ThaliTest[,2048:6603556] multipeer session: start timer: 0x1e4df5b0
2016-01-28 12:49:59.810 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981799801.2048
2016-01-28 12:49:59.811 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 56 Sho,uld be able to call startBroadcasting without error

2016-01-28 12:49:59.812 ThaliTest[2048:6603556] jxcore: stopBroadcasting
2016-01-28 12:49:59.815 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
2016-01-28 12:49:59.815 ThaliTest[2048:6603556] multipeer session: stop timer
2016-01-28 12:49:59.815 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error
,
,2016-01-28 12:49:59.827 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:49:59.831 ThaliTest[2048:6603556] server: starting 1453981799827.2048.KKgjOw==
,2016-01-28 12:49:59.836 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e4c7c10
,2016-01-28 12:49:59.839 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981799827.2048
,2016-01-28 12:49:59.841 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.844 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:49:59.845 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.847 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:49:59.851 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error
,
,2016-01-28 12:49:59.855 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:49:59.859 ThaliTest[2048:6603556] server: starting 1453981799855.2048.PAp/KA==
,2016-01-28 12:49:59.863 ThaliTest[2048:6603556] multipeer session: start timer: 0x1d931970
,2016-01-28 12:49:59.867 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981799855.2048
,2016-01-28 12:49:59.868 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.879 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:49:59.880 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.882 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:49:59.886 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error
,
,2016-01-28 12:49:59.890 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:49:59.893 ThaliTest[2048:6603556] server: starting 1453981799889.2048.n6BJPQ==
,2016-01-28 12:49:59.902 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e46e120
,2016-01-28 12:49:59.903 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981799889.2048
,2016-01-28 12:49:59.904 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.908 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:49:59.909 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.910 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:49:59.914 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error
,
,2016-01-28 12:49:59.917 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:49:59.921 ThaliTest[2048:6603556] server: starting 1453981799917.2048.rfWCiw==
,2016-01-28 12:49:59.929 ThaliTest[2048:6603556] multipeer session: start timer: 0x1d911ea0
,2016-01-28 12:49:59.931 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981799917.2048
,2016-01-28 12:49:59.932 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error
,
,2016-01-28 12:49:59.935 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:49:59.937 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.938 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:49:59.941 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-01-28 12:49:59.945 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:49:59.948 ThaliTest[2048:6603556] server: starting 1453981799945.2048.7fAWPQ==
,2016-01-28 12:49:59.950 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e465580
,2016-01-28 12:49:59.956 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981799945.2048
,2016-01-28 12:49:59.957 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.960 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:49:59.960 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.961 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:49:59.962 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-01-28 12:49:59.968 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:49:59.970 ThaliTest[2048:6603556] server: starting 1453981799967.2048.FyGXCg==
,2016-01-28 12:49:59.973 ThaliTest[2048:6603556] multipeer session: start timer: 0x1d912f10
,2016-01-28 12:49:59.974 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981799967.2048
,2016-01-28 12:49:59.977 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-28 12:49:59.982 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:49:59.983 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:49:59.985 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:49:59.987 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-01-28 12:49:59.992 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:49:59.995 ThaliTest[2048:6603556] server: starting 1453981799992.2048.vskORA==
,2016-01-28 12:49:59.997 ThaliTest[2048:6603556] multipeer session: start timer: 0x1d913450
,2016-01-28 12:49:59.999 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981799992.2048
,2016-01-28 12:50:00.004 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-28 12:50:00.013 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:50:00.013 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:50:00.018 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:50:00.019 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error
,
,2016-01-28 12:50:00.024 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:50:00.027 ThaliTest[2048:6603556] server: starting 1453981800024.2048.PzEfDg==
,2016-01-28 12:50:00.029 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e466860
,2016-01-28 12:50:00.032 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981800024.2048
,2016-01-28 12:50:00.037 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-01-28 12:50:00.039 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:50:00.040 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:50:00.041 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:50:00.046 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-28 12:50:00.686 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:50:00.688 ThaliTest[2048:6603556] server: starting 1453981800685.2048.WIYZ4Q==
2016-01-28 12:50:00.688 ThaliTest[2048:6603556] multipeer session: start timer: 0x1d914370
2016-01-28 12:50:00.689 ThaliTest[2048:6603556] THEMultipeerSession in,itialized peer 1453981800685.2048
2016-01-28 12:50:00.689 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-28 12:50:00.690 ThaliTest[2048:6603556] jxcore: startBroadcasting,
2016-01-28 12:50:00.690 ThaliTest[2048:6603556] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

,2016-01-28 12:50:00.692 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:50:00.702 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:50:00.703 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:50:00.704 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-28 12:50:01.703 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:50:01.705 ThaliTest[2048:6603556] server: starting 1453981801702.2048.gviZgA==
2016-01-28 12:50:01.705 ThaliTest[2048:6603556] multipeer session: start timer: 0x1db61790
2016-01-28 12:50:01.705 ThaliTest[2048:6603556] THEMultipeerSession in,itialized peer 1453981801702.2048
2016-01-28 12:50:01.705 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-28 12:50:01.707 ThaliTest[2048:6603556] jxcore: connect foobar
2,016-01-28 12:50:01.707 ThaliTest[2048:6603556] client: unknown peer foobar
2016-01-28 12:50:01.707 ThaliTest[2048:6603556] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-01-28 12:50:01.710 ThaliTest[2048:6603556] jxcore: stopBroadcasting
2016-01-28 12:50:01.710 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
2016-01-28 12:50:01.710 ThaliTest[2048:6603556] multipeer session: stop timer
2016-01-28 12:50:01.711 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-28 12:50:02.824 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:50:02.826 ThaliTest[2048:6603556] server: starting 1453981802824.2048.2SQpQQ==
2016-01-28 12:50:02.826 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e5eaef0
2016-01-28 12:50:02.826 ThaliTest[2048:6603556] THEMultipeerSession in,itialized peer 1453981802824.2048
2016-01-28 12:50:02.827 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-28 12:50:02.828 ThaliTest[2048:6603556] jxcore: disconnect
2016-01-28 12:50:02.828 ThaliTest[2048:6603556] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

,2016-01-28 12:50:02.832 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:50:02.832 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:50:02.833 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:50:02.833 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers
,
,# teardown

,2016-01-28 12:50:03.751 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:50:03.753 ThaliTest[2048:6603556] server: starting 1453981803751.2048.U+sK7A==
2016-01-28 12:50:03.754 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e5ee7c0
2016-01-28 12:50:03.754 ThaliTest[2048:6603556] THEMultipeerSession in,itialized peer 1453981803751.2048
2016-01-28 12:50:03.754 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-28 12:50:05.039 ThaliTest[2048:6603180] client: found peer: 1453981803779.644.6MjRTg==
2016-01-28 12:50:05.040 ThaliTest[2048:6603556] jxcore: connect 1453981803779.644.6MjRTg==
2016-01-28 12:50:05.041 ThaliTest[2048:6603556] client session: connect
2016-01-28 12:50:05.041 ThaliTest[2048:6603556] client session: stateChange:0->1 1453981803779.644.6MjRTg==
,2016-01-28 12:50:05.363 ThaliTest[2048:6603180] multipeer session: reset timer
2016-01-28 12:50:05.363 ThaliTest[2048:6603180] multipeer session: stop timer
2016-01-28 12:50:05.364 ThaliTest[2048:6603180] multipeer session: start timer: 0x1e5ee7c0
2016-01-28 12:50:05.364 ThaliTest[2048:6603180] server session: connect
2016-01-28 12:50:05.364 ThaliTest[2048:6603180] server session: stateChange:0->1 1453981803779.644
,2016-01-28 12:50:05.369 ThaliTest[2048:6603180] server: accepting invitation 1453981803779.644
,2016-01-28 12:50:07.785 ThaliTest[2048:6605362] server session: connected
2016-01-28 12:50:07.785 ThaliTest[2048:6605362] server session: stateChange:1->2 1453981803779.644
,2016-01-28 12:50:07.801 ThaliTest[2048:6603180] server relay: socket disconnected
2016-01-28 12:50:07.801 ThaliTest[2048:6603180] server relay: 0x1df1a8a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-28 12:50:08.121 ThaliTest[2048:6605361] client session: connected
2016-01-28 12:50:08.122 ThaliTest[2048:6605361] client session: stateChange:1->2 1453981803779.644.6MjRTg==
,2016-01-28 12:50:08.199 ThaliTest[2048:6605362] client session: fireConnectCallback: 1453981803779.644.6MjRTg==
2016-01-28 12:50:08.199 ThaliTest[2048:6605362] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be, within range

2016-01-28 12:50:08.202 ThaliTest[2048:6603556] jxcore: disconnect
2016-01-28 12:50:08.202 ThaliTest[2048:6603556] client session: disconnectFromPeer: 1453981803779.644.6MjRTg==
2016-01-28 12:50:08.202 ThaliTest[2048:6603556] client sess,ion: disconnect
2016-01-28 12:50:08.202 ThaliTest[2048:6603556] client session: stateChange:2->0 1453981803779.644.6MjRTg==
,2016-01-28 12:50:08.217 ThaliTest[2048:6603556] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-28 12:50:08.582 ThaliTest[2048:6603556] jxcore: stopBroadcasting
2016-01-28 12:50:08.582 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
2016-01-28 12:50:08.582 ThaliTest[2048:6603556] multipeer session: stop timer
2016-01-28 12:50:08.583 ThaliTest[2048:6603556] server session: disconnect
2016-01-28 12:50:08.583 ThaliTest[2048:6603556] server session: stateChange:2->0 1453981803779.644
,2016-01-28 12:50:08.594 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-28 12:50:09.111 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:50:09.114 ThaliTest[2048:6603556] server: starting 1453981809111.2048.Ixzgqw==
2016-01-28 12:50:09.114 ThaliTest[2048:6603556] multipeer session: start timer: 0x1df1b600
2016-01-28 12:50:09.115 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981809111.2048
2016-01-28 12:50:09.115 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-28 12:50:10.276 ThaliTest[2048:6603180] client: found peer: 1453981809100.644.hpMmFQ==
2016-01-28 12:50:10.278 ThaliTest[2048:6603556] jxcore: connect 1453981809100.644.hpMmFQ==
2016-01-28 12:50:10.278 ThaliTest[2048:6603556] client session: connect
2016-01-28 12:50:10.278 ThaliTest[2048:6603556] client session: stateChange:0->1 1453981809100.644.hpMmFQ==
,2016-01-28 12:50:10.799 ThaliTest[2048:6603180] multipeer session: reset timer
2016-01-28 12:50:10.800 ThaliTest[2048:6603180] multipeer session: stop timer
,2016-01-28 12:50:10.800 ThaliTest[2048:6603180] multipeer session: start timer: 0x1df1b600
2016-01-28 12:50:10.801 ThaliTest[2048:6603180] server session: connect
2016-01-28 12:50:10.802 ThaliTest[2048:6603180] server session: stateChange:0->1 1453981809,100.644
,2016-01-28 12:50:10.814 ThaliTest[2048:6603180] server: accepting invitation 1453981809100.644
,2016-01-28 12:50:13.016 ThaliTest[2048:6605359] client session: connected
2016-01-28 12:50:13.016 ThaliTest[2048:6605359] client session: stateChange:1->2 1453981809100.644.hpMmFQ==
,2016-01-28 12:50:13.046 ThaliTest[2048:6605358] client session: fireConnectCallback: 1453981809100.644.hpMmFQ==
2016-01-28 12:50:13.046 ThaliTest[2048:6605358] jxcore: connect: success
ok 88 Should be able to connect without error

ok 89 Port should be within range

2016-01-28 12:50:13.048 ThaliTest[2048:6603556] jxcore: connect 1453981809100.644.hpMmFQ==
2016-01-28 12:50:13.048 ThaliTest[2048:6603556] client: already connect(ing/ed) to 1453981809100.644.hpMmFQ==
2016-01-28 12:50:13.048 ThaliTest[20,48:6603556] jxcore: connect: fail: Aleady connecting
ok 90 Should fail on double connect

2016-01-28 12:50:13.050 ThaliTest[2048:6603556] jxcore: disconnect
2016-01-28 12:50:13.050 ThaliTest[2048:6603556] client session: disconnectFromPeer: 14539818091,00.644.hpMmFQ==
2016-01-28 12:50:13.050 ThaliTest[2048:6603556] client session: disconnect
2016-01-28 12:50:13.050 ThaliTest[2048:6603556] client session: stateChange:2->0 1453981809100.644.hpMmFQ==
,2016-01-28 12:50:13.064 ThaliTest[2048:6603556] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-01-28 12:50:13.495 ThaliTest[2048:6605359] server session: connected
2016-01-28 12:50:13.495 ThaliTest[2048:6605359] server session: stateChange:1->2 1453981809100.644
,2016-01-28 12:50:13.527 ThaliTest[2048:6603180] server relay: socket disconnected
2016-01-28 12:50:13.527 ThaliTest[2048:6603180] server relay: 0x1e5e11f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-28 12:50:13.563 ThaliTest[2048:6605359] server session: not connected 1453981809100.644
,calling stopBroadcasting

2016-01-28 12:50:13.832 ThaliTest[2048:6603556] jxcore: stopBroadcasting
2016-01-28 12:50:13.832 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
2016-01-28 12:50:13.833 ThaliTest[2048:6603556] multipeer session: stop, timer
2016-01-28 12:50:13.833 ThaliTest[2048:6603556] server session: disconnect
2016-01-28 12:50:13.833 ThaliTest[2048:6603556] server session: stateChange:2->0 1453981809100.644
,2016-01-28 12:50:13.834 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-28 12:50:14.349 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:50:14.352 ThaliTest[2048:6603556] server: starting 1453981814349.2048.VHQOnA==
2016-01-28 12:50:14.353 ThaliTest[2048:6603556] multipeer session: start timer: 0x1df1b670
2016-01-28 12:50:14.353 ThaliTest[2048:6603556] THEMultipeerSession in,itialized peer 1453981814349.2048
2016-01-28 12:50:14.353 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-28 12:50:15.527 ThaliTest[2048:6603180] client: found peer: 1453981814342.644.otjf6Q==
2016-01-28 12:50:15.528 ThaliTest[2048:6603556] jxcore: connect 1453981814342.644.otjf6Q==
2016-01-28 12:50:15.528 ThaliTest[2048:6603556] client session: conn,ect
2016-01-28 12:50:15.529 ThaliTest[2048:6603556] client session: stateChange:0->1 1453981814342.644.otjf6Q==
,2016-01-28 12:50:15.785 ThaliTest[2048:6603180] multipeer session: reset timer
2016-01-28 12:50:15.785 ThaliTest[2048:6603180] multipeer session: stop timer
,2016-01-28 12:50:15.785 ThaliTest[2048:6603180] multipeer session: start timer: 0x1df1b670
,2016-01-28 12:50:15.786 ThaliTest[2048:6603180] server session: connect
2016-01-28 12:50:15.786 ThaliTest[2048:6603180] server session: stateChange:0->1 1453981814342.644
,2016-01-28 12:50:15.792 ThaliTest[2048:6603180] server: accepting invitation 1453981814342.644
,2016-01-28 12:50:18.275 ThaliTest[2048:6605361] client session: connected
2016-01-28 12:50:18.276 ThaliTest[2048:6605361] client session: stateChange:1->2 1453981814342.644.otjf6Q==
,2016-01-28 12:50:18.283 ThaliTest[2048:6605362] client session: fireConnectCallback: 1453981814342.644.otjf6Q==
2016-01-28 12:50:18.283 ThaliTest[2048:6605362] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be within range

,2016-01-28 12:50:18.285 ThaliTest[2048:6603556] jxcore: disconnect
2016-01-28 12:50:18.286 ThaliTest[2048:6603556] client session: disconnectFromPeer: 1453981814342.644.otjf6Q==
2016-01-28 12:50:18.286 ThaliTest[2048:6603556] client session: disconnect
2016-01-28 12:50:18.286 ThaliTest[2048:6603556] client session: stateChange:2->0 1453981814342.644.otjf6Q==
,2016-01-28 12:50:18.357 ThaliTest[2048:6603556] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-01-28 12:50:18.358 ThaliTest[2048:6603556] jxcore: disconnect
2016-01-28 12:50:18.358 ThaliTest[2048:6603556] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-28 12:50:18.463 ThaliTest[2048:6605358] server session: connected
2016-01-28 12:50:18.463 ThaliTest[2048:6605358] server session: stateChange:1->2 1453981814342.644
,2016-01-28 12:50:18.469 ThaliTest[2048:6603180] server relay: socket disconnected
2016-01-28 12:50:18.469 ThaliTest[2048:6603180] server relay: 0x1e3f2f90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-28 12:50:18.518 ThaliTest[2048:6605361] server session: not connected 1453981814342.644
,calling stopBroadcasting

,2016-01-28 12:50:18.553 ThaliTest[2048:6603556] jxcore: stopBroadcasting
2016-01-28 12:50:18.553 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
2016-01-28 12:50:18.553 ThaliTest[2048:6603556] multipeer session: stop timer
2016-01-28 12:50:18.,553 ThaliTest[2048:6603556] server session: disconnect
2016-01-28 12:50:18.554 ThaliTest[2048:6603556] server session: stateChange:2->0 1453981814342.644
2016-01-28 12:50:18.554 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 58538

,2016-01-28 12:50:20.354 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:50:20.357 ThaliTest[2048:6603556] server: starting 1453981820354.2048.JaM5Ig==
2016-01-28 12:50:20.358 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e5f54d0
2016-01-28 12:50:20.358 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981820354.2048
2016-01-28 12:50:20.358 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-01-28 12:50:20.834 ThaliTest[2048:6603180] client: found peer: 1453981819665.644.F/or/w==
2016-01-28 12:50:20.835 ThaliTest[2048:6603556] jxcore: connect 1453981819665.644.F/or/w==
2016-01-28 12:50:20.835 ThaliTest[2048:6603556] client session: conn,ect
2016-01-28 12:50:20.835 ThaliTest[2048:6603556] client session: stateChange:0->1 1453981819665.644.F/or/w==
,2016-01-28 12:50:21.547 ThaliTest[2048:6603180] multipeer session: reset timer
2016-01-28 12:50:21.547 ThaliTest[2048:6603180] multipeer session: stop timer
2016-01-28 12:50:21.547 ThaliTest[2048:6603180] multipeer session: start timer: 0x1e5f54d0
2016-,01-28 12:50:21.547 ThaliTest[2048:6603180] server session: connect
2016-01-28 12:50:21.548 ThaliTest[2048:6603180] server session: stateChange:0->1 1453981819665.644
,2016-01-28 12:50:21.556 ThaliTest[2048:6603180] server: accepting invitation 1453981819665.644
,2016-01-28 12:50:24.140 ThaliTest[2048:6605359] client session: connected
2016-01-28 12:50:24.140 ThaliTest[2048:6605359] client session: stateChange:1->2 1453981819665.644.F/or/w==
,2016-01-28 12:50:24.143 ThaliTest[2048:6605359] client session: fireConnectCallback: 1453981819665.644.F/or/w==
2016-01-28 12:50:24.143 ThaliTest[2048:6605359] jxcore: connect: success
ok 98 Should be able to connect without error

ok 99 Port should be within range

,2016-01-28 12:50:24.147 ThaliTest[2048:6603180] client: relay established
2016-01-28 12:50:24.147 ThaliTest[2048:6603180] client: new accepted socket: 0x1e575530
,data in 2190

,data in 9855

,data in 10950

,data in 15330
,
,data in 26280

,data in 29352

,data in 44611

,data in 65274

,data in 84315

,data in 87600

,data in 95265

,data in 96360

,data in 98408

,data in 120450

,2016-01-28 12:50:24.639 ThaliTest[2048:6605359] server session: connected
,2016-01-28 12:50:24.640 ThaliTest[2048:6605359] server session: stateChange:1->2 1453981819665.644
,2016-01-28 12:50:24.700 ThaliTest[2048:6603180] server relay: connected (to port: 58538)
,data in 125925

,data in 131072

,ok 100 the test messages should be equal

,2016-01-28 12:50:24.722 ThaliTest[2048:6603556] jxcore: disconnect
,2016-01-28 12:50:24.723 ThaliTest[2048:6603556] client session: disconnectFromPeer: 1453981819665.644.F/or/w==
,2016-01-28 12:50:24.723 ThaliTest[2048:6603556] client session: disconnect
,2016-01-28 12:50:24.723 ThaliTest[2048:6603556] client session: stateChange:2->0 1453981819665.644.F/or/w==
,2016-01-28 12:50:24.733 ThaliTest[2048:6603556] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-01-28 12:50:25.693 ThaliTest[2048:6605415] server session: not connected 1453981819665.644
,calling stopBroadcasting

2016-01-28 12:50:25.881 ThaliTest[2048:6603556] jxcore: stopBroadcasting
2016-01-28 12:50:25.881 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
2016-01-28 12:50:25.882 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:50:25.882 ThaliTest[2048:6603556] server session: disconnect
2016-01-28 12:50:25.882 ThaliTest[2048:6603556] server session: stateChange:2->0 1453981819665.644
2016-01-28 12:50:25.886 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 58544

2016-01-28 12:50:26.470 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:50:26.473 ThaliTest[2048:6603556] server: starting 1453981826470.2048.JUV1sA==
2016-01-28 12:50:26.474 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e3f69e0
2016-01-28 12:50:26.474 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 1453981826470.2048
2016-01-28 12:50:26.474 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-28 12:50:27.641 ThaliTest[2048:6603180] client: found peer: 1453981826405.644.NvlxHg==
[{"peerIdentifier":"1453981826405.644.NvlxHg==","peerName":"(null)","peerAvailable":true}]

2016-01-28 12:50:27.643 ThaliTest[2048:6603556] jxcore: connect 1453981826405.644.NvlxHg==
,2016-01-28 12:50:27.644 ThaliTest[2048:6603556] client session: connect
2016-01-28 12:50:27.644 ThaliTest[2048:6603556] client session: stateChange:0->1 1453981826405.644.NvlxHg==
,2016-01-28 12:50:27.841 ThaliTest[2048:6603180] multipeer session: reset timer
2016-01-28 12:50:27.841 ThaliTest[2048:6603180] multipeer session: stop timer
2016-01-28 12:50:27.841 ThaliTest[2048:6603180] multipeer session: start timer: 0x1e3f69e0
2016-,01-28 12:50:27.841 ThaliTest[2048:6603180] server session: connect
2016-01-28 12:50:27.842 ThaliTest[2048:6603180] server session: stateChange:0->1 1453981826405.644
,2016-01-28 12:50:27.848 ThaliTest[2048:6603180] server: accepting invitation 1453981826405.644
,2016-01-28 12:50:30.398 ThaliTest[2048:6605361] server session: connected
2016-01-28 12:50:30.398 ThaliTest[2048:6605361] server session: stateChange:1->2 1453981826405.644
,2016-01-28 12:50:30.468 ThaliTest[2048:6603180] server relay: connected (to port: 58544)
,2016-01-28 12:50:30.534 ThaliTest[2048:6605359] client session: connected
2016-01-28 12:50:30.534 ThaliTest[2048:6605359] client session: stateChange:1->2 1453981826405.644.NvlxHg==
,2016-01-28 12:50:30.592 ThaliTest[2048:6605363] client session: fireConnectCallback: 1453981826405.644.NvlxHg==
2016-01-28 12:50:30.592 ThaliTest[2048:6605363] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

ok 105 First connect should succeed

,2016-01-28 12:50:30.606 ThaliTest[2048:6605359] server session: not connected 1453981826405.644
,2016-01-28 12:50:30.618 ThaliTest[2048:6603180] client: relay established
2016-01-28 12:50:30.618 ThaliTest[2048:6603180] client: new accepted socket: 0x1e5772e0
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-01-28 12:50:30.697 ThaliTest[2048:6603180] client: socket closed
,2016-01-28 12:50:30.697 ThaliTest[2048:6603180] client relay: socket disconnected
,2016-01-28 12:50:30.697 ThaliTest[2048:6603180] client relay: 0x1e5772e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-28 12:50:,30.697 ThaliTest[2048:6603180] client session: socket closed: 1453981826405.644.NvlxHg==
2016-01-28 12:50:30.697 ThaliTest[2048:6603180] client session: onLinkFailure: 1453981826405.644.NvlxHg==
,2016-01-28 12:50:30.698 ThaliTest[2048:6603180] client session: disconnect
2016-01-28 12:50:30.698 ThaliTest[2048:6603180] client session: stateChange:2->0 1453981826405.644.NvlxHg==
,2016-01-28 12:50:30.708 ThaliTest[2048:6603180] client session: fireConnectionErrorEvent: 1453981826405.644.NvlxHg==
,2016-01-28 12:50:30.712 ThaliTest[2048:6603556] jxcore: connect 1453981826405.644.NvlxHg==
,2016-01-28 12:50:30.714 ThaliTest[2048:6603556] client session: connect
,2016-01-28 12:50:30.716 ThaliTest[2048:6603556] client session: stateChange:0->1 1453981826405.644.NvlxHg==
,2016-01-28 12:50:30.726 ThaliTest[2048:6603180] multipeer session: reset timer
2016-01-28 12:50:30.727 ThaliTest[2048:6603180] multipeer session: stop timer
,2016-01-28 12:50:30.727 ThaliTest[2048:6603180] multipeer session: start timer: 0x1e3f69e0
,2016-01-28 12:50:30.728 ThaliTest[2048:6603180] server: disconnecting to refresh session (1453981826405.644)
,2016-01-28 12:50:30.729 ThaliTest[2048:6603180] server session: disconnect
,2016-01-28 12:50:30.730 ThaliTest[2048:6603180] server session: stateChange:2->0 1453981826405.644
,2016-01-28 12:50:30.906 ThaliTest[2048:6603180] server session: connect
2016-01-28 12:50:30.906 ThaliTest[2048:6603180] server session: stateChange:0->1 1453981826405.644
2016-01-28 12:50:30.912 ThaliTest[2048:6603180] server: accepting invitation 1453981826405.644
,2016-01-28 12:50:33.610 ThaliTest[2048:6605416] server session: connected
2016-01-28 12:50:33.610 ThaliTest[2048:6605416] server session: stateChange:1->2 1453981826405.644
,2016-01-28 12:50:33.638 ThaliTest[2048:6603180] server relay: connected (to port: 58544)
,2016-01-28 12:50:33.804 ThaliTest[2048:6605359] server session: not connected 1453981826405.644
,2016-01-28 12:50:33.817 ThaliTest[2048:6605361] client session: connected
2016-01-28 12:50:33.817 ThaliTest[2048:6605361] client session: stateChange:1->2 1453981826405.644.NvlxHg==
,2016-01-28 12:50:33.876 ThaliTest[2048:6605361] client session: fireConnectCallback: 1453981826405.644.NvlxHg==
2016-01-28 12:50:33.876 ThaliTest[2048:6605361] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-01-28 12:50:33.898 ThaliTest[2048:6603180] client: relay established
2016-01-28 12:50:33.898 ThaliTest[2048:6603180] client: new accepted socket: 0x1e3ac800
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-01-28 12:50:33.978 ThaliTest[2048:6603180] client: socket closed
2016-01-28 12:50:33.978 ThaliTest[2048:6603180] client relay: socket disconnected
2016-01-28 12:50:33.978 ThaliTest[2048:6603180] client relay: 0x1e3ac800 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-28 12:50:33.978 ThaliTest[2048:6603180] client session: socket closed: 1453981826405.644.NvlxHg==
2016-01-28 12:50:33.978 ThaliTest[2048:6603180] client session: onLinkFailure: 1453981826405.644.NvlxHg==
2016-01-28 12:50:33.979 ThaliTest[2048:660,3180] client session: disconnect
2016-01-28 12:50:33.979 ThaliTest[2048:6603180] client session: stateChange:2->0 1453981826405.644.NvlxHg==
,2016-01-28 12:50:33.987 ThaliTest[2048:6603180] client session: fireConnectionErrorEvent: 1453981826405.644.NvlxHg==
,calling stopBroadcasting

2016-01-28 12:50:34.478 ThaliTest[2048:6603556] jxcore: stopBroadcasting
2016-01-28 12:50:34.478 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
2016-01-28 12:50:34.478 ThaliTest[2048:6603556] multipeer session: stop, timer
2016-01-28 12:50:34.479 ThaliTest[2048:6603556] server session: disconnect
2016-01-28 12:50:34.479 ThaliTest[2048:6603556] server session: stateChange:2->0 1453981826405.644
2016-01-28 12:50:34.482 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C6D9761A-C8B8-49D9-BB7B-5546DE2B8A7B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-28 12:51:01.390 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:51:01.392 ThaliTest[2048:6603556] server: starting 5lxph6z1iSKyTRJoLzZ-yg.MkVklw==
,2016-01-28 12:51:01.394 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e57ceb0
,2016-01-28 12:51:01.410 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 5lxph6z1iSKyTRJoLzZ-yg
,2016-01-28 12:51:01.411 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

Now in TRM stop

,State of this._isStarted: true

,ok 115 stopping event should occur in right order

About to call stopBroadcasting

,2016-01-28 12:51:01.415 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:51:01.416 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:51:01.417 ThaliTest[2048:6603556] multipeer session: stop timer
,2016-01-28 12:51:01.422 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C6D9761A-C8B8-49D9-BB7B-5546DE2B8A7B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-28 12:51:03.016 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:51:03.019 ThaliTest[2048:6603556] server: starting 5lxph6z1iSKyTRJoLzZ-yg.uROFkA==
2016-01-28 12:51:03.019 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e346990
2016-01-28 12:51:03.019 ThaliTest[2048:6603556] THEMultipeerSessio,n initialized peer 5lxph6z1iSKyTRJoLzZ-yg
2016-01-28 12:51:03.020 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-01-28 12:51:03.021 ThaliTest[2048:6603556] jxcore: stopBroadcasting
2016-01-28 12:51:03.022 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
,2016-01-28 12:51:03.022 ThaliTest[2048:6603556] multipeer session: stop timer
2016-01-28 12:51:03.027 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/C6D9761A-C8B8-49D9-BB7B-5546DE2B8A7B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-28 12:51:09.066 ThaliTest[2048:6603556] jxcore: startBroadcasting
,2016-01-28 12:51:09.069 ThaliTest[2048:6603556] server: starting 5lxph6z1iSKyTRJoLzZ-yg.pd8cJw==
,2016-01-28 12:51:09.072 ThaliTest[2048:6603556] multipeer session: start timer: 0x1e17a2c0
,2016-01-28 12:51:09.077 ThaliTest[2048:6603556] THEMultipeerSession initialized peer 5lxph6z1iSKyTRJoLzZ-yg
,2016-01-28 12:51:09.081 ThaliTest[2048:6603180] client: found peer: Ta0VTXPdONhln0_rgJJe4Q.f1M0Fg==
2016-01-28 12:51:09.082 ThaliTest[2048:6603556] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceNam,e should not be null

,2016-01-28 12:51:19.490 ThaliTest[2048:6603556] jxcore: connect Ta0VTXPdONhln0_rgJJe4Q.f1M0Fg==
,2016-01-28 12:51:19.492 ThaliTest[2048:6603556] client session: connect
,2016-01-28 12:51:19.493 ThaliTest[2048:6603556] client session: stateChange:0->1 Ta0VTXPdONhln0_rgJJe4Q.f1M0Fg==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-01-28 12:51:25.471 ThaliTest[2048:6603180] client: lost peer: Ta0VTXPdONhln0_rgJJe4Q.f1M0Fg==
2016-01-28 12:51:25.471 ThaliTest[2048:6603180] client session: onPeerLost: Ta0VTXPdONhln0_rgJJe4Q.f1M0Fg==
2016-01-28 12:51:25.471 ThaliTest[2048:6603180], client session: onLinkFailure: Ta0VTXPdONhln0_rgJJe4Q.f1M0Fg==
2016-01-28 12:51:25.471 ThaliTest[2048:6603180] client session: disconnect
2016-01-28 12:51:25.471 ThaliTest[2048:6603180] client session: stateChange:1->0 Ta0VTXPdONhln0_rgJJe4Q.f1M0Fg==
2,016-01-28 12:51:25.472 ThaliTest[2048:6603180] client session: fireConnectCallback: Ta0VTXPdONhln0_rgJJe4Q.f1M0Fg==
2016-01-28 12:51:25.472 ThaliTest[2048:6603180] jxcore: connect: fail: Peer disconnected
Connect error with error: Error: Peer disconnected

,2016-01-28 12:51:25.487 ThaliTest[2048:6603556] jxcore: disconnect
2016-01-28 12:51:25.487 ThaliTest[2048:6603556] jxcore: disconnect: fail
Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available Ta0VTXPdONhln0,_rgJJe4Q.f1M0Fg==

,2016-01-28 12:51:39.078 ThaliTest[2048:6603180] multipeer session: restart
,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-28 12:52:08.983 ThaliTest[2048:6603556] jxcore: stopBroadcasting
,2016-01-28 12:52:08.983 ThaliTest[2048:6603556] THEMultipeerSession stopping peer
2016-01-28 12:52:09.026 ThaliTest[2048:6603556] multipeer session: stop timer
2016-01-28 12:52:09.027 ThaliTest[2048:6603556] jxcore: stopBroadcasting: success
Got callbac,k from stopBroadcasting with err undefined

,mux server bridge listener closed


```
