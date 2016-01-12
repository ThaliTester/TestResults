#### Test 55742142a5c2fdb_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B384E54A-FCB6-41E4-A927-9E64286801EA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/B384E54A-FCB6-41E4-A927-9E64286801EA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C5A15802-067C-4E5C-B168-F9BC5AF88C46/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53463"
,(lldb)     command script import "/tmp/B384E54A-FCB6-41E4-A927-9E64286801EA/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-12 13:13:24.892 ThaliTest[1297:4191412] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2A025286-E531-4830-850B-C605EFD1D1F6/Library/Cookies/Cookies.binarycookies
,2016-01-12 13:13:25.004 ThaliTest[1297:4191412] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-12 13:13:25.006 ThaliTest[1297:4191412] Multi-tasking -> Device: YES, App: YES
,2016-01-12 13:13:25.011 ThaliTest[1297:4191412] Unlimited access to network resources
,2016-01-12 13:13:25.023 ThaliTest[1297:4191412] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-12 13:13:30.965 ThaliTest[1297:4191412] Resetting plugins due to page load.
,2016-01-12 13:13:33.050 ThaliTest[1297:4191412] Finished load of: file:///var/mobile/Containers/Bundle/Application/C5A15802-067C-4E5C-B168-F9BC5AF88C46/ThaliTest.app/www/index.html
,2016-01-12 13:13:33.266 ThaliTest[1297:4191412] JXcore Cordova plugin initializing
,2016-01-12 13:13:33.267 ThaliTest[1297:4191540] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
found test : ./testFindPeers.js
,found test : ./testSendData.js
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
2016-01-12 13:19:31.030 ThaliTest[1297:4191540] jxcore: startBroadcasting
,2016-01-12 13:19:31.040 ThaliTest[1297:4191540] server: starting Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:31.041 ThaliTest[1297:4191540] multipeer session: start timer: 0x1b34fdf0
2016-01-12 13:19:31.041 ThaliTest[1297:4191540] THEMultipeerSession initi,alized peer Apple-Iphone5-1
2016-01-12 13:19:31.041 ThaliTest[1297:4191540] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-12 13:19:32.087 ThaliTest[1297:4191412] client: found peer: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:32.089 ThaliTest[1297:4191412] client: found peer: Apple-Iphone6-1.vdOTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.+FhoNw,==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1.+FhoNw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-12 13:19:32.396 ThaliTest[1297:4191412] client: found peer: Apple-IpadAir2-1.hA+i5Q==
,teardown
testFindPeers stopped
2016-01-12 13:19:33.065 ThaliTest[1297:4191540] jxcore: stopBroadcasting
2016-01-12 13:19:33.065 ThaliTest[1297:4191540] THEMultipeerSession stopping peer
2016-01-12 13:19:33.065 ThaliTest[1297:4191540] multipeer session: stop timer
2016-01-12 13:19:33.066 ThaliTest[1297:4191540] jxcore: stopBroadcasting: success
StopBroadcasting went ok
--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 51793
,2016-01-12 13:19:33.106 ThaliTest[1297:4191540] jxcore: startBroadcasting
,2016-01-12 13:19:33.124 ThaliTest[1297:4191540] server: starting Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:19:33.136 ThaliTest[1297:4191540] multipeer session: start timer: 0x1b3502c0
,2016-01-12 13:19:33.144 ThaliTest[1297:4191540] THEMultipeerSession initialized peer Apple-Iphone5-1
,2016-01-12 13:19:33.149 ThaliTest[1297:4191540] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-12 13:19:33.157 ThaliTest[1297:4191412] client: found peer: Apple-Iphone5-1.IBb4nw==
null
2016-01-12T12:19:33.159Z SendDataTCPServer.js: TCP/IP server is bound to port: 51793
2016-01-12 13:19:33.160 ThaliTest[1297:4191412] client: found peer: Ap,ple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:33.162 ThaliTest[1297:4191412] client: found peer: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:33.163 ThaliTest[1297:4191412] client: found peer: Apple-Iphone6-1.vdOTuw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.IBb4nw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1.IBb4nw==
,2016-01-12T12:19:33.172Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.IBb4nw==
,2016-01-12T12:19:33.173Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.IBb4nw==
,2016-01-12T12:19:33.173Z SendDataConnector.js: do connect now
,2016-01-12 13:19:33.174 ThaliTest[1297:4191540] jxcore: connect Apple-Iphone5-1.IBb4nw==
,2016-01-12 13:19:33.175 ThaliTest[1297:4191540] client session: connect
,2016-01-12 13:19:33.176 ThaliTest[1297:4191540] client session: stateChange:0->1 Apple-Iphone5-1.IBb4nw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.+FhoNw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hA+i5Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.vdOTuw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-12 13:19:34.418 ThaliTest[1297:4191412] client: lost peer: Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:34.419 ThaliTest[1297:4191412] client session: onPeerLost: Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:34.419 ThaliTest[1297:4191412] client sessio,n: onLinkFailure: Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:34.419 ThaliTest[1297:4191412] client session: disconnect
2016-01-12 13:19:34.419 ThaliTest[1297:4191412] client session: stateChange:1->0 Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:34.420 Thali,Test[1297:4191412] client session: fireConnectCallback: Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:34.420 ThaliTest[1297:4191412] jxcore: connect: fail: Peer disconnected
2016-01-12T12:19:34.421Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-12T12:19:34.422Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-12T12:19:34.422Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.IBb4nw==","peerName":",(null)","peerAvailable":false}]
,2016-01-12 13:19:34.742 ThaliTest[1297:4191412] client: lost peer: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:34.743 ThaliTest[1297:4191412] client session: onPeerLost: Apple-Iphone5s-1.+FhoNw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-,1.+FhoNw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2016-01-12 13:19:34.745 ThaliTest[1297:4191412] client: lost peer: Apple-Iphone6-1.vdOTuw==
2016-01-12 13:19:34.745 ThaliTest[1297:4191412] client session: onP,eerLost: Apple-Iphone6-1.vdOTuw==
2016-01-12 13:19:34.746 ThaliTest[1297:4191412] client: lost peer: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:34.746 ThaliTest[1297:4191412] client session: onPeerLost: Apple-IpadAir2-1.hA+i5Q==
peerAvailabilityChanged ,[{"peerIdentifier":"Apple-Iphone6-1.vdOTuw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hA+i5Q==","peerName":"(null)","peerAvailable":false}]
Found peer, : (null), Available: false
,2016-01-12 13:19:34.797 ThaliTest[1297:4191412] client: found peer: Apple-IpadAir2-1.WKZK+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.WKZK+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2016-01-,12 13:19:34.798 ThaliTest[1297:4191412] client: found peer: Apple-Iphone6-1.56+AEA==
2016-01-12 13:19:34.800 ThaliTest[1297:4191412] client: found peer: Apple-Iphone5s-1.8kws4w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.56+AEA==","peer,Name":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.8kws4w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-12T12:19:39.429Z SendDataConnector.js: re-try now : Apple-Iphone5-1.IBb4nw==
2016-01-12T12:19:39.430Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.IBb4nw==
,2016-01-12 13:19:44.449 ThaliTest[1297:4191540] jxcore: disconnect
2016-01-12 13:19:44.450 ThaliTest[1297:4191540] jxcore: disconnect: fail
2016-01-12T12:19:44.450Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.IBb4nw==
20,16-01-12T12:19:44.450Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.IBb4nw== with availability status: true
2016-01-12T12:19:44.450Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.IBb4nw==
2016-01-12T12:19:44.45,1Z SendDataConnector.js: do connect now
2016-01-12 13:19:44.451 ThaliTest[1297:4191540] jxcore: connect Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:44.451 ThaliTest[1297:4191540] client: connect: unreachable Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:44.45,1 ThaliTest[1297:4191540] jxcore: connect: fail: Peer unreachable
2016-01-12T12:19:44.451Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:19:44.452Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-,01-12T12:19:44.452Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:19:49.475Z SendDataConnector.js: re-try now : Apple-Iphone5-1.IBb4nw==
,2016-01-12T12:19:49.475Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.IBb4nw==
,2016-01-12 13:19:54.484 ThaliTest[1297:4191540] jxcore: disconnect
2016-01-12 13:19:54.485 ThaliTest[1297:4191540] jxcore: disconnect: fail
2016-01-12T12:19:54.485Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.IBb4nw==
2016-01-12T12:19:54.485Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.IBb4nw== with availability status: true
2016-01-12T12:19:54.485Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.IBb4nw==
2016-01-12T12:19:54.48,5Z SendDataConnector.js: do connect now
2016-01-12 13:19:54.486 ThaliTest[1297:4191540] jxcore: connect Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:54.486 ThaliTest[1297:4191540] client: connect: unreachable Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:54.48,6 ThaliTest[1297:4191540] jxcore: connect: fail: Peer unreachable
2016-01-12T12:19:54.486Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:19:54.487Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-,01-12T12:19:54.487Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:19:59.498Z SendDataConnector.js: re-try now : Apple-Iphone5-1.IBb4nw==
2016-01-12T12:19:59.498Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.IBb4nw==
,2016-01-12 13:20:03.142 ThaliTest[1297:4191412] multipeer session: restart
,2016-01-12 13:20:03.174 ThaliTest[1297:4191412] client: found peer: Apple-Iphone5s-1.8kws4w==
2016-01-12 13:20:03.174 ThaliTest[1297:4191412] client: found peer: Apple-Iphone6-1.56+AEA==
2016-01-12 13:20:03.175 ThaliTest[1297:4191412] client: found peer: Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:04.505 ThaliTest[1297:4191540] jxcore: disconnect
2016-01-12 13:20:04.505 ThaliTest[1297:4191540] jxcore: disconnect: fail
2016-01-12T12:20:04.506Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.IBb4nw==
20,16-01-12T12:20:04.506Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.IBb4nw== with availability status: true
2016-01-12T12:20:04.506Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.IBb4nw==
2016-01-12T12:20:04.50,6Z SendDataConnector.js: do connect now
2016-01-12 13:20:04.507 ThaliTest[1297:4191540] jxcore: connect Apple-Iphone5-1.IBb4nw==
2016-01-12 13:20:04.507 ThaliTest[1297:4191540] client: connect: unreachable Apple-Iphone5-1.IBb4nw==
2016-01-12 13:20:04.50,7 ThaliTest[1297:4191540] jxcore: connect: fail: Peer unreachable
2016-01-12T12:20:04.507Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:20:04.507Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016,-,01-12T12:20:04.507Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:20:09.520Z SendDataConnector.js: re-try now : Apple-Iphone5-1.IBb4nw==
,2016-01-12T12:20:09.521Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.IBb4nw==
,2016-01-12 13:20:14.526 ThaliTest[1297:4191540] jxcore: disconnect
2016-01-12 13:20:14.526 ThaliTest[1297:4191540] jxcore: disconnect: fail
2016-01-12T12:20:14.526Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.IBb4nw==
20,16-01-12T12:20:14.527Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.IBb4nw== with availability status: true
2016-01-12T12:20:14.527Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.IBb4nw==
2016-01-12T12:20:14.52,7Z SendDataConnector.js: do connect now
2016-01-12 13:20:14.527 ThaliTest[1297:4191540] jxcore: connect Apple-Iphone5-1.IBb4nw==
2016-01-12 13:20:14.527 ThaliTest[1297:4191540] client: connect: unreachable Apple-Iphone5-1.IBb4nw==
2016-01-12 13:20:14.52,7 ThaliTest[1297:4191540] jxcore: connect: fail: Peer unreachable
2016-01-12T12:20:14.528Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:20:14.528Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRo,undDownNow
2016-01-12T12:20:14.531Z SendDataConnector.js: CLIENT Stop now
2016-01-12 13:20:14.532 ThaliTest[1297:4191540] jxcore: disconnect
2016-01-12 13:20:14.532 ThaliTest[1297:4191540] jxcore: disconnect: fail
,2016-01-12T12:20:14.532Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.IBb4nw==
---- round done--------
startWithNextDevice
device[2]: Apple-IpadAir2-1.WKZK+A==
2016-01-12T12:20:14.534Z SendDataConnector.js: Start called ,with peer Apple-IpadAir2-1.WKZK+A==
2016-01-12T12:20:14.535Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.WKZK+A==
2016-01-12T12:20:14.535Z SendDataConnector.js: do connect now
2016-01-12 13:20:14.535 ThaliTest[1297:4191540] jxcore:, connect Apple-IpadAir2-1.WKZK+A==
2016-01-12 13:20:14.535 ThaliTest[1297:4191540] client session: connect
2016-01-12 13:20:14.535 ThaliTest[1297:4191540] client session: stateChange:0->1 Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:14.750 ThaliTest[1297:4191412] multipeer session: reset timer
2016-01-12 13:20:14.751 ThaliTest[1297:4191412] multipeer session: stop timer
2016-01-12 13:20:14.751 ThaliTest[1297:4191412] multipeer session: start timer: 0x1b3502c0
2016-,01-12 13:20:14.751 ThaliTest[1297:4191412] server session: connect
2016-01-12 13:20:14.751 ThaliTest[1297:4191412] server session: stateChange:0->1 Apple-Iphone5s-1
2016-01-12 13:20:14.760 ThaliTest[1297:4191412] server: accepting invitation Apple-Iphone5s-1
,2016-01-12 13:20:15.195 ThaliTest[1297:4191412] multipeer session: reset timer
2016-01-12 13:20:15.195 ThaliTest[1297:4191412] multipeer session: stop timer
2016-01-12 13:20:15.196 ThaliTest[1297:4191412] multipeer session: start timer: 0x1b3502c0
2016-,01-12 13:20:15.196 ThaliTest[1297:4191412] server session: connect
2016-01-12 13:20:15.198 ThaliTest[1297:4191412] server session: stateChange:0->1 Apple-Iphone6-1
2016-01-12 13:20:15.204 ThaliTest[1297:4191412] server: accepting invitation Apple-Iphone6-1
,2016-01-12 13:20:17.300 ThaliTest[1297:4192261] server session: connected
2016-01-12 13:20:17.301 ThaliTest[1297:4192261] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-12T12:20:17.307Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12 13:20:17.309 ThaliTest[1297:4191412] server relay: connected (to port: 51793)
,2016-01-12T12:20:17.821Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-12T12:20:17.836Z SendDataTCPServer.js: TCP/IP server has received 19497 bytes of data
,2016-01-12T12:20:17.851Z SendDataTCPServer.js: TCP/IP server has received 38325 bytes of data
,2016-01-12T12:20:17.975Z SendDataTCPServer.js: TCP/IP server has received 58035 bytes of data
,2016-01-12T12:20:18.225Z SendDataTCPServer.js: TCP/IP server has received 64179 bytes of data
,2016-01-12T12:20:18.238Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:18.356 ThaliTest[1297:4192263] server session: not connected Apple-Iphone5s-1
2016-01-12 13:20:18.360 ThaliTest[1297:4192262] server session: connected
2016-01-12 13:20:18.361 ThaliTest[1297:4192262] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-12 13:20:18.416 ThaliTest[1297:4191412] server relay: connected (to port: 51793)
,2016-01-12T12:20:18.425Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12T12:20:18.810Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2016-01-12T12:20:18.824Z SendDataTCPServer.js: TCP/IP server has received 18118 bytes of data
,2016-01-12 13:20:18.829 ThaliTest[1297:4192262] client session: connected
,2016-01-12 13:20:18.833 ThaliTest[1297:4192262] client session: stateChange:1->2 Apple-IpadAir2-1.WKZK+A==
,2016-01-12T12:20:18.838Z SendDataTCPServer.js: TCP/IP server has received 34756 bytes of data
,2016-01-12 13:20:18.839 ThaliTest[1297:4192262] client session: fireConnectCallback: Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:18.841 ThaliTest[1297:4192262] jxcore: connect: success
,2016-01-12T12:20:18.845Z SendDataTCPServer.js: TCP/IP server has received 42705 bytes of data
,2016-01-12T12:20:18.846Z SendDataConnector.js: CLIENT connected to 51802, error: null
,2016-01-12T12:20:18.846Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:18.849 ThaliTest[1297:4191412] client: relay established
,2016-01-12 13:20:18.849 ThaliTest[1297:4191412] client: new accepted socket: 0x1b32bc40
,2016-01-12T12:20:18.861Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2016-01-12T12:20:18.864Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12T12:20:19.871Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12T12:20:19.934Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-12 13:20:19.998 ThaliTest[1297:4192319] server session: not connected Apple-Iphone6-1
,2016-01-12T12:20:20.255Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-12T12:20:20.535Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-12T12:20:20.535Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-12T12:20:20.536Z SendDataConnector.js: CLIENT Stop now
2016-01-12T12:20:2,0.536Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-12 13:20:20.537 ThaliTest[1297:4191540] jxcore: disconnect
2016-01-12 13:20:20.537 ThaliTest[1297:4191540] client session: disconnectFromPeer: Apple-IpadAir2-1.WKZK+A==
2016-01-12 13:20:20.53,7 ThaliTest[1297:4191540] client session: disconnect
2016-01-12 13:20:20.537 ThaliTest[1297:4191540] client session: stateChange:2->0 Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:20.552 ThaliTest[1297:4191540] jxcore: disconnect: success
2016-01-12T12:20:20.552Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.WKZK+A==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one6-1.56+AEA==
2016-01-12T12:20:20.554Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.56+AEA==
2016-01-12T12:20:20.554Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.56+AEA==
2016-01-12T12:20:20.554Z SendDataConnector.,js: do connect now
2016-01-12 13:20:20.554 ThaliTest[1297:4191540] jxcore: connect Apple-Iphone6-1.56+AEA==
2016-01-12 13:20:20.555 ThaliTest[1297:4191540] client session: connect
2016-01-12 13:20:20.555 ThaliTest[1297:4191540] client session: stateChan,ge:0->1 Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:23.598 ThaliTest[1297:4192319] client session: connected
2016-01-12 13:20:23.598 ThaliTest[1297:4192319] client session: stateChange:1->2 Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:23.654 ThaliTest[1297:4192263] client session: fireConnectCallback: Apple-Iphone6-1.56+AEA==
2016-01-12 13:20:23.656 ThaliTest[1297:4192263] jxcore: connect: success
2016-01-12T12:20:23.657Z SendDataConnector.js: CLIENT connected to 5180,5, error: null
2016-01-12T12:20:23.658Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:23.660 ThaliTest[1297:4191412] client: relay established
2016-01-12 13:20:23.660 ThaliTest[1297:4191412] client: new accepted socket: 0x1b4b44a0
,2016-01-12T12:20:23.671Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12 13:20:23.723 ThaliTest[1297:4191412] multipeer session: reset timer
2016-01-12 13:20:23.723 ThaliTest[1297:4191412] multipeer session: stop timer
2016-01-12 13:20:23.723 ThaliTest[1297:4191412] multipeer session: start timer: 0x1b3502c0
2016-01-12 13:20:23.723 ThaliTest[1297:4191412] server session: connect
2016-01-12 13:20:23.723 ThaliTest[1297:4191412] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-12 13:20:23.735 ThaliTest[1297:4191412] server: accepting invitation Apple-IpadAir2-1
,2016-01-12T12:20:25.095Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-12T12:20:25.107Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-12T12:20:25.154Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-12T12:20:25.238Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-12T12:20:25.296Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-12T12:20:25.297Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-12T12:20:25.298Z SendDataConnector.js: CLIENT Stop now
,2016-01-12T12:20:25.298Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-12 13:20:25.299 ThaliTest[1297:4191540] jxcore: disconnect
,2016-01-12 13:20:25.299 ThaliTest[1297:4191540] client session: disconnectFromPeer: Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:25.300 ThaliTest[1297:4191540] client session: disconnect
,2016-01-12 13:20:25.301 ThaliTest[1297:4191540] client session: stateChange:2->0 Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:25.314 ThaliTest[1297:4191540] jxcore: disconnect: success
,2016-01-12T12:20:25.318Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.56+AEA==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5s-1.8kws4w==
,2016-01-12T12:20:25.324Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.8kws4w==
,2016-01-12T12:20:25.325Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.8kws4w==
,2016-01-12T12:20:25.326Z SendDataConnector.js: do connect now
,2016-01-12 13:20:25.326 ThaliTest[1297:4191540] jxcore: connect Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:25.327 ThaliTest[1297:4191540] client session: connect
,2016-01-12 13:20:25.328 ThaliTest[1297:4191540] client session: stateChange:0->1 Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:26.932 ThaliTest[1297:4192276] server session: connected
2016-01-12 13:20:26.933 ThaliTest[1297:4192276] server session: stateChange:1->2 Apple-IpadAir2-1
2016-01-12 13:20:26.936 ThaliTest[1297:4191412] server relay: connected (to port: 51793)
2016-01-12T12:20:26.940Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12T12:20:27.391Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-12T12:20:27.405Z SendDataTCPServer.js: TCP/IP server has received 31613 bytes of data
,2016-01-12T12:20:27.418Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2016-01-12T12:20:27.432Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2016-01-12T12:20:27.456Z SendDataTCPServer.js: TCP/IP server has received 59059 bytes of data
,2016-01-12T12:20:27.469Z SendDataTCPServer.js: TCP/IP server has received 71175 bytes of data
,2016-01-12T12:20:27.481Z SendDataTCPServer.js: TCP/IP server has received 79935 bytes of data
,2016-01-12T12:20:27.495Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-12T12:20:27.519Z SendDataTCPServer.js: TCP/IP server has received 93075 bytes of data
,2016-01-12T12:20:27.532Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:27.596 ThaliTest[1297:4192262] server session: not connected Apple-IpadAir2-1
,2016-01-12 13:20:28.048 ThaliTest[1297:4192263] client session: connected
2016-01-12 13:20:28.050 ThaliTest[1297:4192263] client session: stateChange:1->2 Apple-Iphone5s-1.8kws4w==
2016-01-12 13:20:28.052 ThaliTest[1297:4192263] client session: fireConne,ctCallback: Apple-Iphone5s-1.8kws4w==
2016-01-12 13:20:28.053 ThaliTest[1297:4192263] jxcore: connect: success
2016-01-12T12:20:28.053Z SendDataConnector.js: CLIENT connected to 51809, error: null
2016-01-12T12:20:28.054Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:28.057 ThaliTest[1297:4191412] client: relay established
2016-01-12 13:20:28.057 ThaliTest[1297:4191412] client: new accepted socket: 0x1b31d770
,2016-01-12T12:20:28.068Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12T12:20:29.232Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-12T12:20:29.246Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-12T12:20:29.355Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-12T12:20:29.355Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-12T12:20:29.356Z SendDataConnector.js: CLIENT Stop now
,2016-01-12T12:20:29.356Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-12 13:20:29.357 ThaliTest[1297:4191540] jxcore: disconnect
,2016-01-12 13:20:29.358 ThaliTest[1297:4191540] client session: disconnectFromPeer: Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:29.359 ThaliTest[1297:4191540] client session: disconnect
,2016-01-12 13:20:29.359 ThaliTest[1297:4191540] client session: stateChange:2->0 Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:29.434 ThaliTest[1297:4191540] jxcore: disconnect: success
2016-01-12T12:20:29.434Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.8kws4w==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-12T12:20:29.451Z SendDataConnector.js: CLIENT Stop now
2016-01-12T12:20:29.451Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
2016-01-12 13:20:29.682 ThaliTest[1297:4191540] jxcore: stopBroadcasting
2016-01-12 13:20:29.682 ThaliTest[1297:4191540] THEMultipeerSession stopping peer
2016-01-12 13:20:29.682 ThaliTest[1297:4191540] multipeer session: stop timer,
2016-01-12 13:20:29.682 ThaliTest[1297:4191540] server session: disconnect
2016-01-12 13:20:29.683 ThaliTest[1297:4191540] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-12 13:20:29.688 ThaliTest[1297:4191540] server session: disconnect
2016-01-12 13:20:29.688 ThaliTest[1297:4191540] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-12 13:20:29.699 ThaliTest[1297:4191540] server session: disconnect
2016-01-12 13:20:29.699 ThaliTest[1297:4191540] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-12 13:20:29.720 ThaliTest[1297:4191540] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-12T12:20:29.736Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-12T12:20:29.738Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-12T12:20:29.738Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-12T12:20:29.739Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
