#### Test 55613145c131883_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145c131883/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/67E61EE5-A522-429C-B462-F5F86F021795/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/67E61EE5-A522-429C-B462-F5F86F021795/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145c131883/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145c131883/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55700"
,(lldb)     command script import "/tmp/67E61EE5-A522-429C-B462-F5F86F021795/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-14 13:15:45.323 ThaliTest[1942:4086904] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2C45C082-7082-4DAF-8490-F9F7F6BBC3AF/Library/Cookies/Cookies.binarycookies
,2016-01-14 13:15:45.563 ThaliTest[1942:4086904] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-14 13:15:45.563 ThaliTest[1942:4086904] Multi-tasking -> Device: YES, App: YES
,2016-01-14 13:15:45.570 ThaliTest[1942:4086904] Unlimited access to network resources
,2016-01-14 13:15:45.578 ThaliTest[1942:4086904] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-14 13:15:49.651 ThaliTest[1942:4086904] Resetting plugins due to page load.
,2016-01-14 13:15:51.003 ThaliTest[1942:4086904] Finished load of: file:///var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/index.html
,2016-01-14 13:15:51.162 ThaliTest[1942:4086904] JXcore Cordova plugin initializing
,2016-01-14 13:15:51.163 ThaliTest[1942:4087238] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1
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
ok 8 should not throw
# setup
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
ok 30 should be equal
ok 31 should be equal
# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,ok 32 should be equal
ok 33 should be equal
# setup
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
ok 40 should be equal
# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
ok 42 should be equal
,# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
ok 44 should be equal
# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-14 13:21:17.792 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:17.798 ThaliTest[1942:4087238] server: starting 1452774077792.1942.Zpxlsg==
2016-01-14 13:21:17.799 ThaliTest[1942:4087238] multipeer session: start timer: 0x16144a00
2016-01-14 13:21:17.799 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774077792.1942
2016-01-14 13:21:17.799 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-01-14 13:21:17.800 ThaliTest[1942:4087238] jxcore: stopBroadcasting
,2016-01-14 13:21:17.800 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:17.802 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:17.803 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-14 13:21:17.803 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:17.808 ThaliTest[1942:4087238] server: starting 1452774077803.1942.XZkotw==
2016-01-14 13:21:17.808 ThaliTest[1942:4087238] multipeer session: start timer: 0x16387140
2016-01-14 13:21:17.808 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774077803.1942
,2016-01-14 13:21:17.808 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2016-01-14 13:21:17.813 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:17.813 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:17.813 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:17.813 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting w,ithout error
2016-01-14 13:21:17.814 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:17.820 ThaliTest[1942:4087238] server: starting 1452774077814.1942.gVtVEg==
2016-01-14 13:21:17.820 ThaliTest[1942:4087238] multipeer session: start timer: 0x16418390
2016-01-14 13:21:17.820 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774077814.1942
2016-01-14 13:21:17.821 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
2016-01-14 13:21:17.821 ThaliTest[1942:4087238] jxcore: stopBroadcasting
,2016-01-14 13:21:17.821 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:17.824 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:17.824 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 50 Shoul,d be able to call stopBroadcasting without error
2016-01-14 13:21:17.825 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:17.828 ThaliTest[1942:4087238] server: starting 1452774077825.1942.tJ0Yyg==
2016-01-14 13:21:17.832 ThaliTest[1942:4087238] multipeer session: start timer: 0x162a6ee0
2016-01-14 13:21:17.832 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774077825.1942
2016-01-14 13:21:17.832 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2016-01-14 13:21:17.833 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2,016-01-14 13:21:17.833 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:17.834 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:17.834 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 52 Should, be able to call stopBroadcasting without error
2016-01-14 13:21:17.834 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:17.837 ThaliTest[1942:4087238] server: starting 1452774077834.1942.HO8uzQ==
2016-01-14 13:21:17.838 ThaliTest[1942:4087238] multipeer session: start timer: 0x14d260f0
2016-01-14 13:21:17.838 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774077834.1942
2016-01-14 13:21:17.838 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2016-01-14 13:21:17.838 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:17.839 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.839 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:17.842 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
2016-01-14 13:21:17.843 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:17.847 ThaliTest[1942:4087238] server: starting 1452774077843.1942.XTHiXw==
2016-01-14 13:21:17.848 ThaliTest[1942:4087238] multipeer session: start timer: 0x16536010
2016-01-14 13:21:17.851 ThaliTest[1942:4087238] THEMultipeerSession in,itialized peer 1452774077843.1942
2016-01-14 13:21:17.851 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
2016-01-14 13:21:17.854 ThaliTest[1942:4087238] jxcore: stopBroadcasting
,2016-01-14 13:21:17.854 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:17.857 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:17.857 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
2016-01-14 13:21:17.858 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:17.860 ThaliTest[1942:4087238] server: starting 1452774077857.1942.LW6iSw==
2016-01-14 13:21:17.861 ThaliTest[1942:4087238] multipeer session: start timer: 0x1647e1b0
2016-01-14 13:21:17.861 ThaliTest[1942:4087238] THEMultipeerSession in,itialized peer 1452774077857.1942
2016-01-14 13:21:17.861 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2016-01-14 13:21:17.861 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:17.862 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.862 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:17.865 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2016-01-14 13:21:17.866 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:17.868 ThaliTest[1942:4087238] server: starting 1452774077866.1942.qtIFLQ==
2016-01-14 13:21:17.869 ThaliTest[1942:4087238] multipeer session: start timer: 0x16476210
2016-01-14 13:21:17.869 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774077866.1942
,2016-01-14 13:21:17.869 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
2016-01-14 13:21:17.872 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:17.874 ThaliTest[19,42:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:17.874 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:17.874 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2016-01-14 13:21:17.874 ThaliTest[1942:4087238] jxcore: startBroadcasting
2016-01-14 13:21:17.876 ThaliTest[1942:4087238] server: starting 1452774077874.1942.f+h0QQ==
2016-01-14 13:21:17.876 ThaliTest[1942:4087238] multipeer session: start ,timer: 0x1613b910
2016-01-14 13:21:17.876 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774077874.1942
2016-01-14 13:21:17.876 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting w,ithout error
2016-01-14 13:21:17.879 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:17.879 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:17.879 ThaliTest[1942:4087238] multipeer session: stop timer
2016-0,1-14 13:21:17.879 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 62 Should be able to call stopBroadcasting without error
2016-01-14 13:21:17.880 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:17.891 ThaliTest[1942:4087238] server: starting 1452774077880.1942.04OLEw==
,2016-01-14 13:21:17.894 ThaliTest[1942:4087238] multipeer session: start timer: 0x166434f0
,2016-01-14 13:21:17.898 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774077880.1942
,2016-01-14 13:21:17.899 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-14 13:21:17.901 ThaliTest[1942:4087238] jxcore: stopBroadcasting
,2016-01-14 13:21:17.901 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
,2016-01-14 13:21:17.902 ThaliTest[1942:4087238] multipeer session: stop timer
,2016-01-14 13:21:17.905 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-14 13:21:18.156 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:18.157 ThaliTest[1942:4087238] server: starting 1452774078156.1942.zJX/Lg==
2016-01-14 13:21:18.157 ThaliTest[1942:4087238] multipeer session: start timer: 0x16258b90
2016-01-14 13:21:18.158 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774078156.1942
2016-01-14 13:21:18.158 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-14 13:21:18.159 ThaliTest[1942:4087238] jxcore: startBroadcasting
2016-01-14 13:21:18.159 ThaliTest[1942:4087238] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2016-01-14 13:21:18.160 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:18.160 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:18.161 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:18.161 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-14 13:21:18.253 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:18.255 ThaliTest[1942:4087238] server: starting 1452774078253.1942.tkL+8g==
2016-01-14 13:21:18.255 ThaliTest[1942:4087238] multipeer session: start timer: 0x162da510
2016-01-14 13:21:18.255 ThaliTest[1942:4087238] THEMultipeerSession in,itialized peer 1452774078253.1942
2016-01-14 13:21:18.255 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-14 13:21:18.256 ThaliTest[1942:4087238] jxcore: connect foobar
,2016-01-14 13:21:18.256 ThaliTest[1942:4087238] client: unknown peer foobar
2016-01-14 13:21:18.257 ThaliTest[1942:4087238] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
2016-01-14 13:21:18.258 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:18.258 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:18.258 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:18.258 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on disconnect to bad peer
,# teardown
,2016-01-14 13:21:18.590 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:18.591 ThaliTest[1942:4087238] server: starting 1452774078590.1942.F/i+nQ==
2016-01-14 13:21:18.592 ThaliTest[1942:4087238] multipeer session: start timer: 0x18032ad0
2016-01-14 13:21:18.592 ThaliTest[1942:4087238] THEMultipeerSession in,itialized peer 1452774078590.1942
2016-01-14 13:21:18.592 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 71 Should be able to call startBroadcasting without error
2016-01-14 13:21:18.593 ThaliTest[1942:4087238] jxcore: disconnect
2016-01-14 13:21:18.593 ThaliTest[1942:4087238] jxcore: disconnect: fail
ok 72 Disconnect should fail to a non-existant peer 
,2016-01-14 13:21:18.594 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:18.594 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:18.594 ThaliTest[1942:4087238] multipeer session: stop timer
,2016-01-14 13:21:18.594 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
ok 73 Should be able to call stopBroadcasting without error
# setup
,# ThaliEmitter can discover and connect to peers
,# teardown
,2016-01-14 13:21:18.676 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:18.677 ThaliTest[1942:4087238] server: starting 1452774078676.1942.iyAIIw==
2016-01-14 13:21:18.678 ThaliTest[1942:4087238] multipeer session: start timer: 0x16133970
2016-01-14 13:21:18.678 ThaliTest[1942:4087238] THEMultipeerSession in,itialized peer 1452774078676.1942
2016-01-14 13:21:18.678 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error
,2016-01-14 13:21:19.505 ThaliTest[1942:4086904] client: found peer: 1452774078706.1926.oQcqEw==
2016-01-14 13:21:19.505 ThaliTest[1942:4087238] jxcore: connect 1452774078706.1926.oQcqEw==
2016-01-14 13:21:19.506 ThaliTest[1942:4087238] client session: connect
2016-01-14 13:21:19.506 ThaliTest[1942:4087238] client session: stateChange:0->1 1452774078706.1926.oQcqEw==
,2016-01-14 13:21:19.944 ThaliTest[1942:4086904] multipeer session: reset timer
2016-01-14 13:21:19.944 ThaliTest[1942:4086904] multipeer session: stop timer
2016-01-14 13:21:19.944 ThaliTest[1942:4086904] multipeer session: start timer: 0x16133970
2016-01-14 13:21:19.944 ThaliTest[1942:4086904] server session: connect
,2016-01-14 13:21:19.944 ThaliTest[1942:4086904] server session: stateChange:0->1 1452774078706.1926
,2016-01-14 13:21:19.948 ThaliTest[1942:4086904] server: accepting invitation 1452774078706.1926
,2016-01-14 13:21:22.454 ThaliTest[1942:4087829] server session: connected
2016-01-14 13:21:22.454 ThaliTest[1942:4087829] server session: stateChange:1->2 1452774078706.1926
,2016-01-14 13:21:22.514 ThaliTest[1942:4086904] server relay: socket disconnected
2016-01-14 13:21:22.515 ThaliTest[1942:4086904] server relay: 0x1655f0f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-14 13:21:22.576 ThaliTest[1942:4087823] server session: not connected 1452774078706.1926
,2016-01-14 13:21:22.582 ThaliTest[1942:4087823] client session: connected
2016-01-14 13:21:22.583 ThaliTest[1942:4087823] client session: stateChange:1->2 1452774078706.1926.oQcqEw==
,2016-01-14 13:21:22.640 ThaliTest[1942:4087825] client session: fireConnectCallback: 1452774078706.1926.oQcqEw==
2016-01-14 13:21:22.640 ThaliTest[1942:4087825] jxcore: connect: success
ok 75 Should be able to connect without error
ok 76 Port should be within range
,2016-01-14 13:21:22.642 ThaliTest[1942:4087238] jxcore: disconnect
2016-01-14 13:21:22.643 ThaliTest[1942:4087238] client session: disconnectFromPeer: 1452774078706.1926.oQcqEw==
2016-01-14 13:21:22.643 ThaliTest[1942:4087238] client session: disconnect
2016-01-14 13:21:22.644 ThaliTest[1942:4087238] client session: stateChange:2->0 1452774078706.1926.oQcqEw==
,2016-01-14 13:21:22.650 ThaliTest[1942:4087238] jxcore: disconnect: success
ok 77 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-14 13:21:22.967 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:22.967 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:22.967 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:22.967 ThaliTest[1942:4087238] server session: disconnect
2016-01-14 13:21:22.967 ThaliTest[1942:4087238] server session: stateChange:2->0 1452774078706.1926
,2016-01-14 13:21:22.969 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double connect
,# teardown
,2016-01-14 13:21:23.497 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:23.498 ThaliTest[1942:4087238] server: starting 1452774083497.1942.IjCRHg==
2016-01-14 13:21:23.499 ThaliTest[1942:4087238] multipeer session: start timer: 0x1610a560
2016-01-14 13:21:23.499 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774083497.1942
2016-01-14 13:21:23.499 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
,ok 78 Should be able to call startBroadcasting without error
,2016-01-14 13:21:24.033 ThaliTest[1942:4086904] client: found peer: 1452774078706.1926.oQcqEw==
2016-01-14 13:21:24.033 ThaliTest[1942:4087238] jxcore: connect 1452774078706.1926.oQcqEw==
2016-01-14 13:21:24.033 ThaliTest[1942:4087238] client session: connect
2016-01-14 13:21:24.033 ThaliTest[1942:4087238] client session: stateChange:0->1 1452774078706.1926.oQcqEw==
,2016-01-14 13:21:24.763 ThaliTest[1942:4086904] client: found peer: 1452774083543.1926.t0VUWA==
2016-01-14 13:21:24.764 ThaliTest[1942:4087238] jxcore: connect 1452774083543.1926.t0VUWA==
2016-01-14 13:21:24.764 ThaliTest[1942:4087238] client session: connect
2016-01-14 13:21:24.764 ThaliTest[1942:4087238] client session: stateChange:0->1 1452774083543.1926.t0VUWA==
,2016-01-14 13:21:24.868 ThaliTest[1942:4086904] multipeer session: reset timer
2016-01-14 13:21:24.868 ThaliTest[1942:4086904] multipeer session: stop timer
2016-01-14 13:21:24.868 ThaliTest[1942:4086904] multipeer session: start timer: 0x1610a560
2016-01-14 13:21:24.869 ThaliTest[1942:4086904] server session: connect
2016-01-14 13:21:24.869 ThaliTest[1942:4086904] server session: stateChange:0->1 1452774083543.1926
,2016-01-14 13:21:24.872 ThaliTest[1942:4086904] server: accepting invitation 1452774083543.1926
,2016-01-14 13:21:26.194 ThaliTest[1942:4086904] client: lost peer: 1452774078706.1926.oQcqEw==
2016-01-14 13:21:26.194 ThaliTest[1942:4086904] client session: onPeerLost: 1452774078706.1926.oQcqEw==
2016-01-14 13:21:26.194 ThaliTest[1942:4086904] client ,session: onLinkFailure: 1452774078706.1926.oQcqEw==
2016-01-14 13:21:26.194 ThaliTest[1942:4086904] client session: disconnect
2016-01-14 13:21:26.194 ThaliTest[1942:4086904] client session: stateChange:1->0 1452774078706.1926.oQcqEw==
2016-01-14 13:21:26.194 ThaliTest[1942:4086904] client session: fireConnectCallback: 1452774078706.1926.oQcqEw==
2016-01-14 13:21:26.194 ThaliTest[1942:4086904] jxcore: connect: fail: Peer disconnected
,2016-01-14 13:21:27.197 ThaliTest[1942:4087238] jxcore: connect 1452774078706.1926.oQcqEw==
2016-01-14 13:21:27.197 ThaliTest[1942:4087238] client: connect: unreachable 1452774078706.1926.oQcqEw==
2016-01-14 13:21:27.197 ThaliTest[1942:4087238] jxcore: connect: fail: Peer unreachable
,2016-01-14 13:21:27.361 ThaliTest[1942:4087823] server session: connected
2016-01-14 13:21:27.361 ThaliTest[1942:4087823] server session: stateChange:1->2 1452774083543.1926
,2016-01-14 13:21:27.365 ThaliTest[1942:4087839] client session: connected
2016-01-14 13:21:27.366 ThaliTest[1942:4087839] client session: stateChange:1->2 1452774083543.1926.t0VUWA==
,2016-01-14 13:21:27.429 ThaliTest[1942:4087823] client session: fireConnectCallback: 1452774083543.1926.t0VUWA==
2016-01-14 13:21:27.430 ThaliTest[1942:4087823] jxcore: connect: success
2016-01-14 13:21:27.431 ThaliTest[1942:4086904] server relay: socket, disconnected
2016-01-14 13:21:27.431 ThaliTest[1942:4086904] server relay: 0x162e9790 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescript,ion=Connection refused} 
ok 79 Should be able to connect without error
ok 80 Port should be within range
2016-01-14 13:21:27.432 ThaliTest[1942:4087238] jxcore: connect 1452774083543.1926.t0VUWA==
2016-01-14 13:21:27.432 ThaliTest[1942:4087238] client: already connect(ing/ed) to 1452774083543.1926.t0VUWA==
2016-01-14 13:21:27.432 ThaliTest[1942:4087238] jxcore: connect: fail: Aleady connecting
ok 81 Should fail on double connect
,2016-01-14 13:21:27.433 ThaliTest[1942:4087238] jxcore: disconnect
2016-01-14 13:21:27.433 ThaliTest[1942:4087238] client session: disconnectFromPeer: 1452774083543.1926.t0VUWA==
,2016-01-14 13:21:27.434 ThaliTest[1942:4087238] client session: disconnect
,2016-01-14 13:21:27.434 ThaliTest[1942:4087238] client session: stateChange:2->0 1452774083543.1926.t0VUWA==
,2016-01-14 13:21:27.439 ThaliTest[1942:4087823] server session: not connected 1452774083543.1926
,2016-01-14 13:21:27.443 ThaliTest[1942:4087238] jxcore: disconnect: success
ok 82 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
,2016-01-14 13:21:27.691 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:27.691 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:27.691 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:27.691 ThaliTest[1942:4087238] server session: disconnect
2016-01-14 13:21:27.691 ThaliTest[1942:4087238] server session: stateChange:2->0 1452774083543.1926
2016-01-14 13:21:27.691 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
stopBroadcasting, returned undefined
# ThaliEmitter can discover and connect to peers and then fail on double disconnect
,# teardown
,2016-01-14 13:21:28.688 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:28.689 ThaliTest[1942:4087238] server: starting 1452774088687.1942.fBt/ww==
2016-01-14 13:21:28.689 ThaliTest[1942:4087238] multipeer session: start timer: 0x167759d0
2016-01-14 13:21:28.690 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774088687.1942
2016-01-14 13:21:28.690 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error
,2016-01-14 13:21:29.908 ThaliTest[1942:4086904] client: found peer: 1452774088711.1926.MvUH+A==
2016-01-14 13:21:29.908 ThaliTest[1942:4087238] jxcore: connect 1452774088711.1926.MvUH+A==
2016-01-14 13:21:29.909 ThaliTest[1942:4087238] client session: connect
2016-01-14 13:21:29.909 ThaliTest[1942:4087238] client session: stateChange:0->1 1452774088711.1926.MvUH+A==
,2016-01-14 13:21:30.046 ThaliTest[1942:4086904] multipeer session: reset timer
2016-01-14 13:21:30.046 ThaliTest[1942:4086904] multipeer session: stop timer
2016-01-14 13:21:30.046 ThaliTest[1942:4086904] multipeer session: start timer: 0x167759d0
2016-01-14 13:21:30.046 ThaliTest[1942:4086904] server session: connect
2016-01-14 13:21:30.046 ThaliTest[1942:4086904] server session: stateChange:0->1 1452774088711.1926
2016-01-14 13:21:30.049 ThaliTest[1942:4086904] server: accepting invitation 1452774088,711.1926
,2016-01-14 13:21:32.473 ThaliTest[1942:4087839] server session: connected
2016-01-14 13:21:32.474 ThaliTest[1942:4087839] server session: stateChange:1->2 1452774088711.1926
,2016-01-14 13:21:32.475 ThaliTest[1942:4086904] server relay: socket disconnected
,2016-01-14 13:21:32.476 ThaliTest[1942:4086904] server relay: 0x14ec10c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-14 13:21:32.545 ThaliTest[1942:4087829] server session: not connected 1452774088711.1926
,2016-01-14 13:21:32.549 ThaliTest[1942:4087829] client session: connected
2016-01-14 13:21:32.549 ThaliTest[1942:4087829] client session: stateChange:1->2 1452774088711.1926.MvUH+A==
,2016-01-14 13:21:32.552 ThaliTest[1942:4087829] client session: fireConnectCallback: 1452774088711.1926.MvUH+A==
2016-01-14 13:21:32.552 ThaliTest[1942:4087829] jxcore: connect: success
ok 84 Should be able to connect without error
ok 85 Port should be within range
2016-01-14 13:21:32.553 ThaliTest[1942:4087238] jxcore: disconnect
2016-01-14 13:21:32.553 ThaliTest[1942:4087238] client session: disconnectFromPeer: 1452774088711.1926.MvUH+A==
,2016-01-14 13:21:32.553 ThaliTest[1942:4087238] client session: disconnect
2016-01-14 13:21:32.555 ThaliTest[1942:4087238] client session: stateChange:2->0 1452774088711.1926.MvUH+A==
,2016-01-14 13:21:32.619 ThaliTest[1942:4087238] jxcore: disconnect: success
ok 86 Should be able to disconnect without error
2016-01-14 13:21:32.620 ThaliTest[1942:4087238] jxcore: disconnect
2016-01-14 13:21:32.620 ThaliTest[1942:4087238] jxcore: disconnect: fail
ok 87 Disconnect should fail 
setting stopBroadcasting callback and ending test.
,# setup
,calling stopBroadcasting
2016-01-14 13:21:33.913 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:33.913 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:33.913 ThaliTest[1942:4087238] multipeer session: stop t,imer
2016-01-14 13:21:33.914 ThaliTest[1942:4087238] server session: disconnect
2016-01-14 13:21:33.914 ThaliTest[1942:4087238] server session: stateChange:2->0 1452774088711.1926
,2016-01-14 13:21:33.914 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
# ThaliEmitter can connect and send data
,# teardown
,2016-01-14 13:21:38.065 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:21:38.067 ThaliTest[1942:4087238] server: starting 1452774098065.1942.O2+QVg==
2016-01-14 13:21:38.067 ThaliTest[1942:4087238] multipeer session: start timer: 0x161129e0
2016-01-14 13:21:38.067 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774098065.1942
2016-01-14 13:21:38.067 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 88 Should be able to call startBroadcasting without error
echo server started
,2016-01-14 13:21:38.075 ThaliTest[1942:4086904] client: found peer: 1452774088711.1926.MvUH+A==
2016-01-14 13:21:38.076 ThaliTest[1942:4087238] jxcore: connect 1452774088711.1926.MvUH+A==
2016-01-14 13:21:38.076 ThaliTest[1942:4087238] client session: connect
2016-01-14 13:21:38.076 ThaliTest[1942:4087238] client session: stateChange:0->1 1452774088711.1926.MvUH+A==
,2016-01-14 13:21:39.352 ThaliTest[1942:4086904] client: found peer: 1452774098130.1926.8Qn3rg==
,2016-01-14 13:21:39.353 ThaliTest[1942:4087238] jxcore: connect 1452774098130.1926.8Qn3rg==
2016-01-14 13:21:39.353 ThaliTest[1942:4087238] client session: connect
2016-01-14 13:21:39.353 ThaliTest[1942:4087238] client session: stateChange:0->1 1452774098130.1926.8Qn3rg==
,2016-01-14 13:21:39.870 ThaliTest[1942:4086904] multipeer session: reset timer
2016-01-14 13:21:39.870 ThaliTest[1942:4086904] multipeer session: stop timer
2016-01-14 13:21:39.870 ThaliTest[1942:4086904] multipeer session: start timer: 0x161129e0
2016-,01-14 13:21:39.870 ThaliTest[1942:4086904] server session: connect
2016-01-14 13:21:39.870 ThaliTest[1942:4086904] server session: stateChange:0->1 1452774098130.1926
,2016-01-14 13:21:39.873 ThaliTest[1942:4086904] server: accepting invitation 1452774098130.1926
,2016-01-14 13:21:41.202 ThaliTest[1942:4086904] client: lost peer: 1452774088711.1926.MvUH+A==
2016-01-14 13:21:41.202 ThaliTest[1942:4086904] client session: onPeerLost: 1452774088711.1926.MvUH+A==
2016-01-14 13:21:41.202 ThaliTest[1942:4086904] client session: onLinkFailure: 1452774088711.1926.MvUH+A==
2016-01-14 13:21:41.202 ThaliTest[1942:4086904] client session: disconnect
2016-01-14 13:21:41.202 ThaliTest[1942:4086904] client session: stateChange:1->0 1452774088711.1926.MvUH+A==
2016-01-14 13:21:,41.203 ThaliTest[1942:4086904] client session: fireConnectCallback: 1452774088711.1926.MvUH+A==
2016-01-14 13:21:41.203 ThaliTest[1942:4086904] jxcore: connect: fail: Peer disconnected
,2016-01-14 13:21:42.204 ThaliTest[1942:4087238] jxcore: connect 1452774088711.1926.MvUH+A==
2016-01-14 13:21:42.205 ThaliTest[1942:4087238] client: connect: unreachable 1452774088711.1926.MvUH+A==
2016-01-14 13:21:42.205 ThaliTest[1942:4087238] jxcore: connect: fail: Peer unreachable
,2016-01-14 13:21:42.627 ThaliTest[1942:4087825] client session: connected
2016-01-14 13:21:42.627 ThaliTest[1942:4087825] client session: stateChange:1->2 1452774098130.1926.8Qn3rg==
2016-01-14 13:21:42.628 ThaliTest[1942:4087825] server session: connect,ed
2016-01-14 13:21:42.628 ThaliTest[1942:4087825] server session: stateChange:1->2 1452774098130.1926
,2016-01-14 13:21:42.687 ThaliTest[1942:4087823] client session: fireConnectCallback: 1452774098130.1926.8Qn3rg==
2016-01-14 13:21:42.688 ThaliTest[1942:4087823] jxcore: connect: success
,ok 89 Should be able to connect without error
,ok 90 Port should be within range
,2016-01-14 13:21:42.690 ThaliTest[1942:4086904] server relay: connected (to port: 5001)
2016-01-14 13:21:42.692 ThaliTest[1942:4086904] client: relay established
2016-01-14 13:21:42.692 ThaliTest[1942:4086904] client: new accepted socket: 0x161865c0
,data in 2190
,data in 4380
,data in 14235
,data in 40515
,data in 42705
,data in 45990
,data in 53655
,data in 62415
,data in 67890
,data in 70080
,data in 71175
,data in 72270
,data in 74460
,data in 82125
,data in 97455
,data in 125783
,data in 131072
,ok 91 the test messages should be equal
,2016-01-14 13:21:43.569 ThaliTest[1942:4087238] jxcore: disconnect
2016-01-14 13:21:43.569 ThaliTest[1942:4087238] client session: disconnectFromPeer: 1452774098130.1926.8Qn3rg==
,2016-01-14 13:21:43.569 ThaliTest[1942:4087238] client session: disconnect
2016-01-14 13:21:43.569 ThaliTest[1942:4087238] client session: stateChange:2->0 1452774098130.1926.8Qn3rg==
,2016-01-14 13:21:43.573 ThaliTest[1942:4087238] jxcore: disconnect: success
ok 92 Should be able to disconnect without error
setting stopBroadcasting callback and ending test.
# setup
,2016-01-14 13:21:43.608 ThaliTest[1942:4087839] server session: not connected 1452774098130.1926
,calling stopBroadcasting
,2016-01-14 13:21:43.877 ThaliTest[1942:4087238] jxcore: stopBroadcasting
2016-01-14 13:21:43.877 ThaliTest[1942:4087238] THEMultipeerSession stopping peer
2016-01-14 13:21:43.877 ThaliTest[1942:4087238] multipeer session: stop timer
2016-01-14 13:21:43.877 ThaliTest[1942:4087238] server session: disconnect
2016-01-14 13:21:43.878 ThaliTest[1942:4087238] server session: stateChange:2->0 1452774098130.1926
,2016-01-14 13:21:43.880 ThaliTest[1942:4087238] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined
,# ThaliEmitter handles socket disconnect correctly
,# teardown
,2016-01-14 13:22:05.438 ThaliTest[1942:4087238] jxcore: startBroadcasting
,2016-01-14 13:22:05.440 ThaliTest[1942:4087238] server: starting 1452774125438.1942.ybUGvg==
2016-01-14 13:22:05.441 ThaliTest[1942:4087238] multipeer session: start timer: 0x16313710
2016-01-14 13:22:05.441 ThaliTest[1942:4087238] THEMultipeerSession initialized peer 1452774125438.1942
,2016-01-14 13:22:05.443 ThaliTest[1942:4087238] jxcore: startBroadcasting: success
ok 93 Should be able to call startBroadcasting without error
2016-01-14 13:22:05.445 ThaliTest[1942:4087238] Error!: listen EADDRINUSE
Stack:[{"_fileName":"net.js","_func,tionName":"errnoException","_lineNumber":"835","_columnNumber":"11","_msg":"    at errnoException@net.js:835:11"},{"_fileName":"net.js","_functionName":"Server.prototype._listen2","_lineNumber":"974","_columnNumber":"14","_msg":"    at Server.prototype._li,sten2@net.js:974:14"},{"_fileName":"net.js","_functionName":"listen","_lineNumber":"995","_columnNumber":"5","_msg":"    at listen@net.js:995:5"},{"_fileName":"net.js","_functionName":"Server.prototype.listen","_lineNumber":"1068","_columnNumber":"5","_msg,":"    at Server.prototype.listen@net.js:1068:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js","_functionName":"","_lineNumber":"241","_colum,nNumber":"3","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:241:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A,559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"78","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C2,25283/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_f,unctionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumb,er":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7",},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"263","_columnNumber":"5",,"_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/,Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/private/var,/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/Tha,liTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/Th,aliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-b,ind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-,client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/compo,nent-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/no,de_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-c,lient/node_modules/socket.io-parser/index.js","_functionName":"Decoder.prototype.add","_lineNumber":"247","_columnNumber":"7","_msg":"    at Decoder.prototype.add@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliT,est.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js:247:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/,manager.js","_functionName":"Manager.prototype.ondata","_lineNumber":"323","_columnNumber":"3","_msg":"    at Manager.prototype.ondata@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modu,les/socket.io-client/lib/manager.js:323:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"m,odule.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bi,nd/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functio,nName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine,.io-client/lib/socket.js","_functionName":"Socket.prototype.onPacket","_lineNumber":"441","_columnNumber":"9","_msg":"    at Socket.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/,jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.setTransport/<","_lineNumber":"258","_columnNumber":"5","_msg":"    at Socket.prototype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C22528,3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.i,o-client/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/0466E83,6-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7,C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Transport.prototype.onPacket","_lineNumber":"143","_columnNumber":"3","_msg":"    at Transport.prototype.onPacket@/private/var/m,obile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:143:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0466E83,6-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js","_functionName":"Transport.prototype.onData","_lineNumber":"135","_columnNumber":"3","_msg":"    at Transport.prototype.onD,ata@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:135:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/App,lication/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js","_functionName":"WS.prototype.addEventListeners/this.ws.onmessage","_lineNumber":"127","_columnN,umber":"5","_msg":"    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/tran,sports/websocket.js:127:5"}]
2016-01-14 13:22:05.451 ThaliTest[1942:4086904] client: found peer: 1452774122894.1926.4Z86SQ==
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
  { _fileName: 'net.js',
    _functionName: 'Server.prototype.listen',
    _lineNumber: '1068',
    _columnNumber: '5',
    _msg: '    at Server.prototype.listen@net.js:1068:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A55,9-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js',
    _functionName: '',
    _lineNumber: '241',
    _columnNumber: '3',
    _msg: '    at @/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8B,C7C225283/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js:241:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareT,est/</<',
    _lineNumber: '78',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/lib/thali-tape.js:78:7' },
  { _fileName: '/priva,te/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
  ,  _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Container,s/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    ,_msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/v,ar/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg:, '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/A,pplication/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpacket',
    _lineNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.on,packet@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-40,3B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mo,bile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-4,03B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit,@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Applicat,ion/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',
    _lineNumber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondec,oded@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403,B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mob,ile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-40,3B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: ',    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7' },
  {, _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js',
    _functionName: 'Decoder.prototype.add',
    _lineNumbe,r: '247',
    _columnNumber: '7',
    _msg: '    at Decoder.prototype.add@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/index.js,:247:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondata',
    _lineNumber: '32,3',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondata@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:323:3' },
  { _fileName: ,'/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _lineNumber: '21',
    _colu,mnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12' },
  { _fileName:, '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.e,mit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/eng,ine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib,/socket.js',
    _functionName: 'Socket.prototype.onPacket',
    _lineNumber: '441',
    _columnNumber: '9',
    _msg: '    at Socket.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.ap,p/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:441:9' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/,node_modules/engine.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.setTransport/<',
    _lineNumber: '258',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.setTransport/<@/private/var/mobile/Containers/Bundle/Application/0466,E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/socket.js:258:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit',
    _lineNumber: '134',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/,private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7' },
  { _fileName: '/private/var/mobil,e/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.prototype.onPacket',
    _lineNumber: '143',
    _,columnNumber: '3',
    _msg: '    at Transport.prototype.onPacket@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js:,143:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transport.js',
    _functionName: 'Transport.prototy,pe.onData',
    _lineNumber: '135',
    _columnNumber: '3',
    _msg: '    at Transport.prototype.onData@/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_m,odules/engine.io-client/lib/transport.js:135:3' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/0466E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/w,ebsocket.js',
    _functionName: 'WS.prototype.addEventListeners/this.ws.onmessage',
    _lineNumber: '127',
    _columnNumber: '5',
    _msg: '    at WS.prototype.addEventListeners/this.ws.onmessage@/private/var/mobile/Containers/Bundle/Application/04,66E836-A559-403B-8A20-A8BC7C225283/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/engine.io-client/lib/transports/websocket.js:127:5' },
  toString: [Function] ]
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
