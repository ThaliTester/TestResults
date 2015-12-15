#### Test 50650278ee43ca0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/71421B37-A1AD-4E44-9953-5FCC05D6A140/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/71421B37-A1AD-4E44-9953-5FCC05D6A140/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D822D8E9-7302-4040-9462-B156843ABCB6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56309"
,(lldb)     command script import "/tmp/71421B37-A1AD-4E44-9953-5FCC05D6A140/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 05:01:19.198 ThaliTest[1143:1227758] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8AAEA0B0-76BE-4EF5-AF6B-F23B9DAC4034/Library/Cookies/Cookies.binarycookies
,2015-12-15 05:01:19.525 ThaliTest[1143:1227758] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 05:01:19.526 ThaliTest[1143:1227758] Multi-tasking -> Device: YES, App: YES
,2015-12-15 05:01:19.534 ThaliTest[1143:1227758] Unlimited access to network resources
,2015-12-15 05:01:19.541 ThaliTest[1143:1227758] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 05:01:29.030 ThaliTest[1143:1227758] Resetting plugins due to page load.
,2015-12-15 05:01:32.769 ThaliTest[1143:1227758] Finished load of: file:///var/mobile/Containers/Bundle/Application/D822D8E9-7302-4040-9462-B156843ABCB6/ThaliTest.app/www/index.html
,2015-12-15 05:01:32.947 ThaliTest[1143:1227758] JXcore Cordova plugin initializing
,2015-12-15 05:01:32.948 ThaliTest[1143:1227965] JXcore instance initializing
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
,2015-12-15 05:01:33.923 ThaliTest[1143:1227758] THREAD WARNING: ['JXcore'] took '70.067871' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 05:06:34.068 ThaliTest[1143:1227965] jxcore: startBroadcasting
,2015-12-15 05:06:34.085 ThaliTest[1143:1227965] server: starting Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:06:34.087 ThaliTest[1143:1227965] multipeer session: start timer: 0x15fa39a0
2015-12-15 05:06:34.088 ThaliTest[1143:1227965] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1010
,2015-12-15 05:06:34.089 ThaliTest[1143:1227965] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 05:06:35.182 ThaliTest[1143:1227758] client: found peer: Apple-Iphone6-1_PT9306.6VQMVQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9306.6VQMVQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT9306.6VQMVQ==, peerAvailable: true
,weAreDoneNow
,2015-12-15 05:06:35.188 ThaliTest[1143:1227758] client: found peer: Apple-Iphone5s-1_PT6308.pQEQSw==
done, now sending data to server
,2015-12-15 05:06:35.325 ThaliTest[1143:1227758] client: found peer: Apple-Iphone5-1_PT2557.cLGdMA==
,teardown
,testFindPeers stopped
,2015-12-15 05:06:36.480 ThaliTest[1143:1227965] jxcore: stopBroadcasting
,2015-12-15 05:06:36.480 ThaliTest[1143:1227965] THEMultipeerSession stopping peer
,2015-12-15 05:06:36.480 ThaliTest[1143:1227965] multipeer session: stop timer
,2015-12-15 05:06:36.482 ThaliTest[1143:1227965] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 58481
,2015-12-15 05:06:36.542 ThaliTest[1143:1227965] jxcore: startBroadcasting
,2015-12-15 05:06:36.545 ThaliTest[1143:1227965] server: starting Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:06:36.546 ThaliTest[1143:1227965] multipeer session: start timer: 0x17d29c30
2015-12-15 05:06:36.546 ThaliTest[1143:1227965] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1010
2015-12-15 05:06:36.547 ThaliTest[1143:1227965] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-15T04:06:36.553Z SendDataTCPServer.js: TCP/IP server is bound to port: 58481
,2015-12-15 05:06:36.567 ThaliTest[1143:1227758] client: found peer: Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15 05:06:36.567 ThaliTest[1143:1227758] client: found peer: Apple-Iphone6-1_PT9306.6VQMVQ==
2015-12-15 05:06:36.568 ThaliTest[1143:1227758] clien,t: found peer: Apple-Iphone5-1_PT2557.cLGdMA==
2015-12-15 05:06:36.568 ThaliTest[1143:1227758] client: found peer: Apple-Iphone5s-1_PT6308.pQEQSw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1010.7Cf2mQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15T04:06:36.571Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15T04:06:36.572Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15T04:06:36.572Z SendDataConnector.js: do connect now
,2015-12-15 05:06:36.573 ThaliTest[1143:1227965] jxcore: connect Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15 05:06:36.573 ThaliTest[1143:1227965] client session: connect
,2015-12-15 05:06:36.574 ThaliTest[1143:1227965] client session: stateChange:0->1 Apple-IpadAir2-1_PT1010.7Cf2mQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9306.6VQMVQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.cLGdMA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6308.pQEQSw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:06:37.599 ThaliTest[1143:1227758] client: lost peer: Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15 05:06:37.599 ThaliTest[1143:1227758] client session: onPeerLost: Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15 05:06:37.599 ThaliTest[1143:122775,8] client session: onLinkFailure: Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15 05:06:37.599 ThaliTest[1143:1227758] client session: disconnect
,2015-12-15 05:06:37.600 ThaliTest[1143:1227758] client session: stateChange:1->0 Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:06:37.601 ThaliTest[1143:1227758] client session: fireConnectCallback: Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:06:37.601 ThaliTest[1143:1227758] jxcore: connect: fail: Peer disconnected
,2015-12-15T04:06:37.603Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-15T04:06:37.603Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-15T04:06:37.605Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1010.7Cf2mQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-15 05:06:37.805 ThaliTest[1143:1227758] client: lost peer: Apple-Iphone6-1_PT9306.6VQMVQ==
2015-12-15 05:06:37.805 ThaliTest[1143:1227758] client session: onPeerLost: Apple-Iphone6-1_PT9306.6VQMVQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9306.6VQMVQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-15 05:06:38.296 ThaliTest[1143:1227758] client: lost peer: Apple-Iphone5-1_PT2557.cLGdMA==
,2015-12-15 05:06:38.296 ThaliTest[1143:1227758] client session: onPeerLost: Apple-Iphone5-1_PT2557.cLGdMA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.cLGdMA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-12-15 05:06:38.299 ThaliTest[1143:1227758] client: found peer: Apple-Iphone6-1_PT9306.EdsI,mg==
,2015-12-15 05:06:38.300 ThaliTest[1143:1227758] client: found peer: Apple-Iphone5s-1_PT6308.z27btQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9306.EdsImg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6308.z27btQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:06:38.810 ThaliTest[1143:1227758] client: lost peer: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:38.811 ThaliTest[1143:1227758] client session: onPeerLost: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:38.811 ThaliTest[1143:1227758] client: found peer: Apple-Iphone5-1_PT2557.fyiFnQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6308.pQEQSw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.fyiFnQ==","peerName":"(null,)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15T04:06:42.610Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15T04:06:42.611Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:06:47.624 ThaliTest[1143:1227965] jxcore: disconnect
,2015-12-15 05:06:47.624 ThaliTest[1143:1227965] jxcore: disconnect: fail
,2015-12-15T04:06:47.625Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15T04:06:47.626Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT1010.7Cf2mQ== with availability status: true
,2015-12-15T04:06:47.626Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15T04:06:47.627Z SendDataConnector.js: do connect now
,2015-12-15 05:06:47.628 ThaliTest[1143:1227965] jxcore: connect Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15 05:06:47.629 ThaliTest[1143:1227965] client: connect: unreachable Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:06:47.629 ThaliTest[1143:1227965] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:06:47.630Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T04:06:47.631Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T04:06:47.631Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:06:52.638Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15T04:06:52.639Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:06:57.647 ThaliTest[1143:1227965] jxcore: disconnect
,2015-12-15 05:06:57.647 ThaliTest[1143:1227965] jxcore: disconnect: fail
,2015-12-15T04:06:57.648Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15T04:06:57.649Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT1010.7Cf2mQ== with availability status: true
,2015-12-15T04:06:57.649Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15T04:06:57.650Z SendDataConnector.js: do connect now
,2015-12-15 05:06:57.651 ThaliTest[1143:1227965] jxcore: connect Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:06:57.652 ThaliTest[1143:1227965] client: connect: unreachable Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:06:57.652 ThaliTest[1143:1227965] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:06:57.653Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T04:06:57.653Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T04:06:57.654Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:07:02.656Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15T04:07:02.657Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:07:06.547 ThaliTest[1143:1227758] multipeer session: restart
,2015-12-15 05:07:06.576 ThaliTest[1143:1227758] client: found peer: Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15 05:07:06.576 ThaliTest[1143:1227758] client: found peer: Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:06.580 ThaliTest[1143:1227758] client: found peer: Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:07.670 ThaliTest[1143:1227965] jxcore: disconnect
,2015-12-15 05:07:07.670 ThaliTest[1143:1227965] jxcore: disconnect: fail
,2015-12-15T04:07:07.671Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15T04:07:07.672Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT1010.7Cf2mQ== with availability status: true
,2015-12-15T04:07:07.672Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15T04:07:07.673Z SendDataConnector.js: do connect now
,2015-12-15 05:07:07.674 ThaliTest[1143:1227965] jxcore: connect Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:07:07.674 ThaliTest[1143:1227965] client: connect: unreachable Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:07:07.675 ThaliTest[1143:1227965] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:07:07.676Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:07:07.676Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T04:07:07.677Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:07:12.680Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15T04:07:12.681Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:07:17.692 ThaliTest[1143:1227965] jxcore: disconnect
,2015-12-15 05:07:17.692 ThaliTest[1143:1227965] jxcore: disconnect: fail
,2015-12-15T04:07:17.693Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15T04:07:17.694Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT1010.7Cf2mQ== with availability status: true
,2015-12-15T04:07:17.694Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15T04:07:17.695Z SendDataConnector.js: do connect now
,2015-12-15 05:07:17.697 ThaliTest[1143:1227965] jxcore: connect Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15 05:07:17.697 ThaliTest[1143:1227965] client: connect: unreachable Apple-IpadAir2-1_PT1010.7Cf2mQ==
,2015-12-15 05:07:17.698 ThaliTest[1143:1227965] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:07:17.699Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T04:07:17.700Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-15T04:07:17.702Z SendDataConnector.js: CLIENT Stop now
,2015-12-15 05:07:17.703 ThaliTest[1143:1227965] jxcore: disconnect
,2015-12-15 05:07:17.703 ThaliTest[1143:1227965] jxcore: disconnect: fail
,2015-12-15T04:07:17.705Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1010.7Cf2mQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15T04:07:17.708Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15T04:07:17.708Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15T04:07:17.709Z SendDataConnector.js: do connect now
,2015-12-15 05:07:17.710 ThaliTest[1143:1227965] jxcore: connect Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:17.711 ThaliTest[1143:1227965] client session: connect
,2015-12-15 05:07:17.712 ThaliTest[1143:1227965] client session: stateChange:0->1 Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:21.581 ThaliTest[1143:1228635] client session: connected
,2015-12-15 05:07:21.581 ThaliTest[1143:1228635] client session: stateChange:1->2 Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:21.620 ThaliTest[1143:1228599] client session: fireConnectCallback: Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:21.620 ThaliTest[1143:1228599] jxcore: connect: success
,2015-12-15T04:07:21.623Z SendDataConnector.js: CLIENT connected to 58488, error: null
2015-12-15T04:07:21.623Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:21.626 ThaliTest[1143:1227758] client: relay established
2015-12-15 05:07:21.626 ThaliTest[1143:1227758] client: new accepted socket: 0x17d32c20
,2015-12-15T04:07:21.643Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:07:22.233Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-15T04:07:22.248Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:07:22.248Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:07:22.250Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:07:22.250Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:22.253 ThaliTest[1143:1227965] jxcore: disconnect
,2015-12-15 05:07:22.253 ThaliTest[1143:1227965] client session: disconnectFromPeer: Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:22.254 ThaliTest[1143:1227965] client session: disconnect
,2015-12-15 05:07:22.254 ThaliTest[1143:1227965] client session: stateChange:2->0 Apple-Iphone6-1_PT9306.EdsImg==
,2015-12-15 05:07:22.328 ThaliTest[1143:1227965] jxcore: disconnect: success
2015-12-15T04:07:22.329Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9306.EdsImg==
---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15T04:07:22.331Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15T04:07:22.332Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15T04:07:22.332Z SendDataConnector.js: do connect now
,2015-12-15 05:07:22.333 ThaliTest[1143:1227965] jxcore: connect Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15 05:07:22.334 ThaliTest[1143:1227965] client session: connect
,2015-12-15 05:07:22.335 ThaliTest[1143:1227965] client session: stateChange:0->1 Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:22.556 ThaliTest[1143:1227758] multipeer session: reset timer
,2015-12-15 05:07:22.556 ThaliTest[1143:1227758] multipeer session: stop timer
,2015-12-15 05:07:22.557 ThaliTest[1143:1227758] multipeer session: start timer: 0x17d29c30
,2015-12-15 05:07:22.557 ThaliTest[1143:1227758] server session: connect
,2015-12-15 05:07:22.558 ThaliTest[1143:1227758] server session: stateChange:0->1 Apple-Iphone6-1_PT9306
,2015-12-15 05:07:22.564 ThaliTest[1143:1227758] server: accepting invitation Apple-Iphone6-1_PT9306
,2015-12-15 05:07:22.953 ThaliTest[1143:1227758] multipeer session: reset timer
2015-12-15 05:07:22.954 ThaliTest[1143:1227758] multipeer session: stop timer
2015-12-15 05:07:22.954 ThaliTest[1143:1227758] multipeer session: start timer: 0x17d29c30
2015-12-15 05:07:22.954 ThaliTest[1143:1227758] server session: connect
2015-12-15 05:07:22.955 ThaliTest[1143:1227758] server session: stateChange:0->1 Apple-Iphone5s-1_PT6308
,2015-12-15 05:07:22.961 ThaliTest[1143:1227758] server: accepting invitation Apple-Iphone5s-1_PT6308
,2015-12-15 05:07:25.145 ThaliTest[1143:1228637] server session: connected
2015-12-15 05:07:25.145 ThaliTest[1143:1228637] server session: stateChange:1->2 Apple-Iphone6-1_PT9306
,2015-12-15 05:07:25.174 ThaliTest[1143:1227758] server relay: connected (to port: 58481)
,2015-12-15T04:07:25.178Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15 05:07:25.372 ThaliTest[1143:1228663] server session: connected
2015-12-15 05:07:25.372 ThaliTest[1143:1228663] server session: stateChange:1->2 Apple-Iphone5s-1_PT6308
,2015-12-15 05:07:25.398 ThaliTest[1143:1227758] server relay: connected (to port: 58481)
,2015-12-15T04:07:25.404Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:07:25.445Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-15T04:07:25.464Z SendDataTCPServer.js: TCP/IP server has received 65416 bytes of data
,2015-12-15T04:07:25.482Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:07:25.519 ThaliTest[1143:1228635] server session: not connected Apple-Iphone6-1_PT9306
,2015-12-15 05:07:25.564 ThaliTest[1143:1228599] client session: connected
2015-12-15 05:07:25.565 ThaliTest[1143:1228599] client session: stateChange:1->2 Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:25.577 ThaliTest[1143:1228637] client session: fireConnectCallback: Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:25.578 ThaliTest[1143:1228637] jxcore: connect: success
,2015-12-15T04:07:25.579Z SendDataConnector.js: CLIENT connected to 58493, error: null
,2015-12-15T04:07:25.580Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:25.582 ThaliTest[1143:1227758] client: relay established
2015-12-15 05:07:25.582 ThaliTest[1143:1227758] client: new accepted socket: 0x15efa180
,2015-12-15T04:07:25.596Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:07:25.835Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15T04:07:25.851Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-15T04:07:25.864Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-15T04:07:25.877Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:07:25.878Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-15T04:07:25.878Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:07:25.878Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:25.879 ThaliTest[1143:1227965] jxcore: disconnect
,2015-12-15 05:07:25.879 ThaliTest[1143:1227965] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:25.879 ThaliTest[1143:1227965] client session: disconnect
,2015-12-15 05:07:25.879 ThaliTest[1143:1227965] client session: stateChange:2->0 Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:25.887 ThaliTest[1143:1228635] server session: not connected Apple-Iphone5s-1_PT6308
,2015-12-15 05:07:25.945 ThaliTest[1143:1227965] jxcore: disconnect: success
,2015-12-15T04:07:25.945Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.z27btQ==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15T04:07:25.946Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15T04:07:25.946Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15T04:07:25.947Z SendDataConnector.js: do connect now
,2015-12-15 05:07:25.947 ThaliTest[1143:1227965] jxcore: connect Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:25.947 ThaliTest[1143:1227965] client session: connect
,2015-12-15 05:07:25.947 ThaliTest[1143:1227965] client session: stateChange:0->1 Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:26.735 ThaliTest[1143:1227758] multipeer session: reset timer
2015-12-15 05:07:26.735 ThaliTest[1143:1227758] multipeer session: stop timer
2015-12-15 05:07:26.735 ThaliTest[1143:1227758] multipeer session: start timer: 0x17d29c30
2015-12-15 05:07:26.736 ThaliTest[1143:1227758] server session: connect
2015-12-15 05:07:26.736 ThaliTest[1143:1227758] server session: stateChange:0->1 Apple-Iphone5-1_PT2557
,2015-12-15 05:07:26.743 ThaliTest[1143:1227758] server: accepting invitation Apple-Iphone5-1_PT2557
,2015-12-15 05:07:29.309 ThaliTest[1143:1228637] client session: connected
2015-12-15 05:07:29.309 ThaliTest[1143:1228637] client session: stateChange:1->2 Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:29.341 ThaliTest[1143:1228637] server session: connected
2015-12-15 05:07:29.342 ThaliTest[1143:1228637] server session: stateChange:1->2 Apple-Iphone5-1_PT2557
,2015-12-15 05:07:29.343 ThaliTest[1143:1228599] client session: fireConnectCallback: Apple-Iphone5-1_PT2557.fyiFnQ==
2015-12-15 05:07:29.344 ThaliTest[1143:1228599] jxcore: connect: success
,2015-12-15T04:07:29.345Z SendDataConnector.js: CLIENT connected to 58496, error: null
,2015-12-15T04:07:29.346Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:29.348 ThaliTest[1143:1227758] client: relay established
2015-12-15 05:07:29.349 ThaliTest[1143:1227758] client: new accepted socket: 0x17d3c480
,2015-12-15T04:07:29.362Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15 05:07:29.379 ThaliTest[1143:1227758] server relay: connected (to port: 58481)
,2015-12-15T04:07:29.601Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:07:29.907Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-15T04:07:29.956Z SendDataTCPServer.js: TCP/IP server has received 52418 bytes of data
,2015-12-15T04:07:29.959Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:07:29.959Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-15T04:07:29.960Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:07:2,9.960Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-15 05:07:29.961 ThaliTest[1143:1227965] jxcore: disconnect
2015-12-15 05:07:29.961 ThaliTest[1143:1227965] client session: disconnectFromPeer: Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:29.962 ThaliTest[1143:1227965] client session: disconnect
2015-12-15 05:07:29.962 ThaliTest[1143:1227965] client session: stateChange:2->0 Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:29.971 ThaliTest[1143:1227965] jxcore: disconnect: success
2015-12-15T04:07:29.971Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2557.fyiFnQ==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2015-12-15T04:07:29.977Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:07:29.977Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15T04:07:29.991Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:07:30.084 ThaliTest[1143:1228663] server session: not connected Apple-Iphone5-1_PT2557
,teardown
,testSendData stopped
,2015-12-15 05:07:31.133 ThaliTest[1143:1227965] jxcore: stopBroadcasting
,2015-12-15 05:07:31.134 ThaliTest[1143:1227965] THEMultipeerSession stopping peer
,2015-12-15 05:07:31.134 ThaliTest[1143:1227965] multipeer session: stop timer
,2015-12-15 05:07:31.135 ThaliTest[1143:1227965] server session: disconnect
2015-12-15 05:07:31.136 ThaliTest[1143:1227965] server session: stateChange:2->0 Apple-Iphone5-1_PT2557
,2015-12-15 05:07:31.144 ThaliTest[1143:1227965] server session: disconnect
2015-12-15 05:07:31.145 ThaliTest[1143:1227965] server session: stateChange:2->0 Apple-Iphone6-1_PT9306
,2015-12-15 05:07:31.160 ThaliTest[1143:1227965] server session: disconnect
2015-12-15 05:07:31.160 ThaliTest[1143:1227965] server session: stateChange:2->0 Apple-Iphone5s-1_PT6308
,2015-12-15 05:07:31.790 ThaliTest[1143:1227965] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-15T04:07:31.808Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:31.810Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:31.811Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:31.812Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
