#### Test 506502785032ad1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/442CAA9B-C743-44E4-AC02-F18D44D50199/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/442CAA9B-C743-44E4-AC02-F18D44D50199/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50468"
,(lldb)     command script import "/tmp/442CAA9B-C743-44E4-AC02-F18D44D50199/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 03:55:06.058 ThaliTest[405:210658] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9DBFF5DA-6F0D-45DA-8EE3-E767159CB391/Library/Cookies/Cookies.binarycookies
,2015-12-08 03:55:06.072 ThaliTest[405:210658] <CATransformLayer: 0x14f60670> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-08 03:55:06.073 ThaliTest[405:210658] <CATransformLayer: 0x14f68470> - changing property ma,sksToBounds in transform-only layer, will have no effect
2015-12-08 03:55:06.073 ThaliTest[405:210658] <CATransformLayer: 0x14f695b0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-08 03:55:06.362 ThaliTest[405:210658] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 03:55:06.363 ThaliTest[405:210658] Multi-tasking -> Device: YES, App: YES
,2015-12-08 03:55:06.370 ThaliTest[405:210658] Unlimited access to network resources
,2015-12-08 03:55:06.376 ThaliTest[405:210658] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 03:55:14.900 ThaliTest[405:210658] Resetting plugins due to page load.
,2015-12-08 03:55:18.131 ThaliTest[405:210658] Finished load of: file:///var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/index.html
,2015-12-08 03:55:18.269 ThaliTest[405:210658] JXcore Cordova plugin initializing
,2015-12-08 03:55:18.269 ThaliTest[405:210918] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
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
,2015-12-08 03:56:45.195 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:45.453 ThaliTest[405:210918] server: starting 1449543405194.405.IHSFgw==
,2015-12-08 03:56:45.455 ThaliTest[405:210918] multipeer session: start timer: 0x18a4d700
,2015-12-08 03:56:45.456 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543405194.405
,2015-12-08 03:56:45.457 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-08 03:56:45.465 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:45.466 ThaliTest[405:210918] THEMultipeerSession stopping peer
2015-12-08 03:56:45.466 ThaliTest[405:210918] multipeer session: stop timer
2015-12-08 03:56:45.467 ThaliTest[405:210918] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:45.469 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:45.472 ThaliTest[405:210918] server: starting 1449543405469.405.MsAS9g==
,2015-12-08 03:56:45.473 ThaliTest[405:210918] multipeer session: start timer: 0x18982410
2015-12-08 03:56:45.473 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543405469.405
,2015-12-08 03:56:45.473 ThaliTest[405:210918] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-08 03:56:45.475 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:45.476 ThaliTest[405:210918] THEMultipeerSession stopping peer
2015-12-08 03:56:45.476 ThaliTest[405:210918] multipeer session: stop timer
2015-12-08 03:56:45.476 ThaliTest[405:210918] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2015-12-08 03:56:45.478 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:45.481 ThaliTest[405:210918] server: starting 1449543405477.405.QDnOUQ==
2015-12-08 03:56:45.481 ThaliTest[405:210918] multipeer session: start timer: 0x189838b0
,2015-12-08 03:56:45.482 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543405477.405
2015-12-08 03:56:45.482 ThaliTest[405:210918] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2015-12-08 03:56:45.483 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:45.484 ThaliTest[405:210918] THEMultipeerSession stopping peer
2015-12-08 03:56:45.484 ThaliTest[405:210918] multipeer session: stop timer
2015-12-08 03:56:45.484 ThaliTest[405:210918] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
2015-12-08 03:56:45.486 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:45.488 ThaliTest[405:210918] server: starting 1449543405485.405.1cugkQ==
2015-12-08 03:56:45.488 ThaliTest[405:210918] multipeer session: start timer: 0x16fdc370
2015-12-08 03:56:45.488 ThaliTest[405:210918] THEMultipeerSession initializ,ed peer 1449543405485.405
2015-12-08 03:56:45.488 ThaliTest[405:210918] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-08 03:56:45.490 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:45.490 ThaliTest[405:210918] THEMultipeerSession stopping peer
,2015-12-08 03:56:45.490 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:56:45.491 ThaliTest[405:210918] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2015-12-08 03:56:45.493 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:45.496 ThaliTest[405:210918] server: starting 1449543405493.405.Y56JKA==
,2015-12-08 03:56:45.496 ThaliTest[405:210918] multipeer session: start timer: 0x18982cd0
,2015-12-08 03:56:45.497 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543405493.405
,2015-12-08 03:56:45.497 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-08 03:56:45.498 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:45.498 ThaliTest[405:210918] THEMultipeerSession stopping peer
,2015-12-08 03:56:45.498 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:56:45.498 ThaliTest[405:210918] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
2015-12-08 03:56:45.500 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:45.502 ThaliTest[405:210918] server: starting 1449543405500.405.IcNFlw==
,2015-12-08 03:56:45.503 ThaliTest[405:210918] multipeer session: start timer: 0x18a508d0
2015-12-08 03:56:45.505 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543405500.405
2015-12-08 03:56:45.505 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-08 03:56:45.506 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:45.506 ThaliTest[405:210918] THEMultipeerSession stopping peer
,2015-12-08 03:56:45.506 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:56:45.507 ThaliTest[405:210918] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:45.508 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:45.509 ThaliTest[405:210918] server: starting 1449543405507.405.SKd6tw==
,2015-12-08 03:56:45.509 ThaliTest[405:210918] multipeer session: start timer: 0x16dbf060
2015-12-08 03:56:45.510 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543405507.405
2015-12-08 03:56:45.510 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
2015-12-08 03:56:45.511 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:45.511 ThaliTest[405:210918] THEMultipeerSession stopping peer
2015-12-08 03:56:45.511 ThaliTest[405:210,918] multipeer session: stop timer
2015-12-08 03:56:45.511 ThaliTest[405:210918] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2015-12-08 03:56:45.512 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:45.515 ThaliTest[405:210918] server: starting 1449543405512.405.izB0Cg==
2015-12-08 03:56:45.515 ThaliTest[405:210918] multipeer session: start timer: 0x18984f10
2015-12-08 03:56:45.515 ThaliTest[405:210918] THEMultipeerSession initializ,ed peer 1449543405512.405
2015-12-08 03:56:45.516 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
2015-12-08 03:56:45.517 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:45.517 ThaliTest[405:210918] THEMultipeerSession stopping peer
2015-12-08 03:56:45.517 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:56:45.517 ThaliTest[405:210918] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
2015-12-08 03:56:45.518 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:45.519 ThaliTest[405:210918] server: starting 1449543405518.405.7phb8Q==
,2015-12-08 03:56:45.519 ThaliTest[405:210918] multipeer session: start timer: 0x18a52770
2015-12-08 03:56:45.519 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543405518.405
2015-12-08 03:56:45.519 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-08 03:56:45.520 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:45.520 ThaliTest[405:210918] THEMultipeerSession stopping peer
,2015-12-08 03:56:45.521 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:56:45.521 ThaliTest[405:210918] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:45.522 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:45.523 ThaliTest[405:210918] server: starting 1449543405522.405.F2D0ig==
,2015-12-08 03:56:45.524 ThaliTest[405:210918] multipeer session: start timer: 0x18a51ed0
,2015-12-08 03:56:45.524 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543405522.405
,2015-12-08 03:56:45.524 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
2015-12-08 03:56:45.525 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:45.525 ThaliTest[405:210918] THEMultipeerSession stopping peer
2015-12-08 03:56:45.525 ThaliTest[405:210918] multipeer session: stop timer
2015-12-08 03:56:45.525 ThaliTest[405:210918] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-08 03:56:47.090 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:47.093 ThaliTest[405:210918] server: starting 1449543407090.405.GTtZtg==
,2015-12-08 03:56:47.094 ThaliTest[405:210918] multipeer session: start timer: 0x18a53740
2015-12-08 03:56:47.095 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543407090.405
2015-12-08 03:56:47.095 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
2015-12-08 03:56:47.099 ThaliTest[405:210918] jxcore: startBroadcasting
2015-12-08 03:56:47.099 ThaliTest[405:210918] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2015-12-08 03:56:47.102 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:47.102 ThaliTest[405:210918] THEMultipeerSession stopping peer
2015-12-08 03:56:47.103 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:56:47.104 ThaliTest[405:210918] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-08 03:56:53.669 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:53.673 ThaliTest[405:210918] server: starting 1449543413669.405.3WwVtw==
,2015-12-08 03:56:53.673 ThaliTest[405:210918] multipeer session: start timer: 0x18a56630
2015-12-08 03:56:53.674 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543413669.405
2015-12-08 03:56:53.674 ThaliTest[405:210918] jxcore: startBroad,casting: success
ok 68 Should be able to call startBroadcasting without error
,2015-12-08 03:56:53.678 ThaliTest[405:210918] jxcore: connect foobar
2015-12-08 03:56:53.679 ThaliTest[405:210918] client: unknown peer foobar
2015-12-08 03:56:53.679 ThaliTest[405:210918] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to ,a bad peer
,2015-12-08 03:56:53.683 ThaliTest[405:210918] jxcore: stopBroadcasting
2015-12-08 03:56:53.685 ThaliTest[405:210918] THEMultipeerSession stopping peer
2015-12-08 03:56:53.685 ThaliTest[405:210918] multipeer session: stop timer
2015-12-08 03:56:53.686 ThaliTest[405:210918] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-08 03:56:57.959 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:56:57.963 ThaliTest[405:210918] server: starting 1449543417959.405.NZBwyQ==
,2015-12-08 03:56:57.964 ThaliTest[405:210918] multipeer session: start timer: 0x18a57fa0
,2015-12-08 03:56:57.965 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543417959.405
,2015-12-08 03:56:57.965 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
2015-12-08 03:56:57.970 ThaliTest[405:210918] jxcore: disconnect
,2015-12-08 03:56:57.973 ThaliTest[405:210918] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2015-12-08 03:56:57.978 ThaliTest[405:210918] jxcore: stopBroadcasting
,2015-12-08 03:56:57.980 ThaliTest[405:210918] THEMultipeerSession stopping peer
,2015-12-08 03:56:57.981 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:56:57.983 ThaliTest[405:210918] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-08 03:57:02.874 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:57:02.877 ThaliTest[405:210918] server: starting 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:02.878 ThaliTest[405:210918] multipeer session: start timer: 0x16f2c3e0
,2015-12-08 03:57:02.879 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543422873.405
2015-12-08 03:57:02.880 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2015-12-08 03:57:04.117 ThaliTest[405:210658] client: found peer: 1449543421260.391.hpKQLw==
,2015-12-08 03:57:04.120 ThaliTest[405:210918] jxcore: connect 1449543421260.391.hpKQLw==
2015-12-08 03:57:04.120 ThaliTest[405:210918] client session: connect
,2015-12-08 03:57:04.120 ThaliTest[405:210918] client session: stateChange:0->1 1449543421260.391.hpKQLw==
,2015-12-08 03:57:04.168 ThaliTest[405:210658] client: found peer: 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:04.170 ThaliTest[405:210918] jxcore: connect 1449543421775.439.IbqVaQ==
2015-12-08 03:57:04.170 ThaliTest[405:210918] client session: connect
2015-12-08 03:57:04.170 ThaliTest[405:210918] client session: stateChange:0->1 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:05.215 ThaliTest[405:210658] multipeer session: reset timer
,2015-12-08 03:57:05.215 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:57:05.215 ThaliTest[405:210658] multipeer session: start timer: 0x16f2c3e0
,2015-12-08 03:57:05.215 ThaliTest[405:210658] server session: connect
2015-12-08 03:57:05.215 ThaliTest[405:210658] server session: stateChange:0->1 1449543421260.391
2015-12-08 03:57:05.218 ThaliTest[405:210658] server: accepting invitation 1449543421260.391
,2015-12-08 03:57:05.956 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:57:05.957 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:57:05.957 ThaliTest[405:210658] multipeer session: start timer: 0x16f2c3e0
2015-12-08 03:57:05.957 ThaliTest[405:210658] server session: connect
,2015-12-08 03:57:05.958 ThaliTest[405:210658] server session: stateChange:0->1 1449543421593.431
,2015-12-08 03:57:05.965 ThaliTest[405:210658] server: accepting invitation 1449543421593.431
,2015-12-08 03:57:06.341 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:57:06.341 ThaliTest[405:210658] multipeer session: stop timer
,2015-12-08 03:57:06.342 ThaliTest[405:210658] multipeer session: start timer: 0x16f2c3e0
2015-12-08 03:57:06.342 ThaliTest[405:210658] server session: connect
2015-12-08 03:57:06.342 ThaliTest[405:210658] server session: stateChange:0->1 1449543421775.439
,2015-12-08 03:57:06.345 ThaliTest[405:210658] server: accepting invitation 1449543421775.439
,2015-12-08 03:57:06.759 ThaliTest[405:210658] client: found peer: 1449543421593.431.+h1/ug==
,2015-12-08 03:57:06.761 ThaliTest[405:210918] jxcore: connect 1449543421593.431.+h1/ug==
2015-12-08 03:57:06.761 ThaliTest[405:210918] client session: connect
2015-12-08 03:57:06.761 ThaliTest[405:210918] client session: stateChange:0->1 1449543421593.431.+h1/ug==
,2015-12-08 03:57:07.682 ThaliTest[405:211154] client session: connected
2015-12-08 03:57:07.683 ThaliTest[405:211154] client session: stateChange:1->2 1449543421260.391.hpKQLw==
,2015-12-08 03:57:07.854 ThaliTest[405:211218] client session: fireConnectCallback: 1449543421260.391.hpKQLw==
2015-12-08 03:57:07.854 ThaliTest[405:211218] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-08 03:57:07.856 ThaliTest[405:210918] jxcore: disconnect
2015-12-08 03:57:07.856 ThaliTest[405:210918] client session: disconnectFromPeer: 1449543421260.391.hpKQLw==
,2015-12-08 03:57:07.856 ThaliTest[405:210918] client session: disconnect
2015-12-08 03:57:07.857 ThaliTest[405:210918] client session: stateChange:2->0 1449543421260.391.hpKQLw==
,2015-12-08 03:57:07.920 ThaliTest[405:210918] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2015-12-08 03:57:08.370 ThaliTest[405:211154] server session: connected
2015-12-08 03:57:08.370 ThaliTest[405:211154] server session: stateChange:1->2 1449543421260.391
,2015-12-08 03:57:08.435 ThaliTest[405:210658] server relay: socket disconnected
2015-12-08 03:57:08.436 ThaliTest[405:210658] server relay: 0x189889f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
2015-12-08 03:57:08.437 ThaliTest[405:211150] server session: not connected 1449543421260.391
,2015-12-08 03:57:09.279 ThaliTest[405:211218] server session: connected
,2015-12-08 03:57:09.279 ThaliTest[405:211218] server session: stateChange:1->2 1449543421775.439
,2015-12-08 03:57:09.286 ThaliTest[405:210658] server relay: socket disconnected
2015-12-08 03:57:09.286 ThaliTest[405:210658] server relay: 0x18988560 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:09.361 ThaliTest[405:211150] server session: not connected 1449543421775.439
,2015-12-08 03:57:09.434 ThaliTest[405:211218] server session: connected
,2015-12-08 03:57:09.434 ThaliTest[405:211218] server session: stateChange:1->2 1449543421593.431
,2015-12-08 03:57:09.686 ThaliTest[405:210658] server relay: socket disconnected
,2015-12-08 03:57:09.687 ThaliTest[405:210658] server relay: 0x1898a500 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:09.702 ThaliTest[405:211143] server session: not connected 1449543421593.431
,2015-12-08 03:57:10.210 ThaliTest[405:211154] client session: connected
,2015-12-08 03:57:10.210 ThaliTest[405:211154] client session: stateChange:1->2 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:10.214 ThaliTest[405:211154] client session: fireConnectCallback: 1449543421775.439.IbqVaQ==
2015-12-08 03:57:10.215 ThaliTest[405:211154] jxcore: connect: success
,ok 78 Should be able to connect without error
,ok 79 Port should be within range
,2015-12-08 03:57:10.219 ThaliTest[405:210918] jxcore: disconnect
,2015-12-08 03:57:10.219 ThaliTest[405:210918] client session: disconnectFromPeer: 1449543421775.439.IbqVaQ==
2015-12-08 03:57:10.220 ThaliTest[405:210918] client session: disconnect
2015-12-08 03:57:10.220 ThaliTest[405:210918] client session: stateChange:2->0 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:10.287 ThaliTest[405:210918] jxcore: disconnect: success
,ok 80 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,not ok 81 .end() called twice
,  ---
,    operator: fail
,  ...
,2015-12-08 03:57:10.406 ThaliTest[405:211150] client session: connected
2015-12-08 03:57:10.406 ThaliTest[405:211150] client session: stateChange:1->2 1449543421593.431.+h1/ug==
,2015-12-08 03:57:10.456 ThaliTest[405:211154] client session: fireConnectCallback: 1449543421593.431.+h1/ug==
2015-12-08 03:57:10.456 ThaliTest[405:211154] jxcore: connect: success
,ok 82 Should be able to connect without error
,ok 83 Port should be within range
,2015-12-08 03:57:10.460 ThaliTest[405:210918] jxcore: disconnect
,2015-12-08 03:57:10.461 ThaliTest[405:210918] client session: disconnectFromPeer: 1449543421593.431.+h1/ug==
,2015-12-08 03:57:10.461 ThaliTest[405:210918] client session: disconnect
,2015-12-08 03:57:10.461 ThaliTest[405:210918] client session: stateChange:2->0 1449543421593.431.+h1/ug==
,2015-12-08 03:57:10.472 ThaliTest[405:210918] jxcore: disconnect: success
ok 84 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
not ok 85 .end() called twice
  ---
    operator: fail
  ...
,calling stopBroadcasting
,2015-12-08 03:57:12.255 ThaliTest[405:210918] jxcore: stopBroadcasting
,2015-12-08 03:57:12.256 ThaliTest[405:210918] THEMultipeerSession stopping peer
,2015-12-08 03:57:12.256 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:57:12.259 ThaliTest[405:210918] server session: disconnect
2015-12-08 03:57:12.259 ThaliTest[405:210918] server session: stateChange:2->0 1449543421593.431
,2015-12-08 03:57:12.544 ThaliTest[405:210918] server session: disconnect
2015-12-08 03:57:12.544 ThaliTest[405:210918] server session: stateChange:2->0 1449543421775.439
,2015-12-08 03:57:12.545 ThaliTest[405:210918] server session: disconnect
2015-12-08 03:57:12.546 ThaliTest[405:210918] server session: stateChange:2->0 1449543421260.391
,2015-12-08 03:57:12.548 ThaliTest[405:210918] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-08 03:57:26.505 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:57:26.509 ThaliTest[405:210918] server: starting 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:26.510 ThaliTest[405:210918] multipeer session: start timer: 0x14e57040
,2015-12-08 03:57:26.510 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543446505.405
,2015-12-08 03:57:26.511 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 86 Should be able to call startBroadcasting without error
,2015-12-08 03:57:27.573 ThaliTest[405:210658] client: found peer: 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:27.574 ThaliTest[405:210918] jxcore: connect 1449543444583.391.Wxk+bw==
2015-12-08 03:57:27.575 ThaliTest[405:210918] client session: connect
,2015-12-08 03:57:27.575 ThaliTest[405:210918] client session: stateChange:0->1 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:28.029 ThaliTest[405:210658] client: found peer: 1449543445470.439.9bQ4gA==
2015-12-08 03:57:28.031 ThaliTest[405:210658] client: found peer: 1449543445467.431.nUNHmA==
2015-12-08 03:57:28.033 ThaliTest[405:210918] jxcore: connect 144954,3445470.439.9bQ4gA==
2015-12-08 03:57:28.033 ThaliTest[405:210918] client session: connect
2015-12-08 03:57:28.033 ThaliTest[405:210918] client session: stateChange:0->1 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:28.044 ThaliTest[405:210918] jxcore: connect 1449543445467.431.nUNHmA==
2015-12-08 03:57:28.045 ThaliTest[405:210918] client session: connect
,2015-12-08 03:57:28.045 ThaliTest[405:210918] client session: stateChange:0->1 1449543445467.431.nUNHmA==
,2015-12-08 03:57:28.162 ThaliTest[405:210658] multipeer session: reset timer
,2015-12-08 03:57:28.163 ThaliTest[405:210658] multipeer session: stop timer
,2015-12-08 03:57:28.163 ThaliTest[405:210658] multipeer session: start timer: 0x14e57040
2015-12-08 03:57:28.163 ThaliTest[405:210658] server session: connect
2015-12-08 03:57:28.164 ThaliTest[405:210658] server session: stateChange:0->1 1449543445467.431
,2015-12-08 03:57:28.171 ThaliTest[405:210658] server: accepting invitation 1449543445467.431
,2015-12-08 03:57:28.743 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:57:28.743 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:57:28.743 ThaliTest[405:210658] multipeer session: start timer: 0x14e57040
2015-12-08 03:57:28.743 ThaliTest[405:210658] server session: connect
2015-12-08 03:57:28.743 ThaliTest[405:210658] server session: stateChange:0->1 1449543445470.439
,2015-12-08 03:57:28.746 ThaliTest[405:210658] server: accepting invitation 1449543445470.439
,2015-12-08 03:57:28.750 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:57:28.750 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:57:28.750 ThaliTest[405:210658] multipeer session: start timer: 0x14e57040
2015-12-08 03:57:28.750 ThaliTest[405:210658] server session: connect
2015-12-08 03:57:28.750 ThaliTest[405:210658] server session: stateChange:0->1 1449543444583.391
2015-12-08 03:57:28.754 ThaliTest[405:210658] server: accepting invitation 1449543444583.391
,2015-12-08 03:57:31.373 ThaliTest[405:211247] client session: connected
2015-12-08 03:57:31.374 ThaliTest[405:211247] client session: stateChange:1->2 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.396 ThaliTest[405:211272] client session: fireConnectCallback: 1449543445470.439.9bQ4gA==
2015-12-08 03:57:31.397 ThaliTest[405:211272] jxcore: connect: success
,ok 87 Should be able to connect without error
,ok 88 Port should be within range
,2015-12-08 03:57:31.402 ThaliTest[405:210918] jxcore: connect 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.402 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.402 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,ok 89 Should fail on double connect
,2015-12-08 03:57:31.405 ThaliTest[405:210918] jxcore: disconnect
,2015-12-08 03:57:31.405 ThaliTest[405:210918] client session: disconnectFromPeer: 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.406 ThaliTest[405:210918] client session: disconnect
,2015-12-08 03:57:31.406 ThaliTest[405:210918] client session: stateChange:2->0 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.417 ThaliTest[405:210918] jxcore: disconnect: success
,ok 90 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2015-12-08 03:57:31.805 ThaliTest[405:211298] server session: connected
,2015-12-08 03:57:31.806 ThaliTest[405:211298] server session: stateChange:1->2 1449543445470.439
,2015-12-08 03:57:31.834 ThaliTest[405:211298] server session: connected
,2015-12-08 03:57:31.834 ThaliTest[405:211298] server session: stateChange:1->2 1449543445467.431
,2015-12-08 03:57:31.839 ThaliTest[405:210658] server relay: socket disconnected
,2015-12-08 03:57:31.839 ThaliTest[405:210658] server relay: 0x16f1bf60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:31.865 ThaliTest[405:210658] server relay: socket disconnected
,2015-12-08 03:57:31.866 ThaliTest[405:210658] server relay: 0x18a68fa0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:31.871 ThaliTest[405:211298] server session: not connected 1449543445470.439
,2015-12-08 03:57:31.883 ThaliTest[405:211300] server session: not connected 1449543445467.431
,2015-12-08 03:57:32.317 ThaliTest[405:211298] client session: connected
2015-12-08 03:57:32.317 ThaliTest[405:211298] client session: stateChange:1->2 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:32.359 ThaliTest[405:211300] client session: fireConnectCallback: 1449543444583.391.Wxk+bw==
2015-12-08 03:57:32.360 ThaliTest[405:211300] jxcore: connect: success
ok 91 Should be able to connect without error
ok 92 Port should be within range
2015-12-08 03:57:32.363 ThaliTest[405:210918] jxcore: connect 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:32.364 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543444583.391.Wxk+bw==
2015-12-08 03:57:32.367 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
ok 93 Should fail on double connect
,2015-12-08 03:57:32.369 ThaliTest[405:210918] jxcore: disconnect
2015-12-08 03:57:32.370 ThaliTest[405:210918] client session: disconnectFromPeer: 1449543444583.391.Wxk+bw==
2015-12-08 03:57:32.370 ThaliTest[405:210918] client session: disconnect
2015-12-08 03:57:32.370 ThaliTest[405:210918] client session: stateChange:2->0 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:32.377 ThaliTest[405:210918] jxcore: disconnect: success
,ok 94 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
not ok 95 .end() called twice
  ---
    operator: fail
  ...
,2015-12-08 03:57:32.414 ThaliTest[405:211298] client session: connected
2015-12-08 03:57:32.414 ThaliTest[405:211298] client session: stateChange:1->2 1449543445467.431.nUNHmA==
,2015-12-08 03:57:32.434 ThaliTest[405:211247] client session: fireConnectCallback: 1449543445467.431.nUNHmA==
2015-12-08 03:57:32.435 ThaliTest[405:211247] jxcore: connect: success
,ok 96 Should be able to connect without error
,ok 97 Port should be within range
,2015-12-08 03:57:32.438 ThaliTest[405:210918] jxcore: connect 1449543445467.431.nUNHmA==
2015-12-08 03:57:32.438 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543445467.431.nUNHmA==
,2015-12-08 03:57:32.439 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,ok 98 Should fail on double connect
,2015-12-08 03:57:32.440 ThaliTest[405:210918] jxcore: disconnect
,2015-12-08 03:57:32.441 ThaliTest[405:210918] client session: disconnectFromPeer: 1449543445467.431.nUNHmA==
2015-12-08 03:57:32.441 ThaliTest[405:210918] client session: disconnect
,2015-12-08 03:57:32.441 ThaliTest[405:210918] client session: stateChange:2->0 1449543445467.431.nUNHmA==
,2015-12-08 03:57:32.507 ThaliTest[405:210918] jxcore: disconnect: success
,ok 99 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,not ok 100 .end() called twice
  ---
,    operator: fail
,  ...
,2015-12-08 03:57:33.280 ThaliTest[405:211298] server session: connected
2015-12-08 03:57:33.280 ThaliTest[405:211298] server session: stateChange:1->2 1449543444583.391
,2015-12-08 03:57:33.346 ThaliTest[405:210658] server relay: socket disconnected
,2015-12-08 03:57:33.346 ThaliTest[405:210658] server relay: 0x16f112e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:33.370 ThaliTest[405:211298] server session: not connected 1449543444583.391
,calling stopBroadcasting
,2015-12-08 03:57:55.553 ThaliTest[405:210918] jxcore: stopBroadcasting
,2015-12-08 03:57:55.554 ThaliTest[405:210918] THEMultipeerSession stopping peer
,2015-12-08 03:57:55.554 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:57:55.555 ThaliTest[405:210918] server session: disconnect
2015-12-08 03:57:55.556 ThaliTest[405:210918] server session: stateChange:2->0 1449543445470.439
,2015-12-08 03:57:55.559 ThaliTest[405:210918] server session: disconnect
2015-12-08 03:57:55.559 ThaliTest[405:210918] server session: stateChange:2->0 1449543444583.391
,2015-12-08 03:57:55.563 ThaliTest[405:210918] server session: disconnect
2015-12-08 03:57:55.563 ThaliTest[405:210918] server session: stateChange:2->0 1449543445467.431
,2015-12-08 03:57:55.574 ThaliTest[405:210918] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-08 03:58:00.461 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:58:00.464 ThaliTest[405:210918] server: starting 1449543480460.405.wRZudQ==
2015-12-08 03:58:00.465 ThaliTest[405:210918] multipeer session: start timer: 0x18a5e650
2015-12-08 03:58:00.466 ThaliTest[405:210918] THEMultipeerSession initializ,ed peer 1449543480460.405
2015-12-08 03:58:00.466 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 101 Should be able to call startBroadcasting without error
,2015-12-08 03:58:00.581 ThaliTest[405:210658] client: found peer: 1449543477155.391.TQsX1A==
,2015-12-08 03:58:00.583 ThaliTest[405:210918] jxcore: connect 1449543477155.391.TQsX1A==
2015-12-08 03:58:00.584 ThaliTest[405:210918] client session: connect
2015-12-08 03:58:00.584 ThaliTest[405:210918] client session: stateChange:0->1 1449543477155.391.TQsX1A==
,2015-12-08 03:58:00.678 ThaliTest[405:210658] client: found peer: 1449543477671.439.01rxOw==
,2015-12-08 03:58:00.679 ThaliTest[405:210918] jxcore: connect 1449543477671.439.01rxOw==
2015-12-08 03:58:00.680 ThaliTest[405:210918] client session: connect
2015-12-08 03:58:00.680 ThaliTest[405:210918] client session: stateChange:0->1 1449543477671.439.01rxOw==
,2015-12-08 03:58:00.781 ThaliTest[405:210658] client: found peer: 1449543478008.431.8PN9MA==
,2015-12-08 03:58:00.783 ThaliTest[405:210918] jxcore: connect 1449543478008.431.8PN9MA==
2015-12-08 03:58:00.784 ThaliTest[405:210918] client session: connect
2015-12-08 03:58:00.784 ThaliTest[405:210918] client session: stateChange:0->1 1449543478008.431.8PN9MA==
,2015-12-08 03:58:01.700 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:58:01.700 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:58:01.701 ThaliTest[405:210658] multipeer session: start timer: 0x18a5e650
,2015-12-08 03:58:01.701 ThaliTest[405:210658] server session: connect
,2015-12-08 03:58:01.701 ThaliTest[405:210658] server session: stateChange:0->1 1449543477671.439
,2015-12-08 03:58:01.705 ThaliTest[405:210658] server: accepting invitation 1449543477671.439
,2015-12-08 03:58:01.856 ThaliTest[405:210658] multipeer session: reset timer
,2015-12-08 03:58:01.856 ThaliTest[405:210658] multipeer session: stop timer
,2015-12-08 03:58:01.858 ThaliTest[405:210658] multipeer session: start timer: 0x18a5e650
,2015-12-08 03:58:01.858 ThaliTest[405:210658] server session: connect
,2015-12-08 03:58:01.859 ThaliTest[405:210658] server session: stateChange:0->1 1449543477155.391
,2015-12-08 03:58:01.865 ThaliTest[405:210658] server: accepting invitation 1449543477155.391
,2015-12-08 03:58:02.566 ThaliTest[405:210658] multipeer session: reset timer
,2015-12-08 03:58:02.567 ThaliTest[405:210658] multipeer session: stop timer
,2015-12-08 03:58:02.567 ThaliTest[405:210658] multipeer session: start timer: 0x18a5e650
,2015-12-08 03:58:02.567 ThaliTest[405:210658] server session: connect
,2015-12-08 03:58:02.568 ThaliTest[405:210658] server session: stateChange:0->1 1449543478008.431
,2015-12-08 03:58:02.572 ThaliTest[405:210658] server: accepting invitation 1449543478008.431
,2015-12-08 03:58:03.482 ThaliTest[405:211383] client session: connected
,2015-12-08 03:58:03.483 ThaliTest[405:211383] client session: stateChange:1->2 1449543477671.439.01rxOw==
,2015-12-08 03:58:03.507 ThaliTest[405:211380] client session: fireConnectCallback: 1449543477671.439.01rxOw==
2015-12-08 03:58:03.508 ThaliTest[405:211380] jxcore: connect: success
,ok 102 Should be able to connect without error
,ok 103 Port should be within range
,2015-12-08 03:58:03.512 ThaliTest[405:210918] jxcore: disconnect
2015-12-08 03:58:03.512 ThaliTest[405:210918] client session: disconnectFromPeer: 1449543477671.439.01rxOw==
2015-12-08 03:58:03.513 ThaliTest[405:210918] client session: disconnect
2015-12-08 03:58:03.513 ThaliTest[405:210918] client session: stateChange:2->0 1449543477671.439.01rxOw==
,2015-12-08 03:58:03.583 ThaliTest[405:210918] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error
,2015-12-08 03:58:03.586 ThaliTest[405:210918] jxcore: disconnect
,2015-12-08 03:58:03.586 ThaliTest[405:210918] jxcore: disconnect: fail
,ok 105 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,2015-12-08 03:58:04.472 ThaliTest[405:211377] client session: connected
2015-12-08 03:58:04.472 ThaliTest[405:211377] client session: stateChange:1->2 1449543477155.391.TQsX1A==
,2015-12-08 03:58:04.495 ThaliTest[405:211383] client session: fireConnectCallback: 1449543477155.391.TQsX1A==
2015-12-08 03:58:04.495 ThaliTest[405:211383] jxcore: connect: success
,ok 106 Should be able to connect without error
,ok 107 Port should be within range
,2015-12-08 03:58:04.499 ThaliTest[405:210918] jxcore: disconnect
,2015-12-08 03:58:04.499 ThaliTest[405:210918] client session: disconnectFromPeer: 1449543477155.391.TQsX1A==
,2015-12-08 03:58:04.500 ThaliTest[405:210918] client session: disconnect
,2015-12-08 03:58:04.500 ThaliTest[405:210918] client session: stateChange:2->0 1449543477155.391.TQsX1A==
,2015-12-08 03:58:04.533 ThaliTest[405:211384] client session: connected
2015-12-08 03:58:04.533 ThaliTest[405:211384] client session: stateChange:1->2 1449543478008.431.8PN9MA==
,2015-12-08 03:58:04.568 ThaliTest[405:210918] jxcore: disconnect: success
ok 108 Should be able to disconnect without error
2015-12-08 03:58:04.570 ThaliTest[405:210918] jxcore: disconnect
2015-12-08 03:58:04.570 ThaliTest[405:210918] jxcore: disconnect: fail
ok 109 Disconnect should fail 
setting stopBroadcasting callback and ending test.
2015-12-08 03:58:04.571 ThaliTest[405:211380] client session: fireConnectCallback: 1449543478008.431.8PN9MA==
2015-12-08 03:58:04.572 ThaliTest[405:211380] jxcore: connect: success
,not ok 110 .end() called twice
,  ---
,    operator: fail
,  ...
,ok 111 Should be able to connect without error
,ok 112 Port should be within range
,2015-12-08 03:58:04.577 ThaliTest[405:210918] jxcore: disconnect
,2015-12-08 03:58:04.577 ThaliTest[405:210918] client session: disconnectFromPeer: 1449543478008.431.8PN9MA==
2015-12-08 03:58:04.578 ThaliTest[405:210918] client session: disconnect
,2015-12-08 03:58:04.578 ThaliTest[405:210918] client session: stateChange:2->0 1449543478008.431.8PN9MA==
,2015-12-08 03:58:04.584 ThaliTest[405:210918] jxcore: disconnect: success
ok 113 Should be able to disconnect without error
2015-12-08 03:58:04.586 ThaliTest[405:210918] jxcore: disconnect
2015-12-08 03:58:04.586 ThaliTest[405:210918] jxcore: disconnect,: fail
ok 114 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,not ok 115 .end() called twice
,  ---
,    operator: fail
  ...
,2015-12-08 03:58:04.726 ThaliTest[405:211383] server session: connected
2015-12-08 03:58:04.727 ThaliTest[405:211383] server session: stateChange:1->2 1449543477671.439
,2015-12-08 03:58:04.747 ThaliTest[405:210658] server relay: socket disconnected
,2015-12-08 03:58:04.748 ThaliTest[405:210658] server relay: 0x18990480 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:58:04.797 ThaliTest[405:211378] server session: not connected 1449543477671.439
,2015-12-08 03:58:05.383 ThaliTest[405:211378] server session: connected
2015-12-08 03:58:05.383 ThaliTest[405:211378] server session: stateChange:1->2 1449543478008.431
,2015-12-08 03:58:05.443 ThaliTest[405:210658] server relay: socket disconnected
2015-12-08 03:58:05.443 ThaliTest[405:210658] server relay: 0x18a77a90 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:58:05.509 ThaliTest[405:211384] server session: not connected 1449543478008.431
,2015-12-08 03:58:06.037 ThaliTest[405:211383] server session: connected
2015-12-08 03:58:06.038 ThaliTest[405:211383] server session: stateChange:1->2 1449543477155.391
,2015-12-08 03:58:06.076 ThaliTest[405:210658] server relay: socket disconnected
,2015-12-08 03:58:06.077 ThaliTest[405:210658] server relay: 0x189ab090 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:58:06.163 ThaliTest[405:211384] server session: not connected 1449543477155.391
,calling stopBroadcasting
,2015-12-08 03:58:06.301 ThaliTest[405:210918] jxcore: stopBroadcasting
,2015-12-08 03:58:06.302 ThaliTest[405:210918] THEMultipeerSession stopping peer
,2015-12-08 03:58:06.302 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:58:06.303 ThaliTest[405:210918] server session: disconnect
,2015-12-08 03:58:06.304 ThaliTest[405:210918] server session: stateChange:2->0 1449543477155.391
,2015-12-08 03:58:06.402 ThaliTest[405:210918] server session: disconnect
2015-12-08 03:58:06.402 ThaliTest[405:210918] server session: stateChange:2->0 1449543478008.431
,2015-12-08 03:58:06.403 ThaliTest[405:210918] server session: disconnect
2015-12-08 03:58:06.404 ThaliTest[405:210918] server session: stateChange:2->0 1449543477671.439
,2015-12-08 03:58:06.406 ThaliTest[405:210918] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-08 03:58:11.367 ThaliTest[405:210918] jxcore: startBroadcasting
,2015-12-08 03:58:11.371 ThaliTest[405:210918] server: starting 1449543491366.405.MuCjBg==
,2015-12-08 03:58:11.372 ThaliTest[405:210918] multipeer session: start timer: 0x18a77ab0
2015-12-08 03:58:11.373 ThaliTest[405:210918] THEMultipeerSession initialized peer 1449543491366.405
2015-12-08 03:58:11.373 ThaliTest[405:210918] jxcore: startBroadcasting: success
,ok 116 Should be able to call startBroadcasting without error
echo server started
,2015-12-08 03:58:12.739 ThaliTest[405:210658] client: found peer: 1449543490182.439.HczcmQ==
2015-12-08 03:58:12.740 ThaliTest[405:210658] client: found peer: 1449543489999.431.1e3a9w==
,[{"peerIdentifier":"1449543490182.439.HczcmQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 03:58:12.743 ThaliTest[405:210918] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:12.744 ThaliTest[405:210918] client session: connect
2015-12-08 03:58:12.744 ThaliTest[405:210918] client session: stateChange:0->1 1449543490182.439.HczcmQ==
,[{"peerIdentifier":"1449543489999.431.1e3a9w==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 03:58:12.752 ThaliTest[405:210918] jxcore: connect 1449543489999.431.1e3a9w==
2015-12-08 03:58:12.753 ThaliTest[405:210918] client session: connect
2015-12-08 03:58:12.753 ThaliTest[405:210918] client session: stateChange:0->1 1449543489999.431.1e3a9w==
,2015-12-08 03:58:13.111 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:58:13.111 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:58:13.112 ThaliTest[405:210658] multipeer session: start timer: 0x18a77ab0
2015-12-08 ,03:58:13.112 ThaliTest[405:210658] server session: connect
,2015-12-08 03:58:13.112 ThaliTest[405:210658] server session: stateChange:0->1 1449543490182.439
,2015-12-08 03:58:13.121 ThaliTest[405:210658] server: accepting invitation 1449543490182.439
,2015-12-08 03:58:13.131 ThaliTest[405:210658] client: found peer: 1449543489757.391.iXbQJw==
[{"peerIdentifier":"1449543489757.391.iXbQJw==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 03:58:13.136 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:13.139 ThaliTest[405:210918] client session: connect
2015-12-08 03:58:13.139 ThaliTest[405:210918] client session: stateChange:0->1 1449543489757.391.iXbQJw==
,2015-12-08 03:58:13.174 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:58:13.174 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:58:13.174 ThaliTest[405:210658] multipeer session: start timer: 0x18a77ab0
2015-12-08 03:58:13.174 ThaliTest[405:210658] server session: connect
2015-12-08 03:58:13.175 ThaliTest[405:210658] server session: stateChange:0->1 1449543489999.431
,2015-12-08 03:58:13.178 ThaliTest[405:210658] server: accepting invitation 1449543489999.431
,2015-12-08 03:58:13.231 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:58:13.231 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:58:13.232 ThaliTest[405:210658] multipeer session: start timer: 0x18a77ab0
2015-12-08 03:58:13.232 ThaliTest[405:210658] server session: connect
2015-12-08 03:58:13.232 ThaliTest[405:210658] server session: stateChange:0->1 1449543489757.391
,2015-12-08 03:58:13.237 ThaliTest[405:210658] server: accepting invitation 1449543489757.391
,2015-12-08 03:58:16.345 ThaliTest[405:211388] server session: connected
2015-12-08 03:58:16.345 ThaliTest[405:211388] server session: stateChange:1->2 1449543489999.431
,2015-12-08 03:58:16.348 ThaliTest[405:210658] server relay: connected (to port: 5001)
,2015-12-08 03:58:16.372 ThaliTest[405:211380] server session: connected
2015-12-08 03:58:16.373 ThaliTest[405:211380] server session: stateChange:1->2 1449543490182.439
,2015-12-08 03:58:16.374 ThaliTest[405:210658] server relay: connected (to port: 5001)
,2015-12-08 03:58:16.410 ThaliTest[405:211388] client session: connected
2015-12-08 03:58:16.410 ThaliTest[405:211388] client session: stateChange:1->2 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.443 ThaliTest[405:211380] client session: fireConnectCallback: 1449543489999.431.1e3a9w==
2015-12-08 03:58:16.443 ThaliTest[405:211380] jxcore: connect: success
,ok 117 Should be able to connect without error
,ok 118 Port should be within range
,ok 119 First connect should succeed
,2015-12-08 03:58:16.459 ThaliTest[405:210658] client: relay established
2015-12-08 03:58:16.459 ThaliTest[405:210658] client: new accepted socket: 0x18a7fe50
,ok 120 the test messages should be equal
ok 121 First send should succeed
,2015-12-08 03:58:16.556 ThaliTest[405:211388] server session: not connected 1449543490182.439
,2015-12-08 03:58:16.562 ThaliTest[405:210658] client: socket closed
,2015-12-08 03:58:16.562 ThaliTest[405:210658] client relay: socket disconnected
2015-12-08 03:58:16.562 ThaliTest[405:210658] client relay: 0x18a7fe50 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-08 03:58:16.562 ThaliTest[405:210658] client session: socket closed: 1449543489999.431.1e3a9w==
2015-12-08 03:58:16.562 ThaliTest[405:210658] client session: onLinkFailure: 1449543489999.431.1e3a9w==
2015-12-08 03:58:16.563 ThaliTest[405:210658] ,client session: disconnect
2015-12-08 03:58:16.563 ThaliTest[405:210658] client session: stateChange:2->0 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.566 ThaliTest[405:210658] client session: fireConnectionErrorEvent: 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.571 ThaliTest[405:210918] jxcore: connect 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.571 ThaliTest[405:210918] client session: connect
,2015-12-08 03:58:16.571 ThaliTest[405:210918] client session: stateChange:0->1 1449543489999.431.1e3a9w==
,2015-12-08 03:58:16.707 ThaliTest[405:211384] server session: not connected 1449543489999.431
,2015-12-08 03:58:16.794 ThaliTest[405:210658] multipeer session: reset timer
,2015-12-08 03:58:16.795 ThaliTest[405:210658] multipeer session: stop timer
,2015-12-08 03:58:16.796 ThaliTest[405:210658] multipeer session: start timer: 0x18a77ab0
,2015-12-08 03:58:16.797 ThaliTest[405:210658] server: disconnecting to refresh session (1449543489999.431)
,2015-12-08 03:58:16.799 ThaliTest[405:210658] server session: disconnect
,2015-12-08 03:58:16.800 ThaliTest[405:210658] server session: stateChange:2->0 1449543489999.431
,2015-12-08 03:58:16.803 ThaliTest[405:210658] server session: connect
2015-12-08 03:58:16.804 ThaliTest[405:210658] server session: stateChange:0->1 1449543489999.431
,2015-12-08 03:58:16.817 ThaliTest[405:210658] server: accepting invitation 1449543489999.431
,2015-12-08 03:58:16.843 ThaliTest[405:210658] multipeer session: reset timer
,2015-12-08 03:58:16.843 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:58:16.844 ThaliTest[405:210658] multipeer session: start timer: 0x18a77ab0
,2015-12-08 03:58:16.844 ThaliTest[405:210658] server: disconnecting to refresh session (1449543490182.439)
,2015-12-08 03:58:16.845 ThaliTest[405:210658] server session: disconnect
,2015-12-08 03:58:16.845 ThaliTest[405:210658] server session: stateChange:2->0 1449543490182.439
,2015-12-08 03:58:16.849 ThaliTest[405:210658] server session: connect
,2015-12-08 03:58:16.849 ThaliTest[405:210658] server session: stateChange:0->1 1449543490182.439
,2015-12-08 03:58:16.864 ThaliTest[405:210658] server: accepting invitation 1449543490182.439
,2015-12-08 03:58:17.370 ThaliTest[405:211380] client session: connected
2015-12-08 03:58:17.371 ThaliTest[405:211380] client session: stateChange:1->2 1449543490182.439.HczcmQ==
,2015-12-08 03:58:17.385 ThaliTest[405:211484] client session: fireConnectCallback: 1449543490182.439.HczcmQ==
2015-12-08 03:58:17.385 ThaliTest[405:211484] jxcore: connect: success
,ok 122 Should be able to connect without error
,ok 123 Port should be within range
,ok 124 First connect should succeed
,2015-12-08 03:58:17.408 ThaliTest[405:210658] client: relay established
2015-12-08 03:58:17.408 ThaliTest[405:210658] client: new accepted socket: 0x18a868f0
,ok 125 the test messages should be equal
,ok 126 First send should succeed
,2015-12-08 03:58:17.483 ThaliTest[405:210658] client: socket closed
2015-12-08 03:58:17.483 ThaliTest[405:210658] client relay: socket disconnected
2015-12-08 03:58:17.483 ThaliTest[405:210658] client relay: 0x18a868f0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:17.483 ThaliTest[405:210658] client session: socket closed: 1449543490182.439.HczcmQ==
2015-12-08 03:58:17.483 ThaliTest[405:210658] client session: onLinkFailure: 1449543490182.439.HczcmQ==
2015-12-08 03:58:17.483 ThaliTest[405:210658] client session: disconnect
2015-12-08 03:58:17.483 ThaliTest[405:210658] client session: stateChange:2->0 1449543490182.439.HczcmQ==
,2015-12-08 03:58:17.488 ThaliTest[405:210658] client session: fireConnectionErrorEvent: 1449543490182.439.HczcmQ==
2015-12-08 03:58:17.489 ThaliTest[405:210918] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:17.489 ThaliTest[405:210918] client session: connect
2015-12-08 03:58:17.489 ThaliTest[405:210918] client session: stateChange:0->1 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.002 ThaliTest[405:210918] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:18.002 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:18.003 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:18.954 ThaliTest[405:211384] server session: connected
,2015-12-08 03:58:18.954 ThaliTest[405:211384] server session: stateChange:1->2 1449543489757.391
,2015-12-08 03:58:18.965 ThaliTest[405:211384] client session: connected
2015-12-08 03:58:18.965 ThaliTest[405:211384] client session: stateChange:1->2 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.970 ThaliTest[405:210658] server relay: connected (to port: 5001)
,2015-12-08 03:58:18.994 ThaliTest[405:211378] client session: fireConnectCallback: 1449543489757.391.iXbQJw==
2015-12-08 03:58:18.994 ThaliTest[405:211378] jxcore: connect: success
,ok 127 Should be able to connect without error
,ok 128 Port should be within range
,ok 129 First connect should succeed
,2015-12-08 03:58:19.014 ThaliTest[405:210658] client: relay established
2015-12-08 03:58:19.014 ThaliTest[405:210658] client: new accepted socket: 0x18a6ffd0
,2015-12-08 03:58:19.028 ThaliTest[405:210918] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:19.028 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:19.028 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,ok 130 the test messages should be equal
,ok 131 First send should succeed
,2015-12-08 03:58:19.146 ThaliTest[405:210658] client: socket closed
,2015-12-08 03:58:19.147 ThaliTest[405:210658] client relay: socket disconnected
,2015-12-08 03:58:19.147 ThaliTest[405:210658] client relay: 0x18a6ffd0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:19.147 ThaliTest[405:210658] client session: socket closed: 1449543489757.391.iXbQJw==
,2015-12-08 03:58:19.148 ThaliTest[405:210658] client session: onLinkFailure: 1449543489757.391.iXbQJw==
2015-12-08 03:58:19.148 ThaliTest[405:210658] client session: disconnect
,2015-12-08 03:58:19.148 ThaliTest[405:210658] client session: stateChange:2->0 1449543489757.391.iXbQJw==
,2015-12-08 03:58:19.158 ThaliTest[405:210658] client session: fireConnectionErrorEvent: 1449543489757.391.iXbQJw==
2015-12-08 03:58:19.160 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:19.160 ThaliTest[405:210918] client session: connect
,2015-12-08 03:58:19.163 ThaliTest[405:210918] client session: stateChange:0->1 1449543489757.391.iXbQJw==
,2015-12-08 03:58:19.171 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:19.171 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:19.171 ThaliTest[405:210918] jxcore: con,nect: fail: Aleady connecting
2015-12-08 03:58:19.172 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:19.173 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:19.173 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:19.235 ThaliTest[405:211384] server session: not connected 1449543489757.391
,2015-12-08 03:58:19.400 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:58:19.401 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:58:19.401 ThaliTest[405:210658] multipeer session: start timer: 0x18a77ab0
2015-12-08 03:58:19.402 ThaliTest[405:210658] server: disconnecting to refresh session (1449543489757.391)
,2015-12-08 03:58:19.402 ThaliTest[405:210658] server session: disconnect
2015-12-08 03:58:19.402 ThaliTest[405:210658] server session: stateChange:2->0 1449543489757.391
,2015-12-08 03:58:19.406 ThaliTest[405:210658] server session: connect
2015-12-08 03:58:19.407 ThaliTest[405:210658] server session: stateChange:0->1 1449543489757.391
,2015-12-08 03:58:19.415 ThaliTest[405:210658] server: accepting invitation 1449543489757.391
,2015-12-08 03:58:19.929 ThaliTest[405:211378] server session: connected
2015-12-08 03:58:19.929 ThaliTest[405:211378] server session: stateChange:1->2 1449543489999.431
,2015-12-08 03:58:19.938 ThaliTest[405:210658] server relay: connected (to port: 5001)
,2015-12-08 03:58:19.942 ThaliTest[405:211378] client session: connected
2015-12-08 03:58:19.943 ThaliTest[405:211378] client session: stateChange:1->2 1449543489999.431.1e3a9w==
,2015-12-08 03:58:19.981 ThaliTest[405:211470] client session: fireConnectCallback: 1449543489999.431.1e3a9w==
2015-12-08 03:58:19.981 ThaliTest[405:211470] jxcore: connect: success
,ok 132 Should be able to connect without error
,ok 133 Port should be within range
,ok 134 Second connect should succeed
,2015-12-08 03:58:20.001 ThaliTest[405:210658] client: relay established
2015-12-08 03:58:20.001 ThaliTest[405:210658] client: new accepted socket: 0x16f2a8c0
,2015-12-08 03:58:20.039 ThaliTest[405:210918] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:20.039 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
,2015-12-08 03:58:20.039 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:20.064 ThaliTest[405:211380] server session: connected
2015-12-08 03:58:20.064 ThaliTest[405:211380] server session: stateChange:1->2 1449543490182.439
,ok 135 the test messages should be equal
,ok 136 Second send should succeed
,# setup
,2015-12-08 03:58:20.071 ThaliTest[405:210658] server relay: connected (to port: 5001)
,2015-12-08 03:58:20.084 ThaliTest[405:210658] client: socket closed
2015-12-08 03:58:20.084 ThaliTest[405:210658] client relay: socket disconnected
,2015-12-08 03:58:20.084 ThaliTest[405:210658] client relay: 0x16f2a8c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-08 03:58:20.084 ThaliTest[405:210658] client session: socket closed: 1449543489999.431.1e3a9w==
,2015-12-08 03:58:20.084 ThaliTest[405:210658] client session: onLinkFailure: 1449543489999.431.1e3a9w==
2015-12-08 03:58:20.085 ThaliTest[405:210658] client session: disconnect
,2015-12-08 03:58:20.085 ThaliTest[405:210658] client session: stateChange:2->0 1449543489999.431.1e3a9w==
,2015-12-08 03:58:20.090 ThaliTest[405:210658] client session: fireConnectionErrorEvent: 1449543489999.431.1e3a9w==
,2015-12-08 03:58:20.112 ThaliTest[405:211380] server session: not connected 1449543489999.431
,2015-12-08 03:58:20.182 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:20.183 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
,2015-12-08 03:58:20.183 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:20.185 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:20.185 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
,2015-12-08 03:58:20.186 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:20.445 ThaliTest[405:211380] server session: not connected 1449543490182.439
,2015-12-08 03:58:21.032 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:58:21.032 ThaliTest[405:210658] multipeer session: stop timer
,2015-12-08 03:58:21.033 ThaliTest[405:210658] multipeer session: start timer: 0x18a77ab0
2015-12-08 03:58:21.033 ThaliTest[405:210658] server: disconnecting to refresh session (1449543490182.439)
2015-12-08 03:58:21.034 ThaliTest[405:210658] server session: disconnect
2015-12-08 03:58:21.034 ThaliTest[405:210658] server session: stateChange:2->0 1449543490182.439
,2015-12-08 03:58:21.048 ThaliTest[405:210918] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:21.048 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
,2015-12-08 03:58:21.049 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:21.195 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:21.196 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
,2015-12-08 03:58:21.196 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:21.198 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:21.198 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:21.198 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:21.719 ThaliTest[405:210658] server session: connect
2015-12-08 03:58:21.719 ThaliTest[405:210658] server session: stateChange:0->1 1449543490182.439
,2015-12-08 03:58:21.725 ThaliTest[405:210658] server: accepting invitation 1449543490182.439
,2015-12-08 03:58:22.056 ThaliTest[405:210918] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:22.056 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:22.057 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:22.128 ThaliTest[405:211470] client session: connected
2015-12-08 03:58:22.128 ThaliTest[405:211470] client session: stateChange:1->2 1449543490182.439.HczcmQ==
,2015-12-08 03:58:22.153 ThaliTest[405:211470] client session: fireConnectCallback: 1449543490182.439.HczcmQ==
2015-12-08 03:58:22.153 ThaliTest[405:211470] jxcore: connect: success
,ok 137 Should be able to connect without error
,ok 138 Port should be within range
,ok 139 Second connect should succeed
,2015-12-08 03:58:22.165 ThaliTest[405:210658] client: relay established
2015-12-08 03:58:22.165 ThaliTest[405:210658] client: new accepted socket: 0x16f282c0
,2015-12-08 03:58:22.203 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:22.203 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:22.204 ThaliTest[405:210918] jxcore: con,nect: fail: Aleady connecting
2015-12-08 03:58:22.204 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:22.204 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:22.204 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,ok 140 the test messages should be equal
,ok 141 Second send should succeed
,not ok 142 .end() called twice
  ---
,    operator: fail
,  ...
,2015-12-08 03:58:22.562 ThaliTest[405:210658] client: socket closed
,2015-12-08 03:58:22.563 ThaliTest[405:210658] client relay: socket disconnected
,2015-12-08 03:58:22.563 ThaliTest[405:210658] client relay: 0x16f282c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:22,.563 ThaliTest[405:210658] client session: socket closed: 1449543490182.439.HczcmQ==
2015-12-08 03:58:22.563 ThaliTest[405:210658] client session: onLinkFailure: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:22.564 ThaliTest[405:210658] client session: disconnect
2015-12-08 03:58:22.564 ThaliTest[405:210658] client session: stateChange:2->0 1449543490182.439.HczcmQ==
,2015-12-08 03:58:22.574 ThaliTest[405:210658] client session: fireConnectionErrorEvent: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:23.065 ThaliTest[405:210918] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:23.065 ThaliTest[405:210918] client session: connect
,2015-12-08 03:58:23.067 ThaliTest[405:210918] client session: stateChange:0->1 1449543490182.439.HczcmQ==
,2015-12-08 03:58:23.211 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:23.212 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
,2015-12-08 03:58:23.212 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:23.214 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:23.214 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
,2015-12-08 03:58:23.215 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:24.045 ThaliTest[405:211380] server session: connected
,2015-12-08 03:58:24.046 ThaliTest[405:211380] server session: stateChange:1->2 1449543489757.391
,2015-12-08 03:58:24.051 ThaliTest[405:210658] server relay: connected (to port: 5001)
,2015-12-08 03:58:24.195 ThaliTest[405:211388] server session: not connected 1449543489757.391
,2015-12-08 03:58:24.218 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:24.219 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
2015-12-08 03:58:24.219 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:24.221 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:24.222 ThaliTest[405:210918] client: already connect(ing/ed) to 1449543489757.391.iXbQJw==
,2015-12-08 03:58:24.222 ThaliTest[405:210918] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:24.377 ThaliTest[405:210658] multipeer session: reset timer
2015-12-08 03:58:24.377 ThaliTest[405:210658] multipeer session: stop timer
2015-12-08 03:58:24.378 ThaliTest[405:210658] multipeer session: start timer: 0x18a77ab0
2015-12-08 ,03:58:24.378 ThaliTest[405:210658] server: disconnecting to refresh session (1449543489757.391)
,2015-12-08 03:58:24.378 ThaliTest[405:210658] server session: disconnect
2015-12-08 03:58:24.379 ThaliTest[405:210658] server session: stateChange:2->0 1449543489757.391
,2015-12-08 03:58:24.383 ThaliTest[405:210658] server session: connect
2015-12-08 03:58:24.384 ThaliTest[405:210658] server session: stateChange:0->1 1449543489757.391
,2015-12-08 03:58:24.395 ThaliTest[405:210658] server: accepting invitation 1449543489757.391
,2015-12-08 03:58:24.404 ThaliTest[405:211384] client session: connected
,2015-12-08 03:58:24.405 ThaliTest[405:211384] client session: stateChange:1->2 1449543489757.391.iXbQJw==
,2015-12-08 03:58:24.413 ThaliTest[405:211384] client session: fireConnectCallback: 1449543489757.391.iXbQJw==
2015-12-08 03:58:24.413 ThaliTest[405:211384] jxcore: connect: success
ok 143 Should be able to connect without error
ok 144 Port should be within range
ok 145 Second connect should succeed
,2015-12-08 03:58:24.438 ThaliTest[405:210658] client: relay established
2015-12-08 03:58:24.439 ThaliTest[405:210658] client: new accepted socket: 0x16f2c120
,ok 146 the test messages should be equal
,ok 147 Second send should succeed
,not ok 148 .end() called twice
  ---
    operator: fail
  ...
,2015-12-08 03:58:24.480 ThaliTest[405:210658] client: socket closed
,2015-12-08 03:58:24.480 ThaliTest[405:210658] client relay: socket disconnected
2015-12-08 03:58:24.481 ThaliTest[405:210658] client relay: 0x16f2c120 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:24.481 ThaliTest[405:210658] client session: socket closed: 1449543489757.391.iXbQJw==
2015-12-08 03:58:24.481 ThaliTest[405:210658] client session: onLinkFailure: 144954348975,7.391.iXbQJw==
2015-12-08 03:58:24.481 ThaliTest[405:210658] client session: disconnect
2015-12-08 03:58:24.481 ThaliTest[405:210658] client session: stateChange:2->0 1449543489757.391.iXbQJw==
,2015-12-08 03:58:24.488 ThaliTest[405:210658] client session: fireConnectionErrorEvent: 1449543489757.391.iXbQJw==
,2015-12-08 03:58:24.681 ThaliTest[405:211470] server session: connected
,2015-12-08 03:58:24.682 ThaliTest[405:211470] server session: stateChange:1->2 1449543490182.439
,2015-12-08 03:58:24.684 ThaliTest[405:210658] server relay: connected (to port: 5001)
,2015-12-08 03:58:24.796 ThaliTest[405:211470] server session: not connected 1449543490182.439
,calling stopBroadcasting
,2015-12-08 03:58:25.149 ThaliTest[405:210918] jxcore: stopBroadcasting
,2015-12-08 03:58:25.150 ThaliTest[405:210918] THEMultipeerSession stopping peer
,2015-12-08 03:58:25.150 ThaliTest[405:210918] multipeer session: stop timer
,2015-12-08 03:58:25.151 ThaliTest[405:210918] client session: disconnect
,2015-12-08 03:58:25.152 ThaliTest[405:210918] client session: stateChange:1->0 1449543490182.439.HczcmQ==
,2015-12-08 03:58:25.221 ThaliTest[405:210918] server session: disconnect
2015-12-08 03:58:25.221 ThaliTest[405:210918] server session: stateChange:2->0 1449543490182.439
,2015-12-08 03:58:25.228 ThaliTest[405:210918] server session: disconnect
2015-12-08 03:58:25.228 ThaliTest[405:210918] server session: stateChange:2->0 1449543489999.431
,2015-12-08 03:58:26.228 ThaliTest[405:210918] server session: disconnect
,2015-12-08 03:58:26.228 ThaliTest[405:210918] server session: stateChange:1->0 1449543489757.391
,2015-12-08 03:58:26.229 ThaliTest[405:210918] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,2015-12-08 03:58:26.247 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:26.248 ThaliTest[405:210918] Communications not enabled
,2015-12-08 03:58:26.248 ThaliTest[405:210918] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:26.250 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:26.250 ThaliTest[405:210918] Communications not enabled
,2015-12-08 03:58:26.251 ThaliTest[405:210918] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:27.259 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:27.260 ThaliTest[405:210918] Communications not enabled
,2015-12-08 03:58:27.261 ThaliTest[405:210918] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:27.262 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:27.262 ThaliTest[405:210918] Communications not enabled
,2015-12-08 03:58:27.262 ThaliTest[405:210918] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:28.270 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:28.271 ThaliTest[405:210918] Communications not enabled
,2015-12-08 03:58:28.271 ThaliTest[405:210918] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:28.273 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:28.274 ThaliTest[405:210918] Communications not enabled
,2015-12-08 03:58:28.274 ThaliTest[405:210918] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:29.274 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
,2015-12-08 03:58:29.274 ThaliTest[405:210918] Communications not enabled
,2015-12-08 03:58:29.275 ThaliTest[405:210918] jxcore: connect: fail: app: Not initialised
,2015-12-08 03:58:29.277 ThaliTest[405:210918] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:29.277 ThaliTest[405:210918] Communications not enabled
,2015-12-08 03:58:29.278 ThaliTest[405:210918] jxcore: connect: fail: app: Not initialised
,not ok 149 Second connect should succeed
  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,not ok 150 Second connect should succeed
,  ---
,    operator: ok
,    expected: true
,    actual:   false
,  ...
,2015-12-08 03:58:30.336 ThaliTest[405:210918] Error!: connect EADDRNOTAVAIL
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_functi,onName":"connect","_lineNumber":"707","_columnNumber":"19","_msg":"    at connect@net.js:707:19"},{"_fileName":"net.js","_functionName":"Socket.prototype.connect","_lineNumber":"756","_columnNumber":"5","_msg":"    at Socket.prototype.connect@net.js:756:5"},{"_fileName":"net.js","_functionName":"exports.createConnection","_lineNumber":"72","_columnNumber":"10","_msg":"    at exports.createConnection@net.js:72:10"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF,21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"sendData","_lineNumber":"277","_columnNumber":"24","_msg":"    at sendData@/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"325",",_columnNumber":"17","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B,B91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer","_lineNumber":"251","_columnNumber":"9","_msg":"    at connectWithRetry/connectToPeer@/private/var/mobile/Contain,ers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_t,ests/testThaliNativeLayer.js","_functionName":"connectWithRetry/connectToPeer/</<","_lineNumber":"260","_columnNumber":"45","_msg":"    at connectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21,602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45"},{"_fileName":"timers.js","_functionName":"listOnTimeout","_lineNumber":"112","_columnNumber":"9","_msg":"    at listOnTimeout@timers.js:112:9"},{"_fileName":"net.js","_functionName":"u,nknown","_lineNumber":835,"_columnNumber":10,"_msg":"    at "}]
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
  { _fileName: 'net.js',
    _functionName: 'exports.createConnection',
    _lineNumber: '72',
    _columnNumber: '10',
    _msg: '    at exports.createConnection@net.js:72:10' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/4BB91B72-905,5-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'sendData',
    _lineNumber: '277',
    _columnNumber: '24',
    _msg: '    at sendData@/private/var/mobile/Containers/Bundle/Application/4BB91B72-9,055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:277:24' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.j,s',
    _functionName: '',
    _lineNumber: '325',
    _columnNumber: '17',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:325:17' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer',
    _lineNumber: '251',
    _columnNu,mber: '9',
    _msg: '    at connectWithRetry/connectToPeer@/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:251:9' },
  { _fileName: '/private/var/mobile/Con,tainers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: 'connectWithRetry/connectToPeer/</<',
    _lineNumber: '260',
    _columnNumber: '45',
    _msg: '    at connectWithRetry/connectToPeer/</<@/private/var/mobile/Containers/Bundle/Application/4BB91B72-9055-4C6E-A62F-C620AF21602A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:260:45' },
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
2015-12-08 03:58:30.347 ThaliTest[405:210918] Error!: connect EADDRNOTAVAIL
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg"
```
