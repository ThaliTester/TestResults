#### Test 50650278923ff9f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D0E2852C-FD3E-4FC2-BA3C-BD416363231A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D0E2852C-FD3E-4FC2-BA3C-BD416363231A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/06BB3B88-DEE4-4E7E-965D-5D997D057B97/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58657"
,(lldb)     command script import "/tmp/D0E2852C-FD3E-4FC2-BA3C-BD416363231A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-16 16:44:04.176 ThaliTest[286:109451] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E809714C-B30A-4347-9C22-00792E676315/Library/Cookies/Cookies.binarycookies
,2015-12-16 16:44:04.565 ThaliTest[286:109451] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 16:44:04.566 ThaliTest[286:109451] Multi-tasking -> Device: YES, App: YES
,2015-12-16 16:44:04.574 ThaliTest[286:109451] Unlimited access to network resources
,2015-12-16 16:44:04.584 ThaliTest[286:109451] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 16:44:13.539 ThaliTest[286:109451] Resetting plugins due to page load.
,2015-12-16 16:44:16.634 ThaliTest[286:109451] Finished load of: file:///var/mobile/Containers/Bundle/Application/06BB3B88-DEE4-4E7E-965D-5D997D057B97/ThaliTest.app/www/index.html
,2015-12-16 16:44:16.799 ThaliTest[286:109451] JXcore Cordova plugin initializing
,2015-12-16 16:44:16.800 ThaliTest[286:109725] JXcore instance initializing
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
,2015-12-16 16:44:17.790 ThaliTest[286:109451] THREAD WARNING: ['JXcore'] took '70.999268' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 16:49:29.361 ThaliTest[286:109725] jxcore: startBroadcasting
,2015-12-16 16:49:29.378 ThaliTest[286:109725] server: starting Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16 16:49:29.379 ThaliTest[286:109725] multipeer session: start timer: 0x17d5c2b0
2015-12-16 16:49:29.380 ThaliTest[286:109725] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1077
,2015-12-16 16:49:29.381 ThaliTest[286:109725] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-16 16:49:30.819 ThaliTest[286:109451] client: found peer: Apple-Iphone6-1_PT3392.Ts8/9g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3392.Ts8/9g==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT3392.Ts8/9g==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-16 16:49:30.899 ThaliTest[286:109451] client: found peer: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:30.899 ThaliTest[286:109451] client: found peer: Apple-Iphone5-1_PT9225.vQjqPA==
,teardown
,testFindPeers stopped
,2015-12-16 16:49:31.759 ThaliTest[286:109725] jxcore: stopBroadcasting
2015-12-16 16:49:31.760 ThaliTest[286:109725] THEMultipeerSession stopping peer
,2015-12-16 16:49:31.760 ThaliTest[286:109725] multipeer session: stop timer
,2015-12-16 16:49:31.761 ThaliTest[286:109725] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 50422
,2015-12-16 16:49:32.228 ThaliTest[286:109725] jxcore: startBroadcasting
,2015-12-16 16:49:32.232 ThaliTest[286:109725] server: starting Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:49:32.234 ThaliTest[286:109725] multipeer session: start timer: 0x15f77e20
,2015-12-16 16:49:32.234 ThaliTest[286:109725] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1077
2015-12-16 16:49:32.236 ThaliTest[286:109725] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2015-12-16T15:49:32.240Z SendDataTCPServer.js: TCP/IP server is bound to port: 50422
,2015-12-16 16:49:32.958 ThaliTest[286:109451] client: found peer: Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16 16:49:32.959 ThaliTest[286:109451] client: found peer: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:32.961 ThaliTest[286:109451] client: found peer: Apple-Iphone5-1_PT9225.vQjqPA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3392.Ts8/9g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:49:32.966Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:49:32.967Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16T15:49:32.967Z SendDataConnector.js: do connect now
,2015-12-16 16:49:32.968 ThaliTest[286:109725] jxcore: connect Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:32.969 ThaliTest[286:109725] client session: connect
,2015-12-16 16:49:32.969 ThaliTest[286:109725] client session: stateChange:0->1 Apple-Iphone6-1_PT3392.Ts8/9g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.WIj3og==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9225.vQjqPA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 16:49:33.496 ThaliTest[286:109451] client: lost peer: Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16 16:49:33.496 ThaliTest[286:109451] client session: onPeerLost: Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16 16:49:33.496 ThaliTest[286:109451] client session: onLinkFailure: Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:33.497 ThaliTest[286:109451] client session: disconnect
,2015-12-16 16:49:33.498 ThaliTest[286:109451] client session: stateChange:1->0 Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:33.499 ThaliTest[286:109451] client session: fireConnectCallback: Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16 16:49:33.499 ThaliTest[286:109451] jxcore: connect: fail: Peer disconnected
2015-12-16 16:49:33.499 ThaliTest[286:109451] client: lost peer: Apple-Iphone5-1_PT9225.vQjqPA==
2015-12-16T15:49:33.501Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-16 16:49:33.500 ThaliTest[286:109451] client session: onPeerLost: Apple-Iphone5-1_PT9225.vQjqPA==
2015-12,-16T15:49:33.502Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16 16:49:33.502 ThaliTest[286:109451] client: found peer: Apple-Iphone6-1_PT3392.EGNu6Q==
2015-12-16 16:49:33.503 ThaliTest[286:109451] client: found peer: Apple-Ip,hone5-1_PT9225.kJjMbg==
2015-12-16T15:49:33.503Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3392.Ts8/9g==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9225.vQjqPA==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3392.EGNu6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9225.kJjMbg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-16 16:49:34.497 ThaliTest[286:109451] client: lost peer: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:34.497 ThaliTest[286:109451] client session: onPeerLost: Apple-Iphone5s-1_PT1155.WIj3og==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.WIj3og==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-16 16:49:35.012 ThaliTest[286:109451] client: found peer: Apple-Iphone5s-1_PT1155.Bev+OQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.Bev+OQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16T15:49:38.515Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:49:38.516Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:43.521 ThaliTest[286:109725] jxcore: disconnect
2015-12-16 16:49:43.522 ThaliTest[286:109725] jxcore: disconnect: fail
,2015-12-16T15:49:43.523Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:49:43.523Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT3392.Ts8/9g== with availability status: true
,2015-12-16T15:49:43.524Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:49:43.524Z SendDataConnector.js: do connect now
,2015-12-16 16:49:43.525 ThaliTest[286:109725] jxcore: connect Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:43.526 ThaliTest[286:109725] client: connect: unreachable Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:43.526 ThaliTest[286:109725] jxcore: connect: fail: Peer unreachable
,2015-12-16T15:49:43.527Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T15:49:43.528Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-16T15:49:43.529Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:49:48.534Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:49:48.535Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:53.540 ThaliTest[286:109725] jxcore: disconnect
,2015-12-16 16:49:53.540 ThaliTest[286:109725] jxcore: disconnect: fail
,2015-12-16T15:49:53.541Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:49:53.542Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT3392.Ts8/9g== with availability status: true
,2015-12-16T15:49:53.542Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:49:53.543Z SendDataConnector.js: do connect now
,2015-12-16 16:49:53.544 ThaliTest[286:109725] jxcore: connect Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:53.545 ThaliTest[286:109725] client: connect: unreachable Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16 16:49:53.545 ThaliTest[286:109725] jxcore: connect: fail: Peer unreachable
,2015-12-16T15:49:53.546Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T15:49:53.546Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-16T15:49:53.547Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:49:58.556Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:49:58.557Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:50:02.235 ThaliTest[286:109451] multipeer session: restart
,2015-12-16 16:50:02.267 ThaliTest[286:109451] client: found peer: Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:02.278 ThaliTest[286:109451] client: found peer: Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16 16:50:02.279 ThaliTest[286:109451] client: found peer: Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:03.561 ThaliTest[286:109725] jxcore: disconnect
,2015-12-16 16:50:03.561 ThaliTest[286:109725] jxcore: disconnect: fail
,2015-12-16T15:50:03.562Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:50:03.563Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT3392.Ts8/9g== with availability status: true
,2015-12-16T15:50:03.563Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:50:03.564Z SendDataConnector.js: do connect now
,2015-12-16 16:50:03.565 ThaliTest[286:109725] jxcore: connect Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:50:03.565 ThaliTest[286:109725] client: connect: unreachable Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16 16:50:03.566 ThaliTest[286:109725] jxcore: connect: fail: Peer unreachable
2015-12-16T15:50:03.567Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T15:50:03.568Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-16T15:50:03.568Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:50:08.577Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16T15:50:08.578Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:50:13.572 ThaliTest[286:109725] jxcore: disconnect
,2015-12-16 16:50:13.573 ThaliTest[286:109725] jxcore: disconnect: fail
,2015-12-16T15:50:13.573Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:50:13.574Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT3392.Ts8/9g== with availability status: true
,2015-12-16T15:50:13.575Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16T15:50:13.575Z SendDataConnector.js: do connect now
,2015-12-16 16:50:13.576 ThaliTest[286:109725] jxcore: connect Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:50:13.577 ThaliTest[286:109725] client: connect: unreachable Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:50:13.577 ThaliTest[286:109725] jxcore: connect: fail: Peer unreachable
,2015-12-16T15:50:13.578Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T15:50:13.579Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-16T15:50:13.581Z SendDataConnector.js: CLIENT Stop now
,2015-12-16 16:50:13.582 ThaliTest[286:109725] jxcore: disconnect
,2015-12-16 16:50:13.583 ThaliTest[286:109725] jxcore: disconnect: fail
,2015-12-16T15:50:13.584Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3392.Ts8/9g==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16T15:50:13.587Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16T15:50:13.587Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16T15:50:13.588Z SendDataConnector.js: do connect now
,2015-12-16 16:50:13.589 ThaliTest[286:109725] jxcore: connect Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:13.589 ThaliTest[286:109725] client session: connect
,2015-12-16 16:50:13.591 ThaliTest[286:109725] client session: stateChange:0->1 Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:16.858 ThaliTest[286:110523] client session: connected
2015-12-16 16:50:16.858 ThaliTest[286:110523] client session: stateChange:1->2 Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:16.863 ThaliTest[286:110523] client session: fireConnectCallback: Apple-Iphone6-1_PT3392.EGNu6Q==
2015-12-16 16:50:16.863 ThaliTest[286:110523] jxcore: connect: success
,2015-12-16T15:50:16.865Z SendDataConnector.js: CLIENT connected to 50430, error: null
,2015-12-16T15:50:16.866Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 16:50:16.868 ThaliTest[286:109451] client: relay established
2015-12-16 16:50:16.869 ThaliTest[286:109451] client: new accepted socket: 0x17d6ed30
,2015-12-16T15:50:16.885Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T15:50:17.690Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-16T15:50:17.715Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-16T15:50:17.729Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-16T15:50:17.754Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-16T15:50:17.769Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T15:50:17.769Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T15:50:17.771Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T15:50:17.771Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:17.773 ThaliTest[286:109725] jxcore: disconnect
,2015-12-16 16:50:17.774 ThaliTest[286:109725] client session: disconnectFromPeer: Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:17.774 ThaliTest[286:109725] client session: disconnect
,2015-12-16 16:50:17.775 ThaliTest[286:109725] client session: stateChange:2->0 Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:17.786 ThaliTest[286:109725] jxcore: disconnect: success
2015-12-16T15:50:17.787Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3392.EGNu6Q==
---- round done--------
,startWithNextDevice
device[3]: Apple-Iphone5-1_PT9225.kJjMbg==
2015-12-16T15:50:17.789Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9225.kJjMbg==
2015-12-16T15:50:17.790Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16T15:50:17.790Z SendDataConnector.js: do connect now
,2015-12-16 16:50:17.792 ThaliTest[286:109725] jxcore: connect Apple-Iphone5-1_PT9225.kJjMbg==
2015-12-16 16:50:17.792 ThaliTest[286:109725] client session: connect
2015-12-16 16:50:17.792 ThaliTest[286:109725] client session: stateChange:0->1 Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:18.508 ThaliTest[286:109451] multipeer session: reset timer
2015-12-16 16:50:18.508 ThaliTest[286:109451] multipeer session: stop timer
2015-12-16 16:50:18.508 ThaliTest[286:109451] multipeer session: start timer: 0x15f77e20
,2015-12-16 16:50:18.510 ThaliTest[286:109451] server session: connect
2015-12-16 16:50:18.510 ThaliTest[286:109451] server session: stateChange:0->1 Apple-Iphone5-1_PT9225
,2015-12-16 16:50:18.512 ThaliTest[286:109451] server: accepting invitation Apple-Iphone5-1_PT9225
,2015-12-16 16:50:20.680 ThaliTest[286:109451] multipeer session: reset timer
2015-12-16 16:50:20.681 ThaliTest[286:109451] multipeer session: stop timer
2015-12-16 16:50:20.681 ThaliTest[286:109451] multipeer session: start timer: 0x15f77e20
2015-12-16 ,16:50:20.681 ThaliTest[286:109451] server session: connect
2015-12-16 16:50:20.682 ThaliTest[286:109451] server session: stateChange:0->1 Apple-Iphone6-1_PT3392
,2015-12-16 16:50:20.685 ThaliTest[286:110534] client session: connected
,2015-12-16 16:50:20.687 ThaliTest[286:110534] client session: stateChange:1->2 Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:20.694 ThaliTest[286:110534] client session: fireConnectCallback: Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:20.695 ThaliTest[286:110534] jxcore: connect: success
,2015-12-16T15:50:20.697Z SendDataConnector.js: CLIENT connected to 50433, error: null
,2015-12-16T15:50:20.697Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 16:50:20.702 ThaliTest[286:109451] server: accepting invitation Apple-Iphone6-1_PT3392
,2015-12-16 16:50:20.703 ThaliTest[286:109451] client: relay established
,2015-12-16 16:50:20.704 ThaliTest[286:109451] client: new accepted socket: 0x17e2ad10
,2015-12-16T15:50:20.713Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T15:50:21.087Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-16T15:50:21.111Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-16T15:50:21.124Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-16T15:50:21.124Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-16T15:50:21.125Z SendDataConnector.js: CLIENT Stop now
2015-12-16T15:50:21.125Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:21.126 ThaliTest[286:109725] jxcore: disconnect
,2015-12-16 16:50:21.126 ThaliTest[286:109725] client session: disconnectFromPeer: Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:21.126 ThaliTest[286:109725] client session: disconnect
,2015-12-16 16:50:21.126 ThaliTest[286:109725] client session: stateChange:2->0 Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:21.191 ThaliTest[286:109725] jxcore: disconnect: success
,2015-12-16T15:50:21.192Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9225.kJjMbg==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16T15:50:21.193Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16T15:50:21.193Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16T15:50:21.193Z SendDataConnector.js: do connect now
,2015-12-16 16:50:21.194 ThaliTest[286:109725] jxcore: connect Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:21.195 ThaliTest[286:109725] client session: connect
,2015-12-16 16:50:21.195 ThaliTest[286:109725] client session: stateChange:0->1 Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:21.278 ThaliTest[286:110533] server session: connected
2015-12-16 16:50:21.278 ThaliTest[286:110533] server session: stateChange:1->2 Apple-Iphone5-1_PT9225
,2015-12-16 16:50:21.283 ThaliTest[286:109451] server relay: connected (to port: 50422)
,2015-12-16T15:50:21.285Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T15:50:21.799Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-16T15:50:21.814Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-16T15:50:21.827Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-16T15:50:21.841Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-16T15:50:21.855Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-16T15:50:21.869Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:21.913 ThaliTest[286:110534] server session: not connected Apple-Iphone5-1_PT9225
,2015-12-16 16:50:23.299 ThaliTest[286:110534] server session: connected
2015-12-16 16:50:23.299 ThaliTest[286:110534] server session: stateChange:1->2 Apple-Iphone6-1_PT3392
,2015-12-16 16:50:23.305 ThaliTest[286:109451] server relay: connected (to port: 50422)
,2015-12-16T15:50:23.313Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16 16:50:23.338 ThaliTest[286:109451] multipeer session: reset timer
2015-12-16 16:50:23.339 ThaliTest[286:109451] multipeer session: stop timer
2015-12-16 16:50:23.339 ThaliTest[286:109451] multipeer session: start timer: 0x15f77e20
,2015-12-16 16:50:23.339 ThaliTest[286:109451] server session: connect
2015-12-16 16:50:23.340 ThaliTest[286:109451] server session: stateChange:0->1 Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:23.347 ThaliTest[286:109451] server: accepting invitation Apple-Iphone5s-1_PT1155
,2015-12-16T15:50:23.561Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-16T15:50:23.573Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-16T15:50:23.588Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:23.621 ThaliTest[286:110533] server session: not connected Apple-Iphone6-1_PT3392
,2015-12-16 16:50:23.845 ThaliTest[286:110533] client session: connected
2015-12-16 16:50:23.846 ThaliTest[286:110533] client session: stateChange:1->2 Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:23.858 ThaliTest[286:110467] client session: fireConnectCallback: Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16 16:50:23.858 ThaliTest[286:110467] jxcore: connect: success
2015-12-16T15:50:23.859Z SendDataConnector.js: CLIENT connected to 50438, error: null
,2015-12-16T15:50:23.859Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 16:50:23.861 ThaliTest[286:109451] client: relay established
2015-12-16 16:50:23.862 ThaliTest[286:109451] client: new accepted socket: 0x17d85b50
,2015-12-16T15:50:23.874Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T15:50:24.283Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-16T15:50:24.295Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-16T15:50:24.332Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-16T15:50:24.345Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-16T15:50:24.358Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-16T15:50:24.358Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T15:50:24.359Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T15:50:24.359Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:24.360 ThaliTest[286:109725] jxcore: disconnect
,2015-12-16 16:50:24.360 ThaliTest[286:109725] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:24.360 ThaliTest[286:109725] client session: disconnect
,2015-12-16 16:50:24.361 ThaliTest[286:109725] client session: stateChange:2->0 Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:24.366 ThaliTest[286:109725] jxcore: disconnect: success
,2015-12-16T15:50:24.367Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.Bev+OQ==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-16T15:50:24.371Z SendDataConnector.js: CLIENT Stop now
2015-12-16T15:50:24.371Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:25.869 ThaliTest[286:110523] server session: connected
2015-12-16 16:50:25.869 ThaliTest[286:110523] server session: stateChange:1->2 Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:25.875 ThaliTest[286:109451] server relay: connected (to port: 50422)
,2015-12-16T15:50:25.884Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T15:50:26.348Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-16T15:50:26.363Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-16T15:50:26.379Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-16T15:50:26.396Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:26.432 ThaliTest[286:110467] server session: not connected Apple-Iphone5s-1_PT1155
,teardown
,testSendData stopped
,2015-12-16 16:50:35.115 ThaliTest[286:109725] jxcore: stopBroadcasting
,2015-12-16 16:50:35.115 ThaliTest[286:109725] THEMultipeerSession stopping peer
,2015-12-16 16:50:35.116 ThaliTest[286:109725] multipeer session: stop timer
,2015-12-16 16:50:35.117 ThaliTest[286:109725] server session: disconnect
,2015-12-16 16:50:35.119 ThaliTest[286:109725] server session: stateChange:2->0 Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:35.133 ThaliTest[286:109725] server session: disconnect
,2015-12-16 16:50:35.135 ThaliTest[286:109725] server session: stateChange:2->0 Apple-Iphone5-1_PT9225
,2015-12-16 16:50:35.198 ThaliTest[286:109725] server session: disconnect
,2015-12-16 16:50:35.199 ThaliTest[286:109725] server session: stateChange:2->0 Apple-Iphone6-1_PT3392
,2015-12-16 16:50:35.203 ThaliTest[286:109725] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-16T15:50:35.222Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:35.223Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:35.225Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:35.225Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
