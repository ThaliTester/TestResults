#### Test 54968200254eab2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/946A0DD3-5C6B-48C6-B861-A1BE2D18BC97/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/946A0DD3-5C6B-48C6-B861-A1BE2D18BC97/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5839580F-8218-4B28-B82D-949488F4260E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64605"
,(lldb)     command script import "/tmp/946A0DD3-5C6B-48C6-B861-A1BE2D18BC97/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 01:37:56.405 ThaliTest[1277:2796649] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F1272BA6-5933-42E4-91F8-9CFCDA70E98D/Library/Cookies/Cookies.binarycookies
,2016-01-05 01:37:56.727 ThaliTest[1277:2796649] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 01:37:56.727 ThaliTest[1277:2796649] Multi-tasking -> Device: YES, App: YES
,2016-01-05 01:37:56.736 ThaliTest[1277:2796649] Unlimited access to network resources
,2016-01-05 01:37:56.743 ThaliTest[1277:2796649] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 01:38:05.502 ThaliTest[1277:2796649] Resetting plugins due to page load.
,2016-01-05 01:38:08.601 ThaliTest[1277:2796649] Finished load of: file:///var/mobile/Containers/Bundle/Application/5839580F-8218-4B28-B82D-949488F4260E/ThaliTest.app/www/index.html
,2016-01-05 01:38:08.779 ThaliTest[1277:2796649] JXcore Cordova plugin initializing
,2016-01-05 01:38:08.780 ThaliTest[1277:2796878] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-05 01:38:09.766 ThaliTest[1277:2796649] THREAD WARNING: ['JXcore'] took '70.316162' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 01:43:29.481 ThaliTest[1277:2796878] jxcore: startBroadcasting
,2016-01-05 01:43:29.497 ThaliTest[1277:2796878] server: starting Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05 01:43:29.498 ThaliTest[1277:2796878] multipeer session: start timer: 0x18d9e7c0
2016-01-05 01:43:29.499 ThaliTest[1277:2796878] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT3239
2016-01-05 01:43:29.499 ThaliTest[1277:2796878] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-05 01:43:30.753 ThaliTest[1277:2796649] client: found peer: Apple-Iphone6-1_PT4820.GNbylA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
,2016-01-05 01:43:32.548 ThaliTest[1277:2796878] jxcore: stopBroadcasting
,2016-01-05 01:43:32.548 ThaliTest[1277:2796878] THEMultipeerSession stopping peer
,2016-01-05 01:43:32.549 ThaliTest[1277:2796878] multipeer session: stop timer
,2016-01-05 01:43:32.550 ThaliTest[1277:2796878] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 63065
,2016-01-05 01:43:32.613 ThaliTest[1277:2796878] jxcore: startBroadcasting
,2016-01-05 01:43:32.616 ThaliTest[1277:2796878] server: starting Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:43:32.617 ThaliTest[1277:2796878] multipeer session: start timer: 0x16fcb150
2016-01-05 01:43:32.618 ThaliTest[1277:2796878] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT3239
2016-01-05 01:43:32.618 ThaliTest[1277:2796878] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2016-01-05T00:43:32.623Z SendDataTCPServer.js: TCP/IP server is bound to port: 63065
,2016-01-05 01:43:33.087 ThaliTest[1277:2796649] client: found peer: Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:33.090 ThaliTest[1277:2796649] client: found peer: Apple-IpadAir2-1_PT3239.C7DKtQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:43:33.093Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:33.094Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:33.095Z SendDataConnector.js: do connect now
,2016-01-05 01:43:33.096 ThaliTest[1277:2796878] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:33.097 ThaliTest[1277:2796878] client session: connect
2016-01-05 01:43:33.097 ThaliTest[1277:2796878] client session: stateChange:0->1 Apple-Iphone6-1_PT4820.GNbylA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.C7DKtQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 01:43:33.668 ThaliTest[1277:2796649] client: lost peer: Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:33.668 ThaliTest[1277:2796649] client session: onPeerLost: Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:33.669 ThaliTest[1277:2796649] client: found peer: Apple-Iphone5-1_PT4002.tre7Iw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.C7DKtQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4002.tre7Iw==","peerName":"(null,)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 01:43:33.903 ThaliTest[1277:2796649] client: found peer: Apple-Iphone6-1_PT4820.TWfskw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.TWfskw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 01:43:34.374 ThaliTest[1277:2796649] client: found peer: Apple-Iphone5s-1_PT7515.viE/5Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7515.viE/5Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 01:43:35.443 ThaliTest[1277:2796649] client: lost peer: Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:35.444 ThaliTest[1277:2796649] client session: onPeerLost: Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:35.444 ThaliTest[1277:2796649] client session: onLinkFailure: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:35.444 ThaliTest[1277:2796649] client session: disconnect
2016-01-05 01:43:35.445 ThaliTest[1277:2796649] client session: stat,eChange:1->0 Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:35.445 ThaliTest[1277:2796649] client session: fireConnectCallback: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:35.446 ThaliTest[1277:2796649] jxcore: connect: fail: Peer disconnected
2016-01-05 01:43:35.446 ThaliTest[1277:2796649] ,client: lost peer: Apple-Iphone5-1_PT4002.tre7Iw==
2016-01-05T00:43:35.448Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2016-01-05 01:43:35.447 ThaliTest[1277:2796649] client session: onPeerLost: Apple-Iphone5-1_PT4002.tre7Iw==
2016-01-05T00:43:35.449Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05 01:43:35.449 ThaliTest[1277:2796649] client: f,ound peer: Apple-Iphone5-1_PT4002.r/utkA==
2016-01-05T00:43:35.450Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4002.tre7Iw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4002.r/utkA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05T00:43:40.462Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:40.463Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:45.474 ThaliTest[1277:2796878] jxcore: disconnect
,2016-01-05 01:43:45.474 ThaliTest[1277:2796878] jxcore: disconnect: fail
,2016-01-05T00:43:45.475Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:45.476Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
,2016-01-05T00:43:45.476Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:45.477Z SendDataConnector.js: do connect now
,2016-01-05 01:43:45.478 ThaliTest[1277:2796878] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:45.478 ThaliTest[1277:2796878] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:45.479 ThaliTest[1277:2796878] jxcore: connect: fail: Peer unreachable
,2016-01-05T00:43:45.480Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T00:43:45.480Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T00:43:45.481Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:43:50.493Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:50.494Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:55.504 ThaliTest[1277:2796878] jxcore: disconnect
,2016-01-05 01:43:55.505 ThaliTest[1277:2796878] jxcore: disconnect: fail
,2016-01-05T00:43:55.506Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:55.506Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
,2016-01-05T00:43:55.507Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:43:55.507Z SendDataConnector.js: do connect now
,2016-01-05 01:43:55.509 ThaliTest[1277:2796878] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:55.509 ThaliTest[1277:2796878] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:43:55.510 ThaliTest[1277:2796878] jxcore: connect: fail: Peer unreachable
,2016-01-05T00:43:55.511Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:43:55.511Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T00:43:55.512Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:44:00.518Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:44:00.518Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:02.619 ThaliTest[1277:2796649] multipeer session: restart
,2016-01-05 01:44:02.648 ThaliTest[1277:2796649] client: found peer: Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:02.650 ThaliTest[1277:2796649] client: found peer: Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:44:02.650 ThaliTest[1277:2796649] client: found peer: Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:05.521 ThaliTest[1277:2796878] jxcore: disconnect
,2016-01-05 01:44:05.522 ThaliTest[1277:2796878] jxcore: disconnect: fail
,2016-01-05T00:44:05.522Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:44:05.523Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
,2016-01-05T00:44:05.524Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:44:05.524Z SendDataConnector.js: do connect now
,2016-01-05 01:44:05.525 ThaliTest[1277:2796878] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:44:05.526 ThaliTest[1277:2796878] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:05.526 ThaliTest[1277:2796878] jxcore: connect: fail: Peer unreachable
,2016-01-05T00:44:05.527Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T00:44:05.528Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T00:44:05.529Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:44:10.530Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05T00:44:10.531Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4820.GNbylA==
,2016-01-05 01:44:14.996 ThaliTest[1277:2796649] multipeer session: reset timer
2016-01-05 01:44:14.997 ThaliTest[1277:2796649] multipeer session: stop timer
2016-01-05 01:44:14.997 ThaliTest[1277:2796649] multipeer session: start timer: 0x16fcb150
2016-01-05 01:44:14.998 ThaliTest[1277:2796649] server session: connect
2016-01-05 01:44:14.998 ThaliTest[1277:2796649] server session: stateChange:0->1 Apple-Iphone5s-1_PT7515
,2016-01-05 01:44:15.004 ThaliTest[1277:2796649] server: accepting invitation Apple-Iphone5s-1_PT7515
,2016-01-05 01:44:15.453 ThaliTest[1277:2796649] multipeer session: reset timer
2016-01-05 01:44:15.453 ThaliTest[1277:2796649] multipeer session: stop timer
2016-01-05 01:44:15.453 ThaliTest[1277:2796649] multipeer session: start timer: 0x16fcb150
2016-01-05 01:44:15.453 ThaliTest[1277:2796649] server session: connect
2016-01-05 01:44:15.453 ThaliTest[1277:2796649] server session: stateChange:0->1 Apple-Iphone5-1_PT4002
,2016-01-05 01:44:15.455 ThaliTest[1277:2796649] server: accepting invitation Apple-Iphone5-1_PT4002
,2016-01-05 01:44:15.538 ThaliTest[1277:2796878] jxcore: disconnect
2016-01-05 01:44:15.538 ThaliTest[1277:2796878] jxcore: disconnect: fail
2016-01-05T00:44:15.538Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:44:15.538Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4820.GNbylA== with availability status: true
2016-01-05T00:44:15.538Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05T00:44:15.539Z SendDataConnector.js: do connect now
,2016-01-05 01:44:15.539 ThaliTest[1277:2796878] jxcore: connect Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:44:15.539 ThaliTest[1277:2796878] client: connect: unreachable Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:44:15.539 ThaliTest[1277:2796878] jxcore: connect: fail: Peer unreachable
2016-01-05T00:44:15.539Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:44:15.540Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-05T00:44:15.541Z SendDataConnector.js: CLIENT Stop now
,2016-01-05 01:44:15.541 ThaliTest[1277:2796878] jxcore: disconnect
2016-01-05 01:44:15.541 ThaliTest[1277:2796878] jxcore: disconnect: fail
2016-01-05T00:44:15.541Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.GNbylA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05T00:44:15.543Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05T00:44:15.543Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05T00:44:15.543Z SendDataConnector.js: do connect now
,2016-01-05 01:44:15.544 ThaliTest[1277:2796878] jxcore: connect Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:15.544 ThaliTest[1277:2796878] client session: connect
2016-01-05 01:44:15.544 ThaliTest[1277:2796878] client session: stateChange:0->1 Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:18.606 ThaliTest[1277:2797656] server session: connected
2016-01-05 01:44:18.607 ThaliTest[1277:2797656] server session: stateChange:1->2 Apple-Iphone5s-1_PT7515
,2016-01-05 01:44:18.617 ThaliTest[1277:2796649] server relay: connected (to port: 63065)
,2016-01-05T00:44:18.626Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05 01:44:18.662 ThaliTest[1277:2797695] server session: connected
,2016-01-05 01:44:18.662 ThaliTest[1277:2797695] server session: stateChange:1->2 Apple-Iphone5-1_PT4002
,2016-01-05 01:44:18.726 ThaliTest[1277:2796649] server relay: connected (to port: 63065)
,2016-01-05T00:44:18.736Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T00:44:18.958Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2016-01-05T00:44:18.984Z SendDataTCPServer.js: TCP/IP server has received 25996 bytes of data
,2016-01-05T00:44:18.998Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-05T00:44:19.014Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05T00:44:19.186Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-05T00:44:19.200Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-05T00:44:19.215Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2016-01-05T00:44:19.255Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-05T00:44:19.271Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-05T00:44:19.431Z SendDataTCPServer.js: TCP/IP server has received 88512 bytes of data
,2016-01-05T00:44:19.446Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:44:19.498 ThaliTest[1277:2797693] server session: not connected Apple-Iphone5-1_PT4002
,2016-01-05 01:44:19.522 ThaliTest[1277:2797695] client session: connected
2016-01-05 01:44:19.522 ThaliTest[1277:2797695] client session: stateChange:1->2 Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:19.542 ThaliTest[1277:2797695] server session: not connected Apple-Iphone5s-1_PT7515
,2016-01-05 01:44:19.576 ThaliTest[1277:2797656] client session: fireConnectCallback: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:19.576 ThaliTest[1277:2797656] jxcore: connect: success
,2016-01-05T00:44:19.578Z SendDataConnector.js: CLIENT connected to 63072, error: null
,2016-01-05T00:44:19.578Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 01:44:19.581 ThaliTest[1277:2796649] client: relay established
2016-01-05 01:44:19.582 ThaliTest[1277:2796649] client: new accepted socket: 0x18ce4580
,2016-01-05T00:44:19.597Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T00:44:20.041Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T00:44:20.041Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-05T00:44:20.041Z SendDataConnector.js: CLIENT Stop now
2016-01-05T00:44:20.041Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:20.042 ThaliTest[1277:2796878] jxcore: disconnect
,2016-01-05 01:44:20.042 ThaliTest[1277:2796878] client session: disconnectFromPeer: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:20.043 ThaliTest[1277:2796878] client session: disconnect
2016-01-05 01:44:20.043 ThaliTest[1277:2796878] client session: stateChange:2->0 Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:20.046 ThaliTest[1277:2796878] jxcore: disconnect: success
,2016-01-05T00:44:20.046Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.TWfskw==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05T00:44:20.047Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05T00:44:20.047Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05T00:44:20.047Z SendDataConnector.js: do connect now
,2016-01-05 01:44:20.048 ThaliTest[1277:2796878] jxcore: connect Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:44:20.048 ThaliTest[1277:2796878] client session: connect
2016-01-05 01:44:20.048 ThaliTest[1277:2796878] client session: stateChange:0->1 Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:44:23.701 ThaliTest[1277:2797709] client session: connected
2016-01-05 01:44:23.702 ThaliTest[1277:2797709] client session: stateChange:1->2 Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:44:23.706 ThaliTest[1277:2797709] client session: fireConnectCallback: Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:44:23.706 ThaliTest[1277:2797709] jxcore: connect: success
,2016-01-05T00:44:23.707Z SendDataConnector.js: CLIENT connected to 63075, error: null
,2016-01-05T00:44:23.708Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 01:44:23.711 ThaliTest[1277:2796649] client: relay established
2016-01-05 01:44:23.712 ThaliTest[1277:2796649] client: new accepted socket: 0x18cda690
,2016-01-05T00:44:23.724Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T00:44:24.035Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T00:44:24.096Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T00:44:24.107Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T00:44:24.108Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T00:44:24.108Z SendDataConnector.js: CLIENT Stop now
2016-01-05T00:44:24.108Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:24.109 ThaliTest[1277:2796878] jxcore: disconnect
,2016-01-05 01:44:24.109 ThaliTest[1277:2796878] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:44:24.109 ThaliTest[1277:2796878] client session: disconnect
,2016-01-05 01:44:24.109 ThaliTest[1277:2796878] client session: stateChange:2->0 Apple-Iphone5s-1_PT7515.viE/5Q==
,2016-01-05 01:44:24.113 ThaliTest[1277:2796878] jxcore: disconnect: success
,2016-01-05T00:44:24.115Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7515.viE/5Q==
,---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05T00:44:24.116Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05T00:44:24.116Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4002.r/utkA==
2016-01-05T00:44:24.116Z SendDataConnector.js: do connect now
,2016-01-05 01:44:24.116 ThaliTest[1277:2796878] jxcore: connect Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:24.117 ThaliTest[1277:2796878] client session: connect
,2016-01-05 01:44:24.117 ThaliTest[1277:2796878] client session: stateChange:0->1 Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:27.701 ThaliTest[1277:2797656] client session: connected
2016-01-05 01:44:27.701 ThaliTest[1277:2797656] client session: stateChange:1->2 Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:27.730 ThaliTest[1277:2797709] client session: fireConnectCallback: Apple-Iphone5-1_PT4002.r/utkA==
2016-01-05 01:44:27.731 ThaliTest[1277:2797709] jxcore: connect: success
,2016-01-05T00:44:27.732Z SendDataConnector.js: CLIENT connected to 63078, error: null
,2016-01-05T00:44:27.732Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 01:44:27.735 ThaliTest[1277:2796649] client: relay established
2016-01-05 01:44:27.736 ThaliTest[1277:2796649] client: new accepted socket: 0x18db2700
,2016-01-05T00:44:27.750Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T00:44:28.065Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-05T00:44:28.089Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-05T00:44:28.102Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T00:44:28.102Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-05T00:44:28.102Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T00:44:28.102Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:28.103 ThaliTest[1277:2796878] jxcore: disconnect
,2016-01-05 01:44:28.103 ThaliTest[1277:2796878] client session: disconnectFromPeer: Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:28.103 ThaliTest[1277:2796878] client session: disconnect
,2016-01-05 01:44:28.104 ThaliTest[1277:2796878] client session: stateChange:2->0 Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:28.107 ThaliTest[1277:2796878] jxcore: disconnect: success
,2016-01-05T00:44:28.107Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4002.r/utkA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-05T00:44:28.112Z SendDataConnector.js: CLIENT Stop now
2016-01-05T00:44:28.112Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:45.453 ThaliTest[1277:2796649] multipeer session: restart
,2016-01-05 01:44:45.480 ThaliTest[1277:2796649] client: found peer: Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:44:45.480 ThaliTest[1277:2796649] client: found peer: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:45.481 ThaliTest[1277:2796649] client: found peer: Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:55.193 ThaliTest[1277:2796649] multipeer session: reset timer
2016-01-05 01:44:55.193 ThaliTest[1277:2796649] multipeer session: stop timer
2016-01-05 01:44:55.194 ThaliTest[1277:2796649] multipeer session: start timer: 0x16fcb150
2016-01-05 01:44:55.194 ThaliTest[1277:2796649] server session: connect
,2016-01-05 01:44:55.194 ThaliTest[1277:2796649] server session: stateChange:0->1 Apple-Iphone6-1_PT4820
,2016-01-05 01:44:55.201 ThaliTest[1277:2796649] server: accepting invitation Apple-Iphone6-1_PT4820
,2016-01-05 01:44:58.763 ThaliTest[1277:2797744] server session: connected
2016-01-05 01:44:58.764 ThaliTest[1277:2797744] server session: stateChange:1->2 Apple-Iphone6-1_PT4820
,2016-01-05 01:44:59.278 ThaliTest[1277:2796649] server relay: connected (to port: 63065)
,2016-01-05T00:44:59.281Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T00:44:59.297Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2016-01-05T00:44:59.310Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2016-01-05T00:44:59.350Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:44:59.407 ThaliTest[1277:2797744] server session: not connected Apple-Iphone6-1_PT4820
,teardown
,testSendData stopped
,2016-01-05 01:45:12.630 ThaliTest[1277:2796878] jxcore: stopBroadcasting
2016-01-05 01:45:12.630 ThaliTest[1277:2796878] THEMultipeerSession stopping peer
,2016-01-05 01:45:12.631 ThaliTest[1277:2796878] multipeer session: stop timer
,2016-01-05 01:45:12.632 ThaliTest[1277:2796878] server session: disconnect
2016-01-05 01:45:12.632 ThaliTest[1277:2796878] server session: stateChange:2->0 Apple-Iphone5s-1_PT7515
,2016-01-05 01:45:12.640 ThaliTest[1277:2796878] server session: disconnect
2016-01-05 01:45:12.641 ThaliTest[1277:2796878] server session: stateChange:2->0 Apple-Iphone6-1_PT4820
,2016-01-05 01:45:12.652 ThaliTest[1277:2796878] server session: disconnect
2016-01-05 01:45:12.652 ThaliTest[1277:2796878] server session: stateChange:2->0 Apple-Iphone5-1_PT4002
,2016-01-05 01:45:12.662 ThaliTest[1277:2796878] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-05T00:45:12.681Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:12.682Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:12.684Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:12.685Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
