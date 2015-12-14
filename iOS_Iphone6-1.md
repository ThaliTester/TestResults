#### Test 5065027870036d7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/05418622-32F3-4660-887C-D9DD6DA29475/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/05418622-32F3-4660-887C-D9DD6DA29475/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/47ED0CB2-7A52-476E-902D-94E9523B9F92/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55975"
,(lldb)     command script import "/tmp/05418622-32F3-4660-887C-D9DD6DA29475/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 22:15:12.438 ThaliTest[964:1209051] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C6C4A30E-F6B2-487C-A83F-BFB756E24D27/Library/Cookies/Cookies.binarycookies
,2015-12-14 22:15:12.809 ThaliTest[964:1209051] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 22:15:12.811 ThaliTest[964:1209051] Multi-tasking -> Device: YES, App: YES
,2015-12-14 22:15:12.820 ThaliTest[964:1209051] Unlimited access to network resources
,2015-12-14 22:15:12.830 ThaliTest[964:1209051] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 22:15:21.960 ThaliTest[964:1209051] Resetting plugins due to page load.
,2015-12-14 22:15:25.460 ThaliTest[964:1209051] Finished load of: file:///var/mobile/Containers/Bundle/Application/47ED0CB2-7A52-476E-902D-94E9523B9F92/ThaliTest.app/www/index.html
,2015-12-14 22:15:25.646 ThaliTest[964:1209051] JXcore Cordova plugin initializing
,2015-12-14 22:15:25.649 ThaliTest[964:1209353] JXcore instance initializing
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
,2015-12-14 22:15:26.710 ThaliTest[964:1209051] THREAD WARNING: ['JXcore'] took '76.804932' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 22:20:18.818 ThaliTest[964:1209353] jxcore: startBroadcasting
,2015-12-14 22:20:18.837 ThaliTest[964:1209353] server: starting Apple-Iphone6-1_PT4552.QDCMPg==
,2015-12-14 22:20:18.842 ThaliTest[964:1209353] multipeer session: start timer: 0x15c7d260
,2015-12-14 22:20:18.858 ThaliTest[964:1209353] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4552
,2015-12-14 22:20:18.860 ThaliTest[964:1209353] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-14 22:20:19.558 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.QNnKyw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.QNnKyw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT2471.QNnKyw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2015-12-14 22:20:19.931 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.oXDKcw==
,teardown
,testFindPeers stopped
,2015-12-14 22:20:22.987 ThaliTest[964:1209353] jxcore: stopBroadcasting
2015-12-14 22:20:22.988 ThaliTest[964:1209353] THEMultipeerSession stopping peer
2015-12-14 22:20:22.988 ThaliTest[964:1209353] multipeer session: stop timer
2015-12-14 22:20:22.989, ThaliTest[964:1209353] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 58593
2015-12-14 22:20:23.054 ThaliTest[964:1209353] jxcore: startBroadcasting
,2015-12-14 22:20:23.059 ThaliTest[964:1209353] server: starting Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:20:23.059 ThaliTest[964:1209353] multipeer session: start timer: 0x15c7f9c0
2015-12-14 22:20:23.060 ThaliTest[964:1209353] THEMultipeerSession i,nitialized peer Apple-Iphone6-1_PT4552
2015-12-14 22:20:23.060 ThaliTest[964:1209353] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-14T21:20:23.069Z SendDataTCPServer.js: TCP/IP server is bound to port: 58593
,2015-12-14 22:20:24.081 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.081 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.QNnKyw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadA,ir2-1_PT1227.oXDKcw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14T21:20:24.086Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:24.088Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:24.088Z SendDataConnector.js: do connect now
2015-12-14 22:20:24.089 ThaliTest[964:1209353] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.090 ThaliTest[964:1209353] client session: connect
2015-12-14 22:20:24.090 ThaliTest[964:1209353] client session: stateChange:0->1 Apple-IpadAir2-1_PT1227.oXDKcw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.QNnKyw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 22:20:24.613 ThaliTest[964:1209051] client: lost peer: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.613 ThaliTest[964:1209051] client session: onPeerLost: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.614 ThaliTest[964:1209051] ,client session: onLinkFailure: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.614 ThaliTest[964:1209051] client session: disconnect
2015-12-14 22:20:24.614 ThaliTest[964:1209051] client session: stateChange:1->0 Apple-IpadAir2-1_PT1227.oXDKcw==
20,15-12-14 22:20:24.615 ThaliTest[964:1209051] client session: fireConnectCallback: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.615 ThaliTest[964:1209051] jxcore: connect: fail: Peer disconnected
2015-12-14 22:20:24.616 ThaliTest[964:1209051] clie,nt: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14T21:20:24.617Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-14T21:20:24.618Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T21:20:24.6,18Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.oXDKcw==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.1SWIqQ==","peerName":"(null)","peerAvailable":true}]
Found peer :, (null), Available: true
,2015-12-14 22:20:24.627 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
2015-12-14 22:20:24.629 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4984.xdA4DQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 22:20:26.696 ThaliTest[964:1209051] client: lost peer: Apple-Iphone5-1_PT2471.QNnKyw==
2015-12-14 22:20:26.696 ThaliTest[964:1209051] client session: onPeerLost: Apple-Iphone5-1_PT2471.QNnKyw==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5-1_PT2471.QNnKyw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14T21:20:29.624Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:29.625Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:34.628 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:20:34.629 ThaliTest[964:1209353] jxcore: disconnect: fail
2015-12-14T21:20:34.630Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw,==
2015-12-14T21:20:34.630Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:20:34.630Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:34.631Z SendDataConnector.js: do connect now
,2015-12-14 22:20:34.632 ThaliTest[964:1209353] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:34.633 ThaliTest[964:1209353] client: connect: unreachable Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:34.633 ThaliTest[964:1209353] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:20:34.634Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:20:34.635Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:20:34.635Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:39.636Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:39.637Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:44.642 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:20:44.642 ThaliTest[964:1209353] jxcore: disconnect: fail
2015-12-14T21:20:44.643Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw,==
2015-12-14T21:20:44.643Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:20:44.644Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:44.644Z SendDataConnector.js: do connect now
,2015-12-14 22:20:44.645 ThaliTest[964:1209353] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:44.646 ThaliTest[964:1209353] client: connect: unreachable Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:44.646 ThaliTest[964:1209353] jx,core: connect: fail: Peer unreachable
2015-12-14T21:20:44.647Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:20:44.647Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:20:44.648Z SendData,Connector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:49.653Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:49.654Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:53.061 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:20:54.655 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:20:54.656 ThaliTest[964:1209353] jxcore: disconnect: fail
2015-12-14T21:20:54.656Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw,==
2015-12-14T21:20:54.657Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:20:54.657Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14T21:20:54.657Z SendDataConnector.js: do connect now
,2015-12-14 22:20:54.658 ThaliTest[964:1209353] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:54.660 ThaliTest[964:1209353] client: connect: unreachable Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:54.660 ThaliTest[964:1209353] jxcore: connect: fail: Peer unreachable
2015-12-14T21:20:54.661Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer unreachable
2015-12-14T21:20:54.661Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:20:54.661Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:59.668Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:59.668Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:21:04.674 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:21:04.675 ThaliTest[964:1209353] jxcore: disconnect: fail
2015-12-14T21:21:04.675Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw,==
2015-12-14T21:21:04.676Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:21:04.676Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:21:04.676Z SendDataConnector.js: do connect now
2015-12-14 22:21:04.677 ThaliTest[964:1209353] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:21:04.678 ThaliTest[964:1209353] client: connect: unreachable Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:21:04.679 ThaliTest[964:1209353] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:21:04.679Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:21:04.680Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-14T21:21:04.682Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 22:21:04.683 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:21:04.684 ThaliTest[964:1209353] jxcore: disconnect: fail
2015-12-14T21:21:04.684Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14T21:21:04.688Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14T21:21:04.688Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14T21:21:04.689Z SendDataConnector.js: do connect now
,2015-12-14 22:21:04.691 ThaliTest[964:1209353] jxcore: connect Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:04.691 ThaliTest[964:1209353] client session: connect
2015-12-14 22:21:04.692 ThaliTest[964:1209353] client session: stateChange:0->1 Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:04.704 ThaliTest[964:1209051] client: lost peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:04.705 ThaliTest[964:1209051] client session: onPeerLost: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:04.705 ThaliTest[964:1209051] cl,ient session: onLinkFailure: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:04.705 ThaliTest[964:1209051] client session: disconnect
2015-12-14 22:21:04.706 ThaliTest[964:1209051] client session: stateChange:1->0 Apple-Iphone5-1_PT2471.1SWIqQ==
2015-1,2-14 22:21:04.706 ThaliTest[964:1209051] client session: fireConnectCallback: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:04.706 ThaliTest[964:1209051] jxcore: connect: fail: Peer disconnected
2015-12-14T21:21:04.708Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer disconnected
2015-12-14T21:21:04.709Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T21:21:04.709Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne5-1_PT2471.1SWIqQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-14T21:21:09.711Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14T21:21:09.711Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:14.719 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:21:14.720 ThaliTest[964:1209353] jxcore: disconnect: fail
2015-12-14T21:21:14.720Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.1SWIqQ=,=
2015-12-14T21:21:14.721Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT2471.1SWIqQ== with availability status: true
2015-12-14T21:21:14.721Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14T21:21:14.721Z SendDataConnector.js: do connect now
,2015-12-14 22:21:14.722 ThaliTest[964:1209353] jxcore: connect Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:14.723 ThaliTest[964:1209353] client: connect: unreachable Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:14.724 ThaliTest[964:1209353] jxco,re: connect: fail: Peer unreachable
2015-12-14T21:21:14.724Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:21:14.725Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:21:14.725Z SendDataCo,nnector.js: tryAgain afer: 5000 ms.
,2015-12-14 22:21:15.438 ThaliTest[964:1209051] multipeer session: reset timer
2015-12-14 22:21:15.438 ThaliTest[964:1209051] multipeer session: stop timer
2015-12-14 22:21:15.438 ThaliTest[964:1209051] multipeer session: start timer: 0x15c7f9c0
2015-12-14 22:21:15.439 ThaliTest[964:1209051] server session: connect
2015-12-14 22:21:15.439 ThaliTest[964:1209051] server session: stateChange:0->1 Apple-IpadAir2-1_PT1227
,2015-12-14 22:21:15.449 ThaliTest[964:1209051] server: accepting invitation Apple-IpadAir2-1_PT1227
,2015-12-14 22:21:18.247 ThaliTest[964:1209967] server session: connected
2015-12-14 22:21:18.247 ThaliTest[964:1209967] server session: stateChange:1->2 Apple-IpadAir2-1_PT1227
,2015-12-14 22:21:18.279 ThaliTest[964:1209051] server relay: connected (to port: 58593)
2015-12-14T21:21:18.279Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T21:21:18.574Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-14T21:21:18.589Z SendDataTCPServer.js: TCP/IP server has received 30518 bytes of data
,2015-12-14T21:21:18.608Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-14T21:21:18.626Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-14T21:21:18.641Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:21:18.709 ThaliTest[964:1210015] server session: not connected Apple-IpadAir2-1_PT1227
,2015-12-14T21:21:19.730Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14T21:21:19.731Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:24.737 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:21:24.737 ThaliTest[964:1209353] jxcore: disconnect: fail
2015-12-14T21:21:24.738Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.1SWIqQ=,=
2015-12-14T21:21:24.738Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT2471.1SWIqQ== with availability status: true
2015-12-14T21:21:24.738Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
201,5-12-14T21:21:24.739Z SendDataConnector.js: do connect now
,2015-12-14 22:21:24.739 ThaliTest[964:1209353] jxcore: connect Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:24.740 ThaliTest[964:1209353] client: connect: unreachable Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:24.741 ThaliTest[964:1209353] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:21:24.742Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:21:24.743Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:21:24.743Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:21:29.746Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14T21:21:29.746Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:34.749 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:21:34.749 ThaliTest[964:1209353] jxcore: disconnect: fail
2015-12-14T21:21:34.750Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.1SWIqQ=,=
2015-12-14T21:21:34.750Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT2471.1SWIqQ== with availability status: true
2015-12-14T21:21:34.750Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
201,5-12-14T21:21:34.751Z SendDataConnector.js: do connect now
,2015-12-14 22:21:34.751 ThaliTest[964:1209353] jxcore: connect Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:34.752 ThaliTest[964:1209353] client: connect: unreachable Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:34.753 ThaliTest[964:1209353] jxcore: connect: fail: Peer unreachable
2015-12-14T21:21:34.754Z SendDataConnector.js: CLIENT conne,cted to 0, error: Peer unreachable
2015-12-14T21:21:34.754Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:21:34.755Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:21:39.761Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14T21:21:39.761Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:44.774 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:21:44.775 ThaliTest[964:1209353] jxcore: disconnect: fail
2015-12-14T21:21:44.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.1SWIqQ=,=
2015-12-14T21:21:44.776Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT2471.1SWIqQ== with availability status: true
2015-12-14T21:21:44.776Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
201,5-12-14T21:21:44.776Z SendDataConnector.js: do connect now
,2015-12-14 22:21:44.778 ThaliTest[964:1209353] jxcore: connect Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:44.779 ThaliTest[964:1209353] client: connect: unreachable Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:44.780 ThaliTest[964:1209353] jxcore: connect: fail: Peer unreachable
2015-12-14T21:21:44.780Z SendDataConnector.js: CLIENT conne,cted to 0, error: Peer unreachable
2015-12-14T21:21:44.781Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-14T21:21:44.781Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 22:21:44.782 ThaliTest[964:1209353] jxcore: disconnect
,2015-12-14 22:21:44.783 ThaliTest[964:1209353] jxcore: disconnect: fail
,2015-12-14T21:21:44.784Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.1SWIqQ==
---- round done--------
startWithNextDevice
,device[3]: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:44.786Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:44.787Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:44.788Z SendDataConnector.js: do connect now
,2015-12-14 22:21:44.789 ThaliTest[964:1209353] jxcore: connect Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:44.789 ThaliTest[964:1209353] client session: connect
2015-12-14 22:21:44.790 ThaliTest[964:1209353] client session: stateChange:0->1 Apple-I,padAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:44.803 ThaliTest[964:1209051] client: lost peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:44.803 ThaliTest[964:1209051] client session: onPeerLost: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:44.803 ThaliTest[964:1209051] ,client session: onLinkFailure: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:44.804 ThaliTest[964:1209051] client session: disconnect
2015-12-14 22:21:44.804 ThaliTest[964:1209051] client session: stateChange:1->0 Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:44.858 ThaliTest[964:1209051] client session: fireConnectCallback: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:44.859 ThaliTest[964:1209051] jxcore: connect: fail: Peer disconnected
2015-12-14T21:21:44.860Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-14T21:21:44.860Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T21:21:44.860Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 22:21:45.440 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:21:45.478 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:45.479 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:45.481 ThaliTest[964:1209051] client: ,found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":true}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.1SWIqQ==","peerName":,"(null)","peerAvailable":true}]
,2015-12-14 22:21:46.489 ThaliTest[964:1209051] multipeer session: reset timer
2015-12-14 22:21:46.489 ThaliTest[964:1209051] multipeer session: stop timer
2015-12-14 22:21:46.490 ThaliTest[964:1209051] multipeer session: start timer: 0x15c7f9c0
2015-12-14 22:21:46.490 ThaliTest[964:1209051] server session: connect
2015-12-14 22:21:46.491 ThaliTest[964:1209051] server session: stateChange:0->1 Apple-Iphone5-1_PT2471
,2015-12-14 22:21:46.501 ThaliTest[964:1209051] server: accepting invitation Apple-Iphone5-1_PT2471
,2015-12-14 22:21:49.071 ThaliTest[964:1210085] server session: connected
,2015-12-14 22:21:49.071 ThaliTest[964:1210085] server session: stateChange:1->2 Apple-Iphone5-1_PT2471
,2015-12-14 22:21:49.135 ThaliTest[964:1209051] server relay: connected (to port: 58593)
,2015-12-14T21:21:49.146Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T21:21:49.646Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-14T21:21:49.723Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-14T21:21:49.738Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-14T21:21:49.764Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-14T21:21:49.780Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-14T21:21:49.796Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-14T21:21:49.861Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:49.862Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:50.413Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:21:50.618 ThaliTest[964:1210085] server session: not connected Apple-Iphone5-1_PT2471
,2015-12-14 22:21:52.901 ThaliTest[964:1209051] multipeer session: reset timer
2015-12-14 22:21:52.901 ThaliTest[964:1209051] multipeer session: stop timer
2015-12-14 22:21:52.901 ThaliTest[964:1209051] multipeer session: start timer: 0x15c7f9c0
2015-12-,14 22:21:52.902 ThaliTest[964:1209051] server session: connect
2015-12-14 22:21:52.902 ThaliTest[964:1209051] server session: stateChange:0->1 Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:52.911 ThaliTest[964:1209051] server: accepting invitation Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:54.868 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:21:54.869 ThaliTest[964:1209353] jxcore: disconnect: fail
2015-12-14T21:21:54.869Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.Q+hGxg,==
2015-12-14T21:21:54.870Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT1227.Q+hGxg== with availability status: true
2015-12-14T21:21:54.870Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:54.870Z SendDataConnector.js: do connect now
2015-12-14 22:21:54.871 ThaliTest[964:1209353] jxcore: connect Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:54.871 ThaliTest[964:1209353] client session: connect
2015-12-14 22:21:54.871 ,ThaliTest[964:1209353] client session: stateChange:0->1 Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:55.533 ThaliTest[964:1210117] server session: connected
2015-12-14 22:21:55.533 ThaliTest[964:1210117] server session: stateChange:1->2 Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:55.630 ThaliTest[964:1209051] server relay: connected (to port: 58593)
,2015-12-14T21:21:55.636Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T21:21:55.852Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T21:21:55.866Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-14T21:21:55.993Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-14T21:21:56.006Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-14T21:21:56.021Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-14T21:21:56.035Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-14T21:21:56.053Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:21:56.107 ThaliTest[964:1210086] server session: not connected Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:57.761 ThaliTest[964:1210079] client session: connected
2015-12-14 22:21:57.762 ThaliTest[964:1210079] client session: stateChange:1->2 Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:57.824 ThaliTest[964:1210082] client session: fireConnectCallback: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:57.824 ThaliTest[964:1210082] jxcore: connect: success
,2015-12-14T21:21:57.825Z SendDataConnector.js: CLIENT connected to 58602, error: null
2015-12-14T21:21:57.826Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 22:21:57.830 ThaliTest[964:1209051] client: relay established
2015-12-14 22:21:57.831 ThaliTest[964:1209051] client: new accepted socket: 0x15ba7300
,2015-12-14T21:21:57.845Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:21:58.152Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T21:21:58.165Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T21:21:58.165Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T21:21:58.165Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T21:21:58.165Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:58.166 ThaliTest[964:1209353] jxcore: disconnect
2015-12-14 22:21:58.166 ThaliTest[964:1209353] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:58.167 ThaliTest[964:1209353] client session: disconnec,t
2015-12-14 22:21:58.167 ThaliTest[964:1209353] client session: stateChange:2->0 Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:58.171 ThaliTest[964:1209353] jxcore: disconnect: success
2015-12-14T21:21:58.171Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
---- round done--------
startWithNextDevice
device[4]: App,le-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14T21:21:58.171Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14T21:21:58.171Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14T21:21:58.171Z SendDataConnector.js: do connect now
2015-12-14 22:21:58.172 ThaliTest[964:1209353] jxcore: connect Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:21:58.172 ThaliTest[964:1209353] client session: connect
2015-12-14 22:21:58.172 ThaliTest[964:1209353] client session: stateChange:0->1 Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:22:00.843 ThaliTest[964:1210082] client session: connected
2015-12-14 22:22:00.843 ThaliTest[964:1210082] client session: stateChange:1->2 Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:22:00.870 ThaliTest[964:1210117] client session: fireConnectCallback: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:22:00.870 ThaliTest[964:1210117] jxcore: connect: success
2015-12-14T21:22:00.871Z SendDataConnector.js: CLIENT connected t,o 58605, error: null
2015-12-14T21:22:00.872Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 22:22:00.876 ThaliTest[964:1209051] client: relay established
2015-12-14 22:22:00.877 ThaliTest[964:1209051] client: new accepted socket: 0x15ca8d80
,2015-12-14T21:22:00.889Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:22:01.231Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T21:22:01.244Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-14T21:22:01.294Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T21:22:01.295Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-14T21:22:01.295Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T21:22:01.295Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:22:01.296 ThaliTest[964:1209353] jxcore: disconnect
,2015-12-14 22:22:01.296 ThaliTest[964:1209353] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:22:01.297 ThaliTest[964:1209353] client session: disconnect
,2015-12-14 22:22:01.297 ThaliTest[964:1209353] client session: stateChange:2->0 Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:22:01.362 ThaliTest[964:1209353] jxcore: disconnect: success
,2015-12-14T21:22:01.363Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4984.xdA4DQ==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-14T21:22:01.366Z SendDataConnector.js: CLIENT Stop now
2015-12-14T21:22:01.366Z SendDataConnector.js: CLIENT closeClientSocket
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
,2015-12-14 22:22:15.491 ThaliTest[964:1209353] jxcore: startBroadcasting
2015-12-14 22:22:15.491 ThaliTest[964:1209353] jxcore: startBroadcasting: failure
weAreDoneNow
done, now sending data to server
,done, now sending data to server
,2015-12-14 22:22:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:22:22.939 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:22:22.940 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:22:22.940 ThaliTest[964:1209051] client: ,found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:22:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:22:52.942 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:22:52.943 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:22:52.944 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:23:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:23:22.942 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:23:22.942 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:23:22.944 ThaliTest[964:1209051] client: ,found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:23:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:23:52.940 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:23:52.941 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:23:52.941 ThaliTest[964:1209051] client: ,found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:24:10.378 ThaliTest[964:1209051] client: lost peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:24:10.378 ThaliTest[964:1209051] client session: onPeerLost: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:24:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:24:22.937 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:24:22.939 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:24:23.196 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:24:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:24:52.941 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:24:52.943 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:24:54.294 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:25:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:25:22.940 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:25:22.941 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:25:24.032 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:25:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:25:52.939 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:25:52.939 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:25:53.926 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:26:22.902 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:26:22.938 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:26:22.940 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:26:22.941 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:26:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:26:52.939 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:26:52.941 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:26:52.941 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:27:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:27:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:27:52.937 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:27:52.939 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:27:53.375 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:28:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:28:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:28:52.943 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:28:52.943 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:28:52.943 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:29:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:29:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:29:52.938 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:29:52.938 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:29:53.243 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:30:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:30:22.941 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:30:22.942 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:30:27.260 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:30:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:30:52.940 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:30:52.944 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:30:53.574 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:31:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:31:22.941 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:31:23.367 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:31:24.002 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:31:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:31:52.941 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:31:52.945 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:31:52.946 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:32:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:32:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:32:52.939 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:32:52.940 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:32:52.941 ThaliTest[964:1209051] client: ,found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:33:04.815 ThaliTest[964:1209051] client: lost peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:33:04.815 ThaliTest[964:1209051] client session: onPeerLost: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:33:07.804 ThaliTest[964:1209051] client: lost peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:33:07.805 ThaliTest[964:1209051] client session: onPeerLost: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:33:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:33:22.933 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:33:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:33:52.933 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:34:05.503 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:34:05.911 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:34:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:34:22.936 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:34:22.938 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:34:38.945 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:34:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:34:52.939 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:34:52.948 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:34:52.948 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:35:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:35:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:35:52.938 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:35:52.940 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:35:52.940 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:36:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:36:22.946 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:36:22.949 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:36:22.949 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:36:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:36:52.942 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:36:52.942 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:36:52.945 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:37:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:37:22.939 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:37:22.940 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:37:22.941 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:37:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:37:52.940 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:37:52.941 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:37:52.942 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:38:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:38:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:38:52.938 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:38:52.940 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:38:52.941 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,timeout now
,2015-12-14 22:39:22.902 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:39:22.939 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:39:22.940 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:39:22.940 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:39:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:39:52.942 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:39:52.942 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:39:52.946 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:40:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:40:22.939 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:40:22.942 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:40:22.942 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:40:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:40:52.940 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:40:52.941 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:40:52.942 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:41:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:41:22.942 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:41:22.947 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:41:22.948 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:41:52.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:42:22.903 ThaliTest[964:1209051] multipeer session: restart
,2015-12-14 22:42:22.937 ThaliTest[964:1209051] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:42:22.937 ThaliTest[964:1209051] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:42:22.939 ThaliTest[964:1209051] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==

```
