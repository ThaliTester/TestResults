#### Test 579720943a29850_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/579720943a29850/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/5E1DDCAF-FEE7-4FBA-A7E3-5626C6B33A7D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5E1DDCAF-FEE7-4FBA-A7E3-5626C6B33A7D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/579720943a29850/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/579720943a29850/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FEC34985-9171-4D60-B51A-D1F0A1DABBCD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64120"
,(lldb)     command script import "/tmp/5E1DDCAF-FEE7-4FBA-A7E3-5626C6B33A7D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 13:05:47.218 ThaliTest[428:674922] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9AC8971C-4E59-46EA-B0C0-99FA29C757AD/Library/Cookies/Cookies.binarycookies
,2016-02-02 13:05:47.656 ThaliTest[428:674922] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 13:05:47.657 ThaliTest[428:674922] Multi-tasking -> Device: YES, App: YES
,2016-02-02 13:05:47.666 ThaliTest[428:674922] Unlimited access to network resources
,2016-02-02 13:05:47.675 ThaliTest[428:674922] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 13:05:57.792 ThaliTest[428:674922] Resetting plugins due to page load.
,2016-02-02 13:06:02.079 ThaliTest[428:674922] Finished load of: file:///var/mobile/Containers/Bundle/Application/FEC34985-9171-4D60-B51A-D1F0A1DABBCD/ThaliTest.app/www/index.html
,2016-02-02 13:06:02.217 ThaliTest[428:674922] JXcore Cordova plugin initializing
,2016-02-02 13:06:02.218 ThaliTest[428:675186] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FEC34985-9171-4D60-B51A-D1F0A1DABBCD/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FEC34985-9171-4D60-B51A-D1F0A1DABBCD/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FEC34985-9171-4D60-B51A-D1F0A1DABBCD/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FEC34985-9171-4D60-B51A-D1F0A1DABBCD/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FEC34985-9171-4D60-B51A-D1F0A1DABBCD/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FEC34985-9171-4D60-B51A-D1F0A1DABBCD/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FEC34985-9171-4D60-B51A-D1F0A1DABBCD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FEC34985-9171-4D60-B51A-D1F0A1DABBCD/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-02-02 13:10:17.697 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:17.714 ThaliTest[428:675186] server: starting 1454415017697.428.w35aOw==
,2016-02-02 13:10:17.716 ThaliTest[428:675186] multipeer session: start timer: 0x16e2a7e0
2016-02-02 13:10:17.716 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415017697.428
,2016-02-02 13:10:17.717 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.723 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:17.724 ThaliTest[428:675186] THEMultipeerSession stopping peer
2016-02-02 13:10:17.725 ThaliTest[428:675186] multipeer session: stop timer
2016-02-02 13:10:17.726 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 55 Should be able to call stopBroadcasting without error

2016-02-02 13:10:17.730 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:17.736 ThaliTest[428:675186] server: starting 1454415017730.428.Hi+fHw==
2016-02-02 13:10:17.737 ThaliTest[428:675186] multipeer session: start timer: 0x178ca800
2016-02-02 13:10:17.737 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415017730.428
2016-02-02 13:10:17.738 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.745 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:17.747 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.747 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:17.749 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.754 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:17.757 ThaliTest[428:675186] server: starting 1454415017753.428.CZjDIQ==
,2016-02-02 13:10:17.759 ThaliTest[428:675186] multipeer session: start timer: 0x17c4a620
,2016-02-02 13:10:17.766 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415017753.428
,2016-02-02 13:10:17.767 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.769 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:17.770 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.771 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:17.772 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.778 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:17.782 ThaliTest[428:675186] server: starting 1454415017778.428.BnPEYw==
,2016-02-02 13:10:17.784 ThaliTest[428:675186] multipeer session: start timer: 0x17c4a510
,2016-02-02 13:10:17.790 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415017778.428
,2016-02-02 13:10:17.792 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.796 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:17.796 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.798 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:17.802 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.805 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:17.807 ThaliTest[428:675186] server: starting 1454415017804.428.tpxhfQ==
,2016-02-02 13:10:17.810 ThaliTest[428:675186] multipeer session: start timer: 0x16e2e180
,2016-02-02 13:10:17.813 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415017804.428
2016-02-02 13:10:17.814 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.816 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:17.817 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.817 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:17.818 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.823 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:17.825 ThaliTest[428:675186] server: starting 1454415017822.428.JWWECg==
,2016-02-02 13:10:17.826 ThaliTest[428:675186] multipeer session: start timer: 0x16e2dcf0
,2016-02-02 13:10:17.829 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415017822.428
,2016-02-02 13:10:17.831 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.834 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:17.834 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.835 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:17.836 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.840 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:17.842 ThaliTest[428:675186] server: starting 1454415017839.428.5OI27g==
,2016-02-02 13:10:17.843 ThaliTest[428:675186] multipeer session: start timer: 0x17c4b650
,2016-02-02 13:10:17.847 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415017839.428
,2016-02-02 13:10:17.848 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.851 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:17.851 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.852 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:17.853 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.857 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:17.860 ThaliTest[428:675186] server: starting 1454415017857.428.t+fkvQ==
,2016-02-02 13:10:17.861 ThaliTest[428:675186] multipeer session: start timer: 0x17c4c5f0
,2016-02-02 13:10:17.864 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415017857.428
,2016-02-02 13:10:17.865 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.867 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:17.868 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.868 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:17.870 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.873 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:17.875 ThaliTest[428:675186] server: starting 1454415017873.428.CsbS4w==
,2016-02-02 13:10:17.877 ThaliTest[428:675186] multipeer session: start timer: 0x17c4ca50
,2016-02-02 13:10:17.878 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415017873.428
,2016-02-02 13:10:17.880 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.883 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:17.884 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.884 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:17.885 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.888 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:17.889 ThaliTest[428:675186] server: starting 1454415017887.428.cINZ1w==
,2016-02-02 13:10:17.890 ThaliTest[428:675186] multipeer session: start timer: 0x14ec5480
,2016-02-02 13:10:17.891 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415017887.428
,2016-02-02 13:10:17.892 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.895 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:17.895 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.895 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:17.896 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-02 13:10:18.082 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:18.085 ThaliTest[428:675186] server: starting 1454415018081.428.AEAQAg==
,2016-02-02 13:10:18.087 ThaliTest[428:675186] multipeer session: start timer: 0x17c4a460
,2016-02-02 13:10:18.091 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415018081.428
,2016-02-02 13:10:18.093 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-02 13:10:18.098 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:18.098 ThaliTest[428:675186] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice
,
,2016-02-02 13:10:18.104 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:18.105 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:18.106 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:18.108 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-02 13:10:19.084 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:19.087 ThaliTest[428:675186] server: starting 1454415019083.428.z241XA==
,2016-02-02 13:10:19.088 ThaliTest[428:675186] multipeer session: start timer: 0x16b09390
,2016-02-02 13:10:19.089 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415019083.428
,2016-02-02 13:10:19.090 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

2016-02-02 13:10:19.092 ThaliTest[428:675186] jxcore: connect foobar
2016-02-02 13:10:19.093 ThaliTest[428:675186] client: unknown peer foobar
2016-02-02 13:10:19.093 ThaliTest[428:675186] j,xcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

,2016-02-02 13:10:19.098 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:19.098 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:19.099 ThaliTest[428:675186] multipeer session: stop timer
2016-02-02 13:10:19.100 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-02 13:10:19.628 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:19.632 ThaliTest[428:675186] server: starting 1454415019628.428.gxbgAw==
,2016-02-02 13:10:19.632 ThaliTest[428:675186] multipeer session: start timer: 0x16a89ce0
2016-02-02 13:10:19.633 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415019628.428
2016-02-02 13:10:19.634 ThaliTest[428:675186] jxcore: startBroad,casting: success
ok 80 Should be able to call startBroadcasting without error

,2016-02-02 13:10:19.636 ThaliTest[428:675186] jxcore: disconnect
2016-02-02 13:10:19.637 ThaliTest[428:675186] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

,2016-02-02 13:10:19.643 ThaliTest[428:675186] jxcore: stopBroadcasting
2016-02-02 13:10:19.644 ThaliTest[428:675186] THEMultipeerSession stopping peer
2016-02-02 13:10:19.644 ThaliTest[428:675186] multipeer session: stop timer
2016-02-02 13:10:19.645 ThaliTest[428:675186] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown
,
,2016-02-02 13:10:20.611 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:20.615 ThaliTest[428:675186] server: starting 1454415020611.428.QLjBuw==
,2016-02-02 13:10:20.616 ThaliTest[428:675186] multipeer session: start timer: 0x17b49540
,2016-02-02 13:10:20.616 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415020611.428
,2016-02-02 13:10:20.618 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-02 13:10:21.496 ThaliTest[428:674922] client: found peer: 1454415020523.2313.MLQeWw==
,2016-02-02 13:10:21.499 ThaliTest[428:675186] jxcore: connect 1454415020523.2313.MLQeWw==
2016-02-02 13:10:21.500 ThaliTest[428:675186] client session: connect
2016-02-02 13:10:21.501 ThaliTest[428:675186] client session: stateChange:0->1 1454415020523.2313.MLQeWw==
,2016-02-02 13:10:22.234 ThaliTest[428:674922] multipeer session: reset timer
2016-02-02 13:10:22.234 ThaliTest[428:674922] multipeer session: stop timer
2016-02-02 13:10:22.234 ThaliTest[428:674922] multipeer session: start timer: 0x17b49540
,2016-02-02 13:10:22.235 ThaliTest[428:674922] server session: connect
2016-02-02 13:10:22.235 ThaliTest[428:674922] server session: stateChange:0->1 1454415020523.2313
,2016-02-02 13:10:22.241 ThaliTest[428:674922] server: accepting invitation 1454415020523.2313
,2016-02-02 13:10:25.246 ThaliTest[428:675592] client session: connected
2016-02-02 13:10:25.246 ThaliTest[428:675592] client session: stateChange:1->2 1454415020523.2313.MLQeWw==
,2016-02-02 13:10:25.250 ThaliTest[428:675592] client session: fireConnectCallback: 1454415020523.2313.MLQeWw==
,2016-02-02 13:10:25.251 ThaliTest[428:675592] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-02 13:10:25.256 ThaliTest[428:675186] jxcore: disconnect
,2016-02-02 13:10:25.256 ThaliTest[428:675186] client session: disconnectFromPeer: 1454415020523.2313.MLQeWw==
,2016-02-02 13:10:25.257 ThaliTest[428:675186] client session: disconnect
2016-02-02 13:10:25.258 ThaliTest[428:675186] client session: stateChange:2->0 1454415020523.2313.MLQeWw==
,2016-02-02 13:10:25.331 ThaliTest[428:675186] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-02 13:10:25.439 ThaliTest[428:675590] server session: connected
2016-02-02 13:10:25.439 ThaliTest[428:675590] server session: stateChange:1->2 1454415020523.2313
,2016-02-02 13:10:25.445 ThaliTest[428:674922] server relay: socket disconnected
2016-02-02 13:10:25.445 ThaliTest[428:674922] server relay: 0x14f01bf0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-02 13:10:25.486 ThaliTest[428:675588] server session: not connected 1454415020523.2313
,calling stopBroadcasting

,2016-02-02 13:10:25.515 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:25.516 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:25.517 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:25.518 ThaliTest[428:675186] server session: disconnect
2016-02-02 13:10:25.518 ThaliTest[428:675186] server session: stateChange:2->0 1454415020523.2313
,2016-02-02 13:10:25.522 ThaliTest[428:675186] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-02 13:10:26.027 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:26.030 ThaliTest[428:675186] server: starting 1454415026027.428.a3OVsg==
,2016-02-02 13:10:26.031 ThaliTest[428:675186] multipeer session: start timer: 0x17dd28d0
2016-02-02 13:10:26.032 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415026027.428
2016-02-02 13:10:26.032 ThaliTest[428:675186] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-02 13:10:27.163 ThaliTest[428:674922] client: found peer: 1454415025934.2313.8C1EhA==
,2016-02-02 13:10:27.164 ThaliTest[428:675186] jxcore: connect 1454415025934.2313.8C1EhA==
2016-02-02 13:10:27.165 ThaliTest[428:675186] client session: connect
2016-02-02 13:10:27.165 ThaliTest[428:675186] client session: stateChange:0->1 1454415025934.2313.8C1EhA==
,2016-02-02 13:10:27.691 ThaliTest[428:674922] multipeer session: reset timer
2016-02-02 13:10:27.691 ThaliTest[428:674922] multipeer session: stop timer
2016-02-02 13:10:27.691 ThaliTest[428:674922] multipeer session: start timer: 0x17dd28d0
2016-02-02 13:10:27.691 ThaliTest[428:674922] server session: connect
2016-02-02 13:10:27.691 ThaliTest[428:674922] server session: stateChange:0->1 1454415025934.2313
,2016-02-02 13:10:27.694 ThaliTest[428:674922] server: accepting invitation 1454415025934.2313
,2016-02-02 13:10:30.089 ThaliTest[428:675588] client session: connected
,2016-02-02 13:10:30.090 ThaliTest[428:675588] client session: stateChange:1->2 1454415025934.2313.8C1EhA==
,2016-02-02 13:10:30.100 ThaliTest[428:675588] client session: fireConnectCallback: 1454415025934.2313.8C1EhA==
,2016-02-02 13:10:30.101 ThaliTest[428:675588] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-02 13:10:30.105 ThaliTest[428:675186] jxcore: connect 1454415025934.2313.8C1EhA==
,2016-02-02 13:10:30.106 ThaliTest[428:675186] client: already connect(ing/ed) to 1454415025934.2313.8C1EhA==
,2016-02-02 13:10:30.106 ThaliTest[428:675186] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-02 13:10:30.110 ThaliTest[428:675186] jxcore: disconnect
2016-02-02 13:10:30.110 ThaliTest[428:675186] client session: disconnectFromPeer: 1454415025934.2313.8C1EhA==
,2016-02-02 13:10:30.111 ThaliTest[428:675186] client session: disconnect
,2016-02-02 13:10:30.111 ThaliTest[428:675186] client session: stateChange:2->0 1454415025934.2313.8C1EhA==
,2016-02-02 13:10:30.184 ThaliTest[428:675186] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-02 13:10:30.350 ThaliTest[428:675588] server session: connected
2016-02-02 13:10:30.350 ThaliTest[428:675588] server session: stateChange:1->2 1454415025934.2313
,2016-02-02 13:10:30.362 ThaliTest[428:674922] server relay: socket disconnected
2016-02-02 13:10:30.362 ThaliTest[428:674922] server relay: 0x14e80f30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-02 13:10:30.416 ThaliTest[428:675588] server session: not connected 1454415025934.2313
,calling stopBroadcasting

2016-02-02 13:10:31.025 ThaliTest[428:675186] jxcore: stopBroadcasting
2016-02-02 13:10:31.026 ThaliTest[428:675186] THEMultipeerSession stopping peer
2016-02-02 13:10:31.026 ThaliTest[428:675186] multipeer session: stop timer
2016-02-02 13:10:31.027 ThaliTest[428:675186] server session: disconnect
2016-02-02 13:10:31.028 ThaliTest[428:675186] server session: stateChange:2->0 1454415025934.2313
,2016-02-02 13:10:31.029 ThaliTest[428:675186] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-02 13:10:32.635 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:32.638 ThaliTest[428:675186] server: starting 1454415032635.428.uRxb8A==
,2016-02-02 13:10:32.639 ThaliTest[428:675186] multipeer session: start timer: 0x14e819c0
,2016-02-02 13:10:32.640 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415032635.428
2016-02-02 13:10:32.640 ThaliTest[428:675186] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-02 13:10:34.050 ThaliTest[428:674922] multipeer session: reset timer
2016-02-02 13:10:34.050 ThaliTest[428:674922] multipeer session: stop timer
2016-02-02 13:10:34.051 ThaliTest[428:674922] multipeer session: start timer: 0x14e819c0
2016-02-02 13:10:34.051 ThaliTest[428:674922] server session: connect
,2016-02-02 13:10:34.051 ThaliTest[428:674922] server session: stateChange:0->1 1454415032539.2313
,2016-02-02 13:10:34.058 ThaliTest[428:674922] server: accepting invitation 1454415032539.2313
,2016-02-02 13:10:34.157 ThaliTest[428:674922] client: found peer: 1454415032539.2313.++UI8g==
,2016-02-02 13:10:34.158 ThaliTest[428:675186] jxcore: connect 1454415032539.2313.++UI8g==
2016-02-02 13:10:34.159 ThaliTest[428:675186] client session: connect
2016-02-02 13:10:34.160 ThaliTest[428:675186] client session: stateChange:0->1 1454415032539.2313.++UI8g==
,2016-02-02 13:10:37.072 ThaliTest[428:675588] server session: connected
2016-02-02 13:10:37.073 ThaliTest[428:675588] server session: stateChange:1->2 1454415032539.2313
,2016-02-02 13:10:37.075 ThaliTest[428:675684] client session: connected
,2016-02-02 13:10:37.077 ThaliTest[428:675684] client session: stateChange:1->2 1454415032539.2313.++UI8g==
,2016-02-02 13:10:37.082 ThaliTest[428:675684] client session: fireConnectCallback: 1454415032539.2313.++UI8g==
2016-02-02 13:10:37.082 ThaliTest[428:675684] jxcore: connect: success
,2016-02-02 13:10:37.085 ThaliTest[428:674922] server relay: socket disconnected
ok 93 Should be able to connect without error

2016-02-02 13:10:37.085 ThaliTest[428:674922] server relay: 0x17dd4a40 disconnected with error Error Domain=NSPOSIXErrorDomain, Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,ok 94 Port should be within range

,2016-02-02 13:10:37.087 ThaliTest[428:675186] jxcore: disconnect
,2016-02-02 13:10:37.088 ThaliTest[428:675186] client session: disconnectFromPeer: 1454415032539.2313.++UI8g==
,2016-02-02 13:10:37.088 ThaliTest[428:675186] client session: disconnect
,2016-02-02 13:10:37.089 ThaliTest[428:675186] client session: stateChange:2->0 1454415032539.2313.++UI8g==
,2016-02-02 13:10:37.162 ThaliTest[428:675186] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-02 13:10:37.164 ThaliTest[428:675186] jxcore: disconnect
,2016-02-02 13:10:37.164 ThaliTest[428:675186] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,2016-02-02 13:10:37.176 ThaliTest[428:675598] server session: not connected 1454415032539.2313
,# setup

,calling stopBroadcasting

,2016-02-02 13:10:37.566 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:37.567 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:37.568 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:37.568 ThaliTest[428:675186] server session: disconnect
2016-02-02 13:10:37.569 ThaliTest[428:675186] server session: stateChange:2->0 1454415032539.2313
,2016-02-02 13:10:37.572 ThaliTest[428:675186] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 51080

,2016-02-02 13:10:42.533 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:42.534 ThaliTest[428:675186] server: starting 1454415042533.428.NkSsuA==
,2016-02-02 13:10:42.535 ThaliTest[428:675186] multipeer session: start timer: 0x16c54ad0
2016-02-02 13:10:42.535 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415042533.428
2016-02-02 13:10:42.535 ThaliTest[428:675186] jxcore: startBroad,casting: success
ok 97 Should be able to call startBroadcasting without error

,2016-02-02 13:10:42.538 ThaliTest[428:674922] client: found peer: 1454415040155.2313.JIJ5wg==
,2016-02-02 13:10:42.539 ThaliTest[428:675186] jxcore: connect 1454415040155.2313.JIJ5wg==
2016-02-02 13:10:42.539 ThaliTest[428:675186] client session: connect
2016-02-02 13:10:42.539 ThaliTest[428:675186] client session: stateChange:0->1 1454415040155.2313.JIJ5wg==
,2016-02-02 13:10:43.653 ThaliTest[428:674922] multipeer session: reset timer
2016-02-02 13:10:43.653 ThaliTest[428:674922] multipeer session: stop timer
2016-02-02 13:10:43.653 ThaliTest[428:674922] multipeer session: start timer: 0x16c54ad0
,2016-02-02 13:10:43.653 ThaliTest[428:674922] server session: connect
,2016-02-02 13:10:43.653 ThaliTest[428:674922] server session: stateChange:0->1 1454415040155.2313
,2016-02-02 13:10:43.659 ThaliTest[428:674922] server: accepting invitation 1454415040155.2313
,2016-02-02 13:10:45.628 ThaliTest[428:675588] client session: connected
,2016-02-02 13:10:45.628 ThaliTest[428:675588] client session: stateChange:1->2 1454415040155.2313.JIJ5wg==
,2016-02-02 13:10:45.631 ThaliTest[428:675588] client session: fireConnectCallback: 1454415040155.2313.JIJ5wg==
2016-02-02 13:10:45.631 ThaliTest[428:675588] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-02 13:10:45.637 ThaliTest[428:674922] client: relay established
2016-02-02 13:10:45.637 ThaliTest[428:674922] client: new accepted socket: 0x17dbce50
,data in 8760

,data in 9855

,data in 18615

,data in 24090

,data in 38497

,data in 55845

,data in 59130

,data in 65700

,data in 80959

,data in 88695

,data in 98337

,data in 118260

,data in 131072

,ok 100 the test messages should be equal

,2016-02-02 13:10:46.112 ThaliTest[428:675186] jxcore: disconnect
,2016-02-02 13:10:46.113 ThaliTest[428:675186] client session: disconnectFromPeer: 1454415040155.2313.JIJ5wg==
,2016-02-02 13:10:46.113 ThaliTest[428:675186] client session: disconnect
,2016-02-02 13:10:46.114 ThaliTest[428:675186] client session: stateChange:2->0 1454415040155.2313.JIJ5wg==
,2016-02-02 13:10:46.125 ThaliTest[428:675186] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-02 13:10:46.344 ThaliTest[428:675684] server session: connected
,2016-02-02 13:10:46.344 ThaliTest[428:675684] server session: stateChange:1->2 1454415040155.2313
,2016-02-02 13:10:46.352 ThaliTest[428:674922] server relay: connected (to port: 51080)
,2016-02-02 13:10:47.641 ThaliTest[428:675598] server session: not connected 1454415040155.2313
,calling stopBroadcasting

,2016-02-02 13:10:47.982 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:47.983 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:47.983 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:47.985 ThaliTest[428:675186] server session: disconnect
2016-02-02 13:10:47.986 ThaliTest[428:675186] server session: stateChange:2->0 1454415040155.2313
,2016-02-02 13:10:47.992 ThaliTest[428:675186] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 51086

,2016-02-02 13:10:49.670 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:10:49.673 ThaliTest[428:675186] server: starting 1454415049669.428.6nTPEw==
,2016-02-02 13:10:49.674 ThaliTest[428:675186] multipeer session: start timer: 0x17bab770
2016-02-02 13:10:49.675 ThaliTest[428:675186] THEMultipeerSession initialized peer 1454415049669.428
2016-02-02 13:10:49.675 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 102 Should be able to call startBroadcasting without error

,2016-02-02 13:10:51.252 ThaliTest[428:674922] multipeer session: reset timer
2016-02-02 13:10:51.253 ThaliTest[428:674922] multipeer session: stop timer
2016-02-02 13:10:51.253 ThaliTest[428:674922] multipeer session: start timer: 0x17bab770
2016-02-02 13:10:51.253 ThaliTest[428:674922] server session: connect
,2016-02-02 13:10:51.254 ThaliTest[428:674922] server session: stateChange:0->1 1454415050043.2313
,2016-02-02 13:10:51.260 ThaliTest[428:674922] server: accepting invitation 1454415050043.2313
,2016-02-02 13:10:51.266 ThaliTest[428:674922] client: found peer: 1454415050043.2313.0cmmaw==
[{"peerIdentifier":"1454415050043.2313.0cmmaw==","peerName":"(null)","peerAvailable":true}]

2016-02-02 13:10:51.268 ThaliTest[428:675186] jxcore: connect 1454415050043.2313.0cmmaw==
2016-02-02 13:10:51.268 ThaliTest[428:675186] client session: connect
2016-02-02 13:10:51.269 ThaliTest[428:675186] client session: stateChange:0->1 1454415050043.2313.0cmmaw==
,2016-02-02 13:10:54.150 ThaliTest[428:675598] client session: connected
2016-02-02 13:10:54.150 ThaliTest[428:675598] client session: stateChange:1->2 1454415050043.2313.0cmmaw==
,2016-02-02 13:10:54.165 ThaliTest[428:675684] client session: fireConnectCallback: 1454415050043.2313.0cmmaw==
,2016-02-02 13:10:54.165 ThaliTest[428:675684] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-02 13:10:54.204 ThaliTest[428:674922] client: relay established
2016-02-02 13:10:54.204 ThaliTest[428:674922] client: new accepted socket: 0x17dbd550
,2016-02-02 13:10:54.408 ThaliTest[428:675598] server session: connected
2016-02-02 13:10:54.408 ThaliTest[428:675598] server session: stateChange:1->2 1454415050043.2313
,2016-02-02 13:10:54.461 ThaliTest[428:674922] server relay: connected (to port: 51086)
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-02 13:10:54.485 ThaliTest[428:674922] client: socket closed
,2016-02-02 13:10:54.486 ThaliTest[428:674922] client relay: socket disconnected
,2016-02-02 13:10:54.487 ThaliTest[428:674922] client relay: 0x17dbd550 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-02 13:10:54,.487 ThaliTest[428:674922] client session: socket closed: 1454415050043.2313.0cmmaw==
2016-02-02 13:10:54.487 ThaliTest[428:674922] client session: onLinkFailure: 1454415050043.2313.0cmmaw==
,2016-02-02 13:10:54.487 ThaliTest[428:674922] client session: disconnect
2016-02-02 13:10:54.488 ThaliTest[428:674922] client session: stateChange:2->0 1454415050043.2313.0cmmaw==
,2016-02-02 13:10:54.497 ThaliTest[428:674922] client session: fireConnectionErrorEvent: 1454415050043.2313.0cmmaw==
,2016-02-02 13:10:54.501 ThaliTest[428:675186] jxcore: connect 1454415050043.2313.0cmmaw==
2016-02-02 13:10:54.501 ThaliTest[428:675186] client session: connect
,2016-02-02 13:10:54.502 ThaliTest[428:675186] client session: stateChange:0->1 1454415050043.2313.0cmmaw==
,2016-02-02 13:10:54.599 ThaliTest[428:675598] server session: not connected 1454415050043.2313
,2016-02-02 13:10:54.924 ThaliTest[428:674922] multipeer session: reset timer
2016-02-02 13:10:54.925 ThaliTest[428:674922] multipeer session: stop timer
2016-02-02 13:10:54.925 ThaliTest[428:674922] multipeer session: start timer: 0x17bab770
2016-02-02 ,13:10:54.925 ThaliTest[428:674922] server: disconnecting to refresh session (1454415050043.2313)
2016-02-02 13:10:54.926 ThaliTest[428:674922] server session: disconnect
2016-02-02 13:10:54.926 ThaliTest[428:674922] server session: stateChange:2->0 1454415050043.2313
,2016-02-02 13:10:54.930 ThaliTest[428:674922] server session: connect
2016-02-02 13:10:54.930 ThaliTest[428:674922] server session: stateChange:0->1 1454415050043.2313
,2016-02-02 13:10:54.940 ThaliTest[428:674922] server: accepting invitation 1454415050043.2313
,2016-02-02 13:10:57.683 ThaliTest[428:675684] client session: connected
2016-02-02 13:10:57.683 ThaliTest[428:675684] client session: stateChange:1->2 1454415050043.2313.0cmmaw==
,2016-02-02 13:10:57.702 ThaliTest[428:675638] client session: fireConnectCallback: 1454415050043.2313.0cmmaw==
2016-02-02 13:10:57.703 ThaliTest[428:675638] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-02 13:10:57.739 ThaliTest[428:674922] client: relay established
2016-02-02 13:10:57.740 ThaliTest[428:674922] client: new accepted socket: 0x16f6d9a0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-02 13:10:57.840 ThaliTest[428:674922] client: socket closed
,2016-02-02 13:10:57.841 ThaliTest[428:674922] client relay: socket disconnected
,2016-02-02 13:10:57.841 ThaliTest[428:674922] client relay: 0x16f6d9a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-02 13:10:57.842 ThaliTest[428:674922] client session: socket closed: 1454415050043.2313.0cmmaw==
2016-02-02 13:10:57.842 ThaliTest[428:674922] client session: onLinkFailure: 1454415050043.2313.0cmmaw==
2016-02-02 13:10:57.842 ThaliTest[428:674922] client session: disconnect
,2016-02-02 13:10:57.843 ThaliTest[428:674922] client session: stateChange:2->0 1454415050043.2313.0cmmaw==
,2016-02-02 13:10:57.855 ThaliTest[428:674922] client session: fireConnectionErrorEvent: 1454415050043.2313.0cmmaw==
,2016-02-02 13:10:58.078 ThaliTest[428:675638] server session: connected
2016-02-02 13:10:58.079 ThaliTest[428:675638] server session: stateChange:1->2 1454415050043.2313
,2016-02-02 13:10:58.096 ThaliTest[428:674922] server relay: connected (to port: 51086)
,2016-02-02 13:10:58.265 ThaliTest[428:675757] server session: not connected 1454415050043.2313
,calling stopBroadcasting

,2016-02-02 13:10:59.512 ThaliTest[428:675186] jxcore: stopBroadcasting
,2016-02-02 13:10:59.513 ThaliTest[428:675186] THEMultipeerSession stopping peer
,2016-02-02 13:10:59.514 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:10:59.515 ThaliTest[428:675186] server session: disconnect
2016-02-02 13:10:59.515 ThaliTest[428:675186] server session: stateChange:2->0 1454415050043.2313
,2016-02-02 13:10:59.524 ThaliTest[428:675186] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/9AC8971C-4E59-46EA-B0C0-99FA29C757AD/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-02 13:11:00.796 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:11:00.798 ThaliTest[428:675186] server: starting DtRsu22HVgBakRtUz9QTCw.cT738g==
,2016-02-02 13:11:00.798 ThaliTest[428:675186] multipeer session: start timer: 0x14ff8e50
2016-02-02 13:11:00.798 ThaliTest[428:675186] THEMultipeerSession initialized peer DtRsu22HVgBakRtUz9QTCw
,2016-02-02 13:11:00.799 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

2016-02-02 13:11:00.800 ThaliTest[428:675186] jxcore: stopBroadcasting
2016-02-02 13:11:00.801 ThaliTest[428:675186] THEMultipeerSession stopping peer
2016-02-02 13:11:00.801 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:11:00.801 ThaliTest[428:675186] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/9AC8971C-4E59-46EA-B0C0-99FA29C757AD/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-02 13:11:01.211 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:11:01.215 ThaliTest[428:675186] server: starting DtRsu22HVgBakRtUz9QTCw.+IloFg==
,2016-02-02 13:11:01.215 ThaliTest[428:675186] multipeer session: start timer: 0x178cfd50
,2016-02-02 13:11:01.216 ThaliTest[428:675186] THEMultipeerSession initialized peer DtRsu22HVgBakRtUz9QTCw
2016-02-02 13:11:01.217 ThaliTest[428:675186] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-02-02 13:11:01.220 ThaliTest[428:675186] jxcore: stopBroadcasting
2016-02-02 13:11:01.221 ThaliTest[428:675186] THEMultipeerSession stopping peer
2016-02-02 13:11,:01.221 ThaliTest[428:675186] multipeer session: stop timer
2016-02-02 13:11:01.222 ThaliTest[428:675186] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/9AC8971C-4E59-46EA-B0C0-99FA29C757AD/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-02 13:11:03.965 ThaliTest[428:675186] jxcore: startBroadcasting
,2016-02-02 13:11:03.966 ThaliTest[428:675186] server: starting DtRsu22HVgBakRtUz9QTCw.gDbjyQ==
,2016-02-02 13:11:03.966 ThaliTest[428:675186] multipeer session: start timer: 0x14ed9010
2016-02-02 13:11:03.967 ThaliTest[428:675186] THEMultipeerSession initialized peer DtRsu22HVgBakRtUz9QTCw
2016-02-02 13:11:03.967 ThaliTest[428:675186] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

,ok 120 deviceName should not be null

,2016-02-02 13:11:07.199 ThaliTest[428:674922] client: found peer: JQ6i2aeI0mdeePtIc-qbjA.UblVHA==
,2016-02-02 13:11:08.044 ThaliTest[428:675186] jxcore: connect JQ6i2aeI0mdeePtIc-qbjA.UblVHA==
,2016-02-02 13:11:08.044 ThaliTest[428:675186] client session: connect
2016-02-02 13:11:08.044 ThaliTest[428:675186] client session: stateChange:0->1 JQ6i2aeI0mdeePtIc-qbjA.UblVHA==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-02 13:11:16.215 ThaliTest[428:674922] multipeer session: reset timer
2016-02-02 13:11:16.215 ThaliTest[428:674922] multipeer session: stop timer
,2016-02-02 13:11:16.215 ThaliTest[428:674922] multipeer session: start timer: 0x14ed9010
,2016-02-02 13:11:16.216 ThaliTest[428:674922] server session: connect
2016-02-02 13:11:16.216 ThaliTest[428:674922] server session: stateChange:0->1 JQ6i2aeI0mdeePtIc-qbjA
,2016-02-02 13:11:16.222 ThaliTest[428:674922] server: accepting invitation JQ6i2aeI0mdeePtIc-qbjA
,2016-02-02 13:11:19.035 ThaliTest[428:675684] client session: connected
2016-02-02 13:11:19.035 ThaliTest[428:675684] client session: stateChange:1->2 JQ6i2aeI0mdeePtIc-qbjA.UblVHA==
,2016-02-02 13:11:19.099 ThaliTest[428:675757] client session: fireConnectCallback: JQ6i2aeI0mdeePtIc-qbjA.UblVHA==
2016-02-02 13:11:19.100 ThaliTest[428:675757] jxcore: connect: success
,2016-02-02 13:11:19.112 ThaliTest[428:674922] client: relay established
2016-02-02 13:11:19.112 ThaliTest[428:674922] client: new accepted socket: 0x178d7490
,client bridge: new client socket

,client bridge: new client socket

,2016-02-02 13:11:19.239 ThaliTest[428:675814] server session: connected
2016-02-02 13:11:19.239 ThaliTest[428:675814] server session: stateChange:1->2 JQ6i2aeI0mdeePtIc-qbjA
,2016-02-02 13:11:19.297 ThaliTest[428:674922] server relay: connected (to port: 51101)
,server bridge: new client socket

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

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

client bridge: socket closed
,
,ok 123 1st change of remote doc should contain remote id

,client bridge: new client socket

,ok 124 Can update remote doc without error

null

,{ ok: true,
  id: '0d538615-0de9-4ca3-bce3-f3e2b7a9f6a6',
  rev: '2-ca11b1fbe24f146deadd179ae0dcb77a' }

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

,client bridge: socket closed

,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,client bridge: new client socket
,
,# setup

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-02 13:11:36.777 ThaliTest[428:675186] jxcore: stopBroadcasting
2016-02-02 13:11:36.778 ThaliTest[428:675186] THEMultipeerSession stopping peer
2016-02-02 13:11:36.778 ThaliTest[428:675186] multipeer session: stop timer
,2016-02-02 13:11:36.779 ThaliTest[428:675186] client session: disconnect
2016-02-02 13:11:36.779 ThaliTest[428:675186] client session: stateChange:2->0 JQ6i2aeI0mdeePtIc-qbjA.UblVHA==
,2016-02-02 13:11:36.794 ThaliTest[428:675811] server session: not connected JQ6i2aeI0mdeePtIc-qbjA
,2016-02-02 13:11:36.822 ThaliTest[428:675811] client session: not connected JQ6i2aeI0mdeePtIc-qbjA.UblVHA==
,2016-02-02 13:11:36.886 ThaliTest[428:675811] client session: onLinkFailure: JQ6i2aeI0mdeePtIc-qbjA.UblVHA==
Assertion failed: ([self connectionState] != THEPeerSessionStateNotConnected), function -[THEMultipeerClientSession onLinkFailure], file /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClientSession.m, line 124.
,* thread #1: tid = 0xa4c6a, 0x36abffbc libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x36abffbc libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x36abfdbc libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x2477c48c CoreFoundation`<redacted> + 136
    frame #3: 0x2477a812 CoreFoundation`<redacted> + 1050
    frame #4: 0x246cd0d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #5: 0x246ccecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #6: 0x2d874af8 GraphicsServices`GSEventRunModal + 160
    frame #7: 0x289562dc UIKit`UIApplicationMain + 144
    frame #8: 0x0005b1f2 ThaliTest`main + 50

```
