#### Test 56672827b6f75d5_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56672827b6f75d5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4A4CBA3D-E027-4B93-8E4B-C2098087B147/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4A4CBA3D-E027-4B93-8E4B-C2098087B147/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/56672827b6f75d5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56672827b6f75d5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D1A669BD-34F5-4920-9794-10BEA9252E8A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59704"
,(lldb)     command script import "/tmp/4A4CBA3D-E027-4B93-8E4B-C2098087B147/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 17:42:00.456 ThaliTest[1784:5570924] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FEA2980A-541B-44B3-8610-EA782657A26B/Library/Cookies/Cookies.binarycookies
,2016-01-21 17:42:00.802 ThaliTest[1784:5570924] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-21 17:42:00.804 ThaliTest[1784:5570924] Multi-tasking -> Device: YES, App: YES
,2016-01-21 17:42:00.808 ThaliTest[1784:5570924] Unlimited access to network resources
,2016-01-21 17:42:00.819 ThaliTest[1784:5570924] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 17:42:07.008 ThaliTest[1784:5570924] Resetting plugins due to page load.
,2016-01-21 17:42:08.925 ThaliTest[1784:5570924] Finished load of: file:///var/mobile/Containers/Bundle/Application/D1A669BD-34F5-4920-9794-10BEA9252E8A/ThaliTest.app/www/index.html
,2016-01-21 17:42:09.121 ThaliTest[1784:5570924] JXcore Cordova plugin initializing
2016-01-21 17:42:09.125 ThaliTest[1784:5571164] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1A669BD-34F5-4920-9794-10BEA9252E8A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1A669BD-34F5-4920-9794-10BEA9252E8A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1A669BD-34F5-4920-9794-10BEA9252E8A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1A669BD-34F5-4920-9794-10BEA9252E8A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1A669BD-34F5-4920-9794-10BEA9252E8A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1A669BD-34F5-4920-9794-10BEA9252E8A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1A669BD-34F5-4920-9794-10BEA9252E8A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1A669BD-34F5-4920-9794-10BEA9252E8A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout expected 0 and got 0

ok 3 firstPromise result expected 10 and got 10

ok 4 firstPromise testValue expected 10 and got 10

,ok 5 secondPromise setTimeout expected 10 and got 10

,ok 6 secondPromise result expected 100 and got 100

ok 7 secondPromise testValue expected 100 and got 100

ok 8 thirdPromise in promise expected 100 and got 100

ok 9 thirdPromise result expected 1000 and got 1000

ok 10 thirdPromise result expected 1000 and got 1000

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

ok 20 should not throw

,ok 21 should be equal
,
ok 22 should be equal

# setup

,# failed to extract public key because of corrupt pkcs12 file
,
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

ok 26 should be equal

ok 27 should be equal

# setup

,# #init should register the networkChanged event

,# teardown

,ok 28 should be equal

,# setup

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

# setup

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

,ok 39 should be equal

ok 40 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

,ok 46 should be equal

ok 47 should be equal

# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

,ok 49 should be equal

# setup

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

,2016-01-21 17:48:20.916 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:20.925 ThaliTest[1784:5571164] server: starting 1453394900916.1784.oo0AIA==
2016-01-21 17:48:20.926 ThaliTest[1784:5571164] multipeer session: start timer: 0x19c9cff0
2016-01-21 17:48:20.926 ThaliTest[1784:5571164] THEMultipeerSession in,itialized peer 1453394900916.1784
2016-01-21 17:48:20.926 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

2016-01-21 17:48:20.928 ThaliTest[1784:5571164] jxcore: stopBroadcasting,
2016-01-21 17:48:20.929 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
2016-01-21 17:48:20.929 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:20.931 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:20.932 ThaliTest[1784:5571164] jxcore: startBroadcasting
2016-01-21 17:48:20.935 ThaliTest[1784:5571164] server: starting 1453394900932.1784.aRjZag==
2016-01-21 17:48:20.935 ThaliTest[1784:5571164] multipeer session: start timer: 0x19cc7,430
2016-01-21 17:48:20.935 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 1453394900932.1784
2016-01-21 17:48:20.936 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

,2016-01-21 17:48:20.937 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:20.956 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.959 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:20.962 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error
,
,2016-01-21 17:48:20.967 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:20.971 ThaliTest[1784:5571164] server: starting 1453394900967.1784.6dXX4A==
,2016-01-21 17:48:20.977 ThaliTest[1784:5571164] multipeer session: start timer: 0x19c95f20
,2016-01-21 17:48:20.983 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 1453394900967.1784
,2016-01-21 17:48:20.984 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error
,
,2016-01-21 17:48:20.988 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:20.989 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:20.990 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:20.994 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error
,
,2016-01-21 17:48:20.998 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:21.002 ThaliTest[1784:5571164] server: starting 1453394900998.1784.6dPYIA==
,2016-01-21 17:48:21.006 ThaliTest[1784:5571164] multipeer session: start timer: 0x19cc6330
,2016-01-21 17:48:21.011 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 1453394900998.1784
,2016-01-21 17:48:21.013 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error
,
,2016-01-21 17:48:21.016 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:21.017 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:21.019 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:21.024 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error
,
,2016-01-21 17:48:21.027 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:21.031 ThaliTest[1784:5571164] server: starting 1453394901027.1784.Fc8h1Q==
,2016-01-21 17:48:21.034 ThaliTest[1784:5571164] multipeer session: start timer: 0x19cc6e40
,2016-01-21 17:48:21.041 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 1453394901027.1784
,2016-01-21 17:48:21.042 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error
,
,2016-01-21 17:48:21.045 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:21.047 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:21.048 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:21.053 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:21.056 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:21.060 ThaliTest[1784:5571164] server: starting 1453394901056.1784.bdpdPg==
,2016-01-21 17:48:21.067 ThaliTest[1784:5571164] multipeer session: start timer: 0x1c58d860
,2016-01-21 17:48:21.070 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 1453394901056.1784
,2016-01-21 17:48:21.072 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error
,
,2016-01-21 17:48:21.075 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:21.076 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:21.077 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:21.080 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:21.084 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:21.087 ThaliTest[1784:5571164] server: starting 1453394901084.1784.RmIWCQ==
,2016-01-21 17:48:21.088 ThaliTest[1784:5571164] multipeer session: start timer: 0x1c58dad0
,2016-01-21 17:48:21.090 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 1453394901084.1784
,2016-01-21 17:48:21.091 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error
,
,2016-01-21 17:48:21.098 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:21.099 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:21.099 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:21.100 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:21.106 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:21.108 ThaliTest[1784:5571164] server: starting 1453394901105.1784.eYEeqw==
,2016-01-21 17:48:21.110 ThaliTest[1784:5571164] multipeer session: start timer: 0x19cd2e20
,2016-01-21 17:48:21.113 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 1453394901105.1784
,2016-01-21 17:48:21.118 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-01-21 17:48:21.121 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:21.122 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:21.123 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:21.124 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-01-21 17:48:21.130 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:21.132 ThaliTest[1784:5571164] server: starting 1453394901129.1784.F2J/JQ==
,2016-01-21 17:48:21.133 ThaliTest[1784:5571164] multipeer session: start timer: 0x1c58ee70
,2016-01-21 17:48:21.141 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 1453394901129.1784
,2016-01-21 17:48:21.142 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-01-21 17:48:21.145 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:21.145 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:21.146 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:21.147 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error
,
,2016-01-21 17:48:21.154 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:21.156 ThaliTest[1784:5571164] server: starting 1453394901153.1784.LBq36g==
,2016-01-21 17:48:21.157 ThaliTest[1784:5571164] multipeer session: start timer: 0x19d606e0
,2016-01-21 17:48:21.161 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 1453394901153.1784
,2016-01-21 17:48:21.167 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-01-21 17:48:21.169 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:21.169 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:21.170 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:21.171 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-01-21 17:48:21.388 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:21.391 ThaliTest[1784:5571164] server: starting 1453394901388.1784.8SLGzw==
2016-01-21 17:48:21.391 ThaliTest[1784:5571164] multipeer session: start timer: 0x19d6ed10
2016-01-21 17:48:21.392 ThaliTest[1784:5571164] THEMultipeerSession in,itialized peer 1453394901388.1784
2016-01-21 17:48:21.392 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-01-21 17:48:21.393 ThaliTest[1784:5571164] jxcore: startBroadcasting,
2016-01-21 17:48:21.393 ThaliTest[1784:5571164] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

,2016-01-21 17:48:21.396 ThaliTest[1784:5571164] jxcore: stopBroadcasting
2016-01-21 17:48:21.402 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
2016-01-21 17:48:21.403 ThaliTest[1784:5571164] multipeer session: stop timer
2016-01-21 17:48:21.,403 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-01-21 17:48:21.891 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:21.894 ThaliTest[1784:5571164] server: starting 1453394901891.1784.fUBelw==
2016-01-21 17:48:21.894 ThaliTest[1784:5571164] multipeer session: start timer: 0x1c556ba0
2016-01-21 17:48:21.895 ThaliTest[1784:5571164] THEMultipeerSession in,itialized peer 1453394901891.1784
2016-01-21 17:48:21.895 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-01-21 17:48:21.896 ThaliTest[1784:5571164] jxcore: connect foobar
2,016-01-21 17:48:21.896 ThaliTest[1784:5571164] client: unknown peer foobar
,2016-01-21 17:48:21.896 ThaliTest[1784:5571164] jxcore: connect: fail: Unknown peer
ok 78 Should not connect to a bad peer

2016-01-21 17:48:21.906 ThaliTest[1784:5571164] jxcore: stopBroadcasting
2016-01-21 17:48:21.906 ThaliTest[1784:5571164] THEMult,ipeerSession stopping peer
2016-01-21 17:48:21.906 ThaliTest[1784:5571164] multipeer session: stop timer
2016-01-21 17:48:21.906 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-01-21 17:48:24.948 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:24.951 ThaliTest[1784:5571164] server: starting 1453394904948.1784.ZhTQhg==
2016-01-21 17:48:24.951 ThaliTest[1784:5571164] multipeer session: start timer: 0x1c559500
2016-01-21 17:48:24.951 ThaliTest[1784:5571164] THEMultipeerSession in,itialized peer 1453394904948.1784
2016-01-21 17:48:24.951 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-01-21 17:48:24.952 ThaliTest[1784:5571164] jxcore: disconnect
2016-,01-21 17:48:24.953 ThaliTest[1784:5571164] jxcore: disconnect: fail
ok 81 Disconnect should fail to a non-existant peer 

,2016-01-21 17:48:24.955 ThaliTest[1784:5571164] jxcore: stopBroadcasting
2016-01-21 17:48:24.962 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
2016-01-21 17:48:24.962 ThaliTest[1784:5571164] multipeer session: stop timer
2016-01-21 17:48:24.,962 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers
,
,# teardown

,2016-01-21 17:48:26.446 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:26.449 ThaliTest[1784:5571164] server: starting 1453394906446.1784.e3FjXw==
2016-01-21 17:48:26.450 ThaliTest[1784:5571164] multipeer session: start timer: 0x1c55b730
2016-01-21 17:48:26.450 ThaliTest[1784:5571164] THEMultipeerSession in,itialized peer 1453394906446.1784
2016-01-21 17:48:26.450 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-01-21 17:48:27.648 ThaliTest[1784:5570924] client: found peer: 1453394906370.2417.pTTmAA==
2016-01-21 17:48:27.649 ThaliTest[1784:5571164] jxcore: connect 1453394906370.2417.pTTmAA==
2016-01-21 17:48:27.650 ThaliTest[1784:5571164] client session: co,nnect
2016-01-21 17:48:27.650 ThaliTest[1784:5571164] client session: stateChange:0->1 1453394906370.2417.pTTmAA==
,2016-01-21 17:48:27.808 ThaliTest[1784:5570924] multipeer session: reset timer
2016-01-21 17:48:27.809 ThaliTest[1784:5570924] multipeer session: stop timer
2016-01-21 17:48:27.809 ThaliTest[1784:5570924] multipeer session: start timer: 0x1c55b730
2016-,01-21 17:48:27.809 ThaliTest[1784:5570924] server session: connect
2016-01-21 17:48:27.809 ThaliTest[1784:5570924] server session: stateChange:0->1 1453394906370.2417
2016-01-21 17:48:27.816 ThaliTest[1784:5570924] server: accepting invitation 1453394906370.2417
,2016-01-21 17:48:30.246 ThaliTest[1784:5571818] client session: connected
2016-01-21 17:48:30.246 ThaliTest[1784:5571818] client session: stateChange:1->2 1453394906370.2417.pTTmAA==
,2016-01-21 17:48:30.250 ThaliTest[1784:5571815] server session: connected
2016-01-21 17:48:30.250 ThaliTest[1784:5571815] server session: stateChange:1->2 1453394906370.2417
,2016-01-21 17:48:30.266 ThaliTest[1784:5571815] client session: fireConnectCallback: 1453394906370.2417.pTTmAA==
2016-01-21 17:48:30.266 ThaliTest[1784:5571815] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should b,e within range

,2016-01-21 17:48:30.269 ThaliTest[1784:5571164] jxcore: disconnect
,2016-01-21 17:48:30.271 ThaliTest[1784:5571164] client session: disconnectFromPeer: 1453394906370.2417.pTTmAA==
,2016-01-21 17:48:30.272 ThaliTest[1784:5571164] client session: disconnect
,2016-01-21 17:48:30.273 ThaliTest[1784:5571164] client session: stateChange:2->0 1453394906370.2417.pTTmAA==
,2016-01-21 17:48:30.281 ThaliTest[1784:5570924] server relay: socket disconnected
,2016-01-21 17:48:30.281 ThaliTest[1784:5570924] server relay: 0x19fe3520 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-21 17:48:30.287 ThaliTest[1784:5571164] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.
,
,# setup

,2016-01-21 17:48:30.310 ThaliTest[1784:5571815] server session: not connected 1453394906370.2417
,2016-01-21 17:48:32.419 ThaliTest[1784:5570924] client: lost peer: 1453394906370.2417.pTTmAA==
2016-01-21 17:48:32.419 ThaliTest[1784:5570924] client session: onPeerLost: 1453394906370.2417.pTTmAA==
,calling stopBroadcasting

2016-01-21 17:48:32.541 ThaliTest[1784:5571164] jxcore: stopBroadcasting
2016-01-21 17:48:32.542 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
2016-01-21 17:48:32.542 ThaliTest[1784:5571164] multipeer session: stop, timer
2016-01-21 17:48:32.542 ThaliTest[1784:5571164] server session: disconnect
2016-01-21 17:48:32.542 ThaliTest[1784:5571164] server session: stateChange:2->0 1453394906370.2417
,2016-01-21 17:48:32.549 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-01-21 17:48:33.286 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:33.289 ThaliTest[1784:5571164] server: starting 1453394913286.1784.d06l1w==
2016-01-21 17:48:33.289 ThaliTest[1784:5571164] multipeer session: start timer: 0x19fdea40
2016-01-21 17:48:33.290 ThaliTest[1784:5571164] THEMultipeerSession in,itialized peer 1453394913286.1784
2016-01-21 17:48:33.290 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-01-21 17:48:34.393 ThaliTest[1784:5570924] client: found peer: 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:34.394 ThaliTest[1784:5571164] jxcore: connect 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:34.395 ThaliTest[1784:5571164] client session: co,nnect
2016-01-21 17:48:34.395 ThaliTest[1784:5571164] client session: stateChange:0->1 1453394913196.2417.RcoLiQ==
,2016-01-21 17:48:34.528 ThaliTest[1784:5570924] multipeer session: reset timer
2016-01-21 17:48:34.528 ThaliTest[1784:5570924] multipeer session: stop timer
2016-01-21 17:48:34.528 ThaliTest[1784:5570924] multipeer session: start timer: 0x19fdea40
2016-,01-21 17:48:34.528 ThaliTest[1784:5570924] server session: connect
2016-01-21 17:48:34.528 ThaliTest[1784:5570924] server session: stateChange:0->1 1453394913196.2417
,2016-01-21 17:48:34.537 ThaliTest[1784:5570924] server: accepting invitation 1453394913196.2417
,2016-01-21 17:48:37.153 ThaliTest[1784:5571876] client session: connected
2016-01-21 17:48:37.154 ThaliTest[1784:5571876] client session: stateChange:1->2 1453394913196.2417.RcoLiQ==
,2016-01-21 17:48:37.217 ThaliTest[1784:5571813] client session: fireConnectCallback: 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:37.217 ThaliTest[1784:5571813] jxcore: connect: success
ok 88 Should be able to connect without error

ok 89 Port should b,e within range

2016-01-21 17:48:37.219 ThaliTest[1784:5571164] jxcore: connect 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:37.219 ThaliTest[1784:5571164] client: already connect(ing/ed) to 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:37.220 ThaliTest,[1784:5571164] jxcore: connect: fail: Aleady connecting
ok 90 Should fail on double connect

2016-01-21 17:48:37.222 ThaliTest[1784:5571164] jxcore: disconnect
2016-01-21 17:48:37.222 ThaliTest[1784:5571164] client session: disconnectFromPeer: 14533949,13196.2417.RcoLiQ==
2016-01-21 17:48:37.222 ThaliTest[1784:5571164] client session: disconnect
2016-01-21 17:48:37.222 ThaliTest[1784:5571164] client session: stateChange:2->0 1453394913196.2417.RcoLiQ==
,2016-01-21 17:48:37.243 ThaliTest[1784:5571164] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-01-21 17:48:37.339 ThaliTest[1784:5571813] server session: connected
2016-01-21 17:48:37.339 ThaliTest[1784:5571813] server session: stateChange:1->2 1453394913196.2417
,calling stopBroadcasting

2016-01-21 17:48:37.478 ThaliTest[1784:5571164] jxcore: stopBroadcasting
2016-01-21 17:48:37.478 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
2016-01-21 17:48:37.479 ThaliTest[1784:5571164] multipeer session: stop, timer
2016-01-21 17:48:37.479 ThaliTest[1784:5571164] server session: disconnect
2016-01-21 17:48:37.479 ThaliTest[1784:5571164] server session: stateChange:2->0 1453394913196.2417
,2016-01-21 17:48:37.486 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-01-21 17:48:38.547 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:38.550 ThaliTest[1784:5571164] server: starting 1453394918547.1784.a8jYwA==
2016-01-21 17:48:38.550 ThaliTest[1784:5571164] multipeer session: start timer: 0x19fc5820
2016-01-21 17:48:38.551 ThaliTest[1784:5571164] THEMultipeerSession in,itialized peer 1453394918547.1784
2016-01-21 17:48:38.551 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-01-21 17:48:38.620 ThaliTest[1784:5570924] client: found peer: 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:38.621 ThaliTest[1784:5571164] jxcore: connect 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:38.621 ThaliTest[1784:5571164] client session: co,nnect
2016-01-21 17:48:38.621 ThaliTest[1784:5571164] client session: stateChange:0->1 1453394913196.2417.RcoLiQ==
,2016-01-21 17:48:39.594 ThaliTest[1784:5570924] client: found peer: 1453394918444.2417.sYcs3Q==
2016-01-21 17:48:39.595 ThaliTest[1784:5571164] jxcore: connect 1453394918444.2417.sYcs3Q==
2016-01-21 17:48:39.595 ThaliTest[1784:5571164] client session: co,nnect
2016-01-21 17:48:39.595 ThaliTest[1784:5571164] client session: stateChange:0->1 1453394918444.2417.sYcs3Q==
,2016-01-21 17:48:39.707 ThaliTest[1784:5570924] multipeer session: reset timer
2016-01-21 17:48:39.707 ThaliTest[1784:5570924] multipeer session: stop timer
2016-01-21 17:48:39.707 ThaliTest[1784:5570924] multipeer session: start timer: 0x19fc5820
,2016-01-21 17:48:39.707 ThaliTest[1784:5570924] server session: connect
2016-01-21 17:48:39.709 ThaliTest[1784:5570924] server session: stateChange:0->1 1453394918444.2417
,2016-01-21 17:48:39.714 ThaliTest[1784:5570924] server: accepting invitation 1453394918444.2417
,2016-01-21 17:48:40.724 ThaliTest[1784:5570924] client: lost peer: 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:40.724 ThaliTest[1784:5570924] client session: onPeerLost: 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:40.725 ThaliTest[1784:5570924] client ,session: onLinkFailure: 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:40.725 ThaliTest[1784:5570924] client session: disconnect
2016-01-21 17:48:40.725 ThaliTest[1784:5570924] client session: stateChange:1->0 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:,40.725 ThaliTest[1784:5570924] client session: fireConnectCallback: 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:40.726 ThaliTest[1784:5570924] jxcore: connect: fail: Peer disconnected
,2016-01-21 17:48:41.737 ThaliTest[1784:5571164] jxcore: connect 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:41.737 ThaliTest[1784:5571164] client: connect: unreachable 1453394913196.2417.RcoLiQ==
2016-01-21 17:48:41.737 ThaliTest[1784:5571164] jxcore: c,onnect: fail: Peer unreachable
,2016-01-21 17:48:42.134 ThaliTest[1784:5571813] server session: connected
2016-01-21 17:48:42.136 ThaliTest[1784:5571813] server session: stateChange:1->2 1453394918444.2417
2016-01-21 17:48:42.139 ThaliTest[1784:5570924] server relay: socket disconnecte,d
2016-01-21 17:48:42.139 ThaliTest[1784:5570924] server relay: 0x1c119d70 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-21 17:48:42.243 ThaliTest[1784:5571876] server session: not connected 1453394918444.2417
,2016-01-21 17:48:42.315 ThaliTest[1784:5571813] client session: connected
,2016-01-21 17:48:42.315 ThaliTest[1784:5571813] client session: stateChange:1->2 1453394918444.2417.sYcs3Q==
,2016-01-21 17:48:42.319 ThaliTest[1784:5571813] client session: fireConnectCallback: 1453394918444.2417.sYcs3Q==
2016-01-21 17:48:42.319 ThaliTest[1784:5571813] jxcore: connect: success
,ok 93 Should be able to connect without error

ok 94 Port should be within range

,2016-01-21 17:48:42.322 ThaliTest[1784:5571164] jxcore: disconnect
,2016-01-21 17:48:42.323 ThaliTest[1784:5571164] client session: disconnectFromPeer: 1453394918444.2417.sYcs3Q==
,2016-01-21 17:48:42.324 ThaliTest[1784:5571164] client session: disconnect
,2016-01-21 17:48:42.324 ThaliTest[1784:5571164] client session: stateChange:2->0 1453394918444.2417.sYcs3Q==
,2016-01-21 17:48:42.338 ThaliTest[1784:5571164] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-01-21 17:48:42.341 ThaliTest[1784:5571164] jxcore: disconnect
,2016-01-21 17:48:42.342 ThaliTest[1784:5571164] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-01-21 17:48:43.173 ThaliTest[1784:5571164] jxcore: stopBroadcasting
2016-01-21 17:48:43.174 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
2016-01-21 17:48:43.174 ThaliTest[1784:5571164] multipeer session: stop timer
2016-01-21 17:48:43.,174 ThaliTest[1784:5571164] server session: disconnect
2016-01-21 17:48:43.174 ThaliTest[1784:5571164] server session: stateChange:2->0 1453394918444.2417
,2016-01-21 17:48:43.180 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data
,
,# teardown

,echo server started on port: 56688

,2016-01-21 17:48:44.736 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:44.750 ThaliTest[1784:5571164] server: starting 1453394924736.1784.egjnUA==
,2016-01-21 17:48:44.752 ThaliTest[1784:5571164] multipeer session: start timer: 0x1c118240
,2016-01-21 17:48:44.757 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 1453394924736.1784
,2016-01-21 17:48:44.760 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-01-21 17:48:44.880 ThaliTest[1784:5570924] client: found peer: 1453394923776.2417.xwn/7Q==
,2016-01-21 17:48:44.884 ThaliTest[1784:5571164] jxcore: connect 1453394923776.2417.xwn/7Q==
,2016-01-21 17:48:44.885 ThaliTest[1784:5571164] client session: connect
,2016-01-21 17:48:44.886 ThaliTest[1784:5571164] client session: stateChange:0->1 1453394923776.2417.xwn/7Q==
,2016-01-21 17:48:46.113 ThaliTest[1784:5570924] multipeer session: reset timer
2016-01-21 17:48:46.113 ThaliTest[1784:5570924] multipeer session: stop timer
2016-01-21 17:48:46.114 ThaliTest[1784:5570924] multipeer session: start timer: 0x1c118240
2016-,01-21 17:48:46.114 ThaliTest[1784:5570924] server session: connect
2016-01-21 17:48:46.114 ThaliTest[1784:5570924] server session: stateChange:0->1 1453394923776.2417
,2016-01-21 17:48:46.120 ThaliTest[1784:5570924] server: accepting invitation 1453394923776.2417
,2016-01-21 17:48:47.576 ThaliTest[1784:5571818] client session: connected
2016-01-21 17:48:47.576 ThaliTest[1784:5571818] client session: stateChange:1->2 1453394923776.2417.xwn/7Q==
2016-01-21 17:48:47.578 ThaliTest[1784:5571818] client session: fireCon,nectCallback: 1453394923776.2417.xwn/7Q==
2016-01-21 17:48:47.578 ThaliTest[1784:5571818] jxcore: connect: success
ok 98 Should be able to connect without error

ok 99 Port should be within range

2016-01-21 17:48:47.583 ThaliTest[1784:5570924] clien,t: relay established
2016-01-21 17:48:47.583 ThaliTest[1784:5570924] client: new accepted socket: 0x1c52ce80
,data in 16425

,data in 24090

,data in 25114

,data in 31755

,data in 38923

,data in 74460

data in 84315

,data in 89790

,data in 99645

,data in 116070

,data in 131072

,ok 100 the test messages should be equal

,2016-01-21 17:48:47.987 ThaliTest[1784:5571164] jxcore: disconnect
2016-01-21 17:48:47.987 ThaliTest[1784:5571164] client session: disconnectFromPeer: 1453394923776.2417.xwn/7Q==
2016-01-21 17:48:47.988 ThaliTest[1784:5571164] client session: disconnect,
2016-01-21 17:48:47.988 ThaliTest[1784:5571164] client session: stateChange:2->0 1453394923776.2417.xwn/7Q==
,2016-01-21 17:48:47.998 ThaliTest[1784:5571164] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

# setup

,2016-01-21 17:48:48.556 ThaliTest[1784:5571820] server session: connected
2016-01-21 17:48:48.556 ThaliTest[1784:5571820] server session: stateChange:1->2 1453394923776.2417
,2016-01-21 17:48:48.561 ThaliTest[1784:5570924] server relay: connected (to port: 56688)
,2016-01-21 17:48:49.070 ThaliTest[1784:5571818] server session: not connected 1453394923776.2417
,calling stopBroadcasting

2016-01-21 17:48:50.001 ThaliTest[1784:5571164] jxcore: stopBroadcasting
2016-01-21 17:48:50.001 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
2016-01-21 17:48:50.001 ThaliTest[1784:5571164] multipeer session: stop, timer
2016-01-21 17:48:50.001 ThaliTest[1784:5571164] server session: disconnect
2016-01-21 17:48:50.001 ThaliTest[1784:5571164] server session: stateChange:2->0 1453394923776.2417
,2016-01-21 17:48:50.007 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 56694

,2016-01-21 17:48:50.483 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:50.486 ThaliTest[1784:5571164] server: starting 1453394930482.1784.TAWkpA==
2016-01-21 17:48:50.486 ThaliTest[1784:5571164] multipeer session: start timer: 0x1c5297a0
2016-01-21 17:48:50.486 ThaliTest[1784:5571164] THEMultipeerSession in,itialized peer 1453394930482.1784
2016-01-21 17:48:50.486 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-01-21 17:48:51.134 ThaliTest[1784:5570924] client: found peer: 1453394923776.2417.xwn/7Q==
[{"peerIdentifier":"1453394923776.2417.xwn/7Q==","peerName":"(null)","peerAvailable":true}]

2016-01-21 17:48:51.136 ThaliTest[1784:5571164] jxcore: connect ,1453394923776.2417.xwn/7Q==
2016-01-21 17:48:51.136 ThaliTest[1784:5571164] client session: connect
2016-01-21 17:48:51.136 ThaliTest[1784:5571164] client session: stateChange:0->1 1453394923776.2417.xwn/7Q==
,2016-01-21 17:48:51.703 ThaliTest[1784:5570924] client: lost peer: 1453394923776.2417.xwn/7Q==
2016-01-21 17:48:51.703 ThaliTest[1784:5570924] client session: onPeerLost: 1453394923776.2417.xwn/7Q==
2016-01-21 17:48:51.703 ThaliTest[1784:5570924] client ,session: onLinkFailure: 1453394923776.2417.xwn/7Q==
2016-01-21 17:48:51.703 ThaliTest[1784:5570924] client session: disconnect
2016-01-21 17:48:51.704 ThaliTest[1784:5570924] client session: stateChange:1->0 1453394923776.2417.xwn/7Q==
2016-01-21 17:48:,51.704 ThaliTest[1784:5570924] client session: fireConnectCallback: 1453394923776.2417.xwn/7Q==
2016-01-21 17:48:51.705 ThaliTest[1784:5570924] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1453394923776.2417.xwn/7Q==","peerName":"(null)","peerAvailable":false}]

,2016-01-21 17:48:51.781 ThaliTest[1784:5570924] client: found peer: 1453394930396.2417.fmxBLA==
[{"peerIdentifier":"1453394930396.2417.fmxBLA==","peerName":"(null)","peerAvailable":true}]

2016-01-21 17:48:51.782 ThaliTest[1784:5571164] jxcore: connect ,1453394930396.2417.fmxBLA==
2016-01-21 17:48:51.783 ThaliTest[1784:5571164] client session: connect
2016-01-21 17:48:51.783 ThaliTest[1784:5571164] client session: stateChange:0->1 1453394930396.2417.fmxBLA==
,2016-01-21 17:48:51.948 ThaliTest[1784:5570924] multipeer session: reset timer
2016-01-21 17:48:51.948 ThaliTest[1784:5570924] multipeer session: stop timer
2016-01-21 17:48:51.949 ThaliTest[1784:5570924] multipeer session: start timer: 0x1c5297a0
2016-,01-21 17:48:51.949 ThaliTest[1784:5570924] server session: connect
2016-01-21 17:48:51.949 ThaliTest[1784:5570924] server session: stateChange:0->1 1453394930396.2417
,2016-01-21 17:48:51.956 ThaliTest[1784:5570924] server: accepting invitation 1453394930396.2417
,2016-01-21 17:48:52.715 ThaliTest[1784:5571164] jxcore: connect 1453394923776.2417.xwn/7Q==
2016-01-21 17:48:52.716 ThaliTest[1784:5571164] client: connect: unreachable 1453394923776.2417.xwn/7Q==
2016-01-21 17:48:52.716 ThaliTest[1784:5571164] jxcore: connect: fail: Peer unreachable
,2016-01-21 17:48:54.591 ThaliTest[1784:5571818] client session: connected
,2016-01-21 17:48:54.591 ThaliTest[1784:5571818] client session: stateChange:1->2 1453394930396.2417.fmxBLA==
,2016-01-21 17:48:54.598 ThaliTest[1784:5571876] client session: fireConnectCallback: 1453394930396.2417.fmxBLA==
2016-01-21 17:48:54.601 ThaliTest[1784:5571876] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should be within range

ok 105 First connect should succeed

,2016-01-21 17:48:54.623 ThaliTest[1784:5570924] client: relay established
2016-01-21 17:48:54.623 ThaliTest[1784:5570924] client: new accepted socket: 0x19a0e7d0
,2016-01-21 17:48:54.644 ThaliTest[1784:5571818] server session: connected
2016-01-21 17:48:54.646 ThaliTest[1784:5571818] server session: stateChange:1->2 1453394930396.2417
,2016-01-21 17:48:54.648 ThaliTest[1784:5570924] server relay: connected (to port: 56694)
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-01-21 17:48:54.720 ThaliTest[1784:5570924] client: socket closed
,2016-01-21 17:48:54.720 ThaliTest[1784:5570924] client relay: socket disconnected
2016-01-21 17:48:54.720 ThaliTest[1784:5570924] client relay: 0x19a0e7d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-21 17:48:54.720 ThaliTest[1784:5570924] client session: socket closed: 1453394930396.2417.fmxBLA==
2016-01-21 17:48:54.721 ThaliTest[1784:5570924] client session: onLinkFailure: 1453394930396.2417.fmxBLA==
2016-01-21 17:48:54.721 ThaliTest[1784:5,570924] client session: disconnect
2016-01-21 17:48:54.721 ThaliTest[1784:5570924] client session: stateChange:2->0 1453394930396.2417.fmxBLA==
,2016-01-21 17:48:54.792 ThaliTest[1784:5570924] client session: fireConnectionErrorEvent: 1453394930396.2417.fmxBLA==
,2016-01-21 17:48:54.795 ThaliTest[1784:5571164] jxcore: connect 1453394930396.2417.fmxBLA==
,2016-01-21 17:48:54.796 ThaliTest[1784:5571164] client session: connect
,2016-01-21 17:48:54.797 ThaliTest[1784:5571164] client session: stateChange:0->1 1453394930396.2417.fmxBLA==
,2016-01-21 17:48:54.903 ThaliTest[1784:5571818] server session: not connected 1453394930396.2417
,2016-01-21 17:48:55.103 ThaliTest[1784:5570924] multipeer session: reset timer
2016-01-21 17:48:55.103 ThaliTest[1784:5570924] multipeer session: stop timer
2016-01-21 17:48:55.103 ThaliTest[1784:5570924] multipeer session: start timer: 0x1c5297a0
2016-01-21 17:48:55.103 ThaliTest[1784:5570924] server: disconnecting to refresh session (1453394930396.2417)
2016-01-21 17:48:55.104 ThaliTest[1784:5570924] server session: disconnect
2016-01-21 17:48:55.104 ThaliTest[1784:5570924] server session: stateChange:2->0 1453394930396.2417
,2016-01-21 17:48:55.254 ThaliTest[1784:5570924] server session: connect
,2016-01-21 17:48:55.254 ThaliTest[1784:5570924] server session: stateChange:0->1 1453394930396.2417
,2016-01-21 17:48:55.264 ThaliTest[1784:5570924] server: accepting invitation 1453394930396.2417
,2016-01-21 17:48:57.673 ThaliTest[1784:5571951] client session: connected
,2016-01-21 17:48:57.674 ThaliTest[1784:5571951] client session: stateChange:1->2 1453394930396.2417.fmxBLA==
,2016-01-21 17:48:57.678 ThaliTest[1784:5571951] client session: fireConnectCallback: 1453394930396.2417.fmxBLA==
,2016-01-21 17:48:57.679 ThaliTest[1784:5571951] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-01-21 17:48:57.702 ThaliTest[1784:5570924] client: relay established
,2016-01-21 17:48:57.703 ThaliTest[1784:5570924] client: new accepted socket: 0x155e1000
,2016-01-21 17:48:57.793 ThaliTest[1784:5571815] server session: connected
,2016-01-21 17:48:57.794 ThaliTest[1784:5571815] server session: stateChange:1->2 1453394930396.2417
,2016-01-21 17:48:57.799 ThaliTest[1784:5570924] server relay: connected (to port: 56694)
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup
,
,2016-01-21 17:48:57.881 ThaliTest[1784:5570924] client: socket closed
,2016-01-21 17:48:57.882 ThaliTest[1784:5570924] client relay: socket disconnected
2016-01-21 17:48:57.882 ThaliTest[1784:5570924] client relay: 0x155e1000 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-21 17:48:57.882 ThaliTest[1784:5570924] client session: socket closed: 1453394930396.2417.fmxBLA==
2016-01-21 17:48:57.882 ThaliTest[1784:5570924] client session: onLinkFailure: 1453394930396.2417.fmxBLA==
2016-01-21 17:48:57.882 ThaliTest[1784:5,570924] client session: disconnect
2016-01-21 17:48:57.883 ThaliTest[1784:5570924] client session: stateChange:2->0 1453394930396.2417.fmxBLA==
,2016-01-21 17:48:57.894 ThaliTest[1784:5570924] client session: fireConnectionErrorEvent: 1453394930396.2417.fmxBLA==
,2016-01-21 17:48:57.909 ThaliTest[1784:5571813] server session: not connected 1453394930396.2417
,calling stopBroadcasting

,2016-01-21 17:48:57.931 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:57.931 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:57.932 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:57.936 ThaliTest[1784:5571164] server session: disconnect
,2016-01-21 17:48:57.938 ThaliTest[1784:5571164] server session: stateChange:2->0 1453394930396.2417
,2016-01-21 17:48:57.945 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,
,# ThaliReplicationManager can call start without error
,
,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FEA2980A-541B-44B3-8610-EA782657A26B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-01-21 17:48:58.578 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:58.580 ThaliTest[1784:5571164] server: starting 7CmZmRa2LOtPuthCwLFqow.eT113A==
,2016-01-21 17:48:58.583 ThaliTest[1784:5571164] multipeer session: start timer: 0x19a0d9e0
,2016-01-21 17:48:58.588 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 7CmZmRa2LOtPuthCwLFqow
,2016-01-21 17:48:58.589 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

,Now in TRM stop

,State of this._isStarted: true
,
,ok 115 stopping event should occur in right order

,About to call stopBroadcasting
,
,2016-01-21 17:48:58.594 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:58.595 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:58.595 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:58.599 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FEA2980A-541B-44B3-8610-EA782657A26B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-01-21 17:48:59.566 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:48:59.569 ThaliTest[1784:5571164] server: starting 7CmZmRa2LOtPuthCwLFqow.+7x1jw==
,2016-01-21 17:48:59.574 ThaliTest[1784:5571164] multipeer session: start timer: 0x1c540a50
,2016-01-21 17:48:59.578 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 7CmZmRa2LOtPuthCwLFqow
,2016-01-21 17:48:59.579 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

,Now in TRM stop
,
,State of this._isStarted: true

,About to call stopBroadcasting
,
,2016-01-21 17:48:59.583 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:48:59.584 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:48:59.585 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:48:59.589 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FEA2980A-541B-44B3-8610-EA782657A26B/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,
,2016-01-21 17:49:04.582 ThaliTest[1784:5571164] jxcore: startBroadcasting
,2016-01-21 17:49:04.584 ThaliTest[1784:5571164] server: starting 7CmZmRa2LOtPuthCwLFqow.X62ZIQ==
,2016-01-21 17:49:04.586 ThaliTest[1784:5571164] multipeer session: start timer: 0x19b8dac0
,2016-01-21 17:49:04.594 ThaliTest[1784:5570924] client: found peer: -FhetZcCv7KJMzbq9EHhmw.QS6PJw==
2016-01-21 17:49:04.594 ThaliTest[1784:5571164] THEMultipeerSession initialized peer 7CmZmRa2LOtPuthCwLFqow
,2016-01-21 17:49:04.598 ThaliTest[1784:5571164] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

,ok 120 deviceName should not be null

,2016-01-21 17:49:14.546 ThaliTest[1784:5571164] jxcore: connect -FhetZcCv7KJMzbq9EHhmw.QS6PJw==
,2016-01-21 17:49:14.549 ThaliTest[1784:5571164] client session: connect
,2016-01-21 17:49:14.551 ThaliTest[1784:5571164] client session: stateChange:0->1 -FhetZcCv7KJMzbq9EHhmw.QS6PJw==
,ok 121 Should be able to put doc without error
,
,ok 122 1st change of local doc should contain local id
,
,2016-01-21 17:49:14.817 ThaliTest[1784:5570924] multipeer session: reset timer
2016-01-21 17:49:14.818 ThaliTest[1784:5570924] multipeer session: stop timer
2016-01-21 17:49:14.818 ThaliTest[1784:5570924] multipeer session: start timer: 0x19b8dac0
2016-,01-21 17:49:14.818 ThaliTest[1784:5570924] server session: connect
2016-01-21 17:49:14.818 ThaliTest[1784:5570924] server session: stateChange:0->1 -FhetZcCv7KJMzbq9EHhmw
,2016-01-21 17:49:14.828 ThaliTest[1784:5570924] server: accepting invitation -FhetZcCv7KJMzbq9EHhmw
,2016-01-21 17:49:17.444 ThaliTest[1784:5571980] server session: connected
2016-01-21 17:49:17.444 ThaliTest[1784:5571980] server session: stateChange:1->2 -FhetZcCv7KJMzbq9EHhmw
,2016-01-21 17:49:17.455 ThaliTest[1784:5571876] client session: connected
2016-01-21 17:49:17.456 ThaliTest[1784:5571876] client session: stateChange:1->2 -FhetZcCv7KJMzbq9EHhmw.QS6PJw==
,2016-01-21 17:49:17.459 ThaliTest[1784:5570924] server relay: connected (to port: 56710)
,server bridge: new client socket

2016-01-21 17:49:17.470 ThaliTest[1784:5571980] client session: fireConnectCallback: -FhetZcCv7KJMzbq9EHhmw.QS6PJw==
2016-01-21 17:49:17.470 ThaliTest[1784:5571980] jxcore: connect: success
,2016-01-21 17:49:17.482 ThaliTest[1784:5570924] client: relay established
,2016-01-21 17:49:17.483 ThaliTest[1784:5570924] client: new accepted socket: 0x19ef5bd0
,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed
,
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
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed
,
,ok 123 1st change of remote doc should contain remote id
,
,ok 124 Can update remote doc without error

,null
,
,{ ok: true,
  id: 'bac8bad8-85e5-423f-88d0-9d4e59690034',
  rev: '2-09a96ef6e3ac9771b7eb17ddd5491567' }

,client bridge: new client socket

,ok 125 Remote changes occur in strict order

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
,
,client bridge: socket closed

,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id
,
,# setup
,
,client bridge: new client socket

,client bridge: new client socket

,Now in TRM stop

,State of this._isStarted: true
,
About to call stopBroadcasting

,2016-01-21 17:49:40.778 ThaliTest[1784:5571164] jxcore: stopBroadcasting
,2016-01-21 17:49:40.779 ThaliTest[1784:5571164] THEMultipeerSession stopping peer
,2016-01-21 17:49:40.779 ThaliTest[1784:5571164] multipeer session: stop timer
,2016-01-21 17:49:40.781 ThaliTest[1784:5571164] client session: disconnect
,2016-01-21 17:49:40.783 ThaliTest[1784:5571164] client session: stateChange:2->0 -FhetZcCv7KJMzbq9EHhmw.QS6PJw==
,2016-01-21 17:49:40.842 ThaliTest[1784:5572003] server session: not connected -FhetZcCv7KJMzbq9EHhmw
,2016-01-21 17:49:40.852 ThaliTest[1784:5571164] server session: disconnect
2016-01-21 17:49:40.854 ThaliTest[1784:5571164] server session: stateChange:2->0 -FhetZcCv7KJMzbq9EHhmw
,2016-01-21 17:49:40.929 ThaliTest[1784:5571164] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,# #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

,client bridge: socket closed

,incoming client socket error Error: read ECONNRESET

mux server bridge listener closed

,2016-01-21 17:49:40.977 ThaliTest[1784:5571164] Error!: connect ECONNREFUSED
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$09","_lineNumbe,r":"829","_columnNumber":"13","_msg":"    at $09@net.js:829:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
,Uncaught Exception: Error: connect ECONNREFUSED

,[ { _fileName: 'net.js',
,    _functionName: '$c',
    _lineNumber: '837',
    _columnNumber: '7',
,    _msg: '    at $c@net.js:837:7' },
  { _fileName: 'net.js',
    _functionName: '$09',
    _lineNumber: '829',
    _columnNumber: '13',
    _msg: '    at $09@net.js:829:13' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber,: '837',
    _columnNumber: '7',
    _msg: '' },
  toString: [Function] ]

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
