#### Test 506502781a07ac8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/693488E9-F013-44EE-AAE5-3BC6914FF3B7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/693488E9-F013-44EE-AAE5-3BC6914FF3B7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A53B4883-2301-4967-8911-1861AC1C8EBB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59785"
,(lldb)     command script import "/tmp/693488E9-F013-44EE-AAE5-3BC6914FF3B7/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-18 12:24:34.697 ThaliTest[407:336416] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8BC37C33-1FDD-4997-85BC-529649C75F7A/Library/Cookies/Cookies.binarycookies
,2015-12-18 12:24:35.103 ThaliTest[407:336416] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 12:24:35.105 ThaliTest[407:336416] Multi-tasking -> Device: YES, App: YES
,2015-12-18 12:24:35.115 ThaliTest[407:336416] Unlimited access to network resources
,2015-12-18 12:24:35.128 ThaliTest[407:336416] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 12:24:44.060 ThaliTest[407:336416] Resetting plugins due to page load.
,2015-12-18 12:24:47.401 ThaliTest[407:336416] Finished load of: file:///var/mobile/Containers/Bundle/Application/A53B4883-2301-4967-8911-1861AC1C8EBB/ThaliTest.app/www/index.html
,2015-12-18 12:24:47.641 ThaliTest[407:336416] JXcore Cordova plugin initializing
2015-12-18 12:24:47.642 ThaliTest[407:336627] JXcore instance initializing
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
,2015-12-18 12:24:48.740 ThaliTest[407:336416] THREAD WARNING: ['JXcore'] took '81.351074' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-18 12:31:19.743 ThaliTest[407:336627] jxcore: startBroadcasting
,2015-12-18 12:31:19.758 ThaliTest[407:336627] server: starting Apple-Iphone6-1_PT3077.XaIcQQ==
2015-12-18 12:31:19.759 ThaliTest[407:336627] multipeer session: start timer: 0x18ccd380
2015-12-18 12:31:19.759 ThaliTest[407:336627] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3077
2015-12-18 12:31:19.760 ThaliTest[407:336627] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-18 12:31:20.863 ThaliTest[407:336416] client: found peer: Apple-IpadAir2-1_PT6115.H3bAHA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.H3bAHA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT6115.H3bAHA==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2015-12-18 12:31:21.901 ThaliTest[407:336416] client: found peer: Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:22.545 ThaliTest[407:336416] client: found peer: Apple-Iphone5s-1_PT8285.POBncQ==
,teardown
,testFindPeers stopped
,2015-12-18 12:31:23.134 ThaliTest[407:336627] jxcore: stopBroadcasting
2015-12-18 12:31:23.135 ThaliTest[407:336627] THEMultipeerSession stopping peer
2015-12-18 12:31:23.135 ThaliTest[407:336627] multipeer session: stop timer
2015-12-18 12:31:23.136 Th,aliTest[407:336627] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 52036
,2015-12-18 12:31:23.210 ThaliTest[407:336627] jxcore: startBroadcasting
,2015-12-18 12:31:23.215 ThaliTest[407:336627] server: starting Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:31:23.219 ThaliTest[407:336627] multipeer session: start timer: 0x18a773b0
2015-12-18 12:31:23.222 ThaliTest[407:336627] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3077
2015-12-18 12:31:23.222 ThaliTest[407:336627] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-18T11:31:23.231Z SendDataTCPServer.js: TCP/IP server is bound to port: 52036
,2015-12-18 12:31:23.233 ThaliTest[407:336416] client: found peer: Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:23.233 ThaliTest[407:336416] client: found peer: Apple-Iphone6-1_PT3077.XaIcQQ==
2015-12-18 12:31:23.234 ThaliTest[407:336416] client: found peer: Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18 12:31:23.235 ThaliTest[407:336416] client: found peer: Apple-Iphone5s-1_PT8285.POBncQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6300.vmgLvQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:23.242Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:23.243Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:23.244Z SendDataConnector.js: do connect now
,2015-12-18 12:31:23.245 ThaliTest[407:336627] jxcore: connect Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:23.246 ThaliTest[407:336627] client session: connect
,2015-12-18 12:31:23.247 ThaliTest[407:336627] client session: stateChange:0->1 Apple-Iphone5-1_PT6300.vmgLvQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.XaIcQQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.H3bAHA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8285.POBncQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 12:31:24.368 ThaliTest[407:336416] client: lost peer: Apple-Iphone6-1_PT3077.XaIcQQ==
2015-12-18 12:31:24.369 ThaliTest[407:336416] client session: onPeerLost: Apple-Iphone6-1_PT3077.XaIcQQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT3077.XaIcQQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-18 12:31:24.579 ThaliTest[407:336416] client: lost peer: Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:24.579 ThaliTest[407:336416] client session: onPeerLost: Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:24.580 ThaliTest[407:336416] cli,ent: found peer: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:31:24.580 ThaliTest[407:336416] client: found peer: Apple-Iphone5-1_PT6300.t11aeg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.H3bAHA==","peerName":"(null)","peerAva,ilable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.GXbC4w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifie,r":"Apple-Iphone5-1_PT6300.t11aeg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 12:31:25.576 ThaliTest[407:336416] client: lost peer: Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:25.577 ThaliTest[407:336416] client session: onPeerLost: Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:25.578 ThaliTest[407:336416] client session: onLinkFailure: Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:25.578 ThaliTest[407:3,36416] client session: disconnect
2015-12-18 12:31:25.578 ThaliTest[407:336416] client session: stateChange:1->0 Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:25.579 ThaliTest[407:336416] client session: fireConnectCallback: Apple-Iphone5-1_PT6300.vmg,LvQ==
2015-12-18 12:31:25.580 ThaliTest[407:336416] jxcore: connect: fail: Peer disconnected
2015-12-18T11:31:25.582Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-18T11:31:25.582Z SendDataConnector.js: CLIENT Can not Con,nect: Peer disconnected
2015-12-18T11:31:25.583Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6300.vmgLvQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-18T11:31:30.586Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:30.587Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:30.882 ThaliTest[407:336416] client: lost peer: Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:30.883 ThaliTest[407:336416] client session: onPeerLost: Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:30.884 ThaliTest[407:336416] cli,ent: found peer: Apple-Iphone5s-1_PT8285.14R9MQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8285.POBncQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8285.14R9MQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 12:31:35.597 ThaliTest[407:336627] jxcore: disconnect
2015-12-18 12:31:35.597 ThaliTest[407:336627] jxcore: disconnect: fail
2015-12-18T11:31:35.598Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.vmgLvQ==,
2015-12-18T11:31:35.598Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6300.vmgLvQ== with availability status: true
2015-12-18T11:31:35.599Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:35.599Z SendDataConnector.js: do connect now
,2015-12-18 12:31:35.601 ThaliTest[407:336627] jxcore: connect Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:35.601 ThaliTest[407:336627] client: connect: unreachable Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:35.602 ThaliTest[407:336627] jxcore:, connect: fail: Peer unreachable
2015-12-18T11:31:35.602Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:31:35.603Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:31:35.603Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:31:40.614Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:40.614Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:40.852 ThaliTest[407:336416] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 12:31:45.626 ThaliTest[407:336627] jxcore: disconnect
2015-12-18 12:31:45.627 ThaliTest[407:336627] jxcore: disconnect: fail
2015-12-18T11:31:45.627Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.vmgLvQ==,
2015-12-18T11:31:45.628Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6300.vmgLvQ== with availability status: true
2015-12-18T11:31:45.628Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:45.628Z SendDataConnector.js: do connect now
,2015-12-18 12:31:45.630 ThaliTest[407:336627] jxcore: connect Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:45.631 ThaliTest[407:336627] client: connect: unreachable Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:45.631 ThaliTest[407:336627] jxcore:, connect: fail: Peer unreachable
2015-12-18T11:31:45.631Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:31:45.632Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:31:45.632Z SendDataConne,ctor.js: tryAgain afer: 5000 ms.
,2015-12-18 12:31:50.322 ThaliTest[407:336416] client: lost peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-18 12:31:50.323 ThaliTest[407:336416] client session: onPeerLost: Apple-Iphone5-1_PT6883.KeEEhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-18T11:31:50.634Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:50.634Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:53.224 ThaliTest[407:336416] multipeer session: restart
,2015-12-18 12:31:55.639 ThaliTest[407:336627] jxcore: disconnect
2015-12-18 12:31:55.640 ThaliTest[407:336627] jxcore: disconnect: fail
2015-12-18T11:31:55.640Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.vmgLvQ==,
2015-12-18T11:31:55.641Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT6300.vmgLvQ== with availability status: true
2015-12-18T11:31:55.641Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18T11:31:55.641Z SendDataConnector.js: do connect now
,2015-12-18 12:31:55.643 ThaliTest[407:336627] jxcore: connect Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:55.643 ThaliTest[407:336627] client: connect: unreachable Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:55.644 ThaliTest[407:336627] jxcore: connect: fail: Peer unreachable
2015-12-18T11:31:55.644Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-18T11:31:55.645Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:31:55.645Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:32:00.651Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:32:00.651Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:32:05.661 ThaliTest[407:336627] jxcore: disconnect
2015-12-18 12:32:05.662 ThaliTest[407:336627] jxcore: disconnect: fail
2015-12-18T11:32:05.663Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.vmgLvQ==,
2015-12-18T11:32:05.663Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT6300.vmgLvQ== with availability status: true
2015-12-18T11:32:05.664Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
2015-,12-18T11:32:05.664Z SendDataConnector.js: do connect now
,2015-12-18 12:32:05.665 ThaliTest[407:336627] jxcore: connect Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:32:05.666 ThaliTest[407:336627] client: connect: unreachable Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:32:05.667 ThaliTest[407:336627] jxcore: connect: fail: Peer unreachable
2015-12-18T11:32:05.667Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:32:05.668Z SendDataConnector.js: CLIENT Can not Connect: Pee,r unreachable
oneRoundDownNow
2015-12-18T11:32:05.670Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 12:32:05.671 ThaliTest[407:336627] jxcore: disconnect
2015-12-18 12:32:05.672 ThaliTest[407:336627] jxcore: disconnect: fail
,2015-12-18T11:32:05.674Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:05.680Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:05.680Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:05.681Z SendDataConnector.js: do connect now
,2015-12-18 12:32:05.683 ThaliTest[407:336627] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:05.684 ThaliTest[407:336627] client session: connect
2015-12-18 12:32:05.684 ThaliTest[407:336627] client session: stateChange:0->1 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:05.698 ThaliTest[407:336416] client: lost peer: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:05.698 ThaliTest[407:336416] client session: onPeerLost: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:05.698 ThaliTest[407:336416] client session: onLinkFailure: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:05.699 ThaliTest[407:336416] client session: disconnect
2015-12-18 12:32:05.699 ThaliTest[407:336416] client session: stateChange:1->0 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:05.755 ThaliTest[407:336416] client session: fireConnectCallback: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:05.755 ThaliTest[407:336416] jxcore: connect: fail: Peer disconnected
2015-12-18T11:32:05.756Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-18T11:32:05.756Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-18T11:32:05.757Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.GXbC4w==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 12:32:05.943 ThaliTest[407:336416] multipeer session: reset timer
2015-12-18 12:32:05.943 ThaliTest[407:336416] multipeer session: stop timer
2015-12-18 12:32:05.944 ThaliTest[407:336416] multipeer session: start timer: 0x18a773b0
2015-12-18 ,12:32:05.944 ThaliTest[407:336416] server session: connect
2015-12-18 12:32:05.944 ThaliTest[407:336416] server session: stateChange:0->1 Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:05.953 ThaliTest[407:336416] server: accepting invitation Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:08.109 ThaliTest[407:336416] multipeer session: reset timer
2015-12-18 12:32:08.110 ThaliTest[407:336416] multipeer session: stop timer
2015-12-18 12:32:08.110 ThaliTest[407:336416] multipeer session: start timer: 0x18a773b0
2015-12-18 ,12:32:08.110 ThaliTest[407:336416] server session: connect
2015-12-18 12:32:08.111 ThaliTest[407:336416] server session: stateChange:0->1 Apple-Iphone5-1_PT6300
,2015-12-18 12:32:08.122 ThaliTest[407:336416] server: accepting invitation Apple-Iphone5-1_PT6300
,2015-12-18 12:32:08.769 ThaliTest[407:337318] server session: connected
2015-12-18 12:32:08.770 ThaliTest[407:337318] server session: stateChange:1->2 Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:08.786 ThaliTest[407:336416] server relay: connected (to port: 52036)
2015-12-18T11:32:08.787Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T11:32:09.071Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-18T11:32:09.085Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-18T11:32:09.101Z SendDataTCPServer.js: TCP/IP server has received 50228 bytes of data
,2015-12-18T11:32:09.118Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-18T11:32:09.135Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 12:32:09.165 ThaliTest[407:337317] server session: not connected Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:10.669 ThaliTest[407:337317] server session: connected
2015-12-18 12:32:10.669 ThaliTest[407:337317] server session: stateChange:1->2 Apple-Iphone5-1_PT6300
,2015-12-18 12:32:10.677 ThaliTest[407:336416] server relay: connected (to port: 52036)
,2015-12-18T11:32:10.684Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T11:32:10.761Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:10.761Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:11.231Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-18T11:32:11.249Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-18T11:32:11.266Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-18T11:32:11.282Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-18T11:32:11.298Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-18T11:32:11.313Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-18T11:32:11.328Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 12:32:11.400 ThaliTest[407:337317] server session: not connected Apple-Iphone5-1_PT6300
,2015-12-18 12:32:15.506 ThaliTest[407:336416] multipeer session: reset timer
2015-12-18 12:32:15.506 ThaliTest[407:336416] multipeer session: stop timer
2015-12-18 12:32:15.507 ThaliTest[407:336416] multipeer session: start timer: 0x18a773b0
2015-12-18 ,12:32:15.507 ThaliTest[407:336416] server session: connect
,2015-12-18 12:32:15.507 ThaliTest[407:336416] server session: stateChange:0->1 Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:15.518 ThaliTest[407:336416] server: accepting invitation Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:15.764 ThaliTest[407:336627] jxcore: disconnect
2015-12-18 12:32:15.764 ThaliTest[407:336627] jxcore: disconnect: fail
2015-12-18T11:32:15.765Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==,
2015-12-18T11:32:15.765Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT6115.GXbC4w== with availability status: true
2015-12-18T11:32:15.765Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18T11:32:15.765Z SendDataConnector.js: do connect now
,2015-12-18 12:32:15.766 ThaliTest[407:336627] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:15.767 ThaliTest[407:336627] client: connect: unreachable Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:15.767 ThaliTest[407:336627] jxcore: connect: fail: Peer unreachable
,2015-12-18T11:32:15.769Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:32:15.769Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:32:15.769Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18 12:32:18.274 ThaliTest[407:337317] server session: connected
,2015-12-18 12:32:18.274 ThaliTest[407:337317] server session: stateChange:1->2 Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:18.313 ThaliTest[407:336416] server relay: connected (to port: 52036)
,2015-12-18T11:32:18.320Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T11:32:18.580Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-18T11:32:18.596Z SendDataTCPServer.js: TCP/IP server has received 30092 bytes of data
,2015-12-18T11:32:18.613Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-18T11:32:18.627Z SendDataTCPServer.js: TCP/IP server has received 50086 bytes of data
,2015-12-18T11:32:18.643Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-18T11:32:18.657Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-18T11:32:18.672Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-18T11:32:18.711Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-18T11:32:18.724Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-18T11:32:18.740Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 12:32:18.771 ThaliTest[407:337318] server session: not connected Apple-Iphone5s-1_PT8285
,2015-12-18T11:32:20.776Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:20.777Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:25.782 ThaliTest[407:336627] jxcore: disconnect
2015-12-18 12:32:25.782 ThaliTest[407:336627] jxcore: disconnect: fail
2015-12-18T11:32:25.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==,
2015-12-18T11:32:25.783Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT6115.GXbC4w== with availability status: true
2015-12-18T11:32:25.784Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18T11:32:25.784Z SendDataConnector.js: do connect now
,2015-12-18 12:32:25.785 ThaliTest[407:336627] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:25.786 ThaliTest[407:336627] client: connect: unreachable Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:25.786 ThaliTest[407:336627] jxcor,e: connect: fail: Peer unreachable
2015-12-18T11:32:25.787Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:32:25.788Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:32:25.788Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:32:30.791Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:30.792Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:35.799 ThaliTest[407:336627] jxcore: disconnect
2015-12-18 12:32:35.800 ThaliTest[407:336627] jxcore: disconnect: fail
2015-12-18T11:32:35.800Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==,
2015-12-18T11:32:35.801Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT6115.GXbC4w== with availability status: true
2015-12-18T11:32:35.801Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18T11:32:35.801Z SendDataConnector.js: do connect now
,2015-12-18 12:32:35.803 ThaliTest[407:336627] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:35.804 ThaliTest[407:336627] client: connect: unreachable Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:35.806 ThaliTest[407:336627] jxcore: connect: fail: Peer unreachable
,2015-12-18T11:32:35.808Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:32:35.808Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:32:35.808Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:32:40.819Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:40.819Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:45.508 ThaliTest[407:336416] multipeer session: restart
,2015-12-18 12:32:45.546 ThaliTest[407:336416] client: found peer: Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18 12:32:45.549 ThaliTest[407:336416] client: found peer: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:45.550 ThaliTest[407:336416] client: fo,und peer: Apple-Iphone5-1_PT6300.t11aeg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.GXbC4w==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 12:32:45.825 ThaliTest[407:336627] jxcore: disconnect
2015-12-18 12:32:45.826 ThaliTest[407:336627] jxcore: disconnect: fail
2015-12-18T11:32:45.826Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==,
2015-12-18T11:32:45.826Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT6115.GXbC4w== with availability status: true
2015-12-18T11:32:45.827Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:45.827Z SendDataConnector.js: do connect now
,2015-12-18 12:32:45.828 ThaliTest[407:336627] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:45.829 ThaliTest[407:336627] client session: connect
,2015-12-18 12:32:45.830 ThaliTest[407:336627] client session: stateChange:0->1 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:49.287 ThaliTest[407:337429] client session: connected
2015-12-18 12:32:49.287 ThaliTest[407:337429] client session: stateChange:1->2 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:49.296 ThaliTest[407:337429] client session: fireConnectCallback: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:49.296 ThaliTest[407:337429] jxcore: connect: success
,2015-12-18T11:32:49.298Z SendDataConnector.js: CLIENT connected to 52045, error: null
,2015-12-18T11:32:49.298Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 12:32:49.301 ThaliTest[407:336416] client: relay established
,2015-12-18 12:32:49.301 ThaliTest[407:336416] client: new accepted socket: 0x18cf9640
,2015-12-18T11:32:49.319Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:49.612Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T11:32:49.635Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T11:32:49.646Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T11:32:49.646Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-18T11:32:49.647Z SendDataConnector.js: CLIENT Stop now
2015-12-18T11:32:49.647Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:49.648 ThaliTest[407:336627] jxcore: disconnect
,2015-12-18 12:32:49.648 ThaliTest[407:336627] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:49.649 ThaliTest[407:336627] client session: disconnect
,2015-12-18 12:32:49.649 ThaliTest[407:336627] client session: stateChange:2->0 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:49.712 ThaliTest[407:336627] jxcore: disconnect: success
,2015-12-18T11:32:49.713Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==
---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18T11:32:49.714Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18T11:32:49.714Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18T11:32:49.714Z SendDataConnector.js: do connect now
,2015-12-18 12:32:49.714 ThaliTest[407:336627] jxcore: connect Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:49.715 ThaliTest[407:336627] client session: connect
,2015-12-18 12:32:49.715 ThaliTest[407:336627] client session: stateChange:0->1 Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:52.539 ThaliTest[407:337446] client session: connected
2015-12-18 12:32:52.539 ThaliTest[407:337446] client session: stateChange:1->2 Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:32:52.543 ThaliTest[407:337446] client session: fireConnectCallback: Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:52.544 ThaliTest[407:337446] jxcore: connect: success
2015-12-18T11:32:52.547Z SendDataConnector.js: CLIENT connected to 52048, error: null
2015-12-18T11:32:52.548Z SendDataConnector.js: CLIENT starting client 
2015-12-18 12:32:52.552 ThaliTest[407:336416] client: relay established
2015-12-18 12:32:52.552 ThaliTest[407:336416] client: new accepted socket: 0x18a55750
,2015-12-18T11:32:52.565Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:52.831Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-18T11:32:52.842Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T11:32:52.853Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T11:32:52.877Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T11:32:52.877Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T11:32:52.878Z SendDataConnector.js: CLIENT Stop now
2015-12-18T11:32:52.878Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:52.878 ThaliTest[407:336627] jxcore: disconnect
,2015-12-18 12:32:52.879 ThaliTest[407:336627] client session: disconnectFromPeer: Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:52.880 ThaliTest[407:336627] client session: disconnect
,2015-12-18 12:32:52.880 ThaliTest[407:336627] client session: stateChange:2->0 Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:52.945 ThaliTest[407:336627] jxcore: disconnect: success
,2015-12-18T11:32:52.946Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.t11aeg==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18T11:32:52.947Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18T11:32:52.947Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18T11:32:52.947Z SendDataConnector.js: do connect now
,2015-12-18 12:32:52.948 ThaliTest[407:336627] jxcore: connect Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:52.948 ThaliTest[407:336627] client session: connect
,2015-12-18 12:32:52.949 ThaliTest[407:336627] client session: stateChange:0->1 Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:55.816 ThaliTest[407:337429] client session: connected
2015-12-18 12:32:55.816 ThaliTest[407:337429] client session: stateChange:1->2 Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:55.839 ThaliTest[407:337446] client session: fireConnectCallback: Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18 12:32:55.839 ThaliTest[407:337446] jxcore: connect: success
2015-12-18T11:32:55.840Z SendDataConnector.js: CLIENT connected to ,52051, error: null
2015-12-18T11:32:55.841Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 12:32:55.845 ThaliTest[407:336416] client: relay established
,2015-12-18 12:32:55.845 ThaliTest[407:336416] client: new accepted socket: 0x18a56b20
,2015-12-18T11:32:55.858Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:56.146Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T11:32:56.197Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T11:32:56.235Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T11:32:56.235Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-18T11:32:56.236Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T11:32:56.236Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:56.237 ThaliTest[407:336627] jxcore: disconnect
2015-12-18 12:32:56.237 ThaliTest[407:336627] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:56.237 ThaliTest[407:336627] client session: disconnect
,2015-12-18 12:32:56.237 ThaliTest[407:336627] client session: stateChange:2->0 Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:56.302 ThaliTest[407:336627] jxcore: disconnect: success
,2015-12-18T11:32:56.303Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8285.14R9MQ==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-18T11:32:56.306Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T11:32:56.306Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-18 12:32:57.151 ThaliTest[407:336627] jxcore: stopBroadcasting
2015-12-18 12:32:57.153 ThaliTest[407:336627] THEMultipeerSession stopping peer
2015-12-18 12:32:57.153 ThaliTest[407:336627] multipeer session: stop timer
2015-12-18 12:32:57.154 Th,aliTest[407:336627] server session: disconnect
2015-12-18 12:32:57.154 ThaliTest[407:336627] server session: stateChange:2->0 Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:57.223 ThaliTest[407:336627] server session: disconnect
2015-12-18 12:32:57.224 ThaliTest[407:336627] server session: stateChange:2->0 Apple-Iphone5-1_PT6300
,2015-12-18 12:32:57.227 ThaliTest[407:336627] server session: disconnect
2015-12-18 12:32:57.228 ThaliTest[407:336627] server session: stateChange:2->0 Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:57.292 ThaliTest[407:336627] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-18T11:32:57.308Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:57.310Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:57.312Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:57.313Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
