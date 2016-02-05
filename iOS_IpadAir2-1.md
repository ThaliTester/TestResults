#### Test 58497659c9ea290_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58497659c9ea290/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/6C2C9D00-BD9B-4E7B-B601-3E767558794A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6C2C9D00-BD9B-4E7B-B601-3E767558794A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58497659c9ea290/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58497659c9ea290/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51037"
,(lldb)     command script import "/tmp/6C2C9D00-BD9B-4E7B-B601-3E767558794A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-06 00:26:19.812 ThaliTest[752:1176906] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7EE98165-D957-4E29-B4AC-DADF6222EF20/Library/Cookies/Cookies.binarycookies
,2016-02-06 00:26:20.254 ThaliTest[752:1176906] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-06 00:26:20.255 ThaliTest[752:1176906] Multi-tasking -> Device: YES, App: YES
,2016-02-06 00:26:20.265 ThaliTest[752:1176906] Unlimited access to network resources
,2016-02-06 00:26:20.273 ThaliTest[752:1176906] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-06 00:26:29.935 ThaliTest[752:1176906] Resetting plugins due to page load.
,2016-02-06 00:26:33.814 ThaliTest[752:1176906] Finished load of: file:///var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app/www/index.html
,2016-02-06 00:26:33.969 ThaliTest[752:1176906] JXcore Cordova plugin initializing
,2016-02-06 00:26:33.969 ThaliTest[752:1177151] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0A86FF17-4F7B-4130-81FB-43C474AF3A1D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal

ok 2 should be equal

,ok 3 should be equal

,ok 4 should be equal

,# teardown

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,ok 5 should be equal

,ok 6 should be equal

ok 7 should be equal

,ok 8 should be equal

,# teardown

# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 9 should throw

# teardown

# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 10 should throw

# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 11 should be equal

# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 12 should throw

,# teardown

,# setup

# #parseBeacons addressBookCallback fails decrypt

,ok 13 should be equal

# teardown

,# setup

,# #parseBeacons addressBookCallback returns null for all

,ok 14 (unnamed assert)

,ok 15 should be equal

,# teardown

# setup

,# #parseBeacons addressBookCallback returns public key

,ok 16 (unnamed assert)

,ok 17 (unnamed assert)

,# teardown

,# setup

,# #parseBeacons with beacons both for and not for the user

,ok 18 (unnamed assert)

# teardown

,# setup

,# multiplex can send data

,ok 19 String should be length:200

,# teardown

,# setup

,# enqueue and run in order

,ok 20 firstPromise setTimeout

,ok 21 firstPromise result

,ok 22 firstPromise testValue

,ok 23 secondPromise setTimeout

,ok 24 secondPromise result

,ok 25 secondPromise testValue

,ok 26 thirdPromise in promise

,ok 27 thirdPromise result

,ok 28 thirdPromise testValue

,# teardown

,# setup

,# basic

,ok 29 sane

,# teardown

,# setup

,# another

,ok 30 sane

,# teardown

,# setup

,# successfully create a new pkcs12 file and return hash value

,ok 31 should be equal

,ok 32 null

,ok 33 (unnamed assert)

,ok 34 should be equal

,ok 35 should not throw

# teardown

,# setup

,# successfully read a previous pkcs12 file and return hash value

,ok 36 (unnamed assert)

,ok 37 (unnamed assert)

,ok 38 should not throw

,ok 39 should be equal

,ok 40 should be equal

,# teardown

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,ok 41 should be equal

,# teardown

,# setup

,# failed to get mobile documents path

,ok 42 should be equal

,# teardown

,# setup

,# #init should register the peerAvailabilityChanged event

,ok 43 should be equal

,ok 44 should be equal

,ok 45 should be equal

,# teardown

,# setup

,# #init should register the networkChanged event

,ok 46 should be equal

,# teardown

,# setup

,# #startBroadcasting should throw on null device name

,ok 47 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on empty string device name

,ok 48 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on non-number port

,ok 49 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on NaN port

,ok 50 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on negative port

,ok 51 should throw

,# teardown

,# setup

,# #startBroadcasting should throw on too large port

,ok 52 should throw

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,ok 53 should be equal

,ok 54 should be equal

,ok 55 should be equal

,# teardown

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ok 56 should be equal

,ok 57 should be equal

,ok 58 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ok 59 should be equal

,ok 60 should be equal

,# teardown

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ok 61 should be equal

,ok 62 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,ok 63 should be equal

,ok 64 should be equal

,ok 65 should be equal

,# teardown

,# setup

,# #connect should call Mobile("Connect") and handle an error

,ok 66 should be equal

,ok 67 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") without an error

,ok 68 should be equal

,ok 69 should be equal

,# teardown

,# setup

,# should call Mobile("Disconnect") and handle an error

,ok 70 should be equal

,ok 71 should be equal

,# teardown

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,2016-02-06 00:31:22.720 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:22.737 ThaliTest[752:1177151] server: starting 1454715082720.752.Lb+a4Q==
,2016-02-06 00:31:22.738 ThaliTest[752:1177151] multipeer session: start timer: 0x19b4a1e0
2016-02-06 00:31:22.739 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715082720.752
2016-02-06 00:31:22.740 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

2016-02-06 00:31:22.745 ThaliTest[752:1177151] jxcore: stopBroadcasting
2016-02-06 00:31:22.745 ThaliTest[752:1177151] THEMultipeerSession stopping peer
2016-02-06 00:31:22.746 ThaliTest[752,:1177151] multipeer session: stop timer
2016-02-06 00:31:22.746 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

2016-02-06 00:31:22.751 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:22.756 ThaliTest[752:1177151] server: starting 1454715082750.752.Mf1VuQ==
,2016-02-06 00:31:22.757 ThaliTest[752:1177151] multipeer session: start timer: 0x1a890b00
2016-02-06 00:31:22.758 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715082750.752
2016-02-06 00:31:22.759 ThaliTest[752:1177151] jxcore: startBr,oadcasting: success
ok 74 Should be able to call startBroadcasting without error

,2016-02-06 00:31:22.760 ThaliTest[752:1177151] jxcore: stopBroadcasting
2016-02-06 00:31:22.761 ThaliTest[752:1177151] THEMultipeerSession stopping peer
2016-02-06 00:31:22.762 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:22.762 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 75 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:22.767 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:22.772 ThaliTest[752:1177151] server: starting 1454715082766.752.5IEOJw==
2016-02-06 00:31:22.772 ThaliTest[752:1177151] multipeer session: start timer: 0x19ff4e80
2016-02-06 00:31:22.773 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715082766.752
2016-02-06 00:31:22.773 ThaliTest[752:1177151] jxcore: startBroadcasting: success
ok 76 Should be able to call startBroadcasting without error

2016-02-06 00:31:22.775 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:22.775 ThaliTest[752:1177151] THEMultipeerSession stopping peer
2016-02-06 00:31:22.777 ThaliTest[752:1177151] multipeer session: stop timer
2016-02-06 00:31:22.778 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
ok 77 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:22.781 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:22.788 ThaliTest[752:1177151] server: starting 1454715082779.752.ZF2y6Q==
2016-02-06 00:31:22.789 ThaliTest[752:1177151] multipeer session: start timer: 0x19ff4a40
2016-02-06 00:31:22.789 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715082779.752
,2016-02-06 00:31:22.790 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 78 Should be able to call startBroadcasting without error

2016-02-06 00:31:22.793 ThaliTest[752:1177151] jxcore: stopBroadcasting
2016-02-06 00:31:22.793 ThaliTest[752:1177151] THEMultipeerSession stopping peer
2016-02-06 00:31:22.793 ThaliTest[752:1177151] multipeer session: stop timer
2016-02-06 00:31:22.794 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:22.796 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:22.805 ThaliTest[752:1177151] server: starting 1454715082795.752.ZrAVPw==
,2016-02-06 00:31:22.807 ThaliTest[752:1177151] multipeer session: start timer: 0x17eaf070
2016-02-06 00:31:22.807 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715082795.752
2016-02-06 00:31:22.808 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error
,
,2016-02-06 00:31:22.814 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:22.814 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:22.816 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:22.817 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 81 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:22.823 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:22.827 ThaliTest[752:1177151] server: starting 1454715082823.752.UdMv3Q==
,2016-02-06 00:31:22.828 ThaliTest[752:1177151] multipeer session: start timer: 0x1ab538a0
,2016-02-06 00:31:22.830 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715082823.752
,2016-02-06 00:31:22.832 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 82 Should be able to call startBroadcasting without error

,2016-02-06 00:31:22.834 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:22.835 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:22.835 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:22.836 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 83 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:22.840 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:22.843 ThaliTest[752:1177151] server: starting 1454715082840.752.RGlp/w==
,2016-02-06 00:31:22.844 ThaliTest[752:1177151] multipeer session: start timer: 0x1ab53c10
,2016-02-06 00:31:22.846 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715082840.752
,2016-02-06 00:31:22.847 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 84 Should be able to call startBroadcasting without error

,2016-02-06 00:31:22.850 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:22.851 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:22.851 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:22.852 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:22.856 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:22.859 ThaliTest[752:1177151] server: starting 1454715082855.752.1KaDFA==
,2016-02-06 00:31:22.860 ThaliTest[752:1177151] multipeer session: start timer: 0x19ff65b0
,2016-02-06 00:31:22.862 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715082855.752
,2016-02-06 00:31:22.863 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 86 Should be able to call startBroadcasting without error

,2016-02-06 00:31:22.866 ThaliTest[752:1177151] jxcore: stopBroadcasting
2016-02-06 00:31:22.866 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:22.867 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:22.868 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 87 Should be able to call stopBroadcasting without error
,
,2016-02-06 00:31:22.872 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:22.874 ThaliTest[752:1177151] server: starting 1454715082871.752.5Z//pA==
,2016-02-06 00:31:22.875 ThaliTest[752:1177151] multipeer session: start timer: 0x1a8d22b0
,2016-02-06 00:31:22.877 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715082871.752
,2016-02-06 00:31:22.879 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error

,2016-02-06 00:31:22.881 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:22.882 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:22.882 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:22.884 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 89 Should be able to call stopBroadcasting without error

,2016-02-06 00:31:22.887 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:22.890 ThaliTest[752:1177151] server: starting 1454715082887.752.7Z4KhQ==
,2016-02-06 00:31:22.891 ThaliTest[752:1177151] multipeer session: start timer: 0x19d88150
,2016-02-06 00:31:22.893 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715082887.752
,2016-02-06 00:31:22.894 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 90 Should be able to call startBroadcasting without error

,2016-02-06 00:31:22.897 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:22.898 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:22.898 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:22.900 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,2016-02-06 00:31:23.038 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:23.042 ThaliTest[752:1177151] server: starting 1454715083038.752.1Cp8AA==
,2016-02-06 00:31:23.044 ThaliTest[752:1177151] multipeer session: start timer: 0x1a890a90
,2016-02-06 00:31:23.050 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715083038.752
,2016-02-06 00:31:23.051 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-06 00:31:23.055 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:23.055 ThaliTest[752:1177151] jxcore: startBroadcasting: failure
,ok 93 Cannot call startBroadcasting twice

,2016-02-06 00:31:23.061 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:23.061 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:23.062 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:23.065 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 94 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on connection to bad peer

,2016-02-06 00:31:23.130 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:23.134 ThaliTest[752:1177151] server: starting 1454715083130.752.TMyByg==
,2016-02-06 00:31:23.136 ThaliTest[752:1177151] multipeer session: start timer: 0x19d97860
,2016-02-06 00:31:23.138 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715083130.752
,2016-02-06 00:31:23.141 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 95 Should be able to call startBroadcasting without error

,2016-02-06 00:31:23.145 ThaliTest[752:1177151] jxcore: connect foobar
,2016-02-06 00:31:23.146 ThaliTest[752:1177151] client: unknown peer foobar
,2016-02-06 00:31:23.147 ThaliTest[752:1177151] jxcore: connect: fail: Unknown peer
,ok 96 Should not connect to a bad peer

,2016-02-06 00:31:23.154 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:23.154 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:23.155 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:23.158 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 97 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,2016-02-06 00:31:23.220 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:23.223 ThaliTest[752:1177151] server: starting 1454715083219.752.Ruyu/Q==
,2016-02-06 00:31:23.225 ThaliTest[752:1177151] multipeer session: start timer: 0x17eea710
,2016-02-06 00:31:23.230 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715083219.752
,2016-02-06 00:31:23.233 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 98 Should be able to call startBroadcasting without error

,2016-02-06 00:31:23.237 ThaliTest[752:1177151] jxcore: disconnect
,2016-02-06 00:31:23.237 ThaliTest[752:1177151] jxcore: disconnect: fail
,ok 99 Disconnect should fail to a non-existant peer 

,2016-02-06 00:31:23.243 ThaliTest[752:1177151] jxcore: stopBroadcasting
2016-02-06 00:31:23.244 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:23.244 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:23.247 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
,ok 100 Should be able to call stopBroadcasting without error

,# teardown

,# setup

,# ThaliEmitter can discover and connect to peers

,2016-02-06 00:31:24.283 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:24.287 ThaliTest[752:1177151] server: starting 1454715084283.752.r483fQ==
,2016-02-06 00:31:24.287 ThaliTest[752:1177151] multipeer session: start timer: 0x17eeba80
,2016-02-06 00:31:24.288 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715084283.752
2016-02-06 00:31:24.289 ThaliTest[752:1177151] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-06 00:31:25.497 ThaliTest[752:1176906] client: found peer: 1454715082799.1334.u7t0sQ==
,2016-02-06 00:31:25.500 ThaliTest[752:1177151] jxcore: connect 1454715082799.1334.u7t0sQ==
,2016-02-06 00:31:25.501 ThaliTest[752:1177151] client session: connect
2016-02-06 00:31:25.501 ThaliTest[752:1177151] client session: stateChange:0->1 1454715082799.1334.u7t0sQ==
,2016-02-06 00:31:26.061 ThaliTest[752:1176906] multipeer session: reset timer
,2016-02-06 00:31:26.062 ThaliTest[752:1176906] multipeer session: stop timer
2016-02-06 00:31:26.062 ThaliTest[752:1176906] multipeer session: start timer: 0x17eeba80
,2016-02-06 00:31:26.063 ThaliTest[752:1176906] server session: connect
,2016-02-06 00:31:26.063 ThaliTest[752:1176906] server session: stateChange:0->1 1454715082799.1334
,2016-02-06 00:31:26.070 ThaliTest[752:1176906] server: accepting invitation 1454715082799.1334
,2016-02-06 00:31:28.723 ThaliTest[752:1177672] client session: connected
,2016-02-06 00:31:28.723 ThaliTest[752:1177672] client session: stateChange:1->2 1454715082799.1334.u7t0sQ==
,2016-02-06 00:31:28.743 ThaliTest[752:1177673] client session: fireConnectCallback: 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:28.743 ThaliTest[752:1177673] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-06 00:31:28.748 ThaliTest[752:1177151] jxcore: disconnect
,2016-02-06 00:31:28.749 ThaliTest[752:1177151] client session: disconnectFromPeer: 1454715082799.1334.u7t0sQ==
,2016-02-06 00:31:28.749 ThaliTest[752:1177151] client session: disconnect
,2016-02-06 00:31:28.750 ThaliTest[752:1177151] client session: stateChange:2->0 1454715082799.1334.u7t0sQ==
,2016-02-06 00:31:28.760 ThaliTest[752:1177151] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-06 00:31:28.885 ThaliTest[752:1177670] server session: connected
,2016-02-06 00:31:28.885 ThaliTest[752:1177670] server session: stateChange:1->2 1454715082799.1334
,2016-02-06 00:31:28.903 ThaliTest[752:1176906] server relay: socket disconnected
,2016-02-06 00:31:28.904 ThaliTest[752:1176906] server relay: 0x19dd3960 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-06 00:31:28.937 ThaliTest[752:1177716] server session: not connected 1454715082799.1334
,calling stopBroadcasting

,2016-02-06 00:31:29.413 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:29.414 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:29.415 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:29.415 ThaliTest[752:1177151] server session: disconnect
2016-02-06 00:31:29.416 ThaliTest[752:1177151] server session: stateChange:2->0 1454715082799.1334
,2016-02-06 00:31:29.418 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,2016-02-06 00:31:29.475 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:29.479 ThaliTest[752:1177151] server: starting 1454715089475.752.R2vO/A==
,2016-02-06 00:31:29.480 ThaliTest[752:1177151] multipeer session: start timer: 0x19feb3a0
2016-02-06 00:31:29.480 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715089475.752
2016-02-06 00:31:29.481 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 105 Should be able to call startBroadcasting without error

,2016-02-06 00:31:29.491 ThaliTest[752:1176906] client: found peer: 1454715084283.752.r483fQ==
,2016-02-06 00:31:29.493 ThaliTest[752:1176906] client: found peer: 1454715082799.1334.u7t0sQ==
,2016-02-06 00:31:29.494 ThaliTest[752:1177151] jxcore: connect 1454715084283.752.r483fQ==
,2016-02-06 00:31:29.495 ThaliTest[752:1177151] client session: connect
,2016-02-06 00:31:29.495 ThaliTest[752:1177151] client session: stateChange:0->1 1454715084283.752.r483fQ==
,2016-02-06 00:31:29.567 ThaliTest[752:1177151] jxcore: connect 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:29.567 ThaliTest[752:1177151] client session: connect
,2016-02-06 00:31:29.567 ThaliTest[752:1177151] client session: stateChange:0->1 1454715082799.1334.u7t0sQ==
,2016-02-06 00:31:30.649 ThaliTest[752:1176906] client: lost peer: 1454715084283.752.r483fQ==
2016-02-06 00:31:30.650 ThaliTest[752:1176906] client session: onPeerLost: 1454715084283.752.r483fQ==
2016-02-06 00:31:30.650 ThaliTest[752:1176906] client sessi,on: onLinkFailure: 1454715084283.752.r483fQ==
2016-02-06 00:31:30.650 ThaliTest[752:1176906] client session: disconnect
2016-02-06 00:31:30.651 ThaliTest[752:1176906] client session: stateChange:1->0 1454715084283.752.r483fQ==
2016-02-06 00:31:30.651 Th,aliTest[752:1176906] client session: fireConnectCallback: 1454715084283.752.r483fQ==
2016-02-06 00:31:30.652 ThaliTest[752:1176906] jxcore: connect: fail: Peer disconnected
,2016-02-06 00:31:30.652 ThaliTest[752:1176906] client: found peer: 1454715087678.1334.N89O0g==
,2016-02-06 00:31:30.656 ThaliTest[752:1177151] jxcore: connect 1454715087678.1334.N89O0g==
,2016-02-06 00:31:30.656 ThaliTest[752:1177151] client session: connect
,2016-02-06 00:31:30.657 ThaliTest[752:1177151] client session: stateChange:0->1 1454715087678.1334.N89O0g==
,2016-02-06 00:31:30.881 ThaliTest[752:1176906] multipeer session: reset timer
2016-02-06 00:31:30.881 ThaliTest[752:1176906] multipeer session: stop timer
,2016-02-06 00:31:30.881 ThaliTest[752:1176906] multipeer session: start timer: 0x19feb3a0
2016-02-06 00:31:30.882 ThaliTest[752:1176906] server session: connect
,2016-02-06 00:31:30.882 ThaliTest[752:1176906] server session: stateChange:0->1 1454715087678.1334
,2016-02-06 00:31:30.890 ThaliTest[752:1176906] server: accepting invitation 1454715087678.1334
,2016-02-06 00:31:31.664 ThaliTest[752:1177151] jxcore: connect 1454715084283.752.r483fQ==
,2016-02-06 00:31:31.665 ThaliTest[752:1177151] client: connect: unreachable 1454715084283.752.r483fQ==
,2016-02-06 00:31:31.665 ThaliTest[752:1177151] jxcore: connect: fail: Peer unreachable
,2016-02-06 00:31:33.558 ThaliTest[752:1177673] client session: connected
2016-02-06 00:31:33.559 ThaliTest[752:1177673] client session: stateChange:1->2 1454715087678.1334.N89O0g==
,2016-02-06 00:31:33.590 ThaliTest[752:1177668] client session: fireConnectCallback: 1454715087678.1334.N89O0g==
2016-02-06 00:31:33.590 ThaliTest[752:1177668] jxcore: connect: success
,ok 106 Should be able to connect without error

,ok 107 Port should be within range

,2016-02-06 00:31:33.595 ThaliTest[752:1177151] jxcore: connect 1454715087678.1334.N89O0g==
,2016-02-06 00:31:33.595 ThaliTest[752:1177151] client: already connect(ing/ed) to 1454715087678.1334.N89O0g==
,2016-02-06 00:31:33.596 ThaliTest[752:1177151] jxcore: connect: fail: Aleady connecting
,ok 108 Should fail on double connect

,2016-02-06 00:31:33.600 ThaliTest[752:1177151] jxcore: disconnect
,2016-02-06 00:31:33.600 ThaliTest[752:1177151] client session: disconnectFromPeer: 1454715087678.1334.N89O0g==
,2016-02-06 00:31:33.601 ThaliTest[752:1177151] client session: disconnect
,2016-02-06 00:31:33.601 ThaliTest[752:1177151] client session: stateChange:2->0 1454715087678.1334.N89O0g==
,2016-02-06 00:31:33.609 ThaliTest[752:1177151] jxcore: disconnect: success
ok 109 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-06 00:31:33.734 ThaliTest[752:1177668] server session: connected
,2016-02-06 00:31:33.734 ThaliTest[752:1177668] server session: stateChange:1->2 1454715087678.1334
,2016-02-06 00:31:33.771 ThaliTest[752:1176906] server relay: socket disconnected
2016-02-06 00:31:33.771 ThaliTest[752:1176906] server relay: 0x19ba9180 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-06 00:31:33.814 ThaliTest[752:1177716] server session: not connected 1454715087678.1334
,calling stopBroadcasting

,2016-02-06 00:31:34.186 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:34.187 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:34.187 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:34.188 ThaliTest[752:1177151] client session: disconnect
2016-02-06 00:31:34.188 ThaliTest[752:1177151] client session: stateChange:1->0 1454715082799.1334.u7t0sQ==
2016-02-06 00:31:34.189 ThaliTest[752:1177151] server session: disconnect
2016-02-06 00:31:34.190 ThaliTest[752:1177151] server session: stateChange:2->0 1454715087678.1334
,2016-02-06 00:31:34.193 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,2016-02-06 00:31:36.831 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:36.834 ThaliTest[752:1177151] server: starting 1454715096831.752.tQr+lw==
,2016-02-06 00:31:36.835 ThaliTest[752:1177151] multipeer session: start timer: 0x1aec7e30
,2016-02-06 00:31:36.836 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715096831.752
,2016-02-06 00:31:36.837 ThaliTest[752:1177151] jxcore: startBroadcasting: success
ok 110 Should be able to call startBroadcasting without error

,2016-02-06 00:31:37.724 ThaliTest[752:1176906] client: found peer: 1454715087678.1334.N89O0g==
,2016-02-06 00:31:37.726 ThaliTest[752:1177151] jxcore: connect 1454715087678.1334.N89O0g==
2016-02-06 00:31:37.726 ThaliTest[752:1177151] client session: connect
2016-02-06 00:31:37.727 ThaliTest[752:1177151] client session: stateChange:0->1 1454715087678.1334.N89O0g==
,2016-02-06 00:31:37.915 ThaliTest[752:1176906] client: found peer: 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:37.917 ThaliTest[752:1177151] jxcore: connect 1454715095046.1334.PB48UQ==
2016-02-06 00:31:37.917 ThaliTest[752:1177151] client session: connect
,2016-02-06 00:31:37.917 ThaliTest[752:1177151] client session: stateChange:0->1 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:38.508 ThaliTest[752:1176906] multipeer session: reset timer
2016-02-06 00:31:38.509 ThaliTest[752:1176906] multipeer session: stop timer
2016-02-06 00:31:38.509 ThaliTest[752:1176906] multipeer session: start timer: 0x1aec7e30
2016-02-,06 00:31:38.509 ThaliTest[752:1176906] server session: connect
2016-02-06 00:31:38.510 ThaliTest[752:1176906] server session: stateChange:0->1 1454715095046.1334
,2016-02-06 00:31:38.517 ThaliTest[752:1176906] server: accepting invitation 1454715095046.1334
,2016-02-06 00:31:42.956 ThaliTest[752:1177668] client session: connected
2016-02-06 00:31:42.957 ThaliTest[752:1177668] client session: stateChange:1->2 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:43.082 ThaliTest[752:1177673] client session: fireConnectCallback: 1454715095046.1334.PB48UQ==
2016-02-06 00:31:43.083 ThaliTest[752:1177673] jxcore: connect: success
,ok 111 Should be able to connect without error

,ok 112 Port should be within range

,2016-02-06 00:31:43.087 ThaliTest[752:1177151] jxcore: disconnect
,2016-02-06 00:31:43.088 ThaliTest[752:1177151] client session: disconnectFromPeer: 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:43.088 ThaliTest[752:1177151] client session: disconnect
,2016-02-06 00:31:43.089 ThaliTest[752:1177151] client session: stateChange:2->0 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:43.121 ThaliTest[752:1177670] server session: connected
2016-02-06 00:31:43.121 ThaliTest[752:1177670] server session: stateChange:1->2 1454715095046.1334
,2016-02-06 00:31:43.164 ThaliTest[752:1177151] jxcore: disconnect: success
,ok 113 Should be able to disconnect without error

,2016-02-06 00:31:43.167 ThaliTest[752:1177151] jxcore: disconnect
,2016-02-06 00:31:43.167 ThaliTest[752:1177151] jxcore: disconnect: fail
,ok 114 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# teardown

,2016-02-06 00:31:43.204 ThaliTest[752:1176906] server relay: socket disconnected
2016-02-06 00:31:43.204 ThaliTest[752:1176906] server relay: 0x1aec2990 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting

,2016-02-06 00:31:43.371 ThaliTest[752:1177151] jxcore: stopBroadcasting
,2016-02-06 00:31:43.371 ThaliTest[752:1177151] THEMultipeerSession stopping peer
,2016-02-06 00:31:43.372 ThaliTest[752:1177151] multipeer session: stop timer
,2016-02-06 00:31:43.374 ThaliTest[752:1177151] client session: disconnect
2016-02-06 00:31:43.374 ThaliTest[752:1177151] client session: stateChange:1->0 1454715087678.1334.N89O0g==
,2016-02-06 00:31:43.380 ThaliTest[752:1177151] server session: disconnect
,2016-02-06 00:31:43.390 ThaliTest[752:1177151] server session: stateChange:2->0 1454715095046.1334
,2016-02-06 00:31:43.467 ThaliTest[752:1177151] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# setup

,# ThaliEmitter can connect and send data

,echo server started on port: 53962

,2016-02-06 00:31:44.051 ThaliTest[752:1177151] jxcore: startBroadcasting
,2016-02-06 00:31:44.052 ThaliTest[752:1177151] server: starting 1454715104051.752.L2fN6A==
,2016-02-06 00:31:44.053 ThaliTest[752:1177151] multipeer session: start timer: 0x1aca3470
2016-02-06 00:31:44.053 ThaliTest[752:1177151] THEMultipeerSession initialized peer 1454715104051.752
2016-02-06 00:31:44.053 ThaliTest[752:1177151] jxcore: startBroadcasting: success
,ok 115 Should be able to call startBroadcasting without error

,2016-02-06 00:31:44.685 ThaliTest[752:1176906] client: found peer: 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:44.687 ThaliTest[752:1177151] jxcore: connect 1454715095046.1334.PB48UQ==
2016-02-06 00:31:44.687 ThaliTest[752:1177151] client session: connect
2016-02-06 00:31:44.688 ThaliTest[752:1177151] client session: stateChange:0->1 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:45.323 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:31:45.324 ThaliTest[752:1177151] jxcore: connect 1454715102291.1334.yAxPyA==
2016-02-06 00:31:45.325 ThaliTest[752:1177151] client session: connect
2016-02-06 00:31:45.325 ThaliTest[752:1177151] client session: stateChange:0->1 1454715102291.1334.yAxPyA==
,2016-02-06 00:31:45.742 ThaliTest[752:1176906] multipeer session: reset timer
2016-02-06 00:31:45.742 ThaliTest[752:1176906] multipeer session: stop timer
2016-02-06 00:31:45.743 ThaliTest[752:1176906] multipeer session: start timer: 0x1aca3470
,2016-02-06 00:31:45.743 ThaliTest[752:1176906] server session: connect
,2016-02-06 00:31:45.744 ThaliTest[752:1176906] server session: stateChange:0->1 1454715102291.1334
,2016-02-06 00:31:45.750 ThaliTest[752:1176906] server: accepting invitation 1454715102291.1334
,2016-02-06 00:31:51.501 ThaliTest[752:1177670] client session: connected
2016-02-06 00:31:51.501 ThaliTest[752:1177670] client session: stateChange:1->2 1454715102291.1334.yAxPyA==
,2016-02-06 00:31:51.766 ThaliTest[752:1177668] server session: connected
2016-02-06 00:31:51.766 ThaliTest[752:1177668] server session: stateChange:1->2 1454715102291.1334
,2016-02-06 00:31:51.791 ThaliTest[752:1177668] client session: fireConnectCallback: 1454715102291.1334.yAxPyA==
2016-02-06 00:31:51.792 ThaliTest[752:1177668] jxcore: connect: success
,ok 116 Should be able to connect without error

,ok 117 Port should be within range

,2016-02-06 00:31:51.802 ThaliTest[752:1176906] client: lost peer: 1454715095046.1334.PB48UQ==
2016-02-06 00:31:51.803 ThaliTest[752:1176906] client session: onPeerLost: 1454715095046.1334.PB48UQ==
2016-02-06 00:31:51.803 ThaliTest[752:1176906] client session: onLinkFailure: 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:51.803 ThaliTest[752:1176906] client session: disconnect
2016-02-06 00:31:51.805 ThaliTest[752:1176906] client session: stateChange:1->0 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:51.811 ThaliTest[752:1176906] client session: fireConnectCallback: 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:51.812 ThaliTest[752:1176906] jxcore: connect: fail: Peer disconnected
,2016-02-06 00:31:51.813 ThaliTest[752:1176906] client: relay established
2016-02-06 00:31:51.813 ThaliTest[752:1176906] client: new accepted socket: 0x17ef05e0
,2016-02-06 00:31:51.814 ThaliTest[752:1176906] server relay: connected (to port: 53962)
,2016-02-06 00:31:52.845 ThaliTest[752:1177151] jxcore: connect 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:52.846 ThaliTest[752:1177151] client: connect: unreachable 1454715095046.1334.PB48UQ==
,2016-02-06 00:31:52.846 ThaliTest[752:1177151] jxcore: connect: fail: Peer unreachable
,2016-02-06 00:32:02.897 ThaliTest[752:1177877] client session: not connected 1454715102291.1334.yAxPyA==
2016-02-06 00:32:02.898 ThaliTest[752:1177877] client session: onLinkFailure: 1454715102291.1334.yAxPyA==
2016-02-06 00:32:02.898 ThaliTest[752:11778,77] client session: disconnect
2016-02-06 00:32:02.898 ThaliTest[752:1177877] client session: stateChange:2->0 1454715102291.1334.yAxPyA==
,2016-02-06 00:32:02.902 ThaliTest[752:1177877] client session: fireConnectionErrorEvent: 1454715102291.1334.yAxPyA==
,2016-02-06 00:32:15.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:32:15.768 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:32:19.903 ThaliTest[752:1177668] server session: not connected 1454715102291.1334
,2016-02-06 00:32:45.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:32:45.771 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:33:15.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:33:15.768 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:33:45.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:33:45.767 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:34:15.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:34:15.771 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:34:45.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:34:45.769 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:35:15.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:35:15.771 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:35:45.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:35:45.769 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:36:15.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:36:15.768 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:36:45.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:37:15.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:37:15.764 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:37:45.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:37:45.764 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:38:15.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:38:15.765 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:38:45.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:38:45.765 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:39:15.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:39:15.766 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:39:45.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:39:45.762 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:40:15.743 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:40:15.764 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:40:45.744 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:40:45.763 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:41:11.849 ThaliTest[752:1176906] multipeer session: reset timer
2016-02-06 00:41:11.850 ThaliTest[752:1176906] multipeer session: stop timer
2016-02-06 00:41:11.850 ThaliTest[752:1176906] multipeer session: start timer: 0x1aca3470
2016-02-06 00:41:11.850 ThaliTest[752:1176906] server: disconnecting to refresh session (1454715102291.1334)
2016-02-06 00:41:11.850 ThaliTest[752:1176906] server session: disconnect
,2016-02-06 00:41:11.851 ThaliTest[752:1176906] server session: stateChange:2->0 1454715102291.1334
,2016-02-06 00:41:11.854 ThaliTest[752:1176906] server session: connect
,2016-02-06 00:41:11.855 ThaliTest[752:1176906] server session: stateChange:0->1 1454715102291.1334
,2016-02-06 00:41:11.862 ThaliTest[752:1176906] server: accepting invitation 1454715102291.1334
,2016-02-06 00:41:13.648 ThaliTest[752:1179129] server session: connected
,2016-02-06 00:41:13.648 ThaliTest[752:1179129] server session: stateChange:1->2 1454715102291.1334
,2016-02-06 00:41:13.760 ThaliTest[752:1176906] server relay: connected (to port: 53962)
,2016-02-06 00:41:41.851 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:41:41.874 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:41:48.599 ThaliTest[752:1179176] server session: not connected 1454715102291.1334
,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,2016-02-06 00:42:11.851 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:42:11.873 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:42:41.851 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:42:41.873 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:43:11.851 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:43:11.871 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==
,2016-02-06 00:43:41.851 ThaliTest[752:1176906] multipeer session: restart
,2016-02-06 00:43:41.874 ThaliTest[752:1176906] client: found peer: 1454715102291.1334.yAxPyA==

```
