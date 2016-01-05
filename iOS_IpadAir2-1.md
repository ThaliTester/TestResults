#### Test 54970261aa56788_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54970261aa56788/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/59F2B042-2A3B-47FB-9CF7-D13A51B7875E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/59F2B042-2A3B-47FB-9CF7-D13A51B7875E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54970261aa56788/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54970261aa56788/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/04C99F0A-0035-441F-96B4-AC509865FBCE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65433"
,(lldb)     command script import "/tmp/59F2B042-2A3B-47FB-9CF7-D13A51B7875E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 19:39:21.645 ThaliTest[1361:2911286] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/25C7DBBA-7AE2-4A7E-8AE5-AB3C7B697C55/Library/Cookies/Cookies.binarycookies
,2016-01-05 19:39:21.963 ThaliTest[1361:2911286] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 19:39:21.964 ThaliTest[1361:2911286] Multi-tasking -> Device: YES, App: YES
,2016-01-05 19:39:21.972 ThaliTest[1361:2911286] Unlimited access to network resources
,2016-01-05 19:39:21.978 ThaliTest[1361:2911286] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 19:39:30.764 ThaliTest[1361:2911286] Resetting plugins due to page load.
,2016-01-05 19:39:34.423 ThaliTest[1361:2911286] Finished load of: file:///var/mobile/Containers/Bundle/Application/04C99F0A-0035-441F-96B4-AC509865FBCE/ThaliTest.app/www/index.html
,2016-01-05 19:39:34.587 ThaliTest[1361:2911286] JXcore Cordova plugin initializing
,2016-01-05 19:39:34.588 ThaliTest[1361:2911521] JXcore instance initializing
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
ok 11 should not throw
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
,2016-01-05 19:44:48.883 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:48.899 ThaliTest[1361:2911521] server: starting 1452019488883.1361.rtBi9w==
,2016-01-05 19:44:48.901 ThaliTest[1361:2911521] multipeer session: start timer: 0x1ba28a70
2016-01-05 19:44:48.901 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019488883.1361
,2016-01-05 19:44:48.903 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2016-01-05 19:44:48.910 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:44:48.911 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
,2016-01-05 19:44:48.911 ThaliTest[1361:2911521] multipeer session: stop timer
2016-01-05 19:44:48.912 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
2016-01-05 19:44:48.917 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:48.921 ThaliTest[1361:2911521] server: starting 1452019488916.1361.mBWVNg==
,2016-01-05 19:44:48.922 ThaliTest[1361:2911521] multipeer session: start timer: 0x17fd8b10
2016-01-05 19:44:48.923 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019488916.1361
2016-01-05 19:44:48.924 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2016-01-05 19:44:48.926 ThaliTest[1361:2911521] jxcore: stopBroadcasting
2016-01-05 19:44:48.927 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
2016-01-05 19:44:48.927 ThaliTest[1361:2911521] multipeer session: stop timer
,2016-01-05 19:44:48.930 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2016-01-05 19:44:48.933 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:48.938 ThaliTest[1361:2911521] server: starting 1452019488932.1361.cNYg4g==
2016-01-05 19:44:48.938 ThaliTest[1361:2911521] multipeer session: start timer: 0x1ba2b710
2016-01-05 19:44:48.939 ThaliTest[1361:2911521] THEMultipeerSession in,itialized peer 1452019488932.1361
2016-01-05 19:44:48.939 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2016-01-05 19:44:48.942 ThaliTest[1361:2911521] jxcore: stopBroadcasting
2016-01-05 19:44:48.942 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
2016-01-05 19:44:48.942 ThaliTest[1361:2911521] multipeer session: stop timer
2016-01-05 19:44:48.,943 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:48.946 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:48.950 ThaliTest[1361:2911521] server: starting 1452019488945.1361.z+/jpw==
2016-01-05 19:44:48.951 ThaliTest[1361:2911521] multipeer session: start timer: 0x1b808c20
2016-01-05 19:44:48.951 ThaliTest[1361:2911521] THEMultipeerSession in,itialized peer 1452019488945.1361
2016-01-05 19:44:48.951 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-05 19:44:48.953 ThaliTest[1361:2911521] jxcore: stopBroadcasting
2,016-01-05 19:44:48.954 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
2016-01-05 19:44:48.954 ThaliTest[1361:2911521] multipeer session: stop timer
2016-01-05 19:44:48.955 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
ok 52 Should, be able to call stopBroadcasting without error
2016-01-05 19:44:48.957 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:48.962 ThaliTest[1361:2911521] server: starting 1452019488957.1361.SeuZhQ==
2016-01-05 19:44:48.963 ThaliTest[1361:2911521] multipeer session: start timer: 0x1b8078e0
2016-01-05 19:44:48.963 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019488957.1361
,2016-01-05 19:44:48.970 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2016-01-05 19:44:48.978 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:44:48.978 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
,2016-01-05 19:44:48.980 ThaliTest[1361:2911521] multipeer session: stop timer
,2016-01-05 19:44:48.982 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:48.986 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:48.989 ThaliTest[1361:2911521] server: starting 1452019488986.1361.T0dQHg==
,2016-01-05 19:44:48.990 ThaliTest[1361:2911521] multipeer session: start timer: 0x17fda2d0
,2016-01-05 19:44:48.991 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019488986.1361
,2016-01-05 19:44:48.993 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2016-01-05 19:44:48.997 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:44:48.998 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
,2016-01-05 19:44:48.998 ThaliTest[1361:2911521] multipeer session: stop timer
,2016-01-05 19:44:49.001 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:49.003 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:49.006 ThaliTest[1361:2911521] server: starting 1452019489003.1361.inxdGg==
,2016-01-05 19:44:49.007 ThaliTest[1361:2911521] multipeer session: start timer: 0x17fda2d0
,2016-01-05 19:44:49.010 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019489003.1361
,2016-01-05 19:44:49.011 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2016-01-05 19:44:49.014 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:44:49.014 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
,2016-01-05 19:44:49.016 ThaliTest[1361:2911521] multipeer session: stop timer
,2016-01-05 19:44:49.017 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:49.021 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:49.023 ThaliTest[1361:2911521] server: starting 1452019489020.1361.BSmqCw==
,2016-01-05 19:44:49.025 ThaliTest[1361:2911521] multipeer session: start timer: 0x17fd91a0
,2016-01-05 19:44:49.027 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019489020.1361
,2016-01-05 19:44:49.029 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-05 19:44:49.031 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:44:49.032 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
,2016-01-05 19:44:49.032 ThaliTest[1361:2911521] multipeer session: stop timer
,2016-01-05 19:44:49.034 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:49.037 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:49.040 ThaliTest[1361:2911521] server: starting 1452019489037.1361.hksX2A==
,2016-01-05 19:44:49.041 ThaliTest[1361:2911521] multipeer session: start timer: 0x1b806140
,2016-01-05 19:44:49.042 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019489037.1361
,2016-01-05 19:44:49.045 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-05 19:44:49.048 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:44:49.049 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
,2016-01-05 19:44:49.049 ThaliTest[1361:2911521] multipeer session: stop timer
,2016-01-05 19:44:49.050 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-05 19:44:49.054 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:49.057 ThaliTest[1361:2911521] server: starting 1452019489054.1361.MSMOnw==
,2016-01-05 19:44:49.058 ThaliTest[1361:2911521] multipeer session: start timer: 0x17fd9f50
,2016-01-05 19:44:49.062 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019489054.1361
,2016-01-05 19:44:49.064 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-05 19:44:49.065 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:44:49.066 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
,2016-01-05 19:44:49.066 ThaliTest[1361:2911521] multipeer session: stop timer
,2016-01-05 19:44:49.067 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-05 19:44:49.814 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:49.817 ThaliTest[1361:2911521] server: starting 1452019489813.1361.YWAiZQ==
,2016-01-05 19:44:49.818 ThaliTest[1361:2911521] multipeer session: start timer: 0x1ba2f170
,2016-01-05 19:44:49.818 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019489813.1361
,2016-01-05 19:44:49.819 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
,2016-01-05 19:44:49.822 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:49.822 ThaliTest[1361:2911521] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2016-01-05 19:44:49.825 ThaliTest[1361:2911521] jxcore: stopBroadcasting
2016-01-05 19:44:49.826 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
2016-01-05 19:44:49.826 ThaliTest[1361:2911521] multipee,r session: stop timer
2016-01-05 19:44:49.826 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-05 19:44:52.962 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:52.965 ThaliTest[1361:2911521] server: starting 1452019492961.1361.NOxySw==
,2016-01-05 19:44:52.966 ThaliTest[1361:2911521] multipeer session: start timer: 0x17fd8e50
,2016-01-05 19:44:52.966 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019492961.1361
,2016-01-05 19:44:52.966 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
,2016-01-05 19:44:52.970 ThaliTest[1361:2911521] jxcore: connect foobar
2016-01-05 19:44:52.971 ThaliTest[1361:2911521] client: unknown peer foobar
2016-01-05 19:44:52.971 ThaliTest[1361:2911521] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2016-01-05 19:44:52.974 ThaliTest[1361:2911521] jxcore: stopBroadcasting
2016-01-05 19:44:52.975 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
2016-01-05 19:44:52.975 ThaliTest[1361:2911521] multipeer session: stop timer
2016-01-05 19:44:52.976 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-05 19:44:53.447 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:53.451 ThaliTest[1361:2911521] server: starting 1452019493447.1361.2yHV4w==
2016-01-05 19:44:53.452 ThaliTest[1361:2911521] multipeer session: start timer: 0x1ba344b0
,2016-01-05 19:44:53.452 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019493447.1361
2016-01-05 19:44:53.453 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
,2016-01-05 19:44:53.457 ThaliTest[1361:2911521] jxcore: disconnect
2016-01-05 19:44:53.457 ThaliTest[1361:2911521] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-05 19:44:53.460 ThaliTest[1361:2911521] jxcore: stopBroadcasting
2016-01-05 19:44:53.461 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
2016-01-05 19:44:53.461 ThaliTest[1361:2911521] multipeer session: stop timer
2016-01-05 19:44:53.,461 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-05 19:44:54.007 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:44:54.011 ThaliTest[1361:2911521] server: starting 1452019494007.1361.eWIdzQ==
,2016-01-05 19:44:54.011 ThaliTest[1361:2911521] multipeer session: start timer: 0x1ba36380
,2016-01-05 19:44:54.012 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019494007.1361
2016-01-05 19:44:54.013 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-05 19:44:55.100 ThaliTest[1361:2911286] client: found peer: 1452019490655.980.3hnmXQ==
,2016-01-05 19:44:55.103 ThaliTest[1361:2911521] jxcore: connect 1452019490655.980.3hnmXQ==
,2016-01-05 19:44:55.103 ThaliTest[1361:2911521] client session: connect
,2016-01-05 19:44:55.104 ThaliTest[1361:2911521] client session: stateChange:0->1 1452019490655.980.3hnmXQ==
,2016-01-05 19:44:55.562 ThaliTest[1361:2911286] multipeer session: reset timer
,2016-01-05 19:44:55.562 ThaliTest[1361:2911286] multipeer session: stop timer
2016-01-05 19:44:55.563 ThaliTest[1361:2911286] multipeer session: start timer: 0x1ba36380
,2016-01-05 19:44:55.563 ThaliTest[1361:2911286] server session: connect
2016-01-05 19:44:55.564 ThaliTest[1361:2911286] server session: stateChange:0->1 1452019490655.980
,2016-01-05 19:44:55.570 ThaliTest[1361:2911286] server: accepting invitation 1452019490655.980
,2016-01-05 19:44:58.979 ThaliTest[1361:2912060] client session: connected
2016-01-05 19:44:58.980 ThaliTest[1361:2912060] client session: stateChange:1->2 1452019490655.980.3hnmXQ==
,2016-01-05 19:44:58.985 ThaliTest[1361:2912060] client session: fireConnectCallback: 1452019490655.980.3hnmXQ==
2016-01-05 19:44:58.986 ThaliTest[1361:2912060] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-05 19:44:58.990 ThaliTest[1361:2911521] jxcore: disconnect
,2016-01-05 19:44:58.991 ThaliTest[1361:2911521] client session: disconnectFromPeer: 1452019490655.980.3hnmXQ==
,2016-01-05 19:44:58.992 ThaliTest[1361:2911521] client session: disconnect
2016-01-05 19:44:58.992 ThaliTest[1361:2911521] client session: stateChange:2->0 1452019490655.980.3hnmXQ==
,2016-01-05 19:44:59.065 ThaliTest[1361:2911521] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-05 19:44:59.180 ThaliTest[1361:2912054] server session: connected
2016-01-05 19:44:59.181 ThaliTest[1361:2912054] server session: stateChange:1->2 1452019490655.980
,2016-01-05 19:44:59.187 ThaliTest[1361:2911286] server relay: socket disconnected
,2016-01-05 19:44:59.188 ThaliTest[1361:2911286] server relay: 0x1bb27db0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 19:44:59.236 ThaliTest[1361:2912054] server session: not connected 1452019490655.980
,calling stopBroadcasting
,2016-01-05 19:44:59.670 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:44:59.671 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
,2016-01-05 19:44:59.671 ThaliTest[1361:2911521] multipeer session: stop timer
,2016-01-05 19:44:59.672 ThaliTest[1361:2911521] server session: disconnect
2016-01-05 19:44:59.673 ThaliTest[1361:2911521] server session: stateChange:2->0 1452019490655.980
,2016-01-05 19:44:59.743 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-05 19:45:01.088 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:45:01.092 ThaliTest[1361:2911521] server: starting 1452019501088.1361.2oCJJw==
,2016-01-05 19:45:01.093 ThaliTest[1361:2911521] multipeer session: start timer: 0x1ba3a3b0
2016-01-05 19:45:01.094 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019501088.1361
2016-01-05 19:45:01.094 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-05 19:45:02.449 ThaliTest[1361:2911286] client: found peer: 1452019497729.980.9fJ0Fg==
2016-01-05 19:45:02.451 ThaliTest[1361:2911521] jxcore: connect 1452019497729.980.9fJ0Fg==
2016-01-05 19:45:02.452 ThaliTest[1361:2911521] client session: connect
2016-01-05 19:45:02.452 ThaliTest[1361:2911521] client session: stateChange:0->1 1452019497729.980.9fJ0Fg==
,2016-01-05 19:45:02.457 ThaliTest[1361:2911286] multipeer session: reset timer
2016-01-05 19:45:02.457 ThaliTest[1361:2911286] multipeer session: stop timer
,2016-01-05 19:45:02.458 ThaliTest[1361:2911286] multipeer session: start timer: 0x1ba3a3b0
2016-01-05 19:45:02.458 ThaliTest[1361:2911286] server session: connect
,2016-01-05 19:45:02.458 ThaliTest[1361:2911286] server session: stateChange:0->1 1452019497729.980
,2016-01-05 19:45:02.468 ThaliTest[1361:2911286] server: accepting invitation 1452019497729.980
,2016-01-05 19:45:05.947 ThaliTest[1361:2912056] client session: connected
2016-01-05 19:45:05.947 ThaliTest[1361:2912056] client session: stateChange:1->2 1452019497729.980.9fJ0Fg==
,2016-01-05 19:45:05.991 ThaliTest[1361:2912060] client session: fireConnectCallback: 1452019497729.980.9fJ0Fg==
,2016-01-05 19:45:05.992 ThaliTest[1361:2912060] jxcore: connect: success
,ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2016-01-05 19:45:05.997 ThaliTest[1361:2911521] jxcore: connect 1452019497729.980.9fJ0Fg==
,2016-01-05 19:45:05.997 ThaliTest[1361:2911521] client: already connect(ing/ed) to 1452019497729.980.9fJ0Fg==
,2016-01-05 19:45:05.998 ThaliTest[1361:2911521] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2016-01-05 19:45:06.001 ThaliTest[1361:2911521] jxcore: disconnect
,2016-01-05 19:45:06.001 ThaliTest[1361:2911521] client session: disconnectFromPeer: 1452019497729.980.9fJ0Fg==
,2016-01-05 19:45:06.002 ThaliTest[1361:2911521] client session: disconnect
,2016-01-05 19:45:06.002 ThaliTest[1361:2911521] client session: stateChange:2->0 1452019497729.980.9fJ0Fg==
,2016-01-05 19:45:06.076 ThaliTest[1361:2911521] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-05 19:45:06.252 ThaliTest[1361:2912054] server session: connected
2016-01-05 19:45:06.252 ThaliTest[1361:2912054] server session: stateChange:1->2 1452019497729.980
,2016-01-05 19:45:06.318 ThaliTest[1361:2911286] server relay: socket disconnected
,2016-01-05 19:45:06.318 ThaliTest[1361:2911286] server relay: 0x17fe26e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 19:45:06.375 ThaliTest[1361:2912056] server session: not connected 1452019497729.980
,calling stopBroadcasting
,2016-01-05 19:45:06.498 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:45:06.498 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
,2016-01-05 19:45:06.499 ThaliTest[1361:2911521] multipeer session: stop timer
,2016-01-05 19:45:06.499 ThaliTest[1361:2911521] server session: disconnect
2016-01-05 19:45:06.500 ThaliTest[1361:2911521] server session: stateChange:2->0 1452019497729.980
,2016-01-05 19:45:06.503 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-05 19:45:07.635 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:45:07.639 ThaliTest[1361:2911521] server: starting 1452019507635.1361./UnwPQ==
,2016-01-05 19:45:07.640 ThaliTest[1361:2911521] multipeer session: start timer: 0x17fe2ab0
,2016-01-05 19:45:07.641 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019507635.1361
,2016-01-05 19:45:07.641 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error
,2016-01-05 19:45:08.739 ThaliTest[1361:2911286] client: found peer: 1452019504292.980.HwEYsA==
,2016-01-05 19:45:08.740 ThaliTest[1361:2911521] jxcore: connect 1452019504292.980.HwEYsA==
2016-01-05 19:45:08.741 ThaliTest[1361:2911521] client session: connect
2016-01-05 19:45:08.741 ThaliTest[1361:2911521] client session: stateChange:0->1 1452019504292.980.HwEYsA==
,2016-01-05 19:45:09.846 ThaliTest[1361:2911286] multipeer session: reset timer
2016-01-05 19:45:09.846 ThaliTest[1361:2911286] multipeer session: stop timer
2016-01-05 19:45:09.846 ThaliTest[1361:2911286] multipeer session: start timer: 0x17fe2ab0
2016-,01-05 19:45:09.846 ThaliTest[1361:2911286] server session: connect
2016-01-05 19:45:09.846 ThaliTest[1361:2911286] server session: stateChange:0->1 1452019504292.980
,2016-01-05 19:45:09.849 ThaliTest[1361:2911286] server: accepting invitation 1452019504292.980
,2016-01-05 19:45:12.672 ThaliTest[1361:2912137] client session: connected
,2016-01-05 19:45:12.673 ThaliTest[1361:2912137] client session: stateChange:1->2 1452019504292.980.HwEYsA==
,2016-01-05 19:45:12.695 ThaliTest[1361:2912054] client session: fireConnectCallback: 1452019504292.980.HwEYsA==
2016-01-05 19:45:12.696 ThaliTest[1361:2912054] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-05 19:45:12.699 ThaliTest[1361:2911521] jxcore: disconnect
,2016-01-05 19:45:12.700 ThaliTest[1361:2911521] client session: disconnectFromPeer: 1452019504292.980.HwEYsA==
,2016-01-05 19:45:12.700 ThaliTest[1361:2911521] client session: disconnect
2016-01-05 19:45:12.701 ThaliTest[1361:2911521] client session: stateChange:2->0 1452019504292.980.HwEYsA==
,2016-01-05 19:45:12.773 ThaliTest[1361:2911521] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2016-01-05 19:45:12.776 ThaliTest[1361:2911521] jxcore: disconnect
,2016-01-05 19:45:12.777 ThaliTest[1361:2911521] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-05 19:45:13.067 ThaliTest[1361:2912056] server session: connected
2016-01-05 19:45:13.068 ThaliTest[1361:2912056] server session: stateChange:1->2 1452019504292.980
,2016-01-05 19:45:13.133 ThaliTest[1361:2911286] server relay: socket disconnected
,2016-01-05 19:45:13.133 ThaliTest[1361:2911286] server relay: 0x1bb25a00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-05 19:45:13.189 ThaliTest[1361:2912137] server session: not connected 1452019504292.980
,calling stopBroadcasting
,2016-01-05 19:45:13.308 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:45:13.308 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
,2016-01-05 19:45:13.310 ThaliTest[1361:2911521] multipeer session: stop timer
2016-01-05 19:45:13.311 ThaliTest[1361:2911521] server session: disconnect
2016-01-05 19:45:13.311 ThaliTest[1361:2911521] server session: stateChange:2->0 1452019504292.980
,2016-01-05 19:45:13.319 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-05 19:45:15.723 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:45:15.727 ThaliTest[1361:2911521] server: starting 1452019515723.1361.poqfdw==
2016-01-05 19:45:15.728 ThaliTest[1361:2911521] multipeer session: start timer: 0x17fe5500
,2016-01-05 19:45:15.728 ThaliTest[1361:2911521] THEMultipeerSession initialized peer 1452019515723.1361
2016-01-05 19:45:15.729 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,echo server started
,2016-01-05 19:45:16.696 ThaliTest[1361:2911286] client: found peer: 1452019512061.980.ux/WWw==
,[{"peerIdentifier":"1452019512061.980.ux/WWw==","peerName":"(null)","peerAvailable":true}]
,2016-01-05 19:45:16.699 ThaliTest[1361:2911521] jxcore: connect 1452019512061.980.ux/WWw==
,2016-01-05 19:45:16.699 ThaliTest[1361:2911521] client session: connect
,2016-01-05 19:45:16.700 ThaliTest[1361:2911521] client session: stateChange:0->1 1452019512061.980.ux/WWw==
,2016-01-05 19:45:17.771 ThaliTest[1361:2911286] multipeer session: reset timer
2016-01-05 19:45:17.771 ThaliTest[1361:2911286] multipeer session: stop timer
2016-01-05 19:45:17.771 ThaliTest[1361:2911286] multipeer session: start timer: 0x17fe5500
,2016-01-05 19:45:17.772 ThaliTest[1361:2911286] server session: connect
2016-01-05 19:45:17.772 ThaliTest[1361:2911286] server session: stateChange:0->1 1452019512061.980
,2016-01-05 19:45:17.779 ThaliTest[1361:2911286] server: accepting invitation 1452019512061.980
,2016-01-05 19:45:21.323 ThaliTest[1361:2912056] client session: connected
,2016-01-05 19:45:21.323 ThaliTest[1361:2912056] client session: stateChange:1->2 1452019512061.980.ux/WWw==
,2016-01-05 19:45:21.382 ThaliTest[1361:2912056] client session: fireConnectCallback: 1452019512061.980.ux/WWw==
2016-01-05 19:45:21.383 ThaliTest[1361:2912056] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
,ok 91 First connect should succeed
,2016-01-05 19:45:21.392 ThaliTest[1361:2912056] server session: connected
2016-01-05 19:45:21.393 ThaliTest[1361:2912056] server session: stateChange:1->2 1452019512061.980
,2016-01-05 19:45:21.439 ThaliTest[1361:2911286] client: relay established
2016-01-05 19:45:21.440 ThaliTest[1361:2911286] client: new accepted socket: 0x1ba45f10
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2016-01-05 19:45:21.536 ThaliTest[1361:2911286] client: socket closed
,2016-01-05 19:45:21.537 ThaliTest[1361:2911286] client relay: socket disconnected
,2016-01-05 19:45:21.537 ThaliTest[1361:2911286] client relay: 0x1ba45f10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-05 19:45:21.537 ThaliTest[1361:2911286] client session: socket closed: 1452019512061.980.ux/WWw==
2016-01-05 19:45:21.537 ThaliTest[1361:2911286] client session: onLinkFailure: 1452019512061.980.ux/WWw==
2016-01-05 19:45:21.538 ThaliTest[1361:291,1286] client session: disconnect
,2016-01-05 19:45:21.538 ThaliTest[1361:2911286] client session: stateChange:2->0 1452019512061.980.ux/WWw==
,2016-01-05 19:45:21.547 ThaliTest[1361:2911286] client session: fireConnectionErrorEvent: 1452019512061.980.ux/WWw==
,2016-01-05 19:45:21.550 ThaliTest[1361:2911521] jxcore: connect 1452019512061.980.ux/WWw==
2016-01-05 19:45:21.551 ThaliTest[1361:2911521] client session: connect
2016-01-05 19:45:21.551 ThaliTest[1361:2911521] client session: stateChange:0->1 1452019512061.980.ux/WWw==
,2016-01-05 19:45:21.612 ThaliTest[1361:2911286] server relay: connected (to port: 5001)
,2016-01-05 19:45:21.841 ThaliTest[1361:2912054] server session: not connected 1452019512061.980
,2016-01-05 19:45:21.972 ThaliTest[1361:2911286] multipeer session: reset timer
2016-01-05 19:45:21.973 ThaliTest[1361:2911286] multipeer session: stop timer
2016-01-05 19:45:21.973 ThaliTest[1361:2911286] multipeer session: start timer: 0x17fe5500
2016-,01-05 19:45:21.973 ThaliTest[1361:2911286] server: disconnecting to refresh session (1452019512061.980)
2016-01-05 19:45:21.973 ThaliTest[1361:2911286] server session: disconnect
2016-01-05 19:45:21.974 ThaliTest[1361:2911286] server session: stateChange:2->0 1452019512061.980
,2016-01-05 19:45:21.979 ThaliTest[1361:2911286] server session: connect
2016-01-05 19:45:21.979 ThaliTest[1361:2911286] server session: stateChange:0->1 1452019512061.980
,2016-01-05 19:45:21.989 ThaliTest[1361:2911286] server: accepting invitation 1452019512061.980
,2016-01-05 19:45:25.345 ThaliTest[1361:2912089] client session: connected
2016-01-05 19:45:25.345 ThaliTest[1361:2912089] client session: stateChange:1->2 1452019512061.980.ux/WWw==
,2016-01-05 19:45:25.388 ThaliTest[1361:2912054] client session: fireConnectCallback: 1452019512061.980.ux/WWw==
2016-01-05 19:45:25.388 ThaliTest[1361:2912054] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 Second connect should succeed
,2016-01-05 19:45:25.423 ThaliTest[1361:2911286] client: relay established
2016-01-05 19:45:25.423 ThaliTest[1361:2911286] client: new accepted socket: 0x1bb2c3c0
,2016-01-05 19:45:25.447 ThaliTest[1361:2912056] server session: connected
2016-01-05 19:45:25.447 ThaliTest[1361:2912056] server session: stateChange:1->2 1452019512061.980
,ok 97 the test messages should be equal
,2016-01-05 19:45:25.476 ThaliTest[1361:2911286] server relay: connected (to port: 5001)
,ok 98 Second send should succeed
,# setup
,2016-01-05 19:45:25.497 ThaliTest[1361:2911286] client: socket closed
,2016-01-05 19:45:25.498 ThaliTest[1361:2911286] client relay: socket disconnected
,2016-01-05 19:45:25.498 ThaliTest[1361:2911286] client relay: 0x1bb2c3c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-01-05 19:45:25.498 ThaliTest[1361:2911286] client session: socket closed: 1452019512061.980.ux/WWw==
2016-01-05 19:45:25.499 ThaliTest[1361:2911286] client session: onLinkFailure: 1452019512061.980.ux/WWw==
,2016-01-05 19:45:25.499 ThaliTest[1361:2911286] client session: disconnect
2016-01-05 19:45:25.499 ThaliTest[1361:2911286] client session: stateChange:2->0 1452019512061.980.ux/WWw==
,2016-01-05 19:45:25.508 ThaliTest[1361:2911286] client session: fireConnectionErrorEvent: 1452019512061.980.ux/WWw==
,2016-01-05 19:45:25.625 ThaliTest[1361:2912089] server session: not connected 1452019512061.980
,calling stopBroadcasting
,2016-01-05 19:45:25.896 ThaliTest[1361:2911521] jxcore: stopBroadcasting
,2016-01-05 19:45:25.896 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
2016-01-05 19:45:25.897 ThaliTest[1361:2911521] multipeer session: stop timer
2016-01-05 19:45:25.898 ThaliTest[1361:2911521] server session: disconnect
2016-01-05 19:45:25.898 ThaliTest[1361:2911521] server session: stateChange:2->0 1452019512061.980
,2016-01-05 19:45:25.908 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/25C7DBBA-7AE2-4A7E-8AE5-AB3C7B697C55/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2016-01-05 19:45:26.643 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:45:26.644 ThaliTest[1361:2911521] server: starting Cf4C7VaXbAFwZEZ3sGXUIg.dpdHpQ==
,2016-01-05 19:45:26.645 ThaliTest[1361:2911521] multipeer session: start timer: 0x1bb2f3a0
2016-01-05 19:45:26.645 ThaliTest[1361:2911521] THEMultipeerSession initialized peer Cf4C7VaXbAFwZEZ3sGXUIg
2016-01-05 19:45:26.645 ThaliTest[1361:2911521] jxcore: startBroadcasting: success
,ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
,ok 101 stopping event should occur in right order
About to call stopBroadcasting
,2016-01-05 19:45:26.648 ThaliTest[1361:2911521] jxcore: stopBroadcasting
2016-01-05 19:45:26.648 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
2016-01-05 19:45:26.648 ThaliTest[1361:2911521] multipeer session: stop timer
,2016-01-05 19:45:26.648 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,ok 102 stopped event should occur in right order
,mux server bridge listener closed
,# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/25C7DBBA-7AE2-4A7E-8AE5-AB3C7B697C55/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2016-01-05 19:45:27.553 ThaliTest[1361:2911521] jxcore: startBroadcasting
,2016-01-05 19:45:27.558 ThaliTest[1361:2911521] server: starting Cf4C7VaXbAFwZEZ3sGXUIg.xxBCXA==
,2016-01-05 19:45:27.558 ThaliTest[1361:2911521] multipeer session: start timer: 0x1bb33040
2016-01-05 19:45:27.559 ThaliTest[1361:2911521] THEMultipeerSession initialized peer Cf4C7VaXbAFwZEZ3sGXUIg
2016-01-05 19:45:27.559 ThaliTest[1361:2911521] jxcore:, startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
,ok 104 deviceName should not be null
Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
,2016-01-05 19:45:27.565 ThaliTest[1361:2911521] jxcore: stopBroadcasting
2016-01-05 19:45:27.566 ThaliTest[1361:2911521] THEMultipeerSession stopping peer
2016-01-05 19:45:27.566 ThaliTest[1361:2911521] multipeer session: stop timer
2016-01-05 19:45:27.566 ThaliTest[1361:2911521] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
