#### Test 5507315224df3aa_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D135839A-459A-438B-A2FF-BEC37484171F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D135839A-459A-438B-A2FF-BEC37484171F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AD80508C-947F-4559-BB95-77FEBA4D5927/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65052"
,(lldb)     command script import "/tmp/D135839A-459A-438B-A2FF-BEC37484171F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 16:43:39.601 ThaliTest[1328:2889723] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/67609170-937C-43E1-9059-A664B22538FD/Library/Cookies/Cookies.binarycookies
,2016-01-05 16:43:39.966 ThaliTest[1328:2889723] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 16:43:39.967 ThaliTest[1328:2889723] Multi-tasking -> Device: YES, App: YES
,2016-01-05 16:43:39.976 ThaliTest[1328:2889723] Unlimited access to network resources
,2016-01-05 16:43:39.985 ThaliTest[1328:2889723] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 16:43:49.167 ThaliTest[1328:2889723] Resetting plugins due to page load.
,2016-01-05 16:43:52.798 ThaliTest[1328:2889723] Finished load of: file:///var/mobile/Containers/Bundle/Application/AD80508C-947F-4559-BB95-77FEBA4D5927/ThaliTest.app/www/index.html
,2016-01-05 16:43:52.947 ThaliTest[1328:2889723] JXcore Cordova plugin initializing
,2016-01-05 16:43:52.948 ThaliTest[1328:2889962] JXcore instance initializing
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
,2016-01-05 16:43:53.939 ThaliTest[1328:2889723] THREAD WARNING: ['JXcore'] took '70.277832' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 16:48:42.041 ThaliTest[1328:2889962] jxcore: startBroadcasting
,2016-01-05 16:48:42.058 ThaliTest[1328:2889962] server: starting Apple-IpadAir2-1.S4dItg==
,2016-01-05 16:48:42.061 ThaliTest[1328:2889962] multipeer session: start timer: 0x14fa4980
2016-01-05 16:48:42.063 ThaliTest[1328:2889962] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-05 16:48:42.063 ThaliTest[1328:2889962] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-05 16:48:43.150 ThaliTest[1328:2889723] client: found peer: Apple-Iphone6-1.DocMgw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DocMgw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1.DocMgw==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-05 16:48:45.241 ThaliTest[1328:2889723] client: found peer: Apple-Iphone5-1.uykjrA==
,teardown
,testFindPeers stopped
,2016-01-05 16:48:45.439 ThaliTest[1328:2889962] jxcore: stopBroadcasting
,2016-01-05 16:48:45.440 ThaliTest[1328:2889962] THEMultipeerSession stopping peer
,2016-01-05 16:48:45.440 ThaliTest[1328:2889962] multipeer session: stop timer
,2016-01-05 16:48:45.441 ThaliTest[1328:2889962] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 63499
,2016-01-05 16:48:45.502 ThaliTest[1328:2889962] jxcore: startBroadcasting
,2016-01-05 16:48:45.505 ThaliTest[1328:2889962] server: starting Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:48:45.505 ThaliTest[1328:2889962] multipeer session: start timer: 0x14fa8470
2016-01-05 16:48:45.506 ThaliTest[1328:2889962] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-05 16:48:45.506 ThaliTest[1328:2889962] jxcore: start,Broadcasting: success
StartBroadcasting started ok
,null
,2016-01-05T15:48:45.510Z SendDataTCPServer.js: TCP/IP server is bound to port: 63499
,2016-01-05 16:48:45.980 ThaliTest[1328:2889723] client: found peer: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:45.981 ThaliTest[1328:2889723] client: found peer: Apple-IpadAir2-1.S4dItg==
2016-01-05 16:48:45.982 ThaliTest[1328:2889723] client: found peer:, Apple-Iphone5-1.uykjrA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DocMgw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone6-1.DocMgw==
,2016-01-05T15:48:45.986Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05T15:48:45.988Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DocMgw==
2016-01-05T15:48:45.988Z SendDataConnector.js: do connect now
,2016-01-05 16:48:45.989 ThaliTest[1328:2889962] jxcore: connect Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:45.990 ThaliTest[1328:2889962] client session: connect
,2016-01-05 16:48:45.990 ThaliTest[1328:2889962] client session: stateChange:0->1 Apple-Iphone6-1.DocMgw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.S4dItg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.uykjrA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 16:48:46.566 ThaliTest[1328:2889723] client: lost peer: Apple-IpadAir2-1.S4dItg==
2016-01-05 16:48:46.566 ThaliTest[1328:2889723] client session: onPeerLost: Apple-IpadAir2-1.S4dItg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.S4dItg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-05 16:48:47.084 ThaliTest[1328:2889723] client: found peer: Apple-Iphone5s-1.lzdGtw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.lzdGtw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 16:48:47.883 ThaliTest[1328:2889723] client: lost peer: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:47.883 ThaliTest[1328:2889723] client session: onPeerLost: Apple-Iphone6-1.DocMgw==
,2016-01-05 16:48:47.883 ThaliTest[1328:2889723] client session: onLinkFailure: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:47.884 ThaliTest[1328:2889723] client session: disconnect
,2016-01-05 16:48:47.884 ThaliTest[1328:2889723] client session: stateChange:1->0 Apple-Iphone6-1.DocMgw==
,2016-01-05 16:48:47.949 ThaliTest[1328:2889723] client session: fireConnectCallback: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:47.950 ThaliTest[1328:2889723] jxcore: connect: fail: Peer disconnected
,2016-01-05 16:48:47.950 ThaliTest[1328:2889723] client: found peer: Apple-Iphone6-1.GJN/JA==
,2016-01-05T15:48:47.952Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2016-01-05T15:48:47.953Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-05T15:48:47.954Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DocMgw==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.GJN/JA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 16:48:48.766 ThaliTest[1328:2889723] client: found peer: Apple-Iphone5-1.cnOsew==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.cnOsew==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 16:48:50.997 ThaliTest[1328:2889723] client: lost peer: Apple-Iphone5-1.uykjrA==
2016-01-05 16:48:50.998 ThaliTest[1328:2889723] client session: onPeerLost: Apple-Iphone5-1.uykjrA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.uykjrA==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-05T15:48:52.954Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DocMgw==
,2016-01-05T15:48:52.955Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05 16:48:57.957 ThaliTest[1328:2889962] jxcore: disconnect
,2016-01-05 16:48:57.957 ThaliTest[1328:2889962] jxcore: disconnect: fail
,2016-01-05T15:48:57.958Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DocMgw==
,2016-01-05T15:48:57.959Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.DocMgw== with availability status: true
,2016-01-05T15:48:57.959Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05T15:48:57.960Z SendDataConnector.js: do connect now
,2016-01-05 16:48:57.961 ThaliTest[1328:2889962] jxcore: connect Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:57.961 ThaliTest[1328:2889962] client: connect: unreachable Apple-Iphone6-1.DocMgw==
,2016-01-05 16:48:57.962 ThaliTest[1328:2889962] jxcore: connect: fail: Peer unreachable
,2016-01-05T15:48:57.962Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T15:48:57.963Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T15:48:57.964Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:02.964Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:02.965Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:07.968 ThaliTest[1328:2889962] jxcore: disconnect
,2016-01-05 16:49:07.968 ThaliTest[1328:2889962] jxcore: disconnect: fail
,2016-01-05T15:49:07.969Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:07.970Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.DocMgw== with availability status: true
2016-01-05T15:49:07.970Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:07.971Z SendDataConnector.js: do connect now
,2016-01-05 16:49:07.972 ThaliTest[1328:2889962] jxcore: connect Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:07.972 ThaliTest[1328:2889962] client: connect: unreachable Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:07.973 ThaliTest[1328:2889962] jxcore: connect: fail: Peer unreachable
,2016-01-05T15:49:07.974Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T15:49:07.974Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T15:49:07.975Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:12.976Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:12.976Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:15.507 ThaliTest[1328:2889723] multipeer session: restart
,2016-01-05 16:49:15.533 ThaliTest[1328:2889723] client: found peer: Apple-Iphone6-1.GJN/JA==
2016-01-05 16:49:15.533 ThaliTest[1328:2889723] client: found peer: Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:49:15.534 ThaliTest[1328:2889723] client: found peer: Apple-Iphone5-1.cnOsew==
,2016-01-05 16:49:17.985 ThaliTest[1328:2889962] jxcore: disconnect
,2016-01-05 16:49:17.986 ThaliTest[1328:2889962] jxcore: disconnect: fail
,2016-01-05T15:49:17.987Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:17.987Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.DocMgw== with availability status: true
,2016-01-05T15:49:17.988Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:17.989Z SendDataConnector.js: do connect now
,2016-01-05 16:49:17.990 ThaliTest[1328:2889962] jxcore: connect Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:17.990 ThaliTest[1328:2889962] client: connect: unreachable Apple-Iphone6-1.DocMgw==
2016-01-05 16:49:17.991 ThaliTest[1328:2889962] jxcore: connect: fail: Peer unreachable
,2016-01-05T15:49:17.991Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T15:49:17.992Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T15:49:17.993Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:22.999Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:23.000Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:27.393 ThaliTest[1328:2889723] multipeer session: reset timer
2016-01-05 16:49:27.393 ThaliTest[1328:2889723] multipeer session: stop timer
2016-01-05 16:49:27.394 ThaliTest[1328:2889723] multipeer session: start timer: 0x14fa8470
2016-01-05 16:49:27.394 ThaliTest[1328:2889723] server session: connect
2016-01-05 16:49:27.394 ThaliTest[1328:2889723] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-05 16:49:27.401 ThaliTest[1328:2889723] server: accepting invitation Apple-Iphone5-1
,2016-01-05 16:49:28.004 ThaliTest[1328:2889962] jxcore: disconnect
2016-01-05 16:49:28.004 ThaliTest[1328:2889962] jxcore: disconnect: fail
2016-01-05T15:49:28.005Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DocMgw==
20,16-01-05T15:49:28.005Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.DocMgw== with availability status: true
2016-01-05T15:49:28.005Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DocMgw==
2016-01-05T15:49:28.005Z SendDataConnector.js: do connect now
,2016-01-05 16:49:28.005 ThaliTest[1328:2889962] jxcore: connect Apple-Iphone6-1.DocMgw==
2016-01-05 16:49:28.006 ThaliTest[1328:2889962] client: connect: unreachable Apple-Iphone6-1.DocMgw==
2016-01-05 16:49:28.006 ThaliTest[1328:2889962] jxcore: connect: fail: Peer unreachable
2016-01-05T15:49:28.006Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:49:28.006Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2016-01-05T15:49:28.007Z SendDataConnector.js: CLIENT Stop now
,2016-01-05 16:49:28.007 ThaliTest[1328:2889962] jxcore: disconnect
2016-01-05 16:49:28.007 ThaliTest[1328:2889962] jxcore: disconnect: fail
2016-01-05T15:49:28.007Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DocMgw==
---- round done--------
startWithNextDevice
,device[2]: Apple-Iphone5s-1.lzdGtw==
2016-01-05T15:49:28.008Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.lzdGtw==
,2016-01-05T15:49:28.008Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.lzdGtw==
,2016-01-05T15:49:28.009Z SendDataConnector.js: do connect now
,2016-01-05 16:49:28.009 ThaliTest[1328:2889962] jxcore: connect Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:49:28.009 ThaliTest[1328:2889962] client session: connect
2016-01-05 16:49:28.009 ThaliTest[1328:2889962] client session: stateChange:0->1 Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:49:30.350 ThaliTest[1328:2890625] server session: connected
2016-01-05 16:49:30.350 ThaliTest[1328:2890625] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-05 16:49:30.359 ThaliTest[1328:2889723] server relay: connected (to port: 63499)
,2016-01-05T15:49:30.371Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05 16:49:30.413 ThaliTest[1328:2889723] multipeer session: reset timer
2016-01-05 16:49:30.413 ThaliTest[1328:2889723] multipeer session: stop timer
2016-01-05 16:49:30.414 ThaliTest[1328:2889723] multipeer session: start timer: 0x14fa8470
,2016-01-05 16:49:30.414 ThaliTest[1328:2889723] server session: connect
2016-01-05 16:49:30.414 ThaliTest[1328:2889723] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-05 16:49:30.422 ThaliTest[1328:2889723] server: accepting invitation Apple-Iphone5s-1
,2016-01-05T15:49:30.903Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-05T15:49:30.928Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2016-01-05T15:49:30.942Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-05T15:49:30.956Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-05T15:49:30.992Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:49:31.052 ThaliTest[1328:2890624] server session: not connected Apple-Iphone5-1
,2016-01-05 16:49:32.042 ThaliTest[1328:2890652] client session: connected
2016-01-05 16:49:32.042 ThaliTest[1328:2890652] client session: stateChange:1->2 Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:49:32.046 ThaliTest[1328:2890652] client session: fireConnectCallback: Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:49:32.046 ThaliTest[1328:2890652] jxcore: connect: success
,2016-01-05T15:49:32.048Z SendDataConnector.js: CLIENT connected to 63505, error: null
,2016-01-05T15:49:32.048Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 16:49:32.052 ThaliTest[1328:2889723] client: relay established
2016-01-05 16:49:32.052 ThaliTest[1328:2889723] client: new accepted socket: 0x16e62080
,2016-01-05T15:49:32.067Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T15:49:32.431Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-05T15:49:32.442Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-05T15:49:32.468Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-05T15:49:32.481Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T15:49:32.481Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-05T15:49:32.481Z SendDataConnector.js: CLIENT Stop now
2016-01-05T15:49:32.482Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:49:32.482 ThaliTest[1328:2889962] jxcore: disconnect
,2016-01-05 16:49:32.483 ThaliTest[1328:2889962] client session: disconnectFromPeer: Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:49:32.483 ThaliTest[1328:2889962] client session: disconnect
,2016-01-05 16:49:32.483 ThaliTest[1328:2889962] client session: stateChange:2->0 Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:49:32.486 ThaliTest[1328:2889962] jxcore: disconnect: success
2016-01-05T15:49:32.486Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.lzdGtw==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone6-1.GJN/JA==
2016-01-05T15:49:32.486Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.GJN/JA==
2016-01-05T15:49:32.487Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.GJN/JA==
,2016-01-05T15:49:32.487Z SendDataConnector.js: do connect now
,2016-01-05 16:49:32.487 ThaliTest[1328:2889962] jxcore: connect Apple-Iphone6-1.GJN/JA==
2016-01-05 16:49:32.487 ThaliTest[1328:2889962] client session: connect
2016-01-05 16:49:32.487 ThaliTest[1328:2889962] client session: stateChange:0->1 Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:34.017 ThaliTest[1328:2890624] server session: connected
2016-01-05 16:49:34.017 ThaliTest[1328:2890624] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-05 16:49:34.030 ThaliTest[1328:2889723] server relay: connected (to port: 63499)
,2016-01-05T15:49:34.034Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T15:49:34.463Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2016-01-05T15:49:34.477Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2016-01-05T15:49:34.503Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-05T15:49:34.527Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:49:34.559 ThaliTest[1328:2890653] server session: not connected Apple-Iphone5s-1
,2016-01-05 16:49:37.638 ThaliTest[1328:2890660] client session: connected
2016-01-05 16:49:37.639 ThaliTest[1328:2890660] client session: stateChange:1->2 Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:37.643 ThaliTest[1328:2890653] client session: fireConnectCallback: Apple-Iphone6-1.GJN/JA==
2016-01-05 16:49:37.643 ThaliTest[1328:2890653] jxcore: connect: success
2016-01-05T15:49:37.645Z SendDataConnector.js: CLIENT connected to 63509, error: null
,2016-01-05T15:49:37.645Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 16:49:37.648 ThaliTest[1328:2889723] client: relay established
2016-01-05 16:49:37.648 ThaliTest[1328:2889723] client: new accepted socket: 0x16da7d50
,2016-01-05T15:49:37.662Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T15:49:38.167Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T15:49:38.180Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-05T15:49:38.206Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T15:49:38.220Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T15:49:38.220Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-05T15:49:38.220Z SendDataConnector.js: CLIENT Stop now
2016-01-05T15:49:38.220Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-05 16:49:38.221 ThaliTest[1328:2889962] jxcore: disconnect
2016-01-05 16:49:38.221 ThaliTest[1328:2889962] client session: disconnectFromPeer: Apple-Iphone6-1.GJN/JA==
2016-01-05 16:49:38.221, ThaliTest[1328:2889962] client session: disconnect
2016-01-05 16:49:38.221 ThaliTest[1328:2889962] client session: stateChange:2->0 Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:38.231 ThaliTest[1328:2889962] jxcore: disconnect: success
,2016-01-05T15:49:38.232Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.GJN/JA==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5-1.cnOsew==
2016-01-05T15:49:38.234Z SendDataConnector.js: Start called w,ith peer Apple-Iphone5-1.cnOsew==
2016-01-05T15:49:38.234Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.cnOsew==
2016-01-05T15:49:38.235Z SendDataConnector.js: do connect now
2016-01-05 16:49:38.235 ThaliTest[1328:2889962] jxcore: connect Apple-Iphone5-1.cnOsew==
2016-01-05 16:49:38.235 ThaliTest[1328:2889962] client session: connect
2016-01-05 16:49:38.235 ThaliTest[1328:2889962] client session: stateChange:0->1 Apple-Iphone5-1.cnOsew==
,2016-01-05 16:49:41.312 ThaliTest[1328:2890653] client session: connected
2016-01-05 16:49:41.313 ThaliTest[1328:2890653] client session: stateChange:1->2 Apple-Iphone5-1.cnOsew==
,2016-01-05 16:49:41.316 ThaliTest[1328:2890653] client session: fireConnectCallback: Apple-Iphone5-1.cnOsew==
2016-01-05 16:49:41.316 ThaliTest[1328:2890653] jxcore: connect: success
,2016-01-05T15:49:41.318Z SendDataConnector.js: CLIENT connected to 63512, error: null
,2016-01-05T15:49:41.318Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 16:49:41.322 ThaliTest[1328:2889723] client: relay established
,2016-01-05 16:49:41.322 ThaliTest[1328:2889723] client: new accepted socket: 0x14fb98c0
,2016-01-05T15:49:41.334Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T15:49:41.584Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T15:49:41.800Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T15:49:41.801Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-05T15:49:41.801Z SendDataConnector.js: CLIENT Stop now
2016-01-05T15:49:41.801Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:49:41.802 ThaliTest[1328:2889962] jxcore: disconnect
,2016-01-05 16:49:41.802 ThaliTest[1328:2889962] client session: disconnectFromPeer: Apple-Iphone5-1.cnOsew==
,2016-01-05 16:49:41.802 ThaliTest[1328:2889962] client session: disconnect
,2016-01-05 16:49:41.803 ThaliTest[1328:2889962] client session: stateChange:2->0 Apple-Iphone5-1.cnOsew==
,2016-01-05 16:49:41.806 ThaliTest[1328:2889962] jxcore: disconnect: success
,2016-01-05T15:49:41.807Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.cnOsew==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-05T15:49:41.811Z SendDataConnector.js: CLIENT Stop now
2016-01-05T15:49:41.811Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:50:00.401 ThaliTest[1328:2889723] multipeer session: restart
,2016-01-05 16:50:00.430 ThaliTest[1328:2889723] client: found peer: Apple-Iphone6-1.GJN/JA==
2016-01-05 16:50:00.430 ThaliTest[1328:2889723] client: found peer: Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:50:00.432 ThaliTest[1328:2889723] client: found peer: Apple-Iphone5-1.cnOsew==
,2016-01-05 16:50:08.041 ThaliTest[1328:2889723] multipeer session: reset timer
2016-01-05 16:50:08.041 ThaliTest[1328:2889723] multipeer session: stop timer
2016-01-05 16:50:08.042 ThaliTest[1328:2889723] multipeer session: start timer: 0x14fa8470
,2016-01-05 16:50:08.042 ThaliTest[1328:2889723] server session: connect
2016-01-05 16:50:08.042 ThaliTest[1328:2889723] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-05 16:50:08.048 ThaliTest[1328:2889723] server: accepting invitation Apple-Iphone6-1
,2016-01-05 16:50:11.195 ThaliTest[1328:2890731] server session: connected
2016-01-05 16:50:11.195 ThaliTest[1328:2890731] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-05 16:50:11.219 ThaliTest[1328:2889723] server relay: connected (to port: 63499)
,2016-01-05T15:50:11.222Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T15:50:11.506Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-05T15:50:11.523Z SendDataTCPServer.js: TCP/IP server has received 54608 bytes of data
,2016-01-05T15:50:11.541Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:50:11.590 ThaliTest[1328:2890768] server session: not connected Apple-Iphone6-1
,2016-01-05 16:50:38.043 ThaliTest[1328:2889723] multipeer session: restart
,2016-01-05 16:50:38.074 ThaliTest[1328:2889723] client: found peer: Apple-Iphone6-1.GJN/JA==
2016-01-05 16:50:38.074 ThaliTest[1328:2889723] client: found peer: Apple-Iphone5-1.cnOsew==
2016-01-05 16:50:38.075 ThaliTest[1328:2889723] client: found peer: Apple-Iphone5s-1.lzdGtw==
,teardown
,testSendData stopped
,2016-01-05 16:50:42.358 ThaliTest[1328:2889962] jxcore: stopBroadcasting
,2016-01-05 16:50:42.359 ThaliTest[1328:2889962] THEMultipeerSession stopping peer
,2016-01-05 16:50:42.359 ThaliTest[1328:2889962] multipeer session: stop timer
,2016-01-05 16:50:42.360 ThaliTest[1328:2889962] server session: disconnect
2016-01-05 16:50:42.361 ThaliTest[1328:2889962] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-05 16:50:42.438 ThaliTest[1328:2889962] server session: disconnect
,2016-01-05 16:50:42.439 ThaliTest[1328:2889962] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-05 16:50:42.444 ThaliTest[1328:2889962] server session: disconnect
,2016-01-05 16:50:42.447 ThaliTest[1328:2889962] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-05 16:50:42.454 ThaliTest[1328:2889962] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2016-01-05T15:50:42.476Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T15:50:42.478Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T15:50:42.480Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T15:50:42.481Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
