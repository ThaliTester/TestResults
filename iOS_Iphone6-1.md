#### Test 50650278c17c777_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c17c777/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/BD0F0407-01A0-43E8-920E-CA97AD1144F2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BD0F0407-01A0-43E8-920E-CA97AD1144F2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c17c777/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c17c777/build_ios/ThaliTest.app' (armv7).
,(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AAAB614D-6B52-49A3-BED2-D256986453F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52929"
,(lldb)     command script import "/tmp/BD0F0407-01A0-43E8-920E-CA97AD1144F2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 12:15:38.242 ThaliTest[656:557299] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/922A697F-5A7F-47EA-A04D-F47E381C4862/Library/Cookies/Cookies.binarycookies
,2015-12-10 12:15:38.605 ThaliTest[656:557299] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 12:15:38.606 ThaliTest[656:557299] Multi-tasking -> Device: YES, App: YES
,2015-12-10 12:15:38.616 ThaliTest[656:557299] Unlimited access to network resources
,2015-12-10 12:15:38.627 ThaliTest[656:557299] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 12:15:47.584 ThaliTest[656:557299] Resetting plugins due to page load.
,2015-12-10 12:15:51.330 ThaliTest[656:557299] Finished load of: file:///var/mobile/Containers/Bundle/Application/AAAB614D-6B52-49A3-BED2-D256986453F4/ThaliTest.app/www/index.html
,2015-12-10 12:15:51.514 ThaliTest[656:557299] JXcore Cordova plugin initializing
,2015-12-10 12:15:51.515 ThaliTest[656:557600] JXcore instance initializing
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
ok 13 should be equal
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
,2015-12-10 12:21:25.645 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:25.659 ThaliTest[656:557600] server: starting 1449746485644.656.0Mwsww==
,2015-12-10 12:21:25.661 ThaliTest[656:557600] multipeer session: start timer: 0x1a0f1460
2015-12-10 12:21:25.662 ThaliTest[656:557600] THEMultipeerSession initialized peer 1449746485644.656
2015-12-10 12:21:25.663 ThaliTest[656:557600] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2015-12-10 12:21:25.669 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12:21:25.670 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:21:25.670 ThaliTest[656:557,600] multipeer session: stop timer
2015-12-10 12:21:25.670 ThaliTest[656:557600] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2015-12-10 12:21:25.679 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:25.693 ThaliTest[656:557600] server: starting 1449746485678.656.ERGsog==
2015-12-10 12:21:25.694 ThaliTest[656:557600] multipeer session: start timer: 0x1a1ae440
2015-12-10 12:21:25.695 ThaliTest[656:557600] THEMultipeerSession initializ,ed peer 1449746485678.656
2015-12-10 12:21:25.695 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2015-12-10 12:21:25.698 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12:21:25.699 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:21:25.699 ThaliTest[656:557600] multipeer session: stop timer
2015-12-10 12:21:25.699 Th,aliTest[656:557600] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2015-12-10 12:21:25.701 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:25.706 ThaliTest[656:557600] server: starting 1449746485701.656.NSd5vQ==
2015-12-10 12:21:25.707 ThaliTest[656:557600] multipeer session: start timer: 0x1a1ae440
2015-12-10 12:21:25.708 ThaliTest[656:557600] THEMultipeerSession initializ,ed peer 1449746485701.656
2015-12-10 12:21:25.708 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2015-12-10 12:21:25.711 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12,:21:25.711 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:21:25.711 ThaliTest[656:557600] multipeer session: stop timer
2015-12-10 12:21:25.711 ThaliTest[656:557600] jxcore: stopBroadcasting: success
ok 50 Should be able to call s,topBroadcasting without error
2015-12-10 12:21:25.713 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:25.728 ThaliTest[656:557600] server: starting 1449746485713.656.WTTotA==
2015-12-10 12:21:25.731 ThaliTest[656:557600] multipeer session: start timer: 0x1a1b0eb0
,2015-12-10 12:21:25.733 ThaliTest[656:557600] THEMultipeerSession initialized peer 1449746485713.656
2015-12-10 12:21:25.735 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-10, 12:21:25.738 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12:21:25.738 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:21:25.739 ThaliTest[656:557600] multipeer session: stop timer
2015-12-10 12:21:25.739 ThaliTest[65,6:557600] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2015-12-10 12:21:25.741 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:25.748 ThaliTest[656:557600] server: starting 1449746485741.656.A7+3CA==
2015-12-10 12:21:25.748 ThaliTest[656:557600] multipeer session: start timer: 0x1a0f56a0
2015-12-10 12:21:25.748 ThaliTest[656:557600] THEMultipeerSession initializ,ed peer 1449746485741.656
2015-12-10 12:21:25.749 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2015-12-10 12:21:25.750 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12,:21:25.750 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:21:25.750 ThaliTest[656:557600] multipeer session: stop timer
2015-12-10 12:21:25.750 ThaliTest[656:557600] jxcore: stopBroadcasting: success
ok 54 Should be able to call s,topBroadcasting without error
2015-12-10 12:21:25.752 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:25.759 ThaliTest[656:557600] server: starting 1449746485751.656.EIkWvA==
2015-12-10 12:21:25.759 ThaliTest[656:557600] multipeer session: start timer: 0x1a1b2730
2015-12-10 12:21:25.760 ThaliTest[656:557600] THEMultipeerSession initializ,ed peer 1449746485751.656
2015-12-10 12:21:25.760 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2015-12-10 12:21:25.762 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12,:21:25.762 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:21:25.762 ThaliTest[656:557600] multipeer session: stop timer
2015-12-10 12:21:25.762 ThaliTest[656:557600] jxcore: stopBroadcasting: success
ok 56 Should be able to call s,topBroadcasting without error
2015-12-10 12:21:25.764 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:25.769 ThaliTest[656:557600] server: starting 1449746485764.656.P/9UsQ==
2015-12-10 12:21:25.770 ThaliTest[656:557600] multipeer session: start timer: 0x1a1b2850
2015-12-10 12:21:25.770 ThaliTest[656:557600] THEMultipeerSession initialized peer 1449746485764.656
,2015-12-10 12:21:25.770 ThaliTest[656:557600] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-10 12:21:25.786 ThaliTest[656:557600] jxcore: stopBroadcasting
,2015-12-10 12:21:25.787 ThaliTest[656:557600] THEMultipeerSession stopping peer
,2015-12-10 12:21:25.788 ThaliTest[656:557600] multipeer session: stop timer
,2015-12-10 12:21:25.790 ThaliTest[656:557600] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-10 12:21:25.795 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:25.797 ThaliTest[656:557600] server: starting 1449746485795.656.ucP9PA==
,2015-12-10 12:21:25.798 ThaliTest[656:557600] multipeer session: start timer: 0x1a0f5190
,2015-12-10 12:21:25.801 ThaliTest[656:557600] THEMultipeerSession initialized peer 1449746485795.656
,2015-12-10 12:21:25.804 ThaliTest[656:557600] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-10 12:21:25.807 ThaliTest[656:557600] jxcore: stopBroadcasting
,2015-12-10 12:21:25.807 ThaliTest[656:557600] THEMultipeerSession stopping peer
,2015-12-10 12:21:25.808 ThaliTest[656:557600] multipeer session: stop timer
,2015-12-10 12:21:25.809 ThaliTest[656:557600] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-10 12:21:25.816 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:25.819 ThaliTest[656:557600] server: starting 1449746485816.656.Jf+Cpw==
,2015-12-10 12:21:25.821 ThaliTest[656:557600] multipeer session: start timer: 0x1a0f3e80
,2015-12-10 12:21:25.823 ThaliTest[656:557600] THEMultipeerSession initialized peer 1449746485816.656
,2015-12-10 12:21:25.824 ThaliTest[656:557600] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-10 12:21:25.829 ThaliTest[656:557600] jxcore: stopBroadcasting
,2015-12-10 12:21:25.830 ThaliTest[656:557600] THEMultipeerSession stopping peer
,2015-12-10 12:21:25.831 ThaliTest[656:557600] multipeer session: stop timer
,2015-12-10 12:21:25.832 ThaliTest[656:557600] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-10 12:21:25.838 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:25.840 ThaliTest[656:557600] server: starting 1449746485837.656.m7PU/w==
,2015-12-10 12:21:25.842 ThaliTest[656:557600] multipeer session: start timer: 0x1a1b2e10
,2015-12-10 12:21:25.846 ThaliTest[656:557600] THEMultipeerSession initialized peer 1449746485837.656
,2015-12-10 12:21:25.848 ThaliTest[656:557600] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-10 12:21:25.850 ThaliTest[656:557600] jxcore: stopBroadcasting
,2015-12-10 12:21:25.850 ThaliTest[656:557600] THEMultipeerSession stopping peer
,2015-12-10 12:21:25.851 ThaliTest[656:557600] multipeer session: stop timer
,2015-12-10 12:21:25.852 ThaliTest[656:557600] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-10 12:21:26.141 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:26.146 ThaliTest[656:557600] server: starting 1449746486141.656.T8QGsA==
,2015-12-10 12:21:26.148 ThaliTest[656:557600] multipeer session: start timer: 0x1a0f4310
,2015-12-10 12:21:26.153 ThaliTest[656:557600] THEMultipeerSession initialized peer 1449746486141.656
,2015-12-10 12:21:26.158 ThaliTest[656:557600] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2015-12-10 12:21:26.162 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:26.163 ThaliTest[656:557600] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2015-12-10 12:21:26.168 ThaliTest[656:557600] jxcore: stopBroadcasting
,2015-12-10 12:21:26.169 ThaliTest[656:557600] THEMultipeerSession stopping peer
,2015-12-10 12:21:26.170 ThaliTest[656:557600] multipeer session: stop timer
,2015-12-10 12:21:26.174 ThaliTest[656:557600] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-10 12:21:26.650 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:26.654 ThaliTest[656:557600] server: starting 1449746486650.656.zXZe9g==
2015-12-10 12:21:26.655 ThaliTest[656:557600] multipeer session: start timer: 0x1a0f4f20
2015-12-10 12:21:26.655 ThaliTest[656:557600] THEMultipeerSession initializ,ed peer 1449746486650.656
2015-12-10 12:21:26.655 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-10 12:21:26.658 ThaliTest[656:557600] jxcore: connect foobar
2015-12-10 12:2,1:26.658 ThaliTest[656:557600] client: unknown peer foobar
2015-12-10 12:21:26.658 ThaliTest[656:557600] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2015-12-10 12:21:26.661 ThaliTest[656:557600] jxcore: stopBroadcasting
,2015-12-10 12:21:26.662 ThaliTest[656:557600] THEMultipeerSession stopping peer
,2015-12-10 12:21:26.668 ThaliTest[656:557600] multipeer session: stop timer
,2015-12-10 12:21:26.676 ThaliTest[656:557600] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-10 12:21:27.249 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:27.253 ThaliTest[656:557600] server: starting 1449746487249.656.FIETzg==
2015-12-10 12:21:27.254 ThaliTest[656:557600] multipeer session: start timer: 0x1a0708d0
2015-12-10 12:21:27.254 ThaliTest[656:557600] THEMultipeerSession initializ,ed peer 1449746487249.656
2015-12-10 12:21:27.255 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
,2015-12-10 12:21:27.257 ThaliTest[656:557600] jxcore: disconnect
2015-12-10 12:21:27.258 ThaliTest[656:557600] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
2015-12-10 12:21:27.261 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12:21:27.262 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:21:27.262 ThaliTest[656:557600] mul,tipeer session: stop timer
2015-12-10 12:21:27.263 ThaliTest[656:557600] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-10 12:21:27.715 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:27.719 ThaliTest[656:557600] server: starting 1449746487715.656.yfLGbQ==
2015-12-10 12:21:27.719 ThaliTest[656:557600] multipeer session: start timer: 0x1a1bfe30
2015-12-10 12:21:27.720 ThaliTest[656:557600] THEMultipeerSession initializ,ed peer 1449746487715.656
2015-12-10 12:21:27.720 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2015-12-10 12:21:28.860 ThaliTest[656:557299] client: found peer: 1449746489968.690.ts45FQ==
2015-12-10 12:21:28.862 ThaliTest[656:557600] jxcore: connect 1449746489968.690.ts45FQ==
,2015-12-10 12:21:28.863 ThaliTest[656:557600] client session: connect
2015-12-10 12:21:28.863 ThaliTest[656:557600] client session: stateChange:0->1 1449746489968.690.ts45FQ==
,2015-12-10 12:21:29.772 ThaliTest[656:557299] multipeer session: reset timer
2015-12-10 12:21:29.772 ThaliTest[656:557299] multipeer session: stop timer
2015-12-10 12:21:29.773 ThaliTest[656:557299] multipeer session: start timer: 0x1a1bfe30
2015-12-10 ,12:21:29.773 ThaliTest[656:557299] server session: connect
2015-12-10 12:21:29.773 ThaliTest[656:557299] server session: stateChange:0->1 1449746489968.690
,2015-12-10 12:21:29.783 ThaliTest[656:557299] server: accepting invitation 1449746489968.690
,2015-12-10 12:21:31.688 ThaliTest[656:558176] client session: connected
2015-12-10 12:21:31.689 ThaliTest[656:558176] client session: stateChange:1->2 1449746489968.690.ts45FQ==
,2015-12-10 12:21:31.706 ThaliTest[656:558174] client session: fireConnectCallback: 1449746489968.690.ts45FQ==
2015-12-10 12:21:31.706 ThaliTest[656:558174] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-10 12:21:31.712 ThaliTest[656:557600] jxcore: disconnect
2015-12-10 12:21:31.713 ThaliTest[656:557600] client session: disconnectFromPeer: 1449746489968.690.ts45FQ==
2015-12-10 12:21:31.713 ThaliTest[656:557600] client session: disconnect
2015-1,2-10 12:21:31.713 ThaliTest[656:557600] client session: stateChange:2->0 1449746489968.690.ts45FQ==
,2015-12-10 12:21:31.726 ThaliTest[656:557600] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-10 12:21:32.312 ThaliTest[656:558174] server session: connected
2015-12-10 12:21:32.313 ThaliTest[656:558174] server session: stateChange:1->2 1449746489968.690
,2015-12-10 12:21:32.330 ThaliTest[656:557299] server relay: socket disconnected
2015-12-10 12:21:32.331 ThaliTest[656:557299] server relay: 0x1a1c1bb0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 12:21:32.382 ThaliTest[656:558186] server session: not connected 1449746489968.690
,2015-12-10 12:21:33.716 ThaliTest[656:557299] client: lost peer: 1449746489968.690.ts45FQ==
2015-12-10 12:21:33.716 ThaliTest[656:557299] client session: onPeerLost: 1449746489968.690.ts45FQ==
,calling stopBroadcasting
,2015-12-10 12:21:33.933 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12:21:33.934 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:21:33.934 ThaliTest[656:557600] multipeer session: stop timer
2015-12-10 12:21:33.935 Th,aliTest[656:557600] server session: disconnect
2015-12-10 12:21:33.935 ThaliTest[656:557600] server session: stateChange:2->0 1449746489968.690
2015-12-10 12:21:33.936 ThaliTest[656:557600] jxcore: stopBroadcasting: success
stopBroadcasting returned und,efined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-10 12:21:34.589 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:21:34.592 ThaliTest[656:557600] server: starting 1449746494588.656.DS2djg==
2015-12-10 12:21:34.593 ThaliTest[656:557600] multipeer session: start timer: 0x1a06cab0
2015-12-10 12:21:34.594 ThaliTest[656:557600] THEMultipeerSession initializ,ed peer 1449746494588.656
2015-12-10 12:21:34.594 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2015-12-10 12:21:35.732 ThaliTest[656:557299] client: found peer: 1449746496843.690.bUZAvw==
,2015-12-10 12:21:35.733 ThaliTest[656:557600] jxcore: connect 1449746496843.690.bUZAvw==
2015-12-10 12:21:35.734 ThaliTest[656:557600] client session: connect
2015-12-10 12:21:35.735 ThaliTest[656:557600] client session: stateChange:0->1 1449746496843.690.bUZAvw==
,2015-12-10 12:21:36.160 ThaliTest[656:557299] multipeer session: reset timer
2015-12-10 12:21:36.161 ThaliTest[656:557299] multipeer session: stop timer
2015-12-10 12:21:36.161 ThaliTest[656:557299] multipeer session: start timer: 0x1a06cab0
2015-12-10 ,12:21:36.161 ThaliTest[656:557299] server session: connect
2015-12-10 12:21:36.162 ThaliTest[656:557299] server session: stateChange:0->1 1449746496843.690
,2015-12-10 12:21:36.169 ThaliTest[656:557299] server: accepting invitation 1449746496843.690
,2015-12-10 12:21:38.697 ThaliTest[656:558176] server session: connected
,2015-12-10 12:21:38.699 ThaliTest[656:558176] server session: stateChange:1->2 1449746496843.690
,2015-12-10 12:21:38.741 ThaliTest[656:557299] server relay: socket disconnected
,2015-12-10 12:21:38.742 ThaliTest[656:557299] server relay: 0x1a1c6390 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 12:21:38.822 ThaliTest[656:558174] client session: connected
,2015-12-10 12:21:38.823 ThaliTest[656:558174] client session: stateChange:1->2 1449746496843.690.bUZAvw==
,2015-12-10 12:21:38.827 ThaliTest[656:558178] server session: not connected 1449746496843.690
,2015-12-10 12:21:38.834 ThaliTest[656:558174] client session: fireConnectCallback: 1449746496843.690.bUZAvw==
,2015-12-10 12:21:38.835 ThaliTest[656:558174] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2015-12-10 12:21:38.841 ThaliTest[656:557600] jxcore: connect 1449746496843.690.bUZAvw==
,2015-12-10 12:21:38.842 ThaliTest[656:557600] client: already connect(ing/ed) to 1449746496843.690.bUZAvw==
,2015-12-10 12:21:38.843 ThaliTest[656:557600] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2015-12-10 12:21:38.848 ThaliTest[656:557600] jxcore: disconnect
2015-12-10 12:21:38.848 ThaliTest[656:557600] client session: disconnectFromPeer: 1449746496843.690.bUZAvw==
,2015-12-10 12:21:38.848 ThaliTest[656:557600] client session: disconnect
,2015-12-10 12:21:38.850 ThaliTest[656:557600] client session: stateChange:2->0 1449746496843.690.bUZAvw==
,2015-12-10 12:21:38.929 ThaliTest[656:557600] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-10 12:21:39.264 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12:21:39.264 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:21:39.265 ThaliTest[656:557600] multipeer session: stop timer
2015-12-10 12:21:39.265 Th,aliTest[656:557600] server session: disconnect
2015-12-10 12:21:39.266 ThaliTest[656:557600] server session: stateChange:2->0 1449746496843.690
2015-12-10 12:21:39.267 ThaliTest[656:557600] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-10 12:22:36.405 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:22:36.409 ThaliTest[656:557600] server: starting 1449746556404.656.kXXqfg==
2015-12-10 12:22:36.409 ThaliTest[656:557600] multipeer session: start timer: 0x1a093990
2015-12-10 12:22:36.410 ThaliTest[656:557600] THEMultipeerSession initialized peer 1449746556404.656
2015-12-10 12:22:36.410 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2015-12-10 12:22:37.727 ThaliTest[656:557299] client: found peer: 1449746558828.690.o7lGwQ==
,2015-12-10 12:22:37.729 ThaliTest[656:557600] jxcore: connect 1449746558828.690.o7lGwQ==
2015-12-10 12:22:37.730 ThaliTest[656:557600] client session: connect
2015-12-10 12:22:37.730 ThaliTest[656:557600] client session: stateChange:0->1 1449746558828.690.o7lGwQ==
,2015-12-10 12:22:37.835 ThaliTest[656:557299] multipeer session: reset timer
2015-12-10 12:22:37.836 ThaliTest[656:557299] multipeer session: stop timer
2015-12-10 12:22:37.836 ThaliTest[656:557299] multipeer session: start timer: 0x1a093990
2015-12-10 ,12:22:37.837 ThaliTest[656:557299] server session: connect
2015-12-10 12:22:37.837 ThaliTest[656:557299] server session: stateChange:0->1 1449746558828.690
,2015-12-10 12:22:37.847 ThaliTest[656:557299] server: accepting invitation 1449746558828.690
,2015-12-10 12:22:40.395 ThaliTest[656:558627] client session: connected
2015-12-10 12:22:40.396 ThaliTest[656:558627] client session: stateChange:1->2 1449746558828.690.o7lGwQ==
,2015-12-10 12:22:40.407 ThaliTest[656:558627] server session: connected
2015-12-10 12:22:40.408 ThaliTest[656:558627] server session: stateChange:1->2 1449746558828.690
,2015-12-10 12:22:40.423 ThaliTest[656:558628] client session: fireConnectCallback: 1449746558828.690.o7lGwQ==
2015-12-10 12:22:40.424 ThaliTest[656:558628] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
2015-12-10 12:22:40.428 ThaliTest[656:557600] jxcore: disconnect
,2015-12-10 12:22:40.429 ThaliTest[656:557600] client session: disconnectFromPeer: 1449746558828.690.o7lGwQ==
2015-12-10 12:22:40.429 ThaliTest[656:557600] client session: disconnect
,2015-12-10 12:22:40.430 ThaliTest[656:557600] client session: stateChange:2->0 1449746558828.690.o7lGwQ==
,2015-12-10 12:22:40.438 ThaliTest[656:557299] server relay: socket disconnected
,2015-12-10 12:22:40.439 ThaliTest[656:557299] server relay: 0x1a062770 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 12:22:40.468 ThaliTest[656:558626] server session: not connected 1449746558828.690
,2015-12-10 12:22:40.473 ThaliTest[656:557600] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2015-12-10 12:22:40.475 ThaliTest[656:557600] jxcore: disconnect
,2015-12-10 12:22:40.476 ThaliTest[656:557600] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-10 12:22:41.326 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12:22:41.326 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:22:41.326 ThaliTest[656:557600] multipeer session: stop timer
2015-12-10 12:22:41.327 Th,aliTest[656:557600] server session: disconnect
2015-12-10 12:22:41.327 ThaliTest[656:557600] server session: stateChange:2->0 1449746558828.690
2015-12-10 12:22:41.328 ThaliTest[656:557600] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-10 12:22:41.771 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:22:41.775 ThaliTest[656:557600] server: starting 1449746561771.656.BPhKwQ==
2015-12-10 12:22:41.776 ThaliTest[656:557600] multipeer session: start timer: 0x1a0600f0
2015-12-10 12:22:41.776 ThaliTest[656:557600] THEMultipeerSession initializ,ed peer 1449746561771.656
2015-12-10 12:22:41.776 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2015-12-10 12:22:42.971 ThaliTest[656:557299] client: found peer: 1449746564029.690.awV4UA==
[{"peerIdentifier":"1449746564029.690.awV4UA==","peerName":"(null)","peerAvailable":true}]
2015-12-10 12:22:42.974 ThaliTest[656:557600] jxcore: connect 14497465,64029.690.awV4UA==
2015-12-10 12:22:42.975 ThaliTest[656:557600] client session: connect
2015-12-10 12:22:42.975 ThaliTest[656:557600] client session: stateChange:0->1 1449746564029.690.awV4UA==
,2015-12-10 12:22:43.013 ThaliTest[656:557299] multipeer session: reset timer
2015-12-10 12:22:43.014 ThaliTest[656:557299] multipeer session: stop timer
2015-12-10 12:22:43.014 ThaliTest[656:557299] multipeer session: start timer: 0x1a0600f0
,2015-12-10 12:22:43.014 ThaliTest[656:557299] server session: connect
,2015-12-10 12:22:43.020 ThaliTest[656:557299] server session: stateChange:0->1 1449746564029.690
,2015-12-10 12:22:43.036 ThaliTest[656:557299] server: accepting invitation 1449746564029.690
,2015-12-10 12:22:45.596 ThaliTest[656:558656] server session: connected
2015-12-10 12:22:45.598 ThaliTest[656:558656] server session: stateChange:1->2 1449746564029.690
,2015-12-10 12:22:45.615 ThaliTest[656:557299] server relay: connected (to port: 5001)
,2015-12-10 12:22:45.656 ThaliTest[656:558627] client session: connected
,2015-12-10 12:22:45.657 ThaliTest[656:558627] client session: stateChange:1->2 1449746564029.690.awV4UA==
2015-12-10 12:22:45.662 ThaliTest[656:558627] client session: fireConnectCallback: 1449746564029.690.awV4UA==
2015-12-10 12:22:45.663 ThaliTest[656:558627] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
,ok 91 First connect should succeed
,2015-12-10 12:22:45.723 ThaliTest[656:557299] client: relay established
2015-12-10 12:22:45.723 ThaliTest[656:557299] client: new accepted socket: 0x1a0584d0
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2015-12-10 12:22:45.792 ThaliTest[656:557299] client: socket closed
,2015-12-10 12:22:45.793 ThaliTest[656:557299] client relay: socket disconnected
2015-12-10 12:22:45.793 ThaliTest[656:557299] client relay: 0x1a0584d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-10 12:22:45.793 ThaliTest[656:557299] client session: socket closed: 1449746564029.690.awV4UA==
,2015-12-10 12:22:45.794 ThaliTest[656:557299] client session: onLinkFailure: 1449746564029.690.awV4UA==
2015-12-10 12:22:45.794 ThaliTest[656:557299] client session: disconnect
2015-12-10 12:22:45.794 ThaliTest[656:557299] client session: stateChange:2->,0 1449746564029.690.awV4UA==
,2015-12-10 12:22:45.821 ThaliTest[656:558628] server session: not connected 1449746564029.690
,2015-12-10 12:22:45.930 ThaliTest[656:557299] client session: fireConnectionErrorEvent: 1449746564029.690.awV4UA==
,2015-12-10 12:22:45.935 ThaliTest[656:557600] jxcore: connect 1449746564029.690.awV4UA==
,2015-12-10 12:22:45.943 ThaliTest[656:557600] client session: connect
,2015-12-10 12:22:45.944 ThaliTest[656:557600] client session: stateChange:0->1 1449746564029.690.awV4UA==
,2015-12-10 12:22:45.958 ThaliTest[656:557299] multipeer session: reset timer
2015-12-10 12:22:45.959 ThaliTest[656:557299] multipeer session: stop timer
2015-12-10 12:22:45.959 ThaliTest[656:557299] multipeer session: start timer: 0x1a0600f0
2015-12-10 12:22:45.960 ThaliTest[656:557299] server: disconnecting to refresh session (1449746564029.690)
,2015-12-10 12:22:45.960 ThaliTest[656:557299] server session: disconnect
,2015-12-10 12:22:45.961 ThaliTest[656:557299] server session: stateChange:2->0 1449746564029.690
,2015-12-10 12:22:45.965 ThaliTest[656:557299] server session: connect
,2015-12-10 12:22:45.966 ThaliTest[656:557299] server session: stateChange:0->1 1449746564029.690
,2015-12-10 12:22:45.982 ThaliTest[656:557299] server: accepting invitation 1449746564029.690
,2015-12-10 12:22:48.552 ThaliTest[656:558652] server session: connected
2015-12-10 12:22:48.552 ThaliTest[656:558652] server session: stateChange:1->2 1449746564029.690
,2015-12-10 12:22:48.558 ThaliTest[656:557299] server relay: connected (to port: 5001)
,2015-12-10 12:22:48.733 ThaliTest[656:558628] server session: not connected 1449746564029.690
,2015-12-10 12:22:48.748 ThaliTest[656:558628] client session: connected
2015-12-10 12:22:48.748 ThaliTest[656:558628] client session: stateChange:1->2 1449746564029.690.awV4UA==
,2015-12-10 12:22:48.753 ThaliTest[656:558628] client session: fireConnectCallback: 1449746564029.690.awV4UA==
,2015-12-10 12:22:48.754 ThaliTest[656:558628] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 Second connect should succeed
,2015-12-10 12:22:48.792 ThaliTest[656:557299] client: relay established
2015-12-10 12:22:48.792 ThaliTest[656:557299] client: new accepted socket: 0x1a1ddc90
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2015-12-10 12:22:48.855 ThaliTest[656:557299] client: socket closed
,2015-12-10 12:22:48.857 ThaliTest[656:557299] client relay: socket disconnected
,2015-12-10 12:22:48.857 ThaliTest[656:557299] client relay: 0x1a1ddc90 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-10 12:22:48.858 ThaliTest[656:557299] client session: socket closed: 1449746564029.690.awV4UA==
2015-12-10 12:22:48.858 ThaliTest[656:557299] client session: onLinkFailure: 1449746564029.690.awV4UA==
2015-12-10 12:22:48.858 ThaliTest[656:557299] ,client session: disconnect
,2015-12-10 12:22:48.859 ThaliTest[656:557299] client session: stateChange:2->0 1449746564029.690.awV4UA==
,2015-12-10 12:22:48.870 ThaliTest[656:557299] client session: fireConnectionErrorEvent: 1449746564029.690.awV4UA==
,calling stopBroadcasting
,2015-12-10 12:22:49.171 ThaliTest[656:557600] jxcore: stopBroadcasting
,2015-12-10 12:22:49.173 ThaliTest[656:557600] THEMultipeerSession stopping peer
,2015-12-10 12:22:49.174 ThaliTest[656:557600] multipeer session: stop timer
,2015-12-10 12:22:49.178 ThaliTest[656:557600] server session: disconnect
,2015-12-10 12:22:49.189 ThaliTest[656:557600] server session: stateChange:2->0 1449746564029.690
,2015-12-10 12:22:49.202 ThaliTest[656:557600] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/922A697F-5A7F-47EA-A04D-F47E381C4862/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2015-12-10 12:22:50.430 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:22:50.431 ThaliTest[656:557600] server: starting CrOrHdY3yuXJbkBtveQWIg.Z8W75g==
2015-12-10 12:22:50.431 ThaliTest[656:557600] multipeer session: start timer: 0x1a061a10
2015-12-10 12:22:50.431 ThaliTest[656:557600] THEMultipeerSession init,ialized peer CrOrHdY3yuXJbkBtveQWIg
2015-12-10 12:22:50.431 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should occur in right order
About to call stopBroadcasting
,2015-12-10 12:22:50.433 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12:22:50.434 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:22:50.434 ThaliTest[656:557600] multipeer session: stop timer
2015-12-10 12:22:50.434 ThaliTest[656:557600] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/922A697F-5A7F-47EA-A04D-F47E381C4862/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2015-12-10 12:22:51.405 ThaliTest[656:557600] jxcore: startBroadcasting
,2015-12-10 12:22:51.408 ThaliTest[656:557600] server: starting CrOrHdY3yuXJbkBtveQWIg.V9Hb+A==
2015-12-10 12:22:51.409 ThaliTest[656:557600] multipeer session: start timer: 0x1a1df370
2015-12-10 12:22:51.409 ThaliTest[656:557600] THEMultipeerSession init,ialized peer CrOrHdY3yuXJbkBtveQWIg
2015-12-10 12:22:51.410 ThaliTest[656:557600] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
,ok 104 deviceName should not be null
,Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
,2015-12-10 12:22:51.417 ThaliTest[656:557600] jxcore: stopBroadcasting
2015-12-10 12:22:51.418 ThaliTest[656:557600] THEMultipeerSession stopping peer
2015-12-10 12:22:51.418 ThaliTest[656:557600] multipeer session: stop timer
2015-12-10 12:22:51.419 Th,aliTest[656:557600] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
Tests Complete

```
