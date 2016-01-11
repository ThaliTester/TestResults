#### Test 55613145dd493c6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3896E26F-69F6-4C18-B496-27AF5840DCEA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3896E26F-69F6-4C18-B496-27AF5840DCEA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DA95D8A4-8EEC-47FB-9470-39051404CCFE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52224"
,(lldb)     command script import "/tmp/3896E26F-69F6-4C18-B496-27AF5840DCEA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 13:54:50.248 ThaliTest[1722:3665019] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C665C7F4-85C7-48F7-A104-DBDE54A9F6BB/Library/Cookies/Cookies.binarycookies
,2016-01-11 13:54:50.654 ThaliTest[1722:3665019] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 13:54:50.656 ThaliTest[1722:3665019] Multi-tasking -> Device: YES, App: YES
,2016-01-11 13:54:50.668 ThaliTest[1722:3665019] Unlimited access to network resources
,2016-01-11 13:54:50.682 ThaliTest[1722:3665019] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 13:55:00.187 ThaliTest[1722:3665019] Resetting plugins due to page load.
,2016-01-11 13:55:03.914 ThaliTest[1722:3665019] Finished load of: file:///var/mobile/Containers/Bundle/Application/DA95D8A4-8EEC-47FB-9470-39051404CCFE/ThaliTest.app/www/index.html
,2016-01-11 13:55:04.104 ThaliTest[1722:3665019] JXcore Cordova plugin initializing
2016-01-11 13:55:04.107 ThaliTest[1722:3665240] JXcore instance initializing
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
,2016-01-11 13:55:05.361 ThaliTest[1722:3665019] THREAD WARNING: ['JXcore'] took '75.346924' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-11 13:59:31.674 ThaliTest[1722:3665240] jxcore: startBroadcasting
,2016-01-11 13:59:31.690 ThaliTest[1722:3665240] server: starting Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:31.692 ThaliTest[1722:3665240] multipeer session: start timer: 0x19252e90
2016-01-11 13:59:31.692 ThaliTest[1722:3665240] THEMultipeerSession initi,alized peer Apple-Iphone6-1
2016-01-11 13:59:31.693 ThaliTest[1722:3665240] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-11 13:59:32.740 ThaliTest[1722:3665019] client: found peer: Apple-Iphone5s-1.hXPtug==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1.hXPtug==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-11 13:59:32.907 ThaliTest[1722:3665019] client: found peer: Apple-Iphone5-1.b8hDBw==
,teardown
,testFindPeers stopped
,2016-01-11 13:59:33.174 ThaliTest[1722:3665240] jxcore: stopBroadcasting
2016-01-11 13:59:33.174 ThaliTest[1722:3665240] THEMultipeerSession stopping peer
2016-01-11 13:59:33.175 ThaliTest[1722:3665240] multipeer session: stop timer
2016-01-11 13:59:33.175 ThaliTest[1722:3665240] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 49660
,2016-01-11 13:59:33.521 ThaliTest[1722:3665240] jxcore: startBroadcasting
,2016-01-11 13:59:33.522 ThaliTest[1722:3665240] server: starting Apple-Iphone6-1.zQytdg==
2016-01-11 13:59:33.523 ThaliTest[1722:3665240] multipeer session: start timer: 0x1939aef0
2016-01-11 13:59:33.523 ThaliTest[1722:3665240] THEMultipeerSession initi,alized peer Apple-Iphone6-1
2016-01-11 13:59:33.523 ThaliTest[1722:3665240] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-11T12:59:33.526Z SendDataTCPServer.js: TCP/IP server is bound to port: 49660
,2016-01-11 13:59:33.675 ThaliTest[1722:3665019] client: found peer: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:33.676 ThaliTest[1722:3665019] client: found peer: Apple-Iphone5-1.b8hDBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.hXPtug,==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5s-1.hXPtug==
2016-01-11T12:59:33.677Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.hXPtug==
2016-01-11T12:,59:33.677Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.hXPtug==
2016-01-11T12:59:33.677Z SendDataConnector.js: do connect now
2016-01-11 13:59:33.678 ThaliTest[1722:3665240] jxcore: connect Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:33.678 ThaliTest[1722:3665240] client session: connect
2016-01-11 13:59:33.678 ThaliTest[1722:3665240] client session: stateChange:0->1 Apple-Iphone5s-1.hXPtug==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.b8hDBw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:34.409 ThaliTest[1722:3665019] client: found peer: Apple-IpadAir2-1.oW56/g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.oW56/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:34.780 ThaliTest[1722:3665019] client: found peer: Apple-Iphone5-1.03CIBg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.03CIBg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:35.524 ThaliTest[1722:3665019] client: lost peer: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:35.525 ThaliTest[1722:3665019] client session: onPeerLost: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:35.525 ThaliTest[1722:3665019] client session: onLinkFailure: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:35.525 ThaliTest[1722:3665019] client session: disconnect
2016-01-11 13:59:35.525 ThaliTest[1722:3665019] client session: stateChange:1->0 Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:35.526 ThaliTest[1722:3665019] client session: fireConnectCallback: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:35.526 ThaliTest[1722:3665019] jxcore: connect: fail: Peer disconnected
2016-01-11 13:59:35.526 ThaliTest[1722:3665019] client: found peer: Apple-Iphon,e5s-1.yPThEg==
2016-01-11T12:59:35.527Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-11T12:59:35.527Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-11T12:59:35.527Z SendDataConnector.js: tryAgai,n afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.yPThEg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:36.473 ThaliTest[1722:3665019] client: lost peer: Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:36.473 ThaliTest[1722:3665019] client session: onPeerLost: Apple-Iphone5-1.b8hDBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.b8hDBw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11T12:59:40.540Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.hXPtug==
2016-01-11T12:59:40.540Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11 13:59:45.550 ThaliTest[1722:3665240] jxcore: disconnect
2016-01-11 13:59:45.550 ThaliTest[1722:3665240] jxcore: disconnect: fail
2016-01-11T12:59:45.551Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.hXPtug==
2,016-01-11T12:59:45.551Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1.hXPtug== with availability status: true
2016-01-11T12:59:45.551Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.hXPtug==
2016-01-11T12:59:45,.551Z SendDataConnector.js: do connect now
2016-01-11 13:59:45.551 ThaliTest[1722:3665240] jxcore: connect Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:45.551 ThaliTest[1722:3665240] client: connect: unreachable Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:,45.551 ThaliTest[1722:3665240] jxcore: connect: fail: Peer unreachable
2016-01-11T12:59:45.552Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T12:59:45.552Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-11T12:59:45.552Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T12:59:50.556Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.hXPtug==
2016-01-11T12:59:50.556Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11 13:59:55.567 ThaliTest[1722:3665240] jxcore: disconnect
2016-01-11 13:59:55.568 ThaliTest[1722:3665240] jxcore: disconnect: fail
2016-01-11T12:59:55.568Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.hXPtug==
2,016-01-11T12:59:55.568Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1.hXPtug== with availability status: true
2016-01-11T12:59:55.568Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.hXPtug==
2016-01-11T12:59:55.568Z SendDataConnector.js: do connect now
2016-01-11 13:59:55.568 ThaliTest[1722:3665240] jxcore: connect Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:55.568 ThaliTest[1722:3665240] client: connect: unreachable Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:55.568 ThaliTest[1722:3665240] jxcore: connect: fail: Peer unreachable
2016-01-11T12:59:55.568Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T12:59:55.569Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-11T12:59:55.569Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T13:00:00.570Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.hXPtug==
2016-01-11T13:00:00.570Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11 14:00:03.524 ThaliTest[1722:3665019] multipeer session: restart
,2016-01-11 14:00:03.541 ThaliTest[1722:3665019] client: found peer: Apple-Iphone5s-1.yPThEg==
2016-01-11 14:00:03.541 ThaliTest[1722:3665019] client: found peer: Apple-IpadAir2-1.oW56/g==
2016-01-11 14:00:03.541 ThaliTest[1722:3665019] client: found peer: Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:05.572 ThaliTest[1722:3665240] jxcore: disconnect
2016-01-11 14:00:05.573 ThaliTest[1722:3665240] jxcore: disconnect: fail
2016-01-11T13:00:05.573Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.hXPtug==
2,016-01-11T13:00:05.573Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1.hXPtug== with availability status: true
2016-01-11T13:00:05.573Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.hXPtug==
2016-01-11T13:00:05.573Z SendDataConnector.js: do connect now
2016-01-11 14:00:05.573 ThaliTest[1722:3665240] jxcore: connect Apple-Iphone5s-1.hXPtug==
2016-01-11 14:00:05.573 ThaliTest[1722:3665240] client: connect: unreachable Apple-Iphone5s-1.hXPtug==
2016-01-11 14:00:,05.573 ThaliTest[1722:3665240] jxcore: connect: fail: Peer unreachable
2016-01-11T13:00:05.574Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T13:00:05.574Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-11T13:00:05.574Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T13:00:10.575Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.hXPtug==
2016-01-11T13:00:10.575Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11 14:00:15.584 ThaliTest[1722:3665240] jxcore: disconnect
2016-01-11 14:00:15.585 ThaliTest[1722:3665240] jxcore: disconnect: fail
2016-01-11T13:00:15.585Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.hXPtug==
2,016-01-11T13:00:15.585Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1.hXPtug== with availability status: true
2016-01-11T13:00:15.585Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.hXPtug==
2016-01-11T13:00:15,.585Z SendDataConnector.js: do connect now
2016-01-11 14:00:15.585 ThaliTest[1722:3665240] jxcore: connect Apple-Iphone5s-1.hXPtug==
2016-01-11 14:00:15.585 ThaliTest[1722:3665240] client: connect: unreachable Apple-Iphone5s-1.hXPtug==
2016-01-11 14:00:,15.585 ThaliTest[1722:3665240] jxcore: connect: fail: Peer unreachable
2016-01-11T13:00:15.586Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T13:00:15.586Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2016-01-11T13:00:15.588Z SendDataConnector.js: CLIENT Stop now
,2016-01-11 14:00:15.588 ThaliTest[1722:3665240] jxcore: disconnect
2016-01-11 14:00:15.588 ThaliTest[1722:3665240] jxcore: disconnect: fail
2016-01-11T13:00:15.588Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.hXPtug==
-,--- round done--------
startWithNextDevice
device[2]: Apple-IpadAir2-1.oW56/g==
2016-01-11T13:00:15.589Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.oW56/g==
2016-01-11T13:00:15.589Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.oW56/g==
2016-01-11T13:00:15.589Z SendDataConnector.js: do connect now
2016-01-11 14:00:15.589 ThaliTest[1722:3665240] jxcore: connect Apple-IpadAir2-1.oW56/g==
2016-01-11 14:00:15.590 ThaliTest[1722:3665240] client session: connect
2016-01-11 14:00:15.590 ThaliTest[1722:3665240] client session: stateChange:0->1 Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:20.644 ThaliTest[1722:3666602] client session: connected
,2016-01-11 14:00:20.645 ThaliTest[1722:3666602] client session: stateChange:1->2 Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:20.852 ThaliTest[1722:3666611] client session: fireConnectCallback: Apple-IpadAir2-1.oW56/g==
2016-01-11 14:00:20.853 ThaliTest[1722:3666611] jxcore: connect: success
2016-01-11T13:00:20.853Z SendDataConnector.js: CLIENT connected to 496,65, error: null
2016-01-11T13:00:20.853Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 14:00:20.854 ThaliTest[1722:3665019] client: relay established
2016-01-11 14:00:20.854 ThaliTest[1722:3665019] client: new accepted socket: 0x193a7720
,2016-01-11T13:00:20.867Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T13:00:21.578Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T13:00:21.579Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-11T13:00:21.579Z SendDataConnector.js: CLIENT Stop now
2016-01-11T13:00:21.579Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-11 14:00:21.579 ThaliTest[1722:3665240] jxcore: disconnect
2016-01-11 14:00:21.580 ThaliTest[1722:3665240] client session: disconnectFromPeer: Apple-IpadAir2-1.oW56/g==
2016-01-11 14:00:21.580 ThaliTest[1722:3665240] client session: disconnect
2016-01-11 14:00:21.580 ThaliTest[1722:3665240] client session: stateChange:2->0 Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:21.589 ThaliTest[1722:3665240] jxcore: disconnect: success
2016-01-11T13:00:21.589Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.oW56/g==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one5-1.03CIBg==
2016-01-11T13:00:21.590Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.03CIBg==
2016-01-11T13:00:21.590Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.03CIBg==
2016-01-11T13:00:21.590Z SendDataConnector.js: do connect now
,2016-01-11 14:00:21.590 ThaliTest[1722:3665240] jxcore: connect Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:21.597 ThaliTest[1722:3665240] client session: connect
,2016-01-11 14:00:21.599 ThaliTest[1722:3665240] client session: stateChange:0->1 Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:25.368 ThaliTest[1722:3666602] client session: connected
2016-01-11 14:00:25.368 ThaliTest[1722:3666602] client session: stateChange:1->2 Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:25.429 ThaliTest[1722:3666599] client session: fireConnectCallback: Apple-Iphone5-1.03CIBg==
2016-01-11 14:00:25.429 ThaliTest[1722:3666599] jxcore: connect: success
,2016-01-11T13:00:25.430Z SendDataConnector.js: CLIENT connected to 49668, error: null
2016-01-11T13:00:25.431Z SendDataConnector.js: CLIENT starting client 
2016-01-11 14:00:25.432 ThaliTest[1722:3665019] client: relay established
2016-01-11 14:00:25.432 ThaliTest[1722:3665019] client: new accepted socket: 0x193a8dd0
,2016-01-11T13:00:25.444Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11 14:00:25.820 ThaliTest[1722:3665019] multipeer session: reset timer
2016-01-11 14:00:25.820 ThaliTest[1722:3665019] multipeer session: stop timer
2016-01-11 14:00:25.821 ThaliTest[1722:3665019] multipeer session: start timer: 0x1939aef0
2016-01-11 14:00:25.821 ThaliTest[1722:3665019] server session: connect
2016-01-11 14:00:25.821 ThaliTest[1722:3665019] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-11 14:00:25.824 ThaliTest[1722:3665019] server: accepting invitation Apple-IpadAir2-1
,2016-01-11T13:00:26.743Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T13:00:26.743Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-11T13:00:26.743Z SendDataConnector.js: CLIENT Stop now
2016-01-11T13:00:2,6.743Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-11 14:00:26.743 ThaliTest[1722:3665240] jxcore: disconnect
2016-01-11 14:00:26.744 ThaliTest[1722:3665240] client session: disconnectFromPeer: Apple-Iphone5-1.03CIBg==
2016-01-11 14:00:26.744, ThaliTest[1722:3665240] client session: disconnect
2016-01-11 14:00:26.744 ThaliTest[1722:3665240] client session: stateChange:2->0 Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:26.752 ThaliTest[1722:3665240] jxcore: disconnect: success
2016-01-11T13:00:26.753Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.03CIBg==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5s-1.yPThEg==
2016-01-11T13:00:26.753Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.yPThEg==
2016-01-11T13:00:26.753Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.yPThEg==
2016-01-11T13:00:26.753Z SendDataConnecto,r.js: do connect now
2016-01-11 14:00:26.754 ThaliTest[1722:3665240] jxcore: connect Apple-Iphone5s-1.yPThEg==
2016-01-11 14:00:26.754 ThaliTest[1722:3665240] client session: connect
2016-01-11 14:00:26.754 ThaliTest[1722:3665240] client session: stateChange:0->1 Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:27.331 ThaliTest[1722:3665019] multipeer session: reset timer
2016-01-11 14:00:27.332 ThaliTest[1722:3665019] multipeer session: stop timer
2016-01-11 14:00:27.332 ThaliTest[1722:3665019] multipeer session: start timer: 0x1939aef0
2016-,01-11 14:00:27.332 ThaliTest[1722:3665019] server session: connect
2016-01-11 14:00:27.332 ThaliTest[1722:3665019] server session: stateChange:0->1 Apple-Iphone5-1
2016-01-11 14:00:27.336 ThaliTest[1722:3665019] server: accepting invitation Apple-Iphone5-1
,2016-01-11 14:00:28.100 ThaliTest[1722:3665019] multipeer session: reset timer
2016-01-11 14:00:28.100 ThaliTest[1722:3665019] multipeer session: stop timer
2016-01-11 14:00:28.100 ThaliTest[1722:3665019] multipeer session: start timer: 0x1939aef0
2016-01-11 14:00:28.100 ThaliTest[1722:3665019] server session: connect
2016-01-11 14:00:28.100 ThaliTest[1722:3665019] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-11 14:00:28.103 ThaliTest[1722:3665019] server: accepting invitation Apple-Iphone5s-1
,2016-01-11 14:00:28.775 ThaliTest[1722:3666599] server session: connected
2016-01-11 14:00:28.775 ThaliTest[1722:3666599] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-11 14:00:28.778 ThaliTest[1722:3665019] server relay: connected (to port: 49660)
,2016-01-11T13:00:28.784Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T13:00:29.220Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-11T13:00:29.232Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2016-01-11T13:00:29.245Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-11T13:00:29.257Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-11T13:00:29.270Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-11T13:00:29.282Z SendDataTCPServer.js: TCP/IP server has received 86505 bytes of data
,2016-01-11T13:00:29.296Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 14:00:29.325 ThaliTest[1722:3666611] server session: not connected Apple-IpadAir2-1
,2016-01-11 14:00:29.561 ThaliTest[1722:3666611] client session: connected
2016-01-11 14:00:29.561 ThaliTest[1722:3666611] client session: stateChange:1->2 Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:29.618 ThaliTest[1722:3666611] client session: fireConnectCallback: Apple-Iphone5s-1.yPThEg==
2016-01-11 14:00:29.618 ThaliTest[1722:3666611] jxcore: connect: success
2016-01-11T13:00:29.618Z SendDataConnector.js: CLIENT connected to 49672, error: null
,2016-01-11T13:00:29.618Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 14:00:29.620 ThaliTest[1722:3665019] client: relay established
2016-01-11 14:00:29.620 ThaliTest[1722:3665019] client: new accepted socket: 0x193b4ab0
,2016-01-11T13:00:29.632Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11 14:00:30.046 ThaliTest[1722:3666611] server session: connected
2016-01-11 14:00:30.046 ThaliTest[1722:3666611] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-11 14:00:30.079 ThaliTest[1722:3665019] server relay: connected (to port: 49660)
,2016-01-11T13:00:30.194Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T13:00:30.342Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-11T13:00:30.356Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T13:00:30.418Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T13:00:30.418Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-11T13:00:30.418Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T13:00:30.418Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 14:00:30.419 ThaliTest[1722:3665240] jxcore: disconnect
,2016-01-11 14:00:30.420 ThaliTest[1722:3665240] client session: disconnectFromPeer: Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:30.420 ThaliTest[1722:3665240] client session: disconnect
,2016-01-11 14:00:30.420 ThaliTest[1722:3665240] client session: stateChange:2->0 Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:30.471 ThaliTest[1722:3666647] server session: connected
2016-01-11 14:00:30.471 ThaliTest[1722:3666647] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-11 14:00:30.481 ThaliTest[1722:3665240] jxcore: disconnect: success
,2016-01-11T13:00:30.482Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:30.483 ThaliTest[1722:3665019] server relay: connected (to port: 49660)
,---- round done--------
,startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-11T13:00:30.497Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T13:00:30.497Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11T13:00:30.511Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T13:00:31.079Z SendDataTCPServer.js: TCP/IP server has received 14235 bytes of data
,2016-01-11T13:00:31.139Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2016-01-11T13:00:31.152Z SendDataTCPServer.js: TCP/IP server has received 47085 bytes of data
,2016-01-11T13:00:31.199Z SendDataTCPServer.js: TCP/IP server has received 58035 bytes of data
,2016-01-11T13:00:31.212Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2016-01-11T13:00:31.261Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-11T13:00:31.273Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2016-01-11T13:00:31.311Z SendDataTCPServer.js: TCP/IP server has received 86505 bytes of data
,2016-01-11T13:00:31.394Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
2016-01-11T13:00:31.396Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2016-01-11T13:00:31.407Z SendDataTCPServer.js: TCP/IP server has received 86505 bytes of data
,2016-01-11T13:00:31.466Z SendDataTCPServer.js: TCP/IP server has received 97840 bytes of data
,2016-01-11T13:00:31.478Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 14:00:31.521 ThaliTest[1722:3666602] server session: not connected Apple-Iphone5s-1
,2016-01-11 14:00:31.604 ThaliTest[1722:3666602] server session: not connected Apple-Iphone5-1
,teardown
,testSendData stopped
2016-01-11 14:00:32.440 ThaliTest[1722:3665240] jxcore: stopBroadcasting
,2016-01-11 14:00:32.441 ThaliTest[1722:3665240] THEMultipeerSession stopping peer
,2016-01-11 14:00:32.441 ThaliTest[1722:3665240] multipeer session: stop timer
2016-01-11 14:00:32.441 ThaliTest[1722:3665240] server session: disconnect
2016-01-11 14:00:32.441 ThaliTest[1722:3665240] server session: stateChange:2->0 Apple-Iphone5s-1
20,16-01-11 14:00:32.444 ThaliTest[1722:3665240] server session: disconnect
2016-01-11 14:00:32.444 ThaliTest[1722:3665240] server session: stateChange:2->0 Apple-IpadAir2-1
2016-01-11 14:00:32.446 ThaliTest[1722:3665240] server session: disconnect
2016-01,-11 14:00:32.446 ThaliTest[1722:3665240] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-11 14:00:32.450 ThaliTest[1722:3665240] jxcore: stopBroadcasting: success
StopBroadcasting went ok
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
