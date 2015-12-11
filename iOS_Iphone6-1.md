#### Test 5065027857de7f1_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/D4F60EE0-E18C-4F05-AFD3-0C978AD94B1B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D4F60EE0-E18C-4F05-AFD3-0C978AD94B1B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AD2F420E-E6F6-456C-878D-0ED184878139/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54041"
,(lldb)     command script import "/tmp/D4F60EE0-E18C-4F05-AFD3-0C978AD94B1B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 12:10:22.100 ThaliTest[755:701810] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AAB06C45-BC8B-495E-9190-0B57BFAE805C/Library/Cookies/Cookies.binarycookies
,2015-12-11 12:10:22.514 ThaliTest[755:701810] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 12:10:22.515 ThaliTest[755:701810] Multi-tasking -> Device: YES, App: YES
,2015-12-11 12:10:22.521 ThaliTest[755:701810] Unlimited access to network resources
,2015-12-11 12:10:22.536 ThaliTest[755:701810] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 12:10:31.719 ThaliTest[755:701810] Resetting plugins due to page load.
,2015-12-11 12:10:35.288 ThaliTest[755:701810] Finished load of: file:///var/mobile/Containers/Bundle/Application/AD2F420E-E6F6-456C-878D-0ED184878139/ThaliTest.app/www/index.html
,2015-12-11 12:10:35.472 ThaliTest[755:701810] JXcore Cordova plugin initializing
2015-12-11 12:10:35.474 ThaliTest[755:702152] JXcore instance initializing
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
,2015-12-11 12:10:36.549 ThaliTest[755:701810] THREAD WARNING: ['JXcore'] took '78.206055' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-11 12:15:25.956 ThaliTest[755:702152] jxcore: startBroadcasting
,2015-12-11 12:15:25.972 ThaliTest[755:702152] server: starting Apple-Iphone6-1_PT2932.QOwtzQ==
2015-12-11 12:15:25.974 ThaliTest[755:702152] multipeer session: start timer: 0x16bab890
2015-12-11 12:15:25.974 ThaliTest[755:702152] THEMultipeerSession initialized peer Apple-Iphone6-1_PT2932
,2015-12-11 12:15:25.979 ThaliTest[755:702152] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-11 12:15:27.010 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.1YTBNQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT2428.1YTBNQ==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2015-12-11 12:15:29.654 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.IK91fw==
,teardown
,testFindPeers stopped
,2015-12-11 12:15:29.976 ThaliTest[755:702152] jxcore: stopBroadcasting
2015-12-11 12:15:29.976 ThaliTest[755:702152] THEMultipeerSession stopping peer
2015-12-11 12:15:29.976 ThaliTest[755:702152] multipeer session: stop timer
2015-12-11 12:15:29.977 Th,aliTest[755:702152] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 56475
,2015-12-11 12:15:30.048 ThaliTest[755:702152] jxcore: startBroadcasting
,2015-12-11 12:15:30.050 ThaliTest[755:702152] server: starting Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:15:30.051 ThaliTest[755:702152] multipeer session: start timer: 0x16cb1250
2015-12-11 12:15:30.051 ThaliTest[755:702152] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT2932
2015-12-11 12:15:30.052 ThaliTest[755:702152] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-11T11:15:30.054Z SendDataTCPServer.js: TCP/IP server is bound to port: 56475
,2015-12-11 12:15:31.023 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:15:31.025 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.IK91fw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAi,r2-1_PT2428.1YTBNQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:15:31.028Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1,_PT2428.1YTBNQ==
,2015-12-11T11:15:31.029Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:15:31.030Z SendDataConnector.js: do connect now
2015-12-11 12:15:31.031 ThaliTest[755:702152] jxcore: connect Apple-IpadAir2-1_PT2428,.1YTBNQ==
2015-12-11 12:15:31.031 ThaliTest[755:702152] client session: connect
2015-12-11 12:15:31.032 ThaliTest[755:702152] client session: stateChange:0->1 Apple-IpadAir2-1_PT2428.1YTBNQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8695.IK91fw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 12:15:33.450 ThaliTest[755:701810] client: lost peer: Apple-Iphone5s-1_PT8695.IK91fw==
2015-12-11 12:15:33.450 ThaliTest[755:701810] client session: onPeerLost: Apple-Iphone5s-1_PT8695.IK91fw==
2015-12-11 12:15:33.452 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8695.IK91fw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8695.iCr2Pw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 12:15:33.896 ThaliTest[755:702669] client session: connected
2015-12-11 12:15:33.896 ThaliTest[755:702669] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:15:33.905 ThaliTest[755:702669] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:15:33.906 ThaliTest[755:702669] jxcore: connect: success
,2015-12-11T11:15:33.908Z SendDataConnector.js: CLIENT connected to 56484, error: null
2015-12-11T11:15:33.909Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:15:33.912 ThaliTest[755:701810] client: relay established
2015-12-11 12:15:33.912 ThaliTest[755:701810] client: new accepted socket: 0x16cb67d0
,2015-12-11T11:15:33.928Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 12:15:37.075 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2684.BiXlYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11T11:15:44.193Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T11:15:44.194Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:15:44.196Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:15:44.197Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:15:44.198Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11 12:15:44.200 ThaliTest[755:701810] client: socket closed
2015-12-11 12:15:44.200 ThaliTest[755:701810] client relay: socket disconnected
2015-12-11 12:15:44.200 ThaliTest[755:701810] client relay: 0x16cb67d0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-11 12:15:44.201 ThaliTest[755:701810] client session: socket closed: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:,15:44.201 ThaliTest[755:701810] client session: onLinkFailure: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:15:44.201 ThaliTest[755:701810] client session: disconnect
2015-12-11 12:15:44.201 ThaliTest[755:701810] client session: stateChange:2->0 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:15:44.208 ThaliTest[755:701810] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:15:49.203Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:15:49.204Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:15:54.209 ThaliTest[755:702152] jxcore: disconnect
2015-12-11 12:15:54.210 ThaliTest[755:702152] jxcore: disconnect: fail
2015-12-11T11:15:54.211Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:15:54.212Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
,2015-12-11T11:15:54.212Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:15:54.212Z SendDataConnector.js: do connect now
,2015-12-11 12:15:54.214 ThaliTest[755:702152] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:15:54.214 ThaliTest[755:702152] client session: connect
2015-12-11 12:15:54.215 ThaliTest[755:702152] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT2428.1YTBNQ==
,2015-12-11 12:15:57.074 ThaliTest[755:702790] client session: connected
2015-12-11 12:15:57.074 ThaliTest[755:702790] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:15:57.078 ThaliTest[755:702790] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:15:57.080 ThaliTest[755:702790] jxcore: connect: success
2015-12-11T11:15:57.081Z SendDataConnector.js: CLIENT connected to ,56489, error: null
2015-12-11T11:15:57.081Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:15:57.087 ThaliTest[755:701810] client: relay established
2015-12-11 12:15:57.088 ThaliTest[755:701810] client: new accepted socket: 0x16cc4720
,2015-12-11T11:15:57.100Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 12:16:00.052 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:16:00.092 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:00.094 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:16:00.095 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11T11:16:07.341Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T11:16:07.341Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:07.342Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:07.343Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:16:07.344Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11 12:16:07.346 ThaliTest[755:701810] client: socket closed
2015-12-11 12:16:07.346 ThaliTest[755:701810] client relay: socket disconnected
2015-12-11 12:16:07.346 ThaliTest[755:701810] client relay: 0x16cc4720 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-11 12:16:07.347 ThaliTest[755:701810] client session: socket closed: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:,16:07.347 ThaliTest[755:701810] client session: onLinkFailure: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:07.347 ThaliTest[755:701810] client session: disconnect
2015-12-11 12:16:07.347 ThaliTest[755:701810] client session: stateChange:2->0 Apple-,IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:07.355 ThaliTest[755:701810] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:12.347Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:12.348Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:16.344 ThaliTest[755:701810] client: lost peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:16:16.344 ThaliTest[755:701810] client session: onPeerLost: Apple-Iphone5-1_PT2684.BiXlYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT2684.BiXlYA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-11 12:16:16.939 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2684.BiXlYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 12:16:17.360 ThaliTest[755:702152] jxcore: disconnect
2015-12-11 12:16:17.361 ThaliTest[755:702152] jxcore: disconnect: fail
2015-12-11T11:16:17.361Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==,
2015-12-11T11:16:17.362Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
2015-12-11T11:16:17.362Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:16:17.362Z SendDataConnector.js: do connect now
,2015-12-11 12:16:17.363 ThaliTest[755:702152] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:17.364 ThaliTest[755:702152] client session: connect
,2015-12-11 12:16:17.365 ThaliTest[755:702152] client session: stateChange:0->1 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:20.753 ThaliTest[755:702868] client session: connected
2015-12-11 12:16:20.754 ThaliTest[755:702868] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:20.758 ThaliTest[755:702868] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:20.758 ThaliTest[755:702868] jxcore: connect: success
2015-12-11T11:16:20.760Z SendDataConnector.js: CLIENT connected to 56493, error: null
2015-12-11T11:16:20.761Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:16:20.763 ThaliTest[755:701810] client: relay established
,2015-12-11 12:16:20.765 ThaliTest[755:701810] client: new accepted socket: 0x16bb8a80
,2015-12-11T11:16:20.777Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 12:16:30.052 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:16:30.095 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:16:30.095 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:31.034Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T11:16:31.035Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:31.036Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:31.036Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:16:31.038Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11 12:16:31.039 ThaliTest[755:701810] client: socket closed
2015-12-11 12:16:31.040 ThaliTest[755:701810] client relay: socket disconnected
2015-12-11 12:16:31.040 ThaliTest[755:701810] client relay: 0x16bb8a80 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-11 12:16:31.040 ThaliTest[755:701810] client session: socket closed: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:,16:31.041 ThaliTest[755:701810] client session: onLinkFailure: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:31.041 ThaliTest[755:701810] client session: disconnect
2015-12-11 12:16:31.041 ThaliTest[755:701810] client session: stateChange:2->0 Apple-,IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:31.050 ThaliTest[755:701810] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:36.045Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:36.045Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:41.047 ThaliTest[755:702152] jxcore: disconnect
2015-12-11 12:16:41.047 ThaliTest[755:702152] jxcore: disconnect: fail
2015-12-11T11:16:41.048Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==,
2015-12-11T11:16:41.048Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
2015-12-11T11:16:41.048Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:41.049Z SendDataConnector.js: do connect now
,2015-12-11 12:16:41.050 ThaliTest[755:702152] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:41.051 ThaliTest[755:702152] client session: connect
2015-12-11 12:16:41.051 ThaliTest[755:702152] client session: stateChange:0->1 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:41.654 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:16:43.870 ThaliTest[755:702921] client session: connected
,2015-12-11 12:16:43.871 ThaliTest[755:702921] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:43.876 ThaliTest[755:702921] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:43.877 ThaliTest[755:702921] jxcore: connect: success
,2015-12-11T11:16:43.878Z SendDataConnector.js: CLIENT connected to 56498, error: null
,2015-12-11T11:16:43.880Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:16:43.884 ThaliTest[755:701810] client: relay established
2015-12-11 12:16:43.884 ThaliTest[755:701810] client: new accepted socket: 0x16cc72d0
,2015-12-11T11:16:43.894Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 12:16:48.358 ThaliTest[755:702921] client session: not connected Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:48.359 ThaliTest[755:702921] client session: onLinkFailure: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:48.359 ThaliTest[755:702921] client session: disconnect
2015-12-11 12:16:48.362 ThaliTest[755:702921] client session: stateChange:2->0 Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:48.364 ThaliTest[755:702921] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:49.549 ThaliTest[755:701810] multipeer session: reset timer
2015-12-11 12:16:49.550 ThaliTest[755:701810] multipeer session: stop timer
2015-12-11 12:16:49.550 ThaliTest[755:701810] multipeer session: start timer: 0x16cb1250
2015-12-11 ,12:16:49.550 ThaliTest[755:701810] server session: connect
2015-12-11 12:16:49.551 ThaliTest[755:701810] server session: stateChange:0->1 Apple-IpadAir2-1_PT2428
,2015-12-11 12:16:49.560 ThaliTest[755:701810] server: accepting invitation Apple-IpadAir2-1_PT2428
,2015-12-11 12:16:49.928 ThaliTest[755:701810] client: lost peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:49.928 ThaliTest[755:701810] client session: onPeerLost: Apple-IpadAir2-1_PT2428.1YTBNQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.1YTBNQ==","peerName":"(null)","peerAvailable":false}]
2015-12-11 12:16:49.929 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.ucnEeA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 12:16:52.196 ThaliTest[755:702923] server session: connected
,2015-12-11 12:16:52.197 ThaliTest[755:702923] server session: stateChange:1->2 Apple-IpadAir2-1_PT2428
,2015-12-11 12:16:52.204 ThaliTest[755:701810] server relay: connected (to port: 56475)
2015-12-11T11:16:52.209Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T11:16:52.512Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-11T11:16:52.529Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-11T11:16:52.546Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-11T11:16:52.560Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-11T11:16:52.575Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 12:16:52.621 ThaliTest[755:702918] server session: not connected Apple-IpadAir2-1_PT2428
,2015-12-11T11:16:54.136Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T11:16:54.136Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:54.137Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:54.138Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:16:54.139Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11T11:16:59.143Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:59.143Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:59.144Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:04.148 ThaliTest[755:702152] jxcore: disconnect
2015-12-11 12:17:04.149 ThaliTest[755:702152] jxcore: disconnect: fail
2015-12-11T11:17:04.149Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==,
2015-12-11T11:17:04.150Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
2015-12-11T11:17:04.150Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:17:04.150Z SendDataConnector.js: do connect now
,2015-12-11 12:17:04.151 ThaliTest[755:702152] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:17:04.152 ThaliTest[755:702152] client: connect: unreachable Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:17:04.153 ThaliTest[755:702152] jxcore: connect: fail: Peer unreachable
2015-12-11T11:17:04.153Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-11T11:17:04.154Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T11:17:04.154Z SendDataConnector.js: CLIENT closeClientSocket
,oneRoundDownNow
,2015-12-11T11:17:04.157Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T11:17:04.157Z SendDataConnector.js: Stop data retrieving timer
,2015-12-11T11:17:04.158Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:04.160 ThaliTest[755:702152] jxcore: disconnect
,2015-12-11 12:17:04.161 ThaliTest[755:702152] jxcore: disconnect: fail
2015-12-11T11:17:04.161Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11T11:17:04.165Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11T11:17:04.166Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11T11:17:04.166Z SendDataConnector.js: do connect now
,2015-12-11 12:17:04.168 ThaliTest[755:702152] jxcore: connect Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:17:04.168 ThaliTest[755:702152] client session: connect
2015-12-11 12:17:04.168 ThaliTest[755:702152] client session: stateChange:0->1 Apple-Ipho,ne5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:07.463 ThaliTest[755:702923] client session: connected
2015-12-11 12:17:07.464 ThaliTest[755:702923] client session: stateChange:1->2 Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:07.468 ThaliTest[755:702923] client session: fireConnectCallback: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:17:07.469 ThaliTest[755:702923] jxcore: connect: success
2015-12-11T11:17:07.470Z SendDataConnector.js: CLIENT connected to ,56502, error: null
2015-12-11T11:17:07.470Z SendDataConnector.js: CLIENT starting client 
2015-12-11 12:17:07.473 ThaliTest[755:701810] client: relay established
2015-12-11 12:17:07.473 ThaliTest[755:701810] client: new accepted socket: 0x16bc8b30
,2015-12-11T11:17:07.486Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:17:07.847Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T11:17:07.910Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T11:17:07.911Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-11T11:17:07.911Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T11:17:07.911Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:07.912 ThaliTest[755:702152] jxcore: disconnect
2015-12-11 12:17:07.912 ThaliTest[755:702152] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:17:07.912 ThaliTest[755:702152] client session: disconnect
,2015-12-11 12:17:07.912 ThaliTest[755:702152] client session: stateChange:2->0 Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:07.918 ThaliTest[755:702152] jxcore: disconnect: success
2015-12-11T11:17:07.918Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8695.iCr2Pw==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11T11:17:07.918Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11T11:17:07.919Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11T11:17:,07.919Z SendDataConnector.js: do connect now
2015-12-11 12:17:07.919 ThaliTest[755:702152] jxcore: connect Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:17:07.919 ThaliTest[755:702152] client session: connect
2015-12-11 12:17:07.919 ThaliTest[755:702152,] client session: stateChange:0->1 Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:17:11.136 ThaliTest[755:702941] client session: connected
2015-12-11 12:17:11.136 ThaliTest[755:702941] client session: stateChange:1->2 Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:17:11.150 ThaliTest[755:702923] client session: fireConnectCallback: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:17:11.150 ThaliTest[755:702923] jxcore: connect: success
2015-12-11T11:17:11.152Z SendDataConnector.js: CLIENT connected to 5,6505, error: null
2015-12-11T11:17:11.152Z SendDataConnector.js: CLIENT starting client 
2015-12-11 12:17:11.155 ThaliTest[755:701810] client: relay established
2015-12-11 12:17:11.155 ThaliTest[755:701810] client: new accepted socket: 0x16ccbab0
,2015-12-11T11:17:11.167Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:17:11.460Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-11T11:17:11.483Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-11T11:17:11.520Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T11:17:11.520Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-11T11:17:11.521Z SendDataConnector.js: CLIENT Stop now
2015-12-11T11:17:11.521Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:11.521 ThaliTest[755:702152] jxcore: disconnect
2015-12-11 12:17:11.521 ThaliTest[755:702152] client session: disconnectFromPeer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:17:11.521 ThaliTest[755:702152] client session: disconnect
2015-12-11 12:17:11.522 ThaliTest[755:702152] client session: stateChange:2->0 Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:17:11.525 ThaliTest[755:702152] jxcore: disconnect: success
2015-12-11T11:17:11.526Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2684.BiXlYA==
---- round done--------
startWithNextDevice
device[4]: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11T11:17:11.526Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11T11:17:11.526Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11T11:1,7:11.526Z SendDataConnector.js: do connect now
2015-12-11 12:17:11.526 ThaliTest[755:702152] jxcore: connect Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:17:11.526 ThaliTest[755:702152] client session: connect
2015-12-11 12:17:11.528 ThaliTest[755:702152] client session: stateChange:0->1 Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:17:15.112 ThaliTest[755:702918] client session: connected
2015-12-11 12:17:15.113 ThaliTest[755:702918] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:17:15.121 ThaliTest[755:702941] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:17:15.121 ThaliTest[755:702941] jxcore: connect: success
2015-12-11T11:17:15.122Z SendDataConnector.js: CLIENT connected to 56508, error: null
2015-12-11T11:17:15.123Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:17:15.127 ThaliTest[755:701810] client: relay established
2015-12-11 12:17:15.127 ThaliTest[755:701810] client: new accepted socket: 0x15553030
,2015-12-11T11:17:15.140Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:17:15.548Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T11:17:15.584Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T11:17:15.584Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-11T11:17:15.585Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T11:17:15.585Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:15.585 ThaliTest[755:702152] jxcore: disconnect
2015-12-11 12:17:15.585 ThaliTest[755:702152] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:17:15.585 ThaliTest[755:702152] client session: disconnect
,2015-12-11 12:17:15.586 ThaliTest[755:702152] client session: stateChange:2->0 Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:17:15.590 ThaliTest[755:702152] jxcore: disconnect: success
2015-12-11T11:17:15.590Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.ucnEeA==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2015-12-11T11:17:15.594Z SendDataConnector.js: CLIENT Stop now
2015-12-11T11:17:15.594Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:19.551 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:17:19.593 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:17:19.593 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:17:19.594 ThaliTest[755:701810] client: fo,und peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:17:20.563 ThaliTest[755:701810] multipeer session: reset timer
2015-12-11 12:17:20.564 ThaliTest[755:701810] multipeer session: stop timer
2015-12-11 12:17:20.564 ThaliTest[755:701810] multipeer session: start timer: 0x16cb1250
2015-12-11 12:17:20.565 ThaliTest[755:701810] server session: connect
2015-12-11 12:17:20.565 ThaliTest[755:701810] server session: stateChange:0->1 Apple-Iphone5-1_PT2684
,2015-12-11 12:17:20.577 ThaliTest[755:701810] server: accepting invitation Apple-Iphone5-1_PT2684
,2015-12-11 12:17:21.857 ThaliTest[755:702918] server session: connected
2015-12-11 12:17:21.858 ThaliTest[755:702918] server session: stateChange:1->2 Apple-Iphone5-1_PT2684
,2015-12-11 12:17:22.025 ThaliTest[755:701810] server relay: connected (to port: 56475)
,2015-12-11T11:17:22.033Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T11:17:22.641Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-11T11:17:22.704Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-11T11:17:22.831Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-11T11:17:22.908Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-11T11:17:22.957Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-11T11:17:22.973Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-11T11:17:23.113Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-11T11:17:23.298Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-11T11:17:23.423Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-11T11:17:23.438Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-11T11:17:23.501Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-11T11:17:23.767Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-11T11:17:23.893Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-11T11:17:24.078Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-11T11:17:24.154Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-11T11:17:24.372Z SendDataTCPServer.js: TCP/IP server has received 34898 bytes of data
,2015-12-11T11:17:24.385Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-11T11:17:24.488Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-11T11:17:24.675Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-11T11:17:24.914Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-11T11:17:24.929Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-11T11:17:25.065Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-11T11:17:25.200Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-11T11:17:25.388Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-11T11:17:25.402Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-11T11:17:25.452Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-11T11:17:25.580Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-11T11:17:25.641Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-11T11:17:25.692Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-11T11:17:25.707Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-11T11:17:25.755Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-11T11:17:25.768Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-11T11:17:25.967Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-11T11:17:25.994Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-11T11:17:26.181Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-11T11:17:26.381Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-11T11:17:26.648Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-11T11:17:26.874Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-11T11:17:26.901Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-11T11:17:26.954Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-11T11:17:26.968Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-11T11:17:27.094Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 12:17:27.148 ThaliTest[755:702941] server session: not connected Apple-Iphone5-1_PT2684
,2015-12-11 12:17:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:18:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:18:20.603 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:18:20.605 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:18:20.606 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:18:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:18:50.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:18:50.603 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:18:51.956 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:19:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:19:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:19:50.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:19:50.604 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:19:50.606 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:20:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:20:20.601 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:20:20.603 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:20:20.604 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:20:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:20:50.605 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:20:50.605 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:20:50.607 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:21:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:21:20.603 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:21:20.607 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:21:20.609 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:21:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:21:50.606 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:21:50.606 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:21:50.607 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:22:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:22:20.606 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:22:20.606 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:22:20.609 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:22:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:22:50.607 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:22:50.609 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:22:50.609 ThaliTest[755:701810] client: fou,nd peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,Connected to the server!
,2015-12-11 12:23:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:23:20.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:23:20.605 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:23:20.605 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:23:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:24:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:24:20.601 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:24:20.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:24:20.603 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:24:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:24:50.606 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:24:50.606 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:24:50.609 ThaliTest[755:701810] client: fou,nd peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:25:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:25:20.601 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:25:20.602 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:25:20.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:25:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:26:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:26:20.601 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:26:20.602 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:26:21.034 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:26:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:26:50.601 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:26:50.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:26:50.608 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:27:20.565 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:27:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:27:50.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:27:50.603 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:27:50.604 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:28:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:28:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:28:50.603 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:28:50.603 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:28:50.604 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:29:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:29:20.603 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:29:20.604 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:29:20.609 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:29:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:30:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:30:20.601 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:30:20.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:30:20.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:30:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:31:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:31:20.600 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:31:20.604 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:31:20.605 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:31:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:31:50.604 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:31:50.607 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:31:50.608 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:32:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:32:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:32:50.600 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:32:50.601 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:32:51.001 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:33:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:33:20.603 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:33:20.604 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:33:20.604 ThaliTest[755:701810] client: fou,nd peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:33:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:34:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:34:20.601 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:34:20.601 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:34:20.603 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:34:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:35:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:35:20.601 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:35:20.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:35:20.603 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:35:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:35:50.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:35:50.604 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:35:50.604 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:36:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:36:20.603 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:36:20.605 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:36:20.605 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:36:50.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:36:50.602 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:36:50.605 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:36:50.606 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:37:20.566 ThaliTest[755:701810] multipeer session: restart
,2015-12-11 12:37:20.603 ThaliTest[755:701810] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:37:20.604 ThaliTest[755:701810] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:37:20.607 ThaliTest[755:701810] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==

```
