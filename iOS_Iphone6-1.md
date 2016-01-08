#### Test 5546736337bcedb_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E93D8852-C472-4326-A6EF-58A2F52DA130/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E93D8852-C472-4326-A6EF-58A2F52DA130/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F42732BE-6D89-46B9-965B-3D92321934DC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50280"
,(lldb)     command script import "/tmp/E93D8852-C472-4326-A6EF-58A2F52DA130/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 15:48:22.110 ThaliTest[1512:3242369] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A294CE31-2653-4C68-8161-54E34FEB3226/Library/Cookies/Cookies.binarycookies
,2016-01-08 15:48:22.519 ThaliTest[1512:3242369] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 15:48:22.521 ThaliTest[1512:3242369] Multi-tasking -> Device: YES, App: YES
,2016-01-08 15:48:22.531 ThaliTest[1512:3242369] Unlimited access to network resources
,2016-01-08 15:48:22.545 ThaliTest[1512:3242369] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 15:48:31.612 ThaliTest[1512:3242369] Resetting plugins due to page load.
,2016-01-08 15:48:35.359 ThaliTest[1512:3242369] Finished load of: file:///var/mobile/Containers/Bundle/Application/F42732BE-6D89-46B9-965B-3D92321934DC/ThaliTest.app/www/index.html
,2016-01-08 15:48:35.540 ThaliTest[1512:3242369] JXcore Cordova plugin initializing
2016-01-08 15:48:35.541 ThaliTest[1512:3242618] JXcore instance initializing
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
,2016-01-08 15:48:36.738 ThaliTest[1512:3242369] THREAD WARNING: ['JXcore'] took '74.838867' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 15:53:15.036 ThaliTest[1512:3242618] jxcore: startBroadcasting
,2016-01-08 15:53:15.055 ThaliTest[1512:3242618] server: starting Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:15.060 ThaliTest[1512:3242618] multipeer session: start timer: 0x17bf6510
,2016-01-08 15:53:15.068 ThaliTest[1512:3242618] THEMultipeerSession initialized peer Apple-Iphone6-1
,2016-01-08 15:53:15.070 ThaliTest[1512:3242618] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-08 15:53:16.245 ThaliTest[1512:3242369] client: found peer: Apple-IpadAir2-1.xmg6Nw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xmg6Nw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.xmg6Nw==, peerAv,ailable: true
,weAreDoneNow
done, now sending data to server
,2016-01-08 15:53:18.252 ThaliTest[1512:3242369] client: found peer: Apple-Iphone5s-1.MP5wlA==
,2016-01-08 15:53:19.308 ThaliTest[1512:3242369] client: found peer: Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:19.457 ThaliTest[1512:3242369] multipeer session: reset timer
2016-01-08 15:53:19.457 ThaliTest[1512:3242369] multipeer session: stop timer
2016-01-08 15:53:19.457 ThaliTest[1512:3242369] multipeer session: start timer: 0x17bf6510
,2016-01-08 15:53:19.458 ThaliTest[1512:3242369] server session: connect
,2016-01-08 15:53:19.459 ThaliTest[1512:3242369] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 15:53:19.468 ThaliTest[1512:3242369] server: accepting invitation Apple-Iphone5s-1
,teardown
,testFindPeers stopped
,2016-01-08 15:53:19.657 ThaliTest[1512:3242618] jxcore: stopBroadcasting
2016-01-08 15:53:19.657 ThaliTest[1512:3242618] THEMultipeerSession stopping peer
2016-01-08 15:53:19.658 ThaliTest[1512:3242618] multipeer session: stop timer
2016-01-08 15:53:19.,658 ThaliTest[1512:3242618] server session: disconnect
2016-01-08 15:53:19.658 ThaliTest[1512:3242618] server session: stateChange:1->0 Apple-Iphone5s-1
2016-01-08 15:53:19.659 ThaliTest[1512:3242618] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 64525
,2016-01-08 15:53:19.680 ThaliTest[1512:3242618] jxcore: startBroadcasting
,2016-01-08 15:53:19.686 ThaliTest[1512:3242618] server: starting Apple-Iphone6-1.bICwVA==
2016-01-08 15:53:19.686 ThaliTest[1512:3242618] multipeer session: start timer: 0x17b45160
2016-01-08 15:53:19.687 ThaliTest[1512:3242618] THEMultipeerSession initi,alized peer Apple-Iphone6-1
2016-01-08 15:53:19.687 ThaliTest[1512:3242618] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2016-01-08T14:53:19.690Z SendDataTCPServer.js: TCP/IP server is bound to port: 64525
,2016-01-08 15:53:20.321 ThaliTest[1512:3242369] client: found peer: Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:20.323 ThaliTest[1512:3242369] client: found peer: Apple-Iphone5s-1.MP5wlA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.j1bF8Q=,=","peerName":"(null)","peerAvailable":true}]
2016-01-08 15:53:20.324 ThaliTest[1512:3242369] client: found peer: Apple-IpadAir2-1.xmg6Nw==
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1.j1bF8Q==
2016-01-08T14:53:2,0.326Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.j1bF8Q==
2016-01-08T14:53:20.326Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.j1bF8Q==
2016-01-08T14:53:20.327Z SendDataConnector.js: do connect now
2016-01-08 15:5,3:20.328 ThaliTest[1512:3242618] jxcore: connect Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:20.328 ThaliTest[1512:3242618] client session: connect
2016-01-08 15:53:20.329 ThaliTest[1512:3242618] client session: stateChange:0->1 Apple-Iphone6-1.j1bF8Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.MP5wlA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xmg6Nw==","peerName":"(null)","peerAvailab,le":true}]
Found peer : (null), Available: true
,2016-01-08 15:53:20.786 ThaliTest[1512:3242369] client: lost peer: Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:20.786 ThaliTest[1512:3242369] client session: onPeerLost: Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:20.787 ThaliTest[1512:3242369] client sessio,n: onLinkFailure: Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:20.787 ThaliTest[1512:3242369] client session: disconnect
2016-01-08 15:53:20.787 ThaliTest[1512:3242369] client session: stateChange:1->0 Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:20.788 ThaliTest[1512:3242369] client session: fireConnectCallback: Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:20.789 ThaliTest[1512:3242369] jxcore: connect: fail: Peer disconnected
2016-01-08T14:53:20.791Z SendDataConnector.js: CLIENT c,onnected to 0, error: Peer disconnected
2016-01-08T14:53:20.791Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T14:53:20.792Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iph,one6-1.j1bF8Q==","peerName":"(null)","peerAvailable":false}]
,2016-01-08 15:53:20.950 ThaliTest[1512:3242369] client: found peer: Apple-IpadAir2-1.+bX+WA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.+bX+WA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2016-01-,08 15:53:20.952 ThaliTest[1512:3242369] client: lost peer: Apple-Iphone5s-1.MP5wlA==
2016-01-08 15:53:20.952 ThaliTest[1512:3242369] client session: onPeerLost: Apple-Iphone5s-1.MP5wlA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.MP5wlA,==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 15:53:21.288 ThaliTest[1512:3242369] client: lost peer: Apple-IpadAir2-1.xmg6Nw==
2016-01-08 15:53:21.288 ThaliTest[1512:3242369] client session: onPeerLost: Apple-IpadAir2-1.xmg6Nw==
2016-01-08 15:53:21.289 ThaliTest[1512:3242369] client: fou,nd peer: Apple-Iphone5-1.ziR9IQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xmg6Nw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.ziR9IQ,==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 15:53:21.460 ThaliTest[1512:3242369] client: found peer: Apple-Iphone5s-1.zHt1vQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.zHt1vQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08T14:53:25.803Z SendDataConnector.js: re-try now : Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:25.804Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:30.807 ThaliTest[1512:3242618] jxcore: disconnect
2016-01-08 15:53:30.808 ThaliTest[1512:3242618] jxcore: disconnect: fail
2016-01-08T14:53:30.809Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.j1bF8Q==
20,16-01-08T14:53:30.809Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.j1bF8Q== with availability status: true
2016-01-08T14:53:30.809Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:30.810Z SendDataConnector.js: do connect now
,2016-01-08 15:53:30.811 ThaliTest[1512:3242618] jxcore: connect Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:30.812 ThaliTest[1512:3242618] client: connect: unreachable Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:30.812 ThaliTest[1512:3242618] jxcore: connect: fail: Peer unreachable
,2016-01-08T14:53:30.813Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T14:53:30.813Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T14:53:30.814Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:35.821Z SendDataConnector.js: re-try now : Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:35.822Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:40.831 ThaliTest[1512:3242618] jxcore: disconnect
2016-01-08 15:53:40.832 ThaliTest[1512:3242618] jxcore: disconnect: fail
2016-01-08T14:53:40.832Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.j1bF8Q==
20,16-01-08T14:53:40.832Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.j1bF8Q== with availability status: true
2016-01-08T14:53:40.833Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.j1bF8Q==
2016-01-08T14:53:40.833Z SendDataConnector.js: do connect now
,2016-01-08 15:53:40.834 ThaliTest[1512:3242618] jxcore: connect Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:40.835 ThaliTest[1512:3242618] client: connect: unreachable Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:40.835 ThaliTest[1512:3242618] jxcore: connect: fail: Peer unreachable
2016-01-08T14:53:40.836Z SendDataConnector.js: CLIENT connected ,to 0, error: Peer unreachable
2016-01-08T14:53:40.836Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T14:53:40.836Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:45.846Z SendDataConnector.js: re-try now : Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:45.846Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:49.704 ThaliTest[1512:3242369] multipeer session: restart
,2016-01-08 15:53:49.746 ThaliTest[1512:3242369] client: found peer: Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:53:49.746 ThaliTest[1512:3242369] client: found peer: Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:53:49.748 ThaliTest[1512:3242369] client: found peer: Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:53:50.856 ThaliTest[1512:3242618] jxcore: disconnect
,2016-01-08 15:53:50.856 ThaliTest[1512:3242618] jxcore: disconnect: fail
2016-01-08T14:53:50.857Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.j1bF8Q==
2016-01-08T14:53:50.857Z SendDataConnector.js: Connect (retry count 3), to peer Apple-Iphone6-1.j1bF8Q== with availability status: true
2016-01-08T14:53:50.857Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:50.858Z SendDataConnector.js: do connect now
,2016-01-08 15:53:50.859 ThaliTest[1512:3242618] jxcore: connect Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:50.860 ThaliTest[1512:3242618] client: connect: unreachable Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:50.860 ThaliTest[1512:3242618] jxcore: connect,: fail: Peer unreachable
2016-01-08T14:53:50.862Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T14:53:50.862Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T14:53:50.862Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:55.869Z SendDataConnector.js: re-try now : Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:55.869Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:54:00.880 ThaliTest[1512:3242618] jxcore: disconnect
2016-01-08 15:54:00.881 ThaliTest[1512:3242618] jxcore: disconnect: fail
2016-01-08T14:54:00.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.j1bF8Q==
20,16-01-08T14:54:00.882Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.j1bF8Q== with availability status: true
2016-01-08T14:54:00.882Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.j1bF8Q==
2016-01-08T14:54:00.88,2Z SendDataConnector.js: do connect now
,2016-01-08 15:54:00.883 ThaliTest[1512:3242618] jxcore: connect Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:54:00.884 ThaliTest[1512:3242618] client: connect: unreachable Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:54:00.885 ThaliTest[1512:3242618] jxcore: connect: fail: Peer unreachable
2016-01-08T14:54:00.885Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T14:54:00.886Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-08T14:54:00.888Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 15:54:00.889 ThaliTest[1512:3242618] jxcore: disconnect
2016-01-08 15:54:00.890 ThaliTest[1512:3242618] jxcore: disconnect: fail
2016-01-08T14:54:00.890Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.j1bF8Q==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1.+bX+WA==
,2016-01-08T14:54:00.894Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.+bX+WA==
,2016-01-08T14:54:00.895Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.+bX+WA==
,2016-01-08T14:54:00.895Z SendDataConnector.js: do connect now
,2016-01-08 15:54:00.897 ThaliTest[1512:3242618] jxcore: connect Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:54:00.897 ThaliTest[1512:3242618] client session: connect
2016-01-08 15:54:00.897 ThaliTest[1512:3242618] client session: stateChange:0->1 Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:54:07.118 ThaliTest[1512:3243527] client session: connected
,2016-01-08 15:54:07.119 ThaliTest[1512:3243527] client session: stateChange:1->2 Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:54:07.127 ThaliTest[1512:3243527] client session: fireConnectCallback: Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:54:07.128 ThaliTest[1512:3243527] jxcore: connect: success
2016-01-08T14:54:07.129Z SendDataConnector.js: CLIENT connected to 64532, error: null
2016-01-08T14:54:07.130Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 15:54:07.136 ThaliTest[1512:3242369] client: relay established
2016-01-08 15:54:07.137 ThaliTest[1512:3242369] client: new accepted socket: 0x17c8d1f0
,2016-01-08T14:54:07.150Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T14:54:07.790Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T14:54:07.803Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T14:54:07.804Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T14:54:07.804Z SendDataConnector.js: CLIENT Stop now
2016-01-08T14:54:07.804Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:07.805 ThaliTest[1512:3242618] jxcore: disconnect
2016-01-08 15:54:07.805 ThaliTest[1512:3242618] client session: disconnectFromPeer: Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:54:07.805 ThaliTest[1512:3242618] client session: disconnect
2016-01-08 15:54:07.805 ThaliTest[1512:3242618] client session: stateChange:2->0 Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:54:07.809 ThaliTest[1512:3242618] jxcore: disconnect: success
2016-01-08T14:54:07.809Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.+bX+WA==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5-1.ziR9IQ==
2016-01-08T14:54:07.810Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.ziR9IQ==
2016-01-08T14:54:07.810Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.ziR9IQ==
2016-01-08T14:54:07.810Z SendDataConnector.,js: do connect now
2016-01-08 15:54:07.810 ThaliTest[1512:3242618] jxcore: connect Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:54:07.810 ThaliTest[1512:3242618] client session: connect
2016-01-08 15:54:07.810 ThaliTest[1512:3242618] client session: stateChange:0->1 Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:09.496 ThaliTest[1512:3242369] multipeer session: reset timer
2016-01-08 15:54:09.497 ThaliTest[1512:3242369] multipeer session: stop timer
2016-01-08 15:54:09.497 ThaliTest[1512:3242369] multipeer session: start timer: 0x17b45160
2016-,01-08 15:54:09.497 ThaliTest[1512:3242369] server session: connect
2016-01-08 15:54:09.498 ThaliTest[1512:3242369] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 15:54:09.508 ThaliTest[1512:3242369] server: accepting invitation Apple-IpadAir2-1
,2016-01-08 15:54:10.851 ThaliTest[1512:3243515] client session: connected
,2016-01-08 15:54:10.851 ThaliTest[1512:3243515] client session: stateChange:1->2 Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:10.867 ThaliTest[1512:3243453] client session: fireConnectCallback: Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:54:10.868 ThaliTest[1512:3243453] jxcore: connect: success
2016-01-08T14:54:10.869Z SendDataConnector.js: CLIENT connected to 64535, error: null
2016-01-08T14:54:10.870Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 15:54:10.874 ThaliTest[1512:3242369] client: relay established
2016-01-08 15:54:10.874 ThaliTest[1512:3242369] client: new accepted socket: 0x17c942d0
,2016-01-08T14:54:10.885Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T14:54:11.515Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T14:54:11.526Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T14:54:11.575Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T14:54:11.588Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T14:54:11.588Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-08T14:54:11.589Z SendDataConnector.js: CLIENT Stop now
2016-01-08T14:54:11.589Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-08 15:54:11.589 ThaliTest[1512:3242618] jxcore: disconnect
2016-01-08 15:54:11.589 ThaliTest[1512:3242618] client session: disconnectFromPeer: Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:54:11.590 ThaliTest[1512:3242618] client session: disconnect
2016-01-08 15:54:11.590 ThaliTest[1512:3242618] client session: stateChange:2->0 Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:11.595 ThaliTest[1512:3242618] jxcore: disconnect: success
2016-01-08T14:54:11.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.ziR9IQ==
---- round done--------
startWithNextDevice
device[4]: Apple-Ipho,hange:0->1 Apple-Iphone5s-1.zHt1vQ==
ne5s-1.zHt1vQ==
2016-01-08T14:54:11.596Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.zHt1vQ==
2016-01-08T14:54:11.596Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.zHt1vQ==
2016-01-08T14:54:11.596Z SendDataConnector.js: do connect now
2016-01-08 15:54:11.596 ThaliTest[1512:3242618] jxcore: connect Apple-Iphone5s-1.zHt1vQ==
2016-01-08 15:54:11.596 ThaliTest[1512:3242618] client session: connect
2016-01-08 15:54:11.597 ThaliTest[1512:3242618] client session: stateC,2016-01-08 15:54:12.373 ThaliTest[1512:3242369] multipeer session: reset timer
2016-01-08 15:54:12.374 ThaliTest[1512:3242369] multipeer session: stop timer
2016-01-08 15:54:12.374 ThaliTest[1512:3242369] multipeer session: start timer: 0x17b45160
,2016-01-08 15:54:12.375 ThaliTest[1512:3242369] server session: connect
2016-01-08 15:54:12.376 ThaliTest[1512:3242369] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 15:54:12.385 ThaliTest[1512:3242369] server: accepting invitation Apple-Iphone5s-1
,2016-01-08 15:54:12.774 ThaliTest[1512:3243453] server session: connected
2016-01-08 15:54:12.775 ThaliTest[1512:3243453] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08T14:54:12.839Z SendDataTCPServer.js: TCP/IP server connected
2016-01-08 15:54:12.837 ThaliTest[1512:3242369] server relay: connected (to port: 64525)
,2016-01-08T14:54:13.249Z SendDataTCPServer.js: TCP/IP server has received 1095 bytes of data
,2016-01-08T14:54:13.290Z SendDataTCPServer.js: TCP/IP server has received 9855 bytes of data
,2016-01-08T14:54:13.304Z SendDataTCPServer.js: TCP/IP server has received 14235 bytes of data
,2016-01-08T14:54:13.342Z SendDataTCPServer.js: TCP/IP server has received 21403 bytes of data
,2016-01-08T14:54:13.360Z SendDataTCPServer.js: TCP/IP server has received 86939 bytes of data
,2016-01-08T14:54:13.364Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:13.437 ThaliTest[1512:3243572] server session: not connected Apple-IpadAir2-1
,2016-01-08 15:54:14.025 ThaliTest[1512:3242369] multipeer session: reset timer
2016-01-08 15:54:14.026 ThaliTest[1512:3242369] multipeer session: stop timer
2016-01-08 15:54:14.026 ThaliTest[1512:3242369] multipeer session: start timer: 0x17b45160
,2016-01-08 15:54:14.026 ThaliTest[1512:3242369] server session: connect
,2016-01-08 15:54:14.028 ThaliTest[1512:3242369] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 15:54:14.041 ThaliTest[1512:3242369] server: accepting invitation Apple-Iphone5-1
,2016-01-08 15:54:14.955 ThaliTest[1512:3243572] server session: connected
,2016-01-08 15:54:14.955 ThaliTest[1512:3243572] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08 15:54:14.976 ThaliTest[1512:3242369] server relay: connected (to port: 64525)
,2016-01-08T14:54:14.989Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 15:54:15.298 ThaliTest[1512:3243560] client session: connected
2016-01-08 15:54:15.299 ThaliTest[1512:3243560] client session: stateChange:1->2 Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:54:15.325 ThaliTest[1512:3243572] client session: fireConnectCallback: Apple-Iphone5s-1.zHt1vQ==
2016-01-08 15:54:15.325 ThaliTest[1512:3243572] jxcore: connect: success
2016-01-08T14:54:15.326Z SendDataConnector.js: CLIENT connected to 64540, error: null
2016-01-08T14:54:15.327Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 15:54:15.331 ThaliTest[1512:3242369] client: relay established
,2016-01-08 15:54:15.332 ThaliTest[1512:3242369] client: new accepted socket: 0x17c9bcd0
,2016-01-08T14:54:15.343Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T14:54:15.856Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
,2016-01-08T14:54:15.866Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08T14:54:15.975Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08T14:54:16.038Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T14:54:16.051Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08 15:54:16.100 ThaliTest[1512:3243572] server session: not connected Apple-Iphone5s-1
,2016-01-08T14:54:16.162Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T14:54:16.162Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T14:54:16.162Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T14:54:16.163Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:16.163 ThaliTest[1512:3242618] jxcore: disconnect
2016-01-08 15:54:16.163 ThaliTest[1512:3242618] client session: disconnectFromPeer: Apple-Iphone5s-1.zHt1vQ==
2016-01-08 15:54:16.163 ThaliTest[1512:3242618] client session: disconnect
2016-01-08 15:54:16.163 ThaliTest[1512:3242618] client session: stateChange:2->0 Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:54:16.168 ThaliTest[1512:3242618] jxcore: disconnect: success
2016-01-08T14:54:16.169Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.zHt1vQ==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-08T14:54:16.183Z SendDataConnector.js: CLIENT Stop now
2016-01-08T14:54:16.183Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:16.498 ThaliTest[1512:3243527] server session: connected
2016-01-08 15:54:16.500 ThaliTest[1512:3243527] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08 15:54:16.571 ThaliTest[1512:3242369] server relay: connected (to port: 64525)
,2016-01-08T14:54:16.579Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T14:54:17.617Z SendDataTCPServer.js: TCP/IP server has received 12045 bytes of data
,2016-01-08T14:54:17.632Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2016-01-08T14:54:17.647Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2016-01-08T14:54:17.676Z SendDataTCPServer.js: TCP/IP server has received 29565 bytes of data
,2016-01-08T14:54:17.693Z SendDataTCPServer.js: TCP/IP server has received 40373 bytes of data
,2016-01-08T14:54:17.709Z SendDataTCPServer.js: TCP/IP server has received 58035 bytes of data
,2016-01-08T14:54:17.722Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-08T14:54:17.735Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-08T14:54:17.750Z SendDataTCPServer.js: TCP/IP server has received 84315 bytes of data
,2016-01-08T14:54:17.815Z SendDataTCPServer.js: TCP/IP server has received 96674 bytes of data
,2016-01-08T14:54:17.831Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:18.141 ThaliTest[1512:3243527] server session: not connected Apple-Iphone5-1
,teardown
,testSendData stopped
,2016-01-08 15:54:18.857 ThaliTest[1512:3242618] jxcore: stopBroadcasting
2016-01-08 15:54:18.859 ThaliTest[1512:3242618] THEMultipeerSession stopping peer
2016-01-08 15:54:18.859 ThaliTest[1512:3242618] multipeer session: stop timer
2016-01-08 15:54:18.,860 ThaliTest[1512:3242618] server session: disconnect
2016-01-08 15:54:18.860 ThaliTest[1512:3242618] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-08 15:54:18.868 ThaliTest[1512:3242618] server session: disconnect
2016-01-08 15:54:18.868 ThaliTest[1512:3242618] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-08 15:54:18.877 ThaliTest[1512:3242618] server session: disconnect
2016-01-08 15:54:18.877 ThaliTest[1512:3242618] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-08 15:54:18.891 ThaliTest[1512:3242618] jxcore: stopBroadcasting: success
StopBroadcasting went ok
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
