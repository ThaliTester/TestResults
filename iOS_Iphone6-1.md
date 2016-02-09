#### Test 58135655e9e7eb8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655e9e7eb8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/A43BE7E9-8803-4881-9D65-FF19E30F0B3A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A43BE7E9-8803-4881-9D65-FF19E30F0B3A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655e9e7eb8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655e9e7eb8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53031"
,(lldb)     command script import "/tmp/A43BE7E9-8803-4881-9D65-FF19E30F0B3A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 13:36:46.691 ThaliTest[1620:2955451] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A86BCF1D-7FD9-42FB-B093-E631C88D928D/Library/Cookies/Cookies.binarycookies
,2016-02-09 13:36:47.083 ThaliTest[1620:2955451] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 13:36:47.085 ThaliTest[1620:2955451] Multi-tasking -> Device: YES, App: YES
,2016-02-09 13:36:47.095 ThaliTest[1620:2955451] Unlimited access to network resources
,2016-02-09 13:36:47.108 ThaliTest[1620:2955451] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 13:36:55.457 ThaliTest[1620:2955451] Resetting plugins due to page load.
,2016-02-09 13:36:58.871 ThaliTest[1620:2955451] Finished load of: file:///var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app/www/index.html
,2016-02-09 13:36:59.067 ThaliTest[1620:2955451] JXcore Cordova plugin initializing
2016-02-09 13:36:59.068 ThaliTest[1620:2955822] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!
,
,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507549F3-558E-4A66-98D8-DC6948978A0D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,appEnteringBackground wasn't registered

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

,# #start should fail if called twice in a row

,# teardown

,ok 54 specific error should be received

,# setup

,# #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 55 specific error should be returned

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,# setup

,# should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 58 error should be null

,ok 59 error should be null

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 60 error should be null

,ok 61 error should be null

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 62 specific error should be returned

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 13:41:43.795 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:43.811 ThaliTest[1620:2955822] server: starting 1455021703794.1620.2aAGkQ==
,2016-02-09 13:41:43.812 ThaliTest[1620:2955822] multipeer session: start timer: 0x18d06aa0
,2016-02-09 13:41:43.813 ThaliTest[1620:2955822] THEMultipeerSession initialized peer 1455021703794.1620
2016-02-09 13:41:43.813 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
,
,2016-02-09 13:41:43.817 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:41:43.818 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:41:43.818 ThaliTest[1620:2955822] multipeer session: stop timer
,2016-02-09 13:41:43.822 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error

2016-02-09 13:41:43.824 ThaliTest[1620:2955822] jxcore: startBroadcasting
2016-02-09 13:41:43.830 ThaliTest[1,620:2955822] server: starting 1455021703824.1620.URFZsw==
2016-02-09 13:41:43.831 ThaliTest[1620:2955822] multipeer session: start timer: 0x19d71730
2016-02-09 13:41:43.831 ThaliTest[1620:2955822] THEMultipeerSession initialized peer 1455021703824.1620
,2016-02-09 13:41:43.832 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-02-09 13:41:43.833 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:41:43.834 ThaliTest[,1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:41:43.834 ThaliTest[1620:2955822] multipeer session: stop timer
2016-02-09 13:41:43.834 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
ok 66 Should be able to call stopBroadcasting, without error

2016-02-09 13:41:43.843 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:43.850 ThaliTest[1620:2955822] server: starting 1455021703842.1620.DxovWg==
2016-02-09 13:41:43.851 ThaliTest[1620:2955822] multipeer session: start timer: 0x19d71710
2016-02-09 13:41:43.852 ThaliTest[1620:2955822] THEMultipeerSession in,itialized peer 1455021703842.1620
2016-02-09 13:41:43.853 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 67 Should be able to call startBroadcasting without error

2016-02-09 13:41:43.856 ThaliTest[1620:2955822] jxcore: stopBroadcasting,
2016-02-09 13:41:43.856 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:41:43.856 ThaliTest[1620:2955822] multipeer session: stop timer
2016-02-09 13:41:43.857 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
ok 68 Shou,ld be able to call stopBroadcasting without error

2016-02-09 13:41:43.859 ThaliTest[1620:2955822] jxcore: startBroadcasting
2016-02-09 13:41:43.865 ThaliTest[1620:2955822] server: starting 1455021703859.1620.iTCtGA==
,2016-02-09 13:41:43.870 ThaliTest[1620:2955822] multipeer session: start timer: 0x18e45b80
2016-02-09 13:41:43.871 ThaliTest[1620:2955822] THEMultipeerSession initialized peer 1455021703859.1620
2016-02-09 13:41:43.871 ThaliTest[1620:2955822] jxcore: sta,rtBroadcasting: success
ok 69 Should be able to call startBroadcasting without error

2016-02-09 13:41:43.874 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:41:43.874 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09, 13:41:43.874 ThaliTest[1620:2955822] multipeer session: stop timer
2016-02-09 13:41:43.875 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error

2016-02-09 13:41:43.877 ThaliTest[1620:29,55822] jxcore: startBroadcasting
2016-02-09 13:41:43.881 ThaliTest[1620:2955822] server: starting 1455021703876.1620.KpycRQ==
,2016-02-09 13:41:43.886 ThaliTest[1620:2955822] multipeer session: start timer: 0x19d73f90
2016-02-09 13:41:43.886 ThaliTest[1620:2955822] THEMultipeerSession initialized peer 1455021703876.1620
2016-02-09 13:41:43.887 ThaliTest[1620:2955822] jxcore: sta,rtBroadcasting: success
ok 71 Should be able to call startBroadcasting without error

2016-02-09 13:41:43.890 ThaliTest[1620:2955822] jxcore: stopBroadcasting
,2016-02-09 13:41:43.890 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:41:43.896 ThaliTest[1620:2955822] multipeer session: stop timer
2016-02-09 13:41:43.896 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
ok 72 Shoul,d be able to call stopBroadcasting without error

2016-02-09 13:41:43.898 ThaliTest[1620:2955822] jxcore: startBroadcasting
2016-02-09 13:41:43.905 ThaliTest[1620:2955822] server: starting 1455021703898.1620.ioTPnw==
,2016-02-09 13:41:43.909 ThaliTest[1620:2955822] multipeer session: start timer: 0x18e30290
2016-02-09 13:41:43.909 ThaliTest[1620:2955822] THEMultipeerSession initialized peer 1455021703898.1620
2016-02-09 13:41:43.910 ThaliTest[1620:2955822] jxcore: sta,rtBroadcasting: success
ok 73 Should be able to call startBroadcasting without error

2016-02-09 13:41:43.911 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:41:43.911 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09, 13:41:43.912 ThaliTest[1620:2955822] multipeer session: stop timer
,2016-02-09 13:41:43.912 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
ok 74 Should be able to call stopBroadcasting without error

2016-02-09 13:41:43.916 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:43.922 ThaliTest[1620:2955822] server: starting 1455021703916.1620.wLDBSA==
2016-02-09 13:41:43.922 ThaliTest[1620:2955822] multipeer session: start timer: 0x18e463e0
2016-02-09 13:41:43.923 ThaliTest[1620:2955822] THEMultipeerSession in,itialized peer 1455021703916.1620
2016-02-09 13:41:43.923 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 75 Should be able to call startBroadcasting without error

2016-02-09 13:41:43.924 ThaliTest[1620:2955822] jxcore: stopBroadcasting,
2016-02-09 13:41:43.924 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:41:43.924 ThaliTest[1620:2955822] multipeer session: stop timer
2016-02-09 13:41:43.925 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
ok 76 Shou,ld be able to call stopBroadcasting without error

2016-02-09 13:41:43.926 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:43.930 ThaliTest[1620:2955822] server: starting 1455021703926.1620.61l8Cw==
2016-02-09 13:41:43.931 ThaliTest[1620:2955822] multipeer session: start timer: 0x18e462e0
,2016-02-09 13:41:43.931 ThaliTest[1620:2955822] THEMultipeerSession initialized peer 1455021703926.1620
,2016-02-09 13:41:43.936 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error
,
,2016-02-09 13:41:43.945 ThaliTest[1620:2955822] jxcore: stopBroadcasting
,2016-02-09 13:41:43.947 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
,2016-02-09 13:41:43.949 ThaliTest[1620:2955822] multipeer session: stop timer
,2016-02-09 13:41:43.951 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-09 13:41:43.957 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:43.960 ThaliTest[1620:2955822] server: starting 1455021703956.1620.ooRkSg==
,2016-02-09 13:41:43.962 ThaliTest[1620:2955822] multipeer session: start timer: 0x18e46800
,2016-02-09 13:41:43.964 ThaliTest[1620:2955822] THEMultipeerSession initialized peer 1455021703956.1620
,2016-02-09 13:41:43.966 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 13:41:43.970 ThaliTest[1620:2955822] jxcore: stopBroadcasting
,2016-02-09 13:41:43.971 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
,2016-02-09 13:41:43.972 ThaliTest[1620:2955822] multipeer session: stop timer
,2016-02-09 13:41:43.973 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 13:41:43.978 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:43.981 ThaliTest[1620:2955822] server: starting 1455021703978.1620.DBO6Aw==
,2016-02-09 13:41:43.983 ThaliTest[1620:2955822] multipeer session: start timer: 0x18e46600
,2016-02-09 13:41:43.987 ThaliTest[1620:2955822] THEMultipeerSession initialized peer 1455021703978.1620
,2016-02-09 13:41:43.990 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 13:41:43.993 ThaliTest[1620:2955822] jxcore: stopBroadcasting
,2016-02-09 13:41:43.994 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
,2016-02-09 13:41:43.994 ThaliTest[1620:2955822] multipeer session: stop timer
,2016-02-09 13:41:43.995 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 13:41:44.195 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:44.199 ThaliTest[1620:2955822] server: starting 1455021704195.1620.hv4MWw==
2016-02-09 13:41:44.200 ThaliTest[1620:2955822] multipeer session: start timer: 0x19d79ce0
2016-02-09 13:41:44.200 ThaliTest[1620:2955822] THEMultipeerSession in,itialized peer 1455021704195.1620
2016-02-09 13:41:44.201 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-09 13:41:44.203 ThaliTest[1620:2955822] jxcore: startBroadcasting
2016-02-09 13:41:44.204 ThaliTest[1620:2955822] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

2016-02-09 13:41:44.208 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:41:44.209 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:41:44.209 ThaliTest[1620:2955822] multip,eer session: stop timer
2016-02-09 13:41:44.210 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
ok 85 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 13:41:44.673 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:44.677 ThaliTest[1620:2955822] server: starting 1455021704673.1620.ckWtkg==
2016-02-09 13:41:44.677 ThaliTest[1620:2955822] multipeer session: start timer: 0x18f452e0
2016-02-09 13:41:44.678 ThaliTest[1620:2955822] THEMultipeerSession in,itialized peer 1455021704673.1620
2016-02-09 13:41:44.679 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

2016-02-09 13:41:44.681 ThaliTest[1620:2955822] jxcore: connect foobar
2,016-02-09 13:41:44.682 ThaliTest[1620:2955822] client: unknown peer foobar
2016-02-09 13:41:44.682 ThaliTest[1620:2955822] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

2016-02-09 13:41:44.687 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:41:44.688 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:41:44.688 ThaliTest[1620:2955822] multipeer, session: stop timer
2016-02-09 13:41:44.688 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 13:41:45.714 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:45.718 ThaliTest[1620:2955822] server: starting 1455021705714.1620.YrNKaA==
2016-02-09 13:41:45.718 ThaliTest[1620:2955822] multipeer session: start timer: 0x18f29f10
2016-02-09 13:41:45.719 ThaliTest[1620:2955822] THEMultipeerSession in,itialized peer 1455021705714.1620
2016-02-09 13:41:45.720 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 89 Should be able to call startBroadcasting without error

,2016-02-09 13:41:45.722 ThaliTest[1620:2955822] jxcore: disconnect
,2016-02-09 13:41:45.723 ThaliTest[1620:2955822] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

,2016-02-09 13:41:45.736 ThaliTest[1620:2955822] jxcore: stopBroadcasting
,2016-02-09 13:41:45.738 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
,2016-02-09 13:41:45.739 ThaliTest[1620:2955822] multipeer session: stop timer
,2016-02-09 13:41:45.746 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 13:41:46.284 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:46.288 ThaliTest[1620:2955822] server: starting 1455021706284.1620.33VlJQ==
2016-02-09 13:41:46.288 ThaliTest[1620:2955822] multipeer session: start timer: 0x19d84a30
2016-02-09 13:41:46.289 ThaliTest[1620:2955822] THEMultipeerSession in,itialized peer 1455021706284.1620
2016-02-09 13:41:46.289 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-09 13:41:47.090 ThaliTest[1620:2955451] client: found peer: 1455021707778.1081.poBOdw==
,2016-02-09 13:41:47.093 ThaliTest[1620:2955822] jxcore: connect 1455021707778.1081.poBOdw==
2016-02-09 13:41:47.093 ThaliTest[1620:2955822] client session: connect
2016-02-09 13:41:47.094 ThaliTest[1620:2955822] client session: stateChange:0->1 1455021707778.1081.poBOdw==
,2016-02-09 13:41:47.816 ThaliTest[1620:2955451] multipeer session: reset timer
2016-02-09 13:41:47.816 ThaliTest[1620:2955451] multipeer session: stop timer
2016-02-09 13:41:47.816 ThaliTest[1620:2955451] multipeer session: start timer: 0x19d84a30
2016-,02-09 13:41:47.817 ThaliTest[1620:2955451] server session: connect
2016-02-09 13:41:47.817 ThaliTest[1620:2955451] server session: stateChange:0->1 1455021707778.1081
,2016-02-09 13:41:47.828 ThaliTest[1620:2955451] server: accepting invitation 1455021707778.1081
,2016-02-09 13:41:50.347 ThaliTest[1620:2956375] client session: connected
2016-02-09 13:41:50.348 ThaliTest[1620:2956375] client session: stateChange:1->2 1455021707778.1081.poBOdw==
,2016-02-09 13:41:50.363 ThaliTest[1620:2956374] client session: fireConnectCallback: 1455021707778.1081.poBOdw==
2016-02-09 13:41:50.364 ThaliTest[1620:2956374] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 13:41:50.369 ThaliTest[1620:2955822] jxcore: disconnect
2016-02-09 13:41:50.370 ThaliTest[1620:2955822] client session: disconnectFromPeer: 1455021707778.1081.poBOdw==
2016-02-09 13:41:50.370 ThaliTest[1620:2955822] client session: disconnect,
2016-02-09 13:41:50.370 ThaliTest[1620:2955822] client session: stateChange:2->0 1455021707778.1081.poBOdw==
,2016-02-09 13:41:50.383 ThaliTest[1620:2955822] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 13:41:50.565 ThaliTest[1620:2956375] server session: connected
2016-02-09 13:41:50.565 ThaliTest[1620:2956375] server session: stateChange:1->2 1455021707778.1081
,2016-02-09 13:41:50.572 ThaliTest[1620:2955451] server relay: socket disconnected
2016-02-09 13:41:50.572 ThaliTest[1620:2955451] server relay: 0x19d87f30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 13:41:50.620 ThaliTest[1620:2956369] server session: not connected 1455021707778.1081
,calling stopBroadcasting

,2016-02-09 13:41:51.135 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:41:51.136 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:41:51.136 ThaliTest[1620:2955822] multipeer session: stop timer
2016-02-09 13:41:51.,137 ThaliTest[1620:2955822] server session: disconnect
2016-02-09 13:41:51.137 ThaliTest[1620:2955822] server session: stateChange:2->0 1455021707778.1081
,2016-02-09 13:41:51.141 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 13:41:51.555 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:51.558 ThaliTest[1620:2955822] server: starting 1455021711554.1620.cVRjvg==
2016-02-09 13:41:51.559 ThaliTest[1620:2955822] multipeer session: start timer: 0x19d85460
2016-02-09 13:41:51.559 ThaliTest[1620:2955822] THEMultipeerSession in,itialized peer 1455021711554.1620
2016-02-09 13:41:51.560 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 96 Should be able to call startBroadcasting without error

,2016-02-09 13:41:53.247 ThaliTest[1620:2955451] client: found peer: 1455021713594.1081.S7JWnA==
2016-02-09 13:41:53.249 ThaliTest[1620:2955822] jxcore: connect 1455021713594.1081.S7JWnA==
2016-02-09 13:41:53.249 ThaliTest[1620:2955822] client session: co,nnect
2016-02-09 13:41:53.250 ThaliTest[1620:2955822] client session: stateChange:0->1 1455021713594.1081.S7JWnA==
,2016-02-09 13:41:53.323 ThaliTest[1620:2955451] multipeer session: reset timer
2016-02-09 13:41:53.324 ThaliTest[1620:2955451] multipeer session: stop timer
2016-02-09 13:41:53.324 ThaliTest[1620:2955451] multipeer session: start timer: 0x19d85460
2016-,02-09 13:41:53.325 ThaliTest[1620:2955451] server session: connect
2016-02-09 13:41:53.325 ThaliTest[1620:2955451] server session: stateChange:0->1 1455021713594.1081
,2016-02-09 13:41:53.334 ThaliTest[1620:2955451] server: accepting invitation 1455021713594.1081
,2016-02-09 13:41:55.948 ThaliTest[1620:2956374] server session: connected
2016-02-09 13:41:55.948 ThaliTest[1620:2956374] server session: stateChange:1->2 1455021713594.1081
,2016-02-09 13:41:55.989 ThaliTest[1620:2955451] server relay: socket disconnected
2016-02-09 13:41:55.990 ThaliTest[1620:2955451] server relay: 0x175fac10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 13:41:56.018 ThaliTest[1620:2956374] server session: not connected 1455021713594.1081
,2016-02-09 13:41:56.075 ThaliTest[1620:2956374] client session: connected
2016-02-09 13:41:56.075 ThaliTest[1620:2956374] client session: stateChange:1->2 1455021713594.1081.S7JWnA==
,2016-02-09 13:41:56.099 ThaliTest[1620:2956371] client session: fireConnectCallback: 1455021713594.1081.S7JWnA==
2016-02-09 13:41:56.099 ThaliTest[1620:2956371] jxcore: connect: success
ok 97 Should be able to connect without error

ok 98 Port should b,e within range

2016-02-09 13:41:56.103 ThaliTest[1620:2955822] jxcore: connect 1455021713594.1081.S7JWnA==
2016-02-09 13:41:56.103 ThaliTest[1620:2955822] client: already connect(ing/ed) to 1455021713594.1081.S7JWnA==
2016-02-09 13:41:56.103 ThaliTest,[1620:2955822] jxcore: connect: fail: Aleady connecting
ok 99 Should fail on double connect

,2016-02-09 13:41:56.107 ThaliTest[1620:2955822] jxcore: disconnect
,2016-02-09 13:41:56.107 ThaliTest[1620:2955822] client session: disconnectFromPeer: 1455021713594.1081.S7JWnA==
,2016-02-09 13:41:56.108 ThaliTest[1620:2955822] client session: disconnect
,2016-02-09 13:41:56.108 ThaliTest[1620:2955822] client session: stateChange:2->0 1455021713594.1081.S7JWnA==
,2016-02-09 13:41:56.185 ThaliTest[1620:2955822] jxcore: disconnect: success
ok 100 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 13:41:56.288 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:41:56.289 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:41:56.289 ThaliTest[1620:2955822] multipeer session: stop timer
2016-02-09 13:41:56.,289 ThaliTest[1620:2955822] server session: disconnect
2016-02-09 13:41:56.290 ThaliTest[1620:2955822] server session: stateChange:2->0 1455021713594.1081
2016-02-09 13:41:56.291 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 13:41:56.800 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:41:56.804 ThaliTest[1620:2955822] server: starting 1455021716800.1620.2qdl/g==
2016-02-09 13:41:56.805 ThaliTest[1620:2955822] multipeer session: start timer: 0x18d61d40
2016-02-09 13:41:56.805 ThaliTest[1620:2955822] THEMultipeerSession in,itialized peer 1455021716800.1620
2016-02-09 13:41:56.805 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-09 13:41:57.600 ThaliTest[1620:2955451] client: found peer: 1455021718319.1081.miCMOQ==
2016-02-09 13:41:57.602 ThaliTest[1620:2955822] jxcore: connect 1455021718319.1081.miCMOQ==
2016-02-09 13:41:57.603 ThaliTest[1620:2955822] client session: co,nnect
2016-02-09 13:41:57.603 ThaliTest[1620:2955822] client session: stateChange:0->1 1455021718319.1081.miCMOQ==
,2016-02-09 13:41:58.235 ThaliTest[1620:2955451] multipeer session: reset timer
2016-02-09 13:41:58.235 ThaliTest[1620:2955451] multipeer session: stop timer
2016-02-09 13:41:58.236 ThaliTest[1620:2955451] multipeer session: start timer: 0x18d61d40
2016-,02-09 13:41:58.236 ThaliTest[1620:2955451] server session: connect
2016-02-09 13:41:58.236 ThaliTest[1620:2955451] server session: stateChange:0->1 1455021718319.1081
,2016-02-09 13:41:58.245 ThaliTest[1620:2955451] server: accepting invitation 1455021718319.1081
,2016-02-09 13:42:00.719 ThaliTest[1620:2956374] client session: connected
2016-02-09 13:42:00.720 ThaliTest[1620:2956374] client session: stateChange:1->2 1455021718319.1081.miCMOQ==
,2016-02-09 13:42:00.732 ThaliTest[1620:2956374] client session: fireConnectCallback: 1455021718319.1081.miCMOQ==
2016-02-09 13:42:00.735 ThaliTest[1620:2956374] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-09 13:42:00.740 ThaliTest[1620:2955822] jxcore: disconnect
2016-02-09 13:42:00.740 ThaliTest[1620:2955822] client session: disconnectFromPeer: 1455021718319.1081.miCMOQ==
2016-02-09 13:42:00.741 ThaliTest[1620:2955822] client session: disconnect,
2016-02-09 13:42:00.741 ThaliTest[1620:2955822] client session: stateChange:2->0 1455021718319.1081.miCMOQ==
,2016-02-09 13:42:00.804 ThaliTest[1620:2956375] server session: connected
,2016-02-09 13:42:00.805 ThaliTest[1620:2956375] server session: stateChange:1->2 1455021718319.1081
,2016-02-09 13:42:00.828 ThaliTest[1620:2955822] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error

,2016-02-09 13:42:00.831 ThaliTest[1620:2955822] jxcore: disconnect
,2016-02-09 13:42:00.831 ThaliTest[1620:2955822] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

,setting stopBroadcasting callback and ending test.
,
,# setup

,2016-02-09 13:42:00.883 ThaliTest[1620:2956374] server session: not connected 1455021718319.1081
,calling stopBroadcasting

,2016-02-09 13:42:00.998 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:42:00.998 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:42:00.998 ThaliTest[1620:2955822] multipeer session: stop timer
2016-02-09 13:42:00.,999 ThaliTest[1620:2955822] server session: disconnect
2016-02-09 13:42:00.999 ThaliTest[1620:2955822] server session: stateChange:2->0 1455021718319.1081
,2016-02-09 13:42:01.416 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 59745

,2016-02-09 13:42:02.225 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:42:02.227 ThaliTest[1620:2955822] server: starting 1455021722225.1620.NsK3Lw==
2016-02-09 13:42:02.227 ThaliTest[1620:2955822] multipeer session: start timer: 0x19d85540
2016-02-09 13:42:02.228 ThaliTest[1620:2955822] THEMultipeerSession in,itialized peer 1455021722225.1620
2016-02-09 13:42:02.228 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 106 Should be able to call startBroadcasting without error

,2016-02-09 13:42:03.348 ThaliTest[1620:2955451] client: found peer: 1455021723663.1081.ObekEA==
2016-02-09 13:42:03.350 ThaliTest[1620:2955822] jxcore: connect 1455021723663.1081.ObekEA==
2016-02-09 13:42:03.350 ThaliTest[1620:2955822] client session: co,nnect
2016-02-09 13:42:03.351 ThaliTest[1620:2955822] client session: stateChange:0->1 1455021723663.1081.ObekEA==
,2016-02-09 13:42:03.416 ThaliTest[1620:2955451] multipeer session: reset timer
,2016-02-09 13:42:03.416 ThaliTest[1620:2955451] multipeer session: stop timer
2016-02-09 13:42:03.417 ThaliTest[1620:2955451] multipeer session: start timer: 0x19d85540
,2016-02-09 13:42:03.417 ThaliTest[1620:2955451] server session: connect
2016-02-09 13:42:03.418 ThaliTest[1620:2955451] server session: stateChange:0->1 1455021723663.1081
,2016-02-09 13:42:03.427 ThaliTest[1620:2955451] server: accepting invitation 1455021723663.1081
,2016-02-09 13:42:06.301 ThaliTest[1620:2956374] server session: connected
2016-02-09 13:42:06.302 ThaliTest[1620:2956374] server session: stateChange:1->2 1455021723663.1081
,2016-02-09 13:42:06.325 ThaliTest[1620:2955451] server relay: connected (to port: 59745)
,2016-02-09 13:42:06.823 ThaliTest[1620:2956374] server session: not connected 1455021723663.1081
,2016-02-09 13:42:07.663 ThaliTest[1620:2956367] client session: connected
,2016-02-09 13:42:07.663 ThaliTest[1620:2956367] client session: stateChange:1->2 1455021723663.1081.ObekEA==
,2016-02-09 13:42:07.727 ThaliTest[1620:2956374] client session: fireConnectCallback: 1455021723663.1081.ObekEA==
,2016-02-09 13:42:07.728 ThaliTest[1620:2956374] jxcore: connect: success
,ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 13:42:07.738 ThaliTest[1620:2955451] client: relay established
,2016-02-09 13:42:07.739 ThaliTest[1620:2955451] client: new accepted socket: 0x18e32d30
,data in 1095

,data in 2190

,data in 5262

,data in 32850
,
,data in 47186

,data in 75555

,data in 76650

,data in 88695

,data in 101835

,data in 111193

,data in 123735

,data in 125925

,data in 127020

,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 13:42:08.199 ThaliTest[1620:2955822] jxcore: disconnect
2016-02-09 13:42:08.199 ThaliTest[1620:2955822] client session: disconnectFromPeer: 1455021723663.1081.ObekEA==
2016-02-09 13:42:08.200 ThaliTest[1620:2955822] client session: disconnect,
2016-02-09 13:42:08.200 ThaliTest[1620:2955822] client session: stateChange:2->0 1455021723663.1081.ObekEA==
,2016-02-09 13:42:08.215 ThaliTest[1620:2955822] jxcore: disconnect: success
ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 13:42:08.328 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:42:08.328 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:42:08.328 ThaliTest[1620:2955822] multipeer session: stop timer
2016-02-09 13:42:08.,329 ThaliTest[1620:2955822] server session: disconnect
2016-02-09 13:42:08.329 ThaliTest[1620:2955822] server session: stateChange:2->0 1455021723663.1081
,2016-02-09 13:42:08.336 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 59751

,2016-02-09 13:42:08.929 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:42:08.933 ThaliTest[1620:2955822] server: starting 1455021728929.1620.Zh8/dA==
2016-02-09 13:42:08.934 ThaliTest[1620:2955822] multipeer session: start timer: 0x19d85540
2016-02-09 13:42:08.934 ThaliTest[1620:2955822] THEMultipeerSession in,itialized peer 1455021728929.1620
2016-02-09 13:42:08.934 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error

,2016-02-09 13:42:09.472 ThaliTest[1620:2955451] client: found peer: 1455021723663.1081.ObekEA==
[{"peerIdentifier":"1455021723663.1081.ObekEA==","peerName":"(null)","peerAvailable":true}]

2016-02-09 13:42:09.474 ThaliTest[1620:2955822] jxcore: connect ,1455021723663.1081.ObekEA==
2016-02-09 13:42:09.474 ThaliTest[1620:2955822] client session: connect
2016-02-09 13:42:09.475 ThaliTest[1620:2955822] client session: stateChange:0->1 1455021723663.1081.ObekEA==
,2016-02-09 13:42:10.019 ThaliTest[1620:2955451] client: found peer: 1455021730415.1081.TLIvfQ==
[{"peerIdentifier":"1455021730415.1081.TLIvfQ==","peerName":"(null)","peerAvailable":true}]

2016-02-09 13:42:10.022 ThaliTest[1620:2955822] jxcore: connect ,1455021730415.1081.TLIvfQ==
2016-02-09 13:42:10.022 ThaliTest[1620:2955822] client session: connect
2016-02-09 13:42:10.022 ThaliTest[1620:2955822] client session: stateChange:0->1 1455021730415.1081.TLIvfQ==
,2016-02-09 13:42:10.165 ThaliTest[1620:2955451] multipeer session: reset timer
2016-02-09 13:42:10.166 ThaliTest[1620:2955451] multipeer session: stop timer
,2016-02-09 13:42:10.166 ThaliTest[1620:2955451] multipeer session: start timer: 0x19d85540
,2016-02-09 13:42:10.168 ThaliTest[1620:2955451] server session: connect
2016-02-09 13:42:10.168 ThaliTest[1620:2955451] server session: stateChange:0->1 1455021730415.1081
,2016-02-09 13:42:10.177 ThaliTest[1620:2955451] server: accepting invitation 1455021730415.1081
,2016-02-09 13:42:11.667 ThaliTest[1620:2955451] client: lost peer: 1455021723663.1081.ObekEA==
2016-02-09 13:42:11.668 ThaliTest[1620:2955451] client session: onPeerLost: 1455021723663.1081.ObekEA==
2016-02-09 13:42:11.668 ThaliTest[1620:2955451] client ,session: onLinkFailure: 1455021723663.1081.ObekEA==
2016-02-09 13:42:11.668 ThaliTest[1620:2955451] client session: disconnect
2016-02-09 13:42:11.668 ThaliTest[1620:2955451] client session: stateChange:1->0 1455021723663.1081.ObekEA==
2016-02-09 13:42:,11.669 ThaliTest[1620:2955451] client session: fireConnectCallback: 1455021723663.1081.ObekEA==
2016-02-09 13:42:11.669 ThaliTest[1620:2955451] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1455021723663.1081.ObekEA==","peerName":"(null)","peerAvailable":false}]

,2016-02-09 13:42:12.677 ThaliTest[1620:2955822] jxcore: connect 1455021723663.1081.ObekEA==
2016-02-09 13:42:12.678 ThaliTest[1620:2955822] client: connect: unreachable 1455021723663.1081.ObekEA==
2016-02-09 13:42:12.678 ThaliTest[1620:2955822] jxcore: connect: fail: Peer unreachable
,2016-02-09 13:42:12.744 ThaliTest[1620:2956369] server session: connected
2016-02-09 13:42:12.745 ThaliTest[1620:2956369] server session: stateChange:1->2 1455021730415.1081
,2016-02-09 13:42:12.752 ThaliTest[1620:2955451] server relay: connected (to port: 59751)
,2016-02-09 13:42:12.789 ThaliTest[1620:2956375] client session: connected
,2016-02-09 13:42:12.789 ThaliTest[1620:2956375] client session: stateChange:1->2 1455021730415.1081.TLIvfQ==
,2016-02-09 13:42:12.811 ThaliTest[1620:2956367] client session: fireConnectCallback: 1455021730415.1081.TLIvfQ==
2016-02-09 13:42:12.811 ThaliTest[1620:2956367] jxcore: connect: success
,ok 112 Should be able to connect without error

,ok 113 Port should be within range

,ok 114 First connect should succeed

,2016-02-09 13:42:12.869 ThaliTest[1620:2955451] client: relay established
2016-02-09 13:42:12.870 ThaliTest[1620:2955451] client: new accepted socket: 0x18ae10f0
,ok 115 the test messages should be equal

,ok 116 First send should succeed

,2016-02-09 13:42:12.934 ThaliTest[1620:2955451] client: socket closed
2016-02-09 13:42:12.934 ThaliTest[1620:2955451] client relay: socket disconnected
2016-02-09 13:42:12.935 ThaliTest[1620:2955451] client relay: 0x18ae10f0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 13:42:12.935 ThaliTest[1620:2955451] client session: socket closed: 1455021730415.1081.TLIvfQ==
2016-02-09 ,13:42:12.935 ThaliTest[1620:2955451] client session: onLinkFailure: 1455021730415.1081.TLIvfQ==
2016-02-09 13:42:12.936 ThaliTest[1620:2955451] client session: disconnect
2016-02-09 13:42:12.936 ThaliTest[1620:2955451] client session: stateChange:2->0 14,55021730415.1081.TLIvfQ==
,2016-02-09 13:42:12.948 ThaliTest[1620:2955451] client session: fireConnectionErrorEvent: 1455021730415.1081.TLIvfQ==
,2016-02-09 13:42:12.953 ThaliTest[1620:2955822] jxcore: connect 1455021730415.1081.TLIvfQ==
,2016-02-09 13:42:12.963 ThaliTest[1620:2955822] client session: connect
,2016-02-09 13:42:12.971 ThaliTest[1620:2955822] client session: stateChange:0->1 1455021730415.1081.TLIvfQ==
,2016-02-09 13:42:12.988 ThaliTest[1620:2956371] server session: not connected 1455021730415.1081
,2016-02-09 13:42:13.007 ThaliTest[1620:2955451] multipeer session: reset timer
2016-02-09 13:42:13.009 ThaliTest[1620:2955451] multipeer session: stop timer
2016-02-09 13:42:13.009 ThaliTest[1620:2955451] multipeer session: start timer: 0x19d85540
2016-,02-09 13:42:13.010 ThaliTest[1620:2955451] server: disconnecting to refresh session (1455021730415.1081)
2016-02-09 13:42:13.010 ThaliTest[1620:2955451] server session: disconnect
2016-02-09 13:42:13.010 ThaliTest[1620:2955451] server session: stateChang,e:2->0 1455021730415.1081
,2016-02-09 13:42:13.015 ThaliTest[1620:2955451] server session: connect
,2016-02-09 13:42:13.015 ThaliTest[1620:2955451] server session: stateChange:0->1 1455021730415.1081
,2016-02-09 13:42:13.035 ThaliTest[1620:2955451] server: accepting invitation 1455021730415.1081
,2016-02-09 13:42:15.621 ThaliTest[1620:2956369] server session: connected
2016-02-09 13:42:15.622 ThaliTest[1620:2956369] server session: stateChange:1->2 1455021730415.1081
,2016-02-09 13:42:15.627 ThaliTest[1620:2955451] server relay: connected (to port: 59751)
,2016-02-09 13:42:15.747 ThaliTest[1620:2956375] client session: connected
2016-02-09 13:42:15.748 ThaliTest[1620:2956375] client session: stateChange:1->2 1455021730415.1081.TLIvfQ==
,2016-02-09 13:42:15.765 ThaliTest[1620:2956371] client session: fireConnectCallback: 1455021730415.1081.TLIvfQ==
2016-02-09 13:42:15.766 ThaliTest[1620:2956371] jxcore: connect: success
,ok 117 Should be able to connect without error

,ok 118 Port should be within range

ok 119 Second connect should succeed

,2016-02-09 13:42:15.798 ThaliTest[1620:2956371] server session: not connected 1455021730415.1081
,2016-02-09 13:42:15.807 ThaliTest[1620:2955451] client: relay established
2016-02-09 13:42:15.807 ThaliTest[1620:2955451] client: new accepted socket: 0x19d87130
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,# setup

,2016-02-09 13:42:15.899 ThaliTest[1620:2955451] client: socket closed
2016-02-09 13:42:15.899 ThaliTest[1620:2955451] client relay: socket disconnected
2016-02-09 13:42:15.900 ThaliTest[1620:2955451] client relay: 0x19d87130 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 13:42:15.900 ThaliTest[1620:2955451] client session: socket closed: 1455021730415.1081.TLIvfQ==
2016-02-09 ,13:42:15.900 ThaliTest[1620:2955451] client session: onLinkFailure: 1455021730415.1081.TLIvfQ==
2016-02-09 13:42:15.900 ThaliTest[1620:2955451] client session: disconnect
2016-02-09 13:42:15.901 ThaliTest[1620:2955451] client session: stateChange:2->0 14,55021730415.1081.TLIvfQ==
,2016-02-09 13:42:15.913 ThaliTest[1620:2955451] client session: fireConnectionErrorEvent: 1455021730415.1081.TLIvfQ==
,calling stopBroadcasting

,2016-02-09 13:42:16.194 ThaliTest[1620:2955822] jxcore: stopBroadcasting
,2016-02-09 13:42:16.195 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
,2016-02-09 13:42:16.196 ThaliTest[1620:2955822] multipeer session: stop timer
,2016-02-09 13:42:16.215 ThaliTest[1620:2955822] server session: disconnect
,2016-02-09 13:42:16.217 ThaliTest[1620:2955822] server session: stateChange:2->0 1455021730415.1081
,2016-02-09 13:42:16.292 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A86BCF1D-7FD9-42FB-B093-E631C88D928D/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 122 starting event should occur in right order

,2016-02-09 13:42:16.751 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:42:16.753 ThaliTest[1620:2955822] server: starting bKW0MF74g-13gggg2lZtCg.N68tJA==
,2016-02-09 13:42:16.754 ThaliTest[1620:2955822] multipeer session: start timer: 0x19a520b0
,2016-02-09 13:42:16.757 ThaliTest[1620:2955822] THEMultipeerSession initialized peer bKW0MF74g-13gggg2lZtCg
,2016-02-09 13:42:16.758 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
,ok 123 started event should occur in right order

,Now in TRM stop
,
,State of this._isStarted: true

,ok 124 stopping event should occur in right order

,About to call stopBroadcasting

,2016-02-09 13:42:16.760 ThaliTest[1620:2955822] jxcore: stopBroadcasting
,2016-02-09 13:42:16.761 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
,2016-02-09 13:42:16.761 ThaliTest[1620:2955822] multipeer session: stop timer
,2016-02-09 13:42:16.762 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 125 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A86BCF1D-7FD9-42FB-B093-E631C88D928D/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 13:42:17.193 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:42:17.197 ThaliTest[1620:2955822] server: starting bKW0MF74g-13gggg2lZtCg.84UkVQ==
2016-02-09 13:42:17.198 ThaliTest[1620:2955822] multipeer session: start timer: 0x19838c00
2016-02-09 13:42:17.198 ThaliTest[1620:2955822] THEMultipeerSessio,n initialized peer bKW0MF74g-13gggg2lZtCg
2016-02-09 13:42:17.198 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 126 getDeviceIdentity should not return an error

ok 127 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

,2016-02-09 13:42:17.202 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:42:17.202 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:42:17.202 ThaliTest[1620:2955822] multipeer session: stop timer
,2016-02-09 13:42:17.204 ThaliTest[1620:2955822] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/A86BCF1D-7FD9-42FB-B093-E631C88D928D/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 13:42:19.349 ThaliTest[1620:2955822] jxcore: startBroadcasting
,2016-02-09 13:42:19.351 ThaliTest[1620:2955822] server: starting bKW0MF74g-13gggg2lZtCg.dhRfRQ==
2016-02-09 13:42:19.351 ThaliTest[1620:2955822] multipeer session: start timer: 0x18ca0920
2016-02-09 13:42:19.351 ThaliTest[1620:2955822] THEMultipeerSession initialized peer bKW0MF74g-13gggg2lZtCg
2016-02-09 13:42:19.351 ThaliTest[1620:2955822] jxcore: startBroadcasting: success
ok 128 getDeviceIdentity should not return an error

ok 129 deviceName should not be null

,2016-02-09 13:42:20.096 ThaliTest[1620:2955451] client: found peer: 1455021730415.1081.TLIvfQ==
,2016-02-09 13:42:23.944 ThaliTest[1620:2955451] client: found peer: 2HEd01SRKhm8KBSuSAzcIg.fWNtwg==
,2016-02-09 13:42:23.967 ThaliTest[1620:2955822] jxcore: connect 1455021730415.1081.TLIvfQ==
2016-02-09 13:42:23.968 ThaliTest[1620:2955822] client session: connect
2016-02-09 13:42:23.968 ThaliTest[1620:2955822] client session: stateChange:0->1 1455021730415.1081.TLIvfQ==
,2016-02-09 13:42:23.976 ThaliTest[1620:2955822] jxcore: connect 2HEd01SRKhm8KBSuSAzcIg.fWNtwg==
2016-02-09 13:42:23.977 ThaliTest[1620:2955822] client session: connect
2016-02-09 13:42:23.977 ThaliTest[1620:2955822] client session: stateChange:0->1 2HEd01SRKhm8KBSuSAzcIg.fWNtwg==
,2016-02-09 13:42:23.988 ThaliTest[1620:2955451] multipeer session: reset timer
2016-02-09 13:42:23.988 ThaliTest[1620:2955451] multipeer session: stop timer
2016-02-09 13:42:23.988 ThaliTest[1620:2955451] multipeer session: start timer: 0x18ca0920
2016-02-09 13:42:23.989 ThaliTest[1620:2955451] server session: connect
,2016-02-09 13:42:23.989 ThaliTest[1620:2955451] server session: stateChange:0->1 2HEd01SRKhm8KBSuSAzcIg
,2016-02-09 13:42:23.993 ThaliTest[1620:2955451] server: accepting invitation 2HEd01SRKhm8KBSuSAzcIg
,ok 130 Should be able to put doc without error
,
,ok 131 1st change of local doc should contain local id

,2016-02-09 13:42:24.358 ThaliTest[1620:2955451] client: lost peer: 1455021730415.1081.TLIvfQ==
2016-02-09 13:42:24.358 ThaliTest[1620:2955451] client session: onPeerLost: 1455021730415.1081.TLIvfQ==
2016-02-09 13:42:24.358 ThaliTest[1620:2955451] client ,session: onLinkFailure: 1455021730415.1081.TLIvfQ==
2016-02-09 13:42:24.358 ThaliTest[1620:2955451] client session: disconnect
2016-02-09 13:42:24.359 ThaliTest[1620:2955451] client session: stateChange:1->0 1455021730415.1081.TLIvfQ==
2016-02-09 13:42:,24.359 ThaliTest[1620:2955451] client session: fireConnectCallback: 1455021730415.1081.TLIvfQ==
2016-02-09 13:42:24.359 ThaliTest[1620:2955451] jxcore: connect: fail: Peer disconnected
,Connect error with error: Error: Peer disconnected

,2016-02-09 13:42:24.375 ThaliTest[1620:2955822] jxcore: disconnect
,2016-02-09 13:42:24.376 ThaliTest[1620:2955822] jxcore: disconnect: fail
,Disconnect error with error: Error: Not connected to specified peer

peerIdentifier not available 1455021730415.1081.TLIvfQ==
,
,2016-02-09 13:42:26.534 ThaliTest[1620:2956375] server session: connected
2016-02-09 13:42:26.535 ThaliTest[1620:2956375] server session: stateChange:1->2 2HEd01SRKhm8KBSuSAzcIg
,2016-02-09 13:42:26.565 ThaliTest[1620:2955451] server relay: connected (to port: 59767)
,server bridge: new client socket

,2016-02-09 13:42:26.914 ThaliTest[1620:2956375] client session: connected
2016-02-09 13:42:26.914 ThaliTest[1620:2956375] client session: stateChange:1->2 2HEd01SRKhm8KBSuSAzcIg.fWNtwg==
,2016-02-09 13:42:26.936 ThaliTest[1620:2956369] client session: fireConnectCallback: 2HEd01SRKhm8KBSuSAzcIg.fWNtwg==
2016-02-09 13:42:26.937 ThaliTest[1620:2956369] jxcore: connect: success
,2016-02-09 13:42:26.944 ThaliTest[1620:2955451] client: relay established
2016-02-09 13:42:26.944 ThaliTest[1620:2955451] client: new accepted socket: 0x19d59e20
,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

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
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: socket closed

,client bridge: new client socket

,ok 132 1st change of remote doc should contain remote id

,ok 133 Can update remote doc without error
,
,null

,{ ok: true,
  id: 'dea43ae9-4a3c-41d5-92cd-3c62655e1864',
  rev: '2-555345f6b2635984eea37400f89646c3' }

,client bridge: new client socket
,
,ok 134 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
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
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,ok 135 Local changes occur in strict order

,ok 136 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,Now in TRM stop

State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-09 13:42:45.615 ThaliTest[1620:2955822] jxcore: stopBroadcasting
2016-02-09 13:42:45.615 ThaliTest[1620:2955822] THEMultipeerSession stopping peer
2016-02-09 13:42:45.615 ThaliTest[1620:2955822] multipeer session: stop timer
2016-02-09 13:42:45.,616 ThaliTest[1620:2955822] client session: disconnect
2016-02-09 13:42:45.616 ThaliTest[1620:2955822] client session: stateChange:2->0 2HEd01SRKhm8KBSuSAzcIg.fWNtwg==
,2016-02-09 13:42:45.637 ThaliTest[1620:2956506] server session: not connected 2HEd01SRKhm8KBSuSAzcIg
,2016-02-09 13:42:45.702 ThaliTest[1620:2956507] client session: not connected 2HEd01SRKhm8KBSuSAzcIg.fWNtwg==
,2016-02-09 13:42:45.788 ThaliTest[1620:2955822] server session: disconnect
2016-02-09 13:42:45.789 ThaliTest[1620:2956507] client session: onLinkFailure: 2HEd01SRKhm8KBSuSAzcIg.fWNtwg==
Assertion failed: ([self connectionState] != THEPeerSessionStateNotC,onnected), function -[THEMultipeerClientSession onLinkFailure], file /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClientSession.m, line 124.
,* thread #1: tid = 0x2d18bb, 0x38fb3fbc libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x38fb3fbc libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x38fb3dbc libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x26d3f48c CoreFoundation`<redacted> + 136
    frame #3: 0x26d3d812 CoreFoundation`<redacted> + 1050
    frame #4: 0x26c900d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #5: 0x26c8fecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #6: 0x2ffc5af8 GraphicsServices`GSEventRunModal + 160
    frame #7: 0x2af192dc UIKit`UIApplicationMain + 144
    frame #8: 0x000671f2 ThaliTest`main + 50

```
