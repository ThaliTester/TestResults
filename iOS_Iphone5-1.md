#### Test 50650278c0f6ec2_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c0f6ec2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E5E68C8F-BAD0-4211-A42A-89C28AAA56D9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/E5E68C8F-BAD0-4211-A42A-89C28AAA56D9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c0f6ec2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c0f6ec2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7D9B475B-C2C7-469D-9D88-465B126D3F87/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53083"
,(lldb)     command script import "/tmp/E5E68C8F-BAD0-4211-A42A-89C28AAA56D9/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-10 12:54:21.870 ThaliTest[575:637082] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FCB9FC2A-B227-4E11-AAC8-CEA119955A9E/Library/Cookies/Cookies.binarycookies
,2015-12-10 12:54:21.993 ThaliTest[575:637082] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 12:54:21.995 ThaliTest[575:637082] Multi-tasking -> Device: YES, App: YES
,2015-12-10 12:54:22.001 ThaliTest[575:637082] Unlimited access to network resources
,2015-12-10 12:54:22.012 ThaliTest[575:637082] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 12:54:31.852 ThaliTest[575:637082] Resetting plugins due to page load.
,2015-12-10 12:54:35.666 ThaliTest[575:637082] Finished load of: file:///var/mobile/Containers/Bundle/Application/7D9B475B-C2C7-469D-9D88-465B126D3F87/ThaliTest.app/www/index.html
,2015-12-10 12:54:35.886 ThaliTest[575:637082] JXcore Cordova plugin initializing
,2015-12-10 12:54:35.888 ThaliTest[575:637256] JXcore instance initializing
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
,2015-12-10 13:01:01.656 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:01.665 ThaliTest[575:637256] server: starting 1449748861655.575.qlprWw==
,2015-12-10 13:01:01.666 ThaliTest[575:637256] multipeer session: start timer: 0x1e160af0
2015-12-10 13:01:01.667 ThaliTest[575:637256] THEMultipeerSession initialized peer 1449748861655.575
,2015-12-10 13:01:01.668 ThaliTest[575:637256] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2015-12-10 13:01:01.671 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13:01:01.672 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:01.672 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:01.672 ThaliTest[575:637256] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
2015-12-10 13:01:01.675 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:01.686 ThaliTest[575:637256] server: starting 1449748861674.575.7JaCjA==
2015-12-10 13:01:01.687 ThaliTest[575:637256] multipeer session: start timer: 0x1e0ebbf0
2015-12-10 13:01:01.688 ThaliTest[575:637256] THEMultipeerSession initializ,ed peer 1449748861674.575
2015-12-10 13:01:01.688 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-10 13:01:01.690 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13,:01:01.690 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:01.690 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:01.691 ThaliTest[575:637256] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2015-12-10 13:01:01.695 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:01.700 ThaliTest[575:637256] server: starting 1449748861694.575.GkFLbQ==
2015-12-10 13:01:01.701 ThaliTest[575:637256] multipeer session: start timer: 0x1658a980
2015-12-10 13:01:01.702 ThaliTest[575:637256] THEMultipeerSession initializ,ed peer 1449748861694.575
2015-12-10 13:01:01.702 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2015-12-10 13:01:01.705 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13,:01:01.706 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:01.706 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:01.706 ThaliTest[575:637256] jxcore: stopBroadcasting: success
ok 50 Should be able to call s,topBroadcasting without error
2015-12-10 13:01:01.709 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:01.720 ThaliTest[575:637256] server: starting 1449748861708.575.RRQsAg==
2015-12-10 13:01:01.720 ThaliTest[575:637256] multipeer session: start timer: 0x1e162ef0
2015-12-10 13:01:01.721 ThaliTest[575:637256] THEMultipeerSession initialized peer 1449748861708.575
,2015-12-10 13:01:01.727 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
,2015-12-10 13:01:01.734 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13:01:01.734 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:01.734 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:01.735 Th,aliTest[575:637256] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2015-12-10 13:01:01.737 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:01.745 ThaliTest[575:637256] server: starting 1449748861736.575.j96XmA==
2015-12-10 13:01:01.746 ThaliTest[575:637256] multipeer session: start timer: 0x1e162240
2015-12-10 13:01:01.746 ThaliTest[575:637256] THEMultipeerSession initializ,ed peer 1449748861736.575
2015-12-10 13:01:01.747 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2015-12-10 13:01:01.748 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13,:01:01.749 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:01.749 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:01.749 ThaliTest[575:637256] jxcore: stopBroadcasting: success
ok 54 Should be able to call s,topBroadcasting without error
2015-12-10 13:01:01.751 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:01.758 ThaliTest[575:637256] server: starting 1449748861751.575.nqP8fw==
2015-12-10 13:01:01.759 ThaliTest[575:637256] multipeer session: start timer: 0x1e164990
2015-12-10 13:01:01.759 ThaliTest[575:637256] THEMultipeerSession initializ,ed peer 1449748861751.575
2015-12-10 13:01:01.760 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2015-12-10 13:01:01.762 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13,:01:01.762 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:01.762 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:01.763 ThaliTest[575:637256] jxcore: stopBroadcasting: success
ok 56 Should be able to call s,topBroadcasting without error
2015-12-10 13:01:01.765 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:01.772 ThaliTest[575:637256] server: starting 1449748861764.575.GOPwRQ==
2015-12-10 13:01:01.773 ThaliTest[575:637256] multipeer session: start timer: 0x1e165440
2015-12-10 13:01:01.773 ThaliTest[575:637256] THEMultipeerSession initializ,ed peer 1449748861764.575
2015-12-10 13:01:01.774 ThaliTest[575:637256] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-10 13:01:01.782 ThaliTest[575:637256] jxcore: stopBroadcasting
,2015-12-10 13:01:01.784 ThaliTest[575:637256] THEMultipeerSession stopping peer
,2015-12-10 13:01:01.786 ThaliTest[575:637256] multipeer session: stop timer
,2015-12-10 13:01:01.787 ThaliTest[575:637256] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-10 13:01:01.793 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:01.797 ThaliTest[575:637256] server: starting 1449748861793.575.9kai1w==
,2015-12-10 13:01:01.798 ThaliTest[575:637256] multipeer session: start timer: 0x1e0eaa90
,2015-12-10 13:01:01.801 ThaliTest[575:637256] THEMultipeerSession initialized peer 1449748861793.575
,2015-12-10 13:01:01.806 ThaliTest[575:637256] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-10 13:01:01.808 ThaliTest[575:637256] jxcore: stopBroadcasting
,2015-12-10 13:01:01.809 ThaliTest[575:637256] THEMultipeerSession stopping peer
,2015-12-10 13:01:01.811 ThaliTest[575:637256] multipeer session: stop timer
,2015-12-10 13:01:01.813 ThaliTest[575:637256] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-10 13:01:01.819 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:01.822 ThaliTest[575:637256] server: starting 1449748861818.575.82db2A==
,2015-12-10 13:01:01.823 ThaliTest[575:637256] multipeer session: start timer: 0x1e0eb6b0
,2015-12-10 13:01:01.825 ThaliTest[575:637256] THEMultipeerSession initialized peer 1449748861818.575
,2015-12-10 13:01:01.832 ThaliTest[575:637256] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-10 13:01:01.835 ThaliTest[575:637256] jxcore: stopBroadcasting
,2015-12-10 13:01:01.835 ThaliTest[575:637256] THEMultipeerSession stopping peer
,2015-12-10 13:01:01.836 ThaliTest[575:637256] multipeer session: stop timer
,2015-12-10 13:01:01.838 ThaliTest[575:637256] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-10 13:01:01.844 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:01.846 ThaliTest[575:637256] server: starting 1449748861843.575.0IKJnA==
,2015-12-10 13:01:01.851 ThaliTest[575:637256] multipeer session: start timer: 0x1e166680
,2015-12-10 13:01:01.852 ThaliTest[575:637256] THEMultipeerSession initialized peer 1449748861843.575
,2015-12-10 13:01:01.856 ThaliTest[575:637256] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-10 13:01:01.860 ThaliTest[575:637256] jxcore: stopBroadcasting
,2015-12-10 13:01:01.860 ThaliTest[575:637256] THEMultipeerSession stopping peer
,2015-12-10 13:01:01.861 ThaliTest[575:637256] multipeer session: stop timer
,2015-12-10 13:01:01.867 ThaliTest[575:637256] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-10 13:01:02.498 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:02.500 ThaliTest[575:637256] server: starting 1449748862497.575.gCjV2Q==
2015-12-10 13:01:02.500 ThaliTest[575:637256] multipeer session: start timer: 0x1e168790
2015-12-10 13:01:02.500 ThaliTest[575:637256] THEMultipeerSession initializ,ed peer 1449748862497.575
2015-12-10 13:01:02.501 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2015-12-10 13:01:02.502 ThaliTest[575:637256] jxcore: startBroadcasting
2015-12-10 1,3:01:02.503 ThaliTest[575:637256] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2015-12-10 13:01:02.504 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13:01:02.504 ThaliTest[575:637256] THEMultipeerSession stopp,ing peer
2015-12-10 13:01:02.504 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:02.505 ThaliTest[575:637256] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-10 13:01:05.688 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:05.691 ThaliTest[575:637256] server: starting 1449748865688.575.LQyC1w==
2015-12-10 13:01:05.692 ThaliTest[575:637256] multipeer session: start timer: 0x1e0ed4c0
2015-12-10 13:01:05.692 ThaliTest[575:637256] THEMultipeerSession initializ,ed peer 1449748865688.575
2015-12-10 13:01:05.692 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-10 13:01:05.693 ThaliTest[575:637256] jxcore: connect foobar
2015-12-10 13:0,1:05.694 ThaliTest[575:637256] client: unknown peer foobar
2015-12-10 13:01:05.694 ThaliTest[575:637256] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2015-12-10 13:01:05.695 ThaliTest[575:637256] jxcore: stopBroadcasting
,2015-12-10 13:01:05.696 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:05.696 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:05.696 ThaliTest[575:637256] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-10 13:01:08.068 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:08.071 ThaliTest[575:637256] server: starting 1449748868068.575.e0ARCA==
2015-12-10 13:01:08.072 ThaliTest[575:637256] multipeer session: start timer: 0x1e16e610
2015-12-10 13:01:08.072 ThaliTest[575:637256] THEMultipeerSession initializ,ed peer 1449748868068.575
2015-12-10 13:01:08.072 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-10 13:01:08.073 ThaliTest[575:637256] jxcore: disconnect
2015-12-10 13:01:08.074 ThaliTest[575:637256] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2015-12-10 13:01:08.086 ThaliTest[575:637256] jxcore: stopBroadcasting
,2015-12-10 13:01:08.087 ThaliTest[575:637256] THEMultipeerSession stopping peer
,2015-12-10 13:01:08.088 ThaliTest[575:637256] multipeer session: stop timer
,2015-12-10 13:01:08.094 ThaliTest[575:637256] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-10 13:01:08.630 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:08.633 ThaliTest[575:637256] server: starting 1449748868629.575.O1KCeA==
2015-12-10 13:01:08.633 ThaliTest[575:637256] multipeer session: start timer: 0x1e1716c0
2015-12-10 13:01:08.633 ThaliTest[575:637256] THEMultipeerSession initializ,ed peer 1449748868629.575
2015-12-10 13:01:08.633 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2015-12-10 13:01:09.941 ThaliTest[575:637082] client: found peer: 1449748868868.677.tgjAXw==
2015-12-10 13:01:09.943 ThaliTest[575:637256] jxcore: connect 1449748868868.677.tgjAXw==
2015-12-10 13:01:09.944 ThaliTest[575:637256] client session: connect
2015-12-10 13:01:09.944 ThaliTest[575:637256] client session: stateChange:0->1 1449748868868.677.tgjAXw==
,2015-12-10 13:01:11.185 ThaliTest[575:637082] multipeer session: reset timer
2015-12-10 13:01:11.185 ThaliTest[575:637082] multipeer session: stop timer
2015-12-10 13:01:11.185 ThaliTest[575:637082] multipeer session: start timer: 0x1e1716c0
2015-12-10 13:01:11.186 ThaliTest[575:637082] server session: connect
2015-12-10 13:01:11.186 ThaliTest[575:637082] server session: stateChange:0->1 1449748868868.677
,2015-12-10 13:01:11.192 ThaliTest[575:637082] server: accepting invitation 1449748868868.677
,2015-12-10 13:01:12.899 ThaliTest[575:637952] client session: connected
2015-12-10 13:01:12.900 ThaliTest[575:637952] client session: stateChange:1->2 1449748868868.677.tgjAXw==
,2015-12-10 13:01:12.924 ThaliTest[575:637928] client session: fireConnectCallback: 1449748868868.677.tgjAXw==
2015-12-10 13:01:12.924 ThaliTest[575:637928] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-10 13:01:12.927 ThaliTest[575:637256] jxcore: disconnect
,2015-12-10 13:01:12.927 ThaliTest[575:637256] client session: disconnectFromPeer: 1449748868868.677.tgjAXw==
2015-12-10 13:01:12.928 ThaliTest[575:637256] client session: disconnect
2015-12-10 13:01:12.928 ThaliTest[575:637256] client session: stateChange:2->0 1449748868868.677.tgjAXw==
,2015-12-10 13:01:12.939 ThaliTest[575:637256] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-10 13:01:13.944 ThaliTest[575:637928] server session: connected
2015-12-10 13:01:13.944 ThaliTest[575:637928] server session: stateChange:1->2 1449748868868.677
,2015-12-10 13:01:13.973 ThaliTest[575:637082] server relay: socket disconnected
2015-12-10 13:01:13.973 ThaliTest[575:637082] server relay: 0x1e0f4350 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 13:01:14.015 ThaliTest[575:637952] server session: not connected 1449748868868.677
,calling stopBroadcasting
,2015-12-10 13:01:15.499 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13:01:15.499 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:15.500 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:15.500 ThaliTest[575:637256] server session: disconnect
2015-12-10 13:01:15.501 ThaliTest[575:637256] server session: stateChange:2->0 1449748868868.677
,2015-12-10 13:01:15.586 ThaliTest[575:637256] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-10 13:01:16.491 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:16.494 ThaliTest[575:637256] server: starting 1449748876491.575.QtSv7Q==
2015-12-10 13:01:16.495 ThaliTest[575:637256] multipeer session: start timer: 0x1e0f9600
2015-12-10 13:01:16.495 ThaliTest[575:637256] THEMultipeerSession initializ,ed peer 1449748876491.575
2015-12-10 13:01:16.495 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2015-12-10 13:01:17.858 ThaliTest[575:637082] client: found peer: 1449748876498.677.ONqMaQ==
2015-12-10 13:01:17.861 ThaliTest[575:637256] jxcore: connect 1449748876498.677.ONqMaQ==
,2015-12-10 13:01:17.861 ThaliTest[575:637256] client session: connect
,2015-12-10 13:01:17.861 ThaliTest[575:637256] client session: stateChange:0->1 1449748876498.677.ONqMaQ==
,2015-12-10 13:01:17.936 ThaliTest[575:637082] multipeer session: reset timer
,2015-12-10 13:01:17.937 ThaliTest[575:637082] multipeer session: stop timer
2015-12-10 13:01:17.937 ThaliTest[575:637082] multipeer session: start timer: 0x1e0f9600
,2015-12-10 13:01:17.937 ThaliTest[575:637082] server session: connect
2015-12-10 13:01:17.938 ThaliTest[575:637082] server session: stateChange:0->1 1449748876498.677
,2015-12-10 13:01:17.945 ThaliTest[575:637082] server: accepting invitation 1449748876498.677
,2015-12-10 13:01:20.616 ThaliTest[575:637951] server session: connected
2015-12-10 13:01:20.618 ThaliTest[575:637951] server session: stateChange:1->2 1449748876498.677
,2015-12-10 13:01:20.640 ThaliTest[575:637082] server relay: socket disconnected
2015-12-10 13:01:20.641 ThaliTest[575:637082] server relay: 0x1e17dbe0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 13:01:20.690 ThaliTest[575:637929] server session: not connected 1449748876498.677
,2015-12-10 13:01:20.828 ThaliTest[575:637952] client session: connected
2015-12-10 13:01:20.829 ThaliTest[575:637952] client session: stateChange:1->2 1449748876498.677.ONqMaQ==
,2015-12-10 13:01:20.954 ThaliTest[575:637928] client session: fireConnectCallback: 1449748876498.677.ONqMaQ==
2015-12-10 13:01:20.954 ThaliTest[575:637928] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
,2015-12-10 13:01:20.957 ThaliTest[575:637256] jxcore: connect 1449748876498.677.ONqMaQ==
2015-12-10 13:01:20.957 ThaliTest[575:637256] client: already connect(ing/ed) to 1449748876498.677.ONqMaQ==
2015-12-10 13:01:20.957 ThaliTest[575:637256] jxcore: con,nect: fail: Aleady connecting
ok 81 Should fail on double connect
,2015-12-10 13:01:20.959 ThaliTest[575:637256] jxcore: disconnect
2015-12-10 13:01:20.959 ThaliTest[575:637256] client session: disconnectFromPeer: 1449748876498.677.ONqMaQ==
,2015-12-10 13:01:20.959 ThaliTest[575:637256] client session: disconnect
2015-12-10 13:01:20.960 ThaliTest[575:637256] client session: stateChange:2->0 1449748876498.677.ONqMaQ==
,2015-12-10 13:01:21.034 ThaliTest[575:637256] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-10 13:01:21.388 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13:01:21.389 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:21.389 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:21.390 ThaliTest[575:637256] server session: disconnect
2015-12-10 13:01:21.390 ThaliTest[575:637256] server session: stateChange:2->0 1449748876498.677
,2015-12-10 13:01:22.364 ThaliTest[575:637256] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-10 13:01:37.199 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:37.201 ThaliTest[575:637256] server: starting 1449748897198.575.+/X1sQ==
2015-12-10 13:01:37.202 ThaliTest[575:637256] multipeer session: start timer: 0x1657d3a0
2015-12-10 13:01:37.202 ThaliTest[575:637256] THEMultipeerSession initialized peer 1449748897198.575
2015-12-10 13:01:37.202 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2015-12-10 13:01:38.177 ThaliTest[575:637082] client: found peer: 1449748897011.677.2n6LLw==
2015-12-10 13:01:38.178 ThaliTest[575:637256] jxcore: connect 1449748897011.677.2n6LLw==
2015-12-10 13:01:38.179 ThaliTest[575:637256] client session: connect
2,015-12-10 13:01:38.179 ThaliTest[575:637256] client session: stateChange:0->1 1449748897011.677.2n6LLw==
,2015-12-10 13:01:38.907 ThaliTest[575:637082] multipeer session: reset timer
2015-12-10 13:01:38.907 ThaliTest[575:637082] multipeer session: stop timer
2015-12-10 13:01:38.908 ThaliTest[575:637082] multipeer session: start timer: 0x1657d3a0
2015-12-10 13:01:38.908 ThaliTest[575:637082] server session: connect
2015-12-10 13:01:38.908 ThaliTest[575:637082] server session: stateChange:0->1 1449748897011.677
,2015-12-10 13:01:38.916 ThaliTest[575:637082] server: accepting invitation 1449748897011.677
,2015-12-10 13:01:41.587 ThaliTest[575:638074] server session: connected
,2015-12-10 13:01:41.587 ThaliTest[575:638074] server session: stateChange:1->2 1449748897011.677
,2015-12-10 13:01:41.606 ThaliTest[575:637082] server relay: socket disconnected
2015-12-10 13:01:41.606 ThaliTest[575:637082] server relay: 0x1e17f580 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 13:01:41.660 ThaliTest[575:638001] server session: not connected 1449748897011.677
,2015-12-10 13:01:42.388 ThaliTest[575:638001] client session: connected
,2015-12-10 13:01:42.388 ThaliTest[575:638001] client session: stateChange:1->2 1449748897011.677.2n6LLw==
,2015-12-10 13:01:42.438 ThaliTest[575:638052] client session: fireConnectCallback: 1449748897011.677.2n6LLw==
2015-12-10 13:01:42.442 ThaliTest[575:638052] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be withi,n range
2015-12-10 13:01:42.444 ThaliTest[575:637256] jxcore: disconnect
2015-12-10 13:01:42.445 ThaliTest[575:637256] client session: disconnectFromPeer: 1449748897011.677.2n6LLw==
2015-12-10 13:01:42.445 ThaliTest[575:637256] client session: disconnec,t
2015-12-10 13:01:42.445 ThaliTest[575:637256] client session: stateChange:2->0 1449748897011.677.2n6LLw==
,2015-12-10 13:01:42.453 ThaliTest[575:637256] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2015-12-10 13:01:42.455 ThaliTest[575:637256] jxcore: disconnect
2015-12-10 13:01:42.455 ThaliTest[575:637256] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-10 13:01:42.881 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13:01:42.882 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:42.882 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:42.883 Th,aliTest[575:637256] server session: disconnect
2015-12-10 13:01:42.883 ThaliTest[575:637256] server session: stateChange:2->0 1449748897011.677
2015-12-10 13:01:42.884 ThaliTest[575:637256] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-10 13:01:44.186 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:44.189 ThaliTest[575:637256] server: starting 1449748904186.575.QU4P/w==
2015-12-10 13:01:44.189 ThaliTest[575:637256] multipeer session: start timer: 0x1e171f40
2015-12-10 13:01:44.189 ThaliTest[575:637256] THEMultipeerSession initialized peer 1449748904186.575
2015-12-10 13:01:44.189 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2015-12-10 13:01:45.530 ThaliTest[575:637082] client: found peer: 1449748904398.677.gz+LMg==
[{"peerIdentifier":"1449748904398.677.gz+LMg==","peerName":"(null)","peerAvailable":true}]
,2015-12-10 13:01:45.533 ThaliTest[575:637256] jxcore: connect 1449748904398.677.gz+LMg==
,2015-12-10 13:01:45.533 ThaliTest[575:637256] client session: connect
2015-12-10 13:01:45.534 ThaliTest[575:637256] client session: stateChange:0->1 1449748904398.677.gz+LMg==
,2015-12-10 13:01:46.043 ThaliTest[575:637082] multipeer session: reset timer
2015-12-10 13:01:46.044 ThaliTest[575:637082] multipeer session: stop timer
,2015-12-10 13:01:46.044 ThaliTest[575:637082] multipeer session: start timer: 0x1e171f40
,2015-12-10 13:01:46.045 ThaliTest[575:637082] server session: connect
,2015-12-10 13:01:46.045 ThaliTest[575:637082] server session: stateChange:0->1 1449748904398.677
,2015-12-10 13:01:46.056 ThaliTest[575:637082] server: accepting invitation 1449748904398.677
,2015-12-10 13:01:48.803 ThaliTest[575:638081] client session: connected
,2015-12-10 13:01:48.804 ThaliTest[575:638081] client session: stateChange:1->2 1449748904398.677.gz+LMg==
,2015-12-10 13:01:48.830 ThaliTest[575:638001] client session: fireConnectCallback: 1449748904398.677.gz+LMg==
2015-12-10 13:01:48.830 ThaliTest[575:638001] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
,ok 91 First connect should succeed
,2015-12-10 13:01:48.868 ThaliTest[575:637082] client: relay established
2015-12-10 13:01:48.868 ThaliTest[575:637082] client: new accepted socket: 0x1e18dec0
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2015-12-10 13:01:48.951 ThaliTest[575:637082] client: socket closed
2015-12-10 13:01:48.951 ThaliTest[575:637082] client relay: socket disconnected
2015-12-10 13:01:48.952 ThaliTest[575:637082] client relay: 0x1e18dec0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-10 13:01:48.952 ThaliTest[575:637082] client session: socket closed: 1449748904398.677.gz+LMg==
2015-12-10 13:01:48.,952 ThaliTest[575:637082] client session: onLinkFailure: 1449748904398.677.gz+LMg==
2015-12-10 13:01:48.953 ThaliTest[575:637082] client session: disconnect
2015-12-10 13:01:48.953 ThaliTest[575:637082] client session: stateChange:2->0 1449748904398.677.,gz+LMg==
,2015-12-10 13:01:48.961 ThaliTest[575:637082] client session: fireConnectionErrorEvent: 1449748904398.677.gz+LMg==
,2015-12-10 13:01:48.965 ThaliTest[575:637256] jxcore: connect 1449748904398.677.gz+LMg==
2015-12-10 13:01:48.967 ThaliTest[575:637256] client session: connect
2015-12-10 13:01:48.967 ThaliTest[575:637256] client session: stateChange:0->1 1449748904398.677.gz+LMg==
,2015-12-10 13:01:49.333 ThaliTest[575:638052] server session: connected
2015-12-10 13:01:49.333 ThaliTest[575:638052] server session: stateChange:1->2 1449748904398.677
,2015-12-10 13:01:49.392 ThaliTest[575:637082] server relay: connected (to port: 5001)
,2015-12-10 13:01:49.752 ThaliTest[575:638081] server session: not connected 1449748904398.677
,2015-12-10 13:01:49.783 ThaliTest[575:637082] multipeer session: reset timer
,2015-12-10 13:01:49.784 ThaliTest[575:637082] multipeer session: stop timer
,2015-12-10 13:01:49.785 ThaliTest[575:637082] multipeer session: start timer: 0x1e171f40
2015-12-10 13:01:49.787 ThaliTest[575:637082] server: disconnecting to refresh session (1449748904398.677)
2015-12-10 13:01:49.787 ThaliTest[575:637082] server session: disconnect
2015-12-10 13:01:49.787 ThaliTest[575:637082] server session: stateChange:2->0 1449748904398.677
,2015-12-10 13:01:49.790 ThaliTest[575:637082] server session: connect
2015-12-10 13:01:49.791 ThaliTest[575:637082] server session: stateChange:0->1 1449748904398.677
,2015-12-10 13:01:49.820 ThaliTest[575:637082] server: accepting invitation 1449748904398.677
,2015-12-10 13:01:52.389 ThaliTest[575:638074] client session: connected
2015-12-10 13:01:52.389 ThaliTest[575:638074] client session: stateChange:1->2 1449748904398.677.gz+LMg==
,2015-12-10 13:01:52.410 ThaliTest[575:638081] client session: fireConnectCallback: 1449748904398.677.gz+LMg==
2015-12-10 13:01:52.410 ThaliTest[575:638081] jxcore: connect: success
ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 Second connect should succeed
,2015-12-10 13:01:52.438 ThaliTest[575:637082] client: relay established
2015-12-10 13:01:52.438 ThaliTest[575:637082] client: new accepted socket: 0x1e193f20
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2015-12-10 13:01:52.549 ThaliTest[575:637082] client: socket closed
2015-12-10 13:01:52.550 ThaliTest[575:637082] client relay: socket disconnected
2015-12-10 13:01:52.550 ThaliTest[575:637082] client relay: 0x1e193f20 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-10 13:01:52.551 ThaliTest[575:637082] client session: socket closed: 1449748904398.677.gz+LMg==
2015-12-10 13:01:52.,551 ThaliTest[575:637082] client session: onLinkFailure: 1449748904398.677.gz+LMg==
2015-12-10 13:01:52.551 ThaliTest[575:637082] client session: disconnect
2015-12-10 13:01:52.551 ThaliTest[575:637082] client session: stateChange:2->0 1449748904398.677.,gz+LMg==
,2015-12-10 13:01:52.559 ThaliTest[575:637082] client session: fireConnectionErrorEvent: 1449748904398.677.gz+LMg==
,2015-12-10 13:01:52.931 ThaliTest[575:638081] server session: connected
,2015-12-10 13:01:52.931 ThaliTest[575:638081] server session: stateChange:1->2 1449748904398.677
,2015-12-10 13:01:52.992 ThaliTest[575:637082] server relay: connected (to port: 5001)
,2015-12-10 13:01:53.450 ThaliTest[575:638074] server session: not connected 1449748904398.677
,calling stopBroadcasting
,2015-12-10 13:01:53.754 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13:01:53.754 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:53.755 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:53.755 Th,aliTest[575:637256] server session: disconnect
2015-12-10 13:01:53.756 ThaliTest[575:637256] server session: stateChange:2->0 1449748904398.677
2015-12-10 13:01:53.759 ThaliTest[575:637256] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FCB9FC2A-B227-4E11-AAC8-CEA119955A9E/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2015-12-10 13:01:55.856 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:55.858 ThaliTest[575:637256] server: starting HM_Uz1FEwFl3YT_WQvg0Wg.FctWXA==
2015-12-10 13:01:55.859 ThaliTest[575:637256] multipeer session: start timer: 0x1e183a50
2015-12-10 13:01:55.859 ThaliTest[575:637256] THEMultipeerSession initialized peer HM_Uz1FEwFl3YT_WQvg0Wg
2015-12-10 13:01:55.859 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
,ok 101 stopping event should occur in right order
About to call stopBroadcasting
,2015-12-10 13:01:55.863 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13:01:55.864 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:55.864 ThaliTest[575:637256] multipeer session: stop timer
2015-12-10 13:01:55.865 ThaliTest[575:637256] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,ok 102 stopped event should occur in right order
mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FCB9FC2A-B227-4E11-AAC8-CEA119955A9E/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2015-12-10 13:01:57.097 ThaliTest[575:637256] jxcore: startBroadcasting
,2015-12-10 13:01:57.099 ThaliTest[575:637256] server: starting HM_Uz1FEwFl3YT_WQvg0Wg.Wz91PA==
2015-12-10 13:01:57.099 ThaliTest[575:637256] multipeer session: start timer: 0x1e187940
2015-12-10 13:01:57.099 ThaliTest[575:637256] THEMultipeerSession init,ialized peer HM_Uz1FEwFl3YT_WQvg0Wg
2015-12-10 13:01:57.099 ThaliTest[575:637256] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
Now in TRM stop
State of this._isStarted: tru,e
About to call stopBroadcasting
2015-12-10 13:01:57.103 ThaliTest[575:637256] jxcore: stopBroadcasting
2015-12-10 13:01:57.103 ThaliTest[575:637256] THEMultipeerSession stopping peer
2015-12-10 13:01:57.103 ThaliTest[575:637256] multipeer session: sto,p timer
2015-12-10 13:01:57.103 ThaliTest[575:637256] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
Tests Complete

```
