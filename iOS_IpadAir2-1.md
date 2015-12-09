#### Test 506502789252e15_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/39963C63-C254-4F40-A44F-5A5B474CAA76/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/39963C63-C254-4F40-A44F-5A5B474CAA76/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/15A1D52C-E68B-492C-ABEB-DA401703C568/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52563"
,(lldb)     command script import "/tmp/39963C63-C254-4F40-A44F-5A5B474CAA76/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-09 18:52:24.261 ThaliTest[644:449813] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/23D8B2FE-A798-4DC1-A946-04DDF499A949/Library/Cookies/Cookies.binarycookies
,2015-12-09 18:52:24.274 ThaliTest[644:449813] <CATransformLayer: 0x16749ee0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-09 18:52:24.275 ThaliTest[644:449813] <CATransformLayer: 0x16661530> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-09 18:52:24.275 ThaliTest[644:449813] <CATransformLayer: 0x16662680> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-09 18:52:24.591 ThaliTest[644:449813] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 18:52:24.592 ThaliTest[644:449813] Multi-tasking -> Device: YES, App: YES
,2015-12-09 18:52:24.599 ThaliTest[644:449813] Unlimited access to network resources
,2015-12-09 18:52:24.605 ThaliTest[644:449813] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 18:52:33.766 ThaliTest[644:449813] Resetting plugins due to page load.
,2015-12-09 18:52:37.157 ThaliTest[644:449813] Finished load of: file:///var/mobile/Containers/Bundle/Application/15A1D52C-E68B-492C-ABEB-DA401703C568/ThaliTest.app/www/index.html
,2015-12-09 18:52:37.297 ThaliTest[644:449813] JXcore Cordova plugin initializing
,2015-12-09 18:52:37.297 ThaliTest[644:450084] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
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
,2015-12-09 18:57:40.042 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.058 ThaliTest[644:450084] server: starting 1449683860042.644.FoMX8A==
,2015-12-09 18:57:40.060 ThaliTest[644:450084] multipeer session: start timer: 0x1a2a3fc0
,2015-12-09 18:57:40.060 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860042.644
2015-12-09 18:57:40.061 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-09 18:57:40.063 ThaliTest[644:450084] jxcore: stopBroadcasting
2015-12-09 18:57:40.064 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:57:40.064 ThaliTest[644:450084] multipeer session: stop timer
2015-12-09 18:57:40.064 ThaliTest[644:450084] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:40.069 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.073 ThaliTest[644:450084] server: starting 1449683860068.644.edpBqA==
2015-12-09 18:57:40.074 ThaliTest[644:450084] multipeer session: start timer: 0x1a2a5da0
,2015-12-09 18:57:40.074 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860068.644
,2015-12-09 18:57:40.075 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2015-12-09 18:57:40.077 ThaliTest[644:450084] jxcore: stopBroadcasting
2015-12-09 18:57:40.077 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:57:40.078 ThaliTest[644:450084] multipeer session: stop timer
,2015-12-09 18:57:40.078 ThaliTest[644:450084] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:40.081 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.082 ThaliTest[644:450084] server: starting 1449683860080.644.vtLMgA==
,2015-12-09 18:57:40.083 ThaliTest[644:450084] multipeer session: start timer: 0x1a1b3aa0
2015-12-09 18:57:40.083 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860080.644
2015-12-09 18:57:40.083 ThaliTest[644:450084] jxcore: startBroad,casting: success
ok 49 Should be able to call startBroadcasting without error
2015-12-09 18:57:40.084 ThaliTest[644:450084] jxcore: stopBroadcasting
2015-12-09 18:57:40.084 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:57:40.084 ThaliTest[644:450084] multipeer session: stop timer
2015-12-09 18:57:40.085 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
2015-12-09 18:57:40.087 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.089 ThaliTest[644:450084] server: starting 1449683860086.644.0lGNgQ==
2015-12-09 18:57:40.089 ThaliTest[644:450084] multipeer session: start timer: 0x1a2a6010
2015-12-09 18:57:40.089 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860086.644
2015-12-09 18:57:40.089 ThaliTest[644:450084] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-09 18:57:40.090 ThaliTest[644:450084] jxcore: stopBroadcasting
2015-12-09 18,:57:40.090 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:57:40.090 ThaliTest[644:450084] multipeer session: stop timer
2015-12-09 18:57:40.091 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:40.092 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.096 ThaliTest[644:450084] server: starting 1449683860091.644.bqFUEA==
2015-12-09 18:57:40.096 ThaliTest[644:450084] multipeer session: start timer: 0x1a2a6980
2015-12-09 18:57:40.096 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860091.644
2015-12-09 18:57:40.097 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
2015-12-09 18:57:40.098 ThaliTest[644:450084] jxcore: stopBroadcasting
2015-12-09 18:57:40.098 ThaliTest[644:450084] THEMultipeerSession stopping peer
,2015-12-09 18:57:40.098 ThaliTest[644:450084] multipeer session: stop timer
,2015-12-09 18:57:40.100 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:40.103 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.104 ThaliTest[644:450084] server: starting 1449683860102.644./zor+w==
,2015-12-09 18:57:40.105 ThaliTest[644:450084] multipeer session: start timer: 0x1a34bf10
,2015-12-09 18:57:40.106 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860102.644
,2015-12-09 18:57:40.106 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-09 18:57:40.108 ThaliTest[644:450084] jxcore: stopBroadcasting
,2015-12-09 18:57:40.109 ThaliTest[644:450084] THEMultipeerSession stopping peer
,2015-12-09 18:57:40.109 ThaliTest[644:450084] multipeer session: stop timer
,2015-12-09 18:57:40.110 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:40.112 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.113 ThaliTest[644:450084] server: starting 1449683860111.644.H5gOHw==
,2015-12-09 18:57:40.113 ThaliTest[644:450084] multipeer session: start timer: 0x1a1b58c0
,2015-12-09 18:57:40.114 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860111.644
,2015-12-09 18:57:40.114 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-09 18:57:40.116 ThaliTest[644:450084] jxcore: stopBroadcasting
,2015-12-09 18:57:40.116 ThaliTest[644:450084] THEMultipeerSession stopping peer
,2015-12-09 18:57:40.116 ThaliTest[644:450084] multipeer session: stop timer
,2015-12-09 18:57:40.117 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:40.119 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.120 ThaliTest[644:450084] server: starting 1449683860118.644.kSEkgg==
,2015-12-09 18:57:40.120 ThaliTest[644:450084] multipeer session: start timer: 0x1a1b4820
,2015-12-09 18:57:40.122 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860118.644
,2015-12-09 18:57:40.122 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-09 18:57:40.123 ThaliTest[644:450084] jxcore: stopBroadcasting
,2015-12-09 18:57:40.124 ThaliTest[644:450084] THEMultipeerSession stopping peer
,2015-12-09 18:57:40.124 ThaliTest[644:450084] multipeer session: stop timer
,2015-12-09 18:57:40.125 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:40.126 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.127 ThaliTest[644:450084] server: starting 1449683860126.644.5eWaHQ==
,2015-12-09 18:57:40.128 ThaliTest[644:450084] multipeer session: start timer: 0x1a1b6e70
,2015-12-09 18:57:40.129 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860126.644
,2015-12-09 18:57:40.129 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-09 18:57:40.130 ThaliTest[644:450084] jxcore: stopBroadcasting
,2015-12-09 18:57:40.131 ThaliTest[644:450084] THEMultipeerSession stopping peer
,2015-12-09 18:57:40.131 ThaliTest[644:450084] multipeer session: stop timer
,2015-12-09 18:57:40.132 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:40.133 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.134 ThaliTest[644:450084] server: starting 1449683860133.644.wbLZjw==
,2015-12-09 18:57:40.135 ThaliTest[644:450084] multipeer session: start timer: 0x1a1b7700
,2015-12-09 18:57:40.136 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860133.644
2015-12-09 18:57:40.136 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-09 18:57:40.137 ThaliTest[644:450084] jxcore: stopBroadcasting
,2015-12-09 18:57:40.137 ThaliTest[644:450084] THEMultipeerSession stopping peer
,2015-12-09 18:57:40.138 ThaliTest[644:450084] multipeer session: stop timer
,2015-12-09 18:57:40.138 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-09 18:57:40.876 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:40.879 ThaliTest[644:450084] server: starting 1449683860875.644.117Z+g==
,2015-12-09 18:57:40.881 ThaliTest[644:450084] multipeer session: start timer: 0x1a34f930
2015-12-09 18:57:40.881 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683860875.644
2015-12-09 18:57:40.882 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
2015-12-09 18:57:40.885 ThaliTest[644:450084] jxcore: startBroadcasting
2015-12-09 18:57:40.885 ThaliTest[644:450084] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2015-12-09 18:57:40.889 ThaliTest[644:450084] jxcore: stopBroadcasting
2015-12-09 18:57:40.890 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:57:40.890 ThaliTest[644:450084] multipeer session: stop timer
2015-12-09 18:57:40.891 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-09 18:57:41.968 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:41.972 ThaliTest[644:450084] server: starting 1449683861968.644.qfT3Dg==
,2015-12-09 18:57:41.973 ThaliTest[644:450084] multipeer session: start timer: 0x1a3512e0
,2015-12-09 18:57:41.973 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683861968.644
2015-12-09 18:57:41.974 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2015-12-09 18:57:41.977 ThaliTest[644:450084] jxcore: connect foobar
2015-12-09 18:57:41.977 ThaliTest[644:450084] client: unknown peer foobar
2015-12-09 18:57:41.977 ThaliTest[644:450084] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2015-12-09 18:57:41.981 ThaliTest[644:450084] jxcore: stopBroadcasting
2015-12-09 18:57:41.982 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:57:41.982 ThaliTest[644:450084] multipeer session: stop timer
2015-12-09 18:57:41.982 ThaliTest[644:450084] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-09 18:57:42.669 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:42.672 ThaliTest[644:450084] server: starting 1449683862669.644.2PDtoQ==
,2015-12-09 18:57:42.673 ThaliTest[644:450084] multipeer session: start timer: 0x1a3539d0
2015-12-09 18:57:42.674 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683862669.644
2015-12-09 18:57:42.674 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
,2015-12-09 18:57:42.677 ThaliTest[644:450084] jxcore: disconnect
2015-12-09 18:57:42.677 ThaliTest[644:450084] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2015-12-09 18:57:42.680 ThaliTest[644:450084] jxcore: stopBroadc,asting
2015-12-09 18:57:42.680 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:57:42.680 ThaliTest[644:450084] multipeer session: stop timer
2015-12-09 18:57:42.681 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-09 18:57:43.445 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:43.448 ThaliTest[644:450084] server: starting 1449683863444.644.Ac9XDg==
,2015-12-09 18:57:43.449 ThaliTest[644:450084] multipeer session: start timer: 0x1a2ae0a0
2015-12-09 18:57:43.450 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683863444.644
2015-12-09 18:57:43.451 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2015-12-09 18:57:44.982 ThaliTest[644:449813] client: found peer: 1449683862381.622.vuGzaA==
,2015-12-09 18:57:44.985 ThaliTest[644:450084] jxcore: connect 1449683862381.622.vuGzaA==
,2015-12-09 18:57:44.986 ThaliTest[644:450084] client session: connect
2015-12-09 18:57:44.987 ThaliTest[644:450084] client session: stateChange:0->1 1449683862381.622.vuGzaA==
,2015-12-09 18:57:45.544 ThaliTest[644:449813] multipeer session: reset timer
2015-12-09 18:57:45.545 ThaliTest[644:449813] multipeer session: stop timer
2015-12-09 18:57:45.545 ThaliTest[644:449813] multipeer session: start timer: 0x1a2ae0a0
2015-12-09 18:57:45.545 ThaliTest[644:449813] server session: connect
2015-12-09 18:57:45.546 ThaliTest[644:449813] server session: stateChange:0->1 1449683862381.622
,2015-12-09 18:57:45.551 ThaliTest[644:449813] server: accepting invitation 1449683862381.622
,2015-12-09 18:57:48.752 ThaliTest[644:450583] client session: connected
,2015-12-09 18:57:48.752 ThaliTest[644:450583] client session: stateChange:1->2 1449683862381.622.vuGzaA==
,2015-12-09 18:57:49.089 ThaliTest[644:450583] client session: fireConnectCallback: 1449683862381.622.vuGzaA==
2015-12-09 18:57:49.090 ThaliTest[644:450583] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-09 18:57:49.095 ThaliTest[644:450084] jxcore: disconnect
,2015-12-09 18:57:49.095 ThaliTest[644:450084] client session: disconnectFromPeer: 1449683862381.622.vuGzaA==
,2015-12-09 18:57:49.096 ThaliTest[644:450084] client session: disconnect
,2015-12-09 18:57:49.096 ThaliTest[644:450084] client session: stateChange:2->0 1449683862381.622.vuGzaA==
,2015-12-09 18:57:49.105 ThaliTest[644:450084] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-09 18:57:49.212 ThaliTest[644:450583] server session: connected
2015-12-09 18:57:49.212 ThaliTest[644:450583] server session: stateChange:1->2 1449683862381.622
,2015-12-09 18:57:49.219 ThaliTest[644:449813] server relay: socket disconnected
2015-12-09 18:57:49.219 ThaliTest[644:449813] server relay: 0x1a359f50 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-09 18:57:49.281 ThaliTest[644:450631] server session: not connected 1449683862381.622
,calling stopBroadcasting
,2015-12-09 18:57:49.583 ThaliTest[644:450084] jxcore: stopBroadcasting
2015-12-09 18:57:49.584 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:57:49.584 ThaliTest[644:450084] multipeer session: stop timer
2015-12-09 18:57:49.584 ThaliTest[644:450084] server session: disconnect
2015-12-09 18:57:49.585 ThaliTest[644:450084] server session: stateChange:2->0 1449683862381.622
2015-12-09 18:57:49.586 ThaliTest[644:450084] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-09 18:57:50.967 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:50.971 ThaliTest[644:450084] server: starting 1449683870966.644./y0MMw==
,2015-12-09 18:57:50.972 ThaliTest[644:450084] multipeer session: start timer: 0x1a1bf440
2015-12-09 18:57:50.973 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683870966.644
2015-12-09 18:57:50.973 ThaliTest[644:450084] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2015-12-09 18:57:51.864 ThaliTest[644:449813] client: found peer: 1449683869672.622.QYm7ZQ==
2015-12-09 18:57:51.866 ThaliTest[644:450084] jxcore: connect 1449683869672.622.QYm7ZQ==
,2015-12-09 18:57:51.867 ThaliTest[644:450084] client session: connect
,2015-12-09 18:57:51.867 ThaliTest[644:450084] client session: stateChange:0->1 1449683869672.622.QYm7ZQ==
,2015-12-09 18:57:52.423 ThaliTest[644:449813] multipeer session: reset timer
2015-12-09 18:57:52.424 ThaliTest[644:449813] multipeer session: stop timer
,2015-12-09 18:57:52.424 ThaliTest[644:449813] multipeer session: start timer: 0x1a1bf440
,2015-12-09 18:57:52.425 ThaliTest[644:449813] server session: connect
2015-12-09 18:57:52.425 ThaliTest[644:449813] server session: stateChange:0->1 1449683869672.622
,2015-12-09 18:57:52.431 ThaliTest[644:449813] server: accepting invitation 1449683869672.622
,2015-12-09 18:57:55.059 ThaliTest[644:450578] client session: connected
2015-12-09 18:57:55.060 ThaliTest[644:450578] client session: stateChange:1->2 1449683869672.622.QYm7ZQ==
,2015-12-09 18:57:55.073 ThaliTest[644:450578] server session: connected
2015-12-09 18:57:55.073 ThaliTest[644:450578] server session: stateChange:1->2 1449683869672.622
,2015-12-09 18:57:55.103 ThaliTest[644:450632] client session: fireConnectCallback: 1449683869672.622.QYm7ZQ==
2015-12-09 18:57:55.103 ThaliTest[644:450632] jxcore: connect: success
,2015-12-09 18:57:55.104 ThaliTest[644:449813] server relay: socket disconnected
2015-12-09 18:57:55.106 ThaliTest[644:449813] server relay: 0x1a1bdd90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2015-12-09 18:57:55.110 ThaliTest[644:450084] jxcore: connect 1449683869672.622.QYm7ZQ==
2015-12-09 18:57:55.111 ThaliTest[644:450084] client: already connect(ing/ed) to 1449683869672.622.QYm7ZQ==
2015-12-09 18:57:55.111 ThaliTest[644:450084] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2015-12-09 18:57:55.113 ThaliTest[644:450084] jxcore: disconnect
,2015-12-09 18:57:55.113 ThaliTest[644:450084] client session: disconnectFromPeer: 1449683869672.622.QYm7ZQ==
,2015-12-09 18:57:55.113 ThaliTest[644:450084] client session: disconnect
,2015-12-09 18:57:55.114 ThaliTest[644:450084] client session: stateChange:2->0 1449683869672.622.QYm7ZQ==
,2015-12-09 18:57:55.168 ThaliTest[644:450582] server session: not connected 1449683869672.622
,2015-12-09 18:57:55.180 ThaliTest[644:450084] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-09 18:57:55.333 ThaliTest[644:450084] jxcore: stopBroadcasting
,2015-12-09 18:57:55.333 ThaliTest[644:450084] THEMultipeerSession stopping peer
,2015-12-09 18:57:55.333 ThaliTest[644:450084] multipeer session: stop timer
,2015-12-09 18:57:55.335 ThaliTest[644:450084] server session: disconnect
2015-12-09 18:57:55.336 ThaliTest[644:450084] server session: stateChange:2->0 1449683869672.622
,2015-12-09 18:57:55.338 ThaliTest[644:450084] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-09 18:57:56.137 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:57:56.141 ThaliTest[644:450084] server: starting 1449683876137.644.Z5FaWQ==
,2015-12-09 18:57:56.142 ThaliTest[644:450084] multipeer session: start timer: 0x16550df0
,2015-12-09 18:57:56.143 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683876137.644
,2015-12-09 18:57:56.144 ThaliTest[644:450084] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2015-12-09 18:57:57.539 ThaliTest[644:449813] multipeer session: reset timer
2015-12-09 18:57:57.540 ThaliTest[644:449813] multipeer session: stop timer
2015-12-09 18:57:57.540 ThaliTest[644:449813] multipeer session: start timer: 0x16550df0
,2015-12-09 18:57:57.540 ThaliTest[644:449813] server session: connect
2015-12-09 18:57:57.541 ThaliTest[644:449813] server session: stateChange:0->1 1449683875092.622
,2015-12-09 18:57:57.547 ThaliTest[644:449813] server: accepting invitation 1449683875092.622
,2015-12-09 18:57:57.555 ThaliTest[644:449813] client: found peer: 1449683875092.622.6ELNYA==
,2015-12-09 18:57:57.557 ThaliTest[644:450084] jxcore: connect 1449683875092.622.6ELNYA==
2015-12-09 18:57:57.557 ThaliTest[644:450084] client session: connect
2015-12-09 18:57:57.557 ThaliTest[644:450084] client session: stateChange:0->1 1449683875092.622.6ELNYA==
,2015-12-09 18:58:00.354 ThaliTest[644:450582] server session: connected
2015-12-09 18:58:00.354 ThaliTest[644:450582] server session: stateChange:1->2 1449683875092.622
,2015-12-09 18:58:00.378 ThaliTest[644:449813] server relay: socket disconnected
2015-12-09 18:58:00.378 ThaliTest[644:449813] server relay: 0x1a35eb50 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-09 18:58:00.416 ThaliTest[644:450578] server session: not connected 1449683875092.622
,2015-12-09 18:58:00.556 ThaliTest[644:450631] client session: connected
2015-12-09 18:58:00.556 ThaliTest[644:450631] client session: stateChange:1->2 1449683875092.622.6ELNYA==
,2015-12-09 18:58:00.572 ThaliTest[644:450578] client session: fireConnectCallback: 1449683875092.622.6ELNYA==
2015-12-09 18:58:00.572 ThaliTest[644:450578] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2015-12-09 18:58:00.576 ThaliTest[644:450084] jxcore: disconnect
,2015-12-09 18:58:00.577 ThaliTest[644:450084] client session: disconnectFromPeer: 1449683875092.622.6ELNYA==
2015-12-09 18:58:00.577 ThaliTest[644:450084] client session: disconnect
2015-12-09 18:58:00.578 ThaliTest[644:450084] client session: stateChange:2->0 1449683875092.622.6ELNYA==
,2015-12-09 18:58:00.647 ThaliTest[644:450084] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2015-12-09 18:58:00.650 ThaliTest[644:450084] jxcore: disconnect
,2015-12-09 18:58:00.651 ThaliTest[644:450084] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-09 18:58:01.052 ThaliTest[644:450084] jxcore: stopBroadcasting
,2015-12-09 18:58:01.053 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:58:01.053 ThaliTest[644:450084] multipeer session: stop timer
,2015-12-09 18:58:01.054 ThaliTest[644:450084] server session: disconnect
2015-12-09 18:58:01.054 ThaliTest[644:450084] server session: stateChange:2->0 1449683875092.622
2015-12-09 18:58:01.055 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-09 18:58:02.113 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:58:02.116 ThaliTest[644:450084] server: starting 1449683882113.644.Gl5U4g==
,2015-12-09 18:58:02.117 ThaliTest[644:450084] multipeer session: start timer: 0x1a1c2460
2015-12-09 18:58:02.118 ThaliTest[644:450084] THEMultipeerSession initialized peer 1449683882113.644
2015-12-09 18:58:02.118 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
echo server started
,2015-12-09 18:58:03.259 ThaliTest[644:449813] client: found peer: 1449683880874.622.t8LlVA==
,[{"peerIdentifier":"1449683880874.622.t8LlVA==","peerName":"(null)","peerAvailable":true}]
,2015-12-09 18:58:03.262 ThaliTest[644:450084] jxcore: connect 1449683880874.622.t8LlVA==
,2015-12-09 18:58:03.263 ThaliTest[644:450084] client session: connect
,2015-12-09 18:58:03.264 ThaliTest[644:450084] client session: stateChange:0->1 1449683880874.622.t8LlVA==
,2015-12-09 18:58:03.556 ThaliTest[644:449813] multipeer session: reset timer
2015-12-09 18:58:03.556 ThaliTest[644:449813] multipeer session: stop timer
2015-12-09 18:58:03.556 ThaliTest[644:449813] multipeer session: start timer: 0x1a1c2460
,2015-12-09 18:58:03.557 ThaliTest[644:449813] server session: connect
2015-12-09 18:58:03.557 ThaliTest[644:449813] server session: stateChange:0->1 1449683880874.622
,2015-12-09 18:58:03.563 ThaliTest[644:449813] server: accepting invitation 1449683880874.622
,2015-12-09 18:58:06.074 ThaliTest[644:450582] client session: connected
2015-12-09 18:58:06.074 ThaliTest[644:450582] client session: stateChange:1->2 1449683880874.622.t8LlVA==
,2015-12-09 18:58:06.094 ThaliTest[644:450578] client session: fireConnectCallback: 1449683880874.622.t8LlVA==
2015-12-09 18:58:06.094 ThaliTest[644:450578] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
,2015-12-09 18:58:06.134 ThaliTest[644:449813] client: relay established
2015-12-09 18:58:06.134 ThaliTest[644:449813] client: new accepted socket: 0x1a2b8930
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2015-12-09 18:58:06.201 ThaliTest[644:449813] client: socket closed
2015-12-09 18:58:06.202 ThaliTest[644:449813] client relay: socket disconnected
,2015-12-09 18:58:06.202 ThaliTest[644:449813] client relay: 0x1a2b8930 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-09 18:58:06.202 ThaliTest[644:449813] client session: socket closed: 1449683880874.622.t8LlVA==
2015-12-09 18:58:06.202 ThaliTest[644:449813] client session: onLinkFailure: 1449683880874.622.t8LlVA==
2015-12-09 18:58:06.203 ThaliTest[644:449813] client session: disconnect
,2015-12-09 18:58:06.203 ThaliTest[644:449813] client session: stateChange:2->0 1449683880874.622.t8LlVA==
,2015-12-09 18:58:06.266 ThaliTest[644:449813] client session: fireConnectionErrorEvent: 1449683880874.622.t8LlVA==
,2015-12-09 18:58:06.268 ThaliTest[644:450084] jxcore: connect 1449683880874.622.t8LlVA==
,2015-12-09 18:58:06.268 ThaliTest[644:450084] client session: connect
,2015-12-09 18:58:06.269 ThaliTest[644:450084] client session: stateChange:0->1 1449683880874.622.t8LlVA==
,2015-12-09 18:58:06.517 ThaliTest[644:450632] server session: connected
,2015-12-09 18:58:06.519 ThaliTest[644:450632] server session: stateChange:1->2 1449683880874.622
,2015-12-09 18:58:06.576 ThaliTest[644:449813] server relay: connected (to port: 5001)
,2015-12-09 18:58:06.855 ThaliTest[644:450723] server session: not connected 1449683880874.622
,2015-12-09 18:58:06.880 ThaliTest[644:449813] multipeer session: reset timer
2015-12-09 18:58:06.880 ThaliTest[644:449813] multipeer session: stop timer
2015-12-09 18:58:06.880 ThaliTest[644:449813] multipeer session: start timer: 0x1a1c2460
2015-12-09 18:58:06.880 ThaliTest[644:449813] server: disconnecting to refresh session (1449683880874.622)
2015-12-09 18:58:06.881 ThaliTest[644:449813] server session: disconnect
2015-12-09 18:58:06.881 ThaliTest[644:449813] server session: stateChange:2->0 1449683880874.622
,2015-12-09 18:58:07.077 ThaliTest[644:449813] server session: connect
2015-12-09 18:58:07.077 ThaliTest[644:449813] server session: stateChange:0->1 1449683880874.622
,2015-12-09 18:58:07.079 ThaliTest[644:449813] server: accepting invitation 1449683880874.622
,2015-12-09 18:58:09.271 ThaliTest[644:450723] client session: connected
2015-12-09 18:58:09.271 ThaliTest[644:450723] client session: stateChange:1->2 1449683880874.622.t8LlVA==
,2015-12-09 18:58:09.454 ThaliTest[644:450582] client session: fireConnectCallback: 1449683880874.622.t8LlVA==
2015-12-09 18:58:09.454 ThaliTest[644:450582] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 Second connect should succeed
,2015-12-09 18:58:09.484 ThaliTest[644:449813] client: relay established
2015-12-09 18:58:09.485 ThaliTest[644:449813] client: new accepted socket: 0x1a2c3530
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2015-12-09 18:58:09.753 ThaliTest[644:449813] client: socket closed
,2015-12-09 18:58:09.754 ThaliTest[644:449813] client relay: socket disconnected
,2015-12-09 18:58:09.755 ThaliTest[644:449813] client relay: 0x1a2c3530 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-09 18:58:09,.755 ThaliTest[644:449813] client session: socket closed: 1449683880874.622.t8LlVA==
2015-12-09 18:58:09.755 ThaliTest[644:449813] client session: onLinkFailure: 1449683880874.622.t8LlVA==
,2015-12-09 18:58:09.755 ThaliTest[644:449813] client session: disconnect
2015-12-09 18:58:09.756 ThaliTest[644:449813] client session: stateChange:2->0 1449683880874.622.t8LlVA==
,2015-12-09 18:58:09.763 ThaliTest[644:449813] client session: fireConnectionErrorEvent: 1449683880874.622.t8LlVA==
,2015-12-09 18:58:09.839 ThaliTest[644:450578] server session: connected
,2015-12-09 18:58:09.839 ThaliTest[644:450578] server session: stateChange:1->2 1449683880874.622
,2015-12-09 18:58:09.866 ThaliTest[644:449813] server relay: connected (to port: 5001)
,2015-12-09 18:58:10.023 ThaliTest[644:450723] server session: not connected 1449683880874.622
,calling stopBroadcasting
,2015-12-09 18:58:10.059 ThaliTest[644:450084] jxcore: stopBroadcasting
,2015-12-09 18:58:10.060 ThaliTest[644:450084] THEMultipeerSession stopping peer
,2015-12-09 18:58:10.060 ThaliTest[644:450084] multipeer session: stop timer
,2015-12-09 18:58:10.061 ThaliTest[644:450084] server session: disconnect
2015-12-09 18:58:10.062 ThaliTest[644:450084] server session: stateChange:2->0 1449683880874.622
,2015-12-09 18:58:10.070 ThaliTest[644:450084] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/23D8B2FE-A798-4DC1-A946-04DDF499A949/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2015-12-09 18:58:11.670 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:58:11.672 ThaliTest[644:450084] server: starting zLbf_xbSFfpxjYL9n16uFQ.d9PBHQ==
,2015-12-09 18:58:11.673 ThaliTest[644:450084] multipeer session: start timer: 0x1a35e140
2015-12-09 18:58:11.673 ThaliTest[644:450084] THEMultipeerSession initialized peer zLbf_xbSFfpxjYL9n16uFQ
2015-12-09 18:58:11.673 ThaliTest[644:450084] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
,Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should occur in right order
About to call stopBroadcasting
,2015-12-09 18:58:11.676 ThaliTest[644:450084] jxcore: stopBroadcasting
2015-12-09 18:58:11.677 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:58:11.677 ThaliTest[644:450084] multipeer session: stop timer
2015-12-09 18:58:11.677 Th,aliTest[644:450084] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,ok 102 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/23D8B2FE-A798-4DC1-A946-04DDF499A949/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2015-12-09 18:58:12.242 ThaliTest[644:450084] jxcore: startBroadcasting
,2015-12-09 18:58:12.244 ThaliTest[644:450084] server: starting zLbf_xbSFfpxjYL9n16uFQ.+FAzzw==
,2015-12-09 18:58:12.245 ThaliTest[644:450084] multipeer session: start timer: 0x1a372360
,2015-12-09 18:58:12.245 ThaliTest[644:450084] THEMultipeerSession initialized peer zLbf_xbSFfpxjYL9n16uFQ
,2015-12-09 18:58:12.246 ThaliTest[644:450084] jxcore: startBroadcasting: success
,ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
Now in TRM stop
State of this._isStarted: true
,About to call stopBroadcasting
,2015-12-09 18:58:12.249 ThaliTest[644:450084] jxcore: stopBroadcasting
2015-12-09 18:58:12.250 ThaliTest[644:450084] THEMultipeerSession stopping peer
2015-12-09 18:58:12.250 ThaliTest[644:450084] multipeer session: stop timer
2015-12-09 18:58:12.250 ThaliTest[644:450084] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
,Tests Complete

```
