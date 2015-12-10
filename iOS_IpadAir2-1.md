#### Test 50650278c17c777_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c17c777/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/8C12A924-4204-4760-9F66-F9B35967DFD9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8C12A924-4204-4760-9F66-F9B35967DFD9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c17c777/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c17c777/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/153D50C4-F035-4ED1-9EF7-119F646DF059/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52922"
,(lldb)     command script import "/tmp/8C12A924-4204-4760-9F66-F9B35967DFD9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 12:15:39.174 ThaliTest[690:551182] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1868F086-91DC-4CB6-B4FE-E33176BC335F/Library/Cookies/Cookies.binarycookies
,2015-12-10 12:15:39.188 ThaliTest[690:551182] <CATransformLayer: 0x15d44880> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-10 12:15:39.189 ThaliTest[690:551182] <CATransformLayer: 0x15d480f0> - changing property ma,sksToBounds in transform-only layer, will have no effect
2015-12-10 12:15:39.190 ThaliTest[690:551182] <CATransformLayer: 0x15d49260> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-10 12:15:39.475 ThaliTest[690:551182] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 12:15:39.475 ThaliTest[690:551182] Multi-tasking -> Device: YES, App: YES
,2015-12-10 12:15:39.483 ThaliTest[690:551182] Unlimited access to network resources
,2015-12-10 12:15:39.488 ThaliTest[690:551182] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 12:15:48.181 ThaliTest[690:551182] Resetting plugins due to page load.
,2015-12-10 12:15:50.597 ThaliTest[690:551182] Finished load of: file:///var/mobile/Containers/Bundle/Application/153D50C4-F035-4ED1-9EF7-119F646DF059/ThaliTest.app/www/index.html
,2015-12-10 12:15:50.758 ThaliTest[690:551182] JXcore Cordova plugin initializing
,2015-12-10 12:15:50.759 ThaliTest[690:551558] JXcore instance initializing
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
# setup
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
,2015-12-10 12:21:27.908 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:27.927 ThaliTest[690:551558] server: starting 1449746487907.690.qairqg==
,2015-12-10 12:21:27.928 ThaliTest[690:551558] multipeer session: start timer: 0x1919b8f0
,2015-12-10 12:21:27.929 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746487907.690
,2015-12-10 12:21:27.931 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-10 12:21:27.935 ThaliTest[690:551558] jxcore: stopBroadcasting
,2015-12-10 12:21:27.936 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:21:27.937 ThaliTest[690:551558] multipeer session: stop timer
,2015-12-10 12:21:27.941 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
2015-12-10 12:21:27.944 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:27.949 ThaliTest[690:551558] server: starting 1449746487944.690.ema4zw==
,2015-12-10 12:21:27.951 ThaliTest[690:551558] multipeer session: start timer: 0x1927efa0
2015-12-10 12:21:27.955 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746487944.690
,2015-12-10 12:21:27.957 ThaliTest[690:551558] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2015-12-10 12:21:27.960 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:21:27.960 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:21:27.961 ThaliTest[690:551558] multipeer session: stop timer
2015-12-10 12:21:27.961 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2015-12-10 12:21:27.964 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:27.969 ThaliTest[690:551558] server: starting 1449746487963.690.pc7F8A==
2015-12-10 12:21:27.970 ThaliTest[690:551558] multipeer session: start timer: 0x1919f810
2015-12-10 12:21:27.970 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746487963.690
2015-12-10 12:21:27.970 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
2015-12-10 12:21:27.973 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:21:27.973 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:21:27.974 ThaliTest[690:551558] multipeer session: stop timer
2015-12-10 12:21:27.974 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-10 12:21:27.977 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:27.983 ThaliTest[690:551558] server: starting 1449746487976.690.ivcoNA==
,2015-12-10 12:21:27.985 ThaliTest[690:551558] multipeer session: start timer: 0x1919f580
2015-12-10 12:21:27.985 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746487976.690
2015-12-10 12:21:27.986 ThaliTest[690:551558] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-10 12:21:27.987 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:21:27.988 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:21:27.988, ThaliTest[690:551558] multipeer session: stop timer
2015-12-10 12:21:27.988 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-10 12:21:27.991 ThaliTest[690:551558] jxcore: startBroadcasting
2015-12-10 12:21:27.995 ThaliTest[690:551558] server: starting 1449746487991.690.EEsh+g==
,2015-12-10 12:21:27.999 ThaliTest[690:551558] multipeer session: start timer: 0x1927fdc0
2015-12-10 12:21:27.999 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746487991.690
2015-12-10 12:21:27.999 ThaliTest[690:551558] jxcore: startBroad,casting: success
ok 53 Should be able to call startBroadcasting without error
2015-12-10 12:21:28.001 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:21:28.001 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:21:28.002 ThaliTest[690:551558] multipeer session: stop timer
2015-12-10 12:21:28.004 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-10 12:21:28.006 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:28.011 ThaliTest[690:551558] server: starting 1449746488005.690.opy+8g==
2015-12-10 12:21:28.012 ThaliTest[690:551558] multipeer session: start timer: 0x1927fdc0
,2015-12-10 12:21:28.012 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746488005.690
2015-12-10 12:21:28.012 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-10 12:21:28.016 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:21:28.016 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:21:28.016 ThaliTest[690:551558] multipeer session: stop timer
2015-12-10 12:21:28.017 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
2015-12-10 12:21:28.019 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:28.022 ThaliTest[690:551558] server: starting 1449746488019.690.i5NY8w==
2015-12-10 12:21:28.023 ThaliTest[690:551558] multipeer session: start timer: 0x191a0880
2015-12-10 12:21:28.023 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746488019.690
2015-12-10 12:21:28.024 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
2015-12-10 12:21:28.026 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:21:28.027 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:21:28.027 ThaliTest[690:551,558] multipeer session: stop timer
2015-12-10 12:21:28.027 ThaliTest[690:551558] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
,2015-12-10 12:21:28.030 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:28.033 ThaliTest[690:551558] server: starting 1449746488028.690.r5u+4g==
2015-12-10 12:21:28.034 ThaliTest[690:551558] multipeer session: start timer: 0x1932c2a0
2015-12-10 12:21:28.034 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746488028.690
2015-12-10 12:21:28.034 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
2015-12-10 12:21:28.040 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:21:28.040 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:21:28.040 ThaliTest[690:551558] multipeer session: stop timer
,2015-12-10 12:21:28.041 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
2015-12-10 12:21:28.043 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:28.046 ThaliTest[690:551558] server: starting 1449746488043.690.rlzyqA==
2015-12-10 12:21:28.047 ThaliTest[690:551558] multipeer session: start timer: 0x1932aad0
,2015-12-10 12:21:28.047 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746488043.690
,2015-12-10 12:21:28.049 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-10 12:21:28.053 ThaliTest[690:551558] jxcore: stopBroadcasting
,2015-12-10 12:21:28.054 ThaliTest[690:551558] THEMultipeerSession stopping peer
,2015-12-10 12:21:28.054 ThaliTest[690:551558] multipeer session: stop timer
,2015-12-10 12:21:28.055 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-10 12:21:28.059 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:28.062 ThaliTest[690:551558] server: starting 1449746488059.690.3RNInw==
,2015-12-10 12:21:28.063 ThaliTest[690:551558] multipeer session: start timer: 0x1932bc00
,2015-12-10 12:21:28.064 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746488059.690
,2015-12-10 12:21:28.066 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-10 12:21:28.069 ThaliTest[690:551558] jxcore: stopBroadcasting
,2015-12-10 12:21:28.070 ThaliTest[690:551558] THEMultipeerSession stopping peer
,2015-12-10 12:21:28.071 ThaliTest[690:551558] multipeer session: stop timer
,2015-12-10 12:21:28.072 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-10 12:21:28.398 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:28.402 ThaliTest[690:551558] server: starting 1449746488398.690.N3fbHA==
,2015-12-10 12:21:28.403 ThaliTest[690:551558] multipeer session: start timer: 0x19327620
,2015-12-10 12:21:28.406 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746488398.690
,2015-12-10 12:21:28.410 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2015-12-10 12:21:28.416 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:28.417 ThaliTest[690:551558] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2015-12-10 12:21:28.421 ThaliTest[690:551558] jxcore: stopBroadcasting
,2015-12-10 12:21:28.421 ThaliTest[690:551558] THEMultipeerSession stopping peer
,2015-12-10 12:21:28.422 ThaliTest[690:551558] multipeer session: stop timer
,2015-12-10 12:21:28.425 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-10 12:21:28.906 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:28.910 ThaliTest[690:551558] server: starting 1449746488906.690.gVqtAw==
,2015-12-10 12:21:28.911 ThaliTest[690:551558] multipeer session: start timer: 0x19328110
2015-12-10 12:21:28.911 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746488906.690
2015-12-10 12:21:28.912 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2015-12-10 12:21:28.915 ThaliTest[690:551558] jxcore: connect foobar
2015-12-10 12:21:28.916 ThaliTest[690:551558] client: unknown peer foobar
2015-12-10 12:21:28.916 ThaliTest[690:551558] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2015-12-10 12:21:28.920 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:21:28.921 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:21:28.921 ThaliTest[690:551558] multipeer session: stop timer
2015-12-10 12:21:28.921 Th,aliTest[690:551558] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-10 12:21:29.495 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:29.499 ThaliTest[690:551558] server: starting 1449746489495.690.qCO4KQ==
,2015-12-10 12:21:29.500 ThaliTest[690:551558] multipeer session: start timer: 0x191a5be0
,2015-12-10 12:21:29.501 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746489495.690
2015-12-10 12:21:29.501 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
2015-12-10 12:21:29.505 ThaliTest[690:551558] jxcore: disconnect
2015-12-10 12:21:29.505 ThaliTest[690:551558] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2015-12-10 12:21:29.508 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:21:29.509 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:21:29.509 ThaliTest[690:551558] multipeer session: stop timer
2015-12-10 12:21:29.509 Th,aliTest[690:551558] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-10 12:21:29.968 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:29.972 ThaliTest[690:551558] server: starting 1449746489968.690.ts45FQ==
,2015-12-10 12:21:29.973 ThaliTest[690:551558] multipeer session: start timer: 0x1932efc0
2015-12-10 12:21:29.974 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746489968.690
2015-12-10 12:21:29.974 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2015-12-10 12:21:31.204 ThaliTest[690:551182] client: found peer: 1449746487715.656.yfLGbQ==
,2015-12-10 12:21:31.207 ThaliTest[690:551558] jxcore: connect 1449746487715.656.yfLGbQ==
,2015-12-10 12:21:31.207 ThaliTest[690:551558] client session: connect
,2015-12-10 12:21:31.208 ThaliTest[690:551558] client session: stateChange:0->1 1449746487715.656.yfLGbQ==
,2015-12-10 12:21:31.301 ThaliTest[690:551182] multipeer session: reset timer
,2015-12-10 12:21:31.301 ThaliTest[690:551182] multipeer session: stop timer
2015-12-10 12:21:31.301 ThaliTest[690:551182] multipeer session: start timer: 0x1932efc0
,2015-12-10 12:21:31.302 ThaliTest[690:551182] server session: connect
,2015-12-10 12:21:31.302 ThaliTest[690:551182] server session: stateChange:0->1 1449746487715.656
,2015-12-10 12:21:31.309 ThaliTest[690:551182] server: accepting invitation 1449746487715.656
,2015-12-10 12:21:33.943 ThaliTest[690:552202] server session: connected
2015-12-10 12:21:33.943 ThaliTest[690:552202] server session: stateChange:1->2 1449746487715.656
,2015-12-10 12:21:33.949 ThaliTest[690:551182] server relay: socket disconnected
,2015-12-10 12:21:33.950 ThaliTest[690:551182] server relay: 0x1932fec0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 12:21:34.002 ThaliTest[690:552202] server session: not connected 1449746487715.656
,2015-12-10 12:21:34.566 ThaliTest[690:552217] client session: connected
2015-12-10 12:21:34.567 ThaliTest[690:552217] client session: stateChange:1->2 1449746487715.656.yfLGbQ==
,2015-12-10 12:21:34.571 ThaliTest[690:552202] client session: fireConnectCallback: 1449746487715.656.yfLGbQ==
2015-12-10 12:21:34.571 ThaliTest[690:552202] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-10 12:21:34.577 ThaliTest[690:551558] jxcore: disconnect
,2015-12-10 12:21:34.577 ThaliTest[690:551558] client session: disconnectFromPeer: 1449746487715.656.yfLGbQ==
2015-12-10 12:21:34.578 ThaliTest[690:551558] client session: disconnect
2015-12-10 12:21:34.578 ThaliTest[690:551558] client session: stateChange:2->0 1449746487715.656.yfLGbQ==
,2015-12-10 12:21:34.588 ThaliTest[690:551558] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-10 12:21:34.683 ThaliTest[690:551558] jxcore: stopBroadcasting
,2015-12-10 12:21:34.683 ThaliTest[690:551558] THEMultipeerSession stopping peer
,2015-12-10 12:21:34.684 ThaliTest[690:551558] multipeer session: stop timer
,2015-12-10 12:21:34.685 ThaliTest[690:551558] server session: disconnect
2015-12-10 12:21:34.685 ThaliTest[690:551558] server session: stateChange:2->0 1449746487715.656
,2015-12-10 12:21:34.687 ThaliTest[690:551558] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-10 12:21:36.844 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:21:36.847 ThaliTest[690:551558] server: starting 1449746496843.690.bUZAvw==
,2015-12-10 12:21:36.848 ThaliTest[690:551558] multipeer session: start timer: 0x191a9ac0
2015-12-10 12:21:36.849 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746496843.690
2015-12-10 12:21:36.849 ThaliTest[690:551558] jxcore: startBroad,casting: success
ok 78 Should be able to call startBroadcasting without error
,2015-12-10 12:21:38.015 ThaliTest[690:551182] client: found peer: 1449746494588.656.DS2djg==
,2015-12-10 12:21:38.017 ThaliTest[690:551558] jxcore: connect 1449746494588.656.DS2djg==
2015-12-10 12:21:38.017 ThaliTest[690:551558] client session: connect
2015-12-10 12:21:38.018 ThaliTest[690:551558] client session: stateChange:0->1 1449746494588.656.DS2djg==
,2015-12-10 12:21:38.409 ThaliTest[690:551182] multipeer session: reset timer
2015-12-10 12:21:38.409 ThaliTest[690:551182] multipeer session: stop timer
,2015-12-10 12:21:38.409 ThaliTest[690:551182] multipeer session: start timer: 0x191a9ac0
,2015-12-10 12:21:38.410 ThaliTest[690:551182] server session: connect
,2015-12-10 12:21:38.410 ThaliTest[690:551182] server session: stateChange:0->1 1449746494588.656
,2015-12-10 12:21:38.416 ThaliTest[690:551182] server: accepting invitation 1449746494588.656
,2015-12-10 12:21:40.937 ThaliTest[690:552209] client session: connected
2015-12-10 12:21:40.938 ThaliTest[690:552209] client session: stateChange:1->2 1449746494588.656.DS2djg==
,2015-12-10 12:21:40.996 ThaliTest[690:552202] client session: fireConnectCallback: 1449746494588.656.DS2djg==
2015-12-10 12:21:40.996 ThaliTest[690:552202] jxcore: connect: success
,ok 79 Should be able to connect without error
ok 80 Port should be within range
2015-12-10 12:21:41.000 ThaliTest[690:551558] jxcore: connect 1449746494588.656.DS2djg==
,2015-12-10 12:21:41.001 ThaliTest[690:551558] client: already connect(ing/ed) to 1449746494588.656.DS2djg==
2015-12-10 12:21:41.005 ThaliTest[690:552208] server session: connected
,2015-12-10 12:21:41.005 ThaliTest[690:552208] server session: stateChange:1->2 1449746494588.656
,2015-12-10 12:21:41.004 ThaliTest[690:551558] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
,2015-12-10 12:21:41.011 ThaliTest[690:551558] jxcore: disconnect
,2015-12-10 12:21:41.011 ThaliTest[690:551558] client session: disconnectFromPeer: 1449746494588.656.DS2djg==
2015-12-10 12:21:41.012 ThaliTest[690:551558] client session: disconnect
,2015-12-10 12:21:41.012 ThaliTest[690:551558] client session: stateChange:2->0 1449746494588.656.DS2djg==
,2015-12-10 12:21:41.022 ThaliTest[690:551558] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-10 12:21:41.124 ThaliTest[690:551182] server relay: socket disconnected
,2015-12-10 12:21:41.125 ThaliTest[690:551182] server relay: 0x1933f300 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 12:21:41.134 ThaliTest[690:552208] server session: not connected 1449746494588.656
,calling stopBroadcasting
,2015-12-10 12:21:41.522 ThaliTest[690:551558] jxcore: stopBroadcasting
,2015-12-10 12:21:41.523 ThaliTest[690:551558] THEMultipeerSession stopping peer
,2015-12-10 12:21:41.523 ThaliTest[690:551558] multipeer session: stop timer
,2015-12-10 12:21:41.524 ThaliTest[690:551558] server session: disconnect
2015-12-10 12:21:41.525 ThaliTest[690:551558] server session: stateChange:2->0 1449746494588.656
,2015-12-10 12:21:41.528 ThaliTest[690:551558] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-10 12:22:38.828 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:22:38.832 ThaliTest[690:551558] server: starting 1449746558828.690.o7lGwQ==
,2015-12-10 12:22:38.833 ThaliTest[690:551558] multipeer session: start timer: 0x191b5100
2015-12-10 12:22:38.834 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746558828.690
2015-12-10 12:22:38.834 ThaliTest[690:551558] jxcore: startBroad,casting: success
,ok 83 Should be able to call startBroadcasting without error
,2015-12-10 12:22:39.611 ThaliTest[690:551182] client: found peer: 1449746556404.656.kXXqfg==
,2015-12-10 12:22:39.613 ThaliTest[690:551558] jxcore: connect 1449746556404.656.kXXqfg==
2015-12-10 12:22:39.613 ThaliTest[690:551558] client session: connect
2015-12-10 12:22:39.613 ThaliTest[690:551558] client session: stateChange:0->1 1449746556404.65,6.kXXqfg==
,2015-12-10 12:22:40.061 ThaliTest[690:551182] multipeer session: reset timer
2015-12-10 12:22:40.061 ThaliTest[690:551182] multipeer session: stop timer
,2015-12-10 12:22:40.062 ThaliTest[690:551182] multipeer session: start timer: 0x191b5100
,2015-12-10 12:22:40.062 ThaliTest[690:551182] server session: connect
2015-12-10 12:22:40.063 ThaliTest[690:551182] server session: stateChange:0->1 1449746556404.656
,2015-12-10 12:22:40.069 ThaliTest[690:551182] server: accepting invitation 1449746556404.656
,2015-12-10 12:22:42.643 ThaliTest[690:552375] server session: connected
2015-12-10 12:22:42.643 ThaliTest[690:552375] server session: stateChange:1->2 1449746556404.656
,2015-12-10 12:22:42.652 ThaliTest[690:552376] client session: connected
2015-12-10 12:22:42.653 ThaliTest[690:552376] client session: stateChange:1->2 1449746556404.656.kXXqfg==
,2015-12-10 12:22:42.656 ThaliTest[690:551182] server relay: socket disconnected
2015-12-10 12:22:42.657 ThaliTest[690:551182] server relay: 0x19336f40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 12:22:42.665 ThaliTest[690:552374] client session: fireConnectCallback: 1449746556404.656.kXXqfg==
2015-12-10 12:22:42.665 ThaliTest[690:552374] jxcore: connect: success
,ok 84 Should be able to connect without error
,ok 85 Port should be within range
,2015-12-10 12:22:42.670 ThaliTest[690:551558] jxcore: disconnect
,2015-12-10 12:22:42.671 ThaliTest[690:551558] client session: disconnectFromPeer: 1449746556404.656.kXXqfg==
,2015-12-10 12:22:42.672 ThaliTest[690:551558] client session: disconnect
,2015-12-10 12:22:42.672 ThaliTest[690:551558] client session: stateChange:2->0 1449746556404.656.kXXqfg==
,2015-12-10 12:22:42.683 ThaliTest[690:551558] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2015-12-10 12:22:42.688 ThaliTest[690:551558] jxcore: disconnect
,2015-12-10 12:22:42.689 ThaliTest[690:551558] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-10 12:22:42.745 ThaliTest[690:552376] server session: not connected 1449746556404.656
,calling stopBroadcasting
,2015-12-10 12:22:43.570 ThaliTest[690:551558] jxcore: stopBroadcasting
,2015-12-10 12:22:43.571 ThaliTest[690:551558] THEMultipeerSession stopping peer
,2015-12-10 12:22:43.572 ThaliTest[690:551558] multipeer session: stop timer
,2015-12-10 12:22:43.572 ThaliTest[690:551558] server session: disconnect
2015-12-10 12:22:43.573 ThaliTest[690:551558] server session: stateChange:2->0 1449746556404.656
2015-12-10 12:22:43.574 ThaliTest[690:551558] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-10 12:22:44.030 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:22:44.033 ThaliTest[690:551558] server: starting 1449746564029.690.awV4UA==
,2015-12-10 12:22:44.035 ThaliTest[690:551558] multipeer session: start timer: 0x193383d0
2015-12-10 12:22:44.035 ThaliTest[690:551558] THEMultipeerSession initialized peer 1449746564029.690
2015-12-10 12:22:44.036 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,echo server started
,2015-12-10 12:22:44.882 ThaliTest[690:551182] client: found peer: 1449746561771.656.BPhKwQ==
[{"peerIdentifier":"1449746561771.656.BPhKwQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-10 12:22:44.885 ThaliTest[690:551558] jxcore: connect 1449746561771.656.BPhKwQ==
2015-12-10 12:22:44.886 ThaliTest[690:551558] client session: connect
,2015-12-10 12:22:44.886 ThaliTest[690:551558] client session: stateChange:0->1 1449746561771.656.BPhKwQ==
,2015-12-10 12:22:45.328 ThaliTest[690:551182] multipeer session: reset timer
2015-12-10 12:22:45.328 ThaliTest[690:551182] multipeer session: stop timer
2015-12-10 12:22:45.329 ThaliTest[690:551182] multipeer session: start timer: 0x193383d0
,2015-12-10 12:22:45.329 ThaliTest[690:551182] server session: connect
2015-12-10 12:22:45.329 ThaliTest[690:551182] server session: stateChange:0->1 1449746561771.656
,2015-12-10 12:22:45.338 ThaliTest[690:551182] server: accepting invitation 1449746561771.656
,2015-12-10 12:22:47.790 ThaliTest[690:552374] client session: connected
2015-12-10 12:22:47.790 ThaliTest[690:552374] client session: stateChange:1->2 1449746561771.656.BPhKwQ==
,2015-12-10 12:22:47.858 ThaliTest[690:552396] client session: fireConnectCallback: 1449746561771.656.BPhKwQ==
2015-12-10 12:22:47.858 ThaliTest[690:552396] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,ok 91 First connect should succeed
,2015-12-10 12:22:47.901 ThaliTest[690:552396] server session: connected
2015-12-10 12:22:47.901 ThaliTest[690:552396] server session: stateChange:1->2 1449746561771.656
,2015-12-10 12:22:47.923 ThaliTest[690:551182] server relay: connected (to port: 5001)
2015-12-10 12:22:47.925 ThaliTest[690:551182] client: relay established
2015-12-10 12:22:47.926 ThaliTest[690:551182] client: new accepted socket: 0x191b7e90
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2015-12-10 12:22:48.027 ThaliTest[690:551182] client: socket closed
,2015-12-10 12:22:48.027 ThaliTest[690:551182] client relay: socket disconnected
,2015-12-10 12:22:48.028 ThaliTest[690:551182] client relay: 0x191b7e90 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-10 12:22:48.028 ThaliTest[690:551182] client session: socket closed: 1449746561771.656.BPhKwQ==
2015-12-10 12:22:48.028 ThaliTest[690:551182] client session: onLinkFailure: 1449746561771.656.BPhKwQ==
,2015-12-10 12:22:48.029 ThaliTest[690:551182] client session: disconnect
2015-12-10 12:22:48.029 ThaliTest[690:551182] client session: stateChange:2->0 1449746561771.656.BPhKwQ==
,2015-12-10 12:22:48.039 ThaliTest[690:551182] client session: fireConnectionErrorEvent: 1449746561771.656.BPhKwQ==
2015-12-10 12:22:48.042 ThaliTest[690:551558] jxcore: connect 1449746561771.656.BPhKwQ==
,2015-12-10 12:22:48.042 ThaliTest[690:551558] client session: connect
2015-12-10 12:22:48.045 ThaliTest[690:551558] client session: stateChange:0->1 1449746561771.656.BPhKwQ==
,2015-12-10 12:22:48.091 ThaliTest[690:552375] server session: not connected 1449746561771.656
,2015-12-10 12:22:48.365 ThaliTest[690:551182] multipeer session: reset timer
2015-12-10 12:22:48.365 ThaliTest[690:551182] multipeer session: stop timer
2015-12-10 12:22:48.365 ThaliTest[690:551182] multipeer session: start timer: 0x193383d0
,2015-12-10 12:22:48.366 ThaliTest[690:551182] server: disconnecting to refresh session (1449746561771.656)
2015-12-10 12:22:48.366 ThaliTest[690:551182] server session: disconnect
2015-12-10 12:22:48.366 ThaliTest[690:551182] server session: stateChange:2->0 1449746561771.656
,2015-12-10 12:22:48.371 ThaliTest[690:551182] server session: connect
2015-12-10 12:22:48.371 ThaliTest[690:551182] server session: stateChange:0->1 1449746561771.656
,2015-12-10 12:22:48.379 ThaliTest[690:551182] server: accepting invitation 1449746561771.656
,2015-12-10 12:22:50.793 ThaliTest[690:552396] client session: connected
2015-12-10 12:22:50.793 ThaliTest[690:552396] client session: stateChange:1->2 1449746561771.656.BPhKwQ==
,2015-12-10 12:22:50.809 ThaliTest[690:552375] client session: fireConnectCallback: 1449746561771.656.BPhKwQ==
2015-12-10 12:22:50.810 ThaliTest[690:552375] jxcore: connect: success
,ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 Second connect should succeed
,2015-12-10 12:22:50.846 ThaliTest[690:551182] client: relay established
2015-12-10 12:22:50.847 ThaliTest[690:551182] client: new accepted socket: 0x191af1d0
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2015-12-10 12:22:50.945 ThaliTest[690:551182] client: socket closed
2015-12-10 12:22:50.945 ThaliTest[690:551182] client relay: socket disconnected
,2015-12-10 12:22:50.946 ThaliTest[690:551182] client relay: 0x191af1d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-10 12:22:50,.946 ThaliTest[690:551182] client session: socket closed: 1449746561771.656.BPhKwQ==
,2015-12-10 12:22:50.946 ThaliTest[690:551182] client session: onLinkFailure: 1449746561771.656.BPhKwQ==
2015-12-10 12:22:50.946 ThaliTest[690:551182] client session: disconnect
2015-12-10 12:22:50.947 ThaliTest[690:551182] client session: stateChange:2->0 1449746561771.656.BPhKwQ==
,2015-12-10 12:22:50.984 ThaliTest[690:552410] server session: connected
2015-12-10 12:22:50.984 ThaliTest[690:552410] server session: stateChange:1->2 1449746561771.656
,2015-12-10 12:22:51.019 ThaliTest[690:551182] client session: fireConnectionErrorEvent: 1449746561771.656.BPhKwQ==
2015-12-10 12:22:51.020 ThaliTest[690:551182] server relay: connected (to port: 5001)
,2015-12-10 12:22:51.141 ThaliTest[690:552396] server session: not connected 1449746561771.656
,calling stopBroadcasting
,2015-12-10 12:22:51.431 ThaliTest[690:551558] jxcore: stopBroadcasting
,2015-12-10 12:22:51.431 ThaliTest[690:551558] THEMultipeerSession stopping peer
,2015-12-10 12:22:51.432 ThaliTest[690:551558] multipeer session: stop timer
,2015-12-10 12:22:51.433 ThaliTest[690:551558] server session: disconnect
2015-12-10 12:22:51.433 ThaliTest[690:551558] server session: stateChange:2->0 1449746561771.656
,2015-12-10 12:22:51.448 ThaliTest[690:551558] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/1868F086-91DC-4CB6-B4FE-E33176BC335F/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2015-12-10 12:22:52.726 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:22:52.728 ThaliTest[690:551558] server: starting rCPfrdZ3GP5lHLDP7S6zSg.rL057w==
,2015-12-10 12:22:52.728 ThaliTest[690:551558] multipeer session: start timer: 0x191bb3a0
2015-12-10 12:22:52.728 ThaliTest[690:551558] THEMultipeerSession initialized peer rCPfrdZ3GP5lHLDP7S6zSg
2015-12-10 12:22:52.728 ThaliTest[690:551558] jxcore: startBroadcasting: success
,ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
,ok 101 stopping event should occur in right order
About to call stopBroadcasting
2015-12-10 12:22:52.730 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:22:52.730 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:22:52.730 ThaliTest[690:551558] multipeer session: stop timer
2015-12-10 12:22:52.731 ThaliTest[690:551558] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/1868F086-91DC-4CB6-B4FE-E33176BC335F/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2015-12-10 12:22:53.649 ThaliTest[690:551558] jxcore: startBroadcasting
,2015-12-10 12:22:53.653 ThaliTest[690:551558] server: starting rCPfrdZ3GP5lHLDP7S6zSg.oixHqA==
,2015-12-10 12:22:53.654 ThaliTest[690:551558] multipeer session: start timer: 0x191bf9b0
,2015-12-10 12:22:53.654 ThaliTest[690:551558] THEMultipeerSession initialized peer rCPfrdZ3GP5lHLDP7S6zSg
,2015-12-10 12:22:53.655 ThaliTest[690:551558] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
,2015-12-10 12:22:53.660 ThaliTest[690:551558] jxcore: stopBroadcasting
2015-12-10 12:22:53.661 ThaliTest[690:551558] THEMultipeerSession stopping peer
2015-12-10 12:22:53.661 ThaliTest[690:551558] multipeer session: stop timer
,2015-12-10 12:22:53.662 ThaliTest[690:551558] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
Tests Complete

```
