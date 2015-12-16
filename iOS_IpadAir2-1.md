#### Test 50650278b44f053_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A3610194-3D98-4C0C-B3C4-E4E061F47926/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A3610194-3D98-4C0C-B3C4-E4E061F47926/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A6E1A97E-1FC2-43BC-B653-2B8A820FF3EE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58799"
,(lldb)     command script import "/tmp/A3610194-3D98-4C0C-B3C4-E4E061F47926/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 18:41:16.183 ThaliTest[300:120740] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A16360CF-25FE-4F15-9DE2-02EF72B5B8B9/Library/Cookies/Cookies.binarycookies
,2015-12-16 18:41:16.575 ThaliTest[300:120740] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 18:41:16.576 ThaliTest[300:120740] Multi-tasking -> Device: YES, App: YES
,2015-12-16 18:41:16.585 ThaliTest[300:120740] Unlimited access to network resources
,2015-12-16 18:41:16.594 ThaliTest[300:120740] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 18:41:25.515 ThaliTest[300:120740] Resetting plugins due to page load.
,2015-12-16 18:41:28.812 ThaliTest[300:120740] Finished load of: file:///var/mobile/Containers/Bundle/Application/A6E1A97E-1FC2-43BC-B653-2B8A820FF3EE/ThaliTest.app/www/index.html
,2015-12-16 18:41:28.975 ThaliTest[300:120740] JXcore Cordova plugin initializing
,2015-12-16 18:41:28.976 ThaliTest[300:120976] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-16 18:41:29.962 ThaliTest[300:120740] THREAD WARNING: ['JXcore'] took '69.874023' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 18:46:34.728 ThaliTest[300:120976] jxcore: startBroadcasting
,2015-12-16 18:46:34.744 ThaliTest[300:120976] server: starting Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:34.745 ThaliTest[300:120976] multipeer session: start timer: 0x17b09950
2015-12-16 18:46:34.746 ThaliTest[300:120976] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT5378
,2015-12-16 18:46:34.747 ThaliTest[300:120976] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-16 18:46:35.847 ThaliTest[300:120740] client: found peer: Apple-Iphone5-1_PT6761.ad6Xvw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6761.ad6Xvw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT6761.ad6Xvw==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-16 18:46:35.932 ThaliTest[300:120740] client: found peer: Apple-Iphone6-1_PT3143.XZF93A==
,teardown
,testFindPeers stopped
,2015-12-16 18:46:37.301 ThaliTest[300:120976] jxcore: stopBroadcasting
,2015-12-16 18:46:37.301 ThaliTest[300:120976] THEMultipeerSession stopping peer
,2015-12-16 18:46:37.302 ThaliTest[300:120976] multipeer session: stop timer
,2015-12-16 18:46:37.303 ThaliTest[300:120976] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 50587
,2015-12-16 18:46:37.406 ThaliTest[300:120976] jxcore: startBroadcasting
,2015-12-16 18:46:37.409 ThaliTest[300:120976] server: starting Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:46:37.410 ThaliTest[300:120976] multipeer session: start timer: 0x15f63f90
2015-12-16 18:46:37.411 ThaliTest[300:120976] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT5378
2015-12-16 18:46:37.412 ThaliTest[300:120976] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2015-12-16T17:46:37.418Z SendDataTCPServer.js: TCP/IP server is bound to port: 50587
,2015-12-16 18:46:38.423 ThaliTest[300:120740] client: found peer: Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:38.424 ThaliTest[300:120740] client: found peer: Apple-Iphone6-1_PT3143.XZF93A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.xtukLA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:38.429Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:38.430Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:38.430Z SendDataConnector.js: do connect now
,2015-12-16 18:46:38.431 ThaliTest[300:120976] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:38.432 ThaliTest[300:120976] client session: connect
,2015-12-16 18:46:38.433 ThaliTest[300:120976] client session: stateChange:0->1 Apple-IpadAir2-1_PT5378.xtukLA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.XZF93A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 18:46:38.613 ThaliTest[300:120740] client: lost peer: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:38.613 ThaliTest[300:120740] client session: onPeerLost: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:38.614 ThaliTest[300:120740] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:38.614 ThaliTest[300:120740] client session: disconnect
2015-12-16 18:46:38.614 ThaliTest[300:120740] client session: stateChange:1->0 Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:38.615 ThaliTest[300:120740] client session: fireConnectCallback: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:38.615 ThaliTest[300:120740] jxcore: connect: fail: Peer disconnected
2015-12-16 18:46:38.615 ThaliTest[300:120740] clien,t: lost peer: Apple-Iphone6-1_PT3143.XZF93A==
2015-12-16 18:46:38.616 ThaliTest[300:120740] client session: onPeerLost: Apple-Iphone6-1_PT3143.XZF93A==
,2015-12-16T17:46:38.618Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-16 18:46:38.620 ThaliTest[300:120740] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16 18:46:38.620 ThaliTest[300:120740] client: found peer: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16T17:46:38.619Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T17:46:38.621Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.xtukLA==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.XZF93A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6682.xKUG+w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2015-12-16 18:46:38.628 ThaliTest[300:120740] client: found peer: Apple-Iphone6-1_PT3143.YUb0wA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6761.1E6mhw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.YUb0wA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16T17:46:43.628Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:43.629Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:48.639 ThaliTest[300:120976] jxcore: disconnect
2015-12-16 18:46:48.639 ThaliTest[300:120976] jxcore: disconnect: fail
,2015-12-16T17:46:48.640Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:48.641Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
2015-12-16T17:46:48.641Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:48.641Z SendDataConnector.js: do connect now
,2015-12-16 18:46:48.642 ThaliTest[300:120976] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:48.643 ThaliTest[300:120976] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:48.644 ThaliTest[300:120976] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:46:48.644Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T17:46:48.645Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-16T17:46:48.645Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:46:53.653Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:53.654Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:58.664 ThaliTest[300:120976] jxcore: disconnect
,2015-12-16 18:46:58.664 ThaliTest[300:120976] jxcore: disconnect: fail
,2015-12-16T17:46:58.665Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:58.666Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
,2015-12-16T17:46:58.666Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:58.667Z SendDataConnector.js: do connect now
,2015-12-16 18:46:58.668 ThaliTest[300:120976] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:58.669 ThaliTest[300:120976] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:58.669 ThaliTest[300:120976] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:46:58.670Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T17:46:58.671Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-16T17:46:58.671Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:47:03.676Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16T17:47:03.676Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:07.413 ThaliTest[300:120740] multipeer session: restart
,2015-12-16 18:47:07.454 ThaliTest[300:120740] client: found peer: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:07.454 ThaliTest[300:120740] client: found peer: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:07.454 ThaliTest[300:120740] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:08.682 ThaliTest[300:120976] jxcore: disconnect
,2015-12-16 18:47:08.682 ThaliTest[300:120976] jxcore: disconnect: fail
,2015-12-16T17:47:08.683Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:47:08.684Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
2015-12-16T17:47:08.684Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16T17:47:08.685Z SendDataConnector.js: do connect now
,2015-12-16 18:47:08.686 ThaliTest[300:120976] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:08.686 ThaliTest[300:120976] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:08.687 ThaliTest[300:120976] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:47:08.687Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T17:47:08.688Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-16T17:47:08.688Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:47:13.701Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:47:13.702Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:18.707 ThaliTest[300:120976] jxcore: disconnect
,2015-12-16 18:47:18.707 ThaliTest[300:120976] jxcore: disconnect: fail
,2015-12-16T17:47:18.708Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:47:18.709Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
,2015-12-16T17:47:18.709Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:47:18.710Z SendDataConnector.js: do connect now
,2015-12-16 18:47:18.711 ThaliTest[300:120976] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:18.711 ThaliTest[300:120976] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:18.712 ThaliTest[300:120976] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:47:18.713Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T17:47:18.714Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-16T17:47:18.716Z SendDataConnector.js: CLIENT Stop now
,2015-12-16 18:47:18.717 ThaliTest[300:120976] jxcore: disconnect
,2015-12-16 18:47:18.717 ThaliTest[300:120976] jxcore: disconnect: fail
2015-12-16T17:47:18.718Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16T17:47:18.721Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16T17:47:18.722Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16T17:47:18.722Z SendDataConnector.js: do connect now
,2015-12-16 18:47:18.723 ThaliTest[300:120976] jxcore: connect Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:18.724 ThaliTest[300:120976] client session: connect
,2015-12-16 18:47:18.724 ThaliTest[300:120976] client session: stateChange:0->1 Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:21.809 ThaliTest[300:121696] client session: connected
,2015-12-16 18:47:21.809 ThaliTest[300:121696] client session: stateChange:1->2 Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:21.829 ThaliTest[300:121692] client session: fireConnectCallback: Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:21.829 ThaliTest[300:121692] jxcore: connect: success
,2015-12-16T17:47:21.831Z SendDataConnector.js: CLIENT connected to 50594, error: null
,2015-12-16T17:47:21.832Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 18:47:21.834 ThaliTest[300:120740] client: relay established
2015-12-16 18:47:21.835 ThaliTest[300:120740] client: new accepted socket: 0x17d7f860
,2015-12-16T17:47:21.851Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T17:47:22.141Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-16T17:47:22.190Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-16T17:47:22.203Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-16T17:47:22.252Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-16T17:47:22.252Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-16T17:47:22.253Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T17:47:22.253Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:47:22.254 ThaliTest[300:120976] jxcore: disconnect
,2015-12-16 18:47:22.254 ThaliTest[300:120976] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:22.254 ThaliTest[300:120976] client session: disconnect
,2015-12-16 18:47:22.255 ThaliTest[300:120976] client session: stateChange:2->0 Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:22.259 ThaliTest[300:120976] jxcore: disconnect: success
,2015-12-16T17:47:22.259Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6682.xKUG+w==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16T17:47:22.261Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:22.261Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:22.261Z SendDataConnector.js: do connect now
,2015-12-16 18:47:22.262 ThaliTest[300:120976] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:22.262 ThaliTest[300:120976] client session: connect
,2015-12-16 18:47:22.262 ThaliTest[300:120976] client session: stateChange:0->1 Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:29.470 ThaliTest[300:121713] client session: connected
2015-12-16 18:47:29.470 ThaliTest[300:121713] client session: stateChange:1->2 Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:29.482 ThaliTest[300:121692] client session: fireConnectCallback: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:29.482 ThaliTest[300:121692] jxcore: connect: success
,2015-12-16T17:47:29.483Z SendDataConnector.js: CLIENT connected to 50597, error: null
,2015-12-16T17:47:29.484Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 18:47:29.486 ThaliTest[300:120740] client: relay established
,2015-12-16 18:47:29.487 ThaliTest[300:120740] client: new accepted socket: 0x17d81a00
,2015-12-16T17:47:29.500Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T17:47:30.085Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T17:47:30.085Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T17:47:30.086Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T17:47:30.086Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:47:30.087 ThaliTest[300:120976] jxcore: disconnect
,2015-12-16 18:47:30.087 ThaliTest[300:120976] client session: disconnectFromPeer: Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:30.087 ThaliTest[300:120976] client session: disconnect
2015-12-16 18:47:30.088 ThaliTest[300:120976] client session: stateChange:2->0 Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:30.093 ThaliTest[300:120976] jxcore: disconnect: success
2015-12-16T17:47:30.093Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.1E6mhw==
---- round done--------
startWithNextDevice
device[4]: Apple,-Iphone6-1_PT3143.YUb0wA==
2015-12-16T17:47:30.094Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16T17:47:30.094Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16T17:47:30.094Z SendDataConnector.js: do connect now
2015-12-16 18:47:30.095 ThaliTest[300:120976] jxcore: connect Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:30.095 ThaliTest[300:120976] client session: connect
2015-12-16 18:47:30.096 ThaliTest[300:120976] client session: stateChange:0->1 Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:30.155 ThaliTest[300:120740] multipeer session: reset timer
2015-12-16 18:47:30.155 ThaliTest[300:120740] multipeer session: stop timer
2015-12-16 18:47:30.155 ThaliTest[300:120740] multipeer session: start timer: 0x15f63f90
2015-12-16 18:47:30.155 ThaliTest[300:120740] server session: connect
2015-12-16 18:47:30.156 ThaliTest[300:120740] server session: stateChange:0->1 Apple-Iphone5-1_PT6761
,2015-12-16 18:47:30.159 ThaliTest[300:120740] server: accepting invitation Apple-Iphone5-1_PT6761
,2015-12-16 18:47:32.930 ThaliTest[300:121696] client session: connected
2015-12-16 18:47:32.931 ThaliTest[300:121696] client session: stateChange:1->2 Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:32.936 ThaliTest[300:121782] client session: fireConnectCallback: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:32.936 ThaliTest[300:121782] jxcore: connect: success
2015-12-16T17:47:32.937Z SendDataConnector.js: CLIENT connected to 50600, error: null
,2015-12-16T17:47:32.938Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 18:47:32.941 ThaliTest[300:120740] client: relay established
2015-12-16 18:47:32.942 ThaliTest[300:120740] client: new accepted socket: 0x17d85d90
,2015-12-16T17:47:32.954Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T17:47:33.269Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-16T17:47:33.269Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T17:47:33.270Z SendDataConnector.js: CLIENT Stop now
2015-12-16T17:47:33.270Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:47:33.270 ThaliTest[300:120976] jxcore: disconnect
,2015-12-16 18:47:33.271 ThaliTest[300:120976] client session: disconnectFromPeer: Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:33.271 ThaliTest[300:120976] client session: disconnect
,2015-12-16 18:47:33.271 ThaliTest[300:120976] client session: stateChange:2->0 Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:33.275 ThaliTest[300:120976] jxcore: disconnect: success
,2015-12-16T17:47:33.276Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3143.YUb0wA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-16T17:47:33.280Z SendDataConnector.js: CLIENT Stop now
2015-12-16T17:47:33.280Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:47:33.664 ThaliTest[300:121696] server session: connected
2015-12-16 18:47:33.664 ThaliTest[300:121696] server session: stateChange:1->2 Apple-Iphone5-1_PT6761
,2015-12-16 18:47:33.686 ThaliTest[300:120740] server relay: connected (to port: 50587)
,2015-12-16T17:47:33.696Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T17:47:34.206Z SendDataTCPServer.js: TCP/IP server has received 17378 bytes of data
,2015-12-16T17:47:34.221Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-16T17:47:34.249Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-16T17:47:34.266Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-16T17:47:34.283Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 18:47:34.358 ThaliTest[300:121713] server session: not connected Apple-Iphone5-1_PT6761
,2015-12-16 18:47:37.439 ThaliTest[300:120740] client: lost peer: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:37.440 ThaliTest[300:120740] client session: onPeerLost: Apple-Iphone6-1_PT3143.YUb0wA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.YUb0wA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-16 18:48:00.157 ThaliTest[300:120740] multipeer session: restart
,2015-12-16 18:48:00.184 ThaliTest[300:120740] client: found peer: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:48:00.185 ThaliTest[300:120740] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.YUb0wA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-16 18:48:06.748 ThaliTest[300:120740] multipeer session: reset timer
2015-12-16 18:48:06.748 ThaliTest[300:120740] multipeer session: stop timer
2015-12-16 18:48:06.748 ThaliTest[300:120740] multipeer session: start timer: 0x15f63f90
,2015-12-16 18:48:06.749 ThaliTest[300:120740] server session: connect
2015-12-16 18:48:06.749 ThaliTest[300:120740] server session: stateChange:0->1 Apple-Iphone6-1_PT3143
,2015-12-16 18:48:06.756 ThaliTest[300:120740] server: accepting invitation Apple-Iphone6-1_PT3143
,2015-12-16 18:48:09.431 ThaliTest[300:121855] server session: connected
2015-12-16 18:48:09.431 ThaliTest[300:121855] server session: stateChange:1->2 Apple-Iphone6-1_PT3143
,2015-12-16 18:48:09.437 ThaliTest[300:120740] server relay: connected (to port: 50587)
,2015-12-16T17:48:09.443Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T17:48:09.709Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-16T17:48:09.725Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-16T17:48:09.753Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-16T17:48:09.768Z SendDataTCPServer.js: TCP/IP server has received 74176 bytes of data
,2015-12-16T17:48:09.784Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 18:48:09.825 ThaliTest[300:121913] server session: not connected Apple-Iphone6-1_PT3143
,2015-12-16 18:48:27.984 ThaliTest[300:120740] client: found peer: Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:48:36.750 ThaliTest[300:120740] multipeer session: restart
,2015-12-16 18:48:36.785 ThaliTest[300:120740] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16 18:48:36.786 ThaliTest[300:120740] client: found peer: Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:48:36.794 ThaliTest[300:120740] client: found peer: Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:48:50.997 ThaliTest[300:120740] multipeer session: reset timer
2015-12-16 18:48:50.998 ThaliTest[300:120740] multipeer session: stop timer
,2015-12-16 18:48:50.998 ThaliTest[300:120740] multipeer session: start timer: 0x15f63f90
,2015-12-16 18:48:50.998 ThaliTest[300:120740] server session: connect
2015-12-16 18:48:50.999 ThaliTest[300:120740] server session: stateChange:0->1 Apple-Iphone5s-1_PT6682
,2015-12-16 18:48:51.006 ThaliTest[300:120740] server: accepting invitation Apple-Iphone5s-1_PT6682
,2015-12-16 18:48:54.952 ThaliTest[300:121995] server session: connected
2015-12-16 18:48:54.952 ThaliTest[300:121995] server session: stateChange:1->2 Apple-Iphone5s-1_PT6682
,2015-12-16 18:48:54.958 ThaliTest[300:120740] server relay: connected (to port: 50587)
,2015-12-16T17:48:54.964Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T17:48:55.375Z SendDataTCPServer.js: TCP/IP server has received 17378 bytes of data
,2015-12-16T17:48:55.392Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-16T17:48:55.408Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-16T17:48:55.424Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 18:48:55.461 ThaliTest[300:121995] server session: not connected Apple-Iphone5s-1_PT6682
,teardown
,testSendData stopped
,2015-12-16 18:48:56.267 ThaliTest[300:120976] jxcore: stopBroadcasting
2015-12-16 18:48:56.267 ThaliTest[300:120976] THEMultipeerSession stopping peer
,2015-12-16 18:48:56.268 ThaliTest[300:120976] multipeer session: stop timer
,2015-12-16 18:48:56.270 ThaliTest[300:120976] server session: disconnect
2015-12-16 18:48:56.270 ThaliTest[300:120976] server session: stateChange:2->0 Apple-Iphone5s-1_PT6682
,2015-12-16 18:48:56.287 ThaliTest[300:120976] server session: disconnect
2015-12-16 18:48:56.288 ThaliTest[300:120976] server session: stateChange:2->0 Apple-Iphone5-1_PT6761
,2015-12-16 18:48:56.358 ThaliTest[300:120976] server session: disconnect
2015-12-16 18:48:56.358 ThaliTest[300:120976] server session: stateChange:2->0 Apple-Iphone6-1_PT3143
,2015-12-16 18:48:56.362 ThaliTest[300:120976] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-16T17:48:56.382Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T17:48:56.383Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T17:48:56.385Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T17:48:56.385Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
