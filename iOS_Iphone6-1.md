#### Test 54968200254eab2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7F3EA563-5B7C-47A7-9FB1-941D59A6DCA4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7F3EA563-5B7C-47A7-9FB1-941D59A6DCA4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7C5DAAB3-57EE-4D4E-8D20-8C2F5E7CEAB5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64607"
,(lldb)     command script import "/tmp/7F3EA563-5B7C-47A7-9FB1-941D59A6DCA4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 01:37:55.360 ThaliTest[1267:2726449] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2E33B0A0-B41A-4903-8ACD-48681C4C43D8/Library/Cookies/Cookies.binarycookies
,2016-01-05 01:37:55.678 ThaliTest[1267:2726449] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 01:37:55.679 ThaliTest[1267:2726449] Multi-tasking -> Device: YES, App: YES
,2016-01-05 01:37:55.688 ThaliTest[1267:2726449] Unlimited access to network resources
,2016-01-05 01:37:55.695 ThaliTest[1267:2726449] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 01:38:04.302 ThaliTest[1267:2726449] Resetting plugins due to page load.
,2016-01-05 01:38:07.722 ThaliTest[1267:2726449] Finished load of: file:///var/mobile/Containers/Bundle/Application/7C5DAAB3-57EE-4D4E-8D20-8C2F5E7CEAB5/ThaliTest.app/www/index.html
,2016-01-05 01:38:07.959 ThaliTest[1267:2726449] JXcore Cordova plugin initializing
,2016-01-05 01:38:07.960 ThaliTest[1267:2726652] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-05 01:38:09.053 ThaliTest[1267:2726449] THREAD WARNING: ['JXcore'] took '81.406982' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 01:43:27.313 ThaliTest[1267:2726652] jxcore: startBroadcasting
,2016-01-05 01:43:27.331 ThaliTest[1267:2726652] server: starting Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:27.332 ThaliTest[1267:2726652] multipeer session: start timer: 0x17bc3900
2016-01-05 01:43:27.333 ThaliTest[1267:2726652] THEMultipeerSessio,n initialized peer Apple-Iphone6-1_PT4820
2016-01-05 01:43:27.333 ThaliTest[1267:2726652] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-05 01:43:28.433 ThaliTest[1267:2726449] client: found peer: Apple-Iphone5-1_PT4002.tre7Iw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4002.tre7Iw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT4002.tre7Iw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2016-01-05 01:43:30.390 ThaliTest[1267:2726652] jxcore: stopBroadcasting
2016-01-05 01:43:30.391 ThaliTest[1267:2726652] THEMultipeerSession stopping peer
2016-01-05 01:43:30.391 ThaliTest[1267:2726652] multipeer session: stop timer
2016-01-05 01:43:30.392 ThaliTest[1267:2726652] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 62786
,2016-01-05 01:43:30.460 ThaliTest[1267:2726652] jxcore: startBroadcasting
,2016-01-05 01:43:30.464 ThaliTest[1267:2726652] server: starting Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:43:30.464 ThaliTest[1267:2726652] multipeer session: start timer: 0x17bca400
2016-01-05 01:43:30.465 ThaliTest[1267:2726652] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4820
2016-01-05 01:43:30.465 ThaliTest[1267:2726652] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-05T00:43:30.468Z SendDataTCPServer.js: TCP/IP server is bound to port: 62786
,2016-01-05 01:43:30.480 ThaliTest[1267:2726449] client: found peer: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:30.482 ThaliTest[1267:2726449] client: found peer: Apple-Iphone5-1_PT4002.tre7Iw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne6-1_PT4820.GNbylA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:43:30.484Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:43:30.485Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:43:30.485Z SendDataConnector.js: do connect now
2016-01-05 01:43:30.485 ThaliTest[1267:2726652] jxcore: connect Apple,-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:30.485 ThaliTest[1267:2726652] client session: connect
2016-01-05 01:43:30.486 ThaliTest[1267:2726652] client session: stateChange:0->1 Apple-Iphone6-1_PT4820.GNbylA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4002.tre7Iw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 01:43:32.244 ThaliTest[1267:2726449] client: lost peer: Apple-Iphone5-1_PT4002.tre7Iw==
2016-01-05 01:43:32.244 ThaliTest[1267:2726449] client session: onPeerLost: Apple-Iphone5-1_PT4002.tre7Iw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4002.tre7Iw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-05 01:43:32.475 ThaliTest[1267:2726449] client: lost peer: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.476 ThaliTest[1267:2726449] client session: onPeerLost: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.476 ThaliTest[1267:2726449], client session: onLinkFailure: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.476 ThaliTest[1267:2726449] client session: disconnect
2016-01-05 01:43:32.476 ThaliTest[1267:2726449] client session: stateChange:1->0 Apple-Iphone6-1_PT4820.GNbylA==
2,016-01-05 01:43:32.477 ThaliTest[1267:2726449] client session: fireConnectCallback: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.477 ThaliTest[1267:2726449] jxcore: connect: fail: Peer disconnected
2016-01-05 01:43:32.478 ThaliTest[1267:2726449] c,lient: found peer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:43:32.478 ThaliTest[1267:2726449] client: found peer: Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05T00:43:32.480Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-,01-05T00:43:32.480Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-05T00:43:32.484Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_P,T3239.85RfWg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7515.viE/5Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 01:43:32.733 ThaliTest[1267:2726449] client: found peer: Apple-Iphone5-1_PT4002.r/utkA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4002.r/utkA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05T00:43:37.487Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:37.488Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:42.494 ThaliTest[1267:2726652] jxcore: disconnect
2016-01-05 01:43:42.495 ThaliTest[1267:2726652] jxcore: disconnect: fail
2016-01-05T00:43:42.496Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbyl,A==
2016-01-05T00:43:42.496Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
2016-01-05T00:43:42.496Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:42.497Z SendDataConnector.js: do connect now
,2016-01-05 01:43:42.498 ThaliTest[1267:2726652] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:42.499 ThaliTest[1267:2726652] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:42.499 ThaliTest[1267:2726652] jxcore: connect: fail: Peer unreachable
2016-01-05T00:43:42.500Z SendDataConnector.js: CLIENT con,nected to 0, error: Peer unreachable
2016-01-05T00:43:42.500Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:43:42.501Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:43:47.513Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:47.513Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:52.520 ThaliTest[1267:2726652] jxcore: disconnect
2016-01-05 01:43:52.521 ThaliTest[1267:2726652] jxcore: disconnect: fail
2016-01-05T00:43:52.521Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbyl,A==
2016-01-05T00:43:52.522Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
2016-01-05T00:43:52.522Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
2,016-01-05T00:43:52.522Z SendDataConnector.js: do connect now
,2016-01-05 01:43:52.523 ThaliTest[1267:2726652] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:52.525 ThaliTest[1267:2726652] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:52.525 ThaliTest[1267:2726652] j,xcore: connect: fail: Peer unreachable
2016-01-05T00:43:52.525Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:43:52.526Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:43:52.526Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:43:57.533Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:57.534Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:00.466 ThaliTest[1267:2726449] multipeer session: restart
,2016-01-05 01:44:02.539 ThaliTest[1267:2726652] jxcore: disconnect
2016-01-05 01:44:02.539 ThaliTest[1267:2726652] jxcore: disconnect: fail
2016-01-05T00:44:02.540Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbyl,A==
2016-01-05T00:44:02.540Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
2016-01-05T00:44:02.540Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:44:02.541Z SendDataConnector.js: do connect now
,2016-01-05 01:44:02.541 ThaliTest[1267:2726652] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:02.543 ThaliTest[1267:2726652] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:02.544 ThaliTest[1267:2726652] jxcore: connect: fail: Peer unreachable
2016-01-05T00:44:02.544Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:44:02.545Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:44:02.545Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:44:07.552Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:44:07.553Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:12.567 ThaliTest[1267:2726652] jxcore: disconnect
2016-01-05 01:44:12.567 ThaliTest[1267:2726652] jxcore: disconnect: fail
2016-01-05T00:44:12.568Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbyl,A==
2016-01-05T00:44:12.568Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
2016-01-05T00:44:12.568Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:44:12.569Z SendDataConnector.js: do connect now
,2016-01-05 01:44:12.569 ThaliTest[1267:2726652] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:12.570 ThaliTest[1267:2726652] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:12.571 ThaliTest[1267:2726652] jxcore: connect: fail: Peer unreachable
,2016-01-05T00:44:12.572Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:44:12.573Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2016-01-05T00:44:12.574Z SendDataConnector.js: CLIENT Stop now
,2016-01-05 01:44:12.575 ThaliTest[1267:2726652] jxcore: disconnect
2016-01-05 01:44:12.576 ThaliTest[1267:2726652] jxcore: disconnect: fail
2016-01-05T00:44:12.577Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:12.580Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:12.580Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:12.581Z SendDataConnector.js: do connect now
,2016-01-05 01:44:12.582 ThaliTest[1267:2726652] jxcore: connect Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:12.582 ThaliTest[1267:2726652] client session: connect
2016-01-05 01:44:12.583 ThaliTest[1267:2726652] client session: stateChange:0->1 Appl,e-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:12.595 ThaliTest[1267:2726449] client: lost peer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:12.596 ThaliTest[1267:2726449] client session: onPeerLost: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:12.596 ThaliTest[1267:272644,9] client session: onLinkFailure: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:12.596 ThaliTest[1267:2726449] client session: disconnect
2016-01-05 01:44:12.596 ThaliTest[1267:2726449] client session: stateChange:1->0 Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:12.651 ThaliTest[1267:2726449] client session: fireConnectCallback: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:12.651 ThaliTest[1267:2726449] jxcore: connect: fail: Peer disconnected
2016-01-05T00:44:12.652Z SendDataConnector.js: ,CLIENT connected to 0, error: Peer disconnected
2016-01-05T00:44:12.652Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05T00:44:12.653Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.85RfWg==","peerName":"(null)","peerAvailable":false}]
,2016-01-05 01:44:14.107 ThaliTest[1267:2726449] multipeer session: reset timer
2016-01-05 01:44:14.107 ThaliTest[1267:2726449] multipeer session: stop timer
2016-01-05 01:44:14.108 ThaliTest[1267:2726449] multipeer session: start timer: 0x17bca400
2016-,01-05 01:44:14.108 ThaliTest[1267:2726449] server session: connect
2016-01-05 01:44:14.108 ThaliTest[1267:2726449] server session: stateChange:0->1 Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:14.117 ThaliTest[1267:2726449] server: accepting invitation Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:17.286 ThaliTest[1267:2727256] server session: connected
2016-01-05 01:44:17.286 ThaliTest[1267:2727256] server session: stateChange:1->2 Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:17.297 ThaliTest[1267:2726449] server relay: connected (to port: 62786)
,2016-01-05T00:44:17.304Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05 01:44:17.392 ThaliTest[1267:2726449] multipeer session: reset timer
2016-01-05 01:44:17.392 ThaliTest[1267:2726449] multipeer session: stop timer
2016-01-05 01:44:17.392 ThaliTest[1267:2726449] multipeer session: start timer: 0x17bca400
2016-,01-05 01:44:17.393 ThaliTest[1267:2726449] server session: connect
2016-01-05 01:44:17.393 ThaliTest[1267:2726449] server session: stateChange:0->1 Apple-Iphone5-1_PT4002
,2016-01-05 01:44:17.402 ThaliTest[1267:2726449] server: accepting invitation Apple-Iphone5-1_PT4002
,2016-01-05T00:44:17.659Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:17.660Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:17.721Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-05T00:44:17.736Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2016-01-05T00:44:17.752Z SendDataTCPServer.js: TCP/IP server has received 94858 bytes of data
,2016-01-05T00:44:17.767Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:44:17.780 ThaliTest[1267:2726449] multipeer session: reset timer
2016-01-05 01:44:17.780 ThaliTest[1267:2726449] multipeer session: stop timer
2016-01-05 01:44:17.780 ThaliTest[1267:2726449] multipeer session: start timer: 0x17bca400
2016-,01-05 01:44:17.781 ThaliTest[1267:2726449] server session: connect
2016-01-05 01:44:17.781 ThaliTest[1267:2726449] server session: stateChange:0->1 Apple-Iphone5s-1_PT7515
,2016-01-05 01:44:17.790 ThaliTest[1267:2726449] server: accepting invitation Apple-Iphone5s-1_PT7515
,2016-01-05 01:44:17.822 ThaliTest[1267:2727256] server session: not connected Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:20.472 ThaliTest[1267:2727256] server session: connected
2016-01-05 01:44:20.473 ThaliTest[1267:2727256] server session: stateChange:1->2 Apple-Iphone5-1_PT4002
,2016-01-05 01:44:20.495 ThaliTest[1267:2727250] server session: connected
2016-01-05 01:44:20.495 ThaliTest[1267:2727250] server session: stateChange:1->2 Apple-Iphone5s-1_PT7515
,2016-01-05 01:44:20.509 ThaliTest[1267:2726449] server relay: connected (to port: 62786)
2016-01-05 01:44:20.510 ThaliTest[1267:2726449] server relay: connected (to port: 62786)
2016-01-05T00:44:20.520Z SendDataTCPServer.js: TCP/IP server connected
2016-01-05T00:44:20.522Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T00:44:20.862Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-05T00:44:20.876Z SendDataTCPServer.js: TCP/IP server has received 41042 bytes of data
,2016-01-05T00:44:20.892Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2016-01-05T00:44:20.905Z SendDataTCPServer.js: TCP/IP server has received 95792 bytes of data
,2016-01-05T00:44:20.922Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:44:21.219 ThaliTest[1267:2727256] server session: not connected Apple-Iphone5s-1_PT7515
,2016-01-05T00:44:21.449Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-05T00:44:21.463Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2016-01-05T00:44:21.478Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2016-01-05T00:44:21.517Z SendDataTCPServer.js: TCP/IP server has received 47470 bytes of data
,2016-01-05T00:44:21.534Z SendDataTCPServer.js: TCP/IP server has received 71844 bytes of data
,2016-01-05T00:44:21.550Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:44:21.648 ThaliTest[1267:2727257] server session: not connected Apple-Iphone5-1_PT4002
,2016-01-05 01:44:22.665 ThaliTest[1267:2726652] jxcore: disconnect
2016-01-05 01:44:22.665 ThaliTest[1267:2726652] jxcore: disconnect: fail
2016-01-05T00:44:22.666Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.85Rf,Wg==
2016-01-05T00:44:22.666Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT3239.85RfWg== with availability status: true
2016-01-05T00:44:22.667Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05T00:44:22.667Z SendDataConnector.js: do connect now
,2016-01-05 01:44:22.668 ThaliTest[1267:2726652] jxcore: connect Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:22.669 ThaliTest[1267:2726652] client: connect: unreachable Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:22.669 ThaliTest[1267:2726652], jxcore: connect: fail: Peer unreachable
2016-01-05T00:44:22.670Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:44:22.670Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:44:22.670Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:44:27.672Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:27.672Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:32.685 ThaliTest[1267:2726652] jxcore: disconnect
2016-01-05 01:44:32.686 ThaliTest[1267:2726652] jxcore: disconnect: fail
2016-01-05T00:44:32.686Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.85Rf,Wg==
2016-01-05T00:44:32.687Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT3239.85RfWg== with availability status: true
2016-01-05T00:44:32.687Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.85RfWg==,
2016-01-05T00:44:32.687Z SendDataConnector.js: do connect now
,2016-01-05 01:44:32.688 ThaliTest[1267:2726652] jxcore: connect Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:32.689 ThaliTest[1267:2726652] client: connect: unreachable Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:32.690 ThaliTest[1267:2726652], jxcore: connect: fail: Peer unreachable
2016-01-05T00:44:32.690Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:44:32.690Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:44:32.691Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:44:37.695Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:37.695Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:42.697 ThaliTest[1267:2726652] jxcore: disconnect
2016-01-05 01:44:42.698 ThaliTest[1267:2726652] jxcore: disconnect: fail
2016-01-05T00:44:42.698Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.85Rf,Wg==
2016-01-05T00:44:42.699Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT3239.85RfWg== with availability status: true
2016-01-05T00:44:42.699Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05T00:44:42.699Z SendDataConnector.js: do connect now
,2016-01-05 01:44:42.700 ThaliTest[1267:2726652] jxcore: connect Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:42.701 ThaliTest[1267:2726652] client: connect: unreachable Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:42.701 ThaliTest[1267:2726652] jxcore: connect: fail: Peer unreachable
,2016-01-05T00:44:42.702Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:44:42.703Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:44:42.703Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:44:47.706Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:47.707Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:47.782 ThaliTest[1267:2726449] multipeer session: restart
,2016-01-05 01:44:47.819 ThaliTest[1267:2726449] client: found peer: Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:44:47.821 ThaliTest[1267:2726449] client: found peer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:47.822 ThaliTest[1267:2726449] client: found peer: Apple-Iphone5-1_PT4002.r/utkA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.85RfWg==","peerName":"(null)","peerAvailable":true}]
,2016-01-05 01:44:52.712 ThaliTest[1267:2726652] jxcore: disconnect
2016-01-05 01:44:52.712 ThaliTest[1267:2726652] jxcore: disconnect: fail
2016-01-05T00:44:52.713Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.85Rf,Wg==
2016-01-05T00:44:52.713Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT3239.85RfWg== with availability status: true
2016-01-05T00:44:52.714Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.85RfWg==,
2016-01-05T00:44:52.714Z SendDataConnector.js: do connect now
,2016-01-05 01:44:52.715 ThaliTest[1267:2726652] jxcore: connect Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:52.716 ThaliTest[1267:2726652] client session: connect
,2016-01-05 01:44:52.717 ThaliTest[1267:2726652] client session: stateChange:0->1 Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:56.512 ThaliTest[1267:2727335] client session: connected
,2016-01-05 01:44:56.512 ThaliTest[1267:2727335] client session: stateChange:1->2 Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:56.518 ThaliTest[1267:2727335] client session: fireConnectCallback: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:56.518 ThaliTest[1267:2727335] jxcore: connect: success
2016-01-05T00:44:56.519Z SendDataConnector.js: CLIENT connected to 62797, error: null
2016-01-05T00:44:56.520Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 01:44:56.526 ThaliTest[1267:2726449] client: relay established
2016-01-05 01:44:56.526 ThaliTest[1267:2726449] client: new accepted socket: 0x17c730b0
,2016-01-05T00:44:56.541Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T00:44:57.062Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-05T00:44:57.098Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-05T00:44:57.123Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T00:44:57.124Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-05T00:44:57.124Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T00:44:57.124Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:57.125 ThaliTest[1267:2726652] jxcore: disconnect
2016-01-05 01:44:57.125 ThaliTest[1267:2726652] client session: disconnectFromPeer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:57.126 ThaliTest[1267:2726652] client session: disconnect
2016-01-05 01:44:57.126 ThaliTest[1267:2726652] client session: stateChange:2->0 Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:57.131 ThaliTest[1267:2726652] jxcore: disconnect: success
2016-01-05T00:44:57.131Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.85RfWg==
---- round done--------
startWithNextDevice
device[3]: Ap,ple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05T00:44:57.132Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05T00:44:57.132Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05T00:44:57.132Z SendDataConnector.js: do connect now
2016-01-05 01:44:57.132 ThaliTest[1267:2726652] jxcore: connect Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:44:57.132 ThaliTest[1267:2726652] client session: connect
2016-01-05 01:44:57.132 ThaliTest[1267:2726652] client session: stateChange:0->1 Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:45:00.440 ThaliTest[1267:2727337] client session: connected
2016-01-05 01:45:00.441 ThaliTest[1267:2727337] client session: stateChange:1->2 Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:45:00.989 ThaliTest[1267:2727336] client session: fireConnectCallback: Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:45:00.989 ThaliTest[1267:2727336] jxcore: connect: success
2016-01-05T00:45:00.990Z SendDataConnector.js: CLIENT connected, to 62800, error: null
2016-01-05T00:45:00.990Z SendDataConnector.js: CLIENT starting client 
2016-01-05 01:45:00.993 ThaliTest[1267:2726449] client: relay established
2016-01-05 01:45:00.994 ThaliTest[1267:2726449] client: new accepted socket: 0x17c849,a0
,2016-01-05T00:45:01.005Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T00:45:01.285Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T00:45:01.309Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-05T00:45:01.323Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-05T00:45:01.336Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T00:45:01.336Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T00:45:01.336Z SendDataConnector.js: CLIENT Stop now
2016-01-05T00:45:01.337Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:45:01.337 ThaliTest[1267:2726652] jxcore: disconnect
,2016-01-05 01:45:01.338 ThaliTest[1267:2726652] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:45:01.338 ThaliTest[1267:2726652] client session: disconnect
,2016-01-05 01:45:01.339 ThaliTest[1267:2726652] client session: stateChange:2->0 Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:45:01.400 ThaliTest[1267:2726652] jxcore: disconnect: success
,2016-01-05T00:45:01.400Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7515.viE/5Q==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05T00:45:01.401Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05T00:45:01.402Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05T00:45:01.402Z SendDataConnector.js: do connect now
,2016-01-05 01:45:01.402 ThaliTest[1267:2726652] jxcore: connect Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:45:01.403 ThaliTest[1267:2726652] client session: connect
,2016-01-05 01:45:01.404 ThaliTest[1267:2726652] client session: stateChange:0->1 Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:45:07.575 ThaliTest[1267:2727338] client session: connected
2016-01-05 01:45:07.576 ThaliTest[1267:2727338] client session: stateChange:1->2 Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:45:08.157 ThaliTest[1267:2727337] client session: fireConnectCallback: Apple-Iphone5-1_PT4002.r/utkA==
2016-01-05 01:45:08.158 ThaliTest[1267:2727337] jxcore: connect: success
2016-01-05T00:45:08.159Z SendDataConnector.js: CLIENT connected ,to 62803, error: null
2016-01-05T00:45:08.160Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 01:45:08.164 ThaliTest[1267:2726449] client: relay established
2016-01-05 01:45:08.165 ThaliTest[1267:2726449] client: new accepted socket: 0x17bd9280
,2016-01-05T00:45:08.176Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T00:45:08.585Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-05T00:45:08.608Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-05T00:45:08.621Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T00:45:08.634Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T00:45:08.634Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-05T00:45:08.634Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T00:45:08.635Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:45:08.635 ThaliTest[1267:2726652] jxcore: disconnect
,2016-01-05 01:45:08.635 ThaliTest[1267:2726652] client session: disconnectFromPeer: Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:45:08.636 ThaliTest[1267:2726652] client session: disconnect
,2016-01-05 01:45:08.636 ThaliTest[1267:2726652] client session: stateChange:2->0 Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:45:08.700 ThaliTest[1267:2726652] jxcore: disconnect: success
,2016-01-05T00:45:08.700Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4002.r/utkA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-05T00:45:08.704Z SendDataConnector.js: CLIENT Stop now
2016-01-05T00:45:08.704Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2016-01-05 01:45:09.915 ThaliTest[1267:2726652] jxcore: stopBroadcasting
2016-01-05 01:45:09.916 ThaliTest[1267:2726652] THEMultipeerSession stopping peer
2016-01-05 01:45:09.916 ThaliTest[1267:2726652] multipeer session: stop timer
,2016-01-05 01:45:09.919 ThaliTest[1267:2726652] server session: disconnect
2016-01-05 01:45:09.919 ThaliTest[1267:2726652] server session: stateChange:2->0 Apple-IpadAir2-1_PT3239
,2016-01-05 01:45:09.929 ThaliTest[1267:2726652] server session: disconnect
2016-01-05 01:45:09.929 ThaliTest[1267:2726652] server session: stateChange:2->0 Apple-Iphone5s-1_PT7515
2016-01-05 01:45:09.936 ThaliTest[1267:2726652] server session: disconnect,
2016-01-05 01:45:09.936 ThaliTest[1267:2726652] server session: stateChange:2->0 Apple-Iphone5-1_PT4002
,2016-01-05 01:45:10.026 ThaliTest[1267:2726652] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2016-01-05T00:45:10.043Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:10.045Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:10.047Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:10.047Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
