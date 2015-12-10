#### Test 50650278b86327b_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/AFE2554B-AC60-4D9F-8DF3-95BC9459CEBA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/AFE2554B-AC60-4D9F-8DF3-95BC9459CEBA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DAB3235D-EC52-4C79-AC18-31EDAFAC417F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53569"
,(lldb)     command script import "/tmp/AFE2554B-AC60-4D9F-8DF3-95BC9459CEBA/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 15:08:29.030 ThaliTest[598:656545] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9068C295-D3B1-4A17-B709-6A860DDA8B9E/Library/Cookies/Cookies.binarycookies
,2015-12-10 15:08:29.163 ThaliTest[598:656545] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 15:08:29.165 ThaliTest[598:656545] Multi-tasking -> Device: YES, App: YES
,2015-12-10 15:08:29.173 ThaliTest[598:656545] Unlimited access to network resources
,2015-12-10 15:08:29.188 ThaliTest[598:656545] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 15:08:39.576 ThaliTest[598:656545] Resetting plugins due to page load.
,2015-12-10 15:08:43.812 ThaliTest[598:656545] Finished load of: file:///var/mobile/Containers/Bundle/Application/DAB3235D-EC52-4C79-AC18-31EDAFAC417F/ThaliTest.app/www/index.html
,2015-12-10 15:08:44.027 ThaliTest[598:656545] JXcore Cordova plugin initializing
,2015-12-10 15:08:44.029 ThaliTest[598:656737] JXcore instance initializing
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
,2015-12-10 15:08:46.467 ThaliTest[598:656545] THREAD WARNING: ['JXcore'] took '154.621826' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-10 15:14:33.667 ThaliTest[598:656737] jxcore: startBroadcasting
,2015-12-10 15:14:33.679 ThaliTest[598:656737] server: starting Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:14:33.680 ThaliTest[598:656737] multipeer session: start timer: 0x1a3b47f0
2015-12-10 15:14:33.681 ThaliTest[598:656737] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9189
2015-12-10 15:14:33.681 ThaliTest[598:656737] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-10 15:14:35.251 ThaliTest[598:656545] client: found peer: Apple-Iphone6-1_PT4262.KAmLlg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4262.KAmLlg==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT4262.KAmLlg==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-10 15:14:35.546 ThaliTest[598:656545] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 15:14:39.687 ThaliTest[598:656545] client: lost peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 15:14:39.687 ThaliTest[598:656545] client session: onPeerLost: Apple-Iphone6-1_PT5811.hStH7w==
,teardown
,testFindPeers stopped
,2015-12-10 15:14:46.103 ThaliTest[598:656737] jxcore: stopBroadcasting
2015-12-10 15:14:46.103 ThaliTest[598:656737] THEMultipeerSession stopping peer
2015-12-10 15:14:46.103 ThaliTest[598:656737] multipeer session: stop timer
2015-12-10 15:14:46.104 ThaliTest[598:656737] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":2}bt-address length : 0
,daya100000
,check server
,serverPort is 56710
,2015-12-10 15:14:46.175 ThaliTest[598:656737] jxcore: startBroadcasting
,2015-12-10 15:14:46.178 ThaliTest[598:656737] server: starting Apple-Iphone5-1_PT9189.dQfCuw==
,2015-12-10 15:14:46.179 ThaliTest[598:656737] multipeer session: start timer: 0x1a200af0
,2015-12-10 15:14:46.191 ThaliTest[598:656737] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9189
,2015-12-10 15:14:46.197 ThaliTest[598:656737] jxcore: startBroadcasting: success
,2015-12-10 15:14:46.204 ThaliTest[598:656545] client: found peer: Apple-Iphone5-1_PT9189.I0Ha/w==
StartBroadcasting started ok
null
2015-12-10T14:14:46.207Z SendDataTCPServer.js: TCP/IP server is bound to port: 56710
2015-12-10 15:14:46.209 ThaliTest[598:656545] client: found peer: Apple-Iphone6-1_PT4262.KAmLlg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9189.I0Ha/w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10T14:14:46.219Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10T14:14:46.220Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10T14:14:46.221Z SendDataConnector.js: do connect now
,2015-12-10 15:14:46.222 ThaliTest[598:656737] jxcore: connect Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10 15:14:46.224 ThaliTest[598:656737] client session: connect
,2015-12-10 15:14:46.225 ThaliTest[598:656737] client session: stateChange:0->1 Apple-Iphone5-1_PT9189.I0Ha/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4262.KAmLlg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-10 15:14:47.223 ThaliTest[598:656545] client: lost peer: Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:14:47.224 ThaliTest[598:656545] client session: onPeerLost: Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:14:47.224 ThaliTest[598:656545] clien,t session: onLinkFailure: Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:14:47.224 ThaliTest[598:656545] client session: disconnect
2015-12-10 15:14:47.224 ThaliTest[598:656545] client session: stateChange:1->0 Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 ,15:14:47.225 ThaliTest[598:656545] client session: fireConnectCallback: Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:14:47.225 ThaliTest[598:656545] jxcore: connect: fail: Peer disconnected
2015-12-10T14:14:47.226Z SendDataConnector.js: CLIENT connected, to 0, error: Peer disconnected
2015-12-10T14:14:47.226Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-10T14:14:47.226Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_P,T9189.I0Ha/w==","peerName":"(null)","peerAvailable":false}]
,2015-12-10 15:14:50.848 ThaliTest[598:656545] client: found peer: Apple-Iphone6-1_PT4262.fxR5Pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4262.fxR5Pw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-10T14:14:52.232Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10T14:14:52.233Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10 15:14:53.388 ThaliTest[598:656545] client: lost peer: Apple-Iphone6-1_PT4262.KAmLlg==
2015-12-10 15:14:53.388 ThaliTest[598:656545] client session: onPeerLost: Apple-Iphone6-1_PT4262.KAmLlg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4262.KAmLlg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-10 15:14:57.244 ThaliTest[598:656737] jxcore: disconnect
2015-12-10 15:14:57.245 ThaliTest[598:656737] jxcore: disconnect: fail
2015-12-10T14:14:57.245Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9189.I0Ha/w==,
2015-12-10T14:14:57.246Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT9189.I0Ha/w== with availability status: true
2015-12-10T14:14:57.246Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10T14:14:57.246Z SendDataConnector.js: do connect now
2015-12-10 15:14:57.247 ThaliTest[598:656737] jxcore: connect Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:14:57.248 ThaliTest[598:656737] client: connect: unreachable Apple-Iphone5-1_PT9189.,I0Ha/w==
2015-12-10 15:14:57.248 ThaliTest[598:656737] jxcore: connect: fail: Peer unreachable
,2015-12-10T14:14:57.248Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-10T14:14:57.248Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-10T14:14:57.249Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-10T14:15:02.255Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10T14:15:02.255Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10 15:15:07.266 ThaliTest[598:656737] jxcore: disconnect
2015-12-10 15:15:07.267 ThaliTest[598:656737] jxcore: disconnect: fail
2015-12-10T14:15:07.267Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9189.I0Ha/w==,
2015-12-10T14:15:07.268Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT9189.I0Ha/w== with availability status: true
2015-12-10T14:15:07.268Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10T14:15:07.269Z SendDataConnector.js: do connect now
,2015-12-10 15:15:07.270 ThaliTest[598:656737] jxcore: connect Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:15:07.270 ThaliTest[598:656737] client: connect: unreachable Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:15:07.270 ThaliTest[598:656737] jxcore:, connect: fail: Peer unreachable
2015-12-10T14:15:07.271Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-10T14:15:07.271Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-10T14:15:07.271Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-10T14:15:12.280Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10T14:15:12.280Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10 15:15:16.189 ThaliTest[598:656545] multipeer session: restart
,2015-12-10 15:15:16.218 ThaliTest[598:656545] client: found peer: Apple-Iphone6-1_PT4262.fxR5Pw==
,2015-12-10 15:15:17.284 ThaliTest[598:656737] jxcore: disconnect
2015-12-10 15:15:17.285 ThaliTest[598:656737] jxcore: disconnect: fail
2015-12-10T14:15:17.286Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9189.I0Ha/w==,
2015-12-10T14:15:17.286Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT9189.I0Ha/w== with availability status: true
2015-12-10T14:15:17.287Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10T14:15:17.287Z SendDataConnector.js: do connect now
,2015-12-10 15:15:17.288 ThaliTest[598:656737] jxcore: connect Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:15:17.288 ThaliTest[598:656737] client: connect: unreachable Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:15:17.289 ThaliTest[598:656737] jxcore:, connect: fail: Peer unreachable
,2015-12-10T14:15:17.289Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-10T14:15:17.289Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-10T14:15:17.290Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-10T14:15:22.295Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10T14:15:22.296Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9189.I0Ha/w==
,2015-12-10 15:15:27.301 ThaliTest[598:656737] jxcore: disconnect
2015-12-10 15:15:27.301 ThaliTest[598:656737] jxcore: disconnect: fail
2015-12-10T14:15:27.302Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9189.I0Ha/w==,
2015-12-10T14:15:27.302Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT9189.I0Ha/w== with availability status: true
2015-12-10T14:15:27.303Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10T14:15:27.303Z SendDataConnector.js: do connect now
,2015-12-10 15:15:27.304 ThaliTest[598:656737] jxcore: connect Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:15:27.305 ThaliTest[598:656737] client: connect: unreachable Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:15:27.305 ThaliTest[598:656737] jxcore:, connect: fail: Peer unreachable
2015-12-10T14:15:27.305Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-10T14:15:27.305Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-10T14:15:27.307Z SendDataConnector.js: CLIENT Stop now
2015-12-10 15:15:27.307 ThaliTest[598:656737] jxcore: disconnect
2015-12-10 15:15:27.308 ThaliTest[598:656737] jxcore: disconnect: fail
2015-12-10T14:15:27.308Z SendDataConnector.js: Mobile.,Disconnect() callback with peer Apple-Iphone5-1_PT9189.I0Ha/w==
---- round done--------
startWithNextDevice
device[2]: Apple-Iphone6-1_PT4262.fxR5Pw==
2015-12-10T14:15:27.309Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4262.fxR5Pw==
,2015-12-10T14:15:27.309Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4262.fxR5Pw==
2015-12-10T14:15:27.309Z SendDataConnector.js: do connect now
2015-12-10 15:15:27.310 ThaliTest[598:656737] jxcore: connect Apple-Iphone6-1_PT4262.f,xR5Pw==
,2015-12-10 15:15:27.310 ThaliTest[598:656737] client session: connect
2015-12-10 15:15:27.311 ThaliTest[598:656737] client session: stateChange:0->1 Apple-Iphone6-1_PT4262.fxR5Pw==
,2015-12-10 15:15:34.004 ThaliTest[598:656545] multipeer session: reset timer
2015-12-10 15:15:34.004 ThaliTest[598:656545] multipeer session: stop timer
2015-12-10 15:15:34.004 ThaliTest[598:656545] multipeer session: start timer: 0x1a200af0
,2015-12-10 15:15:34.005 ThaliTest[598:656545] server session: connect
2015-12-10 15:15:34.006 ThaliTest[598:656545] server session: stateChange:0->1 Apple-Iphone6-1_PT4262
,2015-12-10 15:15:34.011 ThaliTest[598:656545] server: accepting invitation Apple-Iphone6-1_PT4262
,2015-12-10 15:15:36.965 ThaliTest[598:657514] server session: connected
2015-12-10 15:15:36.965 ThaliTest[598:657514] server session: stateChange:1->2 Apple-Iphone6-1_PT4262
,2015-12-10 15:15:36.974 ThaliTest[598:656545] server relay: connected (to port: 56710)
2015-12-10T14:15:36.979Z SendDataTCPServer.js: TCP/IP server connected
2015-12-10 15:15:36.981 ThaliTest[598:657514] client session: connected
2015-12-10 15:15:36.981 ThaliTest[598:657514] client session: stateChange:1->2 Apple-Iphone6-1_PT4262.fxR5Pw==
,2015-12-10 15:15:37.146 ThaliTest[598:657616] client session: fireConnectCallback: Apple-Iphone6-1_PT4262.fxR5Pw==
2015-12-10 15:15:37.146 ThaliTest[598:657616] jxcore: connect: success
2015-12-10T14:15:37.147Z SendDataConnector.js: CLIENT connected to 56718, error: null
2015-12-10T14:15:37.147Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 15:15:37.150 ThaliTest[598:656545] client: relay established
2015-12-10 15:15:37.150 ThaliTest[598:656545] client: new accepted socket: 0x1a4391e0
,2015-12-10T14:15:37.162Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-10T14:15:37.806Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-10T14:15:37.820Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-10T14:15:37.870Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-10T14:15:37.945Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-10T14:15:38.018Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-10T14:15:38.084Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-10T14:15:38.209Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-10T14:15:38.274Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-10T14:15:38.326Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-10T14:15:38.462Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-10T14:15:38.526Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-10T14:15:38.540Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-10T14:15:38.654Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-10T14:15:38.693Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-10T14:15:38.744Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-10T14:15:38.944Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-10T14:15:39.004Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-10T14:15:39.262Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-10T14:15:39.387Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-10T14:15:39.439Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-10T14:15:39.465Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-10T14:15:39.703Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-10T14:15:39.966Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-10T14:15:40.143Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-10T14:15:40.614Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-10T14:15:40.766Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-10T14:15:40.963Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-10T14:15:41.015Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-10T14:15:41.140Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-10T14:15:41.394Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-10T14:15:41.544Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-10T14:15:41.796Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-10T14:15:41.880Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-10T14:15:42.016Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-10T14:15:42.143Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-10T14:15:42.208Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-10T14:15:42.394Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-10T14:15:42.530Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-10T14:15:42.658Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-10T14:15:42.722Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-10T14:15:42.737Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-10T14:15:42.790Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-10T14:15:42.917Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-10T14:15:42.931Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-10T14:15:43.119Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10T14:15:43.463Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-10T14:15:43.912Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-10T14:15:50.716Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-10T14:15:50.982Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-10T14:15:51.476Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-10T14:15:51.825Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-10T14:15:52.305Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-10T14:15:52.823Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-10T14:15:52.864Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-10T14:15:53.209Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-10T14:15:53.210Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-10T14:15:53.211Z SendDataConnector.js: CLIENT Stop now
,2015-12-10T14:15:53.213Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 15:15:53.214 ThaliTest[598:656737] jxcore: disconnect
2015-12-10 15:15:53.215 ThaliTest[598:656737] client session: disconnectFromPeer: Apple-Iphone6-1_PT4262.fxR5Pw==
2015-12-10 15:15:53.215 ThaliTest[598:656737] client session: disconnect
2,015-12-10 15:15:53.215 ThaliTest[598:656737] client session: stateChange:2->0 Apple-Iphone6-1_PT4262.fxR5Pw==
,2015-12-10 15:15:53.220 ThaliTest[598:656737] jxcore: disconnect: success
2015-12-10T14:15:53.221Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4262.fxR5Pw==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 2
sendReportNow
done, now sending data to server
,2015-12-10T14:15:53.225Z SendDataConnector.js: CLIENT Stop now
2015-12-10T14:15:53.225Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-10 15:15:53.504 ThaliTest[598:656737] jxcore: stopBroadcasting
2015-12-10 15:15:53.504 ThaliTest[598:656737] THEMultipeerSession stopping peer
2015-12-10 15:15:53.505 ThaliTest[598:656737] multipeer session: stop timer
2015-12-10 15:15:53.505 ThaliTest[598:656737] server session: disconnect
2015-12-10 15:15:53.505 ThaliTest[598:656737] server session: stateChange:2->0 Apple-Iphone6-1_PT4262
,2015-12-10 15:15:53.607 ThaliTest[598:656737] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-10T14:15:53.628Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-10T14:15:53.629Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
