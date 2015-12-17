#### Test 506502785223c58_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7C2EE933-BEF5-455E-BDF7-C0705E29D2A5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7C2EE933-BEF5-455E-BDF7-C0705E29D2A5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/38550403-FC39-46F6-B29B-8B98A1A14274/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59086"
,(lldb)     command script import "/tmp/7C2EE933-BEF5-455E-BDF7-C0705E29D2A5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-17 01:37:13.381 ThaliTest[338:159245] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0BA4431A-BEF0-4D23-B04A-9D2F0E896303/Library/Cookies/Cookies.binarycookies
,2015-12-17 01:37:13.731 ThaliTest[338:159245] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-17 01:37:13.732 ThaliTest[338:159245] Multi-tasking -> Device: YES, App: YES
,2015-12-17 01:37:13.741 ThaliTest[338:159245] Unlimited access to network resources
,2015-12-17 01:37:13.749 ThaliTest[338:159245] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-17 01:37:22.906 ThaliTest[338:159245] Resetting plugins due to page load.
,2015-12-17 01:37:26.585 ThaliTest[338:159245] Finished load of: file:///var/mobile/Containers/Bundle/Application/38550403-FC39-46F6-B29B-8B98A1A14274/ThaliTest.app/www/index.html
,2015-12-17 01:37:26.749 ThaliTest[338:159245] JXcore Cordova plugin initializing
,2015-12-17 01:37:26.750 ThaliTest[338:159474] JXcore instance initializing
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
,2015-12-17 01:37:27.747 ThaliTest[338:159245] THREAD WARNING: ['JXcore'] took '70.750000' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-17 01:42:49.623 ThaliTest[338:159474] jxcore: startBroadcasting
,2015-12-17 01:42:49.642 ThaliTest[338:159474] server: starting Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:42:49.644 ThaliTest[338:159474] multipeer session: start timer: 0x1748ab30
,2015-12-17 01:42:49.645 ThaliTest[338:159474] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2260
,2015-12-17 01:42:49.646 ThaliTest[338:159474] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-17 01:42:50.690 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.8JQKBA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.8JQKBA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT4129.8JQKBA==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-17 01:42:51.202 ThaliTest[338:159474] jxcore: stopBroadcasting
,2015-12-17 01:42:51.203 ThaliTest[338:159474] THEMultipeerSession stopping peer
,2015-12-17 01:42:51.203 ThaliTest[338:159474] multipeer session: stop timer
,2015-12-17 01:42:51.204 ThaliTest[338:159474] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 51016
,2015-12-17 01:42:51.268 ThaliTest[338:159474] jxcore: startBroadcasting
,2015-12-17 01:42:51.272 ThaliTest[338:159474] server: starting Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:42:51.272 ThaliTest[338:159474] multipeer session: start timer: 0x17496370
,2015-12-17 01:42:51.273 ThaliTest[338:159474] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2260
,2015-12-17 01:42:51.274 ThaliTest[338:159474] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
2015-12-17T00:42:51.280Z SendDataTCPServer.js: TCP/IP server is bound to port: 51016
,2015-12-17 01:42:52.284 ThaliTest[338:159245] client: found peer: Apple-IpadAir2-1_PT2260.GOF+uA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.GOF+uA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:42:52.288Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:42:52.289Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:42:52.289Z SendDataConnector.js: do connect now
,2015-12-17 01:42:52.290 ThaliTest[338:159474] jxcore: connect Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:42:52.291 ThaliTest[338:159474] client session: connect
2015-12-17 01:42:52.291 ThaliTest[338:159474] client session: stateChange:0->1 Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:42:52.326 ThaliTest[338:159245] client: lost peer: Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:42:52.327 ThaliTest[338:159245] client session: onPeerLost: Apple-IpadAir2-1_PT2260.GOF+uA==
2015-12-17 01:42:52.327 ThaliTest[338:159245] client session: onLinkFailure: Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:42:52.327 ThaliTest[338:159245] client session: disconnect
,2015-12-17 01:42:52.328 ThaliTest[338:159245] client session: stateChange:1->0 Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:42:52.329 ThaliTest[338:159245] client session: fireConnectCallback: Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:42:52.329 ThaliTest[338:159245] jxcore: connect: fail: Peer disconnected
,2015-12-17T00:42:52.331Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-17T00:42:52.331Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-17T00:42:52.332Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.GOF+uA==","peerName":"(null)","peerAvailable":false}]
,2015-12-17 01:42:52.775 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17 01:42:53.283 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17 01:42:53.409 ThaliTest[338:159245] multipeer session: reset timer
2015-12-17 01:42:53.410 ThaliTest[338:159245] multipeer session: stop timer
,2015-12-17 01:42:53.410 ThaliTest[338:159245] multipeer session: start timer: 0x17496370
,2015-12-17 01:42:53.410 ThaliTest[338:159245] server session: connect
2015-12-17 01:42:53.411 ThaliTest[338:159245] server session: stateChange:0->1 Apple-Iphone5s-1_PT4765
,2015-12-17 01:42:53.417 ThaliTest[338:159245] server: accepting invitation Apple-Iphone5s-1_PT4765
,2015-12-17 01:42:53.732 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17 01:42:56.858 ThaliTest[338:160084] server session: connected
,2015-12-17 01:42:56.861 ThaliTest[338:160084] server session: stateChange:1->2 Apple-Iphone5s-1_PT4765
,2015-12-17 01:42:56.868 ThaliTest[338:159245] server relay: connected (to port: 51016)
,2015-12-17T00:42:56.876Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T00:42:57.333Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-17T00:42:57.349Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:42:57.351Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:42:57.352Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-17T00:42:57.408Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-17T00:42:57.424Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 01:42:57.490 ThaliTest[338:160070] server session: not connected Apple-Iphone5s-1_PT4765
,2015-12-17 01:43:02.360 ThaliTest[338:159474] jxcore: disconnect
2015-12-17 01:43:02.360 ThaliTest[338:159474] jxcore: disconnect: fail
,2015-12-17T00:43:02.361Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:43:02.362Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT2260.GOF+uA== with availability status: true
,2015-12-17T00:43:02.363Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:43:02.363Z SendDataConnector.js: do connect now
,2015-12-17 01:43:02.364 ThaliTest[338:159474] jxcore: connect Apple-IpadAir2-1_PT2260.GOF+uA==
2015-12-17 01:43:02.365 ThaliTest[338:159474] client: connect: unreachable Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:43:02.365 ThaliTest[338:159474] jxcore: connect: fail: Peer unreachable
,2015-12-17T00:43:02.366Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-17T00:43:02.367Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-17T00:43:02.367Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17T00:43:07.368Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:43:07.369Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:43:12.373 ThaliTest[338:159474] jxcore: disconnect
2015-12-17 01:43:12.374 ThaliTest[338:159474] jxcore: disconnect: fail
,2015-12-17T00:43:12.375Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:43:12.376Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT2260.GOF+uA== with availability status: true
,2015-12-17T00:43:12.377Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:43:12.377Z SendDataConnector.js: do connect now
,2015-12-17 01:43:12.378 ThaliTest[338:159474] jxcore: connect Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:43:12.379 ThaliTest[338:159474] client: connect: unreachable Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:43:12.380 ThaliTest[338:159474] jxcore: connect: fail: Peer unreachable
,2015-12-17T00:43:12.380Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-17T00:43:12.381Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-17T00:43:12.381Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17T00:43:17.383Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:43:17.384Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:43:22.392 ThaliTest[338:159474] jxcore: disconnect
,2015-12-17 01:43:22.393 ThaliTest[338:159474] jxcore: disconnect: fail
,2015-12-17T00:43:22.393Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:43:22.394Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT2260.GOF+uA== with availability status: true
,2015-12-17T00:43:22.395Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:43:22.395Z SendDataConnector.js: do connect now
,2015-12-17 01:43:22.396 ThaliTest[338:159474] jxcore: connect Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:43:22.397 ThaliTest[338:159474] client: connect: unreachable Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:43:22.397 ThaliTest[338:159474] jxcore: connect: fail: Peer unreachable
,2015-12-17T00:43:22.398Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-17T00:43:22.399Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-17T00:43:22.399Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17 01:43:23.412 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:43:23.456 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:43:23.457 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:23.674 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:43:27.407Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2260.GOF+uA==
2015-12-17T00:43:27.407Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:43:32.410 ThaliTest[338:159474] jxcore: disconnect
,2015-12-17 01:43:32.410 ThaliTest[338:159474] jxcore: disconnect: fail
,2015-12-17T00:43:32.411Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:43:32.412Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT2260.GOF+uA== with availability status: true
2015-12-17T00:43:32.413Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17T00:43:32.413Z SendDataConnector.js: do connect now
,2015-12-17 01:43:32.414 ThaliTest[338:159474] jxcore: connect Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:43:32.415 ThaliTest[338:159474] client: connect: unreachable Apple-IpadAir2-1_PT2260.GOF+uA==
,2015-12-17 01:43:32.416 ThaliTest[338:159474] jxcore: connect: fail: Peer unreachable
,2015-12-17T00:43:32.416Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-17T00:43:32.417Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-17T00:43:32.419Z SendDataConnector.js: CLIENT Stop now
,2015-12-17 01:43:32.420 ThaliTest[338:159474] jxcore: disconnect
,2015-12-17 01:43:32.421 ThaliTest[338:159474] jxcore: disconnect: fail
,2015-12-17T00:43:32.422Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.GOF+uA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17T00:43:32.425Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17T00:43:32.425Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17T00:43:32.426Z SendDataConnector.js: do connect now
,2015-12-17 01:43:32.427 ThaliTest[338:159474] jxcore: connect Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:32.427 ThaliTest[338:159474] client session: connect
,2015-12-17 01:43:32.429 ThaliTest[338:159474] client session: stateChange:0->1 Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:36.325 ThaliTest[338:160229] client session: connected
2015-12-17 01:43:36.326 ThaliTest[338:160229] client session: stateChange:1->2 Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:36.338 ThaliTest[338:160190] client session: fireConnectCallback: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:43:36.338 ThaliTest[338:160190] jxcore: connect: success
,2015-12-17T00:43:36.340Z SendDataConnector.js: CLIENT connected to 51024, error: null
,2015-12-17T00:43:36.340Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:43:36.343 ThaliTest[338:159245] client: relay established
2015-12-17 01:43:36.343 ThaliTest[338:159245] client: new accepted socket: 0x1749f510
,2015-12-17T00:43:36.362Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:43:36.711Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T00:43:36.711Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-17T00:43:36.712Z SendDataConnector.js: CLIENT Stop now
2015-12-17T00:43:36.712Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:43:36.712 ThaliTest[338:159474] jxcore: disconnect
,2015-12-17 01:43:36.713 ThaliTest[338:159474] client session: disconnectFromPeer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:36.713 ThaliTest[338:159474] client session: disconnect
2015-12-17 01:43:36.713 ThaliTest[338:159474] client session: stateChange:2->0 Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:36.716 ThaliTest[338:159474] jxcore: disconnect: success
2015-12-17T00:43:36.716Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4129.i5O+Uw==
---- round done--------
startWithNextDevice
device[3]: Apple,-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17T00:43:36.717Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17T00:43:36.717Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17T00:43:36.717Z SendDataConnector.js: do connect now
2015-12-17 01:43:36.717 ThaliTest[338:159474] jxcore: connect Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:36.717 ThaliTest[338:159474] client session: connect
2015-12-17 01:43:36.717 ThaliTest[338:159474] client session: stateChange:0->1 Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:43:40.257 ThaliTest[338:160234] client session: connected
2015-12-17 01:43:40.258 ThaliTest[338:160234] client session: stateChange:1->2 Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:43:40.262 ThaliTest[338:160190] client session: fireConnectCallback: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:40.263 ThaliTest[338:160190] jxcore: connect: success
,2015-12-17T00:43:40.264Z SendDataConnector.js: CLIENT connected to 51027, error: null
,2015-12-17T00:43:40.264Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:43:40.267 ThaliTest[338:159245] client: relay established
2015-12-17 01:43:40.267 ThaliTest[338:159245] client: new accepted socket: 0x1754daf0
,2015-12-17T00:43:40.281Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:43:40.573Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-17T00:43:40.586Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-17T00:43:40.599Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-17T00:43:40.624Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-17T00:43:40.637Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T00:43:40.637Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-17T00:43:40.637Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T00:43:40.637Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:43:40.638 ThaliTest[338:159474] jxcore: disconnect
,2015-12-17 01:43:40.638 ThaliTest[338:159474] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:40.638 ThaliTest[338:159474] client session: disconnect
,2015-12-17 01:43:40.638 ThaliTest[338:159474] client session: stateChange:2->0 Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:43:40.641 ThaliTest[338:159474] jxcore: disconnect: success
2015-12-17T00:43:40.641Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17T00:43:40.642Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17T00:43:40.643Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17T00:43:40.643Z SendDataConnector.js:, do connect now
2015-12-17 01:43:40.643 ThaliTest[338:159474] jxcore: connect Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:43:40.643 ThaliTest[338:159474] client session: connect
,2015-12-17 01:43:40.643 ThaliTest[338:159474] client session: stateChange:0->1 Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:43:44.780 ThaliTest[338:160183] client session: connected
2015-12-17 01:43:44.780 ThaliTest[338:160183] client session: stateChange:1->2 Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:43:44.832 ThaliTest[338:160234] client session: fireConnectCallback: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:43:44.832 ThaliTest[338:160234] jxcore: connect: success
,2015-12-17T00:43:44.833Z SendDataConnector.js: CLIENT connected to 51030, error: null
,2015-12-17T00:43:44.834Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:43:44.836 ThaliTest[338:159245] client: relay established
2015-12-17 01:43:44.837 ThaliTest[338:159245] client: new accepted socket: 0x174a7c30
,2015-12-17T00:43:44.850Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:43:45.141Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-17T00:43:45.164Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-17T00:43:45.177Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T00:43:45.177Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-17T00:43:45.177Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T00:43:45.178Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-17 01:43:45.178 ThaliTest[338:159474] jxcore: disconnect
,2015-12-17 01:43:45.178 ThaliTest[338:159474] client session: disconnectFromPeer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:43:45.179 ThaliTest[338:159474] client session: disconnect
2015-12-17 01:43:45.179 ThaliTest[338:159474] client session: stateChange:2->0 Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:43:45.182 ThaliTest[338:159474] jxcore: disconnect: success
2015-12-17T00:43:45.182Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6883.KeEEhw==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2015-12-17T00:43:45.186Z SendDataConnector.js: CLIENT Stop now
2015-12-17T00:43:45.186Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:43:53.412 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:43:53.451 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:43:53.451 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:53.453 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:44:01.470 ThaliTest[338:159245] client: lost peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:44:01.471 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone6-1_PT4129.i5O+Uw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
2015-12-17 01:44:01.472 ThaliTest[338:159245] client: lost peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:44:01.473 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-17 01:44:06.640 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:44:08.851 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-17 01:44:18.190 ThaliTest[338:159245] multipeer session: reset timer
2015-12-17 01:44:18.190 ThaliTest[338:159245] multipeer session: stop timer
2015-12-17 01:44:18.191 ThaliTest[338:159245] multipeer session: start timer: 0x17496370
,2015-12-17 01:44:18.191 ThaliTest[338:159245] server session: connect
2015-12-17 01:44:18.191 ThaliTest[338:159245] server session: stateChange:0->1 Apple-Iphone5-1_PT6883
,2015-12-17 01:44:18.199 ThaliTest[338:159245] server: accepting invitation Apple-Iphone5-1_PT6883
,2015-12-17 01:44:20.988 ThaliTest[338:160332] server session: connected
,2015-12-17 01:44:20.989 ThaliTest[338:160332] server session: stateChange:1->2 Apple-Iphone5-1_PT6883
,2015-12-17 01:44:21.209 ThaliTest[338:159245] server relay: connected (to port: 51016)
,2015-12-17T00:44:21.212Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T00:44:21.726Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-17T00:44:21.740Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-17T00:44:21.754Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-17T00:44:21.768Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 01:44:21.850 ThaliTest[338:160434] server session: not connected Apple-Iphone5-1_PT6883
,2015-12-17 01:44:27.105 ThaliTest[338:159245] multipeer session: reset timer
2015-12-17 01:44:27.105 ThaliTest[338:159245] multipeer session: stop timer
2015-12-17 01:44:27.105 ThaliTest[338:159245] multipeer session: start timer: 0x17496370
2015-12-17 01:44:27.106 ThaliTest[338:159245] server session: connect
2015-12-17 01:44:27.106 ThaliTest[338:159245] server session: stateChange:0->1 Apple-Iphone6-1_PT4129
,2015-12-17 01:44:27.113 ThaliTest[338:159245] server: accepting invitation Apple-Iphone6-1_PT4129
,2015-12-17 01:44:29.880 ThaliTest[338:160434] server session: connected
2015-12-17 01:44:29.881 ThaliTest[338:160434] server session: stateChange:1->2 Apple-Iphone6-1_PT4129
,2015-12-17 01:44:29.887 ThaliTest[338:159245] server relay: connected (to port: 51016)
,2015-12-17T00:44:29.892Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T00:44:30.180Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-17T00:44:30.198Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-17T00:44:30.217Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 01:44:30.263 ThaliTest[338:160385] server session: not connected Apple-Iphone6-1_PT4129
,2015-12-17 01:44:34.815 ThaliTest[338:159245] client: lost peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:34.816 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone5s-1_PT4765.ZBlg+A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-17 01:44:39.666 ThaliTest[338:159245] client: lost peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:44:39.667 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone6-1_PT4129.i5O+Uw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-17 01:44:41.145 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:44:57.107 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:44:57.139 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:57.139 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:44:57.141 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-17 01:45:27.107 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:45:27.141 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:45:27.142 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:45:57.107 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:45:57.141 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:45:57.141 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:46:06.074 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:46:22.415 ThaliTest[338:159245] client: lost peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:46:22.415 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone6-1_PT4129.i5O+Uw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-17 01:46:23.803 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-17 01:46:27.107 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:46:27.150 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:46:27.150 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:46:27.152 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:46:57.107 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:46:57.140 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:46:57.140 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:47:27.107 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:47:27.142 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:47:27.142 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:47:27.143 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:47:57.107 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:47:57.140 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:47:57.140 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:48:27.107 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:48:27.135 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:48:27.147 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:48:27.148 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:48:57.106 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:48:57.137 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:48:57.137 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:49:27.107 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:49:27.145 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:49:27.147 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:49:27.148 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:49:53.659 ThaliTest[338:159245] client: lost peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:49:53.660 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-17 01:49:57.107 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:49:57.137 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:49:57.137 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:50:27.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:50:27.121 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:50:27.135 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:50:27.136 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:50:52.120 ThaliTest[338:159245] client: lost peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:50:52.120 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-17 01:50:55.772 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:50:57.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:50:57.133 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:50:57.133 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:50:57.136 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:51:27.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:51:27.126 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:51:27.127 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:51:29.933 ThaliTest[338:159245] client: lost peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:51:29.933 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone5-1_PT6883.KeEEhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-17 01:51:41.094 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:51:42.092 ThaliTest[338:159245] client: lost peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:51:42.092 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone6-1_PT4129.i5O+Uw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-17 01:51:49.620 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-17 01:51:57.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:51:57.121 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:51:57.135 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:51:57.135 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:52:27.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:52:27.126 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:52:27.127 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:52:57.091 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:52:57.131 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:52:57.133 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:52:57.134 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:53:24.798 ThaliTest[338:159245] client: lost peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:53:24.798 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-17 01:53:27.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:53:27.118 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:53:27.120 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:53:57.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:53:57.124 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:53:57.126 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:54:27.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:54:27.123 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:54:27.135 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:54:27.135 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:54:57.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:54:57.129 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:54:57.131 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:55:27.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:55:27.128 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:55:27.130 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:55:27.131 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:55:29.507 ThaliTest[338:159245] client: lost peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:55:29.507 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone6-1_PT4129.i5O+Uw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-17 01:55:57.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:55:57.122 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:55:57.130 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:55:57.131 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:56:27.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:56:27.126 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:56:27.126 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:56:49.488 ThaliTest[338:159245] client: lost peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:56:49.489 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone6-1_PT4129.i5O+Uw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-17 01:56:57.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:56:57.121 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:56:57.121 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:56:57.129 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:57:27.091 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:57:27.127 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:57:27.127 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:57:27.128 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:57:57.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:57:57.119 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:57:57.132 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:57:57.132 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:58:27.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:58:27.122 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:58:27.124 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:58:57.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:58:57.121 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:58:57.122 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:58:57.129 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:59:02.786 ThaliTest[338:159245] client: lost peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:59:02.786 ThaliTest[338:159245] client session: onPeerLost: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-17 01:59:05.644 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:59:27.092 ThaliTest[338:159245] multipeer session: restart
,2015-12-17 01:59:27.121 ThaliTest[338:159245] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:59:27.133 ThaliTest[338:159245] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:59:27.134 ThaliTest[338:159245] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,teardown
,testSendData stopped
,2015-12-17 01:59:32.046 ThaliTest[338:159474] jxcore: stopBroadcasting
,2015-12-17 01:59:32.046 ThaliTest[338:159474] THEMultipeerSession stopping peer
2015-12-17 01:59:32.047 ThaliTest[338:159474] multipeer session: stop timer
,2015-12-17 01:59:32.048 ThaliTest[338:159474] server session: disconnect
,2015-12-17 01:59:32.048 ThaliTest[338:159474] server session: stateChange:2->0 Apple-Iphone6-1_PT4129
,2015-12-17 01:59:32.057 ThaliTest[338:159474] server session: disconnect
2015-12-17 01:59:32.057 ThaliTest[338:159474] server session: stateChange:2->0 Apple-Iphone5-1_PT6883
,2015-12-17 01:59:32.070 ThaliTest[338:159474] server session: disconnect
2015-12-17 01:59:32.070 ThaliTest[338:159474] server session: stateChange:2->0 Apple-Iphone5s-1_PT4765
,2015-12-17 01:59:32.076 ThaliTest[338:159474] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-17T00:59:32.095Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T00:59:32.097Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T00:59:32.098Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T00:59:32.099Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
