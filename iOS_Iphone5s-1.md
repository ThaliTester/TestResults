#### Test 5590220275263c8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5590220275263c8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/2103640E-33D0-40D4-AB04-BE506D69FB8B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2103640E-33D0-40D4-AB04-BE506D69FB8B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5590220275263c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5590220275263c8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54983"
,(lldb)     command script import "/tmp/2103640E-33D0-40D4-AB04-BE506D69FB8B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-13 15:31:25.177 ThaliTest[1869:4226823] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C369F2A5-0F62-4088-9062-629364933655/Library/Cookies/Cookies.binarycookies
,2016-01-13 15:31:25.453 ThaliTest[1869:4226823] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-13 15:31:25.454 ThaliTest[1869:4226823] Multi-tasking -> Device: YES, App: YES
,2016-01-13 15:31:25.461 ThaliTest[1869:4226823] Unlimited access to network resources
,2016-01-13 15:31:25.471 ThaliTest[1869:4226823] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-13 15:31:29.756 ThaliTest[1869:4226823] Resetting plugins due to page load.
,2016-01-13 15:31:31.147 ThaliTest[1869:4226823] Finished load of: file:///var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/index.html
,2016-01-13 15:31:31.343 ThaliTest[1869:4226823] JXcore Cordova plugin initializing
,2016-01-13 15:31:31.345 ThaliTest[1869:4226985] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,My device name is: Apple-Iphone5s-1
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
ok 17 should be equal
ok 18 should be equal
# setup
,# #init should register the networkChanged event
,# teardown
,ok 19 should be equal
# setup
,# #startBroadcasting should throw on null device name
,# teardown
,ok 20 should throw
# setup
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
ok 28 should be equal
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
ok 30 should be equal
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
,ok 35 should be equal
# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
ok 37 should be equal
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
ok 42 should be equal
,# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
,ok 44 should be equal
# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-13 15:37:44.060 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:44.068 ThaliTest[1869:4226985] server: starting 1452695864060.1869.UK2jmQ==
2016-01-13 15:37:44.068 ThaliTest[1869:4226985] multipeer session: start timer: 0x194d7970
2016-01-13 15:37:44.069 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695864060.1869
2016-01-13 15:37:44.069 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-13 15:37:44.070 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2,016-01-13 15:37:44.070 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:37:44.072 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:37:44.072 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
ok 46 Should, be able to call stopBroadcasting without error
2016-01-13 15:37:44.073 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:44.075 ThaliTest[1869:4226985] server: starting 1452695864073.1869.YFhN+g==
2016-01-13 15:37:44.076 ThaliTest[1869:4226985] multipeer session: start timer: 0x17ebc140
2016-01-13 15:37:44.076 ThaliTest[1869:4226985] THEMultipeerSession in,itialized peer 1452695864073.1869
2016-01-13 15:37:44.076 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-13 15:37:44.077 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:37:44.077 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
,2016-01-13 15:37:44.077 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:37:44.086 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-13 15:37:44.087 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:44.094 ThaliTest[1869:4226985] server: starting 1452695864087.1869.1M1IjA==
,2016-01-13 15:37:44.099 ThaliTest[1869:4226985] multipeer session: start timer: 0x19460840
2016-01-13 15:37:44.099 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695864087.1869
2016-01-13 15:37:44.100 ThaliTest[1869:4226985] jxcore: sta,rtBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-13 15:37:44.101 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:37:44.101 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
,2016-01-13 15:37:44.101 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:37:44.104 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2016-01-13 15:37:44.105 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:44.111 ThaliTest[1869:4226985] server: starting 1452695864105.1869.kh+Q7w==
2016-01-13 15:37:44.114 ThaliTest[1869:4226985] multipeer session: start timer: 0x1954d3e0
2016-01-13 15:37:44.114 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695864105.1869
2016-01-13 15:37:44.114 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-13 15:37:44.116 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2,016-01-13 15:37:44.116 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:37:44.116 ThaliTest[1869:4226985] multipeer session: stop timer
,2016-01-13 15:37:44.116 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-13 15:37:44.122 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:44.126 ThaliTest[1869:4226985] server: starting 1452695864121.1869.T5wkgw==
,2016-01-13 15:37:44.127 ThaliTest[1869:4226985] multipeer session: start timer: 0x1953f2c0
2016-01-13 15:37:44.131 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695864121.1869
2016-01-13 15:37:44.131 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-13 15:37:44.132 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:37:44.132 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:37:44.132 ThaliTest[1869:4226985] multipeer session: stop timer
,2016-01-13 15:37:44.132 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
2016-01-13 15:37:44.136 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:44.149 ThaliTest[1869:4226985] server: starting 1452695864136.1869.+4trNA==
2016-01-13 15:37:44.150 ThaliTest[1869:4226985] multipeer session: start timer: 0x1953f2c0
2016-01-13 15:37:44.150 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695864136.1869
2016-01-13 15:37:44.150 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-13 15:37:44.151 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2,016-01-13 15:37:44.151 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:37:44.151 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:37:44.152 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
2016-01-13 15:37:44.153 ThaliTest[1869:4226985] jxcore: startBroadcasting
2016-01-13 15:37:44.155 ThaliTest[1869:4226985] server: starting 1452695864153.1869.3smFMA==
2016-01-13 15:37:44.155 ThaliTest[1869,:4226985] multipeer session: start timer: 0x19359f70
2016-01-13 15:37:44.162 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695864153.1869
2016-01-13 15:37:44.162 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2016-01-13 15:37:44.163 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:37:44.163 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:37:44.163 ThaliTest[1869:4226985] mu,ltipeer session: stop timer
2016-01-13 15:37:44.164 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
,2016-01-13 15:37:44.164 ThaliTest[1869:4226985] jxcore: startBroadcasting
2016-01-13 15:37:44.172 ThaliTest[1869:4226985] server: starting 1452695864164.1869.oJDcPA==
,2016-01-13 15:37:44.177 ThaliTest[1869:4226985] multipeer session: start timer: 0x194974a0
,2016-01-13 15:37:44.179 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695864164.1869
,2016-01-13 15:37:44.179 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2016-01-13 15:37:44.186 ThaliTest[1869:4226985] jxcore: stopBroadcasting
,2016-01-13 15:37:44.186 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
,2016-01-13 15:37:44.186 ThaliTest[1869:4226985] multipeer session: stop timer
,2016-01-13 15:37:44.187 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2016-01-13 15:37:44.192 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:44.194 ThaliTest[1869:4226985] server: starting 1452695864192.1869.VwHhfA==
,2016-01-13 15:37:44.195 ThaliTest[1869:4226985] multipeer session: start timer: 0x193b7ec0
,2016-01-13 15:37:44.196 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695864192.1869
2016-01-13 15:37:44.199 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-13 15:37:44.203 ThaliTest[1869:4226985] jxcore: stopBroadcasting
,2016-01-13 15:37:44.204 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
,2016-01-13 15:37:44.204 ThaliTest[1869:4226985] multipeer session: stop timer
,2016-01-13 15:37:44.205 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-13 15:37:44.209 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:44.212 ThaliTest[1869:4226985] server: starting 1452695864209.1869.F375bg==
,2016-01-13 15:37:44.213 ThaliTest[1869:4226985] multipeer session: start timer: 0x1947fac0
,2016-01-13 15:37:44.213 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695864209.1869
,2016-01-13 15:37:44.217 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-13 15:37:44.221 ThaliTest[1869:4226985] jxcore: stopBroadcasting
,2016-01-13 15:37:44.222 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
,2016-01-13 15:37:44.222 ThaliTest[1869:4226985] multipeer session: stop timer
,2016-01-13 15:37:44.223 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-13 15:37:46.496 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:46.498 ThaliTest[1869:4226985] server: starting 1452695866496.1869.DLzXwg==
2016-01-13 15:37:46.499 ThaliTest[1869:4226985] multipeer session: start timer: 0x194260d0
2016-01-13 15:37:46.499 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695866496.1869
2016-01-13 15:37:46.499 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-13 15:37:46.500 ThaliTest[1869:4226985] jxcore: startBroadcasting
2016-01-13 15:37:46.500 ThaliTest[1869:4226985] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2016-01-13 15:37:46.501 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:37:46.505 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:37:46.505 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:37:46.505 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-13 15:37:49.291 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:49.293 ThaliTest[1869:4226985] server: starting 1452695869290.1869.tVp3rA==
2016-01-13 15:37:49.293 ThaliTest[1869:4226985] multipeer session: start timer: 0x194bcf20
2016-01-13 15:37:49.293 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695869290.1869
2016-01-13 15:37:49.293 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-13 15:37:49.294 ThaliTest[1869:4226985] jxcore: connect foobar
2016-01-13 15:37:49.295 ThaliTest[1869:4226985] client: unknown peer foobar
,2016-01-13 15:37:49.295 ThaliTest[1869:4226985] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-13 15:37:49.299 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:37:49.299 ThaliTest[1869:4226985] THEMultip,eerSession stopping peer
2016-01-13 15:37:49.299 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:37:49.299 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
# setup,
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-13 15:37:51.082 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:51.084 ThaliTest[1869:4226985] server: starting 1452695871082.1869.6SwTuQ==
2016-01-13 15:37:51.084 ThaliTest[1869:4226985] multipeer session: start timer: 0x19404660
2016-01-13 15:37:51.085 ThaliTest[1869:4226985] THEMultipeerSession in,itialized peer 1452695871082.1869
2016-01-13 15:37:51.085 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-13 15:37:51.086 ThaliTest[1869:4226985] jxcore: disconnect
2016-01-13 15:37:51.086 ThaliTest[1869:4226985] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-13 15:37:51.087 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:37:51.091 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:37:51.091 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:37:51.091 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-13 15:37:52.260 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:52.262 ThaliTest[1869:4226985] server: starting 1452695872259.1869.zesqHQ==
2016-01-13 15:37:52.262 ThaliTest[1869:4226985] multipeer session: start timer: 0x192bb8e0
2016-01-13 15:37:52.262 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695872259.1869
2016-01-13 15:37:52.262 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-13 15:37:53.119 ThaliTest[1869:4226823] client: found peer: 1452695873445.1937.9y2Uag==
2016-01-13 15:37:53.120 ThaliTest[1869:4226985] jxcore: connect 1452695873445.1937.9y2Uag==
2016-01-13 15:37:53.121 ThaliTest[1869:4226985] client session: co,nnect
2016-01-13 15:37:53.121 ThaliTest[1869:4226985] client session: stateChange:0->1 1452695873445.1937.9y2Uag==
,2016-01-13 15:37:53.812 ThaliTest[1869:4226823] multipeer session: reset timer
2016-01-13 15:37:53.812 ThaliTest[1869:4226823] multipeer session: stop timer
2016-01-13 15:37:53.812 ThaliTest[1869:4226823] multipeer session: start timer: 0x192bb8e0
2016-,01-13 15:37:53.812 ThaliTest[1869:4226823] server session: connect
2016-01-13 15:37:53.813 ThaliTest[1869:4226823] server session: stateChange:0->1 1452695873445.1937
2016-01-13 15:37:53.817 ThaliTest[1869:4226823] server: accepting invitation 1452695873445.1937
,2016-01-13 15:37:57.729 ThaliTest[1869:4227926] server session: connected
,2016-01-13 15:37:57.729 ThaliTest[1869:4227926] server session: stateChange:1->2 1452695873445.1937
,2016-01-13 15:37:57.734 ThaliTest[1869:4226823] server relay: socket disconnected
2016-01-13 15:37:57.734 ThaliTest[1869:4226823] server relay: 0x191f1570 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 15:37:57.762 ThaliTest[1869:4227923] server session: not connected 1452695873445.1937
,2016-01-13 15:37:57.769 ThaliTest[1869:4227928] client session: connected
2016-01-13 15:37:57.769 ThaliTest[1869:4227928] client session: stateChange:1->2 1452695873445.1937.9y2Uag==
2016-01-13 15:37:57.772 ThaliTest[1869:4227928] client session: fireConnectCallback: 1452695873445.1937.9y2Uag==
2016-01-13 15:37:57.772 ThaliTest[1869:4227928] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2016-01-13 15:37:57.774 ThaliTest[1869:4226985] jxcore: disconnect
2016-01-13 15:37:57.775 ThaliTest[1869:4226985] client session: disconnectFromPeer: 1452695873445.1937.9y2Uag==
2016-01-13 15:37:57.775 ThaliTest[1869:4226985] client session: disconnect
2016-01-13 15:37:57.775 ThaliTest[1869:4226985] client session: stateChange:2->0 1452695873445.1937.9y2Uag==
,2016-01-13 15:37:57.835 ThaliTest[1869:4226985] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-13 15:37:58.099 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:37:58.099 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:37:58.099 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:37:58.099 ThaliTest[1869:4226985] server session: disconnect
2016-01-13 15:37:58.099 ThaliTest[1869:4226985] server session: stateChange:2->0 1452695873445.1937
,2016-01-13 15:37:58.101 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-13 15:37:59.676 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:37:59.678 ThaliTest[1869:4226985] server: starting 1452695879675.1869.eHGJAQ==
2016-01-13 15:37:59.678 ThaliTest[1869:4226985] multipeer session: start timer: 0x19440620
2016-01-13 15:37:59.678 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695879675.1869
2016-01-13 15:37:59.678 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-13 15:38:00.454 ThaliTest[1869:4226823] client: found peer: 1452695880833.1937.bzvYvA==
2016-01-13 15:38:00.455 ThaliTest[1869:4226985] jxcore: connect 1452695880833.1937.bzvYvA==
2016-01-13 15:38:00.455 ThaliTest[1869:4226985] client session: connect
2016-01-13 15:38:00.455 ThaliTest[1869:4226985] client session: stateChange:0->1 1452695880833.1937.bzvYvA==
,2016-01-13 15:38:00.878 ThaliTest[1869:4226823] multipeer session: reset timer
2016-01-13 15:38:00.879 ThaliTest[1869:4226823] multipeer session: stop timer
2016-01-13 15:38:00.879 ThaliTest[1869:4226823] multipeer session: start timer: 0x19440620
2016-,01-13 15:38:00.879 ThaliTest[1869:4226823] server session: connect
2016-01-13 15:38:00.879 ThaliTest[1869:4226823] server session: stateChange:0->1 1452695880833.1937
,2016-01-13 15:38:00.883 ThaliTest[1869:4226823] server: accepting invitation 1452695880833.1937
,2016-01-13 15:38:04.576 ThaliTest[1869:4227984] server session: connected
2016-01-13 15:38:04.577 ThaliTest[1869:4227984] server session: stateChange:1->2 1452695880833.1937
,2016-01-13 15:38:04.580 ThaliTest[1869:4226823] server relay: socket disconnected
2016-01-13 15:38:04.580 ThaliTest[1869:4226823] server relay: 0x197dc990 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 15:38:04.594 ThaliTest[1869:4227926] server session: not connected 1452695880833.1937
,2016-01-13 15:38:04.734 ThaliTest[1869:4227926] client session: connected
2016-01-13 15:38:04.734 ThaliTest[1869:4227926] client session: stateChange:1->2 1452695880833.1937.bzvYvA==
,2016-01-13 15:38:04.739 ThaliTest[1869:4227984] client session: fireConnectCallback: 1452695880833.1937.bzvYvA==
2016-01-13 15:38:04.739 ThaliTest[1869:4227984] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
,2016-01-13 15:38:04.741 ThaliTest[1869:4226985] jxcore: connect 1452695880833.1937.bzvYvA==
2016-01-13 15:38:04.741 ThaliTest[1869:4226985] client: already connect(ing/ed) to 1452695880833.1937.bzvYvA==
2016-01-13 15:38:04.741 ThaliTest[1869:4226985] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-13 15:38:04.742 ThaliTest[1869:4226985] jxcore: disconnect
2016-01-13 15:38:04.743 ThaliTest[1869:4226985] client session: disconnectFromPeer: 1452695880833.1937.bzvYvA==
2016-01-13 15:38:04.743 ThaliTest[1869:4226985] client session: disconnect
2016-01-13 15:38:04.743 ThaliTest[1869:4226985] client session: stateChange:2->0 1452695880833.1937.bzvYvA==
,2016-01-13 15:38:04.805 ThaliTest[1869:4226985] jxcore: disconnect: success
,ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-13 15:38:06.390 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:38:06.391 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:38:06.391 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:38:06.,391 ThaliTest[1869:4226985] server session: disconnect
2016-01-13 15:38:06.391 ThaliTest[1869:4226985] server session: stateChange:2->0 1452695880833.1937
2016-01-13 15:38:06.391 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-13 15:38:07.956 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:38:07.959 ThaliTest[1869:4226985] server: starting 1452695887956.1869.qlJofQ==
2016-01-13 15:38:07.959 ThaliTest[1869:4226985] multipeer session: start timer: 0x1b09f490
2016-01-13 15:38:07.959 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695887956.1869
2016-01-13 15:38:07.959 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-13 15:38:08.864 ThaliTest[1869:4226823] client: found peer: 1452695889138.1937.jCak2w==
,2016-01-13 15:38:08.865 ThaliTest[1869:4226985] jxcore: connect 1452695889138.1937.jCak2w==
2016-01-13 15:38:08.865 ThaliTest[1869:4226985] client session: connect
2016-01-13 15:38:08.866 ThaliTest[1869:4226985] client session: stateChange:0->1 1452695889138.1937.jCak2w==
,2016-01-13 15:38:09.289 ThaliTest[1869:4226823] multipeer session: reset timer
2016-01-13 15:38:09.289 ThaliTest[1869:4226823] multipeer session: stop timer
2016-01-13 15:38:09.289 ThaliTest[1869:4226823] multipeer session: start timer: 0x1b09f490
,2016-01-13 15:38:09.289 ThaliTest[1869:4226823] server session: connect
2016-01-13 15:38:09.289 ThaliTest[1869:4226823] server session: stateChange:0->1 1452695889138.1937
,2016-01-13 15:38:09.294 ThaliTest[1869:4226823] server: accepting invitation 1452695889138.1937
,2016-01-13 15:38:13.089 ThaliTest[1869:4227928] server session: connected
2016-01-13 15:38:13.089 ThaliTest[1869:4227928] server session: stateChange:1->2 1452695889138.1937
,2016-01-13 15:38:13.099 ThaliTest[1869:4226823] server relay: socket disconnected
2016-01-13 15:38:13.099 ThaliTest[1869:4226823] server relay: 0x1b15fd40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-13 15:38:13.128 ThaliTest[1869:4227985] server session: not connected 1452695889138.1937
,2016-01-13 15:38:13.161 ThaliTest[1869:4227926] client session: connected
,2016-01-13 15:38:13.161 ThaliTest[1869:4227926] client session: stateChange:1->2 1452695889138.1937.jCak2w==
,2016-01-13 15:38:13.170 ThaliTest[1869:4227985] client session: fireConnectCallback: 1452695889138.1937.jCak2w==
2016-01-13 15:38:13.170 ThaliTest[1869:4227985] jxcore: connect: success
ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2016-01-13 15:38:13.172 ThaliTest[1869:4226985] jxcore: disconnect
2016-01-13 15:38:13.172 ThaliTest[1869:4226985] client session: disconnectFromPeer: 1452695889138.1937.jCak2w==
2016-01-13 15:38:13.172 ThaliTest[1869:4226985] client session: disconnect
2016-01-13 15:38:13.172 ThaliTest[1869:4226985] client session: stateChange:2->0 1452695889138.1937.jCak2w==
,2016-01-13 15:38:13.176 ThaliTest[1869:4226985] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
,2016-01-13 15:38:13.178 ThaliTest[1869:4226985] jxcore: disconnect
2016-01-13 15:38:13.180 ThaliTest[1869:4226985] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-13 15:38:13.306 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:38:13.306 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:38:13.306 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:38:13.,307 ThaliTest[1869:4226985] server session: disconnect
2016-01-13 15:38:13.307 ThaliTest[1869:4226985] server session: stateChange:2->0 1452695889138.1937
,2016-01-13 15:38:13.308 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can connect and send data
,# teardown
,2016-01-13 15:38:15.159 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:38:15.161 ThaliTest[1869:4226985] server: starting 1452695895159.1869.zT4upg==
,2016-01-13 15:38:15.163 ThaliTest[1869:4226985] multipeer session: start timer: 0x1b173990
,2016-01-13 15:38:15.168 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695895159.1869
,2016-01-13 15:38:15.169 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,echo server started
,2016-01-13 15:38:15.675 ThaliTest[1869:4226823] client: found peer: 1452695896061.1937.ws+hIg==
,2016-01-13 15:38:15.678 ThaliTest[1869:4226985] jxcore: connect 1452695896061.1937.ws+hIg==
,2016-01-13 15:38:15.678 ThaliTest[1869:4226985] client session: connect
,2016-01-13 15:38:15.679 ThaliTest[1869:4226985] client session: stateChange:0->1 1452695896061.1937.ws+hIg==
,2016-01-13 15:38:16.308 ThaliTest[1869:4226823] multipeer session: reset timer
2016-01-13 15:38:16.308 ThaliTest[1869:4226823] multipeer session: stop timer
2016-01-13 15:38:16.308 ThaliTest[1869:4226823] multipeer session: start timer: 0x1b173990
2016-,01-13 15:38:16.308 ThaliTest[1869:4226823] server session: connect
2016-01-13 15:38:16.308 ThaliTest[1869:4226823] server session: stateChange:0->1 1452695896061.1937
2016-01-13 15:38:16.313 ThaliTest[1869:4226823] server: accepting invitation 1452695896061.1937
,2016-01-13 15:38:19.709 ThaliTest[1869:4227986] client session: connected
2016-01-13 15:38:19.709 ThaliTest[1869:4227986] client session: stateChange:1->2 1452695896061.1937.ws+hIg==
,2016-01-13 15:38:19.715 ThaliTest[1869:4227985] client session: fireConnectCallback: 1452695896061.1937.ws+hIg==
2016-01-13 15:38:19.715 ThaliTest[1869:4227985] jxcore: connect: success
ok 89 Should be able to connect without error
ok 90 Port should be within range
,2016-01-13 15:38:19.718 ThaliTest[1869:4226823] client: relay established
2016-01-13 15:38:19.718 ThaliTest[1869:4226823] client: new accepted socket: 0x1912cf90
,data in 3285
,data in 7665
,data in 16425
,data in 18615
,data in 51465
,data in 61705
,data in 82368
,data in 116070
,data in 117165
,data in 123735
,data in 130305
,2016-01-13 15:38:19.976 ThaliTest[1869:4227986] server session: connected
2016-01-13 15:38:19.976 ThaliTest[1869:4227986] server session: stateChange:1->2 1452695896061.1937
,data in 131072
ok 91 the test messages should be equal
,2016-01-13 15:38:19.985 ThaliTest[1869:4226985] jxcore: disconnect
2016-01-13 15:38:19.985 ThaliTest[1869:4226985] client session: disconnectFromPeer: 1452695896061.1937.ws+hIg==
2016-01-13 15:38:19.985 ThaliTest[1869:4226985] client session: disconnect
2016-01-13 15:38:19.985 ThaliTest[1869:4226985] client session: stateChange:2->0 1452695896061.1937.ws+hIg==
2016-01-13 15:38:19.987 ThaliTest[1869:4226823] server relay: connected (to port: 5001)
,2016-01-13 15:38:19.996 ThaliTest[1869:4226985] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-13 15:38:20.333 ThaliTest[1869:4227986] server session: not connected 1452695896061.1937
,calling stopBroadcasting
,2016-01-13 15:38:20.641 ThaliTest[1869:4226985] jxcore: stopBroadcasting
2016-01-13 15:38:20.642 ThaliTest[1869:4226985] THEMultipeerSession stopping peer
2016-01-13 15:38:20.642 ThaliTest[1869:4226985] multipeer session: stop timer
2016-01-13 15:38:20.642 ThaliTest[1869:4226985] server session: disconnect
2016-01-13 15:38:20.642 ThaliTest[1869:4226985] server session: stateChange:2->0 1452695896061.1937
2016-01-13 15:38:20.644 ThaliTest[1869:4226985] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-13 15:38:21.690 ThaliTest[1869:4226985] jxcore: startBroadcasting
,2016-01-13 15:38:21.692 ThaliTest[1869:4226985] server: starting 1452695901690.1869.OrCURA==
2016-01-13 15:38:21.693 ThaliTest[1869:4226985] multipeer session: start timer: 0x1b16c5c0
,2016-01-13 15:38:21.693 ThaliTest[1869:4226985] THEMultipeerSession initialized peer 1452695901690.1869
2016-01-13 15:38:21.694 ThaliTest[1869:4226985] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
,2016-01-13 15:38:21.697 ThaliTest[1869:4226985] Error!: listen EADDRINUSE
Stack:[{"_fileName":"net.js","_functionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_function,Name":"Server.prototype._listen2","_lineNumber":"974","_columnNumber":"14","_msg":"    at Server.prototype._listen2@net.js:974:14"},{"_fileName":"net.js","_functionName":"listen","_lineNumber":"995","_columnNumber":"5","_msg":"    at listen@net.js:995:5"},,{"_fileName":"net.js","_functionName":"Server.prototype.listen","_lineNumber":"1068","_columnNumber":"5","_msg":"    at Server.prototype.listen@net.js:1068:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2E,B2E8/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"241","_columnNumber":"3","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/bv_te,sts/testThaliNativeLayer.js:241:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"78","_columnNumber":"7","_,msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25,F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8,AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules,/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socke,t.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/j,xcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.pro,totype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:22,1:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/pri,vate/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":,"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/v,ar/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager,.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332,D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Conta,iners/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B,2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/pri,vate/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Contai,ners/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js","_functionName":"Decoder.prototype.add","_lineNumber":"247","_columnNumber":"7","_msg":"    at Decod,er.prototype.add@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js:247:7"},{"_fileName":"/private/var/mobile/Containers/Bundl,e/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondata","_lineNumber":"323","_columnNumber":"3","_msg":"    at Manager.prototype.ondata@/private/va,r/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/T,haliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/6C0332D,8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/,node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundl,e/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8,-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onPacket","_lineNumber":"441","_columnNumber":"9","_msg":"    at Socket.prototype.onPacket@/p,rivate/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/,6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.setTransport/<","_lineNumber":"258","_columnNumber":"5","_msg":"    at Socket.prototy,pe.setTransport/<@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5"},{"_fileName":"/private/var/mobile/Containers,/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumb,er":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.j,s:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Transport.prototype.onPac,ket","_lineNumber":"143","_columnNumber":"3","_msg":"    at Transport.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-cl,ient/lib/transport.js:143:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Tr,ansport.prototype.onData","_lineNumber":"135","_columnNumber":"3","_msg":"    at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_m,odules/engine.io-client/lib/transport.js:135:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websoc,ket.js","_functionName":"WS.prototype.addEventListeners/this.ws.onmessage","_lineNumber":"127","_columnNumber":"5","_msg":"    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F,76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js:127:5"}]
Uncaught Exception: Error: listen EADDRINUSE
,[ { _fileName: 'net.js',
    _functionName: 'errnoException',
    _lineNumber: '835',
    _columnNumber: '11',
    _msg: '    at errnoException@net.js:835:11' },
  { _fileName: 'net.js',
    _functionName: 'Server.prototype._listen2',
    _lineNumbe,r: '974',
    _columnNumber: '14',
    _msg: '    at Server.prototype._listen2@net.js:974:14' },
  { _fileName: 'net.js',
    _functionName: 'listen',
    _lineNumber: '995',
    _columnNumber: '5',
    _msg: '    at listen@net.js:995:5' },
  { _fi,leName: 'net.js',
    _functionName: 'Server.prototype.listen',
    _lineNumber: '1068',
    _columnNumber: '5',
    _msg: '    at Server.prototype.listen@net.js:1068:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-871,1-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: '',
    _lineNumber: '241',
    _columnNumber: '3',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F,76B2EB2E8/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:241:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareT,est/</<',
    _lineNumber: '78',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7' },
  { _fileName: '/priva,te/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
  ,  _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Container,s/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    ,_msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/v,ar/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg:, '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _lineNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.on,packet@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D,9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mo,bile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4,D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit,@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Applicat,ion/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineNumber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondec,oded@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9,C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mob,ile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D,9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: ',    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7' },
  {, _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js',
    _functionName: 'Decoder.prototype.add',
    _lineNumbe,r: '247',
    _columnNumber: '7',
    _msg: '    at Decoder.prototype.add@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js,:247:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondata',
    _lineNumber: '32,3',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondata@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3' },
  { _fileName: ,'/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _colu,mnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName:, '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.e,mit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/eng,ine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib,/socket.js',
    _functionName: 'Socket.prototype.onPacket',
    _lineNumber: '441',
    _columnNumber: '9',
    _msg: '    at Socket.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.ap,p/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/,node_modules/engine.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.setTransport/<',
    _lineNumber: '258',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/6C03,32D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/,private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobil,e/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.prototype.onPacket',
    _lineNumber: '143',
    _,columnNumber: '3',
    _msg: '    at Transport.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:,143:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.prototy,pe.onData',
    _lineNumber: '135',
    _columnNumber: '3',
    _msg: '    at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_m,odules/engine.io-client/lib/transport.js:135:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/6C0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/w,ebsocket.js',
    _functionName: 'WS.prototype.addEventListeners/this.ws.onmessage',
    _lineNumber: '127',
    _columnNumber: '5',
    _msg: '    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/6C,0332D8-8711-4D9C-B8AA-25F76B2EB2E8/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js:127:5' },
  toString: [Function] ]
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
