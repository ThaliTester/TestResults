#### Test 50650278923ff9f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/C41C8C24-872E-437F-8C7B-0475BB9FFBDF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C41C8C24-872E-437F-8C7B-0475BB9FFBDF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E18869A9-C056-4EA6-BA2E-0C3D6E67E522/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58659"
,(lldb)     command script import "/tmp/C41C8C24-872E-437F-8C7B-0475BB9FFBDF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 16:44:03.792 ThaliTest[296:108585] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8FED4909-0089-4916-9694-CB09D698997B/Library/Cookies/Cookies.binarycookies
,2015-12-16 16:44:04.162 ThaliTest[296:108585] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 16:44:04.163 ThaliTest[296:108585] Multi-tasking -> Device: YES, App: YES
,2015-12-16 16:44:04.173 ThaliTest[296:108585] Unlimited access to network resources
,2015-12-16 16:44:04.186 ThaliTest[296:108585] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 16:44:13.377 ThaliTest[296:108585] Resetting plugins due to page load.
,2015-12-16 16:44:17.138 ThaliTest[296:108585] Finished load of: file:///var/mobile/Containers/Bundle/Application/E18869A9-C056-4EA6-BA2E-0C3D6E67E522/ThaliTest.app/www/index.html
,2015-12-16 16:44:17.323 ThaliTest[296:108585] JXcore Cordova plugin initializing
,2015-12-16 16:44:17.324 ThaliTest[296:108818] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-16 16:44:18.431 ThaliTest[296:108585] THREAD WARNING: ['JXcore'] took '80.634033' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 16:49:28.694 ThaliTest[296:108818] jxcore: startBroadcasting
,2015-12-16 16:49:28.713 ThaliTest[296:108818] server: starting Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:28.714 ThaliTest[296:108818] multipeer session: start timer: 0x18be7170
2015-12-16 16:49:28.715 ThaliTest[296:108818] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3392
2015-12-16 16:49:28.715 ThaliTest[296:108818] jxcore: start,Broadcasting: success
StartBroadcasting started ok
,2015-12-16 16:49:30.088 ThaliTest[296:108585] client: found peer: Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:30.089 ThaliTest[296:108585] client: found peer: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:30.089 ThaliTest[296:108585] client: found peer: Apple-Iphone5-1_PT9225.vQjqPA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1077.nIXSkg==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT1077.nIXSkg==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-16 16:49:31.012 ThaliTest[296:108818] jxcore: stopBroadcasting
2015-12-16 16:49:31.013 ThaliTest[296:108818] THEMultipeerSession stopping peer
2015-12-16 16:49:31.013 ThaliTest[296:108818] multipeer session: stop timer
2015-12-16 16:49:31.014 Th,aliTest[296:108818] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 50477
2015-12-16 16:49:31.085 ThaliTest[296:108818] jxcore: startBroadcasting
,2015-12-16 16:49:31.088 ThaliTest[296:108818] server: starting Apple-Iphone6-1_PT3392.EGNu6Q==
2015-12-16 16:49:31.089 ThaliTest[296:108818] multipeer session: start timer: 0x18c84280
2015-12-16 16:49:31.090 ThaliTest[296:108818] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT3392
2015-12-16 16:49:31.090 ThaliTest[296:108818] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-16T15:49:31.094Z SendDataTCPServer.js: TCP/IP server is bound to port: 50477
,2015-12-16 16:49:31.570 ThaliTest[296:108585] client: found peer: Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:31.570 ThaliTest[296:108585] client: found peer: Apple-Iphone5-1_PT9225.vQjqPA==
2015-12-16 16:49:31.571 ThaliTest[296:108585] client: fou,nd peer: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:31.571 ThaliTest[296:108585] client: found peer: Apple-Iphone6-1_PT3392.Ts8/9g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1077.nIXSkg==","peerName":"(null)","peerAvailable":,true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16T15:49:31.575Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16T15:49:31.576Z SendDataConnect,or.js: doConnect called with peer Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16T15:49:31.576Z SendDataConnector.js: do connect now
2015-12-16 16:49:31.577 ThaliTest[296:108818] jxcore: connect Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:31.578 Thali,Test[296:108818] client session: connect
2015-12-16 16:49:31.582 ThaliTest[296:108818] client session: stateChange:0->1 Apple-IpadAir2-1_PT1077.nIXSkg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9225.vQjqPA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.WIj3og==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3392.Ts8/9g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 16:49:32.438 ThaliTest[296:108585] client: lost peer: Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16 16:49:32.439 ThaliTest[296:108585] client session: onPeerLost: Apple-Iphone6-1_PT3392.Ts8/9g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT3392.Ts8/9g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-16 16:49:32.591 ThaliTest[296:108585] client: lost peer: Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:32.591 ThaliTest[296:108585] client session: onPeerLost: Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:32.592 ThaliTest[296:108585] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:32.592 ThaliTest[296:108585] client session: disconnect
2015-12-16 16:49:32.592 ThaliTest[296:108585] client session: stateChange:1->0 Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12,-16 16:49:32.593 ThaliTest[296:108585] client session: fireConnectCallback: Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:32.593 ThaliTest[296:108585] jxcore: connect: fail: Peer disconnected
2015-12-16T15:49:32.595Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer disconnected
2015-12-16T15:49:32.596Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T15:49:32.596Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAi,r2-1_PT1077.nIXSkg==","peerName":"(null)","peerAvailable":false}]
,2015-12-16 16:49:32.614 ThaliTest[296:108585] client: lost peer: Apple-Iphone5-1_PT9225.vQjqPA==
2015-12-16 16:49:32.615 ThaliTest[296:108585] client session: onPeerLost: Apple-Iphone5-1_PT9225.vQjqPA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9225.vQjqPA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-16 16:49:32.715 ThaliTest[296:108585] client: found peer: Apple-Iphone5-1_PT9225.kJjMbg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9225.kJjMbg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 16:49:33.639 ThaliTest[296:108585] client: lost peer: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:33.640 ThaliTest[296:108585] client session: onPeerLost: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:33.641 ThaliTest[296:108585] cli,ent: found peer: Apple-Iphone5s-1_PT1155.Bev+OQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.WIj3og==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-12-16 16:49:33.642 ThaliTest[296:10858,5] client: found peer: Apple-IpadAir2-1_PT1077.khzDiQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.Bev+OQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifi,er":"Apple-IpadAir2-1_PT1077.khzDiQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16T15:49:37.609Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16T15:49:37.610Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16 16:49:42.614 ThaliTest[296:108818] jxcore: disconnect
2015-12-16 16:49:42.614 ThaliTest[296:108818] jxcore: disconnect: fail
2015-12-16T15:49:42.615Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1077.nIXSkg==,
2015-12-16T15:49:42.615Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT1077.nIXSkg== with availability status: true
2015-12-16T15:49:42.616Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16T15:49:42.616Z SendDataConnector.js: do connect now
,2015-12-16 16:49:42.617 ThaliTest[296:108818] jxcore: connect Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16 16:49:42.618 ThaliTest[296:108818] client: connect: unreachable Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:42.619 ThaliTest[296:108818] jxcore: connect: fail: Peer unreachable
2015-12-16T15:49:42.619Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-16T15:49:42.620Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T15:49:42.620Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:49:47.632Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16T15:49:47.632Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16 16:49:52.636 ThaliTest[296:108818] jxcore: disconnect
2015-12-16 16:49:52.637 ThaliTest[296:108818] jxcore: disconnect: fail
2015-12-16T15:49:52.637Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1077.nIXSkg==,
2015-12-16T15:49:52.638Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT1077.nIXSkg== with availability status: true
2015-12-16T15:49:52.638Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16T15:49:52.638Z SendDataConnector.js: do connect now
,2015-12-16 16:49:52.640 ThaliTest[296:108818] jxcore: connect Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:52.641 ThaliTest[296:108818] client: connect: unreachable Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:52.641 ThaliTest[296:108818] jxcor,e: connect: fail: Peer unreachable
2015-12-16T15:49:52.641Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T15:49:52.642Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T15:49:52.642Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:49:57.646Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16T15:49:57.646Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16 16:50:01.091 ThaliTest[296:108585] multipeer session: restart
,2015-12-16 16:50:01.128 ThaliTest[296:108585] client: found peer: Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:01.142 ThaliTest[296:108585] client: found peer: Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16 16:50:01.143 ThaliTest[296:108585] client: found peer: Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:02.653 ThaliTest[296:108818] jxcore: disconnect
2015-12-16 16:50:02.653 ThaliTest[296:108818] jxcore: disconnect: fail
2015-12-16T15:50:02.654Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1077.nIXSkg==,
2015-12-16T15:50:02.654Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT1077.nIXSkg== with availability status: true
2015-12-16T15:50:02.654Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1077.nIXSkg==
20,15-12-16T15:50:02.655Z SendDataConnector.js: do connect now
,2015-12-16 16:50:02.656 ThaliTest[296:108818] jxcore: connect Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:50:02.657 ThaliTest[296:108818] client: connect: unreachable Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:50:02.657 ThaliTest[296:108818] jxcor,e: connect: fail: Peer unreachable
2015-12-16T15:50:02.657Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T15:50:02.658Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T15:50:02.658Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16 16:50:03.236 ThaliTest[296:108585] client: lost peer: Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16 16:50:03.237 ThaliTest[296:108585] client session: onPeerLost: Apple-Iphone5s-1_PT1155.Bev+OQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.Bev+OQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-16T15:50:07.615Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16T15:50:07.615Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16 16:50:07.875 ThaliTest[296:108585] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1441.VYOaAw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 16:50:12.606 ThaliTest[296:108585] client: found peer: Apple-Iphone5s-1_PT1155.Bev+OQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.Bev+OQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-16 16:50:12.620 ThaliTest[296:108818] jxcore: disconnect
2015-12-16 16:50:12.620 ThaliTest[296:108818] jxcore: disconnect: fail
2015-12-16T15:50:12.621Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1077.nIXSkg==,
2015-12-16T15:50:12.621Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT1077.nIXSkg== with availability status: true
2015-12-16T15:50:12.622Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16T15:50:12.622Z SendDataConnector.js: do connect now
2015-12-16 16:50:12.623 ThaliTest[296:108818] jxcore: connect Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16 16:50:12.624 ThaliTest[296:108818] client: connect: unreachable Apple-IpadAir2-1_PT1077.nIXSkg==
,2015-12-16 16:50:12.624 ThaliTest[296:108818] jxcore: connect: fail: Peer unreachable
,2015-12-16T15:50:12.625Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T15:50:12.626Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-16T15:50:12.628Z SendDataConnector.js: CLIENT Stop now
,2015-12-16 16:50:12.629 ThaliTest[296:108818] jxcore: disconnect
2015-12-16 16:50:12.630 ThaliTest[296:108818] jxcore: disconnect: fail
2015-12-16T15:50:12.630Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1077.nIXSkg==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16T15:50:12.634Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16T15:50:12.634Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16T15:50:12.635Z SendDataConnector.js: do connect now
,2015-12-16 16:50:12.636 ThaliTest[296:108818] jxcore: connect Apple-Iphone5-1_PT9225.kJjMbg==
2015-12-16 16:50:12.636 ThaliTest[296:108818] client session: connect
2015-12-16 16:50:12.637 ThaliTest[296:108818] client session: stateChange:0->1 Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:12.884 ThaliTest[296:108585] multipeer session: reset timer
2015-12-16 16:50:12.884 ThaliTest[296:108585] multipeer session: stop timer
2015-12-16 16:50:12.885 ThaliTest[296:108585] multipeer session: start timer: 0x18c84280
2015-12-16 16:50:12.885 ThaliTest[296:108585] server session: connect
2015-12-16 16:50:12.885 ThaliTest[296:108585] server session: stateChange:0->1 Apple-IpadAir2-1_PT1077
,2015-12-16 16:50:12.902 ThaliTest[296:108585] server: accepting invitation Apple-IpadAir2-1_PT1077
,2015-12-16 16:50:14.061 ThaliTest[296:108585] multipeer session: reset timer
2015-12-16 16:50:14.061 ThaliTest[296:108585] multipeer session: stop timer
2015-12-16 16:50:14.061 ThaliTest[296:108585] multipeer session: start timer: 0x18c84280
2015-12-16 16:50:14.062 ThaliTest[296:108585] server session: connect
2015-12-16 16:50:14.062 ThaliTest[296:108585] server session: stateChange:0->1 Apple-Iphone5-1_PT9225
,2015-12-16 16:50:14.073 ThaliTest[296:108585] server: accepting invitation Apple-Iphone5-1_PT9225
,2015-12-16 16:50:15.645 ThaliTest[296:109774] client session: connected
2015-12-16 16:50:15.645 ThaliTest[296:109774] client session: stateChange:1->2 Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:15.705 ThaliTest[296:109537] client session: fireConnectCallback: Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:15.709 ThaliTest[296:109537] jxcore: connect: success
2015-12-16T15:50:15.712Z SendDataConnector.js: CLIENT connected to 50485, error: null
2015-12-16T15:50:15.712Z SendDataConnector.js: CLIENT starting client 
2015-12-16 16:50:15.716 T,haliTest[296:108585] client: relay established
2015-12-16 16:50:15.716 ThaliTest[296:108585] client: new accepted socket: 0x18c92af0
,2015-12-16T15:50:15.730Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16 16:50:15.957 ThaliTest[296:109499] server session: connected
2015-12-16 16:50:15.957 ThaliTest[296:109499] server session: stateChange:1->2 Apple-IpadAir2-1_PT1077
,2015-12-16T15:50:16.160Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-16T15:50:16.183Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-16T15:50:16.196Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-16T15:50:16.209Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T15:50:16.210Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-16T15:50:16.210Z SendDataConnector.js: CLIENT Stop now
2015-12-16T15:50:16.210Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:16.211 ThaliTest[296:108818] jxcore: disconnect
2015-12-16 16:50:16.211 ThaliTest[296:108818] client session: disconnectFromPeer: Apple-Iphone5-1_PT9225.kJjMbg==
2015-12-16 16:50:16.211 ThaliTest[296:108818] client session: disconnect
2015-12-16 16:50:16.211 ThaliTest[296:108818] client session: stateChange:2->0 Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:16.217 ThaliTest[296:108818] jxcore: disconnect: success
2015-12-16T15:50:16.217Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9225.kJjMbg==
---- round done--------
startWithNextDevice
device[3]: Apple,-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16T15:50:16.218Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16T15:50:16.218Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16T15:50:16.218Z SendDataConnector.js: do connect now
2015-12-16 16:50:16.218 ThaliTest[296:108818] jxcore: connect Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16 16:50:16.218 ThaliTest[296:108818] client session: connect
2015-12-16 16:50:16.218 ThaliTest[296:108,818] client session: stateChange:0->1 Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:16.683 ThaliTest[296:109499] server session: connected
2015-12-16 16:50:16.684 ThaliTest[296:109499] server session: stateChange:1->2 Apple-Iphone5-1_PT9225
,2015-12-16T15:50:16.691Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16 16:50:16.694 ThaliTest[296:108585] server relay: connected (to port: 50477)
,2015-12-16 16:50:16.747 ThaliTest[296:108585] server relay: connected (to port: 50477)
,2015-12-16T15:50:16.759Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T15:50:16.778Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
2015-12-16T15:50:16.797Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-16T15:50:16.819Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
2015-12-16T15:50:16.832Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-16T15:50:16.845Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-16T15:50:16.863Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:16.910 ThaliTest[296:109537] server session: not connected Apple-IpadAir2-1_PT1077
,2015-12-16T15:50:17.354Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-16T15:50:17.368Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-16T15:50:17.384Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-16T15:50:17.400Z SendDataTCPServer.js: TCP/IP server has received 85126 bytes of data
,2015-12-16T15:50:17.414Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:17.465 ThaliTest[296:109787] server session: not connected Apple-Iphone5-1_PT9225
,2015-12-16 16:50:19.216 ThaliTest[296:109774] client session: connected
2015-12-16 16:50:19.216 ThaliTest[296:109774] client session: stateChange:1->2 Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:19.241 ThaliTest[296:109537] client session: fireConnectCallback: Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16 16:50:19.241 ThaliTest[296:109537] jxcore: connect: success
2015-12-16T15:50:19.242Z SendDataConnector.js: CLIENT connected to 50490, error: null
2015-12-16T15:50:19.243Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 16:50:19.247 ThaliTest[296:108585] client: relay established
2015-12-16 16:50:19.247 ThaliTest[296:108585] client: new accepted socket: 0x18c77f30
,2015-12-16T15:50:19.260Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T15:50:19.720Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-16T15:50:19.733Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T15:50:19.733Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T15:50:19.734Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T15:50:19.734Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:19.735 ThaliTest[296:108818] jxcore: disconnect
2015-12-16 16:50:19.735 ThaliTest[296:108818] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16 16:50:19.735 ThaliTest[296:108818] client session: disconnect
2015-12-16 16:50:19.735 ThaliTest[296:108818] client session: stateChange:2->0 Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:19.741 ThaliTest[296:108818] jxcore: disconnect: success
2015-12-16T15:50:19.741Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.Bev+OQ==
---- round done--------
startWithNextDevice
device[4]: Appl,e-IpadAir2-1_PT1077.khzDiQ==
2015-12-16T15:50:19.742Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16T15:50:19.742Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16T15:,50:19.742Z SendDataConnector.js: do connect now
2015-12-16 16:50:19.742 ThaliTest[296:108818] jxcore: connect Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:19.742 ThaliTest[296:108818] client session: connect
2015-12-16 16:50:19.744 ThaliTest[296:108818] client session: stateChange:0->1 Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:19.822 ThaliTest[296:108585] multipeer session: reset timer
2015-12-16 16:50:19.823 ThaliTest[296:108585] multipeer session: stop timer
2015-12-16 16:50:19.823 ThaliTest[296:108585] multipeer session: start timer: 0x18c84280
2015-12-16 16:50:19.823 ThaliTest[296:108585] server session: connect
2015-12-16 16:50:19.823 ThaliTest[296:108585] server session: stateChange:0->1 Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:19.827 ThaliTest[296:108585] server: accepting invitation Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:22.003 ThaliTest[296:109499] server session: connected
,2015-12-16 16:50:22.003 ThaliTest[296:109499] server session: stateChange:1->2 Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:22.024 ThaliTest[296:108585] server relay: connected (to port: 50477)
,2015-12-16T15:50:22.026Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T15:50:22.316Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-16T15:50:22.331Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-16T15:50:22.348Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
2015-12-16T15:50:22.363Z SendDataTCPServer.js: TCP/IP server has received 76366 bytes of data
,2015-12-16T15:50:22.380Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:22.403 ThaliTest[296:109805] client session: connected
2015-12-16 16:50:22.403 ThaliTest[296:109805] client session: stateChange:1->2 Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:22.422 ThaliTest[296:109499] server session: not connected Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:22.423 ThaliTest[296:109805] client session: fireConnectCallback: Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16 16:50:22.425 ThaliTest[296:109805] jxcore: connect: success
2015-12-16T15:50:22.426Z SendDataConnector.js: CLIENT connected to ,50494, error: null
2015-12-16T15:50:22.426Z SendDataConnector.js: CLIENT starting client 
2015-12-16 16:50:22.428 ThaliTest[296:108585] client: relay established
2015-12-16 16:50:22.429 ThaliTest[296:108585] client: new accepted socket: 0x175f3640
,2015-12-16T15:50:22.441Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T15:50:22.682Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-16T15:50:22.695Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-16T15:50:22.708Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T15:50:22.708Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-16T15:50:22.709Z SendDataConnector.js: CLIENT Stop now
2015-12-16T15:50:22.709Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:22.709 ThaliTest[296:108818] jxcore: disconnect
2015-12-16 16:50:22.710 ThaliTest[296:108818] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16 16:50:22.710 ThaliTest[296:108818] client session: disconnect
2015-12-16 16:50:22.710 ThaliTest[296:108818] client session: stateChange:2->0 Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:22.715 ThaliTest[296:108818] jxcore: disconnect: success
2015-12-16T15:50:22.715Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1077.khzDiQ==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2015-12-16T15:50:22.719Z SendDataConnector.js: CLIENT Stop now
2015-12-16T15:50:22.719Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-16 16:50:34.145 ThaliTest[296:108818] jxcore: stopBroadcasting
2015-12-16 16:50:34.146 ThaliTest[296:108818] THEMultipeerSession stopping peer
2015-12-16 16:50:34.146 ThaliTest[296:108818] multipeer session: stop timer
2015-12-16 16:50:34.147 Th,aliTest[296:108818] server session: disconnect
2015-12-16 16:50:34.147 ThaliTest[296:108818] server session: stateChange:2->0 Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:34.244 ThaliTest[296:108818] server session: disconnect
,2015-12-16 16:50:34.246 ThaliTest[296:108818] server session: stateChange:2->0 Apple-Iphone5-1_PT9225
,2015-12-16 16:50:34.255 ThaliTest[296:108818] server session: disconnect
,2015-12-16 16:50:34.260 ThaliTest[296:108818] server session: stateChange:2->0 Apple-IpadAir2-1_PT1077
,2015-12-16 16:50:34.269 ThaliTest[296:108818] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-16T15:50:34.289Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:34.290Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:34.292Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:34.293Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
