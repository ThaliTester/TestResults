#### Test 5497026179923a9_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5497026179923a9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/77DBA3C7-80B4-4624-8DA7-8D7D72F8B711/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/77DBA3C7-80B4-4624-8DA7-8D7D72F8B711/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5497026179923a9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5497026179923a9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/50CBCDD1-084B-46B7-B011-3D0ECC1207C2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51928"
,(lldb)     command script import "/tmp/77DBA3C7-80B4-4624-8DA7-8D7D72F8B711/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 11:47:42.039 ThaliTest[1220:4031668] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/30E9C032-7FF7-4CC1-B1A0-0FBB08933497/Library/Cookies/Cookies.binarycookies
,2016-01-11 11:47:42.171 ThaliTest[1220:4031668] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 11:47:42.173 ThaliTest[1220:4031668] Multi-tasking -> Device: YES, App: YES
,2016-01-11 11:47:42.178 ThaliTest[1220:4031668] Unlimited access to network resources
2016-01-11 11:47:42.191 ThaliTest[1220:4031668] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.,
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 11:47:52.532 ThaliTest[1220:4031668] Resetting plugins due to page load.
,2016-01-11 11:47:56.384 ThaliTest[1220:4031668] Finished load of: file:///var/mobile/Containers/Bundle/Application/50CBCDD1-084B-46B7-B011-3D0ECC1207C2/ThaliTest.app/www/index.html
,2016-01-11 11:47:56.596 ThaliTest[1220:4031668] JXcore Cordova plugin initializing
,2016-01-11 11:47:56.597 ThaliTest[1220:4031844] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5-1
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
,2016-01-11 11:54:19.795 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:19.804 ThaliTest[1220:4031844] server: starting 1452509659794.1220.tXmveQ==
,2016-01-11 11:54:19.805 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d37f080
,2016-01-11 11:54:19.805 ThaliTest[1220:4031844] THEMultipeerSession initialized peer 1452509659794.1220
,2016-01-11 11:54:19.806 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.808 ThaliTest[1220:4031844] jxcore: stopBroadcasting
,2016-01-11 11:54:19.808 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
2016-01-11 11:54:19.808 ThaliTest[1220:4031844] multipeer session: stop timer
,2016-01-11 11:54:19.809 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-11 11:54:19.810 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:19.816 ThaliTest[1220:4031844] server: starting 1452509659810.1220.3tiHDQ==
2016-01-11 11:54:19.817 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d436170
2016-01-11 11:54:19.817 ThaliTest[1220:4031844] THEMultipeerSession in,itialized peer 1452509659810.1220
2016-01-11 11:54:19.817 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-11 11:54:19.819 ThaliTest[1220:4031844] jxcore: stopBroadcasting
2,016-01-11 11:54:19.819 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
2016-01-11 11:54:19.819 ThaliTest[1220:4031844] multipeer session: stop timer
,2016-01-11 11:54:19.820 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:19.832 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:19.841 ThaliTest[1220:4031844] server: starting 1452509659832.1220.savAhA==
2016-01-11 11:54:19.842 ThaliTest[1220:4031844] multipeer session: start timer: 0x1769dad0
2016-01-11 11:54:19.842 ThaliTest[1220:4031844] THEMultipeerSession in,itialized peer 1452509659832.1220
,2016-01-11 11:54:19.843 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-11 11:54:19.849 ThaliTest[1220:4031844] jxcore: stopBroadcasting
2016-01-11 11:54:19.850 ThaliTest[12,20:4031844] THEMultipeerSession stopping peer
2016-01-11 11:54:19.850 ThaliTest[1220:4031844] multipeer session: stop timer
2016-01-11 11:54:19.850 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting w,ithout error
,2016-01-11 11:54:19.852 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:19.860 ThaliTest[1220:4031844] server: starting 1452509659852.1220.KQSP6g==
2016-01-11 11:54:19.860 ThaliTest[1220:4031844] multipeer session: start timer: 0x175b0280
2016-01-11 11:54:19.861 ThaliTest[1220:4031844] THEMultipeerSession in,itialized peer 1452509659852.1220
2016-01-11 11:54:19.861 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.864 ThaliTest[1220:4031844] jxcore: stopBroadcasting
2016-01-11 11:54:19.865 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
2016-01-11 11:54:19.865 ThaliTest[1220:4031844] multipeer session: stop timer
2016-01-11 11:54:19.,867 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-11 11:54:19.869 ThaliTest[1220:4031844] jxcore: startBroadcasting
2016-01-11 11:54:19.873 ThaliTest[1220:4031844] server: s,tarting 1452509659868.1220.LZpsGw==
2016-01-11 11:54:19.874 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d6e57f0
2016-01-11 11:54:19.874 ThaliTest[1220:4031844] THEMultipeerSession initialized peer 1452509659868.1220
2016-01-11 11:54:19.87,5 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-11 11:54:19.877 ThaliTest[1220:4031844] jxcore: stopBroadcasting
2016-01-11 11:54:19.877 ThaliTest[1220:4031844] THEMultipe,erSession stopping peer
2016-01-11 11:54:19.883 ThaliTest[1220:4031844] multipeer session: stop timer
2016-01-11 11:54:19.883 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
2016-01-11 11:54:19.886 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:19.894 ThaliTest[1220:4031844] server: starting 1452509659885.1220.88lPpg==
2016-01-11 11:54:19.895 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d753a20
2016-01-11 11:54:19.895 ThaliTest[1220:4031844] THEMultipeerSession initialized peer 1452509659885.1220
,2016-01-11 11:54:19.897 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.919 ThaliTest[1220:4031844] jxcore: stopBroadcasting
,2016-01-11 11:54:19.920 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
,2016-01-11 11:54:19.923 ThaliTest[1220:4031844] multipeer session: stop timer
,2016-01-11 11:54:19.934 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:19.940 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:19.943 ThaliTest[1220:4031844] server: starting 1452509659940.1220.wheQHA==
,2016-01-11 11:54:19.944 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d755fd0
,2016-01-11 11:54:19.950 ThaliTest[1220:4031844] THEMultipeerSession initialized peer 1452509659940.1220
,2016-01-11 11:54:19.953 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.958 ThaliTest[1220:4031844] jxcore: stopBroadcasting
,2016-01-11 11:54:19.958 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
,2016-01-11 11:54:19.959 ThaliTest[1220:4031844] multipeer session: stop timer
,2016-01-11 11:54:19.960 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:19.966 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:19.969 ThaliTest[1220:4031844] server: starting 1452509659965.1220.p5D4fg==
,2016-01-11 11:54:19.972 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d2827e0
,2016-01-11 11:54:19.973 ThaliTest[1220:4031844] THEMultipeerSession initialized peer 1452509659965.1220
,2016-01-11 11:54:19.974 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-11 11:54:19.982 ThaliTest[1220:4031844] jxcore: stopBroadcasting
,2016-01-11 11:54:19.982 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
,2016-01-11 11:54:19.983 ThaliTest[1220:4031844] multipeer session: stop timer
,2016-01-11 11:54:19.984 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:19.991 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:19.993 ThaliTest[1220:4031844] server: starting 1452509659990.1220.OHOLdg==
,2016-01-11 11:54:19.996 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d53b240
,2016-01-11 11:54:19.998 ThaliTest[1220:4031844] THEMultipeerSession initialized peer 1452509659990.1220
,2016-01-11 11:54:20.003 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-11 11:54:20.005 ThaliTest[1220:4031844] jxcore: stopBroadcasting
,2016-01-11 11:54:20.006 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
,2016-01-11 11:54:20.007 ThaliTest[1220:4031844] multipeer session: stop timer
,2016-01-11 11:54:20.008 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-11 11:54:20.014 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:20.017 ThaliTest[1220:4031844] server: starting 1452509660013.1220.7r1Cgg==
,2016-01-11 11:54:20.018 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d211c30
,2016-01-11 11:54:20.020 ThaliTest[1220:4031844] THEMultipeerSession initialized peer 1452509660013.1220
,2016-01-11 11:54:20.026 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-11 11:54:20.029 ThaliTest[1220:4031844] jxcore: stopBroadcasting
,2016-01-11 11:54:20.030 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
,2016-01-11 11:54:20.031 ThaliTest[1220:4031844] multipeer session: stop timer
,2016-01-11 11:54:20.033 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-11 11:54:20.423 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:20.425 ThaliTest[1220:4031844] server: starting 1452509660422.1220.hSFSTw==
2016-01-11 11:54:20.426 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d109e80
2016-01-11 11:54:20.426 ThaliTest[1220:4031844] THEMultipeerSession in,itialized peer 1452509660422.1220
2016-01-11 11:54:20.426 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-11 11:54:20.428 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:20.428 ThaliTest[1220:4031844] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-11 11:54:20.430 ThaliTest[1220:4031844] jxcore: stopBroadcasting
2016-01-11 11:54:20.430 ThaliTest[1220:4031844] THEMult,ipeerSession stopping peer
2016-01-11 11:54:20.430 ThaliTest[1220:4031844] multipeer session: stop timer
2016-01-11 11:54:20.430 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-11 11:54:20.791 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:20.793 ThaliTest[1220:4031844] server: starting 1452509660790.1220.AQyW3w==
2016-01-11 11:54:20.793 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d44b060
2016-01-11 11:54:20.794 ThaliTest[1220:4031844] THEMultipeerSession in,itialized peer 1452509660790.1220
2016-01-11 11:54:20.794 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-11 11:54:20.795 ThaliTest[1220:4031844] jxcore: connect foobar
201,6-01-11 11:54:20.796 ThaliTest[1220:4031844] client: unknown peer foobar
2016-01-11 11:54:20.796 ThaliTest[1220:4031844] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-11 11:54:20.797 ThaliTest[1220:4031844] jxcore: s,topBroadcasting
,2016-01-11 11:54:20.797 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
2016-01-11 11:54:20.798 ThaliTest[1220:4031844] multipeer session: stop timer
2016-01-11 11:54:20.798 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
ok 70 Shoul,d be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-11 11:54:21.300 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:21.302 ThaliTest[1220:4031844] server: starting 1452509661299.1220.LJ8wvA==
2016-01-11 11:54:21.303 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d29aaf0
2016-01-11 11:54:21.303 ThaliTest[1220:4031844] THEMultipeerSession in,itialized peer 1452509661299.1220
2016-01-11 11:54:21.303 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-11 11:54:21.304 ThaliTest[1220:4031844] jxcore: disconnect
2016-01,-11 11:54:21.305 ThaliTest[1220:4031844] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2016-01-11 11:54:21.306 ThaliTest[1220:4031844] jxcore: stopBroadcasting
2016-01-11 11:54:21.306 ThaliTest[1220:4031844] THEMultipeerS,ession stopping peer
2016-01-11 11:54:21.306 ThaliTest[1220:4031844] multipeer session: stop timer
2016-01-11 11:54:21.307 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-11 11:54:21.382 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:21.384 ThaliTest[1220:4031844] server: starting 1452509661382.1220.V/ONYw==
2016-01-11 11:54:21.385 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d492890
2016-01-11 11:54:21.385 ThaliTest[1220:4031844] THEMultipeerSession in,itialized peer 1452509661382.1220
2016-01-11 11:54:21.385 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-11 11:54:22.610 ThaliTest[1220:4031668] client: found peer: 1452509661366.1699.C11Mzw==
2016-01-11 11:54:22.611 ThaliTest[1220:4031844] jxcore: connect 1452509661366.1699.C11Mzw==
2016-01-11 11:54:22.612 ThaliTest[1220:4031844] client session: co,nnect
2016-01-11 11:54:22.612 ThaliTest[1220:4031844] client session: stateChange:0->1 1452509661366.1699.C11Mzw==
,2016-01-11 11:54:23.268 ThaliTest[1220:4031668] multipeer session: reset timer
2016-01-11 11:54:23.268 ThaliTest[1220:4031668] multipeer session: stop timer
2016-01-11 11:54:23.268 ThaliTest[1220:4031668] multipeer session: start timer: 0x1d492890
2016-,01-11 11:54:23.269 ThaliTest[1220:4031668] server session: connect
2016-01-11 11:54:23.269 ThaliTest[1220:4031668] server session: stateChange:0->1 1452509661366.1699
,2016-01-11 11:54:23.277 ThaliTest[1220:4031668] server: accepting invitation 1452509661366.1699
,2016-01-11 11:54:25.834 ThaliTest[1220:4032740] client session: connected
2016-01-11 11:54:25.835 ThaliTest[1220:4032740] client session: stateChange:1->2 1452509661366.1699.C11Mzw==
,2016-01-11 11:54:25.889 ThaliTest[1220:4032727] client session: fireConnectCallback: 1452509661366.1699.C11Mzw==
2016-01-11 11:54:25.889 ThaliTest[1220:4032727] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-11 11:54:25.892 ThaliTest[1220:4031844] jxcore: disconnect
2016-01-11 11:54:25.892 ThaliTest[1220:4031844] client session: disconnectFromPeer: 1452509661366.1699.C11Mzw==
2016-01-11 11:54:25.893 ThaliTest[1220:4031844] client session: disconnect,
2016-01-11 11:54:25.893 ThaliTest[1220:4031844] client session: stateChange:2->0 1452509661366.1699.C11Mzw==
,2016-01-11 11:54:25.902 ThaliTest[1220:4031844] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,2016-01-11 11:54:25.910 ThaliTest[1220:4032740] server session: connected
2016-01-11 11:54:25.914 ThaliTest[1220:4032740] server session: stateChange:1->2 1452509661366.1699
,# setup
,2016-01-11 11:54:25.954 ThaliTest[1220:4031668] server relay: socket disconnected
2016-01-11 11:54:25.954 ThaliTest[1220:4031668] server relay: 0x1d2c1f00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-11 11:54:25.965 ThaliTest[1220:4032740] server session: not connected 1452509661366.1699
,calling stopBroadcasting
,2016-01-11 11:54:26.163 ThaliTest[1220:4031844] jxcore: stopBroadcasting
,2016-01-11 11:54:26.163 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
,2016-01-11 11:54:26.163 ThaliTest[1220:4031844] multipeer session: stop timer
,2016-01-11 11:54:26.164 ThaliTest[1220:4031844] server session: disconnect
,2016-01-11 11:54:26.165 ThaliTest[1220:4031844] server session: stateChange:2->0 1452509661366.1699
,2016-01-11 11:54:26.310 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-11 11:54:26.496 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:26.499 ThaliTest[1220:4031844] server: starting 1452509666496.1220./vaZJQ==
2016-01-11 11:54:26.500 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d6abb40
2016-01-11 11:54:26.500 ThaliTest[1220:4031844] THEMultipeerSession in,itialized peer 1452509666496.1220
2016-01-11 11:54:26.500 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-11 11:54:27.294 ThaliTest[1220:4031668] client: found peer: 1452509661366.1699.C11Mzw==
2016-01-11 11:54:27.295 ThaliTest[1220:4031844] jxcore: connect 1452509661366.1699.C11Mzw==
2016-01-11 11:54:27.295 ThaliTest[1220:4031844] client session: co,nnect
2016-01-11 11:54:27.295 ThaliTest[1220:4031844] client session: stateChange:0->1 1452509661366.1699.C11Mzw==
,2016-01-11 11:54:27.864 ThaliTest[1220:4031668] client: lost peer: 1452509661366.1699.C11Mzw==
2016-01-11 11:54:27.864 ThaliTest[1220:4031668] client session: onPeerLost: 1452509661366.1699.C11Mzw==
2016-01-11 11:54:27.865 ThaliTest[1220:4031668] client ,session: onLinkFailure: 1452509661366.1699.C11Mzw==
2016-01-11 11:54:27.865 ThaliTest[1220:4031668] client session: disconnect
2016-01-11 11:54:27.865 ThaliTest[1220:4031668] client session: stateChange:1->0 1452509661366.1699.C11Mzw==
2016-01-11 11:54:,27.866 ThaliTest[1220:4031668] client session: fireConnectCallback: 1452509661366.1699.C11Mzw==
2016-01-11 11:54:27.866 ThaliTest[1220:4031668] jxcore: connect: fail: Peer disconnected
2016-01-11 11:54:27.867 ThaliTest[1220:4031668] client: found peer: 1,452509666476.1699.ArKldA==
2016-01-11 11:54:27.868 ThaliTest[1220:4031844] jxcore: connect 1452509666476.1699.ArKldA==
2016-01-11 11:54:27.868 ThaliTest[1220:4031844] client session: connect
2016-01-11 11:54:27.869 ThaliTest[1220:4031844] client session,: stateChange:0->1 1452509666476.1699.ArKldA==
,2016-01-11 11:54:28.050 ThaliTest[1220:4031668] multipeer session: reset timer
2016-01-11 11:54:28.050 ThaliTest[1220:4031668] multipeer session: stop timer
2016-01-11 11:54:28.050 ThaliTest[1220:4031668] multipeer session: start timer: 0x1d6abb40
2016-,01-11 11:54:28.050 ThaliTest[1220:4031668] server session: connect
2016-01-11 11:54:28.051 ThaliTest[1220:4031668] server session: stateChange:0->1 1452509666476.1699
2016-01-11 11:54:28.058 ThaliTest[1220:4031668] server: accepting invitation 1452509666476.1699
,2016-01-11 11:54:28.874 ThaliTest[1220:4031844] jxcore: connect 1452509661366.1699.C11Mzw==
2016-01-11 11:54:28.875 ThaliTest[1220:4031844] client: connect: unreachable 1452509661366.1699.C11Mzw==
2016-01-11 11:54:28.875 ThaliTest[1220:4031844] jxcore: connect: fail: Peer unreachable
,2016-01-11 11:54:30.626 ThaliTest[1220:4032729] client session: connected
2016-01-11 11:54:30.626 ThaliTest[1220:4032729] client session: stateChange:1->2 1452509666476.1699.ArKldA==
,2016-01-11 11:54:30.635 ThaliTest[1220:4032727] client session: fireConnectCallback: 1452509666476.1699.ArKldA==
2016-01-11 11:54:30.635 ThaliTest[1220:4032727] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be ,within range
2016-01-11 11:54:30.637 ThaliTest[1220:4031844] jxcore: connect 1452509666476.1699.ArKldA==
,2016-01-11 11:54:30.637 ThaliTest[1220:4031844] client: already connect(ing/ed) to 1452509666476.1699.ArKldA==
2016-01-11 11:54:30.638 ThaliTest[1220:4031844] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
2016-01-11 11:54:30.640 ThaliTest[1220:4031844] jxcore: disconnect
2016-01-11 11:54:30.640 ThaliTest[1220:4031844] client session: disconnectFromPeer: 1452509666476.1699.ArKldA==
,2016-01-11 11:54:30.640 ThaliTest[1220:4031844] client session: disconnect
2016-01-11 11:54:30.640 ThaliTest[1220:4031844] client session: stateChange:2->0 1452509666476.1699.ArKldA==
,2016-01-11 11:54:30.646 ThaliTest[1220:4031844] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-11 11:54:30.749 ThaliTest[1220:4032727] server session: connected
2016-01-11 11:54:30.749 ThaliTest[1220:4032727] server session: stateChange:1->2 1452509666476.1699
,2016-01-11 11:54:30.754 ThaliTest[1220:4031668] server relay: socket disconnected
2016-01-11 11:54:30.754 ThaliTest[1220:4031668] server relay: 0x1d1c62c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-11 11:54:30.796 ThaliTest[1220:4032722] server session: not connected 1452509666476.1699
,calling stopBroadcasting
2016-01-11 11:54:30.808 ThaliTest[1220:4031844] jxcore: stopBroadcasting
2016-01-11 11:54:30.809 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
2016-01-11 11:54:30.809 ThaliTest[1220:4031844] multipeer session: stop t,imer
2016-01-11 11:54:30.809 ThaliTest[1220:4031844] server session: disconnect
2016-01-11 11:54:30.809 ThaliTest[1220:4031844] server session: stateChange:2->0 1452509666476.1699
,2016-01-11 11:54:31.166 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-11 11:54:32.398 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:32.401 ThaliTest[1220:4031844] server: starting 1452509672398.1220.C+LQdg==
2016-01-11 11:54:32.401 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d5d88b0
2016-01-11 11:54:32.401 ThaliTest[1220:4031844] THEMultipeerSession in,itialized peer 1452509672398.1220
2016-01-11 11:54:32.402 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-11 11:54:33.563 ThaliTest[1220:4031668] client: found peer: 1452509672384.1699.WepvLA==
2016-01-11 11:54:33.564 ThaliTest[1220:4031844] jxcore: connect 1452509672384.1699.WepvLA==
2016-01-11 11:54:33.564 ThaliTest[1220:4031844] client session: co,nnect
2016-01-11 11:54:33.564 ThaliTest[1220:4031844] client session: stateChange:0->1 1452509672384.1699.WepvLA==
,2016-01-11 11:54:33.641 ThaliTest[1220:4031668] multipeer session: reset timer
2016-01-11 11:54:33.641 ThaliTest[1220:4031668] multipeer session: stop timer
2016-01-11 11:54:33.641 ThaliTest[1220:4031668] multipeer session: start timer: 0x1d5d88b0
2016-,01-11 11:54:33.641 ThaliTest[1220:4031668] server session: connect
2016-01-11 11:54:33.641 ThaliTest[1220:4031668] server session: stateChange:0->1 1452509672384.1699
,2016-01-11 11:54:33.652 ThaliTest[1220:4031668] server: accepting invitation 1452509672384.1699
,2016-01-11 11:54:36.120 ThaliTest[1220:4032802] server session: connected
2016-01-11 11:54:36.120 ThaliTest[1220:4032802] server session: stateChange:1->2 1452509672384.1699
,2016-01-11 11:54:36.155 ThaliTest[1220:4031668] server relay: socket disconnected
2016-01-11 11:54:36.156 ThaliTest[1220:4031668] server relay: 0x1d41dd60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-11 11:54:36.188 ThaliTest[1220:4032729] server session: not connected 1452509672384.1699
,2016-01-11 11:54:36.239 ThaliTest[1220:4032729] client session: connected
,2016-01-11 11:54:36.239 ThaliTest[1220:4032729] client session: stateChange:1->2 1452509672384.1699.WepvLA==
,2016-01-11 11:54:36.247 ThaliTest[1220:4032729] client session: fireConnectCallback: 1452509672384.1699.WepvLA==
,2016-01-11 11:54:36.247 ThaliTest[1220:4032729] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-11 11:54:36.251 ThaliTest[1220:4031844] jxcore: disconnect
,2016-01-11 11:54:36.251 ThaliTest[1220:4031844] client session: disconnectFromPeer: 1452509672384.1699.WepvLA==
,2016-01-11 11:54:36.251 ThaliTest[1220:4031844] client session: disconnect
2016-01-11 11:54:36.252 ThaliTest[1220:4031844] client session: stateChange:2->0 1452509672384.1699.WepvLA==
,2016-01-11 11:54:36.265 ThaliTest[1220:4031844] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
,2016-01-11 11:54:36.267 ThaliTest[1220:4031844] jxcore: disconnect
,2016-01-11 11:54:36.267 ThaliTest[1220:4031844] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-11 11:54:36.639 ThaliTest[1220:4031844] jxcore: stopBroadcasting
2016-01-11 11:54:36.639 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
2016-01-11 11:54:36.639 ThaliTest[1220:4031844] multipeer session: stop timer
2016-01-11 11:54:36.,640 ThaliTest[1220:4031844] server session: disconnect
2016-01-11 11:54:36.640 ThaliTest[1220:4031844] server session: stateChange:2->0 1452509672384.1699
2016-01-11 11:54:36.642 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-11 11:54:37.154 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:37.157 ThaliTest[1220:4031844] server: starting 1452509677154.1220.2HrfNw==
2016-01-11 11:54:37.158 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d4319e0
2016-01-11 11:54:37.158 ThaliTest[1220:4031844] THEMultipeerSession in,itialized peer 1452509677154.1220
2016-01-11 11:54:37.158 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-11 11:54:37.782 ThaliTest[1220:4031668] client: found peer: 1452509672384.1699.WepvLA==
[{"peerIdentifier":"1452509672384.1699.WepvLA==","peerName":"(null)","peerAvailable":true}]
2016-01-11 11:54:37.784 ThaliTest[1220:4031844] jxcore: connect 14,52509672384.1699.WepvLA==
2016-01-11 11:54:37.784 ThaliTest[1220:4031844] client session: connect
2016-01-11 11:54:37.784 ThaliTest[1220:4031844] client session: stateChange:0->1 1452509672384.1699.WepvLA==
,2016-01-11 11:54:38.290 ThaliTest[1220:4031668] client: lost peer: 1452509672384.1699.WepvLA==
2016-01-11 11:54:38.290 ThaliTest[1220:4031668] client session: onPeerLost: 1452509672384.1699.WepvLA==
2016-01-11 11:54:38.291 ThaliTest[1220:4031668] client ,session: onLinkFailure: 1452509672384.1699.WepvLA==
2016-01-11 11:54:38.291 ThaliTest[1220:4031668] client session: disconnect
2016-01-11 11:54:38.291 ThaliTest[1220:4031668] client session: stateChange:1->0 1452509672384.1699.WepvLA==
2016-01-11 11:54:,38.292 ThaliTest[1220:4031668] client session: fireConnectCallback: 1452509672384.1699.WepvLA==
2016-01-11 11:54:38.292 ThaliTest[1220:4031668] jxcore: connect: fail: Peer disconnected
[{"peerIdentifier":"1452509672384.1699.WepvLA==","peerName":"(null)",,"peerAvailable":false}]
,2016-01-11 11:54:38.362 ThaliTest[1220:4031668] client: found peer: 1452509677139.1699.NryW3g==
[{"peerIdentifier":"1452509677139.1699.NryW3g==","peerName":"(null)","peerAvailable":true}]
2016-01-11 11:54:38.363 ThaliTest[1220:4031844] jxcore: connect 14,52509677139.1699.NryW3g==
2016-01-11 11:54:38.363 ThaliTest[1220:4031844] client session: connect
2016-01-11 11:54:38.363 ThaliTest[1220:4031844] client session: stateChange:0->1 1452509677139.1699.NryW3g==
,2016-01-11 11:54:38.497 ThaliTest[1220:4031668] multipeer session: reset timer
2016-01-11 11:54:38.497 ThaliTest[1220:4031668] multipeer session: stop timer
2016-01-11 11:54:38.497 ThaliTest[1220:4031668] multipeer session: start timer: 0x1d4319e0
2016-,01-11 11:54:38.497 ThaliTest[1220:4031668] server session: connect
2016-01-11 11:54:38.498 ThaliTest[1220:4031668] server session: stateChange:0->1 1452509677139.1699
,2016-01-11 11:54:38.504 ThaliTest[1220:4031668] server: accepting invitation 1452509677139.1699
,2016-01-11 11:54:39.296 ThaliTest[1220:4031844] jxcore: connect 1452509672384.1699.WepvLA==
2016-01-11 11:54:39.296 ThaliTest[1220:4031844] client: connect: unreachable 1452509672384.1699.WepvLA==
2016-01-11 11:54:39.296 ThaliTest[1220:4031844] jxcore: c,onnect: fail: Peer unreachable
,2016-01-11 11:54:41.034 ThaliTest[1220:4032802] client session: connected
2016-01-11 11:54:41.034 ThaliTest[1220:4032802] client session: stateChange:1->2 1452509677139.1699.NryW3g==
2016-01-11 11:54:41.038 ThaliTest[1220:4032802] client session: fireCon,nectCallback: 1452509677139.1699.NryW3g==
2016-01-11 11:54:41.038 ThaliTest[1220:4032802] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
ok 91 First connect should succeed
,2016-01-11 11:54:41.073 ThaliTest[1220:4031668] client: relay established
2016-01-11 11:54:41.073 ThaliTest[1220:4031668] client: new accepted socket: 0x1753f620
,2016-01-11 11:54:41.101 ThaliTest[1220:4032722] server session: connected
2016-01-11 11:54:41.101 ThaliTest[1220:4032722] server session: stateChange:1->2 1452509677139.1699
,2016-01-11 11:54:41.121 ThaliTest[1220:4031668] server relay: connected (to port: 5001)
,ok 92 the test messages should be equal
ok 93 First send should succeed
,2016-01-11 11:54:41.181 ThaliTest[1220:4031668] client: socket closed
2016-01-11 11:54:41.181 ThaliTest[1220:4031668] client relay: socket disconnected
2016-01-11 11:54:41.181 ThaliTest[1220:4031668] client relay: 0x1753f620 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-11 11:54:41.181 ThaliTest[1220:4031668] client session: socket closed: 1452509677139.1699.NryW3g==
2016-01-11 ,11:54:41.181 ThaliTest[1220:4031668] client session: onLinkFailure: 1452509677139.1699.NryW3g==
2016-01-11 11:54:41.182 ThaliTest[1220:4031668] client session: disconnect
2016-01-11 11:54:41.182 ThaliTest[1220:4031668] client session: stateChange:2->0 14,52509677139.1699.NryW3g==
,2016-01-11 11:54:41.190 ThaliTest[1220:4031668] client session: fireConnectionErrorEvent: 1452509677139.1699.NryW3g==
2016-01-11 11:54:41.197 ThaliTest[1220:4031844] jxcore: connect 1452509677139.1699.NryW3g==
2016-01-11 11:54:41.197 ThaliTest[1220:40318,44] client session: connect
2016-01-11 11:54:41.197 ThaliTest[1220:4031844] client session: stateChange:0->1 1452509677139.1699.NryW3g==
,2016-01-11 11:54:41.237 ThaliTest[1220:4032729] server session: not connected 1452509677139.1699
,2016-01-11 11:54:41.311 ThaliTest[1220:4031668] multipeer session: reset timer
2016-01-11 11:54:41.312 ThaliTest[1220:4031668] multipeer session: stop timer
2016-01-11 11:54:41.313 ThaliTest[1220:4031668] multipeer session: start timer: 0x1d4319e0
2016-,01-11 11:54:41.313 ThaliTest[1220:4031668] server: disconnecting to refresh session (1452509677139.1699)
2016-01-11 11:54:41.313 ThaliTest[1220:4031668] server session: disconnect
2016-01-11 11:54:41.313 ThaliTest[1220:4031668] server session: stateChang,e:2->0 1452509677139.1699
2016-01-11 11:54:41.315 ThaliTest[1220:4031668] server session: connect
2016-01-11 11:54:41.315 ThaliTest[1220:4031668] server session: stateChange:0->1 1452509677139.1699
,2016-01-11 11:54:41.328 ThaliTest[1220:4031668] server: accepting invitation 1452509677139.1699
,2016-01-11 11:54:43.974 ThaliTest[1220:4032740] client session: connected
2016-01-11 11:54:43.975 ThaliTest[1220:4032740] client session: stateChange:1->2 1452509677139.1699.NryW3g==
2016-01-11 11:54:43.976 ThaliTest[1220:4032722] server session: connected
,2016-01-11 11:54:43.976 ThaliTest[1220:4032722] server session: stateChange:1->2 1452509677139.1699
,2016-01-11 11:54:43.987 ThaliTest[1220:4032724] client session: fireConnectCallback: 1452509677139.1699.NryW3g==
2016-01-11 11:54:43.988 ThaliTest[1220:4032724] jxcore: connect: success
ok 94 Should be able to connect without error
,ok 95 Port should be within range
2016-01-11 11:54:43.992 ThaliTest[1220:4031668] server relay: connected (to port: 5001)
ok 96 Second connect should succeed
,2016-01-11 11:54:44.016 ThaliTest[1220:4031668] client: relay established
2016-01-11 11:54:44.017 ThaliTest[1220:4031668] client: new accepted socket: 0x1761e380
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2016-01-11 11:54:44.124 ThaliTest[1220:4031668] client: socket closed
,2016-01-11 11:54:44.125 ThaliTest[1220:4031668] client relay: socket disconnected
2016-01-11 11:54:44.125 ThaliTest[1220:4031668] client relay: 0x1761e380 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-11 11:54:44.125 ThaliTest[1220:4031668] client session: socket closed: 1452509677139.1699.NryW3g==
2016-01-11 11:54:44.125 ThaliTest[1220:4031668] client session: onLinkFailure: 1452509677139.1699.NryW3g==
2016-01-11 11:54:44.125 ThaliTest[1220:4,031668] client session: disconnect
2016-01-11 11:54:44.126 ThaliTest[1220:4031668] client session: stateChange:2->0 1452509677139.1699.NryW3g==
,2016-01-11 11:54:44.144 ThaliTest[1220:4031668] client session: fireConnectionErrorEvent: 1452509677139.1699.NryW3g==
,2016-01-11 11:54:44.168 ThaliTest[1220:4032724] server session: not connected 1452509677139.1699
,calling stopBroadcasting
,2016-01-11 11:54:44.444 ThaliTest[1220:4031844] jxcore: stopBroadcasting
,2016-01-11 11:54:44.445 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
,2016-01-11 11:54:44.446 ThaliTest[1220:4031844] multipeer session: stop timer
,2016-01-11 11:54:44.447 ThaliTest[1220:4031844] server session: disconnect
,2016-01-11 11:54:44.447 ThaliTest[1220:4031844] server session: stateChange:2->0 1452509677139.1699
,2016-01-11 11:54:44.533 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/30E9C032-7FF7-4CC1-B1A0-0FBB08933497/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-11 11:54:45.941 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:45.944 ThaliTest[1220:4031844] server: starting cV_3gRnFnBLDWB9ABPqW7Q.NEZamQ==
,2016-01-11 11:54:45.949 ThaliTest[1220:4031844] multipeer session: start timer: 0x1d234030
,2016-01-11 11:54:45.952 ThaliTest[1220:4031844] THEMultipeerSession initialized peer cV_3gRnFnBLDWB9ABPqW7Q
,2016-01-11 11:54:45.953 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
,ok 100 started event should occur in right order
,Now in TRM stop
,State of this._isStarted: true
,ok 101 stopping event should occur in right order
,About to call stopBroadcasting
,2016-01-11 11:54:45.958 ThaliTest[1220:4031844] jxcore: stopBroadcasting
,2016-01-11 11:54:45.959 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
,2016-01-11 11:54:45.959 ThaliTest[1220:4031844] multipeer session: stop timer
,2016-01-11 11:54:45.962 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,ok 102 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/30E9C032-7FF7-4CC1-B1A0-0FBB08933497/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-11 11:54:46.493 ThaliTest[1220:4031844] jxcore: startBroadcasting
,2016-01-11 11:54:46.496 ThaliTest[1220:4031844] server: starting cV_3gRnFnBLDWB9ABPqW7Q.e9QR6A==
2016-01-11 11:54:46.497 ThaliTest[1220:4031844] multipeer session: start timer: 0x1f190cb0
2016-01-11 11:54:46.497 ThaliTest[1220:4031844] THEMultipeerSessio,n initialized peer cV_3gRnFnBLDWB9ABPqW7Q
2016-01-11 11:54:46.497 ThaliTest[1220:4031844] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
Now in TRM stop
State of this._isStar,ted: true
About to call stopBroadcasting
2016-01-11 11:54:46.499 ThaliTest[1220:4031844] jxcore: stopBroadcasting
2016-01-11 11:54:46.499 ThaliTest[1220:4031844] THEMultipeerSession stopping peer
,2016-01-11 11:54:46.499 ThaliTest[1220:4031844] multipeer session: stop timer
2016-01-11 11:54:46.505 ThaliTest[1220:4031844] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
