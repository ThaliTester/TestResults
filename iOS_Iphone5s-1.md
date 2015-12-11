#### Test 5065027857de7f1_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/E2606678-9A80-4289-BC53-3DB14785DE5E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E2606678-9A80-4289-BC53-3DB14785DE5E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/298FE496-5F53-44F1-92D3-980836907ADE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54043"
,(lldb)     command script import "/tmp/E2606678-9A80-4289-BC53-3DB14785DE5E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-11 12:10:24.120 ThaliTest[758:701428] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/26C6ACE2-D0EF-462D-9B6E-3DB41F01CE74/Library/Cookies/Cookies.binarycookies
,2015-12-11 12:10:24.559 ThaliTest[758:701428] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 12:10:24.561 ThaliTest[758:701428] Multi-tasking -> Device: YES, App: YES
,2015-12-11 12:10:24.571 ThaliTest[758:701428] Unlimited access to network resources
,2015-12-11 12:10:24.584 ThaliTest[758:701428] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 12:10:33.649 ThaliTest[758:701428] Resetting plugins due to page load.
,2015-12-11 12:10:36.990 ThaliTest[758:701428] Finished load of: file:///var/mobile/Containers/Bundle/Application/298FE496-5F53-44F1-92D3-980836907ADE/ThaliTest.app/www/index.html
,2015-12-11 12:10:37.192 ThaliTest[758:701428] JXcore Cordova plugin initializing
,2015-12-11 12:10:37.194 ThaliTest[758:701794] JXcore instance initializing
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
,2015-12-11 12:10:38.515 ThaliTest[758:701428] THREAD WARNING: ['JXcore'] took '90.190918' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-11 12:15:28.530 ThaliTest[758:701794] jxcore: startBroadcasting
,2015-12-11 12:15:28.552 ThaliTest[758:701794] server: starting Apple-Iphone5s-1_PT8695.IK91fw==
,2015-12-11 12:15:28.553 ThaliTest[758:701794] multipeer session: start timer: 0x18b6aca0
2015-12-11 12:15:28.554 ThaliTest[758:701794] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8695
,2015-12-11 12:15:28.557 ThaliTest[758:701794] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-11 12:15:29.092 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.X/CFmw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2684.X/CFmw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT2684.X/CFmw==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2015-12-11 12:15:29.168 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.QOwtzQ==
2015-12-11 12:15:29.169 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:15:31.287 ThaliTest[758:701428] client: lost peer: Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:31.287 ThaliTest[758:701428] client session: onPeerLost: Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:31.288 ThaliTest[758:701428] clien,t: lost peer: Apple-Iphone6-1_PT2932.QOwtzQ==
2015-12-11 12:15:31.290 ThaliTest[758:701428] client session: onPeerLost: Apple-Iphone6-1_PT2932.QOwtzQ==
,2015-12-11 12:15:31.391 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,teardown
,testFindPeers stopped
,2015-12-11 12:15:31.961 ThaliTest[758:701794] jxcore: stopBroadcasting
2015-12-11 12:15:31.962 ThaliTest[758:701794] THEMultipeerSession stopping peer
2015-12-11 12:15:31.962 ThaliTest[758:701794] multipeer session: stop timer
2015-12-11 12:15:31.963 ThaliTest[758:701794] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 56661
2015-12-11 12:15:32.112 ThaliTest[758:701794] jxcore: startBroadcasting
,2015-12-11 12:15:32.117 ThaliTest[758:701794] server: starting Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:15:32.118 ThaliTest[758:701794] multipeer session: start timer: 0x18c2d5b0
2015-12-11 12:15:32.118 ThaliTest[758:701794] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8695
2015-12-11 12:15:32.118 ThaliTest[758:701794] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-11T11:15:32.123Z SendDataTCPServer.js: TCP/IP server is bound to port: 56661
,2015-12-11 12:15:33.115 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:15:33.116 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:15:33.117 ThaliTest[758:701428] client: fou,nd peer: Apple-Iphone6-1_PT2932.PHL+kA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2684.BiXlYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1_PT2684.,BiXlYA==
2015-12-11T11:15:33.121Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11T11:15:33.122Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11T11:15:33.125Z SendDataConnector.js: do connect now
,2015-12-11 12:15:33.128 ThaliTest[758:701794] jxcore: connect Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:15:33.128 ThaliTest[758:701794] client session: connect
,2015-12-11 12:15:33.129 ThaliTest[758:701794] client session: stateChange:0->1 Apple-Iphone5-1_PT2684.BiXlYA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.1YTBNQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.PHL+kA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 12:15:37.093 ThaliTest[758:702384] client session: connected
2015-12-11 12:15:37.093 ThaliTest[758:702384] client session: stateChange:1->2 Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:15:37.103 ThaliTest[758:702384] client session: fireConnectCallback: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:15:37.103 ThaliTest[758:702384] jxcore: connect: success
,2015-12-11T11:15:37.106Z SendDataConnector.js: CLIENT connected to 56664, error: null
,2015-12-11T11:15:37.107Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:15:37.114 ThaliTest[758:701428] client: relay established
2015-12-11 12:15:37.114 ThaliTest[758:701428] client: new accepted socket: 0x1763e040
,2015-12-11T11:15:37.127Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:15:37.514Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T11:15:37.528Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-11T11:15:37.540Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T11:15:37.540Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-11T11:15:37.541Z SendDataConnector.js: CLIENT Stop now
2015-12-11T11:15:37.541Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:15:37.542 ThaliTest[758:701794] jxcore: disconnect
2015-12-11 12:15:37.543 ThaliTest[758:701794] client session: disconnectFromPeer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:15:37.543 ThaliTest[758:701794] client session: disconnect
2015-12-11 12:15:37.543 ThaliTest[758:701794] client session: stateChange:2->0 Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:15:37.549 ThaliTest[758:701794] jxcore: disconnect: success
2015-12-11T11:15:37.552Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2684.BiXlYA==
---- round done--------
startWithNextDevice
device[2]: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:15:37.553Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:15:37.553Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:1,5:37.553Z SendDataConnector.js: do connect now
2015-12-11 12:15:37.553 ThaliTest[758:701794] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:15:37.553 ThaliTest[758:701794] client session: connect
2015-12-11 12:15:37.553 ThaliTest[758:701794] client session: stateChange:0->1 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:15:40.365 ThaliTest[758:702364] client session: connected
2015-12-11 12:15:40.365 ThaliTest[758:702364] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:15:40.398 ThaliTest[758:702381] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:15:40.399 ThaliTest[758:702381] jxcore: connect: success
2015-12-11T11:15:40.400Z SendDataConnector.js: CLIENT connected to 56667, error: null
2015-12-11T11:15:40.401Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:15:40.404 ThaliTest[758:701428] client: relay established
2015-12-11 12:15:40.405 ThaliTest[758:701428] client: new accepted socket: 0x18c30860
,2015-12-11T11:15:40.419Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:15:50.695Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T11:15:50.696Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:15:50.697Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:15:50.698Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:15:50.699Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11 12:15:50.701 ThaliTest[758:701428] client: socket closed
2015-12-11 12:15:50.702 ThaliTest[758:701428] client relay: socket disconnected
2015-12-11 12:15:50.703 ThaliTest[758:701428] client relay: 0x18c30860 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-11 12:15:50.703 ThaliTest[758:701428] client session: socket closed: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:,15:50.703 ThaliTest[758:701428] client session: onLinkFailure: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:15:50.703 ThaliTest[758:701428] client session: disconnect
2015-12-11 12:15:50.704 ThaliTest[758:701428] client session: stateChange:2->0 Apple-,IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:15:50.713 ThaliTest[758:701428] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:15:55.703Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:15:55.704Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:00.706 ThaliTest[758:701794] jxcore: disconnect
2015-12-11 12:16:00.707 ThaliTest[758:701794] jxcore: disconnect: fail
2015-12-11T11:16:00.708Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:16:00.708Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
,2015-12-11T11:16:00.709Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:16:00.709Z SendDataConnector.js: do connect now
,2015-12-11 12:16:00.711 ThaliTest[758:701794] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:00.711 ThaliTest[758:701794] client session: connect
2015-12-11 12:16:00.712 ThaliTest[758:701794] client session: stateChange:0->1 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:02.119 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:16:02.175 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:02.176 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:16:02.188 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:16:03.793 ThaliTest[758:702365] client session: connected
2015-12-11 12:16:03.793 ThaliTest[758:702365] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:03.830 ThaliTest[758:702455] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:03.831 ThaliTest[758:702455] jxcore: connect: success
2015-12-11T11:16:03.833Z SendDataConnector.js: CLIENT connected to ,56673, error: null
2015-12-11T11:16:03.833Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:16:03.837 ThaliTest[758:701428] client: relay established
2015-12-11 12:16:03.838 ThaliTest[758:701428] client: new accepted socket: 0x18c305b0
,2015-12-11T11:16:03.848Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:16:14.122Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T11:16:14.122Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:14.124Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:14.124Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:16:14.125Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11 12:16:14.126 ThaliTest[758:701428] client: socket closed
2015-12-11 12:16:14.127 ThaliTest[758:701428] client relay: socket disconnected
2015-12-11 12:16:14.127 ThaliTest[758:701428] client relay: 0x18c305b0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-11 12:16:14.128 ThaliTest[758:701428] client session: socket closed: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:,16:14.128 ThaliTest[758:701428] client session: onLinkFailure: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:14.128 ThaliTest[758:701428] client session: disconnect
2015-12-11 12:16:14.128 ThaliTest[758:701428] client session: stateChange:2->0 Apple-,IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:14.142 ThaliTest[758:701428] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:19.136Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:19.137Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:24.138 ThaliTest[758:701794] jxcore: disconnect
2015-12-11 12:16:24.139 ThaliTest[758:701794] jxcore: disconnect: fail
2015-12-11T11:16:24.139Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==,
2015-12-11T11:16:24.140Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
2015-12-11T11:16:24.140Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:24.140Z SendDataConnector.js: do connect now
2015-12-11 12:16:24.141 ThaliTest[758:701794] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:24.142 ThaliTest[758:701794] client session: connect
2015-12-11 12:16:24.143 ThaliTest[758:701794] client session: stateChange:0->1 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:27.571 ThaliTest[758:702549] client session: connected
2015-12-11 12:16:27.571 ThaliTest[758:702549] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:28.323 ThaliTest[758:702552] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:28.327 ThaliTest[758:702552] jxcore: connect: success
2015-12-11T11:16:28.328Z SendDataConnector.js: CLIENT connected to ,56676, error: null
2015-12-11T11:16:28.329Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:16:28.334 ThaliTest[758:701428] client: relay established
2015-12-11 12:16:28.338 ThaliTest[758:701428] client: new accepted socket: 0x18c31160
,2015-12-11T11:16:28.346Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 12:16:32.119 ThaliTest[758:701428] multipeer session: restart
,2015-12-11T11:16:38.611Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T11:16:38.612Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:38.613Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:38.613Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:16:38.614Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11 12:16:38.616 ThaliTest[758:701428] client: socket closed
2015-12-11 12:16:38.617 ThaliTest[758:701428] client relay: socket disconnected
2015-12-11 12:16:38.617 ThaliTest[758:701428] client relay: 0x18c31160 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-11 12:16:38.617 ThaliTest[758:701428] client session: socket closed: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:,16:38.618 ThaliTest[758:701428] client session: onLinkFailure: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:38.618 ThaliTest[758:701428] client session: disconnect
2015-12-11 12:16:38.618 ThaliTest[758:701428] client session: stateChange:2->0 Apple-,IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:38.626 ThaliTest[758:701428] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:43.621Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:43.622Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:48.632 ThaliTest[758:701794] jxcore: disconnect
2015-12-11 12:16:48.633 ThaliTest[758:701794] jxcore: disconnect: fail
,2015-12-11T11:16:48.635Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:16:48.635Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status,: true
2015-12-11T11:16:48.636Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:16:48.636Z SendDataConnector.js: do connect now
2015-12-11 12:16:48.637 ThaliTest[758:701794] jxcore: connect Apple-IpadAir2-,1_PT2428.1YTBNQ==
2015-12-11 12:16:48.637 ThaliTest[758:701794] client session: connect
2015-12-11 12:16:48.637 ThaliTest[758:701794] client session: stateChange:0->1 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:48.651 ThaliTest[758:701428] client: lost peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:48.651 ThaliTest[758:701428] client session: onPeerLost: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:48.651 ThaliTest[758:701428] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:48.652 ThaliTest[758:701428] client session: disconnect
2015-12-11 12:16:48.652 ThaliTest[758:701428] client session: stateChange:1->0 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:48.708 ThaliTest[758:701428] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:48.709 ThaliTest[758:701428] jxcore: connect: fail: Peer disconnected
2015-12-11T11:16:48.710Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-11T11:16:48.710Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-11T11:16:48.710Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.1YTBNQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-11T11:16:53.721Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:53.722Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:57.428 ThaliTest[758:701428] multipeer session: reset timer
2015-12-11 12:16:57.429 ThaliTest[758:701428] multipeer session: stop timer
,2015-12-11 12:16:57.429 ThaliTest[758:701428] multipeer session: start timer: 0x18c2d5b0
,2015-12-11 12:16:57.431 ThaliTest[758:701428] server session: connect
2015-12-11 12:16:57.432 ThaliTest[758:701428] server session: stateChange:0->1 Apple-IpadAir2-1_PT2428
,2015-12-11 12:16:57.443 ThaliTest[758:701428] server: accepting invitation Apple-IpadAir2-1_PT2428
,2015-12-11 12:16:58.728 ThaliTest[758:701794] jxcore: disconnect
2015-12-11 12:16:58.729 ThaliTest[758:701794] jxcore: disconnect: fail
2015-12-11T11:16:58.729Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==,
2015-12-11T11:16:58.730Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
2015-12-11T11:16:58.730Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:58.730Z SendDataConnector.js: do connect now
2015-12-11 12:16:58.731 ThaliTest[758:701794] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:58.732 ThaliTest[758:701794] client: connect: unreachable Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:58.733 ThaliTest[758:701794] jxcore: connect: fail: Peer unreachable
2015-12-11T11:16:58.734Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T11:16:58.735Z SendDataConnector.js: CLIENT Can not Connect: Pee,r unreachable
oneRoundDownNow
2015-12-11T11:16:58.735Z SendDataConnector.js: CLIENT Stop now
2015-12-11T11:16:58.736Z SendDataConnector.js: Stop data retrieving timer
,2015-12-11 12:16:58.736 ThaliTest[758:701794] jxcore: disconnect
,2015-12-11 12:16:58.737 ThaliTest[758:701794] jxcore: disconnect: fail
2015-12-11T11:16:58.738Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:16:58.743Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:16:58.744Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:16:58.744Z SendDataConnector.js: do connect now
,2015-12-11 12:16:58.746 ThaliTest[758:701794] jxcore: connect Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:16:58.747 ThaliTest[758:701794] client session: connect
,2015-12-11 12:16:58.749 ThaliTest[758:701794] client session: stateChange:0->1 Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:16:58.765 ThaliTest[758:701428] client: lost peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:16:58.766 ThaliTest[758:701428] client session: onPeerLost: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:16:58.766 ThaliTest[758:701428] clien,t session: onLinkFailure: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:16:58.767 ThaliTest[758:701428] client session: disconnect
2015-12-11 12:16:58.767 ThaliTest[758:701428] client session: stateChange:1->0 Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:16:58.822 ThaliTest[758:701428] client session: fireConnectCallback: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:16:58.822 ThaliTest[758:701428] jxcore: connect: fail: Peer disconnected
2015-12-11T11:16:58.823Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-11T11:16:58.825Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-11T11:16:58.826Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.PHL+kA==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 12:17:00.138 ThaliTest[758:702610] server session: connected
,2015-12-11 12:17:00.139 ThaliTest[758:702610] server session: stateChange:1->2 Apple-IpadAir2-1_PT2428
,2015-12-11T11:17:00.149Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11 12:17:00.152 ThaliTest[758:701428] server relay: connected (to port: 56661)
,2015-12-11T11:17:00.402Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-11T11:17:00.418Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-11T11:17:00.440Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-11T11:17:00.457Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-11T11:17:00.479Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-11T11:17:00.494Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 12:17:00.510 ThaliTest[758:702607] server session: not connected Apple-IpadAir2-1_PT2428
,2015-12-11T11:17:03.837Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:17:03.838Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:04.625 ThaliTest[758:701428] multipeer session: reset timer
2015-12-11 12:17:04.625 ThaliTest[758:701428] multipeer session: stop timer
2015-12-11 12:17:04.625 ThaliTest[758:701428] multipeer session: start timer: 0x18c2d5b0
2015-12-11 ,12:17:04.626 ThaliTest[758:701428] server session: connect
2015-12-11 12:17:04.626 ThaliTest[758:701428] server session: stateChange:0->1 Apple-Iphone6-1_PT2932
,2015-12-11 12:17:04.638 ThaliTest[758:701428] server: accepting invitation Apple-Iphone6-1_PT2932
,2015-12-11 12:17:07.436 ThaliTest[758:702607] server session: connected
2015-12-11 12:17:07.437 ThaliTest[758:702607] server session: stateChange:1->2 Apple-Iphone6-1_PT2932
,2015-12-11 12:17:07.500 ThaliTest[758:701428] server relay: connected (to port: 56661)
,2015-12-11T11:17:07.501Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T11:17:07.773Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-11T11:17:07.792Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
2015-12-11T11:17:07.813Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-11T11:17:07.832Z SendDataTCPServer.js: TCP/IP server has received 82794 bytes of data
,2015-12-11T11:17:07.849Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-11T11:17:07.865Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 12:17:07.922 ThaliTest[758:702604] server session: not connected Apple-Iphone6-1_PT2932
,2015-12-11 12:17:08.851 ThaliTest[758:701794] jxcore: disconnect
2015-12-11 12:17:08.852 ThaliTest[758:701794] jxcore: disconnect: fail
2015-12-11T11:17:08.852Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2932.PHL+kA==,
2015-12-11T11:17:08.853Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT2932.PHL+kA== with availability status: true
2015-12-11T11:17:08.853Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:17:08.853Z SendDataConnector.js: do connect now
2015-12-11 12:17:08.854 ThaliTest[758:701794] jxcore: connect Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:08.855 ThaliTest[758:701794] client: connect: unreachable Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:08.856 ThaliTest[758:701794] jxcore: connect: fail: Peer unreachable
,2015-12-11T11:17:08.857Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T11:17:08.858Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T11:17:08.858Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:17:13.868Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:17:13.868Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:18.880 ThaliTest[758:701794] jxcore: disconnect
2015-12-11 12:17:18.881 ThaliTest[758:701794] jxcore: disconnect: fail
2015-12-11T11:17:18.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2932.PHL+kA==,
2015-12-11T11:17:18.882Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT2932.PHL+kA== with availability status: true
2015-12-11T11:17:18.882Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:17:18.882Z SendDataConnector.js: do connect now
2015-12-11 12:17:18.883 ThaliTest[758:701794] jxcore: connect Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:18.884 ThaliTest[758:701794] client: connect: unreachable Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:17:18.885 ThaliTest[758:701794] jxcore: connect: fail: Peer unreachable
2015-12-11T11:17:18.885Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-11T11:17:18.886Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T11:17:18.886Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:17:23.894Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:17:23.894Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:27.690 ThaliTest[758:701428] multipeer session: reset timer
2015-12-11 12:17:27.691 ThaliTest[758:701428] multipeer session: stop timer
2015-12-11 12:17:27.691 ThaliTest[758:701428] multipeer session: start timer: 0x18c2d5b0
2015-12-11 ,12:17:27.692 ThaliTest[758:701428] server session: connect
2015-12-11 12:17:27.692 ThaliTest[758:701428] server session: stateChange:0->1 Apple-Iphone5-1_PT2684
,2015-12-11 12:17:27.703 ThaliTest[758:701428] server: accepting invitation Apple-Iphone5-1_PT2684
,2015-12-11 12:17:28.904 ThaliTest[758:701794] jxcore: disconnect
2015-12-11 12:17:28.904 ThaliTest[758:701794] jxcore: disconnect: fail
2015-12-11T11:17:28.905Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2932.PHL+kA==,
2015-12-11T11:17:28.905Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT2932.PHL+kA== with availability status: true
2015-12-11T11:17:28.906Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2932.PHL+kA==
2015-,12-11T11:17:28.906Z SendDataConnector.js: do connect now
,2015-12-11 12:17:28.907 ThaliTest[758:701794] jxcore: connect Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:17:28.908 ThaliTest[758:701794] client: connect: unreachable Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:28.908 ThaliTest[758:701794] jxcore: connect: fail: Peer unreachable
,2015-12-11T11:17:28.910Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-11T11:17:28.911Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T11:17:28.911Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11 12:17:31.354 ThaliTest[758:702718] server session: connected
2015-12-11 12:17:31.354 ThaliTest[758:702718] server session: stateChange:1->2 Apple-Iphone5-1_PT2684
,2015-12-11 12:17:31.361 ThaliTest[758:701428] server relay: connected (to port: 56661)
2015-12-11T11:17:31.364Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T11:17:31.877Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-11T11:17:31.898Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-11T11:17:31.915Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-11T11:17:31.944Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-11T11:17:31.985Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-11T11:17:32.001Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-11T11:17:32.016Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 12:17:32.069 ThaliTest[758:702719] server session: not connected Apple-Iphone5-1_PT2684
,2015-12-11T11:17:33.921Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:17:33.922Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:38.926 ThaliTest[758:701794] jxcore: disconnect
2015-12-11 12:17:38.926 ThaliTest[758:701794] jxcore: disconnect: fail
2015-12-11T11:17:38.927Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2932.PHL+kA==,
2015-12-11T11:17:38.927Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT2932.PHL+kA== with availability status: true
2015-12-11T11:17:38.928Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:17:38.928Z SendDataConnector.js: do connect now
2015-12-11 12:17:38.929 ThaliTest[758:701794] jxcore: connect Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:38.930 ThaliTest[758:701794] client: connect: unreachable Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:38.930 ThaliTest[758:701794] jxcore: connect: fail: Peer unreachable
,2015-12-11T11:17:38.932Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T11:17:38.932Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-11T11:17:38.933Z SendDataConnector.js: CLIENT Stop now
2015-12-11 12:17:38.934 ThaliTest[758:701794] jxcore: disconnect
,2015-12-11 12:17:38.934 ThaliTest[758:701794] jxcore: disconnect: fail
2015-12-11T11:17:38.935Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2932.PHL+kA==
,---- round done--------
startWithNextDevice
,2015-12-11 12:17:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:17:57.744 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:17:57.745 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:17:57.746 ThaliTest[758:701428] client: foun,d peer: Apple-IpadAir2-1_PT2428.ucnEeA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.PHL+kA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.ucnE,eA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[4]: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11T11:17:57.757Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11T11:17:57.757Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11T11:17:57.758Z SendDataConnector.j,s: do connect now
2015-12-11 12:17:57.759 ThaliTest[758:701794] jxcore: connect Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:17:57.760 ThaliTest[758:701794] client session: connect
2015-12-11 12:17:57.761 ThaliTest[758:701794] client session: stateCha,nge:0->1 Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:18:01.240 ThaliTest[758:702795] client session: connected
2015-12-11 12:18:01.242 ThaliTest[758:702795] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:18:01.246 ThaliTest[758:702795] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:18:01.247 ThaliTest[758:702795] jxcore: connect: success
2015-12-11T11:18:01.248Z SendDataConnector.js: CLIENT connected to 56687, error: null
2015-12-11T11:18:01.248Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:18:01.254 ThaliTest[758:701428] client: relay established
2015-12-11 12:18:01.254 ThaliTest[758:701428] client: new accepted socket: 0x18c4d5c0
,2015-12-11T11:18:01.267Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:18:01.594Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T11:18:01.606Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T11:18:01.797Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T11:18:01.797Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T11:18:01.798Z SendDataConnector.js: CLIENT Stop now
2015-12-11T11:18:01.798Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:18:01.799 ThaliTest[758:701794] jxcore: disconnect
,2015-12-11 12:18:01.800 ThaliTest[758:701794] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:18:01.800 ThaliTest[758:701794] client session: disconnect
,2015-12-11 12:18:01.801 ThaliTest[758:701794] client session: stateChange:2->0 Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:18:01.871 ThaliTest[758:701794] jxcore: disconnect: success
,2015-12-11T11:18:01.872Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.ucnEeA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-11T11:18:01.878Z SendDataConnector.js: CLIENT Stop now
2015-12-11T11:18:01.878Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:18:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:18:27.743 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:18:27.744 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:18:27.746 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:18:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:19:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:19:27.740 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:19:27.741 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:19:27.743 ThaliTest[758:701428] client: foun,d peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:19:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:19:57.745 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:19:57.745 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:19:57.748 ThaliTest[758:701428] client: foun,d peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:20:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:20:27.748 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:20:27.748 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:20:27.749 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:20:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:20:57.747 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:20:57.756 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:20:58.357 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:21:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:21:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:21:57.744 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:21:57.745 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:21:57.756 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:22:22.637 ThaliTest[758:701428] client: lost peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:22:22.637 ThaliTest[758:701428] client session: onPeerLost: Apple-IpadAir2-1_PT2428.ucnEeA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT2428.ucnEeA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-11 12:22:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:22:27.730 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:22:27.733 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:22:32.498 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.ucnEeA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,appEnteringBackground wasn't registered
,2015-12-11 12:22:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:23:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:23:27.745 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:23:27.747 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:23:27.752 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,Connected to the server!
,2015-12-11 12:23:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:24:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:24:27.742 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:24:27.743 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:24:27.750 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:24:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:24:57.743 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:24:57.744 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:24:57.754 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:25:27.692 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:25:27.750 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:25:27.751 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:25:27.751 ThaliTest[758:701428] client: foun,d peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:25:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:26:27.692 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:26:27.740 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:26:27.740 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:26:27.749 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:26:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:26:57.744 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:26:57.748 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:26:57.748 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:27:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:27:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:27:57.742 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:27:57.743 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:27:57.745 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:28:27.692 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:28:27.744 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:28:27.745 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:28:27.746 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:28:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:28:57.747 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:28:57.748 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:28:57.749 ThaliTest[758:701428] client: fou,nd peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:29:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:29:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:29:57.747 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:29:57.748 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:29:57.750 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:30:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:30:27.745 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:30:27.746 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:30:27.748 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:30:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:30:57.746 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:30:57.747 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:30:57.756 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:31:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:31:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:31:57.747 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:31:57.748 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:31:57.748 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:32:27.692 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:32:27.745 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:32:27.746 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:32:27.746 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:32:57.692 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:32:57.749 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:32:57.750 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:32:59.279 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:33:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:33:27.745 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:33:27.746 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:33:27.747 ThaliTest[758:701428] client: fou,nd peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:33:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:34:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:34:27.747 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:34:27.747 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:34:27.751 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:34:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:34:57.743 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:34:57.744 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:34:57.758 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:35:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:35:57.692 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:35:57.746 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:35:57.747 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:35:57.754 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:36:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:36:27.742 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:36:27.746 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:36:27.747 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:36:57.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:36:57.751 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:36:57.752 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:36:57.752 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:37:27.693 ThaliTest[758:701428] multipeer session: restart
,2015-12-11 12:37:27.750 ThaliTest[758:701428] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:37:27.751 ThaliTest[758:701428] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:37:27.756 ThaliTest[758:701428] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==

```
