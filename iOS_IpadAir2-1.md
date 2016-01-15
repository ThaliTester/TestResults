#### Test 56204092c98eeae_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4D5B4E6B-8DA3-4A48-AABB-84DE5B323225/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4D5B4E6B-8DA3-4A48-AABB-84DE5B323225/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F78E19B0-B0CE-428B-AB49-CAE79844D0C4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56538"
,(lldb)     command script import "/tmp/4D5B4E6B-8DA3-4A48-AABB-84DE5B323225/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-15 19:42:57.207 ThaliTest[2094:4461743] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6DDB4C58-052D-4A2B-8038-B77D96F49E05/Library/Cookies/Cookies.binarycookies
,2016-01-15 19:42:57.431 ThaliTest[2094:4461743] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-15 19:42:57.432 ThaliTest[2094:4461743] Multi-tasking -> Device: YES, App: YES
,2016-01-15 19:42:57.438 ThaliTest[2094:4461743] Unlimited access to network resources
,2016-01-15 19:42:57.444 ThaliTest[2094:4461743] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-15 19:43:01.467 ThaliTest[2094:4461743] Resetting plugins due to page load.
,2016-01-15 19:43:02.762 ThaliTest[2094:4461743] Finished load of: file:///var/mobile/Containers/Bundle/Application/F78E19B0-B0CE-428B-AB49-CAE79844D0C4/ThaliTest.app/www/index.html
,2016-01-15 19:43:02.903 ThaliTest[2094:4461743] JXcore Cordova plugin initializing
2016-01-15 19:43:02.904 ThaliTest[2094:4461924] JXcore instance initializing
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
,2016-01-15 19:43:03.934 ThaliTest[2094:4461743] THREAD WARNING: ['JXcore'] took '61.388184' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
2016-01-15 19:48:23.031 ThaliTest[2094:4461924] jxcore: startBroadcasting
,2016-01-15 19:48:23.037 ThaliTest[2094:4461924] server: starting Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15 19:48:23.038 ThaliTest[2094:4461924] multipeer session: start timer: 0x19c7be00
2016-01-15 19:48:23.038 ThaliTest[2094:4461924] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6810
2016-01-15 19:48:23.038 ThaliTest[2094:4461924] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-15 19:48:30.403 ThaliTest[2094:4461743] client: found peer: Apple-Iphone5s-1_PT6477.NhmDbg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.NhmDbg==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5s-1_PT6477.NhmDbg==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-15 19:48:30.417 ThaliTest[2094:4461743] client: found peer: Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:48:30.543 ThaliTest[2094:4461743] client: found peer: Apple-Iphone6-1_PT3224.cXLr/Q==
,teardown
testFindPeers stopped
,2016-01-15 19:48:30.591 ThaliTest[2094:4461924] jxcore: stopBroadcasting
2016-01-15 19:48:30.591 ThaliTest[2094:4461924] THEMultipeerSession stopping peer
2016-01-15 19:48:30.591 ThaliTest[2094:4461924] multipeer session: stop timer
2016-01-15 19:48:30.591 ThaliTest[2094:4461924] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 52508
,2016-01-15 19:48:30.599 ThaliTest[2094:4461924] jxcore: startBroadcasting
,2016-01-15 19:48:30.600 ThaliTest[2094:4461924] server: starting Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:48:30.601 ThaliTest[2094:4461924] multipeer session: start timer: 0x19d5bb80
2016-01-15 19:48:30.601 ThaliTest[2094:4461924] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6810
2016-01-15 19:48:30.601 ThaliTest[2094:4461924] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2016-01-15T18:48:30.603Z SendDataTCPServer.js: TCP/IP server is bound to port: 52508
,2016-01-15 19:48:30.610 ThaliTest[2094:4461743] client: found peer: Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:30.610 ThaliTest[2094:4461743] client: found peer: Apple-Iphone5s-1_PT6477.NhmDbg==
2016-01-15 19:48:30.611 ThaliTest[2094:4461743] client: found peer: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:30.611 ThaliTest[2094:4461743] client: found peer: Apple-Iphone6-1_PT3224.cXLr/Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6810.+fMbbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15T18:48:30.612Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15T18:48:30.613Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15T18:48:30.613Z SendDataConnector.js: do connect now
,2016-01-15 19:48:30.613 ThaliTest[2094:4461924] jxcore: connect Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15 19:48:30.613 ThaliTest[2094:4461924] client session: connect
,2016-01-15 19:48:30.613 ThaliTest[2094:4461924] client session: stateChange:0->1 Apple-IpadAir2-1_PT6810.+fMbbA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.NhmDbg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5004.158h0w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3224.cXLr/Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-15 19:48:31.803 ThaliTest[2094:4461743] client: lost peer: Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:31.803 ThaliTest[2094:4461743] client session: onPeerLost: Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:31.803 ThaliTest[2094:446174,3] client session: onLinkFailure: Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:31.803 ThaliTest[2094:4461743] client session: disconnect
2016-01-15 19:48:31.803 ThaliTest[2094:4461743] client session: stateChange:1->0 Apple-IpadAir2-1_PT6810.+fMbbA=,=
2016-01-15 19:48:31.804 ThaliTest[2094:4461743] client session: fireConnectCallback: Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:31.804 ThaliTest[2094:4461743] jxcore: connect: fail: Peer disconnected
,2016-01-15T18:48:31.804Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2016-01-15T18:48:31.805Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-15T18:48:31.805Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6810.+fMbbA==","peerName":"(null)","peerAvailable":false}]
,2016-01-15 19:48:31.967 ThaliTest[2094:4461743] client: lost peer: Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:31.967 ThaliTest[2094:4461743] client session: onPeerLost: Apple-Iphone6-1_PT3224.cXLr/Q==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT3224.cXLr/Q==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-15 19:48:32.406 ThaliTest[2094:4461743] client: lost peer: Apple-Iphone5s-1_PT6477.NhmDbg==
2016-01-15 19:48:32.406 ThaliTest[2094:4461743] client session: onPeerLost: Apple-Iphone5s-1_PT6477.NhmDbg==
2016-01-15 19:48:32.406 ThaliTest[2094:4461743] client: found peer: Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:48:32.406 ThaliTest[2094:4461743] client: found peer: Apple-Iphone5-1_PT5004.rhpQQw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.NhmDbg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3224.81B+Sg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5004.rhpQQw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-15 19:48:32.438 ThaliTest[2094:4461743] client: found peer: Apple-Iphone5s-1_PT6477.TN0Czw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.TN0Czw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-15 19:48:34.108 ThaliTest[2094:4461743] client: lost peer: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:34.108 ThaliTest[2094:4461743] client session: onPeerLost: Apple-Iphone5-1_PT5004.158h0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5004.158h0w==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-15T18:48:36.815Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15T18:48:36.816Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15 19:48:41.826 ThaliTest[2094:4461924] jxcore: disconnect
2016-01-15 19:48:41.826 ThaliTest[2094:4461924] jxcore: disconnect: fail
,2016-01-15T18:48:41.826Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15T18:48:41.826Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT6810.+fMbbA== with availability status: true
2016-01-15T18:48:41.826Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6810.+fMbbA==
2016,-01-15T18:48:41.826Z SendDataConnector.js: do connect now
,2016-01-15 19:48:41.827 ThaliTest[2094:4461924] jxcore: connect Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:41.827 ThaliTest[2094:4461924] client: connect: unreachable Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:41.827 ThaliTest[2094:4461924], jxcore: connect: fail: Peer unreachable
2016-01-15T18:48:41.827Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:48:41.827Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-15T18:48:41.827Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:48:46.835Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15T18:48:46.835Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15 19:48:51.843 ThaliTest[2094:4461924] jxcore: disconnect
,2016-01-15 19:48:51.843 ThaliTest[2094:4461924] jxcore: disconnect: fail
,2016-01-15T18:48:51.843Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15T18:48:51.844Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT6810.+fMbbA== with availability status: true
2016-01-15T18:48:51.844Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15T18:48:51.844Z SendDataConnector.js: do connect now
2016-01-15 19:48:51.844 ThaliTest[2094:4461924] jxcore: connect Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15 19:48:51.844 ThaliTest[2094:4461924] client: connect: unreachable Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:51.844 ThaliTest[2094:4461924] jxcore: connect: fail: Peer unreachable
2016-01-15T18:48:51.844Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:48:51.845Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-15T18:48:51.845Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:48:56.854Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15T18:48:56.854Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15 19:49:00.606 ThaliTest[2094:4461743] multipeer session: restart
,2016-01-15 19:49:00.616 ThaliTest[2094:4461743] client: found peer: Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:00.617 ThaliTest[2094:4461743] client: found peer: Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:49:00.617 ThaliTest[2094:4461743] client: found peer: Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:01.856 ThaliTest[2094:4461924] jxcore: disconnect
2016-01-15 19:49:01.856 ThaliTest[2094:4461924] jxcore: disconnect: fail
2016-01-15T18:49:01.856Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15T18:49:01.856Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT6810.+fMbbA== with availability status: true
2016-01-15T18:49:01.857Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6810.+fMbbA==,
2016-01-15T18:49:01.857Z SendDataConnector.js: do connect now
2016-01-15 19:49:01.857 ThaliTest[2094:4461924] jxcore: connect Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:49:01.857 ThaliTest[2094:4461924] client: connect: unreachable Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:49:01.857 ThaliTest[2094:4461924] jxcore: connect: fail: Peer unreachable
,2016-01-15T18:49:01.858Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:49:01.858Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-15T18:49:01.858Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:49:06.863Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15T18:49:06.863Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15 19:49:11.871 ThaliTest[2094:4461924] jxcore: disconnect
2016-01-15 19:49:11.871 ThaliTest[2094:4461924] jxcore: disconnect: fail
2016-01-15T18:49:11.871Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6810.+fMb,bA==
2016-01-15T18:49:11.871Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT6810.+fMbbA== with availability status: true
2016-01-15T18:49:11.871Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15T18:49:11.871Z SendDataConnector.js: do connect now
2016-01-15 19:49:11.871 ThaliTest[2094:4461924] jxcore: connect Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15 19:49:11.871 ThaliTest[2094:4461924] client: connect: unreachable Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:49:11.872 ThaliTest[2094:4461924] jxcore: connect: fail: Peer unreachable
2016-01-15T18:49:11.872Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2016-01-15T18:49:11.872Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2016-01-15T18:49:11.872Z SendDataConnector.js: CLIENT Stop now
2016-01-15 19:49:11.873 ThaliTest[2094:4461924] jxcore: disconnect
2016-01-15 19:49:11.873 ThaliTest[2094:4461924] jxcore: disconnect: fail
2016-01-15T18:49:11.873Z SendData,Connector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6810.+fMbbA==
---- round done--------
startWithNextDevice
device[2]: Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15T18:49:11.874Z SendDataConnector.js: Start called with peer Apple-Iph,one6-1_PT3224.81B+Sg==
2016-01-15T18:49:11.874Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15T18:49:11.874Z SendDataConnector.js: do connect now
2016-01-15 19:49:11.874 ThaliTest[2094:4461924] jxcore: connect Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:49:11.874 ThaliTest[2094:4461924] client session: connect
2016-01-15 19:49:11.874 ThaliTest[2094:4461924] client session: stateChange:0->1 Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:12.028 ThaliTest[2094:4461743] multipeer session: reset timer
2016-01-15 19:49:12.028 ThaliTest[2094:4461743] multipeer session: stop timer
2016-01-15 19:49:12.029 ThaliTest[2094:4461743] multipeer session: start timer: 0x19d5bb80
2016-,01-15 19:49:12.029 ThaliTest[2094:4461743] server session: connect
2016-01-15 19:49:12.029 ThaliTest[2094:4461743] server session: stateChange:0->1 Apple-Iphone6-1_PT3224
,2016-01-15 19:49:12.031 ThaliTest[2094:4461743] server: accepting invitation Apple-Iphone6-1_PT3224
,2016-01-15 19:49:14.516 ThaliTest[2094:4461743] multipeer session: reset timer
2016-01-15 19:49:14.516 ThaliTest[2094:4461743] multipeer session: stop timer
,2016-01-15 19:49:14.516 ThaliTest[2094:4461743] multipeer session: start timer: 0x19d5bb80
2016-01-15 19:49:14.516 ThaliTest[2094:4461743] server session: connect
2016-01-15 19:49:14.516 ThaliTest[2094:4461743] server session: stateChange:0->1 Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:14.518 ThaliTest[2094:4461743] server: accepting invitation Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:15.960 ThaliTest[2094:4462557] client session: connected
,2016-01-15 19:49:15.961 ThaliTest[2094:4462557] client session: stateChange:1->2 Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:15.962 ThaliTest[2094:4462557] client session: fireConnectCallback: Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:49:15.962 ThaliTest[2094:4462557] jxcore: connect: success
2016-01-15T18:49:15.963Z SendDataConnector.js: CLIENT connected to 52515, error: null
,2016-01-15T18:49:15.963Z SendDataConnector.js: CLIENT starting client 
,2016-01-15 19:49:15.964 ThaliTest[2094:4461743] client: relay established
,2016-01-15 19:49:15.964 ThaliTest[2094:4461743] client: new accepted socket: 0x19b41790
,2016-01-15T18:49:15.977Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15 19:49:16.013 ThaliTest[2094:4462577] server session: connected
2016-01-15 19:49:16.013 ThaliTest[2094:4462577] server session: stateChange:1->2 Apple-Iphone6-1_PT3224
,2016-01-15 19:49:16.016 ThaliTest[2094:4461743] server relay: connected (to port: 52508)
,2016-01-15T18:49:16.172Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15T18:49:16.233Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-15T18:49:16.246Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2016-01-15T18:49:16.484Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-15T18:49:16.484Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-15T18:49:16.484Z SendDataConnector.js: CLIENT Stop now
2016-01-15T18:49:16.484Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-15 19:49:16.485 ThaliTest[2094:4461924] jxcore: disconnect
,2016-01-15 19:49:16.485 ThaliTest[2094:4461924] client session: disconnectFromPeer: Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:16.486 ThaliTest[2094:4461924] client session: disconnect
,2016-01-15 19:49:16.486 ThaliTest[2094:4461924] client session: stateChange:2->0 Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:16.489 ThaliTest[2094:4461924] jxcore: disconnect: success
,2016-01-15T18:49:16.492Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3224.81B+Sg==
---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15T18:49:16.493Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15T18:49:16.493Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.rhpQQw==
2016-01-15T18:49:16.493Z SendDataConnector.js: do connect now
,2016-01-15 19:49:16.494 ThaliTest[2094:4461924] jxcore: connect Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:16.494 ThaliTest[2094:4461924] client session: connect
,2016-01-15 19:49:16.494 ThaliTest[2094:4461924] client session: stateChange:0->1 Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15T18:49:16.497Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:16.602 ThaliTest[2094:4462558] server session: not connected Apple-Iphone6-1_PT3224
,2016-01-15 19:49:17.595 ThaliTest[2094:4462645] server session: connected
2016-01-15 19:49:17.595 ThaliTest[2094:4462645] server session: stateChange:1->2 Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:17.631 ThaliTest[2094:4461743] server relay: connected (to port: 52508)
,2016-01-15T18:49:17.639Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15T18:49:17.903Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2016-01-15T18:49:17.915Z SendDataTCPServer.js: TCP/IP server has received 19284 bytes of data
,2016-01-15T18:49:17.928Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:17.955 ThaliTest[2094:4462557] server session: not connected Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:19.475 ThaliTest[2094:4461743] multipeer session: reset timer
2016-01-15 19:49:19.475 ThaliTest[2094:4461743] multipeer session: stop timer
2016-01-15 19:49:19.475 ThaliTest[2094:4461743] multipeer session: start timer: 0x19d5bb80
2016-,01-15 19:49:19.475 ThaliTest[2094:4461743] server session: connect
2016-01-15 19:49:19.475 ThaliTest[2094:4461743] server session: stateChange:0->1 Apple-Iphone5-1_PT5004
2016-01-15 19:49:19.477 ThaliTest[2094:4461743] server: accepting invitation Apple-Iphone5-1_PT5004
,2016-01-15 19:49:20.159 ThaliTest[2094:4462650] client session: connected
2016-01-15 19:49:20.159 ThaliTest[2094:4462650] client session: stateChange:1->2 Apple-Iphone5-1_PT5004.rhpQQw==
2016-01-15 19:49:20.160 ThaliTest[2094:4462650] client session: fir,eConnectCallback: Apple-Iphone5-1_PT5004.rhpQQw==
2016-01-15 19:49:20.160 ThaliTest[2094:4462650] jxcore: connect: success
,2016-01-15T18:49:20.161Z SendDataConnector.js: CLIENT connected to 52520, error: null
2016-01-15T18:49:20.161Z SendDataConnector.js: CLIENT starting client 
,2016-01-15 19:49:20.162 ThaliTest[2094:4461743] client: relay established
2016-01-15 19:49:20.162 ThaliTest[2094:4461743] client: new accepted socket: 0x19b32f90
,2016-01-15T18:49:20.174Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:20.469Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-15T18:49:20.521Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-15T18:49:20.521Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-15T18:49:20.522Z SendDataConnector.js: CLIENT Stop now
,2016-01-15T18:49:20.522Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-15 19:49:20.522 ThaliTest[2094:4461924] jxcore: disconnect
,2016-01-15 19:49:20.523 ThaliTest[2094:4461924] client session: disconnectFromPeer: Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:20.523 ThaliTest[2094:4461924] client session: disconnect
,2016-01-15 19:49:20.523 ThaliTest[2094:4461924] client session: stateChange:2->0 Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:20.583 ThaliTest[2094:4461924] jxcore: disconnect: success
,2016-01-15T18:49:20.584Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.rhpQQw==
,---- round done--------
,startWithNextDevice
device[4]: Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15T18:49:20.584Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15T18:49:20.584Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15T18:49:20.584Z SendDataConnector.js: do connect now
,2016-01-15 19:49:20.585 ThaliTest[2094:4461924] jxcore: connect Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:20.585 ThaliTest[2094:4461924] client session: connect
,2016-01-15 19:49:20.585 ThaliTest[2094:4461924] client session: stateChange:0->1 Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:22.815 ThaliTest[2094:4462650] server session: connected
2016-01-15 19:49:22.815 ThaliTest[2094:4462650] server session: stateChange:1->2 Apple-Iphone5-1_PT5004
,2016-01-15 19:49:22.819 ThaliTest[2094:4461743] server relay: connected (to port: 52508)
,2016-01-15T18:49:22.826Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15T18:49:23.337Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-15T18:49:23.348Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2016-01-15T18:49:23.374Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2016-01-15T18:49:23.400Z SendDataTCPServer.js: TCP/IP server has received 71986 bytes of data
,2016-01-15T18:49:23.413Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:23.500 ThaliTest[2094:4462650] server session: not connected Apple-Iphone5-1_PT5004
,2016-01-15 19:49:23.912 ThaliTest[2094:4462650] client session: connected
2016-01-15 19:49:23.912 ThaliTest[2094:4462650] client session: stateChange:1->2 Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15 19:49:23.913 ThaliTest[2094:4462650] client session: fireConnectCallback: Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15 19:49:23.913 ThaliTest[2094:4462650] jxcore: connect: success
2016-01-15T18:49:23.913Z SendDataConnector.js: CLIENT connected to 52524, error: null
2016-01-15T18:49:23.913Z SendDataConnector.js: CLIENT starting client 
,2016-01-15 19:49:23.914 ThaliTest[2094:4461743] client: relay established
2016-01-15 19:49:23.914 ThaliTest[2094:4461743] client: new accepted socket: 0x19b38070
,2016-01-15T18:49:23.925Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:24.423Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-15T18:49:24.436Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-15T18:49:24.510Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-15T18:49:24.510Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-15T18:49:24.511Z SendDataConnector.js: CLIENT Stop now
,2016-01-15T18:49:24.511Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-15 19:49:24.511 ThaliTest[2094:4461924] jxcore: disconnect
,2016-01-15 19:49:24.511 ThaliTest[2094:4461924] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:24.512 ThaliTest[2094:4461924] client session: disconnect
,2016-01-15 19:49:24.512 ThaliTest[2094:4461924] client session: stateChange:2->0 Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:24.574 ThaliTest[2094:4461924] jxcore: disconnect: success
,2016-01-15T18:49:24.575Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6477.TN0Czw==
,---- round done--------
,startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
,done, now sending data to server
,2016-01-15T18:49:24.585Z SendDataConnector.js: CLIENT Stop now
2016-01-15T18:49:24.585Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
2016-01-15 19:49:25.566 ThaliTest[2094:4461924] jxcore: stopBroadcasting
,2016-01-15 19:49:25.566 ThaliTest[2094:4461924] THEMultipeerSession stopping peer
2016-01-15 19:49:25.567 ThaliTest[2094:4461924] multipeer session: stop timer
2016-01-15 19:49:25.567 ThaliTest[2094:4461924] server session: disconnect
2016-01-15 19:49:2,5.567 ThaliTest[2094:4461924] server session: stateChange:2->0 Apple-Iphone6-1_PT3224
,2016-01-15 19:49:25.569 ThaliTest[2094:4461924] server session: disconnect
2016-01-15 19:49:25.569 ThaliTest[2094:4461924] server session: stateChange:2->0 Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:25.571 ThaliTest[2094:4461924] server session: disconnect
2016-01-15 19:49:25.571 ThaliTest[2094:4461924] server session: stateChange:2->0 Apple-Iphone5-1_PT5004
,2016-01-15 19:49:25.575 ThaliTest[2094:4461924] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
