#### Test 506502789b39735_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502789b39735/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E265AC1D-EEDE-4EF2-8539-86AAEE86F8B2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E265AC1D-EEDE-4EF2-8539-86AAEE86F8B2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502789b39735/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502789b39735/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/450087C9-DC0D-4B45-B505-98E7B5D0795C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58075"
,(lldb)     command script import "/tmp/E265AC1D-EEDE-4EF2-8539-86AAEE86F8B2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 02:32:42.568 ThaliTest[243:30055] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/508CEFA1-4FA8-4446-A738-4F76E6F28B06/Library/Cookies/Cookies.binarycookies
,2015-12-16 02:32:42.988 ThaliTest[243:30055] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 02:32:42.990 ThaliTest[243:30055] Multi-tasking -> Device: YES, App: YES
,2015-12-16 02:32:43.000 ThaliTest[243:30055] Unlimited access to network resources
,2015-12-16 02:32:43.015 ThaliTest[243:30055] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 02:32:52.032 ThaliTest[243:30055] Resetting plugins due to page load.
,2015-12-16 02:32:55.298 ThaliTest[243:30055] Finished load of: file:///var/mobile/Containers/Bundle/Application/450087C9-DC0D-4B45-B505-98E7B5D0795C/ThaliTest.app/www/index.html
,2015-12-16 02:32:55.474 ThaliTest[243:30055] JXcore Cordova plugin initializing
,2015-12-16 02:32:55.475 ThaliTest[243:30291] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-16 02:32:56.574 ThaliTest[243:30055] THREAD WARNING: ['JXcore'] took '80.648926' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 02:37:43.914 ThaliTest[243:30291] jxcore: startBroadcasting
,2015-12-16 02:37:43.932 ThaliTest[243:30291] server: starting Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:37:43.933 ThaliTest[243:30291] multipeer session: start timer: 0x16381960
2015-12-16 02:37:43.934 ThaliTest[243:30291] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3762
2015-12-16 02:37:43.934 ThaliTest[243:30291] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-16 02:38:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:38:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:39:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:39:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:40:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:40:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:41:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:41:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:42:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:42:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:43:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:43:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:44:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:44:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:45:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:45:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:46:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:46:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:47:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:47:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:48:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:48:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:49:13.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:49:43.935 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:50:13.882 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:50:43.882 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:51:13.882 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:51:43.882 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:52:13.882 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:52:43.882 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:53:13.882 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:53:43.882 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:54:13.882 ThaliTest[243:30055] multipeer session: restart
,timeout now
,weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-16 02:54:24.209 ThaliTest[243:30291] jxcore: stopBroadcasting
2015-12-16 02:54:24.209 ThaliTest[243:30291] THEMultipeerSession stopping peer
2015-12-16 02:54:24.209 ThaliTest[243:30291] multipeer session: stop timer
2015-12-16 02:54:24.210 ThaliTest[243:30291] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":1}bt-address length : 0
,daya100000
check server
,serverPort is 49725
,2015-12-16 02:54:24.273 ThaliTest[243:30291] jxcore: startBroadcasting
,2015-12-16 02:54:24.279 ThaliTest[243:30291] server: starting Apple-Iphone6-1_PT3762.fjZKAg==
2015-12-16 02:54:24.279 ThaliTest[243:30291] multipeer session: start timer: 0x1643e4c0
2015-12-16 02:54:24.280 ThaliTest[243:30291] THEMultipeerSession initial,ized peer Apple-Iphone6-1_PT3762
2015-12-16 02:54:24.280 ThaliTest[243:30291] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-16T01:54:24.284Z SendDataTCPServer.js: TCP/IP server is bound to port: 49725
,2015-12-16 02:54:24.300 ThaliTest[243:30055] client: found peer: Apple-Iphone6-1_PT3762.d2shgQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3762.d2shgQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
startWithNextDevice
device[1]: Apple-Iphone6-1_PT3762.d2shgQ==
2015-12-16T01:54:24.306Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3762.d2shgQ==
2015-12-16T01:54:24.307Z SendDataConnector.js: doConnect called with peer Apple-Iphone6,-1_PT3762.d2shgQ==
2015-12-16T01:54:24.307Z SendDataConnector.js: do connect now
,2015-12-16 02:54:24.307 ThaliTest[243:30291] jxcore: connect Apple-Iphone6-1_PT3762.d2shgQ==
2015-12-16 02:54:24.308 ThaliTest[243:30291] client session: connect
,2015-12-16 02:54:24.308 ThaliTest[243:30291] client session: stateChange:0->1 Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:54:25.338 ThaliTest[243:30055] client: lost peer: Apple-Iphone6-1_PT3762.d2shgQ==
2015-12-16 02:54:25.339 ThaliTest[243:30055] client session: onPeerLost: Apple-Iphone6-1_PT3762.d2shgQ==
2015-12-16 02:54:25.339 ThaliTest[243:30055] client s,ession: onLinkFailure: Apple-Iphone6-1_PT3762.d2shgQ==
2015-12-16 02:54:25.339 ThaliTest[243:30055] client session: disconnect
2015-12-16 02:54:25.340 ThaliTest[243:30055] client session: stateChange:1->0 Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:54:25.342 ThaliTest[243:30055] client session: fireConnectCallback: Apple-Iphone6-1_PT3762.d2shgQ==
2015-12-16 02:54:25.342 ThaliTest[243:30055] jxcore: connect: fail: Peer disconnected
,2015-12-16T01:54:25.346Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-16T01:54:25.346Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T01:54:25.347Z SendDataConnector.js: tryAgain afer: 5000 ms.,
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3762.d2shgQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-16T01:54:30.353Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16T01:54:30.354Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:54:35.356 ThaliTest[243:30291] jxcore: disconnect
2015-12-16 02:54:35.356 ThaliTest[243:30291] jxcore: disconnect: fail
2015-12-16T01:54:35.357Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3762.d2shgQ==
2,015-12-16T01:54:35.357Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT3762.d2shgQ== with availability status: true
2015-12-16T01:54:35.357Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16T01:54:35.358Z SendDataConnector.js: do connect now
2015-12-16 02:54:35.359 ThaliTest[243:30291] jxcore: connect Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:54:35.360 ThaliTest[243:30291] client: connect: unreachable Apple-Iphone6-1_PT3762.d2shgQ==
2015-12-16 02:54:35.360 ThaliTest[243:30291] jxcore: connect: fail: Peer unreachable
2015-12-16T01:54:35.360Z SendDataConnector.js: CLIENT connected, to 0, error: Peer unreachable
2015-12-16T01:54:35.361Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T01:54:35.361Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T01:54:40.368Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16T01:54:40.368Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:54:45.372 ThaliTest[243:30291] jxcore: disconnect
2015-12-16 02:54:45.373 ThaliTest[243:30291] jxcore: disconnect: fail
2015-12-16T01:54:45.374Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3762.d2shgQ==
2,015-12-16T01:54:45.374Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT3762.d2shgQ== with availability status: true
2015-12-16T01:54:45.374Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3762.d2shgQ==
2015-12,-16T01:54:45.374Z SendDataConnector.js: do connect now
,2015-12-16 02:54:45.375 ThaliTest[243:30291] jxcore: connect Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:54:45.376 ThaliTest[243:30291] client: connect: unreachable Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:54:45.377 ThaliTest[243:30291] jxcore: connect: fail: Peer unreachable
2015-12-16T01:54:45.378Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T01:54:45.378Z SendDataConnector.js: CLIENT Can not Connect: Peer, unreachable
2015-12-16T01:54:45.379Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T01:54:50.391Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16T01:54:50.391Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:54:54.281 ThaliTest[243:30055] multipeer session: restart
,2015-12-16 02:54:55.394 ThaliTest[243:30291] jxcore: disconnect
2015-12-16 02:54:55.394 ThaliTest[243:30291] jxcore: disconnect: fail
2015-12-16T01:54:55.395Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3762.d2shgQ==
2,015-12-16T01:54:55.395Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT3762.d2shgQ== with availability status: true
2015-12-16T01:54:55.395Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16T01:54:55.396Z SendDataConnector.js: do connect now
2015-12-16 02:54:55.397 ThaliTest[243:30291] jxcore: connect Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:54:55.398 ThaliTest[243:30291] client: connect: unreachable Apple-Iphone6-1_PT3762.d2shgQ==
2015-12-16 02:54:55.398 ThaliTest[243:30291] jxcore: connect: fail: Peer unreachable
2015-12-16T01:54:55.399Z SendDataConnector.js: CLIENT connected, to 0, error: Peer unreachable
2015-12-16T01:54:55.399Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T01:54:55.399Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T01:55:00.401Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16T01:55:00.402Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:55:05.404 ThaliTest[243:30291] jxcore: disconnect
2015-12-16 02:55:05.404 ThaliTest[243:30291] jxcore: disconnect: fail
2015-12-16T01:55:05.405Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3762.d2shgQ==
2,015-12-16T01:55:05.405Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT3762.d2shgQ== with availability status: true
2015-12-16T01:55:05.405Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3762.d2shgQ==
2015-12,-16T01:55:05.406Z SendDataConnector.js: do connect now
,2015-12-16 02:55:05.406 ThaliTest[243:30291] jxcore: connect Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:55:05.407 ThaliTest[243:30291] client: connect: unreachable Apple-Iphone6-1_PT3762.d2shgQ==
,2015-12-16 02:55:05.408 ThaliTest[243:30291] jxcore: connect: fail: Peer unreachable
,2015-12-16T01:55:05.409Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T01:55:05.410Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-16T01:55:05.411Z SendDataConnector.js: CLIENT Stop now
,2015-12-16 02:55:05.412 ThaliTest[243:30291] jxcore: disconnect
2015-12-16 02:55:05.413 ThaliTest[243:30291] jxcore: disconnect: fail
2015-12-16T01:55:05.413Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3762.d2shgQ==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 1
,sendReportNow
,done, now sending data to server
,2015-12-16T01:55:05.422Z SendDataConnector.js: CLIENT Stop now
,teardown
,testSendData stopped
,2015-12-16 02:55:06.012 ThaliTest[243:30291] jxcore: stopBroadcasting
2015-12-16 02:55:06.013 ThaliTest[243:30291] THEMultipeerSession stopping peer
2015-12-16 02:55:06.013 ThaliTest[243:30291] multipeer session: stop timer
2015-12-16 02:55:06.013 ThaliTest[243:30291] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-16T01:55:06.016Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
