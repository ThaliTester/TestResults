#### Test 5065027857de7f1_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C3986020-525B-472A-B1B1-1DCA0B0F8204/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/C3986020-525B-472A-B1B1-1DCA0B0F8204/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BD7E5E56-DF4D-4388-9CE2-DBEFEEF38620/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54004"
,(lldb)     command script import "/tmp/C3986020-525B-472A-B1B1-1DCA0B0F8204/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 12:09:02.600 ThaliTest[646:797005] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DE46AA91-4F79-42B5-ACF2-B07C04205737/Library/Cookies/Cookies.binarycookies
,2015-12-11 12:09:03.099 ThaliTest[646:797005] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 12:09:03.100 ThaliTest[646:797005] Multi-tasking -> Device: YES, App: YES
,2015-12-11 12:09:03.107 ThaliTest[646:797005] Unlimited access to network resources
,2015-12-11 12:09:03.120 ThaliTest[646:797005] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 12:09:13.586 ThaliTest[646:797005] Resetting plugins due to page load.
,2015-12-11 12:09:17.295 ThaliTest[646:797005] Finished load of: file:///var/mobile/Containers/Bundle/Application/BD7E5E56-DF4D-4388-9CE2-DBEFEEF38620/ThaliTest.app/www/index.html
,2015-12-11 12:09:17.504 ThaliTest[646:797005] JXcore Cordova plugin initializing
,2015-12-11 12:09:17.506 ThaliTest[646:797201] JXcore instance initializing
Initializing JXcore engine
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
,2015-12-11 12:09:19.972 ThaliTest[646:797005] THREAD WARNING: ['JXcore'] took '153.859863' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-11 12:15:25.856 ThaliTest[646:797201] jxcore: startBroadcasting
,2015-12-11 12:15:25.869 ThaliTest[646:797201] server: starting Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11 12:15:25.870 ThaliTest[646:797201] multipeer session: start timer: 0x1c3dbfc0
2015-12-11 12:15:25.871 ThaliTest[646:797201] THEMultipeerSession initialized peer Apple-Iphone5-1_PT2684
,2015-12-11 12:15:25.872 ThaliTest[646:797201] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-11 12:15:27.026 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.1YTBNQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT2428.1YTBNQ==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-11 12:15:27.645 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.QOwtzQ==
,2015-12-11 12:15:29.669 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.IK91fw==
,teardown
,testFindPeers stopped
,2015-12-11 12:15:29.990 ThaliTest[646:797201] jxcore: stopBroadcasting
2015-12-11 12:15:29.990 ThaliTest[646:797201] THEMultipeerSession stopping peer
2015-12-11 12:15:29.991 ThaliTest[646:797201] multipeer session: stop timer
2015-12-11 12:15:29.991 Th,aliTest[646:797201] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 57109
,2015-12-11 12:15:30.057 ThaliTest[646:797201] jxcore: startBroadcasting
,2015-12-11 12:15:30.061 ThaliTest[646:797201] server: starting Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:15:30.064 ThaliTest[646:797201] multipeer session: start timer: 0x1c3e2c90
,2015-12-11 12:15:30.073 ThaliTest[646:797201] THEMultipeerSession initialized peer Apple-Iphone5-1_PT2684
,2015-12-11 12:15:30.075 ThaliTest[646:797201] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-12-11 12:15:30.088 ThaliTest[646:797005] client: found peer: Apple-Iphone5-1_PT2684.X/CFmw==
null
2015-12-11T11:15:30.091Z SendDataTCPServer.js: TCP/IP server is bound to port: 57109
2015-12-11 12:15:30.092 ThaliTest[6,46:797005] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:15:30.092 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.QOwtzQ==
2015-12-11 12:15:30.093 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.IK91fw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2684.X/CFmw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11T11:15:30.109Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11T11:15:30.110Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11T11:15:30.110Z SendDataConnector.js: do connect now
,2015-12-11 12:15:30.111 ThaliTest[646:797201] jxcore: connect Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11 12:15:30.113 ThaliTest[646:797201] client session: connect
,2015-12-11 12:15:30.114 ThaliTest[646:797201] client session: stateChange:0->1 Apple-Iphone5-1_PT2684.X/CFmw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.1YTBNQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.QOwtzQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8695.IK91fw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-11 12:15:31.212 ThaliTest[646:797005] client: lost peer: Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:31.213 ThaliTest[646:797005] client session: onPeerLost: Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:31.213 ThaliTest[646:797005] clien,t session: onLinkFailure: Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:31.213 ThaliTest[646:797005] client session: disconnect
2015-12-11 12:15:31.214 ThaliTest[646:797005] client session: stateChange:1->0 Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 ,12:15:31.214 ThaliTest[646:797005] client session: fireConnectCallback: Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:31.215 ThaliTest[646:797005] jxcore: connect: fail: Peer disconnected
2015-12-11T11:15:31.215Z SendDataConnector.js: CLIENT connected, to 0, error: Peer disconnected
2015-12-11T11:15:31.216Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-11T11:15:31.216Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_P,T2684.X/CFmw==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 12:15:31.320 ThaliTest[646:797005] client: lost peer: Apple-Iphone6-1_PT2932.QOwtzQ==
2015-12-11 12:15:31.320 ThaliTest[646:797005] client session: onPeerLost: Apple-Iphone6-1_PT2932.QOwtzQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.QOwtzQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-11 12:15:31.355 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.PHL+kA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 12:15:33.337 ThaliTest[646:797005] client: lost peer: Apple-Iphone5s-1_PT8695.IK91fw==
2015-12-11 12:15:33.338 ThaliTest[646:797005] client session: onPeerLost: Apple-Iphone5s-1_PT8695.IK91fw==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT8695.IK91fw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-11 12:15:33.446 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8695.iCr2Pw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 12:15:33.888 ThaliTest[646:797005] multipeer session: reset timer
2015-12-11 12:15:33.888 ThaliTest[646:797005] multipeer session: stop timer
2015-12-11 12:15:33.888 ThaliTest[646:797005] multipeer session: start timer: 0x1c3e2c90
2015-12-11 12:15:33.888 ThaliTest[646:797005] server session: connect
2015-12-11 12:15:33.888 ThaliTest[646:797005] server session: stateChange:0->1 Apple-Iphone5s-1_PT8695
,2015-12-11 12:15:33.895 ThaliTest[646:797005] server: accepting invitation Apple-Iphone5s-1_PT8695
,2015-12-11T11:15:36.226Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11T11:15:36.227Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11 12:15:37.114 ThaliTest[646:797885] server session: connected
2015-12-11 12:15:37.115 ThaliTest[646:797885] server session: stateChange:1->2 Apple-Iphone5s-1_PT8695
,2015-12-11T11:15:37.141Z SendDataTCPServer.js: TCP/IP server connected
2015-12-11 12:15:37.141 ThaliTest[646:797005] server relay: connected (to port: 57109)
,2015-12-11T11:15:37.516Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-11T11:15:37.531Z SendDataTCPServer.js: TCP/IP server has received 47754 bytes of data
,2015-12-11T11:15:37.547Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-11T11:15:37.560Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 12:15:37.606 ThaliTest[646:797889] server session: not connected Apple-Iphone5s-1_PT8695
,2015-12-11 12:15:41.232 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:15:41.232 ThaliTest[646:797201] jxcore: disconnect: fail
2015-12-11T11:15:41.234Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2684.X/CFmw==,
2015-12-11T11:15:41.234Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT2684.X/CFmw== with availability status: true
2015-12-11T11:15:41.235Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11T11:15:41.235Z SendDataConnector.js: do connect now
,2015-12-11 12:15:41.235 ThaliTest[646:797201] jxcore: connect Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:41.236 ThaliTest[646:797201] client: connect: unreachable Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:41.236 ThaliTest[646:797201] jxcore:, connect: fail: Peer unreachable
,2015-12-11T11:15:41.237Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T11:15:41.237Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-11T11:15:41.238Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:15:46.243Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11T11:15:46.243Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11 12:15:51.248 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:15:51.249 ThaliTest[646:797201] jxcore: disconnect: fail
2015-12-11T11:15:51.249Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2684.X/CFmw==,
2015-12-11T11:15:51.250Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT2684.X/CFmw== with availability status: true
2015-12-11T11:15:51.250Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11T11:15:51.251Z SendDataConnector.js: do connect now
2015-12-11 12:15:51.252 ThaliTest[646:797201] jxcore: connect Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:51.252 ThaliTest[646:797201] client: connect: unreachable Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11 12:15:51.252 ThaliTest[646:797201] jxcore: connect: fail: Peer unreachable
2015-12-11T11:15:51.253Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T11:15:51.253Z SendDataConnector.js: CLIENT Can not Connect: Pee,r unreachable
,2015-12-11T11:15:51.253Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:15:56.261Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11T11:15:56.261Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11 12:16:01.265 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:16:01.266 ThaliTest[646:797201] jxcore: disconnect: fail
2015-12-11T11:16:01.266Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2684.X/CFmw==,
2015-12-11T11:16:01.267Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT2684.X/CFmw== with availability status: true
2015-12-11T11:16:01.267Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2684.X/CFmw==
2015-,12-11T11:16:01.267Z SendDataConnector.js: do connect now
,2015-12-11 12:16:01.268 ThaliTest[646:797201] jxcore: connect Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:16:01.269 ThaliTest[646:797201] client: connect: unreachable Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:16:01.269 ThaliTest[646:797201] jxcore: connect: fail: Peer unreachable
,2015-12-11T11:16:01.269Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T11:16:01.270Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T11:16:01.270Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11 12:16:03.889 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:16:03.930 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:16:03.930 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:04.189 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11T11:16:06.281Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11T11:16:06.281Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2684.X/CFmw==
,2015-12-11 12:16:11.292 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:16:11.293 ThaliTest[646:797201] jxcore: disconnect: fail
2015-12-11T11:16:11.293Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2684.X/CFmw==,
2015-12-11T11:16:11.294Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT2684.X/CFmw== with availability status: true
2015-12-11T11:16:11.294Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11T11:16:11.294Z SendDataConnector.js: do connect now
,2015-12-11 12:16:11.295 ThaliTest[646:797201] jxcore: connect Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:16:11.296 ThaliTest[646:797201] client: connect: unreachable Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:16:11.296 ThaliTest[646:797201] jxcore: connect: fail: Peer unreachable
,2015-12-11T11:16:11.296Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T11:16:11.297Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2015-12-11T11:16:11.298Z SendDataConnector.js: CLIENT Stop now
2015-12-11 12:16:11.299 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:16:11.299 ThaliTest[646:797201] jxcore: disconnect: fail
,2015-12-11T11:16:11.300Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2684.X/CFmw==
---- round done--------
startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:16:11.301Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:11.301Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:16:11.302Z SendDataConnector.js: do connect now
,2015-12-11 12:16:11.302 ThaliTest[646:797201] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:11.303 ThaliTest[646:797201] client session: connect
2015-12-11 12:16:11.303 ThaliTest[646:797201] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:15.321 ThaliTest[646:797985] client session: connected
2015-12-11 12:16:15.321 ThaliTest[646:797985] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:15.382 ThaliTest[646:797998] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:15.382 ThaliTest[646:797998] jxcore: connect: success
2015-12-11T11:16:15.383Z SendDataConnector.js: CLIENT connected to ,57117, error: null
2015-12-11T11:16:15.383Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:16:15.386 ThaliTest[646:797005] client: relay established
2015-12-11 12:16:15.387 ThaliTest[646:797005] client: new accepted socket: 0x1c47a5e0
,2015-12-11T11:16:15.400Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:16:25.884Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T11:16:25.885Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:25.887Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:25.888Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:16:25.888Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11 12:16:25.889 ThaliTest[646:797005] client: socket closed
2015-12-11 12:16:25.890 ThaliTest[646:797005] client relay: socket disconnected
2015-12-11 12:16:25.890 ThaliTest[646:797005] client relay: 0x1c47a5e0 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-11 12:16:25.890 ThaliTest[646:797005] client session: socket closed: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:,16:25.890 ThaliTest[646:797005] client session: onLinkFailure: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:25.890 ThaliTest[646:797005] client session: disconnect
2015-12-11 12:16:25.891 ThaliTest[646:797005] client session: stateChange:2->0 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:25.895 ThaliTest[646:797005] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:30.897Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:30.897Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:33.889 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:16:33.924 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:34.200 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:16:35.909 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:16:35.910 ThaliTest[646:797201] jxcore: disconnect: fail
2015-12-11T11:16:35.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==,
2015-12-11T11:16:35.911Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
2015-12-11T11:16:35.911Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
20,15-12-11T11:16:35.912Z SendDataConnector.js: do connect now
,2015-12-11 12:16:35.912 ThaliTest[646:797201] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:35.913 ThaliTest[646:797201] client session: connect
2015-12-11 12:16:35.913 ThaliTest[646:797201] client session: stateChange:0->1 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:39.499 ThaliTest[646:798048] client session: connected
2015-12-11 12:16:39.500 ThaliTest[646:798048] client session: stateChange:1->2 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:39.524 ThaliTest[646:798049] client session: fireConnectCallback: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:39.525 ThaliTest[646:798049] jxcore: connect: success
2015-12-11T11:16:39.526Z SendDataConnector.js: CLIENT connected to 57121, error: null
2015-12-11T11:16:39.526Z SendDataConnector.js: CLIENT starting client 
2015-12-11 12:16:39.528 ThaliTest[646:797005] client: relay established
2015-12-11 12:16:39.528 ThaliTest[646:797005] client: new accepted socket: 0x1c354720
,2015-12-11T11:16:39.541Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 12:16:48.341 ThaliTest[646:798049] client session: not connected Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:48.342 ThaliTest[646:798049] client session: onLinkFailure: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:48.342 ThaliTest[6,46:798049] client session: disconnect
2015-12-11 12:16:48.342 ThaliTest[646:798049] client session: stateChange:2->0 Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:48.344 ThaliTest[646:798049] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:16:49.910 ThaliTest[646:797005] client: lost peer: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:49.910 ThaliTest[646:797005] client session: onPeerLost: Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:16:49.910 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.1YTBNQ==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2428.ucnEeA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11T11:16:50.024Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T11:16:50.025Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:50.026Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T11:16:50.026Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:16:50.027Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11 12:16:54.049 ThaliTest[646:797005] multipeer session: reset timer
2015-12-11 12:16:54.049 ThaliTest[646:797005] multipeer session: stop timer
2015-12-11 12:16:54.049 ThaliTest[646:797005] multipeer session: start timer: 0x1c3e2c90
2015-12-11 ,12:16:54.049 ThaliTest[646:797005] server session: connect
2015-12-11 12:16:54.049 ThaliTest[646:797005] server session: stateChange:0->1 Apple-IpadAir2-1_PT2428
2015-12-11 12:16:54.054 ThaliTest[646:797005] server: accepting invitation Apple-IpadAir2-1_PT2428
,2015-12-11T11:16:55.036Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:55.037Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:16:55.037Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:16:56.920 ThaliTest[646:797999] server session: connected
,2015-12-11 12:16:56.921 ThaliTest[646:797999] server session: stateChange:1->2 Apple-IpadAir2-1_PT2428
,2015-12-11 12:16:56.925 ThaliTest[646:797005] server relay: connected (to port: 57109)
,2015-12-11T11:16:56.933Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T11:16:57.194Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-11T11:16:57.209Z SendDataTCPServer.js: TCP/IP server has received 49944 bytes of data
,2015-12-11T11:16:57.226Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-11T11:16:57.252Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-11T11:16:57.267Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 12:16:57.317 ThaliTest[646:798109] server session: not connected Apple-IpadAir2-1_PT2428
,2015-12-11 12:17:00.045 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:17:00.046 ThaliTest[646:797201] jxcore: disconnect: fail
2015-12-11T11:17:00.046Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==,
2015-12-11T11:17:00.046Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
2015-12-11T11:17:00.047Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:17:00.048Z SendDataConnector.js: do connect now
2015-12-11 12:17:00.048 ThaliTest[646:797201] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:17:00.049 ThaliTest[646:797201] client: connect: unreachable Apple-IpadAir2-1_PT242,8.1YTBNQ==
2015-12-11 12:17:00.049 ThaliTest[646:797201] jxcore: connect: fail: Peer unreachable
,2015-12-11T11:17:00.049Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T11:17:00.050Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-11T11:17:00.050Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-11T11:17:00.050Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T11:17:05.053Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:17:05.053Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:17:05.054Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:08.323 ThaliTest[646:797005] multipeer session: reset timer
2015-12-11 12:17:08.323 ThaliTest[646:797005] multipeer session: stop timer
2015-12-11 12:17:08.323 ThaliTest[646:797005] multipeer session: start timer: 0x1c3e2c90
2015-12-11 ,12:17:08.323 ThaliTest[646:797005] server session: connect
2015-12-11 12:17:08.323 ThaliTest[646:797005] server session: stateChange:0->1 Apple-Iphone6-1_PT2932
,2015-12-11 12:17:08.330 ThaliTest[646:797005] server: accepting invitation Apple-Iphone6-1_PT2932
,2015-12-11 12:17:10.057 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:17:10.057 ThaliTest[646:797201] jxcore: disconnect: fail
2015-12-11T11:17:10.058Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==,
2015-12-11T11:17:10.058Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
2015-12-11T11:17:10.059Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:17:10.059Z SendDataConnector.js: do connect now
2015-12-11 12:17:10.060 ThaliTest[646:797201] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:17:10.061 ThaliTest[646:797201] client: connect: unreachable Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:17:10.061 ThaliTest[646:797201] jxcore: connect: fail: Peer unreachable
,2015-12-11T11:17:10.062Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-11T11:17:10.062Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-11T11:17:10.063Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-11T11:17:10.063Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11 12:17:11.146 ThaliTest[646:798109] server session: connected
2015-12-11 12:17:11.146 ThaliTest[646:798109] server session: stateChange:1->2 Apple-Iphone6-1_PT2932
,2015-12-11 12:17:11.173 ThaliTest[646:797005] server relay: connected (to port: 57109)
2015-12-11T11:17:11.177Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T11:17:11.437Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-11T11:17:11.466Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-11T11:17:11.483Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-11T11:17:11.498Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-11T11:17:11.514Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 12:17:11.556 ThaliTest[646:798160] server session: not connected Apple-Iphone6-1_PT2932
,2015-12-11 12:17:14.427 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:17:15.069Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:17:15.070Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11T11:17:15.070Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:20.083 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:17:20.084 ThaliTest[646:797201] jxcore: disconnect: fail
2015-12-11T11:17:20.085Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==,
2015-12-11T11:17:20.085Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT2428.1YTBNQ== with availability status: true
2015-12-11T11:17:20.085Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11T11:17:20.086Z SendDataConnector.js: do connect now
,2015-12-11 12:17:20.087 ThaliTest[646:797201] jxcore: connect Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:17:20.087 ThaliTest[646:797201] client: connect: unreachable Apple-IpadAir2-1_PT2428.1YTBNQ==
2015-12-11 12:17:20.087 ThaliTest[646:797201] jxcore: connect: fail: Peer unreachable
,2015-12-11T11:17:20.088Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T11:17:20.088Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T11:17:20.088Z SendDataConnector.js: CLIENT closeClientSocket,
,oneRoundDownNow
2015-12-11T11:17:20.089Z SendDataConnector.js: CLIENT Stop now
2015-12-11T11:17:20.089Z SendDataConnector.js: Stop data retrieving timer
2015-12-11T11:17:20.089Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-11 12:17:20.090 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:17:20.090 ThaliTest[646:797201] jxcore: disconnect: fail
2015-12-11T11:17:20.090Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2428.1YTBNQ==
---- round done--------
,startWithNextDevice
device[3]: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11T11:17:20.091Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11T11:17:20.091Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-,1_PT2932.PHL+kA==
2015-12-11T11:17:20.092Z SendDataConnector.js: do connect now
,2015-12-11 12:17:20.092 ThaliTest[646:797201] jxcore: connect Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:17:20.092 ThaliTest[646:797201] client session: connect
2015-12-11 12:17:20.092 ThaliTest[646:797201] client session: stateChange:0->1 Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:21.799 ThaliTest[646:798202] client session: connected
2015-12-11 12:17:21.799 ThaliTest[646:798202] client session: stateChange:1->2 Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:22.105 ThaliTest[646:798203] client session: fireConnectCallback: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:17:22.106 ThaliTest[646:798203] jxcore: connect: success
2015-12-11T11:17:22.106Z SendDataConnector.js: CLIENT connected to 5,7133, error: null
2015-12-11T11:17:22.107Z SendDataConnector.js: CLIENT starting client 
2015-12-11 12:17:22.108 ThaliTest[646:797005] client: relay established
2015-12-11 12:17:22.109 ThaliTest[646:797005] client: new accepted socket: 0x1c356cc0
,2015-12-11T11:17:22.121Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:17:23.132Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T11:17:23.517Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-11T11:17:24.106Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T11:17:24.706Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-11T11:17:25.230Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-11T11:17:25.618Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-11T11:17:25.731Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T11:17:26.022Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-11T11:17:27.057Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-11T11:17:27.121Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T11:17:27.121Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T11:17:27.123Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T11:17:27.123Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:27.124 ThaliTest[646:797201] jxcore: disconnect
2015-12-11 12:17:27.124 ThaliTest[646:797201] client session: disconnectFromPeer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:17:27.125 ThaliTest[646:797201] client session: disconnect
2015-12-11 12:17:27.125 ThaliTest[646:797201] client session: stateChange:2->0 Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:27.136 ThaliTest[646:797201] jxcore: disconnect: success
2015-12-11T11:17:27.137Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2932.PHL+kA==
---- round done--------
startWithNextDevice
device[4]: Apple,-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11T11:17:27.138Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11T11:17:27.138Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11T11:1,7:27.138Z SendDataConnector.js: do connect now
2015-12-11 12:17:27.139 ThaliTest[646:797201] jxcore: connect Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:17:27.139 ThaliTest[646:797201] client session: connect
2015-12-11 12:17:27.139 ThaliTest[646:797,201] client session: stateChange:0->1 Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:31.358 ThaliTest[646:798109] client session: connected
2015-12-11 12:17:31.359 ThaliTest[646:798109] client session: stateChange:1->2 Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:31.398 ThaliTest[646:798202] client session: fireConnectCallback: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:17:31.399 ThaliTest[646:798202] jxcore: connect: success
2015-12-11T11:17:31.400Z SendDataConnector.js: CLIENT connected to 57136, error: null
2015-12-11T11:17:31.400Z SendDataConnector.js: CLIENT starting client 
2015-12-11 12:17:31.402 ThaliTest[646:797005] client: relay established
2015-12-11 12:17:31.402 ThaliTest[646:797005] client: new accepted socket: 0x1c492470
,2015-12-11T11:17:31.415Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:17:31.950Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T11:17:31.998Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-11T11:17:32.039Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T11:17:32.052Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-11T11:17:32.066Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T11:17:32.068Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T11:17:32.070Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T11:17:32.070Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:32.071 ThaliTest[646:797201] jxcore: disconnect
,2015-12-11 12:17:32.071 ThaliTest[646:797201] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:32.072 ThaliTest[646:797201] client session: disconnect
,2015-12-11 12:17:32.073 ThaliTest[646:797201] client session: stateChange:2->0 Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:32.088 ThaliTest[646:797201] jxcore: disconnect: success
,2015-12-11T11:17:32.091Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8695.iCr2Pw==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-11T11:17:32.105Z SendDataConnector.js: CLIENT Stop now
2015-12-11T11:17:32.105Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:17:38.361 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:17:38.365 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:17:38.367 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:18:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:18:08.365 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:18:08.365 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:18:08.365 ThaliTest[646:797005] client: fou,nd peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:18:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:18:38.361 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:18:38.362 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:18:38.367 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:19:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:19:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:19:38.355 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:19:38.355 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:19:38.363 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:20:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:20:08.357 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:20:08.357 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:20:08.360 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:20:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:20:38.357 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:20:38.359 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:20:38.361 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:21:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:21:08.357 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:21:08.358 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:21:08.362 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:21:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:21:38.358 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:21:38.358 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:21:38.359 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:22:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:22:08.366 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:22:08.370 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:22:08.370 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:22:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:23:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:23:08.355 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:23:08.355 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:23:08.610 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:23:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:24:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:24:08.354 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:24:08.354 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:24:08.355 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:24:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:24:38.357 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:24:38.358 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:24:38.359 ThaliTest[646:797005] client: fou,nd peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:25:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:25:08.354 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:25:08.625 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:25:22.333 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:25:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:25:38.357 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:25:38.357 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:25:38.358 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:26:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:26:08.354 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:26:08.355 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:26:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:27:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:27:08.350 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:27:08.353 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:27:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:27:38.353 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:27:38.356 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:27:45.876 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:28:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:28:08.355 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:28:09.054 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:28:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:28:38.353 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:28:38.354 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:29:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:29:08.353 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:29:08.357 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:29:17.088 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:29:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:29:38.356 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:29:38.357 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:29:48.541 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:30:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:30:08.354 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:30:08.355 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:30:12.717 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:30:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:30:38.357 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:30:38.357 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:30:38.360 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:31:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:31:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:31:38.354 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:31:38.639 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:31:44.321 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:32:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:32:08.352 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:32:08.352 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:32:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:32:38.354 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
2015-12-11 12:32:38.354 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:33:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:33:08.353 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:33:08.866 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:33:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:33:38.353 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:33:38.357 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:34:03.363 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:34:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:34:09.257 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:34:09.257 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:34:34.151 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:34:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:34:38.358 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:34:38.359 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:34:38.936 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:35:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:35:08.359 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:35:08.361 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:35:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:35:38.353 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:35:38.677 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:35:53.363 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:36:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:36:08.355 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:36:08.358 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:36:18.522 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:36:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:36:38.354 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:36:38.357 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:37:08.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:37:08.352 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:37:08.356 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:37:15.148 ThaliTest[646:797005] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:37:38.324 ThaliTest[646:797005] multipeer session: restart
,2015-12-11 12:37:38.355 ThaliTest[646:797005] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:37:38.355 ThaliTest[646:797005] client: found peer: Apple-IpadAir2-1_PT2428.ucnEeA==

```
