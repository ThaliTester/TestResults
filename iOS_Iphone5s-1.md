#### Test 55613145b105d0b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145b105d0b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/20A337EB-BA9B-4E63-A22D-3D3F8DB04118/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/20A337EB-BA9B-4E63-A22D-3D3F8DB04118/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145b105d0b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145b105d0b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2611B990-54A3-45F6-BF8A-ADA870EAF558/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55394"
,(lldb)     command script import "/tmp/20A337EB-BA9B-4E63-A22D-3D3F8DB04118/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-14 10:30:23.311 ThaliTest[1914:4405016] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/67597892-D998-4F86-97C7-68A210AFC5EB/Library/Cookies/Cookies.binarycookies
,2016-01-14 10:30:23.596 ThaliTest[1914:4405016] Apache Cordova native platform version 3.9.2 is starting.
2016-01-14 10:30:23.597 ThaliTest[1914:4405016] Multi-tasking -> Device: YES, App: YES
,2016-01-14 10:30:23.604 ThaliTest[1914:4405016] Unlimited access to network resources
,2016-01-14 10:30:23.614 ThaliTest[1914:4405016] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-14 10:30:27.900 ThaliTest[1914:4405016] Resetting plugins due to page load.
,2016-01-14 10:30:29.446 ThaliTest[1914:4405016] Finished load of: file:///var/mobile/Containers/Bundle/Application/2611B990-54A3-45F6-BF8A-ADA870EAF558/ThaliTest.app/www/index.html
,2016-01-14 10:30:29.638 ThaliTest[1914:4405016] JXcore Cordova plugin initializing
,2016-01-14 10:30:29.639 ThaliTest[1914:4405196] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5s-1
,Test app app.js loaded
,TAP version 13
,# setup
,# multiplex can send data
,# teardown
,ok 1 String should be length:200
# setup
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
,ok 11 should not throw
,ok 12 should be equal
,ok 13 should be equal
# setup
,# failed to extract public key because of corrupt pkcs12 file
,# teardown
,ok 14 should be equal
,# setup
,# failed to get mobile documents path
,# teardown
,ok 15 should be equal
# setup
,# #init should register the peerAvailabilityChanged event
,# teardown
,ok 16 should be equal
ok 17 should be equal
ok 18 should be equal
,# setup
,# #init should register the networkChanged event
,# teardown
,ok 19 should be equal
,# setup
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
# setup
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
# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,ok 26 should be equal
ok 27 should be equal
ok 28 should be equal
# setup
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
ok 35 should be equal
# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
,ok 37 should be equal
ok 38 should be equal
# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
,ok 40 should be equal
# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
,ok 42 should be equal
# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
ok 44 should be equal
# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-14 10:35:58.741 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:58.749 ThaliTest[1914:4405196] server: starting 1452764158741.1914.BzxJ8w==
2016-01-14 10:35:58.750 ThaliTest[1914:4405196] multipeer session: start timer: 0x17b05000
2016-01-14 10:35:58.750 ThaliTest[1914:4405196] THEMultipeerSession in,itialized peer 1452764158741.1914
2016-01-14 10:35:58.750 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.751 ThaliTest[1914:4405196] jxcore: stopBroadcasting
,2016-01-14 10:35:58.751 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
2016-01-14 10:35:58.755 ThaliTest[1914:4405196] multipeer session: stop timer
2016-01-14 10:35:58.755 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-14 10:35:58.756 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:58.764 ThaliTest[1914:4405196] server: starting 1452764158756.1914.lz4VUw==
2016-01-14 10:35:58.765 ThaliTest[1914:4405196] multipeer session: start timer: 0x179acd80
2016-01-14 10:35:58.765 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764158756.1914
2016-01-14 10:35:58.765 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.766 ThaliTest[1914:4405196] jxcore: stopBroadcasting
2016-01-14 10:35:58.766 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
,2016-01-14 10:35:58.766 ThaliTest[1914:4405196] multipeer session: stop timer
2016-01-14 10:35:58.772 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2016-01-14 10:35:58.773 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:58.778 ThaliTest[1914:4405196] server: starting 1452764158772.1914.XKy6Vg==
2016-01-14 10:35:58.778 ThaliTest[1914:4405196] multipeer session: start timer: 0x17b89dd0
2016-01-14 10:35:58.778 ThaliTest[1914:4405196] THEMultipeerSession in,itialized peer 1452764158772.1914
2016-01-14 10:35:58.778 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.779 ThaliTest[1914:4405196] jxcore: stopBroadcasting
2,016-01-14 10:35:58.780 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
2016-01-14 10:35:58.780 ThaliTest[1914:4405196] multipeer session: stop timer
2016-01-14 10:35:58.780 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
ok 50 Should, be able to call stopBroadcasting without error
2016-01-14 10:35:58.781 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:58.787 ThaliTest[1914:4405196] server: starting 1452764158781.1914.RnfGeA==
2016-01-14 10:35:58.787 ThaliTest[1914:4405196] multipeer session: start timer: 0x17c79bb0
2016-01-14 10:35:58.787 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764158781.1914
,2016-01-14 10:35:58.790 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.791 ThaliTest[1914:4405196] jxcore: stopBroadcasting
2016-01-14 10:35:58.791 ThaliTest[19,14:4405196] THEMultipeerSession stopping peer
2016-01-14 10:35:58.791 ThaliTest[1914:4405196] multipeer session: stop timer
2016-01-14 10:35:58.791 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting w,ithout error
2016-01-14 10:35:58.792 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:58.798 ThaliTest[1914:4405196] server: starting 1452764158792.1914.Dh7cyQ==
2016-01-14 10:35:58.799 ThaliTest[1914:4405196] multipeer session: start timer: 0x17ac2160
2016-01-14 10:35:58.799 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764158792.1914
,2016-01-14 10:35:58.799 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.803 ThaliTest[1914:4405196] jxcore: stopBroadcasting
2016-01-14 10:35:58.804 ThaliTest[19,14:4405196] THEMultipeerSession stopping peer
2016-01-14 10:35:58.804 ThaliTest[1914:4405196] multipeer session: stop timer
2016-01-14 10:35:58.804 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
2016-01-14 10:35:58.805 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:58.812 ThaliTest[1914:4405196] server: starting 1452764158805.1914.J9Kvvg==
2016-01-14 10:35:58.816 ThaliTest[1914:4405196] multipeer session: start timer: 0x1791e3b0
2016-01-14 10:35:58.816 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764158805.1914
2016-01-14 10:35:58.816 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.817 ThaliTest[1914:4405196] jxcore: stopBroadcasting
2,016-01-14 10:35:58.817 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
2016-01-14 10:35:58.817 ThaliTest[1914:4405196] multipeer session: stop timer
2016-01-14 10:35:58.818 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
ok 56 Should, be able to call stopBroadcasting without error
2016-01-14 10:35:58.820 ThaliTest[1914:4405196] jxcore: startBroadcasting
2016-01-14 10:35:58.823 ThaliTest[1914:4405196] server: starting 1452764158819.1914.TLZjYQ==
2016-01-14 10:35:58.823 ThaliTest[1914,:4405196] multipeer session: start timer: 0x1660b6d0
2016-01-14 10:35:58.828 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764158819.1914
2016-01-14 10:35:58.829 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
ok 57 Should ,be able to call startBroadcasting without error
2016-01-14 10:35:58.830 ThaliTest[1914:4405196] jxcore: stopBroadcasting
2016-01-14 10:35:58.830 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
2016-01-14 10:35:58.830 ThaliTest[1914:4405196] multipeer session: stop timer
2016-01-14 10:35:58.830 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2016-01-14 10:35:58.831 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:58.837 ThaliTest[1914:4405196] server: starting 1452764158831.1914.USzLKQ==
2016-01-14 10:35:58.837 ThaliTest[1914:4405196] multipeer session: start timer: 0x17b782b0
2016-01-14 10:35:58.837 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764158831.1914
2016-01-14 10:35:58.837 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
2016-01-14 10:35:58.839 ThaliTest[1914:4405196] jxcore: stopBroadcasting
2,016-01-14 10:35:58.839 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
2016-01-14 10:35:58.839 ThaliTest[1914:4405196] multipeer session: stop timer
2016-01-14 10:35:58.839 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2016-01-14 10:35:58.841 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:58.849 ThaliTest[1914:4405196] server: starting 1452764158840.1914.qKKMSg==
,2016-01-14 10:35:58.856 ThaliTest[1914:4405196] multipeer session: start timer: 0x17ad9230
,2016-01-14 10:35:58.859 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764158840.1914
,2016-01-14 10:35:58.859 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2016-01-14 10:35:58.861 ThaliTest[1914:4405196] jxcore: stopBroadcasting
,2016-01-14 10:35:58.863 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
,2016-01-14 10:35:58.863 ThaliTest[1914:4405196] multipeer session: stop timer
,2016-01-14 10:35:58.864 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-14 10:35:58.868 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:58.870 ThaliTest[1914:4405196] server: starting 1452764158868.1914.4ulYxA==
,2016-01-14 10:35:58.872 ThaliTest[1914:4405196] multipeer session: start timer: 0x17a67530
,2016-01-14 10:35:58.873 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764158868.1914
,2016-01-14 10:35:58.874 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-14 10:35:58.879 ThaliTest[1914:4405196] jxcore: stopBroadcasting
,2016-01-14 10:35:58.879 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
,2016-01-14 10:35:58.879 ThaliTest[1914:4405196] multipeer session: stop timer
,2016-01-14 10:35:58.881 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-14 10:35:59.040 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:59.042 ThaliTest[1914:4405196] server: starting 1452764159040.1914.ATTvww==
,2016-01-14 10:35:59.044 ThaliTest[1914:4405196] multipeer session: start timer: 0x17a47930
,2016-01-14 10:35:59.048 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764159040.1914
,2016-01-14 10:35:59.048 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2016-01-14 10:35:59.050 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:59.051 ThaliTest[1914:4405196] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2016-01-14 10:35:59.053 ThaliTest[1914:4405196] jxcore: stopBroadcasting
,2016-01-14 10:35:59.053 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
,2016-01-14 10:35:59.054 ThaliTest[1914:4405196] multipeer session: stop timer
,2016-01-14 10:35:59.056 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-14 10:35:59.104 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:59.106 ThaliTest[1914:4405196] server: starting 1452764159104.1914.PDG8oA==
,2016-01-14 10:35:59.107 ThaliTest[1914:4405196] multipeer session: start timer: 0x17ab7590
,2016-01-14 10:35:59.111 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764159104.1914
,2016-01-14 10:35:59.112 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2016-01-14 10:35:59.114 ThaliTest[1914:4405196] jxcore: connect foobar
,2016-01-14 10:35:59.115 ThaliTest[1914:4405196] client: unknown peer foobar
,2016-01-14 10:35:59.115 ThaliTest[1914:4405196] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2016-01-14 10:35:59.117 ThaliTest[1914:4405196] jxcore: stopBroadcasting
,2016-01-14 10:35:59.118 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
,2016-01-14 10:35:59.118 ThaliTest[1914:4405196] multipeer session: stop timer
,2016-01-14 10:35:59.121 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-14 10:35:59.171 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:59.173 ThaliTest[1914:4405196] server: starting 1452764159171.1914.L9bskA==
,2016-01-14 10:35:59.175 ThaliTest[1914:4405196] multipeer session: start timer: 0x198db0b0
,2016-01-14 10:35:59.178 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764159171.1914
,2016-01-14 10:35:59.179 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error
,2016-01-14 10:35:59.181 ThaliTest[1914:4405196] jxcore: disconnect
,2016-01-14 10:35:59.182 ThaliTest[1914:4405196] jxcore: disconnect: fail
,ok 72 Disconnect should fail to a non-existant peer 
,2016-01-14 10:35:59.184 ThaliTest[1914:4405196] jxcore: stopBroadcasting
2016-01-14 10:35:59.184 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
,2016-01-14 10:35:59.184 ThaliTest[1914:4405196] multipeer session: stop timer
,2016-01-14 10:35:59.186 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-14 10:35:59.536 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:35:59.538 ThaliTest[1914:4405196] server: starting 1452764159536.1914.fKIvag==
2016-01-14 10:35:59.538 ThaliTest[1914:4405196] multipeer session: start timer: 0x179486a0
2016-01-14 10:35:59.539 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764159536.1914
2016-01-14 10:35:59.539 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-14 10:36:00.393 ThaliTest[1914:4405016] client: found peer: 1452764159517.1929.GoKB6w==
,2016-01-14 10:36:00.394 ThaliTest[1914:4405196] jxcore: connect 1452764159517.1929.GoKB6w==
2016-01-14 10:36:00.395 ThaliTest[1914:4405196] client session: connect
2016-01-14 10:36:00.395 ThaliTest[1914:4405196] client session: stateChange:0->1 1452764159517.1929.GoKB6w==
,2016-01-14 10:36:00.629 ThaliTest[1914:4405016] multipeer session: reset timer
2016-01-14 10:36:00.629 ThaliTest[1914:4405016] multipeer session: stop timer
2016-01-14 10:36:00.629 ThaliTest[1914:4405016] multipeer session: start timer: 0x179486a0
2016-01-14 10:36:00.629 ThaliTest[1914:4405016] server session: connect
2016-01-14 10:36:00.629 ThaliTest[1914:4405016] server session: stateChange:0->1 1452764159517.1929
,2016-01-14 10:36:00.634 ThaliTest[1914:4405016] server: accepting invitation 1452764159517.1929
,2016-01-14 10:36:03.062 ThaliTest[1914:4406035] server session: connected
,2016-01-14 10:36:03.062 ThaliTest[1914:4406035] server session: stateChange:1->2 1452764159517.1929
,2016-01-14 10:36:03.068 ThaliTest[1914:4405016] server relay: socket disconnected
2016-01-14 10:36:03.068 ThaliTest[1914:4405016] server relay: 0x17fc1730 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-14 10:36:03.123 ThaliTest[1914:4406033] server session: not connected 1452764159517.1929
,2016-01-14 10:36:03.255 ThaliTest[1914:4406033] client session: connected
2016-01-14 10:36:03.255 ThaliTest[1914:4406033] client session: stateChange:1->2 1452764159517.1929.GoKB6w==
,2016-01-14 10:36:03.261 ThaliTest[1914:4406031] client session: fireConnectCallback: 1452764159517.1929.GoKB6w==
,2016-01-14 10:36:03.261 ThaliTest[1914:4406031] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
2016-01-14 10:36:03.265 ThaliTest[1914:4405196] jxcore: disconnect
2016-01-14 10:36:03.265 ThaliTest[1914:4405196] client session: disconnectFromPeer: 1452764159517.1929.GoKB6w==
2016-01-14 10:36:03.265 ThaliTest[1914:4405196] client session: disconnect
2016-01-14 10:36:03.265 ThaliTest[1914:4405196] client session: stateChange:2->0 1452764159517.1929.GoKB6w==
,2016-01-14 10:36:03.334 ThaliTest[1914:4405196] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-14 10:36:04.764 ThaliTest[1914:4405196] jxcore: stopBroadcasting
,2016-01-14 10:36:04.764 ThaliTest[1914:4405196] THEMultipeerSession stopping peer
2016-01-14 10:36:04.765 ThaliTest[1914:4405196] multipeer session: stop timer
2016-01-14 10:36:04.765 ThaliTest[1914:4405196] server session: disconnect
2016-01-14 10:36:04.765 ThaliTest[1914:4405196] server session: stateChange:2->0 1452764159517.1929
2016-01-14 10:36:04.768 ThaliTest[1914:4405196] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-14 10:36:38.371 ThaliTest[1914:4405196] jxcore: startBroadcasting
,2016-01-14 10:36:38.374 ThaliTest[1914:4405196] server: starting 1452764198371.1914.JdST9g==
2016-01-14 10:36:38.374 ThaliTest[1914:4405196] multipeer session: start timer: 0x179c0360
2016-01-14 10:36:38.374 ThaliTest[1914:4405196] THEMultipeerSession initialized peer 1452764198371.1914
2016-01-14 10:36:38.374 ThaliTest[1914:4405196] jxcore: startBroadcasting: success
ok 78 Should be able to call startBroadcasting without error
,2016-01-14 10:37:07.567 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
2016-01-14 10:37:07.568 ThaliTest[1914:4405196] jxcore: connect 1452764195482.1929.S3Tdjw==
2016-01-14 10:37:07.568 ThaliTest[1914:4405196] client session: connect
2016-01-14 10:37:07.568 ThaliTest[1914:4405196] client session: stateChange:0->1 1452764195482.1929.S3Tdjw==
,2016-01-14 10:37:08.375 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:37:08.392 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:37:35.653 ThaliTest[1914:4405016] multipeer session: reset timer
2016-01-14 10:37:35.653 ThaliTest[1914:4405016] multipeer session: stop timer
2016-01-14 10:37:35.653 ThaliTest[1914:4405016] multipeer session: start timer: 0x179c0360
,2016-01-14 10:37:35.654 ThaliTest[1914:4405016] server session: connect
2016-01-14 10:37:35.654 ThaliTest[1914:4405016] server session: stateChange:0->1 1452764195482.1929
,2016-01-14 10:37:35.658 ThaliTest[1914:4405016] server: accepting invitation 1452764195482.1929
,2016-01-14 10:37:38.175 ThaliTest[1914:4406423] server session: connected
2016-01-14 10:37:38.176 ThaliTest[1914:4406423] server session: stateChange:1->2 1452764195482.1929
,2016-01-14 10:37:38.221 ThaliTest[1914:4405016] server relay: socket disconnected
2016-01-14 10:37:38.222 ThaliTest[1914:4405016] server relay: 0x17d656e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-14 10:37:38.276 ThaliTest[1914:4406423] server session: not connected 1452764195482.1929
,2016-01-14 10:37:38.731 ThaliTest[1914:4406447] client session: not connected 1452764195482.1929.S3Tdjw==
2016-01-14 10:37:38.731 ThaliTest[1914:4406447] client session: onLinkFailure: 1452764195482.1929.S3Tdjw==
2016-01-14 10:37:38.731 ThaliTest[1914:44,06447] client session: disconnect
2016-01-14 10:37:38.731 ThaliTest[1914:4406447] client session: stateChange:1->0 1452764195482.1929.S3Tdjw==
,2016-01-14 10:37:38.733 ThaliTest[1914:4406447] client session: fireConnectCallback: 1452764195482.1929.S3Tdjw==
2016-01-14 10:37:38.734 ThaliTest[1914:4406447] jxcore: connect: fail: Peer disconnected
,2016-01-14 10:37:39.740 ThaliTest[1914:4405196] jxcore: connect 1452764195482.1929.S3Tdjw==
2016-01-14 10:37:39.740 ThaliTest[1914:4405196] client session: connect
2016-01-14 10:37:39.741 ThaliTest[1914:4405196] client session: stateChange:0->1 1452764195482.1929.S3Tdjw==
,2016-01-14 10:37:42.478 ThaliTest[1914:4406347] client session: connected
2016-01-14 10:37:42.478 ThaliTest[1914:4406347] client session: stateChange:1->2 1452764195482.1929.S3Tdjw==
,2016-01-14 10:37:42.533 ThaliTest[1914:4406423] client session: fireConnectCallback: 1452764195482.1929.S3Tdjw==
2016-01-14 10:37:42.533 ThaliTest[1914:4406423] jxcore: connect: success
ok 79 Should be able to connect without error
ok 80 Port should be within range
,2016-01-14 10:37:42.534 ThaliTest[1914:4405196] jxcore: connect 1452764195482.1929.S3Tdjw==
2016-01-14 10:37:42.536 ThaliTest[1914:4405196] client: already connect(ing/ed) to 1452764195482.1929.S3Tdjw==
2016-01-14 10:37:42.536 ThaliTest[1914:4405196] jxc,ore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
2016-01-14 10:37:42.537 ThaliTest[1914:4405196] jxcore: disconnect
2016-01-14 10:37:42.537 ThaliTest[1914:4405196] client session: disconnectFromPeer: 1452764195482.1929.S3Tdjw==,
2016-01-14 10:37:42.537 ThaliTest[1914:4405196] client session: disconnect
2016-01-14 10:37:42.537 ThaliTest[1914:4405196] client session: stateChange:2->0 1452764195482.1929.S3Tdjw==
,2016-01-14 10:37:42.545 ThaliTest[1914:4405196] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,2016-01-14 10:38:05.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:38:05.669 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:38:35.655 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:38:35.670 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:39:02.984 ThaliTest[1914:4405016] client: lost peer: 1452764195482.1929.S3Tdjw==
2016-01-14 10:39:02.984 ThaliTest[1914:4405016] client session: onPeerLost: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:39:05.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:39:35.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:40:05.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:40:05.985 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:40:35.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:40:35.882 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:41:05.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:41:11.500 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:41:35.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:42:05.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:42:06.018 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:42:35.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:42:42.760 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
2016-01-14 10:42:42.760 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:43:05.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:43:05.673 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:43:35.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:43:35.841 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:44:05.655 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:44:11.409 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:44:35.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:44:35.973 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:45:05.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:45:35.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:45:35.666 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:46:05.655 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:46:35.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:46:35.672 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:47:05.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:47:05.955 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:47:35.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:47:35.843 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:48:05.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:48:05.674 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:48:35.654 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:49:05.655 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:49:05.671 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:49:35.646 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:49:35.794 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:50:05.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:50:05.652 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:50:35.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:50:35.647 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:51:05.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:51:35.634 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:51:35.970 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:52:05.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:52:05.653 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:52:35.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:52:35.699 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:53:05.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:53:06.034 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:53:35.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:54:05.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:54:05.645 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:54:35.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:55:05.634 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:55:06.003 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:55:35.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:55:35.955 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:56:05.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:56:35.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:56:35.649 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:57:05.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:57:05.653 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:57:35.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:57:36.023 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==
,2016-01-14 10:58:05.633 ThaliTest[1914:4405016] multipeer session: restart
,2016-01-14 10:58:05.649 ThaliTest[1914:4405016] client: found peer: 1452764195482.1929.S3Tdjw==

```
