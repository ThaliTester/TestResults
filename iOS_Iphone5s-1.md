#### Test 50650278c0f6ec2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c0f6ec2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/CCD90577-EE8B-4975-AAC3-5E8232C9F7E7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CCD90577-EE8B-4975-AAC3-5E8232C9F7E7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c0f6ec2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c0f6ec2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F40BE68F-036B-40F6-B884-AEBAC47F4578/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53122"
,(lldb)     command script import "/tmp/CCD90577-EE8B-4975-AAC3-5E8232C9F7E7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 12:55:46.852 ThaliTest[677:563147] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1649CD04-5B1B-4DD2-981A-FDC200080B88/Library/Cookies/Cookies.binarycookies
,2015-12-10 12:55:47.286 ThaliTest[677:563147] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 12:55:47.288 ThaliTest[677:563147] Multi-tasking -> Device: YES, App: YES
,2015-12-10 12:55:47.297 ThaliTest[677:563147] Unlimited access to network resources
,2015-12-10 12:55:47.310 ThaliTest[677:563147] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 12:55:55.245 ThaliTest[677:563147] Resetting plugins due to page load.
,2015-12-10 12:55:58.286 ThaliTest[677:563147] Finished load of: file:///var/mobile/Containers/Bundle/Application/F40BE68F-036B-40F6-B884-AEBAC47F4578/ThaliTest.app/www/index.html
,2015-12-10 12:55:58.488 ThaliTest[677:563147] JXcore Cordova plugin initializing
2015-12-10 12:55:58.490 ThaliTest[677:563359] JXcore instance initializing
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
,2015-12-10 13:01:01.615 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:01.632 ThaliTest[677:563359] server: starting 1449748861614.677.uchxxQ==
,2015-12-10 13:01:01.633 ThaliTest[677:563359] multipeer session: start timer: 0x1b12db50
2015-12-10 13:01:01.634 ThaliTest[677:563359] THEMultipeerSession initialized peer 1449748861614.677
,2015-12-10 13:01:01.635 ThaliTest[677:563359] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-10 13:01:01.642 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:01.644 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:01.644 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:01.653 Th,aliTest[677:563359] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2015-12-10 13:01:01.659 ThaliTest[677:563359] jxcore: startBroadcasting
2015-12-10 13:01:01.668 ThaliTest[677:563359] server: starting 1449748861656.677.qwrKeQ==
,2015-12-10 13:01:01.671 ThaliTest[677:563359] multipeer session: start timer: 0x1b12eb40
2015-12-10 13:01:01.671 ThaliTest[677:563359] THEMultipeerSession initialized peer 1449748861656.677
2015-12-10 13:01:01.671 ThaliTest[677:563359] jxcore: startBroad,casting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-10 13:01:01.674 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:01.675 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:01.675, ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:01.675 ThaliTest[677:563359] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2015-12-10 13:01:01.679 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:01.690 ThaliTest[677:563359] server: starting 1449748861678.677.8uxhkw==
2015-12-10 13:01:01.691 ThaliTest[677:563359] multipeer session: start timer: 0x1b1305e0
2015-12-10 13:01:01.692 ThaliTest[677:563359] THEMultipeerSession initializ,ed peer 1449748861678.677
2015-12-10 13:01:01.692 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2015-12-10 13:01:01.694 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13,:01:01.694 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:01.695 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:01.695 ThaliTest[677:563359] jxcore: stopBroadcasting: success
ok 50 Should be able to call s,topBroadcasting without error
2015-12-10 13:01:01.697 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:01.705 ThaliTest[677:563359] server: starting 1449748861697.677.9DXmCA==
2015-12-10 13:01:01.706 ThaliTest[677:563359] multipeer session: start timer: 0x197878a0
2015-12-10 13:01:01.707 ThaliTest[677:563359] THEMultipeerSession initializ,ed peer 1449748861697.677
2015-12-10 13:01:01.707 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-10 13:01:01.709 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13,:01:01.709 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:01.710 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:01.710 ThaliTest[677:563359] jxcore: stopBroadcasting: success
ok 52 Should be able to call s,topBroadcasting without error
2015-12-10 13:01:01.712 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:01.720 ThaliTest[677:563359] server: starting 1449748861712.677.PvzJvA==
2015-12-10 13:01:01.720 ThaliTest[677:563359] multipeer session: start timer: 0x197892e0
2015-12-10 13:01:01.721 ThaliTest[677:563359] THEMultipeerSession initializ,ed peer 1449748861712.677
2015-12-10 13:01:01.721 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2015-12-10 13:01:01.723 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:01.723 ThaliTest[677:563359] THEMultipeerSession stopping peer
,2015-12-10 13:01:01.724 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:01.724 ThaliTest[677:563359] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
2015-12-10 13:01:01.726 ThaliTest[677:563359] jxcore: startBroadcasting
2015-12-10 13:01:01.730 ThaliTest[677:563359] server: starting 1449748861726.677.mBcjLQ==
2015-12-10 13:01:01.731 ThaliTe,st[677:563359] multipeer session: start timer: 0x1b132470
2015-12-10 13:01:01.731 ThaliTest[677:563359] THEMultipeerSession initialized peer 1449748861726.677
2015-12-10 13:01:01.731 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 55 Should ,be able to call startBroadcasting without error
2015-12-10 13:01:01.733 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:01.733 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:01.733 ThaliTest[677:563359] multipee,r session: stop timer
2015-12-10 13:01:01.734 ThaliTest[677:563359] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
2015-12-10 13:01:01.735 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:01.742 ThaliTest[677:563359] server: starting 1449748861735.677.jddP1g==
,2015-12-10 13:01:01.747 ThaliTest[677:563359] multipeer session: start timer: 0x1978a370
,2015-12-10 13:01:01.753 ThaliTest[677:563359] THEMultipeerSession initialized peer 1449748861735.677
,2015-12-10 13:01:01.755 ThaliTest[677:563359] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-10 13:01:01.760 ThaliTest[677:563359] jxcore: stopBroadcasting
,2015-12-10 13:01:01.762 ThaliTest[677:563359] THEMultipeerSession stopping peer
,2015-12-10 13:01:01.766 ThaliTest[677:563359] multipeer session: stop timer
,2015-12-10 13:01:01.770 ThaliTest[677:563359] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-10 13:01:01.774 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:01.782 ThaliTest[677:563359] server: starting 1449748861774.677.lHcvEA==
,2015-12-10 13:01:01.804 ThaliTest[677:563359] multipeer session: start timer: 0x1978a370
,2015-12-10 13:01:01.808 ThaliTest[677:563359] THEMultipeerSession initialized peer 1449748861774.677
,2015-12-10 13:01:01.811 ThaliTest[677:563359] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-10 13:01:01.815 ThaliTest[677:563359] jxcore: stopBroadcasting
,2015-12-10 13:01:01.816 ThaliTest[677:563359] THEMultipeerSession stopping peer
,2015-12-10 13:01:01.817 ThaliTest[677:563359] multipeer session: stop timer
,2015-12-10 13:01:01.818 ThaliTest[677:563359] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-10 13:01:01.824 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:01.826 ThaliTest[677:563359] server: starting 1449748861823.677.3AUMHA==
,2015-12-10 13:01:01.828 ThaliTest[677:563359] multipeer session: start timer: 0x197881a0
,2015-12-10 13:01:01.830 ThaliTest[677:563359] THEMultipeerSession initialized peer 1449748861823.677
,2015-12-10 13:01:01.835 ThaliTest[677:563359] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-10 13:01:01.838 ThaliTest[677:563359] jxcore: stopBroadcasting
,2015-12-10 13:01:01.839 ThaliTest[677:563359] THEMultipeerSession stopping peer
,2015-12-10 13:01:01.840 ThaliTest[677:563359] multipeer session: stop timer
,2015-12-10 13:01:01.842 ThaliTest[677:563359] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-10 13:01:01.847 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:01.851 ThaliTest[677:563359] server: starting 1449748861846.677.ruFISA==
,2015-12-10 13:01:01.857 ThaliTest[677:563359] multipeer session: start timer: 0x1978a430
,2015-12-10 13:01:01.860 ThaliTest[677:563359] THEMultipeerSession initialized peer 1449748861846.677
,2015-12-10 13:01:01.862 ThaliTest[677:563359] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-10 13:01:01.865 ThaliTest[677:563359] jxcore: stopBroadcasting
,2015-12-10 13:01:01.865 ThaliTest[677:563359] THEMultipeerSession stopping peer
,2015-12-10 13:01:01.866 ThaliTest[677:563359] multipeer session: stop timer
,2015-12-10 13:01:01.868 ThaliTest[677:563359] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2015-12-10 13:01:02.509 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:02.513 ThaliTest[677:563359] server: starting 1449748862508.677.ruJPHg==
2015-12-10 13:01:02.514 ThaliTest[677:563359] multipeer session: start timer: 0x19788970
2015-12-10 13:01:02.515 ThaliTest[677:563359] THEMultipeerSession initializ,ed peer 1449748862508.677
2015-12-10 13:01:02.515 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2015-12-10 13:01:02.518 ThaliTest[677:563359] jxcore: startBroadcasting
2015-12-10 1,3:01:02.518 ThaliTest[677:563359] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2015-12-10 13:01:02.522 ThaliTest[677:563359] jxcore: stopBroadcasting
,2015-12-10 13:01:02.522 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:02.523 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:02.523 ThaliTest[677:563359] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2015-12-10 13:01:06.463 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:06.467 ThaliTest[677:563359] server: starting 1449748866463.677.KoNYRg==
2015-12-10 13:01:06.468 ThaliTest[677:563359] multipeer session: start timer: 0x1b138b40
2015-12-10 13:01:06.469 ThaliTest[677:563359] THEMultipeerSession initializ,ed peer 1449748866463.677
2015-12-10 13:01:06.469 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
,2015-12-10 13:01:06.489 ThaliTest[677:563359] jxcore: connect foobar
,2015-12-10 13:01:06.491 ThaliTest[677:563359] client: unknown peer foobar
,2015-12-10 13:01:06.493 ThaliTest[677:563359] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2015-12-10 13:01:06.499 ThaliTest[677:563359] jxcore: stopBroadcasting
,2015-12-10 13:01:06.501 ThaliTest[677:563359] THEMultipeerSession stopping peer
,2015-12-10 13:01:06.504 ThaliTest[677:563359] multipeer session: stop timer
,2015-12-10 13:01:06.513 ThaliTest[677:563359] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2015-12-10 13:01:07.942 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:07.946 ThaliTest[677:563359] server: starting 1449748867941.677.grPasQ==
2015-12-10 13:01:07.947 ThaliTest[677:563359] multipeer session: start timer: 0x19790bf0
2015-12-10 13:01:07.947 ThaliTest[677:563359] THEMultipeerSession initializ,ed peer 1449748867941.677
2015-12-10 13:01:07.947 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2015-12-10 13:01:07.950 ThaliTest[677:563359] jxcore: disconnect
2015-12-10 13:01:07,.950 ThaliTest[677:563359] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
2015-12-10 13:01:07.953 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:07.953 ThaliTest[677:563359] THEMultipeerSession stopping pe,er
2015-12-10 13:01:07.953 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:07.954 ThaliTest[677:563359] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2015-12-10 13:01:08.869 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:08.873 ThaliTest[677:563359] server: starting 1449748868868.677.tgjAXw==
2015-12-10 13:01:08.874 ThaliTest[677:563359] multipeer session: start timer: 0x197931b0
2015-12-10 13:01:08.874 ThaliTest[677:563359] THEMultipeerSession initializ,ed peer 1449748868868.677
2015-12-10 13:01:08.874 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2015-12-10 13:01:10.223 ThaliTest[677:563147] multipeer session: reset timer
2015-12-10 13:01:10.223 ThaliTest[677:563147] multipeer session: stop timer
2015-12-10 13:01:10.224 ThaliTest[677:563147] multipeer session: start timer: 0x197931b0
2015-12-10 ,13:01:10.225 ThaliTest[677:563147] server session: connect
2015-12-10 13:01:10.225 ThaliTest[677:563147] server session: stateChange:0->1 1449748868629.575
,2015-12-10 13:01:10.236 ThaliTest[677:563147] server: accepting invitation 1449748868629.575
,2015-12-10 13:01:10.981 ThaliTest[677:563147] client: found peer: 1449748868629.575.O1KCeA==
,2015-12-10 13:01:10.984 ThaliTest[677:563359] jxcore: connect 1449748868629.575.O1KCeA==
2015-12-10 13:01:10.986 ThaliTest[677:563359] client session: connect
2015-12-10 13:01:10.986 ThaliTest[677:563359] client session: stateChange:0->1 1449748868629.575.O1KCeA==
,2015-12-10 13:01:12.926 ThaliTest[677:563879] server session: connected
2015-12-10 13:01:12.927 ThaliTest[677:563879] server session: stateChange:1->2 1449748868629.575
2015-12-10 13:01:12.936 ThaliTest[677:563147] server relay: socket disconnected
2015,-12-10 13:01:12.936 ThaliTest[677:563147] server relay: 0x197aa140 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 13:01:12.979 ThaliTest[677:563882] server session: not connected 1449748868629.575
,2015-12-10 13:01:13.967 ThaliTest[677:563870] client session: connected
2015-12-10 13:01:13.967 ThaliTest[677:563870] client session: stateChange:1->2 1449748868629.575.O1KCeA==
,2015-12-10 13:01:13.984 ThaliTest[677:563879] client session: fireConnectCallback: 1449748868629.575.O1KCeA==
2015-12-10 13:01:13.984 ThaliTest[677:563879] jxcore: connect: success
,ok 75 Should be able to connect without error
,ok 76 Port should be within range
,2015-12-10 13:01:13.990 ThaliTest[677:563359] jxcore: disconnect
2015-12-10 13:01:13.991 ThaliTest[677:563359] client session: disconnectFromPeer: 1449748868629.575.O1KCeA==
2015-12-10 13:01:13.992 ThaliTest[677:563359] client session: disconnect
2015-1,2-10 13:01:13.992 ThaliTest[677:563359] client session: stateChange:2->0 1449748868629.575.O1KCeA==
,2015-12-10 13:01:14.078 ThaliTest[677:563359] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
,setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2015-12-10 13:01:14.581 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:14.582 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:14.582 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:14.583 Th,aliTest[677:563359] server session: disconnect
2015-12-10 13:01:14.583 ThaliTest[677:563359] server session: stateChange:2->0 1449748868629.575
2015-12-10 13:01:14.585 ThaliTest[677:563359] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2015-12-10 13:01:16.498 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:16.503 ThaliTest[677:563359] server: starting 1449748876498.677.ONqMaQ==
2015-12-10 13:01:16.504 ThaliTest[677:563359] multipeer session: start timer: 0x197a6a90
2015-12-10 13:01:16.504 ThaliTest[677:563359] THEMultipeerSession initializ,ed peer 1449748876498.677
2015-12-10 13:01:16.505 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2015-12-10 13:01:17.815 ThaliTest[677:563147] client: found peer: 1449748876491.575.QtSv7Q==
2015-12-10 13:01:17.818 ThaliTest[677:563359] jxcore: connect 1449748876491.575.QtSv7Q==
2015-12-10 13:01:17.819 ThaliTest[677:563359] client session: connect
2,015-12-10 13:01:17.820 ThaliTest[677:563359] client session: stateChange:0->1 1449748876491.575.QtSv7Q==
,2015-12-10 13:01:18.016 ThaliTest[677:563147] multipeer session: reset timer
,2015-12-10 13:01:18.017 ThaliTest[677:563147] multipeer session: stop timer
2015-12-10 13:01:18.017 ThaliTest[677:563147] multipeer session: start timer: 0x197a6a90
,2015-12-10 13:01:18.018 ThaliTest[677:563147] server session: connect
2015-12-10 13:01:18.018 ThaliTest[677:563147] server session: stateChange:0->1 1449748876491.575
,2015-12-10 13:01:18.029 ThaliTest[677:563147] server: accepting invitation 1449748876491.575
,2015-12-10 13:01:20.642 ThaliTest[677:563935] client session: connected
2015-12-10 13:01:20.644 ThaliTest[677:563935] client session: stateChange:1->2 1449748876491.575.QtSv7Q==
,2015-12-10 13:01:20.651 ThaliTest[677:563935] client session: fireConnectCallback: 1449748876491.575.QtSv7Q==
2015-12-10 13:01:20.651 ThaliTest[677:563935] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
,2015-12-10 13:01:20.657 ThaliTest[677:563359] jxcore: connect 1449748876491.575.QtSv7Q==
,2015-12-10 13:01:20.657 ThaliTest[677:563359] client: already connect(ing/ed) to 1449748876491.575.QtSv7Q==
,2015-12-10 13:01:20.658 ThaliTest[677:563359] jxcore: connect: fail: Aleady connecting
,ok 81 Should fail on double connect
2015-12-10 13:01:20.663 ThaliTest[677:563359] jxcore: disconnect
2015-12-10 13:01:20.663 ThaliTest[677:563359] client session: disconnectFromPeer: 1449748876491.575.QtSv7Q==
2015-12-10 13:01:20.664 ThaliTest[677:56335,9] client session: disconnect
2015-12-10 13:01:20.664 ThaliTest[677:563359] client session: stateChange:2->0 1449748876491.575.QtSv7Q==
,2015-12-10 13:01:20.681 ThaliTest[677:563359] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-10 13:01:20.907 ThaliTest[677:563879] server session: connected
2015-12-10 13:01:20.908 ThaliTest[677:563879] server session: stateChange:1->2 1449748876491.575
,2015-12-10 13:01:20.915 ThaliTest[677:563147] server relay: socket disconnected
2015-12-10 13:01:20.916 ThaliTest[677:563147] server relay: 0x1b146da0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocaliz,edFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-10 13:01:21.042 ThaliTest[677:563881] server session: not connected 1449748876491.575
,calling stopBroadcasting
,2015-12-10 13:01:21.400 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:21.401 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:21.401 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:21.401 Th,aliTest[677:563359] server session: disconnect
2015-12-10 13:01:21.402 ThaliTest[677:563359] server session: stateChange:2->0 1449748876491.575
2015-12-10 13:01:21.403 ThaliTest[677:563359] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2015-12-10 13:01:37.012 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:37.015 ThaliTest[677:563359] server: starting 1449748897011.677.2n6LLw==
2015-12-10 13:01:37.016 ThaliTest[677:563359] multipeer session: start timer: 0x1978aac0
2015-12-10 13:01:37.017 ThaliTest[677:563359] THEMultipeerSession initializ,ed peer 1449748897011.677
2015-12-10 13:01:37.017 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2015-12-10 13:01:38.780 ThaliTest[677:563147] client: found peer: 1449748897198.575.+/X1sQ==
2015-12-10 13:01:38.782 ThaliTest[677:563359] jxcore: connect 1449748897198.575.+/X1sQ==
2015-12-10 13:01:38.783 ThaliTest[677:563359] client session: connect
,2015-12-10 13:01:38.783 ThaliTest[677:563359] client session: stateChange:0->1 1449748897198.575.+/X1sQ==
,2015-12-10 13:01:38.926 ThaliTest[677:563147] multipeer session: reset timer
,2015-12-10 13:01:38.926 ThaliTest[677:563147] multipeer session: stop timer
,2015-12-10 13:01:38.926 ThaliTest[677:563147] multipeer session: start timer: 0x1978aac0
,2015-12-10 13:01:38.927 ThaliTest[677:563147] server session: connect
,2015-12-10 13:01:38.928 ThaliTest[677:563147] server session: stateChange:0->1 1449748897198.575
,2015-12-10 13:01:38.939 ThaliTest[677:563147] server: accepting invitation 1449748897198.575
,2015-12-10 13:01:41.613 ThaliTest[677:563973] client session: connected
2015-12-10 13:01:41.613 ThaliTest[677:563973] client session: stateChange:1->2 1449748897198.575.+/X1sQ==
2015-12-10 13:01:41.617 ThaliTest[677:563973] client session: fireConnectCal,lback: 1449748897198.575.+/X1sQ==
2015-12-10 13:01:41.618 ThaliTest[677:563973] jxcore: connect: success
,ok 84 Should be able to connect without error
ok 85 Port should be within range
,2015-12-10 13:01:41.624 ThaliTest[677:563359] jxcore: disconnect
,2015-12-10 13:01:41.625 ThaliTest[677:563359] client session: disconnectFromPeer: 1449748897198.575.+/X1sQ==
,2015-12-10 13:01:41.626 ThaliTest[677:563359] client session: disconnect
,2015-12-10 13:01:41.627 ThaliTest[677:563359] client session: stateChange:2->0 1449748897198.575.+/X1sQ==
,2015-12-10 13:01:41.712 ThaliTest[677:563359] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error
2015-12-10 13:01:41.715 ThaliTest[677:563359] jxcore: disconnect
,2015-12-10 13:01:41.716 ThaliTest[677:563359] jxcore: disconnect: fail
,ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,2015-12-10 13:01:42.422 ThaliTest[677:563971] server session: connected
2015-12-10 13:01:42.424 ThaliTest[677:563971] server session: stateChange:1->2 1449748897198.575
,2015-12-10 13:01:42.435 ThaliTest[677:563147] server relay: socket disconnected
,2015-12-10 13:01:42.436 ThaliTest[677:563147] server relay: 0x1b1537b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,calling stopBroadcasting
,2015-12-10 13:01:42.819 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:42.819 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:42.820 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:42.820 Th,aliTest[677:563359] server session: disconnect
2015-12-10 13:01:42.821 ThaliTest[677:563359] server session: stateChange:2->0 1449748897198.575
,2015-12-10 13:01:42.855 ThaliTest[677:563359] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter handles socket disconnect correctly
,# teardown
,2015-12-10 13:01:44.399 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:44.403 ThaliTest[677:563359] server: starting 1449748904398.677.gz+LMg==
2015-12-10 13:01:44.404 ThaliTest[677:563359] multipeer session: start timer: 0x1b146fb0
2015-12-10 13:01:44.405 ThaliTest[677:563359] THEMultipeerSession initializ,ed peer 1449748904398.677
2015-12-10 13:01:44.405 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
,echo server started
,2015-12-10 13:01:45.174 ThaliTest[677:563147] client: found peer: 1449748904186.575.QU4P/w==
[{"peerIdentifier":"1449748904186.575.QU4P/w==","peerName":"(null)","peerAvailable":true}]
2015-12-10 13:01:45.182 ThaliTest[677:563359] jxcore: connect 14497489,04186.575.QU4P/w==
2015-12-10 13:01:45.183 ThaliTest[677:563359] client session: connect
2015-12-10 13:01:45.184 ThaliTest[677:563359] client session: stateChange:0->1 1449748904186.575.QU4P/w==
,2015-12-10 13:01:45.677 ThaliTest[677:563147] multipeer session: reset timer
2015-12-10 13:01:45.677 ThaliTest[677:563147] multipeer session: stop timer
2015-12-10 13:01:45.678 ThaliTest[677:563147] multipeer session: start timer: 0x1b146fb0
2015-12-10 ,13:01:45.678 ThaliTest[677:563147] server session: connect
,2015-12-10 13:01:45.679 ThaliTest[677:563147] server session: stateChange:0->1 1449748904186.575
,2015-12-10 13:01:45.694 ThaliTest[677:563147] server: accepting invitation 1449748904186.575
,2015-12-10 13:01:48.827 ThaliTest[677:563987] server session: connected
2015-12-10 13:01:48.827 ThaliTest[677:563987] server session: stateChange:1->2 1449748904186.575
,2015-12-10 13:01:48.844 ThaliTest[677:563147] server relay: connected (to port: 5001)
,2015-12-10 13:01:49.224 ThaliTest[677:563973] server session: not connected 1449748904186.575
,2015-12-10 13:01:49.279 ThaliTest[677:563147] multipeer session: reset timer
,2015-12-10 13:01:49.280 ThaliTest[677:563147] multipeer session: stop timer
,2015-12-10 13:01:49.280 ThaliTest[677:563147] multipeer session: start timer: 0x1b146fb0
2015-12-10 13:01:49.282 ThaliTest[677:563147] server: disconnecting to refresh session (1449748904186.575)
2015-12-10 13:01:49.283 ThaliTest[677:563147] server sessi,on: disconnect
2015-12-10 13:01:49.283 ThaliTest[677:563147] server session: stateChange:2->0 1449748904186.575
,2015-12-10 13:01:49.291 ThaliTest[677:563147] server session: connect
,2015-12-10 13:01:49.291 ThaliTest[677:563147] server session: stateChange:0->1 1449748904186.575
,2015-12-10 13:01:49.314 ThaliTest[677:563147] server: accepting invitation 1449748904186.575
,2015-12-10 13:01:49.381 ThaliTest[677:563987] client session: connected
,2015-12-10 13:01:49.383 ThaliTest[677:563987] client session: stateChange:1->2 1449748904186.575.QU4P/w==
,2015-12-10 13:01:49.390 ThaliTest[677:563987] client session: fireConnectCallback: 1449748904186.575.QU4P/w==
2015-12-10 13:01:49.391 ThaliTest[677:563987] jxcore: connect: success
,ok 89 Should be able to connect without error
ok 90 Port should be within range
ok 91 First connect should succeed
,2015-12-10 13:01:49.430 ThaliTest[677:563147] client: relay established
2015-12-10 13:01:49.430 ThaliTest[677:563147] client: new accepted socket: 0x1b158ee0
,ok 92 the test messages should be equal
,ok 93 First send should succeed
,2015-12-10 13:01:49.503 ThaliTest[677:563147] client: socket closed
2015-12-10 13:01:49.504 ThaliTest[677:563147] client relay: socket disconnected
2015-12-10 13:01:49.504 ThaliTest[677:563147] client relay: 0x1b158ee0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-10 13:01:49.504 ThaliTest[677:563147] client session: socket closed: 1449748904186.575.QU4P/w==
2015-12-10 13:01:49.,504 ThaliTest[677:563147] client session: onLinkFailure: 1449748904186.575.QU4P/w==
2015-12-10 13:01:49.504 ThaliTest[677:563147] client session: disconnect
2015-12-10 13:01:49.505 ThaliTest[677:563147] client session: stateChange:2->0 1449748904186.575.QU4P/w==
,2015-12-10 13:01:49.532 ThaliTest[677:563147] client session: fireConnectionErrorEvent: 1449748904186.575.QU4P/w==
,2015-12-10 13:01:49.535 ThaliTest[677:563359] jxcore: connect 1449748904186.575.QU4P/w==
,2015-12-10 13:01:49.538 ThaliTest[677:563359] client session: connect
,2015-12-10 13:01:49.541 ThaliTest[677:563359] client session: stateChange:0->1 1449748904186.575.QU4P/w==
,2015-12-10 13:01:52.415 ThaliTest[677:563987] server session: connected
2015-12-10 13:01:52.416 ThaliTest[677:563987] server session: stateChange:1->2 1449748904186.575
,2015-12-10 13:01:52.429 ThaliTest[677:563147] server relay: connected (to port: 5001)
,2015-12-10 13:01:52.608 ThaliTest[677:563988] server session: not connected 1449748904186.575
,2015-12-10 13:01:52.951 ThaliTest[677:563988] client session: connected
2015-12-10 13:01:52.951 ThaliTest[677:563988] client session: stateChange:1->2 1449748904186.575.QU4P/w==
,2015-12-10 13:01:53.009 ThaliTest[677:563971] client session: fireConnectCallback: 1449748904186.575.QU4P/w==
2015-12-10 13:01:53.009 ThaliTest[677:563971] jxcore: connect: success
ok 94 Should be able to connect without error
,ok 95 Port should be within range
,ok 96 Second connect should succeed
,2015-12-10 13:01:53.047 ThaliTest[677:563147] client: relay established
2015-12-10 13:01:53.048 ThaliTest[677:563147] client: new accepted socket: 0x1979de10
,ok 97 the test messages should be equal
,ok 98 Second send should succeed
,# setup
,2015-12-10 13:01:53.158 ThaliTest[677:563147] client: socket closed
2015-12-10 13:01:53.158 ThaliTest[677:563147] client relay: socket disconnected
2015-12-10 13:01:53.159 ThaliTest[677:563147] client relay: 0x1979de10 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-10 13:01:53.159 ThaliTest[677:563147] client session: socket closed: 1449748904186.575.QU4P/w==
2015-12-10 13:01:53.,159 ThaliTest[677:563147] client session: onLinkFailure: 1449748904186.575.QU4P/w==
2015-12-10 13:01:53.160 ThaliTest[677:563147] client session: disconnect
2015-12-10 13:01:53.160 ThaliTest[677:563147] client session: stateChange:2->0 1449748904186.575.QU4P/w==
,2015-12-10 13:01:53.172 ThaliTest[677:563147] client session: fireConnectionErrorEvent: 1449748904186.575.QU4P/w==
,calling stopBroadcasting
,2015-12-10 13:01:53.830 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:53.831 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:53.831 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:53.832 Th,aliTest[677:563359] server session: disconnect
2015-12-10 13:01:53.832 ThaliTest[677:563359] server session: stateChange:2->0 1449748904186.575
2015-12-10 13:01:53.838 ThaliTest[677:563359] jxcore: stopBroadcasting: success
stopBroadcasting returned und,efined
# ThaliReplicationManager can call start without error
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/1649CD04-5B1B-4DD2-981A-FDC200080B88/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,ok 99 starting event should occur in right order
,2015-12-10 13:01:55.532 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:55.533 ThaliTest[677:563359] server: starting 4i9cTcELqXKrz0TWtB_QOQ.JmOHbg==
2015-12-10 13:01:55.534 ThaliTest[677:563359] multipeer session: start timer: 0x1b14fdf0
2015-12-10 13:01:55.534 ThaliTest[677:563359] THEMultipeerSession init,ialized peer 4i9cTcELqXKrz0TWtB_QOQ
2015-12-10 13:01:55.534 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 100 started event should occur in right order
Now in TRM stop
State of this._isStarted: true
ok 101 stopping event should occur in right order
,About to call stopBroadcasting
,2015-12-10 13:01:55.537 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:55.537 ThaliTest[677:563359] THEMultipeerSession stopping peer
2015-12-10 13:01:55.537 ThaliTest[677:563359] multipeer session: stop timer
2015-12-10 13:01:55.538 ThaliTest[677:563359] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined
,ok 102 stopped event should occur in right order
mux server bridge listener closed
# setup
,# ThaliReplicationManager receives identity
,# teardown
,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/1649CD04-5B1B-4DD2-981A-FDC200080B88/tmp/pouchdb"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,",failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,2015-12-10 13:01:57.142 ThaliTest[677:563359] jxcore: startBroadcasting
,2015-12-10 13:01:57.146 ThaliTest[677:563359] server: starting 4i9cTcELqXKrz0TWtB_QOQ.Utyijw==
2015-12-10 13:01:57.147 ThaliTest[677:563359] multipeer session: start timer: 0x197b8360
2015-12-10 13:01:57.147 ThaliTest[677:563359] THEMultipeerSession init,ialized peer 4i9cTcELqXKrz0TWtB_QOQ
2015-12-10 13:01:57.148 ThaliTest[677:563359] jxcore: startBroadcasting: success
ok 103 getDeviceIdentity should not return an error
ok 104 deviceName should not be null
Now in TRM stop
State of this._isStarted: tru,e
About to call stopBroadcasting
,2015-12-10 13:01:57.153 ThaliTest[677:563359] jxcore: stopBroadcasting
2015-12-10 13:01:57.154 ThaliTest[677:563359] THEMultipeerSession stopping peer
,2015-12-10 13:01:57.154 ThaliTest[677:563359] multipeer session: stop timer
,2015-12-10 13:01:57.155 ThaliTest[677:563359] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
mux server bridge listener closed
,Tests Complete

```
