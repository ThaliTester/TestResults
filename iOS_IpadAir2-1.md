#### Test 564317025f150b2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/564317025f150b2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B6E20428-58A0-4577-A536-D4368526A8F6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B6E20428-58A0-4577-A536-D4368526A8F6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/564317025f150b2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/564317025f150b2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5148BA85-7CDA-4DE8-8392-670880ED9B37/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58373"
,(lldb)     command script import "/tmp/B6E20428-58A0-4577-A536-D4368526A8F6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-19 09:04:03.351 ThaliTest[2335:5021955] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F07574F4-EEBA-4649-9222-716724458B78/Library/Cookies/Cookies.binarycookies
,2016-01-19 09:04:03.589 ThaliTest[2335:5021955] Apache Cordova native platform version 3.9.2 is starting.
2016-01-19 09:04:03.589 ThaliTest[2335:5021955] Multi-tasking -> Device: YES, App: YES
,2016-01-19 09:04:03.596 ThaliTest[2335:5021955] Unlimited access to network resources
,2016-01-19 09:04:03.601 ThaliTest[2335:5021955] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-19 09:04:07.632 ThaliTest[2335:5021955] Resetting plugins due to page load.
,2016-01-19 09:04:09.059 ThaliTest[2335:5021955] Finished load of: file:///var/mobile/Containers/Bundle/Application/5148BA85-7CDA-4DE8-8392-670880ED9B37/ThaliTest.app/www/index.html
,2016-01-19 09:04:09.193 ThaliTest[2335:5021955] JXcore Cordova plugin initializing
,2016-01-19 09:04:09.194 ThaliTest[2335:5022134] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5148BA85-7CDA-4DE8-8392-670880ED9B37/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5148BA85-7CDA-4DE8-8392-670880ED9B37/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5148BA85-7CDA-4DE8-8392-670880ED9B37/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5148BA85-7CDA-4DE8-8392-670880ED9B37/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5148BA85-7CDA-4DE8-8392-670880ED9B37/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5148BA85-7CDA-4DE8-8392-670880ED9B37/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5148BA85-7CDA-4DE8-8392-670880ED9B37/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
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
,# setup
,# another
,# teardown
,ok 3 sane
,# setup
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
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,ok 26 should be equal
ok 27 should be equal
,ok 28 should be equal
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
,ok 30 should be equal
,ok 31 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,ok 32 should be equal
ok 33 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
ok 35 should be equal
,# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
,ok 37 should be equal
,ok 38 should be equal
,# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
,ok 40 should be equal
,# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
,ok 42 should be equal
,# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-19 09:09:28.022 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:28.028 ThaliTest[2335:5022134] server: starting 1453190968022.2335.ZatYOA==
,2016-01-19 09:09:28.028 ThaliTest[2335:5022134] multipeer session: start timer: 0x17f98780
2016-01-19 09:09:28.028 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190968022.2335
2016-01-19 09:09:28.029 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-19 09:09:28.029 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.030 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:28.030 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:28.030 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
,2016-01-19 09:09:28.031 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:28.034 ThaliTest[2335:5022134] server: starting 1453190968031.2335.yfiLOw==
2016-01-19 09:09:28.034 ThaliTest[2335:5022134] multipeer session: start timer: 0x1b261b10
2016-01-19 09:09:28.034 ThaliTest[2335:5022134] THEMultipeerSession in,itialized peer 1453190968031.2335
2016-01-19 09:09:28.035 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-19 09:09:28.036 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.036 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
,2016-01-19 09:09:28.036 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:28.037 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-19 09:09:28.038 ThaliTest[2335:5022134] jxcore: startBroadcasting
2016-01-19 09:09:28.039 ThaliTest[2335:5022134] server: starting 1453190968038.2335.3hpeWA==
2016-01-19 09:09:28.039 ThaliTest[2335:5022134] multipeer session: start timer: 0x17f97fa0
,2016-01-19 09:09:28.039 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190968038.2335
2016-01-19 09:09:28.040 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-19 09:09:28.041 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.041 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:28.041 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:28.041 T,haliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-19 09:09:28.041 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:28.043 ThaliTest[2335:5022134] server: starting 1453190968041.2335.zKrm6w==
2016-01-19 09:09:28.044 ThaliTest[2335:5022134] multipeer session: start timer: 0x17f99b30
2016-01-19 09:09:28.044 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190968041.2335
,2016-01-19 09:09:28.044 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-19 09:09:28.046 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.046 ThaliTest[23,35:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:28.046 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:28.046 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-19 09:09:28.046 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:28.048 ThaliTest[2335:5022134] server: starting 1453190968046.2335.L6KmmQ==
,2016-01-19 09:09:28.050 ThaliTest[2335:5022134] multipeer session: start timer: 0x17f8e530
,2016-01-19 09:09:28.050 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190968046.2335
2016-01-19 09:09:28.053 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-,01-19 09:09:28.054 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.055 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
,2016-01-19 09:09:28.055 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:28.055 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
2016-01-19 09:09:28.056 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:28.057 ThaliTest[2335:5022134] server: starting 1453190968056.2335.7JW8oQ==
2016-01-19 09:09:28.058 ThaliTest[2335:5022134] multipeer session: start timer: 0x1b263380
2016-01-19 09:09:28.058 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190968056.2335
2016-01-19 09:09:28.058 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-19 09:09:28.059 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.059 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:28.059 ThaliTest[2335:5022134] multipeer session: stop timer
,2016-01-19 09:09:28.061 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
2016-01-19 09:09:28.061 ThaliTest[2335:5022134] jxcore: startBroadcasting
2016-01-19 09:09:28.062 ThaliTest[233,5:5022134] server: starting 1453190968061.2335.SYmiRQ==
2016-01-19 09:09:28.062 ThaliTest[2335:5022134] multipeer session: start timer: 0x17f942a0
2016-01-19 09:09:28.063 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190968061.2335
2016-01-19 09:09:28.063 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2016-01-19 09:09:28.063 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.063 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:28.063 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:28.064 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting wit,hout error
2016-01-19 09:09:28.065 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:28.068 ThaliTest[2335:5022134] server: starting 1453190968065.2335.t3BOgQ==
2016-01-19 09:09:28.068 ThaliTest[2335:5022134] multipeer session: start timer: 0x17f8dfe0
2016-01-19 09:09:28.068 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190968065.2335
2016-01-19 09:09:28.068 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
2016-01-19 09:09:28.069 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2,016-01-19 09:09:28.069 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:28.070 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:28.070 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2016-01-19 09:09:28.070 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:28.072 ThaliTest[2335:5022134] server: starting 1453190968070.2335.oTbopg==
2016-01-19 09:09:28.072 ThaliTest[2335:5022134] multipeer session: start timer: 0x19b8d920
2016-01-19 09:09:28.072 ThaliTest[2335:5022134] THEMultipeerSession in,itialized peer 1453190968070.2335
2016-01-19 09:09:28.072 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2016-01-19 09:09:28.073 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.073 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:28.074 ThaliTest[2335:5022134] multipeer session: stop timer
,2016-01-19 09:09:28.074 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 62 Should be able to call stopBroadcasting without error
,2016-01-19 09:09:28.076 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:28.078 ThaliTest[2335:5022134] server: starting 1453190968076.2335.Sdv+mQ==
,2016-01-19 09:09:28.080 ThaliTest[2335:5022134] multipeer session: start timer: 0x1b257e20
2016-01-19 09:09:28.080 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190968076.2335
2016-01-19 09:09:28.080 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
,2016-01-19 09:09:28.081 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.081 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:28.081 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:28.,081 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-19 09:09:28.392 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:28.393 ThaliTest[2335:5022134] server: starting 1453190968392.2335.d/gxZw==
2016-01-19 09:09:28.393 ThaliTest[2335:5022134] multipeer session: start timer: 0x1b25d840
2016-01-19 09:09:28.394 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190968392.2335
2016-01-19 09:09:28.394 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-19 09:09:28.394 ThaliTest[2335:5022134] jxcore: startBroadcasting
2016-01-19 09:09:28.395 ThaliTest[2335:5022134] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2016-01-19 09:09:28.395 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.396 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:28.396 ThaliTest[2335:5022134] multipee,r session: stop timer
2016-01-19 09:09:28.396 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-19 09:09:28.823 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:28.825 ThaliTest[2335:5022134] server: starting 1453190968823.2335.llEjWg==
2016-01-19 09:09:28.825 ThaliTest[2335:5022134] multipeer session: start timer: 0x1b258cf0
2016-01-19 09:09:28.825 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190968823.2335
2016-01-19 09:09:28.825 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
,2016-01-19 09:09:28.826 ThaliTest[2335:5022134] jxcore: connect foobar
2016-01-19 09:09:28.826 ThaliTest[2335:5022134] client: unknown peer foobar
2016-01-19 09:09:28.826 ThaliTest[2335:5022134] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2016-01-19 09:09:28.827 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:28.827 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:28.827 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:28.827 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-19 09:09:29.925 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:29.926 ThaliTest[2335:5022134] server: starting 1453190969924.2335.Ghi4ng==
2016-01-19 09:09:29.926 ThaliTest[2335:5022134] multipeer session: start timer: 0x1b259720
2016-01-19 09:09:29.926 ThaliTest[2335:5022134] THEMultipeerSession in,itialized peer 1453190969924.2335
2016-01-19 09:09:29.926 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
,2016-01-19 09:09:29.927 ThaliTest[2335:5022134] jxcore: disconnect
2016-01-19 09:09:29.927 ThaliTest[2335:5022134] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2016-01-19 09:09:29.928 ThaliTest[2335:5022134] jxcore: stop,Broadcasting
2016-01-19 09:09:29.928 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:29.928 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:29.928 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-19 09:09:30.021 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:30.023 ThaliTest[2335:5022134] server: starting 1453190970021.2335.ofaeGQ==
2016-01-19 09:09:30.023 ThaliTest[2335:5022134] multipeer session: start timer: 0x19b87bc0
2016-01-19 09:09:30.023 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190970021.2335
2016-01-19 09:09:30.023 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2016-01-19 09:09:31.282 ThaliTest[2335:5021955] client: found peer: 1453190967268.1630.W1YW5w==
,2016-01-19 09:09:31.283 ThaliTest[2335:5022134] jxcore: connect 1453190967268.1630.W1YW5w==
2016-01-19 09:09:31.283 ThaliTest[2335:5022134] client session: connect
2016-01-19 09:09:31.283 ThaliTest[2335:5022134] client session: stateChange:0->1 1453190967268.1630.W1YW5w==
,2016-01-19 09:09:32.315 ThaliTest[2335:5021955] multipeer session: reset timer
2016-01-19 09:09:32.315 ThaliTest[2335:5021955] multipeer session: stop timer
2016-01-19 09:09:32.315 ThaliTest[2335:5021955] multipeer session: start timer: 0x19b87bc0
2016-01-19 09:09:32.315 ThaliTest[2335:5021955] server session: connect
2016-01-19 09:09:32.315 ThaliTest[2335:5021955] server session: stateChange:0->1 1453190967268.1630
,2016-01-19 09:09:32.318 ThaliTest[2335:5021955] server: accepting invitation 1453190967268.1630
,2016-01-19 09:09:36.470 ThaliTest[2335:5023884] server session: connected
2016-01-19 09:09:36.470 ThaliTest[2335:5023884] server session: stateChange:1->2 1453190967268.1630
,2016-01-19 09:09:36.516 ThaliTest[2335:5021955] server relay: socket disconnected
2016-01-19 09:09:36.516 ThaliTest[2335:5021955] server relay: 0x1b253d30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 09:09:36.522 ThaliTest[2335:5023872] client session: connected
,2016-01-19 09:09:36.522 ThaliTest[2335:5023872] client session: stateChange:1->2 1453190967268.1630.W1YW5w==
,2016-01-19 09:09:36.528 ThaliTest[2335:5023884] client session: fireConnectCallback: 1453190967268.1630.W1YW5w==
,2016-01-19 09:09:36.529 ThaliTest[2335:5023884] jxcore: connect: success
,ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-19 09:09:36.530 ThaliTest[2335:5022134] jxcore: disconnect
,2016-01-19 09:09:36.530 ThaliTest[2335:5022134] client session: disconnectFromPeer: 1453190967268.1630.W1YW5w==
,2016-01-19 09:09:36.530 ThaliTest[2335:5022134] client session: disconnect
2016-01-19 09:09:36.530 ThaliTest[2335:5022134] client session: stateChange:2->0 1453190967268.1630.W1YW5w==
,2016-01-19 09:09:36.534 ThaliTest[2335:5022134] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-19 09:09:36.567 ThaliTest[2335:5023888] server session: not connected 1453190967268.1630
,calling stopBroadcasting
,2016-01-19 09:09:37.343 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:37.343 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:37.343 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:37.343 ThaliTest[2335:5022134] server session: disconnect
2016-01-19 09:09:37.343 ThaliTest[2335:5022134] server session: stateChange:2->0 1453190967268.1630
,2016-01-19 09:09:37.345 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-19 09:09:37.873 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:37.874 ThaliTest[2335:5022134] server: starting 1453190977873.2335.tKKIAA==
2016-01-19 09:09:37.874 ThaliTest[2335:5022134] multipeer session: start timer: 0x19b78190
2016-01-19 09:09:37.874 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190977873.2335
2016-01-19 09:09:37.874 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-19 09:09:39.085 ThaliTest[2335:5021955] client: found peer: 1453190975133.1630.HOv04Q==
,2016-01-19 09:09:39.086 ThaliTest[2335:5022134] jxcore: connect 1453190975133.1630.HOv04Q==
2016-01-19 09:09:39.086 ThaliTest[2335:5022134] client session: connect
2016-01-19 09:09:39.086 ThaliTest[2335:5022134] client session: stateChange:0->1 1453190975133.1630.HOv04Q==
,2016-01-19 09:09:39.268 ThaliTest[2335:5021955] multipeer session: reset timer
2016-01-19 09:09:39.268 ThaliTest[2335:5021955] multipeer session: stop timer
2016-01-19 09:09:39.268 ThaliTest[2335:5021955] multipeer session: start timer: 0x19b78190
2016-,01-19 09:09:39.268 ThaliTest[2335:5021955] server session: connect
2016-01-19 09:09:39.268 ThaliTest[2335:5021955] server session: stateChange:0->1 1453190975133.1630
,2016-01-19 09:09:39.270 ThaliTest[2335:5021955] server: accepting invitation 1453190975133.1630
,2016-01-19 09:09:43.343 ThaliTest[2335:5023872] client session: connected
2016-01-19 09:09:43.344 ThaliTest[2335:5023872] client session: stateChange:1->2 1453190975133.1630.HOv04Q==
,2016-01-19 09:09:43.394 ThaliTest[2335:5023884] client session: fireConnectCallback: 1453190975133.1630.HOv04Q==
2016-01-19 09:09:43.394 ThaliTest[2335:5023884] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be ,within range
,2016-01-19 09:09:43.396 ThaliTest[2335:5022134] jxcore: connect 1453190975133.1630.HOv04Q==
2016-01-19 09:09:43.396 ThaliTest[2335:5022134] client: already connect(ing/ed) to 1453190975133.1630.HOv04Q==
2016-01-19 09:09:43.396 ThaliTest[2335:5022134] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-19 09:09:43.397 ThaliTest[2335:5022134] jxcore: disconnect
2016-01-19 09:09:43.397 ThaliTest[2335:5022134] client session: disconnectFromPeer: 1453190975133.1630.HOv04Q==
2016-01-19 09:09:43.397 ThaliTest[2335:5022134] client session: disconnect
2016-01-19 09:09:43.397 ThaliTest[2335:5022134] client session: stateChange:2->0 1453190975133.1630.HOv04Q==
,2016-01-19 09:09:43.467 ThaliTest[2335:5022134] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-19 09:09:43.531 ThaliTest[2335:5023888] server session: connected
2016-01-19 09:09:43.531 ThaliTest[2335:5023888] server session: stateChange:1->2 1453190975133.1630
,2016-01-19 09:09:43.533 ThaliTest[2335:5021955] server relay: socket disconnected
,2016-01-19 09:09:43.533 ThaliTest[2335:5021955] server relay: 0x19b7ddf0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 09:09:43.598 ThaliTest[2335:5023875] server session: not connected 1453190975133.1630
,calling stopBroadcasting
,2016-01-19 09:09:44.141 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:44.141 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:44.141 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:44.,142 ThaliTest[2335:5022134] server session: disconnect
2016-01-19 09:09:44.142 ThaliTest[2335:5022134] server session: stateChange:2->0 1453190975133.1630
2016-01-19 09:09:44.142 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-19 09:09:44.723 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:44.724 ThaliTest[2335:5022134] server: starting 1453190984722.2335.2y+qhQ==
2016-01-19 09:09:44.724 ThaliTest[2335:5022134] multipeer session: start timer: 0x19b638f0
2016-01-19 09:09:44.724 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190984722.2335
2016-01-19 09:09:44.724 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-19 09:09:45.931 ThaliTest[2335:5021955] client: found peer: 1453190981990.1630.EJAjVw==
,2016-01-19 09:09:45.931 ThaliTest[2335:5022134] jxcore: connect 1453190981990.1630.EJAjVw==
2016-01-19 09:09:45.932 ThaliTest[2335:5022134] client session: connect
2016-01-19 09:09:45.932 ThaliTest[2335:5022134] client session: stateChange:0->1 145319098,1990.1630.EJAjVw==
,2016-01-19 09:09:45.935 ThaliTest[2335:5021955] multipeer session: reset timer
2016-01-19 09:09:45.935 ThaliTest[2335:5021955] multipeer session: stop timer
2016-01-19 09:09:45.935 ThaliTest[2335:5021955] multipeer session: start timer: 0x19b638f0
2016-01-19 09:09:45.935 ThaliTest[2335:5021955] server session: connect
2016-01-19 09:09:45.935 ThaliTest[2335:5021955] server session: stateChange:0->1 1453190981990.1630
,2016-01-19 09:09:45.937 ThaliTest[2335:5021955] server: accepting invitation 1453190981990.1630
,2016-01-19 09:09:49.956 ThaliTest[2335:5023884] server session: connected
2016-01-19 09:09:49.956 ThaliTest[2335:5023884] server session: stateChange:1->2 1453190981990.1630
,2016-01-19 09:09:49.957 ThaliTest[2335:5021955] server relay: socket disconnected
2016-01-19 09:09:49.957 ThaliTest[2335:5021955] server relay: 0x17f80250 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-19 09:09:50.080 ThaliTest[2335:5023872] client session: connected
2016-01-19 09:09:50.080 ThaliTest[2335:5023872] client session: stateChange:1->2 1453190981990.1630.EJAjVw==
,2016-01-19 09:09:50.083 ThaliTest[2335:5023872] client session: fireConnectCallback: 1453190981990.1630.EJAjVw==
2016-01-19 09:09:50.084 ThaliTest[2335:5023872] jxcore: connect: success
ok 84 Should be able to connect without error
,ok 85 Port should be within range
2016-01-19 09:09:50.085 ThaliTest[2335:5022134] jxcore: disconnect
2016-01-19 09:09:50.085 ThaliTest[2335:5022134] client session: disconnectFromPeer: 1453190981990.1630.EJAjVw==
2016-01-19 09:09:50.085 ThaliTest[2335:5022134] client session: disconnect
2016-01-19 09:09:50.085 ThaliTest[2335:5022134] client session: stateChange:2->0 1453190981990.1630.EJAjVw==
,2016-01-19 09:09:50.086 ThaliTest[2335:5023872] server session: not connected 1453190981990.1630
,2016-01-19 09:09:50.091 ThaliTest[2335:5022134] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-19 09:09:50.092 ThaliTest[2335:5022134] jxcore: disconnect
2016-01-19 09:09:50.092 ThaliTest[2335:5022134] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-19 09:09:50.439 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:50.439 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:50.439 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:50.439 ThaliTest[2335:5022134] server session: disconnect
2016-01-19 09:09:50.439 ThaliTest[2335:5022134] server session: stateChange:2->0 1453190981990.1630
2016-01-19 09:09:50.439 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,echo server started on port: 54536
,2016-01-19 09:09:51.433 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:09:51.435 ThaliTest[2335:5022134] server: starting 1453190991433.2335.u+MAlg==
2016-01-19 09:09:51.435 ThaliTest[2335:5022134] multipeer session: start timer: 0x17f027d0
2016-01-19 09:09:51.435 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453190991433.2335
2016-01-19 09:09:51.435 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,2016-01-19 09:09:52.774 ThaliTest[2335:5021955] multipeer session: reset timer
2016-01-19 09:09:52.774 ThaliTest[2335:5021955] multipeer session: stop timer
2016-01-19 09:09:52.775 ThaliTest[2335:5021955] multipeer session: start timer: 0x17f027d0
2016-,01-19 09:09:52.775 ThaliTest[2335:5021955] server session: connect
2016-01-19 09:09:52.775 ThaliTest[2335:5021955] server session: stateChange:0->1 1453190989471.1630
,2016-01-19 09:09:52.777 ThaliTest[2335:5021955] server: accepting invitation 1453190989471.1630
,2016-01-19 09:09:53.104 ThaliTest[2335:5021955] client: found peer: 1453190989471.1630.faRcUw==
2016-01-19 09:09:53.106 ThaliTest[2335:5022134] jxcore: connect 1453190989471.1630.faRcUw==
2016-01-19 09:09:53.106 ThaliTest[2335:5022134] client session: connect
,2016-01-19 09:09:53.106 ThaliTest[2335:5022134] client session: stateChange:0->1 1453190989471.1630.faRcUw==
,2016-01-19 09:09:56.568 ThaliTest[2335:5023884] server session: connected
2016-01-19 09:09:56.568 ThaliTest[2335:5023884] server session: stateChange:1->2 1453190989471.1630
,2016-01-19 09:09:56.630 ThaliTest[2335:5021955] server relay: connected (to port: 54536)
,2016-01-19 09:09:57.224 ThaliTest[2335:5023939] client session: connected
2016-01-19 09:09:57.224 ThaliTest[2335:5023939] client session: stateChange:1->2 1453190989471.1630.faRcUw==
,2016-01-19 09:09:57.226 ThaliTest[2335:5023939] client session: fireConnectCallback: 1453190989471.1630.faRcUw==
2016-01-19 09:09:57.226 ThaliTest[2335:5023939] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,2016-01-19 09:09:57.228 ThaliTest[2335:5021955] client: relay established
2016-01-19 09:09:57.228 ThaliTest[2335:5021955] client: new accepted socket: 0x19b4ae10
,2016-01-19 09:09:57.236 ThaliTest[2335:5023939] server session: not connected 1453190989471.1630
,data in 9855
,data in 10950
,data in 19710
,data in 32850
,data in 51323
,data in 56940
,data in 63510
,data in 67890
,data in 77745
,data in 78840
,data in 90885
,data in 111690
,data in 127020
,data in 131072
ok 91 the test messages should be equal
,2016-01-19 09:09:57.880 ThaliTest[2335:5022134] jxcore: disconnect
2016-01-19 09:09:57.880 ThaliTest[2335:5022134] client session: disconnectFromPeer: 1453190989471.1630.faRcUw==
2016-01-19 09:09:57.880 ThaliTest[2335:5022134] client session: disconnect
,2016-01-19 09:09:57.880 ThaliTest[2335:5022134] client session: stateChange:2->0 1453190989471.1630.faRcUw==
,2016-01-19 09:09:57.883 ThaliTest[2335:5022134] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-19 09:09:58.349 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:09:58.350 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:09:58.350 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:09:58.350 ThaliTest[2335:5022134] server session: disconnect
2016-01-19 09:09:58.350 ThaliTest[2335:5022134] server session: stateChange:2->0 1453190989471.1630
,2016-01-19 09:09:58.352 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,echo server started on port: 54542
,2016-01-19 09:10:01.230 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:10:01.231 ThaliTest[2335:5022134] server: starting 1453191001230.2335.n2a+/A==
2016-01-19 09:10:01.231 ThaliTest[2335:5022134] multipeer session: start timer: 0x17f80300
2016-01-19 09:10:01.231 ThaliTest[2335:5022134] THEMultipeerSession initialized peer 1453191001230.2335
2016-01-19 09:10:01.232 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-19 09:10:02.079 ThaliTest[2335:5021955] client: found peer: 1453190998198.1630.TpvP9A==
[{"peerIdentifier":"1453190998198.1630.TpvP9A==","peerName":"(null)","peerAvailable":true}]
2016-01-19 09:10:02.080 ThaliTest[2335:5022134] jxcore: connect 1453190998198.1630.TpvP9A==
2016-01-19 09:10:02.080 ThaliTest[2335:5022134] client session: connect
2016-01-19 09:10:02.080 ThaliTest[2335:5022134] client session: stateChange:0->1 1453190998198.1630.TpvP9A==
,2016-01-19 09:10:02.732 ThaliTest[2335:5021955] multipeer session: reset timer
2016-01-19 09:10:02.732 ThaliTest[2335:5021955] multipeer session: stop timer
2016-01-19 09:10:02.732 ThaliTest[2335:5021955] multipeer session: start timer: 0x17f80300
2016-,01-19 09:10:02.732 ThaliTest[2335:5021955] server session: connect
2016-01-19 09:10:02.732 ThaliTest[2335:5021955] server session: stateChange:0->1 1453190998198.1630
,2016-01-19 09:10:02.734 ThaliTest[2335:5021955] server: accepting invitation 1453190998198.1630
,2016-01-19 09:10:06.837 ThaliTest[2335:5023888] client session: connected
2016-01-19 09:10:06.837 ThaliTest[2335:5023888] client session: stateChange:1->2 1453190998198.1630.TpvP9A==
,2016-01-19 09:10:06.852 ThaliTest[2335:5023875] client session: fireConnectCallback: 1453190998198.1630.TpvP9A==
2016-01-19 09:10:06.853 ThaliTest[2335:5023875] jxcore: connect: success
ok 94 Should be able to connect without error
ok 95 Port should be within range
,ok 96 First connect should succeed
,2016-01-19 09:10:06.863 ThaliTest[2335:5021955] client: relay established
2016-01-19 09:10:06.863 ThaliTest[2335:5021955] client: new accepted socket: 0x1b24a7f0
,ok 97 the test messages should be equal
,ok 98 First send should succeed
,2016-01-19 09:10:06.911 ThaliTest[2335:5021955] client: socket closed
2016-01-19 09:10:06.911 ThaliTest[2335:5021955] client relay: socket disconnected
2016-01-19 09:10:06.911 ThaliTest[2335:5021955] client relay: 0x1b24a7f0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 09:10:06.911 ThaliTest[2335:5021955] client session: socket closed: 1453190998198.1630.TpvP9A==
2016-01-19 09:10:06.911 ThaliTest[2335:5021955] client session: onLinkFailure: 1453190998198.1630.TpvP9A==
2016-01-19 09:10:06.911 ThaliTest[2335:5021955] client session: disconnect
2016-01-19 09:10:06.911 ThaliTest[2335:5021955] client session: stateChange:2->0 14,53190998198.1630.TpvP9A==
,2016-01-19 09:10:06.914 ThaliTest[2335:5021955] client session: fireConnectionErrorEvent: 1453190998198.1630.TpvP9A==
,2016-01-19 09:10:06.917 ThaliTest[2335:5022134] jxcore: connect 1453190998198.1630.TpvP9A==
2016-01-19 09:10:06.917 ThaliTest[2335:5022134] client session: connect
2016-01-19 09:10:06.917 ThaliTest[2335:5022134] client session: stateChange:0->1 1453190998198.1630.TpvP9A==
,2016-01-19 09:10:07.026 ThaliTest[2335:5023888] server session: connected
2016-01-19 09:10:07.026 ThaliTest[2335:5023888] server session: stateChange:1->2 1453190998198.1630
,2016-01-19 09:10:07.050 ThaliTest[2335:5021955] server relay: connected (to port: 54542)
,2016-01-19 09:10:07.167 ThaliTest[2335:5023888] server session: not connected 1453190998198.1630
,2016-01-19 09:10:07.475 ThaliTest[2335:5021955] multipeer session: reset timer
2016-01-19 09:10:07.475 ThaliTest[2335:5021955] multipeer session: stop timer
2016-01-19 09:10:07.475 ThaliTest[2335:5021955] multipeer session: start timer: 0x17f80300
2016-01-19 09:10:07.476 ThaliTest[2335:5021955] server: disconnecting to refresh session (1453190998198.1630)
2016-01-19 09:10:07.476 ThaliTest[2335:5021955] server session: disconnect
,2016-01-19 09:10:07.476 ThaliTest[2335:5021955] server session: stateChange:2->0 1453190998198.1630
,2016-01-19 09:10:07.478 ThaliTest[2335:5021955] server session: connect
2016-01-19 09:10:07.478 ThaliTest[2335:5021955] server session: stateChange:0->1 1453190998198.1630
2016-01-19 09:10:07.483 ThaliTest[2335:5021955] server: accepting invitation 14531,90998198.1630
,2016-01-19 09:10:10.988 ThaliTest[2335:5023872] client session: connected
2016-01-19 09:10:10.988 ThaliTest[2335:5023872] client session: stateChange:1->2 1453190998198.1630.TpvP9A==
,2016-01-19 09:10:11.011 ThaliTest[2335:5023884] client session: fireConnectCallback: 1453190998198.1630.TpvP9A==
2016-01-19 09:10:11.011 ThaliTest[2335:5023884] jxcore: connect: success
ok 99 Should be able to connect without error
,ok 100 Port should be within range
,ok 101 Second connect should succeed
,2016-01-19 09:10:11.022 ThaliTest[2335:5021955] client: relay established
2016-01-19 09:10:11.022 ThaliTest[2335:5021955] client: new accepted socket: 0x19b3be80
,ok 102 the test messages should be equal
,ok 103 Second send should succeed
,# setup
,2016-01-19 09:10:11.075 ThaliTest[2335:5021955] client: socket closed
2016-01-19 09:10:11.075 ThaliTest[2335:5021955] client relay: socket disconnected
2016-01-19 09:10:11.075 ThaliTest[2335:5021955] client relay: 0x19b3be80 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-19 09:10:11.075 ThaliTest[2335:5021955] client session: socket closed: 1453190998198.1630.TpvP9A==
2016-01-19 ,09:10:11.075 ThaliTest[2335:5021955] client session: onLinkFailure: 1453190998198.1630.TpvP9A==
2016-01-19 09:10:11.075 ThaliTest[2335:5021955] client session: disconnect
2016-01-19 09:10:11.075 ThaliTest[2335:5021955] client session: stateChange:2->0 1453190998198.1630.TpvP9A==
,2016-01-19 09:10:11.079 ThaliTest[2335:5021955] client session: fireConnectionErrorEvent: 1453190998198.1630.TpvP9A==
,2016-01-19 09:10:11.531 ThaliTest[2335:5024015] server session: connected
2016-01-19 09:10:11.531 ThaliTest[2335:5024015] server session: stateChange:1->2 1453190998198.1630
,2016-01-19 09:10:11.579 ThaliTest[2335:5021955] server relay: connected (to port: 54542)
,2016-01-19 09:10:11.661 ThaliTest[2335:5024015] server session: not connected 1453190998198.1630
,calling stopBroadcasting
,2016-01-19 09:10:11.912 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:10:11.912 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:10:11.912 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:10:11.913 ThaliTest[2335:5022134] server session: disconnect
2016-01-19 09:10:11.913 ThaliTest[2335:5022134] server session: stateChange:2->0 1453190998198.1630
,2016-01-19 09:10:12.009 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F07574F4-EEBA-4649-9222-716724458B78/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 104 starting event should occur in right order
2016-01-19 09:10:13.409 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:10:13.411 ThaliTest[2335:5022134] server: starting ZTHUoh1ZkhpN3fJwV-fsPw.NV29gg==
2016-01-19 09:10:13.411 ThaliTest[2335:5022134] multipeer session: start timer: 0x1b2360d0
2016-01-19 09:10:13.411 ThaliTest[2335:5022134] THEMultipeerSessio,n initialized peer ZTHUoh1ZkhpN3fJwV-fsPw
,2016-01-19 09:10:13.412 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 105 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 106 stopping event should occur in right order
About to call stopBroadcasting
2016-01-19 09:10:13.414 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:10:13.414 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
2016-01-19 09:10:13.414 ThaliTest[2335:5022134] multipeer session: stop timer
,2016-01-19 09:10:13.415 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 107 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F07574F4-EEBA-4649-9222-716724458B78/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-19 09:10:14.684 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:10:14.686 ThaliTest[2335:5022134] server: starting ZTHUoh1ZkhpN3fJwV-fsPw.HuoXCA==
2016-01-19 09:10:14.686 ThaliTest[2335:5022134] multipeer session: start timer: 0x19b70940
2016-01-19 09:10:14.686 ThaliTest[2335:5022134] THEMultipeerSession initialized peer ZTHUoh1ZkhpN3fJwV-fsPw
2016-01-19 09:10:14.686 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 108 getDeviceIdentity should not return an error
ok 109 deviceName should not be null
Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
2016-01-19 09:10:14.687 ThaliTest[2335:5022134] jxcore: stopBroadcasting
2016-01-19 09:10:14.688 ThaliTest[2335:5022134] THEMultipeerSession stopping peer
,2016-01-19 09:10:14.688 ThaliTest[2335:5022134] multipeer session: stop timer
2016-01-19 09:10:14.689 ThaliTest[2335:5022134] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
# setup
,# ThaliReplicationManager replicates database
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/F07574F4-EEBA-4649-9222-716724458B78/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-19 09:10:16.096 ThaliTest[2335:5022134] jxcore: startBroadcasting
,2016-01-19 09:10:16.097 ThaliTest[2335:5022134] server: starting ZTHUoh1ZkhpN3fJwV-fsPw.VOnTzg==
2016-01-19 09:10:16.097 ThaliTest[2335:5022134] multipeer session: start timer: 0x1b3913c0
2016-01-19 09:10:16.097 ThaliTest[2335:5022134] THEMultipeerSession initialized peer ZTHUoh1ZkhpN3fJwV-fsPw
2016-01-19 09:10:16.098 ThaliTest[2335:5022134] jxcore: startBroadcasting: success
ok 110 getDeviceIdentity should not return an error
ok 111 deviceName should not be null
,2016-01-19 09:10:18.936 ThaliTest[2335:5021955] client: found peer: jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
,2016-01-19 09:10:20.202 ThaliTest[2335:5022134] jxcore: connect jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
2016-01-19 09:10:20.203 ThaliTest[2335:5022134] client session: connect
2016-01-19 09:10:20.203 ThaliTest[2335:5022134] client session: stateChange:0->1 jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
,ok 112 Should be able to put doc without error
,ok 113 1st change of local doc should contain local id
,2016-01-19 09:10:28.377 ThaliTest[2335:5021955] multipeer session: reset timer
2016-01-19 09:10:28.377 ThaliTest[2335:5021955] multipeer session: stop timer
2016-01-19 09:10:28.377 ThaliTest[2335:5021955] multipeer session: start timer: 0x1b3913c0
2016-01-19 09:10:28.377 ThaliTest[2335:5021955] server session: connect
2016-01-19 09:10:28.377 ThaliTest[2335:5021955] server session: stateChange:0->1 jhtZruJZ3UIZw5wMArQ0mw
2016-01-19 09:10:28.379 ThaliTest[2335:5021955] server: accepting invitation jhtZru,JZ3UIZw5wMArQ0mw
,2016-01-19 09:10:32.545 ThaliTest[2335:5024088] server session: connected
2016-01-19 09:10:32.545 ThaliTest[2335:5024088] server session: stateChange:1->2 jhtZruJZ3UIZw5wMArQ0mw
,2016-01-19 09:10:32.549 ThaliTest[2335:5021955] server relay: connected (to port: 54557)
,server bridge: new client socket
,2016-01-19 09:10:32.615 ThaliTest[2335:5023884] client session: connected
2016-01-19 09:10:32.615 ThaliTest[2335:5023884] client session: stateChange:1->2 jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
,2016-01-19 09:10:32.634 ThaliTest[2335:5023875] client session: fireConnectCallback: jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
2016-01-19 09:10:32.634 ThaliTest[2335:5023875] jxcore: connect: success
,2016-01-19 09:10:32.636 ThaliTest[2335:5021955] client: relay established
2016-01-19 09:10:32.636 ThaliTest[2335:5021955] client: new accepted socket: 0x1b294450
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
client bridge: new client socket
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
,client bridge: socket closed
,client bridge: new client socket
,ok 114 1st change of remote doc should contain remote id
,ok 115 Can update remote doc without error
null
,{ ok: true,
  id: '8eac1693-f973-4840-ab28-66236f165b3e',
  rev: '2-3050db00d56e987f45b8c7fe079c97fb' }
,ok 116 Remote changes occur in strict order
,client bridge: socket closed
client bridge: socket closed
client bridge: socket closed
,client bridge: new client socket
client bridge: new client socket
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
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
,client bridge: new client socket
,client bridge: socket closed
,client bridge: socket closed
,client bridge: new client socket
,client bridge: new client socket
,client bridge: socket closed
,client bridge: new client socket
,2016-01-19 09:10:48.237 ThaliTest[2335:5024077] server session: not connected jhtZruJZ3UIZw5wMArQ0mw
,2016-01-19 09:10:49.555 ThaliTest[2335:5021955] client: lost peer: jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
2016-01-19 09:10:49.555 ThaliTest[2335:5021955] client session: onPeerLost: jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
2016-01-19 09:10:49.555 ThaliTest[2335:5021955] client session: onLinkFailure: jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
2016-01-19 09:10:49.555 ThaliTest[2335:5021955] client session: disconnect
2016-01-19 09:10:49.555 ThaliTest[2335:5021955] client session: stateChange:2->0 jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
,2016-01-19 09:10:49.558 ThaliTest[2335:5021955] client session: fireConnectionErrorEvent: jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
,2016-01-19 09:10:49.561 ThaliTest[2335:5022134] jxcore: disconnect
2016-01-19 09:10:49.561 ThaliTest[2335:5022134] jxcore: disconnect: fail
Disconnect error with error: Error: Not connected to specified peer
2016-01-19 09:10:49.561 ThaliTest[2335:5022134] jxcore: connect jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
2016-01-19 09:10:49.562 ThaliTest[2335:5022134] client: connect: unreachable jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
2016-01-19 09:10:49.562 ThaliTest[2335:5022134] jxcore: connect: fail: Peer unreachable
Connect error with error: Error: Peer unreachable
,2016-01-19 09:10:49.577 ThaliTest[2335:5022134] jxcore: disconnect
2016-01-19 09:10:49.577 ThaliTest[2335:5022134] jxcore: disconnect: fail
Disconnect error with error: Error: Not connected to specified peer
peerIdentifier not available jhtZruJZ3UIZw5wMArQ0mw.KDlQ9Q==
,client bridge: socket closed
,client bridge: socket closed
,2016-01-19 09:10:58.378 ThaliTest[2335:5021955] multipeer session: restart
,client bridge: socket closed
,2016-01-19 09:11:28.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:11:58.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:12:28.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:12:58.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:13:28.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:13:58.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:14:28.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:14:58.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:15:28.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:15:58.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:16:28.377 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:16:58.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:17:28.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:17:58.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:18:28.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:18:58.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:19:28.377 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:19:58.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:20:28.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:20:58.378 ThaliTest[2335:5021955] multipeer session: restart
,2016-01-19 09:21:28.378 ThaliTest[2335:5021955] multipeer session: restart

```
