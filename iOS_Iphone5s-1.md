#### Test 506502785032ad1_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/7B435501-3194-482D-B5E2-4B5B07C43338/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7B435501-3194-482D-B5E2-4B5B07C43338/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785032ad1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4D2237CA-5544-4CDD-8F6F-976262E5CEA2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50472"
,(lldb)     command script import "/tmp/7B435501-3194-482D-B5E2-4B5B07C43338/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 03:55:07.445 ThaliTest[431:219189] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/753DFE48-7B89-4D25-8479-F09E4FF0C313/Library/Cookies/Cookies.binarycookies
,2015-12-08 03:55:07.837 ThaliTest[431:219189] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 03:55:07.838 ThaliTest[431:219189] Multi-tasking -> Device: YES, App: YES
,2015-12-08 03:55:07.849 ThaliTest[431:219189] Unlimited access to network resources
,2015-12-08 03:55:07.862 ThaliTest[431:219189] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 03:55:16.986 ThaliTest[431:219189] Resetting plugins due to page load.
,2015-12-08 03:55:20.991 ThaliTest[431:219189] Finished load of: file:///var/mobile/Containers/Bundle/Application/4D2237CA-5544-4CDD-8F6F-976262E5CEA2/ThaliTest.app/www/index.html
,2015-12-08 03:55:21.210 ThaliTest[431:219189] JXcore Cordova plugin initializing
,2015-12-08 03:55:21.212 ThaliTest[431:219404] JXcore instance initializing
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
,2015-12-08 03:56:43.812 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:44.061 ThaliTest[431:219404] server: starting 1449543403811.431.SOHjeg==
,2015-12-08 03:56:44.062 ThaliTest[431:219404] multipeer session: start timer: 0x187b7590
2015-12-08 03:56:44.063 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543403811.431
2015-12-08 03:56:44.064 ThaliTest[431:219404] jxcore: startBroad,casting: success
ok 45 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.068 ThaliTest[431:219404] jxcore: stopBroadcasting
2015-12-08 03:56:44.069 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.070 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:56:44.071 ThaliTest[431:219404] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2015-12-08 03:56:44.076 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:44.085 ThaliTest[431:219404] server: starting 1449543404076.431.5Y6DjA==
2015-12-08 03:56:44.086 ThaliTest[431:219404] multipeer session: start timer: 0x1a0d9180
2015-12-08 03:56:44.086 ThaliTest[431:219404] THEMultipeerSession initializ,ed peer 1449543404076.431
2015-12-08 03:56:44.087 ThaliTest[431:219404] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.118 ThaliTest[431:219404] jxcore: stopBroadcasting
,2015-12-08 03:56:44.120 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.122 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:56:44.128 ThaliTest[431:219404] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.146 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:44.149 ThaliTest[431:219404] server: starting 1449543404145.431.2pVfeA==
,2015-12-08 03:56:44.152 ThaliTest[431:219404] multipeer session: start timer: 0x1a0d7630
,2015-12-08 03:56:44.155 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543404145.431
,2015-12-08 03:56:44.156 ThaliTest[431:219404] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.159 ThaliTest[431:219404] jxcore: stopBroadcasting
,2015-12-08 03:56:44.160 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.160 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:56:44.162 ThaliTest[431:219404] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.165 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:44.168 ThaliTest[431:219404] server: starting 1449543404165.431.fCTYrg==
,2015-12-08 03:56:44.169 ThaliTest[431:219404] multipeer session: start timer: 0x187bc470
,2015-12-08 03:56:44.171 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543404165.431
,2015-12-08 03:56:44.172 ThaliTest[431:219404] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.174 ThaliTest[431:219404] jxcore: stopBroadcasting
,2015-12-08 03:56:44.175 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.175 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:56:44.178 ThaliTest[431:219404] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.180 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:44.182 ThaliTest[431:219404] server: starting 1449543404180.431.T2r2xA==
,2015-12-08 03:56:44.184 ThaliTest[431:219404] multipeer session: start timer: 0x1a0da190
,2015-12-08 03:56:44.186 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543404180.431
,2015-12-08 03:56:44.187 ThaliTest[431:219404] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.188 ThaliTest[431:219404] jxcore: stopBroadcasting
,2015-12-08 03:56:44.189 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.189 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:56:44.190 ThaliTest[431:219404] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.193 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:44.195 ThaliTest[431:219404] server: starting 1449543404193.431.pdu6QQ==
,2015-12-08 03:56:44.197 ThaliTest[431:219404] multipeer session: start timer: 0x187bcc20
,2015-12-08 03:56:44.198 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543404193.431
,2015-12-08 03:56:44.199 ThaliTest[431:219404] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.201 ThaliTest[431:219404] jxcore: stopBroadcasting
,2015-12-08 03:56:44.202 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.202 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:56:44.203 ThaliTest[431:219404] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.206 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:44.208 ThaliTest[431:219404] server: starting 1449543404206.431.JMdNBw==
,2015-12-08 03:56:44.209 ThaliTest[431:219404] multipeer session: start timer: 0x1a0dc590
,2015-12-08 03:56:44.210 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543404206.431
,2015-12-08 03:56:44.212 ThaliTest[431:219404] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.213 ThaliTest[431:219404] jxcore: stopBroadcasting
,2015-12-08 03:56:44.214 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.214 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:56:44.216 ThaliTest[431:219404] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.218 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:44.220 ThaliTest[431:219404] server: starting 1449543404218.431.1IVmbg==
,2015-12-08 03:56:44.221 ThaliTest[431:219404] multipeer session: start timer: 0x1a0dd140
,2015-12-08 03:56:44.222 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543404218.431
,2015-12-08 03:56:44.223 ThaliTest[431:219404] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-08 03:56:44.225 ThaliTest[431:219404] jxcore: stopBroadcasting
,2015-12-08 03:56:44.225 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:56:44.225 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:56:44.228 ThaliTest[431:219404] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-08 03:56:44.229 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:44.231 ThaliTest[431:219404] server: starting 1449543404229.431.3y37hg==
2015-12-08 03:56:44.231 ThaliTest[431:219404] multipeer session: start timer: 0x187bf500
2015-12-08 03:56:44.231 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543404229.431
2015-12-08 03:56:44.232 ThaliTest[431:219404] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2015-12-08 03:56:44.232 ThaliTest[431:219404] jxcore: stopBroadcasting
2015-12-08 03,:56:44.233 ThaliTest[431:219404] THEMultipeerSession stopping peer
2015-12-08 03:56:44.233 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:56:44.233 ThaliTest[431:219404] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
2015-12-08 03:56:44.234 ThaliTest[431:219404] jxcore: startBroadcasting
2015-12-08 03:56:44.236 ThaliTest[431:219404] server: starting 1449543404234.431.cqyYcw==
,2015-12-08 03:56:44.237 ThaliTest[431:219404] multipeer session: start timer: 0x1a0de870
2015-12-08 03:56:44.237 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543404234.431
2015-12-08 03:56:44.237 ThaliTest[431:219404] jxcore: startBroad,casting: success
ok 63 Should be able to call startBroadcasting without error
2015-12-08 03:56:44.239 ThaliTest[431:219404] jxcore: stopBroadcasting
2015-12-08 03:56:44.239 ThaliTest[431:219404] THEMultipeerSession stopping peer
2015-12-08 03:56:44.239, ThaliTest[431:219404] multipeer session: stop timer
2015-12-08 03:56:44.239 ThaliTest[431:219404] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-08 03:56:46.110 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:46.114 ThaliTest[431:219404] server: starting 1449543406110.431.Oxwuew==
2015-12-08 03:56:46.115 ThaliTest[431:219404] multipeer session: start timer: 0x1a0decc0
2015-12-08 03:56:46.116 ThaliTest[431:219404] THEMultipeerSession initializ,ed peer 1449543406110.431
2015-12-08 03:56:46.116 ThaliTest[431:219404] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2015-12-08 03:56:46.121 ThaliTest[431:219404] jxcore: startBroadcasting
2015-12-08 03:56:46.121 ThaliTest[431:219404] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2015-12-08 03:56:46.124 ThaliTest[431:219404] jxcore: stop,Broadcasting
2015-12-08 03:56:46.125 ThaliTest[431:219404] THEMultipeerSession stopping peer
2015-12-08 03:56:46.125 ThaliTest[431:219404] multipeer session: stop timer
2015-12-08 03:56:46.125 ThaliTest[431:219404] jxcore: stopBroadcasting: success
ok ,67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-08 03:56:53.651 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:53.655 ThaliTest[431:219404] server: starting 1449543413650.431.7RfI9g==
2015-12-08 03:56:53.656 ThaliTest[431:219404] multipeer session: start timer: 0x1a0e30b0
2015-12-08 03:56:53.656 ThaliTest[431:219404] THEMultipeerSession initializ,ed peer 1449543413650.431
2015-12-08 03:56:53.657 ThaliTest[431:219404] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-08 03:56:53.659 ThaliTest[431:219404] jxcore: connect foobar
2015-12-08 03:5,6:53.660 ThaliTest[431:219404] client: unknown peer foobar
2015-12-08 03:56:53.660 ThaliTest[431:219404] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2015-12-08 03:56:53.663 ThaliTest[431:219404] jxcore: stopBroadcasting
2015-12-08 03:56:53.664 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:56:53.666 ThaliTest[431:219404] multipeer session: stop timer
2015-12-08 03:56:53.667 ThaliTest[431:219404] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-08 03:56:58.653 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:56:58.657 ThaliTest[431:219404] server: starting 1449543418652.431.h69rDA==
2015-12-08 03:56:58.657 ThaliTest[431:219404] multipeer session: start timer: 0x187c55d0
2015-12-08 03:56:58.658 ThaliTest[431:219404] THEMultipeerSession initializ,ed peer 1449543418652.431
2015-12-08 03:56:58.658 ThaliTest[431:219404] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
,2015-12-08 03:56:58.665 ThaliTest[431:219404] jxcore: disconnect
,2015-12-08 03:56:58.680 ThaliTest[431:219404] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2015-12-08 03:56:58.687 ThaliTest[431:219404] jxcore: stopBroadcasting
,2015-12-08 03:56:58.688 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:56:58.691 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:56:58.699 ThaliTest[431:219404] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-08 03:57:01.594 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:57:01.598 ThaliTest[431:219404] server: starting 1449543421593.431.+h1/ug==
2015-12-08 03:57:01.599 ThaliTest[431:219404] multipeer session: start timer: 0x1a0ea180
2015-12-08 03:57:01.599 ThaliTest[431:219404] THEMultipeerSession initializ,ed peer 1449543421593.431
2015-12-08 03:57:01.600 ThaliTest[431:219404] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2015-12-08 03:57:03.140 ThaliTest[431:219189] client: found peer: 1449543421260.391.hpKQLw==
2015-12-08 03:57:03.141 ThaliTest[431:219189] client: found peer: 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:03.144 ThaliTest[431:219404] jxcore: connect 1449543421260.391.hpKQLw==
2015-12-08 03:57:03.145 ThaliTest[431:219404] client session: connect
2015-12-08 03:57:03.146 ThaliTest[431:219404] client session: stateChange:0->1 1449543421260.391.hpKQLw==
,2015-12-08 03:57:03.165 ThaliTest[431:219404] jxcore: connect 1449543422873.405.4eQM3Q==
2015-12-08 03:57:03.166 ThaliTest[431:219404] client session: connect
2015-12-08 03:57:03.166 ThaliTest[431:219404] client session: stateChange:0->1 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:04.281 ThaliTest[431:219189] client: found peer: 1449543421775.439.IbqVaQ==
2015-12-08 03:57:04.283 ThaliTest[431:219404] jxcore: connect 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:04.284 ThaliTest[431:219404] client session: connect
,2015-12-08 03:57:04.284 ThaliTest[431:219404] client session: stateChange:0->1 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:05.453 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:57:05.453 ThaliTest[431:219189] multipeer session: stop timer
2015-12-08 03:57:05.453 ThaliTest[431:219189] multipeer session: start timer: 0x1a0ea180
2015-12-08 03:57:05.454 ThaliTest[431:219189] server session: connect
,2015-12-08 03:57:05.454 ThaliTest[431:219189] server session: stateChange:0->1 1449543421775.439
,2015-12-08 03:57:05.462 ThaliTest[431:219189] server: accepting invitation 1449543421775.439
,2015-12-08 03:57:05.471 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:57:05.471 ThaliTest[431:219189] multipeer session: stop timer
2015-12-08 03:57:05.472 ThaliTest[431:219189] multipeer session: start timer: 0x1a0ea180
,2015-12-08 03:57:05.472 ThaliTest[431:219189] server session: connect
,2015-12-08 03:57:05.473 ThaliTest[431:219189] server session: stateChange:0->1 1449543422873.405
,2015-12-08 03:57:05.502 ThaliTest[431:219189] server: accepting invitation 1449543422873.405
,2015-12-08 03:57:05.741 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:57:05.741 ThaliTest[431:219189] multipeer session: stop timer
2015-12-08 03:57:05.741 ThaliTest[431:219189] multipeer session: start timer: 0x1a0ea180
,2015-12-08 03:57:05.741 ThaliTest[431:219189] server session: connect
,2015-12-08 03:57:05.742 ThaliTest[431:219189] server session: stateChange:0->1 1449543421260.391
,2015-12-08 03:57:05.752 ThaliTest[431:219189] server: accepting invitation 1449543421260.391
,2015-12-08 03:57:08.083 ThaliTest[431:219674] client session: connected
2015-12-08 03:57:08.084 ThaliTest[431:219674] client session: stateChange:1->2 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:08.095 ThaliTest[431:219659] client session: fireConnectCallback: 1449543422873.405.4eQM3Q==
2015-12-08 03:57:08.096 ThaliTest[431:219659] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-08 03:57:08.103 ThaliTest[431:219404] jxcore: disconnect
2015-12-08 03:57:08.104 ThaliTest[431:219404] client session: disconnectFromPeer: 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:08.104 ThaliTest[431:219404] client session: disconnect
,2015-12-08 03:57:08.104 ThaliTest[431:219404] client session: stateChange:2->0 1449543422873.405.4eQM3Q==
,2015-12-08 03:57:08.198 ThaliTest[431:219404] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,2015-12-08 03:57:08.500 ThaliTest[431:219676] client session: connected
2015-12-08 03:57:08.500 ThaliTest[431:219676] client session: stateChange:1->2 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:08.517 ThaliTest[431:219563] client session: fireConnectCallback: 1449543421775.439.IbqVaQ==
2015-12-08 03:57:08.517 ThaliTest[431:219563] jxcore: connect: success
ok 78 Should be able to connect without error
,ok 79 Port should be within range
,2015-12-08 03:57:08.522 ThaliTest[431:219404] jxcore: disconnect
,2015-12-08 03:57:08.523 ThaliTest[431:219404] client session: disconnectFromPeer: 1449543421775.439.IbqVaQ==
2015-12-08 03:57:08.524 ThaliTest[431:219404] client session: disconnect
2015-12-08 03:57:08.525 ThaliTest[431:219404] client session: stateChange:2->0 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:08.610 ThaliTest[431:219404] jxcore: disconnect: success
ok 80 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,not ok 81 .end() called twice
,  ---
,    operator: fail
,  ...
,2015-12-08 03:57:08.852 ThaliTest[431:219676] client session: connected
2015-12-08 03:57:08.853 ThaliTest[431:219676] client session: stateChange:1->2 1449543421260.391.hpKQLw==
,2015-12-08 03:57:08.904 ThaliTest[431:219676] client session: fireConnectCallback: 1449543421260.391.hpKQLw==
2015-12-08 03:57:08.906 ThaliTest[431:219676] jxcore: connect: success
ok 82 Should be able to connect without error
ok 83 Port should be withi,n range
2015-12-08 03:57:08.910 ThaliTest[431:219404] jxcore: disconnect
2015-12-08 03:57:08.910 ThaliTest[431:219404] client session: disconnectFromPeer: 1449543421260.391.hpKQLw==
2015-12-08 03:57:08.911 ThaliTest[431:219404] client session: disconnec,t
2015-12-08 03:57:08.911 ThaliTest[431:219404] client session: stateChange:2->0 1449543421260.391.hpKQLw==
,2015-12-08 03:57:08.932 ThaliTest[431:219404] jxcore: disconnect: success
ok 84 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,not ok 85 .end() called twice
  ---
    operator: fail
  ...
,2015-12-08 03:57:08.997 ThaliTest[431:219563] server session: connected
2015-12-08 03:57:08.997 ThaliTest[431:219563] server session: stateChange:1->2 1449543421775.439
,2015-12-08 03:57:09.001 ThaliTest[431:219189] server relay: socket disconnected
2015-12-08 03:57:09.001 ThaliTest[431:219189] server relay: 0x1a0f0320 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:09.025 ThaliTest[431:219659] server session: connected
2015-12-08 03:57:09.026 ThaliTest[431:219659] server session: stateChange:1->2 1449543422873.405
,2015-12-08 03:57:09.031 ThaliTest[431:219189] server relay: socket disconnected
2015-12-08 03:57:09.032 ThaliTest[431:219189] server relay: 0x187cf740 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:09.119 ThaliTest[431:219675] server session: not connected 1449543421775.439
,2015-12-08 03:57:09.146 ThaliTest[431:219659] server session: not connected 1449543422873.405
,2015-12-08 03:57:09.492 ThaliTest[431:219675] server session: connected
2015-12-08 03:57:09.492 ThaliTest[431:219675] server session: stateChange:1->2 1449543421260.391
,2015-12-08 03:57:09.525 ThaliTest[431:219189] server relay: socket disconnected
,2015-12-08 03:57:09.526 ThaliTest[431:219189] server relay: 0x187d3660 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:09.542 ThaliTest[431:219674] server session: not connected 1449543421260.391
,2015-12-08 03:57:12.603 ThaliTest[431:219189] client: lost peer: 1449543421775.439.IbqVaQ==
2015-12-08 03:57:12.603 ThaliTest[431:219189] client session: onPeerLost: 1449543421775.439.IbqVaQ==
,2015-12-08 03:57:12.632 ThaliTest[431:219189] client: lost peer: 1449543422873.405.4eQM3Q==
2015-12-08 03:57:12.632 ThaliTest[431:219189] client session: onPeerLost: 1449543422873.405.4eQM3Q==
,calling stopBroadcasting
,2015-12-08 03:57:16.081 ThaliTest[431:219404] jxcore: stopBroadcasting
2015-12-08 03:57:16.081 ThaliTest[431:219404] THEMultipeerSession stopping peer
2015-12-08 03:57:16.081 ThaliTest[431:219404] multipeer session: stop timer
2015-12-08 03:57:16.083 Th,aliTest[431:219404] server session: disconnect
2015-12-08 03:57:16.083 ThaliTest[431:219404] server session: stateChange:2->0 1449543422873.405
2015-12-08 03:57:16.084 ThaliTest[431:219404] server session: disconnect
2015-12-08 03:57:16.085 ThaliTest[43,1:219404] server session: stateChange:2->0 1449543421775.439
2015-12-08 03:57:16.086 ThaliTest[431:219404] server session: disconnect
,2015-12-08 03:57:16.086 ThaliTest[431:219404] server session: stateChange:2->0 1449543421260.391
,2015-12-08 03:57:16.095 ThaliTest[431:219404] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-08 03:57:25.467 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:57:25.471 ThaliTest[431:219404] server: starting 1449543445467.431.nUNHmA==
2015-12-08 03:57:25.472 ThaliTest[431:219404] multipeer session: start timer: 0x187cdce0
2015-12-08 03:57:25.473 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543445467.431
2015-12-08 03:57:25.473 ThaliTest[431:219404] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error
,2015-12-08 03:57:25.499 ThaliTest[431:219189] client: found peer: 1449543421260.391.hpKQLw==
2015-12-08 03:57:25.502 ThaliTest[431:219404] jxcore: connect 1449543421260.391.hpKQLw==
2015-12-08 03:57:25.503 ThaliTest[431:219404] client session: connect
2015-12-08 03:57:25.504 ThaliTest[431:219404] client session: stateChange:0->1 1449543421260.391.hpKQLw==
,2015-12-08 03:57:26.190 ThaliTest[431:219189] client: found peer: 1449543444583.391.Wxk+bw==
2015-12-08 03:57:26.192 ThaliTest[431:219404] jxcore: connect 1449543444583.391.Wxk+bw==
2015-12-08 03:57:26.193 ThaliTest[431:219404] client session: connect
2,015-12-08 03:57:26.194 ThaliTest[431:219404] client session: stateChange:0->1 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:26.318 ThaliTest[431:219189] client: found peer: 1449543446505.405.XRtx8Q==
2015-12-08 03:57:26.323 ThaliTest[431:219404] jxcore: connect 1449543446505.405.XRtx8Q==
2015-12-08 03:57:26.324 ThaliTest[431:219404] client session: connect
2,015-12-08 03:57:26.325 ThaliTest[431:219404] client session: stateChange:0->1 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:26.654 ThaliTest[431:219189] client: found peer: 1449543445470.439.9bQ4gA==
2015-12-08 03:57:26.662 ThaliTest[431:219404] jxcore: connect 1449543445470.439.9bQ4gA==
2015-12-08 03:57:26.663 ThaliTest[431:219404] client session: connect
2,015-12-08 03:57:26.663 ThaliTest[431:219404] client session: stateChange:0->1 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:26.840 ThaliTest[431:219189] multipeer session: reset timer
,2015-12-08 03:57:26.840 ThaliTest[431:219189] multipeer session: stop timer
,2015-12-08 03:57:26.841 ThaliTest[431:219189] multipeer session: start timer: 0x187cdce0
,2015-12-08 03:57:26.842 ThaliTest[431:219189] server session: connect
,2015-12-08 03:57:26.842 ThaliTest[431:219189] server session: stateChange:0->1 1449543446505.405
,2015-12-08 03:57:26.848 ThaliTest[431:219189] server: accepting invitation 1449543446505.405
,2015-12-08 03:57:26.853 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:57:26.855 ThaliTest[431:219189] multipeer session: stop timer
,2015-12-08 03:57:26.855 ThaliTest[431:219189] multipeer session: start timer: 0x187cdce0
,2015-12-08 03:57:26.856 ThaliTest[431:219189] server session: connect
,2015-12-08 03:57:26.857 ThaliTest[431:219189] server session: stateChange:0->1 1449543444583.391
,2015-12-08 03:57:26.866 ThaliTest[431:219189] server: accepting invitation 1449543444583.391
,2015-12-08 03:57:26.884 ThaliTest[431:219189] multipeer session: reset timer
,2015-12-08 03:57:26.885 ThaliTest[431:219189] multipeer session: stop timer
,2015-12-08 03:57:26.886 ThaliTest[431:219189] multipeer session: start timer: 0x187cdce0
,2015-12-08 03:57:26.887 ThaliTest[431:219189] server session: connect
,2015-12-08 03:57:26.888 ThaliTest[431:219189] server session: stateChange:0->1 1449543445470.439
,2015-12-08 03:57:26.904 ThaliTest[431:219189] server: accepting invitation 1449543445470.439
,2015-12-08 03:57:30.194 ThaliTest[431:219189] client: lost peer: 1449543421260.391.hpKQLw==
2015-12-08 03:57:30.205 ThaliTest[431:219189] client session: onPeerLost: 1449543421260.391.hpKQLw==
2015-12-08 03:57:30.205 ThaliTest[431:219189] client session:, onLinkFailure: 1449543421260.391.hpKQLw==
2015-12-08 03:57:30.206 ThaliTest[431:219189] client session: disconnect
2015-12-08 03:57:30.206 ThaliTest[431:219189] client session: stateChange:1->0 1449543421260.391.hpKQLw==
2015-12-08 03:57:30.206 ThaliTe,st[431:219189] client session: fireConnectCallback: 1449543421260.391.hpKQLw==
2015-12-08 03:57:30.207 ThaliTest[431:219189] jxcore: connect: fail: Peer disconnected
,2015-12-08 03:57:30.449 ThaliTest[431:219748] client session: connected
,2015-12-08 03:57:30.450 ThaliTest[431:219748] client session: stateChange:1->2 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:30.456 ThaliTest[431:219749] client session: connected
,2015-12-08 03:57:30.457 ThaliTest[431:219748] client session: fireConnectCallback: 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:30.457 ThaliTest[431:219749] client session: stateChange:1->2 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:30.458 ThaliTest[431:219748] jxcore: connect: success
,ok 87 Should be able to connect without error
,ok 88 Port should be within range
,2015-12-08 03:57:30.463 ThaliTest[431:219749] client session: fireConnectCallback: 1449543444583.391.Wxk+bw==
2015-12-08 03:57:30.463 ThaliTest[431:219404] jxcore: connect 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:30.464 ThaliTest[431:219749] jxcore: connect: success
2015-12-08 03:57:30.465 ThaliTest[431:219404] client: already connect(ing/ed) to 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:30.465 ThaliTest[431:219404] jxcore: connect: fail: Aleady connecting
,ok 89 Should fail on double connect
,2015-12-08 03:57:30.467 ThaliTest[431:219404] jxcore: disconnect
,2015-12-08 03:57:30.468 ThaliTest[431:219404] client session: disconnectFromPeer: 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:30.468 ThaliTest[431:219404] client session: disconnect
,2015-12-08 03:57:30.468 ThaliTest[431:219404] client session: stateChange:2->0 1449543446505.405.XRtx8Q==
,2015-12-08 03:57:30.531 ThaliTest[431:219404] jxcore: disconnect: success
ok 90 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,ok 91 Should be able to connect without error
,ok 92 Port should be within range
2015-12-08 03:57:30.535 ThaliTest[431:219404] jxcore: connect 1449543444583.391.Wxk+bw==
2015-12-08 03:57:30.536 ThaliTest[431:219404] client: already connect(ing/ed) to 1449543444583.391.Wxk+bw==
2015-12-08 03:57:30.536 ThaliTest[431:219404] jxcore: connect: fail: Aleady connecting
ok 93 Should fail on double connect
2015-12-08 03:57:30.537 ThaliTest[431:219404] jxcore: disconnect
,2015-12-08 03:57:30.537 ThaliTest[431:219404] client session: disconnectFromPeer: 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:30.538 ThaliTest[431:219404] client session: disconnect
2015-12-08 03:57:30.538 ThaliTest[431:219404] client session: stateChange:2->0 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:30.547 ThaliTest[431:219404] jxcore: disconnect: success
ok 94 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
not ok 95 .end() called twice
  ---
    operator: fail
  ...
,# setup
,2015-12-08 03:57:31.036 ThaliTest[431:219708] server session: connected
,2015-12-08 03:57:31.038 ThaliTest[431:219708] server session: stateChange:1->2 1449543446505.405
,2015-12-08 03:57:31.045 ThaliTest[431:219189] server relay: socket disconnected
,2015-12-08 03:57:31.046 ThaliTest[431:219189] server relay: 0x1a040f30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:31.072 ThaliTest[431:219708] server session: not connected 1449543446505.405
,2015-12-08 03:57:31.379 ThaliTest[431:219748] server session: connected
2015-12-08 03:57:31.379 ThaliTest[431:219748] server session: stateChange:1->2 1449543445470.439
,2015-12-08 03:57:31.383 ThaliTest[431:219708] client session: connected
2015-12-08 03:57:31.385 ThaliTest[431:219708] client session: stateChange:1->2 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.440 ThaliTest[431:219674] client session: fireConnectCallback: 1449543445470.439.9bQ4gA==
2015-12-08 03:57:31.441 ThaliTest[431:219674] jxcore: connect: success
ok 96 Should be able to connect without error
ok 97 Port should be within range
2015-12-08 03:57:31.444 ThaliTest[431:219404] jxcore: connect 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.445 ThaliTest[431:219404] client: already connect(ing/ed) to 1449543445470.439.9bQ4gA==
2015-12-08 03:57:31.445 ThaliTest[431:219404] jxcore: connect: fail: Aleady connecting
,ok 98 Should fail on double connect
2015-12-08 03:57:31.450 ThaliTest[431:219404] jxcore: disconnect
2015-12-08 03:57:31.450 ThaliTest[431:219404] client session: disconnectFromPeer: 1449543445470.439.9bQ4gA==
2015-12-08 03:57:31.450 ThaliTest[431:21940,4] client session: disconnect
2015-12-08 03:57:31.450 ThaliTest[431:219404] client session: stateChange:2->0 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:31.451 ThaliTest[431:219189] server relay: socket disconnected
2015-12-08 03:57:31.453 ThaliTest[431:219189] server relay: 0x1a0f5260 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:31.459 ThaliTest[431:219404] jxcore: disconnect: success
ok 99 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
not ok 100 .end() called twice
  ---
    operator: fail
  ...
,2015-12-08 03:57:31.478 ThaliTest[431:219708] server session: not connected 1449543445470.439
,2015-12-08 03:57:31.959 ThaliTest[431:219748] server session: connected
,2015-12-08 03:57:31.959 ThaliTest[431:219748] server session: stateChange:1->2 1449543444583.391
,2015-12-08 03:57:31.963 ThaliTest[431:219189] server relay: socket disconnected
,2015-12-08 03:57:31.964 ThaliTest[431:219189] server relay: 0x1a057750 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:57:32.082 ThaliTest[431:219749] server session: not connected 1449543444583.391
,calling stopBroadcasting
,2015-12-08 03:57:54.790 ThaliTest[431:219404] jxcore: stopBroadcasting
2015-12-08 03:57:54.791 ThaliTest[431:219404] THEMultipeerSession stopping peer
2015-12-08 03:57:54.791 ThaliTest[431:219404] multipeer session: stop timer
2015-12-08 03:57:54.792 Th,aliTest[431:219404] server session: disconnect
2015-12-08 03:57:54.792 ThaliTest[431:219404] server session: stateChange:2->0 1449543445470.439
2015-12-08 03:57:54.793 ThaliTest[431:219404] server session: disconnect
2015-12-08 03:57:54.794 ThaliTest[43,1:219404] server session: stateChange:2->0 1449543446505.405
,2015-12-08 03:57:54.800 ThaliTest[431:219404] server session: disconnect
2015-12-08 03:57:54.801 ThaliTest[431:219404] server session: stateChange:2->0 1449543444583.391
2015-12-08 03:57:54.808 ThaliTest[431:219404] jxcore: stopBroadcasting: success
sto,pBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-08 03:57:58.008 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:57:58.012 ThaliTest[431:219404] server: starting 1449543478008.431.8PN9MA==
2015-12-08 03:57:58.013 ThaliTest[431:219404] multipeer session: start timer: 0x1a0f0230
2015-12-08 03:57:58.013 ThaliTest[431:219404] THEMultipeerSession initialized peer 1449543478008.431
,2015-12-08 03:57:58.014 ThaliTest[431:219404] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error
,2015-12-08 03:57:58.049 ThaliTest[431:219189] client: found peer: 1449543444583.391.Wxk+bw==
2015-12-08 03:57:58.050 ThaliTest[431:219189] client: found peer: 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:58.062 ThaliTest[431:219404] jxcore: connect 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:58.065 ThaliTest[431:219404] client session: connect
,2015-12-08 03:57:58.067 ThaliTest[431:219404] client session: stateChange:0->1 1449543444583.391.Wxk+bw==
,2015-12-08 03:57:58.101 ThaliTest[431:219404] jxcore: connect 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:58.107 ThaliTest[431:219404] client session: connect
,2015-12-08 03:57:58.113 ThaliTest[431:219404] client session: stateChange:0->1 1449543445470.439.9bQ4gA==
,2015-12-08 03:57:58.704 ThaliTest[431:219189] client: found peer: 1449543477155.391.TQsX1A==
,2015-12-08 03:57:58.707 ThaliTest[431:219404] jxcore: connect 1449543477155.391.TQsX1A==
2015-12-08 03:57:58.708 ThaliTest[431:219404] client session: connect
2015-12-08 03:57:58.708 ThaliTest[431:219404] client session: stateChange:0->1 1449543477155.391.TQsX1A==
,2015-12-08 03:57:59.026 ThaliTest[431:219189] client: found peer: 1449543477671.439.01rxOw==
2015-12-08 03:57:59.028 ThaliTest[431:219404] jxcore: connect 1449543477671.439.01rxOw==
2015-12-08 03:57:59.029 ThaliTest[431:219404] client session: connect
2015-12-08 03:57:59.029 ThaliTest[431:219404] client session: stateChange:0->1 1449543477671.439.01rxOw==
,2015-12-08 03:57:59.285 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:57:59.286 ThaliTest[431:219189] multipeer session: stop timer
2015-12-08 03:57:59.286 ThaliTest[431:219189] multipeer session: start timer: 0x1a0f0230
2015-12-08 ,03:57:59.286 ThaliTest[431:219189] server session: connect
2015-12-08 03:57:59.287 ThaliTest[431:219189] server session: stateChange:0->1 1449543477671.439
,2015-12-08 03:57:59.301 ThaliTest[431:219189] server: accepting invitation 1449543477671.439
,2015-12-08 03:57:59.932 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:57:59.933 ThaliTest[431:219189] multipeer session: stop timer
2015-12-08 03:57:59.933 ThaliTest[431:219189] multipeer session: start timer: 0x1a0f0230
,2015-12-08 03:57:59.933 ThaliTest[431:219189] server session: connect
,2015-12-08 03:57:59.933 ThaliTest[431:219189] server session: stateChange:0->1 1449543480460.405
,2015-12-08 03:57:59.937 ThaliTest[431:219189] server: accepting invitation 1449543480460.405
,2015-12-08 03:58:00.325 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:58:00.325 ThaliTest[431:219189] multipeer session: stop timer
2015-12-08 03:58:00.325 ThaliTest[431:219189] multipeer session: start timer: 0x1a0f0230
2015-12-08 03:58:00.325 ThaliTest[431:219189] server session: connect
2015-12-08 03:58:00.325 ThaliTest[431:219189] server session: stateChange:0->1 1449543477155.391
2015-12-08 03:58:00.331 ThaliTest[431:219189] server: accepting invitation 1449543477155.391
,2015-12-08 03:58:00.461 ThaliTest[431:219189] client: found peer: 1449543480460.405.wRZudQ==
2015-12-08 03:58:00.462 ThaliTest[431:219404] jxcore: connect 1449543480460.405.wRZudQ==
2015-12-08 03:58:00.463 ThaliTest[431:219404] client session: connect
2015-12-08 03:58:00.463 ThaliTest[431:219404] client session: stateChange:0->1 1449543480460.405.wRZudQ==
,2015-12-08 03:58:02.334 ThaliTest[431:219863] client session: connected
2015-12-08 03:58:02.338 ThaliTest[431:219863] client session: stateChange:1->2 1449543477155.391.TQsX1A==
,2015-12-08 03:58:02.347 ThaliTest[431:219863] client session: fireConnectCallback: 1449543477155.391.TQsX1A==
,2015-12-08 03:58:02.351 ThaliTest[431:219863] jxcore: connect: success
,ok 102 Should be able to connect without error
,ok 103 Port should be within range
,2015-12-08 03:58:02.359 ThaliTest[431:219404] jxcore: disconnect
2015-12-08 03:58:02.359 ThaliTest[431:219404] client session: disconnectFromPeer: 1449543477155.391.TQsX1A==
2015-12-08 03:58:02.360 ThaliTest[431:219404] client session: disconnect
2015-1,2-08 03:58:02.360 ThaliTest[431:219404] client session: stateChange:2->0 1449543477155.391.TQsX1A==
,2015-12-08 03:58:02.381 ThaliTest[431:219404] jxcore: disconnect: success
ok 104 Should be able to disconnect without error
2015-12-08 03:58:02.384 ThaliTest[431:219404] jxcore: disconnect
2015-12-08 03:58:02.384 ThaliTest[431:219404] jxcore: disconnect,: fail
ok 105 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-08 03:58:02.750 ThaliTest[431:219863] server session: connected
2015-12-08 03:58:02.750 ThaliTest[431:219863] server session: stateChange:1->2 1449543477671.439
,2015-12-08 03:58:02.829 ThaliTest[431:219863] server session: not connected 1449543477671.439
,2015-12-08 03:58:03.153 ThaliTest[431:219862] server session: connected
2015-12-08 03:58:03.154 ThaliTest[431:219862] server session: stateChange:1->2 1449543480460.405
,2015-12-08 03:58:03.160 ThaliTest[431:219189] server relay: socket disconnected
,2015-12-08 03:58:03.160 ThaliTest[431:219189] server relay: 0x187e7720 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:58:03.179 ThaliTest[431:219862] client session: connected
2015-12-08 03:58:03.179 ThaliTest[431:219862] client session: stateChange:1->2 1449543477671.439.01rxOw==
,2015-12-08 03:58:03.189 ThaliTest[431:219862] client session: fireConnectCallback: 1449543477671.439.01rxOw==
2015-12-08 03:58:03.190 ThaliTest[431:219862] jxcore: connect: success
,ok 106 Should be able to connect without error
,ok 107 Port should be within range
,2015-12-08 03:58:03.198 ThaliTest[431:219404] jxcore: disconnect
2015-12-08 03:58:03.199 ThaliTest[431:219404] client session: disconnectFromPeer: 1449543477671.439.01rxOw==
,2015-12-08 03:58:03.199 ThaliTest[431:219404] client session: disconnect
,2015-12-08 03:58:03.200 ThaliTest[431:219404] client session: stateChange:2->0 1449543477671.439.01rxOw==
,2015-12-08 03:58:03.219 ThaliTest[431:219866] server session: not connected 1449543480460.405
,2015-12-08 03:58:03.293 ThaliTest[431:219404] jxcore: disconnect: success
,ok 108 Should be able to disconnect without error
,2015-12-08 03:58:03.296 ThaliTest[431:219404] jxcore: disconnect
,2015-12-08 03:58:03.297 ThaliTest[431:219404] jxcore: disconnect: fail
,ok 109 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,not ok 110 .end() called twice
  ---
,    operator: fail
,  ...
,2015-12-08 03:58:04.003 ThaliTest[431:219866] client session: connected
2015-12-08 03:58:04.003 ThaliTest[431:219866] client session: stateChange:1->2 1449543480460.405.wRZudQ==
,2015-12-08 03:58:04.056 ThaliTest[431:219862] client session: fireConnectCallback: 1449543480460.405.wRZudQ==
2015-12-08 03:58:04.057 ThaliTest[431:219862] jxcore: connect: success
,ok 111 Should be able to connect without error
,ok 112 Port should be within range
,2015-12-08 03:58:04.064 ThaliTest[431:219404] jxcore: disconnect
2015-12-08 03:58:04.065 ThaliTest[431:219404] client session: disconnectFromPeer: 1449543480460.405.wRZudQ==
2015-12-08 03:58:04.065 ThaliTest[431:219404] client session: disconnect
2015-1,2-08 03:58:04.066 ThaliTest[431:219404] client session: stateChange:2->0 1449543480460.405.wRZudQ==
,2015-12-08 03:58:04.084 ThaliTest[431:219404] jxcore: disconnect: success
ok 113 Should be able to disconnect without error
2015-12-08 03:58:04.086 ThaliTest[431:219404] jxcore: disconnect
2015-12-08 03:58:04.087 ThaliTest[431:219404] jxcore: disconnect,: fail
ok 114 Disconnect should fail 
setting stopBroadcasting callback and ending test.
not ok 115 .end() called twice
  ---
    operator: fail
  ...
,2015-12-08 03:58:04.506 ThaliTest[431:219866] server session: connected
,2015-12-08 03:58:04.507 ThaliTest[431:219866] server session: stateChange:1->2 1449543477155.391
,2015-12-08 03:58:04.517 ThaliTest[431:219189] server relay: socket disconnected
,2015-12-08 03:58:04.519 ThaliTest[431:219189] server relay: 0x187dc4b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-08 03:58:04.603 ThaliTest[431:219862] server session: not connected 1449543477155.391
,2015-12-08 03:58:06.143 ThaliTest[431:219189] client: lost peer: 1449543480460.405.wRZudQ==
2015-12-08 03:58:06.143 ThaliTest[431:219189] client session: onPeerLost: 1449543480460.405.wRZudQ==
,calling stopBroadcasting
,2015-12-08 03:58:06.390 ThaliTest[431:219404] jxcore: stopBroadcasting
2015-12-08 03:58:06.390 ThaliTest[431:219404] THEMultipeerSession stopping peer
,2015-12-08 03:58:06.392 ThaliTest[431:219404] multipeer session: stop timer
,2015-12-08 03:58:06.395 ThaliTest[431:219404] client session: disconnect
,2015-12-08 03:58:06.399 ThaliTest[431:219404] client session: stateChange:1->0 1449543444583.391.Wxk+bw==
,2015-12-08 03:58:06.405 ThaliTest[431:219404] client session: disconnect
,2015-12-08 03:58:06.410 ThaliTest[431:219404] client session: stateChange:1->0 1449543445470.439.9bQ4gA==
,2015-12-08 03:58:06.416 ThaliTest[431:219404] server session: disconnect
,2015-12-08 03:58:06.440 ThaliTest[431:219404] server session: stateChange:2->0 1449543480460.405
,2015-12-08 03:58:07.803 ThaliTest[431:219404] server session: disconnect
2015-12-08 03:58:07.804 ThaliTest[431:219404] server session: stateChange:2->0 1449543477155.391
2015-12-08 03:58:07.805 ThaliTest[431:219404] server session: disconnect
2015-12-08, 03:58:07.805 ThaliTest[431:219404] server session: stateChange:2->0 1449543477671.439
,2015-12-08 03:58:08.736 ThaliTest[431:219404] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-08 03:58:10.000 ThaliTest[431:219404] jxcore: startBroadcasting
,2015-12-08 03:58:10.004 ThaliTest[431:219404] server: starting 1449543489999.431.1e3a9w==
2015-12-08 03:58:10.006 ThaliTest[431:219404] multipeer session: start timer: 0x1a0474f0
2015-12-08 03:58:10.006 ThaliTest[431:219404] THEMultipeerSession initializ,ed peer 1449543489999.431
2015-12-08 03:58:10.007 ThaliTest[431:219404] jxcore: startBroadcasting: success
ok 116 Should be able to call startBroadcasting without error
echo server started
,2015-12-08 03:58:10.904 ThaliTest[431:219189] client: found peer: 1449543444583.391.Wxk+bw==
,[{"peerIdentifier":"1449543444583.391.Wxk+bw==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 03:58:10.910 ThaliTest[431:219404] jxcore: connect 1449543444583.391.Wxk+bw==
2015-12-08 03:58:10.910 ThaliTest[431:219404] client session: connect
2015-12-08 03:58:10.911 ThaliTest[431:219404] client session: stateChange:0->1 1449543444583.391.Wxk+bw==
,2015-12-08 03:58:11.375 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:58:11.375 ThaliTest[431:219189] multipeer session: stop timer
2015-12-08 03:58:11.375 ThaliTest[431:219189] multipeer session: start timer: 0x1a0474f0
2015-12-08 ,03:58:11.376 ThaliTest[431:219189] server session: connect
2015-12-08 03:58:11.376 ThaliTest[431:219189] server session: stateChange:0->1 1449543490182.439
,2015-12-08 03:58:11.388 ThaliTest[431:219189] server: accepting invitation 1449543490182.439
,2015-12-08 03:58:11.481 ThaliTest[431:219189] client: found peer: 1449543490182.439.HczcmQ==
[{"peerIdentifier":"1449543490182.439.HczcmQ==","peerName":"(null)","peerAvailable":true}]
2015-12-08 03:58:11.485 ThaliTest[431:219404] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:11.485 ThaliTest[431:219404] client session: connect
2015-12-08 03:58:11.486 ThaliTest[431:219404] client session: stateChange:0->1 1449543490182.439.HczcmQ==
2015-12-08 03:58:11.494 ThaliTest[431:219189] client: foun,d peer: 1449543491366.405.MuCjBg==
2015-12-08 03:58:11.506 ThaliTest[431:219189] client: found peer: 1449543489757.391.iXbQJw==
[{"peerIdentifier":"1449543491366.405.MuCjBg==","peerName":"(null)","peerAvailable":true}]
2015-12-08 03:58:11.518 ThaliTest[431:219404] jxcore: connect 1449543491366.405.MuCjBg==
,2015-12-08 03:58:11.518 ThaliTest[431:219404] client session: connect
2015-12-08 03:58:11.532 ThaliTest[431:219404] client session: stateChange:0->1 1449543491366.405.MuCjBg==
,[{"peerIdentifier":"1449543489757.391.iXbQJw==","peerName":"(null)","peerAvailable":true}]
2015-12-08 03:58:11.577 ThaliTest[431:219404] jxcore: connect 1449543489757.391.iXbQJw==
2015-12-08 03:58:11.578 ThaliTest[431:219404] client session: connect
2015-12-08 03:58:11.578 ThaliTest[431:219404] client session: stateChange:0->1 1449543489757.391.iXbQJw==
,2015-12-08 03:58:11.791 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:58:11.791 ThaliTest[431:219189] multipeer session: stop timer
2015-12-08 03:58:11.791 ThaliTest[431:219189] multipeer session: start timer: 0x1a0474f0
2015-12-08 03:58:11.791 ThaliTest[431:219189] server session: connect
2015-12-08 03:58:11.791 ThaliTest[431:219189] server session: stateChange:0->1 1449543491366.405
,2015-12-08 03:58:11.798 ThaliTest[431:219189] server: accepting invitation 1449543491366.405
,2015-12-08 03:58:11.803 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:58:11.803 ThaliTest[431:219189] multipeer session: stop timer
2015-12-08 03:58:11.803 ThaliTest[431:219189] multipeer session: start timer: 0x1a0474f0
2015-12-08 03:58:11.804 ThaliTest[431:219189] server session: connect
2015-12-08 03:58:11.804 ThaliTest[431:219189] server session: stateChange:0->1 1449543489757.391
2015-12-08 03:58:11.813 ThaliTest[431:219189] server: accepting invitation 1449543489757.391
,2015-12-08 03:58:14.943 ThaliTest[431:219866] client session: connected
2015-12-08 03:58:14.944 ThaliTest[431:219866] client session: stateChange:1->2 1449543491366.405.MuCjBg==
,2015-12-08 03:58:15.037 ThaliTest[431:219953] server session: connected
,2015-12-08 03:58:15.038 ThaliTest[431:219953] server session: stateChange:1->2 1449543491366.405
,2015-12-08 03:58:15.048 ThaliTest[431:219862] client session: fireConnectCallback: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:15.051 ThaliTest[431:219862] jxcore: connect: success
,ok 117 Should be able to connect without error
,ok 118 Port should be within range
,ok 119 First connect should succeed
,2015-12-08 03:58:15.108 ThaliTest[431:219189] client: relay established
,2015-12-08 03:58:15.111 ThaliTest[431:219189] client: new accepted socket: 0x1a025880
,2015-12-08 03:58:15.127 ThaliTest[431:219189] server relay: connected (to port: 5001)
,2015-12-08 03:58:15.144 ThaliTest[431:219862] server session: connected
,2015-12-08 03:58:15.145 ThaliTest[431:219862] server session: stateChange:1->2 1449543490182.439
,ok 120 the test messages should be equal
,ok 121 First send should succeed
,2015-12-08 03:58:15.178 ThaliTest[431:219189] client: socket closed
2015-12-08 03:58:15.178 ThaliTest[431:219189] client relay: socket disconnected
,2015-12-08 03:58:15.178 ThaliTest[431:219189] client relay: 0x1a025880 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:15,.179 ThaliTest[431:219189] client session: socket closed: 1449543491366.405.MuCjBg==
2015-12-08 03:58:15.179 ThaliTest[431:219189] client session: onLinkFailure: 1449543491366.405.MuCjBg==
2015-12-08 03:58:15.179 ThaliTest[431:219189] client session: disconnect
,2015-12-08 03:58:15.180 ThaliTest[431:219189] client session: stateChange:2->0 1449543491366.405.MuCjBg==
,2015-12-08 03:58:15.209 ThaliTest[431:219866] server session: not connected 1449543491366.405
,2015-12-08 03:58:15.219 ThaliTest[431:219189] client session: fireConnectionErrorEvent: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:15.223 ThaliTest[431:219404] jxcore: connect 1449543491366.405.MuCjBg==
,2015-12-08 03:58:15.225 ThaliTest[431:219404] client session: connect
,2015-12-08 03:58:15.230 ThaliTest[431:219404] client session: stateChange:0->1 1449543491366.405.MuCjBg==
,2015-12-08 03:58:15.312 ThaliTest[431:219189] multipeer session: reset timer
,2015-12-08 03:58:15.314 ThaliTest[431:219189] multipeer session: stop timer
,2015-12-08 03:58:15.314 ThaliTest[431:219189] multipeer session: start timer: 0x1a0474f0
,2015-12-08 03:58:15.315 ThaliTest[431:219189] server: disconnecting to refresh session (1449543491366.405)
,2015-12-08 03:58:15.316 ThaliTest[431:219189] server session: disconnect
,2015-12-08 03:58:15.317 ThaliTest[431:219189] server session: stateChange:2->0 1449543491366.405
,2015-12-08 03:58:15.323 ThaliTest[431:219189] server session: connect
,2015-12-08 03:58:15.324 ThaliTest[431:219189] server session: stateChange:0->1 1449543491366.405
,2015-12-08 03:58:15.341 ThaliTest[431:219189] server: accepting invitation 1449543491366.405
,2015-12-08 03:58:15.420 ThaliTest[431:219189] server relay: connected (to port: 5001)
,2015-12-08 03:58:15.522 ThaliTest[431:219960] client session: connected
,2015-12-08 03:58:15.523 ThaliTest[431:219960] client session: stateChange:1->2 1449543490182.439.HczcmQ==
,2015-12-08 03:58:15.976 ThaliTest[431:219960] client session: fireConnectCallback: 1449543490182.439.HczcmQ==
2015-12-08 03:58:15.976 ThaliTest[431:219960] jxcore: connect: success
,ok 122 Should be able to connect without error
ok 123 Port should be within range
ok 124 First connect should succeed
,2015-12-08 03:58:15.989 ThaliTest[431:219189] client: relay established
2015-12-08 03:58:15.990 ThaliTest[431:219189] client: new accepted socket: 0x1a031620
,ok 125 the test messages should be equal
,ok 126 First send should succeed
,2015-12-08 03:58:16.075 ThaliTest[431:219189] client: socket closed
2015-12-08 03:58:16.075 ThaliTest[431:219189] client relay: socket disconnected
,2015-12-08 03:58:16.075 ThaliTest[431:219189] client relay: 0x1a031620 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:16.075 ThaliTest[431:219189] client session: socket closed: 1449543490182.439.HczcmQ==
2015-12-08 03:58:16.075 ThaliTest[431:219189] client session: onLinkFailure: 1449543490182.439.HczcmQ==
2015-12-08 03:58:16.075 ThaliTest[431:219189] client session: dis,connect
,2015-12-08 03:58:16.075 ThaliTest[431:219189] client session: stateChange:2->0 1449543490182.439.HczcmQ==
,2015-12-08 03:58:16.086 ThaliTest[431:219189] client session: fireConnectionErrorEvent: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:16.090 ThaliTest[431:219404] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:16.091 ThaliTest[431:219404] client session: connect
,2015-12-08 03:58:16.091 ThaliTest[431:219404] client session: stateChange:0->1 1449543490182.439.HczcmQ==
,2015-12-08 03:58:16.110 ThaliTest[431:219404] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:16.111 ThaliTest[431:219404] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
,2015-12-08 03:58:16.111 ThaliTest[431:219404] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:16.627 ThaliTest[431:219866] server session: not connected 1449543490182.439
,2015-12-08 03:58:17.011 ThaliTest[431:219866] server session: connected
2015-12-08 03:58:17.012 ThaliTest[431:219866] server session: stateChange:1->2 1449543489757.391
,2015-12-08 03:58:17.128 ThaliTest[431:219404] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:17.129 ThaliTest[431:219404] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:17.129 ThaliTest[431:219404] jxcore: con,nect: fail: Aleady connecting
,2015-12-08 03:58:17.743 ThaliTest[431:219189] server relay: connected (to port: 5001)
,2015-12-08 03:58:18.091 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:58:18.091 ThaliTest[431:219189] multipeer session: stop timer
,2015-12-08 03:58:18.091 ThaliTest[431:219189] multipeer session: start timer: 0x1a0474f0
,2015-12-08 03:58:18.095 ThaliTest[431:219189] server: disconnecting to refresh session (1449543490182.439)
2015-12-08 03:58:18.096 ThaliTest[431:219189] server session: disconnect
,2015-12-08 03:58:18.097 ThaliTest[431:219189] server session: stateChange:2->0 1449543490182.439
,2015-12-08 03:58:18.112 ThaliTest[431:219189] server session: connect
,2015-12-08 03:58:18.112 ThaliTest[431:219189] server session: stateChange:0->1 1449543490182.439
,2015-12-08 03:58:18.136 ThaliTest[431:219404] jxcore: connect 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.139 ThaliTest[431:219404] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
,2015-12-08 03:58:18.140 ThaliTest[431:219404] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:18.159 ThaliTest[431:219189] server: accepting invitation 1449543490182.439
,2015-12-08 03:58:18.189 ThaliTest[431:219953] client session: connected
,2015-12-08 03:58:18.191 ThaliTest[431:219953] client session: stateChange:1->2 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.216 ThaliTest[431:219953] server session: not connected 1449543489757.391
,2015-12-08 03:58:18.390 ThaliTest[431:219866] client session: fireConnectCallback: 1449543489757.391.iXbQJw==
,2015-12-08 03:58:18.393 ThaliTest[431:219866] jxcore: connect: success
ok 127 Should be able to connect without error
ok 128 Port should be within range
ok 129 First connect should succeed
,2015-12-08 03:58:18.411 ThaliTest[431:219189] client: relay established
,2015-12-08 03:58:18.412 ThaliTest[431:219189] client: new accepted socket: 0x187f51b0
,2015-12-08 03:58:18.536 ThaliTest[431:219960] client session: connected
2015-12-08 03:58:18.536 ThaliTest[431:219960] client session: stateChange:1->2 1449543491366.405.MuCjBg==
,2015-12-08 03:58:18.545 ThaliTest[431:219866] server session: connected
2015-12-08 03:58:18.545 ThaliTest[431:219866] server session: stateChange:1->2 1449543491366.405
,2015-12-08 03:58:18.566 ThaliTest[431:219866] client session: fireConnectCallback: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:18.567 ThaliTest[431:219866] jxcore: connect: success
ok 130 Should be able to connect without error
,ok 131 Port should be within range
,ok 132 Second connect should succeed
,2015-12-08 03:58:18.580 ThaliTest[431:219189] client: relay established
2015-12-08 03:58:18.580 ThaliTest[431:219189] client: new accepted socket: 0x1875f190
,2015-12-08 03:58:18.645 ThaliTest[431:219189] server relay: connected (to port: 5001)
,ok 133 the test messages should be equal
,ok 134 Second send should succeed
,# setup
,2015-12-08 03:58:18.692 ThaliTest[431:219189] client: socket closed
2015-12-08 03:58:18.693 ThaliTest[431:219189] client relay: socket disconnected
2015-12-08 03:58:18.693 ThaliTest[431:219189] client relay: 0x1875f190 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:18.693 ThaliTest[431:219189] client session: socket closed: 1449543491366.405.MuCjBg==
2015-12-08 03:58:18.693 ThaliTest[431:219189] client session: onLinkFailure: 1449543491366.405.MuCjBg==
2015-12-08 03:58:18.693 ThaliTest[431:219189] client session: disconnect
2015-12-08 03:58:18.693 ThaliTest[431:219189] client session: stateChange:2->0 1449543491366.405.MuCjBg==
,2015-12-08 03:58:18.705 ThaliTest[431:219189] client session: fireConnectionErrorEvent: 1449543491366.405.MuCjBg==
,2015-12-08 03:58:18.728 ThaliTest[431:219866] server session: not connected 1449543491366.405
,2015-12-08 03:58:19.149 ThaliTest[431:219404] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:19.150 ThaliTest[431:219404] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:19.150 ThaliTest[431:219404] jxcore: con,nect: fail: Aleady connecting
,2015-12-08 03:58:19.508 ThaliTest[431:219189] multipeer session: reset timer
2015-12-08 03:58:19.509 ThaliTest[431:219189] multipeer session: stop timer
2015-12-08 03:58:19.509 ThaliTest[431:219189] multipeer session: start timer: 0x1a0474f0
2015-12-08 ,03:58:19.509 ThaliTest[431:219189] server: disconnecting to refresh session (1449543489757.391)
2015-12-08 03:58:19.510 ThaliTest[431:219189] server session: disconnect
2015-12-08 03:58:19.510 ThaliTest[431:219189] server session: stateChange:2->0 144954,3489757.391
,2015-12-08 03:58:19.584 ThaliTest[431:219189] server session: connect
2015-12-08 03:58:19.585 ThaliTest[431:219189] server session: stateChange:0->1 1449543489757.391
,2015-12-08 03:58:19.596 ThaliTest[431:219189] server: accepting invitation 1449543489757.391
,ok 135 the test messages should be equal
,ok 136 First send should succeed
,2015-12-08 03:58:20.117 ThaliTest[431:219189] client: socket closed
2015-12-08 03:58:20.117 ThaliTest[431:219189] client relay: socket disconnected
2015-12-08 03:58:20.118 ThaliTest[431:219189] client relay: 0x187f51b0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:20.118 ThaliTest[431:219189] client session: socket closed: 1449543489757.391.iXbQJw==
2015-12-08 03:58:20.,118 ThaliTest[431:219189] client session: onLinkFailure: 1449543489757.391.iXbQJw==
2015-12-08 03:58:20.118 ThaliTest[431:219189] client session: disconnect
2015-12-08 03:58:20.118 ThaliTest[431:219189] client session: stateChange:2->0 1449543489757.391.iXbQJw==
,2015-12-08 03:58:20.127 ThaliTest[431:219189] client session: fireConnectionErrorEvent: 1449543489757.391.iXbQJw==
,2015-12-08 03:58:20.155 ThaliTest[431:219404] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:20.155 ThaliTest[431:219404] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:20.155 ThaliTest[431:219404] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:21.164 ThaliTest[431:219404] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:21.165 ThaliTest[431:219404] client: already connect(ing/ed) to 1449543490182.439.HczcmQ==
2015-12-08 03:58:21.165 ThaliTest[431:219404] jxcore: connect: fail: Aleady connecting
,2015-12-08 03:58:21.272 ThaliTest[431:219867] client session: connected
,2015-12-08 03:58:21.276 ThaliTest[431:219867] client session: stateChange:1->2 1449543490182.439.HczcmQ==
,2015-12-08 03:58:21.301 ThaliTest[431:219863] client session: fireConnectCallback: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:21.301 ThaliTest[431:219863] jxcore: connect: success
,ok 137 Should be able to connect without error
,ok 138 Port should be within range
,ok 139 Second connect should succeed
,2015-12-08 03:58:21.344 ThaliTest[431:219189] client: relay established
2015-12-08 03:58:21.344 ThaliTest[431:219189] client: new accepted socket: 0x187f56b0
,ok 140 the test messages should be equal
,ok 141 Second send should succeed
,not ok 142 .end() called twice
  ---
,    operator: fail
,  ...
,2015-12-08 03:58:21.412 ThaliTest[431:219189] client: socket closed
,2015-12-08 03:58:21.412 ThaliTest[431:219189] client relay: socket disconnected
,2015-12-08 03:58:21.413 ThaliTest[431:219189] client relay: 0x187f56b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-08 03:58:21,.413 ThaliTest[431:219189] client session: socket closed: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:21.414 ThaliTest[431:219189] client session: onLinkFailure: 1449543490182.439.HczcmQ==
2015-12-08 03:58:21.414 ThaliTest[431:219189] client session: disconnect
2015-12-08 03:58:21.415 ThaliTest[431:219189] client session: stateChange:2->0 1449543490182.439.HczcmQ==
,2015-12-08 03:58:21.498 ThaliTest[431:219189] client session: fireConnectionErrorEvent: 1449543490182.439.HczcmQ==
,2015-12-08 03:58:21.736 ThaliTest[431:219863] server session: connected
,2015-12-08 03:58:21.736 ThaliTest[431:219863] server session: stateChange:1->2 1449543490182.439
,2015-12-08 03:58:21.772 ThaliTest[431:219189] server relay: connected (to port: 5001)
,2015-12-08 03:58:22.167 ThaliTest[431:219404] jxcore: connect 1449543490182.439.HczcmQ==
2015-12-08 03:58:22.168 ThaliTest[431:219404] client session: connect
2015-12-08 03:58:22.168 ThaliTest[431:219404] client session: stateChange:0->1 1449543490182.439.HczcmQ==
,2015-12-08 03:58:23.256 ThaliTest[431:219867] server session: not connected 1449543490182.439
,2015-12-08 03:58:23.676 ThaliTest[431:219863] server session: connected
2015-12-08 03:58:23.676 ThaliTest[431:219863] server session: stateChange:1->2 1449543489757.391
,2015-12-08 03:58:23.704 ThaliTest[431:219189] server relay: connected (to port: 5001)
,calling stopBroadcasting
,2015-12-08 03:58:23.712 ThaliTest[431:219404] jxcore: stopBroadcasting
2015-12-08 03:58:23.712 ThaliTest[431:219404] THEMultipeerSession stopping peer
2015-12-08 03:58:23.712 ThaliTest[431:219404] multipeer session: stop timer
2015-12-08 03:58:23.712 Th,aliTest[431:219404] client session: disconnect
2015-12-08 03:58:23.712 ThaliTest[431:219404] client session: stateChange:1->0 1449543444583.391.Wxk+bw==
2015-12-08 03:58:23.713 ThaliTest[431:219404] client session: disconnect
2015-12-08 03:58:23.713 ThaliTest[431:219404] client session: stateChange:1->0 1449543490182.439.HczcmQ==
2015-12-08 03:58:23.713 ThaliTest[431:219404] server session: disconnect
2015-12-08 03:58:23.714 ThaliTest[431:219404] server session: stateChange:2->0 1449543490182.439
,2015-12-08 03:58:24.627 ThaliTest[431:219404] server session: disconnect
2015-12-08 03:58:24.627 ThaliTest[431:219404] server session: stateChange:2->0 1449543489757.391
,2015-12-08 03:58:24.648 ThaliTest[431:219404] server session: disconnect
2015-12-08 03:58:24.648 ThaliTest[431:219404] server session: stateChange:2->0 1449543491366.405
,2015-12-08 03:58:24.658 ThaliTest[431:219404] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error

```
