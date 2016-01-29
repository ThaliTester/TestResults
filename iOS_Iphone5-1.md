#### Test 56818254e6f5c3b_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56818254e6f5c3b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F2B93007-37B2-4DD7-B21D-2116EACE09C1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F2B93007-37B2-4DD7-B21D-2116EACE09C1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56818254e6f5c3b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56818254e6f5c3b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/66C8917F-AECD-43A5-B6D2-2B14629F7614/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62963"
,(lldb)     command script import "/tmp/F2B93007-37B2-4DD7-B21D-2116EACE09C1/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 17:39:03.311 ThaliTest[2139:6808794] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5CC5EFA2-BB2C-4F4B-80D5-723BB57A734A/Library/Cookies/Cookies.binarycookies
,2016-01-29 17:39:03.653 ThaliTest[2139:6808794] Apache Cordova native platform version 3.9.2 is starting.
2016-01-29 17:39:03.654 ThaliTest[2139:6808794] Multi-tasking -> Device: YES, App: YES
,2016-01-29 17:39:03.659 ThaliTest[2139:6808794] Unlimited access to network resources
,2016-01-29 17:39:03.670 ThaliTest[2139:6808794] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 17:39:09.703 ThaliTest[2139:6808794] Resetting plugins due to page load.
,2016-01-29 17:39:11.865 ThaliTest[2139:6808794] Finished load of: file:///var/mobile/Containers/Bundle/Application/66C8917F-AECD-43A5-B6D2-2B14629F7614/ThaliTest.app/www/index.html
,2016-01-29 17:39:12.069 ThaliTest[2139:6808794] JXcore Cordova plugin initializing
2016-01-29 17:39:12.070 ThaliTest[2139:6809013] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!
,
,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66C8917F-AECD-43A5-B6D2-2B14629F7614/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66C8917F-AECD-43A5-B6D2-2B14629F7614/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66C8917F-AECD-43A5-B6D2-2B14629F7614/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66C8917F-AECD-43A5-B6D2-2B14629F7614/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66C8917F-AECD-43A5-B6D2-2B14629F7614/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66C8917F-AECD-43A5-B6D2-2B14629F7614/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66C8917F-AECD-43A5-B6D2-2B14629F7614/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66C8917F-AECD-43A5-B6D2-2B14629F7614/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

# setup

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

,# setup

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

ok 16 should be equal

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

# setup

,# failed to get mobile documents path

,# teardown

,ok 24 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 25 should be equal

,ok 26 should be equal

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

# setup

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

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

ok 39 should be equal

ok 40 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

,# setup
,
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

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

ok 53 should be equal

# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-01-29 17:44:32.698 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:32.717 ThaliTest[2139:6809013] server: starting 1454085872698.2139.FDamHg==
,2016-01-29 17:44:32.718 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ab19430
,2016-01-29 17:44:32.726 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085872698.2139
,2016-01-29 17:44:32.727 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

,2016-01-29 17:44:32.729 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:32.730 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.731 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:32.735 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 55 Should be able to call stopBroadcasting without error
,
,2016-01-29 17:44:32.738 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:32.741 ThaliTest[2139:6809013] server: starting 1454085872737.2139.yyXLoQ==
,2016-01-29 17:44:32.743 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ac95340
,2016-01-29 17:44:32.747 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085872737.2139
,2016-01-29 17:44:32.748 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error

,2016-01-29 17:44:32.750 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:32.751 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.752 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:32.761 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-01-29 17:44:32.764 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:32.767 ThaliTest[2139:6809013] server: starting 1454085872763.2139.lYUYkA==
,2016-01-29 17:44:32.772 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ab105f0
,2016-01-29 17:44:32.777 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085872763.2139
,2016-01-29 17:44:32.778 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error
,
,2016-01-29 17:44:32.781 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:32.782 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.782 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:32.786 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-01-29 17:44:32.789 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:32.792 ThaliTest[2139:6809013] server: starting 1454085872789.2139.k4D2Lw==
,2016-01-29 17:44:32.794 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ab123e0
,2016-01-29 17:44:32.803 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085872789.2139
,2016-01-29 17:44:32.804 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-01-29 17:44:32.807 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:32.808 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.808 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:32.814 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-01-29 17:44:32.816 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:32.819 ThaliTest[2139:6809013] server: starting 1454085872816.2139.9HSYqQ==
,2016-01-29 17:44:32.821 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ac71fe0
,2016-01-29 17:44:32.829 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085872816.2139
,2016-01-29 17:44:32.830 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-01-29 17:44:32.832 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:32.833 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.834 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:32.838 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error
,
,2016-01-29 17:44:32.841 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:32.844 ThaliTest[2139:6809013] server: starting 1454085872841.2139.Q3jeTQ==
,2016-01-29 17:44:32.846 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ac70cd0
,2016-01-29 17:44:32.853 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085872841.2139
,2016-01-29 17:44:32.854 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error
,
,2016-01-29 17:44:32.856 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:32.857 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.858 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:32.859 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-01-29 17:44:32.865 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:32.867 ThaliTest[2139:6809013] server: starting 1454085872864.2139.mI1jyA==
,2016-01-29 17:44:32.869 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ab04390
,2016-01-29 17:44:32.871 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085872864.2139
,2016-01-29 17:44:32.873 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error
,
,2016-01-29 17:44:32.879 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:32.880 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.881 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:32.881 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,
,2016-01-29 17:44:32.888 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:32.891 ThaliTest[2139:6809013] server: starting 1454085872888.2139.xrZSZQ==
,2016-01-29 17:44:32.893 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ab04940
,2016-01-29 17:44:32.895 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085872888.2139
,2016-01-29 17:44:32.897 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-29 17:44:32.903 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:32.904 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.905 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:32.907 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error
,
,2016-01-29 17:44:32.912 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:32.915 ThaliTest[2139:6809013] server: starting 1454085872912.2139.yOupHQ==
,2016-01-29 17:44:32.918 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ac72280
,2016-01-29 17:44:32.922 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085872912.2139
,2016-01-29 17:44:32.925 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error
,
,2016-01-29 17:44:32.929 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:32.929 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.930 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:32.931 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error
,
,2016-01-29 17:44:32.937 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:32.940 ThaliTest[2139:6809013] server: starting 1454085872937.2139.ojwTdw==
,2016-01-29 17:44:32.942 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ab046d0
,2016-01-29 17:44:32.945 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085872937.2139
,2016-01-29 17:44:32.950 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-01-29 17:44:32.953 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:32.953 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:32.954 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:32.955 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,
,# setup
,
,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-29 17:44:33.925 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:33.927 ThaliTest[2139:6809013] server: starting 1454085873925.2139.frr6Bg==
2016-01-29 17:44:33.927 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ab074b0
2016-01-29 17:44:33.928 ThaliTest[2139:6809013] THEMultipeerSession in,itialized peer 1454085873925.2139
2016-01-29 17:44:33.928 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-29 17:44:33.929 ThaliTest[2139:6809013] jxcore: startBroadcasting
2016-01-29 17:44:33.929 ThaliTest[2139:6809013] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-01-29 17:44:33.933 ThaliTest[2139:6809013] jxcore: stopBroadcasting
2016-01-29 17:44:33.933 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
2016-01-29 17:44:33.933 ThaliTest[2139:6809013] multipeer session: stop timer
2016-01-29 17:44:33.933 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-29 17:44:38.513 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:38.516 ThaliTest[2139:6809013] server: starting 1454085878513.2139.emTFDw==
2016-01-29 17:44:38.517 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ab0a610
2016-01-29 17:44:38.517 ThaliTest[2139:6809013] THEMultipeerSession in,itialized peer 1454085878513.2139
2016-01-29 17:44:38.517 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-29 17:44:38.518 ThaliTest[2139:6809013] jxcore: connect foobar
2,016-01-29 17:44:38.519 ThaliTest[2139:6809013] client: unknown peer foobar
2016-01-29 17:44:38.519 ThaliTest[2139:6809013] jxcore: connect: fail: Unknown peer
ok 78 Should not connect to a bad peer

2016-01-29 17:44:38.523 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:38.524 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
2016-01-29 17:44:38.524 ThaliTest[2139:6809013] multipeer session: stop timer
2016-01-29 17:44:38.524 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-29 17:44:39.952 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:39.955 ThaliTest[2139:6809013] server: starting 1454085879952.2139.oE6YOQ==
2016-01-29 17:44:39.956 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ab0f870
2016-01-29 17:44:39.956 ThaliTest[2139:6809013] THEMultipeerSession in,itialized peer 1454085879952.2139
2016-01-29 17:44:39.956 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-29 17:44:39.957 ThaliTest[2139:6809013] jxcore: disconnect
2016-01-29 17:44:39.958 ThaliTest[2139:6809013] jxcore: disconnect: fail
ok 81 Disconnect should fail to a non-existant peer 

,2016-01-29 17:44:39.960 ThaliTest[2139:6809013] jxcore: stopBroadcasting
2016-01-29 17:44:39.961 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
2016-01-29 17:44:39.961 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:39.975 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-01-29 17:44:41.367 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:41.369 ThaliTest[2139:6809013] server: starting 1454085881367.2139.Fq/gzg==
2016-01-29 17:44:41.369 ThaliTest[2139:6809013] multipeer session: start timer: 0x1aa08470
2016-01-29 17:44:41.369 ThaliTest[2139:6809013] THEMultipeerSession in,itialized peer 1454085881367.2139
2016-01-29 17:44:41.370 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-29 17:44:42.694 ThaliTest[2139:6808794] client: found peer: 1454085881342.2936.2DH/dw==
2016-01-29 17:44:42.695 ThaliTest[2139:6809013] jxcore: connect 1454085881342.2936.2DH/dw==
2016-01-29 17:44:42.696 ThaliTest[2139:6809013] client session: co,nnect
2016-01-29 17:44:42.696 ThaliTest[2139:6809013] client session: stateChange:0->1 1454085881342.2936.2DH/dw==
,2016-01-29 17:44:43.187 ThaliTest[2139:6808794] multipeer session: reset timer
2016-01-29 17:44:43.187 ThaliTest[2139:6808794] multipeer session: stop timer
2016-01-29 17:44:43.187 ThaliTest[2139:6808794] multipeer session: start timer: 0x1aa08470
2016-,01-29 17:44:43.187 ThaliTest[2139:6808794] server session: connect
2016-01-29 17:44:43.188 ThaliTest[2139:6808794] server session: stateChange:0->1 1454085881342.2936
2016-01-29 17:44:43.195 ThaliTest[2139:6808794] server: accepting invitation 1454085881342.2936
,2016-01-29 17:44:45.620 ThaliTest[2139:6809648] server session: connected
,2016-01-29 17:44:45.620 ThaliTest[2139:6809648] server session: stateChange:1->2 1454085881342.2936
,2016-01-29 17:44:45.631 ThaliTest[2139:6808794] server relay: socket disconnected
2016-01-29 17:44:45.631 ThaliTest[2139:6808794] server relay: 0x1ac9a170 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-29 17:44:45.665 ThaliTest[2139:6809647] server session: not connected 1454085881342.2936
,2016-01-29 17:44:45.675 ThaliTest[2139:6809647] client session: connected
2016-01-29 17:44:45.675 ThaliTest[2139:6809647] client session: stateChange:1->2 1454085881342.2936.2DH/dw==
,2016-01-29 17:44:45.684 ThaliTest[2139:6809625] client session: fireConnectCallback: 1454085881342.2936.2DH/dw==
2016-01-29 17:44:45.684 ThaliTest[2139:6809625] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should b,e within range

2016-01-29 17:44:45.686 ThaliTest[2139:6809013] jxcore: disconnect
2016-01-29 17:44:45.686 ThaliTest[2139:6809013] client session: disconnectFromPeer: 1454085881342.2936.2DH/dw==
2016-01-29 17:44:45.686 ThaliTest[2139:6809013] client se,ssion: disconnect
2016-01-29 17:44:45.687 ThaliTest[2139:6809013] client session: stateChange:2->0 1454085881342.2936.2DH/dw==
,2016-01-29 17:44:45.766 ThaliTest[2139:6809013] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-29 17:44:46.718 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:46.719 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:46.719 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:46.720 ThaliTest[2139:6809013] server session: disconnect
2016-01-29 17:44:46.720 ThaliTest[2139:6809013] server session: stateChange:2->0 1454085881342.2936
,2016-01-29 17:44:46.725 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-29 17:44:48.241 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:48.244 ThaliTest[2139:6809013] server: starting 1454085888241.2139.CSRtYw==
2016-01-29 17:44:48.245 ThaliTest[2139:6809013] multipeer session: start timer: 0x1ad96530
2016-01-29 17:44:48.245 ThaliTest[2139:6809013] THEMultipeerSession in,itialized peer 1454085888241.2139
2016-01-29 17:44:48.245 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-29 17:44:49.539 ThaliTest[2139:6808794] multipeer session: reset timer
2016-01-29 17:44:49.540 ThaliTest[2139:6808794] multipeer session: stop timer
2016-01-29 17:44:49.540 ThaliTest[2139:6808794] multipeer session: start timer: 0x1ad96530
2016-,01-29 17:44:49.540 ThaliTest[2139:6808794] server session: connect
2016-01-29 17:44:49.542 ThaliTest[2139:6808794] server session: stateChange:0->1 1454085888777.2936
2016-01-29 17:44:49.547 ThaliTest[2139:6808794] server: accepting invitation 1454085888777.2936
,2016-01-29 17:44:49.734 ThaliTest[2139:6808794] client: found peer: 1454085888777.2936.B5dxuA==
,2016-01-29 17:44:49.735 ThaliTest[2139:6809013] jxcore: connect 1454085888777.2936.B5dxuA==
2016-01-29 17:44:49.735 ThaliTest[2139:6809013] client session: connect
2016-01-29 17:44:49.736 ThaliTest[2139:6809013] client session: stateChange:0->1 1454085888777.2936.B5dxuA==
,2016-01-29 17:44:52.035 ThaliTest[2139:6809647] server session: connected
2016-01-29 17:44:52.036 ThaliTest[2139:6809647] server session: stateChange:1->2 1454085888777.2936
,2016-01-29 17:44:52.113 ThaliTest[2139:6808794] server relay: socket disconnected
2016-01-29 17:44:52.114 ThaliTest[2139:6808794] server relay: 0x1aa27910 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
2016-01-29 17:44:52.114 ThaliTest[2139:6809618] server session: not connected 1454085888777.2936
,2016-01-29 17:44:52.416 ThaliTest[2139:6809618] client session: connected
2016-01-29 17:44:52.416 ThaliTest[2139:6809618] client session: stateChange:1->2 1454085888777.2936.B5dxuA==
,2016-01-29 17:44:52.434 ThaliTest[2139:6809622] client session: fireConnectCallback: 1454085888777.2936.B5dxuA==
2016-01-29 17:44:52.434 ThaliTest[2139:6809622] jxcore: connect: success
ok 88 Should be able to connect without error

ok 89 Port should b,e within range

2016-01-29 17:44:52.436 ThaliTest[2139:6809013] jxcore: connect 1454085888777.2936.B5dxuA==
2016-01-29 17:44:52.436 ThaliTest[2139:6809013] client: already connect(ing/ed) to 1454085888777.2936.B5dxuA==
2016-01-29 17:44:52.436 ThaliTest,[2139:6809013] jxcore: connect: fail: Aleady connecting
ok 90 Should fail on double connect

2016-01-29 17:44:52.438 ThaliTest[2139:6809013] jxcore: disconnect
,2016-01-29 17:44:52.438 ThaliTest[2139:6809013] client session: disconnectFromPeer: 1454085888777.2936.B5dxuA==
2016-01-29 17:44:52.442 ThaliTest[2139:6809013] client session: disconnect
2016-01-29 17:44:52.442 ThaliTest[2139:6809013] client session: stateChange:2->0 1454085888777.2936.B5dxuA==
,2016-01-29 17:44:52.453 ThaliTest[2139:6809013] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-29 17:44:52.497 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:44:52.497 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:44:52.498 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:44:52.498 ThaliTest[2139:6809013] server session: disconnect
,2016-01-29 17:44:52.499 ThaliTest[2139:6809013] server session: stateChange:2->0 1454085888777.2936
,2016-01-29 17:44:52.507 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-29 17:44:53.984 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:44:53.987 ThaliTest[2139:6809013] server: starting 1454085893984.2139.8zyT5Q==
2016-01-29 17:44:53.987 ThaliTest[2139:6809013] multipeer session: start timer: 0x1adba530
2016-01-29 17:44:53.987 ThaliTest[2139:6809013] THEMultipeerSession in,itialized peer 1454085893984.2139
2016-01-29 17:44:53.988 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-29 17:44:55.304 ThaliTest[2139:6808794] multipeer session: reset timer
2016-01-29 17:44:55.304 ThaliTest[2139:6808794] multipeer session: stop timer
2016-01-29 17:44:55.304 ThaliTest[2139:6808794] multipeer session: start timer: 0x1adba530
2016-,01-29 17:44:55.305 ThaliTest[2139:6808794] server session: connect
2016-01-29 17:44:55.305 ThaliTest[2139:6808794] server session: stateChange:0->1 1454085893964.2936
2016-01-29 17:44:55.313 ThaliTest[2139:6808794] server: accepting invitation 1454085893,964.2936
,2016-01-29 17:44:55.323 ThaliTest[2139:6808794] client: found peer: 1454085893964.2936.R5nDuQ==
2016-01-29 17:44:55.323 ThaliTest[2139:6809013] jxcore: connect 1454085893964.2936.R5nDuQ==
2016-01-29 17:44:55.324 ThaliTest[2139:6809013] client session: connect
2016-01-29 17:44:55.324 ThaliTest[2139:6809013] client session: stateChange:0->1 1454085893964.2936.R5nDuQ==
,2016-01-29 17:44:57.800 ThaliTest[2139:6809622] server session: connected
2016-01-29 17:44:57.800 ThaliTest[2139:6809622] server session: stateChange:1->2 1454085893964.2936
,2016-01-29 17:44:57.865 ThaliTest[2139:6808794] server relay: socket disconnected
,2016-01-29 17:44:57.866 ThaliTest[2139:6808794] server relay: 0x1ad9dd00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-29 17:44:57.871 ThaliTest[2139:6809647] server session: not connected 1454085893964.2936
,2016-01-29 17:44:58.122 ThaliTest[2139:6809647] client session: connected
,2016-01-29 17:44:58.122 ThaliTest[2139:6809647] client session: stateChange:1->2 1454085893964.2936.R5nDuQ==
,2016-01-29 17:44:58.149 ThaliTest[2139:6809618] client session: fireConnectCallback: 1454085893964.2936.R5nDuQ==
2016-01-29 17:44:58.149 ThaliTest[2139:6809618] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be within range

2016-01-29 17:44:58.151 ThaliTest[2139:6809013] jxcore: disconnect
2016-01-29 17:44:58.151 ThaliTest[2139:6809013] client session: disconnectFromPeer: 1454085893964.2936.R5nDuQ==
2016-01-29 17:44:58.152 ThaliTest[2139:6809013] client se,ssion: disconnect
2016-01-29 17:44:58.152 ThaliTest[2139:6809013] client session: stateChange:2->0 1454085893964.2936.R5nDuQ==
,2016-01-29 17:44:58.167 ThaliTest[2139:6809013] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-01-29 17:44:58.168 ThaliTest[2139:6809013] jxcore: disconnect
2016-01-29 17:44:58.168 ThaliTest[2139:6809013] jxcore: disconnect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-01-29 17:44:58.708 ThaliTest[2139:6809013] jxcore: stopBroadcasting
2016-01-29 17:44:58.708 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
2016-01-29 17:44:58.708 ThaliTest[2139:6809013] multipeer session: stop, timer
2016-01-29 17:44:58.708 ThaliTest[2139:6809013] server session: disconnect
2016-01-29 17:44:58.708 ThaliTest[2139:6809013] server session: stateChange:2->0 1454085893964.2936
,2016-01-29 17:44:58.711 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 59453

,2016-01-29 17:45:00.795 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:45:00.799 ThaliTest[2139:6809013] server: starting 1454085900795.2139.ZfgRDw==
,2016-01-29 17:45:00.801 ThaliTest[2139:6809013] multipeer session: start timer: 0x1adb2cf0
,2016-01-29 17:45:00.806 ThaliTest[2139:6809013] THEMultipeerSession initialized peer 1454085900795.2139
,2016-01-29 17:45:00.809 ThaliTest[2139:6808794] client: found peer: 1454085893964.2936.R5nDuQ==
2016-01-29 17:45:00.810 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-01-29 17:45:00.815 ThaliTest[2139:6809013] jxcore: connect 1454085893964.2936.R5nDuQ==
,2016-01-29 17:45:00.817 ThaliTest[2139:6809013] client session: connect
,2016-01-29 17:45:00.818 ThaliTest[2139:6809013] client session: stateChange:0->1 1454085893964.2936.R5nDuQ==
,2016-01-29 17:45:01.946 ThaliTest[2139:6808794] client: lost peer: 1454085893964.2936.R5nDuQ==
2016-01-29 17:45:01.946 ThaliTest[2139:6808794] client session: onPeerLost: 1454085893964.2936.R5nDuQ==
2016-01-29 17:45:01.946 ThaliTest[2139:6808794] client ,session: onLinkFailure: 1454085893964.2936.R5nDuQ==
2016-01-29 17:45:01.946 ThaliTest[2139:6808794] client session: disconnect
2016-01-29 17:45:01.946 ThaliTest[2139:6808794] client session: stateChange:1->0 1454085893964.2936.R5nDuQ==
2016-01-29 17:45:,01.947 ThaliTest[2139:6808794] client session: fireConnectCallback: 1454085893964.2936.R5nDuQ==
2016-01-29 17:45:01.948 ThaliTest[2139:6808794] jxcore: connect: fail: Peer disconnected
2016-01-29 17:45:01.950 ThaliTest[2139:6808794] client: found peer: 1,454085900428.2936.MW4pdw==
2016-01-29 17:45:01.951 ThaliTest[2139:6809013] jxcore: connect 1454085900428.2936.MW4pdw==
2016-01-29 17:45:01.951 ThaliTest[2139:6809013] client session: connect
2016-01-29 17:45:01.951 ThaliTest[2139:6809013] client session,: stateChange:0->1 1454085900428.2936.MW4pdw==
,2016-01-29 17:45:02.119 ThaliTest[2139:6808794] multipeer session: reset timer
2016-01-29 17:45:02.119 ThaliTest[2139:6808794] multipeer session: stop timer
2016-01-29 17:45:02.119 ThaliTest[2139:6808794] multipeer session: start timer: 0x1adb2cf0
2016-,01-29 17:45:02.119 ThaliTest[2139:6808794] server session: connect
2016-01-29 17:45:02.119 ThaliTest[2139:6808794] server session: stateChange:0->1 1454085900428.2936
2016-01-29 17:45:02.127 ThaliTest[2139:6808794] server: accepting invitation 1454085900428.2936
,2016-01-29 17:45:02.952 ThaliTest[2139:6809013] jxcore: connect 1454085893964.2936.R5nDuQ==
2016-01-29 17:45:02.952 ThaliTest[2139:6809013] client: connect: unreachable 1454085893964.2936.R5nDuQ==
2016-01-29 17:45:02.952 ThaliTest[2139:6809013] jxcore: connect: fail: Peer unreachable
,2016-01-29 17:45:04.672 ThaliTest[2139:6809625] client session: connected
,2016-01-29 17:45:04.672 ThaliTest[2139:6809625] client session: stateChange:1->2 1454085900428.2936.MW4pdw==
,2016-01-29 17:45:04.676 ThaliTest[2139:6809625] client session: fireConnectCallback: 1454085900428.2936.MW4pdw==
2016-01-29 17:45:04.676 ThaliTest[2139:6809625] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-01-29 17:45:04.680 ThaliTest[2139:6808794] client: relay established
2016-01-29 17:45:04.680 ThaliTest[2139:6808794] client: new accepted socket: 0x1ade0db0
,data in 3285

,data in 7665

,data in 8760

,data in 13140

,data in 15330

,data in 25043

,data in 25185

,data in 33377

,data in 50370

,data in 51465

,data in 54750

2016-01-29 17:45:05.216 ThaliTest[2139:6809648] server session: connected
2016-01-29 17:45:05.216 ThaliTest[2139:6809648] server session: stateChange:1->2 1454085900428.2936
,2016-01-29 17:45:05.229 ThaliTest[2139:6808794] server relay: connected (to port: 59453)
data in 56940

,data in 73365

,data in 83220

,data in 109500

,data in 112785

,data in 119355

,data in 123735

,data in 124830

,data in 128115

,data in 131072

,ok 100 the test messages should be equal

,2016-01-29 17:45:05.442 ThaliTest[2139:6809013] jxcore: disconnect
,2016-01-29 17:45:05.443 ThaliTest[2139:6809013] client session: disconnectFromPeer: 1454085900428.2936.MW4pdw==
,2016-01-29 17:45:05.444 ThaliTest[2139:6809013] client session: disconnect
,2016-01-29 17:45:05.445 ThaliTest[2139:6809013] client session: stateChange:2->0 1454085900428.2936.MW4pdw==
,2016-01-29 17:45:05.464 ThaliTest[2139:6809013] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.
,
,# setup

,2016-01-29 17:45:05.927 ThaliTest[2139:6809647] server session: not connected 1454085900428.2936
,calling stopBroadcasting

,2016-01-29 17:45:06.058 ThaliTest[2139:6809013] jxcore: stopBroadcasting
2016-01-29 17:45:06.059 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
2016-01-29 17:45:06.059 ThaliTest[2139:6809013] multipeer session: stop timer
2016-01-29 17:45:06.,059 ThaliTest[2139:6809013] server session: disconnect
2016-01-29 17:45:06.059 ThaliTest[2139:6809013] server session: stateChange:2->0 1454085900428.2936
,2016-01-29 17:45:06.063 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 59460

2016-01-29 17:45:06.574 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:45:06.577 ThaliTest[2139:6809013] server: starting 1454085906574.2139.8tpZOw==
2016-01-29 17:45:06.578 ThaliTest[2139:6809013] multipeer session: start timer: 0x1adde750
2016-01-29 17:45:06.578 ThaliTest[2139:6809013] THEMultipeerSession in,itialized peer 1454085906574.2139
2016-01-29 17:45:06.578 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-29 17:45:07.213 ThaliTest[2139:6808794] client: found peer: 1454085900428.2936.MW4pdw==
[{"peerIdentifier":"1454085900428.2936.MW4pdw==","peerName":"(null)","peerAvailable":true}]

2016-01-29 17:45:07.215 ThaliTest[2139:6809013] jxcore: connect ,1454085900428.2936.MW4pdw==
2016-01-29 17:45:07.215 ThaliTest[2139:6809013] client session: connect
2016-01-29 17:45:07.216 ThaliTest[2139:6809013] client session: stateChange:0->1 1454085900428.2936.MW4pdw==
,2016-01-29 17:45:07.856 ThaliTest[2139:6808794] client: found peer: 1454085906543.2936.5mQb3g==
[{"peerIdentifier":"1454085906543.2936.5mQb3g==","peerName":"(null)","peerAvailable":true}]

2016-01-29 17:45:07.857 ThaliTest[2139:6809013] jxcore: connect ,1454085906543.2936.5mQb3g==
2016-01-29 17:45:07.857 ThaliTest[2139:6809013] client session: connect
2016-01-29 17:45:07.857 ThaliTest[2139:6809013] client session: stateChange:0->1 1454085906543.2936.5mQb3g==
,2016-01-29 17:45:07.944 ThaliTest[2139:6808794] multipeer session: reset timer
2016-01-29 17:45:07.944 ThaliTest[2139:6808794] multipeer session: stop timer
2016-01-29 17:45:07.945 ThaliTest[2139:6808794] multipeer session: start timer: 0x1adde750
2016-,01-29 17:45:07.945 ThaliTest[2139:6808794] server session: connect
2016-01-29 17:45:07.945 ThaliTest[2139:6808794] server session: stateChange:0->1 1454085906543.2936
,2016-01-29 17:45:07.956 ThaliTest[2139:6808794] server: accepting invitation 1454085906543.2936
,2016-01-29 17:45:10.452 ThaliTest[2139:6809647] client session: connected
2016-01-29 17:45:10.453 ThaliTest[2139:6809647] client session: stateChange:1->2 1454085906543.2936.5mQb3g==
,2016-01-29 17:45:10.472 ThaliTest[2139:6809647] client session: fireConnectCallback: 1454085906543.2936.5mQb3g==
,2016-01-29 17:45:10.472 ThaliTest[2139:6809622] server session: connected
,2016-01-29 17:45:10.473 ThaliTest[2139:6809647] jxcore: connect: success
,ok 103 Should be able to connect without error

2016-01-29 17:45:10.474 ThaliTest[2139:6809622] server session: stateChange:1->2 1454085906543.2936
ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-01-29 17:45:10.481 ThaliTest[2139:6808794] server relay: connected (to port: 59460)
,2016-01-29 17:45:10.506 ThaliTest[2139:6808794] client: relay established
2016-01-29 17:45:10.506 ThaliTest[2139:6808794] client: new accepted socket: 0x1ade97a0
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-01-29 17:45:10.586 ThaliTest[2139:6808794] client: socket closed
,2016-01-29 17:45:10.586 ThaliTest[2139:6808794] client relay: socket disconnected
2016-01-29 17:45:10.586 ThaliTest[2139:6808794] client relay: 0x1ade97a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-29 17:45:10.586 ThaliTest[2139:6808794] client session: socket closed: 1454085906543.2936.5mQb3g==
2016-01-29 17:45:10.586 ThaliTest[2139:6808794] client session: onLinkFailure: 1454085906543.2936.5mQb3g==
2016-01-29 17:45:10.586 ThaliTest[2139:6,808794] client session: disconnect
2016-01-29 17:45:10.587 ThaliTest[2139:6808794] client session: stateChange:2->0 1454085906543.2936.5mQb3g==
,2016-01-29 17:45:10.640 ThaliTest[2139:6809622] server session: not connected 1454085906543.2936
,2016-01-29 17:45:10.655 ThaliTest[2139:6808794] client session: fireConnectionErrorEvent: 1454085906543.2936.5mQb3g==
,2016-01-29 17:45:10.656 ThaliTest[2139:6809013] jxcore: connect 1454085906543.2936.5mQb3g==
,2016-01-29 17:45:10.658 ThaliTest[2139:6809013] client session: connect
,2016-01-29 17:45:10.660 ThaliTest[2139:6809013] client session: stateChange:0->1 1454085906543.2936.5mQb3g==
,2016-01-29 17:45:10.710 ThaliTest[2139:6808794] multipeer session: reset timer
,2016-01-29 17:45:10.710 ThaliTest[2139:6808794] multipeer session: stop timer
2016-01-29 17:45:10.711 ThaliTest[2139:6808794] multipeer session: start timer: 0x1adde750
,2016-01-29 17:45:10.711 ThaliTest[2139:6808794] server: disconnecting to refresh session (1454085906543.2936)
,2016-01-29 17:45:10.711 ThaliTest[2139:6808794] server session: disconnect
,2016-01-29 17:45:10.712 ThaliTest[2139:6808794] server session: stateChange:2->0 1454085906543.2936
,2016-01-29 17:45:10.716 ThaliTest[2139:6808794] server session: connect
,2016-01-29 17:45:10.717 ThaliTest[2139:6808794] server session: stateChange:0->1 1454085906543.2936
,2016-01-29 17:45:10.735 ThaliTest[2139:6808794] server: accepting invitation 1454085906543.2936
,2016-01-29 17:45:12.793 ThaliTest[2139:6808794] client: lost peer: 1454085900428.2936.MW4pdw==
2016-01-29 17:45:12.794 ThaliTest[2139:6808794] client session: onPeerLost: 1454085900428.2936.MW4pdw==
2016-01-29 17:45:12.794 ThaliTest[2139:6808794] client ,session: onLinkFailure: 1454085900428.2936.MW4pdw==
2016-01-29 17:45:12.794 ThaliTest[2139:6808794] client session: disconnect
2016-01-29 17:45:12.794 ThaliTest[2139:6808794] client session: stateChange:1->0 1454085900428.2936.MW4pdw==
2016-01-29 17:45:,12.794 ThaliTest[2139:6808794] client session: fireConnectCallback: 1454085900428.2936.MW4pdw==
2016-01-29 17:45:12.795 ThaliTest[2139:6808794] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1454085900428.2936.MW4pdw==","peerName":"(null)",,"peerAvailable":false}]

,2016-01-29 17:45:13.334 ThaliTest[2139:6809647] client session: connected
2016-01-29 17:45:13.334 ThaliTest[2139:6809647] client session: stateChange:1->2 1454085906543.2936.5mQb3g==
,2016-01-29 17:45:13.346 ThaliTest[2139:6809648] client session: fireConnectCallback: 1454085906543.2936.5mQb3g==
,2016-01-29 17:45:13.349 ThaliTest[2139:6809648] jxcore: connect: success
2016-01-29 17:45:13.357 ThaliTest[2139:6809622] server session: connected
2016-01-29 17:45:13.357 ThaliTest[2139:6809622] server session: stateChange:1->2 1454085906543.2936
ok 108 Should be able to connect without error

,ok 109 Port should be within range

ok 110 Second connect should succeed

2016-01-29 17:45:13.362 ThaliTest[2139:6808794] server relay: connected (to port: 59460)
,2016-01-29 17:45:13.385 ThaliTest[2139:6808794] client: relay established
2016-01-29 17:45:13.385 ThaliTest[2139:6808794] client: new accepted socket: 0x1ade9cd0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-01-29 17:45:13.482 ThaliTest[2139:6808794] client: socket closed
2016-01-29 17:45:13.482 ThaliTest[2139:6808794] client relay: socket disconnected
2016-01-29 17:45:13.483 ThaliTest[2139:6808794] client relay: 0x1ade9cd0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-29 17:45:13.483 ThaliTest[2139:6808794] client session: socket closed: 1454085906543.2936.5mQb3g==
2016-01-29 ,17:45:13.483 ThaliTest[2139:6808794] client session: onLinkFailure: 1454085906543.2936.5mQb3g==
2016-01-29 17:45:13.483 ThaliTest[2139:6808794] client session: disconnect
2016-01-29 17:45:13.483 ThaliTest[2139:6808794] client session: stateChange:2->0 14,54085906543.2936.5mQb3g==
,2016-01-29 17:45:13.494 ThaliTest[2139:6808794] client session: fireConnectionErrorEvent: 1454085906543.2936.5mQb3g==
,2016-01-29 17:45:13.527 ThaliTest[2139:6809622] server session: not connected 1454085906543.2936
,2016-01-29 17:45:13.799 ThaliTest[2139:6809013] jxcore: connect 1454085900428.2936.MW4pdw==
2016-01-29 17:45:13.799 ThaliTest[2139:6809013] client: connect: unreachable 1454085900428.2936.MW4pdw==
2016-01-29 17:45:13.800 ThaliTest[2139:6809013] jxcore: connect: fail: Peer unreachable
,calling stopBroadcasting

2016-01-29 17:45:14.441 ThaliTest[2139:6809013] jxcore: stopBroadcasting
2016-01-29 17:45:14.441 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
2016-01-29 17:45:14.441 ThaliTest[2139:6809013] multipeer session: stop, timer
2016-01-29 17:45:14.441 ThaliTest[2139:6809013] server session: disconnect
2016-01-29 17:45:14.442 ThaliTest[2139:6809013] server session: stateChange:2->0 1454085906543.2936
,2016-01-29 17:45:14.449 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/5CC5EFA2-BB2C-4F4B-80D5-723BB57A734A/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-29 17:45:15.025 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:45:15.027 ThaliTest[2139:6809013] server: starting Uwpyz15uvsEce9PnLtS3SQ.QfBZmw==
,2016-01-29 17:45:15.029 ThaliTest[2139:6809013] multipeer session: start timer: 0x1a2a7730
,2016-01-29 17:45:15.036 ThaliTest[2139:6809013] THEMultipeerSession initialized peer Uwpyz15uvsEce9PnLtS3SQ
,2016-01-29 17:45:15.037 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

,Now in TRM stop

,State of this._isStarted: true
,
,ok 115 stopping event should occur in right order

,About to call stopBroadcasting
,
,2016-01-29 17:45:15.041 ThaliTest[2139:6809013] jxcore: stopBroadcasting
,2016-01-29 17:45:15.042 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:45:15.043 ThaliTest[2139:6809013] multipeer session: stop timer
,2016-01-29 17:45:15.046 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/5CC5EFA2-BB2C-4F4B-80D5-723BB57A734A/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-29 17:45:16.028 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:45:16.031 ThaliTest[2139:6809013] server: starting Uwpyz15uvsEce9PnLtS3SQ.tjtNyA==
2016-01-29 17:45:16.032 ThaliTest[2139:6809013] multipeer session: start timer: 0x1adeee70
2016-01-29 17:45:16.032 ThaliTest[2139:6809013] THEMultipeerSessio,n initialized peer Uwpyz15uvsEce9PnLtS3SQ
2016-01-29 17:45:16.032 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-01-29 17:45:16.034 ThaliTest[2139:6809013] jxcore: stopBroadcasting
2016-01-29 17:45:16.034 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
,2016-01-29 17:45:16.035 ThaliTest[2139:6809013] multipeer session: stop timer
2016-01-29 17:45:16.039 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/5CC5EFA2-BB2C-4F4B-80D5-723BB57A734A/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-29 17:45:20.731 ThaliTest[2139:6809013] jxcore: startBroadcasting
,2016-01-29 17:45:20.734 ThaliTest[2139:6809013] server: starting Uwpyz15uvsEce9PnLtS3SQ.UamVKQ==
2016-01-29 17:45:20.734 ThaliTest[2139:6809013] multipeer session: start timer: 0x1aaa11d0
2016-01-29 17:45:20.735 ThaliTest[2139:6809013] THEMultipeerSessio,n initialized peer Uwpyz15uvsEce9PnLtS3SQ
2016-01-29 17:45:20.735 ThaliTest[2139:6809013] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-01-29 17:45:20.770 ThaliTest[2139:6808794] client: found peer: 3FYYZiHqGQblvDtT62oZ0w.kOsNPw==
,2016-01-29 17:45:30.757 ThaliTest[2139:6809013] jxcore: connect 3FYYZiHqGQblvDtT62oZ0w.kOsNPw==
,2016-01-29 17:45:30.758 ThaliTest[2139:6809013] client session: connect
,2016-01-29 17:45:30.760 ThaliTest[2139:6809013] client session: stateChange:0->1 3FYYZiHqGQblvDtT62oZ0w.kOsNPw==
,ok 121 Should be able to put doc without error

,2016-01-29 17:45:30.960 ThaliTest[2139:6808794] multipeer session: reset timer
2016-01-29 17:45:30.961 ThaliTest[2139:6808794] multipeer session: stop timer
2016-01-29 17:45:30.961 ThaliTest[2139:6808794] multipeer session: start timer: 0x1aaa11d0
2016-,01-29 17:45:30.961 ThaliTest[2139:6808794] server session: connect
2016-01-29 17:45:30.961 ThaliTest[2139:6808794] server session: stateChange:0->1 3FYYZiHqGQblvDtT62oZ0w
,2016-01-29 17:45:30.975 ThaliTest[2139:6808794] server: accepting invitation 3FYYZiHqGQblvDtT62oZ0w
,ok 122 1st change of local doc should contain local id

,2016-01-29 17:45:33.577 ThaliTest[2139:6809625] client session: connected
2016-01-29 17:45:33.577 ThaliTest[2139:6809625] client session: stateChange:1->2 3FYYZiHqGQblvDtT62oZ0w.kOsNPw==
2016-01-29 17:45:33.580 ThaliTest[2139:6809625] client session: fireConnectCallback: 3FYYZiHqGQblvDtT62oZ0w.kOsNPw==
2016-01-29 17:45:33.580 ThaliTest[2139:6809625] jxcore: connect: success
,2016-01-29 17:45:33.594 ThaliTest[2139:6808794] client: relay established
2016-01-29 17:45:33.594 ThaliTest[2139:6808794] client: new accepted socket: 0x1a7b8c40
,2016-01-29 17:45:33.631 ThaliTest[2139:6809782] server session: connected
2016-01-29 17:45:33.632 ThaliTest[2139:6809782] server session: stateChange:1->2 3FYYZiHqGQblvDtT62oZ0w
,2016-01-29 17:45:33.636 ThaliTest[2139:6808794] server relay: connected (to port: 59476)
,server bridge: new client socket

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-01-29 17:45:43.540 ThaliTest[2139:6809013] jxcore: stopBroadcasting
2016-01-29 17:45:43.541 ThaliTest[2139:6809013] THEMultipeerSession stopping peer
2016-01-29 17:45:43.541 ThaliTest[2139:6809013] multipeer session: stop timer
2016-01-29 17:45:43.541 ThaliTest[2139:6809013] client session: disconnect
2016-01-29 17:45:43.541 ThaliTest[2139:6809013] client session: stateChange:2->0 3FYYZiHqGQblvDtT62oZ0w.kOsNPw==,
,2016-01-29 17:45:43.562 ThaliTest[2139:6809013] server session: disconnect
2016-01-29 17:45:43.562 ThaliTest[2139:6809013] server session: stateChange:2->0 3FYYZiHqGQblvDtT62oZ0w
,2016-01-29 17:45:46.662 ThaliTest[2139:6809013] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,Process 2139 stopped
* thread #17: tid = 0x67e830, 0x38ef3ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCSession.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0xc1a89613)
    frame #0: 0x38ef3ae6 libobjc.A.dylib`objc_msgSend + 6
libobjc.A.dylib`objc_msgSend:
->  0x38ef3ae6 <+6>:  ldrh.w r12, [r9, #0xc]
    0x38ef3aea <+10>: ldr.w  r9, [r9, #0x8]
    0x38ef3aee <+14>: and.w  r12, r12, r1
    0x38ef3af2 <+18>: add.w  r9, r9, r12, lsl #3
,* thread #17: tid = 0x67e830, 0x38ef3ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCSession.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0xc1a89613)
  * frame #0: 0x38ef3ae6 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x29d3f85e MultipeerConnectivity`<redacted> + 1334
    frame #2: 0x3961e72a libdispatch.dylib`<redacted> + 2042
    frame #3: 0x3960dd6e libdispatch.dylib`<redacted> + 738
    frame #4: 0x39615b5c libdispatch.dylib`<redacted> + 592
    frame #5: 0x3960ef86 libdispatch.dylib`<redacted> + 282
    frame #6: 0x3961737c libdispatch.dylib`<redacted> + 400
    frame #7: 0x396171ea libdispatch.dylib`<redacted> + 94
    frame #8: 0x397a0e0c libsystem_pthread.dylib`_pthread_wqthread + 1024
    frame #9: 0x397a09fc libsystem_pthread.dylib`start_wqthread + 8

```
