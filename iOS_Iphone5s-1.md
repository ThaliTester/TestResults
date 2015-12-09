#### Test 506502789252e15_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/A41012A5-F533-4B4B-9B29-DD7FE584CEFC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A41012A5-F533-4B4B-9B29-DD7FE584CEFC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502789252e15/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D5D19B48-C1AB-4E77-8352-B77F5CB4FFAF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52567"
,(lldb)     command script import "/tmp/A41012A5-F533-4B4B-9B29-DD7FE584CEFC/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-09 18:52:25.513 ThaliTest[622:456706] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4AE3E50D-A6DA-440C-A0EB-3A311A8DE86C/Library/Cookies/Cookies.binarycookies
,2015-12-09 18:52:25.972 ThaliTest[622:456706] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 18:52:25.973 ThaliTest[622:456706] Multi-tasking -> Device: YES, App: YES
,2015-12-09 18:52:25.983 ThaliTest[622:456706] Unlimited access to network resources
,2015-12-09 18:52:25.994 ThaliTest[622:456706] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 18:52:35.564 ThaliTest[622:456706] Resetting plugins due to page load.
,2015-12-09 18:52:39.601 ThaliTest[622:456706] Finished load of: file:///var/mobile/Containers/Bundle/Application/D5D19B48-C1AB-4E77-8352-B77F5CB4FFAF/ThaliTest.app/www/index.html
,2015-12-09 18:52:39.807 ThaliTest[622:456706] JXcore Cordova plugin initializing
,2015-12-09 18:52:39.808 ThaliTest[622:456941] JXcore instance initializing
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
,2015-12-09 18:57:38.814 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:38.831 ThaliTest[622:456941] server: starting 1449683858813.622.NtPOOA==
,2015-12-09 18:57:38.832 ThaliTest[622:456941] multipeer session: start timer: 0x1793dc30
2015-12-09 18:57:38.833 ThaliTest[622:456941] THEMultipeerSession initialized peer 1449683858813.622
2015-12-09 18:57:38.834 ThaliTest[622:456941] jxcore: startBroad,casting: success
ok 45 Should be able to call startBroadcasting without error
2015-12-09 18:57:38.838 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:57:38.838 ThaliTest[622:456941] THEMultipeerSession stopping peer
2015-12-09 18:57:38.839, ThaliTest[622:456941] multipeer session: stop timer
2015-12-09 18:57:38.839 ThaliTest[622:456941] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2015-12-09 18:57:38.841 ThaliTest[622:456941] jxcore: startB,roadcasting
,2015-12-09 18:57:38.848 ThaliTest[622:456941] server: starting 1449683858841.622.nXPOEg==
2015-12-09 18:57:38.849 ThaliTest[622:456941] multipeer session: start timer: 0x15ece640
2015-12-09 18:57:38.849 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683858841.622
2015-12-09 18:57:38.849 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2015-12-09 18:57:38.852 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:57:38.863 ThaliTest[622:456941] THEMultipeerSession stopping peer
2015-12-09 18:57:38.863 ThaliTest[622:456941] multipeer session: stop timer
,2015-12-09 18:57:38.865 ThaliTest[622:456941] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2015-12-09 18:57:38.875 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:38.882 ThaliTest[622:456941] server: starting 1449683858875.622.vdp5rg==
2015-12-09 18:57:38.883 ThaliTest[622:456941] multipeer session: start timer: 0x17942500
2015-12-09 18:57:38.884 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683858875.622
2015-12-09 18:57:38.884 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2015-12-09 18:57:38.887 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:57:38.887 ThaliTest[622:456941] THEMultipeerSession stopping peer
2015-12-09 18:57:38.887 ThaliTest[622:456941] multipeer session: stop timer
,2015-12-09 18:57:38.888 ThaliTest[622:456941] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
2015-12-09 18:57:38.891 ThaliTest[622:456941] jxcore: startBroadcasting
2015-12-09 18:57:38.898 ThaliTest[622:456941] server: starting 1449683858891.622.UP18cA==
2015-12-09 18:57:38.899 ThaliTe,st[622:456941] multipeer session: start timer: 0x179429e0
2015-12-09 18:57:38.899 ThaliTest[622:456941] THEMultipeerSession initialized peer 1449683858891.622
2015-12-09 18:57:38.900 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 51 Should ,be able to call startBroadcasting without error
,2015-12-09 18:57:38.902 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:57:38.906 ThaliTest[622:456941] THEMultipeerSession stopping peer
2015-12-09 18:57:38.906 ThaliTest[622:456941] multipeer session: stop timer
2015-12-09 18:57:38.907 Th,aliTest[622:456941] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2015-12-09 18:57:38.909 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:38.916 ThaliTest[622:456941] server: starting 1449683858909.622.wBYRxw==
2015-12-09 18:57:38.917 ThaliTest[622:456941] multipeer session: start timer: 0x15ed0c50
2015-12-09 18:57:38.918 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683858909.622
2015-12-09 18:57:38.918 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2015-12-09 18:57:38.920 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18,:57:38.920 ThaliTest[622:456941] THEMultipeerSession stopping peer
2015-12-09 18:57:38.920 ThaliTest[622:456941] multipeer session: stop timer
2015-12-09 18:57:38.920 ThaliTest[622:456941] jxcore: stopBroadcasting: success
ok 54 Should be able to call s,topBroadcasting without error
2015-12-09 18:57:38.922 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:38.931 ThaliTest[622:456941] server: starting 1449683858921.622.LEdkfw==
2015-12-09 18:57:38.934 ThaliTest[622:456941] multipeer session: start timer: 0x15ed2ec0
,2015-12-09 18:57:38.934 ThaliTest[622:456941] THEMultipeerSession initialized peer 1449683858921.622
2015-12-09 18:57:38.937 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2015-12-09, 18:57:38.939 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:57:38.939 ThaliTest[622:456941] THEMultipeerSession stopping peer
2015-12-09 18:57:38.939 ThaliTest[622:456941] multipeer session: stop timer
2015-12-09 18:57:38.939 ThaliTest[62,2:456941] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
2015-12-09 18:57:38.941 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:38.947 ThaliTest[622:456941] server: starting 1449683858940.622.N32JUQ==
2015-12-09 18:57:38.948 ThaliTest[622:456941] multipeer session: start timer: 0x15ed39f0
2015-12-09 18:57:38.948 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683858940.622
2015-12-09 18:57:38.948 ThaliTest[622:456941] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-09 18:57:38.959 ThaliTest[622:456941] jxcore: stopBroadcasting
,2015-12-09 18:57:38.960 ThaliTest[622:456941] THEMultipeerSession stopping peer
,2015-12-09 18:57:38.960 ThaliTest[622:456941] multipeer session: stop timer
,2015-12-09 18:57:38.962 ThaliTest[622:456941] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:38.966 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:38.970 ThaliTest[622:456941] server: starting 1449683858966.622.Rd7xow==
,2015-12-09 18:57:38.971 ThaliTest[622:456941] multipeer session: start timer: 0x1793f8b0
,2015-12-09 18:57:38.976 ThaliTest[622:456941] THEMultipeerSession initialized peer 1449683858966.622
,2015-12-09 18:57:38.979 ThaliTest[622:456941] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-09 18:57:38.983 ThaliTest[622:456941] jxcore: stopBroadcasting
,2015-12-09 18:57:38.984 ThaliTest[622:456941] THEMultipeerSession stopping peer
,2015-12-09 18:57:38.985 ThaliTest[622:456941] multipeer session: stop timer
,2015-12-09 18:57:38.986 ThaliTest[622:456941] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:38.994 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:38.998 ThaliTest[622:456941] server: starting 1449683858994.622.zkEq3A==
,2015-12-09 18:57:39.000 ThaliTest[622:456941] multipeer session: start timer: 0x15ed2f70
,2015-12-09 18:57:39.006 ThaliTest[622:456941] THEMultipeerSession initialized peer 1449683858994.622
,2015-12-09 18:57:39.010 ThaliTest[622:456941] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-09 18:57:39.019 ThaliTest[622:456941] jxcore: stopBroadcasting
,2015-12-09 18:57:39.027 ThaliTest[622:456941] THEMultipeerSession stopping peer
,2015-12-09 18:57:39.030 ThaliTest[622:456941] multipeer session: stop timer
,2015-12-09 18:57:39.034 ThaliTest[622:456941] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-09 18:57:39.039 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:39.042 ThaliTest[622:456941] server: starting 1449683859039.622.PqHBLQ==
,2015-12-09 18:57:39.043 ThaliTest[622:456941] multipeer session: start timer: 0x179444b0
,2015-12-09 18:57:39.044 ThaliTest[622:456941] THEMultipeerSession initialized peer 1449683859039.622
,2015-12-09 18:57:39.049 ThaliTest[622:456941] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-09 18:57:39.051 ThaliTest[622:456941] jxcore: stopBroadcasting
,2015-12-09 18:57:39.052 ThaliTest[622:456941] THEMultipeerSession stopping peer
,2015-12-09 18:57:39.053 ThaliTest[622:456941] multipeer session: stop timer
,2015-12-09 18:57:39.054 ThaliTest[622:456941] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-09 18:57:39.777 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:39.781 ThaliTest[622:456941] server: starting 1449683859776.622.KSmpvQ==
2015-12-09 18:57:39.782 ThaliTest[622:456941] multipeer session: start timer: 0x17947360
2015-12-09 18:57:39.782 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683859776.622
2015-12-09 18:57:39.782 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2015-12-09 18:57:39.786 ThaliTest[622:456941] jxcore: startBroadcasting
2015-12-09 1,8:57:39.786 ThaliTest[622:456941] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2015-12-09 18:57:39.789 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:57:39.790 ThaliTest[622:456941] THEMultipeerSession stopp,ing peer
2015-12-09 18:57:39.790 ThaliTest[622:456941] multipeer session: stop timer
2015-12-09 18:57:39.790 ThaliTest[622:456941] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-09 18:57:40.459 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:40.463 ThaliTest[622:456941] server: starting 1449683860458.622.THrYew==
2015-12-09 18:57:40.464 ThaliTest[622:456941] multipeer session: start timer: 0x15ed6750
2015-12-09 18:57:40.464 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683860458.622
2015-12-09 18:57:40.465 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2015-12-09 18:57:40.468 ThaliTest[622:456941] jxcore: connect foobar
2015-12-09 18:5,7:40.469 ThaliTest[622:456941] client: unknown peer foobar
2015-12-09 18:57:40.469 ThaliTest[622:456941] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2015-12-09 18:57:40.472 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:57:40.472 ThaliTest[622:456941] THEMultipeerSession stopping peer
,2015-12-09 18:57:40.473 ThaliTest[622:456941] multipeer session: stop timer
,2015-12-09 18:57:40.474 ThaliTest[622:456941] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-09 18:57:41.429 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:41.433 ThaliTest[622:456941] server: starting 1449683861429.622.iFagcQ==
2015-12-09 18:57:41.434 ThaliTest[622:456941] multipeer session: start timer: 0x15ed96a0
2015-12-09 18:57:41.434 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683861429.622
2015-12-09 18:57:41.435 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-09 18:57:41.438 ThaliTest[622:456941] jxcore: disconnect
2015-12-09 18:57:41,.438 ThaliTest[622:456941] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2015-12-09 18:57:41.441 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:57:41.441 ThaliTest[622:456941] THEMultipeerSession stopping pe,er
2015-12-09 18:57:41.441 ThaliTest[622:456941] multipeer session: stop timer
2015-12-09 18:57:41.442 ThaliTest[622:456941] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-09 18:57:42.381 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:42.385 ThaliTest[622:456941] server: starting 1449683862381.622.vuGzaA==
2015-12-09 18:57:42.386 ThaliTest[622:456941] multipeer session: start timer: 0x15edc500
2015-12-09 18:57:42.387 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683862381.622
2015-12-09 18:57:42.387 ThaliTest[622:456941] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error
,2015-12-09 18:57:43.653 ThaliTest[622:456706] client: found peer: 1449683863444.644.Ac9XDg==
,2015-12-09 18:57:43.657 ThaliTest[622:456941] jxcore: connect 1449683863444.644.Ac9XDg==
2015-12-09 18:57:43.658 ThaliTest[622:456941] client session: connect
2015-12-09 18:57:43.659 ThaliTest[622:456941] client session: stateChange:0->1 1449683863444.644.Ac9XDg==
,2015-12-09 18:57:44.315 ThaliTest[622:456706] multipeer session: reset timer
2015-12-09 18:57:44.315 ThaliTest[622:456706] multipeer session: stop timer
2015-12-09 18:57:44.316 ThaliTest[622:456706] multipeer session: start timer: 0x15edc500
2015-12-09 ,18:57:44.316 ThaliTest[622:456706] server session: connect
2015-12-09 18:57:44.317 ThaliTest[622:456706] server session: stateChange:0->1 1449683863444.644
,2015-12-09 18:57:44.329 ThaliTest[622:456706] server: accepting invitation 1449683863444.644
,2015-12-09 18:57:47.529 ThaliTest[622:457494] server session: connected
2015-12-09 18:57:47.529 ThaliTest[622:457494] server session: stateChange:1->2 1449683863444.644
,2015-12-09 18:57:47.546 ThaliTest[622:456706] server relay: socket disconnected
,2015-12-09 18:57:47.546 ThaliTest[622:456706] server relay: 0x15ee21e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-09 18:57:47.917 ThaliTest[622:457509] server session: not connected 1449683863444.644
,2015-12-09 18:57:47.978 ThaliTest[622:457509] client session: connected
2015-12-09 18:57:47.978 ThaliTest[622:457509] client session: stateChange:1->2 1449683863444.644.Ac9XDg==
,2015-12-09 18:57:47.991 ThaliTest[622:457500] client session: fireConnectCallback: 1449683863444.644.Ac9XDg==
2015-12-09 18:57:47.991 ThaliTest[622:457500] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-09 18:57:47.997 ThaliTest[622:456941] jxcore: disconnect
,2015-12-09 18:57:47.999 ThaliTest[622:456941] client session: disconnectFromPeer: 1449683863444.644.Ac9XDg==
2015-12-09 18:57:47.999 ThaliTest[622:456941] client session: disconnect
2015-12-09 18:57:48.000 ThaliTest[622:456941] client session: stateChang,e:2->0 1449683863444.644.Ac9XDg==
,2015-12-09 18:57:48.086 ThaliTest[622:456941] jxcore: disconnect: success
,ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-09 18:57:48.279 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:57:48.280 ThaliTest[622:456941] THEMultipeerSession stopping peer
2015-12-09 18:57:48.280 ThaliTest[622:456941] multipeer session: stop timer
2015-12-09 18:57:48.281 Th,aliTest[622:456941] server session: disconnect
2015-12-09 18:57:48.281 ThaliTest[622:456941] server session: stateChange:2->0 1449683863444.644
2015-12-09 18:57:48.282 ThaliTest[622:456941] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-09 18:57:49.672 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:49.676 ThaliTest[622:456941] server: starting 1449683869672.622.QYm7ZQ==
2015-12-09 18:57:49.677 ThaliTest[622:456941] multipeer session: start timer: 0x15ee7aa0
2015-12-09 18:57:49.678 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683869672.622
2015-12-09 18:57:49.678 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2015-12-09 18:57:51.050 ThaliTest[622:456706] multipeer session: reset timer
2015-12-09 18:57:51.051 ThaliTest[622:456706] multipeer session: stop timer
2015-12-09 18:57:51.051 ThaliTest[622:456706] multipeer session: start timer: 0x15ee7aa0
,2015-12-09 18:57:51.051 ThaliTest[622:456706] server session: connect
,2015-12-09 18:57:51.053 ThaliTest[622:456706] server session: stateChange:0->1 1449683870966.644
,2015-12-09 18:57:51.063 ThaliTest[622:456706] server: accepting invitation 1449683870966.644
,2015-12-09 18:57:51.066 ThaliTest[622:456706] client: found peer: 1449683870966.644./y0MMw==
2015-12-09 18:57:51.071 ThaliTest[622:456941] jxcore: connect 1449683870966.644./y0MMw==
,2015-12-09 18:57:51.085 ThaliTest[622:456941] client session: connect
,2015-12-09 18:57:51.086 ThaliTest[622:456941] client session: stateChange:0->1 1449683870966.644./y0MMw==
,2015-12-09 18:57:53.844 ThaliTest[622:457506] server session: connected
2015-12-09 18:57:53.844 ThaliTest[622:457506] server session: stateChange:1->2 1449683870966.644
,2015-12-09 18:57:53.848 ThaliTest[622:457494] client session: connected
2015-12-09 18:57:53.848 ThaliTest[622:457494] client session: stateChange:1->2 1449683870966.644./y0MMw==
,2015-12-09 18:57:53.882 ThaliTest[622:457494] client session: fireConnectCallback: 1449683870966.644./y0MMw==
2015-12-09 18:57:53.882 ThaliTest[622:457494] jxcore: connect: success
,2015-12-09 18:57:53.885 ThaliTest[622:456706] server relay: socket disconnected
2015-12-09 18:57:53.886 ThaliTest[622:456706] server relay: 0x1795dc00 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
ok 79 Should be able to connect without error
,ok 80 Port should be within range
,2015-12-09 18:57:53.892 ThaliTest[622:456941] jxcore: connect 1449683870966.644./y0MMw==
2015-12-09 18:57:53.892 ThaliTest[622:456941] client: already connect(ing/ed) to 1449683870966.644./y0MMw==
2015-12-09 18:57:53.893 ThaliTest[622:456941] jxcore: con,nect: fail: Aleady connecting
ok 81 Should fail on double connect
,2015-12-09 18:57:53.895 ThaliTest[622:456941] jxcore: disconnect
,2015-12-09 18:57:53.897 ThaliTest[622:456941] client session: disconnectFromPeer: 1449683870966.644./y0MMw==
2015-12-09 18:57:53.898 ThaliTest[622:456941] client session: disconnect
2015-12-09 18:57:53.899 ThaliTest[622:456941] client session: stateChang,e:2->0 1449683870966.644./y0MMw==
,2015-12-09 18:57:53.916 ThaliTest[622:456941] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,2015-12-09 18:57:53.932 ThaliTest[622:457506] server session: not connected 1449683870966.644
,# setup
,calling stopBroadcasting
,2015-12-09 18:57:54.106 ThaliTest[622:456941] jxcore: stopBroadcasting
,2015-12-09 18:57:54.106 ThaliTest[622:456941] THEMultipeerSession stopping peer
,2015-12-09 18:57:54.107 ThaliTest[622:456941] multipeer session: stop timer
,2015-12-09 18:57:54.108 ThaliTest[622:456941] server session: disconnect
2015-12-09 18:57:54.109 ThaliTest[622:456941] server session: stateChange:2->0 1449683870966.644
,2015-12-09 18:57:54.113 ThaliTest[622:456941] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-09 18:57:55.092 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:57:55.096 ThaliTest[622:456941] server: starting 1449683875092.622.6ELNYA==
2015-12-09 18:57:55.097 ThaliTest[622:456941] multipeer session: start timer: 0x15eebc80
2015-12-09 18:57:55.098 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683875092.622
2015-12-09 18:57:55.098 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2015-12-09 18:57:55.798 ThaliTest[622:456706] client: found peer: 1449683876137.644.Z5FaWQ==
,2015-12-09 18:57:55.801 ThaliTest[622:456941] jxcore: connect 1449683876137.644.Z5FaWQ==
2015-12-09 18:57:55.802 ThaliTest[622:456941] client session: connect
2015-12-09 18:57:55.802 ThaliTest[622:456941] client session: stateChange:0->1 1449683876137.644.Z5FaWQ==
,2015-12-09 18:57:56.424 ThaliTest[622:456706] multipeer session: reset timer
2015-12-09 18:57:56.424 ThaliTest[622:456706] multipeer session: stop timer
2015-12-09 18:57:56.425 ThaliTest[622:456706] multipeer session: start timer: 0x15eebc80
2015-12-09 ,18:57:56.425 ThaliTest[622:456706] server session: connect
2015-12-09 18:57:56.425 ThaliTest[622:456706] server session: stateChange:0->1 1449683876137.644
,2015-12-09 18:57:56.434 ThaliTest[622:456706] server: accepting invitation 1449683876137.644
,2015-12-09 18:57:59.119 ThaliTest[622:457494] client session: connected
2015-12-09 18:57:59.120 ThaliTest[622:457494] client session: stateChange:1->2 1449683876137.644.Z5FaWQ==
,2015-12-09 18:57:59.144 ThaliTest[622:457499] client session: fireConnectCallback: 1449683876137.644.Z5FaWQ==
2015-12-09 18:57:59.145 ThaliTest[622:457499] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be withi,n range
2015-12-09 18:57:59.149 ThaliTest[622:456941] jxcore: disconnect
2015-12-09 18:57:59.149 ThaliTest[622:456941] client session: disconnectFromPeer: 1449683876137.644.Z5FaWQ==
,2015-12-09 18:57:59.150 ThaliTest[622:456941] client session: disconnect
2015-12-09 18:57:59.150 ThaliTest[622:456941] client session: stateChange:2->0 1449683876137.644.Z5FaWQ==
,2015-12-09 18:57:59.163 ThaliTest[622:456941] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
,2015-12-09 18:57:59.169 ThaliTest[622:456941] jxcore: disconnect
,2015-12-09 18:57:59.170 ThaliTest[622:456941] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
,setting stopBroadcasting callback and ending test.
,# setup
,2015-12-09 18:57:59.319 ThaliTest[622:457499] server session: connected
,2015-12-09 18:57:59.319 ThaliTest[622:457499] server session: stateChange:1->2 1449683876137.644
,2015-12-09 18:57:59.382 ThaliTest[622:456706] server relay: socket disconnected
,2015-12-09 18:57:59.384 ThaliTest[622:456706] server relay: 0x15eef830 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-09 18:57:59.394 ThaliTest[622:457499] server session: not connected 1449683876137.644
,calling stopBroadcasting
,2015-12-09 18:57:59.809 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:57:59.809 ThaliTest[622:456941] THEMultipeerSession stopping peer
2015-12-09 18:57:59.809 ThaliTest[622:456941] multipeer session: stop timer
2015-12-09 18:57:59.810 Th,aliTest[622:456941] server session: disconnect
2015-12-09 18:57:59.810 ThaliTest[622:456941] server session: stateChange:2->0 1449683876137.644
2015-12-09 18:57:59.812 ThaliTest[622:456941] jxcore: stopBroadcasting: success
stopBroadcasting returned und,efined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-09 18:58:00.875 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:58:00.880 ThaliTest[622:456941] server: starting 1449683880874.622.t8LlVA==
2015-12-09 18:58:00.882 ThaliTest[622:456941] multipeer session: start timer: 0x179500e0
2015-12-09 18:58:00.883 ThaliTest[622:456941] THEMultipeerSession initializ,ed peer 1449683880874.622
2015-12-09 18:58:00.884 ThaliTest[622:456941] jxcore: startBroadcasting: success
,ok 88 Should be able to call startBroadcasting without error
,echo server started
,2015-12-09 18:58:02.127 ThaliTest[622:456706] multipeer session: reset timer
2015-12-09 18:58:02.127 ThaliTest[622:456706] multipeer session: stop timer
2015-12-09 18:58:02.128 ThaliTest[622:456706] multipeer session: start timer: 0x179500e0
2015-12-09 ,18:58:02.128 ThaliTest[622:456706] server session: connect
2015-12-09 18:58:02.128 ThaliTest[622:456706] server session: stateChange:0->1 1449683882113.644
,2015-12-09 18:58:02.140 ThaliTest[622:456706] server: accepting invitation 1449683882113.644
,2015-12-09 18:58:02.149 ThaliTest[622:456706] client: found peer: 1449683882113.644.Gl5U4g==
[{"peerIdentifier":"1449683882113.644.Gl5U4g==","peerName":"(null)","peerAvailable":true}]
,2015-12-09 18:58:02.153 ThaliTest[622:456941] jxcore: connect 1449683882113.644.Gl5U4g==
2015-12-09 18:58:02.158 ThaliTest[622:456941] client session: connect
2015-12-09 18:58:02.158 ThaliTest[622:456941] client session: stateChange:0->1 1449683882113.64,4.Gl5U4g==
,2015-12-09 18:58:04.851 ThaliTest[622:457499] server session: connected
2015-12-09 18:58:04.853 ThaliTest[622:457499] server session: stateChange:1->2 1449683882113.644
,2015-12-09 18:58:04.864 ThaliTest[622:456706] server relay: connected (to port: 5001)
,2015-12-09 18:58:05.015 ThaliTest[622:457499] server session: not connected 1449683882113.644
,2015-12-09 18:58:05.142 ThaliTest[622:456706] multipeer session: reset timer
2015-12-09 18:58:05.142 ThaliTest[622:456706] multipeer session: stop timer
2015-12-09 18:58:05.143 ThaliTest[622:456706] multipeer session: start timer: 0x179500e0
,2015-12-09 18:58:05.143 ThaliTest[622:456706] server: disconnecting to refresh session (1449683882113.644)
,2015-12-09 18:58:05.143 ThaliTest[622:456706] server session: disconnect
,2015-12-09 18:58:05.144 ThaliTest[622:456706] server session: stateChange:2->0 1449683882113.644
,2015-12-09 18:58:05.151 ThaliTest[622:456706] server session: connect
2015-12-09 18:58:05.152 ThaliTest[622:456706] server session: stateChange:0->1 1449683882113.644
,2015-12-09 18:58:05.179 ThaliTest[622:456706] server: accepting invitation 1449683882113.644
,2015-12-09 18:58:05.316 ThaliTest[622:457562] client session: connected
2015-12-09 18:58:05.316 ThaliTest[622:457562] client session: stateChange:1->2 1449683882113.644.Gl5U4g==
2015-12-09 18:58:05.323 ThaliTest[622:457562] client session: fireConnectCallback: 1449683882113.644.Gl5U4g==
2015-12-09 18:58:05.324 ThaliTest[622:457562] jxcore: connect: success
,ok 89 Should be able to connect without error
ok 90 Port should be within range
ok 91 First connect should succeed
,2015-12-09 18:58:05.374 ThaliTest[622:456706] client: relay established
2015-12-09 18:58:05.374 ThaliTest[622:456706] client: new accepted socket: 0x15e2ddd0
,ok 92 the test messages should be equal
ok 93 First send should succeed
,2015-12-09 18:58:05.451 ThaliTest[622:456706] client: socket closed
2015-12-09 18:58:05.451 ThaliTest[622:456706] client relay: socket disconnected
2015-12-09 18:58:05.451 ThaliTest[622:456706] client relay: 0x15e2ddd0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-09 18:58:05.451 ThaliTest[622:456706] client session: socket closed: 1449683882113.644.Gl5U4g==
2015-12-09 18:58:05.,451 ThaliTest[622:456706] client session: onLinkFailure: 1449683882113.644.Gl5U4g==
2015-12-09 18:58:05.451 ThaliTest[622:456706] client session: disconnect
2015-12-09 18:58:05.451 ThaliTest[622:456706] client session: stateChange:2->0 1449683882113.644.Gl5U4g==
,2015-12-09 18:58:05.463 ThaliTest[622:456706] client session: fireConnectionErrorEvent: 1449683882113.644.Gl5U4g==
2015-12-09 18:58:05.465 ThaliTest[622:456941] jxcore: connect 1449683882113.644.Gl5U4g==
2015-12-09 18:58:05.465 ThaliTest[622:456941] client session: connect
2015-12-09 18:58:05.465 ThaliTest[622:456941] client session: stateChange:0->1 1449683882113.644.Gl5U4g==
,2015-12-09 18:58:08.210 ThaliTest[622:457494] server session: connected
2015-12-09 18:58:08.211 ThaliTest[622:457494] server session: stateChange:1->2 1449683882113.644
,2015-12-09 18:58:08.455 ThaliTest[622:456706] server relay: connected (to port: 5001)
,2015-12-09 18:58:08.559 ThaliTest[622:457506] server session: not connected 1449683882113.644
,2015-12-09 18:58:08.618 ThaliTest[622:457603] client session: connected
,2015-12-09 18:58:08.619 ThaliTest[622:457603] client session: stateChange:1->2 1449683882113.644.Gl5U4g==
,2015-12-09 18:58:08.627 ThaliTest[622:457603] client session: fireConnectCallback: 1449683882113.644.Gl5U4g==
2015-12-09 18:58:08.627 ThaliTest[622:457603] jxcore: connect: success
,ok 94 Should be able to connect without error
ok 95 Port should be within range
,ok 96 Second connect should succeed
,2015-12-09 18:58:08.667 ThaliTest[622:456706] client: relay established
2015-12-09 18:58:08.667 ThaliTest[622:456706] client: new accepted socket: 0x15efa770
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2015-12-09 18:58:08.732 ThaliTest[622:456706] client: socket closed
2015-12-09 18:58:08.732 ThaliTest[622:456706] client relay: socket disconnected
2015-12-09 18:58:08.732 ThaliTest[622:456706] client relay: 0x15efa770 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-09 18:58:08.733 ThaliTest[622:456706] client session: socket closed: 1449683882113.644.Gl5U4g==
2015-12-09 18:58:08.,733 ThaliTest[622:456706] client session: onLinkFailure: 1449683882113.644.Gl5U4g==
2015-12-09 18:58:08.733 ThaliTest[622:456706] client session: disconnect
2015-12-09 18:58:08.734 ThaliTest[622:456706] client session: stateChange:2->0 1449683882113.644.,Gl5U4g==
,2015-12-09 18:58:08.750 ThaliTest[622:456706] client session: fireConnectionErrorEvent: 1449683882113.644.Gl5U4g==
,calling stopBroadcasting
,2015-12-09 18:58:08.817 ThaliTest[622:456941] jxcore: stopBroadcasting
,2015-12-09 18:58:08.819 ThaliTest[622:456941] THEMultipeerSession stopping peer
,2015-12-09 18:58:08.820 ThaliTest[622:456941] multipeer session: stop timer
,2015-12-09 18:58:08.846 ThaliTest[622:456941] server session: disconnect
,2015-12-09 18:58:08.847 ThaliTest[622:456941] server session: stateChange:2->0 1449683882113.644
,2015-12-09 18:58:09.780 ThaliTest[622:456941] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/4AE3E50D-A6DA-440C-A0EB-3A311A8DE86C/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2015-12-09 18:58:10.374 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:58:10.376 ThaliTest[622:456941] server: starting Admg1fL6dZvo8nEnfRsfSw.1FVTxA==
2015-12-09 18:58:10.376 ThaliTest[622:456941] multipeer session: start timer: 0x1795e760
2015-12-09 18:58:10.377 ThaliTest[622:456941] THEMultipeerSession init,ialized peer Admg1fL6dZvo8nEnfRsfSw
2015-12-09 18:58:10.377 ThaliTest[622:456941] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
,Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should occur in right order
About to call stopBroadcasting
2015-12-09 18:58:10.379 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:58:10.379 ThaliTest[622:456941] THEMul,tipeerSession stopping peer
2015-12-09 18:58:10.380 ThaliTest[622:456941] multipeer session: stop timer
,2015-12-09 18:58:10.380 ThaliTest[622:456941] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
ok 102 stopped event should occur in right order
,mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/4AE3E50D-A6DA-440C-A0EB-3A311A8DE86C/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2015-12-09 18:58:10.999 ThaliTest[622:456941] jxcore: startBroadcasting
,2015-12-09 18:58:11.003 ThaliTest[622:456941] server: starting Admg1fL6dZvo8nEnfRsfSw.6OKb+g==
2015-12-09 18:58:11.004 ThaliTest[622:456941] multipeer session: start timer: 0x15e33900
2015-12-09 18:58:11.005 ThaliTest[622:456941] THEMultipeerSession initialized peer Admg1fL6dZvo8nEnfRsfSw
2015-12-09 18:58:11.005 ThaliTest[622:456941] jxcore: startBroadcasting: success
,ok 103 getDeviceIdentity should not return an error
,ok 104 deviceName should not be null
Now in TRM stop
State of this._isStarted: true
About to call stopBroadcasting
2015-12-09 18:58:11.008 ThaliTest[622:456941] jxcore: stopBroadcasting
2015-12-09 18:58:11.009 ThaliTest[622:456941] THEMultipeerSession, stopping peer
2015-12-09 18:58:11.009 ThaliTest[622:456941] multipeer session: stop timer
2015-12-09 18:58:11.009 ThaliTest[622:456941] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,mux server bridge listener closed
Tests Complete

```
