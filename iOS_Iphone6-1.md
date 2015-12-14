#### Test 506502788f5bfb2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/212547B3-F297-4F2D-A2EB-02F81E36DC94/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/212547B3-F297-4F2D-A2EB-02F81E36DC94/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/10513F36-C018-4B6D-AEEF-835B9A7F5335/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55820"
,(lldb)     command script import "/tmp/212547B3-F297-4F2D-A2EB-02F81E36DC94/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 21:16:06.278 ThaliTest[938:1199736] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/988C8074-1318-4A50-A2E7-A8CB7DAEFC7E/Library/Cookies/Cookies.binarycookies
,2015-12-14 21:16:06.702 ThaliTest[938:1199736] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 21:16:06.703 ThaliTest[938:1199736] Multi-tasking -> Device: YES, App: YES
,2015-12-14 21:16:06.712 ThaliTest[938:1199736] Unlimited access to network resources
,2015-12-14 21:16:06.727 ThaliTest[938:1199736] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 21:16:15.893 ThaliTest[938:1199736] Resetting plugins due to page load.
,2015-12-14 21:16:19.065 ThaliTest[938:1199736] Finished load of: file:///var/mobile/Containers/Bundle/Application/10513F36-C018-4B6D-AEEF-835B9A7F5335/ThaliTest.app/www/index.html
,2015-12-14 21:16:19.082 ThaliTest[938:1199736] JXcore Cordova plugin initializing
,2015-12-14 21:16:19.084 ThaliTest[938:1199955] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-14 21:16:20.255 ThaliTest[938:1199736] THREAD WARNING: ['JXcore'] took '76.997803' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 21:21:34.033 ThaliTest[938:1199955] jxcore: startBroadcasting
,2015-12-14 21:21:34.051 ThaliTest[938:1199955] server: starting Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:21:34.052 ThaliTest[938:1199955] multipeer session: start timer: 0x18b7c690
2015-12-14 21:21:34.053 ThaliTest[938:1199955] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4966
2015-12-14 21:21:34.054 ThaliTest[938:1199955] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-14 21:21:35.085 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.P6/fMg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1173.P6/fMg==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT1,173.P6/fMg==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2015-12-14 21:21:35.720 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.KnhjEg==
,teardown
,testFindPeers stopped
,2015-12-14 21:21:38.261 ThaliTest[938:1199955] jxcore: stopBroadcasting
2015-12-14 21:21:38.262 ThaliTest[938:1199955] THEMultipeerSession stopping peer
2015-12-14 21:21:38.262 ThaliTest[938:1199955] multipeer session: stop timer
2015-12-14 21:21:38.263 ThaliTest[938:1199955] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 58185
,2015-12-14 21:21:38.330 ThaliTest[938:1199955] jxcore: startBroadcasting
,2015-12-14 21:21:38.335 ThaliTest[938:1199955] server: starting Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:21:38.335 ThaliTest[938:1199955] multipeer session: start timer: 0x18b81430
2015-12-14 21:21:38.336 ThaliTest[938:1199955] THEMultipeerSession i,nitialized peer Apple-Iphone6-1_PT4966
2015-12-14 21:21:38.336 ThaliTest[938:1199955] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-14T20:21:38.340Z SendDataTCPServer.js: TCP/IP server is bound to port: 58185
,2015-12-14 21:21:39.270 ThaliTest[938:1199736] client: found peer: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:39.273 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.P6/fMg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphon,e6-1_PT4966.GaMN6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14T20:21:39.275Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_P,T4966.GaMN6Q==
,2015-12-14T20:21:39.276Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14T20:21:39.277Z SendDataConnector.js: do connect now
,2015-12-14 21:21:39.278 ThaliTest[938:1199955] jxcore: connect Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:21:39.283 ThaliTest[938:1199955] client session: connect
,2015-12-14 21:21:39.285 ThaliTest[938:1199955] client session: stateChange:0->1 Apple-Iphone6-1_PT4966.GaMN6Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1173.P6/fMg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 21:21:39.488 ThaliTest[938:1199736] client: lost peer: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:39.488 ThaliTest[938:1199736] client session: onPeerLost: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:39.489 ThaliTest[938:1199736] cl,ient session: onLinkFailure: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:39.489 ThaliTest[938:1199736] client session: disconnect
2015-12-14 21:21:39.489 ThaliTest[938:1199736] client session: stateChange:1->0 Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:21:39.491 ThaliTest[938:1199736] client session: fireConnectCallback: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:39.492 ThaliTest[938:1199736] jxcore: connect: fail: Peer disconnected
2015-12-14 21:21:39.492 ThaliTest[938:1199736] cli,ent: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14T20:21:39.494Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-14T20:21:39.495Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T20:21:39,.495Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.GaMN6Q==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1173.b8TW0A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 21:21:39.867 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5632.ug/nGg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 21:21:39.936 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5395.sHfmmA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 21:21:40.977 ThaliTest[938:1199736] client: lost peer: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:40.978 ThaliTest[938:1199736] client session: onPeerLost: Apple-IpadAir2-1_PT1173.P6/fMg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1173.P6/fMg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14T20:21:44.498Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:21:44.499Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:21:49.510 ThaliTest[938:1199955] jxcore: disconnect
2015-12-14 21:21:49.511 ThaliTest[938:1199955] jxcore: disconnect: fail
2015-12-14T20:21:49.511Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.GaMN6Q=,=
2015-12-14T20:21:49.512Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4966.GaMN6Q== with availability status: true
2015-12-14T20:21:49.512Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
201,5-12-14T20:21:49.512Z SendDataConnector.js: do connect now
,2015-12-14 21:21:49.513 ThaliTest[938:1199955] jxcore: connect Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:21:49.514 ThaliTest[938:1199955] client: connect: unreachable Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:49.515 ThaliTest[938:1199955] jxcore: connect: fail: Peer unreachable
2015-12-14T20:21:49.516Z SendDataConnector.js: CLIENT conne,cted to 0, error: Peer unreachable
2015-12-14T20:21:49.516Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T20:21:49.516Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:21:54.520Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:21:54.521Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:21:59.525 ThaliTest[938:1199955] jxcore: disconnect
2015-12-14 21:21:59.526 ThaliTest[938:1199955] jxcore: disconnect: fail
2015-12-14T20:21:59.526Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.GaMN6Q=,=
2015-12-14T20:21:59.527Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4966.GaMN6Q== with availability status: true
2015-12-14T20:21:59.527Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
201,5-12-14T20:21:59.527Z SendDataConnector.js: do connect now
,2015-12-14 21:21:59.528 ThaliTest[938:1199955] jxcore: connect Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:59.530 ThaliTest[938:1199955] client: connect: unreachable Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:59.530 ThaliTest[938:1199955] jxco,re: connect: fail: Peer unreachable
2015-12-14T20:21:59.530Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:21:59.531Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T20:21:59.531Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:22:04.535Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:22:04.536Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:08.337 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:22:08.374 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:08.375 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:08.375 ThaliTest[938:1199736] client: ,found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:22:09.543 ThaliTest[938:1199955] jxcore: disconnect
2015-12-14 21:22:09.544 ThaliTest[938:1199955] jxcore: disconnect: fail
2015-12-14T20:22:09.544Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.GaMN6Q=,=
2015-12-14T20:22:09.544Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4966.GaMN6Q== with availability status: true
2015-12-14T20:22:09.545Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
201,5-12-14T20:22:09.545Z SendDataConnector.js: do connect now
,2015-12-14 21:22:09.546 ThaliTest[938:1199955] jxcore: connect Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:09.547 ThaliTest[938:1199955] client: connect: unreachable Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:22:09.548 ThaliTest[938:1199955] jxcore: connect: fail: Peer unreachable
2015-12-14T20:22:09.548Z SendDataConnector.js: CLIENT conne,cted to 0, error: Peer unreachable
2015-12-14T20:22:09.549Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T20:22:09.549Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:22:14.559Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14T20:22:14.560Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:19.561 ThaliTest[938:1199955] jxcore: disconnect
2015-12-14 21:22:19.562 ThaliTest[938:1199955] jxcore: disconnect: fail
2015-12-14T20:22:19.562Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.GaMN6Q=,=
2015-12-14T20:22:19.563Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4966.GaMN6Q== with availability status: true
2015-12-14T20:22:19.563Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:22:19.563Z SendDataConnector.js: do connect now
,2015-12-14 21:22:19.564 ThaliTest[938:1199955] jxcore: connect Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:19.565 ThaliTest[938:1199955] client: connect: unreachable Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:22:19.566 ThaliTest[938:1199955] jxcore: connect: fail: Peer unreachable
2015-12-14T20:22:19.567Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:22:19.567Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-14T20:22:19.570Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 21:22:19.571 ThaliTest[938:1199955] jxcore: disconnect
2015-12-14 21:22:19.571 ThaliTest[938:1199955] jxcore: disconnect: fail
,2015-12-14T20:22:19.572Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14T20:22:19.576Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14T20:22:19.577Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14T20:22:19.577Z SendDataConnector.js: do connect now
,2015-12-14 21:22:19.579 ThaliTest[938:1199955] jxcore: connect Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:22:19.579 ThaliTest[938:1199955] client session: connect
2015-12-14 21:22:19.580 ThaliTest[938:1199955] client session: stateChange:0->1 Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:22:20.403 ThaliTest[938:1199736] multipeer session: reset timer
2015-12-14 21:22:20.404 ThaliTest[938:1199736] multipeer session: stop timer
2015-12-14 21:22:20.404 ThaliTest[938:1199736] multipeer session: start timer: 0x18b81430
2015-12-14 21:22:20.405 ThaliTest[938:1199736] server session: connect
2015-12-14 21:22:20.405 ThaliTest[938:1199736] server session: stateChange:0->1 Apple-Iphone5-1_PT5632
,2015-12-14 21:22:20.414 ThaliTest[938:1199736] server: accepting invitation Apple-Iphone5-1_PT5632
,2015-12-14 21:22:22.441 ThaliTest[938:1200788] client session: connected
,2015-12-14 21:22:22.441 ThaliTest[938:1200788] client session: stateChange:1->2 Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:22:22.471 ThaliTest[938:1200785] client session: fireConnectCallback: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:22:22.472 ThaliTest[938:1200785] jxcore: connect: success
2015-12-14T20:22:22.473Z SendDataConnector.js: CLIENT connected t,o 58192, error: null
2015-12-14T20:22:22.474Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 21:22:22.477 ThaliTest[938:1199736] client: relay established
2015-12-14 21:22:22.477 ThaliTest[938:1199736] client: new accepted socket: 0x18c57340
,2015-12-14T20:22:22.493Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14 21:22:22.954 ThaliTest[938:1200788] server session: connected
2015-12-14 21:22:22.954 ThaliTest[938:1200788] server session: stateChange:1->2 Apple-Iphone5-1_PT5632
,2015-12-14 21:22:22.958 ThaliTest[938:1199736] server relay: connected (to port: 58185)
,2015-12-14T20:22:22.964Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14T20:22:22.965Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:22:23.013Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T20:22:23.026Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T20:22:23.026Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T20:22:23.027Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T20:22:23.027Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:23.029 ThaliTest[938:1199955] jxcore: disconnect
2015-12-14 21:22:23.029 ThaliTest[938:1199955] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:22:23.029 ThaliTest[938:1199955] client session: disconnect
2015-12-14 21:22:23.029 ThaliTest[938:1199955] client session: stateChange:2->0 Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:22:23.035 ThaliTest[938:1199955] jxcore: disconnect: success
2015-12-14T20:22:23.035Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1173.b8TW0A==
---- round done--------
startWithNextDevice
device[3]: App,le-Iphone5-1_PT5632.ug/nGg==
2015-12-14T20:22:23.036Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14T20:22:23.036Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14T20:22:23.036Z SendDataConnector.js: do connect now
2015-12-14 21:22:23.036 ThaliTest[938:1199955] jxcore: connect Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:23.036 ThaliTest[938:1199955] client session: connect
2015-12-14 21:22:23.036 ThaliTest[938:119,9955] client session: stateChange:0->1 Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14T20:22:23.670Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-14T20:22:23.686Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-14T20:22:23.700Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-14T20:22:23.938Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-14T20:22:23.956Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-14T20:22:23.971Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:22:24.067 ThaliTest[938:1200600] server session: not connected Apple-Iphone5-1_PT5632
,2015-12-14 21:22:25.644 ThaliTest[938:1200785] client session: connected
2015-12-14 21:22:25.647 ThaliTest[938:1200785] client session: stateChange:1->2 Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:25.651 ThaliTest[938:1200785] client session: fireConnectCallback: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:25.652 ThaliTest[938:1200785] jxcore: connect: success
2015-12-14T20:22:25.653Z SendDataConnector.js: CLIENT connected to 58196, error: null
2015-12-14T20:22:25.653Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 21:22:25.658 ThaliTest[938:1199736] client: relay established
2015-12-14 21:22:25.658 ThaliTest[938:1199736] client: new accepted socket: 0x18c62e90
,2015-12-14T20:22:25.671Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T20:22:26.089Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14T20:22:26.102Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T20:22:26.103Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-14T20:22:26.103Z SendDataConnector.js: CLIENT Stop now
2015-12-14T20:22:26.103Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:26.104 ThaliTest[938:1199955] jxcore: disconnect
2015-12-14 21:22:26.104 ThaliTest[938:1199955] client session: disconnectFromPeer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:26.104 ThaliTest[938:1199955] client session: disconnect,
2015-12-14 21:22:26.104 ThaliTest[938:1199955] client session: stateChange:2->0 Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:26.108 ThaliTest[938:1199955] jxcore: disconnect: success
2015-12-14T20:22:26.109Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5632.ug/nGg==
---- round done--------
startWithNextDevice
device[4]: Appl,e-Iphone5s-1_PT5395.sHfmmA==
2015-12-14T20:22:26.109Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14T20:22:26.109Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14T20:22:26.109Z SendDataConnector.js: do connect now
2015-12-14 21:22:26.109 ThaliTest[938:1199955] jxcore: connect Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:26.109 ThaliTest[938:1199955] client session: connect
2015-12-14 21:22:26.110 ThaliTest[938:1199955] client session: stateChange:0->1 Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:28.787 ThaliTest[938:1200788] client session: connected
2015-12-14 21:22:28.788 ThaliTest[938:1200788] client session: stateChange:1->2 Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:28.839 ThaliTest[938:1200600] client session: fireConnectCallback: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:28.840 ThaliTest[938:1200600] jxcore: connect: success
2015-12-14T20:22:28.841Z SendDataConnector.js: CLIENT connected to 58199, error: null
2015-12-14T20:22:28.841Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 21:22:28.846 ThaliTest[938:1199736] client: relay established
2015-12-14 21:22:28.846 ThaliTest[938:1199736] client: new accepted socket: 0x18b96b90
,2015-12-14T20:22:28.858Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T20:22:29.306Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T20:22:29.319Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T20:22:29.370Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T20:22:29.370Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-14T20:22:29.370Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T20:22:29.371Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:29.371 ThaliTest[938:1199955] jxcore: disconnect
2015-12-14 21:22:29.371 ThaliTest[938:1199955] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:29.371 ThaliTest[938:1199955] client session: disconnect
2015-12-14 21:22:29.372 ThaliTest[938:1199955] client session: stateChange:2->0 Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:29.376 ThaliTest[938:1199955] jxcore: disconnect: success
2015-12-14T20:22:29.376Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5395.sHfmmA==
---- round done--------
startWithNextDevice
weAreDoneNow, ,resultArray.length: 4
sendReportNow
,done, now sending data to server
2015-12-14T20:22:29.379Z SendDataConnector.js: CLIENT Stop now
2015-12-14T20:22:29.379Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:31.274 ThaliTest[938:1199736] multipeer session: reset timer
2015-12-14 21:22:31.275 ThaliTest[938:1199736] multipeer session: stop timer
2015-12-14 21:22:31.275 ThaliTest[938:1199736] multipeer session: start timer: 0x18b81430
,2015-12-14 21:22:31.275 ThaliTest[938:1199736] server session: connect
,2015-12-14 21:22:31.277 ThaliTest[938:1199736] server session: stateChange:0->1 Apple-IpadAir2-1_PT1173
,2015-12-14 21:22:31.287 ThaliTest[938:1199736] server: accepting invitation Apple-IpadAir2-1_PT1173
,2015-12-14 21:22:33.965 ThaliTest[938:1200600] server session: connected
2015-12-14 21:22:33.965 ThaliTest[938:1200600] server session: stateChange:1->2 Apple-IpadAir2-1_PT1173
,2015-12-14 21:22:33.980 ThaliTest[938:1199736] server relay: connected (to port: 58185)
2015-12-14T20:22:33.980Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:22:34.429Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T20:22:34.506Z SendDataTCPServer.js: TCP/IP server has received 12572 bytes of data
,2015-12-14T20:22:34.521Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:22:34.576 ThaliTest[938:1200793] server session: not connected Apple-IpadAir2-1_PT1173
,2015-12-14 21:23:01.277 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:23:01.319 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:23:01.319 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:23:01.320 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:23:04.808 ThaliTest[938:1199736] multipeer session: reset timer
2015-12-14 21:23:04.808 ThaliTest[938:1199736] multipeer session: stop timer
2015-12-14 21:23:04.808 ThaliTest[938:1199736] multipeer session: start timer: 0x18b81430
2015-12-,14 21:23:04.809 ThaliTest[938:1199736] server session: connect
2015-12-14 21:23:04.809 ThaliTest[938:1199736] server session: stateChange:0->1 Apple-Iphone5s-1_PT5395
,2015-12-14 21:23:04.818 ThaliTest[938:1199736] server: accepting invitation Apple-Iphone5s-1_PT5395
,2015-12-14 21:23:08.077 ThaliTest[938:1200886] server session: connected
2015-12-14 21:23:08.077 ThaliTest[938:1200886] server session: stateChange:1->2 Apple-Iphone5s-1_PT5395
,2015-12-14 21:23:08.084 ThaliTest[938:1199736] server relay: connected (to port: 58185)
2015-12-14T20:23:08.089Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:23:08.535Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-14T20:23:08.549Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-14T20:23:08.568Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-14T20:23:08.584Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-14T20:23:08.601Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:23:09.121 ThaliTest[938:1200869] server session: not connected Apple-Iphone5s-1_PT5395
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
,2015-12-14 21:23:32.385 ThaliTest[938:1199955] jxcore: startBroadcasting
,2015-12-14 21:23:32.385 ThaliTest[938:1199955] jxcore: startBroadcasting: failure
,weAreDoneNow
done, now sending data to server
,done, now sending data to server
,2015-12-14 21:23:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:23:34.853 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:23:34.855 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:23:34.856 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:24:04.809 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:24:04.849 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:24:04.849 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:24:04.852 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:24:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:24:34.857 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:24:35.328 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:24:35.328 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:25:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:25:04.850 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:25:04.851 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:25:04.852 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:25:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:26:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:26:04.845 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:26:04.847 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:26:04.847 ThaliTest[938:1199736] client:, found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:26:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:27:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:27:04.854 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:27:04.855 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:27:04.856 ThaliTest[938:1199736] client:, found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:27:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:27:34.845 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:27:34.845 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:27:37.293 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:28:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:28:04.849 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:28:04.850 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:28:04.870 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:28:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:28:34.847 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:28:34.848 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:28:34.850 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:29:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:29:04.847 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:29:04.850 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:29:04.850 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:29:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:30:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:30:04.846 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:30:04.846 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:30:04.849 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:30:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:30:34.848 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:30:34.848 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:30:34.851 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:31:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:31:04.845 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:31:04.846 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:31:04.850 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:31:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:32:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:32:04.846 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:32:04.846 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:32:04.846 ThaliTest[938:1199736] client: ,found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:32:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:32:34.846 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:32:34.849 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:32:34.850 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:33:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:33:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:33:34.847 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:33:34.849 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:33:34.849 ThaliTest[938:1199736] client:, found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:34:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:34:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:34:34.847 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:34:34.847 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:34:34.847 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:35:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:35:04.847 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:35:04.849 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:35:04.850 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:35:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:35:34.848 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:35:34.849 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:35:34.852 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:36:04.809 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:36:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:36:34.843 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:36:34.846 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:36:34.847 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:37:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:37:04.846 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:37:04.851 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:37:04.852 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:37:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:37:34.848 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:37:34.848 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:37:34.851 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:38:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:38:04.847 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:38:04.848 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:38:04.849 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:38:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:38:34.848 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:38:34.848 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:38:34.849 ThaliTest[938:1199736] client:, found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:39:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:39:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:39:34.844 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:39:34.846 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:39:34.846 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:40:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:40:04.848 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:40:04.848 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:40:04.849 ThaliTest[938:1199736] client:, found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,timeout now
,2015-12-14 21:40:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:40:34.846 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:40:34.847 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:40:35.053 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:41:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:41:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:41:34.843 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:41:34.848 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:41:34.849 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:42:04.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:42:04.848 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:42:04.848 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:42:04.855 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:42:31.744 ThaliTest[938:1199736] client: lost peer: Apple-IpadAir2-1_PT1173.b8TW0A==
2015-12-14 21:42:31.745 ThaliTest[938:1199736] client session: onPeerLost: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:42:34.810 ThaliTest[938:1199736] multipeer session: restart
,2015-12-14 21:42:34.843 ThaliTest[938:1199736] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:42:34.848 ThaliTest[938:1199736] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:42:42.848 ThaliTest[938:1199736] client: found peer: Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:43:04.810 ThaliTest[938:1199736] multipeer session: restart

```
