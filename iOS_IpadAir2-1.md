#### Test 55902202f27eba5_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55902202f27eba5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4789C149-D897-46B3-8B8D-EBA267CE7F92/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4789C149-D897-46B3-8B8D-EBA267CE7F92/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55902202f27eba5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55902202f27eba5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B2AF0343-2039-44B3-BE18-256DF5D3DA98/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55083"
,(lldb)     command script import "/tmp/4789C149-D897-46B3-8B8D-EBA267CE7F92/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-13 16:33:54.772 ThaliTest[1952:4125289] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/57117E68-209B-4B2F-A2CD-37FA1901CCE2/Library/Cookies/Cookies.binarycookies
,2016-01-13 16:33:54.999 ThaliTest[1952:4125289] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-13 16:33:55.000 ThaliTest[1952:4125289] Multi-tasking -> Device: YES, App: YES
,2016-01-13 16:33:55.006 ThaliTest[1952:4125289] Unlimited access to network resources
,2016-01-13 16:33:55.012 ThaliTest[1952:4125289] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-13 16:33:59.184 ThaliTest[1952:4125289] Resetting plugins due to page load.
,2016-01-13 16:34:00.666 ThaliTest[1952:4125289] Finished load of: file:///var/mobile/Containers/Bundle/Application/B2AF0343-2039-44B3-BE18-256DF5D3DA98/ThaliTest.app/www/index.html
,2016-01-13 16:34:00.793 ThaliTest[1952:4125289] JXcore Cordova plugin initializing
,2016-01-13 16:34:00.793 ThaliTest[1952:4125457] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-IpadAir2-1
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
ok 31 should be equal
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
ok 38 should be equal
,# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
ok 40 should be equal
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
,2016-01-13 16:40:37.966 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:40:37.971 ThaliTest[1952:4125457] server: starting 1452699637966.1952.vEIr7Q==
2016-01-13 16:40:37.971 ThaliTest[1952:4125457] multipeer session: start timer: 0x14d02ee0
2016-01-13 16:40:37.972 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699637966.1952
,2016-01-13 16:40:37.972 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2016-01-13 16:40:37.973 ThaliTest[1952:4125457] jxcore: stopBroadcasting
,2016-01-13 16:40:37.973 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:37.973 ThaliTest[1952:4125457] multipeer session: stop timer
,2016-01-13 16:40:37.975 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2016-01-13 16:40:37.976 ThaliTest[1952:4125457] jxcore: startBroadcasting
2016-01-13 16:40:37.977 ThaliTest[1952:4125457] server: starting 1452699637975.1952.TSuf4Q==
,2016-01-13 16:40:37.978 ThaliTest[1952:4125457] multipeer session: start timer: 0x16e92020
2016-01-13 16:40:37.978 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699637975.1952
2016-01-13 16:40:37.978 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-13 16:40:37.979 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:40:37.979 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:37.979 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:40:37.979 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-13 16:40:37.980 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:40:37.983 ThaliTest[1952:4125457] server: starting 1452699637980.1952.6YSVtw==
2016-01-13 16:40:37.983 ThaliTest[1952:4125457] multipeer session: start timer: 0x18052a80
2016-01-13 16:40:37.983 ThaliTest[1952:4125457] THEMultipeerSession in,itialized peer 1452699637980.1952
2016-01-13 16:40:37.983 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-13 16:40:37.984 ThaliTest[1952:4125457] jxcore: stopBroadcasting
,2016-01-13 16:40:37.984 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:37.985 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:40:37.985 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-13 16:40:37.986 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:40:37.987 ThaliTest[1952:4125457] server: starting 1452699637985.1952./D+aAg==
2016-01-13 16:40:37.987 ThaliTest[1952:4125457] multipeer session: start timer: 0x180593f0
2016-01-13 16:40:37.987 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699637985.1952
2016-01-13 16:40:37.988 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-13 16:40:37.988 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:40:37.988 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:37.988 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:40:37.989 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 52 Should, be able to call stopBroadcasting without error
2016-01-13 16:40:37.989 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:40:37.990 ThaliTest[1952:4125457] server: starting 1452699637989.1952.TSxeQA==
2016-01-13 16:40:37.991 ThaliTest[1952:4125457] multipeer session: start timer: 0x16b43f30
2016-01-13 16:40:37.991 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699637989.1952
2016-01-13 16:40:37.991 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-13 16:40:37.991 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2,016-01-13 16:40:37.991 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
,2016-01-13 16:40:37.992 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:40:37.993 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
2016-01-13 16:40:37.994 ThaliTest[1952:4125457] jxcore: startBroadcasting
2016-01-13 16:40:37.996 ThaliTest[1952:4125457] server: starting 1452699637994.1952.1tWARw==
2016-01-13 16:40:37.996 ThaliTest[1952:4125457] multipeer session: start timer: 0x16c6a5c0
2016-01-13 16:40:37.996 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699637994.1952
2016-01-13 16:40:37.996 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-13 16:40:37.997 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:40:37.997 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:37.997 ThaliTest[1952:4125457] multipeer session: stop timer
,2016-01-13 16:40:37.999 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
2016-01-13 16:40:38.000 ThaliTest[1952:4125457] jxcore: startBroadcasting
2016-01-13 16:40:38.001 ThaliTest[195,2:4125457] server: starting 1452699638000.1952.RBKhTg==
2016-01-13 16:40:38.001 ThaliTest[1952:4125457] multipeer session: start timer: 0x16d1cdd0
,2016-01-13 16:40:38.001 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699638000.1952
2016-01-13 16:40:38.002 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2016-,01-13 16:40:38.002 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:40:38.002 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:38.002 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:40:38.003 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2016-01-13 16:40:38.003 ThaliTest[1952:4125457] jxcore: startBroadcasting
2016-01-13 16:40:38.004 ThaliTest[1952:4125457] server: starti,ng 1452699638003.1952.kGfNpg==
2016-01-13 16:40:38.004 ThaliTest[1952:4125457] multipeer session: start timer: 0x16f5c100
2016-01-13 16:40:38.004 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699638003.1952
2016-01-13 16:40:38.004 Tha,liTest[1952:4125457] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
2016-01-13 16:40:38.007 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:40:38.007 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:38.007 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:40:38.007 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
,2016-01-13 16:40:38.008 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:40:38.010 ThaliTest[1952:4125457] server: starting 1452699638008.1952.FaYjyg==
2016-01-13 16:40:38.011 ThaliTest[1952:4125457] multipeer session: start timer: 0x16fa0560
,2016-01-13 16:40:38.012 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699638008.1952
,2016-01-13 16:40:38.014 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-13 16:40:38.016 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:40:38.016 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:38.016 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:40:38.016 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 62 Should be able to call stopBroadcasting without error
2016-01-13 16:40:38.016 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:40:38.018 ThaliTest[1952:4125457] server: starting 1452699638016.1952.K/YpEg==
,2016-01-13 16:40:38.019 ThaliTest[1952:4125457] multipeer session: start timer: 0x16cb75c0
2016-01-13 16:40:38.019 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699638016.1952
2016-01-13 16:40:38.019 ThaliTest[1952:4125457] jxcore: sta,rtBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
2016-01-13 16:40:38.020 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:40:38.020 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:38.020 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:40:38.020 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-13 16:40:41.108 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:40:41.109 ThaliTest[1952:4125457] server: starting 1452699641107.1952.5pZsow==
2016-01-13 16:40:41.109 ThaliTest[1952:4125457] multipeer session: start timer: 0x16b9d370
2016-01-13 16:40:41.109 ThaliTest[1952:4125457] THEMultipeerSession in,itialized peer 1452699641107.1952
2016-01-13 16:40:41.109 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-13 16:40:41.110 ThaliTest[1952:4125457] jxcore: startBroadcasting
2016-01-13 16:40:41.110 ThaliTest[1952:4125457] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2016-01-13 16:40:41.112 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:40:41.112 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:41.112 ThaliTest[1952:4125457] multipeer session: stop timer
,2016-01-13 16:40:41.112 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-13 16:40:45.953 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:40:45.954 ThaliTest[1952:4125457] server: starting 1452699645953.1952.nTN0qQ==
2016-01-13 16:40:45.955 ThaliTest[1952:4125457] multipeer session: start timer: 0x16bb2140
2016-01-13 16:40:45.955 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699645953.1952
2016-01-13 16:40:45.955 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
,2016-01-13 16:40:45.956 ThaliTest[1952:4125457] jxcore: connect foobar
2016-01-13 16:40:45.956 ThaliTest[1952:4125457] client: unknown peer foobar
2016-01-13 16:40:45.956 ThaliTest[1952:4125457] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-13 16:40:45.957 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:40:45.957 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:40:45.957 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:40:45.957 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-13 16:40:48.718 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:40:48.719 ThaliTest[1952:4125457] server: starting 1452699648718.1952.aU1K2w==
2016-01-13 16:40:48.720 ThaliTest[1952:4125457] multipeer session: start timer: 0x14f1bc90
2016-01-13 16:40:48.720 ThaliTest[1952:4125457] THEMultipeerSession in,itialized peer 1452699648718.1952
2016-01-13 16:40:48.720 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-13 16:40:48.720 ThaliTest[1952:4125457] jxcore: disconnect
2016-01-13 16:40:48.720 ThaliTest[1952:4125457] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2016-01-13 16:40:48.721 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:40:48.721 ThaliTest[1952:4125457] THEMultipeerS,ession stopping peer
2016-01-13 16:40:48.721 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:40:48.722 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-13 16:40:52.928 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:40:52.929 ThaliTest[1952:4125457] server: starting 1452699652928.1952.Evgw/g==
2016-01-13 16:40:52.930 ThaliTest[1952:4125457] multipeer session: start timer: 0x16dba3a0
2016-01-13 16:40:52.930 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699652928.1952
2016-01-13 16:40:52.930 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2016-01-13 16:40:54.125 ThaliTest[1952:4125289] client: found peer: 1452699651463.1878.xtBYyw==
,2016-01-13 16:40:54.126 ThaliTest[1952:4125457] jxcore: connect 1452699651463.1878.xtBYyw==
2016-01-13 16:40:54.126 ThaliTest[1952:4125457] client session: connect
2016-01-13 16:40:54.126 ThaliTest[1952:4125457] client session: stateChange:0->1 1452699651463.1878.xtBYyw==
,2016-01-13 16:40:55.260 ThaliTest[1952:4125289] multipeer session: reset timer
2016-01-13 16:40:55.260 ThaliTest[1952:4125289] multipeer session: stop timer
2016-01-13 16:40:55.260 ThaliTest[1952:4125289] multipeer session: start timer: 0x16dba3a0
2016-01-13 16:40:55.261 ThaliTest[1952:4125289] server session: connect
,2016-01-13 16:40:55.261 ThaliTest[1952:4125289] server session: stateChange:0->1 1452699651463.1878
,2016-01-13 16:40:55.263 ThaliTest[1952:4125289] server: accepting invitation 1452699651463.1878
,2016-01-13 16:40:58.671 ThaliTest[1952:4126227] client session: connected
2016-01-13 16:40:58.672 ThaliTest[1952:4126227] client session: stateChange:1->2 1452699651463.1878.xtBYyw==
,2016-01-13 16:40:58.696 ThaliTest[1952:4126213] client session: fireConnectCallback: 1452699651463.1878.xtBYyw==
2016-01-13 16:40:58.696 ThaliTest[1952:4126213] jxcore: connect: success
ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-13 16:40:58.698 ThaliTest[1952:4125457] jxcore: disconnect
2016-01-13 16:40:58.698 ThaliTest[1952:4125457] client session: disconnectFromPeer: 1452699651463.1878.xtBYyw==
2016-01-13 16:40:58.698 ThaliTest[1952:4125457] client session: disconnect
2016-01-13 16:40:58.698 ThaliTest[1952:4125457] client session: stateChange:2->0 1452699651463.1878.xtBYyw==
,2016-01-13 16:40:58.760 ThaliTest[1952:4125457] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-13 16:40:58.993 ThaliTest[1952:4126224] server session: connected
2016-01-13 16:40:58.993 ThaliTest[1952:4126224] server session: stateChange:1->2 1452699651463.1878
,2016-01-13 16:40:59.003 ThaliTest[1952:4125289] server relay: socket disconnected
2016-01-13 16:40:59.004 ThaliTest[1952:4125289] server relay: 0x14d1b620 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 16:40:59.025 ThaliTest[1952:4126227] server session: not connected 1452699651463.1878
,calling stopBroadcasting
,2016-01-13 16:41:00.105 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:41:00.105 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:41:00.106 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:41:00.106 ThaliTest[1952:4125457] server session: disconnect
2016-01-13 16:41:00.106 ThaliTest[1952:4125457] server session: stateChange:2->0 1452699651463.1878
,2016-01-13 16:41:00.107 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-13 16:41:02.261 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:41:02.262 ThaliTest[1952:4125457] server: starting 1452699662261.1952.lqAjwg==
2016-01-13 16:41:02.263 ThaliTest[1952:4125457] multipeer session: start timer: 0x16f4d430
2016-01-13 16:41:02.263 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699662261.1952
2016-01-13 16:41:02.263 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-13 16:41:03.379 ThaliTest[1952:4125289] client: found peer: 1452699661014.1878.m1Wf4Q==
,2016-01-13 16:41:03.379 ThaliTest[1952:4125457] jxcore: connect 1452699661014.1878.m1Wf4Q==
2016-01-13 16:41:03.380 ThaliTest[1952:4125457] client session: connect
2016-01-13 16:41:03.380 ThaliTest[1952:4125457] client session: stateChange:0->1 145269966,1014.1878.m1Wf4Q==
,2016-01-13 16:41:03.460 ThaliTest[1952:4125289] multipeer session: reset timer
2016-01-13 16:41:03.461 ThaliTest[1952:4125289] multipeer session: stop timer
2016-01-13 16:41:03.461 ThaliTest[1952:4125289] multipeer session: start timer: 0x16f4d430
2016-01-13 16:41:03.461 ThaliTest[1952:4125289] server session: connect
2016-01-13 16:41:03.461 ThaliTest[1952:4125289] server session: stateChange:0->1 1452699661014.1878
,2016-01-13 16:41:03.463 ThaliTest[1952:4125289] server: accepting invitation 1452699661014.1878
,2016-01-13 16:41:07.253 ThaliTest[1952:4126213] client session: connected
2016-01-13 16:41:07.254 ThaliTest[1952:4126213] client session: stateChange:1->2 1452699661014.1878.m1Wf4Q==
,2016-01-13 16:41:07.257 ThaliTest[1952:4126284] client session: fireConnectCallback: 1452699661014.1878.m1Wf4Q==
2016-01-13 16:41:07.258 ThaliTest[1952:4126284] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
2016-01-13 16:41:07.259 ThaliTest[1952:4125457] jxcore: connect 1452699661014.1878.m1Wf4Q==
2016-01-13 16:41:07.259 ThaliTest[1952:4125457] client: already connect(ing/ed) to 1452699661014.1878.m1Wf4Q==
2016-01-13 16:41:07.259 ThaliTest[1952:4125457] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-13 16:41:07.258 ThaliTest[1952:4126213] server session: connected
2016-01-13 16:41:07.260 ThaliTest[1952:4126213] server session: stateChange:1->2 1452699661014.1878
,2016-01-13 16:41:07.261 ThaliTest[1952:4125457] jxcore: disconnect
2016-01-13 16:41:07.261 ThaliTest[1952:4125457] client session: disconnectFromPeer: 1452699661014.1878.m1Wf4Q==
2016-01-13 16:41:07.261 ThaliTest[1952:4125457] client session: disconnect
2016-01-13 16:41:07.261 ThaliTest[1952:4125457] client session: stateChange:2->0 1452699661014.1878.m1Wf4Q==
,2016-01-13 16:41:07.264 ThaliTest[1952:4125289] server relay: socket disconnected
2016-01-13 16:41:07.265 ThaliTest[1952:4125289] server relay: 0x16ea12e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 16:41:07.322 ThaliTest[1952:4125457] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2016-01-13 16:41:07.363 ThaliTest[1952:4126285] server session: not connected 1452699661014.1878
,calling stopBroadcasting
,2016-01-13 16:41:07.447 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:41:07.447 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:41:07.447 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:41:07.447 ThaliTest[1952:4125457] server session: disconnect
2016-01-13 16:41:07.447 ThaliTest[1952:4125457] server session: stateChange:2->0 1452699661014.1878
,2016-01-13 16:41:07.723 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-13 16:41:09.369 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:41:09.370 ThaliTest[1952:4125457] server: starting 1452699669369.1952.brRIHQ==
2016-01-13 16:41:09.370 ThaliTest[1952:4125457] multipeer session: start timer: 0x16dd30a0
2016-01-13 16:41:09.371 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699669369.1952
2016-01-13 16:41:09.371 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-13 16:41:10.844 ThaliTest[1952:4125289] client: found peer: 1452699668119.1878.SPfBqA==
2016-01-13 16:41:10.844 ThaliTest[1952:4125457] jxcore: connect 1452699668119.1878.SPfBqA==
,2016-01-13 16:41:10.844 ThaliTest[1952:4125457] client session: connect
2016-01-13 16:41:10.845 ThaliTest[1952:4125457] client session: stateChange:0->1 1452699668119.1878.SPfBqA==
,2016-01-13 16:41:10.860 ThaliTest[1952:4125289] multipeer session: reset timer
,2016-01-13 16:41:10.860 ThaliTest[1952:4125289] multipeer session: stop timer
2016-01-13 16:41:10.860 ThaliTest[1952:4125289] multipeer session: start timer: 0x16dd30a0
2016-01-13 16:41:10.860 ThaliTest[1952:4125289] server session: connect
2016-01-13 16:41:10.860 ThaliTest[1952:4125289] server session: stateChange:0->1 1452699668119.1878
,2016-01-13 16:41:10.863 ThaliTest[1952:4125289] server: accepting invitation 1452699668119.1878
,2016-01-13 16:41:14.466 ThaliTest[1952:4126227] server session: connected
2016-01-13 16:41:14.466 ThaliTest[1952:4126227] server session: stateChange:1->2 1452699668119.1878
2016-01-13 16:41:14.467 ThaliTest[1952:4125289] server relay: socket disconnected
,2016-01-13 16:41:14.468 ThaliTest[1952:4125289] server relay: 0x14e07dd0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-01-13 16:41:14.918 ThaliTest[1952:4126284] client session: connected
2016-01-13 16:41:14.918 ThaliTest[1952:4126284] client session: stateChange:1->2 1452699668119.1878.SPfBqA==
2016-01-13 16:41:14.919 ThaliTest[1952:4126284] client session: fireCon,nectCallback: 1452699668119.1878.SPfBqA==
2016-01-13 16:41:14.919 ThaliTest[1952:4126284] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
,2016-01-13 16:41:14.920 ThaliTest[1952:4125457] jxcore: disconnect
2016-01-13 16:41:14.920 ThaliTest[1952:4125457] client session: disconnectFromPeer: 1452699668119.1878.SPfBqA==
2016-01-13 16:41:14.920 ThaliTest[1952:4125457] client session: disconnect,
2016-01-13 16:41:14.920 ThaliTest[1952:4125457] client session: stateChange:2->0 1452699668119.1878.SPfBqA==
,2016-01-13 16:41:14.982 ThaliTest[1952:4125457] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
,2016-01-13 16:41:14.983 ThaliTest[1952:4125457] jxcore: disconnect
2016-01-13 16:41:14.983 ThaliTest[1952:4125457] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-13 16:41:15.273 ThaliTest[1952:4126284] server session: not connected 1452699668119.1878
,calling stopBroadcasting
,2016-01-13 16:41:15.317 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:41:15.317 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:41:15.317 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:41:15.317 ThaliTest[1952:4125457] server session: disconnect
2016-01-13 16:41:15.317 ThaliTest[1952:4125457] server session: stateChange:2->0 1452699668119.1878
,2016-01-13 16:41:15.319 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,2016-01-13 16:41:16.868 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:41:16.870 ThaliTest[1952:4125457] server: starting 1452699676868.1952.Alnprw==
2016-01-13 16:41:16.870 ThaliTest[1952:4125457] multipeer session: start timer: 0x16fcd9e0
2016-01-13 16:41:16.870 ThaliTest[1952:4125457] THEMultipeerSession in,itialized peer 1452699676868.1952
2016-01-13 16:41:16.870 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-13 16:41:18.594 ThaliTest[1952:4125289] client: found peer: 1452699675723.1878.N5o+8Q==
,2016-01-13 16:41:18.594 ThaliTest[1952:4125457] jxcore: connect 1452699675723.1878.N5o+8Q==
2016-01-13 16:41:18.594 ThaliTest[1952:4125457] client session: connect
2016-01-13 16:41:18.594 ThaliTest[1952:4125457] client session: stateChange:0->1 1452699675723.1878.N5o+8Q==
,2016-01-13 16:41:18.721 ThaliTest[1952:4125289] multipeer session: reset timer
2016-01-13 16:41:18.721 ThaliTest[1952:4125289] multipeer session: stop timer
2016-01-13 16:41:18.721 ThaliTest[1952:4125289] multipeer session: start timer: 0x16fcd9e0
2016-01-13 16:41:18.721 ThaliTest[1952:4125289] server session: connect
2016-01-13 16:41:18.722 ThaliTest[1952:4125289] server session: stateChange:0->1 1452699675723.1878
,2016-01-13 16:41:18.724 ThaliTest[1952:4125289] server: accepting invitation 1452699675723.1878
,2016-01-13 16:41:22.630 ThaliTest[1952:4126227] server session: connected
,2016-01-13 16:41:22.631 ThaliTest[1952:4126227] server session: stateChange:1->2 1452699675723.1878
,2016-01-13 16:41:22.633 ThaliTest[1952:4125289] server relay: connected (to port: 5001)
,2016-01-13 16:41:22.648 ThaliTest[1952:4126285] client session: connected
2016-01-13 16:41:22.648 ThaliTest[1952:4126285] client session: stateChange:1->2 1452699675723.1878.N5o+8Q==
,2016-01-13 16:41:22.684 ThaliTest[1952:4126213] client session: fireConnectCallback: 1452699675723.1878.N5o+8Q==
2016-01-13 16:41:22.684 ThaliTest[1952:4126213] jxcore: connect: success
,ok 89 Should be able to connect without error
ok 90 Port should be within range
,2016-01-13 16:41:22.687 ThaliTest[1952:4125289] client: relay established
2016-01-13 16:41:22.687 ThaliTest[1952:4125289] client: new accepted socket: 0x16fe7f00
,data in 1095
,data in 8760
,data in 9855
,data in 22924
,data in 45990
,data in 49275
,data in 55845
,data in 70080
,data in 71175
,data in 99503
,data in 116070
,data in 131072
,ok 91 the test messages should be equal
,2016-01-13 16:41:23.412 ThaliTest[1952:4125457] jxcore: disconnect
2016-01-13 16:41:23.413 ThaliTest[1952:4125457] client session: disconnectFromPeer: 1452699675723.1878.N5o+8Q==
2016-01-13 16:41:23.413 ThaliTest[1952:4125457] client session: disconnect
2016-01-13 16:41:23.413 ThaliTest[1952:4125457] client session: stateChange:2->0 1452699675723.1878.N5o+8Q==
,2016-01-13 16:41:23.417 ThaliTest[1952:4125457] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-13 16:41:23.428 ThaliTest[1952:4126227] server session: not connected 1452699675723.1878
,calling stopBroadcasting
,2016-01-13 16:41:23.703 ThaliTest[1952:4125457] jxcore: stopBroadcasting
2016-01-13 16:41:23.703 ThaliTest[1952:4125457] THEMultipeerSession stopping peer
2016-01-13 16:41:23.703 ThaliTest[1952:4125457] multipeer session: stop timer
2016-01-13 16:41:23.703 ThaliTest[1952:4125457] server session: disconnect
2016-01-13 16:41:23.704 ThaliTest[1952:4125457] server session: stateChange:2->0 1452699675723.1878
,2016-01-13 16:41:23.705 ThaliTest[1952:4125457] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-13 16:41:25.356 ThaliTest[1952:4125457] jxcore: startBroadcasting
,2016-01-13 16:41:25.357 ThaliTest[1952:4125457] server: starting 1452699685356.1952.wdtcsw==
2016-01-13 16:41:25.357 ThaliTest[1952:4125457] multipeer session: start timer: 0x16c368b0
2016-01-13 16:41:25.357 ThaliTest[1952:4125457] THEMultipeerSession initialized peer 1452699685356.1952
2016-01-13 16:41:25.357 ThaliTest[1952:4125457] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
echo server started
,2016-01-13 16:41:26.447 ThaliTest[1952:4125289] client: found peer: 1452699684127.1878.EUikBA==
[{"peerIdentifier":"1452699684127.1878.EUikBA==","peerName":"(null)","peerAvailable":true}]
2016-01-13 16:41:26.447 ThaliTest[1952:4125457] jxcore: connect 1452699684127.1878.EUikBA==
2016-01-13 16:41:26.448 ThaliTest[1952:4125457] client session: connect
2016-01-13 16:41:26.448 ThaliTest[1952:4125457] client session: stateChange:0->1 1452699684127.1878.EUikBA==
,2016-01-13 16:41:26.782 ThaliTest[1952:4125289] multipeer session: reset timer
2016-01-13 16:41:26.782 ThaliTest[1952:4125289] multipeer session: stop timer
2016-01-13 16:41:26.782 ThaliTest[1952:4125289] multipeer session: start timer: 0x16c368b0
2016-01-13 16:41:26.782 ThaliTest[1952:4125289] server session: connect
2016-01-13 16:41:26.782 ThaliTest[1952:4125289] server session: stateChange:0->1 1452699684127.1878
,2016-01-13 16:41:26.786 ThaliTest[1952:4125289] server: accepting invitation 1452699684127.1878
,2016-01-13 16:41:30.441 ThaliTest[1952:4126213] client session: connected
2016-01-13 16:41:30.441 ThaliTest[1952:4126213] client session: stateChange:1->2 1452699684127.1878.EUikBA==
,2016-01-13 16:41:30.449 ThaliTest[1952:4126213] client session: fireConnectCallback: 1452699684127.1878.EUikBA==
2016-01-13 16:41:30.449 ThaliTest[1952:4126213] jxcore: connect: success
ok 94 Should be able to connect without error
ok 95 Port should be within range
,ok 96 First connect should succeed
,2016-01-13 16:41:30.460 ThaliTest[1952:4125289] client: relay established
2016-01-13 16:41:30.460 ThaliTest[1952:4125289] client: new accepted socket: 0x16b43d40
,ok 97 the test messages should be equal
,ok 98 First send should succeed
,2016-01-13 16:41:30.524 ThaliTest[1952:4125289] client: socket closed
2016-01-13 16:41:30.524 ThaliTest[1952:4125289] client relay: socket disconnected
2016-01-13 16:41:30.524 ThaliTest[1952:4125289] client relay: 0x16b43d40 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-01-13 16:41:30.524 ThaliTest[1952:4125289] client session: socket closed: 1452699684127.1878.EUikBA==
2016-01-13 ,16:41:30.524 ThaliTest[1952:4125289] client session: onLinkFailure: 1452699684127.1878.EUikBA==
2016-01-13 16:41:30.525 ThaliTest[1952:4125289] client session: disconnect
2016-01-13 16:41:30.525 ThaliTest[1952:4125289] client session: stateChange:2->0 1452699684127.1878.EUikBA==
,2016-01-13 16:41:30.529 ThaliTest[1952:4125289] client session: fireConnectionErrorEvent: 1452699684127.1878.EUikBA==
,2016-01-13 16:41:30.530 ThaliTest[1952:4125457] jxcore: connect 1452699684127.1878.EUikBA==
2016-01-13 16:41:30.531 ThaliTest[1952:4125457] client session: connect
2016-01-13 16:41:30.531 ThaliTest[1952:4125457] client session: stateChange:0->1 1452699684127.1878.EUikBA==
,2016-01-13 16:41:30.552 ThaliTest[1952:4126224] server session: connected
,2016-01-13 16:41:30.552 ThaliTest[1952:4126224] server session: stateChange:1->2 1452699684127.1878
,2016-01-13 16:41:30.574 ThaliTest[1952:4125289] server relay: connected (to port: 5001)
,2016-01-13 16:41:30.694 ThaliTest[1952:4126284] server session: not connected 1452699684127.1878
,2016-01-13 16:41:35.547 ThaliTest[1952:4125289] client: lost peer: 1452699684127.1878.EUikBA==
2016-01-13 16:41:35.547 ThaliTest[1952:4125289] client session: onPeerLost: 1452699684127.1878.EUikBA==
2016-01-13 16:41:35.547 ThaliTest[1952:4125289] client session: onLinkFailure: 1452699684127.1878.EUikBA==
2016-01-13 16:41:35.547 ThaliTest[1952:4125289] client session: disconnect
2016-01-13 16:41:35.547 ThaliTest[1952:4125289] client session: stateChange:1->0 1452699684127.1878.EUikBA==
,2016-01-13 16:41:35.550 ThaliTest[1952:4125289] client session: fireConnectCallback: 1452699684127.1878.EUikBA==
2016-01-13 16:41:35.550 ThaliTest[1952:4125289] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1452699684127.1878.EUikBA==","peerName":"(null)","peerAvailable":false}]
,2016-01-13 16:41:36.559 ThaliTest[1952:4125457] jxcore: connect 1452699684127.1878.EUikBA==
2016-01-13 16:41:36.559 ThaliTest[1952:4125457] client: connect: unreachable 1452699684127.1878.EUikBA==
2016-01-13 16:41:36.560 ThaliTest[1952:4125457] jxcore: connect: fail: Peer unreachable
,2016-01-13 16:41:56.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:42:26.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:42:56.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:43:26.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:43:56.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:44:26.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:44:56.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:45:26.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:45:56.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:46:26.782 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:46:56.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:47:26.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:47:56.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:48:26.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:48:56.783 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:49:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:49:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:50:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:50:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:51:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:51:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:52:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:52:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:53:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:53:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:54:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:54:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:55:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:55:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:56:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:56:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:57:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:57:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:58:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:58:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:59:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 16:59:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 17:00:26.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 17:00:56.767 ThaliTest[1952:4125289] multipeer session: restart
,2016-01-13 17:01:26.767 ThaliTest[1952:4125289] multipeer session: restart

```
