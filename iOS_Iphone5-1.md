#### Test 506502785032ad1_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0DA38547-F9CD-4ED3-8765-8C2200E4C5A8/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/0DA38547-F9CD-4ED3-8765-8C2200E4C5A8/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/41BCAEF1-1844-4290-BD3A-423E93886527/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50466"
,(lldb)     command script import "/tmp/0DA38547-F9CD-4ED3-8765-8C2200E4C5A8/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 03:53:38.043 ThaliTest[391:256944] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1B260CF2-380B-4064-A67C-AAF30A81BA98/Library/Cookies/Cookies.binarycookies
,2015-12-08 03:53:38.176 ThaliTest[391:256944] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 03:53:38.177 ThaliTest[391:256944] Multi-tasking -> Device: YES, App: YES
,2015-12-08 03:53:38.184 ThaliTest[391:256944] Unlimited access to network resources
,2015-12-08 03:53:38.199 ThaliTest[391:256944] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 03:53:49.431 ThaliTest[391:256944] Resetting plugins due to page load.
,2015-12-08 03:53:53.982 ThaliTest[391:256944] Finished load of: file:///var/mobile/Containers/Bundle/Application/41BCAEF1-1844-4290-BD3A-423E93886527/ThaliTest.app/www/index.html
,2015-12-08 03:53:54.205 ThaliTest[391:256944] JXcore Cordova plugin initializing
,2015-12-08 03:53:54.206 ThaliTest[391:257129] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,2015-12-08 03:56:43.582 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:43.832 ThaliTest[391:257129] server: starting 1449543403581.391.DGRFZw==
,2015-12-08 03:56:43.833 ThaliTest[391:257129] multipeer session: start timer: 0x1c049d50
,2015-12-08 03:56:43.833 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543403581.391
,2015-12-08 03:56:43.834 ThaliTest[391:257129] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2015-12-08 03:56:43.835 ThaliTest[391:257129] jxcore: stopBroadcasting
2015-12-08 03:56:43.836 ThaliTest[391:257129] THEMultipeerSession stopping peer
2015-12-08 03:56:43.836 ThaliTest[391:257129] multipeer session: stop timer
2015-12-08 03:56:43.836 Th,aliTest[391:257129] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:43.838 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:43.842 ThaliTest[391:257129] server: starting 1449543403837.391.sDsskQ==
2015-12-08 03:56:43.843 ThaliTest[391:257129] multipeer session: start timer: 0x197e3aa0
2015-12-08 03:56:43.843 ThaliTest[391:257129] THEMultipeerSession initializ,ed peer 1449543403837.391
2015-12-08 03:56:43.845 ThaliTest[391:257129] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-08 03:56:43.846 ThaliTest[391:257129] jxcore: stopBroadcasting
2015-12-08 03,:56:43.847 ThaliTest[391:257129] THEMultipeerSession stopping peer
2015-12-08 03:56:43.847 ThaliTest[391:257129] multipeer session: stop timer
2015-12-08 03:56:43.847 ThaliTest[391:257129] jxcore: stopBroadcasting: success
ok 48 Should be able to call s,topBroadcasting without error
2015-12-08 03:56:43.849 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:43.863 ThaliTest[391:257129] server: starting 1449543403848.391.3zzhYg==
,2015-12-08 03:56:43.868 ThaliTest[391:257129] multipeer session: start timer: 0x145ad980
,2015-12-08 03:56:43.872 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543403848.391
,2015-12-08 03:56:43.873 ThaliTest[391:257129] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2015-12-08 03:56:43.875 ThaliTest[391:257129] jxcore: stopBroadcasting
2015-12-08 03:56:43.876 ThaliTest[391:257129] THEMultipeerSession stopping peer
,2015-12-08 03:56:43.876 ThaliTest[391:257129] multipeer session: stop timer
,2015-12-08 03:56:43.878 ThaliTest[391:257129] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:43.885 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:43.888 ThaliTest[391:257129] server: starting 1449543403884.391.jjvYJw==
,2015-12-08 03:56:43.891 ThaliTest[391:257129] multipeer session: start timer: 0x146761f0
,2015-12-08 03:56:43.895 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543403884.391
,2015-12-08 03:56:43.897 ThaliTest[391:257129] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2015-12-08 03:56:43.900 ThaliTest[391:257129] jxcore: stopBroadcasting
,2015-12-08 03:56:43.901 ThaliTest[391:257129] THEMultipeerSession stopping peer
,2015-12-08 03:56:43.903 ThaliTest[391:257129] multipeer session: stop timer
,2015-12-08 03:56:43.907 ThaliTest[391:257129] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:43.910 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:43.914 ThaliTest[391:257129] server: starting 1449543403910.391.9UjrLg==
,2015-12-08 03:56:43.917 ThaliTest[391:257129] multipeer session: start timer: 0x1c04b420
,2015-12-08 03:56:43.921 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543403910.391
,2015-12-08 03:56:43.923 ThaliTest[391:257129] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-08 03:56:43.926 ThaliTest[391:257129] jxcore: stopBroadcasting
,2015-12-08 03:56:43.927 ThaliTest[391:257129] THEMultipeerSession stopping peer
,2015-12-08 03:56:43.928 ThaliTest[391:257129] multipeer session: stop timer
,2015-12-08 03:56:43.932 ThaliTest[391:257129] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:43.936 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:43.941 ThaliTest[391:257129] server: starting 1449543403936.391.T7OQfA==
,2015-12-08 03:56:43.953 ThaliTest[391:257129] multipeer session: start timer: 0x14596c30
,2015-12-08 03:56:43.958 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543403936.391
,2015-12-08 03:56:43.958 ThaliTest[391:257129] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-08 03:56:43.962 ThaliTest[391:257129] jxcore: stopBroadcasting
,2015-12-08 03:56:43.963 ThaliTest[391:257129] THEMultipeerSession stopping peer
,2015-12-08 03:56:43.965 ThaliTest[391:257129] multipeer session: stop timer
,2015-12-08 03:56:43.972 ThaliTest[391:257129] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:43.977 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:43.980 ThaliTest[391:257129] server: starting 1449543403976.391.V8Y36Q==
,2015-12-08 03:56:43.981 ThaliTest[391:257129] multipeer session: start timer: 0x14699700
,2015-12-08 03:56:43.984 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543403976.391
,2015-12-08 03:56:43.986 ThaliTest[391:257129] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-08 03:56:43.997 ThaliTest[391:257129] jxcore: stopBroadcasting
,2015-12-08 03:56:43.998 ThaliTest[391:257129] THEMultipeerSession stopping peer
,2015-12-08 03:56:43.999 ThaliTest[391:257129] multipeer session: stop timer
,2015-12-08 03:56:44.000 ThaliTest[391:257129] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.005 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:44.008 ThaliTest[391:257129] server: starting 1449543404005.391.tOwIHQ==
,2015-12-08 03:56:44.010 ThaliTest[391:257129] multipeer session: start timer: 0x1465a700
,2015-12-08 03:56:44.012 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543404005.391
,2015-12-08 03:56:44.017 ThaliTest[391:257129] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.021 ThaliTest[391:257129] jxcore: stopBroadcasting
,2015-12-08 03:56:44.022 ThaliTest[391:257129] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.023 ThaliTest[391:257129] multipeer session: stop timer
,2015-12-08 03:56:44.024 ThaliTest[391:257129] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.030 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:44.033 ThaliTest[391:257129] server: starting 1449543404030.391.otDpDA==
,2015-12-08 03:56:44.035 ThaliTest[391:257129] multipeer session: start timer: 0x146990a0
,2015-12-08 03:56:44.041 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543404030.391
,2015-12-08 03:56:44.042 ThaliTest[391:257129] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.047 ThaliTest[391:257129] jxcore: stopBroadcasting
,2015-12-08 03:56:44.047 ThaliTest[391:257129] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.049 ThaliTest[391:257129] multipeer session: stop timer
,2015-12-08 03:56:44.050 ThaliTest[391:257129] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.056 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:44.059 ThaliTest[391:257129] server: starting 1449543404056.391.2iVG6w==
,2015-12-08 03:56:44.060 ThaliTest[391:257129] multipeer session: start timer: 0x197e18f0
,2015-12-08 03:56:44.063 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543404056.391
,2015-12-08 03:56:44.065 ThaliTest[391:257129] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.073 ThaliTest[391:257129] jxcore: stopBroadcasting
,2015-12-08 03:56:44.074 ThaliTest[391:257129] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.075 ThaliTest[391:257129] multipeer session: stop timer
,2015-12-08 03:56:44.076 ThaliTest[391:257129] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-08 03:56:47.366 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:47.369 ThaliTest[391:257129] server: starting 1449543407365.391.fKnHSA==
2015-12-08 03:56:47.369 ThaliTest[391:257129] multipeer session: start timer: 0x197e5620
2015-12-08 03:56:47.369 ThaliTest[391:257129] THEMultipeerSession initializ,ed peer 1449543407365.391
2015-12-08 03:56:47.370 ThaliTest[391:257129] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
,2015-12-08 03:56:47.371 ThaliTest[391:257129] jxcore: startBroadcasting
2015-12-08 03:56:47.371 ThaliTest[391:257129] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2015-12-08 03:56:47.373 ThaliTest[391:257129] jxcore: stopBroadcasting
2015-12-08 03:56:47.373 ThaliTest[391:257129] THEMultipeerSession stopping peer
2015-12-08 03:56:47.374 ThaliTest[391:257129] multipeer sess,ion: stop timer
2015-12-08 03:56:47.374 ThaliTest[391:257129] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-08 03:56:52.113 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:52.115 ThaliTest[391:257129] server: starting 1449543412112.391.5d1S1Q==
2015-12-08 03:56:52.116 ThaliTest[391:257129] multipeer session: start timer: 0x1c052ab0
2015-12-08 03:56:52.116 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543412112.391
2015-12-08 03:56:52.116 ThaliTest[391:257129] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-08 03:56:52.118 ThaliTest[391:257129] jxcore: connect foobar
2015-12-08 03:5,6:52.118 ThaliTest[391:257129] client: unknown peer foobar
2015-12-08 03:56:52.118 ThaliTest[391:257129] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2015-12-08 03:56:52.119 ThaliTest[391:257129] jxcore: stopBroadcasting
2,015-12-08 03:56:52.120 ThaliTest[391:257129] THEMultipeerSession stopping peer
2015-12-08 03:56:52.120 ThaliTest[391:257129] multipeer session: stop timer
2015-12-08 03:56:52.120 ThaliTest[391:257129] jxcore: stopBroadcasting: success
ok 70 Should be ab,le to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-08 03:56:55.893 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:56:55.896 ThaliTest[391:257129] server: starting 1449543415893.391.2JTxCw==
2015-12-08 03:56:55.896 ThaliTest[391:257129] multipeer session: start timer: 0x197ecff0
2015-12-08 03:56:55.896 ThaliTest[391:257129] THEMultipeerSession initializ,ed peer 1449543415893.391
2015-12-08 03:56:55.897 ThaliTest[391:257129] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-08 03:56:55.898 ThaliTest[391:257129] jxcore: disconnect
2015-12-08 03:56:55,.898 ThaliTest[391:257129] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2015-12-08 03:56:55.900 ThaliTest[391:257129] jxcore: stopBroadcasting
2015-12-08 03:56:55.900 ThaliTest[391:257129] THEMultipeerSession stopping pe,er
2015-12-08 03:56:55.900 ThaliTest[391:257129] multipeer session: stop timer
2015-12-08 03:56:55.900 ThaliTest[391:257129] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-08 03:57:01.261 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:57:01.264 ThaliTest[391:257129] server: starting 1449543421260.391.hpKQLw==
,2015-12-08 03:57:01.267 ThaliTest[391:257129] multipeer session: start timer: 0x197ee6a0
,2015-12-08 03:57:01.269 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543421260.391
,2015-12-08 03:57:01.277 ThaliTest[391:257129] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2015-12-08 03:57:02.461 ThaliTest[391:256944] client: found peer: 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:02.463 ThaliTest[391:257129] jxcore: connect 1449543422873.405.4eQM3Q==
2015-12-08 03:57:02.464 ThaliTest[391:257129] client session: connect
2015-12-08 03:57:02.464 ThaliTest[391:257129] client session: stateChange:0->1 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:03.024 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:57:03.024 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:57:03.024 ThaliTest[391:256944] multipeer session: start timer: 0x197ee6a0
2015-12-08 ,03:57:03.024 ThaliTest[391:256944] server session: connect
2015-12-08 03:57:03.024 ThaliTest[391:256944] server session: stateChange:0->1 1449543422873.405
,2015-12-08 03:57:03.030 ThaliTest[391:256944] server: accepting invitation 1449543422873.405
,2015-12-08 03:57:03.283 ThaliTest[391:256944] client: found peer: 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:03.286 ThaliTest[391:257129] jxcore: connect 1449543421775.439.IbqVaQ==
2015-12-08 03:57:03.287 ThaliTest[391:257129] client session: connect
2015-12-08 03:57:03.287 ThaliTest[391:257129] client session: stateChange:0->1 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:04.135 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:57:04.136 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:57:04.137 ThaliTest[391:256944] multipeer session: start timer: 0x197ee6a0
2015-12-08 ,03:57:04.137 ThaliTest[391:256944] server session: connect
2015-12-08 03:57:04.137 ThaliTest[391:256944] server session: stateChange:0->1 1449543421593.431
2015-12-08 03:57:04.146 ThaliTest[391:256944] server: accepting invitation 1449543421593.431
,2015-12-08 03:57:05.122 ThaliTest[391:256944] client: found peer: 1449543421593.431.+h1/ug==
2015-12-08 03:57:05.124 ThaliTest[391:257129] jxcore: connect 1449543421593.431.+h1/ug==
2015-12-08 03:57:05.124 ThaliTest[391:257129] client session: connect
2015-12-08 03:57:05.124 ThaliTest[391:257129] client session: stateChange:0->1 1449543421593.431.+h1/ug==
,2015-12-08 03:57:05.536 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:57:05.537 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:57:05.538 ThaliTest[391:256944] multipeer session: start timer: 0x197ee6a0
,2015-12-08 03:57:05.539 ThaliTest[391:256944] server session: connect
,2015-12-08 03:57:05.540 ThaliTest[391:256944] server session: stateChange:0->1 1449543421775.439
,2015-12-08 03:57:05.547 ThaliTest[391:256944] server: accepting invitation 1449543421775.439
,2015-12-08 03:57:06.236 ThaliTest[391:257480] server session: connected
2015-12-08 03:57:06.236 ThaliTest[391:257480] server session: stateChange:1->2 1449543422873.405
,2015-12-08 03:57:06.265 ThaliTest[391:257562] server session: not connected 1449543422873.405
,2015-12-08 03:57:06.762 ThaliTest[391:257563] client session: connected
2015-12-08 03:57:06.762 ThaliTest[391:257563] client session: stateChange:1->2 1449543422873.405.4eQM3Q==
2015-12-08 03:57:06.767 ThaliTest[391:257563] client session: fireConnectCal,lback: 1449543422873.405.4eQM3Q==
2015-12-08 03:57:06.767 ThaliTest[391:257563] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
2015-12-08 03:57:06.770 ThaliTest[391:257129] jxcore: disconnect
2,015-12-08 03:57:06.770 ThaliTest[391:257129] client session: disconnectFromPeer: 1449543422873.405.4eQM3Q==
2015-12-08 03:57:06.770 ThaliTest[391:257129] client session: disconnect
2015-12-08 03:57:06.770 ThaliTest[391:257129] client session: stateChange:2->0 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:06.778 ThaliTest[391:257129] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-08 03:57:08.169 ThaliTest[391:257480] client session: connected
2015-12-08 03:57:08.170 ThaliTest[391:257480] client session: stateChange:1->2 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:08.652 ThaliTest[391:257562] server session: connected
2015-12-08 03:57:08.652 ThaliTest[391:257562] server session: stateChange:1->2 1449543421593.431
,2015-12-08 03:57:08.655 ThaliTest[391:256944] server relay: socket disconnected
2015-12-08 03:57:08.655 ThaliTest[391:256944] server relay: 0x1c062d70 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:08.750 ThaliTest[391:257478] server session: not connected 1449543421593.431
,2015-12-08 03:57:08.775 ThaliTest[391:257562] server session: connected
2015-12-08 03:57:08.775 ThaliTest[391:257562] server session: stateChange:1->2 1449543421775.439
,2015-12-08 03:57:08.779 ThaliTest[391:256944] server relay: socket disconnected
2015-12-08 03:57:08.779 ThaliTest[391:256944] server relay: 0x1c063100 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:08.863 ThaliTest[391:257545] server session: not connected 1449543421775.439
,2015-12-08 03:57:09.117 ThaliTest[391:257545] client session: fireConnectCallback: 1449543421775.439.IbqVaQ==
2015-12-08 03:57:09.117 ThaliTest[391:257545] jxcore: connect: success
ok 78 Should be able to connect without error
,ok 79 Port should be within range
,2015-12-08 03:57:09.121 ThaliTest[391:257129] jxcore: disconnect
2015-12-08 03:57:09.121 ThaliTest[391:257129] client session: disconnectFromPeer: 1449543421775.439.IbqVaQ==
2015-12-08 03:57:09.121 ThaliTest[391:257129] client session: disconnect
2015-12-08 03:57:09.121 ThaliTest[391:257129] client session: stateChange:2->0 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:09.197 ThaliTest[391:257129] jxcore: disconnect: success
ok 80 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,not ok 81 .end() called twice
,  ---
,    operator: fail
  ...
,2015-12-08 03:57:09.272 ThaliTest[391:257545] client session: connected
2015-12-08 03:57:09.272 ThaliTest[391:257545] client session: stateChange:1->2 1449543421593.431.+h1/ug==
2015-12-08 03:57:09.276 ThaliTest[391:257545] client session: fireConnectCal,lback: 1449543421593.431.+h1/ug==
2015-12-08 03:57:09.276 ThaliTest[391:257545] jxcore: connect: success
ok 82 Should be able to connect without error
ok 83 Port should be within range
2015-12-08 03:57:09.278 ThaliTest[391:257129] jxcore: disconnect
2,015-12-08 03:57:09.279 ThaliTest[391:257129] client session: disconnectFromPeer: 1449543421593.431.+h1/ug==
2015-12-08 03:57:09.279 ThaliTest[391:257129] client session: disconnect
2015-12-08 03:57:09.279 ThaliTest[391:257129] client session: stateChange,:2->0 1449543421593.431.+h1/ug==
,2015-12-08 03:57:09.288 ThaliTest[391:257129] jxcore: disconnect: success
ok 84 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
not ok 85 .end() called twice
  ---
    operator: fail
  ...
,calling stopBroadcasting
,2015-12-08 03:57:11.455 ThaliTest[391:257129] jxcore: stopBroadcasting
2015-12-08 03:57:11.456 ThaliTest[391:257129] THEMultipeerSession stopping peer
2015-12-08 03:57:11.456 ThaliTest[391:257129] multipeer session: stop timer
2015-12-08 03:57:11.457 Th,aliTest[391:257129] server session: disconnect
2015-12-08 03:57:11.457 ThaliTest[391:257129] server session: stateChange:2->0 1449543422873.405
,2015-12-08 03:57:12.328 ThaliTest[391:257129] server session: disconnect
2015-12-08 03:57:12.328 ThaliTest[391:257129] server session: stateChange:2->0 1449543421775.439
,2015-12-08 03:57:12.331 ThaliTest[391:257129] server session: disconnect
2015-12-08 03:57:12.331 ThaliTest[391:257129] server session: stateChange:2->0 1449543421593.431
,2015-12-08 03:57:12.333 ThaliTest[391:257129] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-08 03:57:24.583 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:57:24.586 ThaliTest[391:257129] server: starting 1449543444583.391.Wxk+bw==
2015-12-08 03:57:24.586 ThaliTest[391:257129] multipeer session: start timer: 0x1c06ac40
2015-12-08 03:57:24.587 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543444583.391
2015-12-08 03:57:24.587 ThaliTest[391:257129] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error
,2015-12-08 03:57:24.599 ThaliTest[391:256944] client: found peer: 1449543421593.431.+h1/ug==
2015-12-08 03:57:24.601 ThaliTest[391:257129] jxcore: connect 1449543421593.431.+h1/ug==
2015-12-08 03:57:24.601 ThaliTest[391:257129] client session: connect
2,015-12-08 03:57:24.601 ThaliTest[391:257129] client session: stateChange:0->1 1449543421593.431.+h1/ug==
,2015-12-08 03:57:26.427 ThaliTest[391:256944] client: found peer: 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:26.429 ThaliTest[391:257129] jxcore: connect 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:26.437 ThaliTest[391:257129] client session: connect
,2015-12-08 03:57:26.439 ThaliTest[391:257129] client session: stateChange:0->1 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:26.447 ThaliTest[391:256944] client: found peer: 1449543446505.405.XRtx8Q==
2015-12-08 03:57:26.448 ThaliTest[391:256944] client: found peer: 1449543445467.431.nUNHmA==
,2015-12-08 03:57:26.464 ThaliTest[391:257129] jxcore: connect 1449543446505.405.XRtx8Q==
2015-12-08 03:57:26.464 ThaliTest[391:257129] client session: connect
2015-12-08 03:57:26.464 ThaliTest[391:257129] client session: stateChange:0->1 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:26.483 ThaliTest[391:257129] jxcore: connect 1449543445467.431.nUNHmA==
2015-12-08 03:57:26.485 ThaliTest[391:257129] client session: connect
2015-12-08 03:57:26.486 ThaliTest[391:257129] client session: stateChange:0->1 1449543445467.43,1.nUNHmA==
,2015-12-08 03:57:26.546 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:57:26.546 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:57:26.547 ThaliTest[391:256944] multipeer session: start timer: 0x1c06ac40
2015-12-08 ,03:57:26.547 ThaliTest[391:256944] server session: connect
2015-12-08 03:57:26.547 ThaliTest[391:256944] server session: stateChange:0->1 1449543445467.431
,2015-12-08 03:57:26.558 ThaliTest[391:256944] server: accepting invitation 1449543445467.431
,2015-12-08 03:57:27.009 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:57:27.009 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:57:27.009 ThaliTest[391:256944] multipeer session: start timer: 0x1c06ac40
2015-12-08 03:57:27.010 ThaliTest[391:256944] server session: connect
,2015-12-08 03:57:27.010 ThaliTest[391:256944] server session: stateChange:0->1 1449543446505.405
,2015-12-08 03:57:27.025 ThaliTest[391:256944] server: accepting invitation 1449543446505.405
,2015-12-08 03:57:27.048 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:57:27.049 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:57:27.050 ThaliTest[391:256944] multipeer session: start timer: 0x1c06ac40
2015-12-08 03:57:27.051 ThaliTest[391:256944] server session: connect
2015-12-08 03:57:27.051 ThaliTest[391:256944] server session: stateChange:0->1 1449543445470.439
,2015-12-08 03:57:27.084 ThaliTest[391:256944] server: accepting invitation 1449543445470.439
,2015-12-08 03:57:28.960 ThaliTest[391:256944] client: lost peer: 1449543421593.431.+h1/ug==
2015-12-08 03:57:28.961 ThaliTest[391:256944] client session: onPeerLost: 1449543421593.431.+h1/ug==
2015-12-08 03:57:28.961 ThaliTest[391:256944] client session:, onLinkFailure: 1449543421593.431.+h1/ug==
2015-12-08 03:57:28.961 ThaliTest[391:256944] client session: disconnect
2015-12-08 03:57:28.961 ThaliTest[391:256944] client session: stateChange:1->0 1449543421593.431.+h1/ug==
,2015-12-08 03:57:28.963 ThaliTest[391:256944] client session: fireConnectCallback: 1449543421593.431.+h1/ug==
2015-12-08 03:57:28.963 ThaliTest[391:256944] jxcore: connect: fail: Peer disconnected
,2015-12-08 03:57:29.975 ThaliTest[391:257129] jxcore: connect 1449543421593.431.+h1/ug==
,2015-12-08 03:57:29.976 ThaliTest[391:257129] client: connect: unreachable 1449543421593.431.+h1/ug==
2015-12-08 03:57:29.976 ThaliTest[391:257129] jxcore: connect: fail: Peer unreachable
,2015-12-08 03:57:30.216 ThaliTest[391:257697] server session: connected
2015-12-08 03:57:30.218 ThaliTest[391:257697] server session: stateChange:1->2 1449543445467.431
,2015-12-08 03:57:30.253 ThaliTest[391:256944] server relay: socket disconnected
2015-12-08 03:57:30.254 ThaliTest[391:256944] server relay: 0x1c078d00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:30.357 ThaliTest[391:257680] server session: not connected 1449543445467.431
,2015-12-08 03:57:30.708 ThaliTest[391:257680] server session: connected
2015-12-08 03:57:30.709 ThaliTest[391:257680] server session: stateChange:1->2 1449543446505.405
,2015-12-08 03:57:30.717 ThaliTest[391:256944] server relay: socket disconnected
2015-12-08 03:57:30.718 ThaliTest[391:256944] server relay: 0x1c064cb0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:30.787 ThaliTest[391:257696] server session: not connected 1449543446505.405
,2015-12-08 03:57:30.830 ThaliTest[391:257697] server session: connected
2015-12-08 03:57:30.831 ThaliTest[391:257697] server session: stateChange:1->2 1449543445470.439
,2015-12-08 03:57:30.848 ThaliTest[391:256944] server relay: socket disconnected
,2015-12-08 03:57:30.849 ThaliTest[391:256944] server relay: 0x1972ada0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:30.878 ThaliTest[391:257697] server session: not connected 1449543445470.439
,2015-12-08 03:57:31.432 ThaliTest[391:257680] client session: connected
,2015-12-08 03:57:31.432 ThaliTest[391:257680] client session: stateChange:1->2 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.462 ThaliTest[391:257693] client session: fireConnectCallback: 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.463 ThaliTest[391:257693] jxcore: connect: success
,ok 87 Should be able to connect without error
,ok 88 Port should be within range
,2015-12-08 03:57:31.466 ThaliTest[391:257129] jxcore: connect 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.467 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.468 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,ok 89 Should fail on double connect
,2015-12-08 03:57:31.470 ThaliTest[391:257129] jxcore: disconnect
,2015-12-08 03:57:31.472 ThaliTest[391:257129] client session: disconnectFromPeer: 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.474 ThaliTest[391:257129] client session: disconnect
,2015-12-08 03:57:31.476 ThaliTest[391:257129] client session: stateChange:2->0 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.554 ThaliTest[391:257129] jxcore: disconnect: success
,ok 90 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-08 03:57:31.689 ThaliTest[391:257625] client session: connected
,2015-12-08 03:57:31.689 ThaliTest[391:257625] client session: stateChange:1->2 1449543446505.405.XRtx8Q==
2015-12-08 03:57:31.692 ThaliTest[391:257625] client session: fireConnectCallback: 1449543446505.405.XRtx8Q==
2015-12-08 03:57:31.692 ThaliTest[391:,257625] jxcore: connect: success
ok 91 Should be able to connect without error
ok 92 Port should be within range
2015-12-08 03:57:31.694 ThaliTest[391:257129] jxcore: connect 1449543446505.405.XRtx8Q==
2015-12-08 03:57:31.695 ThaliTest[391:257129] clie,nt: already connect(ing/ed) to 1449543446505.405.XRtx8Q==
2015-12-08 03:57:31.695 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
ok 93 Should fail on double connect
2015-12-08 03:57:31.696 ThaliTest[391:257129] jxcore: disconnect
2015-1,2-08 03:57:31.696 ThaliTest[391:257129] client session: disconnectFromPeer: 1449543446505.405.XRtx8Q==
2015-12-08 03:57:31.696 ThaliTest[391:257129] client session: disconnect
2015-12-08 03:57:31.696 ThaliTest[391:257129] client session: stateChange:2->0, 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:31.723 ThaliTest[391:257695] client session: connected
,2015-12-08 03:57:31.724 ThaliTest[391:257695] client session: stateChange:1->2 1449543445467.431.nUNHmA==
,2015-12-08 03:57:31.770 ThaliTest[391:257695] client session: fireConnectCallback: 1449543445467.431.nUNHmA==
2015-12-08 03:57:31.770 ThaliTest[391:257695] jxcore: connect: success
,2015-12-08 03:57:31.783 ThaliTest[391:257129] jxcore: disconnect: success
,ok 94 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,not ok 95 .end() called twice
,  ---
,    operator: fail
,  ...
,ok 96 Should be able to connect without error
,ok 97 Port should be within range
,2015-12-08 03:57:31.794 ThaliTest[391:257129] jxcore: connect 1449543445467.431.nUNHmA==
,2015-12-08 03:57:31.794 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543445467.431.nUNHmA==
,2015-12-08 03:57:31.795 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,ok 98 Should fail on double connect
,2015-12-08 03:57:31.796 ThaliTest[391:257129] jxcore: disconnect
,2015-12-08 03:57:31.797 ThaliTest[391:257129] client session: disconnectFromPeer: 1449543445467.431.nUNHmA==
,2015-12-08 03:57:31.797 ThaliTest[391:257129] client session: disconnect
,2015-12-08 03:57:31.798 ThaliTest[391:257129] client session: stateChange:2->0 1449543445467.431.nUNHmA==
,2015-12-08 03:57:31.874 ThaliTest[391:257129] jxcore: disconnect: success
ok 99 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,not ok 100 .end() called twice
  ---
,    operator: fail
  ...
,calling stopBroadcasting
,2015-12-08 03:57:53.964 ThaliTest[391:257129] jxcore: stopBroadcasting
2015-12-08 03:57:53.964 ThaliTest[391:257129] THEMultipeerSession stopping peer
2015-12-08 03:57:53.964 ThaliTest[391:257129] multipeer session: stop timer
2015-12-08 03:57:53.965 ThaliTest[391:257129] server session: disconnect
2015-12-08 03:57:53.965 ThaliTest[391:257129] server session: stateChange:2->0 1449543445470.439
2015-12-08 03:57:53.966 ThaliTest[391:257129] server session: disconnect
,2015-12-08 03:57:53.970 ThaliTest[391:257129] server session: stateChange:2->0 1449543446505.405
,2015-12-08 03:57:53.979 ThaliTest[391:257129] server session: disconnect
2015-12-08 03:57:53.979 ThaliTest[391:257129] server session: stateChange:2->0 1449543445467.431
,2015-12-08 03:57:54.058 ThaliTest[391:257129] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-08 03:57:57.156 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:57:57.159 ThaliTest[391:257129] server: starting 1449543477155.391.TQsX1A==
2015-12-08 03:57:57.159 ThaliTest[391:257129] multipeer session: start timer: 0x1c057840
2015-12-08 03:57:57.159 ThaliTest[391:257129] THEMultipeerSession initialized peer 1449543477155.391
2015-12-08 03:57:57.160 ThaliTest[391:257129] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error
,2015-12-08 03:57:57.364 ThaliTest[391:256944] client: found peer: 1449543445470.439.9bQ4gA==
2015-12-08 03:57:57.366 ThaliTest[391:257129] jxcore: connect 1449543445470.439.9bQ4gA==
2015-12-08 03:57:57.367 ThaliTest[391:256944] client: found peer: 144954,3445467.431.nUNHmA==
2015-12-08 03:57:57.367 ThaliTest[391:257129] client session: connect
2015-12-08 03:57:57.367 ThaliTest[391:257129] client session: stateChange:0->1 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:57.381 ThaliTest[391:257129] jxcore: connect 1449543445467.431.nUNHmA==
2015-12-08 03:57:57.381 ThaliTest[391:257129] client session: connect
2015-12-08 03:57:57.381 ThaliTest[391:257129] client session: stateChange:0->1 1449543445467.431.nUNHmA==
,2015-12-08 03:57:58.586 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:57:58.586 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:57:58.586 ThaliTest[391:256944] multipeer session: start timer: 0x1c057840
2015-12-08 ,03:57:58.587 ThaliTest[391:256944] server session: connect
2015-12-08 03:57:58.587 ThaliTest[391:256944] server session: stateChange:0->1 1449543478008.431
,2015-12-08 03:57:58.594 ThaliTest[391:256944] server: accepting invitation 1449543478008.431
,2015-12-08 03:57:58.935 ThaliTest[391:256944] client: found peer: 1449543477671.439.01rxOw==
2015-12-08 03:57:58.935 ThaliTest[391:257129] jxcore: connect 1449543477671.439.01rxOw==
2015-12-08 03:57:58.936 ThaliTest[391:257129] client session: connect
2015-12-08 03:57:58.936 ThaliTest[391:257129] client session: stateChange:0->1 1449543477671.439.01rxOw==
,2015-12-08 03:57:58.987 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:57:58.987 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:57:58.988 ThaliTest[391:256944] multipeer session: start timer: 0x1c057840
2015-12-08 ,03:57:58.989 ThaliTest[391:256944] server session: connect
2015-12-08 03:57:58.989 ThaliTest[391:256944] server session: stateChange:0->1 1449543477671.439
2015-12-08 03:57:59.000 ThaliTest[391:256944] server: accepting invitation 1449543477671.439
2015,-12-08 03:57:59.017 ThaliTest[391:256944] client: found peer: 1449543478008.431.8PN9MA==
2015-12-08 03:57:59.026 ThaliTest[391:257129] jxcore: connect 1449543478008.431.8PN9MA==
,2015-12-08 03:57:59.026 ThaliTest[391:257129] client session: connect
,2015-12-08 03:57:59.042 ThaliTest[391:257129] client session: stateChange:0->1 1449543478008.431.8PN9MA==
,2015-12-08 03:57:59.135 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:57:59.135 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:57:59.136 ThaliTest[391:256944] multipeer session: start timer: 0x1c057840
,2015-12-08 03:57:59.136 ThaliTest[391:256944] server session: connect
,2015-12-08 03:57:59.137 ThaliTest[391:256944] server session: stateChange:0->1 1449543480460.405
,2015-12-08 03:57:59.148 ThaliTest[391:256944] server: accepting invitation 1449543480460.405
,2015-12-08 03:58:00.057 ThaliTest[391:256944] client: found peer: 1449543480460.405.wRZudQ==
,2015-12-08 03:58:00.059 ThaliTest[391:257129] jxcore: connect 1449543480460.405.wRZudQ==
2015-12-08 03:58:00.059 ThaliTest[391:257129] client session: connect
,2015-12-08 03:58:00.059 ThaliTest[391:257129] client session: stateChange:0->1 1449543480460.405.wRZudQ==
,2015-12-08 03:58:02.075 ThaliTest[391:257769] server session: connected
2015-12-08 03:58:02.075 ThaliTest[391:257769] server session: stateChange:1->2 1449543478008.431
,2015-12-08 03:58:02.136 ThaliTest[391:256944] server relay: socket disconnected
2015-12-08 03:58:02.136 ThaliTest[391:256944] server relay: 0x1c077220 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:58:02.191 ThaliTest[391:257773] server session: not connected 1449543478008.431
,2015-12-08 03:58:02.727 ThaliTest[391:257773] server session: connected
2015-12-08 03:58:02.727 ThaliTest[391:257773] server session: stateChange:1->2 1449543477671.439
,2015-12-08 03:58:02.743 ThaliTest[391:256944] server relay: socket disconnected
,2015-12-08 03:58:02.744 ThaliTest[391:256944] server relay: 0x19722a90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:58:02.767 ThaliTest[391:257769] server session: not connected 1449543477671.439
,2015-12-08 03:58:02.865 ThaliTest[391:257769] server session: connected
2015-12-08 03:58:02.865 ThaliTest[391:257769] server session: stateChange:1->2 1449543480460.405
,2015-12-08 03:58:02.912 ThaliTest[391:257773] server session: not connected 1449543480460.405
,2015-12-08 03:58:04.275 ThaliTest[391:257773] client session: connected
2015-12-08 03:58:04.276 ThaliTest[391:257773] client session: stateChange:1->2 1449543478008.431.8PN9MA==
,2015-12-08 03:58:04.308 ThaliTest[391:257773] client session: fireConnectCallback: 1449543478008.431.8PN9MA==
,2015-12-08 03:58:04.313 ThaliTest[391:257773] jxcore: connect: success
,ok 102 Should be able to connect without error
ok 103 Port should be within range
,2015-12-08 03:58:04.320 ThaliTest[391:257129] jxcore: disconnect
,2015-12-08 03:58:04.322 ThaliTest[391:257129] client session: disconnectFromPeer: 1449543478008.431.8PN9MA==
,2015-12-08 03:58:04.327 ThaliTest[391:257129] client session: disconnect
,2015-12-08 03:58:04.330 ThaliTest[391:257129] client session: stateChange:2->0 1449543478008.431.8PN9MA==
,2015-12-08 03:58:04.431 ThaliTest[391:257129] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error
,2015-12-08 03:58:04.433 ThaliTest[391:257129] jxcore: disconnect
,2015-12-08 03:58:04.433 ThaliTest[391:257129] jxcore: disconnect: fail
,ok 105 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,2015-12-08 03:58:04.436 ThaliTest[391:257773] client session: connected
2015-12-08 03:58:04.437 ThaliTest[391:257773] client session: stateChange:1->2 1449543480460.405.wRZudQ==
,# setup
,2015-12-08 03:58:04.479 ThaliTest[391:257775] client session: fireConnectCallback: 1449543480460.405.wRZudQ==
2015-12-08 03:58:04.479 ThaliTest[391:257775] jxcore: connect: success
,ok 106 Should be able to connect without error
,ok 107 Port should be within range
,2015-12-08 03:58:04.483 ThaliTest[391:257129] jxcore: disconnect
,2015-12-08 03:58:04.483 ThaliTest[391:257129] client session: disconnectFromPeer: 1449543480460.405.wRZudQ==
,2015-12-08 03:58:04.484 ThaliTest[391:257129] client session: disconnect
,2015-12-08 03:58:04.484 ThaliTest[391:257129] client session: stateChange:2->0 1449543480460.405.wRZudQ==
,2015-12-08 03:58:04.498 ThaliTest[391:257129] jxcore: disconnect: success
,ok 108 Should be able to disconnect without error
,2015-12-08 03:58:04.502 ThaliTest[391:257129] jxcore: disconnect
,2015-12-08 03:58:04.503 ThaliTest[391:257129] jxcore: disconnect: fail
,ok 109 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,not ok 110 .end() called twice
  ---
,    operator: fail
,  ...
,calling stopBroadcasting
,2015-12-08 03:58:04.677 ThaliTest[391:257129] jxcore: stopBroadcasting
,2015-12-08 03:58:04.678 ThaliTest[391:257129] THEMultipeerSession stopping peer
,2015-12-08 03:58:04.678 ThaliTest[391:257129] multipeer session: stop timer
,2015-12-08 03:58:04.679 ThaliTest[391:257129] client session: disconnect
,2015-12-08 03:58:04.680 ThaliTest[391:257129] client session: stateChange:1->0 1449543445467.431.nUNHmA==
,2015-12-08 03:58:04.683 ThaliTest[391:257129] client session: disconnect
,2015-12-08 03:58:04.683 ThaliTest[391:257129] client session: stateChange:1->0 1449543445470.439.9bQ4gA==
,2015-12-08 03:58:04.685 ThaliTest[391:257129] client session: disconnect
,2015-12-08 03:58:04.685 ThaliTest[391:257129] client session: stateChange:1->0 1449543477671.439.01rxOw==
,2015-12-08 03:58:04.768 ThaliTest[391:257129] server session: disconnect
,2015-12-08 03:58:04.772 ThaliTest[391:257129] server session: stateChange:2->0 1449543478008.431
,2015-12-08 03:58:04.779 ThaliTest[391:257129] server session: disconnect
,2015-12-08 03:58:04.783 ThaliTest[391:257129] server session: stateChange:2->0 1449543480460.405
,2015-12-08 03:58:05.270 ThaliTest[391:257129] server session: disconnect
2015-12-08 03:58:05.271 ThaliTest[391:257129] server session: stateChange:2->0 1449543477671.439
2015-12-08 03:58:05.271 ThaliTest[391:257129] jxcore: stopBroadcasting: success
sto,pBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-08 03:58:09.758 ThaliTest[391:257129] jxcore: startBroadcasting
,2015-12-08 03:58:09.760 ThaliTest[391:257129] server: starting 1449543489757.391.iXbQJw==
2015-12-08 03:58:09.761 ThaliTest[391:257129] multipeer session: start timer: 0x1972b6e0
2015-12-08 03:58:09.761 ThaliTest[391:257129] THEMultipeerSession initializ,ed peer 1449543489757.391
2015-12-08 03:58:09.761 ThaliTest[391:257129] jxcore: startBroadcasting: success
ok 111 Should be able to call startBroadcasting without error
echo server started
,2015-12-08 03:58:09.774 ThaliTest[391:256944] client: found peer: 1449543445470.439.9bQ4gA==
[{"peerIdentifier":"1449543445470.439.9bQ4gA==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 03:58:09.777 ThaliTest[391:256944] client: found peer: 1449543445467.431.nUNHmA==
2015-12-08 03:58:09.778 ThaliTest[391:257129] jxcore: connect 1449543445470.439.9bQ4gA==
2015-12-08 03:58:09.778 ThaliTest[391:257129] client session: connect
2,015-12-08 03:58:09.778 ThaliTest[391:257129] client session: stateChange:0->1 1449543445470.439.9bQ4gA==
,[{"peerIdentifier":"1449543445467.431.nUNHmA==","peerName":"(null)","peerAvailable":true}]
2015-12-08 03:58:09.790 ThaliTest[391:257129] jxcore: connect 1449543445467.431.nUNHmA==
2015-12-08 03:58:09.790 ThaliTest[391:257129] client session: connect
201,5-12-08 03:58:09.790 ThaliTest[391:257129] client session: stateChange:0->1 1449543445467.431.nUNHmA==
,2015-12-08 03:58:10.975 ThaliTest[391:256944] client: found peer: 1449543491366.405.MuCjBg==
[{"peerIdentifier":"1449543491366.405.MuCjBg==","peerName":"(null)","peerAvailable":true}]
2015-12-08 03:58:10.976 ThaliTest[391:257129] jxcore: connect 14495434,91366.405.MuCjBg==
2015-12-08 03:58:10.977 ThaliTest[391:257129] client session: connect
,2015-12-08 03:58:10.977 ThaliTest[391:257129] client session: stateChange:0->1 1449543491366.405.MuCjBg==
,2015-12-08 03:58:11.131 ThaliTest[391:256944] client: found peer: 1449543489999.431.1e3a9w==
2015-12-08 03:58:11.132 ThaliTest[391:256944] client: found peer: 1449543490182.439.HczcmQ==
[{"peerIdentifier":"1449543489999.431.1e3a9w==","peerName":"(null)",,"peerAvailable":true}]
2015-12-08 03:58:11.133 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:11.133 ThaliTest[391:257129] client session: connect
2015-12-08 03:58:11.134 ThaliTest[391:257129] client session: stateChan,ge:0->1 1449543489999.431.1e3a9w==
,[{"peerIdentifier":"1449543490182.439.HczcmQ==","peerName":"(null)","peerAvailable":true}]
2015-12-08 03:58:11.147 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:11.148 ThaliTest[391:257129] client session: connect
2015-12-08 03:58:11.150 ThaliTest[391:257129] client session: stateChange:0->1 1449543490182.439.HczcmQ==
,2015-12-08 03:58:11.633 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:58:11.633 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:58:11.634 ThaliTest[391:256944] multipeer session: start timer: 0x1972b6e0
2015-12-08 03:58:11.634 ThaliTest[391:256944] server session: connect
,2015-12-08 03:58:11.635 ThaliTest[391:256944] server session: stateChange:0->1 1449543491366.405
2015-12-08 03:58:11.641 ThaliTest[391:256944] server: accepting invitation 1449543491366.405
,2015-12-08 03:58:11.674 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:58:11.674 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:58:11.674 ThaliTest[391:256944] multipeer session: start timer: 0x1972b6e0
2015-12-08 ,03:58:11.675 ThaliTest[391:256944] server session: connect
2015-12-08 03:58:11.675 ThaliTest[391:256944] server session: stateChange:0->1 1449543490182.439
2015-12-08 03:58:11.692 ThaliTest[391:256944] server: accepting invitation 1449543490182.439
,2015-12-08 03:58:11.759 ThaliTest[391:256944] multipeer session: reset timer
,2015-12-08 03:58:11.761 ThaliTest[391:256944] multipeer session: stop timer
,2015-12-08 03:58:11.762 ThaliTest[391:256944] multipeer session: start timer: 0x1972b6e0
,2015-12-08 03:58:11.763 ThaliTest[391:256944] server session: connect
,2015-12-08 03:58:11.764 ThaliTest[391:256944] server session: stateChange:0->1 1449543489999.431
,2015-12-08 03:58:11.777 ThaliTest[391:256944] server: accepting invitation 1449543489999.431
,2015-12-08 03:58:16.848 ThaliTest[391:257768] client session: connected
2015-12-08 03:58:16.848 ThaliTest[391:257768] client session: stateChange:1->2 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.962 ThaliTest[391:256944] client: lost peer: 1449543445467.431.nUNHmA==
,2015-12-08 03:58:16.962 ThaliTest[391:256944] client session: onPeerLost: 1449543445467.431.nUNHmA==
2015-12-08 03:58:16.962 ThaliTest[391:256944] client session: onLinkFailure: 1449543445467.431.nUNHmA==
2015-12-08 03:58:16.962 ThaliTest[391:256944] cli,ent session: disconnect
2015-12-08 03:58:16.963 ThaliTest[391:256944] client session: stateChange:1->0 1449543445467.431.nUNHmA==
,2015-12-08 03:58:16.964 ThaliTest[391:256944] client session: fireConnectCallback: 1449543445467.431.nUNHmA==
,2015-12-08 03:58:16.964 ThaliTest[391:256944] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1449543445467.431.nUNHmA==","peerName":"(null)","peerAvailable":false}]
,2015-12-08 03:58:16.986 ThaliTest[391:257876] client session: fireConnectCallback: 1449543489999.431.1e3a9w==
2015-12-08 03:58:16.987 ThaliTest[391:257876] jxcore: connect: success
,ok 112 Should be able to connect without error
ok 113 Port should be within range
,ok 114 First connect should succeed
,2015-12-08 03:58:17.027 ThaliTest[391:256944] client: relay established
2015-12-08 03:58:17.028 ThaliTest[391:256944] client: new accepted socket: 0x1973bdb0
,2015-12-08 03:58:17.352 ThaliTest[391:257775] client session: connected
,2015-12-08 03:58:17.352 ThaliTest[391:257775] client session: stateChange:1->2 1449543491366.405.MuCjBg==
,2015-12-08 03:58:17.363 ThaliTest[391:257775] server session: connected
,2015-12-08 03:58:17.365 ThaliTest[391:257775] server session: stateChange:1->2 1449543491366.405
,2015-12-08 03:58:17.422 ThaliTest[391:257775] client session: fireConnectCallback: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:17.423 ThaliTest[391:257770] server session: connected
,2015-12-08 03:58:17.424 ThaliTest[391:257775] jxcore: connect: success
,ok 115 Should be able to connect without error
,ok 116 Port should be within range
,ok 117 First connect should succeed
,2015-12-08 03:58:17.425 ThaliTest[391:257770] server session: stateChange:1->2 1449543490182.439
,2015-12-08 03:58:17.448 ThaliTest[391:256944] server relay: connected (to port: 5001)
,2015-12-08 03:58:17.460 ThaliTest[391:256944] client: relay established
,2015-12-08 03:58:17.462 ThaliTest[391:256944] client: new accepted socket: 0x1c149a20
,ok 118 the test messages should be equal
,ok 119 First send should succeed
,2015-12-08 03:58:17.551 ThaliTest[391:256944] client: socket closed
2015-12-08 03:58:17.552 ThaliTest[391:256944] client relay: socket disconnected
2015-12-08 03:58:17.552 ThaliTest[391:256944] client relay: 0x1c149a20 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:17.552 ThaliTest[391:256944] client session: socket closed: 1449543491366.405.MuCjBg==
2015-12-08 03:58:17.,552 ThaliTest[391:256944] client session: onLinkFailure: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:17.552 ThaliTest[391:256944] client session: disconnect
,2015-12-08 03:58:17.554 ThaliTest[391:256944] client session: stateChange:2->0 1449543491366.405.MuCjBg==
,2015-12-08 03:58:17.570 ThaliTest[391:256944] client session: fireConnectionErrorEvent: 1449543491366.405.MuCjBg==
2015-12-08 03:58:17.571 ThaliTest[391:257129] jxcore: connect 1449543491366.405.MuCjBg==
2015-12-08 03:58:17.572 ThaliTest[391:257129] clie,nt session: connect
2015-12-08 03:58:17.572 ThaliTest[391:256944] server relay: connected (to port: 5001)
2015-12-08 03:58:17.572 ThaliTest[391:257129] client session: stateChange:0->1 1449543491366.405.MuCjBg==
,2015-12-08 03:58:17.612 ThaliTest[391:257876] server session: not connected 1449543491366.405
,2015-12-08 03:58:17.629 ThaliTest[391:257129] jxcore: connect 1449543491366.405.MuCjBg==
,2015-12-08 03:58:17.634 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543491366.405.MuCjBg==
,2015-12-08 03:58:17.635 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:17.691 ThaliTest[391:256944] multipeer session: reset timer
2015-12-08 03:58:17.692 ThaliTest[391:256944] multipeer session: stop timer
2015-12-08 03:58:17.692 ThaliTest[391:256944] multipeer session: start timer: 0x1972b6e0
2015-12-08 03:58:17.692 ThaliTest[391:256944] server: disconnecting to refresh session (1449543491366.405)
,2015-12-08 03:58:17.692 ThaliTest[391:256944] server session: disconnect
,2015-12-08 03:58:17.698 ThaliTest[391:256944] server session: stateChange:2->0 1449543491366.405
,2015-12-08 03:58:17.715 ThaliTest[391:256944] server session: connect
,2015-12-08 03:58:17.716 ThaliTest[391:256944] server session: stateChange:0->1 1449543491366.405
,2015-12-08 03:58:17.741 ThaliTest[391:256944] server: accepting invitation 1449543491366.405
,ok 120 the test messages should be equal
,ok 121 First send should succeed
,2015-12-08 03:58:17.817 ThaliTest[391:256944] client: socket closed
,2015-12-08 03:58:17.818 ThaliTest[391:256944] client relay: socket disconnected
,2015-12-08 03:58:17.819 ThaliTest[391:256944] client relay: 0x1973bdb0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-08 03:58:17.820 ThaliTest[391:256944] client session: socket closed: 1449543489999.431.1e3a9w==
,2015-12-08 03:58:17.821 ThaliTest[391:256944] client session: onLinkFailure: 1449543489999.431.1e3a9w==
,2015-12-08 03:58:17.822 ThaliTest[391:256944] client session: disconnect
,2015-12-08 03:58:17.823 ThaliTest[391:256944] client session: stateChange:2->0 1449543489999.431.1e3a9w==
,2015-12-08 03:58:17.908 ThaliTest[391:257768] client session: connected
,2015-12-08 03:58:17.909 ThaliTest[391:257768] client session: stateChange:1->2 1449543490182.439.HczcmQ==
,2015-12-08 03:58:17.939 ThaliTest[391:257770] client session: fireConnectCallback: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:17.940 ThaliTest[391:257770] jxcore: connect: success
,ok 122 Should be able to connect without error
,ok 123 Port should be within range
,ok 124 First connect should succeed
,2015-12-08 03:58:17.976 ThaliTest[391:256944] client session: fireConnectionErrorEvent: 1449543489999.431.1e3a9w==
2015-12-08 03:58:17.976 ThaliTest[391:256944] client: relay established
,2015-12-08 03:58:17.978 ThaliTest[391:256944] client: new accepted socket: 0x1c08a540
,2015-12-08 03:58:17.979 ThaliTest[391:257129] jxcore: connect 1449543445467.431.nUNHmA==
,2015-12-08 03:58:17.980 ThaliTest[391:257129] client: connect: unreachable 1449543445467.431.nUNHmA==
,2015-12-08 03:58:17.982 ThaliTest[391:257129] jxcore: connect: fail: Peer unreachable
,2015-12-08 03:58:17.986 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:17.987 ThaliTest[391:257129] client session: connect
,2015-12-08 03:58:17.987 ThaliTest[391:257129] client session: stateChange:0->1 1449543489999.431.1e3a9w==
,2015-12-08 03:58:18.001 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
,2015-12-08 03:58:18.002 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
,2015-12-08 03:58:18.007 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:18.011 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
,2015-12-08 03:58:18.014 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
,2015-12-08 03:58:18.018 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,ok 125 the test messages should be equal
ok 126 First send should succeed
,2015-12-08 03:58:18.066 ThaliTest[391:257772] server session: connected
,2015-12-08 03:58:18.067 ThaliTest[391:256944] client: socket closed
,2015-12-08 03:58:18.073 ThaliTest[391:256944] client relay: socket disconnected
2015-12-08 03:58:18.072 ThaliTest[391:257772] server session: stateChange:1->2 1449543489999.431
,2015-12-08 03:58:18.074 ThaliTest[391:256944] client relay: 0x1c08a540 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-08 03:58:18.077 ThaliTest[391:256944] client session: socket closed: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.078 ThaliTest[391:256944] client session: onLinkFailure: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.081 ThaliTest[391:256944] client session: disconnect
2015-12-08 03:58:18.083 ThaliTest[391:256944] client session: stateChange:2->0 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.127 ThaliTest[391:257772] server session: not connected 1449543490182.439
,2015-12-08 03:58:18.150 ThaliTest[391:256944] client session: fireConnectionErrorEvent: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.160 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.163 ThaliTest[391:257129] client session: connect
,2015-12-08 03:58:18.164 ThaliTest[391:257129] client session: stateChange:0->1 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.171 ThaliTest[391:256944] server relay: connected (to port: 5001)
,2015-12-08 03:58:18.196 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.198 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.199 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:18.200 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.200 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.200 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:18.418 ThaliTest[391:256944] multipeer session: reset timer
,2015-12-08 03:58:18.418 ThaliTest[391:256944] multipeer session: stop timer
,2015-12-08 03:58:18.418 ThaliTest[391:256944] multipeer session: start timer: 0x1972b6e0
,2015-12-08 03:58:18.419 ThaliTest[391:256944] server: disconnecting to refresh session (1449543490182.439)
,2015-12-08 03:58:18.419 ThaliTest[391:256944] server session: disconnect
,2015-12-08 03:58:18.422 ThaliTest[391:256944] server session: stateChange:2->0 1449543490182.439
,2015-12-08 03:58:18.430 ThaliTest[391:256944] server session: connect
,2015-12-08 03:58:18.430 ThaliTest[391:256944] server session: stateChange:0->1 1449543490182.439
,2015-12-08 03:58:18.459 ThaliTest[391:256944] server: accepting invitation 1449543490182.439
,2015-12-08 03:58:18.638 ThaliTest[391:257129] jxcore: connect 1449543491366.405.MuCjBg==
2015-12-08 03:58:18.638 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543491366.405.MuCjBg==
2015-12-08 03:58:18.638 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:19.018 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:19.018 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
,2015-12-08 03:58:19.018 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:19.031 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
,2015-12-08 03:58:19.031 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
,2015-12-08 03:58:19.031 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:19.204 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:19.204 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:19.205 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:19.205 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:19.206 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
,2015-12-08 03:58:19.207 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:19.640 ThaliTest[391:257129] jxcore: connect 1449543491366.405.MuCjBg==
2015-12-08 03:58:19.642 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543491366.405.MuCjBg==
2015-12-08 03:58:19.642 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:19.951 ThaliTest[391:257773] server session: not connected 1449543489999.431
,2015-12-08 03:58:20.032 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:20.033 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
2015-12-08 03:58:20.033 ThaliTest[391:257129] jxcore: con,nect: fail: Aleady connecting
2015-12-08 03:58:20.033 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:20.034 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
2015-12-08 03:58:20.034 Th,aliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:20.211 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:20.211 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:20.212 ThaliTest[391:257129] jxcore: con,nect: fail: Aleady connecting
2015-12-08 03:58:20.212 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:20.212 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:20.213 Th,aliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:20.645 ThaliTest[391:257129] jxcore: connect 1449543491366.405.MuCjBg==
2015-12-08 03:58:20.645 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543491366.405.MuCjBg==
2015-12-08 03:58:20.646 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:21.039 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:21.042 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
2015-12-08 03:58:21.042 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:21.046 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:21.047 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
2015-12-08 03:58:21.049 ThaliTest[391:257129] jxcore: con,nect: fail: Aleady connecting
,2015-12-08 03:58:21.213 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:21.214 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:21.214 ThaliTest[391:257129] jxcore: con,nect: fail: Aleady connecting
2015-12-08 03:58:21.216 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:21.216 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:21.216 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:21.651 ThaliTest[391:257129] jxcore: connect 1449543491366.405.MuCjBg==
2015-12-08 03:58:21.653 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543491366.405.MuCjBg==
2015-12-08 03:58:21.654 ThaliTest[391:257129] jxcore: con,nect: fail: Aleady connecting
,2015-12-08 03:58:22.047 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:22.047 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
2015-12-08 03:58:22.048 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:22.062 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:22.062 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
,2015-12-08 03:58:22.063 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:22.221 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:22.221 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:22.221 ThaliTest[391:257129] jxcore: con,nect: fail: Aleady connecting
2015-12-08 03:58:22.222 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:22.222 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:22.222 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:22.425 ThaliTest[391:257772] client session: connected
2015-12-08 03:58:22.425 ThaliTest[391:257772] client session: stateChange:1->2 1449543491366.405.MuCjBg==
,2015-12-08 03:58:22.450 ThaliTest[391:257876] client session: fireConnectCallback: 1449543491366.405.MuCjBg==
2015-12-08 03:58:22.450 ThaliTest[391:257876] jxcore: connect: success
ok 127 Should be able to connect without error
,ok 128 Port should be within range
,ok 129 Second connect should succeed
,2015-12-08 03:58:22.479 ThaliTest[391:256944] client: relay established
2015-12-08 03:58:22.479 ThaliTest[391:256944] client: new accepted socket: 0x19718640
,ok 130 the test messages should be equal
,ok 131 Second send should succeed
,# setup
,2015-12-08 03:58:22.551 ThaliTest[391:256944] client: socket closed
2015-12-08 03:58:22.552 ThaliTest[391:256944] client relay: socket disconnected
2015-12-08 03:58:22.552 ThaliTest[391:256944] client relay: 0x19718640 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:22.553 ThaliTest[391:256944] client session: socket closed: 1449543491366.405.MuCjBg==
2015-12-08 03:58:22.,553 ThaliTest[391:256944] client session: onLinkFailure: 1449543491366.405.MuCjBg==
2015-12-08 03:58:22.553 ThaliTest[391:256944] client session: disconnect
2015-12-08 03:58:22.553 ThaliTest[391:256944] client session: stateChange:2->0 1449543491366.405.MuCjBg==
,2015-12-08 03:58:22.564 ThaliTest[391:256944] client session: fireConnectionErrorEvent: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:22.665 ThaliTest[391:257129] jxcore: connect 1449543491366.405.MuCjBg==
,2015-12-08 03:58:22.666 ThaliTest[391:257129] client session: connect
,2015-12-08 03:58:22.666 ThaliTest[391:257129] client session: stateChange:0->1 1449543491366.405.MuCjBg==
,2015-12-08 03:58:22.783 ThaliTest[391:257776] server session: connected
2015-12-08 03:58:22.784 ThaliTest[391:257776] server session: stateChange:1->2 1449543491366.405
,2015-12-08 03:58:22.829 ThaliTest[391:256944] server relay: connected (to port: 5001)
2015-12-08 03:58:22.830 ThaliTest[391:257768] client session: connected
2015-12-08 03:58:22.830 ThaliTest[391:257768] client session: stateChange:1->2 1449543490182.439.HczcmQ==
,2015-12-08 03:58:22.898 ThaliTest[391:257772] server session: not connected 1449543491366.405
,2015-12-08 03:58:23.059 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:23.059 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
2015-12-08 03:58:23.060 ThaliTest[391:257129] jxcore: con,nect: fail: Aleady connecting
2015-12-08 03:58:23.060 ThaliTest[391:257772] client session: fireConnectCallback: 1449543490182.439.HczcmQ==
2015-12-08 03:58:23.061 ThaliTest[391:257772] jxcore: connect: success
ok 132 Should be able to connect without e,rror
ok 133 Port should be within range
ok 134 Second connect should succeed
,2015-12-08 03:58:23.088 ThaliTest[391:256944] client: relay established
2015-12-08 03:58:23.089 ThaliTest[391:256944] client: new accepted socket: 0x1c081b60
,2015-12-08 03:58:23.101 ThaliTest[391:257129] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:23.102 ThaliTest[391:257129] client: already connect(ing/ed) to 1449543489999.431.1e3a9w==
2015-12-08 03:58:23.102 ThaliTest[391:257129] jxcore: connect: fail: Aleady connecting
,ok 135 the test messages should be equal
ok 136 Second send should succeed
,not ok 137 .end() called twice
,  ---
,    operator: fail
,  ...
,2015-12-08 03:58:23.158 ThaliTest[391:256944] client: socket closed
,2015-12-08 03:58:23.159 ThaliTest[391:256944] client relay: socket disconnected
,2015-12-08 03:58:23.161 ThaliTest[391:256944] client relay: 0x1c081b60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-08 03:58:23.162 ThaliTest[391:256944] client session: socket closed: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:23.165 ThaliTest[391:256944] client session: onLinkFailure: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:23.166 ThaliTest[391:256944] client session: disconnect
,2015-12-08 03:58:23.167 ThaliTest[391:256944] client session: stateChange:2->0 1449543490182.439.HczcmQ==
,2015-12-08 03:58:23.203 ThaliTest[391:257776] server session: connected
,2015-12-08 03:58:23.206 ThaliTest[391:257776] server session: stateChange:1->2 1449543490182.439
,2015-12-08 03:58:23.222 ThaliTest[391:257129] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:23.232 ThaliTest[391:256944] client session: fireConnectionErrorEvent: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:23.458 ThaliTest[391:257876] client session: connected
2015-12-08 03:58:23.458 ThaliTest[391:257876] client session: stateChange:1->2 1449543489999.431.1e3a9w==
,2015-12-08 03:58:23.481 ThaliTest[391:257772] client session: fireConnectCallback: 1449543489999.431.1e3a9w==
2015-12-08 03:58:23.482 ThaliTest[391:257772] jxcore: connect: success
,2015-12-08 03:58:23.634 ThaliTest[391:257776] server session: not connected 1449543490182.439
,2015-12-08 03:58:33.682 ThaliTest[391:257773] client session: not connected 1449543491366.405.MuCjBg==
2015-12-08 03:58:33.682 ThaliTest[391:257773] client session: onLinkFailure: 1449543491366.405.MuCjBg==
2015-12-08 03:58:33.682 ThaliTest[391:257773] client session: disconnect
2015-12-08 03:58:33.682 ThaliTest[391:257773] client session: stateChange:1->0 1449543491366.405.MuCjBg==
,2015-12-08 03:58:33.716 ThaliTest[391:257773] client session: fireConnectCallback: 1449543491366.405.MuCjBg==
2015-12-08 03:58:33.717 ThaliTest[391:257773] jxcore: connect: fail: Peer disconnected
,2015-12-08 03:58:42.776 ThaliTest[391:257776] client session: not connected 1449543445470.439.9bQ4gA==
2015-12-08 03:58:42.776 ThaliTest[391:257776] client session: onLinkFailure: 1449543445470.439.9bQ4gA==
2015-12-08 03:58:42.776 ThaliTest[391:257776] c,lient session: disconnect
2015-12-08 03:58:42.777 ThaliTest[391:257776] client session: stateChange:1->0 1449543445470.439.9bQ4gA==
2015-12-08 03:58:42.777 ThaliTest[391:257776] client session: fireConnectCallback: 1449543445470.439.9bQ4gA==
2015-12-08 ,03:58:42.778 ThaliTest[391:257776] jxcore: connect: fail: Peer disconnected

```
