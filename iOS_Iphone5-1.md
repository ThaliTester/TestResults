#### Test 5507315224df3aa_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/369BBEB0-60CE-4EBF-838A-1FE6A4156153/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/369BBEB0-60CE-4EBF-838A-1FE6A4156153/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EDD64095-C265-46E5-9ACE-886C7FE6D0B3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65019"
,(lldb)     command script import "/tmp/369BBEB0-60CE-4EBF-838A-1FE6A4156153/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 16:42:08.903 ThaliTest[956:3118619] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C1372620-4C06-4161-A707-A79468714C68/Library/Cookies/Cookies.binarycookies
,2016-01-05 16:42:09.406 ThaliTest[956:3118619] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 16:42:09.408 ThaliTest[956:3118619] Multi-tasking -> Device: YES, App: YES
,2016-01-05 16:42:09.413 ThaliTest[956:3118619] Unlimited access to network resources
,2016-01-05 16:42:09.425 ThaliTest[956:3118619] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 16:42:19.947 ThaliTest[956:3118619] Resetting plugins due to page load.
,2016-01-05 16:42:23.559 ThaliTest[956:3118619] Finished load of: file:///var/mobile/Containers/Bundle/Application/EDD64095-C265-46E5-9ACE-886C7FE6D0B3/ThaliTest.app/www/index.html
,2016-01-05 16:42:23.773 ThaliTest[956:3118619] JXcore Cordova plugin initializing
,2016-01-05 16:42:23.776 ThaliTest[956:3118804] JXcore instance initializing
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
,2016-01-05 16:42:26.255 ThaliTest[956:3118619] THREAD WARNING: ['JXcore'] took '155.111084' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 16:48:38.780 ThaliTest[956:3118804] jxcore: startBroadcasting
,2016-01-05 16:48:38.793 ThaliTest[956:3118804] server: starting Apple-Iphone5-1.uykjrA==
,2016-01-05 16:48:38.795 ThaliTest[956:3118804] multipeer session: start timer: 0x19bab040
,2016-01-05 16:48:38.808 ThaliTest[956:3118804] THEMultipeerSession initialized peer Apple-Iphone5-1
,2016-01-05 16:48:38.812 ThaliTest[956:3118804] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-05 16:48:40.119 ThaliTest[956:3118619] client: found peer: Apple-IpadAir2-1.S4dItg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.S4dItg==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.S4dItg==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2016-01-05 16:48:40.551 ThaliTest[956:3118619] client: found peer: Apple-Iphone6-1.DocMgw==
,teardown
,testFindPeers stopped
,2016-01-05 16:48:42.369 ThaliTest[956:3118804] jxcore: stopBroadcasting
2016-01-05 16:48:42.369 ThaliTest[956:3118804] THEMultipeerSession stopping peer
2016-01-05 16:48:42.370 ThaliTest[956:3118804] multipeer session: stop timer
2016-01-05 16:48:42.370, ThaliTest[956:3118804] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 63762
,2016-01-05 16:48:42.435 ThaliTest[956:3118804] jxcore: startBroadcasting
,2016-01-05 16:48:42.438 ThaliTest[956:3118804] server: starting Apple-Iphone5-1.cnOsew==
2016-01-05 16:48:42.439 ThaliTest[956:3118804] multipeer session: start timer: 0x19bb8630
2016-01-05 16:48:42.439 ThaliTest[956:3118804] THEMultipeerSession initiali,zed peer Apple-Iphone5-1
2016-01-05 16:48:42.439 ThaliTest[956:3118804] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-05T15:48:42.443Z SendDataTCPServer.js: TCP/IP server is bound to port: 63762
,2016-01-05 16:48:42.909 ThaliTest[956:3118619] client: found peer: Apple-IpadAir2-1.S4dItg==
2016-01-05 16:48:42.909 ThaliTest[956:3118619] client: found peer: Apple-Iphone5-1.uykjrA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.S4dItg==,","peerName":"(null)","peerAvailable":true}]
2016-01-05 16:48:42.911 ThaliTest[956:3118619] client: found peer: Apple-Iphone6-1.DocMgw==
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1.S4dItg==
2016-01-05T15:48:42.,913Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.S4dItg==
,2016-01-05T15:48:42.914Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.S4dItg==
2016-01-05T15:48:42.914Z SendDataConnector.js: do connect now
2016-01-05 16:48:42.915 ThaliTest[956:3118804] jxcore: connect Apple-IpadAir2-1.S4dItg==
,2016-01-05 16:48:42.916 ThaliTest[956:3118804] client session: connect
2016-01-05 16:48:42.916 ThaliTest[956:3118804] client session: stateChange:0->1 Apple-IpadAir2-1.S4dItg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.uykjrA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DocMgw==","peerName":"(null)","peerAvailable,":true}]
Found peer : (null), Available: true
,2016-01-05 16:48:43.514 ThaliTest[956:3118619] client: lost peer: Apple-Iphone5-1.uykjrA==
2016-01-05 16:48:43.515 ThaliTest[956:3118619] client session: onPeerLost: Apple-Iphone5-1.uykjrA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.uykjrA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-05 16:48:43.627 ThaliTest[956:3118619] client: lost peer: Apple-IpadAir2-1.S4dItg==
2016-01-05 16:48:43.627 ThaliTest[956:3118619] client session: onPeerLost: Apple-IpadAir2-1.S4dItg==
2016-01-05 16:48:43.627 ThaliTest[956:3118619] client session,: onLinkFailure: Apple-IpadAir2-1.S4dItg==
2016-01-05 16:48:43.627 ThaliTest[956:3118619] client session: disconnect
2016-01-05 16:48:43.628 ThaliTest[956:3118619] client session: stateChange:1->0 Apple-IpadAir2-1.S4dItg==
,2016-01-05 16:48:43.628 ThaliTest[956:3118619] client session: fireConnectCallback: Apple-IpadAir2-1.S4dItg==
2016-01-05 16:48:43.629 ThaliTest[956:3118619] jxcore: connect: fail: Peer disconnected
,2016-01-05T15:48:43.631Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-05T15:48:43.631Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05T15:48:43.632Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.S4dItg==","peerName":"(null)","peerAvailable":false}]
,2016-01-05 16:48:44.332 ThaliTest[956:3118619] client: found peer: Apple-IpadAir2-1.xC8Jhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xC8Jhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 16:48:44.611 ThaliTest[956:3118619] client: found peer: Apple-Iphone5s-1.lzdGtw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.lzdGtw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 16:48:44.718 ThaliTest[956:3118619] client: lost peer: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:44.719 ThaliTest[956:3118619] client session: onPeerLost: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:44.719 ThaliTest[956:3118619] client: found pe,er: Apple-Iphone6-1.GJN/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DocMgw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.GJN/JA==","p,eerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05T15:48:48.644Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.S4dItg==
,2016-01-05T15:48:48.644Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.S4dItg==
,2016-01-05 16:48:53.650 ThaliTest[956:3118804] jxcore: disconnect
2016-01-05 16:48:53.651 ThaliTest[956:3118804] jxcore: disconnect: fail
2016-01-05T15:48:53.651Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.S4dItg==
201,6-01-05T15:48:53.652Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.S4dItg== with availability status: true
2016-01-05T15:48:53.652Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.S4dItg==
,2016-01-05T15:48:53.653Z SendDataConnector.js: do connect now
2016-01-05 16:48:53.654 ThaliTest[956:3118804] jxcore: connect Apple-IpadAir2-1.S4dItg==
2016-01-05 16:48:53.654 ThaliTest[956:3118804] client: connect: unreachable Apple-IpadAir2-1.S4dItg==
,2016-01-05 16:48:53.654 ThaliTest[956:3118804] jxcore: connect: fail: Peer unreachable
,2016-01-05T15:48:53.655Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:48:53.655Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T15:48:53.655Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:48:58.666Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.S4dItg==
,2016-01-05T15:48:58.667Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.S4dItg==
,appEnteredForeground wasn't registered
,2016-01-05 16:49:03.678 ThaliTest[956:3118804] jxcore: disconnect
2016-01-05 16:49:03.678 ThaliTest[956:3118804] jxcore: disconnect: fail
2016-01-05T15:49:03.679Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.S4dItg==
201,6-01-05T15:49:03.679Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1.S4dItg== with availability status: true
2016-01-05T15:49:03.680Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.S4dItg==
2016-01-05T15:49:03.680Z SendDataConnector.js: do connect now
,2016-01-05 16:49:03.682 ThaliTest[956:3118804] jxcore: connect Apple-IpadAir2-1.S4dItg==
,2016-01-05 16:49:03.682 ThaliTest[956:3118804] client: connect: unreachable Apple-IpadAir2-1.S4dItg==
,2016-01-05 16:49:03.683 ThaliTest[956:3118804] jxcore: connect: fail: Peer unreachable
,2016-01-05T15:49:03.683Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T15:49:03.684Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T15:49:03.684Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:08.692Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.S4dItg==
,2016-01-05T15:49:08.693Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.S4dItg==
,2016-01-05 16:49:12.440 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:49:12.477 ThaliTest[956:3118619] client: found peer: Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:49:12.477 ThaliTest[956:3118619] client: found peer: Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:12.484 ThaliTest[956:3118619] client: found peer: Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:13.706 ThaliTest[956:3118804] jxcore: disconnect
2016-01-05 16:49:13.706 ThaliTest[956:3118804] jxcore: disconnect: fail
2016-01-05T15:49:13.707Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.S4dItg==
201,6-01-05T15:49:13.707Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1.S4dItg== with availability status: true
2016-01-05T15:49:13.708Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.S4dItg==
,2016-01-05T15:49:13.708Z SendDataConnector.js: do connect now
2016-01-05 16:49:13.709 ThaliTest[956:3118804] jxcore: connect Apple-IpadAir2-1.S4dItg==
2016-01-05 16:49:13.709 ThaliTest[956:3118804] client: connect: unreachable Apple-IpadAir2-1.S4dItg==
2016-01-05 16:49:13.710 ThaliTest[956:3118804] jxcore: connect: fail: Peer unreachable
,2016-01-05T15:49:13.710Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:49:13.710Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T15:49:13.711Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:18.718Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.S4dItg==
,2016-01-05T15:49:18.719Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.S4dItg==
,2016-01-05 16:49:23.727 ThaliTest[956:3118804] jxcore: disconnect
2016-01-05 16:49:23.728 ThaliTest[956:3118804] jxcore: disconnect: fail
2016-01-05T15:49:23.729Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.S4dItg==
2016-01-05T15:49:23.730Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1.S4dItg== with availability status: true
2016-01-05T15:49:23.730Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.S4dItg==
,2016-01-05T15:49:23.731Z SendDataConnector.js: do connect now
2016-01-05 16:49:23.731 ThaliTest[956:3118804] jxcore: connect Apple-IpadAir2-1.S4dItg==
2016-01-05 16:49:23.732 ThaliTest[956:3118804] client: connect: unreachable Apple-IpadAir2-1.S4dItg==
,2016-01-05 16:49:23.732 ThaliTest[956:3118804] jxcore: connect: fail: Peer unreachable
2016-01-05T15:49:23.732Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T15:49:23.733Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2016-01-05T15:49:23.734Z SendDataConnector.js: CLIENT Stop now
2016-01-05 16:49:23.734 ThaliTest[956:3118804] jxcore: disconnect
2016-01-05 16:49:23.734 ThaliTest[956:3118804] jxcore: disconnect: fail
2016-01-05T15:49:23.735Z SendDataCo,nnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.S4dItg==
---- round done--------
,startWithNextDevice
device[2]: Apple-IpadAir2-1.xC8Jhw==
2016-01-05T15:49:23.736Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:49:23.736Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.xC8Jhw==
2016-01-05T15:49:23.737Z SendDataConnector.js: do connect now
,2016-01-05 16:49:23.737 ThaliTest[956:3118804] jxcore: connect Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:23.737 ThaliTest[956:3118804] client session: connect
2016-01-05 16:49:23.738 ThaliTest[956:3118804] client session: stateChange:0->1 Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:24.175 ThaliTest[956:3118619] multipeer session: reset timer
2016-01-05 16:49:24.175 ThaliTest[956:3118619] multipeer session: stop timer
2016-01-05 16:49:24.175 ThaliTest[956:3118619] multipeer session: start timer: 0x19bb8630
2016-01-05 16:49:24.175 ThaliTest[956:3118619] server session: connect
2016-01-05 16:49:24.175 ThaliTest[956:3118619] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-05 16:49:24.182 ThaliTest[956:3118619] server: accepting invitation Apple-Iphone5s-1
,2016-01-05 16:49:26.655 ThaliTest[956:3119713] server session: connected
2016-01-05 16:49:26.655 ThaliTest[956:3119713] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-05 16:49:26.694 ThaliTest[956:3118619] server relay: connected (to port: 63762)
,2016-01-05T15:49:26.699Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T15:49:27.110Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-05T15:49:27.126Z SendDataTCPServer.js: TCP/IP server has received 48038 bytes of data
,2016-01-05T15:49:27.143Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-05T15:49:27.155Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2016-01-05T15:49:27.170Z SendDataTCPServer.js: TCP/IP server has received 94028 bytes of data
,2016-01-05 16:49:27.181 ThaliTest[956:3119724] client session: connected
2016-01-05 16:49:27.181 ThaliTest[956:3119724] client session: stateChange:1->2 Apple-IpadAir2-1.xC8Jhw==
2016-01-05T15:49:27.185Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:49:27.205 ThaliTest[956:3119714] client session: fireConnectCallback: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:27.205 ThaliTest[956:3119714] jxcore: connect: success
2016-01-05T15:49:27.206Z SendDataConnector.js: CLIENT connected to 63768,, error: null
2016-01-05T15:49:27.206Z SendDataConnector.js: CLIENT starting client 
2016-01-05 16:49:27.209 ThaliTest[956:3118619] client: relay established
2016-01-05 16:49:27.209 ThaliTest[956:3118619] client: new accepted socket: 0x19bcacb0
,2016-01-05T15:49:27.220Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05 16:49:27.231 ThaliTest[956:3119714] server session: not connected Apple-Iphone5s-1
,2016-01-05T15:49:27.781Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-05T15:49:27.846Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T15:49:27.847Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T15:49:27.848Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T15:49:27.849Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:49:27.850 ThaliTest[956:3118804] jxcore: disconnect
2016-01-05 16:49:27.850 ThaliTest[956:3118804] client session: disconnectFromPeer: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:27.851 ThaliTest[956:3118804] client session: disconnect
2016-01-05 16:49:27.851 ThaliTest[956:3118804] client session: stateChange:2->0 Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:27.858 ThaliTest[956:3118804] jxcore: disconnect: success
2016-01-05T15:49:27.858Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.xC8Jhw==
---- round done--------
startWithNextDevice
device[3]: Apple-Ipho,ne5s-1.lzdGtw==
2016-01-05T15:49:27.859Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.lzdGtw==
2016-01-05T15:49:27.859Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.lzdGtw==
2016-01-05T15:49:27.859Z SendDataConnecto,r.js: do connect now
2016-01-05 16:49:27.860 ThaliTest[956:3118804] jxcore: connect Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:49:27.860 ThaliTest[956:3118804] client session: connect
2016-01-05 16:49:27.860 ThaliTest[956:3118804] client session: stateChan,ge:0->1 Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:49:30.982 ThaliTest[956:3119714] client session: connected
2016-01-05 16:49:30.982 ThaliTest[956:3119714] client session: stateChange:1->2 Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:49:30.994 ThaliTest[956:3119724] client session: fireConnectCallback: Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:49:30.994 ThaliTest[956:3119724] jxcore: connect: success
2016-01-05T15:49:30.995Z SendDataConnector.js: CLIENT connected to 63771,, error: null
2016-01-05T15:49:30.995Z SendDataConnector.js: CLIENT starting client 
2016-01-05 16:49:30.997 ThaliTest[956:3118619] client: relay established
2016-01-05 16:49:30.998 ThaliTest[956:3118619] client: new accepted socket: 0x19c2a7e0
,2016-01-05T15:49:31.010Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T15:49:31.577Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-05T15:49:31.630Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T15:49:32.133Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T15:49:32.134Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T15:49:32.135Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T15:49:32.136Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:49:32.137 ThaliTest[956:3118804] jxcore: disconnect
2016-01-05 16:49:32.137 ThaliTest[956:3118804] client session: disconnectFromPeer: Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:49:32.137 ThaliTest[956:3118804] client session: disconnect
2016-01-05 16:49:32.137 ThaliTest[956:3118804] client session: stateChange:2->0 Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:49:32.145 ThaliTest[956:3118804] jxcore: disconnect: success
2016-01-05T15:49:32.145Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.lzdGtw==
---- round done--------
startWithNextDevice
device[4]: Apple-Ipho,ne6-1.GJN/JA==
2016-01-05T15:49:32.146Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.GJN/JA==
2016-01-05T15:49:32.146Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.GJN/JA==
2016-01-05T15:49:32.146Z SendDataConnector.js: do connect now
,2016-01-05 16:49:32.147 ThaliTest[956:3118804] jxcore: connect Apple-Iphone6-1.GJN/JA==
2016-01-05 16:49:32.150 ThaliTest[956:3118804] client session: connect
2016-01-05 16:49:32.150 ThaliTest[956:3118804] client session: stateChange:0->1 Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:35.112 ThaliTest[956:3118619] multipeer session: reset timer
2016-01-05 16:49:35.112 ThaliTest[956:3118619] multipeer session: stop timer
2016-01-05 16:49:35.112 ThaliTest[956:3118619] multipeer session: start timer: 0x19bb8630
2016-01-05 16:49:35.113 ThaliTest[956:3118619] server session: connect
2016-01-05 16:49:35.113 ThaliTest[956:3118619] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-05 16:49:35.119 ThaliTest[956:3118619] server: accepting invitation Apple-IpadAir2-1
,2016-01-05 16:49:36.048 ThaliTest[956:3119712] client session: connected
2016-01-05 16:49:36.048 ThaliTest[956:3119712] client session: stateChange:1->2 Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:36.067 ThaliTest[956:3119725] client session: fireConnectCallback: Apple-Iphone6-1.GJN/JA==
2016-01-05 16:49:36.067 ThaliTest[956:3119725] jxcore: connect: success
2016-01-05T15:49:36.068Z SendDataConnector.js: CLIENT connected to 63774, error: null
2016-01-05T15:49:36.068Z SendDataConnector.js: CLIENT starting client 
2016-01-05 16:49:36.070 ThaliTest[956:3118619] client: relay established
2016-01-05 16:49:36.070 ThaliTest[956:3118619] client: new accepted socket: 0x19bc83d0
,2016-01-05T15:49:36.083Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T15:49:36.590Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T15:49:36.602Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-05T15:49:36.616Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-05T15:49:36.631Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-05T15:49:36.645Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T15:49:36.660Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T15:49:36.661Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T15:49:36.663Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T15:49:36.663Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:49:36.664 ThaliTest[956:3118804] jxcore: disconnect
2016-01-05 16:49:36.664 ThaliTest[956:3118804] client session: disconnectFromPeer: Apple-Iphone6-1.GJN/JA==
2016-01-05 16:49:36.664 ThaliTest[956:3118804] client session: disconnect
2016-01-05 16:49:36.664 ThaliTest[956:3118804] client session: stateChange:2->0 Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:36.670 ThaliTest[956:3118804] jxcore: disconnect: success
2016-01-05T15:49:36.672Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.GJN/JA==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
2016-01-05T15:49:36.678Z SendDataConnector.js: CLIENT Stop now
2016-01-05T15:49:36.678Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:49:38.155 ThaliTest[956:3119712] server session: connected
2016-01-05 16:49:38.156 ThaliTest[956:3119712] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-05 16:49:38.175 ThaliTest[956:3118619] server relay: connected (to port: 63762)
,2016-01-05T15:49:38.186Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T15:49:38.423Z SendDataTCPServer.js: TCP/IP server has received 19426 bytes of data
,2016-01-05T15:49:38.438Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2016-01-05T15:49:38.453Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:49:38.666 ThaliTest[956:3119724] server session: not connected Apple-IpadAir2-1
,2016-01-05 16:50:05.044 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:50:05.076 ThaliTest[956:3118619] client: found peer: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:50:05.077 ThaliTest[956:3118619] client: found peer: Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:50:05.771 ThaliTest[956:3118619] client: found peer: Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:50:11.711 ThaliTest[956:3118619] multipeer session: reset timer
2016-01-05 16:50:11.711 ThaliTest[956:3118619] multipeer session: stop timer
2016-01-05 16:50:11.711 ThaliTest[956:3118619] multipeer session: start timer: 0x19bb8630
2016-01-,05 16:50:11.712 ThaliTest[956:3118619] server session: connect
,2016-01-05 16:50:11.712 ThaliTest[956:3118619] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-05 16:50:11.718 ThaliTest[956:3118619] server: accepting invitation Apple-Iphone6-1
,2016-01-05 16:50:13.898 ThaliTest[956:3119725] server session: connected
2016-01-05 16:50:13.898 ThaliTest[956:3119725] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-05 16:50:13.916 ThaliTest[956:3118619] server relay: connected (to port: 63762)
,2016-01-05T15:50:13.922Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T15:50:14.212Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2016-01-05T15:50:14.226Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2016-01-05T15:50:14.240Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-05T15:50:14.253Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2016-01-05T15:50:14.267Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:50:14.299 ThaliTest[956:3120099] server session: not connected Apple-Iphone6-1
,2016-01-05 16:50:40.468 ThaliTest[956:3118619] client: lost peer: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:50:40.469 ThaliTest[956:3118619] client session: onPeerLost: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:50:40.469 ThaliTest[956:3118619] client: lost p,eer: Apple-Iphone6-1.GJN/JA==
2016-01-05 16:50:40.470 ThaliTest[956:3118619] client session: onPeerLost: Apple-Iphone6-1.GJN/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xC8Jhw==","peerName":"(null)","peerAvailable":false}]
startWit,hNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.GJN/JA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2016-01-05 16:50:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:50:41.742 ThaliTest[956:3118619] client: found peer: Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:50:45.455 ThaliTest[956:3118619] client: lost peer: Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:50:45.455 ThaliTest[956:3118619] client session: onPeerLost: Apple-Iphone5s-1.lzdGtw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.lzdGtw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2016-01-05 16:51:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:51:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:52:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:52:41.712 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:53:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:53:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:54:11.712 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:54:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:55:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:55:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:56:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:56:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:57:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:57:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:58:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:58:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:59:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 16:59:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:00:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:00:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:01:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:01:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:02:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:02:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:03:11.712 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:03:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:04:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:04:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:05:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:05:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:06:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:06:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:07:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:07:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:08:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:08:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:09:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:09:41.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:10:11.713 ThaliTest[956:3118619] multipeer session: restart
,2016-01-05 17:10:41.713 ThaliTest[956:3118619] multipeer session: restart

```
