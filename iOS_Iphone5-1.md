#### Test 5065027860d2bae_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D4BBC16A-8CCC-4CE1-B43A-8FE65AA39A9D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D4BBC16A-8CCC-4CE1-B43A-8FE65AA39A9D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027860d2bae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50336"
,(lldb)     command script import "/tmp/D4BBC16A-8CCC-4CE1-B43A-8FE65AA39A9D/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-07 18:45:35.875 ThaliTest[375:198338] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/80AF41FB-813E-4F7B-A80F-74DB4584B712/Library/Cookies/Cookies.binarycookies
,2015-12-07 18:45:35.994 ThaliTest[375:198338] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-07 18:45:35.996 ThaliTest[375:198338] Multi-tasking -> Device: YES, App: YES
,2015-12-07 18:45:36.002 ThaliTest[375:198338] Unlimited access to network resources
,2015-12-07 18:45:36.014 ThaliTest[375:198338] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-07 18:45:47.354 ThaliTest[375:198338] Resetting plugins due to page load.
,2015-12-07 18:45:51.789 ThaliTest[375:198338] Finished load of: file:///var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/index.html
,2015-12-07 18:45:52.005 ThaliTest[375:198338] JXcore Cordova plugin initializing
,2015-12-07 18:45:52.008 ThaliTest[375:198535] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
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
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,ok 26 should be equal
,ok 27 should be equal
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
,ok 33 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
,ok 35 should be equal
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
,ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2015-12-07 18:47:36.657 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:36.921 ThaliTest[375:198535] server: starting 1449510456656.375.Tm6q2g==
,2015-12-07 18:47:36.921 ThaliTest[375:198535] multipeer session: start timer: 0x1f0ccf40
2015-12-07 18:47:36.922 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510456656.375
2015-12-07 18:47:36.923 ThaliTest[375:198535] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-07 18:47:36.925 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:47:36.926 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:47:36.926 ThaliTest[375:198535] multipeer session: stop timer
2015-12-07 18:47:36.926 Th,aliTest[375:198535] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2015-12-07 18:47:36.928 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:36.938 ThaliTest[375:198535] server: starting 1449510456928.375.iz8/OQ==
2015-12-07 18:47:36.939 ThaliTest[375:198535] multipeer session: start timer: 0x1bfd5390
2015-12-07 18:47:36.940 ThaliTest[375:198535] THEMultipeerSession initializ,ed peer 1449510456928.375
2015-12-07 18:47:36.941 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2015-12-07 18:47:36.943 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:47:36.943 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:47:36.943 ThaliTest[375:198535] multipeer session: stop timer
,2015-12-07 18:47:36.944 ThaliTest[375:198535] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2015-12-07 18:47:36.947 ThaliTest[375:198535] jxcore: startBroadcasting
2015-12-07 18:47:36.952 ThaliTest[375:198535] server: starting 1449510456946.375.5gkRyw==
2015-12-07 18:47:36.953 ThaliTe,st[375:198535] multipeer session: start timer: 0x175b0f10
2015-12-07 18:47:36.953 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510456946.375
2015-12-07 18:47:36.954 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 49 Should ,be able to call startBroadcasting without error
2015-12-07 18:47:36.956 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:47:36.956 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:47:36.956 ThaliTest[375:198535] multipee,r session: stop timer
2015-12-07 18:47:36.957 ThaliTest[375:198535] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:36.959 ThaliTest[375:198535] jxcore: startBroadcasting
2015-12-07 18:47:36.966 ThaliTest[375:198535] server: starting 1449510456959.375.AdxqGA==
2015-12-07 18:47:36.967 ThaliTest[375:198535] multipeer session: start timer: 0x17589e30
20,15-12-07 18:47:36.967 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510456959.375
2015-12-07 18:47:36.968 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-07 1,8:47:36.970 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:47:36.970 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:47:36.970 ThaliTest[375:198535] multipeer session: stop timer
2015-12-07 18:47:36.971 ThaliTest[375:,198535] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2015-12-07 18:47:36.974 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:36.990 ThaliTest[375:198535] server: starting 1449510456973.375.CQlVkQ==
,2015-12-07 18:47:36.995 ThaliTest[375:198535] multipeer session: start timer: 0x1f0d1650
,2015-12-07 18:47:37.000 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510456973.375
,2015-12-07 18:47:37.006 ThaliTest[375:198535] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.013 ThaliTest[375:198535] jxcore: stopBroadcasting
,2015-12-07 18:47:37.015 ThaliTest[375:198535] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.016 ThaliTest[375:198535] multipeer session: stop timer
,2015-12-07 18:47:37.023 ThaliTest[375:198535] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.027 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:37.029 ThaliTest[375:198535] server: starting 1449510457026.375.KPRejA==
,2015-12-07 18:47:37.031 ThaliTest[375:198535] multipeer session: start timer: 0x175b2460
,2015-12-07 18:47:37.034 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510457026.375
,2015-12-07 18:47:37.034 ThaliTest[375:198535] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.037 ThaliTest[375:198535] jxcore: stopBroadcasting
,2015-12-07 18:47:37.038 ThaliTest[375:198535] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.038 ThaliTest[375:198535] multipeer session: stop timer
,2015-12-07 18:47:37.045 ThaliTest[375:198535] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.050 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:37.053 ThaliTest[375:198535] server: starting 1449510457048.375.n/TrBQ==
,2015-12-07 18:47:37.055 ThaliTest[375:198535] multipeer session: start timer: 0x176a5f90
,2015-12-07 18:47:37.057 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510457048.375
,2015-12-07 18:47:37.057 ThaliTest[375:198535] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.063 ThaliTest[375:198535] jxcore: stopBroadcasting
,2015-12-07 18:47:37.065 ThaliTest[375:198535] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.065 ThaliTest[375:198535] multipeer session: stop timer
,2015-12-07 18:47:37.069 ThaliTest[375:198535] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.072 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:37.076 ThaliTest[375:198535] server: starting 1449510457072.375.x6ihNw==
,2015-12-07 18:47:37.078 ThaliTest[375:198535] multipeer session: start timer: 0x175a86a0
,2015-12-07 18:47:37.080 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510457072.375
,2015-12-07 18:47:37.083 ThaliTest[375:198535] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.086 ThaliTest[375:198535] jxcore: stopBroadcasting
,2015-12-07 18:47:37.088 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:47:37.088 ThaliTest[375:198535] multipeer session: stop timer
,2015-12-07 18:47:37.091 ThaliTest[375:198535] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.095 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:37.098 ThaliTest[375:198535] server: starting 1449510457095.375.bR2/Gw==
,2015-12-07 18:47:37.099 ThaliTest[375:198535] multipeer session: start timer: 0x1bfd5770
,2015-12-07 18:47:37.103 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510457095.375
,2015-12-07 18:47:37.106 ThaliTest[375:198535] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.108 ThaliTest[375:198535] jxcore: stopBroadcasting
,2015-12-07 18:47:37.109 ThaliTest[375:198535] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.110 ThaliTest[375:198535] multipeer session: stop timer
,2015-12-07 18:47:37.112 ThaliTest[375:198535] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-07 18:47:37.115 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:37.118 ThaliTest[375:198535] server: starting 1449510457115.375.nGmnFw==
,2015-12-07 18:47:37.121 ThaliTest[375:198535] multipeer session: start timer: 0x1bfd5770
,2015-12-07 18:47:37.130 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510457115.375
,2015-12-07 18:47:37.131 ThaliTest[375:198535] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-07 18:47:37.133 ThaliTest[375:198535] jxcore: stopBroadcasting
,2015-12-07 18:47:37.134 ThaliTest[375:198535] THEMultipeerSession stopping peer
,2015-12-07 18:47:37.135 ThaliTest[375:198535] multipeer session: stop timer
,2015-12-07 18:47:37.139 ThaliTest[375:198535] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-07 18:47:37.796 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:37.798 ThaliTest[375:198535] server: starting 1449510457795.375.LcwC0w==
2015-12-07 18:47:37.799 ThaliTest[375:198535] multipeer session: start timer: 0x1f0d32f0
2015-12-07 18:47:37.799 ThaliTest[375:198535] THEMultipeerSession initializ,ed peer 1449510457795.375
2015-12-07 18:47:37.799 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2015-12-07 18:47:37.800 ThaliTest[375:198535] jxcore: startBroadcasting
2015-12-07 1,8:47:37.801 ThaliTest[375:198535] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2015-12-07 18:47:37.802 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:47:37.803 ThaliTest[375:198535] THEMultipeerSession stopp,ing peer
2015-12-07 18:47:37.803 ThaliTest[375:198535] multipeer session: stop timer
2015-12-07 18:47:37.803 ThaliTest[375:198535] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-07 18:47:40.882 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:40.885 ThaliTest[375:198535] server: starting 1449510460882.375.a3ViKQ==
2015-12-07 18:47:40.886 ThaliTest[375:198535] multipeer session: start timer: 0x1bfd9fa0
2015-12-07 18:47:40.886 ThaliTest[375:198535] THEMultipeerSession initializ,ed peer 1449510460882.375
2015-12-07 18:47:40.886 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-07 18:47:40.888 ThaliTest[375:198535] jxcore: connect foobar
2015-12-07 18:4,7:40.888 ThaliTest[375:198535] client: unknown peer foobar
2015-12-07 18:47:40.889 ThaliTest[375:198535] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2015-12-07 18:47:40.892 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:47:40.893 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:47:40.893 ThaliTest[375:198535] multipeer session: stop timer
2015-12-07 18:47:40.893 ThaliTest[375:198535] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-07 18:47:46.070 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:46.072 ThaliTest[375:198535] server: starting 1449510466069.375.6eVJPw==
2015-12-07 18:47:46.073 ThaliTest[375:198535] multipeer session: start timer: 0x1bfdc510
2015-12-07 18:47:46.073 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510466069.375
2015-12-07 18:47:46.073 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-07 18:47:46.075 ThaliTest[375:198535] jxcore: disconnect
2015-12-07 18:47:46,.075 ThaliTest[375:198535] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2015-12-07 18:47:46.076 ThaliTest[375:198535] jxcore: stopBroadcasting
,2015-12-07 18:47:46.077 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:47:46.077 ThaliTest[375:198535] multipeer session: stop timer
2015-12-07 18:47:46.077 ThaliTest[375:198535] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-07 18:47:48.178 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:48.180 ThaliTest[375:198535] server: starting 1449510468177.375.Xvfalg==
2015-12-07 18:47:48.181 ThaliTest[375:198535] multipeer session: start timer: 0x1bfdfd40
2015-12-07 18:47:48.181 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510468177.375
2015-12-07 18:47:48.181 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2015-12-07 18:47:49.336 ThaliTest[375:198338] client: found peer: 1449510468363.408.sJcxPg==
2015-12-07 18:47:49.338 ThaliTest[375:198535] jxcore: connect 1449510468363.408.sJcxPg==
2015-12-07 18:47:49.338 ThaliTest[375:198535] client session: connect
2,015-12-07 18:47:49.338 ThaliTest[375:198535] client session: stateChange:0->1 1449510468363.408.sJcxPg==
,2015-12-07 18:47:49.345 ThaliTest[375:198338] client: found peer: 1449510468488.416.gJkiTg==
,2015-12-07 18:47:49.352 ThaliTest[375:198535] jxcore: connect 1449510468488.416.gJkiTg==
2015-12-07 18:47:49.352 ThaliTest[375:198535] client session: connect
2015-12-07 18:47:49.352 ThaliTest[375:198535] client session: stateChange:0->1 1449510468488.41,6.gJkiTg==
,2015-12-07 18:47:49.396 ThaliTest[375:198338] client: found peer: 1449510469411.383.Wmi/Ew==
2015-12-07 18:47:49.397 ThaliTest[375:198535] jxcore: connect 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:49.397 ThaliTest[375:198535] client session: connect
2015-12-07 18:47:49.397 ThaliTest[375:198535] client session: stateChange:0->1 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:49.988 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:47:49.988 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:47:49.988 ThaliTest[375:198338] multipeer session: start timer: 0x1bfdfd40
2015-12-07 ,18:47:49.990 ThaliTest[375:198338] server session: connect
2015-12-07 18:47:49.990 ThaliTest[375:198338] server session: stateChange:0->1 1449510468488.416
,2015-12-07 18:47:49.998 ThaliTest[375:198338] server: accepting invitation 1449510468488.416
,2015-12-07 18:47:50.130 ThaliTest[375:198338] multipeer session: reset timer
,2015-12-07 18:47:50.131 ThaliTest[375:198338] multipeer session: stop timer
,2015-12-07 18:47:50.132 ThaliTest[375:198338] multipeer session: start timer: 0x1bfdfd40
,2015-12-07 18:47:50.136 ThaliTest[375:198338] server session: connect
,2015-12-07 18:47:50.139 ThaliTest[375:198338] server session: stateChange:0->1 1449510468363.408
,2015-12-07 18:47:50.169 ThaliTest[375:198338] server: accepting invitation 1449510468363.408
,2015-12-07 18:47:51.895 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:47:51.896 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:47:51.896 ThaliTest[375:198338] multipeer session: start timer: 0x1bfdfd40
2015-12-07 18:47:51.896 ThaliTest[375:198338] server session: connect
2015-12-07 18:47:51.896 ThaliTest[375:198338] server session: stateChange:0->1 1449510469411.383
,2015-12-07 18:47:51.902 ThaliTest[375:198338] server: accepting invitation 1449510469411.383
,2015-12-07 18:47:53.296 ThaliTest[375:199122] client session: connected
2015-12-07 18:47:53.296 ThaliTest[375:199122] client session: stateChange:1->2 1449510468488.416.gJkiTg==
2015-12-07 18:47:53.299 ThaliTest[375:199122] client session: fireConnectCal,lback: 1449510468488.416.gJkiTg==
2015-12-07 18:47:53.299 ThaliTest[375:199122] jxcore: connect: success
ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-07 18:47:53.304 ThaliTest[375:198535] jxcore: disconnect
2015-12-07 18:47:53.304 ThaliTest[375:198535] client session: disconnectFromPeer: 1449510468488.416.gJkiTg==
2015-12-07 18:47:53.304 ThaliTest[375:198535] client session: disconnect
2015-12-07 18:47:53.305 ThaliTest[375:198535] client session: stateChange:2->0 1449510468488.416.gJkiTg==
,2015-12-07 18:47:53.382 ThaliTest[375:198535] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-07 18:47:53.419 ThaliTest[375:199071] server session: connected
2015-12-07 18:47:53.419 ThaliTest[375:199071] server session: stateChange:1->2 1449510468488.416
,2015-12-07 18:47:53.431 ThaliTest[375:198338] server relay: socket disconnected
2015-12-07 18:47:53.432 ThaliTest[375:198338] server relay: 0x1f0e1fc0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:53.493 ThaliTest[375:199071] server session: not connected 1449510468488.416
,2015-12-07 18:47:53.622 ThaliTest[375:199147] client session: connected
2015-12-07 18:47:53.623 ThaliTest[375:199147] client session: stateChange:1->2 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:53.655 ThaliTest[375:199071] client session: fireConnectCallback: 1449510469411.383.Wmi/Ew==
2015-12-07 18:47:53.655 ThaliTest[375:199071] jxcore: connect: success
,ok 78 Should be able to connect without error
,ok 79 Port should be within range
,2015-12-07 18:47:53.658 ThaliTest[375:198535] jxcore: disconnect
,2015-12-07 18:47:53.659 ThaliTest[375:198535] client session: disconnectFromPeer: 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:53.659 ThaliTest[375:198535] client session: disconnect
,2015-12-07 18:47:53.659 ThaliTest[375:198535] client session: stateChange:2->0 1449510469411.383.Wmi/Ew==
,2015-12-07 18:47:53.669 ThaliTest[375:198535] jxcore: disconnect: success
,ok 80 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,not ok 81 .end() called twice
,  ---
,    operator: fail
,  ...
,2015-12-07 18:47:53.801 ThaliTest[375:199147] client session: connected
,2015-12-07 18:47:53.801 ThaliTest[375:199147] client session: stateChange:1->2 1449510468363.408.sJcxPg==
,2015-12-07 18:47:53.817 ThaliTest[375:199147] client session: fireConnectCallback: 1449510468363.408.sJcxPg==
,2015-12-07 18:47:53.818 ThaliTest[375:199147] jxcore: connect: success
,ok 82 Should be able to connect without error
,ok 83 Port should be within range
,2015-12-07 18:47:53.822 ThaliTest[375:198535] jxcore: disconnect
,2015-12-07 18:47:53.822 ThaliTest[375:198535] client session: disconnectFromPeer: 1449510468363.408.sJcxPg==
,2015-12-07 18:47:53.824 ThaliTest[375:198535] client session: disconnect
,2015-12-07 18:47:53.824 ThaliTest[375:198535] client session: stateChange:2->0 1449510468363.408.sJcxPg==
,2015-12-07 18:47:53.832 ThaliTest[375:199071] server session: connected
,2015-12-07 18:47:53.833 ThaliTest[375:199071] server session: stateChange:1->2 1449510468363.408
,2015-12-07 18:47:53.841 ThaliTest[375:198338] server relay: socket disconnected
,2015-12-07 18:47:53.842 ThaliTest[375:198338] server relay: 0x1f0e1000 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:47:53.916 ThaliTest[375:198535] jxcore: disconnect: success
,ok 84 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,not ok 85 .end() called twice
  ---
,    operator: fail
,  ...
,2015-12-07 18:47:53.923 ThaliTest[375:199121] server session: not connected 1449510468363.408
,calling stopBroadcasting
,2015-12-07 18:47:53.977 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:47:53.977 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:47:53.978 ThaliTest[375:198535] multipeer session: stop timer
2015-12-07 18:47:53.978 ThaliTest[375:198535] server session: disconnect
2015-12-07 18:47:53.978 ThaliTest[375:198535] server session: stateChange:2->0 1449510468488.416
,2015-12-07 18:47:53.982 ThaliTest[375:198535] server session: disconnect
2015-12-07 18:47:53.982 ThaliTest[375:198535] server session: stateChange:1->0 1449510469411.383
,2015-12-07 18:47:53.991 ThaliTest[375:198535] server session: disconnect
2015-12-07 18:47:53.991 ThaliTest[375:198535] server session: stateChange:2->0 1449510468363.408
,2015-12-07 18:47:54.278 ThaliTest[375:198535] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-07 18:47:56.485 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:47:56.488 ThaliTest[375:198535] server: starting 1449510476485.375./zzCMA==
2015-12-07 18:47:56.489 ThaliTest[375:198535] multipeer session: start timer: 0x1f0eb9d0
2015-12-07 18:47:56.489 ThaliTest[375:198535] THEMultipeerSession initializ,ed peer 1449510476485.375
2015-12-07 18:47:56.489 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error
,2015-12-07 18:47:56.782 ThaliTest[375:198338] client: found peer: 1449510476527.383.t1iPAw==
,2015-12-07 18:47:56.783 ThaliTest[375:198535] jxcore: connect 1449510476527.383.t1iPAw==
2015-12-07 18:47:56.785 ThaliTest[375:198535] client session: connect
2015-12-07 18:47:56.785 ThaliTest[375:198535] client session: stateChange:0->1 1449510476527.383.t1iPAw==
,2015-12-07 18:47:57.094 ThaliTest[375:198338] client: found peer: 1449510475581.416.zFnyqQ==
2015-12-07 18:47:57.096 ThaliTest[375:198535] jxcore: connect 1449510475581.416.zFnyqQ==
2015-12-07 18:47:57.096 ThaliTest[375:198535] client session: connect
2,015-12-07 18:47:57.096 ThaliTest[375:198535] client session: stateChange:0->1 1449510475581.416.zFnyqQ==
,2015-12-07 18:47:57.150 ThaliTest[375:198338] client: found peer: 1449510475496.408.7GdpBQ==
2015-12-07 18:47:57.151 ThaliTest[375:198535] jxcore: connect 1449510475496.408.7GdpBQ==
2015-12-07 18:47:57.152 ThaliTest[375:198535] client session: connect
2,015-12-07 18:47:57.152 ThaliTest[375:198535] client session: stateChange:0->1 1449510475496.408.7GdpBQ==
,2015-12-07 18:47:57.585 ThaliTest[375:198338] multipeer session: reset timer
,2015-12-07 18:47:57.585 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:47:57.586 ThaliTest[375:198338] multipeer session: start timer: 0x1f0eb9d0
2015-12-07 18:47:57.587 ThaliTest[375:198338] server session: connect
2015-12-07 18:47:57.587 ThaliTest[375:198338] server session: stateChange:0->1 1449510475581.416
2015-12-07 18:47:57.594 ThaliTest[375:198338] server: accepting invitation 1449510475581.416
,2015-12-07 18:47:57.801 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:47:57.802 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:47:57.802 ThaliTest[375:198338] multipeer session: start timer: 0x1f0eb9d0
2015-12-07 ,18:47:57.802 ThaliTest[375:198338] server session: connect
2015-12-07 18:47:57.802 ThaliTest[375:198338] server session: stateChange:0->1 1449510475496.408
2015-12-07 18:47:57.815 ThaliTest[375:198338] server: accepting invitation 1449510475496.408
,2015-12-07 18:47:57.964 ThaliTest[375:198338] multipeer session: reset timer
,2015-12-07 18:47:57.981 ThaliTest[375:198338] multipeer session: stop timer
,2015-12-07 18:47:57.984 ThaliTest[375:198338] multipeer session: start timer: 0x1f0eb9d0
,2015-12-07 18:47:57.986 ThaliTest[375:198338] server session: connect
,2015-12-07 18:47:57.987 ThaliTest[375:198338] server session: stateChange:0->1 1449510476527.383
,2015-12-07 18:47:58.007 ThaliTest[375:198338] server: accepting invitation 1449510476527.383
,2015-12-07 18:48:00.867 ThaliTest[375:199087] client session: connected
2015-12-07 18:48:00.867 ThaliTest[375:199087] client session: stateChange:1->2 1449510475581.416.zFnyqQ==
,2015-12-07 18:48:00.890 ThaliTest[375:199077] client session: fireConnectCallback: 1449510475581.416.zFnyqQ==
,2015-12-07 18:48:00.891 ThaliTest[375:199077] jxcore: connect: success
,ok 87 Should be able to connect without error
ok 88 Port should be within range
,2015-12-07 18:48:00.894 ThaliTest[375:198535] jxcore: connect 1449510475581.416.zFnyqQ==
,2015-12-07 18:48:00.894 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510475581.416.zFnyqQ==
,2015-12-07 18:48:00.894 ThaliTest[375:198535] jxcore: connect: fail: Aleady connecting
,ok 89 Should fail on double connect
,2015-12-07 18:48:00.896 ThaliTest[375:198535] jxcore: disconnect
2015-12-07 18:48:00.897 ThaliTest[375:198535] client session: disconnectFromPeer: 1449510475581.416.zFnyqQ==
,2015-12-07 18:48:00.897 ThaliTest[375:198535] client session: disconnect
2015-12-07 18:48:00.897 ThaliTest[375:198535] client session: stateChange:2->0 1449510475581.416.zFnyqQ==
,2015-12-07 18:48:00.981 ThaliTest[375:198535] jxcore: disconnect: success
,ok 90 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-07 18:48:01.243 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:48:01.243 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:48:01.243 ThaliTest[375:198535] multipeer session: stop timer
2015-12-07 18:48:01.244 Th,aliTest[375:198535] client session: disconnect
2015-12-07 18:48:01.244 ThaliTest[375:198535] client session: stateChange:1->0 1449510475496.408.7GdpBQ==
,2015-12-07 18:48:01.312 ThaliTest[375:198535] client session: disconnect
,2015-12-07 18:48:01.312 ThaliTest[375:198535] client session: stateChange:1->0 1449510476527.383.t1iPAw==
,2015-12-07 18:48:01.379 ThaliTest[375:198535] server session: disconnect
,2015-12-07 18:48:01.383 ThaliTest[375:198535] server session: stateChange:1->0 1449510476527.383
,2015-12-07 18:48:01.467 ThaliTest[375:198535] server session: disconnect
,2015-12-07 18:48:01.469 ThaliTest[375:198535] server session: stateChange:1->0 1449510475496.408
,2015-12-07 18:48:01.538 ThaliTest[375:198535] server session: disconnect
2015-12-07 18:48:01.539 ThaliTest[375:198535] server session: stateChange:1->0 1449510475581.416
,2015-12-07 18:48:01.606 ThaliTest[375:198535] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-07 18:48:09.482 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:48:09.485 ThaliTest[375:198535] server: starting 1449510489481.375.tffILg==
2015-12-07 18:48:09.485 ThaliTest[375:198535] multipeer session: start timer: 0x1f0fbc10
2015-12-07 18:48:09.485 ThaliTest[375:198535] THEMultipeerSession initializ,ed peer 1449510489481.375
2015-12-07 18:48:09.486 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 91 Should be able to call startBroadcasting without error
,2015-12-07 18:48:10.235 ThaliTest[375:198338] client: found peer: 1449510489175.408.1RR9xA==
2015-12-07 18:48:10.236 ThaliTest[375:198535] jxcore: connect 1449510489175.408.1RR9xA==
2015-12-07 18:48:10.236 ThaliTest[375:198535] client session: connect
2015-12-07 18:48:10.237 ThaliTest[375:198535] client session: stateChange:0->1 1449510489175.408.1RR9xA==
,2015-12-07 18:48:10.896 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:48:10.898 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:48:10.898 ThaliTest[375:198338] multipeer session: start timer: 0x1f0fbc10
2015-12-07 ,18:48:10.899 ThaliTest[375:198338] server session: connect
2015-12-07 18:48:10.900 ThaliTest[375:198338] server session: stateChange:0->1 1449510491347.383
2015-12-07 18:48:10.909 ThaliTest[375:198338] server: accepting invitation 1449510491347.383
2015,-12-07 18:48:10.909 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:48:10.910 ThaliTest[375:198338] multipeer session: stop timer
,2015-12-07 18:48:10.910 ThaliTest[375:198338] multipeer session: start timer: 0x1f0fbc10
,2015-12-07 18:48:10.911 ThaliTest[375:198338] server session: connect
2015-12-07 18:48:10.921 ThaliTest[375:198338] server session: stateChange:0->1 1449510489175.408
2015-12-07 18:48:10.934 ThaliTest[375:198338] server: accepting invitation 1449510489175.408
,2015-12-07 18:48:11.539 ThaliTest[375:198338] client: found peer: 1449510491347.383.nrOfbw==
2015-12-07 18:48:11.540 ThaliTest[375:198535] jxcore: connect 1449510491347.383.nrOfbw==
2015-12-07 18:48:11.540 ThaliTest[375:198535] client session: connect
2015-12-07 18:48:11.541 ThaliTest[375:198535] client session: stateChange:0->1 1449510491347.383.nrOfbw==
,2015-12-07 18:48:11.809 ThaliTest[375:198338] client: found peer: 1449510491053.416.ZCqZnQ==
2015-12-07 18:48:11.811 ThaliTest[375:198535] jxcore: connect 1449510491053.416.ZCqZnQ==
2015-12-07 18:48:11.812 ThaliTest[375:198535] client session: connect
2,015-12-07 18:48:11.812 ThaliTest[375:198535] client session: stateChange:0->1 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:11.931 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:48:11.932 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:48:11.932 ThaliTest[375:198338] multipeer session: start timer: 0x1f0fbc10
2015-12-07 ,18:48:11.932 ThaliTest[375:198338] server session: connect
2015-12-07 18:48:11.933 ThaliTest[375:198338] server session: stateChange:0->1 1449510491053.416
,2015-12-07 18:48:11.944 ThaliTest[375:198338] server: accepting invitation 1449510491053.416
,2015-12-07 18:48:14.495 ThaliTest[375:199087] client session: connected
2015-12-07 18:48:14.495 ThaliTest[375:199087] client session: stateChange:1->2 1449510489175.408.1RR9xA==
,2015-12-07 18:48:14.511 ThaliTest[375:199147] client session: fireConnectCallback: 1449510489175.408.1RR9xA==
2015-12-07 18:48:14.511 ThaliTest[375:199147] jxcore: connect: success
ok 92 Should be able to connect without error
ok 93 Port should be withi,n range
2015-12-07 18:48:14.514 ThaliTest[375:198535] jxcore: disconnect
2015-12-07 18:48:14.514 ThaliTest[375:198535] client session: disconnectFromPeer: 1449510489175.408.1RR9xA==
2015-12-07 18:48:14.514 ThaliTest[375:198535] client session: disconnec,t
,2015-12-07 18:48:14.514 ThaliTest[375:198535] client session: stateChange:2->0 1449510489175.408.1RR9xA==
,2015-12-07 18:48:14.525 ThaliTest[375:198535] jxcore: disconnect: success
ok 94 Should be able to disconnect without error
2015-12-07 18:48:14.527 ThaliTest[375:198535] jxcore: disconnect
2015-12-07 18:48:14.527 ThaliTest[375:198535] jxcore: disconnect: fail
ok 95 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-07 18:48:14.958 ThaliTest[375:199123] server session: connected
,2015-12-07 18:48:14.959 ThaliTest[375:199123] server session: stateChange:1->2 1449510491347.383
,2015-12-07 18:48:14.967 ThaliTest[375:198338] server relay: socket disconnected
,2015-12-07 18:48:14.968 ThaliTest[375:198338] server relay: 0x1f075ea0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:15.041 ThaliTest[375:199123] server session: connected
,2015-12-07 18:48:15.041 ThaliTest[375:199123] server session: stateChange:1->2 1449510489175.408
,2015-12-07 18:48:15.045 ThaliTest[375:198338] server relay: socket disconnected
,2015-12-07 18:48:15.045 ThaliTest[375:198338] server relay: 0x1bff16b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:15.072 ThaliTest[375:199123] server session: not connected 1449510491347.383
,2015-12-07 18:48:15.105 ThaliTest[375:199225] server session: connected
,2015-12-07 18:48:15.106 ThaliTest[375:199225] server session: stateChange:1->2 1449510491053.416
,2015-12-07 18:48:15.151 ThaliTest[375:199147] client session: connected
,2015-12-07 18:48:15.151 ThaliTest[375:199147] client session: stateChange:1->2 1449510491347.383.nrOfbw==
,2015-12-07 18:48:15.167 ThaliTest[375:199123] client session: fireConnectCallback: 1449510491347.383.nrOfbw==
,2015-12-07 18:48:15.167 ThaliTest[375:199123] jxcore: connect: success
,ok 96 Should be able to connect without error
,ok 97 Port should be within range
,2015-12-07 18:48:15.171 ThaliTest[375:198535] jxcore: disconnect
,2015-12-07 18:48:15.173 ThaliTest[375:198535] client session: disconnectFromPeer: 1449510491347.383.nrOfbw==
,2015-12-07 18:48:15.174 ThaliTest[375:198535] client session: disconnect
,2015-12-07 18:48:15.174 ThaliTest[375:198535] client session: stateChange:2->0 1449510491347.383.nrOfbw==
,2015-12-07 18:48:15.188 ThaliTest[375:198338] server relay: socket disconnected
,2015-12-07 18:48:15.189 ThaliTest[375:198338] server relay: 0x1f074950 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-07 18:48:15.217 ThaliTest[375:199147] server session: not connected 1449510491053.416
,2015-12-07 18:48:15.229 ThaliTest[375:199123] server session: not connected 1449510489175.408
,2015-12-07 18:48:15.302 ThaliTest[375:198535] jxcore: disconnect: success
,ok 98 Should be able to disconnect without error
,2015-12-07 18:48:15.305 ThaliTest[375:198535] jxcore: disconnect
,2015-12-07 18:48:15.305 ThaliTest[375:198535] jxcore: disconnect: fail
,ok 99 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,not ok 100 .end() called twice
  ---
,    operator: fail
,  ...
,2015-12-07 18:48:15.534 ThaliTest[375:199123] client session: connected
2015-12-07 18:48:15.534 ThaliTest[375:199123] client session: stateChange:1->2 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:15.556 ThaliTest[375:199147] client session: fireConnectCallback: 1449510491053.416.ZCqZnQ==
2015-12-07 18:48:15.556 ThaliTest[375:199147] jxcore: connect: success
ok 101 Should be able to connect without error
,ok 102 Port should be within range
,2015-12-07 18:48:15.558 ThaliTest[375:198535] jxcore: disconnect
2015-12-07 18:48:15.559 ThaliTest[375:198535] client session: disconnectFromPeer: 1449510491053.416.ZCqZnQ==
2015-12-07 18:48:15.559 ThaliTest[375:198535] client session: disconnect
2015-1,2-07 18:48:15.559 ThaliTest[375:198535] client session: stateChange:2->0 1449510491053.416.ZCqZnQ==
,2015-12-07 18:48:15.569 ThaliTest[375:198535] jxcore: disconnect: success
ok 103 Should be able to disconnect without error
2015-12-07 18:48:15.571 ThaliTest[375:198535] jxcore: disconnect
2015-12-07 18:48:15.571 ThaliTest[375:198535] jxcore: disconnect,: fail
ok 104 Disconnect should fail 
setting stopBroadcasting callback and ending test.
not ok 105 .end() called twice
  ---
    operator: fail
  ...
,2015-12-07 18:48:16.631 ThaliTest[375:198338] client: lost peer: 1449510491347.383.nrOfbw==
2015-12-07 18:48:16.631 ThaliTest[375:198338] client session: onPeerLost: 1449510491347.383.nrOfbw==
,2015-12-07 18:48:17.063 ThaliTest[375:198338] client: lost peer: 1449510489175.408.1RR9xA==
2015-12-07 18:48:17.064 ThaliTest[375:198338] client session: onPeerLost: 1449510489175.408.1RR9xA==
,calling stopBroadcasting
,2015-12-07 18:48:21.514 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:48:21.515 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:48:21.515 ThaliTest[375:198535] multipeer session: stop timer
2015-12-07 18:48:21.516 Th,aliTest[375:198535] server session: disconnect
2015-12-07 18:48:21.516 ThaliTest[375:198535] server session: stateChange:2->0 1449510489175.408
2015-12-07 18:48:21.517 ThaliTest[375:198535] server session: disconnect
,2015-12-07 18:48:21.517 ThaliTest[375:198535] server session: stateChange:2->0 1449510491053.416
,2015-12-07 18:48:21.885 ThaliTest[375:198535] server session: disconnect
2015-12-07 18:48:21.885 ThaliTest[375:198535] server session: stateChange:2->0 1449510491347.383
2015-12-07 18:48:21.886 ThaliTest[375:198535] jxcore: stopBroadcasting: success
sto,pBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-07 18:48:26.999 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:48:27.002 ThaliTest[375:198535] server: starting 1449510506999.375.Lduuig==
2015-12-07 18:48:27.003 ThaliTest[375:198535] multipeer session: start timer: 0x1f06e350
,2015-12-07 18:48:27.003 ThaliTest[375:198535] THEMultipeerSession initialized peer 1449510506999.375
2015-12-07 18:48:27.006 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 106 Should be able to call startBroadcasting without error
,echo server started
,2015-12-07 18:48:27.015 ThaliTest[375:198338] client: found peer: 1449510506003.383.i2Azhg==
[{"peerIdentifier":"1449510506003.383.i2Azhg==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 18:48:27.018 ThaliTest[375:198535] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:27.018 ThaliTest[375:198535] client session: connect
2015-12-07 18:48:27.019 ThaliTest[375:198535] client session: stateChange:0->1 1449510506003.38,3.i2Azhg==
,2015-12-07 18:48:27.844 ThaliTest[375:198338] client: found peer: 1449510506165.416.wWLXyQ==
[{"peerIdentifier":"1449510506165.416.wWLXyQ==","peerName":"(null)","peerAvailable":true}]
2015-12-07 18:48:27.846 ThaliTest[375:198535] jxcore: connect 14495105,06165.416.wWLXyQ==
2015-12-07 18:48:27.849 ThaliTest[375:198535] client session: connect
2015-12-07 18:48:27.849 ThaliTest[375:198535] client session: stateChange:0->1 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:28.047 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:48:28.047 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:48:28.048 ThaliTest[375:198338] multipeer session: start timer: 0x1f06e350
2015-12-07 18:48:28.048 ThaliTest[375:198338] server session: connect
2015-12-07 18:48:28.048 ThaliTest[375:198338] server session: stateChange:0->1 1449510506165.416
,2015-12-07 18:48:28.054 ThaliTest[375:198338] server: accepting invitation 1449510506165.416
,2015-12-07 18:48:28.309 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:48:28.309 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:48:28.310 ThaliTest[375:198338] multipeer session: start timer: 0x1f06e350
2015-12-07 18:48:28.310 ThaliTest[375:198338] server session: connect
2015-12-07 18:48:28.310 ThaliTest[375:198338] server session: stateChange:0->1 1449510506003.383
,2015-12-07 18:48:28.318 ThaliTest[375:198338] server: accepting invitation 1449510506003.383
,2015-12-07 18:48:28.346 ThaliTest[375:198338] multipeer session: reset timer
,2015-12-07 18:48:28.348 ThaliTest[375:198338] multipeer session: stop timer
,2015-12-07 18:48:28.351 ThaliTest[375:198338] multipeer session: start timer: 0x1f06e350
,2015-12-07 18:48:28.353 ThaliTest[375:198338] server session: connect
,2015-12-07 18:48:28.355 ThaliTest[375:198338] server session: stateChange:0->1 1449510507109.408
,2015-12-07 18:48:28.384 ThaliTest[375:198338] server: accepting invitation 1449510507109.408
,2015-12-07 18:48:29.144 ThaliTest[375:198338] client: found peer: 1449510507109.408.rby7cA==
,[{"peerIdentifier":"1449510507109.408.rby7cA==","peerName":"(null)","peerAvailable":true}]
,2015-12-07 18:48:29.205 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:29.206 ThaliTest[375:198535] client session: connect
,2015-12-07 18:48:29.206 ThaliTest[375:198535] client session: stateChange:0->1 1449510507109.408.rby7cA==
,2015-12-07 18:48:29.817 ThaliTest[375:199229] client session: connected
2015-12-07 18:48:29.818 ThaliTest[375:199229] client session: stateChange:1->2 1449510506003.383.i2Azhg==
,2015-12-07 18:48:29.860 ThaliTest[375:199147] client session: fireConnectCallback: 1449510506003.383.i2Azhg==
2015-12-07 18:48:29.860 ThaliTest[375:199147] jxcore: connect: success
ok 107 Should be able to connect without error
ok 108 Port should be within range
ok 109 First connect should succeed
,2015-12-07 18:48:29.901 ThaliTest[375:198338] client: relay established
2015-12-07 18:48:29.901 ThaliTest[375:198338] client: new accepted socket: 0x1f0736e0
,ok 110 the test messages should be equal
ok 111 First send should succeed
,2015-12-07 18:48:30.271 ThaliTest[375:198338] client: socket closed
2015-12-07 18:48:30.271 ThaliTest[375:198338] client relay: socket disconnected
2015-12-07 18:48:30.271 ThaliTest[375:198338] client relay: 0x1f0736e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:30.272 ThaliTest[375:198338] client session: socket closed: 1449510506003.383.i2Azhg==
2015-12-07 18:48:30.272 ThaliTest[375:198338] client session: onLinkFailure: 1449510506003.383.i2Azhg==
2015-12-07 18:48:30.272 ThaliTest[375:198338] client session: disconnect
2015-12-07 18:48:30.272 ThaliTest[375:198338] client session: stateChange:2->0 1449510506003.383.i2Azhg==
,2015-12-07 18:48:30.287 ThaliTest[375:198338] client session: fireConnectionErrorEvent: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:30.289 ThaliTest[375:198535] jxcore: connect 1449510506003.383.i2Azhg==
2015-12-07 18:48:30.289 ThaliTest[375:198535] client session: connect
2015-12-07 18:48:30.289 ThaliTest[375:198535] client session: stateChange:0->1 1449510506003.383.i2Azhg==
,2015-12-07 18:48:31.055 ThaliTest[375:199229] server session: connected
2015-12-07 18:48:31.056 ThaliTest[375:199229] server session: stateChange:1->2 1449510506165.416
,2015-12-07 18:48:31.062 ThaliTest[375:198338] server relay: connected (to port: 5001)
,2015-12-07 18:48:31.279 ThaliTest[375:199147] server session: not connected 1449510506165.416
,2015-12-07 18:48:31.383 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:48:31.383 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:48:31.383 ThaliTest[375:198338] multipeer session: start timer: 0x1f06e350
2015-12-07 ,18:48:31.383 ThaliTest[375:198338] server: disconnecting to refresh session (1449510506165.416)
2015-12-07 18:48:31.384 ThaliTest[375:198338] server session: disconnect
2015-12-07 18:48:31.384 ThaliTest[375:198338] server session: stateChange:2->0 1449510506165.416
,2015-12-07 18:48:31.387 ThaliTest[375:198338] server session: connect
,2015-12-07 18:48:31.387 ThaliTest[375:198338] server session: stateChange:0->1 1449510506165.416
,2015-12-07 18:48:31.397 ThaliTest[375:198338] server: accepting invitation 1449510506165.416
,2015-12-07 18:48:31.724 ThaliTest[375:199297] server session: connected
,2015-12-07 18:48:31.725 ThaliTest[375:199297] server session: stateChange:1->2 1449510506003.383
,2015-12-07 18:48:31.785 ThaliTest[375:198338] server relay: connected (to port: 5001)
,2015-12-07 18:48:31.995 ThaliTest[375:199123] client session: connected
,2015-12-07 18:48:31.995 ThaliTest[375:199123] client session: stateChange:1->2 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:32.001 ThaliTest[375:199229] server session: not connected 1449510506003.383
,2015-12-07 18:48:32.147 ThaliTest[375:198338] multipeer session: reset timer
,2015-12-07 18:48:32.147 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:48:32.147 ThaliTest[375:198338] multipeer session: start timer: 0x1f06e350
,2015-12-07 18:48:32.147 ThaliTest[375:198338] server: disconnecting to refresh session (1449510506003.383)
,2015-12-07 18:48:32.148 ThaliTest[375:198338] server session: disconnect
,2015-12-07 18:48:32.148 ThaliTest[375:198338] server session: stateChange:2->0 1449510506003.383
,2015-12-07 18:48:32.151 ThaliTest[375:198338] server session: connect
2015-12-07 18:48:32.151 ThaliTest[375:198338] server session: stateChange:0->1 1449510506003.383
,2015-12-07 18:48:32.166 ThaliTest[375:198338] server: accepting invitation 1449510506003.383
,2015-12-07 18:48:32.376 ThaliTest[375:199296] server session: connected
2015-12-07 18:48:32.376 ThaliTest[375:199296] server session: stateChange:1->2 1449510507109.408
,2015-12-07 18:48:32.386 ThaliTest[375:198338] server relay: connected (to port: 5001)
,2015-12-07 18:48:32.750 ThaliTest[375:199229] client session: fireConnectCallback: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:32.750 ThaliTest[375:199229] jxcore: connect: success
ok 112 Should be able to connect without error
,ok 113 Port should be within range
ok 114 First connect should succeed
,2015-12-07 18:48:32.778 ThaliTest[375:198338] client: relay established
2015-12-07 18:48:32.779 ThaliTest[375:198338] client: new accepted socket: 0x1bf5ef80
,2015-12-07 18:48:32.826 ThaliTest[375:199297] server session: not connected 1449510507109.408
,2015-12-07 18:48:32.884 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:48:32.884 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:48:32.884 ThaliTest[375:198338] multipeer session: start timer: 0x1f06e350
2015-12-07 ,18:48:32.885 ThaliTest[375:198338] server: disconnecting to refresh session (1449510507109.408)
2015-12-07 18:48:32.885 ThaliTest[375:198338] server session: disconnect
2015-12-07 18:48:32.885 ThaliTest[375:198338] server session: stateChange:2->0 144951,0507109.408
,2015-12-07 18:48:32.891 ThaliTest[375:198338] server session: connect
2015-12-07 18:48:32.891 ThaliTest[375:198338] server session: stateChange:0->1 1449510507109.408
,2015-12-07 18:48:32.907 ThaliTest[375:198338] server: accepting invitation 1449510507109.408
2015-12-07 18:48:32.908 ThaliTest[375:199123] client session: connected
2015-12-07 18:48:32.909 ThaliTest[375:199123] client session: stateChange:1->2 1449510507109.408.rby7cA==
,2015-12-07 18:48:32.918 ThaliTest[375:199123] client session: fireConnectCallback: 1449510507109.408.rby7cA==
,2015-12-07 18:48:32.920 ThaliTest[375:199123] jxcore: connect: success
ok 115 Should be able to connect without error
ok 116 Port should be within range
ok 117 First connect should succeed
,2015-12-07 18:48:32.983 ThaliTest[375:198338] client: relay established
2015-12-07 18:48:32.983 ThaliTest[375:198338] client: new accepted socket: 0x1f0ec9e0
,ok 118 the test messages should be equal
,ok 119 First send should succeed
,2015-12-07 18:48:33.014 ThaliTest[375:198338] client: socket closed
2015-12-07 18:48:33.014 ThaliTest[375:198338] client relay: socket disconnected
2015-12-07 18:48:33.014 ThaliTest[375:198338] client relay: 0x1bf5ef80 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:33.014 ThaliTest[375:198338] client session: socket closed: 1449510506165.416.wWLXyQ==
2015-12-07 18:48:33.,015 ThaliTest[375:198338] client session: onLinkFailure: 1449510506165.416.wWLXyQ==
2015-12-07 18:48:33.015 ThaliTest[375:198338] client session: disconnect
2015-12-07 18:48:33.015 ThaliTest[375:198338] client session: stateChange:2->0 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:33.032 ThaliTest[375:198338] client session: fireConnectionErrorEvent: 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:33.033 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:33.037 ThaliTest[375:198535] client session: connect
,2015-12-07 18:48:33.043 ThaliTest[375:198535] client session: stateChange:0->1 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:33.101 ThaliTest[375:199123] client session: connected
,2015-12-07 18:48:33.101 ThaliTest[375:199123] client session: stateChange:1->2 1449510506003.383.i2Azhg==
,2015-12-07 18:48:33.158 ThaliTest[375:199225] client session: fireConnectCallback: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:33.160 ThaliTest[375:199225] jxcore: connect: success
,2015-12-07 18:48:33.820 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:33.820 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510506165.416.wWLXyQ==
2015-12-07 18:48:33.820 ThaliTest[375:198535] jxcore: con,nect: fail: Aleady connecting
2015-12-07 18:48:33.821 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:33.821 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510506165.416.wWLXyQ==
2015-12-07 18:48:33.821 Th,aliTest[375:198535] jxcore: connect: fail: Aleady connecting
ok 120 Should be able to connect without error
ok 121 Port should be within range
ok 122 Second connect should succeed
,2015-12-07 18:48:33.866 ThaliTest[375:198338] client: relay established
2015-12-07 18:48:33.867 ThaliTest[375:198338] client: new accepted socket: 0x1f0e4d00
,ok 123 the test messages should be equal
,ok 124 First send should succeed
,2015-12-07 18:48:33.899 ThaliTest[375:198338] client: socket closed
2015-12-07 18:48:33.900 ThaliTest[375:198338] client relay: socket disconnected
2015-12-07 18:48:33.900 ThaliTest[375:198338] client relay: 0x1f0ec9e0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:33.901 ThaliTest[375:198338] client session: socket closed: 1449510507109.408.rby7cA==
2015-12-07 18:48:33.,901 ThaliTest[375:198338] client session: onLinkFailure: 1449510507109.408.rby7cA==
2015-12-07 18:48:33.901 ThaliTest[375:198338] client session: disconnect
2015-12-07 18:48:33.902 ThaliTest[375:198338] client session: stateChange:2->0 1449510507109.408.,rby7cA==
,2015-12-07 18:48:33.912 ThaliTest[375:198338] client session: fireConnectionErrorEvent: 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.915 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.922 ThaliTest[375:198535] client session: connect
,2015-12-07 18:48:33.928 ThaliTest[375:198535] client session: stateChange:0->1 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.946 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.948 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.951 ThaliTest[375:198535] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:33.958 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.960 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
,2015-12-07 18:48:33.967 ThaliTest[375:198535] jxcore: connect: fail: Aleady connecting
,ok 125 the test messages should be equal
,ok 126 Second send should succeed
# setup
,2015-12-07 18:48:34.006 ThaliTest[375:198338] client: socket closed
2015-12-07 18:48:34.007 ThaliTest[375:198338] client relay: socket disconnected
2015-12-07 18:48:34.008 ThaliTest[375:198338] client relay: 0x1f0e4d00 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-07 18:48:34.008 ThaliTest[375:198338] client session: socket closed: 1449510506003.383.i2Azhg==
2015-12-07 18:48:34.,008 ThaliTest[375:198338] client session: onLinkFailure: 1449510506003.383.i2Azhg==
2015-12-07 18:48:34.008 ThaliTest[375:198338] client session: disconnect
2015-12-07 18:48:34.008 ThaliTest[375:198338] client session: stateChange:2->0 1449510506003.383.,i2Azhg==
,2015-12-07 18:48:34.016 ThaliTest[375:198338] client session: fireConnectionErrorEvent: 1449510506003.383.i2Azhg==
,2015-12-07 18:48:34.402 ThaliTest[375:199225] server session: connected
,2015-12-07 18:48:34.405 ThaliTest[375:199225] server session: stateChange:1->2 1449510506165.416
,2015-12-07 18:48:34.413 ThaliTest[375:198338] server relay: connected (to port: 5001)
,2015-12-07 18:48:34.594 ThaliTest[375:199297] server session: not connected 1449510506165.416
,2015-12-07 18:48:34.821 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:34.822 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510506165.416.wWLXyQ==
2015-12-07 18:48:34.822 ThaliTest[375:198535] jxcore: con,nect: fail: Aleady connecting
2015-12-07 18:48:34.824 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:34.824 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510506165.416.wWLXyQ==
2015-12-07 18:48:34.825 Th,aliTest[375:198535] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:34.947 ThaliTest[375:199123] server session: connected
,2015-12-07 18:48:34.947 ThaliTest[375:199123] server session: stateChange:1->2 1449510506003.383
,2015-12-07 18:48:34.961 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:34.961 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:34.961 ThaliTest[375:198535] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:34.975 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:34.975 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510507109.408.rby7cA==
2015-12-07 18:48:34.976 ThaliTest[375:198535] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:35.024 ThaliTest[375:198338] server relay: connected (to port: 5001)
,2015-12-07 18:48:35.178 ThaliTest[375:199087] server session: not connected 1449510506003.383
,2015-12-07 18:48:35.439 ThaliTest[375:198338] multipeer session: reset timer
2015-12-07 18:48:35.439 ThaliTest[375:198338] multipeer session: stop timer
2015-12-07 18:48:35.439 ThaliTest[375:198338] multipeer session: start timer: 0x1f06e350
2015-12-07 ,18:48:35.439 ThaliTest[375:198338] server: disconnecting to refresh session (1449510506165.416)
2015-12-07 18:48:35.439 ThaliTest[375:198338] server session: disconnect
2015-12-07 18:48:35.440 ThaliTest[375:198338] server session: stateChange:2->0 1449510506165.416
,2015-12-07 18:48:35.830 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:35.830 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510506165.416.wWLXyQ==
2015-12-07 18:48:35.830 ThaliTest[375:198535] jxcore: con,nect: fail: Aleady connecting
2015-12-07 18:48:35.832 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:35.832 ThaliTest[375:198535] client: already connect(ing/ed) to 1449510506165.416.wWLXyQ==
2015-12-07 18:48:35.833 ThaliTest[375:198535] jxcore: connect: fail: Aleady connecting
,2015-12-07 18:48:35.887 ThaliTest[375:198338] server session: connect
2015-12-07 18:48:35.887 ThaliTest[375:198338] server session: stateChange:0->1 1449510506165.416
,2015-12-07 18:48:35.892 ThaliTest[375:198338] server: accepting invitation 1449510506165.416
,calling stopBroadcasting
2015-12-07 18:48:35.916 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:48:35.916 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:48:35.916 ThaliTest[375:198535] multipeer session: stop timer
2015-12-07 18:48:35.916 ThaliTest[375:198535] client session: disconnect
2015-12-07 18:48:35.919 ThaliTest[375:198535] client session: stateChange:1->0 1449510506165.416.wWLXyQ==
,2015-12-07 18:48:36.017 ThaliTest[375:198535] client session: disconnect
2015-12-07 18:48:36.017 ThaliTest[375:198535] client session: stateChange:1->0 1449510507109.408.rby7cA==
,2015-12-07 18:48:36.220 ThaliTest[375:198535] server session: disconnect
2015-12-07 18:48:36.220 ThaliTest[375:198535] server session: stateChange:1->0 1449510507109.408
,2015-12-07 18:48:36.299 ThaliTest[375:198535] server session: disconnect
,2015-12-07 18:48:36.300 ThaliTest[375:198535] server session: stateChange:1->0 1449510506165.416
,2015-12-07 18:48:36.301 ThaliTest[375:198535] server session: disconnect
,2015-12-07 18:48:36.301 ThaliTest[375:198535] server session: stateChange:2->0 1449510506003.383
,2015-12-07 18:48:36.578 ThaliTest[375:198535] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,2015-12-07 18:48:36.593 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:36.594 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:36.594 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:36.595 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:36.596 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:36.596 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:36.841 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:36.841 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:36.842 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:36.843 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:36.843 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:36.844 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,# teardown
,2015-12-07 18:48:37.605 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:37.605 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:37.606 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:37.607 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:37.608 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:37.608 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:37.845 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:37.846 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:37.846 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:37.847 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:37.848 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:37.849 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:38.615 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:38.615 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:38.616 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2015-12-07 18:48:38.617 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:38.617 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:38.618 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:38.854 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:38.855 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:38.855 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:38.856 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:38.857 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:38.857 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:39.619 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:39.619 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:39.620 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:39.622 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:39.623 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:39.623 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/80AF41FB-813E-4F7B-A80F-74DB4584B712/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2015-12-07 18:48:39.873 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:39.874 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:39.874 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2015-12-07 18:48:39.875 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:39.876 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:39.876 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,ok 127 starting event should occur in right order
,2015-12-07 18:48:39.919 ThaliTest[375:198535] jxcore: startBroadcasting
,2015-12-07 18:48:39.922 ThaliTest[375:198535] server: starting ygVID9zb8fBvqW5rutg4og.gdH4HA==
2015-12-07 18:48:39.922 ThaliTest[375:198535] multipeer session: start timer: 0x1f067bc0
2015-12-07 18:48:39.922 ThaliTest[375:198535] THEMultipeerSession init,ialized peer ygVID9zb8fBvqW5rutg4og
2015-12-07 18:48:39.923 ThaliTest[375:198535] jxcore: startBroadcasting: success
ok 128 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 129 stopping event should occur in ,right order
About to call stopBroadcasting
2015-12-07 18:48:39.926 ThaliTest[375:198535] jxcore: stopBroadcasting
2015-12-07 18:48:39.926 ThaliTest[375:198535] THEMultipeerSession stopping peer
2015-12-07 18:48:39.926 ThaliTest[375:198535] multipeer se,ssion: stop timer
2015-12-07 18:48:39.927 ThaliTest[375:198535] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,ok 130 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,2015-12-07 18:48:40.622 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:40.623 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:40.623 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:40.624 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:40.625 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:40.625 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:40.887 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:40.888 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:40.888 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:40.890 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:40.890 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:40.890 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,# ThaliReplicationManager receives identity
,2015-12-07 18:48:41.626 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:41.627 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:41.627 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:41.628 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:41.629 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:41.629 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:41.893 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:41.894 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:41.894 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:41.895 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:41.896 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:41.896 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:42.637 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:42.637 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:42.638 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:42.639 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:42.639 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:42.640 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:42.902 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:42.902 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:42.902 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2,015-12-07 18:48:42.904 ThaliTest[375:198535] jxcore: connect 1449510506165.416.wWLXyQ==
2015-12-07 18:48:42.904 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:42.904 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,2015-12-07 18:48:43.642 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:43.643 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:43.643 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
2015-12-07 18:48:43.645 ThaliTest[375:198535] jxcore: connect 1449510507109.408.rby7cA==
2015-12-07 18:48:43.645 ThaliTest[375:198535] Communications not enabled
2015-12-07 18:48:43.645 ThaliTest[375:198535] jxcore: connect: fail: app: Not initialised
,not ok 131 Second connect should succeed
,  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,not ok 132 Second connect should succeed
,  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,2015-12-07 18:48:43.967 ThaliTest[375:198535] Error!: connect EADDRNOTAVAIL
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_functi,onName":"connect","_lineNumber":"707","_columnNumber":"19","_msg":"    at connect@net.js:707:19"},{"_fileName":"net.js","_functionName":"Socket.prototype.connect","_lineNumber":"756","_columnNumber":"5","_msg":"    at Socket.prototype.connect@net.js:756:5",},{"_fileName":"net.js","_functionName":"exports.createConnection","_lineNumber":"72","_columnNumber":"10","_msg":"    at exports.createConnection@net.js:72:10"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5F,B35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"sendData","_lineNumber":"277","_columnNumber":"24","_msg":"    at sendData@/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.a,pp/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"325",",_columnNumber":"17","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3F,4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer","_lineNumber":"251","_columnNumber":"9","_msg":"    at connectWithRetry/connectToPeer@/private/var/mobile/Contain,ers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_t,ests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer/</<","_lineNumber":"260","_columnNumber":"45","_msg":"    at connectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB3,5197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45"},{"_fileName":"timers.js","_functionName":"listOnTimeout","_lineNumber":"112","_columnNumber":"9","_msg":"    at listOnTimeout@timers.js:112:9"},{"_fileName":"net.js","_functionName":"u,nknown","_lineNumber":835,"_columnNumber":10,"_msg":"    at "}]
Uncaught Exception: Error: connect EADDRNOTAVAIL
,[ { _fileName: 'net.js',
    _functionName: 'errnoException',
    _lineNumber: '835',
    _columnNumber: '11',
    _msg: '    at errnoException@net.js:835:11' },
  { _fileName: 'net.js',
    _functionName: 'connect',
    _lineNumber: '707',
    _co,lumnNumber: '19',
    _msg: '    at connect@net.js:707:19' },
  { _fileName: 'net.js',
    _functionName: 'Socket.prototype.connect',
    _lineNumber: '756',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.connect@net.js:756:5' },
  { _fi,leName: 'net.js',
    _functionName: 'exports.createConnection',
    _lineNumber: '72',
    _columnNumber: '10',
    _msg: '    at exports.createConnection@net.js:72:10' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF0,1-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'sendData',
    _lineNumber: '277',
    _columnNumber: '24',
    _msg: '    at sendData@/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-E,F01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.j,s',
    _functionName: '',
    _lineNumber: '325',
    _columnNumber: '17',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17' },
,  { _fileName: '/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer',
    _lineNumber: '251',
    _columnNu,mber: '9',
    _msg: '    at connectWithRetry/connectToPeer@/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9' },
  { _fileName: '/private/var/mobile/Con,tainers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer/</<',
    _lineNumber: '260',
    _columnNumber: '45',
    _msg: '    at conn,ectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/3F4DBEB3-EF01-4278-8589-6E1D5FB35197/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45' },
  { _fileName: 'timers.js',
    _functionName: 'listOnTimeout',
  ,  _lineNumber: '112',
    _columnNumber: '9',
    _msg: '    at listOnTimeout@timers.js:112:9' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber: 835,
    _columnNumber: 10,
    _msg: '    at ' },
  toString: [Function] ]
*,***TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
2015-12-07 18:48:43.985 ThaliTest[375:198535] Error!: connect EADDRNOTAVAIL
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg"
```
