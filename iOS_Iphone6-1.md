#### Test 506502782ddd83f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/2E5E39EE-FEA0-4E46-BB2E-C255B80EB84B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2E5E39EE-FEA0-4E46-BB2E-C255B80EB84B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E989C364-6086-48B4-AD01-D8D48601DA15/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56416"
,(lldb)     command script import "/tmp/2E5E39EE-FEA0-4E46-BB2E-C255B80EB84B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 05:41:36.481 ThaliTest[1011:1261770] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2CEA0A33-3DEB-4DC1-A5BF-0281CE3C3AD7/Library/Cookies/Cookies.binarycookies
,2015-12-15 05:41:36.918 ThaliTest[1011:1261770] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 05:41:36.920 ThaliTest[1011:1261770] Multi-tasking -> Device: YES, App: YES
,2015-12-15 05:41:36.931 ThaliTest[1011:1261770] Unlimited access to network resources
,2015-12-15 05:41:36.947 ThaliTest[1011:1261770] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 05:41:46.075 ThaliTest[1011:1261770] Resetting plugins due to page load.
,2015-12-15 05:41:49.767 ThaliTest[1011:1261770] Finished load of: file:///var/mobile/Containers/Bundle/Application/E989C364-6086-48B4-AD01-D8D48601DA15/ThaliTest.app/www/index.html
,2015-12-15 05:41:49.970 ThaliTest[1011:1261770] JXcore Cordova plugin initializing
,2015-12-15 05:41:49.970 ThaliTest[1011:1261974] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-15 05:41:51.034 ThaliTest[1011:1261770] THREAD WARNING: ['JXcore'] took '76.535889' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 05:46:55.754 ThaliTest[1011:1261974] jxcore: startBroadcasting
,2015-12-15 05:46:55.770 ThaliTest[1011:1261974] server: starting Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:46:55.772 ThaliTest[1011:1261974] multipeer session: start timer: 0x15bafbb0
2015-12-15 05:46:55.773 ThaliTest[1011:1261974] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7824
2015-12-15 05:46:55.773 ThaliTest[1011:1261974] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 05:46:56.938 ThaliTest[1011:1261770] client: found peer: Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:46:56.940 ThaliTest[1011:1261770] client: found peer: Apple-IpadAir2-1_PT2678.RP+Etw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne5-1_PT356.zzR6Ww==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT356.zzR6Ww==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-15 05:46:59.276 ThaliTest[1011:1261974] jxcore: stopBroadcasting
2015-12-15 05:46:59.277 ThaliTest[1011:1261974] THEMultipeerSession stopping peer
2015-12-15 05:46:59.278 ThaliTest[1011:1261974] multipeer session: stop timer
2015-12-15 05:46:59.,278 ThaliTest[1011:1261974] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 59277
,2015-12-15 05:46:59.354 ThaliTest[1011:1261974] jxcore: startBroadcasting
,2015-12-15 05:46:59.359 ThaliTest[1011:1261974] server: starting Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:46:59.363 ThaliTest[1011:1261974] multipeer session: start timer: 0x15bb74a0
,2015-12-15 05:46:59.370 ThaliTest[1011:1261974] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7824
,2015-12-15 05:46:59.371 ThaliTest[1011:1261974] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-12-15 05:46:59.377 ThaliTest[1011:1261770] client: found peer: Apple-Iphone5-1_PT356.zzR6Ww==
null
2015-12-15T04:46:59.380Z SendDataTCPServer.js: TCP/IP server is bound to port: 59277
2015-12-15 05:46:59.380 ThaliTest[,1011:1261770] client: found peer: Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:46:59.381 ThaliTest[1011:1261770] client: found peer: Apple-IpadAir2-1_PT2678.RP+Etw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.zzR6Ww==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15T04:46:59.388Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15T04:46:59.388Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15T04:46:59.388Z SendDataConnector.js: do connect now
,2015-12-15 05:46:59.389 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:46:59.390 ThaliTest[1011:1261974] client session: connect
,2015-12-15 05:46:59.390 ThaliTest[1011:1261974] client session: stateChange:0->1 Apple-Iphone5-1_PT356.zzR6Ww==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7824.Q97KpQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2678.RP+Etw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:47:00.497 ThaliTest[1011:1261770] client: lost peer: Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:00.498 ThaliTest[1011:1261770] client session: onPeerLost: Apple-Iphone6-1_PT7824.Q97KpQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT7824.Q97KpQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-12-15 05:47:00.502 ThaliTest[1011:1261770] client: found peer: Apple-Iphone5-1_PT356.aa89HA==
peerAvailabilityChanged [{"peerIdentifier",:"Apple-Iphone5-1_PT356.aa89HA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:47:01.070 ThaliTest[1011:1261770] client: lost peer: Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:47:01.071 ThaliTest[1011:1261770] client session: onPeerLost: Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:47:01.071 ThaliTest[1011:1261770] c,lient session: onLinkFailure: Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:47:01.071 ThaliTest[1011:1261770] client session: disconnect
2015-12-15 05:47:01.071 ThaliTest[1011:1261770] client session: stateChange:1->0 Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:01.072 ThaliTest[1011:1261770] client session: fireConnectCallback: Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:01.073 ThaliTest[1011:1261770] jxcore: connect: fail: Peer disconnected
,2015-12-15T04:47:01.076Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-15T04:47:01.077Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-15T04:47:01.078Z SendDataConnector.js: tryAgain afer: 5000 ms.,
2015-12-15 05:47:01.077 ThaliTest[1011:1261770] client: lost peer: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:01.078 ThaliTest[1011:1261770] client session: onPeerLost: Apple-IpadAir2-1_PT2678.RP+Etw==
peerAvailabilityChanged [{"peerIdentifier":,"Apple-Iphone5-1_PT356.zzR6Ww==","peerName":"(null)","peerAvailable":false}]
2015-12-15 05:47:01.079 ThaliTest[1011:1261770] client: found peer: Apple-Iphone5s-1_PT4162.hYB3TQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2678.RP+Etw==,","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-12-15 05:47:01.079 ThaliTest[1011:1261770] client: found peer: Apple-IpadAir2-1_PT2678.ad0lIQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4162.,hYB3TQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2678.ad0lIQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15T04:47:06.087Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15T04:47:06.088Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:11.091 ThaliTest[1011:1261974] jxcore: disconnect
2015-12-15 05:47:11.092 ThaliTest[1011:1261974] jxcore: disconnect: fail
2015-12-15T04:47:11.092Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.zzR6Ww,==
2015-12-15T04:47:11.093Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT356.zzR6Ww== with availability status: true
2015-12-15T04:47:11.093Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15T04:47:11.094Z SendDataConnector.js: do connect now
,2015-12-15 05:47:11.095 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:11.095 ThaliTest[1011:1261974] client: connect: unreachable Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:47:11.096 ThaliTest[1011:1261974] jxcore: connect: fail: Peer unreachable
2015-12-15T04:47:11.097Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer unreachable
2015-12-15T04:47:11.097Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:47:11.098Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:16.108Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15T04:47:16.109Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:21.114 ThaliTest[1011:1261974] jxcore: disconnect
2015-12-15 05:47:21.115 ThaliTest[1011:1261974] jxcore: disconnect: fail
2015-12-15T04:47:21.115Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.zzR6Ww,==
2015-12-15T04:47:21.115Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT356.zzR6Ww== with availability status: true
2015-12-15T04:47:21.116Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15T04:47:21.116Z SendDataConnector.js: do connect now
,2015-12-15 05:47:21.117 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:21.118 ThaliTest[1011:1261974] client: connect: unreachable Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:21.119 ThaliTest[1011:1261974] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:21.120Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:47:21.120Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:47:21.121Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:26.123Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15T04:47:26.123Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:29.370 ThaliTest[1011:1261770] multipeer session: restart
,2015-12-15 05:47:31.132 ThaliTest[1011:1261974] jxcore: disconnect
,2015-12-15 05:47:31.133 ThaliTest[1011:1261974] jxcore: disconnect: fail
2015-12-15T04:47:31.133Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15T04:47:31.134Z SendDataConnector.js: Connect (retry co,unt 3) to peer Apple-Iphone5-1_PT356.zzR6Ww== with availability status: true
2015-12-15T04:47:31.134Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15T04:47:31.134Z SendDataConnector.js: do connect now
,2015-12-15 05:47:31.136 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:47:31.137 ThaliTest[1011:1261974] client: connect: unreachable Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:47:31.137 ThaliTest[1011:1261974] jxc,ore: connect: fail: Peer unreachable
2015-12-15T04:47:31.138Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:47:31.138Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:47:31.138Z SendDataC,onnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:36.142Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15T04:47:36.143Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:41.148 ThaliTest[1011:1261974] jxcore: disconnect
2015-12-15 05:47:41.148 ThaliTest[1011:1261974] jxcore: disconnect: fail
2015-12-15T04:47:41.149Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.zzR6Ww,==
2015-12-15T04:47:41.149Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT356.zzR6Ww== with availability status: true
2015-12-15T04:47:41.149Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15T04:47:41.150Z SendDataConnector.js: do connect now
2015-12-15 05:47:41.150 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:41.151 ThaliTest[1011:1261974] client: connect: unreachable Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:41.152 ThaliTest[1011:1261974] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:41.153Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:47:41.153Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-15T04:47:41.155Z SendDataConnector.js: CLIENT Stop now
,2015-12-15 05:47:41.156 ThaliTest[1011:1261974] jxcore: disconnect
2015-12-15 05:47:41.157 ThaliTest[1011:1261974] jxcore: disconnect: fail
2015-12-15T04:47:41.158Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.zzR6Ww==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:41.161Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:41.162Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:41.162Z SendDataConnector.js: do connect now
,2015-12-15 05:47:41.163 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:41.164 ThaliTest[1011:1261974] client session: connect
2015-12-15 05:47:41.164 ThaliTest[1011:1261974] client session: stateChange:0->1 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:41.175 ThaliTest[1011:1261770] client: lost peer: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:41.176 ThaliTest[1011:1261770] client session: onPeerLost: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:41.176 ThaliTest[1011:1261770] c,lient session: onLinkFailure: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:41.176 ThaliTest[1011:1261770] client session: disconnect
2015-12-15 05:47:41.177 ThaliTest[1011:1261770] client session: stateChange:1->0 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:41.232 ThaliTest[1011:1261770] client session: fireConnectCallback: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:41.232 ThaliTest[1011:1261770] jxcore: connect: fail: Peer disconnected
2015-12-15T04:47:41.233Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-15T04:47:41.234Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-15T04:47:41.234Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.aa89HA==","peerName":"(null)","peerAvailable":false}]
,2015-12-15 05:47:45.285 ThaliTest[1011:1261770] multipeer session: reset timer
2015-12-15 05:47:45.286 ThaliTest[1011:1261770] multipeer session: stop timer
2015-12-15 05:47:45.286 ThaliTest[1011:1261770] multipeer session: start timer: 0x15bb74a0
,2015-12-15 05:47:45.287 ThaliTest[1011:1261770] server session: connect
2015-12-15 05:47:45.287 ThaliTest[1011:1261770] server session: stateChange:0->1 Apple-IpadAir2-1_PT2678
,2015-12-15 05:47:45.298 ThaliTest[1011:1261770] server: accepting invitation Apple-IpadAir2-1_PT2678
2015-12-15 05:47:45.299 ThaliTest[1011:1261770] multipeer session: reset timer
2015-12-15 05:47:45.299 ThaliTest[1011:1261770] multipeer session: stop timer
2015-12-15 05:47:45.299 ThaliTest[1011:1261770] multipeer session: start timer: 0x15bb74a0
,2015-12-15 05:47:45.300 ThaliTest[1011:1261770] server session: connect
,2015-12-15 05:47:45.301 ThaliTest[1011:1261770] server session: stateChange:0->1 Apple-Iphone5-1_PT356
,2015-12-15 05:47:45.316 ThaliTest[1011:1261770] server: accepting invitation Apple-Iphone5-1_PT356
,2015-12-15T04:47:46.243Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.aa89HA==
2015-12-15T04:47:46.244Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:47.952 ThaliTest[1011:1263536] server session: connected
2015-12-15 05:47:47.953 ThaliTest[1011:1263536] server session: stateChange:1->2 Apple-IpadAir2-1_PT2678
,2015-12-15 05:47:47.973 ThaliTest[1011:1261770] server relay: connected (to port: 59277)
,2015-12-15T04:47:47.982Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15 05:47:48.060 ThaliTest[1011:1263537] server session: connected
2015-12-15 05:47:48.060 ThaliTest[1011:1263537] server session: stateChange:1->2 Apple-Iphone5-1_PT356
,2015-12-15 05:47:48.080 ThaliTest[1011:1261770] server relay: connected (to port: 59277)
,2015-12-15T04:47:48.087Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:47:48.291Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-15T04:47:48.306Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-15T04:47:48.324Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-15T04:47:48.342Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-15T04:47:48.356Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:47:48.366 ThaliTest[1011:1263536] server session: not connected Apple-IpadAir2-1_PT2678
,2015-12-15T04:47:48.606Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-15T04:47:48.823Z SendDataTCPServer.js: TCP/IP server has received 49578 bytes of data
,2015-12-15T04:47:48.842Z SendDataTCPServer.js: TCP/IP server has received 83078 bytes of data
,2015-12-15T04:47:48.859Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:47:49.402 ThaliTest[1011:1263536] server session: not connected Apple-Iphone5-1_PT356
,2015-12-15 05:47:51.252 ThaliTest[1011:1261974] jxcore: disconnect
2015-12-15 05:47:51.252 ThaliTest[1011:1261974] jxcore: disconnect: fail
2015-12-15T04:47:51.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA,==
2015-12-15T04:47:51.253Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT356.aa89HA== with availability status: true
2015-12-15T04:47:51.253Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
2015,-12-15T04:47:51.254Z SendDataConnector.js: do connect now
,2015-12-15 05:47:51.256 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:51.256 ThaliTest[1011:1261974] client: connect: unreachable Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:51.257 ThaliTest[1011:1261974] jxc,ore: connect: fail: Peer unreachable
2015-12-15T04:47:51.257Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:47:51.257Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:47:51.258Z SendDataC,onnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:56.259Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:56.260Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:01.261 ThaliTest[1011:1261974] jxcore: disconnect
2015-12-15 05:48:01.262 ThaliTest[1011:1261974] jxcore: disconnect: fail
2015-12-15T04:48:01.262Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA,==
2015-12-15T04:48:01.263Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT356.aa89HA== with availability status: true
2015-12-15T04:48:01.263Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:48:01.263Z SendDataConnector.js: do connect now
2015-12-15 05:48:01.264 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:01.265 ThaliTest[1011:1261974] client: connect: unreachable Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:48:01.266 ThaliTest[1011:1261974] jxcore: connect: fail: Peer unreachable
2015-12-15T04:48:01.266Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer unreachable
2015-12-15T04:48:01.267Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:48:01.267Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:48:06.272Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:48:06.272Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:11.286 ThaliTest[1011:1261974] jxcore: disconnect
2015-12-15 05:48:11.286 ThaliTest[1011:1261974] jxcore: disconnect: fail
2015-12-15T04:48:11.287Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA,==
2015-12-15T04:48:11.287Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT356.aa89HA== with availability status: true
2015-12-15T04:48:11.287Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
2015,-12-15T04:48:11.288Z SendDataConnector.js: do connect now
,2015-12-15 05:48:11.288 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:48:11.289 ThaliTest[1011:1261974] client: connect: unreachable Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:11.290 ThaliTest[1011:1261974] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:48:11.290Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T04:48:11.292Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:48:11.292Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15 05:48:15.301 ThaliTest[1011:1261770] multipeer session: restart
,2015-12-15 05:48:15.338 ThaliTest[1011:1261770] client: found peer: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:48:15.338 ThaliTest[1011:1261770] client: found peer: Apple-IpadAir2-1_PT2678.ad0lIQ==
2015-12-15 05:48:15.339 ThaliTest[1011:1261770] client,: found peer: Apple-Iphone5s-1_PT4162.hYB3TQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.aa89HA==","peerName":"(null)","peerAvailable":true}]
,2015-12-15T04:48:16.301Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT356.aa89HA==
2015-12-15T04:48:16.302Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:21.313 ThaliTest[1011:1261974] jxcore: disconnect
2015-12-15 05:48:21.314 ThaliTest[1011:1261974] jxcore: disconnect: fail
2015-12-15T04:48:21.314Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA,==
2015-12-15T04:48:21.315Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT356.aa89HA== with availability status: true
2015-12-15T04:48:21.315Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
2015,-12-15T04:48:21.315Z SendDataConnector.js: do connect now
,2015-12-15 05:48:21.316 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:21.317 ThaliTest[1011:1261974] client session: connect
2015-12-15 05:48:21.318 ThaliTest[1011:1261974] client session: stateChange:0->1 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:24.205 ThaliTest[1011:1263648] client session: connected
2015-12-15 05:48:24.205 ThaliTest[1011:1263648] client session: stateChange:1->2 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:24.261 ThaliTest[1011:1263678] client session: fireConnectCallback: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:48:24.261 ThaliTest[1011:1263678] jxcore: connect: success
2015-12-15T04:48:24.262Z SendDataConnector.js: CLIENT connected t,o 59285, error: null
2015-12-15T04:48:24.263Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:48:24.267 ThaliTest[1011:1261770] client: relay established
2015-12-15 05:48:24.268 ThaliTest[1011:1261770] client: new accepted socket: 0x15bca6d0
,2015-12-15T04:48:24.283Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:48:24.621Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-15T04:48:24.660Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-15T04:48:24.732Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:48:24.732Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:48:24.732Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:48:24.733Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:48:24.733 ThaliTest[1011:1261974] jxcore: disconnect
2015-12-15 05:48:24.733 ThaliTest[1011:1261974] client session: disconnectFromPeer: Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:24.734 ThaliTest[1011:1261974] client session: disconnect
,2015-12-15 05:48:24.734 ThaliTest[1011:1261974] client session: stateChange:2->0 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:24.800 ThaliTest[1011:1261974] jxcore: disconnect: success
2015-12-15T04:48:24.801Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA==
,---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15T04:48:24.802Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15T04:48:24.802Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15T04:48:24.802Z SendDataConnector.js: do connect now
,2015-12-15 05:48:24.803 ThaliTest[1011:1261974] jxcore: connect Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:48:24.803 ThaliTest[1011:1261974] client session: connect
,2015-12-15 05:48:24.804 ThaliTest[1011:1261974] client session: stateChange:0->1 Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:48:27.472 ThaliTest[1011:1263650] client session: connected
2015-12-15 05:48:27.472 ThaliTest[1011:1263650] client session: stateChange:1->2 Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:48:27.478 ThaliTest[1011:1263650] client session: fireConnectCallback: Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:48:27.479 ThaliTest[1011:1263650] jxcore: connect: success
,2015-12-15T04:48:27.481Z SendDataConnector.js: CLIENT connected to 59288, error: null
,2015-12-15T04:48:27.481Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:48:27.485 ThaliTest[1011:1261770] client: relay established
,2015-12-15 05:48:27.485 ThaliTest[1011:1261770] client: new accepted socket: 0x15ca9ac0
,2015-12-15T04:48:27.498Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:48:27.859Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-15T04:48:27.921Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-15T04:48:27.934Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:48:27.934Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:48:27.934Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:48:27.935Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:48:27.935 ThaliTest[1011:1261974] jxcore: disconnect
2015-12-15 05:48:27.935 ThaliTest[1011:1261974] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:48:27.936 ThaliTest[1011:1261974] client session: disconnect
,2015-12-15 05:48:27.936 ThaliTest[1011:1261974] client session: stateChange:2->0 Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:48:28.000 ThaliTest[1011:1261974] jxcore: disconnect: success
,2015-12-15T04:48:28.001Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4162.hYB3TQ==
---- round done--------
,startWithNextDevice
,device[4]: Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:48:28.002Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:48:28.002Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:48:28.002Z SendDataConnector.js: do connect now
,2015-12-15 05:48:28.003 ThaliTest[1011:1261974] jxcore: connect Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:48:28.003 ThaliTest[1011:1261974] client session: connect
,2015-12-15 05:48:28.003 ThaliTest[1011:1261974] client session: stateChange:0->1 Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:48:28.665 ThaliTest[1011:1261770] multipeer session: reset timer
2015-12-15 05:48:28.665 ThaliTest[1011:1261770] multipeer session: stop timer
2015-12-15 05:48:28.665 ThaliTest[1011:1261770] multipeer session: start timer: 0x15bb74a0
2015-,12-15 05:48:28.666 ThaliTest[1011:1261770] server session: connect
2015-12-15 05:48:28.666 ThaliTest[1011:1261770] server session: stateChange:0->1 Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:28.677 ThaliTest[1011:1261770] server: accepting invitation Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:31.276 ThaliTest[1011:1263650] server session: connected
,2015-12-15 05:48:31.276 ThaliTest[1011:1263650] server session: stateChange:1->2 Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:31.285 ThaliTest[1011:1261770] server relay: connected (to port: 59277)
2015-12-15T04:48:31.291Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:48:31.688Z SendDataTCPServer.js: TCP/IP server has received 49436 bytes of data
,2015-12-15T04:48:31.704Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-15T04:48:31.720Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-15 05:48:31.732 ThaliTest[1011:1263649] client session: connected
,2015-12-15 05:48:31.732 ThaliTest[1011:1263649] client session: stateChange:1->2 Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15T04:48:31.745Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:48:31.785 ThaliTest[1011:1263678] server session: not connected Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:32.180 ThaliTest[1011:1263649] client session: fireConnectCallback: Apple-IpadAir2-1_PT2678.ad0lIQ==
2015-12-15 05:48:32.181 ThaliTest[1011:1263649] jxcore: connect: success
2015-12-15T04:48:32.182Z SendDataConnector.js: CLIENT connected, to 59292, error: null
2015-12-15T04:48:32.182Z SendDataConnector.js: CLIENT starting client 
2015-12-15 05:48:32.186 ThaliTest[1011:1261770] client: relay established
,2015-12-15 05:48:32.186 ThaliTest[1011:1261770] client: new accepted socket: 0x15caf040
,2015-12-15T04:48:32.198Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:48:32.463Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-15T04:48:32.501Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:48:32.501Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-15T04:48:32.502Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:48:32.502Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:48:32.502 ThaliTest[1011:1261974] jxcore: disconnect
,2015-12-15 05:48:32.503 ThaliTest[1011:1261974] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2678.ad0lIQ==
2015-12-15 05:48:32.503 ThaliTest[1011:1261974] client session: disconnect
,2015-12-15 05:48:32.504 ThaliTest[1011:1261974] client session: stateChange:2->0 Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:48:32.570 ThaliTest[1011:1261974] jxcore: disconnect: success
,2015-12-15T04:48:32.570Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.ad0lIQ==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-15T04:48:32.573Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:48:32.573Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
2015-12-15 05:48:33.288 ThaliTest[1011:1261974] jxcore: stopBroadcasting
2015-12-15 05:48:33.288 ThaliTest[1011:1261974] THEMultipeerSession stopping peer
2015-12-15 05:48:33.288 ThaliTest[1011:1261974] multipeer session: stop timer,
2015-12-15 05:48:33.289 ThaliTest[1011:1261974] server session: disconnect
2015-12-15 05:48:33.289 ThaliTest[1011:1261974] server session: stateChange:2->0 Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:33.299 ThaliTest[1011:1261974] server session: disconnect
2015-12-15 05:48:33.300 ThaliTest[1011:1261974] server session: stateChange:2->0 Apple-IpadAir2-1_PT2678
,2015-12-15 05:48:33.319 ThaliTest[1011:1261974] server session: disconnect
2015-12-15 05:48:33.320 ThaliTest[1011:1261974] server session: stateChange:2->0 Apple-Iphone5-1_PT356
,2015-12-15 05:48:33.329 ThaliTest[1011:1261974] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-15T04:48:33.348Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:33.350Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:33.354Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:33.356Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
