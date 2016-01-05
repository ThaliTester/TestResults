#### Test 54968200254eab2_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E3CAA838-96E7-4150-8726-32C869887519/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/E3CAA838-96E7-4150-8726-32C869887519/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D9E9CD1D-D1E1-466A-A9D8-EB8B75D19226/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64582"
,(lldb)     command script import "/tmp/E3CAA838-96E7-4150-8726-32C869887519/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 01:36:33.631 ThaliTest[924:3019014] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D34B5243-2DF7-47F9-BE81-0DF7B1D40061/Library/Cookies/Cookies.binarycookies
,2016-01-05 01:36:33.749 ThaliTest[924:3019014] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 01:36:33.751 ThaliTest[924:3019014] Multi-tasking -> Device: YES, App: YES
,2016-01-05 01:36:33.755 ThaliTest[924:3019014] Unlimited access to network resources
,2016-01-05 01:36:33.766 ThaliTest[924:3019014] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 01:36:44.180 ThaliTest[924:3019014] Resetting plugins due to page load.
,2016-01-05 01:36:48.184 ThaliTest[924:3019014] Finished load of: file:///var/mobile/Containers/Bundle/Application/D9E9CD1D-D1E1-466A-A9D8-EB8B75D19226/ThaliTest.app/www/index.html
,2016-01-05 01:36:48.399 ThaliTest[924:3019014] JXcore Cordova plugin initializing
,2016-01-05 01:36:48.401 ThaliTest[924:3019214] JXcore instance initializing
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
,2016-01-05 01:36:50.881 ThaliTest[924:3019014] THREAD WARNING: ['JXcore'] took '158.349121' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 01:43:27.399 ThaliTest[924:3019214] jxcore: startBroadcasting
,2016-01-05 01:43:27.411 ThaliTest[924:3019214] server: starting Apple-Iphone5-1_PT4002.tre7Iw==
,2016-01-05 01:43:27.414 ThaliTest[924:3019214] multipeer session: start timer: 0x1a200000
2016-01-05 01:43:27.414 ThaliTest[924:3019214] THEMultipeerSession initialized peer Apple-Iphone5-1_PT4002
2016-01-05 01:43:27.416 ThaliTest[924:3019214] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-05 01:43:28.457 ThaliTest[924:3019014] client: found peer: Apple-Iphone6-1_PT4820.GNbylA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2016-01-05 01:43:30.130 ThaliTest[924:3019014] client: found peer: Apple-IpadAir2-1_PT3239.C7DKtQ==
,teardown
testFindPeers stopped
2016-01-05 01:43:31.074 ThaliTest[924:3019214] jxcore: stopBroadcasting
2016-01-05 01:43:31.074 ThaliTest[924:3019214] THEMultipeerSession stopping peer
2016-01-05 01:43:31.074 ThaliTest[924:3019214] multipeer session: st,op timer
,2016-01-05 01:43:31.075 ThaliTest[924:3019214] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 63306
,2016-01-05 01:43:31.332 ThaliTest[924:3019214] jxcore: startBroadcasting
,2016-01-05 01:43:31.334 ThaliTest[924:3019214] server: starting Apple-Iphone5-1_PT4002.r/utkA==
2016-01-05 01:43:31.335 ThaliTest[924:3019214] multipeer session: start timer: 0x1a3e4260
2016-01-05 01:43:31.335 ThaliTest[924:3019214] THEMultipeerSession i,nitialized peer Apple-Iphone5-1_PT4002
2016-01-05 01:43:31.335 ThaliTest[924:3019214] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-05T00:43:31.338Z SendDataTCPServer.js: TCP/IP server is bound to port: 63306
,2016-01-05 01:43:32.249 ThaliTest[924:3019014] client: found peer: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.251 ThaliTest[924:3019014] client: found peer: Apple-IpadAir2-1_PT3239.C7DKtQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphon,e6-1_PT4820.GNbylA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:43:32.253Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:32.254Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:43:32.254Z SendDataConnector.js: do connect now
2016-01-05 01:43:32.255 ThaliTest[924:3019214] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.255 ThaliTest[924:3019214] client session: connect
2016-01-05 01:43:32.256 ThaliTest[924:3019214] client session: stateChange:0->1 Apple-Iphone6-1_PT4820.GNbylA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.C7DKtQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 01:43:32.617 ThaliTest[924:3019014] client: lost peer: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.618 ThaliTest[924:3019014] client session: onPeerLost: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.618 ThaliTest[924:3019014] cl,ient session: onLinkFailure: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.618 ThaliTest[924:3019014] client session: disconnect
2016-01-05 01:43:32.618 ThaliTest[924:3019014] client session: stateChange:1->0 Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:32.619 ThaliTest[924:3019014] client session: fireConnectCallback: Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:32.620 ThaliTest[924:3019014] jxcore: connect: fail: Peer disconnected
2016-01-05 01:43:32.621 ThaliTest[924:3019014] client: lost peer: Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:32.622 ThaliTest[924:3019014] client session: onPe,erLost: Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05T00:43:32.624Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-05T00:43:32.624Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05 01:43:32.625 Thal,iTest[924:3019014] client: found peer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05T00:43:32.625Z SendDataConnector.js: tryAgain afer: 5000 ms.
2016-01-05 01:43:32.625 ThaliTest[924:3019014] client: found peer: Apple-Iphone6-1_PT4820.TWfskw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.C7DKtQ==","peerName":"(null)","peerAvailable":false}]
Found peer ,: (null), Available: false
2016-01-05 01:43:32.626 ThaliTest[924:3019014] client: found peer: Apple-Iphone5s-1_PT7515.viE/5Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.85RfWg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.TWfskw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7515.viE/5Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05T00:43:37.628Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:37.629Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:42.632 ThaliTest[924:3019214] jxcore: disconnect
2016-01-05 01:43:42.633 ThaliTest[924:3019214] jxcore: disconnect: fail
2016-01-05T00:43:42.633Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA=,=
2016-01-05T00:43:42.634Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
2016-01-05T00:43:42.634Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
201,6-01-05T00:43:42.634Z SendDataConnector.js: do connect now
,2016-01-05 01:43:42.635 ThaliTest[924:3019214] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:42.635 ThaliTest[924:3019214] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:42.636 ThaliTest[924:3019214] jxco,re: connect: fail: Peer unreachable
2016-01-05T00:43:42.636Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:43:42.636Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:43:42.637Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:43:47.642Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:47.642Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:52.652 ThaliTest[924:3019214] jxcore: disconnect
2016-01-05 01:43:52.652 ThaliTest[924:3019214] jxcore: disconnect: fail
2016-01-05T00:43:52.653Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA=,=
2016-01-05T00:43:52.653Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
2016-01-05T00:43:52.654Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:43:52.654Z SendDataConnector.js: do connect now
,2016-01-05 01:43:52.655 ThaliTest[924:3019214] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:52.655 ThaliTest[924:3019214] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:52.656 ThaliTest[924:3019214] jxco,re: connect: fail: Peer unreachable
,2016-01-05T00:43:52.656Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:43:52.656Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:43:52.656Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:43:57.662Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:57.662Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:01.336 ThaliTest[924:3019014] multipeer session: restart
,2016-01-05 01:44:01.370 ThaliTest[924:3019014] client: found peer: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:01.372 ThaliTest[924:3019014] client: found peer: Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:01.377 ThaliTest[924:3019014] client: found peer: Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:44:02.666 ThaliTest[924:3019214] jxcore: disconnect
2016-01-05 01:44:02.667 ThaliTest[924:3019214] jxcore: disconnect: fail
2016-01-05T00:44:02.667Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA=,=
2016-01-05T00:44:02.668Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
2016-01-05T00:44:02.668Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:44:02.669Z SendDataConnector.js: do connect now
,2016-01-05 01:44:02.670 ThaliTest[924:3019214] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:44:02.670 ThaliTest[924:3019214] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:02.671 ThaliTest[924:3019214] jxcore: connect: fail: Peer unreachable
,2016-01-05T00:44:02.671Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T00:44:02.672Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T00:44:02.672Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:44:07.680Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:44:07.681Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:12.688 ThaliTest[924:3019214] jxcore: disconnect
2016-01-05 01:44:12.688 ThaliTest[924:3019214] jxcore: disconnect: fail
2016-01-05T00:44:12.689Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA=,=
2016-01-05T00:44:12.689Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
2016-01-05T00:44:12.690Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
201,6-01-05T00:44:12.690Z SendDataConnector.js: do connect now
,2016-01-05 01:44:12.691 ThaliTest[924:3019214] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:44:12.691 ThaliTest[924:3019214] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:44:12.692 ThaliTest[924:3019214] jxco,re: connect: fail: Peer unreachable
,2016-01-05T00:44:12.692Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:44:12.692Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2016-01-05T00:44:12.694Z SendDataConnector.js: CLIENT Stop now
2016-01-05 01:44:12.694 ThaliTest[924:3019214] jxcore: disconnect
2016-01-05 01:44:12.694 ThaliTest[924:3019214] jxcore: disconnect: fail
2016-01-05T00:44:12.695Z SendDataCo,nnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA==
---- round done--------
,startWithNextDevice
device[2]: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05T00:44:12.696Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:12.696Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:12.697Z SendDataConnector.js: do connect now
,2016-01-05 01:44:12.698 ThaliTest[924:3019214] jxcore: connect Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:12.698 ThaliTest[924:3019214] client session: connect
2016-01-05 01:44:12.698 ThaliTest[924:3019214] client session: stateChange:0->1 Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:16.433 ThaliTest[924:3019973] client session: connected
,2016-01-05 01:44:16.433 ThaliTest[924:3019973] client session: stateChange:1->2 Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:16.438 ThaliTest[924:3019973] client session: fireConnectCallback: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:16.438 ThaliTest[924:3019973] jxcore: connect: success
2016-01-05T00:44:16.439Z SendDataConnector.js: CLIENT connected to 63311, error: null
2016-01-05T00:44:16.439Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 01:44:16.443 ThaliTest[924:3019014] client: relay established
2016-01-05 01:44:16.443 ThaliTest[924:3019014] client: new accepted socket: 0x1a3f4420
,2016-01-05T00:44:16.456Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T00:44:16.983Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T00:44:17.048Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-05T00:44:17.062Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-05T00:44:17.210Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T00:44:17.225Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T00:44:17.225Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T00:44:17.227Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T00:44:17.227Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:17.229 ThaliTest[924:3019214] jxcore: disconnect
2016-01-05 01:44:17.229 ThaliTest[924:3019214] client session: disconnectFromPeer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:17.229 ThaliTest[924:3019214] client session: disconnect
2016-01-05 01:44:17.229 ThaliTest[924:3019214] client session: stateChange:2->0 Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:17.237 ThaliTest[924:3019214] jxcore: disconnect: success
2016-01-05T00:44:17.239Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.85RfWg==
---- round done--------
startWithNextDevice
device[3]: App,le-Iphone6-1_PT4820.TWfskw==
2016-01-05T00:44:17.240Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05T00:44:17.241Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05T00:44,:17.241Z SendDataConnector.js: do connect now
2016-01-05 01:44:17.241 ThaliTest[924:3019214] jxcore: connect Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:17.241 ThaliTest[924:3019214] client session: connect
,2016-01-05 01:44:17.248 ThaliTest[924:3019214] client session: stateChange:0->1 Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:20.497 ThaliTest[924:3019973] client session: connected
2016-01-05 01:44:20.497 ThaliTest[924:3019973] client session: stateChange:1->2 Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:20.941 ThaliTest[924:3019989] client session: fireConnectCallback: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:20.941 ThaliTest[924:3019989] jxcore: connect: success
2016-01-05T00:44:20.942Z SendDataConnector.js: CLIENT connected to 63314, error: null
,2016-01-05T00:44:20.942Z SendDataConnector.js: CLIENT starting client 
2016-01-05 01:44:20.945 ThaliTest[924:3019014] client: relay established
2016-01-05 01:44:20.945 ThaliTest[924:3019014] client: new accepted socket: 0x1a44c040
,2016-01-05T00:44:20.957Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05 01:44:21.433 ThaliTest[924:3019014] multipeer session: reset timer
2016-01-05 01:44:21.433 ThaliTest[924:3019014] multipeer session: stop timer
2016-01-05 01:44:21.434 ThaliTest[924:3019014] multipeer session: start timer: 0x1a3e4260
2016-01-,05 01:44:21.434 ThaliTest[924:3019014] server session: connect
2016-01-05 01:44:21.434 ThaliTest[924:3019014] server session: stateChange:0->1 Apple-Iphone5s-1_PT7515
2016-01-05 01:44:21.441 ThaliTest[924:3019014] server: accepting invitation Apple-Iphone5s-1_PT7515
,2016-01-05T00:44:21.545Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T00:44:21.613Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T00:44:21.614Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-05T00:44:21.614Z SendDataConnector.js: CLIENT Stop now
2016-01-05T00:44:2,1.614Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-05 01:44:21.616 ThaliTest[924:3019214] jxcore: disconnect
2016-01-05 01:44:21.617 ThaliTest[924:3019214] client session: disconnectFromPeer: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:21.617 ThaliTest[924:3019214] client session: disconnect
2016-01-05 01:44:21.617 ThaliTest[924:3019214] client session: stateChange:2->0 Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:21.634 ThaliTest[924:3019214] jxcore: disconnect: success
2016-01-05T00:44:21.638Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.TWfskw==
---- round done--------
startWithNextDevice
device[4]: Appl,e-Iphone5s-1_PT7515.viE/5Q==
2016-01-05T00:44:21.639Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05T00:44:21.639Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05T00:,44:21.639Z SendDataConnector.js: do connect now
2016-01-05 01:44:21.640 ThaliTest[924:3019214] jxcore: connect Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:44:21.646 ThaliTest[924:3019214] client session: connect
2016-01-05 01:44:21.648 ThaliTest[924:3019214] client session: stateChange:0->1 Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:44:22.062 ThaliTest[924:3019014] multipeer session: reset timer
2016-01-05 01:44:22.063 ThaliTest[924:3019014] multipeer session: stop timer
2016-01-05 01:44:22.063 ThaliTest[924:3019014] multipeer session: start timer: 0x1a3e4260
2016-01-05 01:44:22.063 ThaliTest[924:3019014] server session: connect
2016-01-05 01:44:22.063 ThaliTest[924:3019014] server session: stateChange:0->1 Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:22.070 ThaliTest[924:3019014] server: accepting invitation Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:24.177 ThaliTest[924:3019973] server session: connected
2016-01-05 01:44:24.177 ThaliTest[924:3019973] server session: stateChange:1->2 Apple-Iphone5s-1_PT7515
,2016-01-05 01:44:24.182 ThaliTest[924:3019014] server relay: connected (to port: 63306)
,2016-01-05T00:44:24.194Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T00:44:24.627Z SendDataTCPServer.js: TCP/IP server has received 22528 bytes of data
,2016-01-05T00:44:24.653Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
2016-01-05T00:44:24.667Z SendDataTCPServer.js: TCP/IP server has received 76082 bytes of data
,2016-01-05T00:44:24.684Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:44:24.699 ThaliTest[924:3019975] client session: connected
,2016-01-05 01:44:24.699 ThaliTest[924:3019975] client session: stateChange:1->2 Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:44:24.708 ThaliTest[924:3019975] client session: fireConnectCallback: Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:44:24.709 ThaliTest[924:3019975] jxcore: connect: success
,2016-01-05T00:44:24.710Z SendDataConnector.js: CLIENT connected to 63318, error: null
,2016-01-05T00:44:24.711Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 01:44:24.715 ThaliTest[924:3019014] client: relay established
,2016-01-05 01:44:24.715 ThaliTest[924:3019014] client: new accepted socket: 0x1a332840
,2016-01-05T00:44:24.730Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05 01:44:24.758 ThaliTest[924:3019975] server session: not connected Apple-Iphone5s-1_PT7515
,2016-01-05T00:44:25.300Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-05T00:44:25.317Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-05T00:44:25.335Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-05T00:44:25.351Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-05T00:44:25.363Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T00:44:25.379Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T00:44:25.380Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-05T00:44:25.381Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T00:44:25.381Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:25.382 ThaliTest[924:3019214] jxcore: disconnect
,2016-01-05 01:44:25.382 ThaliTest[924:3019214] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:44:25.384 ThaliTest[924:3019214] client session: disconnect
,2016-01-05 01:44:25.384 ThaliTest[924:3019214] client session: stateChange:2->0 Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:44:25.465 ThaliTest[924:3019214] jxcore: disconnect: success
2016-01-05T00:44:25.466Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7515.viE/5Q==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2016-01-05T00:44:25.472Z SendDataConnector.js: CLIENT Stop now
2016-01-05T00:44:25.472Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:25.478 ThaliTest[924:3019975] server session: connected
,2016-01-05 01:44:25.478 ThaliTest[924:3019975] server session: stateChange:1->2 Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:25.482 ThaliTest[924:3019014] server relay: connected (to port: 63306)
,2016-01-05T00:44:25.489Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T00:44:25.797Z SendDataTCPServer.js: TCP/IP server has received 25712 bytes of data
,2016-01-05T00:44:25.815Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2016-01-05T00:44:25.829Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-05T00:44:25.846Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:44:25.894 ThaliTest[924:3019990] server session: not connected Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:52.064 ThaliTest[924:3019014] multipeer session: restart
,2016-01-05 01:44:52.099 ThaliTest[924:3019014] client: found peer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:52.100 ThaliTest[924:3019014] client: found peer: Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:44:52.100 ThaliTest[924:3019014] client: found peer: Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:45:01.896 ThaliTest[924:3019014] multipeer session: reset timer
2016-01-05 01:45:01.897 ThaliTest[924:3019014] multipeer session: stop timer
2016-01-05 01:45:01.897 ThaliTest[924:3019014] multipeer session: start timer: 0x1a3e4260
2016-01-,05 01:45:01.897 ThaliTest[924:3019014] server session: connect
2016-01-05 01:45:01.897 ThaliTest[924:3019014] server session: stateChange:0->1 Apple-Iphone6-1_PT4820
,2016-01-05 01:45:01.903 ThaliTest[924:3019014] server: accepting invitation Apple-Iphone6-1_PT4820
,appEnteredForeground wasn't registered
,2016-01-05 01:45:07.648 ThaliTest[924:3020084] server session: connected
2016-01-05 01:45:07.648 ThaliTest[924:3020084] server session: stateChange:1->2 Apple-Iphone6-1_PT4820
,2016-01-05 01:45:07.652 ThaliTest[924:3019014] server relay: connected (to port: 63306)
,2016-01-05T00:45:07.664Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T00:45:08.596Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2016-01-05T00:45:08.616Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2016-01-05T00:45:08.629Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-05T00:45:08.641Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:45:08.682 ThaliTest[924:3020145] server session: not connected Apple-Iphone6-1_PT4820
,appEnteringBackground wasn't registered
,2016-01-05 01:45:11.907 ThaliTest[924:3019014] client: lost peer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:45:11.908 ThaliTest[924:3019014] client session: onPeerLost: Apple-IpadAir2-1_PT3239.85RfWg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.85RfWg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2016-01-05 01:45:13.346 ThaliTest[924:3019014] client: lost peer: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:45:13.348 ThaliTest[924:3019014] client session: onPeerLost: Apple-Iphone6-1_PT4820.TWfskw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.TWfskw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2016-01-05 01:45:14.309 ThaliTest[924:3019014] client: lost peer: Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:45:14.310 ThaliTest[924:3019014] client session: onPeerLost: Apple-Iphone5s-1_PT7515.viE/5Q==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5s-1_PT7515.viE/5Q==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,teardown
,testSendData stopped
,2016-01-05 01:45:18.554 ThaliTest[924:3019214] jxcore: stopBroadcasting
2016-01-05 01:45:18.554 ThaliTest[924:3019214] THEMultipeerSession stopping peer
2016-01-05 01:45:18.555 ThaliTest[924:3019214] multipeer session: stop timer
2016-01-05 01:45:18.555, ThaliTest[924:3019214] server session: disconnect
2016-01-05 01:45:18.555 ThaliTest[924:3019214] server session: stateChange:2->0 Apple-Iphone5s-1_PT7515
,2016-01-05 01:45:18.562 ThaliTest[924:3019214] server session: disconnect
2016-01-05 01:45:18.562 ThaliTest[924:3019214] server session: stateChange:2->0 Apple-IpadAir2-1_PT3239
2016-01-05 01:45:18.564 ThaliTest[924:3019214] server session: disconnect
2016-01-05 01:45:18.564 ThaliTest[924:3019214] server session: stateChange:2->0 Apple-Iphone6-1_PT4820
,2016-01-05 01:45:18.577 ThaliTest[924:3019214] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-05T00:45:18.615Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:18.620Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:18.623Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:18.624Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
